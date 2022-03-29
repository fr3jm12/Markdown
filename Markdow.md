# 6 Comandos basicos de linux
### Comando pwd
   * Usa el comando pwd para encontrar la ruta del directorio (carpeta) de trabajo actual en el que te encuentras. El comando devolverá una ruta absoluta (completa), que es básicamente una ruta de todos los directorios que comienza con una barra diagonal (/) Un ejemplo de una ruta absoluta es /home/nombredeusuario.
### Comando cd 
   * Para navegar por los archivos y directorios de Linux, usa el comando cd. Te pedirá la ruta completa o el nombre del directorio, dependiendo del directorio de trabajo actual en el que te encuentres.
   Supongamos que estás en /home/nombredeusuario/Documentos y deseas ir a Fotos, un subdirectorio de Documentos. Para hacerlo, simplemente escribe el siguiente comando: cd Fotos.
   Otro escenario es si deseas ir a un directorio completamente nuevo, por ejemplo, /home/nombredeusuario/Peliculas. En este caso, debe escribir cd seguido de la ruta absoluta del directorio: cd /home/ nombredeusuario/Peliculas.
   Hay algunos atajos para ayudarte a navegar rápidamente: cd … (con dos puntos) para ir a un directorio hacia arriba
   cd para ir directamente a la carpeta de inicio cd- (con un guión) para ir al directorio anterior
   Como nota al margen, el shell de Linux distingue entre mayúsculas y minúsculas. Por lo tanto, debe escribir el nombre del directorio de forma exacta.
### Comando ls
   * El comando ls se usa para ver el contenido    de un directorio. Por defecto, este comando muestra el contenido de su directorio de trabajo actual.
    Si desea ver el contenido de otros directorios, escriba ls y luego la ruta del directorio. Por ejemplo, ingresa ls/home/nombredeusuario/Documentos para ver el contenido de Documentos.
    Hay variaciones que puedes usar con el comando ls:
    ls -R también listará todos los archivos en los subdirectorios ls -a mostrará los archivos ocultos ls -al listará los archivos y directorios con información detallada como los permisos, el tamaño, el propietario, etc...
### Comando cat 
   * Cat (abreviatura de concatenate, en inglés) es uno de los comandos más utilizados en Linux. Se utiliza para listar el contenido de un archivo en la salida estándar (sdout). Para ejecutar este comando, escribe cat seguido del nombre del archivo y su extensión. Por ejemplo: gato archivo.txt.
    Aquí hay otras formas de usar el comando cat:
    cat > nombredearchivo crea un nuevo archivo. cat nombredearchivo1 nombredearchivo2>nombredearchivo3 une dos archivos (1 y 2) y almacena la salida de ellos en un nuevo archivo (3) convertir un archivo a mayúsculas o minúsculas, cat nombredearchivo | tr az AZ> salida.txt.
### Comando cp 
   * Usa el comando cp para copiar archivos del directorio actual a un directorio diferente.
    Por ejemplo, el comando cp escenario.jpg /home/nombredeusuario/Imagenes crearía una copia de escenario.jpg (desde tu directorio actual) en el directorio de Imagenes.
### Comando mv 
  * El uso principal del comando mv es mover archivos, aunque también se puede usar para cambiar el nombre de los archivos.
    Los argumentos en mv son similares al comando cp. Debes escribir mv, el nombre del archivo y el directorio destino. Por ejemplo: mv archivo.txt /home/nombredeusuario/Documentos.
    Para cambiar el nombre de los archivos, el comando de Linux es mv nombreviejo.ext nombrenuevo.ext
