# Registro temporal de datos de películas

Este es un pequeño proyecto creado en el lenguaje de programación c#, trata sobre el registro de películas almacenando temporalmente datos como nombre de la pelicula, genero, duracion en minutos, director, idioma y si esta se encuentra subtitulada. A la hora de almacenar estos datos se creara una tabla y una grafica, la tabla almacenara el nombre de la pelicula y si esta se encuentra activa, además de tener un botón, si lo accionamos nos desplegara todos los datos de la pelicula y así podremos editarlos, la grafica nos mostrara por medio grafico la relacion de la pelicula con respecto a la duración, todas las peliculas ingresadas se estaran comparando en una sola grafica.



## Tabla de Contenido.

<ul>
  <li><a href="#install">Como instalar el proyecto </a></li>
  <li><a href="#proyectofun">Funcionalidades del proyecto</a></li>
  <li><a href="#dlls">Sobre los dlls</a>
          <ul>
            <li><a href="dllraiz">Dll Raiz de un numero</a></li>
            <li><a href="dllgraficador">Dll Graficador</a></li>
          </ul>
  </li>
  <li><a href="#autores">Autores</a></li>
</ul>

<h2 id="install"> Como instalar el proyecto </h2>
<ul>
<li>Para instalar el proyecto primero tienes que ir al github en el que se encuentra este y descargarlo como zip, ver Recurso 1.</li>

<img src="http://g.recordit.co/x1h0WN73N0.gif" alt="Instalar Software" id="recurso1" width="550px"></img>

###### Recurso 1. Ejemplo de como descargar el proyecto.

<li>Después tienes que descomprimirlo en una carpeta y ya tendrias dentro de tu ordenador nuestro proyecto, ver Recurso 2.</li>

<img src="http://g.recordit.co/QzXpqnByV7.gif" alt="Descomprimir Software" id="recurso2" width="550px"></img>

###### Recurso 2. Ejemplo de como descomprimir el proyecto.

<li>Por ultimo tienes que ejecutar el programa para esto solo tienes que abrir al archivo llamado <b> "Trabajo1Corte" </b> que se encuentra en la carpeta que descomprimimos anteriormente, ver Recurso 3. </li>

<img src="http://g.recordit.co/9C1RQpxNeo.gif" alt="Abrir el Software" id="recurso2" width="450px"></img>

###### Recurso 3. Ejemplo de abrir el proyecto.

<h2 id="proyectofun"> Funcionalidades del proyecto </h2>
<ul>
  <li><a href="#aggpel"> Agregar y listar peliculas </a></li>
  <li><a href="#editpel"> Editar peliculas listadas </a></li>
  <li><a href="#graficapel"> Graficador con relacion pelicula - duracion </a></li>
  <li><a href="#idiomapel"> Cambiar idioma del Software </a></li>
  <li><a href="#configpel"> Cambiar configuracion del Software </a></li>
  <li><a href="#raiznum"> Calcular la raiz de un numero</a> </li>
</ul>

<h3 id="aggpel"> Agregar y listar peliculas </h3>

El usuario podra agregar tantas peliculas como quiera, para esto tendra que ingresar el nombre, el genero, la duración en minutos, el director, el idioma y si esta subtitulada o no.

Aquí un ejemplo de como se ingresaran los datos:

<img src="http://g.recordit.co/pzKkKEthDc.gif" alt="Agregar una pelicula"></img>
###### Recurso 4. Ejemplo de como se deben agregar las peliculas

<h3 id="editpel"> Editar peliculas listadas </h3>

Del mismo que el usuario puede agregar peliculas tambien las puede editar, para esto solo es necesario darle al botón mostrar, este pondra los datos que ingresamos para esa pelicula y también podemos editar estos, los cuales se guardaran temporalmente y editaran todo lo relacionado a ellos.

Aquí un ejemplo de como editar datos de una pelicula:

<img src="http://g.recordit.co/tz3Xi3Hq18.gif" alt="Editar datos de una pelicula"></img>
###### Recurso 4. Ejemplo de como se deben editar los datos de una pelicula

<h3 id="graficapel"> Graficador con relacion pelicula - duracion </h3>

