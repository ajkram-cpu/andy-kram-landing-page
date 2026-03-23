# STANDARDS.md

## BAIS:3300 - Digital Product Management · Module 8 | Personal Landing Page Project

## 1. Project Overview
This project is a personal professional landing page for Andy Kram, a Business Analytics student at the University of Iowa. The goal is to present a clean, credible, and easy-to-scan overview of his skills, projects, and career interests for recruiters and hiring managers.

A successful outcome is a responsive single-page site that communicates value within 30–60 seconds and makes it easy for visitors to learn more or get in touch.

## 2. Technical Standards
- HTML5 semantic structure only
- CSS3 in `css/stylesheet.css`
- No inline styles and no `<style>` blocks in HTML
- Static site only
- Single `index.html` file at root
- Images stored locally in `/images`
- Responsive from 320px and wider
- No horizontal scrolling
- WCAG 2.2 AA accessibility targets
- External links use `target="_blank"` and `rel="noopener noreferrer"`

### Folder structure
```text
/landing-page
├── index.html
├── PRD.md
├── STANDARDS.md
├── WORKING_NOTES.md
├── /css
│   └── stylesheet.css
├── /js
│   └── scripts.js
└── /images
    └── headshot.jpg
```

### Framework
- No framework — vanilla CSS only

## 3. Design Standards
### Color palette
- Background: `#F8F9FA`
- Primary text: `#212529`
- Accent: `#0D6E6E`
- Secondary background: `#E9ECEF`

### Typography
- Font family: Inter
- Body size: 16px
- Line height: 1.6
- H1: 1.75rem bold
- H2: 1.25rem bold

### Imagery
- One professional headshot only
- No stock images
- No emojis

### Layout
- Max content width: 800px
- Sticky top navigation with anchor links
- 60px vertical section spacing
- Single-column mobile-first layout

### Tone
- Professional
- Approachable
- Data-driven
- First-person writing
- Clear and direct language
