# Phishing Awareness Campaign – Noti0nPhish Simulation 🛡️

## 📄 Project Overview

This repository documents the full design, deployment, and analysis of an internal phishing awareness campaign conducted at CTVC (Cooperativa Tecnológica de Viana do Castelo). The campaign was executed in a fully controlled environment with institutional consent, aiming to test employee awareness of social engineering tactics and inform targeted security training.

## 🎯 Objectives

- Simulate a convincing phishing campaign using realistic branding and delivery
- Measure human behavior: link clicks, credential submissions, and report actions
- Analyze performance data to identify awareness gaps and risk profiles
- Provide tailored training and strategic recommendations
- Build a reproducible, portfolio-ready security assessment project

## 🧪 Campaign Summary

Participants received a simulated Notion-branded workspace invitation from a spoofed domain (`noti0n.com`). The infrastructure leveraged Docker, GoPhish, and NGINX with HTTPS, running on a public Kali Linux VPS.

Collected behavioral metrics included:
- **Click-Through Rate (CTR)**: 42.3%
- **Credential Submission Rate (CSR)**: 38.5%
- **Report Rate (RR)**: 0%
- **Median Time-to-Click**: 23 minutes

The near-identical design and theme of the email and login page proved effective in evoking trust, particularly among administrative personnel.

## 💡 Key Features

- **Custom Domain & DNS Setup**: `noti0n.com` with SPF, DKIM, and DMARC
- **Containerized Deployment**: Docker + Docker Compose for GoPhish and NGINX
- **TLS Certificates**: HTTPS via Let’s Encrypt and Certbot
- **Landing Page Replica**: Notion-themed login page tracked via GoPhish
- **Email Template Engineering**: HTML/CSS mimicking authentic Notion invites
- **Automated Metrics Collection**: REST API logs analyzed with pandas
- **Training Material Development**: Posters, micro-lessons, and a structured debrief

## 📊 Impact & Insights

- 11 of 26 participants clicked the link (42.3%)
- 10 submitted fake credentials (38.5%)
- 0 reported the phishing attempt
- Short reaction times revealed tight attack windows and urgent training needs

These results informed the development of a post-campaign training intervention, focusing on domain verification, email scrutiny, and incident reporting procedures.

## 🛠️ Tech Stack

| Tool / Platform     | Purpose                             |
|---------------------|-------------------------------------|
| GoPhish             | Phishing simulation & tracking      |
| Docker              | Service orchestration               |
| NGINX               | HTTPS reverse proxy                 |
| Certbot             | TLS certificate provisioning        |
| HTML/CSS            | UI/UX for phishing assets           |
| GitHub              | Version control and documentation   |
| pandas (Python)     | Data analysis and metrics reporting |

## 🔒 Ethical Considerations

- **Approved** by CTVC Ethics Committee (Proc. 2025/-07)
- **Consent** obtained from all participants, with opt-out available
- **No real credentials** stored; passwords discarded on submission
- **Immediate debrief** post-campaign with anonymous reporting

## 🧭 Use Case

Ideal as a demonstrable cybersecurity capstone or awareness-training project:
- Shows full-stack simulation capability
- Demonstrates human behavior analysis
- Highlights ethical and legal compliance
- Provides measurable impact and clear recommendations

## 🔄 Future Enhancements

- Expand to include SMS and voice-based phishing (vishing)
- Introduce multilingual and adaptive training content
- Automate real-time dashboards for SOC teams
- Conduct quarterly simulations for progressive tracking

## 📬 Contact

**Jorge Faria**  
🔗 [LinkedIn](https://www.linkedin.com/in/fariajorge/)  
📩 Report available upon request
