# Blog Posts

This repo contains the markdown posts for [devlog](https://your-site-url.com). Drop a `.md` file in the `posts/` folder and it goes live automatically.

## Post Format

Every file in `posts/` must be a `.md` file with YAML frontmatter:

```markdown
---
title: "Your Post Title"
date: "2026-03-12"
tags: ["Tag One", "Tag Two"]
excerpt: "A one-line summary shown on the homepage."
---

Your post content here in standard markdown...

## Headings become TOC entries

Regular paragraphs, **bold**, *italic*, `inline code`, [links](https://example.com).

> Blockquotes work too.

- Unordered lists
- Like this

1. Ordered lists
2. Like this

\`\`\`python
# Code blocks with language hints
print("hello world")
\`\`\`
```

## Rules

| Field     | Required | Format                                      |
|-----------|----------|---------------------------------------------|
| `title`   | Yes      | Quoted string                               |
| `date`    | Yes      | `"YYYY-MM-DD"` format                       |
| `tags`    | Yes      | Array of quoted strings `["A", "B"]`        |
| `excerpt` | Yes      | Quoted string, 1-2 sentences                |

## File naming

The filename becomes the URL slug:
- `my-cool-post.md` → `/blog/my-cool-post`
- Use lowercase, hyphens only, no spaces

## Adding a new post

1. Create a new `.md` file in `posts/`
2. Add the frontmatter header
3. Write your content
4. Commit and push

The site fetches posts from this repo at runtime via the GitHub API — no rebuild needed.

## Folder structure

```
blog-posts/
├── README.md
└── posts/
    ├── building-kavach-safety-systems.md
    ├── ota-firmware-updates-bare-metal.md
    └── ...
```