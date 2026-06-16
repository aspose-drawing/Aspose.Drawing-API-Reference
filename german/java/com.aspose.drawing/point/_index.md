---
title: Punkt
second_title: Aspose.Drawing für Java API-Referenz
description: Stellt ein geordnetes Paar von ganzzahligen x‑ und y‑Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert.
type: docs
weight: 36
url: /de/java/com.aspose.drawing/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Point extends Struct<Point> implements System.IEquatable<Point>, Cloneable
```

Stellt ein geordnetes Paar von ganzzahligen x‑ und y‑Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Initialisiert eine neue Instanz der [Point](../../com.aspose.drawing/point)-Struktur mit den angegebenen Koordinaten. |
| [Point(Size sz)](#Point-com.aspose.drawing.Size-) |  |
| [Point(int dw)](#Point-int-) | Initialisiert eine neue Instanz der [Point](../../com.aspose.drawing/point)-Struktur unter Verwendung von Koordinaten, die durch einen ganzzahligen Wert angegeben werden. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [EMPTY](#EMPTY) | Stellt einen [Point](../../com.aspose.drawing/point) dar, dessen `Point.X`‑ und `Point.Y`‑Werte auf Null gesetzt sind. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [to_PointF(Point p)](#to-PointF-com.aspose.drawing.Point-) | Konvertiert die angegebene [Point](../../com.aspose.drawing/point)-Struktur in eine [PointF](../../com.aspose.drawing/pointf)-Struktur. |
| [to_Size(Point p)](#to-Size-com.aspose.drawing.Point-) |  |
| [op_Addition(Point pt, Size sz)](#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Subtraction(Point pt, Size sz)](#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Equality(Point left, Point right)](#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Vergleicht zwei [Point](../../com.aspose.drawing/point)-Objekte. |
| [op_Inequality(Point left, Point right)](#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Vergleicht zwei [Point](../../com.aspose.drawing/point)-Objekte. |
| [add(Point pt, Size sz)](#add-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Addiert die angegebene [Size](../../com.aspose.drawing/size) zu dem angegebenen [Point](../../com.aspose.drawing/point). |
| [subtract(Point pt, Size sz)](#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [ceiling(PointF value)](#ceiling-com.aspose.drawing.PointF-) |  |
| [truncate(PointF value)](#truncate-com.aspose.drawing.PointF-) | Konvertiert ein PointF in ein Point, indem alle Koordinaten abgeschnitten werden. |
| [round(PointF value)](#round-com.aspose.drawing.PointF-) | Konvertiert die angegebene [PointF](../../com.aspose.drawing/pointf) in ein Point‑Objekt, indem die [Point](../../com.aspose.drawing/point)-Werte auf die nächste ganze Zahl gerundet werden. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-) |  |
| [getEmpty()](#getEmpty--) |  |
| [getX()](#getX--) | Liefert die x‑Koordinate dieses Point. |
| [setX(int value)](#setX-int-) | Setzt die x‑Koordinate dieses Point. |
| [getY()](#getY--) | Liefert die y‑Koordinate dieses Point. |
| [setY(int value)](#setY-int-) | Setzt die y‑Koordinate dieses Point. |
| [isEmpty()](#isEmpty--) | Liefert einen Wert, der angibt, ob dieser [Point](../../com.aspose.drawing/point) leer ist. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diesen [Point](../../com.aspose.drawing/point) zurück. |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt an, ob dieser [Point](../../com.aspose.drawing/point) dieselben Koordinaten wie das angegebene Objekt enthält. |
| [offset(int dx, int dy)](#offset-int-int-) | Verschiebt diesen [Point](../../com.aspose.drawing/point) um den angegebenen Betrag. |
| [offset(Point p)](#offset-com.aspose.drawing.Point-) | Verschiebt diesen [Point](../../com.aspose.drawing/point) um den angegebenen [Point](../../com.aspose.drawing/point). |
| [equals(Point other)](#equals-com.aspose.drawing.Point-) | Prüft, ob eine andere [Point](../../com.aspose.drawing/point)-Struktur dieselbe Position wie diese [Point](../../com.aspose.drawing/point)-Struktur hat. |
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


Initialisiert eine neue Instanz der [Point](../../com.aspose.drawing/point)-Struktur mit den angegebenen Koordinaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die horizontale Position des Punktes. |
| y | int | Die vertikale Position des Punktes. |

### Point(Size sz) {#Point-com.aspose.drawing.Size-}
```
public Point(Size sz)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sz | [Size](../../com.aspose.drawing/size) |  |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Initialisiert eine neue Instanz der [Point](../../com.aspose.drawing/point)-Struktur unter Verwendung von Koordinaten, die durch einen ganzzahligen Wert angegeben werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dw | int | Der ganzzahlige Wert. |

### EMPTY {#EMPTY}
```
public static final Point EMPTY
```


Stellt einen [Point](../../com.aspose.drawing/point) dar, dessen `Point.X`‑ und `Point.Y`‑Werte auf Null gesetzt sind.

### to_PointF(Point p) {#to-PointF-com.aspose.drawing.Point-}
```
public static PointF to_PointF(Point p)
```


Konvertiert die angegebene [Point](../../com.aspose.drawing/point)-Struktur in eine [PointF](../../com.aspose.drawing/pointf)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | Der [Point](../../com.aspose.drawing/point), der konvertiert werden soll. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The [PointF](../../com.aspose.drawing/pointf) that results from the conversion.
### to_Size(Point p) {#to-Size-com.aspose.drawing.Point-}
```
public static Size to_Size(Point p)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
[Size](../../com.aspose.drawing/size)
### op_Addition(Point pt, Size sz) {#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Addition(Point pt, Size sz)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Equality(Point left, Point right) {#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Equality(Point left, Point right)
```


