# jessding.github.io

Jekyll-based personal site.

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000`.

## Add a page

Create a Markdown file at the repo root (e.g. `projects.md`) with this front matter:

```markdown
---
layout: page
title: Projects
permalink: /projects/
---

Your content here.
```

Then link to it from `index.md` or the nav in `_layouts/default.html`.
