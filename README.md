# Kofo Ojo — Portfolio

My personal portfolio and CV website

## Overview

This is a lightweight static website built with HTML, CSS, and vanilla JavaScript. It presents:

- Education and relevant coursework
- Microsoft-sponsored distributed systems project
- Liferay-sponsored software engineering project
- PlaylistPal full-stack group project
- Personal Flask and data analysis project
- Cultúr Migrants leadership experience
- Technical skills, concepts, and interests
- Contact information and links

## Project structure

```text
.
├── index.html   # Page content and semantic structure
├── styles.css   # Visual design, responsive layout, and animations
├── script.js    # Scroll-reveal interactions
└── README.md    # Project documentation
```

## Run locally

From the project directory:

```bash
python3 -m http.server 4173
```

Open [http://localhost:4173](http://localhost:4173) in a browser.

You can also open `index.html` directly, but using a local server is recommended for a more realistic preview.

## Test the site

Check the following areas:

1. Navigation links scroll to the Work, About, and Contact sections.
2. Project cards display the correct experience and technologies.
3. The email links use `mailto:kofoojo1@gmail.com`.
4. Scroll-reveal animations appear as sections enter the viewport.
5. The layout works at mobile, tablet, and desktop widths.
6. There is no horizontal scrolling at narrow viewport sizes.
7. The page title and meta description are correct.

Recommended viewport sizes:

- Mobile: `375px`
- Tablet: `768px`
- Desktop: `1440px`

## Customise the content

Most personal content is in [index.html](./index.html). Update:

- Name and initials in the header
- Email address
- Project descriptions and dates
- Education and coursework
- Social profile links near the bottom of the page

Update colours, spacing, typography, and responsive breakpoints in [styles.css](./styles.css).

## Deployment

Because this is a static site, it can be deployed to any static hosting provider, including:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages

No build command or package installation is required.
