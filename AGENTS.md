# AGENTS.md

Welcome, Agent. This manifesto provides you with the context and guidelines necessary to contribute effectively to this Portfolio project.

## 🏗️ Project Architecture

This is a professional profile and portfolio built with a minimalist and high-performance stack:
- **Frontend**: Pure HTML5, CSS3 (Vanilla), and ES6+ JavaScript.
- **Styling**: Structured via CSS Custom Properties (Variables) in `styles.css`.
- **Content**: Duplicated and synchronized between `README.md` (GitHub Profile) and `index.html` (Web Portfolio).

## 🛠️ Design System

We use a specific visual grammar. When making changes, respect these tokens:
- **Colors**: Use `--gradient-primary` for main accents and `--color-accent-purple` for highlighting.
- **Typography**: `Inter` for prose, `JetBrains Mono` for technical elements.
- **Icons**: FontAwesome v6 (Free). Always check the latest `index.html` for icon usage patterns.

## 🤖 Agent Instructions

### 1. Synchronization Rule (CRITICAL)
Any change to the **Skills**, **Projects**, or **About Me** sections must be applied to BOTH `README.md` and `index.html`. 
- **README.md**: Uses Markdown, badges, and flat lists.
- **index.html**: Uses semantic HTML, FontAwesome icons, and grid layouts.

### 2. Adding Featured Projects
When adding a project to `index.html`:
- Use the `<div class="project-card">` structure.
- Add an appropriate `fas` icon in the `.project-icon` div.
- Ensure the description is concise and highlight the tech stack using `.tag` spans.

### 3. Updating Skills
- Add new technologies to the `## 🛠️ Technologies & Tools` section in `README.md` using shields.io badges.
- Add corresponding `<span class="skill-tag">` in `index.html`.

## 📦 Deployment
The project is hosted on GitHub Pages. Changes to the `main` branch are automatically deployed.

## 📜 Coding Style
- **HTML**: Semantic tags (`section`, `div`, `strong`). Use `class` for styling, avoid inline styles.
- **CSS**: Add new styles to `styles.css` following the established section comments.
- **JS**: Vanilla JS only. Keep `script.js` concise and focused on UI interactions (typing effect, smooth scroll).
