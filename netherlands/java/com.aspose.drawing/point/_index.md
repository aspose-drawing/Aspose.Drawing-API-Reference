---
title: Punt
second_title: Aspose.Drawing voor Java API-referentie
description: Stelt een geordend paar van gehele x- en y-coördinaten voor dat een punt in een tweedimensionaal vlak definieert.
type: docs
weight: 36
url: /nl/java/com.aspose.drawing/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Point extends Struct<Point> implements System.IEquatable<Point>, Cloneable
```

Stelt een geordend paar van gehele x- en y-coördinaten voor dat een punt in een tweedimensionaal vlak definieert.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Initialiseert een nieuw exemplaar van de [Point](../../com.aspose.drawing/point)-struct met de opgegeven coördinaten. |
| [Point(Size sz)](#Point-com.aspose.drawing.Size-) |  |
| [Point(int dw)](#Point-int-) | Initialiseert een nieuw exemplaar van de [Point](../../com.aspose.drawing/point)-struct met coördinaten opgegeven door een geheel getal. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [EMPTY](#EMPTY) | Stelt een [Point](../../com.aspose.drawing/point) voor die `Point.X` en `Point.Y` waarden op nul heeft ingesteld. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [to_PointF(Point p)](#to-PointF-com.aspose.drawing.Point-) | Converteert de opgegeven [Point](../../com.aspose.drawing/point)-structuur naar een [PointF](../../com.aspose.drawing/pointf)-structuur. |
| [to_Size(Point p)](#to-Size-com.aspose.drawing.Point-) |  |
| [op_Addition(Point pt, Size sz)](#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Subtraction(Point pt, Size sz)](#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Equality(Point left, Point right)](#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Vergelijkt twee [Point](../../com.aspose.drawing/point)-objecten. |
| [op_Inequality(Point left, Point right)](#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Vergelijkt twee [Point](../../com.aspose.drawing/point)-objecten. |
| [add(Point pt, Size sz)](#add-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Voegt de opgegeven [Size](../../com.aspose.drawing/size) toe aan de opgegeven [Point](../../com.aspose.drawing/point). |
| [subtract(Point pt, Size sz)](#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [ceiling(PointF value)](#ceiling-com.aspose.drawing.PointF-) |  |
| [truncate(PointF value)](#truncate-com.aspose.drawing.PointF-) | Converteert een PointF naar een Point door een afkappende bewerking op alle coördinaten uit te voeren. |
| [round(PointF value)](#round-com.aspose.drawing.PointF-) | Converteert de opgegeven [PointF](../../com.aspose.drawing/pointf) naar een Point-object door de [Point](../../com.aspose.drawing/point)-waarden af te ronden op het dichtstbijzijnde geheel getal. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-) |  |
| [getEmpty()](#getEmpty--) |  |
| [getX()](#getX--) | Haalt de x-coördinaat van dit Point op. |
| [setX(int value)](#setX-int-) | Stelt de x-coördinaat van dit Point in. |
| [getY()](#getY--) | Haalt de y-coördinaat van dit Point op. |
| [setY(int value)](#setY-int-) | Stelt de y-coördinaat van dit Point in. |
| [isEmpty()](#isEmpty--) | Haalt een waarde op die aangeeft of dit [Point](../../com.aspose.drawing/point) leeg is. |
| [hashCode()](#hashCode--) | Retourneert een hashcode voor dit [Point](../../com.aspose.drawing/point). |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Specificeert of dit [Point](../../com.aspose.drawing/point) dezelfde coördinaten bevat als het opgegeven Object. |
| [offset(int dx, int dy)](#offset-int-int-) | Verschuift dit [Point](../../com.aspose.drawing/point) met de opgegeven hoeveelheid. |
| [offset(Point p)](#offset-com.aspose.drawing.Point-) | Verschuift dit [Point](../../com.aspose.drawing/point) met de opgegeven [Point](../../com.aspose.drawing/point). |
| [equals(Point other)](#equals-com.aspose.drawing.Point-) | Test of een andere [Point](../../com.aspose.drawing/point)-structuur dezelfde locatie heeft als deze [Point](../../com.aspose.drawing/point)-structuur. |
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


Initialiseert een nieuw exemplaar van de [Point](../../com.aspose.drawing/point)-struct met de opgegeven coördinaten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De horizontale positie van het punt. |
| y | int | De verticale positie van het punt. |

### Point(Size sz) {#Point-com.aspose.drawing.Size-}
```
public Point(Size sz)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sz | [Size](../../com.aspose.drawing/size) |  |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Initialiseert een nieuw exemplaar van de [Point](../../com.aspose.drawing/point)-struct met coördinaten opgegeven door een geheel getal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dw | int | De gehele getalwaarde. |

### EMPTY {#EMPTY}
```
public static final Point EMPTY
```


Stelt een [Point](../../com.aspose.drawing/point) voor die `Point.X` en `Point.Y` waarden op nul heeft ingesteld.

### to_PointF(Point p) {#to-PointF-com.aspose.drawing.Point-}
```
public static PointF to_PointF(Point p)
```


Converteert de opgegeven [Point](../../com.aspose.drawing/point)-structuur naar een [PointF](../../com.aspose.drawing/pointf)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | Het [Point](../../com.aspose.drawing/point) dat moet worden geconverteerd. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The [PointF](../../com.aspose.drawing/pointf) that results from the conversion.
### to_Size(Point p) {#to-Size-com.aspose.drawing.Point-}
```
public static Size to_Size(Point p)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
[Size](../../com.aspose.drawing/size)
### op_Addition(Point pt, Size sz) {#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Addition(Point pt, Size sz)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Equality(Point left, Point right) {#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Equality(Point left, Point right)
```


