---
title: RectangleF
second_title: Aspose.Drawing für Java API-Referenz
description: Speichert ein Set von vier Gleitkommazahlen, die den Ort und die Größe eines Rechtecks darstellen.
type: docs
weight: 39
url: /de/java/com.aspose.drawing/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class RectangleF extends Struct<RectangleF> implements System.IEquatable<RectangleF>, Cloneable
```

Speichert einen Satz von vier Gleitkommazahlen, die den Ort und die Größe eines Rechtecks darstellen. Für fortgeschrittenere Regionsfunktionen verwenden Sie ein Region‑Objekt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | Initialisiert eine neue Instanz der RectangleF‑Struktur mit dem angegebenen Ort und der angegebenen Größe. |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Initialisiert eine neue Instanz der RectangleF‑Struktur mit dem angegebenen Ort und der angegebenen Größe. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | Erstellt ein neues Rechteck aus zwei Punkten. |
| [to_RectangleF(Rectangle r)](#to-RectangleF-com.aspose.drawing.Rectangle-) | Konvertiert die angegebene Rectangle‑Struktur in eine RectangleF‑Struktur. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Prüft, ob zwei [RectangleF](../../com.aspose.drawing/rectanglef) Strukturen gleichen Ort und gleiche Größe haben. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Prüft, ob sich zwei [RectangleF](../../com.aspose.drawing/rectanglef) Strukturen im Ort oder in der Größe unterscheiden. |
| [fromLTRB(float left, float top, float right, float bottom)](#fromLTRB-float-float-float-float-) | Erstellt eine RectangleF‑Struktur mit der oberen linken Ecke und der unteren rechten Ecke an den angegebenen Positionen. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.drawing.RectangleF-float-float-) | Erstellt und gibt eine aufgeblähte Kopie der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef) Struktur zurück. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Gibt eine [RectangleF](../../com.aspose.drawing/rectanglef) Struktur zurück, die die Schnittmenge zweier Rechtecke darstellt. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Erstellt das kleinste mögliche dritte Rechteck, das beide Rechtecke, die eine Vereinigung bilden, enthalten kann. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Ermittelt einen Wert, der angibt, ob die Eigenschaft `RectangleF.Width` oder `RectangleF.Height` dieses [RectangleF](../../com.aspose.drawing/rectanglef) den Wert 0 hat. |
| [getX()](#getX--) | Ermittelt die x‑Koordinate der oberen linken Ecke dieser RectangleF‑Struktur. |
| [setX(float value)](#setX-float-) | Setzt die x‑Koordinate der oberen linken Ecke dieser RectangleF‑Struktur. |
| [getY()](#getY--) | Ermittelt die x‑Koordinate der oberen linken Ecke dieser RectangleF‑Struktur. |
| [setY(float value)](#setY-float-) | Setzt die x‑Koordinate der oberen linken Ecke dieser RectangleF‑Struktur. |
| [getLocation()](#getLocation--) | Ermittelt die Koordinaten der oberen linken Ecke dieser [RectangleF](../../com.aspose.drawing/rectanglef) Struktur. |
| [setLocation(PointF value)](#setLocation-com.aspose.drawing.PointF-) | Legt die Koordinaten der oberen linken Ecke dieser [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur fest. |
| [getWidth()](#getWidth--) | Ermittelt die Breite dieser RectangleF-Struktur. |
| [setWidth(float value)](#setWidth-float-) | Legt die Breite dieser RectangleF-Struktur fest. |
| [getHeight()](#getHeight--) | Ermittelt die Höhe dieser RectangleF-Struktur. |
| [setHeight(float value)](#setHeight-float-) | Legt die Höhe dieser RectangleF-Struktur fest. |
| [getSize()](#getSize--) | Ermittelt die Größe dieser [RectangleF](../../com.aspose.drawing/rectanglef). |
| [setSize(SizeF value)](#setSize-com.aspose.drawing.SizeF-) | Legt die Größe dieser [RectangleF](../../com.aspose.drawing/rectanglef) fest. |
| [getLeft()](#getLeft--) | Ermittelt die x-Koordinate der linken Kante dieser RectangleF-Struktur. |
| [getTop()](#getTop--) | Ermittelt die y-Koordinate der oberen Kante dieser RectangleF-Struktur. |
| [getRight()](#getRight--) | Ermittelt die x-Koordinate, die die Summe von X und Breite dieser RectangleF-Struktur ist. |
| [getBottom()](#getBottom--) | Ermittelt die y-Koordinate, die die Summe von Y und Höhe dieser RectangleF-Struktur ist. |
| [toString()](#toString--) |  |
| [inflate(float x, float y)](#inflate-float-float-) | Vergrößert diese [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur um den angegebenen Betrag. |
| [inflate(SizeF size)](#inflate-com.aspose.drawing.SizeF-) | Vergrößert dieses [RectangleF](../../com.aspose.drawing/rectanglef) um den angegebenen Betrag. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Ersetzt diese [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur durch die Schnittmenge aus ihr selbst und der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.drawing.RectangleF-) | Bestimmt, ob dieses Rechteck mit `rect` schneidet. |
| [offset(PointF pos)](#offset-com.aspose.drawing.PointF-) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [offset(float x, float y)](#offset-float-float-) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [contains(float x, float y)](#contains-float-float-) | Bestimmt, ob der angegebene Punkt innerhalb dieser [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur liegt. |
| [contains(PointF pt)](#contains-com.aspose.drawing.PointF-) | Bestimmt, ob der angegebene Punkt innerhalb dieser [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur liegt. |
| [contains(RectangleF rect)](#contains-com.aspose.drawing.RectangleF-) | Bestimmt, ob der durch `rect` dargestellte rechteckige Bereich vollständig innerhalb dieser [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur enthalten ist. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
| [equals(RectangleF other)](#equals-com.aspose.drawing.RectangleF-) | Prüft, ob eine andere [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur dieselbe Position und Größe wie diese [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur hat. |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.drawing.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Initialisiert eine neue Instanz der RectangleF‑Struktur mit dem angegebenen Ort und der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| location | [PointF](../../com.aspose.drawing/pointf) | Ein PointF, der die obere linke Ecke des rechteckigen Bereichs darstellt. |
| size | [SizeF](../../com.aspose.drawing/sizef) | Ein SizeF, der die Breite und Höhe des rechteckigen Bereichs darstellt. |

### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Initialisiert eine neue Instanz der RectangleF‑Struktur mit dem angegebenen Ort und der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate der oberen linken Ecke des Rechtecks. |
| y | float | Die y‑Koordinate der oberen linken Ecke des Rechtecks. |
| Breite | float | Die Breite des Rechtecks. |
| Höhe | float | Die Höhe des Rechtecks. |

### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Erstellt ein neues Rechteck aus zwei Punkten. Das erstellte Rechteck wird normalisiert, sodass (left,top) kleiner ist als (right,bottom).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | Der erste Punkt. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | Der zweite Punkt. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A newly created rectangle.
### to_RectangleF(Rectangle r) {#to-RectangleF-com.aspose.drawing.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle r)
```


