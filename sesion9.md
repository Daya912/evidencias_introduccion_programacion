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

## 5. Unidades de medida absolutas
Las unidades de medida en CSS de tipo absoluto hacen referencia a las unidades que no cambian, esas que en todos lo contextos son iguales. En CSS, existen siete unidades de medida absolutas, te las presentamos a continuación:

+ **in**: hace referencia a las pulgadas, que son iguales a 2.54cm.
+ **cm**: se refiere a los centímetros.
+ **mm**: hace referencia a los milímetros.
+ **q**: se refiere a un cuarto de la unidad mm. 1q=0.248mm.
+ **pt**: un punto es igual a 1/72 de una pulgada o 0.35mm.
+ **pc**: una pica es igual a 12 puntos, o sea 4.23mm.
+ **px**: esta etiqueta se refiere a los píxeles que, aunque son absolutos (0.26mm), también son relativos a la densidad de la pantalla.

## Unidades de medida relativas
Las unidades de medida en CSS de tipo relativo dependen del elemento o factor al que hagan referencia. Aunque pueden ser inicialmente más complejas, algunos prefieren las unidades de medidas de css relativas porque los tamaños de los elementos dependen el uno del otro. Esto hace que las proporciones entre los elementos se mantengan y todo encaje.

+ **em**: esta unidad es relativa al tamaño de letra o font size establecida en el navegador. Su nombre es em porque el tamaño de letra se basa en el tamaño de la letra eme. A menos que haya sido modificada por el usuario, normalmente este tamaño es de 16px.

+ **ex**: esta unidad es relativa a la altura de la «x» del elemento. También se conoce por ser más o menos la mitad del tamaño de la fuente del navegador o 0.5em.

+ **ch**: conocido en inglés como zero width, esta unidad de medida es relativa al tamaño del ancho del cero en la fuente del navegador.

+ **%**: Esta unidad es relativa al tamaño del elemento padre.

+ **rem**: la unidad rem o root em es similar a la unidad em, pero, en vez de tomar como base el tamaño de letra del navegador, la unidad em toma el tamaño base del documento HTML. Este tamaño se personaliza bajo la etiqueta :root {font-size}. De este modo, podemos usar rem para dimensionar nuestros elementos con un múltiplo del tamaño base.

Esta unidad puede ser muy útil a la hora de dimensionar una página cuando el usuario hace zoom, pues los elementos serán relativos unos a otros y mantendrán su proporción. Esta es una unidad de medida comúnmente utilizada para el tamaño de fuente en css

## Index.html
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
## Style.css
```css
.contenedor {
    width: 200px;
    height: 200px;
  }
  
  .elemento {
    width: 100px;
    height: 100px;
  }
  .elemento {
    margin: 10px;
    width: 100px;
    height: 100px;
  }
  .elemento {
    padding: 20px;
    margin: 10px;
    width: 100px;
    height: 100px;
  }
  .elemento {
    border: 5px solid red;
    padding: 20px;
    margin: 10px;
    width: 100px;
    height: 100px;
  }
  .elemento {
    border-radius: 10px;
    border: 5px solid red;
    padding: 20px;
    margin: 10px;
    width: 100px;
    height: 100px;
  }
  .elemento {
    border-radius: 10px;
    border: 5px solid red;
    margin: 50%;
    padding: 50%;
    width: 100px;
    height: 100px;
  }
  ```
