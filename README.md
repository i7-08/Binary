# 🛠️ Modern Binary Converter

A lightweight, minimal, and lightning-fast developer utility that handles real-time translation between plain text strings and raw binary data. It automatically adapts to your operating system's light or dark mode theme.

Live demo link can be placed directly in your repository settings under the **GitHub Pages** section!

---

## ✨ Key Features

* **Instant Sync (Real-time Typing):** No bulky buttons required. Translates as you type on either side.
* **Smart Data Trackers:** Live byte-level character count and active bit counts (ignoring spaces).
* **Local Actions:** One-click clipboard copying, canvas clearing, and direct `.txt` file downloading.
* **Auto Theme Adapting:** Built using native CSS media queries to respect OS-level Light/Dark preference configurations.
* **Zero Dependencies:** Formed completely on minimalist structural standards (Pure HTML5, CSS3, Vanilla JS).

---

## 🚀 Deployment Instructions (GitHub Pages)

Setting this up as your own public live utility page takes less than a minute:

1. Create a repository on your GitHub account (e.g., `binary-converter`).
2. Upload the `index.html` file into the main/root branch.
3. Go to your repository **Settings** tab.
4. On the sidebar menu under "Code and automation", click **Pages**.
5. Under **Build and deployment**, set the source to **Deploy from a branch**.
6. Select your branch (usually `main` or `master`) and folder (`/root`), then hit **Save**.
7. GitHub will provide you with a live link (e.g., `https://yourusername.github.io/binary-converter/`).

---

## 🛠️ Tech Stack & Structure

* **Markup:** Semantic HTML5 Structure
* **Styling:** CSS Custom Properties (Variables) with `prefers-color-scheme` query control.
* **Logic:** Pure modern asynchronous JavaScript (`navigator.clipboard` APIs and Object Blob compilation).

```text
├── index.html     # Single-file application codebase (HTML, CSS, JS)
└── README.md      # Repository documentation