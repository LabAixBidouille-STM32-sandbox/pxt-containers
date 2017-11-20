## Image Docker pour lancer PXT avec la cible microbit

1. Construire le conteneur exécuter la commande suivante :
```sh
docker build -t LabAixBidouille-STM32/pxt-microbit-alpine .
```
1. Le lancer : 
```sh
docker run -d -p 80:80 --name pxt-microbit01 LabAixBidouille-STM32/pxt-microbit-alpine
```
1. Ouvrir le navigateur :
```
http://your_server_ip:80 
```


