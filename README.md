# 熱門影集 <<魷魚遊戲>>有關AI技術的實作 <br>
實作影片 <br>
<img src="https://github.com/erichsiao1106/squid-game_AI/blob/main/move-detect.gif" width="480" height="240" /> <br>




# 目的
1.部署在邊緣(jetson nano 、raspberry pi)，所有運算跟資料庫儲存都在邊緣完成 <br>
2.在<<red light，green light>>遊戲中的移動偵測<br>
<img src="https://github.com/erichsiao1106/squid-game_AI/blob/main/Squid-Game-Games-Ranked.jpg" width="480" height="240" /><br>
3.進入遊戲前的臉部特徵抓取儲存<br>
<img src="https://github.com/erichsiao1106/squid-game_AI/blob/main/intro-1632168234.jpg" width="480" height="240" /><br>



儲存臉部資訊:<br>
自動追蹤臉部，倒數五秒靜止後自動拍照<br>
資訊都儲存在邊緣端，兼顧即時性與隱私性<br>
![Alt Text](https://github.com/erichsiao1106/squid-game_AI/blob/main/auto-take-pic.gif)


人臉身分識別 <br>
![Alt Text](https://github.com/erichsiao1106/squid-game_AI/blob/main/clock-in.gif)
TO do :<br>
自動拍照可以從倒數五秒換成使用情緒分類<br>
例如電影中的"smile"當作指令
