# AC_2-3_A8_RestaurantList
這是Alpha Camp 2-3後端專修的A8作業。

本作業功能清單如下：
  1. 載入種子資料後，首頁(index)可顯示來自restaurant.json中的所有餐廳資訊，包含餐廳名稱、種類、評分、圖片。餐廳卡片的排列依序為由左至右、由上至下。
  2. 使用者可於搜尋框輸入餐廳名稱、英文名稱或分類之關鍵字，點下搜尋鍵後可顯示分類或名稱符合關鍵字的餐廳列表。
  3. 使用者可於搜尋框右邊的下拉式選單選擇餐廳的排序依據，預設為id由小到大排序，可自由選擇依餐廳名稱、餐廳分類、餐廳地區與餐廳評分來呈現排序。
  4. 使用者點擊某一餐廳卡片，或點下"瀏覽"連結後，可瀏覽該餐廳的詳細資訊，包含餐廳地址、電話號碼及描述等，並可編輯餐廳資訊或刪除該餐廳，或是返回首頁。
  5. 使用者可針對某一餐廳，點擊"編輯"來編輯該餐廳資訊。
  6. 使用者可刪除餐廳，點擊刪除按鈕後網頁將詢問是否確定刪除。
  7. 使用者可於首頁右上角點擊「新增餐廳」按鈕來新增餐廳。

安裝步驟:
1. 指令 git clone https://github.com/Cindy-Chiu/restaurantList.git
2. 指令 cd (存放資料夾)
3. 指令npm install
4. 指令npm i nodemon
5. 指令 set MONGODB_URI = 您的MongoDB位址
6. 指令 npm run seed載入種子資料
7. 指令npm run dev 並會看見終端機回傳
"Express is listening on localhost:3000
mongodb connected!"
