<h1 align="center">Hi, I'm Amanda Siriwardane 👋</h1>
<h3 align="center">Computer Engineering Undergraduate · Software Engineering Intern @ WSO2 · Identity & Access Management</h3>

---

## About Me
Computer Engineering undergraduate at the University of Peradeniya, currently a Software Engineering Intern in the IAM team at **WSO2**. I work on backend systems for a security-standards product, and I like building secure, standards-based systems and clean dashboards.

- Building **SSF / CAEP event delivery** for WSO2 Identity Server (Java, OSGi, OAuth2, JWS)
- Learning more about **identity standards, backend architecture & cloud-native development**
- Exploring **Claude / MCP agent tooling** for developer automation
- Open to collaborating on **backend, IAM and full-stack** projects
- Outside code: illustration, UI/UX design, badminton

---

## Contact
- Colombo, Sri Lanka · University of Peradeniya
- [amandasiriwardane01@gmail.com](mailto:amandasiriwardane01@gmail.com)
- [linkedin.com/in/amanda-siriwardane](https://linkedin.com/in/amanda-siriwardane)

---

## Tech Stack

### Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-00618A?style=for-the-badge)

### Backend & Frontend
![OSGi](https://img.shields.io/badge/OSGi-FF6600?style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Redux](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)

### Identity & Access Management
![OAuth2](https://img.shields.io/badge/OAuth2-3E4348?style=for-the-badge)
![OIDC](https://img.shields.io/badge/OIDC-F78C40?style=for-the-badge)
![JWT](https://img.shields.io/badge/JWT%2FJWS-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![WSO2](https://img.shields.io/badge/WSO2_IS_%26_Asgardeo-FF7300?style=for-the-badge)
![SSF](https://img.shields.io/badge/SSF_%2F_CAEP-0A66C2?style=for-the-badge)

### Databases, Cloud & Tools
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---


---

# Featured Projects

## SSF/CAEP Event Delivery for WSO2 Identity Server
_Internship Project · 2026 – Present_
`Java` `OSGi` `REST API` `OAuth2` `JWS/JWT`

A new connector that implements the **SSF Stream Management REST API**, so WSO2 Identity Server can deliver CAEP security events to external receivers over an OAuth2-protected transport.
- Service layer delegates CRUD to the existing `WebhookManagementService`, so there is no duplicated persistence logic.
- Redesigned event-publisher resolution from a single non-deterministic lookup to a **per-event-profile map**. The new JWS-signing SSF publisher now runs alongside the existing HTTP publisher with zero regression.

Work-in-progress forks: [identity-shared-signals-framework](https://github.com/amandasiriwardane/identity-shared-signals-framework-fork) · [carbon-identity-framework](https://github.com/amandasiriwardane/carbon-identity-framework-fork) · [identity-event-publishers](https://github.com/amandasiriwardane/identity-event-publishers-fork) · [identity-webhook-event-handlers](https://github.com/amandasiriwardane/identity-webhook-event-handlers-fork)

---

## Automated Pre-Migration Assessments for WSO2 Identity Server
_Internship Project · May – Jul 2026_
`SQL` `Docker` `MySQL` `Claude + MCP`

- Replaced manual diagnostic calls with SQL scripts that surface feature usage before a migration.
- Wrote and live-verified query sets across major IS upgrades (**5.10.0 → 7.0.0**) on Docker-hosted instances.
- Built a Claude Agent Skill that generates a dialect-aware SQL script per version pair, with traceability and risk flags.

---

## Paws & Homes: Pet Adoption Portal
_Internship Onboarding Project · May 2026_
`React` `Node.js` `Express` `PostgreSQL` `WSO2 Asgardeo` `WSO2 Choreo`

Full-stack SaaS app with **OIDC authentication and JWT validation** via Asgardeo, three user roles with RBAC-secured endpoints, deployed with Choreo CI/CD and API management.

---

## Multimodal Phenotyping in Knee Osteoarthritis Using VLMs
_Research · Sep 2025 – Mar 2026_
`Python` `PyTorch` `BioMedCLIP` `HDBSCAN` `Grad-CAM`

Unsupervised framework that aligns radiographs with clinical text using BioMedCLIP, clusters patients with HDBSCAN to find latent phenotypes beyond standard severity grades, and validates them with Grad-CAM and textual explanations.

[Repository](https://github.com/amandasiriwardane/e20378-4yp-VLM-Guided-Phenotyping-of-KOA)

---

## Safe Plus: Smart Safety Helmet
_3rd Year Group Project · Nov 2024 – Jul 2025_
`ESP32` `AWS IoT Core` `MERN` `JWT` `2FA`

Real-time hazard detection pipeline: **ESP32 → AWS IoT → Backend → Dashboard/Mobile**.
- Led dashboard development: JWT + bcrypt + 2FA auth, worker management, live sensor visualization.
- Handled deployment: Netlify (frontend), Railway (backend), custom domain.
- Showcased at **EngEx 2025** · Finalist, **IEEE Sri Lanka FYP Arena 2025**

[Repository](https://github.com/amandasiriwardane/e20-3yp-SafePlus)

---

## MediGo: Pharmacy Delivery Platform
_Individual Project · Aug – Dec 2025_
`MERN` `Redux Toolkit` `Material-UI` `Cloudinary`

Multi-role platform (3 user types) with 15+ REST endpoints, role-based auth, and Cloudinary-backed product management. Deployed on Vercel and Render.

[Repository](https://github.com/amandasiriwardane/MediGo--Pharmacy-App)

---

## Production Monitoring Dashboard
_2nd Year Group Project · Apr – Oct 2024_
`React` `Python` `MongoDB`

Real-time monitoring for 24 plastic toy machines with live visualization, emergency alerts and historical production records.

---

## More Projects
- **[ai-code-reviewer](https://github.com/amandasiriwardane/ai-code-reviewer)**: LLM-powered tool that analyzes code and suggests improvements
- **[Room Temperature Anomaly Detection](https://github.com/amandasiriwardane/e20-co326-Room-Temperature-Anomaly-Detection)**: ESP32-S3 + DHT22 + MQTT + Python

---

## Awards & Highlights
- Super Contributor, **Hacktoberfest 2025**
- Finalist, **IEEE Sri Lanka FYP Arena 2025**
- Finalist, Pre-Coders 2024 (80+ teams) · Participant, Coders v11.0 (300+ teams)
- Half Color Award, Badminton, University of Peradeniya
- Selected as 1 of 5 Sri Lankan representatives, 13th Shanghai International Youth Interactive Friendship Camp (2017)

## Leadership
- **Chairperson**, IEEE Computer Society Student Chapter, UoP (Nov 2025 – Present); Design Team Lead (Aug 2024 – Nov 2025)
- **Brand Manager & Marketing Specialist**, AIESEC in UoP
- **Undergraduate Teaching Assistant**, CO1810 (Python/C) and CO2030 (Java), UoP
- Member, Rotaract Club of UoP
