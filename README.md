# 📊 Student Performance Prediction using Multiple Linear Regression on AWS SageMaker

## 📌 Project Overview

This project demonstrates how to build a Machine Learning model using **Multiple Linear Regression** on **AWS SageMaker Studio**.

The model predicts **Physics marks** using **Maths** and **English** marks from a student dataset.

The project also covers storing datasets and trained models in **Amazon S3**.

---

# 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- AWS SageMaker Studio
- Amazon S3
- Boto3

---

# 📂 Project Structure

```
Student-Performance-Regression/

│── Student_Performance_Regression.ipynb
│── student-data.json
│── README.md
│── requirements.txt
│── screenshots/
```

---

# 📁 Dataset

Dataset contains:

- Name
- Gender
- Physics Marks
- Maths Marks
- English Marks

Example

| Name | Gender | Physics | Maths | English |
|------|---------|---------|-------|----------|
| Arun | Male | 88 | 87 | 78 |
| Rajesh | Male | 96 | 100 | 95 |

---

# 🧠 Machine Learning Model

Algorithm Used

**Multiple Linear Regression**

Independent Variables

- Maths
- English

Dependent Variable

- Physics

---

# ⚙️ Workflow

### Step 1

Create Amazon S3 Bucket

### Step 2

Upload Dataset into S3

### Step 3

Create AWS SageMaker Studio

### Step 4

Launch JupyterLab

### Step 5

Load Dataset from Amazon S3

### Step 6

Train Multiple Linear Regression Model

### Step 7

Predict Physics Marks

### Step 8

Save Model using Joblib

```
model.joblib
```

### Step 9

Compress Model

```
model.tar.gz
```

### Step 10

Upload Trained Model to Amazon S3

---

# 📈 Model Evaluation

Evaluation Metrics

- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

# 📷 Screenshots

The project includes screenshots of

- AWS SageMaker Studio
- JupyterLab
- Dataset Loading
- Model Training
- Prediction Output
- Amazon S3 Bucket
- Saved Model (.joblib)
- Compressed Model (.tar.gz)

---

# 📦 Python Libraries

```
pandas
numpy
scikit-learn
boto3
joblib
```

Install

```bash
pip install -r requirements.txt
```

---

# ▶️ Run

```bash
jupyter notebook
```

Run all notebook cells.

---

# 📚 Learning Outcomes

- Amazon S3
- AWS SageMaker Studio
- Jupyter Notebook
- Boto3
- Multiple Linear Regression
- Model Serialization
- Model Storage in Amazon S3

---

# 👨‍💻 Author

**Vinay Sharma**

B.Tech CSE (AI)

Arya College of Engineering & IT

Jaipur, Rajasthan

GitHub:
https://github.com/009vinaysharma

LinkedIn:
(Add Your LinkedIn URL)
