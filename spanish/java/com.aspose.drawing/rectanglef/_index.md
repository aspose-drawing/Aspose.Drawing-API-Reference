---
title: RectangleF
second_title: Referencia de la API de Aspose.Drawing para Java
description: Almacena un conjunto de cuatro números de punto flotante que representan la ubicación y el tamaño de un rectángulo.
type: docs
weight: 39
url: /es/java/com.aspose.drawing/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class RectangleF extends Struct<RectangleF> implements System.IEquatable<RectangleF>, Cloneable
```

Almacena un conjunto de cuatro números de punto flotante que representan la ubicación y el tamaño de un rectángulo. Para funciones de región más avanzadas, use un objeto Region.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | Inicializa una nueva instancia de la estructura RectangleF con la ubicación y el tamaño especificados. |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Inicializa una nueva instancia de la estructura RectangleF con la ubicación y el tamaño especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | Crea un nuevo rectángulo a partir de dos puntos. |
| [to_RectangleF(Rectangle r)](#to-RectangleF-com.aspose.drawing.Rectangle-) | Convierte la estructura Rectangle especificada a una estructura RectangleF. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Prueba si dos estructuras [RectangleF](../../com.aspose.drawing/rectanglef) tienen la misma ubicación y tamaño. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Prueba si dos estructuras [RectangleF](../../com.aspose.drawing/rectanglef) difieren en ubicación o tamaño. |
| [fromLTRB(float left, float top, float right, float bottom)](#fromLTRB-float-float-float-float-) | Crea una estructura RectangleF con la esquina superior izquierda y la esquina inferior derecha en las ubicaciones especificadas. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.drawing.RectangleF-float-float-) | Crea y devuelve una copia inflada de la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Devuelve una estructura [RectangleF](../../com.aspose.drawing/rectanglef) que representa la intersección de dos rectángulos. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Crea el tercer rectángulo más pequeño posible que pueda contener ambos rectángulos que forman una unión. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si la propiedad `RectangleF.Width` o `RectangleF.Height` de este [RectangleF](../../com.aspose.drawing/rectanglef) tiene un valor de cero. |
| [getX()](#getX--) | Obtiene la coordenada x de la esquina superior izquierda de esta estructura RectangleF. |
| [setX(float value)](#setX-float-) | Establece la coordenada x de la esquina superior izquierda de esta estructura RectangleF. |
| [getY()](#getY--) | Obtiene la coordenada x de la esquina superior izquierda de esta estructura RectangleF. |
| [setY(float value)](#setY-float-) | Establece la coordenada x de la esquina superior izquierda de esta estructura RectangleF. |
| [getLocation()](#getLocation--) | Obtiene las coordenadas de la esquina superior izquierda de esta estructura [RectangleF](../../com.aspose.drawing/rectanglef). |
| [setLocation(PointF value)](#setLocation-com.aspose.drawing.PointF-) | Establece las coordenadas de la esquina superior izquierda de esta estructura [RectangleF](../../com.aspose.drawing/rectanglef). |
| [getWidth()](#getWidth--) | Obtiene el ancho de esta estructura RectangleF. |
| [setWidth(float value)](#setWidth-float-) | Establece el ancho de esta estructura RectangleF. |
| [getHeight()](#getHeight--) | Obtiene la altura de esta estructura RectangleF. |
| [setHeight(float value)](#setHeight-float-) | Establece la altura de esta estructura RectangleF. |
| [getSize()](#getSize--) | Obtiene el tamaño de esta [RectangleF](../../com.aspose.drawing/rectanglef). |
| [setSize(SizeF value)](#setSize-com.aspose.drawing.SizeF-) | Establece el tamaño de esta [RectangleF](../../com.aspose.drawing/rectanglef). |
| [getLeft()](#getLeft--) | Obtiene la coordenada x del borde izquierdo de esta estructura RectangleF. |
| [getTop()](#getTop--) | Obtiene la coordenada y del borde superior de esta estructura RectangleF. |
| [getRight()](#getRight--) | Obtiene la coordenada x que es la suma de X y Width de esta estructura RectangleF. |
| [getBottom()](#getBottom--) | Obtiene la coordenada y que es la suma de Y y Height de esta estructura RectangleF. |
| [toString()](#toString--) |  |
| [inflate(float x, float y)](#inflate-float-float-) | Infla esta estructura [RectangleF](../../com.aspose.drawing/rectanglef) en la cantidad especificada. |
| [inflate(SizeF size)](#inflate-com.aspose.drawing.SizeF-) | Infla este [RectangleF](../../com.aspose.drawing/rectanglef) en la cantidad especificada. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Reemplaza esta estructura [RectangleF](../../com.aspose.drawing/rectanglef) con la intersección de ella misma y la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.drawing.RectangleF-) | Determina si este rectángulo intersecta con `rect`. |
| [offset(PointF pos)](#offset-com.aspose.drawing.PointF-) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [offset(float x, float y)](#offset-float-float-) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [contains(float x, float y)](#contains-float-float-) | Determina si el punto especificado está contenido dentro de esta estructura [RectangleF](../../com.aspose.drawing/rectanglef). |
| [contains(PointF pt)](#contains-com.aspose.drawing.PointF-) | Determina si el punto especificado está contenido dentro de esta estructura [RectangleF](../../com.aspose.drawing/rectanglef). |
| [contains(RectangleF rect)](#contains-com.aspose.drawing.RectangleF-) | Determina si la región rectangular representada por `rect` está completamente contenida dentro de esta estructura [RectangleF](../../com.aspose.drawing/rectanglef). |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el Object especificado es igual a esta instancia. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
| [equals(RectangleF other)](#equals-com.aspose.drawing.RectangleF-) | Prueba si otra estructura [RectangleF](../../com.aspose.drawing/rectanglef) tiene la misma ubicación y tamaño que esta estructura [RectangleF](../../com.aspose.drawing/rectanglef). |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.drawing.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Inicializa una nueva instancia de la estructura RectangleF con la ubicación y el tamaño especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location | [PointF](../../com.aspose.drawing/pointf) | Un PointF que representa la esquina superior izquierda de la región rectangular. |
| size | [SizeF](../../com.aspose.drawing/sizef) | Un SizeF que representa el ancho y la altura de la región rectangular. |

### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Inicializa una nueva instancia de la estructura RectangleF con la ubicación y el tamaño especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo. |
| ancho | float | El ancho del rectángulo. |
| alto | float | La altura del rectángulo. |

### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Crea un nuevo rectángulo a partir de dos puntos. El rectángulo creado se normalizará con (left,top) menor que (right,bottom).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | El primer punto. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | El segundo punto. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A newly created rectangle.
### to_RectangleF(Rectangle r) {#to-RectangleF-com.aspose.drawing.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle r)
```


