# Hi there, I'm José Carlos Sousa 👋

### Mid-Senior Java / Java Full-Stack Developer
📍 Seixal, Portugal | 📧 [jccsdeveloperrailway@gmail.com](mailto:jccsdeveloperrailway@gmail.com)

Mid-Senior **Java & Full-Stack Developer** with **15+ years of enterprise software experience** across mobility, energy, banking, and telecommunications sectors. Specialized in building, modernizing, and securing scalable backend systems with **Java, Spring Boot, Spring Security, JPA/Hibernate, and PostgreSQL**, paired with modern **React** frontends.

---

### 🚀 Featured Project: Express Remodeling — Full-Stack Web Platform
*End-to-end architecture, development, and cloud deployment of a portfolio showcase and backoffice management system (source repositories are private for client protection).*

#### 🏗️ System Architecture & Key Technical Highlights
* **Backend & RESTful API Design:** Built with **Java 21** and **Spring Boot 3**, featuring **Spring HATEOAS** pagination, content negotiation (JSON, XML, YAML), DTO/VO mapping, centralized exception handling (`@ControllerAdvice`), and interactive **OpenAPI / Swagger** documentation.
* **Authentication & RBAC Security:** Secured with **Spring Security** using stateless **JWT Access & Refresh Tokens**, PBKDF2 password encoding, Role-Based Access Control (`ADMIN`, `MANAGER`, `USER`), CORS policies, and immediate server-side session revocation (`tokenVersion` invalidation on logout).
* **Event-Driven Messaging (RabbitMQ):**
  * Topic-exchange architecture (`portfolio.exchange`) decoupling heavy background tasks such as asynchronous **Cloudinary** image deletion, orphaned division cleanup, and cover-image linking.
  * Asynchronous login audit pipeline recording device user-agents, IP addresses, and browser GPS coordinates without blocking authentication latency.
* **Aspect-Oriented Auditing (Spring AOP):** Custom `@AuditLog` annotation with SpEL expression evaluation to automatically capture before/after entity field diffs on backoffice mutations.
* **Database & Cloud Infrastructure:** **PostgreSQL** schema managed via **Flyway** versioned migrations, multi-stage **Docker** builds (`Eclipse Temurin 21`), **Railway** backend hosting, and a **React (Vite) + i18next** SPA deployed on **Render Cloud**.

---

### 🛠️ Core Tech Stack

* **Backend:** Java (6 to 21), Spring Boot 3, Spring Security (JWT), Spring Data JPA, Hibernate, Spring AOP, Spring HATEOAS, OpenAPI / Swagger, Jakarta EE (JEE), RESTful APIs, SOAP, Maven
* **Messaging & DevOps:** RabbitMQ, Docker, Kubernetes, Flyway, Git, CI/CD, Google Cloud Platform (GCP), Railway, Render
* **Databases:** PostgreSQL, Oracle, MySQL, DB2, SQL Server, Informix
* **Frontend & Mobile:** React, Vite, i18next, JavaScript, Angular, HTML5/CSS3, Swift (iOS)

---

### 📫 Connect & Opportunities
I am currently open to **Java Backend** or **Java Full-Stack Developer** roles (remote or hybrid in Portugal/Europe).  
Feel free to reach out via email at **jccsdeveloperrailway@gmail.com** or connect with me here on GitHub!
