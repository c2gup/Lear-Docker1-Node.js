# 🚀 Node.js Backend App (with Docker + GitHub Integration)

This is a simple backend app built with Express and Nodemon, containerized using Docker.

---

## 🐳 Run the App with Docker

### 1. Build the Docker image
```bash
docker build -t my-backend-app .
```

### 2. Run the Docker container
```bash
docker run -p 3000:3000 my-backend-app
```

---

## 🔁 Hot Reloading with Nodemon (Optional for Development)
Use this for automatic server restarts when code changes:

```bash
docker run -p 3000:3000 -v $(pwd):/app my-backend-app
```

**Update `package.json` if needed:**
```json
"start": "nodemon --legacy-watch index.js"
```

---