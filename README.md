# Phishing Awareness Campaign – Noti0nPhish Simulation

## 📄 Project Overview

This repository documents the planning, deployment, and analysis of an internal phishing awareness campaign using a simulated scenario based on a fake Notion-branded workspace invitation. Conducted in a controlled and ethical environment with participant consent, this project aims to raise awareness around social engineering tactics and improve cybersecurity posture through real-world testing and targeted training.

## 🎯 Objectives

- Simulate a convincing phishing campaign using realistic assets
- Measure participant behavior: link clicks, credential submissions, and email reporting
- Analyze results to identify awareness gaps and high-risk patterns
- Deliver a customized awareness campaign based on actual data
- Document the process as a portfolio-ready cybersecurity training simulation

## 🧪 Project Summary

The campaign used a spoofed domain (`noti0n.com`) and a custom-designed Notion-themed login page. Participants received an email that mimicked a standard team invitation. The infrastructure was deployed via Docker using the GoPhish framework, and Cloudflare Tunnel was used to expose the campaign infrastructure securely to the internet.

Collected metrics such as click-through rate, submission rate, and report rate were used to assess susceptibility. A post-campaign debrief and awareness training were designed based on participant performance.

## 💡 Key Features

- **Custom Domain & Realistic Branding**: `noti0n.com` registered and configured to host the phishing page
- **GoPhish Deployment**: Managed campaign through GoPhish via Docker and cloud tunneling
- **Landing Page Simulation**: Replica Notion login page with credential capture and redirect
- **Email Template Design**: Simulated Notion invitation email with embedded tracking
- **Data-Driven Analysis**: Collection of behavioral metrics with post-campaign visual analytics
- **Awareness Training Material**: Custom posters, quizzes, and debrief documents (post-campaign)


## 🛠️ Tech Stack

| Tool / Platform     | Purpose                             |
|---------------------|-------------------------------------|
| GoPhish             | Phishing campaign framework         |
| Docker              | Local environment & deployment      |
| Cloudflare Tunnel   | Exposing campaign securely online   |
| HTML/CSS            | Email & landing page customization  |
| GitHub              | Documentation & version control     |

## 🔒 Ethical Considerations

This simulation was conducted strictly with prior informed consent from all participants. No real credentials were stored or misused. The campaign is intended purely for educational and awareness purposes and complies with ethical cybersecurity practices.

## 📚 Use Case

This project demonstrates the ability to:
- Design and run full-stack phishing simulations
- Develop realistic phishing infrastructure
- Analyze human behavioral data in a security context
- Produce actionable awareness and training materials based on findings

## 🔄 Future Enhancements

- Add SMS and voice-based phishing components
- Expand to multilingual simulations
- Integrate dynamic dashboards for real-time tracking
- Apply behavior-based training paths depending on user actions

## 📬 Contact

For feedback, collaboration, or digital high-fives:

**Jorge Faria**    
🔗 [LinkedIn](https://www.linkedin.com/in/fariajorge/)
