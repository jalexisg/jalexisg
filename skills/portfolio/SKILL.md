---
name: portfolio_management
description: Skill for maintaining and updating the personal portfolio and github profile.
---

# Portfolio Management Skill

This skill provides specialized procedures for maintaining the consistency and visual quality of the portfolio.

## 📐 Design Tokens Access
- Primary Gradient: `linear-gradient(135deg, #667eea 0%, #764ba2 100%)`
- Secondary Gradient: `linear-gradient(135deg, #f093fb 0%, #f5576c 100%)`
- Background: `#0a0e27`

## 🔄 Content Synchronization Workflow

### 1. Update Profile README
- Locate the relevant section in `README.md`.
- Use GitHub formatted markdown.
- Use `shields.io` for technology badges.

### 2. Update Web Portfolio
- Locate the corresponding section in `index.html`.
- Translate content to Spanish if necessary.
- Wrap key terms in `<strong>` tags.
- Use `text-align: center;` (inherited) or `justify` with `hyphens: auto;` for paragraphs.

## 🎨 Visual Patterns
- **Skill Tags**: `<span class="skill-tag"><i class="fas fa-[icon]"></i> [Name]</span>`
- **Project Cards**: Must include a FontAwesome icon, a title, a brief description, and tech tags.

## 🧪 Verification
- Always check that `index.html` renders correctly without literal markdown symbols (e.g., `**`).
- Ensure FontAwesome icons match the category of the skill or project.
