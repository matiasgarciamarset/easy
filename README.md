# easyCommand
Allow executing instructions in Spanish for ssh, ftp and different files protocols in easy way.

Permite la ejecucion de diferentes instrucciones para la manipulacion de archivos por diferentes protocolos de forma sencilla.

Leguaje del proyecto: Java

Para ejecutarlo: java sshCommand.jar nombreArchivoInstrucciones.txt

donde nombreArchivoInstrucciones.txt = contiene las instrucciones a ejecutar. Por ejemplo:

conectar ssh -host="nombre.host" -user="pepe" -pass="unapass" -port="22"
descargar -remote="test.txt" -local="nuevo.txt"

donde se conecta a dicho host y descarga el archivo test.txt y lo guarda en nuevo.txt.
