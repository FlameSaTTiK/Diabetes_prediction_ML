# Simple Linear Regression Model for Predicting whether a person is Diabetic or not.

This repository contains a Python implementation of a Support Vector Machine model to predict whether a person is Diabetic or not based on Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction & Age. The model is built using libraries like **Pandas**, **NumPy** and **Scikit-Learn**.

---

## Features

- **Data Handling**: Loads and preprocesses data from `diabetes.csv`.
- **Model Training**: Trains a Support Vector Machine model using Scikit-Learn.

---

## Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.x
- Required Python libraries:
  ```bash
  pip install pandas numpy scikit-learn
  ```

---

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone <repository_url>
   ```

2. **Prepare the Dataset**:
   - Place the `diabetes.csv` file in the root directory of the repository.
     
3. **Run the Script**:
   Execute the Python script to train and test the model:
   ```bash
   python diabetes.py
   ```

---

## Code Overview

1. **Import Libraries**:
   - The script uses **Pandas** for data handling, **NumPy** for numerical computations and **Scikit-Learn** for machine learning tasks.

2. **Data Preparation**:
   - The dataset is split into independent variables (`X`) and dependent variables (`Y`).
   - Training and testing sets are created using an 80-20 split.

3. **Model Training**:
   - The script trains a support vector machine model using the training set.

---

## Contributing

Feel free to contribute to this project by improving the code or adding new features. To contribute:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## Acknowledgments

This project is a demonstration of support vector model using Python. Special thanks to the open-source community for providing the libraries used in this project.
