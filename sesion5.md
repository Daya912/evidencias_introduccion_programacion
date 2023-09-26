<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- actividad 05 -->

# Actividad: Diseñar un formulario de pedido de un producto
Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

Instrucciones:

1. Crear un nuevo documento HTML.
2. Crear un formulario con los siguientes campos:
+ Nombre del producto
+ Cantidad
+ Precio unitario
+ Precio total
+ Dirección de envío
+ Información de contacto (nombre, correo electrónico, número de teléfono)
3. Agregar los siguientes campos relacionados al formulario:
+ Método de pago
+ Fecha de entrega
+ Comentarios
4. Utilizar las etiquetas HTML apropiados para cada campo.

## Solución
```java

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <form action="">
        <h1>Formulario</h1>

        <div>
            <label for="idproducto">Nombre del producto</label>
            <input type="text" id="idproducto" name="Nprooducto" placeholder="Nombre del producto">
        </div>
        <br>
        <div>
            <label for="idcantidad">Cantidad</label>
            <input type="number" id="idcantidad" name="cantidad" placeholder="Cantidad" required>
        </div>
        <br>
        <div>
            <label for="idpreciounitario">Precio unitario</label>
            <input type="number" id="idpreciounitario" name="Precio_unitario" placeholder="Precio unitario">
        </div>
        <br>
        <div>
            <label for="idpreciototal">Precio total</label>
            <input type="number" id="idpreciototal" name="precioTotal" placeholder="Precio total">
        </div>
        <br>
        <div>
            <label for="iddireccion">Dirección de envío</label>
            <input type="text" id="iddireccion" name="DirecciónDeenvio" placeholder="Dirección">
        </div>
        <br>
        <h2>Información de contacto</h2>
        <div>
            <label for="idnombre">Nombre</label>
            <input type="text" id="idnombre" name="Nombre" required placeholder="Ingrese su nombre">
        </div>
        <br>
        <div>
            <label for="idcorreo">Correo electrónico</label>
            <input type="email" id="idcorreo" name="correo" required placeholder="Ingrese su correo electronico">
        </div>
        <br>
        <div>
            <label for="idnumero">Numero de teléfono</label>
            <input type="number" id="idnumero" name="Numero" placeholder="Numero de ceular">
        </div>
        <br>
        <div>
            <label for="idnumero">Método de pago</label>
            <select name="Forma_pago" id="idformadepago" required>
                <option value="debito">Tarjeta debito</option>
                <option value="credito" selected>Tarjeta credito</option>
                <option value="PSE">PSE</option>
            </select>
        </div>
        <br>
        <div>
            <label for="idfechaentrega">Fecha de entrega</label>
            <input type="datetime-local" id="idfechaentrega" name="fecha_entrega" required>
        </div>
        <br>
        <div>
            <label for="idcomentarios">Comentarios</label>
            <textarea name="idcomentarios" cols="30" rows="10"
                placeholder="sugerencias sobre nuestros productos"></textarea>
        </div>
        <br>
        <div>
            <button type="submit" id="idenviar" value="Enviar">Enviar</button>
        </div>

    </form>

    <footer>
        <br><br>
        Dayana Castro Villa
        <br><br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>











</form>
</body>

</html>
```





