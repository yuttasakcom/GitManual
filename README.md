## Git Manual
> คู่มือการใช้งาน Git ฉบับ YoProgrammer

## Table of Contents
- [Install](#install)
- [Generating a new SSH key](#generating-a-new-ssh-key)

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
```

## Instlal Git Flow
```
sudo apt install -y git-flow
```

## Git Clone
```
git clone your-repo
```

## Init Git Flow
```
git flow init
```

## Git Add
```
git add .
```

## Git Commit
```
git commit -am "commit description"
```

## Git Push
your create frist branch case
```
git push --set-upstream origin develop

or

git push -u origin develop
```
normal case
```
git push
```

## Git Pull
```
git pull
```

## Git Merge
```
git merge branch-name
```

## Git Flow Feature Start
```
git flow feature start feature-name
```

## Git Flow Feature Finish
```
git flow feature finish feature-name
```

## Git Flow Release Start
```
git flow release start release-name
```

## Git Flow Release Finish
```
git flow release finish release-name
```

## Git Branch
```
git branch branch-name
```

## Git Checkout
```
git checkout branch-name
```

## Git Status
```
git status
```