# profiler-chop

## `utilidades, cli...`

# `CURL`

(-O guardará el archivo en el directorio actual con el mismo nombre):

### `curl -O http://SitioDeDescarga.com/miArchivo.txt.tar.xz`  

(-o guardará el archivo en el directorio actual con el nuevo nombre):

### `curl -o NuevoArchivo.txt.tar.xz http://SitioDeDescarga.com/miArchivo.txt.tar.xz`

(Si por alguna razón, la descarga se interrumpe, puedes reanudarla):

### `curl -C - -O http://SitioDeDescarga.com/miArchivo.tar.xz`

cairo dock, Plank, conky 

### `exec setxkbmap &  (~/.xprofile, ~/.xinitrc)`

https://wiki.archlinux.org/title/Xorg/Keyboard_configuration#Using_setxkbmap  

https://wiki.archlinux.org/title/Xinit#xinitrc

### `exec xbindkeys &  (~/.xprofile)`

### `echo $SHELL`

### `emulate sh`

### `fish -i`

### `makepkg -si PKGBUILD`

### `neofetch | lolcat`

# `REFLECTOR`

### `reflector --latest 5 --sort rate --save /etc/pacman.d/mirrorlist`

### `reflector --latest 200 --protocol http,https --sort rate --save /etc/pacman.d/mirrorlist`

### `reflector --country France,Germany --age 12 --protocol https --sort rate --save /etc/pacman.d/mirrorlist`

# `SSH`

### `ssh -p usuario@192.168...`

### `ssh -p root@192.168...`

### `ssh -2C usuario@192.168...`

### `setfont ter-132n`

### `setfont lat2-16 -m 8859-2`

### `grub-install /dev/sda`

### `grub-mkconfig -o /boot/grub/grub.cfg`

### `umount -R /mnt`
