---
title: Rechthoek
second_title: Aspose.Drawing voor Java API-referentie
description: Slaat een set van vier gehele getallen op die de locatie en grootte van een rechthoek weergeven.
type: docs
weight: 38
url: /nl/java/com.aspose.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Rectangle extends Struct<Rectangle> implements System.IEquatable<Rectangle>, Cloneable
```

Slaat een set van vier gehele getallen op die de locatie en grootte van een rechthoek weergeven.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Initialiseert een nieuw exemplaar van de Rectangle-structuur met de opgegeven locatie en grootte. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Initialiseert een nieuw exemplaar van de [Rectangle](../../com.aspose.drawing/rectangle) struct met de opgegeven locatie en grootte. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [fromLTRB(int left, int top, int right, int bottom)](#fromLTRB-int-int-int-int-) | Maakt een [Rectangle](../../com.aspose.drawing/rectangle) structuur met de opgegeven randlocaties. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Retourneert een derde [Rectangle](../../com.aspose.drawing/rectangle) structuur die de intersectie van twee andere [Rectangle](../../com.aspose.drawing/rectangle) structuren weergeeft. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Test of twee [Rectangle](../../com.aspose.drawing/rectangle) structuren dezelfde locatie en grootte hebben. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Test of twee [Rectangle](../../com.aspose.drawing/rectangle) structuren verschillen in locatie of grootte. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.drawing.RectangleF-) | Converteert de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) structuur naar een [Rectangle](../../com.aspose.drawing/rectangle) structuur door de [RectangleF](../../com.aspose.drawing/rectanglef) waarden af te ronden naar de volgende hogere gehele getallen. |
| [truncate(RectangleF value)](#truncate-com.aspose.drawing.RectangleF-) | Converteert de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) naar een [Rectangle](../../com.aspose.drawing/rectangle) door de [RectangleF](../../com.aspose.drawing/rectanglef) waarden af te kappen. |
| [round(RectangleF value)](#round-com.aspose.drawing.RectangleF-) | Converteert de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) naar een [Rectangle](../../com.aspose.drawing/rectangle) door de [RectangleF](../../com.aspose.drawing/rectanglef) waarden af te ronden naar de dichtstbijzijnde gehele getallen. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Haalt een [Rectangle](../../com.aspose.drawing/rectangle) structuur op die de unie van twee [Rectangle](../../com.aspose.drawing/rectangle) structuren bevat. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.drawing.Rectangle-int-int-) |  |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) |  |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Maakt een nieuwe rechthoek aan vanuit twee punten. |
| [getEmpty()](#getEmpty--) | Haalt een nieuw exemplaar van de `Rectangle` structuur op waarvan de waarden van `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` en `Rectangle.Height` op nul zijn ingesteld. |
| [getX()](#getX--) | Haalt de x-coördinaat op van de linkerbovenhoek van deze Rectangle-structuur. |
| [setX(int value)](#setX-int-) | Stelt de x-coördinaat in van de linkerbovenhoek van deze Rectangle-structuur. |
| [getY()](#getY--) | Haalt de y-coördinaat op van de linkerbovenhoek van deze Rectangle-structuur. |
| [setY(int value)](#setY-int-) | Stelt de y-coördinaat in van de linkerbovenhoek van deze Rectangle-structuur. |
| [getLocation()](#getLocation--) | Haalt de coördinaten op van de linkerbovenhoek van deze [Rectangle](../../com.aspose.drawing/rectangle) structuur. |
| [setLocation(Point value)](#setLocation-com.aspose.drawing.Point-) | Stelt de coördinaten van de linkerbovenhoek van deze [Rectangle](../../com.aspose.drawing/rectangle) structuur in. |
| [getWidth()](#getWidth--) | Haalt de breedte van deze Rectangle-structuur op. |
| [setWidth(int value)](#setWidth-int-) | Stelt de breedte van deze Rectangle-structuur in. |
| [getHeight()](#getHeight--) | Haalt de hoogte van deze Rectangle-structuur op. |
| [setHeight(int value)](#setHeight-int-) | Stelt de hoogte van deze Rectangle-structuur in. |
| [getSize()](#getSize--) | Haalt de grootte van deze [Rectangle](../../com.aspose.drawing/rectangle) op. |
| [setSize(Size value)](#setSize-com.aspose.drawing.Size-) | Stelt de grootte van deze [Rectangle](../../com.aspose.drawing/rectangle) in. |
| [getLeft()](#getLeft--) | Haalt de x-coördinaat van de linkerkant van deze Rectangle-structuur op. |
| [getTop()](#getTop--) | Haalt de y-coördinaat van de bovenkant van deze Rectangle-structuur op. |
| [getRight()](#getRight--) | Haalt de x-coördinaat op die de som is van de X- en Breedte-eigenschapswaarden van deze Rectangle-structuur. |
| [getBottom()](#getBottom--) | Haalt de y-coördinaat op die de som is van de Y- en Hoogte-eigenschapswaarden van deze Rectangle-structuur. |
| [isEmpty()](#isEmpty--) | Haalt een waarde op die aangeeft of alle numerieke eigenschappen van deze [Rectangle](../../com.aspose.drawing/rectangle) nulwaarden hebben. |
| [equals(Object obj)](#equals-java.lang.Object-) | Test of obj een [Rectangle](../../com.aspose.drawing/rectangle)-structuur is met dezelfde locatie en grootte als deze [Rectangle](../../com.aspose.drawing/rectangle)-structuur. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze [Rectangle](../../com.aspose.drawing/rectangle)-structuur. |
| [toString()](#toString--) |  |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Vervangt deze [Rectangle](../../com.aspose.drawing/rectangle) door de doorsnede van zichzelf en de opgegeven [Rectangle](../../com.aspose.drawing/rectangle). |
| [inflate(int width, int height)](#inflate-int-int-) | Vergroot deze [Rectangle](../../com.aspose.drawing/rectangle) met de opgegeven hoeveelheid. |
| [inflate(Size size)](#inflate-com.aspose.drawing.Size-) | Vergroot deze [Rectangle](../../com.aspose.drawing/rectangle) met de opgegeven hoeveelheid. |
| [contains(int x, int y)](#contains-int-int-) | Bepaalt of het opgegeven punt zich binnen deze [Rectangle](../../com.aspose.drawing/rectangle)-structuur bevindt. |
| [contains(Point pt)](#contains-com.aspose.drawing.Point-) | Bepaalt of het opgegeven punt zich binnen deze [Rectangle](../../com.aspose.drawing/rectangle)-structuur bevindt. |
| [contains(Rectangle rect)](#contains-com.aspose.drawing.Rectangle-) |  |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.drawing.Rectangle-) | Bepaalt of deze rechthoek intersecteert met `rect`. |
| [offset(int x, int y)](#offset-int-int-) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| [offset(Point pos)](#offset-com.aspose.drawing.Point-) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| [equals(Rectangle other)](#equals-com.aspose.drawing.Rectangle-) | Test of een andere [Rectangle](../../com.aspose.drawing/rectangle)-structuur dezelfde locatie en grootte heeft als deze [Rectangle](../../com.aspose.drawing/rectangle)-structuur. |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.drawing.Rectangle-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [normalize()](#normalize--) | Normaliseert de rechthoek door de breedte en hoogte positief te maken, links kleiner dan rechts en boven kleiner dan onder. |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Initialiseert een nieuw exemplaar van de Rectangle-structuur met de opgegeven locatie en grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van de linkerbovenhoek van de rechthoek. |
| y | int | De y-coördinaat van de linkerbovenhoek van de rechthoek. |
| breedte | int | De breedte van de rechthoek. |
| hoogte | int | De hoogte van de rechthoek. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public Rectangle(Point location, Size size)
```


