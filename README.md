<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=280&color=0:0F172A,40:0C4A6E,80:0369A1,100:0EA5E9&text=Mirza%20Talha%20Baig&fontColor=f0f9ff&fontSize=48&animation=fadeIn&fontAlignY=40&desc=Cloud%20%E2%80%A2%20DevOps%20%E2%80%A2%20AWS&descAlignY=60&descSize=18&descColor=7DD3FC" />

</div>

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mirza%20Talha%20Baig-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mirzatalhabaig163)
[![Gmail](https://img.shields.io/badge/Gmail-mirzatalhab163%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mirzatalhab163@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-mirzatalha.vercel.app-000000?style=flat-square&logo=vercel&logoColor=white)](https://mirzatalha.vercel.app/)
[![Profile Views](https://komarev.com/ghpvc/?username=mirzaatalhaa&style=flat-square&color=0EA5E9&label=Profile+Views)](https://github.com/mirzaatalhaa)

</div>


---

## `whoami`

```yaml
name:     Mirza Talha Baig
location: Kerala, India
degree:   B.Tech — Computer Science & Engineering

focus:
  - AWS Cloud Architecture & Solutions Design
  - Infrastructure as Code with Terraform
  - Containerization & Orchestration (Docker → Kubernetes)
  - CI/CD Pipelines & Automation
  - Backend Systems & REST APIs
  - Linux Administration & Observability

open_to:
  - Cloud Engineering Internships
  - DevOps Roles
  - Backend Development Positions
  - Open Source Contributions
```

---

## ⚙️ Tech Stack

**Languages**

<p>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" height="30" alt="C++"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="30" alt="Python"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" height="30" alt="JavaScript"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" height="30" alt="SQL"/>
<img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" height="30" alt="Bash"/>
</p>

**Cloud & Infrastructure**

<p>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900" height="30" alt="AWS"/>
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" height="30" alt="Terraform"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" height="30" alt="Docker"/>
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" height="30" alt="GitHub Actions"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" height="30" alt="Linux"/>
<img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" height="30" alt="Nginx"/>
</p>

**Backend & Databases**

<p>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" height="30" alt="Node.js"/>
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" height="30" alt="Express"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" height="30" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white" height="30" alt="DynamoDB"/>
</p>

**Frontend**

<p>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" height="30" alt="React"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" height="30" alt="HTML5"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" height="30" alt="CSS3"/>
</p>



---

## 🚀 Featured Projects

<details>
<summary><b>SkyTracker Dashboard — Full-Stack Flight Cloud-Native Tracking & Analytics Platform</b></summary>
<br/>

> Production-style flight tracking platform with real-time analytics, containerized and deployed on AWS. → [View Repo](https://github.com/mirzaatalhaa/SkyTracker-Dashboard.git)

**Stack:** React · Node.js · PostgreSQL · Docker · AWS EC2 · CloudWatch · GitHub Actions

**What I built:**
- Multi-service Dockerized architecture orchestrated with Docker Compose
- End-to-end CI/CD pipeline with GitHub Actions for automated deployments to EC2
- PostgreSQL backend storing **64,000+ flight snapshots** with analytical queries
- CloudWatch dashboards and alerts for uptime monitoring

**What I learned:** End-to-end ownership of a production deployment — from containerization to observability to zero-intervention rolling updates.

</details>

<details>
<summary><b>FlightWatch — Full-Stack Cloud-Native AvGeek's Logging Platform</b></summary>
<br/>

> A production-grade web app where avgeeks can log and analyze aircraft sightings — real domain, real users, real AWS infrastructure. → [View Repo](https://github.com/mirzaatalhaa/FlightWatch.git)

**Stack:** React + Vite · Node.js · Express · PostgreSQL · Docker · Terraform · AWS (EC2 · RDS · S3 · CloudFront · ECR · Route 53 · ACM) · GitHub Actions · Nginx · JWT

**What I built:**
- React/Vite frontend on S3, globally distributed via CloudFront with cache invalidation on every deploy
- Dockerized Express backend on EC2 behind Nginx with Let's Encrypt SSL on a custom domain
- PostgreSQL on RDS in a **private subnet** — reachable only from the backend EC2 via security group rules
- JWT authentication with bcryptjs password hashing on all protected routes
- Two independent GitHub Actions pipelines — push to `main` triggers build → ECR push → EC2 redeploy automatically
- Full Terraform IaC: VPC, subnets, Route 53, CloudFront, RDS, EC2 — no manual console clicks

**What I learned:** What it actually means to run a production system — DNS, SSL provisioning, RDS SSL requirements, and debugging `bcrypt` failures across OS boundaries in Docker.

</details>

<details>
<summary><b>FlightWatch Ground Control — Internal Operations Console</b></summary>
<br/>

> Python-based command-line operations dashboard for monitoring the health, analytics, and activity of the FlightWatch platform in real time. → [View Repo](https://github.com/mirzaatalhaa/flightwatch-control.git)

**Stack:** Python · REST APIs · JWT · Node.js · Express · PostgreSQL · Docker · Nginx · AWS EC2 · Amazon RDS · Terraform · GitHub Actions

**What I built:**
- Production health monitoring and database connectivity verification against live infrastructure
- JWT-authenticated operator login with secure token-based API communication
- Live analytics dashboard covering aircraft, airline, and airport statistics
- System and network diagnostics for the operator environment

**What I learned:** How operational tooling complements user-facing products — building the visibility layer that makes running a production platform sustainable.

</details>

<details>
<summary><b>Flight Alert System — Serverless AWS Event-Driven Architecture</b></summary>
<br/>

> Fully serverless aircraft monitoring system that detects and alerts on specific flight activity — entirely infrastructure-as-code. → [View Repo](https://github.com/mirzaatalhaa/Flight-Alert-System.git)

**Stack:** AWS Lambda · DynamoDB · EventBridge · SNS · Terraform · IAM

**What I built:**
- Event-driven pipeline triggered every 5 minutes via EventBridge Scheduler
- DynamoDB state tracking with duplicate alert suppression
- SNS-based notification delivery for matching flight events
- Complete Terraform infrastructure — reproducible from `terraform apply`
- IAM least-privilege roles for every Lambda function

**What I learned:** Designing for idempotency and cost-efficiency in serverless systems; treating infrastructure as versioned code.

</details>

<details>
<summary><b>SkyTracker IoT — ESP32 Cloud-Connected Flight Tracker</b></summary>
<br/>

> Embedded device that fetches live aircraft telemetry from AWS and displays it on an OLED screen in real time. → [View Repo](https://github.com/mirzaatalhaa/SkyTracker-IoT.git)

**Stack:** ESP32 (C++) · AWS Lambda · API Gateway · OLED Display

**What I built:**
- Device-to-cloud communication over HTTPS from an ESP32 microcontroller
- AWS Lambda + API Gateway endpoint serving live flight telemetry
- Real-time OLED visualization of aircraft position and altitude data

**What I learned:** The full IoT loop — hardware constraints and embedded C++ through to serverless APIs and latency tuning.

</details>

<details>
<summary><b>AWS Custom VPC — Networking Architecture from Scratch</b></summary>
<br/>

> Designed and deployed a complete AWS network environment — custom CIDR, public/private subnets, bastion host access. → [View Repo](https://github.com/mirzaatalhaa/AWS-Custom-VPC.git)

**Stack:** AWS VPC · Subnets · Route Tables · Security Groups · Internet Gateway · Bastion Host

**What I built:**
- Custom CIDR block with public and private subnet separation
- Routing design with Internet Gateway and route table associations
- Bastion host pattern for secure SSH access to private resources
- Security group rules enforcing least-privilege network access

**What I learned:** How AWS networking primitives compose into real architectures — and why getting routing right matters more than the topology diagram.

</details>



---
 
## 📊 GitHub Stats

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=mirzaatalhaa&show_icons=true&theme=algolia&hide_border=true&include_all_commits=true&count_private=true"/>
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mirzaatalhaa&layout=compact&theme=algolia&hide_border=true&langs_count=8"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=mirzaatalhaa&theme=algolia&hide_border=true"/>

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=mirzaatalhaa&theme=github-dark&hide_border=true&area=true&area_color=0EA5E9&color=7DD3FC&line=0369A1&point=0EA5E9"/>

</div>

---

## 📍 What's Next

```yaml
currently_learning:
  - AWS Solutions Architect Associate
  - Kubernetes (CKA path)
  - Advanced Terraform — modules & remote state

currently_building:
  - Cloud-native applications on AWS
  - More infrastructure automation projects

exploring:
  - Observability (Prometheus, Grafana)
  - Platform Engineering patterns
  - Distributed systems design
```

---
<br/>
<div align="center">

[![LinkedIn](https://img.shields.io/badge/Let's%20connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mirzatalhabaig163)
[![Email](https://img.shields.io/badge/Reach%20out-Gmail-EA4335?style=for-the-badge&logo=gmail)](mailto:mirzatalhab163@gmail.com)
[![GitHub](https://img.shields.io/badge/Follow-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/mirzaatalhaa)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:0F172A,40:0C4A6E,80:0369A1,100:0EA5E9"/>

</div>
