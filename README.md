# 數位時鐘與時間儀表板

本專案為職前培訓的第一份練習作業，主要用於熟悉前端排版與動態邏輯互動。

一個基於純前端技術 (HTML/CSS/JS) 建構的單頁面數位時鐘與時間資訊儀表板。

🔗 [**Live Demo**](https://dec591nyc.github.io/First-AI-Dev-Practice/)

---

## ✨ 核心功能

- **🎨 多主題面板切換**: 支援四種不同風格的背景與卡片主題：
  - 🍃 **Olive Glass (橄欖綠)**: 沉穩的大地綠色調。
  - 🍊 **Warm Orange Glass (暖陽橘)**: 活力的深橘色調。
  - 🌌 **Slate Cyber Glass (極客藍)**: 科技感的藍紫色調。
  - 🥛 **Beige Sand Glass (燕麥米色)**: 簡約柔和的淺米色調。
- **🖱️ 鼠標光暈追蹤**: 卡片背景會隨著滑鼠游標移動產生對應的局部光暈反射效果。
- **⏳ 今日時間流逝進度條**: 即時計算並以進度條與百分比 (精確至小數點後三位) 呈現當天已過去的時間比例。
- **🌐 雙語系支援**: 支援英文 (EN) 與繁體中文 (繁中) 的文字與日期格式切換。
- **⏰ 12H / 24H 制切換**: 可自由切換 12 小時制或 24 小時制顯示。
- **🌍 時區自動偵測**: 自動讀取當前系統的時區偏移量 (UTC Offset) 及時區名稱。
- **💬 隨機金句引擎**: 內置一組隨機重新整理的開發者名言金句。

---

## 🚀 如何在本地執行

本專案為純前端網頁，無須任何建置或打包步驟：

1. **直接開啟**: 在檔案瀏覽器中雙擊 `index.html` 即可在瀏覽器中開啟。
2. **使用 HTTP 伺服器**: 使用 Python 於本地建立靜態伺服器：
   ```bash
   python -m http.server 8000
   ```
   接著在瀏覽器中輸入 `http://localhost:8000` 即可訪問。

---

## 📁 目錄結構

```
First-AI-Dev-Practice/
├── index.html        # 主網頁 (包含 HTML 架構、CSS 樣式與 JS 邏輯)
└── README.md         # 專案說明文件
```

---

## 🛠️ 技術使用

- **結構**: HTML5 語意化標記
- **樣式**: CSS3 (使用自定義 CSS 變數、Flexbox 佈局與 Backdrop-filter 毛玻璃效果)
- **邏輯**: 原生 ES6 JavaScript (DOM 操作、Date 時間 API、定時器與滑鼠事件監聽)
- **字型**: Google Fonts (Outfit, Plus Jakarta Sans, Share Tech Mono)
