# Atelier configuration, compilation et lancement d'un litecoin alternatif

## Crédits
* Atelier crée par Samuel Eyre
* Inspiré du tutoriel d'aqua : https://www.youtube.com/channel/UCgnaLsp9LBdRvJDppY59cvw
#### Contributeurs
* Xavier Lavayssière
* Quentin (Phylante)

## Licence
CC BY SA NC

Vous avez le droit de le modifier et partager, à condition de créditer les auteurs originaux et hors utilisation commerciale.

## Notes
#### Bricotux 

bobby // mdp bricodeur
**Instalation des guest editions de VirtualBox**
sudo apt install build-essential dkms linux-headers-generic 
sudo apt install build-essential dkms linux-headers-$(uname -r)
cd /media/bricodeur/VBox_GAs_5.2.10/
sudo ./VBoxLinuxAdditions.run

**outils de dévéloppement**
sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils python3

**libboost**
* sudo apt-get install libboost-all-dev
* sudo apt-get install libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-program-options-dev libboost-test-dev libboost-thread-dev

**Installation librairie du depôt bitcoin**
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:bitcoin/bitcoin
sudo apt-get update
sudo apt-get install libdb4.8-dev libdb4.8++-dev

**Additionnel**
sudo apt-get install libminiupnpc-dev libzmq3-dev

sudo apt-get install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler

sudo apt install git

> install visual code
ethereum too

sudo add-apt-repository -y ppa:ethereum/ethereum
rebsudo apt-get update
sudo apt-get install ethereum


#### Configuration 

Création de torrent

udp://tracker.torrent.eu.org:451/announce









