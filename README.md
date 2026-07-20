# Mayur Pagote — Portfolio

My personal developer portfolio, built as a single-page site with vanilla HTML, CSS, and JavaScript.

🔗 **Live:** [mayurpagote.dev](https://mayurpagote.dev)

## Overview

- **About** — intro with a profile photo and a fun "DLSS upscaling" toggle animation
- **Experience** — education timeline and work/research experience
- **Projects** — featured project cards, including a small embedded riddle game
- **Certifications** — certificates and badges
- **Extra** — stats, achievements, and hobbies

## Tech Stack

- HTML5, CSS3, JavaScript (vanilla, no framework)
- [Lenis](https://github.com/darkroomengineering/lenis) for smooth scrolling
- Light/dark theme toggle
- Hosted on GitHub Pages with a custom domain

## Project Structure

```
├── index.html          # Main page
├── css/style.css       # Styles
├── js/
│   ├── theme.js        # Theme toggle & interactions
│   └── lenis.min.js    # Smooth scroll library
├── assets/             # Images, icons, badges, certificates
├── docs/                # Resume & recommendation letter
├── CNAME                # Custom domain config
├── robots.txt / sitemap.xml
```

## Running Locally

This is a static site — just open `index.html` in a browser, or serve it locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.
