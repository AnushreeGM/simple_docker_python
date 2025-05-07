# 🐍 **Python App with Jenkins Pipeline & Docker**

This project is a simple Python web application designed to demonstrate **CI/CD automation** using **Jenkins** and **Docker**.

---

## 📦 **Prerequisites**

Make sure the following are installed:

- ✅ **Python 3.x**
- 🐳 **Docker**
- 🧰 **Jenkins**
- 🔧 **Git**

---

## 🚀 **How to Run the Project**

### 🔧 **1. Clone the Repository**

```bash
git clone https://github.com/AnushreeGM/simple_docker_python.git
cd simple_docker_python
```

---

### ▶️ **2. Run the App Locally (Without Docker)**

**Install dependencies:**

```bash
pip install -r requirements.txt
```

**Run the app:**

```bash
python app.py
```

Open your browser and visit:

```
http://localhost:5000
```

---

### 🐳 **3. Run the App Using Docker**

**Build the Docker image:**

```bash
docker build -t python-sample-app .
```

**Run the Docker container:**

```bash
docker run -p 5000:5000 python-sample-app
```

Open your browser and visit:

```
http://localhost:5000
```

---

### ⚙️ **4. Run the Jenkins Pipeline**

1. Open Jenkins in your browser.
2. Create a new **Pipeline** job.
3. Under **Pipeline > Definition**, select:
   - `Pipeline script from SCM`
   - Set **SCM** to **Git**
   - Paste your repository URL
4. Ensure the repository contains a valid `Jenkinsfile` in the root directory.
5. Click **Save**, then **Build Now**.

---

## 📄 **Project Structure**

```
.
├── app.py           # Python Flask application
├── requirements.txt # Python dependencies
├── Dockerfile       # Defines Docker image build process
└── Jenkinsfile      # Defines Jenkins pipeline stages
```

---

## 📌 **License**

This project is licensed under the **MIT License**.

---

## 🙋‍♀️ **Author**

**Anushree**  
🔗 GitHub: [https://github.com/AnushreeGM](https://github.com/AnushreeGM)  
🔗 LinkedIn: [https://in.linkedin.com/in/anushreegm](https://in.linkedin.com/in/anushreegm)
