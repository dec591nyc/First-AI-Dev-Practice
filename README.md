# First-AI-Dev-Practice: Dynamic Glassmorphic Time Dashboard

A beautiful, premium, and interactive single-page digital clock and time dashboard designed as the first project for the Industrial Training program. It showcases high-end frontend capabilities utilizing modern typography, dynamic CSS variables, glassmorphic layout card styling, and subtle micro-animations.

🔗 **Portfolio Integration**: [https://17s-portfolio.vercel.app/](https://17s-portfolio.vercel.app/)

---

## ✨ Features

- **Dynamic Theme Customizer**: Interactive background theme selector supporting three unique styles:
  - 🍃 **Olive Glass**: Clean earthy beige-grey with olive highlights.
  - 🍊 **Warm Orange Glass**: Rich sunset charcoal and orange.
  - indigo **Slate Cyber Glass**: Futuristic dark violet and royal blue.
- **Mouse spotlight refraction tracker**: A premium light reflection effect following mouse coordinates in real-time.
- **Day Progress bar**: Tracks and renders the current day's time elapsed percentage down to the millisecond.
- **Multilingual Support**: Natively toggles strings and calendar settings between English (EN) and Traditional Chinese (繁中).
- **12H / 24H clock formats**: Quick toggles for time notation with persistent digital seconds.
- **UTC Timezone detector**: Automatically retrieves local system timezone offset and location name.
- **Inspirational quotes engine**: A randomized collection of developer and data engineer quotes.

---

## 🚀 How to Run Locally

Since this project is a standalone single-page application built with vanilla web technologies, running it requires no configuration or build step:

1. **Option A**: Double-click the `index.html` file in your system file explorer to open it in any web browser.
2. **Option B**: Spin up a simple HTTP server using Python:
   ```bash
   python -m http.server 8000
   ```
   Then navigate to `http://localhost:8000` in your web browser.

---

## 📁 Repository Structure

```
First-AI-Dev-Practice/
├── index.html        # Main HTML layout, inline CSS stylesheets, and interactive JavaScript logic
└── README.md         # Documentation and guide
```

---

## 🛠️ Technology Stack

- **Structure**: Semantic HTML5 markup
- **Styling**: Vanilla CSS3, custom CSS Variables (`:root`), Flexbox layouts, Backdrop-filter effects (glassmorphism)
- **Logic**: Vanilla ES6 Javascript (DOM manipulation, Date API, interval rendering, and mouse event tracking)
- **Typography**: Google Fonts (Outfit, Plus Jakarta Sans, Share Tech Mono)
