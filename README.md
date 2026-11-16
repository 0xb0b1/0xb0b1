<div align="center">

<img src="./banner-trace.svg" width="100%" alt="Paulo Vicente: I write about how systems break, and why. Drawn as a distributed trace where a broker publish times out and succeeds after two retries." />

<br>

[![Blog](https://img.shields.io/badge/Blog-paulo--vicente.fly.dev-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://paulo-vicente.fly.dev/)
<!-- LinkedIn's glyph was dropped from simple-icons, so shields needs it inlined as a data URI -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Paulo%20Vicente-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjUgMHoiLz48L3N2Zz4%3D)](https://www.linkedin.com/in/paulo-vicente-6abab0198/)
[![X](https://img.shields.io/badge/X-@p__vcent-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/p_vcent)
[![Email](https://img.shields.io/badge/Email-vcente82-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vcente82@gmail.com)

</div>

---

## Hey, I'm Paulo

<p align="center">
  <img src="./banner-ledger.svg" width="100%" alt="Paulo's career as an append-only event stream (LocatedIn, StudiedAppSec, AdoptedGo, JoinedXTeam, RewroteServiceInGo, PostsPublished) folding into a profile projection." />
</p>

**Senior Full Stack Engineer at Eleanor Health via X-Team** · Cuiabá, Mato Grosso — Brazil 🇧🇷

Backend-heavy: **Go** on the server, **TypeScript + React** on the frontend.

I build **resilient, data-heavy backends in Go**.
Studying application security taught me more about architecture than any framework did: you design better
once you understand *how systems break*.

- 🧩 Event Sourcing / CQRS, message brokers, idempotency, graceful degradation — in Go
- 🐿️ Small interfaces, explicit errors, bounded concurrency, the standard library first
- 🔭 Currently deep in: Python → Go strangler-fig migrations, observability that actually traces
- ✍️ Writing **65+ posts** at [paulo-vicente.fly.dev](https://paulo-vicente.fly.dev/) — in 🇬🇧 and 🇧🇷

---

## Featured Work

<p align="center">
  <img src="./banner-gowm.svg" width="100%" alt="A gowm tiling window manager session: a terminal introduces Paulo Vicente, a bounded goroutine pool pulses, and a journal tails retries and dedup hits." />
</p>

| Project | What it is |
| :--- | :--- |
| **[eventsource](https://github.com/0xb0b1/eventsource)** `Go` | Event Sourcing + CQRS, implemented properly — banking domain, append-only log, projections |
| **[taskqueue](https://github.com/0xb0b1/taskqueue)** `Go` `Postgres` | Distributed task queue: scheduling, exponential-backoff retries, bounded worker pools |
| **[gowm](https://github.com/0xb0b1/gowm)** `Go` | A tiling X11 window manager in **pure Go**, no C bindings — xmonad-inspired |
| **[blog](https://github.com/0xb0b1/blog)** `Go` | This blog is a Go binary — `html/template`, markdown content, i18n, shipped on Fly.io |

<sub>**Behind closed repos:** a real-time notification service in Go (gRPC + WebSocket delivery, Redis-backed
deduplication, stateless horizontal scaling) — the migration story is written up
[here](https://paulo-vicente.fly.dev/en/posts/rewriting-python-notifications-service-in-go) — plus subscription
and data-ingestion services in Go.</sub>

---

## From the Blog

Notes from production, not tutorials.

- 🐿️ [Rewriting a Python Notifications Service in Go](https://paulo-vicente.fly.dev/en/posts/rewriting-python-notifications-service-in-go)
- ⏱️ [Your Change Detection Never Fires If the Payload Carries a Clock](https://paulo-vicente.fly.dev/en/posts/change-detection-never-fires-if-the-payload-carries-a-clock)
- 🗄️ [Idempotency Belongs in the Database](https://paulo-vicente.fly.dev/en/posts/idempotency-belongs-in-the-database)

<sub>→ [read everything](https://paulo-vicente.fly.dev/en/posts/) · também [em português](https://paulo-vicente.fly.dev/pt/posts/)</sub>

---

## Toolbox

<div align="center">

**Languages**

[![Languages](https://skillicons.dev/icons?i=go&theme=dark)](https://skillicons.dev)

**Data & Infra**

[![Infra](https://skillicons.dev/icons?i=postgres,redis,kafka,docker,kubernetes,aws,terraform,grafana&theme=dark)](https://skillicons.dev)

**Daily Drivers**

[![Tools](https://skillicons.dev/icons?i=neovim,linux,git,githubactions,bash,nix&theme=dark)](https://skillicons.dev)

</div>

---

## Stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=0xb0b1&theme=tokyonight" />
  <img width="810" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=0xb0b1&theme=default" alt="GitHub profile summary" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=0xb0b1&hide_border=true&theme=tokyonight&ring=00ADD8&fire=00ADD8&currStreakLabel=00ADD8" />
  <img height="180" src="https://streak-stats.demolab.com?user=0xb0b1&hide_border=true&ring=00ADD8&fire=00ADD8&currStreakLabel=00ADD8" alt="Contribution streak" />
</picture>

</div>

---

<div align="center">

<img src="./banner-hexdump.svg" width="100%" alt="xxd hex dump of the line: 0xb0b1 :: Paulo Vicente :: Go, event sourcing, and how systems break." />

<sub>*"Make it correct, make it observable, then make it fast."*</sub>

<br><br>

<a href="https://www.buymeacoffee.com/0xb0b1"><img src="https://img.shields.io/badge/Buy%20me%20a%20coffee-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Buy me a coffee" /></a>

</div>
