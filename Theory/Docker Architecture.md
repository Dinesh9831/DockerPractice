# 🏗 Docker Architecture

---

## 🎯 Overview

Docker follows a client-server architecture to manage containers efficiently.

---

## 🔧 Core Components

### 🔹 Docker Client

* CLI tool (`docker` command)
* Sends commands to Docker daemon

---

### 🔹 Docker Daemon

* Core engine (`dockerd`)
* Builds, runs, and manages containers

---

### 🔹 Docker Images

* Read-only templates
* Used to create containers

---

### 🔹 Docker Containers

* Running instances of images

---

### 🔹 Docker Registry

* Stores and distributes images
* Example: Docker Hub

---

## 🔄 Workflow

```text
User → Docker CLI → Docker Daemon → Container/Image → Registry
```

---

## 🧠 Key Concepts

* Images are immutable
* Containers are ephemeral
* Layers improve efficiency

---

## 🧠 Conclusion

Docker architecture enables seamless container lifecycle management using a modular and scalable design.

---
