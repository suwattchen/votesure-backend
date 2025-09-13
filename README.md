# VoteSure Backend

Backend API for VoteSure – a secure, multi-language polling system that separates audiences (Web users vs World App users).  
Built with **Node.js (Serverless on Vercel)** and **Upstash Redis** for storage.

---

## Features
- Create and manage polls with audience separation:
  - `web` → normal users on the website
  - `world` → users via World App / World ID integration
- Cast votes with basic rate limiting (per IP, per poll)
- Fetch poll results with lightweight caching (20–30s)
- Multi-language friendly (frontend handles i18n, backend is language-agnostic)
- Serverless, deployable with one click on **Vercel**

---

## Project Structure
