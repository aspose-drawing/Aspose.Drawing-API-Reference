---
title: SizeF
second_title: Aspose.Drawing für Java API-Referenz
description: Speichert ein geordnetes Paar von Fließkommazahlen, typischerweise die Breite und Höhe eines Rechtecks.
type: docs
weight: 43
url: /de/java/com.aspose.drawing/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class SizeF extends Struct<SizeF> implements System.IEquatable<SizeF>, Cloneable
```

Speichert ein geordnetes Paar von Gleitkommazahlen, typischerweise die Breite und Höhe eines Rechtecks.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(float width, float height)](#SizeF-float-float-) | Initialisiert eine neue Instanz der SizeF-Struktur mit den angegebenen Abmessungen. |
| [SizeF(PointF pt)](#SizeF-com.aspose.drawing.PointF-) | Initialisiert eine neue Instanz der [SizeF](../../com.aspose.drawing/sizef)-Struktur. |
| [SizeF(SizeF size)](#SizeF-com.aspose.drawing.SizeF-) | Initialisiert eine neue Instanz der [SizeF](../../com.aspose.drawing/sizef)-Struktur. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [op_Equality(SizeF sz1, SizeF sz2)](#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Prüft, ob zwei [SizeF](../../com.aspose.drawing/sizef)-Strukturen gleich sind. |
| [op_Inequality(SizeF sz1, SizeF sz2)](#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Prüft, ob zwei [SizeF](../../com.aspose.drawing/sizef)-Strukturen unterschiedlich sind. |
| [add(SizeF sz1, SizeF sz2)](#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Addiert die Breite und Höhe einer [SizeF](../../com.aspose.drawing/sizef)-Struktur zur Breite und Höhe einer anderen [SizeF](../../com.aspose.drawing/sizef)-Struktur. |
| [subtract(SizeF sz1, SizeF sz2)](#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Subtrahiert die Breite und Höhe einer [SizeF](../../com.aspose.drawing/sizef)-Struktur von der Breite und Höhe einer anderen [SizeF](../../com.aspose.drawing/sizef)-Struktur. |
| [op_Addition(SizeF sz1, SizeF sz2)](#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Addiert die Breite und Höhe einer [SizeF](../../com.aspose.drawing/sizef)-Struktur zur Breite und Höhe einer anderen [SizeF](../../com.aspose.drawing/sizef)-Struktur. |
| [op_Subtraction(SizeF sz1, SizeF sz2)](#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Subtrahiert die Breite und Höhe einer [SizeF](../../com.aspose.drawing/sizef)-Struktur von der Breite und Höhe einer anderen [SizeF](../../com.aspose.drawing/sizef)-Struktur. |
| [op_Multiply(float left, SizeF right)](#op-Multiply-float-com.aspose.drawing.SizeF-) | Multipliziert [SizeF](../../com.aspose.drawing/sizef) mit einem `float` und erzeugt [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(SizeF left, float right)](#op-Multiply-com.aspose.drawing.SizeF-float-) | Multipliziert [SizeF](../../com.aspose.drawing/sizef) mit einem `float` und erzeugt [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(SizeF left, float right)](#op-Division-com.aspose.drawing.SizeF-float-) | Dividiert [SizeF](../../com.aspose.drawing/sizef) durch einen `float` und erzeugt [SizeF](../../com.aspose.drawing/sizef). |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Gibt einen Wert zurück, der angibt, ob diese [SizeF](../../com.aspose.drawing/sizef)-Struktur eine Breite und Höhe von Null hat. |
| [getWidth()](#getWidth--) | Gibt die horizontale Komponente dieser SizeF-Struktur zurück. |
| [setWidth(float value)](#setWidth-float-) | Setzt die horizontale Komponente dieser SizeF-Struktur. |
| [getHeight()](#getHeight--) | Gibt die vertikale Komponente dieser SizeF-Struktur zurück. |
| [setHeight(float value)](#setHeight-float-) | Setzt die vertikale Komponente dieser SizeF-Struktur. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese [SizeF](../../com.aspose.drawing/sizef)-Struktur zurück. |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft, ob das angegebene Objekt eine [SizeF](../../com.aspose.drawing/sizef)-Struktur mit denselben Abmessungen wie diese [SizeF](../../com.aspose.drawing/sizef)-Struktur ist. |
| [toSize()](#toSize--) | Konvertiert eine [SizeF](../../com.aspose.drawing/sizef)-Struktur in eine [Size](../../com.aspose.drawing/size)-Struktur. |
| [toPointF()](#toPointF--) | Konvertiert eine [SizeF](../../com.aspose.drawing/sizef)-Struktur in eine [PointF](../../com.aspose.drawing/pointf)-Struktur. |
| [equals(SizeF other)](#equals-com.aspose.drawing.SizeF-) | Prüft, ob eine andere [SizeF](../../com.aspose.drawing/sizef)-Struktur dieselbe Größe wie diese [SizeF](../../com.aspose.drawing/sizef)-Struktur hat. |
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


Initialisiert eine neue Instanz der SizeF-Struktur mit den angegebenen Abmessungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | float | Die Breitenkomponente der neuen SizeF-Struktur. |
| Höhe | float | Die Höhenkomponente der neuen SizeF-Struktur. |

### SizeF(PointF pt) {#SizeF-com.aspose.drawing.PointF-}
```
public SizeF(PointF pt)
```


Initialisiert eine neue Instanz der [SizeF](../../com.aspose.drawing/sizef)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | Die [PointF](../../com.aspose.drawing/pointf)-Struktur, aus der diese [SizeF](../../com.aspose.drawing/sizef)-Struktur initialisiert wird. |

### SizeF(SizeF size) {#SizeF-com.aspose.drawing.SizeF-}
```
public SizeF(SizeF size)
```


Initialisiert eine neue Instanz der [SizeF](../../com.aspose.drawing/sizef)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | Die [SizeF](../../com.aspose.drawing/sizef)-Struktur, aus der die neue [SizeF](../../com.aspose.drawing/sizef)-Struktur erstellt wird. |

### op_Equality(SizeF sz1, SizeF sz2) {#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Equality(SizeF sz1, SizeF sz2)
```


