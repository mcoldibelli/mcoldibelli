<div align="center">

<h1>Marcelo A. B. Coldibelli</h1>

**Backend Engineer · Financial Systems · Java Ecosystem**

Building distributed, compliant systems for financial environments —
from legacy fiscal engines to cloud-native Open Finance APIs.

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0e76a8?style=for-the-badge&logo=Linkedin&logoColor=white)](https://linkedin.com/in/marcelo-coldibelli)
[![Email](https://img.shields.io/badge/-marcelo@codaline.com.br-D14836?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:marcelo@codaline.com.br)
[![Codaline](https://img.shields.io/badge/-Codaline-000?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNTEyIiBoZWlnaHQ9IjUxMiIgdmlld0JveD0iMCAwIDUxMiA1MTIiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CiAgPHJlY3Qgd2lkdGg9IjUxMiIgaGVpZ2h0PSI1MTIiIHJ4PSIxMTIiIGZpbGw9IiNGRkZGRkYiLz4KICA8cGF0aCBkPSJNMzEwIDY4IEExNDggMTQ4IDAgMSAwIDMxMCA0NDQiIHN0cm9rZT0iIzExMTExMSIgc3Ryb2tlLXdpZHRoPSIzOCIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBmaWxsPSJub25lIi8+CiAgPGNpcmNsZSBjeD0iMzQwIiBjeT0iMjU2IiByPSI0OCIgZmlsbD0iIzhCNUNGNiIvPgo8L3N2Zz4K)](https://codaline.com.br)

</div>

---

### Focus

My background spans enterprise Java at a Brazilian ERP/fiscal software company and greenfield microservices targeting financial regulation compliance. I'm drawn to problems where correctness is non-negotiable: payment reconciliation, identity federation, API security, and distributed system reliability under financial-grade constraints.

---

### Featured Projects

| Project | What it does | Stack |
|---------|-------------|-------|
| **[open-finance](https://github.com/mcoldibelli/open-finance)** | FAPI 1.0 API Gateway with mTLS, certificate-bound tokens (RFC 8705), JTI anti-replay, consent lifecycle management and CNAB240/CIP banking reconciliation engine | Java 21 · Spring Cloud Gateway · Spring Cloud Config · Spring Batch · Redis · Kafka · Docker · Maven |
| **[Biked](https://github.com/mcoldibelli/biked)** | IoT system that turns a spinning bike into smart connected equipment | ESP32 · MQTT · Spring Boot · RabbitMQ |
| **[FlightIssues](https://flightissues.com)** | Micro SaaS — generates EC 261/2004 flight compensation claim letters; structured passenger input → regulation-compliant PDF artifact, one-time payment | React · Supabase · Stripe · React PDF |

---

### Financial Systems Experience

**Open Finance Brasil — FAPI 1.0 Compliance** [`open-finance`]
- API Gateway with ordered filter chain: mTLS validation → JTI anti-replay → consent authorization → rate limiting
- Certificate-bound access tokens per RFC 8705 (`cnf.x5t#S256` thumbprint binding)
- JTI replay prevention via Redis atomic `SETNX` with TTL anchored to JWT lifetime (fail-closed on Redis unavailability)
- CNAB240/CIP reconciliation engine with Spring Batch
- Reactive pipeline (Project Reactor) with security-safe error boundaries

**Brazilian Fiscal Systems — PHD Sistemas**
- NF-e, CT-e and NFS-e generation, signing and transmission
- PL/SQL stored procedures for fiscal calculation engines on Oracle DB
- JWT security library across interconnected Java monoliths (RS256, JWKS endpoint, servlet filters, SOAP handlers)

---

### Tech Stack
<code><img height="27" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java"></code>
<code><img height="27" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg" alt="Spring Boot"></code>
<code><img height="27" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angular/angular-original.svg" alt="Angular"></code>
<code><img height="27" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React"></code>
<code><img height="27" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python"></code>
<code><img height="27" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker"></code>
<code><img height="27" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL"></code>
<code><img height="27" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="Oracle"></code>
<code><img height="27" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" alt="Redis"></code>
<code><img height="27" src="https://www.vectorlogo.zone/logos/apache_kafka/apache_kafka-icon.svg" alt="Kafka"></code>
<code><img height="27" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rabbitmq/rabbitmq-original.svg" alt="RabbitMQ"></code>
<code><img height="27" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/arduino/arduino-original.svg" alt="ESP32"></code>
---

<div align="center">

<sub>The more we automate, the more human we must become — Ginni Rometty</sub>

</div>
