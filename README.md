# Animeiverse — Solo Leveling

An unofficial, fan-focused Solo Leveling website with news, character profiles, episode information, artwork, and original guides.

## Visit the site

- **Public Google Sites page:** [Animeiverse Solo Leveling](https://sites.google.com/view/animeiversesololeveling/home)
- **GitHub Pages version:** [Open the site](https://rajulapati-praveen.github.io/animeiverse-solo-leveling/)

The Google Sites page embeds the GitHub Pages site. Both versions use the same static site files in this repository.

## What’s included

- Responsive Solo Leveling-inspired design for desktop and mobile.
- News and article highlights with links to sources.
- Character profiles for Sung Jinwoo, Igris, Beru, and Cha Hae-In.
- Artwork gallery with an interactive image lightbox.
- Episode hub with links to official viewing and series information.
- Four in-page guides:
  - Solo Leveling watch order
  - Jinwoo’s powers explained
  - Strongest characters
  - Season 2 ending explained
- Search metadata, social sharing metadata, `robots.txt`, and XML and plain-text sitemaps.
- Mobile navigation and basic client-side newsletter form feedback.

> **Newsletter notice:** The subscription form is a front-end demonstration only. It does not send or save email addresses because no mailing-list service or backend is connected.

## Technology

This is a static website built with:

- HTML
- CSS
- Vanilla JavaScript

There are no package-manager dependencies or build step.

## Run locally

1. Clone or download this repository.
2. Open `Animeiverse_Solo_Leveling/index.html` in a web browser.

For local development, you can also serve the `Animeiverse_Solo_Leveling` folder using any static file server or a code-editor live-server extension.

## Project layout

```text
.
├── README.md
├── .github/
│   └── workflows/
│       └── pages.yml
└── Animeiverse_Solo_Leveling/
    ├── index.html
    ├── style.css
    ├── gallery.css
    ├── guides.css
    ├── script.js
    ├── robots.txt
    ├── sitemap.xml
    ├── sitemap.txt
    ├── README.txt
    └── assets/
```

## Deployment

GitHub Actions deploys the contents of `Animeiverse_Solo_Leveling/` to GitHub Pages whenever changes are pushed to the `main` branch. The workflow can also be started manually from the repository’s **Actions** tab.

Sitemap files for the GitHub Pages site:

- [XML sitemap](https://rajulapati-praveen.github.io/animeiverse-solo-leveling/sitemap.xml)
- [Plain-text sitemap](https://rajulapati-praveen.github.io/animeiverse-solo-leveling/sitemap.txt)
- [robots.txt](https://rajulapati-praveen.github.io/animeiverse-solo-leveling/robots.txt)

Google Search Console has accepted submissions for these sitemap URLs, but may take time to fetch and process them. Sitemap submission does not guarantee that Google will index every page.

## Content, images, and rights

Animeiverse is an unofficial fan project and is not affiliated with, endorsed by, or sponsored by the creators, publishers, or distributors of Solo Leveling. Solo Leveling and its characters belong to their respective rights holders.

Before reusing or republishing any artwork in `Animeiverse_Solo_Leveling/assets/`, confirm that you have the necessary permission or a suitable license. Do not use this project to distribute unauthorized episode footage, copied articles, or unlicensed material. Link to official sources where possible.

## Contributing

Improvements to accessibility, responsive behavior, accuracy, and original fan-focused writing are welcome. Please keep source links reliable, identify spoilers where appropriate, and verify rights before adding assets.

## License

No software or content reuse license is currently provided in this repository. Contact the repository owner for permission before redistributing or reusing its code, text, or assets.
