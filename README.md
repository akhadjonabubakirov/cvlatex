# LaTeX CV Builder

A questionnaire-style web app that generates a LaTeX CV. Fill in the form, preview the CV live, then either print/save it as PDF directly or copy the generated LaTeX code into Overleaf.

**Live site:** https://akhadjonabubakirov.github.io/cvlatex/

## Features
- Step-by-step questionnaire (personal details, education, experience, projects, skills, extras)
- Two templates: Academic (navy, master's application style) and Classic (Jake Gutierrez / sb2nov style)
- Live visual preview and generated LaTeX source
- Print / Save as PDF button
- Data is saved in your browser (localStorage) — nothing leaves your machine

## Usage
Open the site, fill the form, switch templates at the top, and use **Print / Save as PDF**. For a compiled LaTeX PDF, copy the code from the LaTeX tab into [Overleaf](https://overleaf.com).

## Development
The app is a single self-contained `index.html` (React 18 + Babel standalone + Tailwind via CDN). Open it directly in a browser or serve it with `python -m http.server`.

Deployment is automatic via GitHub Actions (see `.github/workflows/deploy-pages.yml`).
