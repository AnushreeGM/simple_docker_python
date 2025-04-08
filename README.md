# 🐍 Python App with Jenkins Pipeline & Docker

This project is a simple Python web application designed to demonstrate CI/CD automation using Jenkins and Docker.

---

## 📦 Prerequisites

- Python 3.x
- Docker
- Jenkins
- Git

---

## 🚀 How to Run the Project

### 🔧 1. Clone the Repository

```bash
git clone https://github.com/your-username/python-jenkins-docker-sample.git
cd python-jenk

▶️ 2. Run the App Locally (Without Docker)
Install dependencies:

pip install -r requirements.txt

Run the app:
python app.py

Open your browser and visit:
http://localhost:5000


🐳 3. Run the App Using Docker
Build the Docker image:
docker build -t python-sample-app .

Run the Docker container:
docker run -p 5000:5000 python-sample-app
Visit:
http://localhost:5000

⚙️ 4. Run the Jenkins Pipeline
Open Jenkins in your browser.

Create a new Pipeline job.

Under Pipeline > Definition, select:

"Pipeline script from SCM"

Set SCM to Git

Paste your repository URL

Ensure the repository contains a valid Jenkinsfile in the root.

Save the job and click Build Now.

📄 Project Structure
app.py – Python Flask application

requirements.txt – Python dependencies

Dockerfile – Defines Docker image build process

Jenkinsfile – Defines Jenkins pipeline stages

📌 License
This project is licensed under the MIT License.

🙋‍♂️ Author
Anushree
GitHub: https://github.com/AnushreeGM/
LinkedIn: https://in.linkedin.com/in/anushreegm

