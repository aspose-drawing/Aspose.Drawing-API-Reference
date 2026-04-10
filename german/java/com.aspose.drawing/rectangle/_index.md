---
title: Rectangle
second_title: Aspose.Drawing für Java API-Referenz
description: Speichert ein Set von vier Ganzzahlen, die den Ort und die Größe eines Rechtecks darstellen.
type: docs
weight: 38
url: /de/java/com.aspose.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Rectangle extends Struct<Rectangle> implements System.IEquatable<Rectangle>, Cloneable
```

Speichert ein Set von vier Ganzzahlen, die den Ort und die Größe eines Rechtecks darstellen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Initialisiert eine neue Instanz der Rectangle-Struktur mit dem angegebenen Ort und der Größe. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Initialisiert eine neue Instanz des [Rectangle](../../com.aspose.drawing/rectangle)-Structs mit dem angegebenen Ort und der Größe. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [fromLTRB(int left, int top, int right, int bottom)](#fromLTRB-int-int-int-int-) | Erstellt eine [Rectangle](../../com.aspose.drawing/rectangle)-Struktur mit den angegebenen Kantenpositionen. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Gibt eine dritte [Rectangle](../../com.aspose.drawing/rectangle)-Struktur zurück, die die Schnittmenge von zwei anderen [Rectangle](../../com.aspose.drawing/rectangle)-Strukturen darstellt. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Prüft, ob zwei [Rectangle](../../com.aspose.drawing/rectangle)-Strukturen gleichen Ort und gleiche Größe haben. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Prüft, ob sich zwei [Rectangle](../../com.aspose.drawing/rectangle)-Strukturen im Ort oder in der Größe unterscheiden. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.drawing.RectangleF-) | Konvertiert die angegebene [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur in eine [Rectangle](../../com.aspose.drawing/rectangle)-Struktur, indem die Werte von [RectangleF](../../com.aspose.drawing/rectanglef) auf die nächsthöheren Ganzzahlwerte gerundet werden. |
| [truncate(RectangleF value)](#truncate-com.aspose.drawing.RectangleF-) | Konvertiert das angegebene [RectangleF](../../com.aspose.drawing/rectanglef) in ein [Rectangle](../../com.aspose.drawing/rectangle), indem die Werte von [RectangleF](../../com.aspose.drawing/rectanglef) abgeschnitten werden. |
| [round(RectangleF value)](#round-com.aspose.drawing.RectangleF-) | Konvertiert das angegebene [RectangleF](../../com.aspose.drawing/rectanglef) in ein [Rectangle](../../com.aspose.drawing/rectangle), indem die Werte von [RectangleF](../../com.aspose.drawing/rectanglef) auf die nächsten Ganzzahlwerte gerundet werden. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Gibt eine [Rectangle](../../com.aspose.drawing/rectangle)-Struktur zurück, die die Vereinigung von zwei [Rectangle](../../com.aspose.drawing/rectangle)-Strukturen enthält. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.drawing.Rectangle-int-int-) |  |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) |  |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Erstellt ein neues Rechteck aus zwei Punkten. |
| [getEmpty()](#getEmpty--) | Gibt eine neue Instanz der `Rectangle`-Struktur zurück, deren Werte `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` und `Rectangle.Height` auf Null gesetzt sind. |
| [getX()](#getX--) | Gibt die x-Koordinate der oberen linken Ecke dieser Rectangle-Struktur zurück. |
| [setX(int value)](#setX-int-) | Setzt die x-Koordinate der oberen linken Ecke dieser Rectangle-Struktur. |
| [getY()](#getY--) | Gibt die y-Koordinate der oberen linken Ecke dieser Rectangle-Struktur zurück. |
| [setY(int value)](#setY-int-) | Setzt die y-Koordinate der oberen linken Ecke dieser Rectangle-Struktur. |
| [getLocation()](#getLocation--) | Gibt die Koordinaten der oberen linken Ecke dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur zurück. |
| [setLocation(Point value)](#setLocation-com.aspose.drawing.Point-) | Legt die Koordinaten der oberen linken Ecke dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur fest. |
| [getWidth()](#getWidth--) | Ermittelt die Breite dieser Rectangle-Struktur. |
| [setWidth(int value)](#setWidth-int-) | Legt die Breite dieser Rectangle-Struktur fest. |
| [getHeight()](#getHeight--) | Ermittelt die Höhe dieser Rectangle-Struktur. |
| [setHeight(int value)](#setHeight-int-) | Legt die Höhe dieser Rectangle-Struktur fest. |
| [getSize()](#getSize--) | Ermittelt die Größe dieser [Rectangle](../../com.aspose.drawing/rectangle). |
| [setSize(Size value)](#setSize-com.aspose.drawing.Size-) | Legt die Größe dieser [Rectangle](../../com.aspose.drawing/rectangle) fest. |
| [getLeft()](#getLeft--) | Ermittelt die X-Koordinate der linken Kante dieser Rectangle-Struktur. |
| [getTop()](#getTop--) | Ermittelt die Y-Koordinate der oberen Kante dieser Rectangle-Struktur. |
| [getRight()](#getRight--) | Ermittelt die X-Koordinate, die die Summe der X- und Width-Eigenschaftswerte dieser Rectangle-Struktur ist. |
| [getBottom()](#getBottom--) | Ermittelt die Y-Koordinate, die die Summe der Y- und Height-Eigenschaftswerte dieser Rectangle-Struktur ist. |
| [isEmpty()](#isEmpty--) | Ermittelt einen Wert, der angibt, ob alle numerischen Eigenschaften dieser [Rectangle](../../com.aspose.drawing/rectangle) den Wert Null haben. |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft, ob obj eine [Rectangle](../../com.aspose.drawing/rectangle)-Struktur mit derselben Position und Größe wie diese [Rectangle](../../com.aspose.drawing/rectangle)-Struktur ist. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese [Rectangle](../../com.aspose.drawing/rectangle)-Struktur zurück. |
| [toString()](#toString--) |  |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Ersetzt diese [Rectangle](../../com.aspose.drawing/rectangle) durch die Schnittmenge von ihr selbst und dem angegebenen [Rectangle](../../com.aspose.drawing/rectangle). |
| [inflate(int width, int height)](#inflate-int-int-) | Vergrößert diese [Rectangle](../../com.aspose.drawing/rectangle) um den angegebenen Betrag. |
| [inflate(Size size)](#inflate-com.aspose.drawing.Size-) | Vergrößert diese [Rectangle](../../com.aspose.drawing/rectangle) um den angegebenen Betrag. |
| [contains(int x, int y)](#contains-int-int-) | Bestimmt, ob der angegebene Punkt innerhalb dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur liegt. |
| [contains(Point pt)](#contains-com.aspose.drawing.Point-) | Bestimmt, ob der angegebene Punkt innerhalb dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur liegt. |
| [contains(Rectangle rect)](#contains-com.aspose.drawing.Rectangle-) |  |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.drawing.Rectangle-) | Bestimmt, ob dieses Rechteck mit `rect` schneidet. |
| [offset(int x, int y)](#offset-int-int-) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [offset(Point pos)](#offset-com.aspose.drawing.Point-) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [equals(Rectangle other)](#equals-com.aspose.drawing.Rectangle-) | Prüft, ob eine andere [Rectangle](../../com.aspose.drawing/rectangle)-Struktur dieselbe Position und Größe wie diese [Rectangle](../../com.aspose.drawing/rectangle)-Struktur hat. |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.drawing.Rectangle-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [normalize()](#normalize--) | Normalisiert das Rechteck, indem seine Breite und Höhe positiv gemacht werden, links kleiner als rechts und oben kleiner als unten. |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Initialisiert eine neue Instanz der Rectangle-Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate der oberen linken Ecke des Rechtecks. |
| y | int | Die y‑Koordinate der oberen linken Ecke des Rechtecks. |
| Breite | int | Die Breite des Rechtecks. |
| Höhe | int | Die Höhe des Rechtecks. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public Rectangle(Point location, Size size)
```


