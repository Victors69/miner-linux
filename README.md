# miner-linux
```
sudo su
```
```
apt update
```
Get Repo
```
wget https://github.com/hellcatz/hminer/releases/download/v0.59.1/hellminer_linux64.tar.gz
```
Atau
```
wget https://github.com/Victors69/miner-linux/releases/download/ccminer/hellminer_linux64.tar.gz
```
Lanjut
```
tar -xf hellminer_linux64.tar.gz && nano run_miner.sh
```
Ganti Dengan ini dan wokernya (RX03) beserta walletnya

Version 4 CPU
```
./hellminer -c stratum+tcp://na.luckpool.net:3956 -u RPrvUkG3uapSV1tUrqdpPFrPuNbaTT6XE3.RX03 -p x --cpu 4
```
Version 2 CPU
```
./hellminer -c stratum+tcp://na.luckpool.net:3956 -u RPrvUkG3uapSV1tUrqdpPFrPuNbaTT6XE3.RX03 -p x --cpu 2
```
Lanjut Klik Ctrl + X klik Y Klik Enter
```
tmux
```
Running
```
./run_miner.sh
```
Close SSH Enjoyyyyyyyy
