# Credit Card Fraud Detection

## Overview
This project is a **Credit Card Fraud Detection System** using a machine learning model trained on transaction data. The model predicts whether a transaction is **fraudulent** or **legitimate**.

## Features
- Upload a **CSV file** with transaction data for batch fraud detection.
- Manually enter transaction details to check individual transactions.
- Uses a **pre-trained machine learning model** (`credit_card_model.pkl`).
- Built with **Streamlit** for a simple and interactive UI.

## Requirements
- Python 3.8+
- Required libraries:
  ```bash
  pip install streamlit pandas numpy scikit-learn
  ```

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```
2. Place the trained model in the project folder:
   ```
   credit_card_model.pkl
   ```
3. Ensure the dataset file is placed correctly for testing:
   ```
   creditcard.csv (for dataset testing)
   ```
4. Run the Streamlit app:
   ```bash
   streamlit run streamlit_fraud_detection.py
   ```
5. Open the **localhost URL** provided in the terminal to use the app.

## File Structure
- `streamlit_fraud_detection.py` - The Streamlit app.
- `credit_card_model.pkl` - Trained fraud detection model.
- `creditcard.csv` - Sample dataset for testing.

## Deployment
For deployment, consider using **Streamlit Sharing**, **Heroku**, or **Google Cloud App Engine**.

## Author
Developed by **Adwik Verma**

## License
MIT License
