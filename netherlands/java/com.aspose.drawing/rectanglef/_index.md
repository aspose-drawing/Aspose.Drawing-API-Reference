---
title: RectangleF
second_title: Aspose.Drawing voor Java API-referentie
description: Slaat een set van vier zwevende-komma getallen op die de locatie en grootte van een rechthoek weergeven.
type: docs
weight: 39
url: /nl/java/com.aspose.drawing/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class RectangleF extends Struct<RectangleF> implements System.IEquatable<RectangleF>, Cloneable
```

Slaat een set van vier zwevende-kommagetallen op die de locatie en grootte van een rechthoek vertegenwoordigen. Voor meer geavanceerde regiofuncties, gebruik een Region-object.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | Initialiseert een nieuw exemplaar van de RectangleF-structuur met de opgegeven locatie en grootte. |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Initialiseert een nieuw exemplaar van de RectangleF-structuur met de opgegeven locatie en grootte. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | Maakt een nieuwe rechthoek aan vanuit twee punten. |
| [to_RectangleF(Rectangle r)](#to-RectangleF-com.aspose.drawing.Rectangle-) | Converteert de opgegeven Rectangle-structuur naar een RectangleF-structuur. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Test of twee [RectangleF](../../com.aspose.drawing/rectanglef) structuren dezelfde locatie en grootte hebben. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Test of twee [RectangleF](../../com.aspose.drawing/rectanglef) structuren verschillen in locatie of grootte. |
| [fromLTRB(float left, float top, float right, float bottom)](#fromLTRB-float-float-float-float-) | Maakt een RectangleF-structuur met de linkerbovenhoek en rechteronderhoek op de opgegeven locaties. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.drawing.RectangleF-float-float-) | Maakt en retourneert een opgeblazen kopie van de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) structuur. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Retourneert een [RectangleF](../../com.aspose.drawing/rectanglef) structuur die de intersectie van twee rechthoeken weergeeft. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Maakt de kleinste mogelijke derde rechthoek die beide van twee rechthoeken die een unie vormen, kan bevatten. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Haalt een waarde op die aangeeft of de `RectangleF.Width`- of `RectangleF.Height`-eigenschap van deze [RectangleF](../../com.aspose.drawing/rectanglef) een waarde van nul heeft. |
| [getX()](#getX--) | Haalt de x-coördinaat op van de linkerbovenhoek van deze RectangleF-structuur. |
| [setX(float value)](#setX-float-) | Stelt de x-coördinaat in van de linkerbovenhoek van deze RectangleF-structuur. |
| [getY()](#getY--) | Haalt de x-coördinaat op van de linkerbovenhoek van deze RectangleF-structuur. |
| [setY(float value)](#setY-float-) | Stelt de x-coördinaat in van de linkerbovenhoek van deze RectangleF-structuur. |
| [getLocation()](#getLocation--) | Haalt de coördinaten op van de linkerbovenhoek van deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur. |
| [setLocation(PointF value)](#setLocation-com.aspose.drawing.PointF-) | Stelt de coördinaten van de linkerbovenhoek van deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur in. |
| [getWidth()](#getWidth--) | Haalt de breedte van deze RectangleF-structuur op. |
| [setWidth(float value)](#setWidth-float-) | Stelt de breedte van deze RectangleF-structuur in. |
| [getHeight()](#getHeight--) | Haalt de hoogte van deze RectangleF-structuur op. |
| [setHeight(float value)](#setHeight-float-) | Stelt de hoogte van deze RectangleF-structuur in. |
| [getSize()](#getSize--) | Haalt de grootte van deze [RectangleF](../../com.aspose.drawing/rectanglef) op. |
| [setSize(SizeF value)](#setSize-com.aspose.drawing.SizeF-) | Stelt de grootte van deze [RectangleF](../../com.aspose.drawing/rectanglef) in. |
| [getLeft()](#getLeft--) | Haalt de x-coördinaat van de linkerkant van deze RectangleF-structuur op. |
| [getTop()](#getTop--) | Haalt de y-coördinaat van de bovenkant van deze RectangleF-structuur op. |
| [getRight()](#getRight--) | Haalt de x-coördinaat op die de som is van X en Width van deze RectangleF-structuur. |
| [getBottom()](#getBottom--) | Haalt de y-coördinaat op die de som is van Y en Height van deze RectangleF-structuur. |
| [toString()](#toString--) |  |
| [inflate(float x, float y)](#inflate-float-float-) | Vergroot deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur met de opgegeven hoeveelheid. |
| [inflate(SizeF size)](#inflate-com.aspose.drawing.SizeF-) | Vergroot deze [RectangleF](../../com.aspose.drawing/rectanglef) met de opgegeven hoeveelheid. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Vervangt deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur door de intersectie van zichzelf en de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) structuur. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.drawing.RectangleF-) | Bepaalt of deze rechthoek intersecteert met `rect`. |
| [offset(PointF pos)](#offset-com.aspose.drawing.PointF-) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| [offset(float x, float y)](#offset-float-float-) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| [contains(float x, float y)](#contains-float-float-) | Bepaalt of het opgegeven punt zich binnen deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur bevindt. |
| [contains(PointF pt)](#contains-com.aspose.drawing.PointF-) | Bepaalt of het opgegeven punt zich binnen deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur bevindt. |
| [contains(RectangleF rect)](#contains-com.aspose.drawing.RectangleF-) | Bepaalt of het rechthoekige gebied dat wordt weergegeven door `rect` volledig binnen deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur valt. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of het opgegeven Object gelijk is aan deze instantie. |
| [hashCode()](#hashCode--) | Retourneert een hashcode voor deze instantie. |
| [equals(RectangleF other)](#equals-com.aspose.drawing.RectangleF-) | Test of een andere [RectangleF](../../com.aspose.drawing/rectanglef) structuur dezelfde locatie en grootte heeft als deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur. |
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


Initialiseert een nieuw exemplaar van de RectangleF-structuur met de opgegeven locatie en grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| location | [PointF](../../com.aspose.drawing/pointf) | Een PointF die de linkerbovenhoek van het rechthoekige gebied weergeeft. |
| size | [SizeF](../../com.aspose.drawing/sizef) | Een SizeF die de breedte en hoogte van het rechthoekige gebied weergeeft. |

### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Initialiseert een nieuw exemplaar van de RectangleF-structuur met de opgegeven locatie en grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van de linkerbovenhoek van de rechthoek. |
| y | float | De y-coördinaat van de linkerbovenhoek van de rechthoek. |
| breedte | float | De breedte van de rechthoek. |
| hoogte | float | De hoogte van de rechthoek. |

### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Maakt een nieuwe rechthoek aan op basis van twee punten. De gemaakte rechthoek wordt genormaliseerd zodat (links,boven) lager is dan (rechts,onder).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | Het eerste punt. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | Het tweede punt. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A newly created rectangle.
### to_RectangleF(Rectangle r) {#to-RectangleF-com.aspose.drawing.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle r)
```


