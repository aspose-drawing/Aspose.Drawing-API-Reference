---
title: CharacterRange
second_title: Referencia de la API de Aspose.Drawing para Java
description: Especifica un rango de posiciones de caracteres dentro de una cadena.
type: docs
weight: 13
url: /es/java/com.aspose.drawing/characterrange/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class CharacterRange extends Struct<CharacterRange> implements Cloneable
```

Especifica un rango de posiciones de caracteres dentro de una cadena.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CharacterRange()](#CharacterRange--) |  |
| [CharacterRange(int first, int length)](#CharacterRange-int-int-) | Inicializa una nueva instancia de la estructura [CharacterRange](../../com.aspose.drawing/characterrange), especificando un rango de posiciones de caracteres dentro de una cadena. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFirst()](#getFirst--) | Obtiene o establece la posición en la cadena del primer carácter de este [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setFirst(int value)](#setFirst-int-) | Obtiene o establece la posición en la cadena del primer carácter de este [CharacterRange](../../com.aspose.drawing/characterrange). |
| [getLength()](#getLength--) | Obtiene o establece el número de posiciones en este [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setLength(int value)](#setLength-int-) | Obtiene o establece el número de posiciones en este [CharacterRange](../../com.aspose.drawing/characterrange). |
| [op_Equality(CharacterRange cr1, CharacterRange cr2)](#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Compara dos objetos [CharacterRange](../../com.aspose.drawing/characterrange). |
| [op_Inequality(CharacterRange cr1, CharacterRange cr2)](#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Compara dos objetos [CharacterRange](../../com.aspose.drawing/characterrange). |
| [equals(Object obj)](#equals-java.lang.Object-) | Obtiene un valor que indica si este objeto es equivalente al objeto especificado. |
| [hashCode()](#hashCode--) | Devuelve el código hash de esta instancia. |
| [CloneTo(CharacterRange that)](#CloneTo-com.aspose.drawing.CharacterRange-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### CharacterRange() {#CharacterRange--}
```
public CharacterRange()
```


### CharacterRange(int first, int length) {#CharacterRange-int-int-}
```
public CharacterRange(int first, int length)
```


Inicializa una nueva instancia de la estructura [CharacterRange](../../com.aspose.drawing/characterrange), especificando un rango de posiciones de caracteres dentro de una cadena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| first | int | La posición del primer carácter en el rango. Por ejemplo, si First se establece en 0, la primera posición del rango es la posición 0 en la cadena. |
| length | int | El número de posiciones en el rango. |

### getFirst() {#getFirst--}
```
public final int getFirst()
```


Obtiene o establece la posición en la cadena del primer carácter de este [CharacterRange](../../com.aspose.drawing/characterrange).

Valor: La primera posición de este [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setFirst(int value) {#setFirst-int-}
```
public final void setFirst(int value)
```


Obtiene o establece la posición en la cadena del primer carácter de este [CharacterRange](../../com.aspose.drawing/characterrange).

Valor: La primera posición de este [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getLength() {#getLength--}
```
public final int getLength()
```


Obtiene o establece el número de posiciones en este [CharacterRange](../../com.aspose.drawing/characterrange).

Valor: El número de posiciones en este [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


Obtiene o establece el número de posiciones en este [CharacterRange](../../com.aspose.drawing/characterrange).

Valor: El número de posiciones en este [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### op_Equality(CharacterRange cr1, CharacterRange cr2) {#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Equality(CharacterRange cr1, CharacterRange cr2)
```


Compara dos objetos [CharacterRange](../../com.aspose.drawing/characterrange). Obtiene un valor que indica si los valores First y Length de los dos objetos [CharacterRange](../../com.aspose.drawing/characterrange) son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Un [CharacterRange](../../com.aspose.drawing/characterrange) para comparar por igualdad. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Un [CharacterRange](../../com.aspose.drawing/characterrange) para comparar por igualdad. |

**Returns:**
boolean - `true` para indicar que los dos objetos CharacterRange tienen los mismos valores First y Length; de lo contrario, `false`.
### op_Inequality(CharacterRange cr1, CharacterRange cr2) {#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Inequality(CharacterRange cr1, CharacterRange cr2)
```


Compara dos objetos [CharacterRange](../../com.aspose.drawing/characterrange). Obtiene un valor que indica si los valores First o Length de los dos objetos [CharacterRange](../../com.aspose.drawing/characterrange) no son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Un [CharacterRange](../../com.aspose.drawing/characterrange) para comparar por desigualdad. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Un [CharacterRange](../../com.aspose.drawing/characterrange) para comparar por desigualdad. |

**Returns:**
boolean - `true` para indicar que los valores First o Length de los dos objetos CharacterRange difieren; de lo contrario, `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Obtiene un valor que indica si este objeto es equivalente al objeto especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto con el que comparar para igualdad.. |

**Returns:**
boolean - `true` para indicar que el objeto especificado es una instancia con el mismo valor de First y Length que esta instancia; de lo contrario, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash de esta instancia.

**Returns:**
int - Un entero con signo de 32 bits que es el código hash de esta instancia.
### CloneTo(CharacterRange that) {#CloneTo-com.aspose.drawing.CharacterRange-}
```
public void CloneTo(CharacterRange that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [CharacterRange](../../com.aspose.drawing/characterrange) |  |

### Clone() {#Clone--}
```
public CharacterRange Clone()
```




**Returns:**
[CharacterRange](../../com.aspose.drawing/characterrange)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
