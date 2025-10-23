# deployment-test-app


This is a minimal Python application used for testing Docker and deployment scripts.  
It starts a small web server that displays a "Hello from your EC2 deployment!" message.

---

## 🐳 Docker Setup

**Build the Docker image:**
```bash
docker build -t flask-app .
````

**Run the container:**

```bash
docker run -d -p 8000:8000 flask-app
```

Then open your browser and visit:

```
http://localhost:8000
```

---

## 📁 Project Structure

```
.
├── app.py
└── Dockerfile
```

---

## 💡 Description

* `app.py` — contains a simple Flask web server.
* `Dockerfile` — defines how the app is built and run inside a Docker container.

---

## 🚀 Deployment

You can use this repository to test CI/CD or deployment automation scripts (e.g., deploying to AWS EC2).

