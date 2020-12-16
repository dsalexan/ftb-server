# Client

## Specs

### Minimum
- **DO NOT USE OPTIFINE**
- **RAM**: *4GB*

### Recommended
- **RAM**: *8GB*

## Server

### IP
35.199.100.22:25565

## Original

### Installation
- Install Curse Forge
- At Curse Forge, install FTB Revelation modpack, version 3.4.0
- Open modpack folder, insert OPTIFINE and VOICE CHAT at mods (check github repo)

### Configuration

#### Recommended Specs
- At Curse Forge, go to Installations
- Select "Edit" at FTB Revelations
- More options
- Replace *4096M* by *8G* and *256M* by *4G*

### Run
- *15/12, started at 20:34 and ended at 20:40* — **~6min** (at 4GB)
- *15/12, started at 21:06 and ended at 21:10* — **~4min** (at 10GB)

## Pirate

### Installation
- Download Shiginima Launcher (https://mc-pc.net/launchers/343-shiginima.html)
- (???) Download Forge 1.12.2 (http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.12.2.html)
- Download FTB Revelation (http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.12.2.html)

### Setup
***not implemented***

# Server

## Setup

### Criar VM para minecraft
https://cloud.google.com/solutions/gaming/minecraft-server#schedule_backups

### Habilitar ftp na VM
https://cloud.google.com/compute/docs/instances/transfer-files#winscp

### Liberar acesso em pasta no Linux
https://askubuntu.com/questions/402980/give-user-write-access-to-folder

### Instalar FTB Revelation (ou FTB modpack qualquer)
https://forum.feed-the-beast.com/threads/guide-basic-notes-on-installing-ftb-infinity-evolved-server-on-linux-ubuntu-18-04-lts.302815/

- Jogar arquivo de instalação do FTB para linux dentro do server

#### server.properties
- online-mode=false *Q Q CUSTA COMPRAR A PORRA DO JOGO*

#### ops.json
- Inserir nicks de administradores

### External mods
At server folder, open mods and add:
- Voice chat

## Serve

### Start in screen

**sudo screen sh ./start.sh**

- *15/12, started at 20:35 and ended at 20:40* — **~5min**

### Dettach from screen
CTRL + A + D

### Rettach to screen
screen -r
