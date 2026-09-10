# 𓃥 白六照片主題編輯 (Photo-theme)

> **3D Dynamic Depth Photo Editor**
> 一款基於純前端技術與 AI 景深分割的動態圖文編輯器，輕鬆打造文字穿透人像/主體背後的 3D 視覺震撼卡片！

🔗 **線上體驗**：[https://kuochili-ops.github.io/Photo-theme/](https://kuochili-ops.github.io/Photo-theme/)

---

## 🌟 亮點特色

- 🤖 **AI 自動人像/主體去背**：整合 MediaPipe Selfie Segmentation 模組，上傳照片後自動辨識前景與背景，即時實現「文字夾在主體與背景之間」的 3D 景深效果。
- 🎬 **動態進場預覽**：提供多種 3D 文字進場動畫（由上下滑入、由下向上滑入、左右滑入、淡入放大），專為動態展示與螢幕錄影設計。
- ✏️ **直覺文字排版與旋轉**：支援畫布上直覺式拖曳移動、角度旋轉、寬度縮放與字體大小自由微調。
- 🎨 **自由編修筆刷工具**：
  - **橡皮擦模式**：局部擦除前景主體，露出被遮擋的文字細節。
  - **畫筆還原模式**：精準塗抹還原主體遮罩。
  - **套色遮罩顯示**：一鍵開啟主體覆蓋區域套色，去背範圍一目了然。
- 🔤 **多樣化字體與色彩**：預設黑體、明體、書法體、厚黑體等多款 Google Fonts 中文字型與多元色彩盤。
- 📐 **多種畫布比例**：支援 1:1（正方形）、4:5（肖像）、16:9（橫向）隨時一鍵切換。
- 📱 **流暢的行動端體驗**：專為智慧型手機與觸控螢幕優化，支援原生「複製照片」與「分享/儲存」選單。

---

## 🛠️ 技術架構

- **Core Engine**: HTML5 Canvas / JavaScript (ES6+)
- **AI / Depth Model**: [@mediapipe/selfie_segmentation](https://google.github.io/mediapipe/solutions/selfie_segmentation.html)
- **UI Styling**: [Tailwind CSS CDN](https://tailwindcss.com/)
- **Icons**: [Lucide Icons](https://lucide.dev/)
- **Effects**: [canvas-confetti](https://github.com/catdad/canvas-confetti)

---

## 🚀 快速上手與操作指南

### 1. 上傳與 AI 運算
1. 點擊舞台中央上傳圖片。
2. AI 將自動進行去背分離，並開啟「3D 景深」模式。

### 2. 文字編輯與位置調整
- **修改文字**：點擊文字框直接編輯，或透過下方「文字」輸入框更新。
- **文字移動**：切換至 **「文字移動」** 模式後，可直接拖曳文字框。
- **角度與大小**：利用文字框四周的控制按鈕進行旋轉、調寬與等比例放大縮小。

### 3. 精細修正 (橡皮擦 / 畫筆)
- 切換至 **「橡皮擦」** 或 **「畫筆」** 模式，調整下方「接觸面積（筆刷大小）」。
- 可開啟 **「套色」** 按鈕，清楚查看當前前景主體的涵蓋範圍。

### 4. 成果預覽與匯出
- 點擊右上角 **「預覽成果」**。
- 選擇喜歡的 **動態進場動畫**（如：從上向下滑入）並播放。
- 點擊 **「複製照片」** 快速貼至通訊軟體，或點擊 **「分享/儲存」** 直接將圖片存入手機相簿。

---

## 📦 本地端開發 (Local Development)

本專案為無編譯需求的純前端架構，無需安裝 `node_modules`：

1. **複製專案庫**：
   ```bash
   git clone [https://github.com/kuochili-ops/Photo-theme.git](https://github.com/kuochili-ops/Photo-theme.git)