Vergleicht zwei [Point](../../com.aspose.drawing/point)-Objekte. Das Ergebnis gibt an, ob die Werte der `Point.X`- und `Point.Y`-Eigenschaften der beiden [Point](../../com.aspose.drawing/point)-Objekte gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Erster [Point](../../com.aspose.drawing/point) zum Vergleichen. |
| right | [Point](../../com.aspose.drawing/point) | Zweiter [Point](../../com.aspose.drawing/point) zum Vergleichen. |

**Returns:**
boolean - true, wenn die `Point.X`- und `Point.Y`-Werte von `left` und `right` gleich sind; andernfalls false.
### op_Inequality(Point left, Point right) {#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Inequality(Point left, Point right)
```


Vergleicht zwei [Point](../../com.aspose.drawing/point)-Objekte. Das Ergebnis gibt an, ob die Werte der `Point.X`- oder `Point.Y`-Eigenschaften der beiden [Point](../../com.aspose.drawing/point)-Objekte ungleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Erster [Point](../../com.aspose.drawing/point) zum Vergleichen. |
| right | [Point](../../com.aspose.drawing/point) | Zweiter [Point](../../com.aspose.drawing/point) zum Vergleichen. |

**Returns:**
boolean - true, wenn die Werte entweder der `Point.X`-Eigenschaften oder der `Point.Y`-Eigenschaften von `left` und `right` unterschiedlich sind; andernfalls false.
### add(Point pt, Size sz) {#add-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point add(Point pt, Size sz)
```


Addiert die angegebene [Size](../../com.aspose.drawing/size) zu dem angegebenen [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Der [Point](../../com.aspose.drawing/point) zum Hinzufügen. |
| sz | [Size](../../com.aspose.drawing/size) | Der [Size](../../com.aspose.drawing/size) zum Hinzufügen |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the addition operation.
### subtract(Point pt, Size sz) {#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point subtract(Point pt, Size sz)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### truncate(PointF value) {#truncate-com.aspose.drawing.PointF-}
```
public static Point truncate(PointF value)
```


Konvertiert ein PointF in ein Point, indem alle Koordinaten abgeschnitten werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Der [PointF](../../com.aspose.drawing/pointf) zum Abschneiden. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the truncate operation.
### round(PointF value) {#round-com.aspose.drawing.PointF-}
```
public static Point round(PointF value)
```


Konvertiert die angegebene [PointF](../../com.aspose.drawing/pointf) in ein Point‑Objekt, indem die [Point](../../com.aspose.drawing/point)-Werte auf die nächste ganze Zahl gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Der [PointF](../../com.aspose.drawing/pointf) zum Konvertieren. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) this method converts to.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Liefert die x‑Koordinate dieses Point.

**Returns:**
int - die x-Koordinate dieses Point.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Setzt die x‑Koordinate dieses Point.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | die x-Koordinate dieses Point. |

### getY() {#getY--}
```
public final int getY()
```


Liefert die y‑Koordinate dieses Point.

**Returns:**
int - die y-Koordinate dieses Point.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Setzt die y‑Koordinate dieses Point.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | die y-Koordinate dieses Point. |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Liefert einen Wert, der angibt, ob dieser [Point](../../com.aspose.drawing/point) leer ist.

Wert: `true`, wenn sowohl X als auch Y 0 sind; andernfalls `false`.

**Returns:**
boolean - ein Wert, der angibt, ob dieses dieses [Point](../../com.aspose.drawing/point) leer ist.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diesen [Point](../../com.aspose.drawing/point) zurück.

**Returns:**
int - Ein ganzzahliger Wert, der einen Hashwert für dieses [Point](../../com.aspose.drawing/point) angibt.
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


Gibt an, ob dieser [Point](../../com.aspose.drawing/point) dieselben Koordinaten wie das angegebene Objekt enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt zum Testen. |

**Returns:**
boolean - `true`, wenn obj ein Point ist und dieselben Koordinaten wie dieses [Point](../../com.aspose.drawing/point) hat.
### offset(int dx, int dy) {#offset-int-int-}
```
public final void offset(int dx, int dy)
```


Verschiebt diesen [Point](../../com.aspose.drawing/point) um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | int | Der Betrag, um die x-Koordinate zu verschieben. |
| dy | int | Der Betrag, um die y-Koordinate zu verschieben. |

### offset(Point p) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point p)
```


Verschiebt diesen [Point](../../com.aspose.drawing/point) um den angegebenen [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | Der [Point](../../com.aspose.drawing/point) wird verwendet, um dieses [Point](../../com.aspose.drawing/point) zu versetzen. |

### equals(Point other) {#equals-com.aspose.drawing.Point-}
```
public final boolean equals(Point other)
```


Prüft, ob eine andere [Point](../../com.aspose.drawing/point)-Struktur dieselbe Position wie diese [Point](../../com.aspose.drawing/point)-Struktur hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [Point](../../com.aspose.drawing/point) | Anderer Punkt zum Testen |

**Returns:**
boolean - Diese Methode gibt `true` zurück, wenn die andere [Point](../../com.aspose.drawing/point)-Struktur und deren X- und Y-Eigenschaften den entsprechenden Eigenschaften dieser [Point](../../com.aspose.drawing/point)-Struktur gleich sind; andernfalls `false`.
### CloneTo(Point that) {#CloneTo-com.aspose.drawing.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
