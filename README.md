# GEN Engine Insights

> Expert insights on AI search engine optimization and Generative Engine Optimization (GEO)

A high-performance blog built with Astro 4.1, React 18, and Tailwind CSS, optimized for AI search engine discovery.

## Live Site

🌐 [https://genengineinsights.com](https://genengineinsights.com)

## Tech Stack

- **Framework**: [Astro 4.1](https://astro.build) - Static site generation
- **UI**: [React 18](https://react.dev) + [Tailwind CSS](https://tailwindcss.com)
- **Hosting**: [Vercel](https://vercel.com)
- **CDN/DNS**: [Cloudflare](https://cloudflare.com)
- **Sitemap**: Auto-generated via @astrojs/sitemap

## Features

- ✅ AI crawler optimized robots.txt (GPTBot, ClaudeBot, PerplexityBot)
- ✅ Auto-generated sitemap
- ✅ Open Graph & Twitter Card meta tags
- ✅ Fully responsive design
- ✅ PageSpeed 95+ score
- ✅ TypeScript support
- ✅ SEO-optimized structure

## Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Project Structure

```
/
├── public/
│   ├── favicon.svg
│   └── robots.txt
├── src/
│   ├── components/
│   │   ├── BlogCard.astro
│   │   ├── Footer.astro
│   │   └── Header.astro
│   ├── layouts/
│   │   ├── BaseLayout.astro
│   │   └── BlogPostLayout.astro
│   ├── pages/
│   │   ├── blog/
│   │   │   ├── index.astro
│   │   │   └── *.md        # Blog posts
│   │   ├── 404.astro
│   │   ├── about.astro
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
├── tailwind.config.mjs
└── tsconfig.json
```

## Adding Blog Posts

Create a new `.md` file in `src/pages/blog/`:

```markdown
---
title: "Your Post Title"
description: "Brief description for SEO"
pubDate: 2025-01-01
slug: "your-post-slug"
tags: ["GEO", "AI Search"]
author: "Your Name"
---

Your content here...
```

## Deployment

This project deploys automatically to Vercel on every push to the `main` branch.

## License

MIT
