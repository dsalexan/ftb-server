# Index
- Para contas originais do Minecraft: [Client](https://github.com/dsalexan/ftb-server#client)
- Para acesso pirata: [Pirate](https://github.com/dsalexan/ftb-server#pirate)

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
- At Curse Forge, go to Home and choose Minecraft as game
- Install FTB Revelation modpack, version **3.4.0**
  - ![Search FTB Revelation](assets/curseforge-ftb-search.png)
- Open modpack page
  - ![FTB Revelation](assets/curseforge-ftb-instance.png)
- Open modpack folder
  - ![FTB Revelation](assets/curseforge-ftb-folder.png)
- Open mods folder
  - ![FTB Revelation > mods](assets/curseforge-ftb-folder-mods.png)
- Drag OPTIFINE and VOICE CHAT to folder (**check github repo**)
  - ![Drag external mods](assets/curseforge-ftb-folder-mods-drag.png)

### Configuration

#### Recommended Specs
- At Curse Forge, click Play
  - ![Curse Forge > Play](assets/curseforge-ftb-play.png)
- Go to Installations > FTB Revelations > Edit
  - ![Edit FTB Revelations instance](assets/minecraft-edit.png)
- More options
  - ![More options](assets/minecraft-edit-options.png)
- Replace *4096M* by *8G* and *256M* by *4G*
  - ![JMV Arguments](assets/minecraft-edit-options-args.png)

### Run
- At Curse Forge, click Play
  - ![Curse Forge > Play](assets/curseforge-ftb-play.png)
- Make sure FTB Revelations is selected, then click Play
  - ![Curse Forge > Play](assets/minecraft-play.png)
- It can take from **6 to 10 min** to start
- Click Multiplayer > Add Server
- Input server name and address (35.199.100.22:25565)
  - ![Curse Forge > Play](assets/minecraft-multiplayer-server.png)

#### Minecraft Launcher Run times
- *15/12, started at 20:34 and ended at 20:40* — **~6min** (at 4GB)
- *15/12, started at 21:06 and ended at 21:10* — **~4min** (at 10GB)

## Pirate

### Installation
- Install TLauncher (https://tlauncher.org/en/)
- Select version **ForgeOptifine 1.12.2** or **Forge 1.12.2**, then click Install
  - ![TLauncher install](assets/tlauncher-install.png)
- Click the **gear logo* at bottom-right, and choose *Settings*
  - ![TLauncher settings](assets/tlauncher-configuracoes.png)
- In *Distinguir memória*, input *at least* **6124** (then click **Reter**)
  - ![TLauncher settings, RAM](assets/tlauncher-configuracoes-ram.png)
- Close Minecraft (**not TLauncher, keep it open**), open Curse Forge
- In Choose a game, pick **Minecraft**
  - If the game is not automatically detected, input %appdata/.minecraft as directory
- Install FTB Revelation modpack, version **3.4.0**
  - ![Search FTB Revelation](assets/curseforge-ftb-search.png)
- Open modpack page
  - ![FTB Revelation](assets/curseforge-ftb-instance.png)
- Open modpack folder
  - ![FTB Revelation](assets/curseforge-ftb-folder.png)
- Open mods folder
  - ![FTB Revelation > mods](assets/curseforge-ftb-folder-mods.png)
- Drag VOICE CHAT to folder (**check github repo**), and don't close the window
  - ![Drag external mods](assets/curseforge-ftb-folder-mods-drag-WITHOUT%20OPTIFINE.png)
- In TLauncher, open minecraft folder
  - ![TLauncher, minecraft folder](assets/tlauncher-openfolder.png)
- Copy all ***inexistent folders*** from *\<FTB instance folder\>* to *\<TLauncher minecraft folder\>*
  - ![FTB instance -> TLauncher folder](assets/folder-instance-to-launcher.png)
- Copy the ***config*** folder from *\<FTB instance folder\>* to *\<TLauncher minecraft folder\>*, replacing all files
- Copy ***mod's folder CONTENT*** from *\<FTB instance folder\>/mods* to *\<TLauncher minecraft folder\>/mods*, replacing all files
  - ![FTB instance -> TLauncher folder](assets/folder-instance-to-launcher-mods.png)

### Run
- At TLauncher, click Play
- It can take from **6 to 10 min** to start
- If a message about *MineTogether*/*Offline client* appears, click **Continue**
- Click Multiplayer > Add Server
- Input server name and address (35.199.100.22:25565)
  - ![Curse Forge > Play](assets/minecraft-multiplayer-server.png)

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
