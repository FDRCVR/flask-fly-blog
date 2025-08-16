> © 2025 Alexander Tumanov — All Rights Reserved
---




# Flask Fly Blog

A clean Flask-based blog template ready for deployment on Fly.io.

## Features
- Flask + Bootstrap UI
- SQLite by default
- Auth-ready (Google & GitHub via Flask-Dance planned)
- Dockerfile + fly.toml for deployment

## Local quickstart
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
flask --app app run