Convierte la estructura Rectangle especificada a una estructura RectangleF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| r | [Rectangle](../../com.aspose.drawing/rectangle) | La estructura Rectangle a convertir. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The RectangleF structure that is converted from the specified Rectangle structure.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Prueba si dos estructuras [RectangleF](../../com.aspose.drawing/rectanglef) tienen la misma ubicación y tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | La estructura [RectangleF](../../com.aspose.drawing/rectanglef) que está a la izquierda del operador de igualdad. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | La estructura [RectangleF](../../com.aspose.drawing/rectanglef) que está a la derecha del operador de igualdad. |

**Returns:**
boolean - Este operador devuelve true si las dos estructuras [RectangleF](../../com.aspose.drawing/rectanglef) especificadas tienen iguales las propiedades `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` y `RectangleF.Height`.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Prueba si dos estructuras [RectangleF](../../com.aspose.drawing/rectanglef) difieren en ubicación o tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | La estructura [RectangleF](../../com.aspose.drawing/rectanglef) que está a la izquierda del operador de desigualdad. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | La estructura [RectangleF](../../com.aspose.drawing/rectanglef) que está a la derecha del operador de desigualdad. |

**Returns:**
boolean - Este operador devuelve true si alguna de las propiedades `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` o `RectangleF.Height` de las dos estructuras [Rectangle](../../com.aspose.drawing/rectangle) es desigual; de lo contrario, false.
### fromLTRB(float left, float top, float right, float bottom) {#fromLTRB-float-float-float-float-}
```
public static RectangleF fromLTRB(float left, float top, float right, float bottom)
```


