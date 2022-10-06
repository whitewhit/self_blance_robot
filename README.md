# Self-Balancing-Robot

Side project of self balancing robot that using PID control with Arduino nano and MPU6050.# self_blance_robot

## 專案與設計目的

+ 自主平衡車可以說是控制系統領域的入門主題，藉由基本的「倒單擺」問題，能使觀眾清楚的了解PID控制與閉迴路系統等基礎觀念。

+ 藉由arduino來完成實體，用以宣傳系上相關課程，並激發出觀者對於機電整合、控制系統領域的一大熱忱。
  
## 預計展演方式與成效

+ 1.車體平衡
  + 以車體能夠在兩輪直立的情況下保持自主平衡為先決條件
+ 2.載物
  + 放上物件並能夠保持平衡。可以以液體等防潑出方式進行展演
+ 3.干擾/回復
  + 讓觀者輕推車體使其失去平衡，並觀察他自主回復穩態
+ 4.手機遙控
  + 體驗以手機藍芽的方式遙控車體，並在移動的過程中保持平衡
+ 5.技術講解
  + 介紹使用的電子元件、製作過程與相關領域及原理，並與細上課程有所連結。

## 製作流程

+ 壓克力板、木板、銅柱(車體)
+ 利用繪圖軟體solidworks設計車身
+ 將壓克力、雷射加工後組裝出車身
+ 麵包版、杜邦線
+ 用nano 撰寫好PID程式
+ 調整setpoint 、Ki、Kp、Kd 的參數

## 成果

+ 給予移干擾，一段時間後會回復原來平衡狀態
+ 因為電池的電量會引響馬達的轉速，因此PID參數也需要適度的調整
+ 根據實際的操作，PID控制對於我們終於不再只是紙上談兵，而是努力得來的甜美果實>_<

## 成品圖

![picture 1](https://github.com/whitewhit/self_blance_robot/blob/main/Self-Balancing-Robot-main/img/robot-2.jpg)  
![picture 2](https://github.com/whitewhit/self_blance_robot/blob/main/Self-Balancing-Robot-main/img/robot-1.jpg)