Prüft, ob zwei [SizeF](../../com.aspose.drawing/sizef)-Strukturen gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Die [SizeF](../../com.aspose.drawing/sizef)-Struktur auf der linken Seite des Gleichheitsoperators. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Die [SizeF](../../com.aspose.drawing/sizef)-Struktur auf der rechten Seite des Gleichheitsoperators. |

**Returns:**
boolean - Dieser Operator gibt true zurück, wenn `sz1` und `sz2` gleiche Breite und Höhe haben; andernfalls false.
### op_Inequality(SizeF sz1, SizeF sz2) {#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Inequality(SizeF sz1, SizeF sz2)
```


Prüft, ob zwei [SizeF](../../com.aspose.drawing/sizef)-Strukturen unterschiedlich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Die [SizeF](../../com.aspose.drawing/sizef)-Struktur auf der linken Seite des Ungleichheitsoperators. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Die [SizeF](../../com.aspose.drawing/sizef)-Struktur auf der rechten Seite des Ungleichheitsoperators. |

**Returns:**
boolean - Dieser Operator gibt true zurück, wenn `sz1` und `sz2` entweder in der Breite oder Höhe unterschiedlich sind; false, wenn `sz1` und `sz2` gleich sind.
### add(SizeF sz1, SizeF sz2) {#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF add(SizeF sz1, SizeF sz2)
```


Addiert die Breite und Höhe einer [SizeF](../../com.aspose.drawing/sizef)-Struktur zur Breite und Höhe einer anderen [SizeF](../../com.aspose.drawing/sizef)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Die erste [SizeF](../../com.aspose.drawing/sizef)-Struktur zum Hinzufügen. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Die zweite [SizeF](../../com.aspose.drawing/sizef)-Struktur zum Hinzufügen. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is the result of the addition operation.
### subtract(SizeF sz1, SizeF sz2) {#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF subtract(SizeF sz1, SizeF sz2)
```


Subtrahiert die Breite und Höhe einer [SizeF](../../com.aspose.drawing/sizef)-Struktur von der Breite und Höhe einer anderen [SizeF](../../com.aspose.drawing/sizef)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Die [SizeF](../../com.aspose.drawing/sizef)-Struktur auf der linken Seite des Subtraktionsoperators. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Die [SizeF](../../com.aspose.drawing/sizef) Struktur auf der rechten Seite des Subtraktionsoperators. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is a result of the subtraction operation.
### op_Addition(SizeF sz1, SizeF sz2) {#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Addition(SizeF sz1, SizeF sz2)
```


