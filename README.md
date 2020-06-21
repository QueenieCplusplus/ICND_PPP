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

    
    
