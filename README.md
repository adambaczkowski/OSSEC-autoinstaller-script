# OSSEC-autoinstaller-script
OSSEC autoinstaller script written in bash (change params for your needs!)

On default it chooses: server

How to use:
sudo apt -y install expect #ON UBUNTU 

wget https://github.com/ossec/ossec-hids/archive/3.7.0.tar.gz

tar xvzf 3.7.0.tar.gz

cd ossec-hids-3.7.0

wget https://raw.githubusercontent.com/adambaczkowski/OSSEC-autoinstaller-script/main/autoinstall.exp

sudo expect -f script.exp
