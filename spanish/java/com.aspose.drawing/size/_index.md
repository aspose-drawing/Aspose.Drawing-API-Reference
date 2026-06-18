---
title: Size
second_title: Referencia de la API de Aspose.Drawing para Java
description: Almacena un par ordenado de enteros que normalmente representan el ancho y la altura de un rectángulo.
type: docs
weight: 42
url: /es/java/com.aspose.drawing/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Size extends Struct<Size> implements System.IEquatable<Size>, Cloneable
```

Almacena un par ordenado de enteros, típicamente el ancho y la altura de un rectángulo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point pt)](#Size-com.aspose.drawing.Point-) | Inicializa una nueva instancia de la estructura [Size](../../com.aspose.drawing/size) a partir del [Point](../../com.aspose.drawing/point) especificado. |
| [Size(int width, int height)](#Size-int-int-) | Inicializa una nueva instancia de la estructura [Size](../../com.aspose.drawing/size) a partir de las dimensiones especificadas. |
## Métodos

| Método | Descripción |
| --- | --- |
| [to_SizeF(Size p)](#to-SizeF-com.aspose.drawing.Size-) | Convierte el [Size](../../com.aspose.drawing/size) especificado a un [SizeF](../../com.aspose.drawing/sizef). |
| [op_Addition(Size sz1, Size sz2)](#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Suma el ancho y la altura de una estructura [Size](../../com.aspose.drawing/size) al ancho y la altura de otra estructura [Size](../../com.aspose.drawing/size). |
| [op_Subtraction(Size sz1, Size sz2)](#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Resta el ancho y la altura de una estructura [Size](../../com.aspose.drawing/size) del ancho y la altura de otra estructura [Size](../../com.aspose.drawing/size). |
| [op_Multiply(int left, Size right)](#op-Multiply-int-com.aspose.drawing.Size-) | Multiplica un [Size](../../com.aspose.drawing/size) por un `int` produciendo [Size](../../com.aspose.drawing/size). |
| [op_Multiply(Size left, int right)](#op-Multiply-com.aspose.drawing.Size-int-) | Multiplica [Size](../../com.aspose.drawing/size) por un `int` produciendo [Size](../../com.aspose.drawing/size). |
| [op_Division(Size left, int right)](#op-Division-com.aspose.drawing.Size-int-) | Divide [Size](../../com.aspose.drawing/size) por un `int` produciendo [Size](../../com.aspose.drawing/size). |
| [op_Multiply(float left, Size right)](#op-Multiply-float-com.aspose.drawing.Size-) | Multiplica [Size](../../com.aspose.drawing/size) por un `float` produciendo [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(Size left, float right)](#op-Multiply-com.aspose.drawing.Size-float-) | Multiplica [Size](../../com.aspose.drawing/size) por un `float` produciendo [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(Size left, float right)](#op-Division-com.aspose.drawing.Size-float-) | Divide [Size](../../com.aspose.drawing/size) por un `float` produciendo [SizeF](../../com.aspose.drawing/sizef). |
| [op_Equality(Size sz1, Size sz2)](#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Comprueba si dos estructuras [Size](../../com.aspose.drawing/size) son iguales. |
| [op_Inequality(Size sz1, Size sz2)](#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Comprueba si dos estructuras [Size](../../com.aspose.drawing/size) son diferentes. |
| [to_Point(Size size)](#to-Point-com.aspose.drawing.Size-) | Convierte el [Size](../../com.aspose.drawing/size) especificado a un [Point](../../com.aspose.drawing/point). |
| [add(Size sz1, Size sz2)](#add-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Suma el ancho y la altura de una estructura [Size](../../com.aspose.drawing/size) al ancho y la altura de otra estructura [Size](../../com.aspose.drawing/size). |
| [ceiling(SizeF value)](#ceiling-com.aspose.drawing.SizeF-) | Convierte la estructura [SizeF](../../com.aspose.drawing/sizef) especificada a una estructura [Size](../../com.aspose.drawing/size) redondeando los valores de la estructura [Size](../../com.aspose.drawing/size) al siguiente entero mayor. |
| [subtract(Size sz1, Size sz2)](#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Resta el ancho y la altura de una estructura [Size](../../com.aspose.drawing/size) del ancho y la altura de otra estructura [Size](../../com.aspose.drawing/size). |
| [truncate(SizeF value)](#truncate-com.aspose.drawing.SizeF-) | Convierte la estructura [SizeF](../../com.aspose.drawing/sizef) especificada a una estructura [Size](../../com.aspose.drawing/size) truncando los valores de la estructura [SizeF](../../com.aspose.drawing/sizef) al siguiente entero inferior. |
| [round(SizeF value)](#round-com.aspose.drawing.SizeF-) | Convierte la estructura [SizeF](../../com.aspose.drawing/sizef) especificada a una estructura [Size](../../com.aspose.drawing/size) redondeando los valores de la estructura [SizeF](../../com.aspose.drawing/sizef) al entero más cercano. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si este [Size](../../com.aspose.drawing/size) tiene ancho y alto de 0. |
| [getWidth()](#getWidth--) | Obtiene el componente horizontal de este [Size](../../com.aspose.drawing/size). |
| [setWidth(int value)](#setWidth-int-) | Establece el componente horizontal de este [Size](../../com.aspose.drawing/size). |
| [getHeight()](#getHeight--) | Obtiene el componente vertical de este [Size](../../com.aspose.drawing/size). |
| [setHeight(int value)](#setHeight-int-) | Establece el componente vertical de este [Size](../../com.aspose.drawing/size). |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si el objeto especificado es un [Size](../../com.aspose.drawing/size) con las mismas dimensiones que este [Size](../../com.aspose.drawing/size). |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta estructura [Size](../../com.aspose.drawing/size). |
| [toString()](#toString--) |  |
| [equals(Size other)](#equals-com.aspose.drawing.Size-) | Comprueba si otra estructura [Size](../../com.aspose.drawing/size) tiene el mismo tamaño que esta estructura [Size](../../com.aspose.drawing/size). |
| [CloneTo(Size that)](#CloneTo-com.aspose.drawing.Size-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point pt) {#Size-com.aspose.drawing.Point-}
```
public Size(Point pt)
```


Inicializa una nueva instancia de la estructura [Size](../../com.aspose.drawing/size) a partir del [Point](../../com.aspose.drawing/point) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | El [Point](../../com.aspose.drawing/point) desde el cual inicializar este [Size](../../com.aspose.drawing/size). |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Inicializa una nueva instancia de la estructura [Size](../../com.aspose.drawing/size) a partir de las dimensiones especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El componente de ancho del nuevo [Size](../../com.aspose.drawing/size). |
| height | int | El componente de alto del nuevo [Size](../../com.aspose.drawing/size). |

### to_SizeF(Size p) {#to-SizeF-com.aspose.drawing.Size-}
```
public static SizeF to_SizeF(Size p)
```


Convierte el [Size](../../com.aspose.drawing/size) especificado a un [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | [Size](../../com.aspose.drawing/size) | El [Size](../../com.aspose.drawing/size) a convertir. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - The [SizeF](../../com.aspose.drawing/sizef) structure to which this operator converts.
### op_Addition(Size sz1, Size sz2) {#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Addition(Size sz1, Size sz2)
```


