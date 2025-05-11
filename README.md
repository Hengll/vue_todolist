# vue_todolist

[https://hengll.github.io/vue_todolist/](https://hengll.github.io/vue_todolist/)

這是一個使用 Vue3 + Bootstrap5 製作的 todolist，支援基本的 CRUD 操作、篩選功能、本地儲存等功能，介面簡潔、操作直覺。

## 🚀 功能特色

- ✅ 新增、刪除、編輯待辦事項（支援雙擊編輯 / ESC 取消）
- 🔍 篩選功能（顯示全部 / 已完成 / 未完成）
- 📦 本地儲存資料（使用 LocalStorage，自動保存清單）
- 📌 一鍵操作：
  - 標記全部已完成 / 未完成
  - 刪除全部 / 已完成 / 未完成事項
- 🎨 使用 Bootstrap 5 打造 RWD 響應式設計
- 🖋 自訂字體美化標題（Google Fonts）

## 📦 技術使用

- [Vue 3 CDN 版本](https://vuejs.org/)
- [Bootstrap 5](https://getbootstrap.com/)
- HTML5 / CSS3（無需額外打包工具）

## 🧠 架構設計

- `Task` 類別：負責單一任務的狀態、編輯控制。
- `TaskManager` 類別：負責任務的新增、刪除、篩選、儲存邏輯。
- 使用 Vue Composition API `setup()` 搭配 `ref`、`computed`、`watch` 控制資料與介面同步。

## 🖥️ 使用方式

1. 下載專案或直接打開 `index.html`
2. 開始輸入待辦事項，體驗清單功能！

## 📁 資料儲存

- 所有任務將儲存在瀏覽器的 `localStorage.vueList` 中。
- 關閉網頁後，清單仍會自動保留，下次開啟自動讀取。

## 🧪 預覽截圖（可自加）

![img](/img.PNG)
