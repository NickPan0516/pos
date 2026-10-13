# Su&Cake POS

這是可直接由瀏覽器開啟的靜態 POS 測試版。

## GitHub Pages

此專案已設定 GitHub Actions 自動部署。將專案推送至 GitHub 儲存庫的 `main` 分支後，workflow 會發布網站；部署網址可在 GitHub Actions 的 Pages deployment 查看。

## 資料儲存

商品、銷售紀錄與預訂資料存在瀏覽器的 `localStorage`。每台裝置、每個瀏覽器的資料各自獨立，清除瀏覽器資料也會清除這些紀錄。GitHub Pages 僅提供網頁，不會同步 POS 資料。

