---
title: SizeF
second_title: Referencia de la API de Aspose.Drawing para Java
description: Almacena un par ordenado de números de punto flotante, típicamente el ancho y la altura de un rectángulo.
type: docs
weight: 43
url: /es/java/com.aspose.drawing/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class SizeF extends Struct<SizeF> implements System.IEquatable<SizeF>, Cloneable
```

Almacena un par ordenado de números de punto flotante, típicamente el ancho y la altura de un rectángulo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(float width, float height)](#SizeF-float-float-) | Inicializa una nueva instancia de la estructura SizeF a partir de las dimensiones especificadas. |
| [SizeF(PointF pt)](#SizeF-com.aspose.drawing.PointF-) | Inicializa una nueva instancia de la estructura [SizeF](../../com.aspose.drawing/sizef). |
| [SizeF(SizeF size)](#SizeF-com.aspose.drawing.SizeF-) | Inicializa una nueva instancia de la estructura [SizeF](../../com.aspose.drawing/sizef). |
## Métodos

| Método | Descripción |
| --- | --- |
| [op_Equality(SizeF sz1, SizeF sz2)](#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Comprueba si dos estructuras [SizeF](../../com.aspose.drawing/sizef) son iguales. |
| [op_Inequality(SizeF sz1, SizeF sz2)](#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Comprueba si dos estructuras [SizeF](../../com.aspose.drawing/sizef) son diferentes. |
| [add(SizeF sz1, SizeF sz2)](#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Añade el ancho y la altura de una estructura [SizeF](../../com.aspose.drawing/sizef) al ancho y la altura de otra estructura [SizeF](../../com.aspose.drawing/sizef). |
| [subtract(SizeF sz1, SizeF sz2)](#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Resta el ancho y la altura de una estructura [SizeF](../../com.aspose.drawing/sizef) del ancho y la altura de otra estructura [SizeF](../../com.aspose.drawing/sizef). |
| [op_Addition(SizeF sz1, SizeF sz2)](#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Añade el ancho y la altura de una estructura [SizeF](../../com.aspose.drawing/sizef) al ancho y la altura de otra estructura [SizeF](../../com.aspose.drawing/sizef). |
| [op_Subtraction(SizeF sz1, SizeF sz2)](#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Resta el ancho y la altura de una estructura [SizeF](../../com.aspose.drawing/sizef) del ancho y la altura de otra estructura [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(float left, SizeF right)](#op-Multiply-float-com.aspose.drawing.SizeF-) | Multiplica [SizeF](../../com.aspose.drawing/sizef) por un `float` produciendo [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(SizeF left, float right)](#op-Multiply-com.aspose.drawing.SizeF-float-) | Multiplica [SizeF](../../com.aspose.drawing/sizef) por un `float` produciendo [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(SizeF left, float right)](#op-Division-com.aspose.drawing.SizeF-float-) | Divide [SizeF](../../com.aspose.drawing/sizef) por un `float` produciendo [SizeF](../../com.aspose.drawing/sizef). |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si esta estructura [SizeF](../../com.aspose.drawing/sizef) tiene ancho y altura cero. |
| [getWidth()](#getWidth--) | Obtiene el componente horizontal de esta estructura SizeF. |
| [setWidth(float value)](#setWidth-float-) | Establece el componente horizontal de esta estructura SizeF. |
| [getHeight()](#getHeight--) | Obtiene el componente vertical de esta estructura SizeF. |
| [setHeight(float value)](#setHeight-float-) | Establece el componente vertical de esta estructura SizeF. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta estructura [SizeF](../../com.aspose.drawing/sizef). |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si el objeto especificado es una estructura [SizeF](../../com.aspose.drawing/sizef) con las mismas dimensiones que esta estructura [SizeF](../../com.aspose.drawing/sizef). |
| [toSize()](#toSize--) | Convierte una estructura [SizeF](../../com.aspose.drawing/sizef) a una estructura [Size](../../com.aspose.drawing/size). |
| [toPointF()](#toPointF--) | Convierte una estructura [SizeF](../../com.aspose.drawing/sizef) a una estructura [PointF](../../com.aspose.drawing/pointf). |
| [equals(SizeF other)](#equals-com.aspose.drawing.SizeF-) | Comprueba si otra estructura [SizeF](../../com.aspose.drawing/sizef) tiene el mismo tamaño que esta estructura [SizeF](../../com.aspose.drawing/sizef). |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.drawing.SizeF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Inicializa una nueva instancia de la estructura SizeF a partir de las dimensiones especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho | float | El componente de ancho de la nueva estructura SizeF. |
| alto | float | El componente de altura de la nueva estructura SizeF. |

### SizeF(PointF pt) {#SizeF-com.aspose.drawing.PointF-}
```
public SizeF(PointF pt)
```


Inicializa una nueva instancia de la estructura [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | La estructura [PointF](../../com.aspose.drawing/pointf) desde la cual inicializar esta estructura [SizeF](../../com.aspose.drawing/sizef). |

### SizeF(SizeF size) {#SizeF-com.aspose.drawing.SizeF-}
```
public SizeF(SizeF size)
```


Inicializa una nueva instancia de la estructura [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | La estructura [SizeF](../../com.aspose.drawing/sizef) desde la cual crear la nueva estructura [SizeF](../../com.aspose.drawing/sizef). |

### op_Equality(SizeF sz1, SizeF sz2) {#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Equality(SizeF sz1, SizeF sz2)
```


