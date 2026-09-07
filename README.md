# Lumina 修圖室

一個純 HTML、CSS、原生 JavaScript 製作的輕量修圖平台。可以直接在瀏覽器中調色、裁剪、調整照片尺寸並下載成品；圖片不會上傳到伺服器。

## 本機執行

直接以瀏覽器開啟 `public/index.html`，或使用任何靜態網站伺服器即可。

## Render 部署

1. 在 Render 選擇 **New → Blueprint**，連接此 GitHub 儲存庫。
2. Render 會讀取 `render.yaml`，以 Static Site 部署 `public` 資料夾。
3. 部署完成後即可使用，不需要安裝 Node.js 或資料庫。

也可將 `public` 資料夾直接部署至 GitHub Pages、Netlify 或 Cloudflare Pages。
