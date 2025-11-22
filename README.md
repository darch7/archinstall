#darchinstall 

------------------------------------------------------------------------------------

--------------------------------------------------------------------------------------

nota:

pacman -Sy git wget

cd archinstall

para ejecutar el script      ./archinstall


para seleccionar el disco si o si debe ser asi /dev/sda ; /dev/sdb ,etc, sino se escribe tal cual dara error


nota: el instalador trae para detectar automaticamente los drivers para la gpu y video . Todo lo que instala aparecerá en la tty. Ya viene con codecs y controadores para celulares, codecs multimedia, xorg y drivers wifi.
al terminar el script tendras una instalación de arch linux puro sin entorno grafico y con un kernel lts (a mi criterio el mejor mas para algo mas serio como trabajar por ej), con un esquema de btrfs apto ya para snapshots y tambien para dualboots deberia detectarlo automaticamente Listo para un wm o un DE a eleccion del usuario.


#Opcional


para poder instalar mi bspwm despues de instalar este script de instalacion puedes logearte por tty y descargar el script para instalar mi config completa de bspwm git clone https://github.com/darch7/wm y ejecuta el script.




cualquier bug pudes reportarlo a @darch_7



creditos @hector_vega @Bourne_Again



![captura-pantalla-210119-2317-16](https://user-images.githubusercontent.com/70046164/105121824-c541c600-5ab3-11eb-9b7b-d3889715f54b.png)
