# Banknote Authentication API with FastAPI

This project trains a **Random Forest Classifier** to detect authentic vs counterfeit banknotes, and serves predictions via a **FastAPI** REST API.

## 🚀 Features
- Load and preprocess the **[Banknote Authentication dataset](https://www.kaggle.com/datasets/ritesaluja/bank-note-authentication-uci-data)**.
- Train a Random Forest Classifier.
- Serialize the trained model into `classifier.pkl`.
- Serve model predictions through a FastAPI app.

## 📂 Project Structure
```text
├── BankNote_Authentication.csv    # Dataset for training
├── ModelTraining.ipynb            # Jupyter notebook for model training
├── BankNotes.py                   # Pydantic data model for API request body
├── app.py                         # FastAPI application
├── classifier.pkl                 # Serialized trained model
├── requirements.txt               # Python dependencies
├── Procfile                       # Deployment config (e.g., Heroku)
├── main.py                        # Alternative app entry point
└── README.md                      # Project documentation
