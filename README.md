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

# Aliases

`
nano ~/.bashrc
`

`
killport(){ 
  sudo kill -9 $(sudo fuser -n tcp $1 2> /dev/null);
}

alias add='git add .'
alias commit='git add .; git commit -m'
alias gcm='git commit -m'
alias ns='npm start'
alias push='git push'
alias dev='git checkout dev; git pull'
alias devel='git checkoud devel; git pull'
alias branch='git checkout -b'
alias fn0='echo 0 | sudo tee /sys/module/hid_apple/parameters/fnmode'
alias fn1='echo 1 | sudo tee /sys/module/hid_apple/parameters/fnmode'
`

`
source ~/.bashrc
`

