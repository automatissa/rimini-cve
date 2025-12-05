# Rimini CVE — Static Site Viewer

This repository contains a small static site for viewing CVE/Threat-Risk visualizations.

**Project**
- **Name**: `rimini-cve`
- **Purpose**: Provide static HTML visualizations of threat/risk data you can open locally or serve from a simple HTTP server.

**Files**
- **`index.html`**: Main site entry — open in a browser.
- **`Threat_Risk_Scatter.html`**: Individual visualization (scatter plot) you can view directly.
- **`LICENSE`**: Project license.
- **`README.md`**: This file (usage instructions).

**Quick Start**
- **Open directly in a browser**: Double-click `rimini-cve\index.html` (or right-click -> Open) to view the site locally. This works in most modern browsers for static content.
- **Run a simple local HTTP server (recommended)**: Some visualizations or scripts require a web server (same-origin). From the project root open PowerShell and run:

```powershell
python -m http.server 8000
```

Then open the site in your default browser:

```powershell
Start-Process "http://localhost:8000/rimini-cve/index.html"
```

If you don't have Python, you can install it from https://www.python.org/ or use any static server tool (Node's `http-server`, VS Code Live Server extension, etc.).

**Notes**
- **Static site**: This repo is a static site — no backend/server code is required beyond serving files.
- **Data/scripts**: If visualizations load external data (CSV/JSON), run via a local HTTP server to avoid browser CORS/file access issues.

**License**
- See the `LICENSE` file for license details.

**Next steps / Help**
- **Edit content**: To change text or visualizations, edit the HTML/JS files inside `rimini-cve/` and reload the page.
- **Commit changes**: If you'd like, I can create a Git commit with this `README.md` for you.
- **Questions?**: Tell me if you want the README expanded (development instructions, badges, screenshots), or if you want me to commit the change.
