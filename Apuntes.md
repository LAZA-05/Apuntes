## Apuntes Debian

#### Boot repair
http://www.matthiaskauer.com/2015/03/install-boot-repair-on-debian-from-ubuntu-ppa/

### Activar sudo:

```sh
su
apt-get install sudo
sudo adduser nombre_usuario sudo
```

### Actualizar Debian:

```
sudo apt-get update && sudo apt-get upgrate && sudo apt-get dist-upgrade && sudo apt-get autoremove
```
### Instalar instalador gráfico de paquetes Debian
```sh
sudo apt-get install gdebi
### Instalar mis aplicaciones favoritas

```sh
sudo apt-get install htop
sudo apt-get install libreoffice
sudo apt-get install transmission-gtk
```
Equivalente a:
``` sh
sudo apt-get install htop libreoffice transmission-gtk
```
### Ejecutar *Scripts*

```sh
bash nombre_script.sh
```
