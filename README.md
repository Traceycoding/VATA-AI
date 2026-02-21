# VATA — Virtual Assistant Technology Agent

VATA (pronounced **va-tuh**) is a free, public chatbot experiment designed to be simple, accessible, and easy to run anywhere — including GitHub Pages.  
This project is built for learning, creativity, and fun, with plans to grow into a fully API‑powered assistant in the future.

---

## 🚀 Features

- 🧠 **Chat UI** — Clean, modern interface with message bubbles  
- ⚡ **API‑Ready** — Front‑end already wired to call a backend when added  
- 💬 **Offline Demo Mode** — Generates placeholder replies if no API is connected  
- 📱 **Responsive Layout** — Works on desktop and mobile  
- 🎨 **Simple, lightweight design** — Pure HTML, CSS, and JavaScript  
- 🌐 **GitHub Pages Compatible** — No backend required to host the UI  

---

## 📂 Project Structure


Everything is contained in a single HTML file for simplicity.

---

## 🧩 How It Works

VATA runs entirely in the browser:

1. You type a message  
2. The UI displays it  
3. The script *tries* to send it to a backend API  
4. If no backend exists, VATA replies using a built‑in demo system  

When you eventually build a backend, just replace:

```js
const VATA_API_URL = "https://your-vata-backend.example.com/chat";
