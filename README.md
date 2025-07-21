# 🎓 Student Performance Predictor - End-to-End ML Project

This is a complete **end-to-end Machine Learning project** that predicts student performance based on various academic, demographic, and behavioral features. The project follows a modular and production-ready structure using industry best practices like configuration files, pipelines, CI/CD automation, and containerization.

---

## 🚀 Project Features

- 📊 **EDA & Feature Engineering**
- 🧠 **Regression Model Training**
- ⚙️ **Modular Pipeline with YAML Configs**
- 🌐 **Flask Web App for Predictions**
- 🐳 **Dockerized for Deployment**
- 🔁 **CI/CD using GitHub Actions**

---

## 📁 Project Structure


---

## 🧠 Model Objective

Predict a **student’s final grade or score** based on inputs like:

- Parental education level  
- Study time  
- Failures  
- Internet access  
- Travel time  
- Absences  
- Past grades  

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy, Scikit-learn  
- Flask  
- YAML  
- Docker  
- Git & GitHub Actions  
- HTML/CSS (for UI)  

---

## ⚙️ How to Run Locally

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/student-performance-mlproject.git
cd student-performance-mlproject

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run Flask app
python app.py

# Build Docker image
docker build -t student-performance-app .

# Run Docker container
docker run -p 5000:5000 student-performance-app

