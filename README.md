## How-to-install-linux-on-windows

### 1. Install Windows Subsystem for Linux (wsl)
Cheak if wsl is installed:
<br>
Type `wsl -l -v` in cmd
<br>
If wsl is not installed, install it by:
<br>
Type `wsl --install` to install wsl

### 2. Install a linux distribution
Go to microsoft store and install ubuntu
<br>
**Sometimes when you type `wsl --install` in cmd, windows will download the default linux distribution which is ubuntu for you.

### 3. Enable Hyper V
Type `systeminfo` in cmd to check if hyper v is enable
<p>If hyper v is enable is will show: <br>
"Hyper-V Requirements:      A hypervisor has been detected. Features required for Hyper-V will not be displayed."</p>

### 4. Download extension to access ubuntu in vscode
<p>Install the <a href="https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack" target="_blank" rel="noopener noreferrer">Remote Development</a> extension pack in vscode</p>

### 5. Open Ubuntu
Open ubuntu and set up new user and password
Type `login yourusername` in ubuntu terminal or vscode ubuntu terminal to login
<br>
<p>**Note: when u type in password it wont show anything but your still typing in words so dont think the input is broken</p>

### 6. Download gcc on ubuntu
Now you can use ubuntu in your vscode but when u try to run c/c ++ code it will not work
<br>
You need to download gcc in ubuntu through the terminal in vscode for ubuntu or the terminal when u run ubuntu
<br>
To install gcc just type `sudo apt install gcc` in cmd of the ubuntu
<br>
** its best to check for any update with `sudo apt update` before installing gcc

### 7. Run C/C ++ code on ubuntu through vscode
<p>Now you can basically code in ubuntu through vscode :)</p>

### Additional commands
Type `wsl --shutdown` to forcibly stop the distribution