Konvertiert die angegebene Rectangle‑Struktur in eine RectangleF‑Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| r | [Rectangle](../../com.aspose.drawing/rectangle) | Die Rectangle‑Struktur zum Konvertieren. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The RectangleF structure that is converted from the specified Rectangle structure.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Prüft, ob zwei [RectangleF](../../com.aspose.drawing/rectanglef) Strukturen gleichen Ort und gleiche Größe haben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | Die [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur, die links vom Gleichheitsoperator steht. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | Die [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur, die rechts vom Gleichheitsoperator steht. |

**Returns:**
boolean - Dieser Operator gibt true zurück, wenn die beiden angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Strukturen gleiche `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` und `RectangleF.Height` Eigenschaften haben.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Prüft, ob sich zwei [RectangleF](../../com.aspose.drawing/rectanglef) Strukturen im Ort oder in der Größe unterscheiden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | Die [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur, die links vom Ungleichheitsoperator steht. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | Die [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur, die rechts vom Ungleichheitsoperator steht. |

**Returns:**
boolean - Dieser Operator gibt true zurück, wenn irgendeine der `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` oder `RectangleF.Height` Eigenschaften der beiden [Rectangle](../../com.aspose.drawing/rectangle)-Strukturen ungleich ist; andernfalls false.
### fromLTRB(float left, float top, float right, float bottom) {#fromLTRB-float-float-float-float-}
```
public static RectangleF fromLTRB(float left, float top, float right, float bottom)
```


Erstellt eine RectangleF‑Struktur mit der oberen linken Ecke und der unteren rechten Ecke an den angegebenen Positionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| links | float | Die x‑Koordinate der oberen linken Ecke des rechteckigen Bereichs. |
| oben | float | Die y‑Koordinate der oberen linken Ecke des rechteckigen Bereichs. |
| rechts | float | Die x‑Koordinate der unteren rechten Ecke des rechteckigen Bereichs. |
| unten | float | Die y‑Koordinate der unteren rechten Ecke des rechteckigen Bereichs. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The new RectangleF that this method creates.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.drawing.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Erstellt und gibt eine aufgeblähte Kopie der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur zurück. Die Kopie wird um den angegebenen Betrag aufgebläht. Das ursprüngliche Rechteck bleibt unverändert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Die zu kopierende [RectangleF](../../com.aspose.drawing/rectanglef). Dieses Rechteck wird nicht verändert. |
| x | float | Der Betrag, um den die Kopie des Rechtecks horizontal aufgebläht wird. |
| y | float | Der Betrag, um die Kopie des Rechtecks vertikal zu vergrößern. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The inflated [RectangleF](../../com.aspose.drawing/rectanglef).
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Gibt eine [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur zurück, die die Schnittmenge zweier Rechtecke darstellt. Wenn es keine Schnittmenge gibt, wird ein leeres [RectangleF](../../com.aspose.drawing/rectanglef) zurückgegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Erstes Rechteck zum Schneiden. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Zweites Rechteck zum Schneiden. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Erstellt das kleinste mögliche dritte Rechteck, das beide Rechtecke, die eine Vereinigung bilden, enthalten kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Erstes Rechteck für die Vereinigung. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Zweites Rechteck für die Vereinigung. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure that contains both of the two rectangles that form the union.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Ermittelt einen Wert, der angibt, ob die Eigenschaft `RectangleF.Width` oder `RectangleF.Height` dieses [RectangleF](../../com.aspose.drawing/rectanglef) den Wert 0 hat.

**Returns:**
boolean - Diese Eigenschaft gibt true zurück, wenn die `RectangleF.Width`- oder `P:RectangleF.Height`-Eigenschaft dieses [RectangleF](../../com.aspose.drawing/rectanglef) den Wert 0 hat; andernfalls false.
### getX() {#getX--}
```
public final float getX()
```


Ermittelt die x‑Koordinate der oberen linken Ecke dieser RectangleF‑Struktur.

**Returns:**
float - die x‑Koordinate der oberen linken Ecke dieser RectangleF‑Struktur.
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Setzt die x‑Koordinate der oberen linken Ecke dieser RectangleF‑Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | die x‑Koordinate der oberen linken Ecke dieser RectangleF‑Struktur. |

### getY() {#getY--}
```
public final float getY()
```


Ermittelt die x‑Koordinate der oberen linken Ecke dieser RectangleF‑Struktur.

**Returns:**
float - die x‑Koordinate der oberen linken Ecke dieser RectangleF‑Struktur.
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Setzt die x‑Koordinate der oberen linken Ecke dieser RectangleF‑Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | die x‑Koordinate der oberen linken Ecke dieser RectangleF‑Struktur. |

### getLocation() {#getLocation--}
```
public final PointF getLocation()
```


Ermittelt die Koordinaten der oberen linken Ecke dieser [RectangleF](../../com.aspose.drawing/rectanglef) Struktur.

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - A [PointF](../../com.aspose.drawing/pointf) that represents the upper-left corner of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setLocation(PointF value) {#setLocation-com.aspose.drawing.PointF-}
```
public final void setLocation(PointF value)
```


Legt die Koordinaten der oberen linken Ecke dieser [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | die Koordinaten der oberen linken Ecke dieser [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur. |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Ermittelt die Breite dieser RectangleF-Struktur.

**Returns:**
float - die Breite dieser RectangleF‑Struktur.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Legt die Breite dieser RectangleF-Struktur fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | die Breite dieser RectangleF‑Struktur. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Ermittelt die Höhe dieser RectangleF-Struktur.

**Returns:**
float - die Höhe dieser RectangleF‑Struktur.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Legt die Höhe dieser RectangleF-Struktur fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | die Höhe dieser RectangleF‑Struktur. |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


Ermittelt die Größe dieser [RectangleF](../../com.aspose.drawing/rectanglef).

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that represents the width and height of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setSize(SizeF value) {#setSize-com.aspose.drawing.SizeF-}
```
public final void setSize(SizeF value)
```


Legt die Größe dieser [RectangleF](../../com.aspose.drawing/rectanglef) fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | die Größe dieses [RectangleF](../../com.aspose.drawing/rectanglef). |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


Ermittelt die x-Koordinate der linken Kante dieser RectangleF-Struktur.

**Returns:**
float - die x‑Koordinate der linken Kante dieser RectangleF‑Struktur.
### getTop() {#getTop--}
```
public final float getTop()
```


Ermittelt die y-Koordinate der oberen Kante dieser RectangleF-Struktur.

**Returns:**
float - die y‑Koordinate der oberen Kante dieser RectangleF‑Struktur.
### getRight() {#getRight--}
```
public final float getRight()
```


Ermittelt die x-Koordinate, die die Summe von X und Breite dieser RectangleF-Struktur ist.

**Returns:**
float - die x‑Koordinate, die die Summe von X und Width dieser RectangleF‑Struktur ist.
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Ermittelt die y-Koordinate, die die Summe von Y und Höhe dieser RectangleF-Struktur ist.

**Returns:**
float - die y‑Koordinate, die die Summe von Y und Height dieser RectangleF‑Struktur ist.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### inflate(float x, float y) {#inflate-float-float-}
```
public final void inflate(float x, float y)
```


Vergrößert diese [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Der Betrag, um diese [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur horizontal zu vergrößern. |
| y | float | Der Betrag, um diese [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur vertikal zu vergrößern. |

### inflate(SizeF size) {#inflate-com.aspose.drawing.SizeF-}
```
public final void inflate(SizeF size)
```


Vergrößert dieses [RectangleF](../../com.aspose.drawing/rectanglef) um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | Der Betrag, um dieses Rechteck zu vergrößern. |

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public final void intersect(RectangleF rect)
```


Ersetzt diese [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur durch die Schnittmenge aus ihr selbst und der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Das Rechteck zum Schneiden. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.drawing.RectangleF-}
```
public final boolean intersectsWith(RectangleF rect)
```


Bestimmt, ob dieses Rechteck mit `rect` schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Das Rechteck zum Testen. |

**Returns:**
boolean - diese Methode gibt true zurück, wenn irgendeine Schnittmenge besteht.
### offset(PointF pos) {#offset-com.aspose.drawing.PointF-}
```
public final void offset(PointF pos)
```


Passt die Position dieses Rechtecks um den angegebenen Betrag an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.drawing/pointf) | Der Betrag, um den Ort zu verschieben. |

### offset(float x, float y) {#offset-float-float-}
```
public final void offset(float x, float y)
```


Passt die Position dieses Rechtecks um den angegebenen Betrag an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Der Betrag, um den Ort horizontal zu verschieben. |
| y | float | Der Betrag, um den Ort vertikal zu verschieben. |

### contains(float x, float y) {#contains-float-float-}
```
public final boolean contains(float x, float y)
```


Bestimmt, ob der angegebene Punkt innerhalb dieser [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x‑Koordinate des zu testenden Punktes. |
| y | float | Die y‑Koordinate des zu testenden Punktes. |

**Returns:**
boolean - Diese Methode gibt `true` zurück, wenn der durch x und y definierte Punkt innerhalb dieser [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur liegt; andernfalls `false`.
### contains(PointF pt) {#contains-com.aspose.drawing.PointF-}
```
public final boolean contains(PointF pt)
```


Bestimmt, ob der angegebene Punkt innerhalb dieser [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | Das [PointF](../../com.aspose.drawing/pointf) zum Testen. |

**Returns:**
boolean - Diese Methode gibt `true` zurück, wenn der durch den Parameter pt dargestellte Punkt innerhalb dieser [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur liegt; andernfalls `false`.
### contains(RectangleF rect) {#contains-com.aspose.drawing.RectangleF-}
```
public final boolean contains(RectangleF rect)
```


Bestimmt, ob der durch `rect` dargestellte rechteckige Bereich vollständig innerhalb dieser [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Das [RectangleF](../../com.aspose.drawing/rectanglef) zum Testen. |

**Returns:**
boolean - Diese Methode gibt `true` zurück, wenn der durch `rect` dargestellte rechteckige Bereich vollständig innerhalb des durch dieses [RectangleF](../../com.aspose.drawing/rectanglef) dargestellten rechteckigen Bereichs liegt; andernfalls `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt zum Vergleich mit dieser Instanz. |

**Returns:**
boolean - `true`, wenn das angegebene Objekt dieser Instanz gleich ist; andernfalls `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int - Ein Hash‑Code für diese Instanz, geeignet für den Einsatz in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
### equals(RectangleF other) {#equals-com.aspose.drawing.RectangleF-}
```
public final boolean equals(RectangleF other)
```


Prüft, ob eine andere [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur dieselbe Position und Größe wie diese [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [RectangleF](../../com.aspose.drawing/rectanglef) | Anderes Rechteck zum Testen |

**Returns:**
boolean - Diese Methode gibt `true` zurück, wenn die andere [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur und ihre Eigenschaften X, Y, Width und Height den entsprechenden Eigenschaften dieser [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur entsprechen; andernfalls `false`.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.drawing.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
