# Networking PBQ

Free, self-graded performance-based practice labs for CompTIA Network+ exam prep, built by [Launching IT Solutions](https://launchingitsolutions.com) so students who can't afford paid lab platforms still get hands-on practice.

## Pages

- `index.html` — homepage introducing the mentorship program and the labs
- `networking-pbq-labs.html` — the practice lab suite:
  - **Full Practice Exam** — 200 original, timed, multiple-choice situational questions spanning all five Network+ (N10-009) domains, with per-question hints and a detailed explanation after every answer, plus a domain-by-domain score breakdown at the end. Choose a 25-question quick run, the real exam's 90-question length, or the full 200-question bank.
  - **CompTIA Network+ PBQ Practice** — a 50-question original PBQ bank (match, single/multi-select, ordering, and typed subnet-allocation questions)
  - **Network Topology Builder** — drag-and-drop devices, 5 graded scenarios (LAN, secured office, Wi-Fi branch, VLAN segmentation, site-to-site VPN)
  - **Subnetting Practice** — 3 difficulty tiers with instant grading
  - **Port & Protocol Matching**
  - **Cable & Connector Matching**
  - **Command Line Simulator** — 3 mission packs (Office Basics, VLAN Troubleshooting, VPN Troubleshooting)
  - **My Results** — a printable/screenshotable progress summary
- `exam-bank.js` — the 200-question data set for the Full Practice Exam
- `site-shared.css` — shared header/nav/button styling used by both pages

All exam/PBQ content is original, written to match the real exam's format and objective weighting — not reproductions of real CompTIA exam questions, which would violate CompTIA's candidate agreement.

No build step, no dependencies — plain HTML/CSS/JS. Progress is saved per-student in the browser (`localStorage`), nothing is sent to a server.

## Running locally

Just open `index.html` in a browser.

## Hosting

This repo is set up to be served with GitHub Pages (Settings → Pages → Deploy from branch → `main` → `/ (root)`), which serves `index.html` at the repo's Pages URL automatically.
