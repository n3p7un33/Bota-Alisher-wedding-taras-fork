# Streamlit Google Sheets Auth

This app is a wedding invitation built with Streamlit. Access codes are validated against a Google Sheet using Streamlit's built-in connection.

## Setup
1. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Copy `.streamlit/secrets.toml.example` to `.streamlit/secrets.toml` and set your Google Sheets URL and credentials.

## Running locally
```
streamlit run app.py
```

## Deploying
Deploy on Streamlit Community Cloud and set the same secrets in the UI.
