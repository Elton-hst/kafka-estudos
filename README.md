# kafka

implementação do kafka local no Windows


## Instalação

Instale o kafka em sua máquina(instale na raiz)

```
  https://kafka.apache.org/downloads
```
rode o zookeeper

```bash
  C:\kafka> .\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties
```
posteriormente rode o kafka
```bash
  C:\kafka\bin\windows> .\kafka-server-start.bat ..\..\config\server.properties
```    