Initialisiert eine neue Instanz des [Rectangle](../../com.aspose.drawing/rectangle)-Structs mit dem angegebenen Ort und der Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| location | [Point](../../com.aspose.drawing/point) | Ein [Point](../../com.aspose.drawing/point), der die obere linke Ecke des rechteckigen Bereichs darstellt. |
| size | [Size](../../com.aspose.drawing/size) | Ein `Size`([.getSize](../../null/\#getSize)/[.setSize(Size)](../../null/\#setSize-Size-)), das die Breite und Höhe des rechteckigen Bereichs darstellt. |

### fromLTRB(int left, int top, int right, int bottom) {#fromLTRB-int-int-int-int-}
```
public static Rectangle fromLTRB(int left, int top, int right, int bottom)
```


Erstellt eine [Rectangle](../../com.aspose.drawing/rectangle)-Struktur mit den angegebenen Kantenpositionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | int | Die X-Koordinate der oberen linken Ecke dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur. |
| top | int | Die Y-Koordinate der oberen linken Ecke dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur. |
| right | int | Die X-Koordinate der unteren rechten Ecke dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur. |
| bottom | int | Die Y-Koordinate der unteren rechten Ecke dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The new [Rectangle](../../com.aspose.drawing/rectangle) that this method creates.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Gibt eine dritte [Rectangle](../../com.aspose.drawing/rectangle)-Struktur zurück, die die Schnittmenge zweier anderer [Rectangle](../../com.aspose.drawing/rectangle)-Strukturen darstellt. Wenn es keine Schnittmenge gibt, wird ein leeres [Rectangle](../../com.aspose.drawing/rectangle) zurückgegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | Erstes Rechteck zum Schneiden. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | Zweites Rechteck zum Schneiden. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the intersection of `a` and `b`.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Prüft, ob zwei [Rectangle](../../com.aspose.drawing/rectangle)-Strukturen gleichen Ort und gleiche Größe haben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | Die [Rectangle](../../com.aspose.drawing/rectangle)-Struktur, die sich links vom Gleichheitsoperator befindet. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | Die [Rectangle](../../com.aspose.drawing/rectangle)-Struktur, die sich rechts vom Gleichheitsoperator befindet. |

**Returns:**
boolean - Dieser Operator gibt `true` zurück, wenn die beiden [Rectangle](../../com.aspose.drawing/rectangle)-Strukturen gleiche X-, Y-, Width- und Height‑Eigenschaften haben.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Prüft, ob sich zwei [Rectangle](../../com.aspose.drawing/rectangle)-Strukturen im Ort oder in der Größe unterscheiden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | Die [Rectangle](../../com.aspose.drawing/rectangle)-Struktur, die sich links vom Ungleichheitsoperator befindet. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | Die [Rectangle](../../com.aspose.drawing/rectangle)-Struktur, die sich rechts vom Ungleichheitsoperator befindet. |

**Returns:**
boolean - Dieser Operator gibt `true` zurück, wenn irgendeine der X-, Y-, Width‑ oder Height‑Eigenschaften der beiden [Rectangle](../../com.aspose.drawing/rectangle)-Strukturen ungleich ist; andernfalls `false`.
### ceiling(RectangleF value) {#ceiling-com.aspose.drawing.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Konvertiert die angegebene [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur in eine [Rectangle](../../com.aspose.drawing/rectangle)-Struktur, indem die Werte von [RectangleF](../../com.aspose.drawing/rectanglef) auf die nächsthöheren Ganzzahlwerte gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | Die zu konvertierende [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - Returns a [Rectangle](../../com.aspose.drawing/rectangle).
### truncate(RectangleF value) {#truncate-com.aspose.drawing.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Konvertiert das angegebene [RectangleF](../../com.aspose.drawing/rectanglef) in ein [Rectangle](../../com.aspose.drawing/rectangle), indem die Werte von [RectangleF](../../com.aspose.drawing/rectanglef) abgeschnitten werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | Das zu konvertierende [RectangleF](../../com.aspose.drawing/rectanglef). |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The truncated value of the [Rectangle](../../com.aspose.drawing/rectangle).
### round(RectangleF value) {#round-com.aspose.drawing.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Konvertiert das angegebene [RectangleF](../../com.aspose.drawing/rectanglef) in ein [Rectangle](../../com.aspose.drawing/rectangle), indem die Werte von [RectangleF](../../com.aspose.drawing/rectanglef) auf die nächsten Ganzzahlwerte gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | Das zu konvertierende [RectangleF](../../com.aspose.drawing/rectanglef). |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle).
### union(Rectangle a, Rectangle b) {#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Gibt eine [Rectangle](../../com.aspose.drawing/rectangle)-Struktur zurück, die die Vereinigung von zwei [Rectangle](../../com.aspose.drawing/rectangle)-Strukturen enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | Ein erstes Rechteck für die Vereinigung. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | Ein zweites Rechteck für die Vereinigung. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) structure that bounds the union of the two [Rectangle](../../com.aspose.drawing/rectangle) structures.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.drawing.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| x | int |  |
| y | int |  |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Erstellt ein neues Rechteck aus zwei Punkten. Das erstellte Rechteck wird normalisiert, sodass (left,top) kleiner ist als (right,bottom).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | Der erste Punkt. |
| point2 | [Point](../../com.aspose.drawing/point) | Der zweite Punkt. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A newly created rectangle.
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Gibt eine neue Instanz der `Rectangle`-Struktur zurück, deren Werte `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` und `Rectangle.Height` auf Null gesetzt sind.

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### getX() {#getX--}
```
public final int getX()
```


Gibt die x-Koordinate der oberen linken Ecke dieser Rectangle-Struktur zurück.

**Returns:**
int - die x‑Koordinate der oberen linken Ecke dieser Rectangle‑Struktur.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Setzt die x-Koordinate der oberen linken Ecke dieser Rectangle-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | die x‑Koordinate der oberen linken Ecke dieser Rectangle‑Struktur. |

### getY() {#getY--}
```
public final int getY()
```


Gibt die y-Koordinate der oberen linken Ecke dieser Rectangle-Struktur zurück.

**Returns:**
int - die y‑Koordinate der oberen linken Ecke dieser Rectangle‑Struktur.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Setzt die y-Koordinate der oberen linken Ecke dieser Rectangle-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | die y‑Koordinate der oberen linken Ecke dieser Rectangle‑Struktur. |

### getLocation() {#getLocation--}
```
public final Point getLocation()
```


Gibt die Koordinaten der oberen linken Ecke dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur zurück.

**Returns:**
[Point](../../com.aspose.drawing/point) - the coordinates of the upper-left corner of this [Rectangle](../../com.aspose.drawing/rectangle) structure.
### setLocation(Point value) {#setLocation-com.aspose.drawing.Point-}
```
public final void setLocation(Point value)
```


Legt die Koordinaten der oberen linken Ecke dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.drawing/point) | die Koordinaten der oberen linken Ecke dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ermittelt die Breite dieser Rectangle-Struktur.

**Returns:**
int - die Breite dieser Rectangle‑Struktur.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Legt die Breite dieser Rectangle-Struktur fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | die Breite dieser Rectangle‑Struktur. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ermittelt die Höhe dieser Rectangle-Struktur.

**Returns:**
int - die Höhe dieser Rectangle‑Struktur.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Legt die Höhe dieser Rectangle-Struktur fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | die Höhe dieser Rectangle‑Struktur. |

### getSize() {#getSize--}
```
public final Size getSize()
```


Ermittelt die Größe dieser [Rectangle](../../com.aspose.drawing/rectangle).

**Returns:**
[Size](../../com.aspose.drawing/size) - the size of this [Rectangle](../../com.aspose.drawing/rectangle).
### setSize(Size value) {#setSize-com.aspose.drawing.Size-}
```
public final void setSize(Size value)
```


Legt die Größe dieser [Rectangle](../../com.aspose.drawing/rectangle) fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Size](../../com.aspose.drawing/size) | die Größe dieses [Rectangle](../../com.aspose.drawing/rectangle). |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Ermittelt die X-Koordinate der linken Kante dieser Rectangle-Struktur.

