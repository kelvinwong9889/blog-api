# blog-api
使用 Node.js、MongoDB Compass、Express。
來嘗試開發一個有用戶登錄功能的博客系統。

## 網頁功能
```bash
- 用戶註冊
- 用戶登入
- 用戶登出
- 用戶檢視博客
- 用戶新增博客
- 用戶修改博客
- 用戶刪除博客
```

## MongoDB Compass 安裝指南 (參考以下 youtube 影片)
[MongoDB Installation Made SUPER Easy!](https://www.youtube.com/watch?v=6BuRmE63ZJQ)

## ER Diagram 結構
<img width="378" alt="image" src="https://github.com/user-attachments/assets/6ab94cac-67fc-42f8-a4bc-bb5157863d18" />

## 資料夾結構
```bash
blog-api/
├── config/
│   └── db.js
├── models/
│   ├── blog.js
│   └── user.js
├── middleware/
│   ├── auth.js
│   └── errorHandler.js
├── routes/
│   ├── auth.js
│   └── blogs.js
├── public/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── create-blog.html
│   └── edit-blog.html
├── app.js
└── package.json
```

## 項目初始化及啟動
1. 下載項目然後進入項目資料夾，執行CLI指令
```bash
npm install
npm start
```

2. 開啟 MongoDB Compass，點擊 add new connnection。
<img width="169" alt="002" src="https://github.com/user-attachments/assets/4baf15b8-3b6f-437d-b180-277635f10ca3" />

3. 在 localhost:27017 旁邊點擊 Create Database，開啟 2 個空白的 Collection。
```bash
Database Name: blogDB
Collection Name: blogs
Collection Name: users
```

<img width="157" alt="001" src="https://github.com/user-attachments/assets/461d979f-4cf1-4f73-bda8-925efaaeedc1" />

4. 用瀏覽器進入以下網址測試
```bash
http://localhost:3000
```
