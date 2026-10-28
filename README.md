# Hi, I'm Yakup Çeri 👋

[🇹🇷 Türkçe](./README.tr.md) · 🇬🇧 English

🟢 **Open to junior backend roles** · İzmir, İstanbul or remote · Java / Spring Boot · Python / FastAPI

Computer Programming graduate of İzmir University of Economics. I build RESTful backend services in the Java, Spring Boot, Hibernate and SQL ecosystem, with a layered architecture, dynamic filtering and solid relational data models. I also build full products with Python, FastAPI and PostgreSQL.

<p align="left">
  <a href="./YAKUP_CERI_CV_EN.pdf" target="_blank">
    <img src="https://img.shields.io/badge/📄_View_my_CV-0A66C2?style=for-the-badge&logoColor=white" alt="Yakup Çeri CV" />
  </a>
  <a href="./YAKUP_CERI_CV.pdf" target="_blank">
    <img src="https://img.shields.io/badge/📄_CV_(Türkçe)-555555?style=for-the-badge&logoColor=white" alt="Yakup Çeri CV (Türkçe)" />
  </a>
</p>

---

### ⭐ Featured project: CineVocab

<a href="https://github.com/yakupceri/cinevocab-app"><img src="https://raw.githubusercontent.com/yakupceri/cinevocab-app/main/docs/store/promo-small-440x280.png" align="right" width="260" alt="CineVocab"></a>

**A Chrome extension plus a web app that translates Prime Video, YouTube and Udemy subtitles word by word.** The words are saved to your account, where you can practise them in quick quizzes or race your friends in live duels.

- The extension is on the Chrome Web Store and the site runs on Railway.
- **Python, FastAPI, PostgreSQL, WebSocket** (real-time duel rooms), Chrome Manifest V3.
- Accounts, subtitle language detection, a 6-language interface and an admin panel.

[🔗 GitHub](https://github.com/yakupceri/cinevocab-app) · [🧩 Chrome Web Store](https://chromewebstore.google.com/detail/glhogfbfbjifiihgffjpjgijkjplebkl) · [🌐 Live site](https://cinevocab.up.railway.app)
<br clear="right"/>

---

### ⭐ Featured project: Computer Sales System

<a href="https://github.com/yakupceri/computer-sales-system-spring-boot"><img src="https://raw.githubusercontent.com/yakupceri/computer-sales-system-spring-boot/main/docs/screenshots/magaza-urunler.png" align="right" width="260" alt="Computer Sales System"></a>

**A Spring Boot REST API for a computer store, with a storefront and an admin panel on top.**

- **Dynamic filtering:** one endpoint turns a JSON filter into SQL with JPA Specification, across 10 resources.
- **Safe orders:** stock check, deduction and totals in one transaction, with row locks against overselling.
- **Tested:** JUnit and MockMvc tests run on every push with GitHub Actions. One-command H2 demo mode.

[🔗 GitHub](https://github.com/yakupceri/computer-sales-system-spring-boot) · [▶️ Run the demo](https://github.com/yakupceri/computer-sales-system-spring-boot#-hızlı-başlangıç)
<br clear="right"/>

---

### 🛠️ Skills & technologies

**Backend**  
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" /> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" /> <img src="https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white" alt="Hibernate" /> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" /> <img src="https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="WebSocket" />

**Data**  
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" /> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" /> <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" /> <img src="https://img.shields.io/badge/H2-1021FF?style=flat-square" alt="H2" />

**Tools & testing**  
<img src="https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white" alt="JUnit 5" /> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" /> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" /> <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" alt="Postman" /> <img src="https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white" alt="Railway" /> <img src="https://img.shields.io/badge/Chrome_MV3-4285F4?style=flat-square&logo=googlechrome&logoColor=white" alt="Chrome MV3" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />

Also: JPA Specification, DTOs, transactions (ACID), normalization (3NF), MockMvc, RESTful API design.

---

### 💼 Experience

- **Onur Enerji** — *Backend Developer (Intern)* `(Jul 2025 – Aug 2025)`
  - Developed database operations with Spring Boot and Hibernate (JPA).
  - Designed a dynamic filtering layer that builds SQL queries automatically from user criteria (JPA Specification).
  - Applied a multi-layered architecture of Entity, Controller, Repository, Service, DTO and Specification layers.

- **Eldor Corporation** — *IT Staff (Intern)* `(Jan 2025 – Feb 2025)`
  - Ran SQL queries and supported data validation processes.
  - Handled basic network configuration and hardware fault diagnosis and troubleshooting.

---

### 📌 Projects

- 🎬 **[CineVocab: Chrome extension + web app](https://github.com/yakupceri/cinevocab-app)** (Python / FastAPI)
  - A Chrome extension (Manifest V3: content script, service worker) that translates Prime Video, YouTube and Udemy subtitles word by word, plus a web app that turns the saved words into practice. Published on the Chrome Web Store.
  - REST API with FastAPI and PostgreSQL, and an account system (PBKDF2 password hashing, session tokens, rate limiting, password reset with a recovery code).
  - Real-time multiplayer duel rooms over WebSocket, with scoring and a leaderboard.
  - Subtitle language detection (stopwords + alphabet analysis), a 6-language interface, light/dark theme and an admin panel.
  - Deployed on Railway.

- 💻 **[Computer Sales System: Backend API](https://github.com/yakupceri/computer-sales-system-spring-boot)** (Java / Spring Boot)
  - A RESTful backend service built with Spring Boot that manages computer sales, with a small storefront and an admin panel on top.
  - Dynamic filtering with JPA Specification: one endpoint turns a JSON filter into SQL, with joins, AND/OR, paging and sorting across 10 resources.
  - CRUD with request DTOs, validation and meaningful HTTP codes (201, 204, 400, 404, 409).
  - Transactional order creation: stock check, stock deduction and totals in one transaction, rolled back on insufficient stock, with row locks (`PESSIMISTIC_WRITE`) against overselling.
  - Tests with JUnit and MockMvc on H2, run on every push with GitHub Actions. A one-command H2 demo mode with sample data.

- 🗄️ **[Computer Store: Database Design](https://github.com/yakupceri/computer-store-sqlserver-db)**
  - A relational database for sales processes on SQL Server, designed to Third Normal Form (3NF).
  - Data integrity with PRIMARY KEY, FOREIGN KEY, UNIQUE and CHECK constraints.
  - Transactions (ACID), TRIGGER, FUNCTION and VIEW-based reporting.

---

### 🎓 Education & certificates

- **İzmir University of Economics** — Computer Programming *(Associate degree)* `(2023 - 2025)`
- **Certificates & events:**
  - Gameathon 4.0, IEU Vocational School — Mentor (2024)
  - Introduction to Cybersecurity — CISCO (2023)

---

### 📈 GitHub stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yakupceri&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&v=2" height="145" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yakupceri&layout=compact&theme=tokyonight&v=2" height="145" alt="Top Langs" />
</div>

---

### 📫 Contact

- **LinkedIn:** [linkedin.com/in/yakupceri](https://www.linkedin.com/in/yakupceri/)
- **Email:** [yakupceri24@gmail.com](mailto:yakupceri24@gmail.com)
- **Location:** İzmir, Türkiye
