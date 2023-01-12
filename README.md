# OSSEC-autoinstaller-script
OSSEC autoinstaller script written in bash

How to use:

wget https://github.com/ossec/ossec-hids/archive/3.7.0.tar.gz

tar xvzf 3.7.0.tar.gz

cd ossec-hids-3.7.0

wget https://raw.githubusercontent.com/adambaczkowski/OSSEC-autoinstaller-script/main/autoinstall.exp

expect -f script.exp
