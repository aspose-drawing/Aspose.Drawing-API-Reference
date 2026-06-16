---
title: Size
second_title: Aspose.Drawing voor Java API-referentie
description: Slaat een geordend paar gehele getallen op, meestal de breedte en hoogte van een rechthoek.
type: docs
weight: 42
url: /nl/java/com.aspose.drawing/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Size extends Struct<Size> implements System.IEquatable<Size>, Cloneable
```

Slaat een geordend paar van gehele getallen op, meestal de breedte en hoogte van een rechthoek.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point pt)](#Size-com.aspose.drawing.Point-) | Initialiseert een nieuw exemplaar van de [Size](../../com.aspose.drawing/size)‑structuur vanuit het opgegeven [Point](../../com.aspose.drawing/point). |
| [Size(int width, int height)](#Size-int-int-) | Initialiseert een nieuw exemplaar van de [Size](../../com.aspose.drawing/size)‑structuur vanuit de opgegeven afmetingen. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [to_SizeF(Size p)](#to-SizeF-com.aspose.drawing.Size-) | Converteert de opgegeven [Size](../../com.aspose.drawing/size) naar een [SizeF](../../com.aspose.drawing/sizef). |
| [op_Addition(Size sz1, Size sz2)](#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Voegt de breedte en hoogte van één [Size](../../com.aspose.drawing/size)‑structuur toe aan de breedte en hoogte van een andere [Size](../../com.aspose.drawing/size)‑structuur. |
| [op_Subtraction(Size sz1, Size sz2)](#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Trek de breedte en hoogte van één [Size](../../com.aspose.drawing/size)‑structuur af van de breedte en hoogte van een andere [Size](../../com.aspose.drawing/size)‑structuur. |
| [op_Multiply(int left, Size right)](#op-Multiply-int-com.aspose.drawing.Size-) | Vermenigvuldigt een [Size](../../com.aspose.drawing/size) met een `int` en produceert een [Size](../../com.aspose.drawing/size). |
| [op_Multiply(Size left, int right)](#op-Multiply-com.aspose.drawing.Size-int-) | Vermenigvuldigt [Size](../../com.aspose.drawing/size) met een `int` en produceert een [Size](../../com.aspose.drawing/size). |
| [op_Division(Size left, int right)](#op-Division-com.aspose.drawing.Size-int-) | Deelt [Size](../../com.aspose.drawing/size) door een `int` en produceert een [Size](../../com.aspose.drawing/size). |
| [op_Multiply(float left, Size right)](#op-Multiply-float-com.aspose.drawing.Size-) | Vermenigvuldigt [Size](../../com.aspose.drawing/size) met een `float` en produceert een [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(Size left, float right)](#op-Multiply-com.aspose.drawing.Size-float-) | Vermenigvuldigt [Size](../../com.aspose.drawing/size) met een `float` en produceert een [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(Size left, float right)](#op-Division-com.aspose.drawing.Size-float-) | Deelt [Size](../../com.aspose.drawing/size) door een `float` en produceert [SizeF](../../com.aspose.drawing/sizef). |
| [op_Equality(Size sz1, Size sz2)](#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Test of twee [Size](../../com.aspose.drawing/size) structuren gelijk zijn. |
| [op_Inequality(Size sz1, Size sz2)](#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Test of twee [Size](../../com.aspose.drawing/size) structuren verschillend zijn. |
| [to_Point(Size size)](#to-Point-com.aspose.drawing.Size-) | Converteert de opgegeven [Size](../../com.aspose.drawing/size) naar een [Point](../../com.aspose.drawing/point). |
| [add(Size sz1, Size sz2)](#add-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Voegt de breedte en hoogte van één [Size](../../com.aspose.drawing/size)‑structuur toe aan de breedte en hoogte van een andere [Size](../../com.aspose.drawing/size)‑structuur. |
| [ceiling(SizeF value)](#ceiling-com.aspose.drawing.SizeF-) | Converteert de opgegeven [SizeF](../../com.aspose.drawing/sizef)-structuur naar een [Size](../../com.aspose.drawing/size)-structuur door de waarden van de [Size](../../com.aspose.drawing/size)-structuur af te ronden naar de eerstvolgende hogere gehele getallen. |
| [subtract(Size sz1, Size sz2)](#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Trek de breedte en hoogte van één [Size](../../com.aspose.drawing/size)‑structuur af van de breedte en hoogte van een andere [Size](../../com.aspose.drawing/size)‑structuur. |
| [truncate(SizeF value)](#truncate-com.aspose.drawing.SizeF-) | Converteert de opgegeven [SizeF](../../com.aspose.drawing/sizef)-structuur naar een [Size](../../com.aspose.drawing/size)-structuur door de waarden van de [SizeF](../../com.aspose.drawing/sizef)-structuur af te kappen naar de eerstvolgende lagere gehele getallen. |
| [round(SizeF value)](#round-com.aspose.drawing.SizeF-) | Converteert de opgegeven [SizeF](../../com.aspose.drawing/sizef)-structuur naar een [Size](../../com.aspose.drawing/size)-structuur door de waarden van de [SizeF](../../com.aspose.drawing/sizef)-structuur af te ronden naar het dichtstbijzijnde gehele getal. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Haalt een waarde op die aangeeft of deze [Size](../../com.aspose.drawing/size) een breedte en hoogte van 0 heeft. |
| [getWidth()](#getWidth--) | Haalt het horizontale component van deze [Size](../../com.aspose.drawing/size) op. |
| [setWidth(int value)](#setWidth-int-) | Stelt het horizontale component van deze [Size](../../com.aspose.drawing/size) in. |
| [getHeight()](#getHeight--) | Haalt het verticale component van deze [Size](../../com.aspose.drawing/size) op. |
| [setHeight(int value)](#setHeight-int-) | Stelt het verticale component van deze [Size](../../com.aspose.drawing/size) in. |
| [equals(Object obj)](#equals-java.lang.Object-) | Test of het opgegeven object een [Size](../../com.aspose.drawing/size) is met dezelfde afmetingen als deze [Size](../../com.aspose.drawing/size). |
| [hashCode()](#hashCode--) | Retourneert een hashcode voor deze [Size](../../com.aspose.drawing/size)-structuur. |
| [toString()](#toString--) |  |
| [equals(Size other)](#equals-com.aspose.drawing.Size-) | Test of een andere [Size](../../com.aspose.drawing/size)-structuur dezelfde grootte heeft als deze [Size](../../com.aspose.drawing/size)-structuur. |
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


Initialiseert een nieuw exemplaar van de [Size](../../com.aspose.drawing/size)‑structuur vanuit het opgegeven [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | De [Point](../../com.aspose.drawing/point) waaruit deze [Size](../../com.aspose.drawing/size) moet worden geïnitialiseerd. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Initialiseert een nieuw exemplaar van de [Size](../../com.aspose.drawing/size)‑structuur vanuit de opgegeven afmetingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | int | Het breedtecomponent van de nieuwe [Size](../../com.aspose.drawing/size). |
| height | int | Het hoogtecomponent van de nieuwe [Size](../../com.aspose.drawing/size). |

### to_SizeF(Size p) {#to-SizeF-com.aspose.drawing.Size-}
```
public static SizeF to_SizeF(Size p)
```


Converteert de opgegeven [Size](../../com.aspose.drawing/size) naar een [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| p | [Size](../../com.aspose.drawing/size) | De te converteren [Size](../../com.aspose.drawing/size). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - The [SizeF](../../com.aspose.drawing/sizef) structure to which this operator converts.
### op_Addition(Size sz1, Size sz2) {#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Addition(Size sz1, Size sz2)
```