Converteert de opgegeven Rectangle-structuur naar een RectangleF-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| r | [Rectangle](../../com.aspose.drawing/rectangle) | De Rectangle-structuur om te converteren. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The RectangleF structure that is converted from the specified Rectangle structure.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Test of twee [RectangleF](../../com.aspose.drawing/rectanglef) structuren dezelfde locatie en grootte hebben.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef) structuur die links van de gelijkheidsoperator staat. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef) structuur die rechts van de gelijkheidsoperator staat. |

**Returns:**
boolean - Deze operator geeft true terug als de twee opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) structuren gelijke `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` en `RectangleF.Height` eigenschappen hebben.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Test of twee [RectangleF](../../com.aspose.drawing/rectanglef) structuren verschillen in locatie of grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef) structuur die links van de ongelijkheidsoperator staat. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef) structuur die rechts van de ongelijkheidsoperator staat. |

**Returns:**
boolean - Deze operator geeft true terug als een van de `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` of `RectangleF.Height` eigenschappen van de twee [Rectangle](../../com.aspose.drawing/rectangle) structuren ongelijk zijn; anders false.
### fromLTRB(float left, float top, float right, float bottom) {#fromLTRB-float-float-float-float-}
```
public static RectangleF fromLTRB(float left, float top, float right, float bottom)
```