Initialiseert een nieuw exemplaar van de [Rectangle](../../com.aspose.drawing/rectangle) struct met de opgegeven locatie en grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| location | [Point](../../com.aspose.drawing/point) | Een [Point](../../com.aspose.drawing/point) die de linkerbovenhoek van het rechthoekige gebied weergeeft. |
| size | [Size](../../com.aspose.drawing/size) | Een `Size`([.getSize](../../null/\#getSize)/[.setSize(Size)](../../null/\#setSize-Size-)) die de breedte en hoogte van het rechthoekige gebied weergeeft. |

### fromLTRB(int left, int top, int right, int bottom) {#fromLTRB-int-int-int-int-}
```
public static Rectangle fromLTRB(int left, int top, int right, int bottom)
```


Maakt een [Rectangle](../../com.aspose.drawing/rectangle) structuur met de opgegeven randlocaties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | int | De x-coördinaat van de linkerbovenhoek van deze [Rectangle](../../com.aspose.drawing/rectangle)-structuur. |
| top | int | De y-coördinaat van de linkerbovenhoek van deze [Rectangle](../../com.aspose.drawing/rectangle)-structuur. |
| right | int | De x-coördinaat van de rechteronderhoek van deze [Rectangle](../../com.aspose.drawing/rectangle)-structuur. |
| bottom | int | De y-coördinaat van de rechteronderhoek van deze [Rectangle](../../com.aspose.drawing/rectangle)-structuur. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The new [Rectangle](../../com.aspose.drawing/rectangle) that this method creates.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Retourneert een derde [Rectangle](../../com.aspose.drawing/rectangle)-structuur die de intersectie van twee andere [Rectangle](../../com.aspose.drawing/rectangle)-structuren weergeeft. Als er geen intersectie is, wordt een lege [Rectangle](../../com.aspose.drawing/rectangle) geretourneerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | Eerste rechthoek om te intersecteren. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | Tweede rechthoek om te intersecteren. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the intersection of `a` and `b`.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Test of twee [Rectangle](../../com.aspose.drawing/rectangle) structuren dezelfde locatie en grootte hebben.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | De [Rectangle](../../com.aspose.drawing/rectangle)-structuur die zich links van de gelijkheidsoperator bevindt. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | De [Rectangle](../../com.aspose.drawing/rectangle)-structuur die zich rechts van de gelijkheidsoperator bevindt. |

**Returns:**
boolean - Deze operator retourneert `true` als de twee [Rectangle](../../com.aspose.drawing/rectangle)-structuren gelijke X-, Y-, Width- en Height-eigenschappen hebben.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Test of twee [Rectangle](../../com.aspose.drawing/rectangle) structuren verschillen in locatie of grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | De [Rectangle](../../com.aspose.drawing/rectangle)-structuur die zich links van de ongelijkheidsoperator bevindt. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | De [Rectangle](../../com.aspose.drawing/rectangle)-structuur die zich rechts van de ongelijkheidsoperator bevindt. |

**Returns:**
boolean - Deze operator retourneert `true` als een van de X-, Y-, Width- of Height-eigenschappen van de twee [Rectangle](../../com.aspose.drawing/rectangle)-structuren ongelijk zijn; anders `false`.
### ceiling(RectangleF value) {#ceiling-com.aspose.drawing.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Converteert de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) structuur naar een [Rectangle](../../com.aspose.drawing/rectangle) structuur door de [RectangleF](../../com.aspose.drawing/rectanglef) waarden af te ronden naar de volgende hogere gehele getallen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef)-structuur die moet worden geconverteerd. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - Returns a [Rectangle](../../com.aspose.drawing/rectangle).
### truncate(RectangleF value) {#truncate-com.aspose.drawing.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Converteert de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) naar een [Rectangle](../../com.aspose.drawing/rectangle) door de [RectangleF](../../com.aspose.drawing/rectanglef) waarden af te kappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef) die moet worden geconverteerd. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The truncated value of the [Rectangle](../../com.aspose.drawing/rectangle).
### round(RectangleF value) {#round-com.aspose.drawing.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Converteert de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) naar een [Rectangle](../../com.aspose.drawing/rectangle) door de [RectangleF](../../com.aspose.drawing/rectanglef) waarden af te ronden naar de dichtstbijzijnde gehele getallen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef) die moet worden geconverteerd. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle).
### union(Rectangle a, Rectangle b) {#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Haalt een [Rectangle](../../com.aspose.drawing/rectangle) structuur op die de unie van twee [Rectangle](../../com.aspose.drawing/rectangle) structuren bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | Een eerste rechthoek om te combineren. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | Een tweede rechthoek om te combineren. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) structure that bounds the union of the two [Rectangle](../../com.aspose.drawing/rectangle) structures.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.drawing.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Maakt een nieuwe rechthoek aan op basis van twee punten. De gemaakte rechthoek wordt genormaliseerd zodat (links,boven) lager is dan (rechts,onder).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | Het eerste punt. |
| point2 | [Point](../../com.aspose.drawing/point) | Het tweede punt. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A newly created rectangle.
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Haalt een nieuw exemplaar van de `Rectangle` structuur op waarvan de waarden van `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` en `Rectangle.Height` op nul zijn ingesteld.

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### getX() {#getX--}
```
public final int getX()
```


Haalt de x-coördinaat op van de linkerbovenhoek van deze Rectangle-structuur.

**Returns:**
int - de x-coördinaat van de linkerbovenhoek van deze Rectangle-structuur.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Stelt de x-coördinaat in van de linkerbovenhoek van deze Rectangle-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | de x-coördinaat van de linkerbovenhoek van deze Rectangle-structuur. |

### getY() {#getY--}
```
public final int getY()
```


Haalt de y-coördinaat op van de linkerbovenhoek van deze Rectangle-structuur.

**Returns:**
int - de y-coördinaat van de linkerbovenhoek van deze Rectangle-structuur.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Stelt de y-coördinaat in van de linkerbovenhoek van deze Rectangle-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | de y-coördinaat van de linkerbovenhoek van deze Rectangle-structuur. |

### getLocation() {#getLocation--}
```
public final Point getLocation()
```


Haalt de coördinaten op van de linkerbovenhoek van deze [Rectangle](../../com.aspose.drawing/rectangle) structuur.

**Returns:**
[Point](../../com.aspose.drawing/point) - the coordinates of the upper-left corner of this [Rectangle](../../com.aspose.drawing/rectangle) structure.
### setLocation(Point value) {#setLocation-com.aspose.drawing.Point-}
```
public final void setLocation(Point value)
```


Stelt de coördinaten van de linkerbovenhoek van deze [Rectangle](../../com.aspose.drawing/rectangle) structuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Point](../../com.aspose.drawing/point) | de coördinaten van de linkerbovenhoek van deze [Rectangle](../../com.aspose.drawing/rectangle)-structuur. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Haalt de breedte van deze Rectangle-structuur op.

**Returns:**
int - de breedte van deze Rectangle-structuur.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Stelt de breedte van deze Rectangle-structuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | de breedte van deze Rectangle-structuur. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Haalt de hoogte van deze Rectangle-structuur op.

**Returns:**
int - de hoogte van deze Rectangle-structuur.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Stelt de hoogte van deze Rectangle-structuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | de hoogte van deze Rectangle-structuur. |

### getSize() {#getSize--}
```
public final Size getSize()
```


Haalt de grootte van deze [Rectangle](../../com.aspose.drawing/rectangle) op.

**Returns:**
[Size](../../com.aspose.drawing/size) - the size of this [Rectangle](../../com.aspose.drawing/rectangle).
### setSize(Size value) {#setSize-com.aspose.drawing.Size-}
```
public final void setSize(Size value)
```


Stelt de grootte van deze [Rectangle](../../com.aspose.drawing/rectangle) in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Size](../../com.aspose.drawing/size) | de grootte van deze [Rectangle](../../com.aspose.drawing/rectangle). |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Haalt de x-coördinaat van de linkerkant van deze Rectangle-structuur op.

