<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


<!-- Actividad 02 -->

# Actividad: Creando mi primer sitio web
Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

+ Index o página de inicio
+ Acerca
+ Contacto

## Solución
## About.html
```java

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre nosotros</title>
</head> 

<body>
<header>
    <h1>sobre nosotros</h1>
</header>

<nav>
    <a href="index.html">inicio</a>
    <a href="contac.html">contacto</a>
</nav>

<section>
    <h2>Historia</h2>
    <p>Fundada en 2023</p>

    <article>
        <h3>Misión y visión</h3>
        <p>Nuestra misión es...</p>
    </article>

</section>

<footer>
    <p>Copyright 2023 - Dayana Castro</p>
</footer>
    
</body>
</html>
```

## Contact.html
``` java

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mis Contactos</title>
</head>

<body>
    <header>
        <h1>Contacto</h1>
    </header>

    <nav>
        <a href="index.html">Inicio</a>
        <a href="about.html">Acerca</a>
    </nav>

    <main>
        <form>
            <label for="nombre">Nombre</label>
            <input type="text" id="email"><br>

            <label for="email">Email</label>
            <input type="email">id="email"<br>

            <label for="mensaje">Mensaje</label><br>
            <textarea id="mensaje"></textarea><br>

            <input type="submit" value="Enviar">
        </form>

        <aside>
            <h3>Ubicacion</h3>
            <p>Calle Falsa 123</p>
        </aside>

    </main>

    <footer>
        <p>Copyright 2023 - Dayana Castro</p>
    </footer>

  
</body>
  
</html>
```

## Index.html
``` java

<!DOCTYPE html>
<html>

<head>
    <title>El Cielo Restaurant</title>
</head>

<body>

    <header>
        <h1>El Cielo Restaurant</h1>
    </header>

    <nav>
        <a href="about.html">Acerca</a>
        <a href="contac.html">Contacto</a>
    </nav>

    <main>
        <p>Bienvenidos al Cielo Restaurant</p>
        <p>Aqui encontraran la carta y Ubicacion de nuestro restaurant</p>
    </main>

    <footer>
        <p>Copyright 2023 - El Cielo Restaurant</p>
        <p>Elcielorestaurant@gmail.com</p>
    </footer>

</footer>

</html>
```




