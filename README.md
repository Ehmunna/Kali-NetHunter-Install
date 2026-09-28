![logo](Kali.png)
# Termux Download 
https://t.me/ehmunna999/433
## Kali NetHunter Install
```
apt update -y
apt upgrade -y
pkg install wget -y
termux-setup-storage
```
## Kali directory
```
wget -O install-nethunter-termux https://offs.ec/2MceZWr
```
## permission 
```
chmod +x install-nethunter-termux
```
## Install 
```
./install-nethunter-termux
```
## Run Kali NetHunter 
```
nh
```
## Fix Internet problem 
```
cat /etc/resolv.conf
```
```
printf 'nameserver 1.1.1.1\nnameserver 8.8.8.8\n' > /etc/resolv.conf
```
```
apt update -y
apt upgrade -y
```