**Returns:**
int - de x-coördinaat van de linkerkant van deze Rectangle-structuur.
### getTop() {#getTop--}
```
public final int getTop()
```


Haalt de y-coördinaat van de bovenkant van deze Rectangle-structuur op.

**Returns:**
int - de y-coördinaat van de bovenkant van deze Rectangle-structuur.
### getRight() {#getRight--}
```
public final int getRight()
```


Haalt de x-coördinaat op die de som is van de X- en Breedte-eigenschapswaarden van deze Rectangle-structuur.

**Returns:**
int - de x-coördinaat die de som is van de X- en Width-eigenschapswaarden van deze Rectangle-structuur.
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Haalt de y-coördinaat op die de som is van de Y- en Hoogte-eigenschapswaarden van deze Rectangle-structuur.

**Returns:**
int - de y-coördinaat die de som is van de Y- en Height-eigenschapswaarden van deze Rectangle-structuur.
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Haalt een waarde op die aangeeft of alle numerieke eigenschappen van deze [Rectangle](../../com.aspose.drawing/rectangle) nulwaarden hebben.

**Returns:**
boolean - Deze eigenschap geeft `true` terug als de `Rectangle.Width`, `Rectangle.Height`, `Rectangle.X` en `Rectangle.Y` eigenschappen van deze [Rectangle](../../com.aspose.drawing/rectangle) allemaal de waarde nul hebben; anders `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Test of obj een [Rectangle](../../com.aspose.drawing/rectangle)-structuur is met dezelfde locatie en grootte als deze [Rectangle](../../com.aspose.drawing/rectangle)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te testen. |

**Returns:**
boolean - Deze methode geeft `true` terug als obj een [Rectangle](../../com.aspose.drawing/rectangle) structuur is en zijn X-, Y-, Width- en Height-eigenschappen gelijk zijn aan de overeenkomstige eigenschappen van deze [Rectangle](../../com.aspose.drawing/rectangle) structuur; anders `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze [Rectangle](../../com.aspose.drawing/rectangle) structuur. Voor informatie over het gebruik van hashcodes, zie GetHashCode.

