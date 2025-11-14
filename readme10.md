<div align="center">

<!-- ========================= -->
<!-- 🌐 HEADER GLASS PANEL -->
<!-- ========================= -->

<div style="
    backdrop-filter: blur(14px);
    -webkit-backdrop-filter: blur(14px);
    background: rgba(255,255,255,0.05);
    border: 1px solid rgba(255,255,255,0.12);
    padding: 40px;
    border-radius: 20px;
    max-width: 900px;
">

<h1 style="color:white; margin-bottom:10px;">🌐 Deployments Hub</h1>

<p style="color:#d0d0d0; font-size:17px;">
<strong>Your Bare-Metal Deployment & Automation Command Center</strong>
</p>

<p style="color:#b7b7b7; font-size:15px;">
Built for bare-metal servers using  
<b>Docker</b> · <b>Kubernetes (kubeadm)</b> · <b>Helm</b> · <b>GitHub Actions</b> ·  
<b>Monitoring (Prometheus · Grafana · Loki · Promtail)</b>
</p>

<br>

<a href="#workflows">
  <img src="https://img.shields.io/badge/Workflows-3A7BD5?style=for-the-badge&logo=workflow&logoColor=white" />
</a>
<a href="#tech-stack">
  <img src="https://img.shields.io/badge/Tech%20Stack-6C5CE7?style=for-the-badge&logo=wrench&logoColor=white" />
</a>
<a href="#features">
  <img src="https://img.shields.io/badge/Features-81B29A?style=for-the-badge&logo=cube&logoColor=white" />
</a>

</div>

<br>

<!-- Animated Smooth Wave (STYLE A) -->
<svg width="100%" height="100" viewBox="0 0 1440 320" preserveAspectRatio="none">
  <path fill="#1a1a1a" fill-opacity="1">
    <animate attributeName="d" dur="7s" repeatCount="indefinite"
      values="
      M0,64L80,69.3C160,75,320,85,480,90.7C640,96,800,96,960,101.3C1120,107,1280,117,1360,122.7L1440,128V320H0Z;
      M0,96L60,112C120,128,240,160,360,181.3C480,203,600,213,720,197.3C840,181,960,139,1080,112C1200,85,1320,75,1380,69.3L1440,64V320H0Z;
      M0,64L80,69.3C160,75,320,85,480,90.7C640,96,800,96,960,101.3C1120,107,1280,117,1360,122.7L1440,128V320H0Z;
      " />
  </path>
</svg>

</div>

---

<!-- ========================= -->
## 🛠 What This Hub Delivers  
<!-- ========================= -->

<!-- Animated Terminal Bar (STYLE C) -->
<svg width="100%" height="18">
  <rect width="100%" height="18" fill="#0c0c0c"/>
  <rect width="30%" height="18" fill="#3a7bd5">
    <animate attributeName="width" dur="3s" values="12%;40%;12%" repeatCount="indefinite"/>
  </rect>
</svg>

<div style="
    background: rgba(255,255,255,0.04);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255,255,255,0.09);
    border-radius: 18px;
    padding: 25px;
">

- 🚀 High-performance **bare-metal deployments**
- 🐳 Docker containerized microservices
- ☸️ **Kubernetes via kubeadm** for production-grade clusters
- ⛵ Multi-environment deployments powered by **Helm**
- ⚙️ GitHub Actions for CI/CD automation
- 📊 **Full monitoring stack: Prometheus · Grafana · Loki · Promtail**
- 🧩 Standardized deployment blueprints for org-wide consistency

</div>

---

<!-- ========================= -->
## 🧩 Tech Stack  
<!-- ========================= -->

<!-- Animated Terminal Bar -->
<svg width="100%" height="18">
  <rect width="100%" height="18" fill="#0c0c0c"/>
  <rect width="27%" height="18" fill="#6C5CE7">
    <animate attributeName="width" dur="3s" values="10%;42%;10%" repeatCount="indefinite"/>
  </rect>
</svg>

<div style="
    background: rgba(255,255,255,0.04);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255,255,255,0.08);
    border-radius: 18px;
    padding: 25px;
" align="center">

<!-- Core Runtime -->
<img src="https://img.shields.io/badge/Docker-1D6FA5?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Kubernetes_(kubeadm)-244F7D?style=for-the-badge&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/Helm-2A3F8E?style=for-the-badge&logo=helm&logoColor=white" />

<br><br>

