# travel-ledger

出國記帳：一趟旅程一本帳本，多幣別、每本帳本自己的匯率、分類與付款方式、統計、匯出 Excel 與完整備份還原。

單一 `index.html`，透過 GitHub Pages 發佈：
https://alanchiangg.github.io/travel-ledger/

- **資料只存在使用者自己的手機**（localStorage），不會上傳；這個 repo 只有程式。
- 主畫面 App 和瀏覽器分頁的資料是分開的；刪掉主畫面圖示、換手機都會讓資料不見，請用「備份全部資料」匯出 JSON，換手機時用「從備份還原」。
- 匯率來自 open.er-api.com，記下來就固定在該帳本，可手動改成換錢時的匯率。
- 改了 `index.html` 記得把 `sw.js` 的 `VERSION` 加 1。
