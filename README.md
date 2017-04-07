1. "Makefile:" este es el archivo que contiene las instrucciones para compilar su código.
‘make io’: con este comando se crea la versión de su aplicación de un solo proceso.
‘make iofork’: con este comando se crea la versión de su aplicación que hace uso de la llamada al sistema fork().
2. "io.c:" Versión de un solo proceso de su aplicación.
3. "iofork.c:" Versión de su aplicación usando la función fork().
4. "fileutil.h:" En este archivo está la definición de la función que cuenta el número de bytes de un archivo y la función que me entrega la lista de archivos en un directorio dado.
5. "fileutil.c:" En este archivo se encuentra la implementación de la función que cuenta el número de bytes de un archivo y la función que me entrega la lista de archivos en un directorio dado.

