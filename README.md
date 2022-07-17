# Sui Devnet Fullnode Kurulumu
Minimum gereksinimler:
```
2 core cpu
4 gb ram (8 gb ram tavsiye edilir)
50 gb SSD

```

Öncelikle işletim sistemimizi güncelliyoruz.
```
sudo apt-get update  && sudo apt-get upgrade
```
Daha sonra işletim sistemize screen kuruyoruz.
```
apt install screen
```
Bir screen oluşturuyoruz.
```
screen -S sui
```
Full Node yükleme işlemini gerçekleştirelim:
```
wget -O sui.sh https://raw.githubusercontent.com/kj89/testnet_manuals/main/sui/sui.sh && chmod +x sui.sh && ./sui.sh
```
