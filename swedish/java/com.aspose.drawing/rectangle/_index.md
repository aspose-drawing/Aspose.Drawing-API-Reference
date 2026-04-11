---
title: Rectangle
second_title: Aspose.Drawing för Java API‑referens
description: Lagrar en uppsättning av fyra heltal som representerar positionen och storleken på en rektangel.
type: docs
weight: 38
url: /sv/java/com.aspose.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Rectangle extends Struct<Rectangle> implements System.IEquatable<Rectangle>, Cloneable
```

Lagrar en uppsättning av fyra heltal som representerar positionen och storleken på en rektangel.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Initierar en ny instans av Rectangle-strukturen med den angivna platsen och storleken. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Initierar en ny instans av [Rectangle](../../com.aspose.drawing/rectangle)-strukturen med den angivna platsen och storleken. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [fromLTRB(int left, int top, int right, int bottom)](#fromLTRB-int-int-int-int-) | Skapar en [Rectangle](../../com.aspose.drawing/rectangle)-struktur med de angivna kantpositionerna. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Returnerar en tredje [Rectangle](../../com.aspose.drawing/rectangle)-struktur som representerar skärningspunkten mellan två andra [Rectangle](../../com.aspose.drawing/rectangle)-strukturer. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Testar om två [Rectangle](../../com.aspose.drawing/rectangle)-strukturer har samma plats och storlek. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Testar om två [Rectangle](../../com.aspose.drawing/rectangle)-strukturer skiljer sig åt i plats eller storlek. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.drawing.RectangleF-) | Konverterar den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen till en [Rectangle](../../com.aspose.drawing/rectangle)-struktur genom att avrunda [RectangleF](../../com.aspose.drawing/rectanglef)-värdena till nästa högre heltalsvärde. |
| [truncate(RectangleF value)](#truncate-com.aspose.drawing.RectangleF-) | Konverterar den angivna [RectangleF](../../com.aspose.drawing/rectanglef) till en [Rectangle](../../com.aspose.drawing/rectangle) genom att trunkera [RectangleF](../../com.aspose.drawing/rectanglef)-värdena. |
| [round(RectangleF value)](#round-com.aspose.drawing.RectangleF-) | Konverterar den angivna [RectangleF](../../com.aspose.drawing/rectanglef) till en [Rectangle](../../com.aspose.drawing/rectangle) genom att avrunda [RectangleF](../../com.aspose.drawing/rectanglef)-värdena till närmaste heltal. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Hämtar en [Rectangle](../../com.aspose.drawing/rectangle)-struktur som innehåller unionen av två [Rectangle](../../com.aspose.drawing/rectangle)-strukturer. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.drawing.Rectangle-int-int-) |  |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) |  |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Skapar en ny rektangel från två punkter. |
| [getEmpty()](#getEmpty--) | Hämtar en ny instans av `Rectangle`-strukturen som har `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` och `Rectangle.Height`-värdena satta till noll. |
| [getX()](#getX--) | Hämtar x-koordinaten för det övre vänstra hörnet av denna Rectangle-struktur. |
| [setX(int value)](#setX-int-) | Sätter x-koordinaten för det övre vänstra hörnet av denna Rectangle-struktur. |
| [getY()](#getY--) | Hämtar y-koordinaten för det övre vänstra hörnet av denna Rectangle-struktur. |
| [setY(int value)](#setY-int-) | Sätter y-koordinaten för det övre vänstra hörnet av denna Rectangle-struktur. |
| [getLocation()](#getLocation--) | Hämtar koordinaterna för det övre vänstra hörnet av denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur. |
| [setLocation(Point value)](#setLocation-com.aspose.drawing.Point-) | Ställer in koordinaterna för det övre vänstra hörnet av denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur. |
| [getWidth()](#getWidth--) | Hämtar bredden på denna Rectangle-struktur. |
| [setWidth(int value)](#setWidth-int-) | Ställer in bredden på denna Rectangle-struktur. |
| [getHeight()](#getHeight--) | Hämtar höjden på denna Rectangle-struktur. |
| [setHeight(int value)](#setHeight-int-) | Ställer in höjden på denna Rectangle-struktur. |
| [getSize()](#getSize--) | Hämtar storleken på denna [Rectangle](../../com.aspose.drawing/rectangle). |
| [setSize(Size value)](#setSize-com.aspose.drawing.Size-) | Ställer in storleken på denna [Rectangle](../../com.aspose.drawing/rectangle). |
| [getLeft()](#getLeft--) | Hämtar x-koordinaten för den vänstra kanten av denna Rectangle-struktur. |
| [getTop()](#getTop--) | Hämtar y-koordinaten för den övre kanten av denna Rectangle-struktur. |
| [getRight()](#getRight--) | Hämtar x-koordinaten som är summan av X- och Width-egenskapsvärdena för denna Rectangle-struktur. |
| [getBottom()](#getBottom--) | Hämtar y-koordinaten som är summan av Y- och Height-egenskapsvärdena för denna Rectangle-struktur. |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om alla numeriska egenskaper för denna [Rectangle](../../com.aspose.drawing/rectangle) har värdet noll. |
| [equals(Object obj)](#equals-java.lang.Object-) | Testar om obj är en [Rectangle](../../com.aspose.drawing/rectangle)-struktur med samma position och storlek som denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur. |
| [hashCode()](#hashCode--) | Returnerar hashkoden för denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur. |
| [toString()](#toString--) |  |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Ersätter denna [Rectangle](../../com.aspose.drawing/rectangle) med skärningspunkten mellan den själv och den angivna [Rectangle](../../com.aspose.drawing/rectangle). |
| [inflate(int width, int height)](#inflate-int-int-) | Förstorar denna [Rectangle](../../com.aspose.drawing/rectangle) med den angivna mängden. |
| [inflate(Size size)](#inflate-com.aspose.drawing.Size-) | Förstorar denna [Rectangle](../../com.aspose.drawing/rectangle) med den angivna mängden. |
| [contains(int x, int y)](#contains-int-int-) | Bestämmer om den angivna punkten finns inom denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur. |
| [contains(Point pt)](#contains-com.aspose.drawing.Point-) | Bestämmer om den angivna punkten finns inom denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur. |
| [contains(Rectangle rect)](#contains-com.aspose.drawing.Rectangle-) |  |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.drawing.Rectangle-) | Avgör om detta rektangel skär med `rect`. |
| [offset(int x, int y)](#offset-int-int-) | Justerar placeringen av denna rektangel med den angivna mängden. |
| [offset(Point pos)](#offset-com.aspose.drawing.Point-) | Justerar placeringen av denna rektangel med den angivna mängden. |
| [equals(Rectangle other)](#equals-com.aspose.drawing.Rectangle-) | Testar om en annan [Rectangle](../../com.aspose.drawing/rectangle)-struktur har samma position och storlek som denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur. |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.drawing.Rectangle-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [normalize()](#normalize--) | Normaliserar rektangeln genom att göra dess bredd och höjd positiva, vänster mindre än höger och toppen mindre än botten. |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Initierar en ny instans av Rectangle-strukturen med den angivna platsen och storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | x-koordinaten för det övre vänstra hörnet av rektangeln. |
| y | int | Y-koordinaten för rektangelns övre vänstra hörn. |
| bredd | int | Rektangelns bredd. |
| höjd | int | Rektangelns höjd. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public Rectangle(Point location, Size size)
```


