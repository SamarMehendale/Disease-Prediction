# CarePulse – Intelligent Health Screening System

## Project Overview

CarePulse is a machine learning-based health screening application developed as an academic project for the early screening of diabetes and heart disease.

The application provides separate screening modules for diabetes and heart disease. Users can enter relevant health-related parameters and receive a model-generated prediction.

**Note:** CarePulse is an educational project and is not a substitute for professional medical advice, diagnosis, or treatment.

## Project Objectives

- Develop a machine learning-based health screening application.
- Build separate prediction modules for diabetes and heart disease.
- Apply data preprocessing techniques to prepare datasets.
- Train and evaluate machine learning models.
- Integrate trained models into a Streamlit web application.
- Present prediction results through a user-friendly interface.

## Technologies Used

- **Programming Language:** Python
- **Frontend / Application Framework:** Streamlit
- **Data Processing:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Model Storage:** Pickle
- **Development Environment:** Visual Studio Code

## Project Structure

```text
Disease Prediction/
│
├── Dataset/
│   ├── diabetes.csv
│   └── heart.csv
│
├── models/
│   ├── diabetes_model.pkl
│   └── heart_model.pkl
│
├── src/
│   ├── diabetes.py
│   ├── heart_disease.py
│   ├── preprocessing.py
│   └── evaluation.py
│
├── app.py
├── requirements.txt
└── README.md
```

## Main Modules

### 1. Diabetes Screening
Uses the diabetes dataset and a trained machine learning model to generate a diabetes screening prediction based on user-provided input.

### 2. Heart Disease Screening
Uses the heart disease dataset and a trained machine learning model to generate a heart disease screening prediction.

### 3. Data Preprocessing
Handles the preparation of datasets before model training and evaluation.

### 4. Model Evaluation
Provides functionality for evaluating the performance of the machine learning models.

### 5. Streamlit Application
Provides the interactive web interface through which users can access the screening modules.

## Installation and Execution

### Step 1: Clone the Repository

```bash
git clone https://github.com/SamarMehendale/Disease-Prediction.git
```

### Step 2: Open the Project Folder

```bash
cd Disease-Prediction
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the Application

```bash
python -m streamlit run app.py
```

### Step 5: Open the Application

Streamlit will provide a local URL, usually:

```text
http://localhost:8501
```

Open this URL in your browser.

## Datasets

The project contains two datasets:

- `diabetes.csv` – Dataset used for diabetes screening.
- `heart.csv` – Dataset used for heart disease screening.

## Machine Learning Models

The trained model files are stored in the `models/` directory:

- `diabetes_model.pkl`
- `heart_model.pkl`

The application uses these saved models to generate predictions.

## Future Scope

- Improve prediction performance through additional model experimentation.
- Include more health screening modules.
- Enhance the user interface and accessibility.
- Add further visualizations and analytical insights.
- Explore secure deployment for wider accessibility.

## Disclaimer

CarePulse is developed strictly for academic and educational purposes. Its predictions are not medical diagnoses. Users should consult qualified healthcare professionals for medical advice and decisions.

## Author

**BSc Data Science Project**

**Academic Year:** 2026–2027

## Repository

GitHub: https://github.com/SamarMehendale/Disease-Prediction
