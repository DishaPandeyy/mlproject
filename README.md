## End to End Machine Learning Project

# 🎓 Student Performance Prediction 🚀

[![Python](https://img.shields.io)](https://www.python.org)
[![Framework](https://img.shields.io)](https://flask.palletsprojects.com)
[![Cloud](https://img.shields.io)](https://aws.amazon.com)

## 🔗 Live Demo
Check out the live application here:  
👉 [**Student Performance Predictor**](http://StudentPerformance-env.eba-9c5c7hkh.eu-north-1.elasticbeanstalk.com)

---

## 📝 Project Overview
This project predicts a student's math score based on various demographic and academic factors (gender, ethnicity, parental level of education, lunch, and test preparation course). It uses a **Regression** approach to provide accurate score estimates.

## 🛠️ Tech Stack
- **Machine Learning:** Scikit-learn, XGBoost, CatBoost
- **Data Handling:** Pandas, Numpy
- **Web Framework:** Flask
- **Cloud Deployment:** AWS Elastic Beanstalk
- **CI/CD:** AWS CodePipeline & GitHub

## 📂 Project Structure
- `application.py`: The entry point for the Flask web server.
- `src/`: Contains modular code for Data Ingestion, Transformation, and Model Training.
- `artifacts/`: Stores the trained model and preprocessor `.pkl` files.
- `.ebextensions/`: Configuration files for AWS deployment (WSGI settings).
- `requirements.txt`: CPU-optimized library dependencies for cloud efficiency.

## 🚀 How to Run Locally
1. **Clone the repo:**
   ```bash
   git clone https://github.com
   cd mlproject
