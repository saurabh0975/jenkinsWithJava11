Jenkins Word file sudo apt-get update

sudo apt install -y openjdk-11-jre-headless

wget -qO - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -

sudo apt-get -y upgrade

echo deb https://pkg.jenkins.io/debian-stable binary/ | sudo tee /etc/apt/sources.list.d/jenkins.list

sudo apt-get update

sudo apt-get -y install jenkins
