# ubunturdp
## fix ubuntu rdp / xorg crash on login

sudo sed -i.bak '/fi/a xfce4-session \n' /etc/xrdp/startwm.sh

sudo systemctl restart xrdp