**Returns:**
int - die x‑Koordinate der linken Kante dieser Rectangle‑Struktur.
### getTop() {#getTop--}
```
public final int getTop()
```


Ermittelt die Y-Koordinate der oberen Kante dieser Rectangle-Struktur.

**Returns:**
int - die y‑Koordinate der oberen Kante dieser Rectangle‑Struktur.
### getRight() {#getRight--}
```
public final int getRight()
```


Ermittelt die X-Koordinate, die die Summe der X- und Width-Eigenschaftswerte dieser Rectangle-Struktur ist.

**Returns:**
int - die x‑Koordinate, die die Summe der X‑ und Width‑Eigenschaftswerte dieser Rectangle‑Struktur ist.
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Ermittelt die Y-Koordinate, die die Summe der Y- und Height-Eigenschaftswerte dieser Rectangle-Struktur ist.

**Returns:**
int - die y‑Koordinate, die die Summe der Y‑ und Height‑Eigenschaftswerte dieser Rectangle‑Struktur ist.
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Ermittelt einen Wert, der angibt, ob alle numerischen Eigenschaften dieser [Rectangle](../../com.aspose.drawing/rectangle) den Wert Null haben.

**Returns:**
boolescher - Diese Eigenschaft gibt `true` zurück, wenn die Eigenschaften `Rectangle.Width`, `Rectangle.Height`, `Rectangle.X` und `Rectangle.Y` dieses [Rectangle](../../com.aspose.drawing/rectangle) alle den Wert null haben; andernfalls `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Prüft, ob obj eine [Rectangle](../../com.aspose.drawing/rectangle)-Struktur mit derselben Position und Größe wie diese [Rectangle](../../com.aspose.drawing/rectangle)-Struktur ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt zum Testen. |

**Returns:**
boolescher - Diese Methode gibt `true` zurück, wenn obj eine [Rectangle](../../com.aspose.drawing/rectangle)-Struktur ist und seine X-, Y-, Width- und Height-Eigenschaften den entsprechenden Eigenschaften dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur entsprechen; andernfalls `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese [Rectangle](../../com.aspose.drawing/rectangle)-Struktur zurück. Weitere Informationen zur Verwendung von Hashcodes finden Sie unter GetHashCode.

