<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- actividad 08-->

# Actividad: Aplicando estilos con selectores CSS
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

* Encabezado < header>
* Tres párrafos < p>
* Una imagen < img>
* Un pie de página < footer>

Aplica los siguientes estilos usando selectores de etiqueta:

* Color rojo a los encabezados < h1>
* Color azul a los párrafos < p>
* Borde grueso negro a la imagen < img>

Aplica los siguientes estilos usando seleccionadores de clase:

* Color verde a los elementos con la clase ".destacado"
* Tamaño de fuente grande a los elementos con la clase ".grande"

Aplica los siguientes estilos usando seleccionadores de ID:

* Color amarillo al elemento con ID "#principal"
* Sombra al elemento con ID "#sombras"

Aplica los siguientes estilos usando seleccionadores descendientes:

* Color gris a los párrafos dentro de un < div>
* Centrar el contenido de la sección < section>

## Solución 
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cabinetry Installer</title>
    <link rel="stylesheet" href="estilos.css">
    <style>
        section {
            text-align: center;
        }
    </style>
</head>

<body background="color">
    <section>
        <header style="background-color: rgba(128, 128, 128, 0.726); top: 0%;left: 0%;">
            <h1 style="text-decoration: underline;">Instalación de gabinetes domésticos y de negocios</h1>
            <h2 id="principal">Muebles</h2>
        </header>
        <p class="grande"> Se realiza trabajos que se utilizarán como elementos decorativos y funcionales en
            determinados espacios, como la construcción de accesorios y muebles de madera. Con este tipo de carpintería
            podrás dar un toque único a
            tus espacios.</p>
        <div style="background-color: rgb(163, 161, 161);">
            <p class="grande">Una gran importancia en nuestra sociedad, ya que la madera forma parte de nuestro día a
                día y muchos
                elementos están fabricados a partir de este material. La madera es posiblemente el material más antiguo
                para
                la construcción.</p>
        </div>

        <p class="grande">Consiste en cortar, moldear y fabricar piezas de madera para la construcción de viviendas.
            Existe
            una carpintería del armar, destinada a la construcción de armazones; de taller, dedicada a puertas, ventanas
            y similares; y de mobiliario, cuyo objeto es elaborar muebles de hogar con maderas comunes.</p>

        <img src="https://img.waimaoniu.net/2302/2302-202303041118233570.jpg">

        <footer class="destacado" style="background-color: black;">
            Dayana Castro Villa
            <br>
            Cesde
            <br>
            &copy;2023
        </footer>







    </section>

</body>

</html>
```






