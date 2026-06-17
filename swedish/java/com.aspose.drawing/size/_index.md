---
title: Size
second_title: Aspose.Drawing för Java API‑referens
description: Lagrar ett ordnat par av heltal, vanligtvis bredden och höjden på en rektangel.
type: docs
weight: 42
url: /sv/java/com.aspose.drawing/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Size extends Struct<Size> implements System.IEquatable<Size>, Cloneable
```

Lagrar ett ordnat par av heltal, vanligtvis bredden och höjden på en rektangel.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point pt)](#Size-com.aspose.drawing.Point-) | Initierar en ny instans av strukturen [Size](../../com.aspose.drawing/size) från den angivna [Point](../../com.aspose.drawing/point). |
| [Size(int width, int height)](#Size-int-int-) | Initierar en ny instans av strukturen [Size](../../com.aspose.drawing/size) från de angivna dimensionerna. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [to_SizeF(Size p)](#to-SizeF-com.aspose.drawing.Size-) | Konverterar den angivna [Size](../../com.aspose.drawing/size) till en [SizeF](../../com.aspose.drawing/sizef). |
| [op_Addition(Size sz1, Size sz2)](#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Lägger till bredden och höjden av en [Size](../../com.aspose.drawing/size)-struktur till bredden och höjden av en annan [Size](../../com.aspose.drawing/size)-struktur. |
| [op_Subtraction(Size sz1, Size sz2)](#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Subtraherar bredden och höjden av en [Size](../../com.aspose.drawing/size)-struktur från bredden och höjden av en annan [Size](../../com.aspose.drawing/size)-struktur. |
| [op_Multiply(int left, Size right)](#op-Multiply-int-com.aspose.drawing.Size-) | Multiplicerar en [Size](../../com.aspose.drawing/size) med ett `int` och producerar en [Size](../../com.aspose.drawing/size). |
| [op_Multiply(Size left, int right)](#op-Multiply-com.aspose.drawing.Size-int-) | Multiplicerar [Size](../../com.aspose.drawing/size) med ett `int` och producerar en [Size](../../com.aspose.drawing/size). |
| [op_Division(Size left, int right)](#op-Division-com.aspose.drawing.Size-int-) | Dividerar [Size](../../com.aspose.drawing/size) med ett `int` och producerar en [Size](../../com.aspose.drawing/size). |
| [op_Multiply(float left, Size right)](#op-Multiply-float-com.aspose.drawing.Size-) | Multiplicerar [Size](../../com.aspose.drawing/size) med ett `float` och producerar en [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(Size left, float right)](#op-Multiply-com.aspose.drawing.Size-float-) | Multiplicerar [Size](../../com.aspose.drawing/size) med ett `float` och producerar en [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(Size left, float right)](#op-Division-com.aspose.drawing.Size-float-) | Dividerar [Size](../../com.aspose.drawing/size) med ett `float` och producerar [SizeF](../../com.aspose.drawing/sizef). |
| [op_Equality(Size sz1, Size sz2)](#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Testar om två [Size](../../com.aspose.drawing/size)-strukturer är lika. |
| [op_Inequality(Size sz1, Size sz2)](#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Testar om två [Size](../../com.aspose.drawing/size)-strukturer är olika. |
| [to_Point(Size size)](#to-Point-com.aspose.drawing.Size-) | Konverterar den angivna [Size](../../com.aspose.drawing/size) till en [Point](../../com.aspose.drawing/point). |
| [add(Size sz1, Size sz2)](#add-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Lägger till bredden och höjden av en [Size](../../com.aspose.drawing/size)-struktur till bredden och höjden av en annan [Size](../../com.aspose.drawing/size)-struktur. |
| [ceiling(SizeF value)](#ceiling-com.aspose.drawing.SizeF-) | Konverterar den angivna [SizeF](../../com.aspose.drawing/sizef)-strukturen till en [Size](../../com.aspose.drawing/size)-struktur genom att avrunda värdena i [Size](../../com.aspose.drawing/size)-strukturen till nästa högre heltalsvärde. |
| [subtract(Size sz1, Size sz2)](#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Subtraherar bredden och höjden av en [Size](../../com.aspose.drawing/size)-struktur från bredden och höjden av en annan [Size](../../com.aspose.drawing/size)-struktur. |
| [truncate(SizeF value)](#truncate-com.aspose.drawing.SizeF-) | Konverterar den angivna [SizeF](../../com.aspose.drawing/sizef)-strukturen till en [Size](../../com.aspose.drawing/size)-struktur genom att trunkera värdena i [SizeF](../../com.aspose.drawing/sizef)-strukturen till nästa lägre heltalsvärde. |
| [round(SizeF value)](#round-com.aspose.drawing.SizeF-) | Konverterar den angivna [SizeF](../../com.aspose.drawing/sizef)-strukturen till en [Size](../../com.aspose.drawing/size)-struktur genom att avrunda värdena i [SizeF](../../com.aspose.drawing/sizef)-strukturen till närmaste heltal. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om denna [Size](../../com.aspose.drawing/size) har bredd och höjd på 0. |
| [getWidth()](#getWidth--) | Hämtar den horisontella komponenten i denna [Size](../../com.aspose.drawing/size). |
| [setWidth(int value)](#setWidth-int-) | Ställer in den horisontella komponenten i denna [Size](../../com.aspose.drawing/size). |
| [getHeight()](#getHeight--) | Hämtar den vertikala komponenten i denna [Size](../../com.aspose.drawing/size). |
| [setHeight(int value)](#setHeight-int-) | Ställer in den vertikala komponenten i denna [Size](../../com.aspose.drawing/size). |
| [equals(Object obj)](#equals-java.lang.Object-) | Testar om det angivna objektet är en [Size](../../com.aspose.drawing/size) med samma dimensioner som denna [Size](../../com.aspose.drawing/size). |
| [hashCode()](#hashCode--) | Returnerar en hashkod för denna [Size](../../com.aspose.drawing/size)-struktur. |
| [toString()](#toString--) |  |
| [equals(Size other)](#equals-com.aspose.drawing.Size-) | Testar om en annan [Size](../../com.aspose.drawing/size)-struktur har samma storlek som denna [Size](../../com.aspose.drawing/size)-struktur. |
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


Initierar en ny instans av strukturen [Size](../../com.aspose.drawing/size) från den angivna [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Den [Point](../../com.aspose.drawing/point) som används för att initiera denna [Size](../../com.aspose.drawing/size). |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Initierar en ny instans av strukturen [Size](../../com.aspose.drawing/size) från de angivna dimensionerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | int | Breddkomponenten för den nya [Size](../../com.aspose.drawing/size). |
| height | int | Höjskomponenten för den nya [Size](../../com.aspose.drawing/size). |

### to_SizeF(Size p) {#to-SizeF-com.aspose.drawing.Size-}
```
public static SizeF to_SizeF(Size p)
```


Konverterar den angivna [Size](../../com.aspose.drawing/size) till en [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) att konvertera. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - The [SizeF](../../com.aspose.drawing/sizef) structure to which this operator converts.
### op_Addition(Size sz1, Size sz2) {#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Addition(Size sz1, Size sz2)
```


