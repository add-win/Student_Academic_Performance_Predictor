# Student Academic Performance Predictor

A simple machine learning project for predicting whether a student is likely to pass or fail based on academic input such as study hours and attendance.

## Overview

This project uses a trained logistic regression model to estimate student performance from a small set of features. It includes two web app versions:

- Streamlit app for local interactive prediction
- Gradio app for browser-based prediction

## Project Files

- `app.py` - Streamlit-based prediction interface
- `app_gradio.py` - Gradio-based prediction interface
- `requirements.txt` - Python dependencies
- `log_reg_hours_final_model.pkl` or `log_reg_model.pkl` - trained model files used by the apps

## Features

- Input study hours
- Input attendance percentage (in the Streamlit version)
- Predict pass/fail outcome
- Show probability of success or failure
- Easy to run locally in a browser

## Setup

1. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```
   On Windows:
   ```bash
   venv\Scripts\activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:

   Streamlit:
   ```bash
   streamlit run app.py
   ```

   Gradio:
   ```bash
   python app_gradio.py
   ```

## Example Use

- Enter study hours (for example, 5)
- For the Streamlit app, also enter attendance percentage
- Click predict to see whether the student is likely to pass or fail

## Notes

This project is designed as a general academic performance predictor and does not rely on a specific institution name, making it easy to adapt for other student datasets or learning environments.

## License

This project is for educational and demonstration purposes.
