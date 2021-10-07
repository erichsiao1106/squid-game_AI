# 提供即時的臉部偵測及辨識，運行於邊緣裝置，無需等待臉部影像上傳至雲端的時間<br>
實作影片

![Alt Text](https://github.com/erichsiao1106/squid-game_AI
/blob/main/move-detect.gif)




# 目的
1.在邊緣裝置建置輕量，辨識率上也有極佳表現的人臉辨識應用<br>
2.偵測人臉後五秒自動拍照儲存<br>
3.建立打卡資料庫<br>

![Alt Text](https://github.com/erichsiao1106/edge-face-recognition-sql/blob/main/sql.jpg)


儲存臉部資訊:<br>
連續拍照40張來當作識別的分類器的根據<br>
資訊都儲存在邊緣端，兼顧即時性與隱私性<br>
![Alt Text](https://github.com/erichsiao1106/edge-face-recognition-sql/blob/main/preprocess-face.gif)
