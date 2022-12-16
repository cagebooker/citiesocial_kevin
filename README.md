仿 citisocial 網站，跟龍哥的教學

網站功能 （購物網站）
1. 跑馬燈圖片展示
2. 電子報訂閱
3. 會員系統
4. 第三方串接(google)
5. 後台系統
6. 後台 - 廠商管理
7. 後台 - 商品管理
8. 後台 - 商品庫存管理
9. 商品編輯器
10. 商品分類（拖拉排序）
11. 購物車
12. line pay 付款

技術
* gem Devise 會員系統
  - 客製化 views
  - 客製化 controller
* bulma carousel （跑馬燈效果）
* Omniauth 串接 google API
* 建立後台
  - routes設定，layout設定
  - 開廠商、商品 model
  - 商品編輯器
* 建立庫存機制
  - 庫存 sku model
  - 建立巢狀表單
  - 設定 permit 格式
  - 庫存欄位畫面顯示
* 電子報 API
* 實作購物車
  - TDD Rspec(PORO)
  - MVC中實作 current_cart
  - 轉換 session 資料
* 購物車結帳
  - 訂單及訂單物品分別建立model
* LINE pay串連  
