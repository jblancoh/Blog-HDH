
# Tar

se refiere en Informática a un formato de archivos ampliamente usado en entornos UNIX, identificados por el sufijo de archivo ".tar". Además, hace referencia al programa para la manipulación de archivos que es estándar en estos entornos.

El formato fue diseñado para almacenar archivos de una forma conveniente en cintas magnéticas y de allí proviene su nombre, que proviene de "Tape ARchiver" (en inglés: archivador en cinta).

Se utiliza comúnmente en los servidores como un precursor de los archivos ZIP, funciona para recoger una gran selección de archivos y colocarlos en un solo archivo de almacenamiento.

Es usado para almacenar archivos y directorios en un solo archivo, no para comprimirlos. Dentro de los entornos Unix tar aparece como una orden que puede ser ejecutada desde la línea de órdenes de una consola de texto o desde un simple terminal.

** Ejemplos de opciones más usadas **

| Actividad	| /Opción |	Ejemplo      |
|-----------|--------|---------------|
|descomprimir/extraer	| -x	| tar -xf paquete.tar|
|visualizar lo que se realiza	|-v|	tar -xvf paquete.tar|
|archivar/crear el directorio kernel (y subdirect.)	|-c|	tar -cvf paquete.tar kernel/|
|comprimiendo con bzip2	|-j|	tar -cjvf paquete.tar.bz2 kernel/|
|comprimiendo con lzma	|-J|	tar -cJvf paquete.tar.lzma kernel/|
|comprimiendo con gzip	|-z|	tar -czvf paquete.tar.gz kernel/|
|comprimiendo con lzip	| --lzip |	tar -cvf paquete.tar.lz --lzip kernel/|
|comprimiendo con compress|	-Z|	tar -cZvf paquete.tar.Z kernel/|
|comprime utilizando la extensión facilitada en el nombre del fichero (ej. para bz2)|-a|	tar -cavf paquete.tar.bz2 kernel/|
|muestra el contenido de un archivo tar	|-t	|tar -tvf paquete.tar.bz2 kernel/|
