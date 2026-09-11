# 𓃥 白六照片主題編輯 (White 6 Photo Depth & Motion Editor)

專為 **白六 (White 6)** 品牌打造的 Web 端 3D 景深與多圖層動態文字編輯系統。結合 AI 自動主體分割、多層級獨立景深穿透、階梯式進場動畫與 Canvas 畫布螢幕錄影功能，輕鬆製作影視級的圖文穿透與視覺特效作品。

---

## ✨ 核心亮點與功能特色 (Key Features)

- **🖼️ 多元相片來源載入**
  - **檔案上傳**：支援各式標準圖片格式上傳，自動優化壓縮最佳尺寸。
  - **剪貼板直接貼上**：支援 Web Clipboard API 貼上按鈕與全域快捷鍵 (`Ctrl+V` / `Cmd+V`) 快速載入圖片。

- **🤖 AI 自動景深分割 (AI Selfie Segmentation)**
  - 整合 MediaPipe 機器學習模型，自動精準判斷照片中的人物/主體與背景。
  - **獨立主體快照備份**：AI 辨識完成後自動建立乾淨備份，確保各文字層的橡皮擦/畫筆塗抹修飾互不干擾。

- **🔤 多圖層動態文字編輯 (Multi-Text Layering)**
  - **獨立圖層設定**：支援新增無限文字圖層，每層皆可獨立設定文字內容、色彩、字型（黑體/明體/書法/厚黑）與旋轉角度。
  - **可視化靜態編輯區**：舞台上同步顯示所有文字圖層位置（未選中層呈現半透明虛線外框），隨時可點擊切換。
  - **彈性景深穿透**：可自由選擇將文字置於 AI 前景主體上方或背後。

- **🎬 階梯式動態進場與動畫錄影 (Motion Preview & Screen Recording)**
  - **嚴格銜接動畫**：多圖層採用動態時間軸，保證前一文字層動畫完全歸位後，下一文字層才開始啟動進場。
  - **多樣化進場效果**：支援從上/下/左/右滑入、淡入放大或靜態展示。
  - **一鍵高畫質錄影 (WebM)**：內建 MediaRecorder API 錄影機制，可直接將 Canvas 60FPS 動畫錄製成影片並儲存。

- **📤 多功能輸出與分享**
  - 支援一鍵將成品**複製至剪貼簿**、**系統原生分享**或**下載高清圖片/影片**。

---

## 🛠️ 技術棧 (Tech Stack)

* **前端UI框架**：Tailwind CSS (CDN)
* **圖標庫**：Lucide Icons
* **AI 分割引擎**：Google MediaPipe Selfie Segmentation
* **畫布渲染與錄影**：HTML5 Canvas API, MediaRecorder API
* **特效與動畫**：Canvas Confetti, RequestAnimationFrame Engine

---

## 🚀 快速開始 (Getting Started)

本專案採用單一 HTML 檔案架構 (Single-file Component)，無需額外編譯或安裝 Node.js 環境：

1. 下載或複製專案中的 `index.html`。
2. 使用任何瀏覽器（Chrome, Edge, Safari）直接開啟即可開始體驗。

---

## 📝 授權說明 (License)

Designed & Developed for **白六 (White 6)**. All rights reserved.
