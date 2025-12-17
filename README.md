# Student Exam Performance Indicator

## 📌 Project Overview

This project is an **End-to-End Machine Learning application** developed using **Python**. It demonstrates the complete workflow of a data science project — from data analysis and model training to deployment using a web application.

The project is suitable for **students and beginners in Data Science / Machine Learning** and is designed to showcase practical implementation skills during interviews or academic evaluations.

---

## 🛠️ Technologies Used

### 🔹 Programming Language

* **Python 3**

### 🔹 Data Science & Machine Learning

* **Pandas** – Data manipulation
* **NumPy** – Numerical computations
* **Scikit-learn** – ML utilities and preprocessing
* **CatBoost** – Machine learning model (for classification/regression)

### 🔹 Development & Analysis

* **Jupyter Notebook (.ipynb)** – Data analysis, visualization, and model training

### 🔹 Web Framework

* **Flask** – To deploy the trained ML model as a web application

### 🔹 Frontend

* **HTML** – User interface (via Flask templates)

---

## 📂 Project Structure

```
project/
│
├── artifacts/            # Saved models, preprocessors
├── catboost_info/        # CatBoost training metadata
├── notebook/             # Jupyter notebooks (EDA & model training)
├── src/                  # Source code (pipeline, utils, components)
├── templates/            # HTML files for Flask UI
├── app.py                # Flask application entry point
├── requirements.txt      # Project dependencies
├── setup.py              # Project setup and packaging
└── README.md             # Project documentation
```

---

## ⚙️ Project Workflow

1. **Data Collection**

   * Dataset loaded and explored using Jupyter Notebook

2. **Data Preprocessing**

   * Handling missing values
   * Feature engineering
   * Data transformation

3. **Model Training**

   * ML model trained using **CatBoost**
   * Model evaluation and tuning

4. **Model Saving**

   * Trained model stored in the `artifacts/` directory

5. **Model Deployment**

   * Flask app (`app.py`) loads the trained model
   * User inputs data through a web form
   * Model predicts output and displays results

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/jdevaiya/project.git
cd project
```

### 2️⃣ Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate # Linux/Mac
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Flask Application

```bash
python app.py
```

### 5️⃣ Open in Browser

```
http://127.0.0.1:5000/
```

---

## 🎯 Key Highlights

* Complete **end-to-end ML pipeline**
* Clean project structure
* Model deployment using Flask
* Interview‑ready data science project

---

## 👤 Author

**Jayendra Devaiya**
📌 Data Science / Python Enthusiast
🔗 GitHub: [https://github.com/jdevaiya](https://github.com/jdevaiya)

---

## 📜 License

This project is for **educational and learning purposes only**.

---

⭐ If you like this project, don’t forget to star the repository!
