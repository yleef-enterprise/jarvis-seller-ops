# JARVIS — product tour

An interactive walkthrough of JARVIS, a Hinglish AI seller-operations platform for
Indian marketplaces. Sample data; not a live instance.

Published for prospective acquirers. Source code is not in this repository.

Yleef Enterprise

## About the developer

Hi, I'm Prabhudutt Mishra.

I build **local-first systems** — software that runs on your own hardware and
keeps working when the internet does not.

Right now that means **JARVIS**: a LAN-first assistant and seller-operations
platform. FastAPI backend, React/Vite dashboard, Android app through Capacitor.
Voice control, approval-gated marketplace automation, and system operations,
all behind a default-deny API gate.

### How I work

- **Verify by running it.** A green suite is not evidence a feature works. The
  defects worth fixing have mostly come from starting the server and using it —
  endpoints that reported work they never did, an OCR claim with no call site,
  a document index the model was never handed.
- **Measure, don't reason.** Retrieval thresholds and filter rules get tuned
  against the real corpus and the number written down, because a word list that
  sounds right is how "10 gram" becomes "10 ram".
- **Say what is actually true.** Status endpoints probe rather than assert, and
  a known gap goes in the commit message instead of quietly shipping.
- **Dependency bumps land when the build agrees**, not when the badge is green.

### Tech I reach for

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

Most of my work lives in private repositories.