Vergelijkt twee [Point](../../com.aspose.drawing/point) objecten. Het resultaat geeft aan of de waarden van de `Point.X` en `Point.Y` eigenschappen van de twee [Point](../../com.aspose.drawing/point) objecten gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Eerste [Point](../../com.aspose.drawing/point) om te vergelijken. |
| right | [Point](../../com.aspose.drawing/point) | Tweede [Point](../../com.aspose.drawing/point) om te vergelijken. |

**Returns:**
boolean - true als de `Point.X` en `Point.Y` waarden van `left` en `right` gelijk zijn; anders false.
### op_Inequality(Point left, Point right) {#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Inequality(Point left, Point right)
```


Vergelijkt twee [Point](../../com.aspose.drawing/point) objecten. Het resultaat geeft aan of de waarden van de `Point.X` of `Point.Y` eigenschappen van de twee [Point](../../com.aspose.drawing/point) objecten ongelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Eerste [Point](../../com.aspose.drawing/point) om te vergelijken. |
| right | [Point](../../com.aspose.drawing/point) | Tweede [Point](../../com.aspose.drawing/point) om te vergelijken. |

**Returns:**
boolean - true als de waarden van ofwel de `Point.X` eigenschappen of de `Point.Y` eigenschappen van `left` en `right` verschillen; anders false.
### add(Point pt, Size sz) {#add-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point add(Point pt, Size sz)
```


Voegt de opgegeven [Size](../../com.aspose.drawing/size) toe aan de opgegeven [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Het [Point](../../com.aspose.drawing/point) om toe te voegen. |
| sz | [Size](../../com.aspose.drawing/size) | Het [Size](../../com.aspose.drawing/size) om toe te voegen |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the addition operation.
### subtract(Point pt, Size sz) {#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point subtract(Point pt, Size sz)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### truncate(PointF value) {#truncate-com.aspose.drawing.PointF-}
```
public static Point truncate(PointF value)
```


Converteert een PointF naar een Point door een afkappende bewerking op alle coördinaten uit te voeren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Het [PointF](../../com.aspose.drawing/pointf) om af te kappen. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the truncate operation.
### round(PointF value) {#round-com.aspose.drawing.PointF-}
```
public static Point round(PointF value)
```


Converteert de opgegeven [PointF](../../com.aspose.drawing/pointf) naar een Point-object door de [Point](../../com.aspose.drawing/point)-waarden af te ronden op het dichtstbijzijnde geheel getal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Het [PointF](../../com.aspose.drawing/pointf) om te converteren. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) this method converts to.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de x-coördinaat van dit Point op.

**Returns:**
int - de x-coördinaat van dit Point.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Stelt de x-coördinaat van dit Point in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | de x-coördinaat van dit Point. |

### getY() {#getY--}
```
public final int getY()
```


Haalt de y-coördinaat van dit Point op.

**Returns:**
int - de y-coördinaat van dit Point.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Stelt de y-coördinaat van dit Point in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | de y-coördinaat van dit Point. |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Haalt een waarde op die aangeeft of dit [Point](../../com.aspose.drawing/point) leeg is.

Waarde: `true` als zowel X als Y 0 zijn; anders, `false`.

**Returns:**
boolean - een waarde die aangeeft of dit dit [Point](../../com.aspose.drawing/point) leeg is.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor dit [Point](../../com.aspose.drawing/point).

**Returns:**
int - Een geheel getal dat een hashwaarde voor dit [Point](../../com.aspose.drawing/point) specificeert.
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


Specificeert of dit [Point](../../com.aspose.drawing/point) dezelfde coördinaten bevat als het opgegeven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te testen. |

**Returns:**
boolean - `true` als obj een Point is en dezelfde coördinaten heeft als dit [Point](../../com.aspose.drawing/point).
### offset(int dx, int dy) {#offset-int-int-}
```
public final void offset(int dx, int dy)
```


Verschuift dit [Point](../../com.aspose.drawing/point) met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | int | De hoeveelheid om de x-coördinaat te verschuiven. |
| dy | int | De hoeveelheid om de y-coördinaat te verschuiven. |

### offset(Point p) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point p)
```


Verschuift dit [Point](../../com.aspose.drawing/point) met de opgegeven [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | Het [Point](../../com.aspose.drawing/point) dat wordt gebruikt om dit [Point](../../com.aspose.drawing/point) te verschuiven. |

### equals(Point other) {#equals-com.aspose.drawing.Point-}
```
public final boolean equals(Point other)
```


Test of een andere [Point](../../com.aspose.drawing/point)-structuur dezelfde locatie heeft als deze [Point](../../com.aspose.drawing/point)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [Point](../../com.aspose.drawing/point) | Andere punt om te testen |

**Returns:**
boolean - Deze methode retourneert `true` als de andere [Point](../../com.aspose.drawing/point) structuur en zijn X- en Y-eigenschappen gelijk zijn aan de overeenkomstige eigenschappen van deze [Point](../../com.aspose.drawing/point) structuur; anders, `false`.
### CloneTo(Point that) {#CloneTo-com.aspose.drawing.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
