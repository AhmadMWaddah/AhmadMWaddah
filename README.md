# Hi, I'm Ahmad M Waddah

Backend Engineer specialized in Python, Django, Linux System Administration, and DevOps practices. I build production-style systems — ERP, fintech, real-time social — plus the infrastructure automation to run them.

- 🛠️ **Tech Stack:** Python, Django, PostgreSQL, Docker, Linux (Ubuntu), Bash, Git/GitHub Actions, Hetzner, OCI, AWS
- 🚀 **Featured Projects:** ERP · Fintech Wallet · Real-time Social · KVM Automation (links below)
- 📫 **Contact:** [MyLinkedIn](https://www.linkedin.com/in/ahmadmwaddah/) | [waddah.ahmad@protonmail.com](mailto:waddah.ahmad@protonmail.com) | [MyWebsite](https://amw.work.gd)

---

## 🏗️ Featured Projects

| Project | What it is | Stack | Status |
|---------|-----------|-------|--------|
| [AMW_Django_ERP](https://github.com/AhmadMWaddah/AMW_Django_ERP) | ERP system: employee identity + policy-based access, inventory with WAC valuation, sales/purchasing workflows, audit logging, HTMX UI. 8 phases, 228 tests. | Django 4.2, PostgreSQL 15, Redis 7, Celery 5, Docker | ✅ Complete |
| [DigitalWallet](https://github.com/AhmadMWaddah/DigitalWallet) | Fintech wallet: separate client/staff portals, atomic deposit/withdraw/transfer, fraud detection + review queue, async PDF statements, analytics dashboards. | Django 5.2, PostgreSQL, Celery, Redis, HTMX, ReportLab | ✅ Complete (local demo) |
| [Pulse_Feed](https://github.com/AhmadMWaddah/Pulse_Feed) | Real-time social platform: posts, follows, likes, comments, WebSocket push notifications, email alerts + weekly digest via Celery Beat. 103 tests. | Django 5.0, Channels (WebSockets), PostgreSQL 16, Redis, Celery, Docker | ✅ Complete |
| [KVM_Spin_Ups](https://github.com/AhmadMWaddah/KVM_Spin_Ups) | Infrastructure-as-Code automation: zero-to-VM KVM provisioning with Kickstart unattended installs, multi-VM orchestration for test labs. | Bash, KVM/QEMU, libvirt, Kickstart | ✅ Complete |

> Live demo links coming soon — each repo has full local setup docs (Docker Compose one-command start).

---

## 🛠️ Technology Stack

| Category | Technologies |
|----------|-------------|
| **Backend** | Python 3.10–3.12, Django 4.2–5.2 |
| **Database** | PostgreSQL 15/16, SQLite (dev) |
| **Cache / Queue** | Redis 7, Celery 5 (+ Beat) |
| **Real-time** | Django Channels, WebSockets (Daphne) |
| **Frontend** | HTMX, vanilla JS, plain CSS, Chart.js |
| **Infra / IaC** | Docker + Compose, Bash, KVM/QEMU, libvirt, Kickstart |
| **Cloud** | Hetzner, OCI, AWS |
| **Quality** | pytest / pytest-django, ruff, black, GitHub Actions |

---

## ⚙️ How I Build

- **Services-first logic** — business rules live in `services.py`/`operations/`, never in views.
- **Data integrity** — atomic transactions, row locking, audit trails, soft deletes.
- **Verified, not vibes** — test suite + lint pass before every merge; branch-per-phase workflow.
- **Docs included** — architecture + setup guides in every repo so anyone can run it.
