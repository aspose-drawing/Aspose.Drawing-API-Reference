---
title: SizeF
second_title: Aspose.Drawing för Java API‑referens
description: Lagrar ett ordnat par flyttal, vanligtvis bredden och höjden på en rektangel.
type: docs
weight: 43
url: /sv/java/com.aspose.drawing/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class SizeF extends Struct<SizeF> implements System.IEquatable<SizeF>, Cloneable
```

Lagrar ett ordnat par av flyttal, vanligtvis bredden och höjden på en rektangel.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(float width, float height)](#SizeF-float-float-) | Initierar en ny instans av SizeF‑strukturen från de angivna dimensionerna. |
| [SizeF(PointF pt)](#SizeF-com.aspose.drawing.PointF-) | Initierar en ny instans av [SizeF](../../com.aspose.drawing/sizef)-strukturen. |
| [SizeF(SizeF size)](#SizeF-com.aspose.drawing.SizeF-) | Initierar en ny instans av [SizeF](../../com.aspose.drawing/sizef)-strukturen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [op_Equality(SizeF sz1, SizeF sz2)](#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Testar om två [SizeF](../../com.aspose.drawing/sizef)-strukturer är lika. |
| [op_Inequality(SizeF sz1, SizeF sz2)](#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Testar om två [SizeF](../../com.aspose.drawing/sizef)-strukturer är olika. |
| [add(SizeF sz1, SizeF sz2)](#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Lägger till bredden och höjden för en [SizeF](../../com.aspose.drawing/sizef)-struktur till bredden och höjden för en annan [SizeF](../../com.aspose.drawing/sizef)-struktur. |
| [subtract(SizeF sz1, SizeF sz2)](#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Subtraherar bredden och höjden för en [SizeF](../../com.aspose.drawing/sizef)-struktur från bredden och höjden för en annan [SizeF](../../com.aspose.drawing/sizef)-struktur. |
| [op_Addition(SizeF sz1, SizeF sz2)](#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Lägger till bredden och höjden för en [SizeF](../../com.aspose.drawing/sizef)-struktur till bredden och höjden för en annan [SizeF](../../com.aspose.drawing/sizef)-struktur. |
| [op_Subtraction(SizeF sz1, SizeF sz2)](#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Subtraherar bredden och höjden för en [SizeF](../../com.aspose.drawing/sizef)-struktur från bredden och höjden för en annan [SizeF](../../com.aspose.drawing/sizef)-struktur. |
| [op_Multiply(float left, SizeF right)](#op-Multiply-float-com.aspose.drawing.SizeF-) | Multiplicerar [SizeF](../../com.aspose.drawing/sizef) med ett `float` och producerar [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(SizeF left, float right)](#op-Multiply-com.aspose.drawing.SizeF-float-) | Multiplicerar [SizeF](../../com.aspose.drawing/sizef) med ett `float` och producerar [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(SizeF left, float right)](#op-Division-com.aspose.drawing.SizeF-float-) | Dividerar [SizeF](../../com.aspose.drawing/sizef) med ett `float` och producerar [SizeF](../../com.aspose.drawing/sizef). |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om denna [SizeF](../../com.aspose.drawing/sizef) struktur har noll bredd och höjd. |
| [getWidth()](#getWidth--) | Hämtar den horisontella komponenten i denna SizeF-struktur. |
| [setWidth(float value)](#setWidth-float-) | Ställer in den horisontella komponenten i denna SizeF-struktur. |
| [getHeight()](#getHeight--) | Hämtar den vertikala komponenten i denna SizeF-struktur. |
| [setHeight(float value)](#setHeight-float-) | Ställer in den vertikala komponenten i denna SizeF-struktur. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för denna [SizeF](../../com.aspose.drawing/sizef)-struktur. |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Testar om det angivna objektet är en [SizeF](../../com.aspose.drawing/sizef)-struktur med samma dimensioner som denna [SizeF](../../com.aspose.drawing/sizef)-struktur. |
| [toSize()](#toSize--) | Konverterar en [SizeF](../../com.aspose.drawing/sizef)-struktur till en [Size](../../com.aspose.drawing/size)-struktur. |
| [toPointF()](#toPointF--) | Konverterar en [SizeF](../../com.aspose.drawing/sizef)-struktur till en [PointF](../../com.aspose.drawing/pointf)-struktur. |
| [equals(SizeF other)](#equals-com.aspose.drawing.SizeF-) | Testar om en annan [SizeF](../../com.aspose.drawing/sizef)-struktur har samma storlek som denna [SizeF](../../com.aspose.drawing/sizef)-struktur. |
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


Initierar en ny instans av SizeF‑strukturen från de angivna dimensionerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | flyttal | Breddkomponenten i den nya SizeF-strukturen. |
| höjd | flyttal | Höjskomponenten i den nya SizeF-strukturen. |

### SizeF(PointF pt) {#SizeF-com.aspose.drawing.PointF-}
```
public SizeF(PointF pt)
```


Initierar en ny instans av [SizeF](../../com.aspose.drawing/sizef)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | [PointF](../../com.aspose.drawing/pointf)-strukturen som används för att initiera denna [SizeF](../../com.aspose.drawing/sizef)-struktur. |

### SizeF(SizeF size) {#SizeF-com.aspose.drawing.SizeF-}
```
public SizeF(SizeF size)
```


Initierar en ny instans av [SizeF](../../com.aspose.drawing/sizef)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef)-strukturen som används för att skapa den nya [SizeF](../../com.aspose.drawing/sizef)-strukturen. |

### op_Equality(SizeF sz1, SizeF sz2) {#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Equality(SizeF sz1, SizeF sz2)
```


