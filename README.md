# Pi-Forks

git clone https://github.com/dcoredump/dexed.git
git checkout origin native-lv2
cd dexed/src
make install

wget -q -O - http://rpi.autostatic.com/autostatic.gpg.key | sudo apt-key add -
sudo wget -q -O /etc/apt/sources.list.d/autostatic-audio-raspbian.list http://rpi.autostatic.com/autostatic-audio-raspbian.list
sudo apt-get update

sudo apt-get install carla jackd qjackctl