Crea una estructura RectangleF con la esquina superior izquierda y la esquina inferior derecha en las ubicaciones especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| izquierda | float | La coordenada x de la esquina superior izquierda de la región rectangular. |
| superior | float | La coordenada y de la esquina superior izquierda de la región rectangular. |
| derecha | float | La coordenada x de la esquina inferior derecha de la región rectangular. |
| inferior | float | La coordenada y de la esquina inferior derecha de la región rectangular. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The new RectangleF that this method creates.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.drawing.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Crea y devuelve una copia inflada de la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada. La copia se infla en la cantidad especificada. El rectángulo original permanece sin modificar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | El [RectangleF](../../com.aspose.drawing/rectanglef) que se copiará. Este rectángulo no se modifica. |
| x | float | La cantidad para inflar horizontalmente la copia del rectángulo. |
| y | float | La cantidad para inflar la copia del rectángulo verticalmente. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The inflated [RectangleF](../../com.aspose.drawing/rectanglef).
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Devuelve una estructura [RectangleF](../../com.aspose.drawing/rectanglef) que representa la intersección de dos rectángulos. Si no hay intersección, se devuelve un [RectangleF](../../com.aspose.drawing/rectanglef) vacío.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Primer rectángulo a intersectar. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Segundo rectángulo a intersectar. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Crea el tercer rectángulo más pequeño posible que pueda contener ambos rectángulos que forman una unión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Primer rectángulo para la unión. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Segundo rectángulo para la unión. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure that contains both of the two rectangles that form the union.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Obtiene un valor que indica si la propiedad `RectangleF.Width` o `RectangleF.Height` de este [RectangleF](../../com.aspose.drawing/rectanglef) tiene un valor de cero.

**Returns:**
boolean - Esta propiedad devuelve true si la propiedad `RectangleF.Width` o `P:RectangleF.Height` de este [RectangleF](../../com.aspose.drawing/rectanglef) tiene un valor de cero; de lo contrario, false.
### getX() {#getX--}
```
public final float getX()
```


Obtiene la coordenada x de la esquina superior izquierda de esta estructura RectangleF.

**Returns:**
float - la coordenada x de la esquina superior izquierda de esta estructura RectangleF.
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Establece la coordenada x de la esquina superior izquierda de esta estructura RectangleF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float | la coordenada x de la esquina superior izquierda de esta estructura RectangleF. |

### getY() {#getY--}
```
public final float getY()
```


Obtiene la coordenada x de la esquina superior izquierda de esta estructura RectangleF.

**Returns:**
float - la coordenada x de la esquina superior izquierda de esta estructura RectangleF.
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Establece la coordenada x de la esquina superior izquierda de esta estructura RectangleF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float | la coordenada x de la esquina superior izquierda de esta estructura RectangleF. |

### getLocation() {#getLocation--}
```
public final PointF getLocation()
```


