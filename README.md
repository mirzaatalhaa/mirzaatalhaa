<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Mirza%20Talha%20Baig&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Cloud%20%7C%20AI/ML%20%7C%20Full%20Stack%20Engineer&descAlignY=55&descSize=18)

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=600&lines=Cloud+%26+Backend+Engineer;AWS+%7C+Docker+%7C+Terraform+%7C+CI%2FCD;Building+Scalable+Serverless+Systems;Open+to+Internships+%26+Collaborations" alt="Typing SVG" />
</a>

<br/>

![Education](https://img.shields.io/badge/B.Tech-CSE%202023--2027-6366F1?style=for-the-badge&logo=googlescholar&logoColor=white)
![Location](https://img.shields.io/badge/Location-Kochi,%20Kerala,%20India-7C3AED?style=for-the-badge&logo=googlemaps&logoColor=white)

<br/>

<a href="#"><img src="https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/LinkedIn-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:mirzatalhab163@gmail.com"><img src="https://img.shields.io/badge/Email-4C1D95?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/GitHub-5B21B6?style=for-the-badge&logo=github&logoColor=white" /></a>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=mirzatalhabaig&color=blueviolet&style=for-the-badge&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/mirzatalhabaig?label=Followers&style=for-the-badge&color=8B5CF6)
![Stars](https://img.shields.io/github/stars/mirzatalhabaig?label=Stars&style=for-the-badge&color=A78BFA)

</div>

---

## 👨‍💻 About Me

```yaml
Name:        Mirza Talha Baig
Role:        Computer Science & Engineering Student
Focus:       Cloud Infrastructure, AI/ML, Full Stack Development
Location:    Kochi, Kerala, India
```

I'm a **Computer Science and Engineering** student with hands-on experience building **production-grade cloud applications and networking infrastructure** on AWS. I specialize in **Docker, CI/CD pipelines, CloudWatch monitoring, and Terraform** for infrastructure automation, with deep experience designing **custom VPC environments** — subnets, route tables, Internet Gateways, and Security Groups — to build secure, isolated network architectures.

I enjoy building **scalable serverless systems** and **containerized backend services**, combining cloud engineering with practical full-stack and embedded development.

```yaml
Open To:
  - Software Engineering Internships
  - Cloud / DevOps Roles
  - AI/ML Collaborations
  - Open Source Contributions
```

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Skills](https://skillicons.dev/icons?i=python,js,cpp,nodejs)

**Backend & Databases**

![Skills](https://skillicons.dev/icons?i=nodejs,express,postgres)

**Cloud, DevOps & Tooling**

![Skills](https://skillicons.dev/icons?i=aws,docker,githubactions,terraform,git,nginx)

</div>

---

## 🤖 AI / ML & Engineering Expertise

<div align="center">

| Domain | Proficiency | Details |
|--------|:-----------:|---------|
| Cloud Architecture (AWS) | ⭐⭐⭐⭐⭐ | EC2, Lambda, DynamoDB, S3, SNS, IoT Core, EventBridge, CloudWatch, IAM |
| Networking & VPC Design | ⭐⭐⭐⭐⭐ | Custom VPCs, Subnets, Route Tables, IGW, Security Groups, NACLs, Bastion Hosts |
| Infrastructure as Code | ⭐⭐⭐⭐ | Terraform — resource import, remote state (S3), drift reconciliation |
| Containerization & CI/CD | ⭐⭐⭐⭐⭐ | Docker, Docker Compose, GitHub Actions, automated deployments |
| Serverless Engineering | ⭐⭐⭐⭐⭐ | Lambda, EventBridge Scheduler, DynamoDB TTL, SNS notifications |
| Backend Development | ⭐⭐⭐⭐ | Node.js, Express.js, REST APIs, PostgreSQL, node-cron |
| Embedded / IoT | ⭐⭐⭐ | ESP32, embedded C++, device-to-cloud telemetry pipelines |

</div>

---

## 🚀 Featured Projects

<details open>
<summary><b>🛰️ SkyTracker Dashboard</b></summary>
<br/>

A containerized flight-tracking platform deployed on AWS EC2 with automated CI/CD and real-time monitoring.

| Category | Details |
|----------|---------|
| **Stack** | AWS EC2 · Docker Compose · React · Node.js · PostgreSQL |
| **Scale** | 64,000+ flight snapshots stored and processed |
| **Performance** | Automated container rebuilds & deployments on every push |
| **Security** | CloudWatch monitoring with SNS alerting |
| **Impact** | End-to-end observability for live flight telemetry |
| **Repository** | [View Repo](#) |

Deployed a containerized flight-tracking platform on AWS EC2 using Docker Compose with React, Node.js, and PostgreSQL services. Built a GitHub Actions CI/CD pipeline for automated deployments and container rebuilds on every push, with CloudWatch monitoring and SNS alerts collecting telemetry data continuously.

</details>

<details>
<summary><b>🚨 Flight Alert System</b></summary>
<br/>

A serverless aircraft monitoring system processing live telemetry on a 5-minute cycle.

| Category | Details |
|----------|---------|
| **Stack** | AWS Lambda · DynamoDB · SNS · EventBridge Scheduler · Terraform |
| **Scale** | Live telemetry processed every 5 minutes |
| **Performance** | Duplicate-alert suppression via DynamoDB TTL |
| **Security** | Least-privilege IAM access controls |
| **Impact** | Full infrastructure migrated to Terraform IaC |
| **Repository** | [View Repo](#) |

Architected a serverless aircraft monitoring system using EventBridge Scheduler, Lambda, DynamoDB, and SNS. Implemented duplicate-alert suppression with DynamoDB TTL and enforced least-privilege IAM policies. Migrated existing AWS infrastructure to Terraform by importing live resources, configuring remote state in S3, and reconciling drift across SNS, DynamoDB, IAM, and EventBridge.

</details>

<details>
<summary><b>📡 SkyTracker IoT</b></summary>
<br/>

An end-to-end IoT telemetry pipeline bridging embedded hardware with AWS cloud services.

| Category | Details |
|----------|---------|
| **Stack** | AWS Lambda · API Gateway · ESP32 · Embedded C++ |
| **Scale** | Real-time device-to-cloud telemetry |
| **Performance** | Live tracking data rendered on OLED display |
| **Security** | Secure device-to-cloud communication |
| **Impact** | Functional end-to-end IoT cloud pipeline |
| **Repository** | [View Repo](#) |

Designed and deployed an end-to-end IoT telemetry pipeline using AWS Lambda and API Gateway to process and display real-time tracking data on an OLED. Integrated embedded C++ firmware with AWS cloud services for secure device-to-cloud communication and live dashboard monitoring.

</details>

---

## 💼 Experience

### Independent Cloud & Backend Projects
**Self-Directed Engineering Work**
*2024 – Present*

Designed, built, and deployed multiple production-grade cloud applications spanning containerized backend systems, serverless architectures, and embedded IoT pipelines.

- Architected custom VPC environments with subnets, route tables, IGWs, and Security Groups
- Built CI/CD pipelines with GitHub Actions for automated deployment workflows
- Migrated live AWS infrastructure to Terraform with remote state management
- Implemented monitoring and alerting using CloudWatch and SNS

`AWS` `Docker` `Terraform` `CI/CD` `Node.js` `PostgreSQL`

---

## 🏆 Achievements

<div align="center">

| Recognition | Details |
|--------------|---------|
| 🕋 Hafiz-e-Quran | Completed full memorization of the Holy Quran in the Kingdom of Saudi Arabia |
| 🗣️ CEFR C1+ English | Achieved via Cambridge LinguaSkill assessment |

</div>

---

## 📜 Certifications

<div align="center">

**AWS**

![AWS](https://img.shields.io/badge/AWS-Certified-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

**Oracle**

![Oracle](https://img.shields.io/badge/Oracle-Certified-F80000?style=for-the-badge&logo=oracle&logoColor=white)

**NPTEL**

![NPTEL](https://img.shields.io/badge/NPTEL-Certified-8B5CF6?style=for-the-badge&logo=googlescholar&logoColor=white)

**Cisco**

![Cisco](https://img.shields.io/badge/Cisco-Certified-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)

</div>

---

## 💻 Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-6366F1?style=for-the-badge&logo=leetcode&logoColor=white)](#)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-7C3AED?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](#)
[![HackerRank](https://img.shields.io/badge/HackerRank-4C1D95?style=for-the-badge&logo=hackerrank&logoColor=white)](#)
[![CodeChef](https://img.shields.io/badge/CodeChef-5B21B6?style=for-the-badge&logo=codechef&logoColor=white)](#)

</div>

---

## 📊 GitHub Analytics

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=mirzatalhabaig&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=8B5CF6&text_color=C9D1D9)

![Streak](https://github-readme-streak-stats.herokuapp.com/?user=mirzatalhabaig&theme=tokyonight&hide_border=true&background=0D1117&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mirzatalhabaig&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9)

</div>

---

## 🏅 GitHub Trophies

<div align="center">

![Trophies](https://github-profile-trophy.vercel.app/?username=mirzatalhabaig&theme=algolia&no-frame=true&row=1&column=7&margin-w=10)

</div>

---

## 📈 Contribution Activity

<div align="center">

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=mirzatalhabaig&theme=react-dark&hide_border=true&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=ffffff)

</div>

---

## 🐍 Contribution Snake

<div align="center">

![Snake animation](https://raw.githubusercontent.com/mirzatalhabaig/mirzatalhabaig/output/github-contribution-grid-snake.svg)

</div>

---

## 🎯 Current Focus

```yaml
Learning:
  - Advanced Distributed Systems
  - AI/ML Model Deployment on AWS
  - Kubernetes & Container Orchestration

Building:
  - Scalable Serverless Cloud Applications
  - End-to-End IoT to Cloud Pipelines

Exploring:
  - Infrastructure as Code at Scale (Terraform)
  - AI-Powered Backend Automation

Open To:
  - Internships & Full-Time Opportunities
  - Open Source Collaboration
  - Research in Cloud & AI Systems
```

---

## 📬 Connect With Me

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-mirzatalhab163%40gmail.com-6366F1?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mirzatalhab163@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-5B21B6?style=for-the-badge&logo=github&logoColor=white)](#)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white)](#)

</div>

---

<div align="center">

*"Building secure, scalable systems — one deployment at a time."*

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer)

</div>
