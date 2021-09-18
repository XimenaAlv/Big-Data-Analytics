# Big-Data-Analytics
# TALLER 1
# Elaborado por Ximena Alvarez y John Avila.

## Parte 1

Instalamos el software VirtualBox
![alt text](1.png?raw=true "Title")

Lo primero a realizar es validar la versión del java con el siguiente comando:

![alt text](2.png?raw=true "Title")

se procede a realizar la generación del SSH, se le genera la llave principal y se le brinda permisos a al usuario creado, luego con el comando SSH localhost validamos que este arriba y este ok el usuario creado.

![alt text](3.png?raw=true "Title")

Luego se procede a realizar la instalación del paquete de Hadoop, una vez descargado y descomprimido validamos con el comando ls que se encuentre tanto el .gz y la carpeta hadoop.

![alt text](4.png?raw=true "Title")

Para los siguientes pasos a realizar debemos corroborar la versión del javac para ello se ejecuta con el comando which javac.

![alt text](5.png?raw=true "Title")

Usamos el comando para abrir el hdf-site.xml para editarlo, también procedemos a editar los archivos: mapred-site.xml, yarn-site.xml

![alt text](6.png?raw=true "Title")
![alt text](7.png?raw=true "Title")

Verificamos con el comando NameNode, los servicios de iniciación del Hadoop.


![alt text](8.png?raw=true "Title")
![alt text](9.png?raw=true "Title")

Para navegar en la versión que descargarnos de Hadoop es necesario ejecutar el comando ./start-dfs.sh, ./start-yarn.sh

![alt text](10.png?raw=true "Title")
![alt text](11.png?raw=true "Title")
![alt text](12.png?raw=true "Title")

![alt text](13.png?raw=true "Title")
![alt text](14.png?raw=true "Title")

Luego verificamos en los localhost la instalación de hadoop por el navegador:

http://localhost:9870

![alt text](15.png?raw=true "Title") 

http://localhost:9864  

![alt text](16.png?raw=true "Title")

http://localhost:8088  

![alt text](17.png?raw=true "Title")

# Parte 2

![alt text](18.png?raw=true "Title")

![alt text](19.png?raw=true "Title")

![alt text](20.png?raw=true "Title")

![alt text](21.png?raw=true "Title")

![alt text](22.png?raw=true "Title")

![alt text](23.png?raw=true "Title")

![alt text](24.png?raw=true "Title")

![alt text](25.png?raw=true "Title")

![alt text](26.png?raw=true "Title")

![alt text](27.png?raw=true "Title")

![alt text](28.png?raw=true "Title")

![alt text](29.png?raw=true "Title")

![alt text](30.png?raw=true "Title")

El programa género la contabilidad de los de la expresión regular 'dfs[a-z.]+' lo que quiere decir que va a extraer todas las palabras que inicien con dfs y el resultado que lo guarde en la carpeta output.

MapReduce implementa clústeres de datos para el procesamiento, donde el usuario solo le define las funciones cómo map o reduce, el implementa un sistema de archivos distribuidos para leer y escribir los datos, lo típico es utilizar el sistema de archivos hadoop distributed, que es reconocido cómo HDFS.

Para la segunda  parte se creó el txt llamado canción.txt 

![alt text](31.png?raw=true "Title")

Luego se crea una estructura de archivo, donde toma todos los archivos de la carpeta hola

![alt text](32.png?raw=true "Title")

Luego se sube el archivo de configuración de Hadoop 

![alt text](33.png?raw=true "Title")

Luego nos dirigimos a la ruta anteriormente utilizada y cambiamos el grep por WordCount, y en nuestro ejemplo no tomamos ninguna expresión regular. 

![alt text](34.png?raw=true "Title")

Luego con el comando llamamos la carpeta hola mostrándonos el único archivo que contiene y su resultado es la muestra del TXT.

![alt text](35.png?raw=true "Title")

También desde el localhost podemos ver en la parte superior que estamos ubicados en la carpeta hola y en su interior un archivo llamado canción.txt.
![alt text](36.png?raw=true "Title")

En este caso cómo resultado nos conto todas las palabras, en este caso no se filtró de ninguna manera y el conteo nos da 1033

![alt text](37.png?raw=true "Title")

# Parte 3

Se comprueba que quedó instalado el cluster de Spark con su maestro y su esclavo

![alt text](38.png?raw=true "Title")

Se ejecuta pyspark

![alt text](39.png?raw=true "Title")

Se crea archivo babas.txt con uno de los cuentos de Julio Cortazar

![alt text](40.png?raw=true "Title")

Se ejecuta el código de ejemplo de Word Count para realizar el conteo de repeticiones de cada palabra.

![alt text](41.png?raw=true "Title")

Se abre la carpeta “result” en la cual encontramos un archivo llamado “part-0000” dónde está detallado el conteo de cada palabra del cuento.

![alt text](42.png?raw=true "Title")

# Parte 4

Se clona el repositorio 

![alt text](43.png?raw=true "Title")

Se descarga y se descomprime archivo stocks_price_final.csv

![alt text](44.png?raw=true "Title")
