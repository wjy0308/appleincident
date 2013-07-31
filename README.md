#git update local repository
-------------
git pull master

#commit current changes
-------------
git commit -m "comment"

#push local modifications to server
-------------
git push master


#connect to raspberry using ssh
-------------
~/.ssh pi@192.168.0.2

raspberry


#change network settings
-------------
cd /etc/network/

cp interfaces.STATIC interfaces

cp interfaces.DHCP interfaces
