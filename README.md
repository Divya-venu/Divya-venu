<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=2,12,22&height=200&section=header&text=Divya%20Shree%20GV&fontSize=48&fontColor=ffffff&fontAlignY=40&desc=Backend%20Engineer%20%7C%20Java%20%2F%20Spring%20Boot%20%2F%20Microservices&descAlignY=60&descSize=18&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=14&pause=1200&color=14B8A6&center=true&vCenter=true&width=750&lines=Java+%7C+Spring+Boot+%7C+Spring+Security+%7C+Microservices;REST+APIs+%7C+Kafka+%7C+RabbitMQ+%7C+JWT+%2F+OAuth2;MySQL+%7C+Oracle+SQL+%7C+MongoDB+%7C+AWS+%7C+Docker)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](#)
[![Gmail](https://img.shields.io/badge/gvdivyashree%40gmail.com-14B8A6?style=flat-square&logo=gmail&logoColor=white)](mailto:gvdivyashree@gmail.com)
[![Location](https://img.shields.io/badge/Bangalore%2C_India-2C3E50?style=flat-square&logo=googlemaps&logoColor=white)](#)

</div>

---

### 🧭 About

```
I build backend systems that don't fall over.

Currently:  Software Engineer @ Aroha Technologies (Jun 2025 – Present)
Focus:      Spring Boot microservices · secure REST APIs · event-driven architecture
Patterns:   Singleton · Factory · Builder · Strategy · Observer
Education:  B.E. Computer Science, East Point College of Engg. & Tech. — CGPA 8.9
```

I design and ship production microservices — secure, observable, and built to scale — using Spring Boot, Spring Security, JWT/OAuth2, and message-driven patterns with Kafka and RabbitMQ.

---

### 🧱 Service Architecture I Work In

```
┌─────────────┐     ┌──────────────┐     ┌────────────────────┐
│   Clients   │────▶│  API Gateway │────▶│  Eureka Discovery   │
└─────────────┘     └──────┬───────┘     └────────────────────┘
                            │
        ┌───────────────────┼───────────────────┐
        ▼                   ▼                   ▼
 ┌───────────────┐  ┌───────────────┐  ┌───────────────┐
 │  Auth Service   │  │  Order Service  │  │ Notification Svc │
 │  JWT · OAuth2   │  │  Spring Batch   │  │  RabbitMQ / Kafka│
 └────────┬───────┘  └────────┬───────┘  └────────┬───────┘
          ▼                    ▼                    ▼
   ┌────────────┐      ┌────────────┐       ┌────────────┐
   │   MySQL    │      │  Oracle SQL │       │  MongoDB    │
   └────────────┘      └────────────┘       └────────────┘
```

---

### 🛠️ Tech Stack

**Languages**
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

**Frameworks & Core**
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![Spring MVC](https://img.shields.io/badge/Spring_MVC-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**Messaging & Async**
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

**Databases**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_SQL-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Cloud & Tools**
![AWS](https://img.shields.io/badge/AWS_EC2%2FRDS%2FS3-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

### 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🎓 Placement Management System
Cloud-native microservices platform for companies to post jobs and track placements.

- User Management, Property Listing, Media & Notification services on **Spring Boot**
- **RabbitMQ**-driven async processing for notifications & data sync
- Secured with **Spring Security**, validated via **Swagger**
- Built for scale — responsive APIs designed for high user volume

`Spring Boot` `Spring Data JPA` `RabbitMQ` `MySQL` `AWS`

</td>
<td width="50%" valign="top">

#### 📦 Trade Axis — B2B Order Management
Microservices platform for bulk B2B ordering with automated workflows.

- Auth, catalogue, inventory, orders & billing as independent services
- **Spring Batch + Scheduler** for approvals, low-stock alerts, invoicing
- Email/WhatsApp notification integration
- Performance tuning via pagination, indexing & caching

`Spring MVC` `Spring Batch` `Spring Scheduler` `MySQL`

</td>
</tr>
</table>

---

### 💼 Experience Timeline

```
2025 ── Present   Software Engineer (Java/Spring Boot) @ Aroha Technologies
                  ├─ Spring Boot microservices — HA, scalable, optimized
                  ├─ JWT + OAuth2 secured REST APIs, RBAC enforcement
                  ├─ MySQL & Oracle SQL — indexing, query optimization
                  └─ AWS (EC2/RDS/S3) deployment + Docker packaging

2020 ── 2024      B.E. Computer Science & Engineering
                  East Point College of Engineering & Technology — CGPA 8.9
```

---

### 📊 GitHub Stats

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=14B8A6&icon_color=14B8A6&text_color=c9d1d9"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=14B8A6&text_color=c9d1d9"/>
</div>

---

<div align="center">

### 📬 Let's Connect

[![LinkedIn](https://img.shields.io/badge/Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email_Me-14B8A6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gvdivyashree@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=2,12,22&height=100&section=footer" width="100%"/>

</div>
