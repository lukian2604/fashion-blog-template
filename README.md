# Fashion Blog Template

🔗 **Live Site:** fashion-blog-template

---

## About

Fashion Blog Template is a responsive blog layout for a modern fashion and lifestyle publication. The design focuses on a clean, editorial aesthetic with elegant typography and a structured grid layout — built entirely with HTML and CSS, no frameworks.

---

## Sections

- **Header** — logo, navigation menu with links
- **Banner** — hero section with category label, title, and post meta
- **Post Grid (Top)** — 6-card grid with image, category, title, and date
- **Featured Post** — large highlighted article with description text
- **Post Grid (Bottom)** — 4-card grid continuing the post list
- **Pagination** — numbered navigation with older/next post links
- **Sidebar** — author bio, featured posts, categories, social media counters, tags
- **Footer** — Instagram image gallery, logo, navigation, social icons, copyright

---

## Tech Stack

| Technology | Details |
|---|---|
| HTML5 | Semantic markup |
| CSS3 | Custom properties, Flexbox, Grid |
| Fonts | PT Serif Regular/Bold, PT Sans Regular, Hanken Grotesk — self-hosted `.woff2` |
| Icons | Custom SVG icons |
| Images | JPG / SVG assets |

---

## Project Structure

```
fashion-blog-template/
├── index.html
├── fonts/
│   ├── HankenGrotesk-Regular.woff2
│   ├── PTSans-Regular.woff2
│   ├── PTSerif-Bold.woff2
│   └── PTSerif-Regular.woff2
├── icons/
│   ├── logo.svg
│   ├── left-arrow.svg
│   ├── right-arrow.svg
│   └── social-media/
│       ├── facebook.svg
│       ├── instagram.svg
│       ├── twitter.svg
│       ├── pinterest.svg
│       ├── youtube.svg
│       ├── behance.svg
│       ├── dribbble.svg
│       ├── vimeo.svg
│       └── Group.svg
├── images/
│   ├── banner-image.jpg
│   ├── posts/               # 11 post images
│   ├── sidebar-posts-foto/  # 4 sidebar images
│   └── footer-image/        # 6 Instagram gallery images
└── styles/
    ├── normalize.css
    └── style.css
```

---

## Getting Started

No build step required — open `index.html` directly in a browser or serve with any static file server:

```bash
# Using VS Code Live Server, or:
npx serve .
```

---

## Deployment

This project is deployed via GitHub Pages from the `main` branch root.  
After publishing, replace the link at the top of this README with your live URL.
