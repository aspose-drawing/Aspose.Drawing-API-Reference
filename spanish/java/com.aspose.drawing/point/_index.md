---
title: Punto
second_title: Referencia de la API de Aspose.Drawing para Java
description: Representa un par ordenado de coordenadas x e y enteras que define un punto en un plano bidimensional.
type: docs
weight: 36
url: /es/java/com.aspose.drawing/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Point extends Struct<Point> implements System.IEquatable<Point>, Cloneable
```

Representa un par ordenado de coordenadas x e y enteras que define un punto en un plano bidimensional.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Inicializa una nueva instancia de la estructura [Point](../../com.aspose.drawing/point) con las coordenadas especificadas. |
| [Point(Size sz)](#Point-com.aspose.drawing.Size-) |  |
| [Point(int dw)](#Point-int-) | Inicializa una nueva instancia de la estructura [Point](../../com.aspose.drawing/point) usando coordenadas especificadas por un valor entero. |
## Campos

| Campo | Descripción |
| --- | --- |
| [EMPTY](#EMPTY) | Representa un [Point](../../com.aspose.drawing/point) que tiene los valores `Point.X` y `Point.Y` establecidos en cero. |
## Métodos

| Método | Descripción |
| --- | --- |
| [to_PointF(Point p)](#to-PointF-com.aspose.drawing.Point-) | Convierte la estructura [Point](../../com.aspose.drawing/point) especificada a una estructura [PointF](../../com.aspose.drawing/pointf). |
| [to_Size(Point p)](#to-Size-com.aspose.drawing.Point-) |  |
| [op_Addition(Point pt, Size sz)](#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Subtraction(Point pt, Size sz)](#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Equality(Point left, Point right)](#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Compara dos objetos [Point](../../com.aspose.drawing/point). |
| [op_Inequality(Point left, Point right)](#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Compara dos objetos [Point](../../com.aspose.drawing/point). |
| [add(Point pt, Size sz)](#add-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Agrega el [Size](../../com.aspose.drawing/size) especificado al [Point](../../com.aspose.drawing/point) especificado. |
| [subtract(Point pt, Size sz)](#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [ceiling(PointF value)](#ceiling-com.aspose.drawing.PointF-) |  |
| [truncate(PointF value)](#truncate-com.aspose.drawing.PointF-) | Convierte un PointF a un Point realizando una operación de truncamiento en todas las coordenadas. |
| [round(PointF value)](#round-com.aspose.drawing.PointF-) | Convierte la [PointF](../../com.aspose.drawing/pointf) especificada a un objeto Point redondeando los valores de [Point](../../com.aspose.drawing/point) al entero más cercano. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-) |  |
| [getEmpty()](#getEmpty--) |  |
| [getX()](#getX--) | Obtiene la coordenada x de este Point. |
| [setX(int value)](#setX-int-) | Establece la coordenada x de este Point. |
| [getY()](#getY--) | Obtiene la coordenada y de este Point. |
| [setY(int value)](#setY-int-) | Establece la coordenada y de este Point. |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si este [Point](../../com.aspose.drawing/point) está vacío. |
| [hashCode()](#hashCode--) | Devuelve un código hash para este [Point](../../com.aspose.drawing/point). |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Especifica si este [Point](../../com.aspose.drawing/point) contiene las mismas coordenadas que el Objeto especificado. |
| [offset(int dx, int dy)](#offset-int-int-) | Traslada este [Point](../../com.aspose.drawing/point) por la cantidad especificada. |
| [offset(Point p)](#offset-com.aspose.drawing.Point-) | Traslada este [Point](../../com.aspose.drawing/point) por el [Point](../../com.aspose.drawing/point) especificado. |
| [equals(Point other)](#equals-com.aspose.drawing.Point-) | Prueba si otra estructura [Point](../../com.aspose.drawing/point) tiene la misma ubicación que esta estructura [Point](../../com.aspose.drawing/point). |
| [CloneTo(Point that)](#CloneTo-com.aspose.drawing.Point-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Inicializa una nueva instancia de la estructura [Point](../../com.aspose.drawing/point) con las coordenadas especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La posición horizontal del punto. |
| y | int | La posición vertical del punto. |

### Point(Size sz) {#Point-com.aspose.drawing.Size-}
```
public Point(Size sz)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sz | [Size](../../com.aspose.drawing/size) |  |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Inicializa una nueva instancia de la estructura [Point](../../com.aspose.drawing/point) usando coordenadas especificadas por un valor entero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dw | int | El valor entero. |

### EMPTY {#EMPTY}
```
public static final Point EMPTY
```


Representa un [Point](../../com.aspose.drawing/point) que tiene los valores `Point.X` y `Point.Y` establecidos en cero.

### to_PointF(Point p) {#to-PointF-com.aspose.drawing.Point-}
```
public static PointF to_PointF(Point p)
```


Convierte la estructura [Point](../../com.aspose.drawing/point) especificada a una estructura [PointF](../../com.aspose.drawing/pointf).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | El [Point](../../com.aspose.drawing/point) a convertir. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The [PointF](../../com.aspose.drawing/pointf) that results from the conversion.
### to_Size(Point p) {#to-Size-com.aspose.drawing.Point-}
```
public static Size to_Size(Point p)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
[Size](../../com.aspose.drawing/size)
### op_Addition(Point pt, Size sz) {#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Addition(Point pt, Size sz)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Subtraction(Point pt, Size sz) {#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Subtraction(Point pt, Size sz)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Equality(Point left, Point right) {#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Equality(Point left, Point right)
```


