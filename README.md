# SistemasOperativos
Repositorio con los commands de sistemas operativos

| Comando | Descripción | Example |
|--|--|--|
| `clear` | Limpiar la consola. | `clear` (consola limpia)
| `cd <directorio o archivo>` | Para entrar a un directorio o archivo | `cd /home/ejimenezg149/diruno/archivo0` |
| `ls <directorio>` | Ver los archivos y directorios dentro del directorio. | `ls /home/ejimenezg149/diruno` = archivo0 |
|`echo`| Imprime en pantalla. | `echo "Hola"` imprime Hola |
|`mkdir <nombreDirectorio>`| Crear un directorio (se le puede agregar la ruta). | `mkdir  diruno` |
|`rm -r <nombreDirectorio o Archivo>`| Elimina un archivo o directorio. | `rm -r /home/ejimenezg149/diruno/archivo0`|
|`grep -rs “palabra” $HOME`| Para buscar una palabra en la crapeta de home. | `grep -rs “emily” $HOME`|
|`chown`| Para cambiar el dueño de una carpeta o directorio. | `chown ejimenezg149_02 archivo0`|
|`chmod +x archivo`| Para cambiar los permisos o el modo de un archivo. | `chmod +x archivo0.sh`|
|`su`| Entrar como a root de permisos. | `su` (después de ejecutarlo, se tiene que ingresar la contraseña)|
|`mv`| Mover archivos o renombrar. | `mv archivo_viejo.txt archivo_nuevo.txt`|
|`cp`| Copiar archivos o directorios. | `cp archivo.txt nuevo_destino`|
|`scp`| Copiar archivos o directorios con Secure Shell (Puede ser para copiar un archivo de una servidor remoto a uno local. | `scp usuario@servidor_remoto:/ruta/archivo.txt /ruta/local/`|
|`curl`| Para entrar o hacer request a una página web. | `su` (después de ejecutarlo, se tiene que ingresar la contraseña)|
|`su`| Entrar como a root de permisos. | `nombre=Mario curl -X GET -Lhttps://script.google.com/macros/s/AKfycby61tcPuNY3dw_3IYqNGFnR6Ei55MrLFPe_PHup_VMnGP07HeoRyIy5W8xlrheMB7vJ/exec?data=$nombre`(este es el ejemplo del la hoja de cáculo del prof)|
