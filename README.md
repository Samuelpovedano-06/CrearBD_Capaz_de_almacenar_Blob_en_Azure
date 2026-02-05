# CrearBD Capaz de almacenar Blob en Azure 

## 1. Creación de la cuenta de almacenamiento
1.1. Si es tu primera vez en inicio le damos a "***Crear un nuevo recurso***", si no lo hes ve al paso 2.
![imagen_paso1_sin_cuenta](/images/blob1.png)

1.2. Ahora seleccionamos la opción de ***Cuentas de almacenamiento***.
   ![paso2_sin_seleccionar_Cuentas_de_almacenamiento](/images/blob2.png)

1.3. Si ya tenías aqui te saldrán las que ya habías creado anteriormente entoces le das al boton de ***Añadir***, si no te saldrá un formulario como es siguente para rellenar y crear la primera.
   
Nos encontraremos campos como:
- Suscripción: se agustara automaticamente a la quw tengas activa pero se puede cambiar.
- Grupo de recursos: Te deja seleccionar el grupo que quieras, yoº he creado uno para pruebas con este tipo de datos.
- Nombre de la cuenta de almacenamiento: es como el nombre de la base de datos.
- Región: por defecto sale Estados Unidos(US), lo recomendable es escoger la más cercana para reducir el tiempo de conexión, consulta y manejo de los datos.
- Rendimiento y Redundancia: al ser la primera y/o tener la **trial** gratuita de 1 mes no te dejara modificar nada.

Tras rellenar los datos le damos a ***Siguiente***.
   ![paso3_crear la primera_o_ver_y/o_crear_una_nueva](/images/blob3.png)

1.4. Este paso es por si quieres añadir una etiqueta o tag, pero a ser esto una prueba pues no los asignare asi que le damos a ***Siguiente*** de nuevo o a ***Revisar y Crear*** .
   ![paso4_tag_crear_revisar](/images/blob4.png)

1.5. Ese paso es solo para ver un resumen de lo introducido y porder retroceder a cambiar algo, si todo esta bien le damos al boton de ***Crear***.
   ![paso5_revisar_y_crear](/images/blob5.png)

1.6. Se empezara a crear y cuando termine nos saldra como en la foto, trás esto volvemos al inicio.
   ![paso6_crear](/images/blob6.png)

1.7. Si escroleamos un poco veremos que ahora se nos ha creado todo lo que no estaba antes en mi caso la cuenta de almacenamiento y el grupo de recursos, entonces entramos en la cuenta de almacenamiento.
   ![paso7_volver_menu_entrar](/images/blob7.png)


## 2. Creación del Contenedor del Blob
2.1. Una vez dentro de la cuenta de almacenamiento veremos muchas cosas para este caso nos interesan dos:
- Contenedores: esta en el apartado izquierdo dentro de ***Almacenamiento de datos*** veremos ***Contenedores*** marcado em morado en la foto, es es donde medianto sus respectivos conectores acede Power Apps y Power Automate a los Blobs.
- Blob Services: Este es el servicio de los contenedores por eso vereis que tiene el mismo icono.

Nosotros entraremos directamento donde pone blob Services en azul que se ve dentro de un recuadro rojo en la foto.
   ![paso8_selecionar_blob](/images/blob8.png)

2.2. Ahora le damos donde se ve el recuadro morado en ***Agregar contenedor***, se nos abrira una pequeña ventana en el lateral y ponemos el nombre del contenedor lo dejamos en pripado para asegurar la prbacidad del contenido y los datos avanzados igual, y le damos a crear y tendremos nuestro contenedor.
   ![paso9_crear_contenedor](/images/blob9.png)

2.3. Por aqui ya podemos ver el contenedor al que entraremos y subiremos un audio de varios formatos y una foto.
   ![paso10_vista_contenedor](/images/blob10.png)



## 3. Carga de Archivos
3.1 Una vez dentro le daremos al boton de ***Cargar*** marcado en morado, arrastraremos o subiremos el archivo seleccionado, tras arrastrarlo le daremos al boton de ***Cargar*** rodeado en rojo, trás eso ya podremos ver el archivo subido.
   ![paso11_subir_el_primer_archivo](/images/blob11.png)

3.2 Como podemos ver podemos incluso ver se pueden subir masde un archivo a la vez y de distinta extensión.
   ![paso12_subir_varios_archivos_distintos](/images/blob12.png)

3.3. Se puede ver la gran rescalavilidad y lo versatil que puede llegar a ser ya que es capaz de almacenar todo tipo de archivos juntos como fotos y audios de distinto tipo, siendo el problema de los formatos resuelto en su totalidad.
![paso13_multiformato](/images/blob13.png)