Lägger till bredden och höjden av en [Size](../../com.aspose.drawing/size)-struktur till bredden och höjden av en annan [Size](../../com.aspose.drawing/size)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Den första [Size](../../com.aspose.drawing/size) att lägga till. |
| sz2 | [Size](../../com.aspose.drawing/size) | Den andra [Size](../../com.aspose.drawing/size) att lägga till. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(Size sz1, Size sz2) {#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Subtraction(Size sz1, Size sz2)
```


Subtraherar bredden och höjden av en [Size](../../com.aspose.drawing/size)-struktur från bredden och höjden av en annan [Size](../../com.aspose.drawing/size)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size)-strukturen på vänster sida av subtraktionsoperatorn. |
| sz2 | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size)-strukturen på höger sida av subtraktionsoperatorn. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the subtraction operation.
### op_Multiply(int left, Size right) {#op-Multiply-int-com.aspose.drawing.Size-}
```
public static Size op_Multiply(int left, Size right)
```


Multiplicerar en [Size](../../com.aspose.drawing/size) med ett `int` och producerar en [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | int | Multiplikator av typen `int`. |
| right | [Size](../../com.aspose.drawing/size) | Multiplikand av typen [Size](../../com.aspose.drawing/size). |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Multiply(Size left, int right) {#op-Multiply-com.aspose.drawing.Size-int-}
```
public static Size op_Multiply(Size left, int right)
```


Multiplicerar [Size](../../com.aspose.drawing/size) med ett `int` och producerar en [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Multiplikand av typen [Size](../../com.aspose.drawing/size). |
| höger | int | Multiplikator av typen `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Division(Size left, int right) {#op-Division-com.aspose.drawing.Size-int-}
```
public static Size op_Division(Size left, int right)
```


Dividerar [Size](../../com.aspose.drawing/size) med ett `int` och producerar en [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividend av typen [Size](../../com.aspose.drawing/size). |
| höger | int | Divisor av typen `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Result of type [Size](../../com.aspose.drawing/size).
### op_Multiply(float left, Size right) {#op-Multiply-float-com.aspose.drawing.Size-}
```
public static SizeF op_Multiply(float left, Size right)
```


Multiplicerar [Size](../../com.aspose.drawing/size) med ett `float` och producerar en [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | flyttal | Multiplikator av typen `float`. |
| right | [Size](../../com.aspose.drawing/size) | Multiplikand av typen [Size](../../com.aspose.drawing/size). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(Size left, float right) {#op-Multiply-com.aspose.drawing.Size-float-}
```
public static SizeF op_Multiply(Size left, float right)
```


Multiplicerar [Size](../../com.aspose.drawing/size) med ett `float` och producerar en [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Multiplikand av typen [Size](../../com.aspose.drawing/size). |
| höger | flyttal | Multiplikator av typen `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(Size left, float right) {#op-Division-com.aspose.drawing.Size-float-}
```
public static SizeF op_Division(Size left, float right)
```


Dividerar [Size](../../com.aspose.drawing/size) med ett `float` och producerar [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividend av typen [Size](../../com.aspose.drawing/size). |
| höger | flyttal | Divisor av typen `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### op_Equality(Size sz1, Size sz2) {#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Equality(Size sz1, Size sz2)
```


Testar om två [Size](../../com.aspose.drawing/size)-strukturer är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Strukturen [Size](../../com.aspose.drawing/size) på vänster sida av likhetsoperatorn. |
| sz2 | [Size](../../com.aspose.drawing/size) | Strukturen [Size](../../com.aspose.drawing/size) på högra sidan av likhetsoperatorn. |

**Returns:**
boolesk - true om `sz1` och `sz2` har lika bredd och höjd; annars false.
### op_Inequality(Size sz1, Size sz2) {#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Inequality(Size sz1, Size sz2)
```


Testar om två [Size](../../com.aspose.drawing/size)-strukturer är olika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Strukturen [Size](../../com.aspose.drawing/size) på vänster sida av ojämlikhetsoperatorn. |
| sz2 | [Size](../../com.aspose.drawing/size) | Strukturen [Size](../../com.aspose.drawing/size) på högra sidan av ojämlikhetsoperatorn. |

**Returns:**
boolesk - true om `sz1` och `sz2` skiljer sig i bredd eller höjd; false om `sz1` och `sz2` är lika.
### to_Point(Size size) {#to-Point-com.aspose.drawing.Size-}
```
public static Point to_Point(Size size)
```


Konverterar den angivna [Size](../../com.aspose.drawing/size) till en [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) att konvertera. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) structure to which this operator converts.
### add(Size sz1, Size sz2) {#add-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size add(Size sz1, Size sz2)
```


Lägger till bredden och höjden av en [Size](../../com.aspose.drawing/size)-struktur till bredden och höjden av en annan [Size](../../com.aspose.drawing/size)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Den första [Size](../../com.aspose.drawing/size) att lägga till. |
| sz2 | [Size](../../com.aspose.drawing/size) | Den andra [Size](../../com.aspose.drawing/size) att lägga till. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### ceiling(SizeF value) {#ceiling-com.aspose.drawing.SizeF-}
```
public static Size ceiling(SizeF value)
```


Konverterar den angivna [SizeF](../../com.aspose.drawing/sizef)-strukturen till en [Size](../../com.aspose.drawing/size)-struktur genom att avrunda värdena i [Size](../../com.aspose.drawing/size)-strukturen till nästa högre heltalsvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | Strukturen [SizeF](../../com.aspose.drawing/sizef) att konvertera. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### subtract(Size sz1, Size sz2) {#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size subtract(Size sz1, Size sz2)
```


Subtraherar bredden och höjden av en [Size](../../com.aspose.drawing/size)-struktur från bredden och höjden av en annan [Size](../../com.aspose.drawing/size)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size)-strukturen på vänster sida av subtraktionsoperatorn. |
| sz2 | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size)-strukturen på höger sida av subtraktionsoperatorn. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) that is a result of the subtraction operation.
### truncate(SizeF value) {#truncate-com.aspose.drawing.SizeF-}
```
public static Size truncate(SizeF value)
```


Konverterar den angivna [SizeF](../../com.aspose.drawing/sizef)-strukturen till en [Size](../../com.aspose.drawing/size)-struktur genom att trunkera värdena i [SizeF](../../com.aspose.drawing/sizef)-strukturen till nästa lägre heltalsvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | Strukturen [SizeF](../../com.aspose.drawing/sizef) att konvertera. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### round(SizeF value) {#round-com.aspose.drawing.SizeF-}
```
public static Size round(SizeF value)
```


Konverterar den angivna [SizeF](../../com.aspose.drawing/sizef)-strukturen till en [Size](../../com.aspose.drawing/size)-struktur genom att avrunda värdena i [SizeF](../../com.aspose.drawing/sizef)-strukturen till närmaste heltal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | Strukturen [SizeF](../../com.aspose.drawing/sizef) att konvertera. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar ett värde som indikerar om denna [Size](../../com.aspose.drawing/size) har bredd och höjd på 0.

**Returns:**
boolesk - ett värde som indikerar om denna [Size](../../com.aspose.drawing/size) har bredd och höjd på 0.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar den horisontella komponenten i denna [Size](../../com.aspose.drawing/size).

**Returns:**
int - den horisontella komponenten av denna [Size](../../com.aspose.drawing/size).
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ställer in den horisontella komponenten i denna [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | den horisontella komponenten av denna [Size](../../com.aspose.drawing/size). |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar den vertikala komponenten i denna [Size](../../com.aspose.drawing/size).

**Returns:**
int - den vertikala komponenten av denna [Size](../../com.aspose.drawing/size).
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ställer in den vertikala komponenten i denna [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | den vertikala komponenten av denna [Size](../../com.aspose.drawing/size). |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Testar om det angivna objektet är en [Size](../../com.aspose.drawing/size) med samma dimensioner som denna [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att testa. |

**Returns:**
boolesk - true om `obj` är en [Size](../../com.aspose.drawing/size) och har samma bredd och höjd som denna [Size](../../com.aspose.drawing/size); annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för denna [Size](../../com.aspose.drawing/size)-struktur.

**Returns:**
int - ett heltalsvärde som specificerar ett hashvärde för denna [Size](../../com.aspose.drawing/size)-struktur.
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


Testar om en annan [Size](../../com.aspose.drawing/size)-struktur har samma storlek som denna [Size](../../com.aspose.drawing/size)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [Size](../../com.aspose.drawing/size) | Annan storlek att testa |

**Returns:**
boolesk - Denna metod returnerar `true` om den andra [Size](../../com.aspose.drawing/size)-strukturen och dess Width- och Height-egenskaper är lika med motsvarande egenskaper i denna [Size](../../com.aspose.drawing/size)-struktur; annars `false`.
### CloneTo(Size that) {#CloneTo-com.aspose.drawing.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
