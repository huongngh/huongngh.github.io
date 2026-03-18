# My Portfolio Website

Personal site built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme. Deployed automatically via GitHub Actions to GitHub Pages.

🌐 **Live site:** [huongngh.github.io](https://huongngh.github.io)

---

## What's inside

- **About** — A little about me
- **Projects** — Data engineering projects I've worked on
- **Posts** — Book reviews and things I'm thinking about
- **Reading** — Essays and articles from around the internet worth saving

---

## Stack

- [Hugo](https://gohugo.io/) — Static site generator
- [PaperMod](https://github.com/adityatelange/hugo-PaperMod) — Theme
- [GitHub Actions](https://github.com/features/actions) — CI/CD
- [GitHub Pages](https://pages.github.com/) — Hosting

---

## Run locally
```bash
git clone https://github.com/huongngh/huongngh.github.io
cd huongngh.github.io
git submodule update --init --recursive
hugo server -D
```

Open [http://localhost:1313](http://localhost:1313)

---

## Add a new post
```bash
hugo new posts/your-post-title.md
# edit the file, set draft: false
git add .
git commit -m "feat: add post - your post title"
git push origin main
```

---

*Made with curiosity and too much matcha. 🍵*