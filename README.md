# Diabetes Prediction Web App 🩺📊

## Overview 🌐
This Django web application predicts the likelihood of diabetes based on diagnostic measurements. The project explores the intricacies of diabetic patient data to identify trends and patterns that can aid in improving healthcare outcomes.

## About the Dataset📈

The dataset is sourced from the National Institute of Diabetes and Digestive and Kidney Diseases. It aims to predict whether a patient has diabetes based on certain diagnostic measurements.The dataset comprises various medical predictor variables, including pregnancies, glucose levels, blood pressure, skin thickness, insulin, BMI, diabetes history, age, and the target variable, outcome. All patients in the dataset are females at least 21 years old of Pima Indian heritage.

## Setup

1. Install [PyCharm Community Edition](https://www.jetbrains.com/pycharm/download/) if not already installed.

2. Open a command prompt and run the following:
   ```
   conda install -c anaconda django
   ```

3. Open PyCharm, create a new project named "Diabetes Prediction," and set the interpreter.

4. In the terminal, run:
   ```
   django-admin startproject DiabetesPrediction
   cd DiabetesPrediction
   python manage.py runserver
   ```

## Project Structure

- **predict.html**: Design for the Prediction page.
- **home.html**: Design for the front page.
- **urls.py**: Defines the paths for the home page, predict page, and result.
- **views.py**: Handles user input, performs prediction, and displays the result.

## Dependencies

- **Pandas**: Data analysis and manipulation library for structured data.
- **NumPy**: Numerical computing library for large, multi-dimensional arrays.
- **Seaborn**: Statistical data visualization library for attractive and informative graphics.
- **Matplotlib**: Comprehensive plotting library for creating various plots.

## Usage

1. Open the project in PyCharm.
2. Ensure dependencies are installed (`pip install pandas numpy seaborn matplotlib`).
3. Run the Django development server (`python manage.py runserver`).
4. Access the project in a web browser.

## How to Use

1. Navigate to the home page.
2. Input the required values for pregnancies, glucose, blood pressure, etc.
3. Click the "Predict" button to see the outcome prediction.
4. The result will be displayed as "Positive" or "Negative."


## Acknowledgments

- Dataset source: National Institute of Diabetes and Digestive and Kidney Diseases.
- Inspired by the goal of improving healthcare outcomes for diabetic patients.

## Future Enhancements 🚀
- Implement user authentication for personalized predictions.
- Enhance the frontend for a more user-friendly experience.

🚀 Happy coding!
