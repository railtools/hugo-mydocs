# 📚 Hugo Docs – Railway Template

A minimal Hugo documentation site using the [Hugo Book theme](https://github.com/alex-shpak/hugo-book), deployed on [Railway](https://railway.app) with [Nixpacks](https://nixpacks.com) for zero-config setup.

## 🌐 Features

- ✅ Instant deployment with Hugo pre-installed (via Nixpacks)
- ✅ No Dockerfile required
- 🌍 Dynamic `baseURL` from Railway's public URL
- 📖 [Hugo Book theme](https://github.com/alex-shpak/hugo-book) via Hugo Modules
- 🗂️ Automatic tree-structured navigation from content
- 🌙 Built-in dark mode support
- 📱 Mobile-friendly responsive design
- 🌟 Production build with Hugo and static serving via Caddy

---

## 🚀 Deploy
[![Deploy on Railway](https://railway.com/button.svg)](https://railway.com/deploy/hugo-docs?referralCode=dPr4mc)
---

## 👋 Notes

- Hugo is installed dynamically using Nixpacks — no manual install or image needed.
- Caddy serves your production-ready static files from the `public/` folder.
- The [Hugo Book theme](https://github.com/alex-shpak/hugo-book) is loaded via Hugo Modules — clean documentation layout out of the box.
- Content in `content/docs/` automatically generates navigation menu based on folder structure.
- Use `weight` and `title` in front matter to control menu ordering.

Read more about the theme [here](https://github.com/alex-shpak/hugo-book)