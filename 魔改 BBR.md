```sh
wget https://raw.githubusercontent.com/FunctionClub/YankeeBBR/master/bbr.sh && bash bbr.sh install
bash bbr.sh start
sysctl net.ipv4.tcp_available_congestion_control # 有 tsunami 表示成功
```
