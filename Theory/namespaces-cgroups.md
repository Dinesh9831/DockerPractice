# 🔐 Namespaces and Control Groups (cgroups)

---

## 🎯 Introduction

Containers rely on Linux kernel features like namespaces and control groups (cgroups) to provide isolation and resource management.

---

## 🔹 Namespaces (Isolation)

Namespaces isolate system resources for containers.

### Types of Namespaces:

* PID → Process isolation
* NET → Network isolation
* MNT → File system isolation
* UTS → Hostname isolation
* IPC → Inter-process communication
* USER → User and permissions

---

## 🔹 Control Groups (cgroups)

cgroups limit and manage resource usage.

### Resources Controlled:

* CPU
* Memory
* Disk I/O
* Network bandwidth

---

## 🔍 Example

A container can be limited to:

* 512MB RAM
* 1 CPU core

---

## 🧠 Why Important?

* Prevents resource overuse
* Ensures fair distribution
* Improves system stability

---

## 🧠 Conclusion

Namespaces provide isolation, while cgroups enforce resource limits—together forming the foundation of containerization.

---
