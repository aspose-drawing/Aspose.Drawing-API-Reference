---
title: Rectangle
second_title: Referencia de la API de Aspose.Drawing para Java
description: Almacena un conjunto de cuatro enteros que representan la ubicación y el tamaño de un rectángulo.
type: docs
weight: 38
url: /es/java/com.aspose.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Rectangle extends Struct<Rectangle> implements System.IEquatable<Rectangle>, Cloneable
```

Almacena un conjunto de cuatro enteros que representan la ubicación y el tamaño de un rectángulo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Inicializa una nueva instancia de la estructura Rectangle con la ubicación y el tamaño especificados. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Inicializa una nueva instancia de la estructura [Rectangle](../../com.aspose.drawing/rectangle) con la ubicación y el tamaño especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [fromLTRB(int left, int top, int right, int bottom)](#fromLTRB-int-int-int-int-) | Crea una estructura [Rectangle](../../com.aspose.drawing/rectangle) con las ubicaciones de borde especificadas. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Devuelve una tercera estructura [Rectangle](../../com.aspose.drawing/rectangle) que representa la intersección de dos estructuras [Rectangle](../../com.aspose.drawing/rectangle) diferentes. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Comprueba si dos estructuras [Rectangle](../../com.aspose.drawing/rectangle) tienen la misma ubicación y tamaño. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Comprueba si dos estructuras [Rectangle](../../com.aspose.drawing/rectangle) difieren en ubicación o tamaño. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.drawing.RectangleF-) | Convierte la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada a una estructura [Rectangle](../../com.aspose.drawing/rectangle) redondeando los valores de [RectangleF](../../com.aspose.drawing/rectanglef) al siguiente entero superior. |
| [truncate(RectangleF value)](#truncate-com.aspose.drawing.RectangleF-) | Convierte el [RectangleF](../../com.aspose.drawing/rectanglef) especificado a un [Rectangle](../../com.aspose.drawing/rectangle) truncando los valores de [RectangleF](../../com.aspose.drawing/rectanglef). |
| [round(RectangleF value)](#round-com.aspose.drawing.RectangleF-) | Convierte el [RectangleF](../../com.aspose.drawing/rectanglef) especificado a un [Rectangle](../../com.aspose.drawing/rectangle) redondeando los valores de [RectangleF](../../com.aspose.drawing/rectanglef) al entero más cercano. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Obtiene una estructura [Rectangle](../../com.aspose.drawing/rectangle) que contiene la unión de dos estructuras [Rectangle](../../com.aspose.drawing/rectangle). |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.drawing.Rectangle-int-int-) |  |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) |  |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Crea un nuevo rectángulo a partir de dos puntos. |
| [getEmpty()](#getEmpty--) | Obtiene una nueva instancia de la estructura `Rectangle` que tiene los valores `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` y `Rectangle.Height` establecidos en cero. |
| [getX()](#getX--) | Obtiene la coordenada x de la esquina superior izquierda de esta estructura Rectangle. |
| [setX(int value)](#setX-int-) | Establece la coordenada x de la esquina superior izquierda de esta estructura Rectangle. |
| [getY()](#getY--) | Obtiene la coordenada y de la esquina superior izquierda de esta estructura Rectangle. |
| [setY(int value)](#setY-int-) | Establece la coordenada y de la esquina superior izquierda de esta estructura Rectangle. |
| [getLocation()](#getLocation--) | Obtiene las coordenadas de la esquina superior izquierda de esta estructura [Rectangle](../../com.aspose.drawing/rectangle). |
| [setLocation(Point value)](#setLocation-com.aspose.drawing.Point-) | Establece las coordenadas de la esquina superior izquierda de esta estructura [Rectangle](../../com.aspose.drawing/rectangle). |
| [getWidth()](#getWidth--) | Obtiene el ancho de esta estructura Rectangle. |
| [setWidth(int value)](#setWidth-int-) | Establece el ancho de esta estructura Rectangle. |
| [getHeight()](#getHeight--) | Obtiene la altura de esta estructura Rectangle. |
| [setHeight(int value)](#setHeight-int-) | Establece la altura de esta estructura Rectangle. |
| [getSize()](#getSize--) | Obtiene el tamaño de este [Rectangle](../../com.aspose.drawing/rectangle). |
| [setSize(Size value)](#setSize-com.aspose.drawing.Size-) | Establece el tamaño de este [Rectangle](../../com.aspose.drawing/rectangle). |
| [getLeft()](#getLeft--) | Obtiene la coordenada x del borde izquierdo de esta estructura Rectangle. |
| [getTop()](#getTop--) | Obtiene la coordenada y del borde superior de esta estructura Rectangle. |
| [getRight()](#getRight--) | Obtiene la coordenada x que es la suma de los valores de las propiedades X y Width de esta estructura Rectangle. |
| [getBottom()](#getBottom--) | Obtiene la coordenada y que es la suma de los valores de las propiedades Y y Height de esta estructura Rectangle. |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si todas las propiedades numéricas de este [Rectangle](../../com.aspose.drawing/rectangle) tienen valores cero. |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si obj es una estructura [Rectangle](../../com.aspose.drawing/rectangle) con la misma ubicación y tamaño que esta estructura [Rectangle](../../com.aspose.drawing/rectangle). |
| [hashCode()](#hashCode--) | Devuelve el código hash de esta estructura [Rectangle](../../com.aspose.drawing/rectangle). |
| [toString()](#toString--) |  |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Reemplaza este [Rectangle](../../com.aspose.drawing/rectangle) con la intersección de sí mismo y el [Rectangle](../../com.aspose.drawing/rectangle) especificado. |
| [inflate(int width, int height)](#inflate-int-int-) | Amplía este [Rectangle](../../com.aspose.drawing/rectangle) en la cantidad especificada. |
| [inflate(Size size)](#inflate-com.aspose.drawing.Size-) | Amplía este [Rectangle](../../com.aspose.drawing/rectangle) en la cantidad especificada. |
| [contains(int x, int y)](#contains-int-int-) | Determina si el punto especificado está contenido dentro de esta estructura [Rectangle](../../com.aspose.drawing/rectangle). |
| [contains(Point pt)](#contains-com.aspose.drawing.Point-) | Determina si el punto especificado está contenido dentro de esta estructura [Rectangle](../../com.aspose.drawing/rectangle). |
| [contains(Rectangle rect)](#contains-com.aspose.drawing.Rectangle-) |  |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.drawing.Rectangle-) | Determina si este rectángulo intersecta con `rect`. |
| [offset(int x, int y)](#offset-int-int-) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [offset(Point pos)](#offset-com.aspose.drawing.Point-) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [equals(Rectangle other)](#equals-com.aspose.drawing.Rectangle-) | Comprueba si otra estructura [Rectangle](../../com.aspose.drawing/rectangle) tiene la misma ubicación y tamaño que esta estructura [Rectangle](../../com.aspose.drawing/rectangle). |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.drawing.Rectangle-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [normalize()](#normalize--) | Normaliza el rectángulo haciendo que su ancho y altura sean positivos, que la izquierda sea menor que la derecha y que la parte superior sea menor que la inferior. |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Inicializa una nueva instancia de la estructura Rectangle con la ubicación y el tamaño especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo. |
| ancho | int | El ancho del rectángulo. |
| alto | int | La altura del rectángulo. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public Rectangle(Point location, Size size)
```


