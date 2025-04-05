*A beginner-friendly, open source platform where African Google Cloud enthusiasts can share tutorials, stories, and projects that inspire.*

[![Discord](https://img.shields.io/badge/Join-Discord-blue?style=flat&logo=discord)](https://discord.gg/your-link)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## 📁 What Is This Repo For?

This is our **community blog space**. It's where we:
- ✍🏾 Write about Google Cloud in a way Africans can relate to
- 🎓 Share tutorials using African examples and data
- 🚀 Inspire others with real-world projects and stories

Whether you're just starting or you're already deep in GCP, this is **your space**.

---

## 🔰 New Here? Start With This

### Step 1: Fork and Clone the Repo

1. Click the **Fork** button at the top-right of this page
2. Clone it to your machine:
```bash
git clone https://github.com/YOUR-USERNAME/gcp-africa-blog.git
cd gcp-africa-blog
```

### Step 2: Create Your Contribution Folder

```bash
mkdir -p contributions/your-name-or-alias/assets
cd contributions/your-name-or-alias
```

Copy the example post:
```bash
cp -r ../../TEMPLATE/* .
```

---

## ✍️ How to Write Your Blog Post (post.mdx)

Open the file `post.mdx` and fill in the following:

```mdx
---
title: "How I Deployed My First API on GCP"
author: "Ama Kwame"
date: "2025-04-01"
tags: ["gcp", "cloud-functions", "ghana"]
excerpt: "Learn how I built and deployed a serverless API using Google Cloud Functions."
coverImage: "./assets/cover.jpg"
---

## Introduction
Start by explaining what the post is about and why it’s useful for people in Africa.

## Main Content
Break things down step by step.
Use headings, code blocks, and diagrams.

<Callout type="tip">
Try using examples from your local context or country.
</Callout>

```python
# Sample Python code
from google.cloud import storage
bucket = storage.Client().bucket("my-africa-bucket")
```

![Diagram](#)

## Conclusion
Wrap up with key lessons and next steps for readers.
```

> 🎯 **Goal**: Help others learn something actionable!

---

## 🖼 Media Guidelines

| Type        | Specs                 | Tips                          |
|-------------|----------------------|-------------------------------|
| Cover Image | 1200x630px, <500KB   | Use African tech visuals      |
| Diagrams    | PNG/SVG, under 1MB   | Use clear labels and arrows   |
| Screenshots | Fullscreen, <1MB     | Blur any personal data        |

> ✅ Only share media you created or have permission to use.

---

## 📋 Checklist Before making a PR

- [ ] Does your `post.mdx` have the required frontmatter?
- [ ] Are all images in your `assets/` folder?
- [ ] Did you run a spellcheck?
- [ ] Does your post explain things clearly for beginners?


---

## 💡 Why Contribute?

| Tier       | What's Needed             | You Get...                        |
|------------|---------------------------|-----------------------------------|
| 🌱 Newbie  | 1 post accepted            | Shoutout + Discord Contributor Tag |
| 🚀 Regular | 3+ helpful posts           | Newsletter Feature                |
| 🏅 MVP     | 10+ posts or viral content | Cloud credits + free GCP swag     |

> You don’t have to be a pro — just share what you've learned!

---

## 🛠 Cool Tools You Can Use

You can include these components in your post:

```mdx
<Info>
This is a helpful tip or important note.
</Info>

<Warning>
Make sure not to share passwords or keys!
</Warning>

<CodeBlock lang="bash" title="gcloud setup">
gcloud init
</CodeBlock>
```

Supported tools:
- Diagrams (e.g. [Mermaid.js](https://mermaid.js.org/))
- GCP service code blocks (Python, Terraform, etc.)
- Callout boxes for tips and notes

---

## Need Help?

- 💬 [Join our Discord](https://discord.gg/your-link) — ask questions and get help
- 📄 [Read CONTRIBUTING.md](CONTRIBUTING.md) — advanced tips
- 📧 Email: africacloud-community@google-groups.com

---

Let’s build the future of African cloud innovation together — one post at a time. 

