##DOCKER COMMANDS
#Trocar hora container

`docker exec -u 0 -it oracle-12c bash` #Entra como root

`rm -f /etc/localtime` #Remove localtime atual

`ln -s /usr/share/zoneinfo/America/Sao_Paulo /etc/localtime`  #Recria Link simbolico para timezone
