# ICND PPP
序列式點對點的連線


不像 Vlan 或是 Lan, PPP 是能夠穿越 WAN 的連線方式。

# ISP & Cloud Service

由於建立全球性、可以連線至各端點的網路會耗費很大的資金，故若要使用廣域服務，通常得向電信業者或是網路提供業者租用，抑或是向雲端服務商等對象，承租廣域網路連線。

* PPP 連線方式：

(1) 專線：

    Leased Line

    同步串列

    最高可達 45 Mbps 速度，優點是沒有共享問題，缺點則是價格昂貴。

(2) 利用電信公司提供的 ISDN 電話轉網路服務

    Circuit-Switched

    非同步串列
    
    常見的有數據機的應用。

(3) 封包交換

    Packet-Switched

    同步串列
    
    採用虛擬電路 Virtual-Circuit （程式化）來達成 end-to-end 終端對終端的連線，
    此為共享的 ～ 速率可達到 45 Mbps

 # Serial 序列纜線的同步標準
 
 除了數據機以外，其他如專線或是封包交換的虛擬電路都採用如下序列式標準：
 
 * x.21
 
 * v.35
 
 * EIA/TIA-232
 
 * EIA/TIA-449
 
 * EIA-530
 
 # WAN 設備
 
 * Customer Premise Equipment
 
   服務供應商租給用戶的，或是用戶本身所有的。
 
 * Demarc, Demarcation
 
   劃定界線。
 
   CPE 至本地回圈 Local Loop (Last Mile)，位在用戶端的電信箱內。
 
 * Last Mile
 
   此為銅線，是從用戶端電信箱到網路提供者機房內的一段電路。
 
 * CO, Central Office Switch 
 
   電信交換設備
   
   這是電信服務商最接近用戶端的設備。
 
 
