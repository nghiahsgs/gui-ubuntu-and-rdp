# gui-ubuntu-and-rdp
gui ubuntu and rdp


## 1/update ubuntu
```
sudo apt update
```

## 2/ install xubuntu-desktop
```
sudo apt install xubuntu-desktop
light dm
```

## 3/ install xrdp
```
sudo apt install xrdp
sudo systemctl status xrdp
```

## 4/ add new user
```
sudo adduser xrdp ssl-cert
sudo systemctl restart xrdp
```

## 5/ open port ufw
```
sudo ufw allow 3389
```

## 6/ config rdp
```
sudo service xrdp stop
```

```
vi /etc/xrdp/startwm.sh
command 2 last line in files
add last line
startxfce4
```

```
sudo systemctl restart xrdp
```

## 7/ Open rdp on windows and connect to


## 8/ Reinstall terminal
```
sudo apt remove gnome-terminal
```

```
sudo apt install gnome-terminal
```
