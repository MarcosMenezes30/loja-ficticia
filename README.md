# MB - Marcão Burguer | Institutional Mini Website

A responsive institutional mini website developed for **MB - Marcão Burguer**, a fictional burger restaurant.

This repository was created as part of a **college assignment** focused on front-end fundamentals, semantic HTML structure, and responsive CSS styling for small business web presence.

## Academic Context

- **Project type:** University coursework / practical assignment
- **Objective:** Build a simple, modern, and responsive institutional website
- **Scope:** Multi-page static website (Home, About, Contact)
- **Course focus:** HTML semantics, CSS layout, responsive design, and basic UX patterns

## Project Overview

The website was designed to provide a fast online presence for a small business, with clear navigation and essential communication channels.

### Implemented Pages

- `index.html` (Home)
- `sobre.html` (About)
- `contato.html` (Contact)

### Core Requirements Covered

- Header with brand name and logo
- Internal navigation menu across all pages
- Footer with basic institutional information
- CTA button on Home page
- Benefit cards section
- About section with company history and mission/vision/values
- Contact form (Name, Email, Message)
- External social link, `mailto`, and `tel` links
- Shared stylesheet (`style.css`) for all pages
- Responsive behavior for smaller screens (stacked cards)
- Favicon set from project logo

## Visual Identity

The interface color palette is based on the brand logo (`images/logo.png`), using warm tones commonly associated with burger restaurants:

- Deep red
- Orange
- Yellow/gold accents
- Dark brown for contrast

## Tech Stack

- **HTML5** (semantic structure)
- **CSS3** (layout, hover interactions, responsive rules)
- No frameworks or external dependencies

## Project Structure

```text
loja-ficticia/
├── contato.html
├── index.html
├── sobre.html
├── style.css
├── images/
│   └── logo.png
└── README.md
```

## How to Run Locally

1. Clone this repository:

```bash
git clone <repository-url>
cd loja-ficticia
```

2. Open `index.html` in your browser.

No build step, package installation, or server is required for the current version.

## Responsiveness

The layout uses a centered content container with max width and includes a media query for smaller screens. In mobile view, card sections become a single-column stack for improved readability.

## Future Improvements

- Add JavaScript form handling and validation feedback
- Integrate WhatsApp direct contact CTA
- Improve accessibility with stronger ARIA coverage and focus states
- Add deployment pipeline (GitHub Pages / Netlify / Vercel)

## Author

Developed as an academic project for college coursework.

## License

This project is intended for educational purposes.
