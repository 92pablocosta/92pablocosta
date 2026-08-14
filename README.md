# Hi, I'm Pablo Costa

### Python Backend Developer · AI Automation & LLM Applications

Brazilian software developer building **Python backends, automation tools, and LLM-powered applications**.

My current production work includes **DentBot**, a WhatsApp assistant used by a real dental clinic. I am now rebuilding its backend as a public, test-driven Python project based on lessons learned from operating the original system.

I also spent **four years living and working in Australia**, giving me fluent English and practical experience working across cultures.

**Technology degree in Internet Systems — UNIESP, July 2026**
**Open to remote backend, AI automation, and LLM application roles worldwide.**

<a href="mailto:92pablocosta@gmail.com">
  <img src="https://img.shields.io/badge/Email-333?style=for-the-badge&logo=gmail&logoColor=white">
</a>
<a href="https://www.linkedin.com/in/pablocosta-dev/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
</a>

---

## What I Build

* **LLM-powered applications** connected to real business workflows
* **Python backends and REST APIs** with explicit business rules and automated tests
* **WhatsApp automation** using n8n, Evolution API, Redis, PostgreSQL, and OpenAI
* **Standalone Python tools** packaged for non-technical users
* **Self-hosted infrastructure** with Docker, Traefik, monitoring, backups, and operational documentation
* **Agent-oriented development workflows** with specialized instructions and persistent project state

---

## Tech Stack

### Backend and Testing

<div>
  <img align="center" alt="Python" height="40" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg">
  <img align="center" alt="FastAPI" height="40" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg">
  <img align="center" alt="PostgreSQL" height="40" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg">
  <img align="center" alt="Redis" height="40" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg">
  <img align="center" alt="Pytest" height="40" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytest/pytest-original.svg">
</div>

<br>

### AI and Automation

![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=flat\&logo=openai\&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat\&logo=pydantic\&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat\&logo=n8n\&logoColor=white)
![Evolution API](https://img.shields.io/badge/Evolution_API-2E8B57?style=flat)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat\&logo=anthropic\&logoColor=white)

### Infrastructure

<div>
  <img align="center" alt="Docker" height="40" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg">
  <img align="center" alt="Linux" height="40" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg">
  <img align="center" alt="Traefik" height="40" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/traefikproxy/traefikproxy-original.svg">
  <img align="center" alt="Git" height="40" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg">
</div>

---

## Featured Projects

### 🦷 [DentBot](https://dentbot.com.br) — WhatsApp Assistant in Production

> LLM-powered assistant used by a paying dental clinic to support patient interactions through WhatsApp.

* Supports scheduling requests, frequently asked questions, and initial patient triage
* Uses **n8n**, **OpenAI**, **Evolution API**, **Redis**, **PostgreSQL/Supabase**, and **Docker**
* Implements a Redis-based debounce mechanism to combine rapid consecutive messages before processing
* Maintains conversation state across patient interactions
* Currently establishing reliable baselines for conversation volume, handoff rate, latency, and operating cost

### 🧠 DentBot Core — Test-Driven Backend Rebuild

> A public, production-oriented rebuild that will eventually replace the current DentBot backend.

* Separates deterministic business rules from LLM behavior and workflow orchestration
* Currently implements intent classification and explicit priority rules
* Uses **Python**, **pytest**, and **uv**, with five initial automated tests
* Designed to expose a **FastAPI** HTTP boundary for integration with n8n
* Documents implemented behavior separately from planned functionality

*Status: active development — repository link will be added when the first public version is published.*

### ⚖️ TRT2/PJe Comunica Scraper — Legal Process Automation

> Freelance Python application delivered to a São Paulo law firm for monitoring court communications.

* Approximately **2,300 lines of Python**
* Covered by **93 automated tests**
* Packaged as a standalone Windows executable with **PyInstaller**
* Designed for non-technical users
* Delivered to and used by the client

*Private client project; implementation details are not publicly available.*

### 🖥️ [VPS Public Portfolio](https://github.com/92pablocosta/vps-public-portfolio) — Self-Hosted Infrastructure

> Public documentation of a production-like VPS environment built with security, recoverability, and operational clarity in mind.

* Docker workloads routed through **Traefik** with automatic TLS
* Restricted network exposure and hardened SSH access
* Monitoring and alerting with **Uptime Kuma**
* Off-site encrypted backups with **Restic** and Backblaze B2
* Real restore procedure validated
* Operational decisions, limitations, and recovery procedures documented publicly

---

## Current Focus

I am currently turning lessons from the live DentBot implementation into a more maintainable backend:

1. Deterministic and testable business rules
2. A clear FastAPI integration boundary
3. Persistent conversation state
4. Measurable quality, latency, and operating cost
5. Observability based on actual production requirements

The goal is not to add frameworks for their own sake. It is to make the system easier to test, operate, diagnose, and evolve.

---

## Let's Connect

I am open to remote opportunities involving:

* Python backend development
* AI automation
* LLM application engineering
* API and workflow integrations
* Freelance automation projects

<a href="mailto:92pablocosta@gmail.com">
  <img src="https://img.shields.io/badge/Email-333?style=for-the-badge&logo=gmail&logoColor=white">
</a>
<a href="https://www.linkedin.com/in/pablocosta-dev/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
