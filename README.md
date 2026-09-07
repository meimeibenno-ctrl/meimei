# Lumina 修圖室

一個可以直接在瀏覽器中調色、裁剪、調整照片尺寸並下載成品的輕量修圖平台。圖片只在使用者的瀏覽器內處理，不會上傳到伺服器。

## 本機執行

```bash
npm install
npm start
```

開啟 `http://localhost:3000`。

## Render 部署

1. 在 Render 建立 **Web Service**，連接此 GitHub 儲存庫。
2. Runtime 選擇 Node。
3. Build Command：`npm install`
4. Start Command：`npm start`
5. 部署完成後即可使用。
