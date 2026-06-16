---
title: CharacterRange
second_title: Aspose.Drawing für Java API-Referenz
description: Gibt einen Bereich von Zeichenpositionen innerhalb einer Zeichenkette an.
type: docs
weight: 13
url: /de/java/com.aspose.drawing/characterrange/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class CharacterRange extends Struct<CharacterRange> implements Cloneable
```

Gibt einen Bereich von Zeichenpositionen innerhalb einer Zeichenkette an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CharacterRange()](#CharacterRange--) |  |
| [CharacterRange(int first, int length)](#CharacterRange-int-int-) | Initialisiert eine neue Instanz der [CharacterRange](../../com.aspose.drawing/characterrange) Struktur, die einen Bereich von Zeichenpositionen innerhalb einer Zeichenkette angibt. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFirst()](#getFirst--) | Liest oder setzt die Position im String des ersten Zeichens dieses [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setFirst(int value)](#setFirst-int-) | Liest oder setzt die Position im String des ersten Zeichens dieses [CharacterRange](../../com.aspose.drawing/characterrange). |
| [getLength()](#getLength--) | Liest oder setzt die Anzahl der Positionen in diesem [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setLength(int value)](#setLength-int-) | Liest oder setzt die Anzahl der Positionen in diesem [CharacterRange](../../com.aspose.drawing/characterrange). |
| [op_Equality(CharacterRange cr1, CharacterRange cr2)](#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Vergleicht zwei [CharacterRange](../../com.aspose.drawing/characterrange) Objekte. |
| [op_Inequality(CharacterRange cr1, CharacterRange cr2)](#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Vergleicht zwei [CharacterRange](../../com.aspose.drawing/characterrange) Objekte. |
| [equals(Object obj)](#equals-java.lang.Object-) | Liest einen Wert, der angibt, ob dieses Objekt dem angegebenen Objekt entspricht. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
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


Initialisiert eine neue Instanz der [CharacterRange](../../com.aspose.drawing/characterrange) Struktur, die einen Bereich von Zeichenpositionen innerhalb einer Zeichenkette angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| first | int | Die Position des ersten Zeichens im Bereich. Zum Beispiel, wenn First auf 0 gesetzt ist, ist die erste Position des Bereichs Position 0 im String. |
| length | int | Die Anzahl der Positionen im Bereich. |

### getFirst() {#getFirst--}
```
public final int getFirst()
```


Liest oder setzt die Position im String des ersten Zeichens dieses [CharacterRange](../../com.aspose.drawing/characterrange).

Wert: Die erste Position dieses [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setFirst(int value) {#setFirst-int-}
```
public final void setFirst(int value)
```


Liest oder setzt die Position im String des ersten Zeichens dieses [CharacterRange](../../com.aspose.drawing/characterrange).

Wert: Die erste Position dieses [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getLength() {#getLength--}
```
public final int getLength()
```


Liest oder setzt die Anzahl der Positionen in diesem [CharacterRange](../../com.aspose.drawing/characterrange).

Wert: Die Anzahl der Positionen in diesem [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


Liest oder setzt die Anzahl der Positionen in diesem [CharacterRange](../../com.aspose.drawing/characterrange).

Wert: Die Anzahl der Positionen in diesem [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### op_Equality(CharacterRange cr1, CharacterRange cr2) {#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Equality(CharacterRange cr1, CharacterRange cr2)
```


Vergleicht zwei [CharacterRange](../../com.aspose.drawing/characterrange) Objekte. Liest einen Wert, der angibt, ob die First- und Length-Werte der beiden [CharacterRange](../../com.aspose.drawing/characterrange) Objekte gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Ein [CharacterRange](../../com.aspose.drawing/characterrange) zum Vergleich auf Gleichheit. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Ein [CharacterRange](../../com.aspose.drawing/characterrange) zum Vergleich auf Gleichheit. |

**Returns:**
boolean - `true`, um anzuzeigen, dass die beiden CharacterRange-Objekte dieselben First- und Length-Werte haben; andernfalls `false`.
### op_Inequality(CharacterRange cr1, CharacterRange cr2) {#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Inequality(CharacterRange cr1, CharacterRange cr2)
```


Vergleicht zwei [CharacterRange](../../com.aspose.drawing/characterrange) Objekte. Liest einen Wert, der angibt, ob die First- oder Length-Werte der beiden [CharacterRange](../../com.aspose.drawing/characterrange) Objekte nicht gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Ein [CharacterRange](../../com.aspose.drawing/characterrange) zum Vergleich auf Ungleichheit. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Ein [CharacterRange](../../com.aspose.drawing/characterrange) zum Vergleich auf Ungleichheit. |

**Returns:**
boolean - `true`, um anzuzeigen, dass entweder die First- oder Length-Werte der beiden CharacterRange-Objekte unterschiedlich sind; andernfalls `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Liest einen Wert, der angibt, ob dieses Objekt dem angegebenen Objekt entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt, mit dem auf Gleichheit verglichen werden soll.. |

**Returns:**
boolean - `true`, um anzugeben, dass das angegebene Objekt eine Instanz mit demselben First- und Length-Wert wie diese Instanz ist; andernfalls `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32‑Bit vorzeichenbehafteter Integer, der den Hash‑Code für diese Instanz darstellt.
### CloneTo(CharacterRange that) {#CloneTo-com.aspose.drawing.CharacterRange-}
```
public void CloneTo(CharacterRange that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
