# Flask CI/CD Demo

Simple CI/CD pipeline project using:
- Flask (Python)
- Docker
- GitHub Actions
- AWS ECS / Render

## Run locally
```bash
docker build -t flask-ci-cd-demo .
docker run -p 5000:5000 flask-ci-cd-demo