Suma el ancho y la altura de una estructura [Size](../../com.aspose.drawing/size) al ancho y la altura de otra estructura [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | El primer [Size](../../com.aspose.drawing/size) a añadir. |
| sz2 | [Size](../../com.aspose.drawing/size) | El segundo [Size](../../com.aspose.drawing/size) a añadir. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(Size sz1, Size sz2) {#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Subtraction(Size sz1, Size sz2)
```


Resta el ancho y la altura de una estructura [Size](../../com.aspose.drawing/size) del ancho y la altura de otra estructura [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | La estructura [Size](../../com.aspose.drawing/size) en el lado izquierdo del operador de resta. |
| sz2 | [Size](../../com.aspose.drawing/size) | La estructura [Size](../../com.aspose.drawing/size) en el lado derecho del operador de resta. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the subtraction operation.
### op_Multiply(int left, Size right) {#op-Multiply-int-com.aspose.drawing.Size-}
```
public static Size op_Multiply(int left, Size right)
```


Multiplica un [Size](../../com.aspose.drawing/size) por un `int` produciendo [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| izquierda | int | Multiplicador de tipo `int`. |
| right | [Size](../../com.aspose.drawing/size) | Multiplicando de tipo [Size](../../com.aspose.drawing/size). |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Multiply(Size left, int right) {#op-Multiply-com.aspose.drawing.Size-int-}
```
public static Size op_Multiply(Size left, int right)
```


Multiplica [Size](../../com.aspose.drawing/size) por un `int` produciendo [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Multiplicando de tipo [Size](../../com.aspose.drawing/size). |
| derecha | int | Multiplicador de tipo `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Division(Size left, int right) {#op-Division-com.aspose.drawing.Size-int-}
```
public static Size op_Division(Size left, int right)
```


Divide [Size](../../com.aspose.drawing/size) por un `int` produciendo [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividendo de tipo [Size](../../com.aspose.drawing/size). |
| derecha | int | Divisor de tipo `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Result of type [Size](../../com.aspose.drawing/size).
### op_Multiply(float left, Size right) {#op-Multiply-float-com.aspose.drawing.Size-}
```
public static SizeF op_Multiply(float left, Size right)
```


Multiplica [Size](../../com.aspose.drawing/size) por un `float` produciendo [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| izquierda | float | Multiplicador de tipo `float`. |
| right | [Size](../../com.aspose.drawing/size) | Multiplicando de tipo [Size](../../com.aspose.drawing/size). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(Size left, float right) {#op-Multiply-com.aspose.drawing.Size-float-}
```
public static SizeF op_Multiply(Size left, float right)
```


Multiplica [Size](../../com.aspose.drawing/size) por un `float` produciendo [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Multiplicando de tipo [Size](../../com.aspose.drawing/size). |
| derecha | float | Multiplicador de tipo `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(Size left, float right) {#op-Division-com.aspose.drawing.Size-float-}
```
public static SizeF op_Division(Size left, float right)
```


Divide [Size](../../com.aspose.drawing/size) por un `float` produciendo [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividendo de tipo [Size](../../com.aspose.drawing/size). |
| derecha | float | Divisor de tipo `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### op_Equality(Size sz1, Size sz2) {#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Equality(Size sz1, Size sz2)
```


Comprueba si dos estructuras [Size](../../com.aspose.drawing/size) son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | La estructura [Size](../../com.aspose.drawing/size) en el lado izquierdo del operador de igualdad. |
| sz2 | [Size](../../com.aspose.drawing/size) | La estructura [Size](../../com.aspose.drawing/size) en el lado derecho del operador de igualdad. |

**Returns:**
boolean - verdadero si `sz1` y `sz2` tienen ancho y alto iguales; de lo contrario, falso.
### op_Inequality(Size sz1, Size sz2) {#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Inequality(Size sz1, Size sz2)
```


Comprueba si dos estructuras [Size](../../com.aspose.drawing/size) son diferentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | La estructura [Size](../../com.aspose.drawing/size) en el lado izquierdo del operador de desigualdad. |
| sz2 | [Size](../../com.aspose.drawing/size) | La estructura [Size](../../com.aspose.drawing/size) en el lado derecho del operador de desigualdad. |

**Returns:**
boolean - verdadero si `sz1` y `sz2` difieren ya sea en ancho o en alto; falso si `sz1` y `sz2` son iguales.
### to_Point(Size size) {#to-Point-com.aspose.drawing.Size-}
```
public static Point to_Point(Size size)
```


Convierte el [Size](../../com.aspose.drawing/size) especificado a un [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | El [Size](../../com.aspose.drawing/size) a convertir. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) structure to which this operator converts.
### add(Size sz1, Size sz2) {#add-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size add(Size sz1, Size sz2)
```


Suma el ancho y la altura de una estructura [Size](../../com.aspose.drawing/size) al ancho y la altura de otra estructura [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | El primer [Size](../../com.aspose.drawing/size) a añadir. |
| sz2 | [Size](../../com.aspose.drawing/size) | El segundo [Size](../../com.aspose.drawing/size) a añadir. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### ceiling(SizeF value) {#ceiling-com.aspose.drawing.SizeF-}
```
public static Size ceiling(SizeF value)
```


Convierte la estructura [SizeF](../../com.aspose.drawing/sizef) especificada a una estructura [Size](../../com.aspose.drawing/size) redondeando los valores de la estructura [Size](../../com.aspose.drawing/size) al siguiente entero mayor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | La estructura [SizeF](../../com.aspose.drawing/sizef) a convertir. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### subtract(Size sz1, Size sz2) {#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size subtract(Size sz1, Size sz2)
```


Resta el ancho y la altura de una estructura [Size](../../com.aspose.drawing/size) del ancho y la altura de otra estructura [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | La estructura [Size](../../com.aspose.drawing/size) en el lado izquierdo del operador de resta. |
| sz2 | [Size](../../com.aspose.drawing/size) | La estructura [Size](../../com.aspose.drawing/size) en el lado derecho del operador de resta. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) that is a result of the subtraction operation.
### truncate(SizeF value) {#truncate-com.aspose.drawing.SizeF-}
```
public static Size truncate(SizeF value)
```


Convierte la estructura [SizeF](../../com.aspose.drawing/sizef) especificada a una estructura [Size](../../com.aspose.drawing/size) truncando los valores de la estructura [SizeF](../../com.aspose.drawing/sizef) al siguiente entero inferior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | La estructura [SizeF](../../com.aspose.drawing/sizef) a convertir. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### round(SizeF value) {#round-com.aspose.drawing.SizeF-}
```
public static Size round(SizeF value)
```


Convierte la estructura [SizeF](../../com.aspose.drawing/sizef) especificada a una estructura [Size](../../com.aspose.drawing/size) redondeando los valores de la estructura [SizeF](../../com.aspose.drawing/sizef) al entero más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | La estructura [SizeF](../../com.aspose.drawing/sizef) a convertir. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.drawing/size) |  |
| obj2 | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Obtiene un valor que indica si este [Size](../../com.aspose.drawing/size) tiene ancho y alto de 0.

**Returns:**
boolean - un valor que indica si este [Size](../../com.aspose.drawing/size) tiene ancho y alto de 0.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene el componente horizontal de este [Size](../../com.aspose.drawing/size).

**Returns:**
int - el componente horizontal de este [Size](../../com.aspose.drawing/size).
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Establece el componente horizontal de este [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | el componente horizontal de este [Size](../../com.aspose.drawing/size). |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene el componente vertical de este [Size](../../com.aspose.drawing/size).

**Returns:**
int - el componente vertical de este [Size](../../com.aspose.drawing/size).
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Establece el componente vertical de este [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | el componente vertical de este [Size](../../com.aspose.drawing/size). |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Comprueba si el objeto especificado es un [Size](../../com.aspose.drawing/size) con las mismas dimensiones que este [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto a probar. |

**Returns:**
boolean - verdadero si `obj` es un [Size](../../com.aspose.drawing/size) y tiene el mismo ancho y alto que este [Size](../../com.aspose.drawing/size); de lo contrario, falso.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta estructura [Size](../../com.aspose.drawing/size).

**Returns:**
int - Un valor entero que especifica un valor hash para esta estructura [Size](../../com.aspose.drawing/size).
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Size other) {#equals-com.aspose.drawing.Size-}
```
public final boolean equals(Size other)
```


Comprueba si otra estructura [Size](../../com.aspose.drawing/size) tiene el mismo tamaño que esta estructura [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [Size](../../com.aspose.drawing/size) | Otro tamaño a probar |

**Returns:**
boolean - Este método devuelve `true` si la otra estructura [Size](../../com.aspose.drawing/size) y sus propiedades Width y Height son iguales a las propiedades correspondientes de esta estructura [Size](../../com.aspose.drawing/size); de lo contrario, `false`.
### CloneTo(Size that) {#CloneTo-com.aspose.drawing.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [Size](../../com.aspose.drawing/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### clone() {#clone--}
```
public Size clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