Testar om två [SizeF](../../com.aspose.drawing/sizef)-strukturer är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef)-strukturen på vänster sida av likhetsoperatorn. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef)-strukturen på höger sida av likhetsoperatorn. |

**Returns:**
boolean - Denna operator returnerar true om `sz1` och `sz2` har lika bredd och höjd; annars false.
### op_Inequality(SizeF sz1, SizeF sz2) {#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Inequality(SizeF sz1, SizeF sz2)
```


Testar om två [SizeF](../../com.aspose.drawing/sizef)-strukturer är olika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef)-strukturen på vänster sida av ojämlikhetsoperatorn. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef)-strukturen på höger sida av ojämlikhetsoperatorn. |

**Returns:**
boolean - Denna operator returnerar true om `sz1` och `sz2` skiljer sig i bredd eller höjd; false om `sz1` och `sz2` är lika.
### add(SizeF sz1, SizeF sz2) {#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF add(SizeF sz1, SizeF sz2)
```


Lägger till bredden och höjden för en [SizeF](../../com.aspose.drawing/sizef)-struktur till bredden och höjden för en annan [SizeF](../../com.aspose.drawing/sizef)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Den första [SizeF](../../com.aspose.drawing/sizef)-strukturen att lägga till. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Den andra [SizeF](../../com.aspose.drawing/sizef)-strukturen att lägga till. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is the result of the addition operation.
### subtract(SizeF sz1, SizeF sz2) {#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF subtract(SizeF sz1, SizeF sz2)
```


Subtraherar bredden och höjden för en [SizeF](../../com.aspose.drawing/sizef)-struktur från bredden och höjden för en annan [SizeF](../../com.aspose.drawing/sizef)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef)-strukturen på vänster sida av subtraktionsoperatorn. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Den [SizeF](../../com.aspose.drawing/sizef)-strukturen på högra sidan av subtraktionsoperatorn. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is a result of the subtraction operation.
### op_Addition(SizeF sz1, SizeF sz2) {#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Addition(SizeF sz1, SizeF sz2)
```


