<div align="center">

<!-- Animated Header Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,50:2563eb,100:0ea5e9&height=200&section=header&text=Ankita%20Dhagate&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Java%20%7C%20Spring%20Boot%20%7C%20Full%20Stack%20Engineer&descAlignY=58&descSize=18&animation=fadeIn"/>

<!-- Typing Animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2563EB&center=true&vCenter=true&width=700&lines=Building+Secure+FinTech+Backends+%F0%9F%94%90;Java+21+%7C+Spring+Boot+%7C+MySQL+Developer;AIML+Final+Year+%40+DKTE+Institute;Open+to+Backend+%26+Full+Stack+Roles+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

<!-- Badges Row -->
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://ankitadhagate.github.io/Portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ankita-dhagate1525/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnkitaDhagate)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhagateankita@gmail.com)

</div>

---

## 👩‍💻 About Me

```java
public class Ankita extends Developer {

    String  location  = "Ichalkaranji, Maharashtra, India 🇮🇳";
    String  degree    = "B.Tech AIML @ DKTE Society's T&E Institute (2022–2026)";
    float   cgpa      = 7.85f;
    String  focus     = "Backend Engineering · Spring Boot · FinTech Systems";

    String[] currentlyDoing = {
        "🏦 Building production-grade banking platforms",
        "☕ Deep-diving into Java 21 Virtual Threads & SERIALIZABLE isolation",
        "📈 Exploring real-time data systems with Recharts & REST APIs",
        "🎯 Targeting Backend / Full Stack Developer roles"
    };

    String lifePhilosophy = "Ship working software. Write clean code. Never stop learning.";
}
```

---

## 🛠️ Tech Stack

<div align="center">

