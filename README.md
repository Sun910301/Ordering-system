# Ordering-system!
[c++final](https://user-images.githubusercontent.com/115983672/196676221-5936990e-2cf9-4f6a-a230-3b48edd72a26.png)
利用C++製作出一個能儲存用戶資訊的壽司店訂票系統，在進入選擇時能看到建立訂位、
定位查詢和離開系統並且可以偵測名稱是否重複或輸入錯誤，在程式會再關閉前將用戶
資料存取到 DAT 檔，讓下次開啟還可以資料還存著。兩個DAT檔中AvailSeats存著可
以訂的位子和時間，Reservation存著空位訂位時間、人數、電話號碼、用戶名子並可
讀入進struct裡來完成訂票及定位。在訂票的時候要額外注意時間年分以及記錄該位置
是否被訂走不可以再訂位。
