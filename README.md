# Taiko 3. Node Test Rehberi
![Taiko-Node-Testi](https://mirror-media.imgix.net/publication-images/4qVW-dWhNmMQr61g91hGt.png?height=512&width=1024&h=512&w=1024&auto=compress)

## Testnete katılmak için öncelikle 
* [BURADAN](https://www.alchemy.com/) Alchemy sitesine kaydınızı yaptırın.
* Sepoila Faucet için [BURADAN](https://sepoliafaucet.com/) testnete katılacağınız cüzdanınıza test ETH isteyin

## Kurulum Öncesi Notlar

## Sistem gereksinimleri:
NODE TİPİ | CPU     | RAM      | SSD     |
| ------------- | ------------- | ------------- | -------- |
| Taiko | 2         | 4      | 40 |
 

* Hetzner için bu gereksinimleri almak yeterli olacaktır. Yaklaşık olarak 6$ civarında bir maliyeti var.
Hetzner kaydınız yok ise [BURADAN](https://hetzner.cloud/?ref=ew4WgPUfxeyJ) linke basıp 20€ değerinde ödül kazanıp, testnete katılabilirsiniz.

## Kurulum;
```
sudo apt update
```
```
sudo apt upgrade
```
```
apt install docker-compose
```
```
apt install git
```
```
sudo apt-get update && sudo apt install jq && sudo apt install apt-transport-https ca-certificates curl software-properties-common -y && curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - && sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable" && sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin && sudo apt-get install docker-compose-plugin
```

# Repoyu klonlayıp dizine girelim
```
git clone https://github.com/taikoxyz/simple-taiko-node.git
```
```
cd simple-taiko-node
```

# Ayrı screende çalıştıracağız:
```
screen -S taiko
```

## Alchemy İşlemleri
![111](https://github.com/CoinHuntersTR/Taiko-3-Testnet-Rehberi/assets/111747226/29eed0b5-de57-4c48-8a8c-4dfa28899834)

