---
title: Size
second_title: Aspose.Drawing für Java API-Referenz
description: Speichert ein geordnetes Paar von Ganzzahlen, typischerweise die Breite und Höhe eines Rechtecks.
type: docs
weight: 42
url: /de/java/com.aspose.drawing/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Size extends Struct<Size> implements System.IEquatable<Size>, Cloneable
```

Speichert ein geordnetes Paar von Ganzzahlen, typischerweise die Breite und Höhe eines Rechtecks.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point pt)](#Size-com.aspose.drawing.Point-) | Initialisiert eine neue Instanz der [Size](../../com.aspose.drawing/size)-Struktur aus dem angegebenen [Point](../../com.aspose.drawing/point). |
| [Size(int width, int height)](#Size-int-int-) | Initialisiert eine neue Instanz der [Size](../../com.aspose.drawing/size)-Struktur aus den angegebenen Abmessungen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [to_SizeF(Size p)](#to-SizeF-com.aspose.drawing.Size-) | Konvertiert das angegebene [Size](../../com.aspose.drawing/size) in ein [SizeF](../../com.aspose.drawing/sizef). |
| [op_Addition(Size sz1, Size sz2)](#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Addiert die Breite und Höhe einer [Size](../../com.aspose.drawing/size)-Struktur zur Breite und Höhe einer anderen [Size](../../com.aspose.drawing/size)-Struktur. |
| [op_Subtraction(Size sz1, Size sz2)](#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Subtrahiert die Breite und Höhe einer [Size](../../com.aspose.drawing/size)-Struktur von der Breite und Höhe einer anderen [Size](../../com.aspose.drawing/size)-Struktur. |
| [op_Multiply(int left, Size right)](#op-Multiply-int-com.aspose.drawing.Size-) | Multipliziert ein [Size](../../com.aspose.drawing/size) mit einem `int` und erzeugt ein [Size](../../com.aspose.drawing/size). |
| [op_Multiply(Size left, int right)](#op-Multiply-com.aspose.drawing.Size-int-) | Multipliziert [Size](../../com.aspose.drawing/size) mit einem `int` und erzeugt ein [Size](../../com.aspose.drawing/size). |
| [op_Division(Size left, int right)](#op-Division-com.aspose.drawing.Size-int-) | Dividiert [Size](../../com.aspose.drawing/size) durch einen `int` und erzeugt ein [Size](../../com.aspose.drawing/size). |
| [op_Multiply(float left, Size right)](#op-Multiply-float-com.aspose.drawing.Size-) | Multipliziert [Size](../../com.aspose.drawing/size) mit einem `float` und erzeugt ein [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(Size left, float right)](#op-Multiply-com.aspose.drawing.Size-float-) | Multipliziert [Size](../../com.aspose.drawing/size) mit einem `float` und erzeugt ein [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(Size left, float right)](#op-Division-com.aspose.drawing.Size-float-) | Dividiert [Size](../../com.aspose.drawing/size) durch einen `float` und erzeugt [SizeF](../../com.aspose.drawing/sizef). |
| [op_Equality(Size sz1, Size sz2)](#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Prüft, ob zwei [Size](../../com.aspose.drawing/size)-Strukturen gleich sind. |
| [op_Inequality(Size sz1, Size sz2)](#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Prüft, ob zwei [Size](../../com.aspose.drawing/size)-Strukturen unterschiedlich sind. |
| [to_Point(Size size)](#to-Point-com.aspose.drawing.Size-) | Konvertiert das angegebene [Size](../../com.aspose.drawing/size) in ein [Point](../../com.aspose.drawing/point). |
| [add(Size sz1, Size sz2)](#add-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Addiert die Breite und Höhe einer [Size](../../com.aspose.drawing/size)-Struktur zur Breite und Höhe einer anderen [Size](../../com.aspose.drawing/size)-Struktur. |
| [ceiling(SizeF value)](#ceiling-com.aspose.drawing.SizeF-) | Konvertiert die angegebene [SizeF](../../com.aspose.drawing/sizef)-Struktur in eine [Size](../../com.aspose.drawing/size)-Struktur, indem die Werte der [Size](../../com.aspose.drawing/size)-Struktur auf die nächsthöheren Ganzzahlen gerundet werden. |
| [subtract(Size sz1, Size sz2)](#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Subtrahiert die Breite und Höhe einer [Size](../../com.aspose.drawing/size)-Struktur von der Breite und Höhe einer anderen [Size](../../com.aspose.drawing/size)-Struktur. |
| [truncate(SizeF value)](#truncate-com.aspose.drawing.SizeF-) | Konvertiert die angegebene [SizeF](../../com.aspose.drawing/sizef)-Struktur in eine [Size](../../com.aspose.drawing/size)-Struktur, indem die Werte der [SizeF](../../com.aspose.drawing/sizef)-Struktur auf die nächstniedrigeren Ganzzahlen abgeschnitten werden. |
| [round(SizeF value)](#round-com.aspose.drawing.SizeF-) | Konvertiert die angegebene [SizeF](../../com.aspose.drawing/sizef)-Struktur in eine [Size](../../com.aspose.drawing/size)-Struktur, indem die Werte der [SizeF](../../com.aspose.drawing/sizef)-Struktur auf die nächsten Ganzzahlen gerundet werden. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Gibt einen Wert zurück, der angibt, ob dieses [Size](../../com.aspose.drawing/size) Breite und Höhe von 0 hat. |
| [getWidth()](#getWidth--) | Gibt die horizontale Komponente dieses [Size](../../com.aspose.drawing/size) zurück. |
| [setWidth(int value)](#setWidth-int-) | Setzt die horizontale Komponente dieses [Size](../../com.aspose.drawing/size). |
| [getHeight()](#getHeight--) | Gibt die vertikale Komponente dieses [Size](../../com.aspose.drawing/size) zurück. |
| [setHeight(int value)](#setHeight-int-) | Setzt die vertikale Komponente dieses [Size](../../com.aspose.drawing/size). |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft, ob das angegebene Objekt ein [Size](../../com.aspose.drawing/size) mit denselben Abmessungen wie dieses [Size](../../com.aspose.drawing/size) ist. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese [Size](../../com.aspose.drawing/size)-Struktur zurück. |
| [toString()](#toString--) |  |
| [equals(Size other)](#equals-com.aspose.drawing.Size-) | Prüft, ob eine andere [Size](../../com.aspose.drawing/size)-Struktur dieselbe Größe wie diese [Size](../../com.aspose.drawing/size)-Struktur hat. |
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


Initialisiert eine neue Instanz der [Size](../../com.aspose.drawing/size)-Struktur aus dem angegebenen [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Der [Point](../../com.aspose.drawing/point), von dem aus dieses [Size](../../com.aspose.drawing/size) initialisiert wird. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Initialisiert eine neue Instanz der [Size](../../com.aspose.drawing/size)-Struktur aus den angegebenen Abmessungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | int | Die Breitenkomponente des neuen [Size](../../com.aspose.drawing/size). |
| height | int | Die Höhenkomponente des neuen [Size](../../com.aspose.drawing/size). |

### to_SizeF(Size p) {#to-SizeF-com.aspose.drawing.Size-}
```
public static SizeF to_SizeF(Size p)
```


Konvertiert das angegebene [Size](../../com.aspose.drawing/size) in ein [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| p | [Size](../../com.aspose.drawing/size) | Das zu konvertierende [Size](../../com.aspose.drawing/size). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - The [SizeF](../../com.aspose.drawing/sizef) structure to which this operator converts.
### op_Addition(Size sz1, Size sz2) {#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Addition(Size sz1, Size sz2)
```


