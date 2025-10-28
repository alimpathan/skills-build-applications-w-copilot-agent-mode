OctoFit Tracker — Backend

This folder contains the backend scaffold for OctoFit Tracker (Django + DRF).

Setup (create venv and install dependencies):

```bash
python3 -m venv octofit-tracker/backend/venv
source octofit-tracker/backend/venv/bin/activate
pip install -r octofit-tracker/backend/requirements.txt
```

Notes:
- Use Django's ORM for models and data migrations.
- MongoDB-related packages are included per project instructions, but we recommend verifying DB backend configuration before use.
