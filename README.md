# 終幀捕手 (ClipTail Capturer) 🎞️

### [LIVE DEMO HERE](https://lunarlunar.github.io/ClipTail_Capturer/index.html)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) 
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

> **一款輕量、極速、純前端的「影片結尾截圖提取工具」，專為需要在影片最後一秒捕捉關鍵畫面的創作者與開發者打造。**

## 📖 專案介紹 (Introduction)
無論你是需要提取短影音 (Shorts, Reels, TikTok) 的結尾畫面、擷取 YouTube 影片的 End Screen (片尾畫面)，還是記錄遊戲錄影的最終結算畫面，**ClipTail Capturer (終幀捕手)** 都能為你代為勞。

只需將你的 MP4 影片拖曳或上傳到瀏覽器中，本工具將自動從影片的**最後 0.5 秒提取 5 張連續高畫質截圖**。全程在您的裝置端 (Client-side) 進行處理，**不會將檔案上傳至任何雲端伺服器**，100% 確保您的隱私與資料安全。

## ✨ 核心特色與實用性 (Key Features)
* 🔒 **極致隱私保護 (Privacy-First)**：採用 HTML5 `<video>` 與 `<canvas>` API，純瀏覽器端運算，無後端伺服器參與，機密影片不怕外流。
* ⚡ **零延遲極速處理 (Lightning Fast)**：無須等待上傳與下載，本機直接解析影片源碼並進行精確的時間軸定位 (Seeking)。
* 🎯 **精確定位最後半秒 (Precision Tracking)**：自動讀取影片 MetaData 並跳轉至 `Duration - 0.5s` 的時間點，無須再手動拖拽進度條碰運氣。
* 📥 **一鍵批次預覽與下載 (Batch Download)**：清楚的網格 (Grid) 預覽介面，點擊圖片下方即可單獨下載時間戳記命名的 `.png` 圖檔。
* 📱 **響應式現代設計 (Responsive UI)**：由 Tailwind CSS 刻劃的現代化 UI，在手機、平板與桌機上均能獲得完美的使用體驗。

## 🔍 SEO 關鍵字友好 (SEO Optimization)
本開源專案與工具非常適合以下情境與搜尋意圖：
`影片截圖工具`、`自動擷取影片畫面`、`HTML5 Video 截圖`、`MP4 結尾畫面提取`、`純前端影片處理`、`JavaScript Video Frame Capture`、`Video Ending Screenshot Extractor`

## 🚀 快速開始 (Quick Start)

### 方式一：直接開啟網頁使用
本工具無須任何安裝環境或依賴套件。
1. 將 Repository 下載或 Clone 到本地：
   ```bash
   git clone https://github.com/your-username/ClipTail-Capturer.git
   ```
2. 直接使用瀏覽器 (Chrome, Edge, Safari 等) 開啟 `CTC.html`。
3. 點選「上傳影片 (僅支援 MP4)」，並按下「提取截圖」按鈕。

### 方式二：部署至 GitHub Pages
您可以直接將此專案部署到 [GitHub Pages](https://pages.github.com/) 或 [Vercel](https://vercel.com/)，作為線上工具提供給所有人使用。因其為純靜態頁面 (Static Site)，支援一鍵無縫部署。

## 🛠️ 技術棧 (Tech Stack)
* **HTML5** (`<input type="file">`, `<video>`, `<canvas>`)
* **Vanilla JavaScript** (ES6+, Promise, Async/Await)
* **Tailwind CSS** (透過 CDN 引入，極速構建 UI)
* **Google Fonts** (Inter 字體)

## 💡 應用場景範例 (Use Cases)
* **短影音創作者**：提取影片最後的「訂閱、點讚」呼籲畫面，做為封面或素材。
* **QA / 測試工程師**：錄製 Bug 重現影片時，自動擷取影片最後報錯停止的那一瞬間作為 Issue 附圖。
* **遊戲玩家**：提取遊戲通關、吃雞或破紀錄的最後結算畫面。
* **影音編輯**：快速預覽影片有沒有被提前裁切結尾。

## 🤝 貢獻指南 (Contributing)
歡迎提交 Issues 和 Pull Requests！如果您有希望添加的新功能（例如：自訂提取時長、支援其他影片格式、或打包成 ZIP 檔下載），請大方地發起 PR！

## 📜 授權條款 (License)
本專案採用 [MIT License](LICENSE) 授權。您可以自由地使用、修改與分發本軟體。
