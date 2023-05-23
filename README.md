## 🖇 VPS Deployment

sudo apt-get update && sudo apt-get upgrade -y
sudo apt-get install python3-pip ffmpeg -y
sudo pip3 install -U pip
curl -fssL https://deb.nodesource.com/setup_17.x | sudo -E bash - && sudo apt-get install nodejs -y && npm i -g npm
mkdir music && cd music
git clone https://github.com/Ayubskk/GSID-Music &&  cd CilikMusic
pip3 install -U -r requirements.txt
cp sample.env .env
vi .env

Edit .env
Press I button on keyboard to start editing.
Press Ctrl + C  once you are done with editing vars and type :wq to save .env or :qa to exit editing.

screen -S music
dash start

CTRL A + D