Obtiene las coordenadas de la esquina superior izquierda de esta estructura [RectangleF](../../com.aspose.drawing/rectanglef).

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - A [PointF](../../com.aspose.drawing/pointf) that represents the upper-left corner of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setLocation(PointF value) {#setLocation-com.aspose.drawing.PointF-}
```
public final void setLocation(PointF value)
```


Establece las coordenadas de la esquina superior izquierda de esta estructura [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | las coordenadas de la esquina superior izquierda de esta estructura [RectangleF](../../com.aspose.drawing/rectanglef). |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Obtiene el ancho de esta estructura RectangleF.

**Returns:**
float - el ancho de esta estructura RectangleF.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Establece el ancho de esta estructura RectangleF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float | el ancho de esta estructura RectangleF. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Obtiene la altura de esta estructura RectangleF.

**Returns:**
float - la altura de esta estructura RectangleF.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Establece la altura de esta estructura RectangleF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float | la altura de esta estructura RectangleF. |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


Obtiene el tamaño de esta [RectangleF](../../com.aspose.drawing/rectanglef).

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that represents the width and height of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setSize(SizeF value) {#setSize-com.aspose.drawing.SizeF-}
```
public final void setSize(SizeF value)
```


Establece el tamaño de esta [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | el tamaño de este [RectangleF](../../com.aspose.drawing/rectanglef). |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


Obtiene la coordenada x del borde izquierdo de esta estructura RectangleF.

**Returns:**
float - la coordenada x del borde izquierdo de esta estructura RectangleF.
### getTop() {#getTop--}
```
public final float getTop()
```


Obtiene la coordenada y del borde superior de esta estructura RectangleF.

**Returns:**
float - la coordenada y del borde superior de esta estructura RectangleF.
### getRight() {#getRight--}
```
public final float getRight()
```


Obtiene la coordenada x que es la suma de X y Width de esta estructura RectangleF.

**Returns:**
float - la coordenada x que es la suma de X y Width de esta estructura RectangleF.
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Obtiene la coordenada y que es la suma de Y y Height de esta estructura RectangleF.

**Returns:**
float - la coordenada y que es la suma de Y y Height de esta estructura RectangleF.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### inflate(float x, float y) {#inflate-float-float-}
```
public final void inflate(float x, float y)
```


Infla esta estructura [RectangleF](../../com.aspose.drawing/rectanglef) en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La cantidad para inflar esta estructura [RectangleF](../../com.aspose.drawing/rectanglef) horizontalmente. |
| y | float | La cantidad para inflar esta estructura [RectangleF](../../com.aspose.drawing/rectanglef) verticalmente. |

### inflate(SizeF size) {#inflate-com.aspose.drawing.SizeF-}
```
public final void inflate(SizeF size)
```


Infla este [RectangleF](../../com.aspose.drawing/rectanglef) en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | La cantidad para inflar este rectángulo. |

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public final void intersect(RectangleF rect)
```


Reemplaza esta estructura [RectangleF](../../com.aspose.drawing/rectanglef) con la intersección de ella misma y la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | El rectángulo a intersectar. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.drawing.RectangleF-}
```
public final boolean intersectsWith(RectangleF rect)
```


Determina si este rectángulo intersecta con `rect`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | El rectángulo a probar. |

**Returns:**
boolean - Este método devuelve true si hay alguna intersección.
### offset(PointF pos) {#offset-com.aspose.drawing.PointF-}
```
public final void offset(PointF pos)
```


Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.drawing/pointf) | La cantidad para desplazar la ubicación. |

### offset(float x, float y) {#offset-float-float-}
```
public final void offset(float x, float y)
```


Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La cantidad para desplazar la ubicación horizontalmente. |
| y | float | La cantidad para desplazar la ubicación verticalmente. |

### contains(float x, float y) {#contains-float-float-}
```
public final boolean contains(float x, float y)
```


Determina si el punto especificado está contenido dentro de esta estructura [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns:**
boolean - Este método devuelve `true` si el punto definido por x e y está contenido dentro de esta estructura [RectangleF](../../com.aspose.drawing/rectanglef); de lo contrario `false`.
### contains(PointF pt) {#contains-com.aspose.drawing.PointF-}
```
public final boolean contains(PointF pt)
```


Determina si el punto especificado está contenido dentro de esta estructura [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | El [PointF](../../com.aspose.drawing/pointf) a probar. |

**Returns:**
boolean - Este método devuelve `true` si el punto representado por el parámetro pt está contenido dentro de esta estructura [RectangleF](../../com.aspose.drawing/rectanglef); de lo contrario `false`.
### contains(RectangleF rect) {#contains-com.aspose.drawing.RectangleF-}
```
public final boolean contains(RectangleF rect)
```


Determina si la región rectangular representada por `rect` está completamente contenida dentro de esta estructura [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | El [RectangleF](../../com.aspose.drawing/rectanglef) a probar. |

**Returns:**
boolean - Este método devuelve `true` si la región rectangular representada por `rect` está completamente contenida dentro de la región rectangular representada por esta [RectangleF](../../com.aspose.drawing/rectanglef); de lo contrario `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el Object especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El Object para comparar con esta instancia. |

**Returns:**
boolean - `true` si el Object especificado es igual a esta instancia; de lo contrario, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
### equals(RectangleF other) {#equals-com.aspose.drawing.RectangleF-}
```
public final boolean equals(RectangleF other)
```


Prueba si otra estructura [RectangleF](../../com.aspose.drawing/rectanglef) tiene la misma ubicación y tamaño que esta estructura [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [RectangleF](../../com.aspose.drawing/rectanglef) | Otro rectángulo para probar |

**Returns:**
boolean - Este método devuelve `true` si la otra estructura [RectangleF](../../com.aspose.drawing/rectanglef) y sus propiedades X, Y, Width y Height son iguales a las propiedades correspondientes de esta estructura [RectangleF](../../com.aspose.drawing/rectanglef); de lo contrario, `false`.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.drawing.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