<!-- CI/CD -->
<img src="https://img.shields.io/badge/GitHub_Actions-2F2F2F?style=for-the-badge&logo=githubactions&logoColor=white" />

<br><br>

<!-- Monitoring -->
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
<img src="https://img.shields.io/badge/Loki-Logs-4E9A06?style=for-the-badge&logo=grafana&logoColor=white" />
<img src="https://img.shields.io/badge/Promtail-Logs-4E9A06?style=for-the-badge&logo=grafana&logoColor=white" />

</div>

---

<!-- ========================= -->
## ⚡ Workflows & Getting Started  
<!-- ========================= -->

<!-- Animated Terminal Bar -->
<svg width="100%" height="18">
  <rect width="100%" height="18" fill="#0c0c0c"/>
  <rect width="25%" height="18" fill="#3a7bd5">
    <animate attributeName="width" dur="3s" values="10%;45%;10%" repeatCount="indefinite"/>
  </rect>
</svg>

<div style="
    background: rgba(255,255,255,0.04);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255,255,255,0.08);
    border-radius: 18px;
    padding: 25px;
">

### **1️⃣ Build a Docker Image**
```sh
docker build -t service:latest .
```

### **2️⃣ Deploy Using Helm**
```sh
helm upgrade --install service ./helm-charts/service \
    --namespace production \
    -f ./helm-charts/service/values-prod.yaml
```

### **3️⃣ Kubernetes (kubeadm) Bare-Metal Cluster**
- Initialize master & workers  
- containerd runtime  
- Install flannel / calico  
- Deploy workloads using Helm  

### **4️⃣ GitHub Actions Workflows**
- CI build → Test → Dockerize → Push  
- Deploy via SSH/Kubectl to bare-metal  
- Automated pipelines for each service  

### **5️⃣ Monitoring Setup**
- Prometheus (metrics)  
- Loki (logs)  
- **Promtail (log collector)**  
- Grafana (dashboards)  

</div>

---

<!-- ========================= -->
## 🔐 Secrets & Configuration  
<!-- ========================= -->

<!-- Animated Terminal Bar -->
<svg width="100%" height="18">
  <rect width="100%" height="18" fill="#0b0b0b"/>
  <rect width="21%" height="18" fill="#6c5ce7">
    <animate attributeName="width" dur="3s" values="10%;35%;10%" repeatCount="indefinite"/>
  </rect>
</svg>

<div style="
    background: rgba(255,255,255,0.04);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255,255,255,0.08);
    border-radius: 18px;
    padding: 25px;
">

- 🔑 GitHub Encrypted Secrets  
- 🧩 Kubernetes Secrets  
- 🗂 values-dev.yaml / values-prod.yaml  
- 🚫 No plaintext secrets  

</div>

---

<!-- ========================= -->
## 📊 Observability Stack  
<!-- ========================= -->

<!-- Animated Terminal Bar -->
<svg width="100%" height="18">
  <rect width="100%" height="18" fill="#0b0b0b"/>
  <rect width="30%" height="18" fill="#f46800">
    <animate attributeName="width" dur="3s" values="10%;50%;10%" repeatCount="indefinite"/>
  </rect>
</svg>

<div style="
    background: rgba(255,255,255,0.04);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255,255,255,0.08);
    border-radius: 18px;
    padding: 25px;
">

- 📈 **Prometheus** — Metrics  
- 📊 **Grafana** — Dashboards  
- 📜 **Loki** — Log aggregation  
- 🟢 **Promtail** — Log collector and forwarder  
- 🚨 **Alertmanager** — Alerts  

</div>

---

## ⭐ Status

![CI/CD](https://img.shields.io/badge/CI%2FCD-Passing-4D8ACF?style=flat&logo=github)
![Docker](https://img.shields.io/badge/Docker-Ready-3A7BD5?style=flat&logo=docker)
![Kubernetes](https://img.shields.io/badge/Kubernetes-kubeadm-244F7D?style=flat&logo=kubernetes)
![Helm](https://img.shields.io/badge/Helm-Charts-2A3F8E?style=flat&logo=helm)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana)
![Loki](https://img.shields.io/badge/Loki-4E9A06?style=flat&logo=grafana)
![Promtail](https://img.shields.io/badge/Promtail-4E9A06?style=flat&logo=grafana&logoColor=white)

---

<div align="center">
<h3 style="color:#dddddd;">🚀 Maintained with ❤️ by the DevOps Team</h3>
</div>
