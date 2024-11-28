# Git Installing

1.Download Git Installer (Standalone Installer)
2.Open Installer
3.Finish dowload

### Check Download
1.Check Download with -> git --version

### Configuration
1.enter name -> git config --global user.name "LeonJungmeier"
2.E-Mail -> git config --global user.email "l.jungmeier@students.htl-leonding.ac.at"
3.Check Configuration -> git config --list


# create a github acc
1. enter email
2. choose a password

# Create new Repository, add file, execute commit
1.cd\, cd wlc
2.git repository created with -> git init
3.git status
4.git add .
5.git status
6.git commit -m "First version of protocol"
7.git status

### Connect with github
1.Connect with github -> git remote add origin https://github.com/Leon-Jungmeier/Protocoll.git
2.git branch -M main
3.git push -u origin main

# clone
1.git pull