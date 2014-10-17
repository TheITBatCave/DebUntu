apt-get update
apt-get install linux-headers-`uname -r`
git clone https://github.com/lwfinger/rtl8723au.git
git clone https://github.com/lwfinger/rtl8723au_bt.git
cd rtl8723au/
make
sudo make install
sudo modprobe 8723au
cd ..
cd rtl8723au_bt/
make
sudo make install
