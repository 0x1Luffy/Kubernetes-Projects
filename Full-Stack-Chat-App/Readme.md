# 🚀 Full Stack Chat App – Kubernetes + CI/CD

A production-style **Full Stack Chat Application** deployed on **Kubernetes (kOps)** with **Jenkins CI/CD**, **MongoDB Atlas**, and **Uptime Kuma monitoring**.

---

## 🧱 Infra


<img width="1919" height="599" alt="image" src="https://github.com/user-attachments/assets/7073db80-1720-40ee-bd18-ac0b7d6b097c" />

<img width="1376" height="378" alt="image" src="https://github.com/user-attachments/assets/04f92d33-b117-4690-8b9a-508c1f20fab1" />

<img width="1918" height="986" alt="image" src="https://github.com/user-attachments/assets/6acf6f3b-b0a0-4b10-a739-24d663bcd463" />

<img width="1919" height="1008" alt="image" src="https://github.com/user-attachments/assets/22e424c2-7928-4031-94dd-4961c9f51613" />





🚀 Fully containerized • ☸ Kubernetes managed • 🔁 Auto-deployed

---

## 🛠 Tech Stack

- Frontend: React, Vite, Nginx
- Backend: Node.js, Express
- Database: MongoDB Atlas
- Containers: Docker
- Orchestration: Kubernetes (kOps on AWS)
- CI/CD: Jenkins
- Monitoring: Uptime Kuma

---

## 📂 Repository Structure

```
Kubernetes-Projects/
└── Full-Stack-Chat-App/
    ├── frontend/
    ├── backend/
    ├── K8s/
    ├── Jenkinsfile
    └── docker-compose.yml
```

---

## 🔄 CI/CD Pipeline (Jenkins)

On every **push to `master`**:

```
GitHub Push
   ↓
Jenkins Webhook Trigger
   ↓
Docker Build (Frontend + Backend)
   ↓
Docker Hub Push
   ↓
kubectl apply (kOps Cluster)
```

✔ Fully automated  
✔ Zero manual deployment  

---

## ☸ Kubernetes Deployment

- Separate **Deployments** for frontend & backend
- **Services** for internal communication
- **Ingress / LoadBalancer** for public access
- **Secrets** for MongoDB Atlas connection
- Cluster managed using **kOps**

---

## 📡 Monitoring – Uptime Kuma

Uptime Kuma continuously monitors:

- 🌐 Frontend availability
- ⚙️ Backend health
- ⏱ Response time & downtime

Provides real-time alerts and uptime dashboard.

---

## 🌍 Access

- Application exposed via **Kubernetes LoadBalancer / Ingress**
- Public endpoint monitored by **Uptime Kuma**

---

## ✅ Key Highlights

- Real-world Kubernetes deployment
- Jenkins CI/CD with GitHub Webhooks
- Secure cloud database (MongoDB Atlas)
- Monitoring with Uptime Kuma
- Production-ready DevOps workflow

---

## 📌 Future Enhancements

- HTTPS (cert-manager)
- HPA (Auto Scaling)
- Prometheus + Grafana
- Blue-Green deployments
