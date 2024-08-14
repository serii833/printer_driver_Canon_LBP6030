## Canon LBP6030 linux driver

```bash
sudo apt update && sudo apt upgrade
sudo apt install cups 
sudo apt install libglade2-0 gcc-libs libxml2

# не знаю, надо или нет
??? sudo apt install build-essential

sudo apt install libjpeg-turbo8

# не знаю, надо или нет
??? sudo apt install libjpeg-turbo8-dev

# что-то из этого или оба 
??? sudo apt install libgcrypt
??? sudo apt install libgcrypt-dev

sudo apt install libcupsimage2
```


working driver `linux-UFRIILT-drv-v500-uken-18.tar.gz`  
unpack and run `sudo ./install.sh`


link to driver
`http://gdlp01.c-wss.com/gds/0/0100005950/10/linux-UFRIILT-drv-v500-uken-18.tar.gz`

arch aur package
` https://aur.archlinux.org/packages/cndrvcups-lt`

https://wiki.archlinux.org/title/CUPS#Network_2
https://wiki.archlinux.org/title/CUPS/Troubleshooting
https://www.cups.org/doc/admin.html


