﻿# Hahow-前端網頁設計入門
平台：Hahow <br>
老師：Jeremy Yen <br>
課程：[創業必備：前端網頁設計入門](https://hahow.in/courses/56c1e3b3e91d590900234105/discussions) <br>
<br>


## 練習 ─ BMI 計算器
使用：Bootstrap、jQuery、RWD <br>
連結：[BMI 計算器](https://as60160.github.io/Hahow-Jeremy-Frontend/%E7%B7%B4%E7%BF%92-BMI%E8%A8%88%E7%AE%97%E5%99%A8.html)<br>

* 我嘗試：
1. 將 navbar 使用的 `navbar-light bg-light` 改為 `navbar-dark bg-dark`
2. 使用 `<small>` 、 `<sup>` 增加註解 
<br>

* 我學到：
1. 引入 library 時，如果先引入 bootstrap.js 再引入 jQuery 會出現錯誤。
2. 理解所謂的 library 到底是什麼意思、如何使用。
3. 分析 navbar 的程式碼結構並知道如何取捨要與不要的部分。
4. Tag ： `<small>` 、 `<sup>`
5. 使用縮排時，統一選用 Tab 或 Space ，不然上傳到 github 後程式碼位置會跑掉。
<br>

* 想知道：
1. 為什麼先引入 bootstrap.js 再引入 jQuery 會出現錯誤？
2. 計算按鈕在視窗變小時，如何才能置中？
<br>
<br>



## 作業 ─ 體脂率計算器
使用：Bootstrap、jQuery、RWD <br>
連結：[體脂率計算器](https://as60160.github.io/Hahow-Jeremy-Frontend/%E4%BD%9C%E6%A5%AD-%E9%AB%94%E8%84%82%E7%8E%87%E8%A8%88%E7%AE%97%E5%99%A8.html)<br>

* 作業詳細要求：
1. 先完成一個 BMI 計算器後，在下方新增四個元件(年齡、性別、體脂肪率、計算按鈕)。元件樣式可自訂或使用 Bootstrap 樣式。
2. 撰寫計算體脂肪率的 JavaScript，可使用 jQuery 輔助。
3. 考慮防呆設計（例如防止使用者忘記輸入，或未先計算 BMI 就想算體脂肪率）
4. 使用 Git 管理，最後發佈到 Github Page（參考單元10），繳交個人 github.io 網址 (盡量不要直接打包 zip 上傳)
5. 程式碼內適時加上註解更佳
<br>

* 我嘗試：
1. 使用 `fixed-top` 固定 navbar 的位置，讓它不會隨著捲動而消失。
2. 使用 `card` 來呈現內容。
<br>

* 我學到：
1. `card`、`fixed-top`、`hr`、
2. 使用 `fixed-top` 固定 navbar 的位置時，要拉大 navbar 底部和 div 上方的距離，div 的內容才不會被重疊。
3. 學會使用 form select 來製作下拉選單，並且用 value 來為選項設定值。
<br>

* 想知道：
1. 怎麼設定按鈕的位置，讓他們能呈現在我想要的地方？
2. Reset buttom 要怎麼設定清空內容？
3. 為什麼計算出數值後，無法將數值透過 if 的判斷，回傳到我要的form ？
<br>