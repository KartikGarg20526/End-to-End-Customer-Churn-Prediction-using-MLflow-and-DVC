# **End-to-End Customer Churn Prediction using MLflow and DVC**  

## 📌 Overview  
This project implements an end-to-end machine learning pipeline for customer churn prediction using MLOps best practices. It leverages **MLflow** for experiment tracking, **DVC** for data versioning, and **CI/CD pipelines** for automated deployment on **Render**.

## 📊 Dataset  
The dataset used for this project is obtained from Kaggle. It contains the following attributes:  

| Feature            | Description                                           |
|--------------------|-------------------------------------------------------|
| **Customer ID**    | Unique identifier for each customer                   |
| **Surname**        | Customer's last name                                   |
| **Credit Score**   | Customer's credit score                               |
| **Geography**      | Country of residence (France, Spain, Germany)         |
| **Gender**         | Customer's gender (Male, Female)                      |
| **Age**            | Customer's age                                         |
| **Tenure**         | Years with the bank                                    |
| **Balance**        | Account balance                                        |
| **NumOfProducts**  | Number of bank products used                          |
| **HasCrCard**      | Has a credit card (1 = Yes, 0 = No)                   |
| **IsActiveMember** | Active member status (1 = Yes, 0 = No)                |
| **EstimatedSalary**| Estimated salary of the customer                      |
| **Exited**         | Whether the customer churned (1 = Yes, 0 = No)        |

## ⚡ Running Locally  

### 1️⃣ Clone the repository  
```sh
git clone https://github.com/KartikGarg20526/End-to-End-Customer-Churn-Prediction-using-MLflow-and-DVC
cd End-to-End-Customer-Churn-Prediction-using-MLflow-and-DVC
```

### 2️⃣ Create a virtual environment  

#### **Windows (cmd)**
```sh
pip install virtualenv
python -m virtualenv venv
```
or  
```sh
python3 -m venv venv
```

#### **macOS/Linux**  
```sh
pip install virtualenv
python -m virtualenv venv
```

### 3️⃣ Activate the virtual environment  

#### **Windows (cmd)**
```sh
venv\scripts\activate
```

#### **macOS/Linux**
```sh
. venv/bin/activate
```
or  
```sh
source venv/bin/activate
```

### 4️⃣ Install Dependencies  
```sh
pip install -r requirements.txt
```

### 5️⃣ Run the Application  
```sh
python app.py
```
Now, open **[http://127.0.0.1:5000/](http://127.0.0.1:5000/)** in your browser.

---

## 🚀 Deployment on Render  
The model is automatically deployed using **GitHub Actions** and **Render API**.  

🔗 **Live App:** [Customer Churn Prediction](https://customer-churn-prediction-cvah.onrender.com)  
