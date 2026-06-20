<div align="center">

# Hi, I'm Nelush Gayashan Fernando 👋

### Lead Software Engineer · IAM & API Security Specialist · Full-Stack

**3.5+ years building production-grade, scalable systems across fintech and enterprise software**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nelush-gayashan-fernando-29389b13a/)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@nelushgayashan)
[![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/10507147)

</div>

---

## 🔐 What I Actually Build

I specialize in the layer most engineers avoid: **identity, access control, and the platform-level workflows that sit between users and APIs.** Currently leading **API security and IAM implementations** for enterprise fintech systems, with deep, hands-on WSO2 expertise spanning Identity Server, API Manager, and custom OSGi extension development.

- **WSO2 Identity Server & API Manager** — custom OSGi workflow executors, two-stage signup/approval pipelines, lifecycle event interception (application & subscription creation), full **IS migration (5.11.0 → 7.2.0)** with zero-downtime cutover preserving SAML2/OAuth2/SCIM 2.0 integrity
- **OAuth 2.0 / JWT / Spring Security 6** — authorization code & client credentials flows, JWT-signed assertions, custom OAuth2/JWT transformers, mediation handlers, CORS policy enforcement
- **API Security & Governance** — banking-grade API gateways, fine-grained throttling, mTLS, PCI-DSS-aligned implementations, sub-100ms latency under fintech-grade vulnerability assessment
- **Production-grade reliability by default** — hermetic test suites (Wiser/JUnit 5/Mockito), race-condition guards, regression tests written for bugs found in *real* production server logs, not just happy-path demos

> If a default WSO2 workflow approves silently with zero audit trail, I've probably already replaced it with one that doesn't.

---

## 🏗️ Full-Stack & Systems Range

- **Spring Boot 3.x+ / Java 8+** microservices — domain-driven design, JPA/Hibernate optimization (eliminating N+1 bottlenecks, strategic indexing/joins), Redis/Caffeine caching, Bucket4j rate limiting
- **CQRS & Event-Driven Architecture** — command/query segregation, domain aggregates, projections, denormalized read models, built from scratch (no Axon, no magic)
- **ReactJS / SAP Fiori & UI5** — SPAs with Vite, Redux, Tailwind CSS, optimized Virtual DOM rendering for cross-device consistency; SAP Integration Suite automation (iFlows, value mappings, security artifacts)
- **Databases** — MySQL, PostgreSQL, IBM DB2, Redis, MongoDB — schema design for systems that need to scale and stay consistent
- **DevOps & Automation** — Docker, Maven, GitHub Actions, Bash automation for banking infrastructure workflows, JaCoCo coverage, Testcontainers

---

## 💼 Experience

**Lead Software Engineer** · Top commercial bank, Sri Lanka *(Nov 2025 – Current)*
WSO2 IS/APIM implementation · Java/Spring Boot RESTful APIs with OAuth 2.0, JWT, CORS · Bash automation for banking infra · SQL/PostgreSQL financial data management · regulatory-aligned delivery with compliance & audit teams

**Software Engineer → Junior → Trainee** · Software solutions company, Sri Lanka *(Oct 2023 – Nov 2025)*
Java 8+/Spring Boot 3.x+ microservices with domain-driven design · SAP Fiori-compliant ReactJS SPAs · OData/S/4HANA connectivity · Redis/Caffeine caching, Bucket4j rate limiting

**Technical Assistant (Software)** · Top University, Sri Lanka *(Feb 2023 – Jun 2023)*
MVC architecture, Spring Boot 3.x+ dependency injection & service layers · performance optimization via query/index tuning

---

## 🛠️ Featured Projects

### IAM / WSO2 — Production-Grade
| Project | What it demonstrates |
|---|---|
| [**wso2-usersignup-workflow**](https://github.com/NelushGayashan/wso2-usersignup-workflow) | OSGi bundle replacing WSO2 APIM's silent signup approval with a branded two-stage workflow. Includes a real concurrency bug fix (rejection emails dropped after user-record deletion, found via production logs) and a 32-test hermetic suite using an in-process SMTP server |
| [**wso2-custom-executor**](https://github.com/NelushGayashan/wso2-custom-executor) | OSGi executors intercepting application & subscription lifecycle events across WSO2 APIM, async HTML email dispatch, zero external runtime dependencies |
| [**user-signup-workflow**](https://github.com/NelushGayashan/user-signup-workflow) | External Spring Boot workflow engine for WSO2 APIM — Carbon SOAP-based claim resolution (after SCIM2 hit CSRF walls), async processing, REST approval callbacks |

### Backend Architecture & Systems Design
| Project | What it demonstrates |
|---|---|
| [**cqrs-order-service**](https://github.com/NelushGayashan/cqrs-order-service) | CQRS implemented from scratch in Spring Boot 3 — domain events, aggregates, projections, denormalized read models, RFC 9457 `ProblemDetail` error handling. Companion Medium article included |
| [**Event_Management**](https://github.com/NelushGayashan/Event_Management) | Full RESTful event platform — JWT auth, RBAC, soft deletes, Caffeine caching, Bucket4j rate limiting, MapStruct, comprehensive integration testing |
| [**demo-api**](https://github.com/NelushGayashan/demo-api) | Spring Boot REST API reference implementation |
| [**ToDoFullstack**](https://github.com/NelushGayashan/ToDoFullstack) | Full-stack task app — frontend UI, backend API, database layer |

### Full-Stack Rewrites
| Project | What it demonstrates |
|---|---|
| [**gym_management_system**](https://github.com/NelushGayashan/gym_management_system) | Two-phase rewrite: PHP front-controller + PDO/prepared statements → full  role-based routing (Admin/Clerk/Instructor/Customer), Recharts dashboards |
| [**smart-bill-calculator**](https://github.com/NelushGayashan/smart-bill-calculator) | React app for splitting bills and calculating tips |
| [**smart-loan-calculator**](https://github.com/NelushGayashan/smart-loan-calculator) | Financial calculator utility |
| [**salary-calculator**](https://github.com/NelushGayashan/salary-calculator) | Financial calculator utility |
| [**WeatherApp**](https://github.com/NelushGayashan/WeatherApp) | API-driven weather frontend |
| [**TODO_List_App**](https://github.com/NelushGayashan/TODO_List_App) | Task management app |

### Java Internals & Technical Writing (companion repos to published articles)
| Project | What it demonstrates |
|---|---|
| [**java-streams-mastery**](https://github.com/NelushGayashan/java-streams-mastery) | Advanced Java Streams patterns |
| [**java-multithreads**](https://github.com/NelushGayashan/java-multithreads) | Concurrency & multithreading patterns |
| [**java-queue-deep-dive**](https://github.com/NelushGayashan/java-queue-deep-dive) | Queue data structure internals |
| [**LinkedListJava**](https://github.com/NelushGayashan/LinkedListJava) | Singly, doubly, and circular linked list implementations |
| [**hackerRank**](https://github.com/NelushGayashan/hackerRank) | Algorithm & data structure practice solutions |

### Embedded Systems & Electronics *(Electronics & Communication Engineering background)*
| Project | What it demonstrates |
|---|---|
| [**Robo_Car_C**](https://github.com/NelushGayashan/Robo_Car_C) | Robotic vehicle control — IR sensor array line-following, motor control, ultrasonic obstacle avoidance |
| [**Obstacle_Detection_System**](https://github.com/NelushGayashan/Obstacle_Detection_System) / [**...C_Programming**](https://github.com/NelushGayashan/Obstacle_Detection_System_C_Programming) | Sensor-driven obstacle detection, OOP-based firmware design |
| [**Digital_Pattern_Recognizer**](https://github.com/NelushGayashan/Digital_Pattern_Recognizer) | Digital logic / pattern recognition system |
| [**Bit_Adders**](https://github.com/NelushGayashan/Bit_Adders) | Digital logic design — binary adder circuits |
| [**Electronic_Packaging_System**](https://github.com/NelushGayashan/Electronic_Packaging_System) | Automated control system |
| [**Fluid_Filling_Machine**](https://github.com/NelushGayashan/Fluid_Filling_Machine) | Automated control system |
| [**Automated_Lightning_System**](https://github.com/NelushGayashan/Automated_Lightning_System) | Automated lighting control system |
| [**PC_Control_Projects**](https://github.com/NelushGayashan/PC_Control_Projects) | PC-to-hardware interfacing |
| [**Linear_Equation_Solver**](https://github.com/NelushGayashan/Linear_Equation_Solver) | Numerical methods solver |

*More Java internals deep-dives (Collections, Streams, Multithreading, Data Structures, Spring Security JWT, CQRS) published with companion code on [Medium](https://medium.com/@nelushgayashan).*

---

## 📝 Writing

I publish companion technical articles for most of what I build — Spring Security JWT authentication flows, CQRS in practice, Java Collections/Streams internals, multithreading patterns, Spring Boot annotations deep-dives. Each comes with a working, tested repo — not just theory.

[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@nelushgayashan)

---

## 🎸 Off the Clock

When I'm not deep in classloader errors or Carbon claim resolution logic, I'm usually playing guitar or working through my Vedic astrology (Jyotish) charts. I'm also fairly active crafting content and captions for social media — turns out structuring a good post isn't all that different from structuring a good README.

<details>
<summary><b>📚 Academic background & earlier interests</b></summary>
<br>

I hold two Bachelor's degrees:
- **B.Sc. Honours in Engineering (Electronics & Communication Engineering)** — Open University of Sri Lanka *(Thesis: Comparative Study on Effective Face Recognition Algorithms)*
- **Bachelor of Information Technology (BIT)** — University of Colombo School of Computing *(Thesis: Gym Management System)*

Before specializing in backend/IAM work, I spent time across:
- Embedded systems & microcontroller programming (Arduino, OOP-based firmware design)
- Machine learning & data science fundamentals (Python, TensorFlow, Keras)
- VHDL / FPGA development with Active-HDL

Which is probably why I still can't resist a good hardware tangent.

</details>

---

## 🌐 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nelush-gayashan-fernando-29389b13a/) [![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/10507147) [![Medium](https://img.shields.io/badge/Medium-12100E?style=flat&logo=medium&logoColor=white)](https://medium.com/@nelushgayashan)

---

## 💻 Tech Stack

**IAM & Security**

![WSO2](https://img.shields.io/badge/WSO2-FF7300?style=for-the-badge&logo=wso2&logoColor=white) ![OAuth](https://img.shields.io/badge/OAuth_2.0-000000?style=for-the-badge&logo=auth0&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**Languages**

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

**Backend**

![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) ![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

**Frontend & Enterprise Integration**

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white) ![Tailwind](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![SAP](https://img.shields.io/badge/SAP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![IBM DB2](https://img.shields.io/badge/IBM_DB2-052FAD?style=for-the-badge&logo=ibm&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

**Tools & DevOps**

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)

---

## 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=NelushGayashan&theme=ambient_gradient&hide_border=false&include_all_commits=true&count_private=false)
![](https://github-readme-streak-stats.herokuapp.com/?user=NelushGayashan&theme=ambient_gradient&hide_border=false)

[![](https://visitcount.itsvg.in/api?id=NelushGayashan&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
