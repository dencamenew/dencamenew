# Привет! Я Денис 👋

### DevOps / Infrastructure Engineer | Intern / Junior

Студент 3 курса направления **«Информационная безопасность автоматизированных систем»**.

Развиваюсь в **DevOps / SRE**: Linux, контейнеризация, Kubernetes, Infrastructure as Code, CI/CD, GitOps и мониторинг.

Практикуюсь не только на учебных задачах — разворачиваю собственную Kubernetes-инфраструктуру и занимаюсь инфраструктурой веб-сервисов, работающих на VPS.

📫 **Связаться:** [Telegram](https://t.me/maytgzr) · [Email](mailto:dencamenew@yandex.ru)

---

## 🚀 Основные проекты

### ☸️ Kubernetes Infrastructure Lab

[**→ GitHub Repository**](https://github.com/dencamenew/infra)

Локальная Kubernetes-инфраструктура для микросервисного web-приложения с полностью автоматизированным развёртыванием.

**Что реализовано:**

* Kubernetes-кластер из **3 виртуальных машин**
* создание инфраструктуры через **Terraform**
* автоматическая конфигурация узлов через **Ansible**
* развёртывание Kubernetes через **kubeadm + containerd**
* **ingress-nginx** для маршрутизации
* локальный **GitLab Container Registry**
* GitOps-деплой через **Argo CD**
* мониторинг через **Prometheus + Grafana**
* контейнеризация сервисов через **Docker**

**Архитектура:**

`Terraform → Ansible → kubeadm → Kubernetes → ingress-nginx → GitLab Registry → Argo CD → Prometheus/Grafana`

**Результат:** воспроизводимая Kubernetes-инфраструктура, охватывающая полный цикл от создания виртуальных машин до автоматической доставки приложения и мониторинга состояния кластера.

---

### 🏛 Infrastructure for University Information System

🌐 **Production:** [universityapp.site](https://universityapp.site)

Развиваю и поддерживаю инфраструктуру информационной системы ВУЗа.

**Что реализовано:**

* отдельные **prod/dev окружения**
* CI/CD pipeline на **GitHub Actions**
* автоматическая сборка Docker-образов
* публикация образов в **GHCR**
* автоматический деплой на VPS
* **Docker Compose** для запуска сервисов
* **Nginx** как reverse proxy
* HTTPS и автоматическое обновление SSL-сертификатов
* мониторинг через **Prometheus, Grafana, node-exporter, cAdvisor**
* управление контейнерами через **Portainer**
* базовая защита SSH и ограничение внешнего доступа к сервисам

**Архитектура:**

`GitHub Actions → GHCR → VPS → Docker Compose → Nginx → FastAPI/Redis → Prometheus/Grafana`

---

## 🛠 Технологии

### Infrastructure & DevOps

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square\&logo=linux\&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square\&logo=kubernetes\&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square\&logo=terraform\&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square\&logo=ansible\&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square\&logo=argo\&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square\&logo=nginx\&logoColor=white)

### CI/CD & Monitoring

![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square\&logo=gitlab\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square\&logo=githubactions\&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square\&logo=prometheus\&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square\&logo=grafana\&logoColor=white)

### Development & Data

![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square\&logo=gnubash\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square\&logo=redis\&logoColor=white)

---

## 🌐 Базовые знания

`TCP/IP` · `DNS` · `HTTP/HTTPS` · `TLS` · `Reverse Proxy` · `CI/CD` · `GitOps` · `Infrastructure as Code`

---

## 📫 Контакты

[![Telegram](https://img.shields.io/badge/Telegram-@maytgzr-26A5E4?style=flat-square\&logo=telegram\&logoColor=white)](https://t.me/maytgzr)

**Email:** [dencamenew@yandex.ru](mailto:dencamenew@yandex.ru)
