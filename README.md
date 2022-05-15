# MITM

## 測試環境
![image](https://user-images.githubusercontent.com/69759142/168472086-6418b2b9-c674-4736-94b6-8ace1e228e36.png)

1:Router

104:PC (Windows 10)

105:Notebook (Windows 10)

103:VM (Kali linux)

131:VM (CentOS 7)

## Script

![image](https://user-images.githubusercontent.com/69759142/168472356-4beb570f-59fb-4ecf-b2b4-1cf2bed2c8ae.png)

3~6行為判斷權限

8~11行為判斷參數數量是否正確

13為設定將封包進行轉發

15~18使用arpspoof進行攻擊並將Process ID記錄

23為結束PID1 PID2的Process

![image](https://user-images.githubusercontent.com/69759142/168472437-6fe79ff5-0756-4aac-95fb-a3eac3964544.png)


![image](https://user-images.githubusercontent.com/69759142/168472274-1787c042-c40e-4949-81b0-6960dbddb726.png)
