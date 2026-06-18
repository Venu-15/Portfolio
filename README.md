# Hi, I'm Venugopal 👋

**Full Stack Java Developer** who builds backend systems that actually hold up under load — secure, idempotent, and production-minded, not just CRUD demos.

I work primarily in **Spring Boot, Hibernate/JPA, and MySQL**, and I like projects with real engineering constraints: concurrency, encryption, deduplication, fault tolerance. Two of my recent builds — a banking system and an offline-mesh UPI payment network — reflect that.

---

### About Me

🔭 I'm currently working on backend systems with real engineering constraints — a Spring Boot–based offline payment network using mesh routing and hybrid RSA/AES-256-GCM encryption, and a full-stack banking system handling 1,000+ simulated transactions with normalized MySQL schemas

🤝 I'm looking to collaborate on open-source projects involving Spring Boot, REST API design, relational database architecture, or secure transaction systems

🌱 I'm looking for help with production-scale backend practices — load balancing, containerization, and cloud deployment on AWS/Azure

🌱 I'm currently learning PostgreSQL at a deeper level, Docker, and system design fundamentals for distributed backends

💬 Ask me about Spring Boot, Hibernate/JPA, JDBC, RESTful API design, MySQL/PostgreSQL schema design, or how I implemented idempotent settlement and replay-attack protection in a payments system

⚡ Fun fact: I built a UPI-style payment system that settles transactions over a Bluetooth-style mesh network with zero internet connectivity required

---

### ⚡ Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

### 🚀 Featured Projects

**[UPI Offline Mesh Payments](https://github.com/Venu-15/upi-offline-mesh-payments)** — [Live Demo](https://upi-offline-mesh-payments.onrender.com)
A Spring Boot system simulating offline UPI-style payments routed through a Bluetooth-style mesh network — transactions keep flowing with zero internet until a bridge device reconnects.
- Hybrid encryption: RSA-2048/OAEP for key exchange, AES-256-GCM for payload security
- Idempotent settlement engine using SHA-256 hashing + atomic `ConcurrentHashMap` ops to stop double-settlement when packets arrive via multiple mesh paths
- Replay-attack protection via timestamped, UUID-nonce REST endpoints, with a live dashboard for multi-hop packet gossip

**Online Banking System**
A full-stack banking app in Java, JDBC, and MySQL handling 1,000+ simulated transactions.
- Deposit, withdrawal, balance inquiry, and transaction history with strict exception handling and input validation
- Normalized relational schema across 5+ tables for accounts, transactions, and audit logs
- Built on OOP fundamentals (encapsulation, abstraction, interfaces) inside an MVC architecture

---

### 📜 Certifications
- Essential SQL Skills for Data Beginners — Analytics Vidhya
- JavaScript Bootcamp — LetsUpgrade
- ChatGPT as Your AI Assistant — Analytics Vidhya

---

### 📫 Let's connect
[LinkedIn](https://www.linkedin.com/in/venugopal-lodda/) · loddavenugopal@gmail.com · Thane, Maharashtra, India
