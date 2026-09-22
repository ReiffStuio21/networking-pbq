# Networking PBQ

Free, self-graded performance-based practice labs for CompTIA Network+ exam prep, built by [Launching IT Solutions](https://launchingitsolutions.com) so students who can't afford paid lab platforms still get hands-on practice.

## Pages

- `index.html` — homepage introducing the mentorship program and the labs
- `networking-pbq-labs.html` — the practice lab suite:
  - **CompTIA Network+ PBQ Practice** — a 50-question original PBQ bank spanning all five Network+ (N10-009) exam domains
  - **Network Topology Builder** — drag-and-drop devices, 5 graded scenarios (LAN, secured office, Wi-Fi branch, VLAN segmentation, site-to-site VPN)
  - **Subnetting Practice** — 3 difficulty tiers with instant grading
  - **Port & Protocol Matching**
  - **Cable & Connector Matching**
  - **Command Line Simulator** — 3 mission packs (Office Basics, VLAN Troubleshooting, VPN Troubleshooting)
  - **My Results** — a printable/screenshotable progress summary
- `site-shared.css` — shared header/nav/button styling used by both pages

No build step, no dependencies — plain HTML/CSS/JS. Progress is saved per-student in the browser (`localStorage`), nothing is sent to a server.

## Running locally

Just open `index.html` in a browser.

## Hosting

This repo is set up to be served with GitHub Pages (Settings → Pages → Deploy from branch → `main` → `/ (root)`), which serves `index.html` at the repo's Pages URL automatically.
