# How to Add a New Blog Post — Primora Escape Co.

## Every new post is just one text file uploaded to GitHub.

---

### Step 1 — Create your post file

Create a new file on your computer using Notepad (Windows) or TextEdit (Mac).

The filename format MUST follow this pattern:
```
YYYY-MM-DD-your-post-title.md
```

Examples:
```
2026-04-10-best-beaches-in-batam.md
2026-05-01-bali-travel-guide-singapore.md
2026-06-15-batam-corporate-retreat-ideas.md
```

---

### Step 2 — Write your post

Copy and paste this template into your file and fill it in:

```
---
layout: post
title: "Your Article Title Here"
subtitle: "A short one-line description of the article."
date: 2026-04-10
category: Travel Guide
image: /img/blog/your-cover-image.jpg
description: "This is what Google shows in search results. Keep it under 160 characters."
---

Write your article content here.

## Use two hashes for section headings

Normal paragraphs just type as normal text.

- Use a dash for bullet points
- Like this

**Bold text** uses double asterisks.

*Italic text* uses single asterisks.

> Use a > symbol for a pull quote or highlighted tip.

![Image caption](../img/blog/your-image.jpg)
```

---

### Step 3 — Upload your cover image (optional)

If your post has a cover image:
1. Go to your GitHub repo → `img` folder → `blog` folder (create it if it doesn't exist)
2. Upload your image file there
3. Reference it in your post as `/img/blog/your-image-name.jpg`

**Tip:** Always compress images before uploading at squoosh.app — keeps your site fast.

---

### Step 4 — Upload your post to GitHub

1. Go to your GitHub repo
2. Click into the `_posts` folder
3. Click **Add file → Upload files**
4. Upload your `.md` file
5. Click **Commit changes**

Your article will be live at `primoraescape.com/blog/your-post-title/` within 2 minutes.

---

## Category options

Use one of these in the `category:` field:
- `Travel Guide`
- `Destination`
- `Corporate Travel`
- `Travel Tips`
- `Indonesia`

---

## Example of a complete post

```
---
layout: post
title: "Best Beaches in Batam for a Weekend Escape"
subtitle: "From quiet coves to water sports hubs — our guide to Batam's best shores."
date: 2026-04-10
category: Destination
image: /img/blog/batam-beaches.jpg
description: "Discover the best beaches in Batam for travellers from Singapore. From Nongsa to Ocarina, here is our complete guide."
---

Batam has more coastline than most visitors realise...

## Nongsa Beach

The most developed stretch of Batam's coastline...
```
