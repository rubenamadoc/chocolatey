# Uso
Chcolatey se utiliza a través de la PowerShell por un camando llamado choco. Voy a explicar tres modos con el que podemos disfrutar de esta magnífica herramienta.
## Search
Este modo nos permitirá buscar paquetes en los repositorios. Su estructura es choco search nombre_paquete.
Utilizaré de ejemplo mozilla.
choco search mozilla
[EJEMPLO]()

## Install
Nos permite instalar el paquete deseado.
Tras la búsqueda, seleccionamos el paqeute adecuado para instalar firefox.
choco install nombre_paquete

Al ejecutar el paquete deseado. Chocolatey le preguntará por la ejecución de algunos scripts. Presionando A aceptas todos y presionando Y se acpetarán de uno a uno.

[EJEMPLO]()

## Desinstalar
Desinstala paquetes.
choco uninstall nombre_paquete.
En este caso también preguntara si queremos ejecutar todos los scripts o uno a uno.
[EJEMPLO]()