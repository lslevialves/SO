# Atividade 3

###O que é o Docker?

Para a instalação do docker no ubuntu 17.04 segue os passos:

Entrar no link abaixo e baixar a ultima versão datada
https://download.docker.com/linux/ubuntu/dists/xenial/pool/stable/amd64/

Após é só segur os comandos abaixo:

> 1 cd Downloads/
> 2 dpkg -i (e o nome do arquivo completo, nome caso docker-ce_17.03.1~ce-0~ubuntu-xenial_amd64.deb)


Apos a instalação ative o serviço com o comando:

> systemctl enable docker

Inicie o serviço com o comando 

> systemctl start docker

A seguir segue os comandos:

> docker pull ubuntu

> docker run -t -i d

Instalando apache 
> apt-get update && apt-get install apache2 

Ative o serviço do apache no seu Ubuntu:

> service apache2 start

Verifique o IP da sua máquina Ubuntu:

> ifconfig

No meu caso era: 

> 192.168.25.140 ou 127.0.0.1

Observação:

Se você fechar a máquina (docker – ubuntu) as configurações vão se perder, neste caso, em sua máquina (servidor) abra um terminal e digite o comando :

> docker commit IDdoDocker nomedaimagem

O “IDdoDocker” é o código que está após o root@, exemplo:

Exemplo

> docker commit HP-ENVY  ubuntuapache
