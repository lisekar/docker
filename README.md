
# 🚀 Calculator app with Docker implementation

A lightweight calculator application designed to perform basic arithmetic operations. This project demonstrates how simple applications can be containerized using Docker for consistent, portable, and hassle-free deployment across different environments.

---

## ✨ Features

- 🔧 Clean and modular project structure  
- ⚡ Fast and lightweight  
- 📦 Docker-ready  
- 🛡️ Built with secure best practices  
- 📁 Volume support for persistent storage  

---

## 🛠️ Tech Stack

- **Backend:** Node.js
- **Containerization:** Docker
- **Tools:** Git, Docker Hub

---


commands to follow:
===================

docker ps -a  # List all running container

docker build -t [container-name] .   # Build a container

docker images  # List all docker images

docker run -p 9002:5000 --name [container-name] [image-name]  # create image with container

docker volume ls  # List all volume

docker volume create [Vol-name]  # create volume

docker run -p 9002:5000 -v [Vol-name]:/[vol-filename] --name [container-name] [image-name] # mount volume file

docker run -p 9002:5000 -v [Local sys path]:/[vol-filename] --name [container-name] [image-name] # bind volume with local system folder

docker tag [image-name] [livisekar/simple-calculator (tag-name)]

docker login -u [username]

docker push [livisekar/simple-calculator (tag-name)]

docker pull [livisekar/simple-calculator (tag-name)]

docker rmi [livisekar/simple-calculator (tag-name)]