**Returns:**
int - Eine Ganzzahl, die den Hashcode für dieses Rechteck darstellt.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public final void intersect(Rectangle rect)
```


Ersetzt diese [Rectangle](../../com.aspose.drawing/rectangle) durch die Schnittmenge von ihr selbst und dem angegebenen [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Das [Rectangle](../../com.aspose.drawing/rectangle), mit dem geschnitten werden soll. |

### inflate(int width, int height) {#inflate-int-int-}
```
public final void inflate(int width, int height)
```


Vergrößert diese [Rectangle](../../com.aspose.drawing/rectangle) um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | int | Der Betrag, um den dieses [Rectangle](../../com.aspose.drawing/rectangle) horizontal erweitert wird. |
| height | int | Der Betrag, um den dieses [Rectangle](../../com.aspose.drawing/rectangle) vertikal erweitert wird. |

### inflate(Size size) {#inflate-com.aspose.drawing.Size-}
```
public final void inflate(Size size)
```


Vergrößert diese [Rectangle](../../com.aspose.drawing/rectangle) um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | Die Größe, um die dieses [Rectangle](../../com.aspose.drawing/rectangle) erweitert wird. |

### contains(int x, int y) {#contains-int-int-}
```
public final boolean contains(int x, int y)
```


Bestimmt, ob der angegebene Punkt innerhalb dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y‑Koordinate des zu testenden Punktes. |

**Returns:**
boolescher - Diese Methode gibt `true` zurück, wenn der durch `x` und `y` definierte Punkt innerhalb dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur liegt; andernfalls `false`.
### contains(Point pt) {#contains-com.aspose.drawing.Point-}
```
public final boolean contains(Point pt)
```


Bestimmt, ob der angegebene Punkt innerhalb dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Der zu testende [Point](../../com.aspose.drawing/point). |

**Returns:**
boolescher - Diese Methode gibt `true` zurück, wenn der durch `pt` dargestellte Punkt innerhalb dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur liegt; andernfalls `false`.
### contains(Rectangle rect) {#contains-com.aspose.drawing.Rectangle-}
```
public final boolean contains(Rectangle rect)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.drawing.Rectangle-}
```
public final boolean intersectsWith(Rectangle rect)
```


