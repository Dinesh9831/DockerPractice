# 📄 Dockerfile Concepts

---

## 🎯 Introduction

A Dockerfile is a script containing instructions to build a Docker image automatically.

---

## 🔧 Common Instructions

| Instruction | Purpose                   |
| ----------- | ------------------------- |
| FROM        | Base image                |
| RUN         | Execute commands          |
| COPY        | Copy files                |
| ADD         | Copy with extra features  |
| CMD         | Default command           |
| ENTRYPOINT  | Fixed execution           |
| WORKDIR     | Set working directory     |
| ENV         | Set environment variables |
| EXPOSE      | Define ports              |

---

## 🔍 Example Dockerfile

```dockerfile
FROM nginx
COPY . /usr/share/nginx/html
```

---

## 🔄 Image Layering

* Each instruction creates a layer
* Layers are cached and reused
* Improves build efficiency

---

## ⚙️ Build Process

```bash
docker build -t myimage:v1 .
```

---

## 🧠 Best Practices

* Use minimal base images
* Reduce number of layers
* Use `.dockerignore`
* Avoid unnecessary files

---

## 🧠 Conclusion

Dockerfiles enable automated, repeatable image creation, forming the backbone of containerized workflows.

---
