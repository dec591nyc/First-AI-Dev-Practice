# First-AI-Dev-Practice: 互動式磨砂玻璃時間儀表板 (Dynamic Glassmorphic Time Dashboard)

一個精美、高品質且具備高度互動性的單頁面數位時鐘與時間儀表板。本專案為職前培訓課程的第一份作業，旨在展現前端開發的高階視覺呈現能力，運用現代排版、動態 CSS 變數、毛玻璃（Glassmorphism）卡片樣式以及細緻的微交互動畫。

🔗 **線上展示連結 (Live Demo)**: [https://dec591nyc.github.io/First-AI-Dev-Practice/](https://dec591nyc.github.io/First-AI-Dev-Practice/)  
🔗 **開發作品集連結**: [https://17s-portfolio.vercel.app/](https://17s-portfolio.vercel.app/)

---

## ✨ 核心特色

- **🎨 動態面板主題切換**: 支援四種獨特視覺風格的互動式背景主題：
  - 🍃 **Olive Glass (橄欖綠玻璃)**: 舒適沉穩的自然大地色系搭配橄欖綠點綴。
  - 🍊 **Warm Orange Glass (暖陽橘玻璃)**: 充滿活力的日落炭黑與溫暖橘。
  - 🌌 **Slate Cyber Glass (極客藍玻璃)**: 科技感十足的深紫與皇家藍色調。
  - 🥛 **Beige Sand Glass (燕麥米色玻璃)**: [新增] 溫暖典雅的淺色奶茶燕麥色，搭配奶油與沙岩色調，帶來質感絕佳的淺色視覺體驗。
- **🖱️ 滑鼠折射光效追蹤 (Spotlight Refraction)**: 卡片背景會即時追蹤滑鼠的座標，產生精緻的動態光暈折射效果。
- **⏳ 今日時間流逝進度條**: 以毫秒級的高精度即時計算並渲染當天已過去的時間百分比。
- **🌐 雙語介面切換**: 原生支援英文 (EN) 與繁體中文 (繁中) 之間的字串及日曆語系切換。
- **⏰ 12H / 24H 制切換**: 快速切換時間顯示格式，並保留流暢的秒數顯示。
- **🌍 系統時區自動偵測**: 自動讀取本地系統的時區偏移量 (UTC Offset) 與地理時區名稱。
- **💬 靈感金句引擎**: 內置精選的程式設計師與數據工程師名言金句，點擊即可隨機刷新。

---

## 🚀 如何在本地運行

本專案為純前端單頁面應用程式 (Single Page Application)，完全採用原生網頁技術建構，無需進行任何打包或建置設定即可執行：

1. **方式 A (直接開啟)**: 在檔案瀏覽器中雙擊 `index.html` 即可在瀏覽器中直接開啟。
2. **方式 B (建立本地伺服器)**: 使用 Python 快速建立本地 HTTP 伺服器：
   ```bash
   python -m http.server 8000
   ```
   接著在瀏覽器中輸入 `http://localhost:8000` 即可開啟網頁。

---

## 📁 目錄結構

```
First-AI-Dev-Practice/
├── index.html        # 主網頁架構、內嵌 CSS 樣式及 JavaScript 互動邏輯
└── README.md         # 專案說明文件 (中文版)
```

---

## 🛠️ 技術棧

- **網頁結構**: 語意化 HTML5 標記 (Semantic HTML5)
- **視覺樣式**: 現代 CSS3、自定義 CSS 變數 (`:root`)、彈性盒版面 (Flexbox Layout)、背景濾鏡模糊效果 (Backdrop-filter Glassmorphism)
- **邏輯互動**: Vanilla ES6 JavaScript (DOM 元素操作、Date 時間 API、定時器渲染、滑鼠事件追蹤)
- **字型排版**: Google Fonts (Outfit, Plus Jakarta Sans, Share Tech Mono)