### Languages & Core
![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Backend & Frameworks
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![JDBC](https://img.shields.io/badge/JDBC-007396?style=for-the-badge&logo=java&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

### Databases
![MySQL](https://img.shields.io/badge/MySQL_8-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Oracle SQL](https://img.shields.io/badge/Oracle_SQL-F80000?style=for-the-badge&logo=oracle&logoColor=white)

### Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-0078D4?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse-ide&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)

</div>

---

## 🚀 Featured Projects

<div align="center">

### 💎 VaultCore Financial — Secure Digital Banking & Trading Core
**`Production-Grade FinTech Platform`**

</div>

> A full-stack banking platform engineered with enterprise-level backend patterns — not a tutorial project, but a system built with real financial-grade concerns: ACID compliance, concurrent transaction safety, fraud prevention, and an immutable audit trail.

```
╔════════════════════════════════════════════════════════════════╗
║  React 19  →  JWT Auth Filter  →  Spring Boot  →  MySQL 8      ║
║                    ↓                                           ║
║         SERIALIZABLE Isolation + PESSIMISTIC_WRITE locks       ║
║                    ↓                                           ║
║     Double-Entry Ledger (immutable, trigger-protected)         ║
║                    ↓                                           ║
║     Fraud Detection → OTP 2FA → AspectJ Audit Logging          ║
╚════════════════════════════════════════════════════════════════╝
```

**What makes this production-grade:**

| Engineering Decision | Why It Matters |
|---|---|
| `@Transactional(isolation = SERIALIZABLE)` | Prevents phantom reads in concurrent transfers |
| Pessimistic row-level locks (SELECT FOR UPDATE) | 100 concurrent threads cannot corrupt balances |
| Double-entry ledger with DB-level immutability triggers | Every ₹ in = every ₹ out. No silent corruption |
| Fraud threshold → SecureRandom OTP → 5-min expiry | High-value transfers blocked until 2FA verified |
| AspectJ `@Around` AOP audit logging (async) | Full audit trail without polluting business logic |
| Java 21 Virtual Threads | Balance reads scale to thousands of concurrent requests |

**Tech Stack:**
`Java 21` · `Spring Boot 3` · `Spring Security` · `JWT (JJWT 0.11.5)` · `MySQL 8` · `HikariCP` · `Spring AOP / AspectJ` · `React 19` · `Recharts` · `Bootstrap 5` · `Axios`

---

<div align="center">

### 🏥 MedCare — Hospital Management System
**`Java Full Stack Application`**

</div>

> A comprehensive hospital operations platform covering the full patient lifecycle — registration, appointments, and medical records — with a normalized database schema built for performance.

**Key Engineering Highlights:**
- Normalized relational schema with foreign key constraints and indexing for fast query execution
- RESTful APIs via Spring MVC handling patient CRUD, appointment scheduling, and record retrieval
- Database performance tuning through strategic indexing and optimized JOIN queries
- Responsive frontend built with HTML5, CSS3, and JavaScript

**Tech Stack:** `Java` · `Spring Boot` · `Spring MVC` · `MySQL` · `JDBC` · `HTML5/CSS3/JavaScript`

---

## 💼 Experience

<details>
<summary><b>☕ Java Development Intern — Cognifyz Technologies</b> &nbsp;|&nbsp; Dec 2024 – Jan 2025</summary>

<br/>

- Developed Java-based backend modules leveraging **OOP principles** and **Collections framework**
- Implemented **JDBC database connectivity** and performed optimized CRUD operations with SQL
- Debugged and optimized Java logic alongside SQL query performance
- Improved database interaction efficiency through structured query execution and systematic testing

</details>

<details>
<summary><b>⚡ Salesforce Developer Virtual Intern — Salesforce</b> &nbsp;|&nbsp; Nov 2024 – Jan 2025</summary>

<br/>

- Built **automation workflows** using **Apex** and **Lightning Web Components (LWC)**
- Assisted in security configuration and **CRM module customization**
- Gained hands-on exposure to enterprise-grade cloud platform architecture

</details>

<details>
<summary><b>🤖 Generative AI Virtual Internship — AICTE</b> &nbsp;|&nbsp; Oct 2024 – Dec 2024</summary>

<br/>

- Explored **AI-based recommendation systems** and intelligent automation concepts
- Applied generative AI fundamentals to practical problem-solving scenarios

</details>

---

## 🏅 Certifications & Achievements

<div align="center">

| Platform | Achievement |
|:---:|:---|
| **HackerRank** | ⭐⭐⭐⭐⭐ 5 Stars — Java & SQL |
| **NPTEL** | Database Management Systems (8 Weeks) · Java Programming (12 Weeks) |
| **IIT Bombay Spoken Tutorial** | Java · Python · JavaScript · PHP & MySQL |
| **Infosys Springboard** | Java & SQL Certifications |
| **Oracle** | Oracle SQL Certification |
| **Great Learning** | Backend Development Courses |
| **Vodafone Idea Foundation** | Java & SQL |

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=AnkitaDhagate&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=2563eb&icon_color=0ea5e9&text_color=c9d1d9"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AnkitaDhagate&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=2563eb&text_color=c9d1d9"/>

</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AnkitaDhagate&theme=tokyonight&hide_border=true&background=0d1117&stroke=2563eb&ring=0ea5e9&fire=f97316&currStreakLabel=2563eb" />
</div>

---

## 🎓 Education

```
┌─────────────────────────────────────────────────────────────────
│  🎓  B.Tech — Artificial Intelligence & Machine Learning       
│      DKTE Society's Textile and Engineering Institute          
│      2022 – 2026  |  CGPA: 7.85                               
├─────────────────────────────────────────────────────────────────
│  📘  HSC (Science) — Lord Jiveshwar School & Junior College     
│      2022  |  80%                                               
├─────────────────────────────────────────────────────────────────
│  📗  SSC — Vyankatrao High School & Junior College              
│      2020  |  95.60%  🏆                                        
└─────────────────────────────────────────────────────────────────
```

---

## 🌐 Languages

`English` · `Hindi` · `Marathi` · `Kannada`

---

<div align="center">

### 📬 Let's Connect

**Open to Backend Developer / Full Stack Developer / Java Developer roles**

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-Visit_Now-1e3a8a?style=for-the-badge)](https://ankitadhagate.github.io/Portfolio/)
[![Email](https://img.shields.io/badge/📧_Email-dhagateankita@gmail.com-EA4335?style=for-the-badge)](mailto:dhagateankita@gmail.com)
[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-Connect-0077B5?style=for-the-badge)](https://www.linkedin.com/in/ankita-dhagate1525/)
[![Phone](https://img.shields.io/badge/📞_Phone-7030081664-25D366?style=for-the-badge)]()

<br/>

<!-- Profile Views Counter -->
![Profile Views](https://komarev.com/ghpvc/?username=AnkitaDhagate&color=2563eb&style=for-the-badge&label=PROFILE+VIEWS)

<br/>

<!-- Footer Wave -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,50:2563eb,100:1e3a8a&height=100&section=footer"/>

</div>