Maakt een RectangleF-structuur met de linkerbovenhoek en rechteronderhoek op de opgegeven locaties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| links | float | De x-coördinaat van de linkerbovenhoek van het rechthoekige gebied. |
| boven | float | De y-coördinaat van de linkerbovenhoek van het rechthoekige gebied. |
| rechts | float | De x-coördinaat van de rechteronderhoek van het rechthoekige gebied. |
| onder | float | De y-coördinaat van de rechteronderhoek van het rechthoekige gebied. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The new RectangleF that this method creates.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.drawing.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Maakt en retourneert een opgeblazen kopie van de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) structuur. De kopie wordt opgeblazen met de opgegeven hoeveelheid. De originele rechthoek blijft ongewijzigd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef) die gekopieerd moet worden. Deze rechthoek wordt niet gewijzigd. |
| x | float | De hoeveelheid om de kopie van de rechthoek horizontaal op te blazen. |
| y | float | De hoeveelheid om de kopie van de rechthoek verticaal uit te zetten. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The inflated [RectangleF](../../com.aspose.drawing/rectanglef).
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Retourneert een [RectangleF](../../com.aspose.drawing/rectanglef) structuur die de intersectie van twee rechthoeken weergeeft. Als er geen intersectie is, wordt een lege [RectangleF](../../com.aspose.drawing/rectanglef) geretourneerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Eerste rechthoek om te intersecteren. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Tweede rechthoek om te intersecteren. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Maakt de kleinste mogelijke derde rechthoek die beide van twee rechthoeken die een unie vormen, kan bevatten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Eerste rechthoek om te verenigen. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Tweede rechthoek om te verenigen. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure that contains both of the two rectangles that form the union.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt een waarde op die aangeeft of de `RectangleF.Width`- of `RectangleF.Height`-eigenschap van deze [RectangleF](../../com.aspose.drawing/rectanglef) een waarde van nul heeft.

**Returns:**
boolean - Deze eigenschap retourneert true als de `RectangleF.Width` of `P:RectangleF.Height` eigenschap van deze [RectangleF](../../com.aspose.drawing/rectanglef) een waarde van nul heeft; anders false.
### getX() {#getX--}
```
public final float getX()
```


Haalt de x-coördinaat op van de linkerbovenhoek van deze RectangleF-structuur.

**Returns:**
float - de x-coördinaat van de linkerbovenhoek van deze RectangleF-structuur.
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Stelt de x-coördinaat in van de linkerbovenhoek van deze RectangleF-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | de x-coördinaat van de linkerbovenhoek van deze RectangleF-structuur. |

### getY() {#getY--}
```
public final float getY()
```


Haalt de x-coördinaat op van de linkerbovenhoek van deze RectangleF-structuur.

**Returns:**
float - de x-coördinaat van de linkerbovenhoek van deze RectangleF-structuur.
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Stelt de x-coördinaat in van de linkerbovenhoek van deze RectangleF-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | de x-coördinaat van de linkerbovenhoek van deze RectangleF-structuur. |

### getLocation() {#getLocation--}
```
public final PointF getLocation()
```


