#git update local repository
-------------
cd ~/appleincident
git pull master

#commit current changes
-------------
cd ~/appleincident
git commit -m "comment"

#push local modifications to server
-------------
cd ~/appleincident
git push master


#connect to raspberry using ssh
-------------
ssh pi@192.168.0.2

raspberry


#change network settings
-------------
cd /etc/network/

sudo cp interfaces.STATIC interfaces

sudo cp interfaces.DHCP interfaces


#run demo program
-------------
cd ~/appleincident
python demo.py
