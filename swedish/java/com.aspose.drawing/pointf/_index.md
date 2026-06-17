---
title: PointF
second_title: Aspose.Drawing för Java API‑referens
description: Representerar ett ordnat par av flyttals‑x‑ och y‑koordinater som definierar en punkt i ett tvådimensionellt plan.
type: docs
weight: 37
url: /sv/java/com.aspose.drawing/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class PointF extends Struct<PointF> implements System.IEquatable<PointF>, Cloneable
```

Representerar ett ordnat par av flyttals‑x‑ och y‑koordinater som definierar en punkt i ett tvådimensionellt plan.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | Initierar en ny instans av PointF-strukturen med de angivna koordinaterna. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [op_Addition(PointF pt, Size sz)](#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [op_Subtraction(PointF pt, Size sz)](#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [op_Addition(PointF pt, SizeF sz)](#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [op_Subtraction(PointF pt, SizeF sz)](#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [op_Equality(PointF left, PointF right)](#op-Equality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | Jämför två [PointF](../../com.aspose.drawing/pointf)-strukturer. |
| [op_Inequality(PointF left, PointF right)](#op-Inequality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | Avgör om koordinaterna för de angivna punkterna inte är lika. |
| [add(PointF orig, Size size)](#add-com.aspose.drawing.PointF-com.aspose.drawing.Size-) | Översätter en given [PointF](../../com.aspose.drawing/pointf) med en specificerad [SizeF](../../com.aspose.drawing/sizef). |
| [subtract(PointF pt, Size sz)](#subtract-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [add(PointF orig, SizeF sizeF)](#add-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | Översätter en given [PointF](../../com.aspose.drawing/pointf) med en specificerad [SizeF](../../com.aspose.drawing/sizef). |
| [subtract(PointF pt, SizeF sz)](#subtract-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om denna [PointF](../../com.aspose.drawing/pointf) är tom. |
| [getX()](#getX--) | Hämtar x-koordinaten för detta PointF. |
| [setX(float value)](#setX-float-) | Ställer in x-koordinaten för detta PointF. |
| [getY()](#getY--) | Hämtar y-koordinaten för detta PointF. |
| [setY(float value)](#setY-float-) | Ställer in y-koordinaten för detta PointF. |
| [equals(Object obj)](#equals-java.lang.Object-) | Anger om denna [PointF](../../com.aspose.drawing/pointf) innehåller samma koordinater som det angivna objektet. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för denna instans. |
| [toString()](#toString--) |  |
| [equals(PointF other)](#equals-com.aspose.drawing.PointF-) | Testar om en annan [PointF](../../com.aspose.drawing/pointf)-struktur har samma position som denna [PointF](../../com.aspose.drawing/pointf)-struktur. |
| [CloneTo(PointF that)](#CloneTo-com.aspose.drawing.PointF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


Initierar en ny instans av PointF-strukturen med de angivna koordinaterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | flyttal | Den horisontella positionen för punkten. |
| y | flyttal | Den vertikala positionen för punkten. |

### op_Addition(PointF pt, Size sz) {#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF op_Addition(PointF pt, Size sz)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Subtraction(PointF pt, Size sz) {#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF op_Subtraction(PointF pt, Size sz)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Addition(PointF pt, SizeF sz) {#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF op_Addition(PointF pt, SizeF sz)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Subtraction(PointF pt, SizeF sz) {#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF op_Subtraction(PointF pt, SizeF sz)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Equality(PointF left, PointF right) {#op-Equality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean op_Equality(PointF left, PointF right)
```


Jämför två [PointF](../../com.aspose.drawing/pointf)-strukturer. Resultatet anger om värdena för egenskaperna `PointF.X` och `PointF.Y` i de två [PointF](../../com.aspose.drawing/pointf)-strukturerna är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [PointF](../../com.aspose.drawing/pointf) | Första [PointF](../../com.aspose.drawing/pointf) att jämföra. |
| right | [PointF](../../com.aspose.drawing/pointf) | Andra [PointF](../../com.aspose.drawing/pointf) att jämföra. |

