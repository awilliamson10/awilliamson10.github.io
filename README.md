# awilliamson10.github.io

A simple, minimal blog built with Jekyll for GitHub Pages, inspired by [blog.wilsonl.in](https://blog.wilsonl.in/).

## Features

- Clean, minimal design
- Markdown blog posts
- Automatic reading time calculation
- RSS feed support
- Responsive design
- Dark mode support (follows system preference)

## Setup

1. Install Jekyll and dependencies:
   ```bash
   bundle install
   ```

2. Customize `_config.yml` with your information:
   - Update `title` with your name
   - Update `description` with your welcome message
   - Add your social media usernames
   - Update the `url` if needed

3. Run locally:
   ```bash
   bundle exec jekyll serve
   ```
   Then visit `http://localhost:4000`

## Writing Posts

Create a new `.md` file in the `_posts` directory with the format:
```
YYYY-MM-DD-title.md
```

Each post should start with front matter:
```yaml
---
title: Your Post Title
date: YYYY-MM-DD
icon: ✨
---
```

**Icons**: You can add an `icon` field to your post front matter. This can be:
- An emoji: `icon: ✨` or `icon: 🌲`
- An image path: `icon: /assets/art/tree.webp` (supports jpg, png, webp, gif, svg)

The icon will appear centered above the post title and next to the post title on the homepage.

Then write your content in Markdown below.

## Customization

- **Profile picture**: Edit the `.profile-picture` styles in `assets/css/style.css` or replace with an actual image
- **Colors**: Modify CSS variables in `assets/css/style.css`
- **Layout**: Edit the layout files in `_layouts/`

## Deployment

Push to the `main` branch of your GitHub repository. GitHub Pages will automatically build and deploy your site.
