# dwm

Mi configuración de dwm. Requiere de dwmblocks y libxft-bgra (para emojis y barra de estado).

Requiere además de la instalación de st, por lo cual recomendaría descargarlo desde el repositorio de Luke Smith: [https://github.com/lukesmithxyz/st](https://github.com/lukesmithxyz/st)

Para arrancar desde un manejador de escritorio como _lightdm_, deberán crear un archivo en `/usr/share/xsessions` de nombre `dwm.desktop` con el siguiente contenido:

```
[Desktop Entry]
Encoding=UTF-8
Name=dwm
Comment=Dynamic Window Manager
Exec=dwm
Type=XSession
```

Cualquier modificación que se quiera realizar sobre dwm debe de hacerse en el archivo `config.h` y no sobre `config.def.h`.
