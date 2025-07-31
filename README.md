# 🔍 Website Uptime Monitoring with Prometheus, Grafana, Blackbox Exporter & Alertmanager

Monitor your website's uptime in real time using a modern DevOps stack powered by **Prometheus**, **Grafana**, **Blackbox Exporter**, and **Alertmanager** — all containerized with **Docker** and configured using **Bash** scripts.

---

## 📌 Features

- ✅ Uptime monitoring for any public-facing URL  
- 📊 Custom Grafana dashboard for live metrics  
- 🚨 Alerting with **MailSlurp SMTP** for downtime  
- 🐳 Full Dockerized setup — easy to run and deploy  
- 💡 Prometheus alert rules defined for fast detection  

---

## 🔧 Tech Stack

- **Prometheus** – metrics collection  
- **Blackbox Exporter** – probe target site uptime  
- **Grafana** – dashboard visualization  
- **Alertmanager** – email alerting  
- **Docker & Docker Compose**  
- **Bash scripting**  

---

## 📬 Email Alerting

- SMTP is configured using **MailSlurp** (can be swapped for Gmail, Mailgun, etc.)  
- Alerts trigger if the website is down for more than 30 seconds  
- Configuration files:
  - `alertmanager/config.yml`
  - `prometheus/alerts.yml`  

---

## 📁 Project Structure

├── alertmanager/
│ └── config.yml
├── prometheus/
│ ├── prometheus.yml
│ └── alerts.yml
├── docker-compose.yml
└── README.md


---

## 💼 Real-World Applications

- 👨‍💻 Portfolio project to showcase monitoring & observability  
- 🏢 Used in DevOps teams to ensure high availability  
- 🛠 Great foundation to integrate logging, autoscaling, or notifications  

---

## 🙌 Author

**Oluwahiyanu Akinlalu**  
GitHub: [@oluwahiyanu](https://github.com/oluwahiyanu)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