A la hora de crear una pelicula también se creara una grafica, esta grafica nos mostrara dos datos, el nombre de la pelicula y su duracion, cada pelicula agregada se pondra en la grafica una junto a otra para así poder comparar los tiempos de duración de cada pelicula, en la grafica hay un boton llamado etiqueta, este sirve para esconder o mostrar la duración que aparece sobre la grafica.

Aquí un ejemplo de la grafica y el botón etiqueta:

<img src="http://g.recordit.co/KILIHK9SEo.gif" alt="Botón etiqueta de la grafica"></img>
###### Recurso 5. Ejemplo de la grafica y el botón etiqueta.

<h3 id="idiomapel"> Cambiar idioma del Software </h3>

Una de las funcionalidades de este software es que puedes alternar entre varios idiomas, para cambiar el idioma tan solo basta con ir a la derecha inferior a donde dice "idioma", en este se desplegara una lista que con tan solo poner el idioma que quieres ya se cambiara en todo el software.

Idiomas incluidos en el software:
<ul> <li>Español</li>
  <li> Ingles </li>
  <li> Ruso </li>
  <li> Chino Simplificado </li>
  <li> Frances </li>
  <li> Italiano </li> 
  <li> Aleman </li>
</ul>


Aquí un ejemplo de como cambiar el idioma:

<img src="http://g.recordit.co/x6rbG6I606.gif" alt="Cambiar idioma"></img>
###### Recurso 6. Ejemplo de como cambiar el idioma.


<h3 id="configpel"> Cambiar configuracion del Software </h3>

Una de las funcionalidades de este software es que puedes configurarlo a tu gusto, por el momento solo esta la opcion de cambiar el color, proximamente agregaremos otras funcionas.

Aquí un ejemplo de como cambiar la configuración del software:

<img src="http://g.recordit.co/jx7Qaa9DBA.gif" alt="Cambiar Color"></img>
###### Recurso 7. Ejemplo de como cambiar las configuraciones.

<h3 id="raiznum"> Calcular la raiz de un numero </h3>

Además de agregar peliculas este software también permite calcular la raíz de un numero, que es la raiz de un numero, esta es la suma de sus digitos hasta que el resultado solo sea 1 digito por ejemplo, supongamos que tenemos el numero 123, la raiz de este seria 6, esto es porque 1 + 2 + 3 = 6, otro ejemplo seria 999, el resultado de este es 9, esto es porque 9 + 9 + 9 = 27 y 2 + 7 = 9, osea que si el primer resultado da un numero que sea mayor o igual a dos digitos este tendra que volver a hacer la suma con el resultado obtenido hasta llegar a un numero de un solo digito.

Aquí un ejemplo de como sacar la raiz de un numero:

<img src="http://g.recordit.co/4aIqLrpj6P.gif" alt="Raiz de un numero"></img>
###### Recurso 8. Ejemplo de como sacar la raiz de un numero.

El software también cuenta con un apartado de créditos en los cuales se le hace alución a los creadores de este software, y también cuenta con un apartado de Ayuda, esto para que las personas que tengan algun problema o alguna duda sobre este, puedan enviar su petición de ayuda a los creados de este software.

<h2 id="dlls"> Sobre los Dlls</h2>

Nuestro software cuenta con dos Dlls, estos tienen diferentes funcionalidades por si solos, para nuestro proyecto solo implementamos algunas de estas funcionalidades, para así lograr una funcionalidad más optima dentro de nuestro software.

<h3 id="dllraiz"> Dll Raiz de un Numero </h3>

Anteriormente hablabamos de la raiz de un numero, ahora hablamos del proceso que conlleva hacer este, para sacar la raiz numero como deciamos anteriormente tenemos que sumar todos sus digitos para esto hay que hacer un proceso en el cual hay que verificar cuantos numeros hay en este para que así sume los digitos necesarios y si es el caso volver a sumarlo, cuando se produce esta otra suma, esta se origina cuando el resultado del primer numero sumado es mayor o igual a 2 digitos, si esto es así el programa sumara de nuevo el resultado hasta llegar a 1 solo digito.

Aquí un ejemplo de la logica que implementa este DLL:

<img src="http://g.recordit.co/aG7Y1AxqNw.gif" alt="Logica Raiz de un Numero"></img>
###### Recurso 8. Ejemplo de la logica que implementa el DLL.
