# KR2 template

Counter service on Flask + Redis.

## Local run
1. Copy `.env.example` to `.env` and fill in the values.
2. Run: `pip install -r requirements.txt && flask --app app run`

## Docker run
```bash
docker build -t kr2-app .
docker run -p 8003:8003 --env-file .env kr2-app