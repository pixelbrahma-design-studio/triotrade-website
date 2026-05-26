# TrioTrade — Claude Code Instructions

## Project Overview
TrioTrade is a trading/business website built with pure frontend technologies.

## Tech Stack
- **Frontend:** HTML5, CSS3
- **Forms:** Native HTML form integration (no JavaScript frameworks)

## Development Guidelines

### File Structure
```
TrioTrade/
├── index.html          # Homepage
├── css/
│   └── styles.css      # Main stylesheet
├── pages/              # Additional HTML pages
└── assets/
    ├── images/
    └── fonts/
```

### HTML
- Use semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
- All forms must include proper `name`, `id`, and `label` attributes for accessibility
- Use `required`, `type`, and `pattern` attributes for client-side form validation

### CSS
- Mobile-first responsive design using media queries
- Use CSS custom properties (variables) for colors and spacing
- No CSS frameworks — write all styles from scratch

### Forms
- Use `action` and `method` attributes on `<form>` elements
- Include CSRF-safe practices where applicable
- Validate inputs with HTML5 validation attributes before submission

## Content Reference
See `QUESTIONNAIR  FOR THE WEBSITE-TrioTrade.docx` for the full website content requirements and questionnaire answers.
