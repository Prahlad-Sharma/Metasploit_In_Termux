# Metasploit Framework 6 in Termux

![Metasploit 6 running](https://i.imgur.com/yLFQhvP.png)

## How to install:
```bash
source <(curl -s https://kutt.it/msf)
```
**Or manual**
```bash
pkg install wget

wget https://raw.githubusercontent.com/Prahlad-Sharma/Metasploit_In_Termux/main/Metasploit.sh

chmod +x metasploit.sh

./metasploit.sh
```
## After install, run from terminal
```bash
# Start postgresql
./postgresql_ctl.sh start

# And run msfconsole
msfconsole
```
