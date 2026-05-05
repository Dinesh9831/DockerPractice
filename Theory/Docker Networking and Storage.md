# 🌐 Docker Networking and Storage

---

## 🎯 Introduction

Docker provides networking and storage mechanisms to enable communication and persistence in containers.

---

# 🔹 Docker Networking

## Types of Networks:

* Bridge (default)
* Host
* None
* Custom bridge

---

## 🔍 Bridge Network

* Containers communicate via IP
* Custom bridge allows DNS-based communication

---

## 🔌 Port Mapping

```bash
-p 8080:80
```

Meaning:

```text
Host:8080 → Container:80
```

---

# 🔹 Docker Storage

## Volumes vs Bind Mounts

| Feature           | Volumes    | Bind Mounts |
| ----------------- | ---------- | ----------- |
| Managed by Docker | Yes        | No          |
| Portability       | High       | Low         |
| Performance       | Better     | Depends     |
| Use Case          | Production | Development |

---

## 🔍 Volume Example

```bash
docker run -v mydata:/app nginx
```

---

## 🧠 Why Storage Matters

* Data persistence
* Database storage
* Log retention

---

## 🧠 Conclusion

Docker networking enables container communication, while volumes ensure data persistence—both critical for real-world applications.

---