Addiert die Breite und Höhe einer [Size](../../com.aspose.drawing/size)-Struktur zur Breite und Höhe einer anderen [Size](../../com.aspose.drawing/size)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Das erste [Size](../../com.aspose.drawing/size), das hinzugefügt werden soll. |
| sz2 | [Size](../../com.aspose.drawing/size) | Das zweite [Size](../../com.aspose.drawing/size), das hinzugefügt werden soll. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(Size sz1, Size sz2) {#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Subtraction(Size sz1, Size sz2)
```


Subtrahiert die Breite und Höhe einer [Size](../../com.aspose.drawing/size)-Struktur von der Breite und Höhe einer anderen [Size](../../com.aspose.drawing/size)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Die [Size](../../com.aspose.drawing/size)-Struktur auf der linken Seite des Subtraktionsoperators. |
| sz2 | [Size](../../com.aspose.drawing/size) | Die [Size](../../com.aspose.drawing/size)-Struktur auf der rechten Seite des Subtraktionsoperators. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the subtraction operation.
### op_Multiply(int left, Size right) {#op-Multiply-int-com.aspose.drawing.Size-}
```
public static Size op_Multiply(int left, Size right)
```


Multipliziert ein [Size](../../com.aspose.drawing/size) mit einem `int` und erzeugt ein [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| links | int | Multiplikator vom Typ `int`. |
| right | [Size](../../com.aspose.drawing/size) | Multiplikand vom Typ [Size](../../com.aspose.drawing/size). |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Multiply(Size left, int right) {#op-Multiply-com.aspose.drawing.Size-int-}
```
public static Size op_Multiply(Size left, int right)
```


Multipliziert [Size](../../com.aspose.drawing/size) mit einem `int` und erzeugt ein [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Multiplikand vom Typ [Size](../../com.aspose.drawing/size). |
| rechts | int | Multiplikator vom Typ `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Division(Size left, int right) {#op-Division-com.aspose.drawing.Size-int-}
```
public static Size op_Division(Size left, int right)
```


Dividiert [Size](../../com.aspose.drawing/size) durch einen `int` und erzeugt ein [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividende vom Typ [Size](../../com.aspose.drawing/size). |
| rechts | int | Divisor vom Typ `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Result of type [Size](../../com.aspose.drawing/size).
### op_Multiply(float left, Size right) {#op-Multiply-float-com.aspose.drawing.Size-}
```
public static SizeF op_Multiply(float left, Size right)
```


Multipliziert [Size](../../com.aspose.drawing/size) mit einem `float` und erzeugt ein [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| links | float | Multiplikator vom Typ `float`. |
| right | [Size](../../com.aspose.drawing/size) | Multiplikand vom Typ [Size](../../com.aspose.drawing/size). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(Size left, float right) {#op-Multiply-com.aspose.drawing.Size-float-}
```
public static SizeF op_Multiply(Size left, float right)
```


Multipliziert [Size](../../com.aspose.drawing/size) mit einem `float` und erzeugt ein [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Multiplikand vom Typ [Size](../../com.aspose.drawing/size). |
| rechts | float | Multiplikator vom Typ `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(Size left, float right) {#op-Division-com.aspose.drawing.Size-float-}
```
public static SizeF op_Division(Size left, float right)
```


Dividiert [Size](../../com.aspose.drawing/size) durch einen `float` und erzeugt [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividende vom Typ [Size](../../com.aspose.drawing/size). |
| rechts | float | Divisor vom Typ `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### op_Equality(Size sz1, Size sz2) {#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Equality(Size sz1, Size sz2)
```


Prüft, ob zwei [Size](../../com.aspose.drawing/size)-Strukturen gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Die [Size](../../com.aspose.drawing/size)-Struktur auf der linken Seite des Gleichheitsoperators. |
| sz2 | [Size](../../com.aspose.drawing/size) | Die [Size](../../com.aspose.drawing/size)-Struktur auf der rechten Seite des Gleichheitsoperators. |

**Returns:**
boolean - true, wenn `sz1` und `sz2` gleiche Breite und Höhe haben; sonst false.
### op_Inequality(Size sz1, Size sz2) {#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Inequality(Size sz1, Size sz2)
```


Prüft, ob zwei [Size](../../com.aspose.drawing/size)-Strukturen unterschiedlich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Die [Size](../../com.aspose.drawing/size)-Struktur auf der linken Seite des Ungleichheitsoperators. |
| sz2 | [Size](../../com.aspose.drawing/size) | Die [Size](../../com.aspose.drawing/size)-Struktur auf der rechten Seite des Ungleichheitsoperators. |

**Returns:**
boolean - true, wenn `sz1` und `sz2` sich entweder in der Breite oder Höhe unterscheiden; false, wenn `sz1` und `sz2` gleich sind.
### to_Point(Size size) {#to-Point-com.aspose.drawing.Size-}
```
public static Point to_Point(Size size)
```


Konvertiert das angegebene [Size](../../com.aspose.drawing/size) in ein [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | Das zu konvertierende [Size](../../com.aspose.drawing/size). |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) structure to which this operator converts.
### add(Size sz1, Size sz2) {#add-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size add(Size sz1, Size sz2)
```


Addiert die Breite und Höhe einer [Size](../../com.aspose.drawing/size)-Struktur zur Breite und Höhe einer anderen [Size](../../com.aspose.drawing/size)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Das erste [Size](../../com.aspose.drawing/size), das hinzugefügt werden soll. |
| sz2 | [Size](../../com.aspose.drawing/size) | Das zweite [Size](../../com.aspose.drawing/size), das hinzugefügt werden soll. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### ceiling(SizeF value) {#ceiling-com.aspose.drawing.SizeF-}
```
public static Size ceiling(SizeF value)
```


Konvertiert die angegebene [SizeF](../../com.aspose.drawing/sizef)-Struktur in eine [Size](../../com.aspose.drawing/size)-Struktur, indem die Werte der [Size](../../com.aspose.drawing/size)-Struktur auf die nächsthöheren Ganzzahlen gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | Die [SizeF](../../com.aspose.drawing/sizef)-Struktur zum Konvertieren. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### subtract(Size sz1, Size sz2) {#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size subtract(Size sz1, Size sz2)
```


Subtrahiert die Breite und Höhe einer [Size](../../com.aspose.drawing/size)-Struktur von der Breite und Höhe einer anderen [Size](../../com.aspose.drawing/size)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Die [Size](../../com.aspose.drawing/size)-Struktur auf der linken Seite des Subtraktionsoperators. |
| sz2 | [Size](../../com.aspose.drawing/size) | Die [Size](../../com.aspose.drawing/size)-Struktur auf der rechten Seite des Subtraktionsoperators. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) that is a result of the subtraction operation.
### truncate(SizeF value) {#truncate-com.aspose.drawing.SizeF-}
```
public static Size truncate(SizeF value)
```


Konvertiert die angegebene [SizeF](../../com.aspose.drawing/sizef)-Struktur in eine [Size](../../com.aspose.drawing/size)-Struktur, indem die Werte der [SizeF](../../com.aspose.drawing/sizef)-Struktur auf die nächstniedrigeren Ganzzahlen abgeschnitten werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | Die [SizeF](../../com.aspose.drawing/sizef)-Struktur zum Konvertieren. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### round(SizeF value) {#round-com.aspose.drawing.SizeF-}
```
public static Size round(SizeF value)
```


Konvertiert die angegebene [SizeF](../../com.aspose.drawing/sizef)-Struktur in eine [Size](../../com.aspose.drawing/size)-Struktur, indem die Werte der [SizeF](../../com.aspose.drawing/sizef)-Struktur auf die nächsten Ganzzahlen gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | Die [SizeF](../../com.aspose.drawing/sizef)-Struktur zum Konvertieren. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Gibt einen Wert zurück, der angibt, ob dieses [Size](../../com.aspose.drawing/size) Breite und Höhe von 0 hat.

**Returns:**
boolean - ein Wert, der angibt, ob dieses [Size](../../com.aspose.drawing/size) Breite und Höhe von 0 hat.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gibt die horizontale Komponente dieses [Size](../../com.aspose.drawing/size) zurück.

**Returns:**
int - die horizontale Komponente dieses [Size](../../com.aspose.drawing/size).
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Setzt die horizontale Komponente dieses [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | die horizontale Komponente dieses [Size](../../com.aspose.drawing/size). |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gibt die vertikale Komponente dieses [Size](../../com.aspose.drawing/size) zurück.

**Returns:**
int - die vertikale Komponente dieses [Size](../../com.aspose.drawing/size).
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Setzt die vertikale Komponente dieses [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | die vertikale Komponente dieses [Size](../../com.aspose.drawing/size). |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Prüft, ob das angegebene Objekt ein [Size](../../com.aspose.drawing/size) mit denselben Abmessungen wie dieses [Size](../../com.aspose.drawing/size) ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt zum Testen. |

**Returns:**
boolean - true, wenn `obj` ein [Size](../../com.aspose.drawing/size) ist und dieselbe Breite und Höhe wie dieses [Size](../../com.aspose.drawing/size) hat; sonst false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese [Size](../../com.aspose.drawing/size)-Struktur zurück.

**Returns:**
int - ein ganzzahliger Wert, der einen Hashwert für diese [Size](../../com.aspose.drawing/size)-Struktur angibt.
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


Prüft, ob eine andere [Size](../../com.aspose.drawing/size)-Struktur dieselbe Größe wie diese [Size](../../com.aspose.drawing/size)-Struktur hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [Size](../../com.aspose.drawing/size) | Andere Größe zum Testen |

**Returns:**
boolean - Diese Methode gibt `true` zurück, wenn die andere [Size](../../com.aspose.drawing/size)-Struktur und ihre Width- und Height-Eigenschaften den entsprechenden Eigenschaften dieser [Size](../../com.aspose.drawing/size)-Struktur entsprechen; sonst `false`.
### CloneTo(Size that) {#CloneTo-com.aspose.drawing.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
