<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Actividad 03 -->

# Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5
Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

* 4 Imagenes
* 2 Videos
* 4 Audios
* 2 Inline Frame

Utiliza encabezados para títulos en cada elemento (< h1 >...< h6 >).

Crea una descripción para cada elemento utilizando párrafos (< p >).

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

+ Usa < strong > para resaltar texto importante.
+ Utiliza < br > para insertar saltos de línea si es necesario.
+ Agrega < span > para aplicar estilos específicos a porciones de texto.
+ Emplea < i > para enfatizar o dar énfasis a palabras o frases.
+ Utiliza < u > para subrayar texto cuando sea necesario.
+ Considera el uso de < div > para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

## Plantilla inicial 
```html

<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>Imágenes</h2>
        <p>Contenido sobre imágenes...</p>
    </section>

    <section>
        <h2>Videos</h2>
        <p>Contenido sobre videos...</p>
    </section>

    <section>
        <h2>Audios</h2>
        <p>Contenido sobre audios...</p>

    </section>

    <section>
        <h2>iFrames</h2>
        <p>Contenido sobre iframes...</p>
    </section>

    <footer>
        Nombre Completo
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```

# Semántica y Estructura de la Plantilla
El código HTML y CSS proporcionado describe un sitio web que trata sobre etiquetas multimedia en HTML5. A continuación, se desglosa la semántica y estructura del sitio:

<! DOCTYPE html>: Esto define el tipo de documento como HTML5.

< html >: La etiqueta raíz que envuelve todo el contenido HTML del sitio.

< head >: Aquí se encuentran las metainformaciones y enlaces a recursos externos. En este caso, se define el título de la página y se incluye un bloque < style > para agregar reglas de estilo CSS.

< title >: Establece el título de la página en la pestaña del navegador.

< style >: Contiene reglas de estilo CSS que afectan al diseño y la apariencia del sitio.

< body >: Aquí se coloca el contenido principal visible de la página.

< header>: Sección de encabezado que contiene el título principal y un subtítulo.

< h1> y < h3>: Encabezados de nivel 1 y 3, respectivamente, que proporcionan títulos jerárquicos y estructuran la información del encabezado.

< section>: Define una sección de contenido temático. Se utilizan para agrupar información relacionada.

< h2>: Encabezado de nivel 2 que se utiliza para los títulos de las secciones de contenido.

< p>: Párrafo de texto que contiene contenido informativo sobre las imágenes, videos, audios y iframes.

< footer>: Pie de página que contiene información de autoría y derechos de autor. Incluye saltos de línea < br> para separar las líneas de texto.

En cuanto al estilo, el CSS define reglas para la apariencia visual del sitio:

* La fuente del cuerpo del sitio es Arial o una fuente sans-serif en caso de que Arial no esté disponible.
* El encabezado (< header>) tiene un fondo oscuro, texto blanco y un espacio de relleno.
* Cada sección (< section>) tiene un borde, un espacio de relleno y un margen inferior.
* Los encabezados de nivel 1 y 3 están centrados.
* Los encabezados de nivel 2 (< h2>) tienen color azul.
* El pie de página (< footer>) tiene un fondo oscuro, texto blanco, espacio de relleno y está centrado.

Este sitio utiliza HTML5 y CSS para presentar información sobre etiquetas multimedia en HTML5, con una estructura semántica que utiliza encabezados, párrafos y secciones para organizar y presentar el contenido. El estilo CSS proporciona una apariencia visual coherente y agradable.

