## Git Manual
> คู่มือการใช้งาน Git ฉบับ YoProgrammer

## Install
```
sudo apt install -y git
```

## Generating a new SSH key
```
ssh-keygen -t rsa -b 4096 -C "youremail@example.com"
```

## Adding SSH key to the ssh-agent
```
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
```

## SSH and GPG keys
```
cat .ssh/id_rsa.pub
```

## Setting Config
```
git config --global user.email "youremail@example.com"
git config --global user.name "Your Name"