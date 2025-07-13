# Streamlit Google Sheets Auth

This app is a wedding invitation built with Streamlit. An access code is validated against a Google Sheet using Streamlit's `GSheetsConnection`.

## Setup
1. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Copy `.streamlit/secrets.toml.example` to `.streamlit/secrets.toml` and fill in your Google service account credentials and sheet details.

## Running locally
```
streamlit run app.py
```

## Deploying
Deploy on Streamlit Community Cloud and set the same secrets in the UI.

### Secrets format

```
[connections.gsheets]
spreadsheet = "https://docs.google.com/spreadsheets/d/YOUR_ID"
worksheet = "Codes"
# type = "service_account"
# project_id = "YOUR_PROJECT_ID"
# private_key = "-----BEGIN PRIVATE KEY-----\n...\n-----END PRIVATE KEY-----\n"
# client_email = "your-service-account@your-project.iam.gserviceaccount.com"
```
