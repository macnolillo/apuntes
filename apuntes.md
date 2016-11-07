## Tutorial Debian

### Boot Repair
http://www.matthiaskauer.com/2015/03/install-boot-repair-on-debian-from-ubuntu-ppa/

### Activar sudo:

su
```apt-get install sudo
sudo adduser nombre_usurio sudo
´´´

### Activar Debian

```sh
sudo apt-get update && sudo apt-get upgrade && sudo apt-get dist-upgrade && sudo apt-get autoremove
```

### Instalar instalador gráfico de paquetes debian

```sh
sudo apt-get install gdebi
```

### Instalar mis aplicaciones favoritas

```sh
sudo apt-get install htop
sudo apt-get install libreoffice
sudo apt-get install transmission-gtk
```

Equivale a:
```sh
sudo apt-get install htop libreoffice transmision-gtk
```

### Ejecutar *scripts*

```sh
bash nombre_scripts
```
