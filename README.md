# Flask DevOps Lab nothing wrong

## Usage

```bash
#Activate the virtual environment
source .venv/Scripts/activate

#Install requirements
pip install -r requirements.txt

#Run Flask development server
python app.py
```

# API Endpoints
- /api/health: Returns JSON status check ({"status": "ok"}) to verify the web server is responsive.

- /api/config: Displays the application metadata, version parameters, and environment targets loaded from config.json.

- /api/report: Provides environment details including the host system's name, active Python version, and application runtime uptime trackers.
