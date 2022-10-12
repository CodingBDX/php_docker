# docker powaaa
---

## install on linux
just copy and past into terminal
```
wget -O - https://gist.githubusercontent.com/fredhsu/f3d927d765727181767b3b13a3a23704/raw/3c2c55f185e23268f7fce399539cb6f1f3c45146/ubuntudocker.sh | bash
```

install in line docker on linux
- [] sudo apt update
- [] sudo apt install apt-transport-https ca-certificates curl software-properties-common
- [] curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
- [] sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"
- [] apt-cache policy docker-ce
- [] apt-cache policy docker-ce
- [] sudo apt install docker-ce
- [] sudo systemctl status docker
  

  ---
 ## install  for windows
  ---
download and launch it, that all
  https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe

  ---
 ## install for mac unix
  ---
  i don't know the process, but here, you have easy link
  https://docs.docker.com/desktop/install/mac-install/

  ## extension roxx
  download extension pour toutes les versions

https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker

## for best practice
download file of reposetory
-  click right on "dockerfile", "build image"
-  click right on "docker-compose", 'compose-up", select all choices
-  reload directory of the reposetory files, and at right screen, it propose to enter docker 👍

### the next level
dear friend, you are on new world, look at file "docker-compose", you have all informations for php, mysql connection(extension mysql database), symphony, emojisens, zsh,dxdebug,phpmyadmin,git lot stuffs...