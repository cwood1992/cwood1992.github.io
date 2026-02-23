# cwood1992.github.io

Personal blog powered by Jekyll + GitHub Pages.

## Quick Start

1. Create a new repo on GitHub named `cwood1992.github.io`
2. Push this folder to that repo
3. GitHub Pages will auto-build and serve at `https://cwood1992.github.io`

## Writing a New Post

Create a file in `_posts/` with this naming format:

```
_posts/YYYY-MM-DD-your-post-title.md
```

Start every post with frontmatter:

```yaml
---
title: "Your Post Title"
date: 2026-02-23
subtitle: "Optional subtitle that appears below the title"
---

Your content here. Just write markdown.
```

Commit and push. GitHub builds the site automatically in ~30 seconds.

## Publishing from Medium Workflow

1. Write in markdown
2. Drop the `.md` file in `_posts/` with proper frontmatter and date-prefixed filename
3. Push to GitHub — it's now live on your blog
4. Open `https://cwood1992.github.io/your-post-title/` in browser
5. Use Medium's "Import a story" feature with that URL, OR select-all + copy from the browser and paste into Medium

## Local Preview (Optional)

```bash
gem install bundler jekyll
bundle install
bundle exec jekyll serve
# Open http://localhost:4000
```

## Structure

```
├── _config.yml          # Site settings
├── _layouts/            # Page templates
├── _includes/           # Reusable components (header, footer)
├── _posts/              # Blog posts (markdown)
├── assets/css/          # Stylesheet
├── index.html           # Homepage
├── about.md             # About page
└── README.md            # This file
```