Initierar en ny instans av [Rectangle](../../com.aspose.drawing/rectangle)-strukturen med den angivna platsen och storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location | [Point](../../com.aspose.drawing/point) | En [Point](../../com.aspose.drawing/point) som representerar det övre vänstra hörnet av det rektangulära området. |
| size | [Size](../../com.aspose.drawing/size) | En `Size`([.getSize](../../null/\#getSize)/[.setSize(Size)](../../null/\#setSize-Size-)) som representerar bredden och höjden av det rektangulära området. |

### fromLTRB(int left, int top, int right, int bottom) {#fromLTRB-int-int-int-int-}
```
public static Rectangle fromLTRB(int left, int top, int right, int bottom)
```


Skapar en [Rectangle](../../com.aspose.drawing/rectangle)-struktur med de angivna kantpositionerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | int | x-koordinaten för det övre vänstra hörnet av denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur. |
| top | int | y-koordinaten för det övre vänstra hörnet av denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur. |
| right | int | x-koordinaten för det nedre högra hörnet av denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur. |
| bottom | int | y-koordinaten för det nedre högra hörnet av denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The new [Rectangle](../../com.aspose.drawing/rectangle) that this method creates.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Returnerar en tredje [Rectangle](../../com.aspose.drawing/rectangle)-struktur som representerar skärningspunkten mellan två andra [Rectangle](../../com.aspose.drawing/rectangle)-strukturer. Om det inte finns någon skärning returneras en tom [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | Första rektangeln att skära. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | Andra rektangeln att skära. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the intersection of `a` and `b`.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Testar om två [Rectangle](../../com.aspose.drawing/rectangle)-strukturer har samma plats och storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | Den [Rectangle](../../com.aspose.drawing/rectangle)-struktur som är till vänster om likhetstecknet. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | Den [Rectangle](../../com.aspose.drawing/rectangle)-struktur som är till höger om likhetstecknet. |

**Returns:**
boolean - Denna operator returnerar `true` om de två [Rectangle](../../com.aspose.drawing/rectangle)-strukturerna har lika X-, Y-, Width- och Height-egenskaper.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Testar om två [Rectangle](../../com.aspose.drawing/rectangle)-strukturer skiljer sig åt i plats eller storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | Den [Rectangle](../../com.aspose.drawing/rectangle)-struktur som är till vänster om olikhetstecknet. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | Den [Rectangle](../../com.aspose.drawing/rectangle)-struktur som är till höger om olikhetstecknet. |

**Returns:**
boolean - Denna operator returnerar `true` om någon av X-, Y-, Width- eller Height-egenskaperna för de två [Rectangle](../../com.aspose.drawing/rectangle)-strukturerna är olika; annars `false`.
### ceiling(RectangleF value) {#ceiling-com.aspose.drawing.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Konverterar den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen till en [Rectangle](../../com.aspose.drawing/rectangle)-struktur genom att avrunda [RectangleF](../../com.aspose.drawing/rectanglef)-värdena till nästa högre heltalsvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef)-struktur som ska konverteras. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - Returns a [Rectangle](../../com.aspose.drawing/rectangle).
### truncate(RectangleF value) {#truncate-com.aspose.drawing.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Konverterar den angivna [RectangleF](../../com.aspose.drawing/rectanglef) till en [Rectangle](../../com.aspose.drawing/rectangle) genom att trunkera [RectangleF](../../com.aspose.drawing/rectanglef)-värdena.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef) som ska konverteras. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The truncated value of the [Rectangle](../../com.aspose.drawing/rectangle).
### round(RectangleF value) {#round-com.aspose.drawing.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Konverterar den angivna [RectangleF](../../com.aspose.drawing/rectanglef) till en [Rectangle](../../com.aspose.drawing/rectangle) genom att avrunda [RectangleF](../../com.aspose.drawing/rectanglef)-värdena till närmaste heltal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef) som ska konverteras. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle).
### union(Rectangle a, Rectangle b) {#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Hämtar en [Rectangle](../../com.aspose.drawing/rectangle)-struktur som innehåller unionen av två [Rectangle](../../com.aspose.drawing/rectangle)-strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | En första rektangel att förena. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | En andra rektangel att förena. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) structure that bounds the union of the two [Rectangle](../../com.aspose.drawing/rectangle) structures.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.drawing.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Skapar en ny rektangel från två punkter. Den skapade rektangeln normaliseras så att (left,top) är lägre än (right,bottom).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | Den första punkten. |
| point2 | [Point](../../com.aspose.drawing/point) | Den andra punkten. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A newly created rectangle.
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Hämtar en ny instans av `Rectangle`-strukturen som har `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` och `Rectangle.Height`-värdena satta till noll.

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### getX() {#getX--}
```
public final int getX()
```


Hämtar x-koordinaten för det övre vänstra hörnet av denna Rectangle-struktur.

**Returns:**
int - x-koordinaten för det övre vänstra hörnet av denna Rectangle-struktur.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Sätter x-koordinaten för det övre vänstra hörnet av denna Rectangle-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | x-koordinaten för det övre vänstra hörnet av denna Rectangle-struktur. |

### getY() {#getY--}
```
public final int getY()
```


Hämtar y-koordinaten för det övre vänstra hörnet av denna Rectangle-struktur.

**Returns:**
int - y-koordinaten för det övre vänstra hörnet av denna Rectangle-struktur.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Sätter y-koordinaten för det övre vänstra hörnet av denna Rectangle-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | y-koordinaten för det övre vänstra hörnet av denna Rectangle-struktur. |

### getLocation() {#getLocation--}
```
public final Point getLocation()
```


Hämtar koordinaterna för det övre vänstra hörnet av denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur.

**Returns:**
[Point](../../com.aspose.drawing/point) - the coordinates of the upper-left corner of this [Rectangle](../../com.aspose.drawing/rectangle) structure.
### setLocation(Point value) {#setLocation-com.aspose.drawing.Point-}
```
public final void setLocation(Point value)
```


Ställer in koordinaterna för det övre vänstra hörnet av denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.drawing/point) | koordinaterna för det övre vänstra hörnet av denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar bredden på denna Rectangle-struktur.

**Returns:**
int - bredden på denna Rectangle-struktur.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ställer in bredden på denna Rectangle-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | bredden på denna Rectangle-struktur. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar höjden på denna Rectangle-struktur.

**Returns:**
int - höjden på denna Rectangle-struktur.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ställer in höjden på denna Rectangle-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | höjden på denna Rectangle-struktur. |

### getSize() {#getSize--}
```
public final Size getSize()
```


Hämtar storleken på denna [Rectangle](../../com.aspose.drawing/rectangle).

**Returns:**
[Size](../../com.aspose.drawing/size) - the size of this [Rectangle](../../com.aspose.drawing/rectangle).
### setSize(Size value) {#setSize-com.aspose.drawing.Size-}
```
public final void setSize(Size value)
```


Ställer in storleken på denna [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Size](../../com.aspose.drawing/size) | storleken på denna [Rectangle](../../com.aspose.drawing/rectangle). |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Hämtar x-koordinaten för den vänstra kanten av denna Rectangle-struktur.

**Returns:**
int - x-koordinaten för den vänstra kanten av denna Rectangle-struktur.
### getTop() {#getTop--}
```
public final int getTop()
```


Hämtar y-koordinaten för den övre kanten av denna Rectangle-struktur.

**Returns:**
int - y-koordinaten för den övre kanten av denna Rectangle-struktur.
### getRight() {#getRight--}
```
public final int getRight()
```


Hämtar x-koordinaten som är summan av X- och Width-egenskapsvärdena för denna Rectangle-struktur.

**Returns:**
int - x-koordinaten som är summan av X- och Width-egenskapsvärdena för denna Rectangle-struktur.
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Hämtar y-koordinaten som är summan av Y- och Height-egenskapsvärdena för denna Rectangle-struktur.

**Returns:**
int - y-koordinaten som är summan av Y- och Height-egenskapsvärdena för denna Rectangle-struktur.
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Hämtar ett värde som indikerar om alla numeriska egenskaper för denna [Rectangle](../../com.aspose.drawing/rectangle) har värdet noll.

**Returns:**
boolean - Denna egenskap returnerar `true` om `Rectangle.Width`, `Rectangle.Height`, `Rectangle.X` och `Rectangle.Y` för detta [Rectangle](../../com.aspose.drawing/rectangle) alla har värdet noll; annars `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Testar om obj är en [Rectangle](../../com.aspose.drawing/rectangle)-struktur med samma position och storlek som denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att testa. |

**Returns:**
boolean - Denna metod returnerar `true` om obj är en [Rectangle](../../com.aspose.drawing/rectangle)-struktur och dess X-, Y-, Width- och Height-egenskaper är lika med motsvarande egenskaper för detta [Rectangle](../../com.aspose.drawing/rectangle)-struktur; annars `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur. För information om användning av hash‑koder, se GetHashCode.

**Returns:**
int - Ett heltal som representerar hash‑koden för denna rektangel.
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


Ersätter denna [Rectangle](../../com.aspose.drawing/rectangle) med skärningspunkten mellan den själv och den angivna [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Den [Rectangle](../../com.aspose.drawing/rectangle) att skära med. |

### inflate(int width, int height) {#inflate-int-int-}
```
public final void inflate(int width, int height)
```


Förstorar denna [Rectangle](../../com.aspose.drawing/rectangle) med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | int | Mängden att expandera denna [Rectangle](../../com.aspose.drawing/rectangle) horisontellt. |
| height | int | Mängden att expandera denna [Rectangle](../../com.aspose.drawing/rectangle) vertikalt. |

### inflate(Size size) {#inflate-com.aspose.drawing.Size-}
```
public final void inflate(Size size)
```


Förstorar denna [Rectangle](../../com.aspose.drawing/rectangle) med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | Storleken att expandera denna [Rectangle](../../com.aspose.drawing/rectangle). |

### contains(int x, int y) {#contains-int-int-}
```
public final boolean contains(int x, int y)
```


Bestämmer om den angivna punkten finns inom denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | x‑koordinaten för den punkt som ska testas. |
| y | int | y-koordinaten för punkten som ska testas. |

**Returns:**
boolean - Denna metod returnerar `true` om punkten definierad av `x` och `y` finns inom denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur; annars `false`.
### contains(Point pt) {#contains-com.aspose.drawing.Point-}
```
public final boolean contains(Point pt)
```


Bestämmer om den angivna punkten finns inom denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | [Point](../../com.aspose.drawing/point) att testa. |

**Returns:**
boolean - Denna metod returnerar `true` om punkten representerad av `pt` finns inom denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur; annars `false`.
### contains(Rectangle rect) {#contains-com.aspose.drawing.Rectangle-}
```
public final boolean contains(Rectangle rect)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.drawing.Rectangle-}
```
public final boolean intersectsWith(Rectangle rect)
```


Avgör om detta rektangel skär med `rect`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Rektangeln att testa. |

**Returns:**
boolean - Denna metod returnerar true om det finns någon skärning, annars false.
### offset(int x, int y) {#offset-int-int-}
```
public final void offset(int x, int y)
```


Justerar placeringen av denna rektangel med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Den horisontella förskjutningen. |
| y | int | Den vertikala förskjutningen. |

### offset(Point pos) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point pos)
```


Justerar placeringen av denna rektangel med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pos | [Point](../../com.aspose.drawing/point) | Förskjutningen. |

### equals(Rectangle other) {#equals-com.aspose.drawing.Rectangle-}
```
public final boolean equals(Rectangle other)
```


Testar om en annan [Rectangle](../../com.aspose.drawing/rectangle)-struktur har samma position och storlek som denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.drawing/rectangle) | Annan rektangel att testa |

**Returns:**
boolean - Denna metod returnerar `true` om en annan [Rectangle](../../com.aspose.drawing/rectangle)-struktur och dess X-, Y-, Width- och Height‑egenskaper är lika med motsvarande egenskaper för denna [Rectangle](../../com.aspose.drawing/rectangle)-struktur; annars `false`.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.drawing.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Normaliserar rektangeln genom att göra dess bredd och höjd positiva, vänster mindre än höger och toppen mindre än botten.

