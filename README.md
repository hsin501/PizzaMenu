# React Pizza Menu

這個專案是一個簡單的靜態網頁，用來展示披薩菜單和營業時間資訊。

## 檔案結構

```bash
.
├── public/ # 公共資源 (靜態資源，如圖片等)
│ └── pizzas/ # 披薩圖片資源
├── src/
│ ├── index.js # 主入口檔案
│ ├── index.css # 全域樣式設定
│ └── App.js # 主 React 組件
└── package.json # npm 專案設定檔
```

## 組件

`index.js`: 應用程式入口點，包含 ReactDOM.createRoot 和 App 元件的渲染。

`App.js`: 主應用元件，包含 Header、Menu 和 Footer。

`Header`: 顯示應用標題。

`Menu`: 顯示披薩菜單。

`Pizza`: 顯示披薩細節。

`Footer`: 顯示營業狀態。

`Order`: 營業中顯示的訂購按鈕。

## 使用技術

- React
- CSS
