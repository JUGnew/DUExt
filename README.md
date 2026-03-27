# ✦ DUExt
### Download · Upload · Extract

**A free, AI-powered web tool to analyze URLs, images, files, and YouTube videos.**  
No sign-up. No API key. No cost. Just open and use.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-00e5ff?style=for-the-badge)](https://jugnew.github.io/DUExt)
[![License](https://img.shields.io/badge/License-MIT-b06eff?style=for-the-badge)](LICENSE)
[![Languages](https://img.shields.io/badge/Languages-6-00ff88?style=for-the-badge)](#)
[![Free](https://img.shields.io/badge/100%25-Free-ff7b3a?style=for-the-badge)](#)

</div>

---

## ✨ Features

- 🔗 **URL Analysis** — Summarize any webpage, extract keywords, run sentiment analysis, or get an SEO report
- 🖼️ **Image Tools** — Convert between PNG / JPEG / WebP and analyze images with AI
- 📄 **File Analysis** — Upload PDF, TXT, CSV, JSON or Markdown files and let AI summarize, extract, or translate them
- 📺 **YouTube Insights** — Paste any YouTube link and get an AI-powered breakdown of the video content
- 🌍 **6 Languages** — English, Turkish, German, French, Spanish, Arabic (with RTL support)
- 🔒 **Privacy First** — No data is stored. Files are processed in your browser session only.

---

## 🚀 Getting Started

Just open the `DUExt.html` file in any modern browser — no installation, no setup required.

```
1. Download DUExt.html
2. Open in your browser
3. Start analyzing!
```

Or visit the **[live demo →](https://jugnew.github.io/DUExt)**

---

## 🛠️ How It Works

DUExt uses a **Cloudflare Worker** as a secure proxy to handle AI requests via [Groq](https://groq.com). The API key is stored server-side and never exposed to the user.

```
User → DUExt.html → Cloudflare Worker → Groq AI → Response
```

The AI model used is **Llama 3.3 70B** (via Groq), offering fast and high-quality responses for free.

---

## 📁 Project Structure

```
DUExt/
├── DUExt.html       # Main app (single-file, no dependencies)
└── README.md
```

The Cloudflare Worker code (`worker.js`) is deployed separately and handles all API communication securely.

---

## 🌐 Deployment

To self-host DUExt with your own backend:

1. Create a free account at [Cloudflare](https://cloudflare.com)
2. Deploy `worker.js` as a Cloudflare Worker
3. Add your `GROQ_API_KEY` as an encrypted environment secret
4. Update `WORKER_URL` in `DUExt.html` to point to your Worker
5. Host `DUExt.html` anywhere (GitHub Pages, Netlify, etc.)

---

## 🤝 Contributing

Pull requests are welcome! If you find a bug or have a feature idea, feel free to open an issue.

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

<div align="center">

Built with ❤️ by the **DUA-X Team**

</div>
