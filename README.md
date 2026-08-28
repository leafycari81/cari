# Cari's English

國中英文課堂加扣分與作業檢查紀錄系統（805 / 814 / 819）。單一 HTML 檔，離線可用，資料存在瀏覽器（localStorage）。

## 掛上 GitHub Pages

1. 在 GitHub 建一個新的 repository（例如 `caris-english`），可設 Public。
2. 把這個資料夾裡的檔案、**連同子資料夾**全部上傳到 repo 根目錄：`index.html`、`app.dc.html`、`support.js`、`manifest.webmanifest`、`apple-touch-icon.png`、`icons/`、`_ds/`、`.nojekyll`。
   （GitHub 網頁上傳：Add file → Upload files，可直接把整個資料夾拖進來；檔案都很小，全部加起來不到 300 KB。）
3. Settings → Pages → Source 選 `Deploy from a branch`，Branch 選 `main` / `/ (root)`，Save。
4. 約一分鐘後網址為 `https://<你的帳號>.github.io/caris-english/`。

## 裝到平板主畫面

- iPad（Safari）：開網址（結尾是 `/`，不要直接開 app.html）→ 分享 → 加入主畫面，圖示會是英國國旗。若之前加過舊的捷徑，請先刪除再重新加入。
- Android 平板（Chrome）：開網址 → 右上選單 → 安裝應用程式。

## 功能

- 三個班級切換：805、814、819（名單來自英語科成績登記表）
- 每人學習態度起始 80 分；卡片顯示起始分數、加扣分正負值、目前分數
- 加分：主動發表 +2；認真練習／完成作業／完成訂正／幫助同學 +1
- 扣分：不當言語 -2；講話／做其他事／未寫作業／未訂正／未帶課本 -1
- 作業檢查：課本／講義／學習單／訂正 + 頁數範圍，點選完成者 +1、未完成者 -1，待補交名單可 +1 補回
- 統計：表現亮眼、需要關注、原因次數
- 匯出 Excel（總表 + 明細）與 CSV
- 段考結算歸零：單班或三班一次清空（名單保留）

## 注意

- 首次開啟需要網路（字型與執行庫從 CDN 載入），之後瀏覽器會快取。
- 資料存在該台平板的瀏覽器裡，不會同步到其他裝置；換裝置或清瀏覽器資料前請先匯出 Excel。
- 段考結算歸零無法復原，請先匯出。