Voegt de breedte en hoogte van één [Size](../../com.aspose.drawing/size)‑structuur toe aan de breedte en hoogte van een andere [Size](../../com.aspose.drawing/size)‑structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | De eerste [Size](../../com.aspose.drawing/size) om toe te voegen. |
| sz2 | [Size](../../com.aspose.drawing/size) | De tweede [Size](../../com.aspose.drawing/size) om toe te voegen. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(Size sz1, Size sz2) {#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Subtraction(Size sz1, Size sz2)
```


Trek de breedte en hoogte van één [Size](../../com.aspose.drawing/size)‑structuur af van de breedte en hoogte van een andere [Size](../../com.aspose.drawing/size)‑structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | De [Size](../../com.aspose.drawing/size)-structuur aan de linkerkant van de aftreksomoperator. |
| sz2 | [Size](../../com.aspose.drawing/size) | De [Size](../../com.aspose.drawing/size)-structuur aan de rechterkant van de aftreksomoperator. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the subtraction operation.
### op_Multiply(int left, Size right) {#op-Multiply-int-com.aspose.drawing.Size-}
```
public static Size op_Multiply(int left, Size right)
```


Vermenigvuldigt een [Size](../../com.aspose.drawing/size) met een `int` en produceert een [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| links | int | Vermenigvuldiger van type `int`. |
| right | [Size](../../com.aspose.drawing/size) | Vermenigvuldigde van type [Size](../../com.aspose.drawing/size). |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Multiply(Size left, int right) {#op-Multiply-com.aspose.drawing.Size-int-}
```
public static Size op_Multiply(Size left, int right)
```


Vermenigvuldigt [Size](../../com.aspose.drawing/size) met een `int` en produceert een [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Vermenigvuldigde van type [Size](../../com.aspose.drawing/size). |
| rechts | int | Vermenigvuldiger van type `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Division(Size left, int right) {#op-Division-com.aspose.drawing.Size-int-}
```
public static Size op_Division(Size left, int right)
```


Deelt [Size](../../com.aspose.drawing/size) door een `int` en produceert een [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividend van type [Size](../../com.aspose.drawing/size). |
| rechts | int | Deler van type `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Result of type [Size](../../com.aspose.drawing/size).
### op_Multiply(float left, Size right) {#op-Multiply-float-com.aspose.drawing.Size-}
```
public static SizeF op_Multiply(float left, Size right)
```


Vermenigvuldigt [Size](../../com.aspose.drawing/size) met een `float` en produceert een [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| links | float | Vermenigvuldiger van type `float`. |
| right | [Size](../../com.aspose.drawing/size) | Vermenigvuldigde van type [Size](../../com.aspose.drawing/size). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(Size left, float right) {#op-Multiply-com.aspose.drawing.Size-float-}
```
public static SizeF op_Multiply(Size left, float right)
```


Vermenigvuldigt [Size](../../com.aspose.drawing/size) met een `float` en produceert een [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Vermenigvuldigde van type [Size](../../com.aspose.drawing/size). |
| rechts | float | Vermenigvuldiger van type `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(Size left, float right) {#op-Division-com.aspose.drawing.Size-float-}
```
public static SizeF op_Division(Size left, float right)
```


Deelt [Size](../../com.aspose.drawing/size) door een `float` en produceert [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividend van type [Size](../../com.aspose.drawing/size). |
| rechts | float | Deler van type `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### op_Equality(Size sz1, Size sz2) {#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Equality(Size sz1, Size sz2)
```


Test of twee [Size](../../com.aspose.drawing/size) structuren gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | De [Size](../../com.aspose.drawing/size) structuur aan de linkerkant van de gelijkheidsoperator. |
| sz2 | [Size](../../com.aspose.drawing/size) | De [Size](../../com.aspose.drawing/size) structuur aan de rechterkant van de gelijkheidsoperator. |

**Returns:**
boolean - true als `sz1` en `sz2` gelijke breedte en hoogte hebben; anders false.
### op_Inequality(Size sz1, Size sz2) {#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Inequality(Size sz1, Size sz2)
```


Test of twee [Size](../../com.aspose.drawing/size) structuren verschillend zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | De [Size](../../com.aspose.drawing/size) structuur aan de linkerkant van de ongelijkheidsoperator. |
| sz2 | [Size](../../com.aspose.drawing/size) | De [Size](../../com.aspose.drawing/size) structuur aan de rechterkant van de ongelijkheidsoperator. |

**Returns:**
boolean - true als `sz1` en `sz2` verschillen in breedte of hoogte; false als `sz1` en `sz2` gelijk zijn.
### to_Point(Size size) {#to-Point-com.aspose.drawing.Size-}
```
public static Point to_Point(Size size)
```


Converteert de opgegeven [Size](../../com.aspose.drawing/size) naar een [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | De te converteren [Size](../../com.aspose.drawing/size). |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) structure to which this operator converts.
### add(Size sz1, Size sz2) {#add-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size add(Size sz1, Size sz2)
```


Voegt de breedte en hoogte van één [Size](../../com.aspose.drawing/size)‑structuur toe aan de breedte en hoogte van een andere [Size](../../com.aspose.drawing/size)‑structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | De eerste [Size](../../com.aspose.drawing/size) om toe te voegen. |
| sz2 | [Size](../../com.aspose.drawing/size) | De tweede [Size](../../com.aspose.drawing/size) om toe te voegen. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### ceiling(SizeF value) {#ceiling-com.aspose.drawing.SizeF-}
```
public static Size ceiling(SizeF value)
```


Converteert de opgegeven [SizeF](../../com.aspose.drawing/sizef)-structuur naar een [Size](../../com.aspose.drawing/size)-structuur door de waarden van de [Size](../../com.aspose.drawing/size)-structuur af te ronden naar de eerstvolgende hogere gehele getallen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | De [SizeF](../../com.aspose.drawing/sizef) structuur om te converteren. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### subtract(Size sz1, Size sz2) {#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size subtract(Size sz1, Size sz2)
```


Trek de breedte en hoogte van één [Size](../../com.aspose.drawing/size)‑structuur af van de breedte en hoogte van een andere [Size](../../com.aspose.drawing/size)‑structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | De [Size](../../com.aspose.drawing/size)-structuur aan de linkerkant van de aftreksomoperator. |
| sz2 | [Size](../../com.aspose.drawing/size) | De [Size](../../com.aspose.drawing/size)-structuur aan de rechterkant van de aftreksomoperator. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) that is a result of the subtraction operation.
### truncate(SizeF value) {#truncate-com.aspose.drawing.SizeF-}
```
public static Size truncate(SizeF value)
```


Converteert de opgegeven [SizeF](../../com.aspose.drawing/sizef)-structuur naar een [Size](../../com.aspose.drawing/size)-structuur door de waarden van de [SizeF](../../com.aspose.drawing/sizef)-structuur af te kappen naar de eerstvolgende lagere gehele getallen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | De [SizeF](../../com.aspose.drawing/sizef) structuur om te converteren. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### round(SizeF value) {#round-com.aspose.drawing.SizeF-}
```
public static Size round(SizeF value)
```


Converteert de opgegeven [SizeF](../../com.aspose.drawing/sizef)-structuur naar een [Size](../../com.aspose.drawing/size)-structuur door de waarden van de [SizeF](../../com.aspose.drawing/sizef)-structuur af te ronden naar het dichtstbijzijnde gehele getal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | De [SizeF](../../com.aspose.drawing/sizef) structuur om te converteren. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt een waarde op die aangeeft of deze [Size](../../com.aspose.drawing/size) een breedte en hoogte van 0 heeft.

**Returns:**
boolean - een waarde die aangeeft of deze [Size](../../com.aspose.drawing/size) een breedte en hoogte van 0 heeft.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Haalt het horizontale component van deze [Size](../../com.aspose.drawing/size) op.

**Returns:**
int - het horizontale component van deze [Size](../../com.aspose.drawing/size).
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Stelt het horizontale component van deze [Size](../../com.aspose.drawing/size) in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | het horizontale component van deze [Size](../../com.aspose.drawing/size). |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Haalt het verticale component van deze [Size](../../com.aspose.drawing/size) op.

**Returns:**
int - het verticale component van deze [Size](../../com.aspose.drawing/size).
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Stelt het verticale component van deze [Size](../../com.aspose.drawing/size) in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | het verticale component van deze [Size](../../com.aspose.drawing/size). |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Test of het opgegeven object een [Size](../../com.aspose.drawing/size) is met dezelfde afmetingen als deze [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te testen. |

**Returns:**
boolean - true als `obj` een [Size](../../com.aspose.drawing/size) is en dezelfde breedte en hoogte heeft als deze [Size](../../com.aspose.drawing/size); anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor deze [Size](../../com.aspose.drawing/size)-structuur.

**Returns:**
int - Een gehele waarde die een hashwaarde specificeert voor deze [Size](../../com.aspose.drawing/size) structuur.
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


Test of een andere [Size](../../com.aspose.drawing/size)-structuur dezelfde grootte heeft als deze [Size](../../com.aspose.drawing/size)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [Size](../../com.aspose.drawing/size) | Andere grootte om te testen |

**Returns:**
boolean - Deze methode retourneert `true` als de andere [Size](../../com.aspose.drawing/size) structuur en zijn Breedte- en Hoogte-eigenschappen gelijk zijn aan de overeenkomstige eigenschappen van deze [Size](../../com.aspose.drawing/size) structuur; anders `false`.
### CloneTo(Size that) {#CloneTo-com.aspose.drawing.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