Addiert die Breite und Höhe einer [SizeF](../../com.aspose.drawing/sizef)-Struktur zur Breite und Höhe einer anderen [SizeF](../../com.aspose.drawing/sizef)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Die erste [SizeF](../../com.aspose.drawing/sizef)-Struktur zum Hinzufügen. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Die zweite [SizeF](../../com.aspose.drawing/sizef)-Struktur zum Hinzufügen. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(SizeF sz1, SizeF sz2) {#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Subtraction(SizeF sz1, SizeF sz2)
```


Subtrahiert die Breite und Höhe einer [SizeF](../../com.aspose.drawing/sizef)-Struktur von der Breite und Höhe einer anderen [SizeF](../../com.aspose.drawing/sizef)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Die [SizeF](../../com.aspose.drawing/sizef)-Struktur auf der linken Seite des Subtraktionsoperators. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Die [SizeF](../../com.aspose.drawing/sizef) Struktur auf der rechten Seite des Subtraktionsoperators. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that is the result of the subtraction operation.
### op_Multiply(float left, SizeF right) {#op-Multiply-float-com.aspose.drawing.SizeF-}
```
public static SizeF op_Multiply(float left, SizeF right)
```


Multipliziert [SizeF](../../com.aspose.drawing/sizef) mit einem `float` und erzeugt [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| links | float | Multiplikator vom Typ `float`. |
| right | [SizeF](../../com.aspose.drawing/sizef) | Multiplikand vom Typ [SizeF](../../com.aspose.drawing/sizef). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(SizeF left, float right) {#op-Multiply-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Multiply(SizeF left, float right)
```


Multipliziert [SizeF](../../com.aspose.drawing/sizef) mit einem `float` und erzeugt [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Multiplikand vom Typ [SizeF](../../com.aspose.drawing/sizef). |
| rechts | float | Multiplikator vom Typ `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(SizeF left, float right) {#op-Division-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Division(SizeF left, float right)
```


Dividiert [SizeF](../../com.aspose.drawing/sizef) durch einen `float` und erzeugt [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Dividende vom Typ [SizeF](../../com.aspose.drawing/sizef). |
| rechts | float | Divisor vom Typ `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### to_PointF(SizeF size) {#to-PointF-com.aspose.drawing.SizeF-}
```
public static PointF to_PointF(SizeF size)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Gibt einen Wert zurück, der angibt, ob diese [SizeF](../../com.aspose.drawing/sizef)-Struktur eine Breite und Höhe von Null hat.

**Returns:**
boolean – ein Wert, der angibt, ob diese [SizeF](../../com.aspose.drawing/sizef)-Struktur eine Breite und Höhe von Null hat.
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Gibt die horizontale Komponente dieser SizeF-Struktur zurück.

**Returns:**
float – die horizontale Komponente dieser SizeF-Struktur.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Setzt die horizontale Komponente dieser SizeF-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | die horizontale Komponente dieser SizeF-Struktur. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Gibt die vertikale Komponente dieser SizeF-Struktur zurück.

**Returns:**
float – die vertikale Komponente dieser SizeF-Struktur.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Setzt die vertikale Komponente dieser SizeF-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | die vertikale Komponente dieser SizeF-Struktur. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese [SizeF](../../com.aspose.drawing/sizef)-Struktur zurück.

**Returns:**
int – ein ganzzahliger Wert, der einen Hash-Wert für diese [SizeF](../../com.aspose.drawing/sizef)-Struktur angibt.
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


Prüft, ob das angegebene Objekt eine [SizeF](../../com.aspose.drawing/sizef)-Struktur mit denselben Abmessungen wie diese [SizeF](../../com.aspose.drawing/sizef)-Struktur ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt zum Testen. |

**Returns:**
boolean – Diese Methode gibt `true` zurück, wenn obj ein [SizeF](../../com.aspose.drawing/sizef) ist und dieselbe Breite und Höhe wie dieses SizeF hat; andernfalls `false`.
### toSize() {#toSize--}
```
public final Size toSize()
```


Konvertiert eine [SizeF](../../com.aspose.drawing/sizef)-Struktur in eine [Size](../../com.aspose.drawing/size)-Struktur.

**Returns:**
[Size](../../com.aspose.drawing/size) - Returns a [Size](../../com.aspose.drawing/size) structure.
### toPointF() {#toPointF--}
```
public final PointF toPointF()
```


Konvertiert eine [SizeF](../../com.aspose.drawing/sizef)-Struktur in eine [PointF](../../com.aspose.drawing/pointf)-Struktur.

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - Returns a [PointF](../../com.aspose.drawing/pointf) structure.
### equals(SizeF other) {#equals-com.aspose.drawing.SizeF-}
```
public final boolean equals(SizeF other)
```


Prüft, ob eine andere [SizeF](../../com.aspose.drawing/sizef)-Struktur dieselbe Größe wie diese [SizeF](../../com.aspose.drawing/sizef)-Struktur hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [SizeF](../../com.aspose.drawing/sizef) | Andere Größe zum Testen |

**Returns:**
boolean – Diese Methode gibt `true` zurück, wenn die andere [SizeF](../../com.aspose.drawing/sizef)-Struktur und deren Breiten‑ und Höhen‑Eigenschaften den entsprechenden Eigenschaften dieser [SizeF](../../com.aspose.drawing/sizef)-Struktur entsprechen; andernfalls `false`.
### CloneTo(SizeF that) {#CloneTo-com.aspose.drawing.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
