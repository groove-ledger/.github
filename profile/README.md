# Groove Ledger 🎛️📀

**Groove Ledger** is an open-source playground where music obsession meets cloud-native engineering.

We build tools to help people **track curated album lists**, **log listening history**, and **discover patterns over time** — without trying to replace Discogs or streaming platforms.

Think of it as a **listening journal**, powered by modern infrastructure.

---

## Why “Groove Ledger”?

A **groove** is the spiral track carved into a vinyl record — the physical path where the music lives.  
A **ledger** is a structured record of events over time.

**Groove Ledger = a structured record of your musical journey.**

---

## What we’re building (starting small, aiming big)

✅ **MVP (in progress)**
- A simple API (`/version`) to validate the full delivery flow
- Containerized Spring Boot backend
- Kubernetes-first deployments (k3s)
- GitHub-based releases and automated deployments

🎯 **Next**
- Rolling Stone 2020 list as the first curated dataset
- Multi-user support (GitHub authentication)
- Listen events: _“I listened to this album on this date”_
- Lightweight stats: progress, streaks, decades, artists

🔮 **Future ideas**
- Optional Discogs integration (wishlist sync)
- Mobile-first experience (Ionic/Capacitor or native)
- Hybrid infra experiments (cloud + local observability/analytics)

---

## Philosophy

We aim for:
- **Simple UX** (two clicks to log a listen)
- **Privacy by design** (your history stays yours)
- **Extensibility** (clean architecture, modular growth)
- **Ops-friendly by default** (containers, observability, reproducible deploys)

Groove Ledger is **not**:
- a Discogs clone
- a global music metadata database
- a streaming platform

---

## Tech Stack (current direction)

- **Backend:** Java 21 + Spring Boot
- **Frontend:** Angular (later: mobile packaging)
- **Data:** PostgreSQL (planned)
- **Infra:** Docker + k3s
- **CI/CD:** GitHub Actions
- **Observability:** Grafana + Loki (planned; possibly cloud ↔ local hybrid)

---

## Get involved

- ⭐ Star the repos if you like the direction
- 🐛 Open issues for bugs/ideas
- 🔧 PRs are welcome (small improvements are perfect)

We’re here to build in public and ship incrementally.

---

### Motto

> **Log the listen. Learn the patterns. Keep the groove.** 🎶