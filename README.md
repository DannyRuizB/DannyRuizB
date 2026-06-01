# Danny Ruiz Boluda

**Systems & network administrator — ASIR** · finishing a 400h internship (FCT) at **Zataca Systems**, Elche, Spain.

Based in Torrevieja, Spain — open to relocation.

## // about

- **ASIR** — *Administración de Sistemas Informáticos en Red* (higher vocational degree in systems & network administration).
- Hands-on with Linux, Docker, Proxmox, networking, security and monitoring.
- I like building small, self-hosted tools that make infrastructure easier to *see* and operate.
- Open to: **sysadmin, DevOps, networking, cloud, infrastructure**.

## // stack

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## // projects

### [wikijs-zataca](https://github.com/DannyRuizB/wikijs-zataca)

End-to-end deployment of a **Wiki.js** service on **Docker Compose** (PostgreSQL + Wiki.js + Nginx) over a hardened Debian VM. Two isolated networks, named volumes, healthchecks, automated backups with retention, monitoring and a tested restore procedure. My ASIR final project — the one that ties everything together.

**Stack**: Docker Compose · PostgreSQL · Nginx · Debian · Bash · cron

### [lanscope](https://github.com/DannyRuizB/lanscope) · [live demo](https://lanscope-demo.onrender.com)

Visual **LAN scanner** on top of `nmap`: point it at a CIDR, see who's there, browse the topology and diff scans over time. Runs in Docker with host networking; multi-arch image on GHCR.

**Stack**: Node.js · nmap · SQLite · Docker (host net) · GHCR

### [firewallscope](https://github.com/DannyRuizB/firewallscope) · [live demo](https://dannyruizb.github.io/firewallscope/)

Visual analyzer for **`iptables` / `ip6tables` / `nftables` / `ufw`** rulesets — paste a dump, see the structure. Packet tracing across the full NAT/filter pipeline and a linter for 8 common ruleset smells. 100% client-side.

**Stack**: JavaScript · client-side · GitHub Pages

### [dockerscope](https://github.com/DannyRuizB/dockerscope) · [live demo](https://dannyruizb.github.io/dockerscope/)

Visual analyzer for **`docker-compose.yml`** — paste a compose file, see the architecture (services, networks, volumes, ports). Security linter, Dockerfile inspection and multi-file `extends`/`include` merging. Client-side, no backend.

**Stack**: JavaScript · client-side · GitHub Pages

### [didactic-dashboard](https://github.com/DannyRuizB/didactic-dashboard) · [live demo](https://didactic-dashboard.onrender.com)

Self-hosted **monitoring dashboard**: add a host by IP/hostname and watch it in real time — ICMP/TCP/SSH with live CPU/RAM/disk metrics, threshold alerts and history charts. Published to Docker Hub.

**Stack**: Node.js · Express · SQLite · Docker · Render

## // contact

- **Email** — [dannyruizboluda@gmail.com](mailto:dannyruizboluda@gmail.com)
- **LinkedIn** — [danny-ruiz-boluda](https://www.linkedin.com/in/danny-ruiz-boluda-108452403)
- **Location** — Torrevieja, Spain (available for relocation)

---

### // es

Hola, soy Danny — **administrador de sistemas y redes (titulado ASIR)**. Acabo de terminar las prácticas FCT (400h) en Zataca Systems (Elche). Vivo en Torrevieja, abierto a moverme. Me gusta montar herramientas self-hosted que hacen la infraestructura más fácil de ver y operar. Si quieres hablar sobre oportunidades de sysadmin, DevOps, redes o cloud, escríbeme por email o LinkedIn.
