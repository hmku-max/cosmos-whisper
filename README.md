# 宇宙捎來的話 — PWA 部署說明

## 部署到 GitHub Pages（5 步驟）

1. 前往 https://github.com/new，建立新 repo，名稱填 `cosmos-whisper`
2. 把這個資料夾的 4 個檔案全部上傳：
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. 進入 repo → Settings → Pages → Source 選 **main branch / root**
4. 儲存後等約 1 分鐘，網址會是：
   `https://hmku-max.github.io/cosmos-whisper/`
5. 用手機打開該網址 → 瀏覽器會出現「加入主畫面」提示 → 安裝完成！

## 手機安裝方式
- **iPhone**：Safari 打開網址 → 分享按鈕 → 加入主畫面
- **Android**：Chrome 打開網址 → 右上角選單 → 加入主畫面

## 功能說明
- 每日隨機抽取一則密語（20 則輪播，同天不換籤）
- 🤍 收藏喜歡的籤
- 分享圖卡（長按截圖）
- 深色模式切換
- 連續打卡 / 已集籤數統計
- 資料存在手機本地（localStorage），重裝不清除