# Solución
```html

<!DOCTYPE html>
<html>

<head>
    <title>Turisticos de chile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: red;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>
<!--En esta pagina queria mostrar algunos de los lugares mas bonitos que visite en chile-->
    <header>
        <h1>TURISTICOS DE CHILE</h1>
        <h3>Los lugares mas hermosos del pais</h3>
        <h6>Cultura Chilena</h6>
    </header>

    <div>
        <section>
            <h2>Santiago</h2>
            <p>Santiago, también conocida como Santiago de Chile,<strong> es la capital y ciudad principal de Chile y de
                    la
                    Región Metropolitana de Santiago,</strong><br> la que además es el centro geográfico y cuya población
                se concentra en su gran mayoría en la ciudad.
                Situada a orillas del río Mapocho,<br> Santiago fue fundada por el español Pedro de Valdivia, bajo el nombre
                de
                Santiago de Nueva Extremadura en honor al Apóstol Santiago,<br>convirtiéndose así en la capital de la
                Gobernación de Nueva Extremadura,7​ en el siglo xvi. Actualmente es el centro económico y<br> administrativo
                del
                país, además de ser la aglomeración urbana más grande del país.</p>
            <img src="imagenes/santiago de chile.jpg" width="450">

            <h2>Video</h2>
            <video src="videos/santiago.mp4" width="450" controls></video>
            <p>Este video nos enseña la<i> capital de chile</i></p>

            <h2>Dale play</h2>
            <audio src="audios/santiago.mp3" controls></audio>
            <p><span style="color: red;">Escucha este audio para apreciar la ciudad</span></p>

        </section>

        <section>
            <h2>Viña del Mar</h2>
            <p>Viña del Mar es una ciudad y comuna chilena perteneciente a la provincia y <strong>Región de
                    Valparaíso,</strong> ubicada en
                el litoral central,<br> sobre las cuencas de los esteros Reñaca y Marga Marga y a orillas de la bahía de
                Valparaíso.</p>
            <img src="imagenes/viña del mar.jpg" width="450">

            <h2>Video</h2>
            <video src="videos/viña del mar.mp4" width="450" controls></video>
            <p>Este video nos enseña la hermosa <i>playa de viña del mar</i></p>

            <h2>Dale play</h2>
            <audio src="audios/viña del mar.mp3" controls></audio>
            <p><span style="color: red;">Apreciá la playa con este sonido</span></p>
            <iframe src="https://es.wikipedia.org/wiki/Vi%C3%B1a_del_Mar" width="300" height="100"></iframe>
            <p><u>Contenido detallado sobre Viña del Mar</u></p>
        </section>

        <section>
            <h2>Embalse del Yeso</h2>
            <p>El embalse se encuentra en el lugar denominado Boca del Valle, situado a 23 km aguas arriba de la junta
                del
                río Yeso con el río Maipo,<br>1​ a una altitud de 3000 msnm, <strong>la comuna de San José de Maipo,
                    Provincia
                    de
                    Cordillera,</strong> Región Metropolitana de Santiago.<br> Fue construido para dar seguridad al
                abastecimiento de agua
                potable y riego de la zona.</p>
            <img src="imagenes/embalse del yeso.jpg" width="450">


            <h2>Video</h2>
            <video src="videos/embalse del yeso.mp4" width="450" controls></video>
            <p><span style="color:red;">Reproduce el video para ver este espectacular glacial</span></p>


            <audio src="audios/embalse.mp3" controls></audio>
            <p>Un poco más de este hermoso lugar por visitrar donde econtraremos mas <i>de sus paisajes, gastronomía,
                    etc.></i></p>
            <iframe src="https://www.cajondelmaipo.com/embalse-el-yeso/" width="300" height="100"></iframe>

        </section>


        <section>
            <h2>San Alfonso del Mar</h2>
            <p>San Alfonso del Mar es un complejo residencial o centro vacacional ubicado en Algarrobo, <strong> Región
                    de
                    Valparaíso, Chile, a orillas del Océano Pacífico.</strong><br> Destaca por tener la piscina más extensa
                del mundo.1​
                Fue
                inaugurado en el año 1993. Se encuentra a aproximadamente 90 kilómetros de Santiago.
                <br>potable y riego de la zona.</p>
            <img src="imagenes/San alfonso del mar.jpg" width="450">

            <h2>Dale play</h2>
            <audio src="audios/San alfonso.mp3" controls></audio>
            <p><u>Aquí podras reservar tus vacaciones soñadas</u></p>
            <iframe src="https://www.booking.com/hotel/cl/san-alfonso-del-mar-resort.es.html" width="400"
                height="100"></iframe>








            <footer>
                Dayana Castro Villa
                <br>
                <br>
                CESDE
                <br>
                <br>
                &copy;2023
            </footer>

</body>

</html>
```





