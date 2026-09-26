
# Logistic-Random-Sequential

A Machine Learning project implementing Logistic Regression using **Sequential** and **Random** sampling strategies on a real-world banking dataset.

---

## 📌 Project Overview

This repository demonstrates the application of Logistic Regression for binary classification using different data sampling techniques. The project compares Random Sampling and Sequential Sampling to evaluate model stability and performance.

---

## 📁 Repository Structure

```text
Logistic-Random-Sequential/
│
├── .ipynb_checkpoints/
├── AIML task 9.pdf
├── Logistic-Random-Sequential.ipynb
├── bank-full.csv
├── logistic.pkl
└── README.md

```

---

## 🛠️ Technologies Used

* **Language:** Python 3
* **Data Processing & Math:** NumPy, Pandas
* **Machine Learning:** Scikit-learn
* **Visualization:** Matplotlib
* **Environment:** Jupyter Notebook
* **Serialization:** Pickle

---

## 📊 Dataset Information

* **Dataset:** Bank Marketing Dataset
* **File:** `bank-full.csv`
* **Objective:** Predict whether a client will subscribe to a term deposit.
* **Features Include:**
* Age
* Job
* Education
* Balance
* Contact Type
* Campaign Information


* **Target Variable:**
* `yes` → Subscription
* `no` → No Subscription



---

## 🚀 Installation & Setup

### Step 1: Clone Repository

```bash
git clone [https://github.com/debashish-5/Logistic-Random-Sequential.git](https://github.com/debashish-5/Logistic-Random-Sequential.git)
cd Logistic-Random-Sequential

```

### Step 2: Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

```

### Step 3: Install Dependencies

```bash
pip install numpy pandas scikit-learn matplotlib jupyter

```

---

## ⚙️ How to Run

1. **Start Jupyter Notebook:**
```bash
jupyter notebook

```


2. **Open the Notebook:**
Navigate to and open `Logistic-Random-Sequential.ipynb`.
3. **Execute Cells:**
Run all cells in order. The notebook performs:
* Data loading
* Preprocessing
* Model training
* Evaluation
* Model saving



---

## 🔄 Model Workflow

1. Data Cleaning
2. Categorical Encoding
3. Feature Scaling
4. Train-Test Split
5. Logistic Regression Training (`sklearn.linear_model.LogisticRegression`)
6. Prediction & Performance Evaluation
7. Model Serialization (`logistic.pkl`)

---

## 📈 Model Performance

### Accuracy Comparison

| Sampling Method | Accuracy |
| --- | --- |
| **Random Sampling** | 89.52% |
| **Sequential Sampling** | 89.74% |

### Performance Analysis

* Both sampling strategies produce strong and reliable classification results.
* Sequential sampling shows a slight edge in accuracy over random sampling.
* Low variance across evaluations indicates model stability and good generalization to unseen data.

---

## 💾 Model Storage

* **Saved Model File:** `logistic.pkl`
* **Benefits:**
* Reusability without retraining
* Faster inference
* Deployment readiness



---

## 🚀 Deployment Readiness

This project can easily be wrapped into a web interface or API using:

* **Frameworks:** Streamlit, FastAPI, or Flask
* **Containerization:** Docker
* **Hosting:** Cloud platforms (AWS, Heroku, GCP)

---

## 🔮 Future Improvements

* Hyperparameter tuning for optimization
* Cross-validation for robust evaluation
* Feature engineering to enhance predictive performance
* Integration of model explainability tools (e.g., SHAP, LIME)

---

## 🤝 Contribution Guidelines

1. Fork the repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

---

## 👤 Author

Maintained by **[Debashish Parida](https://github.com/debashish-5?utm_source=gemini)**.

Feel free to open an issue or reach out via [GitHub](https://github.com/debashish-5?utm_source=gemini) for collaboration or feedback!

```

```