Inicializa una nueva instancia de la estructura [Rectangle](../../com.aspose.drawing/rectangle) con la ubicación y el tamaño especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location | [Point](../../com.aspose.drawing/point) | Un [Point](../../com.aspose.drawing/point) que representa la esquina superior izquierda de la región rectangular. |
| size | [Size](../../com.aspose.drawing/size) | Un `Size`([.getSize](../../null/\#getSize)/[.setSize(Size)](../../null/\#setSize-Size-)) que representa el ancho y la altura de la región rectangular. |

### fromLTRB(int left, int top, int right, int bottom) {#fromLTRB-int-int-int-int-}
```
public static Rectangle fromLTRB(int left, int top, int right, int bottom)
```


Crea una estructura [Rectangle](../../com.aspose.drawing/rectangle) con las ubicaciones de borde especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | int | La coordenada x de la esquina superior izquierda de esta estructura [Rectangle](../../com.aspose.drawing/rectangle). |
| top | int | La coordenada y de la esquina superior izquierda de esta estructura [Rectangle](../../com.aspose.drawing/rectangle). |
| right | int | La coordenada x de la esquina inferior derecha de esta estructura [Rectangle](../../com.aspose.drawing/rectangle). |
| bottom | int | La coordenada y de la esquina inferior derecha de esta estructura [Rectangle](../../com.aspose.drawing/rectangle). |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The new [Rectangle](../../com.aspose.drawing/rectangle) that this method creates.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Devuelve una tercera estructura [Rectangle](../../com.aspose.drawing/rectangle) que representa la intersección de dos estructuras [Rectangle](../../com.aspose.drawing/rectangle) adicionales. Si no hay intersección, se devuelve una [Rectangle](../../com.aspose.drawing/rectangle) vacía.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | Primer rectángulo a intersectar. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | Segundo rectángulo a intersectar. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the intersection of `a` and `b`.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Comprueba si dos estructuras [Rectangle](../../com.aspose.drawing/rectangle) tienen la misma ubicación y tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | La estructura [Rectangle](../../com.aspose.drawing/rectangle) que está a la izquierda del operador de igualdad. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | La estructura [Rectangle](../../com.aspose.drawing/rectangle) que está a la derecha del operador de igualdad. |

**Returns:**
boolean - Este operador devuelve `true` si las dos estructuras [Rectangle](../../com.aspose.drawing/rectangle) tienen propiedades X, Y, Width y Height iguales.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Comprueba si dos estructuras [Rectangle](../../com.aspose.drawing/rectangle) difieren en ubicación o tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | La estructura [Rectangle](../../com.aspose.drawing/rectangle) que está a la izquierda del operador de desigualdad. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | La estructura [Rectangle](../../com.aspose.drawing/rectangle) que está a la derecha del operador de desigualdad. |

**Returns:**
boolean - Este operador devuelve `true` si alguna de las propiedades X, Y, Width o Height de las dos estructuras [Rectangle](../../com.aspose.drawing/rectangle) no son iguales; de lo contrario, `false`.
### ceiling(RectangleF value) {#ceiling-com.aspose.drawing.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Convierte la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada a una estructura [Rectangle](../../com.aspose.drawing/rectangle) redondeando los valores de [RectangleF](../../com.aspose.drawing/rectanglef) al siguiente entero superior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | La estructura [RectangleF](../../com.aspose.drawing/rectanglef) que se convertirá. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - Returns a [Rectangle](../../com.aspose.drawing/rectangle).
### truncate(RectangleF value) {#truncate-com.aspose.drawing.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Convierte el [RectangleF](../../com.aspose.drawing/rectanglef) especificado a un [Rectangle](../../com.aspose.drawing/rectangle) truncando los valores de [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | El [RectangleF](../../com.aspose.drawing/rectanglef) que se convertirá. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The truncated value of the [Rectangle](../../com.aspose.drawing/rectangle).
### round(RectangleF value) {#round-com.aspose.drawing.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Convierte el [RectangleF](../../com.aspose.drawing/rectanglef) especificado a un [Rectangle](../../com.aspose.drawing/rectangle) redondeando los valores de [RectangleF](../../com.aspose.drawing/rectanglef) al entero más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | El [RectangleF](../../com.aspose.drawing/rectanglef) que se convertirá. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle).
### union(Rectangle a, Rectangle b) {#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Obtiene una estructura [Rectangle](../../com.aspose.drawing/rectangle) que contiene la unión de dos estructuras [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | Un primer rectángulo para unir. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | Un segundo rectángulo para unir. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) structure that bounds the union of the two [Rectangle](../../com.aspose.drawing/rectangle) structures.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.drawing.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| x | int |  |
| y | int |  |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Crea un nuevo rectángulo a partir de dos puntos. El rectángulo creado se normalizará con (left,top) menor que (right,bottom).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | El primer punto. |
| point2 | [Point](../../com.aspose.drawing/point) | El segundo punto. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A newly created rectangle.
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Obtiene una nueva instancia de la estructura `Rectangle` que tiene los valores `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` y `Rectangle.Height` establecidos en cero.

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### getX() {#getX--}
```
public final int getX()
```


Obtiene la coordenada x de la esquina superior izquierda de esta estructura Rectangle.

**Returns:**
int - la coordenada x de la esquina superior izquierda de esta estructura Rectangle.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Establece la coordenada x de la esquina superior izquierda de esta estructura Rectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | la coordenada x de la esquina superior izquierda de esta estructura Rectangle. |

### getY() {#getY--}
```
public final int getY()
```


Obtiene la coordenada y de la esquina superior izquierda de esta estructura Rectangle.

**Returns:**
int - la coordenada y de la esquina superior izquierda de esta estructura Rectangle.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Establece la coordenada y de la esquina superior izquierda de esta estructura Rectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | la coordenada y de la esquina superior izquierda de esta estructura Rectangle. |

### getLocation() {#getLocation--}
```
public final Point getLocation()
```


Obtiene las coordenadas de la esquina superior izquierda de esta estructura [Rectangle](../../com.aspose.drawing/rectangle).

**Returns:**
[Point](../../com.aspose.drawing/point) - the coordinates of the upper-left corner of this [Rectangle](../../com.aspose.drawing/rectangle) structure.
### setLocation(Point value) {#setLocation-com.aspose.drawing.Point-}
```
public final void setLocation(Point value)
```


Establece las coordenadas de la esquina superior izquierda de esta estructura [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.drawing/point) | las coordenadas de la esquina superior izquierda de esta estructura [Rectangle](../../com.aspose.drawing/rectangle). |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene el ancho de esta estructura Rectangle.

**Returns:**
int - el ancho de esta estructura Rectangle.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Establece el ancho de esta estructura Rectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | el ancho de esta estructura Rectangle. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene la altura de esta estructura Rectangle.

**Returns:**
int - la altura de esta estructura Rectangle.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Establece la altura de esta estructura Rectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | la altura de esta estructura Rectangle. |

### getSize() {#getSize--}
```
public final Size getSize()
```


Obtiene el tamaño de este [Rectangle](../../com.aspose.drawing/rectangle).

**Returns:**
[Size](../../com.aspose.drawing/size) - the size of this [Rectangle](../../com.aspose.drawing/rectangle).
### setSize(Size value) {#setSize-com.aspose.drawing.Size-}
```
public final void setSize(Size value)
```


Establece el tamaño de este [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Size](../../com.aspose.drawing/size) | el tamaño de este [Rectangle](../../com.aspose.drawing/rectangle). |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Obtiene la coordenada x del borde izquierdo de esta estructura Rectangle.

**Returns:**
int - la coordenada x del borde izquierdo de esta estructura Rectangle.
### getTop() {#getTop--}
```
public final int getTop()
```


Obtiene la coordenada y del borde superior de esta estructura Rectangle.

**Returns:**
int - la coordenada y del borde superior de esta estructura Rectangle.
### getRight() {#getRight--}
```
public final int getRight()
```


Obtiene la coordenada x que es la suma de los valores de las propiedades X y Width de esta estructura Rectangle.

**Returns:**
int - la coordenada x que es la suma de los valores de las propiedades X y Width de esta estructura Rectangle.
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Obtiene la coordenada y que es la suma de los valores de las propiedades Y y Height de esta estructura Rectangle.

**Returns:**
int - la coordenada y que es la suma de los valores de las propiedades Y y Height de esta estructura Rectangle.
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Obtiene un valor que indica si todas las propiedades numéricas de este [Rectangle](../../com.aspose.drawing/rectangle) tienen valores cero.

**Returns:**
boolean - Esta propiedad devuelve `true` si las propiedades `Rectangle.Width`, `Rectangle.Height`, `Rectangle.X` y `Rectangle.Y` de este [Rectangle](../../com.aspose.drawing/rectangle) tienen todos valores cero; de lo contrario, `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Comprueba si obj es una estructura [Rectangle](../../com.aspose.drawing/rectangle) con la misma ubicación y tamaño que esta estructura [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto a probar. |

**Returns:**
boolean - Este método devuelve `true` si obj es una estructura [Rectangle](../../com.aspose.drawing/rectangle) y sus propiedades X, Y, Width y Height son iguales a las propiedades correspondientes de esta estructura [Rectangle](../../com.aspose.drawing/rectangle); de lo contrario, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash para esta estructura [Rectangle](../../com.aspose.drawing/rectangle). Para obtener información sobre el uso de códigos hash, consulte GetHashCode.

**Returns:**
int - Un entero que representa el código hash para este rectángulo.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public final void intersect(Rectangle rect)
```


Reemplaza este [Rectangle](../../com.aspose.drawing/rectangle) con la intersección de sí mismo y el [Rectangle](../../com.aspose.drawing/rectangle) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | El [Rectangle](../../com.aspose.drawing/rectangle) con el que intersectar. |

### inflate(int width, int height) {#inflate-int-int-}
```
public final void inflate(int width, int height)
```


Amplía este [Rectangle](../../com.aspose.drawing/rectangle) en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | La cantidad para inflar este [Rectangle](../../com.aspose.drawing/rectangle) horizontalmente. |
| height | int | La cantidad para inflar este [Rectangle](../../com.aspose.drawing/rectangle) verticalmente. |

### inflate(Size size) {#inflate-com.aspose.drawing.Size-}
```
public final void inflate(Size size)
```


Amplía este [Rectangle](../../com.aspose.drawing/rectangle) en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | El tamaño para inflar este [Rectangle](../../com.aspose.drawing/rectangle). |

### contains(int x, int y) {#contains-int-int-}
```
public final boolean contains(int x, int y)
```


Determina si el punto especificado está contenido dentro de esta estructura [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |

**Returns:**
boolean - Este método devuelve `true` si el punto definido por `x` y `y` está contenido dentro de esta estructura [Rectangle](../../com.aspose.drawing/rectangle); de lo contrario `false`.
### contains(Point pt) {#contains-com.aspose.drawing.Point-}
```
public final boolean contains(Point pt)
```


Determina si el punto especificado está contenido dentro de esta estructura [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | El [Point](../../com.aspose.drawing/point) a probar. |

**Returns:**
boolean - Este método devuelve `true` si el punto representado por `pt` está contenido dentro de esta estructura [Rectangle](../../com.aspose.drawing/rectangle); de lo contrario `false`.
### contains(Rectangle rect) {#contains-com.aspose.drawing.Rectangle-}
```
public final boolean contains(Rectangle rect)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.drawing.Rectangle-}
```
public final boolean intersectsWith(Rectangle rect)
```


Determina si este rectángulo intersecta con `rect`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | El rectángulo a probar. |

**Returns:**
boolean - Este método devuelve true si hay alguna intersección, de lo contrario false.
### offset(int x, int y) {#offset-int-int-}
```
public final void offset(int x, int y)
```


Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | El desplazamiento horizontal. |
| y | int | El desplazamiento vertical. |

### offset(Point pos) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point pos)
```


Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pos | [Point](../../com.aspose.drawing/point) | El desplazamiento. |

### equals(Rectangle other) {#equals-com.aspose.drawing.Rectangle-}
```
public final boolean equals(Rectangle other)
```


Comprueba si otra estructura [Rectangle](../../com.aspose.drawing/rectangle) tiene la misma ubicación y tamaño que esta estructura [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.drawing/rectangle) | Otro rectángulo para probar |

**Returns:**
boolean - Este método devuelve `true` si la otra estructura [Rectangle](../../com.aspose.drawing/rectangle) y sus propiedades X, Y, Width y Height son iguales a las propiedades correspondientes de esta estructura [Rectangle](../../com.aspose.drawing/rectangle); de lo contrario, `false`.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.drawing.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.drawing/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### normalize() {#normalize--}
```
public void normalize()
```


Normaliza el rectángulo haciendo que su ancho y altura sean positivos, que la izquierda sea menor que la derecha y que la parte superior sea menor que la inferior.