Comprueba si dos estructuras [SizeF](../../com.aspose.drawing/sizef) son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La estructura [SizeF](../../com.aspose.drawing/sizef) en el lado izquierdo del operador de igualdad. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La estructura [SizeF](../../com.aspose.drawing/sizef) en el lado derecho del operador de igualdad. |

**Returns:**
boolean - Este operador devuelve true si `sz1` y `sz2` tienen el mismo ancho y altura; de lo contrario, false.
### op_Inequality(SizeF sz1, SizeF sz2) {#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Inequality(SizeF sz1, SizeF sz2)
```


Comprueba si dos estructuras [SizeF](../../com.aspose.drawing/sizef) son diferentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La estructura [SizeF](../../com.aspose.drawing/sizef) en el lado izquierdo del operador de desigualdad. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La estructura [SizeF](../../com.aspose.drawing/sizef) en el lado derecho del operador de desigualdad. |

**Returns:**
boolean - Este operador devuelve true si `sz1` y `sz2` difieren ya sea en ancho o en altura; false si `sz1` y `sz2` son iguales.
### add(SizeF sz1, SizeF sz2) {#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF add(SizeF sz1, SizeF sz2)
```


Añade el ancho y la altura de una estructura [SizeF](../../com.aspose.drawing/sizef) al ancho y la altura de otra estructura [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La primera estructura [SizeF](../../com.aspose.drawing/sizef) a añadir. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La segunda estructura [SizeF](../../com.aspose.drawing/sizef) a añadir. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is the result of the addition operation.
### subtract(SizeF sz1, SizeF sz2) {#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF subtract(SizeF sz1, SizeF sz2)
```


Resta el ancho y la altura de una estructura [SizeF](../../com.aspose.drawing/sizef) del ancho y la altura de otra estructura [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La estructura [SizeF](../../com.aspose.drawing/sizef) en el lado izquierdo del operador de sustracción. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La estructura [SizeF](../../com.aspose.drawing/sizef) en el lado derecho del operador de resta. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is a result of the subtraction operation.
### op_Addition(SizeF sz1, SizeF sz2) {#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Addition(SizeF sz1, SizeF sz2)
```


Añade el ancho y la altura de una estructura [SizeF](../../com.aspose.drawing/sizef) al ancho y la altura de otra estructura [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La primera estructura [SizeF](../../com.aspose.drawing/sizef) a añadir. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La segunda estructura [SizeF](../../com.aspose.drawing/sizef) a añadir. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(SizeF sz1, SizeF sz2) {#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Subtraction(SizeF sz1, SizeF sz2)
```


Resta el ancho y la altura de una estructura [SizeF](../../com.aspose.drawing/sizef) del ancho y la altura de otra estructura [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La estructura [SizeF](../../com.aspose.drawing/sizef) en el lado izquierdo del operador de sustracción. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La estructura [SizeF](../../com.aspose.drawing/sizef) en el lado derecho del operador de resta. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that is the result of the subtraction operation.
### op_Multiply(float left, SizeF right) {#op-Multiply-float-com.aspose.drawing.SizeF-}
```
public static SizeF op_Multiply(float left, SizeF right)
```


Multiplica [SizeF](../../com.aspose.drawing/sizef) por un `float` produciendo [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| izquierda | float | Multiplicador de tipo `float`. |
| right | [SizeF](../../com.aspose.drawing/sizef) | Multiplicando de tipo [SizeF](../../com.aspose.drawing/sizef). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(SizeF left, float right) {#op-Multiply-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Multiply(SizeF left, float right)
```


Multiplica [SizeF](../../com.aspose.drawing/sizef) por un `float` produciendo [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Multiplicando de tipo [SizeF](../../com.aspose.drawing/sizef). |
| derecha | float | Multiplicador de tipo `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(SizeF left, float right) {#op-Division-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Division(SizeF left, float right)
```


Divide [SizeF](../../com.aspose.drawing/sizef) por un `float` produciendo [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Dividendo de tipo [SizeF](../../com.aspose.drawing/sizef). |
| derecha | float | Divisor de tipo `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### to_PointF(SizeF size) {#to-PointF-com.aspose.drawing.SizeF-}
```
public static PointF to_PointF(SizeF size)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.drawing/sizef) |  |
| obj2 | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Obtiene un valor que indica si esta estructura [SizeF](../../com.aspose.drawing/sizef) tiene ancho y altura cero.

**Returns:**
boolean - un valor que indica si esta estructura [SizeF](../../com.aspose.drawing/sizef) tiene ancho y alto cero.
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Obtiene el componente horizontal de esta estructura SizeF.

**Returns:**
float - el componente horizontal de esta estructura SizeF.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Establece el componente horizontal de esta estructura SizeF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float | el componente horizontal de esta estructura SizeF. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Obtiene el componente vertical de esta estructura SizeF.

**Returns:**
float - el componente vertical de esta estructura SizeF.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Establece el componente vertical de esta estructura SizeF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float | el componente vertical de esta estructura SizeF. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta estructura [SizeF](../../com.aspose.drawing/sizef).

**Returns:**
int - Un valor entero que especifica un valor hash para esta estructura [SizeF](../../com.aspose.drawing/sizef).
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


Comprueba si el objeto especificado es una estructura [SizeF](../../com.aspose.drawing/sizef) con las mismas dimensiones que esta estructura [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto a probar. |

**Returns:**
boolean - Este método devuelve `true` si obj es un [SizeF](../../com.aspose.drawing/sizef) y tiene el mismo ancho y alto que este SizeF; de lo contrario, `false`.
### toSize() {#toSize--}
```
public final Size toSize()
```


Convierte una estructura [SizeF](../../com.aspose.drawing/sizef) a una estructura [Size](../../com.aspose.drawing/size).

**Returns:**
[Size](../../com.aspose.drawing/size) - Returns a [Size](../../com.aspose.drawing/size) structure.
### toPointF() {#toPointF--}
```
public final PointF toPointF()
```


Convierte una estructura [SizeF](../../com.aspose.drawing/sizef) a una estructura [PointF](../../com.aspose.drawing/pointf).

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - Returns a [PointF](../../com.aspose.drawing/pointf) structure.
### equals(SizeF other) {#equals-com.aspose.drawing.SizeF-}
```
public final boolean equals(SizeF other)
```


Comprueba si otra estructura [SizeF](../../com.aspose.drawing/sizef) tiene el mismo tamaño que esta estructura [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [SizeF](../../com.aspose.drawing/sizef) | Otro tamaño a probar |

**Returns:**
boolean - Este método devuelve `true` si la otra estructura [SizeF](../../com.aspose.drawing/sizef) y sus propiedades Width y Height son iguales a las propiedades correspondientes de esta estructura [SizeF](../../com.aspose.drawing/sizef); de lo contrario, `false`.
### CloneTo(SizeF that) {#CloneTo-com.aspose.drawing.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.drawing/sizef) |  |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
