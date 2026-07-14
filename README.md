# Niya Parvin — Cybersecurity Portfolio

Live, single-file portfolio web app (HTML/CSS/JS) built in **`Index.html`**.

> Designed for recruiters: fast loading, strong section structure, and clear cybersecurity focus (SOC, SIEM monitoring, threat detection), with projects and experience documented in a “case file” style.

---

## Live Preview

Open the file in your browser:

- **`Index.html`**

If you deploy to GitHub Pages or another static host, you can use `Index.html` as the entry point.

---

## How to Run

Because this is a single-file app, there is no build step.

### Option A (recommended): Open locally
1. Double-click **`Index.html`**
2. Or open it in your browser via your file explorer

### Option B: Serve via a simple local server (optional)
Some browsers behave better with a local HTTP server than with `file://`.

If you already have Python installed:

```bash
python -m http.server 5500
```

Then open:

- `http://localhost:5500/`

---

## Project Structure

This repository contains a single HTML file:

- **`Index.html`** — All styles and scripts are embedded in this file.

---

## What’s Included

### 1) Navigation & Sections
The site is organized into anchored sections:

- Home
- About
- Results
- Why Hire Me
- Skills
- Projects (Case Files)
- Experience
- Education
- Journey
- Contact

Includes a **scroll-spy** active state using `IntersectionObserver`.

### 2) Performance & UX Enhancements
- Intro **loader** screen
- **Reveal-on-scroll** animations (`.reveal` elements)
- **Count-up** metrics for the “Results” section
- Mobile-friendly navigation toggle (hamburger button)
- Hero background network visualization on canvas
  - Respects **`prefers-reduced-motion`**

### 3) Contact
The contact form opens the default email client using `mailto:` with:
- Recipient: `niyaparvin626@gmail.com`
- Subject: `Portfolio Contact — <name>`
- Body: includes the message + sender details


---

## Featured Content (From the Page)

### Featured Projects (Case Files)
- **CASE FILE 001 — Interactive Museum QR System**
  - Bilingual exhibit access via QR codes
  - Admin panel + event registration (as described in the page)
  - Tech mentioned: Python, Django, MySQL, HTML, CSS, Bootstrap

- **CASE FILE 002 — SIEM Log Monitoring & Detection**
  - Splunk-based ingestion and monitoring
  - Detection rules described (e.g., failed logins, anomalous traffic)
  - Result described: end-to-end SIEM detection workflows

### Skills
Includes tags across Security, Networking, Operating Systems, Programming, and Tools.

### Experience
Two internships are listed:
- Techmindz (Apr 2023 – May 2023)
- Ociuz Skills Academy (Nov 2024 – Feb 2025)

### Education
- Advanced Diploma in Cyber Defense — in progress
- B.Voc. in Web Technology — completed (CGPA 7.38)

---

## Social & Contact Links

The page links to:
- LinkedIn: https://www.linkedin.com/in/niya-parvin/
- GitHub: https://github.com/niya-parvin
- Email: mailto:niyaparvin626@gmail.com


---

## Deployment Notes

This is a static site. Recommended approaches:

- GitHub Pages (static hosting)
- Netlify / Vercel static deploy
- Any static file host

Because everything is embedded, simply publish the `Index.html`
---

## Security/Privacy Notes

- The site does not upload form data to a server.
- Contact form uses `mailto:` so user message handling stays on the client/device.

---

## Credits

Built as a single-file portfolio app with embedded styles and scripts for ease of sharing.

