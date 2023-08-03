# How to create a env to code with virtual machine

### 1 Download Oracle VM virtualBox 
don't forget the Extension Pack

### 2 Download latest ubuntu LTS

### 3 Create and install it on the VM

### 4 Install guest additions
https://linuxconfig.org/install-virtualbox-guest-additions-on-linux-guest

### 5 make terminal ignore case
```
sudo nano ~/.inputrc
set completion-ignore-case on
```
 - try touch?
```
touch ~/.inputrc >> "set completion-ignore-case on"
```

### 6 install git
use this to save your credentials
```
git config credential.helper store
git push https://github.com/[your_repo].git
```
use your personal acess token on github (Settings/Developer Settings) as password

### 7 install VSCode

