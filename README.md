# AI Health Insurance Premium Prediction

A machine learning application that predicts health insurance premiums based on user information such as age, income, dependants, medical history, lifestyle, and insurance plan.

## Features

* Health insurance premium prediction
* Streamlit web interface
* Machine learning models for different age groups
* User-friendly input form
* Pre-trained models stored in the `artifacts` directory

## Tech Stack

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Joblib

## Run Locally

Create and activate a virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

Install dependencies:

```powershell
python -m pip install -r requirements.txt
```

Run the Streamlit application:

```powershell
python -m streamlit run main.py
```

The application will open at:

```text
http://localhost:8501
```

## Project Structure

```text
ml-project-premium-prediction/
│
├── artifacts/
│   ├── model_young.joblib
│   ├── model_rest.joblib
│   ├── scaler_young.joblib
│   └── scaler_rest.joblib
│
├── main.py
├── prediction_helper.py
├── requirements.txt
└── README.md
```

## License

