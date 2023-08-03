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
<!--- mnveMOnyUv]TV{9YVY_IV7pOx8oQ;_L}l:OS`]Z --->

| [resumo](https://rogerdudler.github.io/git-guide/index.pt_BR.html) | -
| [git tutorial](https://www.w3schools.com/git/default.asp?remote=github) | -
| [credentials](https://git-scm.com/docs/git-credential-store) |

### 7 install VSCode

