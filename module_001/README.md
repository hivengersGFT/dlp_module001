# hivengers

En la carpeta module_001 encontrarás un fichero docker-compose. 
Ejecuta el comando docker-compose up -d desde la ubicación esta carpeta.

Para la ingestión de datos, trabajaremos con NIfi.

Abre Nifi en el explorador (http://localhost:8080/), tendrás el panel vacío.
Vamos a cargar una template que se encargará de ingestar los datos.
Pinchar botón derecho y clickar “ulpoad template”.
Seleccionar el fichero module_001/nifi-conf/nyc2hdfs.xml
Cuando el template esté cargado hay que arrastrar desde la barra de 
herramientas de arriba el que se nombra como template y seleccionar el único disponible.
una vez disponible la template. Ejecuta. 

Abre Zeppelin (http://localhost:9999/)  y importa el archivo module_001.json.
Allí encontrarás una descripción.
Ejecuta los parrafos del notebook.
