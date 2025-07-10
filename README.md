# Streamlit Airtable Auth

This app is a wedding invitation built with Streamlit. An access code is validated against an Airtable table before the invitation is shown.

## Setup
1. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Copy `.streamlit/secrets.toml.example` to `.streamlit/secrets.toml` and fill in your Airtable credentials.

## Running locally
```
streamlit run app.py
```

## Deploying
Deploy on Streamlit Community Cloud and set the same secrets in the UI.
