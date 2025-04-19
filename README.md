
# SimpleWeb

A minimal web application packaged in a Docker container.

## 🚀 Getting Started

Follow these instructions to build and run the project using Docker.

### 🔧 Prerequisites

Make sure you have Docker installed on your machine. You can download it from [https://www.docker.com/get-started](https://www.docker.com/get-started).

---

## 🛠️ Build the Docker Image

Run the following command in the project directory to build the Docker image:

```bash
docker build -t <your-username>/simpleweb .
```

Replace `<your-username>` with your Docker Hub username or any custom image name you prefer.

---

## ▶️ Run the Docker Container

Start the container and map the desired port using:

```bash
docker run -p 5001:5001 <your-username>/simpleweb
```

This maps port `5001` on your host machine to port `5001` inside the container.

---

## 🌐 Access the App

Once running, you can access the web application at:

```
http://localhost:5001
```

---

## 🧼 Stop and Remove the Container (Optional)

To stop and remove the running container:

1. List running containers:
   ```bash
   docker ps
   ```

2. Stop the container:
   ```bash
   docker stop <container-id>
   ```

3. Remove the container:
   ```bash
   docker rm <container-id>
   ```

---

## 📂 Project Structure

```
.
├── Dockerfile
├── app/               # Your application source code
└── README.md
```

---


