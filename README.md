# Ruiyu Shen's Blog

A personal blog for sharing ideas, insights, and experiences.

## Features

- 📝 Clean, modern blog design
- 📱 Fully responsive (mobile and desktop)
- 🎨 Professional styling with gradient hero section
- 📄 Multiple blog posts
- ℹ️ About page
- 🧭 Easy navigation

## Structure

```
.
├── index.html              # Homepage with blog post listings
├── about.html              # About page
├── styles.css              # All styling and responsive design
└── posts/                  # Blog posts directory
    ├── getting-started.html
    ├── why-write.html
    └── future-of-tech.html
```

## Adding New Blog Posts

To add a new blog post:

1. Create a new HTML file in the `posts/` directory
2. Copy the structure from an existing post (e.g., `posts/getting-started.html`)
3. Update the title, date, and content
4. Add a link to the new post in `index.html`

## Local Development

To view the blog locally, start a simple HTTP server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Deployment

This site is designed to be deployed on GitHub Pages. Once merged to the main branch, it will be automatically available at your GitHub Pages URL.