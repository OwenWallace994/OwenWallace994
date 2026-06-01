<h1 align="center">Owen Wallace</h1>

<p align="center">
  Linux infrastructure | self-hosting | operations design | AI-assisted software delivery
</p>

<p align="center">
  I build and operate production systems on hardware I own, and when the software I need does not exist yet, I build that too.
</p>

---

## Overview

I administer Linux infrastructure end to end: containers, reverse proxies, monitoring, networking, and the services that run on top, on hardware I own and operate.

When I need software that does not exist yet, I build it through AI-assisted development. I decide what has to exist and how it should be shaped, direct the tooling that writes it, then deploy, monitor, and troubleshoot it in production.

That work usually lives where infrastructure, operations, and practical software meet:

- self-hosted Linux systems
- containerized services
- reverse proxies and TLS
- monitoring and observability
- internal tools built around real workflow problems

---

## Featured Projects

### Innsmouth Archives

**A production-grade self-hosted environment running on Linux, Docker, and Caddy, live on my own domain across nine subdomains.**

Core services include:

- **Caddy** for reverse proxying and automatic HTTPS
- **Jellyfin** for media streaming
- **Immich** for photo management and backup, including Postgres, Redis/Valkey, and an ML service
- **Kavita** for books and library management
- **Prometheus + Grafana + node-exporter** for metrics, dashboards, and health monitoring
- **Ollama** for local AI model serving on my own GPU
- **Tailscale + SSH** for private remote access, with internal services bound to localhost
- Custom applications that I built and operate on the same server

This is a daily-use production environment with full documentation: installation steps, the failure points I hit, how I debugged them, and a complete writeup of recovering the system after an OS corruption event.

> **Infrastructure portfolio:** [OwenWallace994/infrastructure-operations-portfolio](https://github.com/OwenWallace994/infrastructure-operations-portfolio)

### TradeFlow

**An internal operations platform I designed and built through AI-assisted development for a trade and field-service business.**

TradeFlow turns messy real-world job information, rough field notes, material needs, part requests, and equipment pricing, into structured, trackable jobs.

Most small trade businesses run on texts, paper, spreadsheets, and memory. That works until something gets missed. TradeFlow gives them one system to:

- capture jobs
- build material orders
- look up parts and pricing
- generate supplier-ready outputs
- keep a record they can trust afterward

Current capabilities:

- Job creation across multiple workflows: rough-ins, service work, and equipment quoting
- AI-assisted parsing that reads shorthand field notes and sorts items into the correct material fields
- Automatic handling of repetitive derived logic so the same details do not have to be re-entered every time
- Generated outputs including material lists, summaries, and supplier-facing files
- Post-generation verification checks so a file is never trusted just because it was produced without error
- A searchable job dashboard with archive, restore, and review
- Service-side pricing and part lookup
- A live equipment catalog and quote flow

I owned the whole thing: the problem definition, the workflow design, the architecture decisions, the deployment, and the ongoing operation. It runs as a managed service on the infrastructure above, routed through Caddy.

---

## What I Do

- Linux server administration, including Ubuntu and systemd
- Docker and container operations
- Caddy reverse proxy configuration and TLS
- Prometheus, Grafana, monitoring, and alerting
- Networking, DNS, and Tailscale
- Root-cause troubleshooting across software and hardware
- AI-assisted software development
- Clear, maintainable documentation for every project

---

## What I Am Learning

- Advanced Docker networking
- Infrastructure as Code
- Automated monitoring and alerting
- System hardening and backup strategy
- AWS
- CI/CD

---

## How I Work

My background is in HVAC and electrical work, and that still shapes how I approach technical systems.

I tend to work from the mechanism outward:

- understand how the system actually behaves
- identify the failure points
- trace the root cause
- document the fix
- make the result more reliable than it was before

That mindset carries directly into infrastructure, operations, and production debugging.

---

## A Bit About Me

Outside of infrastructure, I read constantly. Some long-standing favorites are Gene Wolfe's *Book of the New Sun* and Melville's *Moby-Dick*: the kind of dense, ambitious books that reward the effort.

I am currently teaching myself Latin through Orberg's *Lingua Latina*, learning the language by reading it directly.

I keep a steady gaming habit, and a lot of my free time goes back into the homelab and other builds. I like understanding how things work down to the mechanism, which usually means taking them apart to find out.
