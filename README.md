# nethome-pizerow3


doku magicmirror pizero3
minimal image

sudo apt update
sudo apt -y install xorg

https://github.com/sdetweil/MagicMirror_scripts
bash -c  "$(curl -sL https://raw.githubusercontent.com/sdetweil/MagicMirror_scripts/master/raspberry.sh)"

bash -c "$(curl -sL https://raw.githubusercontent.com/sdetweil/MagicMirror_scripts/master/screensaveroff.sh)"



bash -c "$(curl -sL https://raw.githubusercontent.com/sdetweil/MagicMirror_scripts/master/fixuppm2.sh)"

nano MagicMirror/installers/mm.sh
