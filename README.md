# Stripe Billing charging for subscriptions

## Requirements

- Python 3
- [Configured .env file](../README.md)

## How to run

1. Go to folder /server
  cd /server

2. Create and activate a new virtual environment

```
python3 -m venv /env
source /env/bin/activate
```

3. Install dependencies

```
pip install -r requirements.txt
```

4. Export environment variables

source env.dev.sh

5. Export and run the application

```
export FLASK_APP=server.py
python3 -m flask run --port=4242
```

6. Go to `localhost:4242` in your browser to see the demo
