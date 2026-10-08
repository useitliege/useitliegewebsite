# USE-IT Liège

Landing page for **USE-IT Liège** — free, non-commercial city maps for young travellers, made by locals. This repository hosts a single-page static website promoting the 1st Edition map of Liège, Belgium (La Cité Ardente).

## About

USE-IT makes free city maps for young travellers, curated by local youth. No ads, no sponsored spots, no tourist traps — just honest tips on where to eat, drink, and explore like someone who lives in the city. This site introduces the project, shares the mission, highlights the map currently in production, and lets people get involved.

## Features

- Responsive, single-page layout with a playful neo-brutalist design
- Hero section with the project pitch and a feature image
- About section explaining the USE-IT mission
- "Map in Production" section tracking the 1st Edition progress
- USE-IT Europe network section
- Contact form powered by [Web3Forms](https://web3forms.com) with inline success feedback
- Mobile navigation menu
- Footer with the legal publisher details (Oufteam 4000 VZW)

## Tech Stack

- **HTML5** — single `index.html` entry point
- **[Tailwind CSS](https://tailwindcss.com)** — loaded via CDN
- **[Font Awesome](https://fontawesome.com)** — icons via CDN
- **[Google Fonts](https://fonts.google.com)** — Fredoka and Plus Jakarta Sans
- **[Web3Forms](https://web3forms.com)** — serverless contact form handling
- Vanilla JavaScript for the mobile menu and AJAX form submission

No build step or dependencies to install — it is a static site.

## Project Structure

```
.
├── index.html          # The entire site
├── assets/
│   ├── hero.jpeg       # Hero image
│   ├── useit_logo.png  # Header logo
│   └── liege_logo.jpg  # Footer logo
└── README.md
```

## Publisher

Published by **Oufteam 4000 VZW** (Liège, Belgium) — part of the USE-IT Europe network.
