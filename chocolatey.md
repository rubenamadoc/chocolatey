# Uso
Chocolatey se utiliza a través de la PowerShell por un comando llamado choco. Voy a explicar tres modos con el que podemos disfrutar de esta magnífica herramienta.

## Search
Este modo nos permitirá buscar paquetes en los repositorios. Su estructura es ```Choco Search nombre_paquete```.
Utilizaré de ejemplo mozilla.

```
Choco Search mozilla
```

[EJEMPLO](https://github.com/rubenamadoc/chocolatey/blob/main/IMG/Busqueda.png)

## Install
Nos permite instalar el paquete deseado.
Tras la búsqueda, seleccionamos el paquete adecuado para instalar firefox.

```
Choco Install FirefoxESR
```

Al ejecutar el paquete deseado. Chocolatey le preguntará por la ejecución de algunos scripts. Presionando A aceptas todos y presionando Y se acpetarán de uno a uno.


[EJEMPLO](https://github.com/rubenamadoc/chocolatey/blob/main/IMG/Instalacion.png)

## Uninstall
Desinstala paquetes.

```
Choco Uninstall nombre_paquete
```

En este caso también preguntará si queremos ejecutar todos los scripts o uno a uno.

[EJEMPLO](https://github.com/rubenamadoc/chocolatey/blob/main/IMG/Desinstalacion.png)
