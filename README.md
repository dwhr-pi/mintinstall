# Mintinstall

Software Manager for Linux Mint.

![image](https://user-images.githubusercontent.com/19881231/122644976-86767180-d120-11eb-9cf4-eed2813f749b.png)

## Build
Get source code
```
git clone https://github.com/linuxmint/mintinstall
cd mintinstall
```
Build
```
dpkg-buildpackage --no-sign
```
Install
```
cd ..
sudo dpkg -i mintinstall*.deb
```

## Translations
Please use Launchpad to translate Mintinstall: https://translations.launchpad.net/linuxmint/latest/.

The PO files in this project are imported from there.



# Auf Debian, die Abhängigkeiten zuvor installieren.

anderes Paket... wird daher nicht installiert.
sudo apt-get install -y python3-aptdaemon
sudo apt-get install -y aptdaemon-data
sudo apt-get install -y python3-aptdaemon.gtk3widgets
sudo apt-get install -y python3-bs4
sudo apt-get install -y python3-configobj
sudo apt-get install -y python3-setproctitle

funktioniert
sudo apt-get install -y gir1.2-appstream-1.0
sudo apt-get install -y gir1.2-xapp-1.0

nicht gefunden
sudo apt-get install -y mint-common					https://github.com/linuxmint/mintcommon
sudo apt-get install -y app-install-data			https://community.linuxmint.com/software/view/app-install-data
sudo apt-get install -y

sudo dpkg -i mintinstall*.deb
