# Jay Studio

Jay Studio 的接案網站，線上版：**https://jaystudio1004.com/**

## 這是什麼

一頁式的工作室網站，介紹我能幫品牌和小團隊做的事：

- AI 圖片與影片工作流
- AI 工具串接與小型系統
- 網站與全端開發
- 技術評估與研究報告

「做過的東西」放的是實際作品：自己經營的 lofi puppy radio、客戶的 AI 節點式創作畫布、咖啡品牌形象網站，以及五人團隊的觀光酒廠巡禮系統（我負責商品預購與獎品兌換模組）。

## 技術

刻意不用任何前端框架，純 HTML5 + CSS3：

- CSS 自訂屬性（`:root` 變數）統一管理色彩系統
- Flexbox / Grid 排版，`auto-fit` 讓作品卡片自動響應式換行
- `clamp()` 做流體字級，`aspect-ratio` + `object-fit` 處理圖片裁切
- 沒有建置流程，單一 `index.html`。唯一的 JavaScript 是頁首幾行轉址，把舊網址的訪客導到新網域

一個純展示用的靜態頁面不需要框架，少一層建置工具反而載入更快、更好維護。作品裡實際用到的技術（C#、ASP.NET Core、Entity Framework Core、SQL Server、Vue 3、ComfyUI 等）列在網站的「專案中實際用過的技術」區塊，這個網站本身沒有用到。

## 部署

Push 到 `main` 分支後會自動部署到兩個地方：

- **Cloudflare Pages → jaystudio1004.com**：正式網站
- **GitHub Pages → nonbiri1004.github.io**：舊網址，開啟後會自動轉到 jaystudio1004.com（路徑和參數會保留）

## 授權

Jay Studio 網站，原始碼僅供參考。
