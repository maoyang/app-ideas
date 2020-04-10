# 因果效應

**等級:** 1-初學者

模式是軟體工程不可或缺的一部分，在程式邏輯中代表著潛在的可重複使用元件。 
然而，模式並不僅僅用於程式邏輯，它們存在於其他領域，如 DevOps、使用者支援和使用者介面。

常見的使用者介面模式是在頁面的一個部分( section )中彙總資料，
該部分由描述或分類一組資料的某種類型的列表(如文字、影像或圖標)組成。 
單擊列表項時，該項背後的詳細資料將顯示在頁面上的相鄰窗格( pane )中。

例如，在房地產網站上，單擊待售房產列表中的地址，將在頁面的另一部分( section )顯示該房產的詳細資訊。

這個挑戰要求實現它的開發人員遵循以下約束:

-   你負責建立你自己的測試資料。 使用一個硬編碼(hardcoded) 的 Javascript 物件來定義測試資料(見下文)
-   在第一個版本的應用程式中只使用原生 HTML/CSS/Javascript 
-   在實現後續版本時，你可以使用其他套件或程式庫

## 使用者故事

-   [ ] 使用者可以在頁面上的摘要窗格(pane)中看到垂直排列的人名列表
-   [ ] 使用者可以點選列表中的一個名字來更新頁面上的一個相鄰窗格中的個人全名、地址、電話號碼和生日
-   [ ] 使用者可以單擊列表中的另一個名稱，以重新整理該個人資訊的詳細資訊欄

## 額外功能

-   [ ] 使用者可以看到摘要窗格中突出顯示的人名，當收件人懸停(hovered)在其上方時
-   [ ] 使用者可以在單擊摘要窗格(pane)時使用選擇效果( selection effect 例如顏色、大小等)將人名高亮顯示。 這是一個不同於懸停效果的效果
-   [ ] 當單擊新的人名時，使用者可以看到從摘要列表中的人名被移除的選擇效果

## Useful links and resources 有用的連結和資源

-   [DOM Events](https://developer.mozilla.org/en-US/docs/Web/API/Event)
-   考慮在 JavaScript 物件中定義測試資料，其格式如下:

```
const people = [
  {name: "...", street: "...", city: "...", state: "...", country: "...", telephone: "...", birthday: "..."},
  .
  .
  .
  {name: "...", street: "...", city: "...", state: "...", country: "...", telephone: "...", birthday: "..."}
];
```

## 範例專案 

在 [Javascript MDN site](https://developer.mozilla.org/en-US/docs/Web/JavaScript)網站上檢查頁面左側瀏覽條目和頁面主體之間的互動

## 沒有基礎要先上哪些課程？

英文課程 (可用 Google 翻譯成中文字幕 ) 

- [從基礎開始學習最新的 HTML & CSS (包含 Sass)](https://softnshare.com/modern-html-css-from-the-beginning/)
- [完整的 JavaScript 課程 2020 : 開發一個真實世界的專案](https://softnshare.com/the-complete-javascript-course/)
- [最新的 React 與 Redux 課程 – 2020 更新](https://softnshare.com/react-redux/)

中文課程

- [中文課程 – 給網頁設計初學者的一門課：html+css](https://softnshare.com/htmlcss-d/)
- [中文課程 – JavaScript新手秘笈｜三大專案帶你輕鬆入門]( https://softnshare.com/%e4%b8%ad%e6%96%87%e8%aa%b2%e7%a8%8b-javascript%e6%96%b0%e6%89%8b%e7%a7%98%e7%ac%88/)
- [中文課程 – 2019 react 入門到高階課程，包括 react hooks，以及實戰](https://softnshare.com/javascript-react-es6-hook-router-umijs-redux-dva-antd/)
