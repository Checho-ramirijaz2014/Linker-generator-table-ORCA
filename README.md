# Extraction of outputs


## Descargar de la pagina de github el archivo terminado en ipynb

El programa genera un archivo con terminacion txt, el cual contiene tablas con informacion de los estados que nos interesa incluye como parametros:
* Fortaleza del oscilador
* Energia en voltios
* Longitud de onda
* el Assignment
* Transicion de los MOs
* Transicion con respecto al lumo y homo
* La probabilidad calculada
### Como usar el programa con google collab

* buscar google collab en la web, generar un documento nuevo
    *  En la parte superior izquierda hacer click en file, upload notebook y suben el archivo ipynb.
    *  Luego en el icono en donde dice Files (no file, cuidado con eso) hay que ir al directorio root y crear una carpeta que puede ser nombrada como ustedes quieran.
    *  en esa carpeta subir los archivos con terminacion .out que quieran.
* correr el programa
    * En la segunda celda, en la tercera fila que comienza con path, tienen que modificar el texto que dice "archivos" con el nombre de la carpeta que crearon (las comillas deben estar presentes)
    * En la pestaña que dice Runtime, hacer click en donde dice "run all".
* inputs
    * En la segunda celda se les pedira que escriban el maximo y el minimo de la fortaleza del oscilador, si tienen un decimal lo ponen con un punto en vez de una coma. Una vez que se escriba uno tienen que pulsar enter. El programa seguira su curso 
* General: formato no seguido PEP8.
    * el archivo generado va a estar en la carpeta root, para acceder a la carpeta basta con presionar el simnbolo de carpeta que esta en la parte superior izquierda (dice files, no file).
    * El output tiene por defecto el nombre "output.txt". Desde ahi se puede descargar