Bestimmt, ob dieses Rechteck mit `rect` schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Das Rechteck zum Testen. |

**Returns:**
boolescher - Diese Methode gibt true zurück, wenn irgendeine Schnittmenge besteht, andernfalls false.
### offset(int x, int y) {#offset-int-int-}
```
public final void offset(int x, int y)
```


Passt die Position dieses Rechtecks um den angegebenen Betrag an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Der horizontale Versatz. |
| y | int | Der vertikale Versatz. |

### offset(Point pos) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point pos)
```


Passt die Position dieses Rechtecks um den angegebenen Betrag an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pos | [Point](../../com.aspose.drawing/point) | Der Versatz. |

### equals(Rectangle other) {#equals-com.aspose.drawing.Rectangle-}
```
public final boolean equals(Rectangle other)
```


Prüft, ob eine andere [Rectangle](../../com.aspose.drawing/rectangle)-Struktur dieselbe Position und Größe wie diese [Rectangle](../../com.aspose.drawing/rectangle)-Struktur hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.drawing/rectangle) | Anderes Rechteck zum Testen |

**Returns:**
boolescher - Diese Methode gibt `true` zurück, wenn die andere [Rectangle](../../com.aspose.drawing/rectangle)-Struktur und ihre X-, Y-, Width- und Height-Eigenschaften den entsprechenden Eigenschaften dieser [Rectangle](../../com.aspose.drawing/rectangle)-Struktur entsprechen; andernfalls `false`.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.drawing.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.drawing/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### normalize() {#normalize--}
```
public void normalize()
```


Normalisiert das Rechteck, indem seine Breite und Höhe positiv gemacht werden, links kleiner als rechts und oben kleiner als unten.

