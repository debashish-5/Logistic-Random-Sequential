

<!-- ================================================= -->
<!--              PROJECT BANNER                      -->
<!-- ================================================= -->

<div align="center" style="background:linear-gradient(90deg,#0f2027,#203a43,#2c5364); padding:40px; border-radius:10px; color:white;">

<h1>Logistic-Random-Sequential</h1>

<p>
A Machine Learning project implementing Logistic Regression using
Sequential and Random sampling strategies on a real-world banking dataset.
</p>

</div>



## Project Overview

<div style="border-left:6px solid #3498db; background:#ecf6ff; padding:15px; border-radius:6px;">

This repository demonstrates the application of Logistic Regression
for binary classification using different data sampling techniques.

The project compares Random Sampling and Sequential Sampling
to evaluate model stability and performance.

</div>



## Repository Structure

<div style="border-left:6px solid #2ecc71; background:#edfff5; padding:15px; border-radius:6px;">



Logistic-Random-Sequential
│
├── .ipynb_checkpoints/
├── AIML task 9.pdf
├── Logistic-Random-Sequential.ipynb
├── bank-full.csv
├── logistic.pkl
└── README.md



</div>


## Technologies Used

<div style="border-left:6px solid #9b59b6; background:#f7efff; padding:15px; border-radius:6px;">

- Python 3
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Pickle

</div>



## Dataset Information

<div style="border-left:6px solid #f39c12; background:#fff7e6; padding:15px; border-radius:6px;">

Dataset: Bank Marketing Dataset  
File: bank-full.csv  

Objective: Predict whether a client will subscribe to a term deposit.

Features include:
- Age
- Job
- Education
- Balance
- Contact Type
- Campaign Information

Target Variable:
- yes → Subscription
- no → No Subscription

</div>



## Installation and Setup

<div style="border-left:6px solid #1abc9c; background:#eafff9; padding:15px; border-radius:6px;">

Step 1: Clone Repository

```bash
git clone https://github.com/debashish-5/Logistic-Random-Sequential.git
cd Logistic-Random-Sequential
````

Step 2: Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate
```

Step 3: Install Dependencies

```bash
pip install numpy pandas scikit-learn matplotlib jupyter
```

</div>


## How to Run

<div style="border-left:6px solid #2980b9; background:#eef6ff; padding:15px; border-radius:6px;">

1. Start Jupyter Notebook

```bash
jupyter notebook
```

2. Open:

```
Logistic-Random-Sequential.ipynb
```

3. Run all cells in order

4. The notebook performs:

   * Data loading
   * Preprocessing
   * Model training
   * Evaluation
   * Model saving

</div>



## Model Workflow

<div style="border-left:6px solid #e74c3c; background:#fff0f0; padding:15px; border-radius:6px;">

Implementation steps:

* Data Cleaning
* Encoding
* Scaling
* Train-Test Split
* Logistic Regression Training
* Prediction
* Performance Evaluation
* Model Serialization

Library Used:

```
sklearn.linear_model.LogisticRegression
```

</div>

---

## Model Performance

<div style="border-left:6px solid #16a085; background:#e9fffa; padding:15px; border-radius:6px;">

Accuracy Comparison

| Sampling Method     | Accuracy |
| ------------------- | -------- |
| Random Sampling     | 89.52%   |
| Sequential Sampling | 89.74%   |

Performance Analysis:

* Both methods show strong results
* Sequential sampling slightly outperforms random
* Low variance indicates stability
* Model generalizes well

Conclusion:

Logistic Regression delivers consistent performance
across sampling strategies.

</div>


## Model Storage

<div style="border-left:6px solid #8e44ad; background:#f5ecff; padding:15px; border-radius:6px;">

Saved Model File:

```
logistic.pkl
```

Benefits:

* Reusability
* Faster inference
* Deployment readiness
* No retraining required

</div>

---

## Deployment Readiness

<div style="border-left:6px solid #27ae60; background:#ecfff2; padding:15px; border-radius:6px;">

This project can be deployed using:

* Flask
* FastAPI
* Streamlit
* Cloud Platforms

Recommended Enhancements:

* REST API layer
* CI/CD pipeline
* Docker container
* Monitoring system

</div>



## Future Improvements

<div style="border-left:6px solid #d35400; background:#fff3e6; padding:15px; border-radius:6px;">

Planned Enhancements:

* Hyperparameter tuning
* Cross-validation
* Feature engineering
* Explainability tools
* Automated reports

</div>



## Contribution Guidelines

<div style="border-left:6px solid #34495e; background:#f0f4f8; padding:15px; border-radius:6px;">

1. Fork the repository
2. Create a branch
3. Commit changes
4. Push updates
5. Submit Pull Request

Maintain clean code and documentation.

</div>


## License

<div style="border-left:6px solid #7f8c8d; background:#f7f9fa; padding:15px; border-radius:6px;">

No license file is currently included.

Add an open-source license if distribution is planned.

</div>



## Author

<div style="border-left:6px solid #2c3e50; background:#ecf0f1; padding:15px; border-radius:6px;">

Maintained by:

Debashish Parida
GitHub: [https://github.com/debashish-5](https://github.com/debashish-5)

Use GitHub Issues for support and collaboration.

</div>



## Project Status

<div style="border-left:6px solid #f1c40f; background:#fffde7; padding:15px; border-radius:6px;">

Status: Completed
Version: 1.0
Ready for Academic and Portfolio Use

</div>