Lägger till bredden och höjden för en [SizeF](../../com.aspose.drawing/sizef)-struktur till bredden och höjden för en annan [SizeF](../../com.aspose.drawing/sizef)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Den första [SizeF](../../com.aspose.drawing/sizef)-strukturen att lägga till. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Den andra [SizeF](../../com.aspose.drawing/sizef)-strukturen att lägga till. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(SizeF sz1, SizeF sz2) {#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Subtraction(SizeF sz1, SizeF sz2)
```


Subtraherar bredden och höjden för en [SizeF](../../com.aspose.drawing/sizef)-struktur från bredden och höjden för en annan [SizeF](../../com.aspose.drawing/sizef)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef)-strukturen på vänster sida av subtraktionsoperatorn. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Den [SizeF](../../com.aspose.drawing/sizef)-strukturen på högra sidan av subtraktionsoperatorn. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that is the result of the subtraction operation.
### op_Multiply(float left, SizeF right) {#op-Multiply-float-com.aspose.drawing.SizeF-}
```
public static SizeF op_Multiply(float left, SizeF right)
```


Multiplicerar [SizeF](../../com.aspose.drawing/sizef) med ett `float` och producerar [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | flyttal | Multiplikator av typen `float`. |
| right | [SizeF](../../com.aspose.drawing/sizef) | Multiplikand av typen [SizeF](../../com.aspose.drawing/sizef). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(SizeF left, float right) {#op-Multiply-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Multiply(SizeF left, float right)
```


Multiplicerar [SizeF](../../com.aspose.drawing/sizef) med ett `float` och producerar [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Multiplikand av typen [SizeF](../../com.aspose.drawing/sizef). |
| höger | flyttal | Multiplikator av typen `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(SizeF left, float right) {#op-Division-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Division(SizeF left, float right)
```


Dividerar [SizeF](../../com.aspose.drawing/sizef) med ett `float` och producerar [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Dividenden av typen [SizeF](../../com.aspose.drawing/sizef). |
| höger | flyttal | Divisor av typen `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### to_PointF(SizeF size) {#to-PointF-com.aspose.drawing.SizeF-}
```
public static PointF to_PointF(SizeF size)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar ett värde som indikerar om denna [SizeF](../../com.aspose.drawing/sizef) struktur har noll bredd och höjd.

**Returns:**
boolean - ett värde som indikerar om denna [SizeF](../../com.aspose.drawing/sizef)-struktur har noll bredd och höjd.
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Hämtar den horisontella komponenten i denna SizeF-struktur.

**Returns:**
float - den horisontella komponenten i denna SizeF-struktur.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Ställer in den horisontella komponenten i denna SizeF-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | flyttal | den horisontella komponenten i denna SizeF-struktur. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Hämtar den vertikala komponenten i denna SizeF-struktur.

**Returns:**
float - den vertikala komponenten i denna SizeF-struktur.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Ställer in den vertikala komponenten i denna SizeF-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | flyttal | den vertikala komponenten i denna SizeF-struktur. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för denna [SizeF](../../com.aspose.drawing/sizef)-struktur.

**Returns:**
int - ett heltalsvärde som specificerar ett hash‑värde för denna [SizeF](../../com.aspose.drawing/sizef)-struktur.
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


Testar om det angivna objektet är en [SizeF](../../com.aspose.drawing/sizef)-struktur med samma dimensioner som denna [SizeF](../../com.aspose.drawing/sizef)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att testa. |

**Returns:**
boolean - Denna metod returnerar `true` om obj är en [SizeF](../../com.aspose.drawing/sizef) och har samma bredd och höjd som denna SizeF; annars `false`.
### toSize() {#toSize--}
```
public final Size toSize()
```


Konverterar en [SizeF](../../com.aspose.drawing/sizef)-struktur till en [Size](../../com.aspose.drawing/size)-struktur.

**Returns:**
[Size](../../com.aspose.drawing/size) - Returns a [Size](../../com.aspose.drawing/size) structure.
### toPointF() {#toPointF--}
```
public final PointF toPointF()
```


Konverterar en [SizeF](../../com.aspose.drawing/sizef)-struktur till en [PointF](../../com.aspose.drawing/pointf)-struktur.

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - Returns a [PointF](../../com.aspose.drawing/pointf) structure.
### equals(SizeF other) {#equals-com.aspose.drawing.SizeF-}
```
public final boolean equals(SizeF other)
```


Testar om en annan [SizeF](../../com.aspose.drawing/sizef)-struktur har samma storlek som denna [SizeF](../../com.aspose.drawing/sizef)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [SizeF](../../com.aspose.drawing/sizef) | Annan storlek att testa |

**Returns:**
boolean - Denna metod returnerar `true` om den andra [SizeF](../../com.aspose.drawing/sizef)-strukturen och dess Width‑ och Height‑egenskaper är lika med motsvarande egenskaper i denna [SizeF](../../com.aspose.drawing/sizef)-struktur; annars `false`.
### CloneTo(SizeF that) {#CloneTo-com.aspose.drawing.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
