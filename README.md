# Base de datos

La estructura es la siguiente.

![aut](/imagenes/autor.png)

![lib](/imagenes/libro.png)

![cap](/imagenes/capitulo.png)

Las llaves foraneas de la tabla capitulo son:

![for](/imagenes/foraneas.png)


# conexion

Primero se conecta a la base de datos con los datos pertinentes.

![img0](/imagenes/i0.png)

# Crear autor

Se agrego un formulario para agregar un autor.

![img1](/imagenes/i1.png)

Para la conexion con la base de datos se hizo lo siguiente.

![img2](/imagenes/i2.png)

Visualmente se ve de la siguiente manera

![img3](/imagenes/i3.png)

# Agregar libro

Para agregar un libro a la base, se genero un archivo llamado agregarlibro.php donde hay campos para ingresar datos propios de un libro.

![img4](/imagenes/i4.png)

Luego, se genera un archivo javascript para usar AJAX para desplegar datos de los capitulos que se quieren ingresar.

![img5](/imagenes/i5.png)

Y luego, se genera un agregarcap.php para mostrar un formulario para los capitulos.

![img6](/imagenes/i6.png)

Cuando se termina este formulario, se validan los campos y se agregan los datos.

![img7](/imagenes/i7.png)

# Listar

Para listar todos los libros, se uso un archivo php y se implemento AJAX para buscar un libro en especifico.

Primero se creo listar.php para listara todos los libros en la base de datos, donde se busca el libro, con su id se buscan capitulos relacionados y por ultimo, se buscan los autores relacionados a lso capitulos.

![img8](/imagenes/i8.png)

Para la implementacion de ajax, se uso un codigo parecido, pero con un parametro para filtrar, en este caso, solo se aplica para buscar por un autor.

![img9](/imagenes/i9.png)



