# Ejecutar código  con Notepad++:

  Una vez guardado el archivo, pulsar f5 y poner la siguiente línea, seguidamente pulsar enter.
  
## si queremos ejecutar para javascript:  

    cmd /K cd "$(CURRENT_DIRECTORY)"&node "$(FULL_CURRENT_PATH)"&pause&exit

## si queremos ejecutar para python:  

    cmd /K cd "$(CURRENT_DIRECTORY)"&python "$(FULL_CURRENT_PATH)"&pause&exit
    
también se puede guardar el comando y asignarle una tecla rápida.

## Atajos de teclado útiles de Notepad++

* CTRL + D : Si no se tiene seleccionado nada se duplica la línea donde se encuentra el puntero en la línea debajo, si se tiene seleccionado un texto, lo duplica a continuación
* CTRL + L : Elimina la línea en la que se encuentra el cursor
* CTRL + Q : Comentar / Descomentar la línea en la que se encuentra el cursor o selección de líneas con // al principio de esta
* CTRL + SHIFT + Q : Comentar / Descomentar la línea en la que se encuentra el cursor o selección exacta de texto con /* al principio y */ correspondientemente
* CTRL + SHIFT + FLECHA  arriba o abajo: Intercambiar línea actual por la de arriba/abajo respectivamente
* CTRL + ESPACIO : Autocompletar nombre de funciones / propiedades dependiendo del lenguaje

[Regresar a la página principal](https://miguelbarrazaar.github.io/javascript-itgrarte-2021/)