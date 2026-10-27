# GRANRODEO LIVE Archive

以使用者提供的 CSV 整理的靜態網站試作版，目前只呈現兩場指定資料：
- 2026/11/23 — GRANRODEO Acoustic Live 2026 PLUGLESS GR -FIRE HORSE-
- 2026/11/20 — 東武鉄道 presents ANIMAX MUSIX 2026 supported by Lemino【DAY1】

## 部署到 GitHub Pages
1. 開啟此 Repository 的 Settings → Pages。
2. 在 Build and deployment 的 Source 選擇 Deploy from a branch。
3. Branch 選擇 main，資料夾選 /(root)，按 Save。
4. 等待部署完成後，開啟：https://merusutoyumeyubi.github.io/granrodeo-live-archive/

網站目前是單一 index.html，場次與歌單資料直接內嵌在頁面中，不需要另外設定 JSON 檔或連結 Google Sheets。

## 資料說明
- Setlist 顯示順序與歌曲名稱，不顯示 SongID。
- 類型來源欄位目前空白，頁面會顯示「類型待補」。
- 目前頁面僅為資料呈現試作，不代表對未來場次或歌單真實性的獨立查證。
- Google Sheets 與網站分開維護。
