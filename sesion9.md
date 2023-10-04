<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Actividad 09 -->

# Actividad: Propiedades de espaciado y unidades de medida
Objetivo:

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

1. Crea un nuevo archivo HTML y CSS.
2. En el archivo HTML, agrega el siguiente código:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>
```
3. En el archivo CSS, agrega el siguiente código:
```css
.contenedor {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}
```
4. Abre el archivo HTML en tu navegador. Verás un cuadrado de 100x100 píxeles.

5. Practicar el uso de las propiedades de espaciado.

* Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.
```css
.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
* Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.
```css
.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
* Border: Agrega un borde de 5 píxeles de color rojo.
```css
.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
* Border-radius: Agrega un radio de esquina de 10 píxeles.
```css
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
* Unidades de medida: Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%.
```css
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}
```
# Preguntas:
1. ¿Qué es la propiedad margin?
2. ¿Qué es la propiedad padding?
3. ¿Qué es la propiedad border?
4. ¿Qué es la propiedad border-radius?
5. ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?

# Solución 

## 1. Margin
La propiedad margin establece los márgenes de un elemento especificando entre uno y cuatro valores, donde cada valor es una longitud, un porcentaje o auto. Los valores en porcentaje se refieren al ancho del elemento padre. Se permiten márgenes negativos.

Si se dan cuatro valores, se aplican a los márgenes superior, derecho, inferior e izquierdo, respectivamente. Si se da un valor, se aplica a todos los lados. Si se dan dos o tres valores, los valores faltantes se toman del lado opuesto.La propiedad margin establece los márgenes de un elemento especificando entre uno y cuatro valores, donde cada valor es una longitud, un porcentaje o auto. Los valores en porcentaje se refieren al ancho del elemento padre. Se permiten márgenes negativos.

Si se dan cuatro valores, se aplican a los márgenes superior, derecho, inferior e izquierdo, respectivamente. Si se da un valor, se aplica a todos los lados. Si se dan dos o tres valores, los valores faltantes se toman del lado opuesto.

Usando la propiedad margin se pueden establecer todos los márgenes; alternativamente, pueden usarse las propiedades margin-top, margin-bottom, margin-left y margin-right.

## 2. Padding
El padding de un elemento es la cantidad de espacio entre el borde y el contenido del elemento. Se dan entre uno y cuatro valores, donde cada valor puede ser una longitud o un porcentaje. Los valores en porcentaje se refieren al ancho del elemento padre. No se permiten los valores negativos.

Si se dan cuatro valores, se aplican a los rellenos superior, derecho, inferior e izquierdo, respectivamente. Si se da un valor, se aplica a todos los lados. Si se dan dos o tres valores, los valores faltantes se toman del lado opuesto.

La propiedad padding es una manera rápida de aplicar las propiedades padding-top, padding-right, padding-bottom y padding-left.

## 3. Border
La propiedad padding es una manera rápida de aplicar las propiedades padding-top, padding-right, padding-bottom y padding-left.

La propiedad border solo puede establecer todos los cuatro bordes; puede aplicar solo un ancho y estilo de borde. Para dar diferentes valores a los cuatro bordes de un elemento, se deben usar una o más de las propiedades border-top, border-right, border-bottom, border-left, border-color, border-width, border-style, border-top-width, border-right-width, border-bottom-width, o border-left-width.

## 4. Border Radius
La propiedad border-radius de CSS nos permite redondear los bordes de las cajas. Se usa principalmente en el diseño de las cajas que muestran el contenido de una web y para hacer algunas figuras sencilla, como los círculos. Sin embargo, con un poco de imaginación podemos aprovecharlo para crear formas más complejas.

La propiedad border-radius es en realidad un shorthand de varias propiedades. Estas propiedades son:

* border-top-left-radius: Esquina de arriba a la izquierda.
* border-top-right-radius: Esquina de arriba a la derecha.
* border-bottom-right-radius: Esquina de abajo a la derecha.
* border-bottom-left-radius: Esquina de abajo a la izquierda.

Su funcionamiento es similar al de otras propiedades (como margin, padding, etc.), solo que en lugar de aplicar el valor a un lado, se lo aplicamos a una esquina. La diferencia es que cada esquina puede tener dos valores distintos:

border-top-left-radius: 50px 100px;

border-bottom-right-radius: 50px 100px;

Esas dos medidas son la distancia (x,y) de la esquina al centro de la elipse que dibuja el borde redondeado. Las distancias se corresponden con la distancia al centro más pequeña y la más grande de la elipse.

En la forma acortada, border-radius, estos valores se indican separándolos mediante una barra /.

Cuando estos dos valores de la elipse son iguales, el resultado es un círculo. Cuando definimos solo uno de los valores CSS entiende que los dos son iguales, y genera un borde totalmente redondo.

Cabe destacar que no se puede redondear el borde si uno de los dos valores (x o y) es 0.

## 5. 
