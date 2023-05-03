sudo dpkg -i virtualbox-7.0_7.0.8-156879~Ubuntu~jammy_amd64.deb 

sudo dpkg --configure -a

sudo apt-get -f install 

sudo apt-get update 

sudo apt-get dist-upgrade

sudo apt-get install build-essential dkms linux-headers-`uname -r` virtualbox-7.0 -s
