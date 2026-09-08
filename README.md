# nonbiri1004.github.io

我的個人作品集網站,線上版:**https://nonbiri1004.github.io/**

## 這是什麼

一頁式的個人作品集,展示我在全端專題裡做過的東西——五人團隊的觀光酒廠巡禮系統(負責商品預購與獎品兌換模組)、以及一個響應式咖啡品牌形象網站。

## 技術

刻意不用任何前端框架,純 HTML5 + CSS3:

- CSS 自訂屬性(`:root` 變數)統一管理色彩系統
- Flexbox / Grid 排版,`auto-fit` 讓作品卡片自動響應式換行
- `clamp()` 做流體字級,`aspect-ratio` + `object-fit` 處理圖片裁切
- 沒有 JavaScript、沒有建置流程——單一 `index.html`,GitHub Pages 直接部署

一個純展示用的靜態頁面不需要框架,少一層建置工具反而載入更快、更好維護。我在下面兩個作品裡實際用的技術棧是 C#、ASP.NET Core、Entity Framework Core、SQL Server、Vue 3——這個網站本身沒有用到,它只是用來展示它們的櫃子。

## 部署

Push 到 `main` 分支,GitHub Pages 自動 build 並上線,沒有額外的 CI/CD 設定。

## 授權

個人作品集,原始碼僅供參考。
