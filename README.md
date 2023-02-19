# profiler-chop

## DISEÑO DE CONSOLA

 El mapa de teclas predeterminado de la consola es US.  
 Los diseños disponibles se pueden enumerar con:

```ruby
ls /usr/share/kbd/keymaps/**/*.map.gz
```

## PERMISOS

> (RECURSIVO a los archivos de un directorio)

```ruby
sudo chmod -R +x script   
```

## utilidades, cli...

```ruby
sudo chown root:root archivo.sh
```
```ruby
sudo chmod +x archivo.sh
```
## CURL

* (-O guardará el archivo en el directorio actual con el mismo nombre):

```ruby
curl -O http://SitioDeDescarga.com/miArchivo.txt.tar.xz
```

* (-o guardará el archivo en el directorio actual con el nuevo nombre):

```ruby
curl -o NuevoArchivo.txt.tar.xz http://SitioDeDescarga.com/miArchivo.txt.tar.xz
```

* (Si por alguna razón, la descarga se interrumpe, puedes reanudarla):

```ruby
curl -C - -O http://SitioDeDescarga.com/miArchivo.tar.xz
```

* cairo dock, Plank, conky 

## EXO

```ruby
exo-open --launch TerminalEmulator
```

## EXEC

```ruby
exec xbindkeys &  (~/.xprofile)
```
```ruby
exec setxkbmap &  (~/.xprofile, ~/.xinitrc)
```

https://wiki.archlinux.org/title/Xorg/Keyboard_configuration#Using_setxkbmap  

https://wiki.archlinux.org/title/Xinit#xinitrc

```ruby
echo $SHELL
```
```ruby
emulate sh
```
```ruby
fish -i
```
```ruby
makepkg -si PKGBUILD
```
```ruby
neofetch | lolcat
```

## REFLECTOR

```ruby
reflector --latest 5 --sort rate --save /etc/pacman.d/mirrorlist
```
```ruby
reflector --latest 200 --protocol http,https --sort rate --save /etc/pacman.d/mirrorlist
```
```ruby
reflector --country France,Germany --age 12 --protocol https --sort rate --save /etc/pacman.d/mirrorlist
```
## SSH

```ruby
cat /dev/null > /home/profiler/.ssh/known_hosts
```
```ruby
ssh -p usuario@192.168...
```
```ruby
ssh -p root@192.168...
```
```ruby
ssh -2C usuario@192.168...
```
```ruby
setfont ter-132n
```
```ruby
setfont lat2-16 -m 8859-2
```
```ruby
terminal-colors -o
```
```ruby
grub-install /dev/sda
```
```ruby
grub-mkconfig -o /boot/grub/grub.cfg
```
```ruby
umount -R /mnt
```
