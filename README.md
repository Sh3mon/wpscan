## WPscan - Wordpress Security Scanner 
apt update && apt upgrade -y

git clone https://github.com/sh3mon/WPscan

cd Wpscan

pkg install python2

pip2 install -r requirements.txt

python2 wpscan.py -t site.com