**Returns:**
boolean - true om `PointF.X`- och `PointF.Y`-värdena för de vänstra och högra [PointF](../../com.aspose.drawing/pointf)-strukturerna är lika; annars false.
### op_Inequality(PointF left, PointF right) {#op-Inequality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean op_Inequality(PointF left, PointF right)
```


Avgör om koordinaterna för de angivna punkterna inte är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [PointF](../../com.aspose.drawing/pointf) | Första [PointF](../../com.aspose.drawing/pointf) att jämföra. |
| right | [PointF](../../com.aspose.drawing/pointf) | Andra [PointF](../../com.aspose.drawing/pointf) att jämföra. |

**Returns:**
boolean - true för att indikera att `PointF.X`- och `PointF.Y`-värdena för `left` och `right` inte är lika; annars false.
### add(PointF orig, Size size) {#add-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF add(PointF orig, Size size)
```


Översätter en given [PointF](../../com.aspose.drawing/pointf) med en specificerad [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| orig | [PointF](../../com.aspose.drawing/pointf) | Den [PointF](../../com.aspose.drawing/pointf) som ska översättas. |
| size | [Size](../../com.aspose.drawing/size) | Den [Size](../../com.aspose.drawing/size) som specificerar siffrorna att lägga till koordinaterna för `orig`. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The translated [PointF](../../com.aspose.drawing/pointf).
### subtract(PointF pt, Size sz) {#subtract-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF subtract(PointF pt, Size sz)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### add(PointF orig, SizeF sizeF) {#add-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF add(PointF orig, SizeF sizeF)
```


Översätter en given [PointF](../../com.aspose.drawing/pointf) med en specificerad [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| orig | [PointF](../../com.aspose.drawing/pointf) | Den [PointF](../../com.aspose.drawing/pointf) som ska översättas. |
| sizeF | [SizeF](../../com.aspose.drawing/sizef) | Den [SizeF](../../com.aspose.drawing/sizef) som specificerar siffrorna att lägga till koordinaterna för `orig`. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The translated [PointF](../../com.aspose.drawing/pointf).
### subtract(PointF pt, SizeF sz) {#subtract-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF subtract(PointF pt, SizeF sz)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.drawing/pointf) |  |
| obj2 | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```




**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Hämtar ett värde som indikerar om denna [PointF](../../com.aspose.drawing/pointf) är tom.

**Returns:**
boolean - ett värde som indikerar om denna [PointF](../../com.aspose.drawing/pointf) är tom.
### getX() {#getX--}
```
public final float getX()
```


Hämtar x-koordinaten för detta PointF.

**Returns:**
float - x-koordinaten för detta PointF.
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Ställer in x-koordinaten för detta PointF.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | flyttal | x-koordinaten för detta PointF. |

### getY() {#getY--}
```
public final float getY()
```


Hämtar y-koordinaten för detta PointF.

**Returns:**
float - y-koordinaten för detta PointF.
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Ställer in y-koordinaten för detta PointF.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | flyttal | y-koordinaten för detta PointF. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Anger om denna [PointF](../../com.aspose.drawing/pointf) innehåller samma koordinater som det angivna objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att testa. |

**Returns:**
boolean - Denna metod returnerar true om `obj` är en [PointF](../../com.aspose.drawing/pointf) och har samma koordinater som detta [Point](../../com.aspose.drawing/point).
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för denna instans.

**Returns:**
int - En hashkod för denna instans, lämplig för användning i hash-algoritmer och datastrukturer som en hash-tabell.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(PointF other) {#equals-com.aspose.drawing.PointF-}
```
public final boolean equals(PointF other)
```


Testar om en annan [PointF](../../com.aspose.drawing/pointf)-struktur har samma position som denna [PointF](../../com.aspose.drawing/pointf)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [PointF](../../com.aspose.drawing/pointf) | Annan punkt att testa |

**Returns:**
boolean - Denna metod returnerar `true` om den andra [PointF](../../com.aspose.drawing/pointf)-strukturen och dess X- och Y-egenskaper är lika med motsvarande egenskaper i denna [PointF](../../com.aspose.drawing/pointf)-struktur; annars `false`.
### CloneTo(PointF that) {#CloneTo-com.aspose.drawing.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [PointF](../../com.aspose.drawing/pointf) |  |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
