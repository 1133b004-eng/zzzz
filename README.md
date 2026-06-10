# 🏴‍☠️ 海盜寶藏配對 - 多關卡海洋冒險 (Ocean Pirate Multilevel Game)

這是一個基於 HTML5 Canvas、Vanilla CSS 與 JavaScript 開發的現代化、響應式多關卡卡牌配對遊戲。擁有精美的海洋風漸層背景、磨砂玻璃質感（Glassmorphism）面板、流暢的卡牌翻轉特效以及過關時的 Canvas 煙火動態特效。

## 🌟 遊戲特色
- ⚓ **漸進式難度**：隨關卡提升，配對張數將逐漸增加，考驗您的記憶極限！
- ⏱ **時間壓力與懲罰機制**：時間倒數計時中，每過 5 秒未配對成功或每次翻牌配對錯誤，將會扣除分數！
- 🎆 **Canvas 煙火慶祝**：通關且分數大於等於 60 分時，將會施放海盜旗幟與海洋生物形狀的炫麗煙火！
- 📱 **響應式設計**：完美支援手機、平板與桌上型電腦。
- 🎨 **現代化設計**：使用 Google Fonts Outfit 字型與 Glassmorphism 磨砂玻璃視覺風格。

## 🛠 依賴項目 (Dependencies)
本專案為**完全獨立的單網頁應用 (Single Page Application)**，無須安裝任何 Node.js 依賴或進行打包建置。
- **字型**：Outfit (由 Google Fonts CDN 載入)
- **圖示庫**：Tabler Icons (由 jsDelivr CDN 載入)
- **JavaScript/CSS**：純原生 Vanilla JS & CSS，無外部框架（如 React/Vue）依賴。

---

## 🚀 手動部署至 GitHub Pages 步驟

您可以使用以下兩種方式之一，將此遊戲部署到 GitHub Pages：

### 方法一：網頁直接上傳 (最簡單)
1. 登入您的 [GitHub](https://github.com/) 帳號。
2. 點擊右上角的 **+** 號，選擇 **New repository** (新建儲存庫)。
3. 輸入儲存庫名稱（例如：`ocean-pirate-game`），並將權限設為 **Public**，然後點擊 **Create repository**。
4. 在儲存庫頁面，點擊 **uploading an existing file** 連結。
5. 將本資料夾中的 `index.html` 拖曳上傳至網頁中，並點擊 **Commit changes**。
6. 前往儲存庫的 **Settings** -> 左側選單 **Pages**。
7. 在 **Build and deployment** 下的 **Source** 選擇 **Deploy from a branch**。
8. 將 **Branch** 設為 `main` (或 `root`)，並點擊右側的 **Save**。
9. 等待約 1-2 分鐘後，即可透過 `https://<您的帳號名稱>.github.io/ocean-pirate-game/` 線上遊玩！

### 方法二：使用 Git 指令推送
如果您本機已安裝 Git，可以在終端機執行以下指令：
```bash
# 初始化 Git 儲存庫
git init

# 將檔案加入追蹤
git add .

# 提交變更
git commit -m "Initial commit - Ocean Pirate Game"

# 重新命名分支為 main
git branch -M main

# 關聯遠端 GitHub 儲存庫 (請替換為您的遠端 URL)
git remote add origin https://github.com/<您的帳號>/ocean-pirate-game.git

# 推送至 GitHub
git push -u origin main
```
推送完成後，同樣至 GitHub 儲存庫的 **Settings -> Pages** 開啟 GitHub Pages 即可。