**Returns:**
int - Een geheel getal dat de hashcode voor deze rechthoek vertegenwoordigt.
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


Vervangt deze [Rectangle](../../com.aspose.drawing/rectangle) door de doorsnede van zichzelf en de opgegeven [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | De [Rectangle](../../com.aspose.drawing/rectangle) waarmee moet worden intersecteerd. |

### inflate(int width, int height) {#inflate-int-int-}
```
public final void inflate(int width, int height)
```


Vergroot deze [Rectangle](../../com.aspose.drawing/rectangle) met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | int | De hoeveelheid om deze [Rectangle](../../com.aspose.drawing/rectangle) horizontaal uit te breiden. |
| height | int | De hoeveelheid om deze [Rectangle](../../com.aspose.drawing/rectangle) verticaal uit te breiden. |

### inflate(Size size) {#inflate-com.aspose.drawing.Size-}
```
public final void inflate(Size size)
```


Vergroot deze [Rectangle](../../com.aspose.drawing/rectangle) met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | De grootte om deze [Rectangle](../../com.aspose.drawing/rectangle) uit te breiden. |

### contains(int x, int y) {#contains-int-int-}
```
public final boolean contains(int x, int y)
```


Bepaalt of het opgegeven punt zich binnen deze [Rectangle](../../com.aspose.drawing/rectangle)-structuur bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van het te testen punt. |
| y | int | De y-coördinaat van het punt om te testen. |

**Returns:**
boolean - Deze methode geeft `true` terug als het punt gedefinieerd door `x` en `y` zich binnen deze [Rectangle](../../com.aspose.drawing/rectangle) structuur bevindt; anders `false`.
### contains(Point pt) {#contains-com.aspose.drawing.Point-}
```
public final boolean contains(Point pt)
```


Bepaalt of het opgegeven punt zich binnen deze [Rectangle](../../com.aspose.drawing/rectangle)-structuur bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Het [Point](../../com.aspose.drawing/point) om te testen. |

**Returns:**
boolean - Deze methode geeft `true` terug als het punt vertegenwoordigd door `pt` zich binnen deze [Rectangle](../../com.aspose.drawing/rectangle) structuur bevindt; anders `false`.
### contains(Rectangle rect) {#contains-com.aspose.drawing.Rectangle-}
```
public final boolean contains(Rectangle rect)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.drawing.Rectangle-}
```
public final boolean intersectsWith(Rectangle rect)
```


Bepaalt of deze rechthoek intersecteert met `rect`.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | De rechthoek om te testen. |

**Returns:**
boolean - Deze methode geeft true terug als er enige intersectie is, anders false.
### offset(int x, int y) {#offset-int-int-}
```
public final void offset(int x, int y)
```


Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De horizontale offset. |
| y | int | De verticale offset. |

### offset(Point pos) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point pos)
```


Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pos | [Point](../../com.aspose.drawing/point) | De offset. |

### equals(Rectangle other) {#equals-com.aspose.drawing.Rectangle-}
```
public final boolean equals(Rectangle other)
```


Test of een andere [Rectangle](../../com.aspose.drawing/rectangle)-structuur dezelfde locatie en grootte heeft als deze [Rectangle](../../com.aspose.drawing/rectangle)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.drawing/rectangle) | Andere rechthoek om te testen |

**Returns:**
boolean - Deze methode geeft `true` terug als de andere [Rectangle](../../com.aspose.drawing/rectangle) structuur en zijn X-, Y-, Width- en Height-eigenschappen gelijk zijn aan de overeenkomstige eigenschappen van deze [Rectangle](../../com.aspose.drawing/rectangle) structuur; anders `false`.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.drawing.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Normaliseert de rechthoek door de breedte en hoogte positief te maken, links kleiner dan rechts en boven kleiner dan onder.

