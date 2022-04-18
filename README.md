# ubuntu-scripts

Get some basic packages setup in one go

# Usage

The 'clever' way:

```
sudo apt install curl

curl -o- https://raw.githubusercontent.com/waldobeest/ubuntu-scripts/master/install.sh | bash
```
note: if you also want docker installed, instead use install-with-docker.sh

OR if that fails:
```
sudo apt-get update

sudo apt install git

git clone https://github.com/waldobeest/ubuntu-scripts.git

cd ubuntu-scripts

./go.sh
```
note: if you also want docker installed, instead use go.sh --docker

# Credit

Inspired by https://github.com/mrseanryan/ubuntu-scripts