Haalt de coördinaten op van de linkerbovenhoek van deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur.

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - A [PointF](../../com.aspose.drawing/pointf) that represents the upper-left corner of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setLocation(PointF value) {#setLocation-com.aspose.drawing.PointF-}
```
public final void setLocation(PointF value)
```


Stelt de coördinaten van de linkerbovenhoek van deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | de coördinaten van de linkerbovenhoek van deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur. |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Haalt de breedte van deze RectangleF-structuur op.

**Returns:**
float - de breedte van deze RectangleF-structuur.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Stelt de breedte van deze RectangleF-structuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | de breedte van deze RectangleF-structuur. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Haalt de hoogte van deze RectangleF-structuur op.

**Returns:**
float - de hoogte van deze RectangleF-structuur.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Stelt de hoogte van deze RectangleF-structuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | de hoogte van deze RectangleF-structuur. |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


Haalt de grootte van deze [RectangleF](../../com.aspose.drawing/rectanglef) op.

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that represents the width and height of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setSize(SizeF value) {#setSize-com.aspose.drawing.SizeF-}
```
public final void setSize(SizeF value)
```


Stelt de grootte van deze [RectangleF](../../com.aspose.drawing/rectanglef) in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | de grootte van deze [RectangleF](../../com.aspose.drawing/rectanglef). |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


Haalt de x-coördinaat van de linkerkant van deze RectangleF-structuur op.

**Returns:**
float - de x-coördinaat van de linkerkant van deze RectangleF-structuur.
### getTop() {#getTop--}
```
public final float getTop()
```


Haalt de y-coördinaat van de bovenkant van deze RectangleF-structuur op.

**Returns:**
float - de y-coördinaat van de bovenkant van deze RectangleF-structuur.
### getRight() {#getRight--}
```
public final float getRight()
```


Haalt de x-coördinaat op die de som is van X en Width van deze RectangleF-structuur.

**Returns:**
float - de x-coördinaat die de som is van X en Width van deze RectangleF-structuur.
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Haalt de y-coördinaat op die de som is van Y en Height van deze RectangleF-structuur.

**Returns:**
float - de y-coördinaat die de som is van Y en Height van deze RectangleF-structuur.
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


Vergroot deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De hoeveelheid om deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur horizontaal uit te zetten. |
| y | float | De hoeveelheid om deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur verticaal uit te zetten. |

### inflate(SizeF size) {#inflate-com.aspose.drawing.SizeF-}
```
public final void inflate(SizeF size)
```


Vergroot deze [RectangleF](../../com.aspose.drawing/rectanglef) met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | De hoeveelheid om deze rechthoek uit te zetten. |

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public final void intersect(RectangleF rect)
```


Vervangt deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur door de intersectie van zichzelf en de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | De rechthoek om te intersecteren. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.drawing.RectangleF-}
```
public final boolean intersectsWith(RectangleF rect)
```


Bepaalt of deze rechthoek intersecteert met `rect`.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | De rechthoek om te testen. |

**Returns:**
boolean - Deze methode retourneert true als er enige intersectie is.
### offset(PointF pos) {#offset-com.aspose.drawing.PointF-}
```
public final void offset(PointF pos)
```


Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.drawing/pointf) | De hoeveelheid om de locatie te verschuiven. |

### offset(float x, float y) {#offset-float-float-}
```
public final void offset(float x, float y)
```


Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De hoeveelheid om de locatie horizontaal te verschuiven. |
| y | float | De hoeveelheid om de locatie verticaal te verschuiven. |

### contains(float x, float y) {#contains-float-float-}
```
public final boolean contains(float x, float y)
```


Bepaalt of het opgegeven punt zich binnen deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het punt om te testen. |
| y | float | De y-coördinaat van het punt om te testen. |

**Returns:**
boolean - Deze methode retourneert `true` als het punt gedefinieerd door x en y binnen deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur valt; anders `false`.
### contains(PointF pt) {#contains-com.aspose.drawing.PointF-}
```
public final boolean contains(PointF pt)
```


Bepaalt of het opgegeven punt zich binnen deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | Het [PointF](../../com.aspose.drawing/pointf) om te testen. |

**Returns:**
boolean - Deze methode retourneert `true` als het punt vertegenwoordigd door de pt-parameter binnen deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur valt; anders `false`.
### contains(RectangleF rect) {#contains-com.aspose.drawing.RectangleF-}
```
public final boolean contains(RectangleF rect)
```


Bepaalt of het rechthoekige gebied dat wordt weergegeven door `rect` volledig binnen deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur valt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef) om te testen. |

**Returns:**
boolean - Deze methode retourneert `true` als het rechthoekige gebied vertegenwoordigd door `rect` volledig binnen het rechthoekige gebied vertegenwoordigd door deze [RectangleF](../../com.aspose.drawing/rectanglef) valt; anders `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of het opgegeven Object gelijk is aan deze instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het Object om te vergelijken met deze instantie. |

**Returns:**
boolean - `true` als het opgegeven Object gelijk is aan deze instantie; anders `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor deze instantie.

**Returns:**
int - Een hashcode voor deze instantie, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel.
### equals(RectangleF other) {#equals-com.aspose.drawing.RectangleF-}
```
public final boolean equals(RectangleF other)
```


Test of een andere [RectangleF](../../com.aspose.drawing/rectanglef) structuur dezelfde locatie en grootte heeft als deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [RectangleF](../../com.aspose.drawing/rectanglef) | Andere rechthoek om te testen |

**Returns:**
boolean - Deze methode retourneert `true` als de andere [RectangleF](../../com.aspose.drawing/rectanglef) structuur en zijn X-, Y-, Breedte- en Hoogte-eigenschappen gelijk zijn aan de overeenkomstige eigenschappen van deze [RectangleF](../../com.aspose.drawing/rectanglef) structuur; anders `false`.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.drawing.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
