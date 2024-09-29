# Diabetes Prediction App

A web-based application built with Streamlit for predicting diabetes using a dataset from Kaggle. This app allows users to input various health metrics such as Hemoglobin A1c (HbA1c) level and Blood Glucose level to predict the likelihood of diabetes.

## Dataset

The dataset used in this project is available on Kaggle: [Diabetes Prediction Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset). It contains various health metrics and indicators that are used for predicting diabetes.

### Feature Descriptions:

- **HbA1c Level**: Hemoglobin A1c level is a measure of a person's average blood sugar level over the past 2-3 months. Higher levels indicate poor blood sugar control and increased risk of diabetes.
  
- **Blood Glucose Level**: Blood glucose level refers to the amount of glucose in the bloodstream at a given time. High blood glucose levels are a key indicator of diabetes.

## Installation

To run the app locally, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/diabetes-prediction-app.git
    cd diabetes-prediction-app
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Install Streamlit:
    ```bash
    pip install streamlit
    ```

## How to Run the App

1. Open the `app.py` file in the project directory.
2. Open a terminal or command prompt and run the following command:
    ```bash
    streamlit run app.py
    ```

3. Your web browser will automatically open the app. If not, visit the provided local URL (usually `http://localhost:8501`).

## File Structure

```bash
diabetes-prediction-app/
│
├── app.py               # Main file to run the Streamlit app
├── dataset/             # Folder containing the Kaggle dataset (optional, if used locally)
├── README.md            # Project documentation (this file)
```
## Libraries Used
-Streamlit (for building the web application)
-Pandas (for data manipulation)
-Scikit-learn (for model building)

## Notes
Ensure that you have Python installed before running the app.

## Acknowledgments
The dataset is provided by Mustafa Tz on Kaggle.