Compara dos objetos [Point](../../com.aspose.drawing/point). El resultado indica si los valores de las propiedades `Point.X` y `Point.Y` de los dos objetos [Point](../../com.aspose.drawing/point) son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Primer [Point](../../com.aspose.drawing/point) a comparar. |
| right | [Point](../../com.aspose.drawing/point) | Segundo [Point](../../com.aspose.drawing/point) a comparar. |

**Returns:**
boolean - verdadero si los valores `Point.X` y `Point.Y` de `left` y `right` son iguales; de lo contrario, falso.
### op_Inequality(Point left, Point right) {#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Inequality(Point left, Point right)
```


Compara dos objetos [Point](../../com.aspose.drawing/point). El resultado indica si los valores de la propiedad `Point.X` o `Point.Y` de los dos objetos [Point](../../com.aspose.drawing/point) son diferentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Primer [Point](../../com.aspose.drawing/point) a comparar. |
| right | [Point](../../com.aspose.drawing/point) | Segundo [Point](../../com.aspose.drawing/point) a comparar. |

**Returns:**
boolean - verdadero si los valores de cualquiera de las propiedades `Point.X` o `Point.Y` de `left` y `right` difieren; de lo contrario, falso.
### add(Point pt, Size sz) {#add-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point add(Point pt, Size sz)
```


Agrega el [Size](../../com.aspose.drawing/size) especificado al [Point](../../com.aspose.drawing/point) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | El [Point](../../com.aspose.drawing/point) a añadir. |
| sz | [Size](../../com.aspose.drawing/size) | El [Size](../../com.aspose.drawing/size) a añadir |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the addition operation.
### subtract(Point pt, Size sz) {#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point subtract(Point pt, Size sz)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### ceiling(PointF value) {#ceiling-com.aspose.drawing.PointF-}
```
public static Point ceiling(PointF value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### truncate(PointF value) {#truncate-com.aspose.drawing.PointF-}
```
public static Point truncate(PointF value)
```


Convierte un PointF a un Point realizando una operación de truncamiento en todas las coordenadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | El [PointF](../../com.aspose.drawing/pointf) a truncar. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the truncate operation.
### round(PointF value) {#round-com.aspose.drawing.PointF-}
```
public static Point round(PointF value)
```


Convierte la [PointF](../../com.aspose.drawing/pointf) especificada a un objeto Point redondeando los valores de [Point](../../com.aspose.drawing/point) al entero más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | El [PointF](../../com.aspose.drawing/pointf) a convertir. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) this method converts to.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.drawing/point) |  |
| obj2 | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### getX() {#getX--}
```
public final int getX()
```


Obtiene la coordenada x de este Point.

**Returns:**
int - la coordenada x de este Point.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Establece la coordenada x de este Point.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | la coordenada x de este Point. |

### getY() {#getY--}
```
public final int getY()
```


Obtiene la coordenada y de este Point.

**Returns:**
int - la coordenada y de este Point.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Establece la coordenada y de este Point.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | la coordenada y de este Point. |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Obtiene un valor que indica si este [Point](../../com.aspose.drawing/point) está vacío.

Valor: `true` si tanto X como Y son 0; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si este este [Point](../../com.aspose.drawing/point) está vacío.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para este [Point](../../com.aspose.drawing/point).

**Returns:**
int - Un valor entero que especifica un valor hash para este [Point](../../com.aspose.drawing/point).
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Especifica si este [Point](../../com.aspose.drawing/point) contiene las mismas coordenadas que el Objeto especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto a probar. |

**Returns:**
boolean - `true` si obj es un Point y tiene las mismas coordenadas que este [Point](../../com.aspose.drawing/point).
### offset(int dx, int dy) {#offset-int-int-}
```
public final void offset(int dx, int dy)
```


Traslada este [Point](../../com.aspose.drawing/point) por la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | int | La cantidad para desplazar la coordenada x. |
| dy | int | La cantidad para desplazar la coordenada y. |

### offset(Point p) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point p)
```


Traslada este [Point](../../com.aspose.drawing/point) por el [Point](../../com.aspose.drawing/point) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | El [Point](../../com.aspose.drawing/point) usado para desplazar este [Point](../../com.aspose.drawing/point). |

### equals(Point other) {#equals-com.aspose.drawing.Point-}
```
public final boolean equals(Point other)
```


Prueba si otra estructura [Point](../../com.aspose.drawing/point) tiene la misma ubicación que esta estructura [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [Point](../../com.aspose.drawing/point) | Otro punto para probar |

**Returns:**
boolean - Este método devuelve `true` si la otra estructura [Point](../../com.aspose.drawing/point) y sus propiedades X y Y son iguales a las propiedades correspondientes de esta estructura [Point](../../com.aspose.drawing/point); de lo contrario, `false`.
### CloneTo(Point that) {#CloneTo-com.aspose.drawing.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [Point](../../com.aspose.drawing/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
