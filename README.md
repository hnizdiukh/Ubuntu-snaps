# Commands to install:

`
sudo apt-get install git
sudo snap install flameshot discord slack telegram-desktop code node
`
## chrome
`
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome-stable_current_amd64.deb
`
## meteor
`
sudo apt install curl
curl https://install.meteor.com/ | sh
`

## mongo
`
wget -qO - https://www.mongodb.org/static/pgp/server-4.4.asc | sudo apt-key add -
echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/4.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.4.list
sudo apt-get update
sudo apt-get install -y mongodb-org
`

# Websites:

https://studio3t.com/download/