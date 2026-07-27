# soper.dev — Portfolio

Personal portfolio site for **Joseph Soper** — founder of [BezaCore Labs](https://bezacore.com), a DevOps / AI / software development studio.

**Live at [soper.dev](https://soper.dev)**

---

## What It Is

A single `index.html` file — no framework, no build step, no dependencies. All CSS and JavaScript are inline. Hosted on GitHub Pages with a custom domain.

**Design:** *Ember & Cobalt* on a dark surface, shared with [bezacore.com](https://bezacore.com) so the two sites read as siblings. IBM Plex Mono + IBM Plex Sans throughout.

**Sections:** Hero · About · Studio · Work · Skills · Contact

---

## Tech

- Pure HTML/CSS/JS — no framework, no bundler, no package manager
- Google Fonts (IBM Plex Mono, IBM Plex Sans)
- Hamburger nav below 720px
- Motion behind `prefers-reduced-motion`
- GitHub Pages + Cloudflare DNS (`CNAME`)

---

## Work Featured

Shipped and running only.

| Project | What | Link |
|---------|------|------|
| BezaForge Infrastructure | Self-hosted Proxmox/Docker platform — Terraform, Ansible, Prometheus/Grafana | [bezaforge-infrastructure](https://github.com/thejollydev/bezaforge-infrastructure) |
| Petoskey Church of Christ | WordPress site, designed and deployed | [petoskeychurchofchrist.com](https://petoskeychurchofchrist.com) |
| Brizza | Personal AI assistant on a self-hosted agent bridge | — |
| ansible-arch | Idempotent Arch Linux workstation provisioning | [ansible-arch](https://github.com/thejollydev/ansible-arch) |
| bezacore.com | BezaCore Labs studio site — Next.js on Cloud Run | [bezacore.com](https://bezacore.com) |

---

## Local Development

No build step needed.

```bash
git clone https://github.com/thejollydev/portfolio.git
cd portfolio
python -m http.server 8000    # then open http://localhost:8000
```

Or open `index.html` directly in a browser.

---

## Contact

[joseph@soper.dev](mailto:joseph@soper.dev) · [LinkedIn](https://www.linkedin.com/in/joseph-soper-dev/) · [GitHub](https://github.com/thejollydev)

---

## License

[MIT](LICENSE)
