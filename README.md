# Crear-un-USB-booteable-en-MAC

## Ver la lista de discos

diskutil list

## Desmontar el disco que se quiere bootear

diskutil unmountDisk /dev/disk2

sudo dd if=RUTA DEL ISO of=/dev/disk2 bs=1m

## Sacamos el disco

diskutil eject /dev/disk2
