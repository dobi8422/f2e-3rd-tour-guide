# f2e-3rd-tour-guide

>F2E-3rd參賽作品
>
>TDX API - (Transport Data eXchange) 限取50次/day

## 簡介

* 台灣觀光網站，可查詢景點、美食、住宿、活動
* [Demo](http://dobi8422.github.io/f2e-3rd-tour-guide/)

## 功能

* 關鍵字搜尋
* 篩選功能(多選)(按鈕:景點分類，縣市分類)
* mobile/iPad/desktop介面
* 調整閱讀模式(圖文/列表) (for iPad/desktop)

---

## 自我挑戰

* 調整閱讀模式(圖文/列表) (for iPad/desktop)
* vue - Composition API - `<script setup>`
* oData搜尋語法，(過濾無圖片資料、篩選縣市、關鍵字、...)
* 無限滾動
* 顯示地圖 - leaflet

---

## 待優化

* css review
* vuex -> pinia
* tailwind樣式不見 -> 先重做-> 把defineProps...改都用pinia
* API path change

* 改善 -> 要先滾動才會出現第一筆資料😂
* detail頁面 -> 新增附近景點nearby...`https://2021.thef2e.com/news/week2`
* localstorage -> 收藏
* detail頁面 -> 重整 or 直接輸入ID網址，直接查詢資料
