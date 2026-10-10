# PRIORIX - Intelligent Ticket Management System

This package contains the complete standalone website exported from:
**https://app-ezvw5disyha9.appmedo.com/**

## Overview
PRIORIX is an enterprise support ticket management system featuring:
- Automated Priority Scoring & SLA Tracking
- AI Troubleshooting & Knowledge Base Integration
- Role-based Workflows (Customer, Support Agent, Admin)
- Real-time Analytics & Performance Reports
- Cloud-backed persistence via Supabase

---

## Directory Structure
- `index.html`: Main application entry point (configured with relative local assets)
- `index.original.html`: Original untouched HTML file
- `favicon.png`: Site favicon
- `package.json`: NPM configuration with launch scripts
- `README.md`: Documentation and running instructions
- `assets/index-BDXEjzmG.js`: Compiled React + Vite application bundle
- `assets/index-DocXIvER.css`: Tailored application stylesheet
- `assets/fonts-code.css`: Font stylesheet
- `assets/miaoda-external.js`: Helper script
- `assets/favicon.png`: Favicon icon
- `assets/fonts/`: Local font files (Alibaba PuHuiTi, Source Han Serif)

---

## How to Run Locally

Because this is a Single Page Application (SPA) using ES Modules, it should be served over HTTP/HTTPS rather than opened via the direct `file://` protocol.

### Option 1: Using Python (No installation needed)
Run in the project directory:
```bash
python3 -m http.server 3000
```
Then open your browser at: `http://localhost:3000`

### Option 2: Using Node.js / npx
Using npx serve (recommended for SPA client routing):
```bash
npx serve . -s -p 3000
```
Or with npm:
```bash
npm start
```
Then open: `http://localhost:3000`

### Option 3: Deploy to any Static Web Host
You can deploy this directory to any modern static hosting service:
- **Vercel**: Run `vercel` or link your Git repository.
- **Netlify**: Drag and drop the folder onto app.netlify.com/drop.
- **GitHub Pages**: Push to a repository and enable GitHub Pages.
- **Nginx / Apache / Caddy**: Copy the files into your web root directory.

---

## Architecture & Backend Connection
- **Frontend**: React 18, Tailwind CSS, Radix UI components, Lucide icons, Sonner notifications.
- **Backend**: Supabase Auth and Database endpoints (configured inside the bundle with live endpoints).
