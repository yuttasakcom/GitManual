## Git Handbook

## Install
```
sudo apt install -y git
```

## Generating a new SSH key
```
ssh-keygen -t rsa -b 4096 -C "yuttasakcom@gmail.com"
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
git config --global user.email "you@example.com"
git config --global user.name "Your Name"