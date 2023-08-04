# Extraction of outputs


## Descargar de la pagina de github el archivo terminado en ``ipynb``

El programa genera un archivo con terminacion txt, el cual contiene tablas con informacion de los estados que nos interesa incluye como parametros:
* Fortaleza del oscilador
* Energia en voltios
* Longitud de onda
* el Assignment
* Transicion de los MOs
* Transicion con respecto al lumo y homo
* La probabilidad calculada
### Como usar el programa con google collab

* Buscar google collab en la web, generar un documento nuevo:
    *  En la parte superior izquierda hacer click en ``file``, ``upload notebook`` y suben el archivo ``extraccion_outs.ipynb``.
    *  Luego en el icono en donde dice Files, **marcado en la imagen con un circulo azul** (no ``file``, cuidado con eso) hay que ir al directorio root y crear una carpeta que puede ser nombrada como ustedes quieran, **en donde dice la flecha roja** (por defecto la deje como ``"archivos"``).
    *  En esa carpeta subir los archivos con terminacion ``.out`` que quieran, **en la imagen se muestra con un circulo amarillo**.

    ![](images\googllecollabhelper.png)
* Correr el programa:
    * En la segunda celda, en la tercera fila que comienza con ``path``, tienen que modificar el texto que dice ``"archivos"`` con el nombre de la carpeta que crearon (las comillas deben estar presentes).
    * En la pestaña que dice ``Runtime``, hacer click en donde dice ``"run all"`` (o tambien basta con presionar ``ctrl+F9``), **marcado con el ovalo verde**.
* Inputs:
    * En la segunda celda se les pedira que escriban el maximo y el minimo de la fortaleza del oscilador, si tienen un decimal lo ponen con un punto en vez de una coma. Una vez que se escriba uno tienen que pulsar enter. Una vez pulsado enter l programa seguira su curso (no tienen que hacer nada)
* Outputs:
    * el archivo generado va a estar en la carpeta ``root``, para acceder a la carpeta basta esperar a que termine el programa y presionar el simnbolo de carpeta que esta en la parte superior izquierda (dice ``files``, no ``file``).
    * El output tiene por defecto el nombre ``"output.txt"``. Desde ahi se puede descargar.
    * Una vez que el programa este terminado, en la ultima celda aparecera como output ``"listo"``. El programa puede ser ejecutado cuantas veces quieran.

