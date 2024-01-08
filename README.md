# Multi-Disease Predictor

## Overview
Multi-Disease Predictor is a machine learning prediction project developed using Python libraries such as NumPy, Pandas, Pickle, and Streamlit. The project utilizes two prediction models, namely Support Vector Machine (SVM) and Logistic Regression, to predict multiple diseases based on input data.

## Getting Started
To run the Multi-Disease Predictor on your local machine, follow these steps:

1. **Download Files:**
   Download the following files from the [GitHub repository](https://github.com/SameerShekhar2003/multi-disease-predictor):
   - `app.py`
   - Three model files with the extension `.sav`

2. **Update Model Paths:**
   Open the `app.py` file and update the paths of the three model files. Locate the following lines in the `app.py` file:
   ```python
   diabetes_model = pickle.load(open('path/to/your/diabetes_model.sav', 'rb'))
   heart_disease_model = pickle.load(open('path/to/your/heart_disease_model.sav', 'rb'))
   parkinsons_model = pickle.load(open('path/to/your/parkinsons_model.sav', 'rb'))
   ```
   Replace `'path/to/your/diabetes_model.sav'`, `'path/to/your/heart_disease_model.sav'`, and `'path/to/your/parkinsons_model.sav'` with the actual paths to the downloaded model files on your machine.

3. **Run the Application:**
   Open a terminal and navigate to the directory where `app.py` is located. Run the following command:
   ```bash
   streamlit run app.py
   ```
   This will launch the Streamlit web application.

4. **Explore and Predict:**
   Once the application is running, open your web browser and navigate to the provided address (usually http://localhost:8501). You should be able to interact with the Multi-Disease Predictor, input data, and receive predictions based on the selected models.

## Models Used
- **Support Vector Machine (SVM):** A powerful classification algorithm that aims to find the hyperplane that best separates different classes in the input data.
- **Logistic Regression:** A regression analysis algorithm used for predicting the probability of a binary outcome.

## Technologies Used
- **NumPy:** A library for numerical operations in Python.
- **Pandas:** A data manipulation and analysis library.
- **Pickle:** A module for serializing and deserializing Python objects.
- **Streamlit:** An open-source Python library for creating web applications with minimal effort.



Thank you for exploring the Multi-Disease Predictor! Happy predicting!
