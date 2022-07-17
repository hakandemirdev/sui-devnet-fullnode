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
Yükleme işlemi başarıyla tamamlanırsa full node'un çalışmaya başladığına dair aşağıdaki ekranı göreceğiz.

![This is an image](https://i.imgur.com/6h8OqzF.png)

[Node Kontrolü için bu adrese gidip sunucumuzun ip adresimizi giriyoruz.](https://node.sui.zvalid.com)
https://node.sui.zvalid.com/
