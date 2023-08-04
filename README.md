# How to create a env to code with virtual machine

### 1 Download Oracle VM virtualBox 
don't forget the Extension Pack

### 2 Download latest ubuntu LTS

### 3 Create and install it on the VM

### 4 Install guest additions
https://linuxconfig.org/install-virtualbox-guest-additions-on-linux-guest

### 5 improve confort

#### 5.0 keyboard abnt

Portuguese(Brazil, no dead keys)


#### 5.1 make terminal ignore case
```
sudo nano ~/.inputrc
set completion-ignore-case on
```
 - try touch?
```
touch ~/.inputrc >> "set completion-ignore-case on"
```


#### 5.2 set always on top hotkey
install [dconf](https://fostips.com/set-always-on-top-hotkey-ubuntu-20-04/)
```
sudo apt install dconf-editor
```
 - go to: /org/gnome/desktop/wm/keybindings/always-on-top
 - unbind "use default value"
 - past: ['<Control><Shift>T']


#### 5.3 windows in center
```
sudo apt install gnome-tweaks
```
Windows>Center New Windows


### 6 install git
| [resumo](https://rogerdudler.github.io/git-guide/index.pt_BR.html) | -
| [git tutorial](https://www.w3schools.com/git/default.asp?remote=github) | -
| [credentials](https://git-scm.com/docs/git-credential-store) |

use this to save your credentials:
```
git config credential.helper store
git push https://github.com/[your_repo].git
```
use your personal acess token on github (Settings/Developer Settings) as password
<!--- mnveMOnyUv]TV{9YVY_IV7pOx8oQ;_L}l:OS`]Z --->


### 7 install VSCode

### 8 install PlatformIO IDE
[follow this guide](https://www.youtube.com/watch?v=5edPOlQQKmo&list=PLzvRQMJ9HDiQ3OIuBWCEW6yE0S0LUWhGU&index=7)
use to install:
```
sudo apt install python3-venv
```


