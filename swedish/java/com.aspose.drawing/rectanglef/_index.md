---
title: RectangleF
second_title: Aspose.Drawing för Java API‑referens
description: Lagrar en uppsättning av fyra flyttal som representerar positionen och storleken på en rektangel.
type: docs
weight: 39
url: /sv/java/com.aspose.drawing/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class RectangleF extends Struct<RectangleF> implements System.IEquatable<RectangleF>, Cloneable
```

Lagrar en uppsättning av fyra flyttal som representerar positionen och storleken på en rektangel. För mer avancerade regionfunktioner, använd ett Region-objekt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | Initierar en ny instans av RectangleF-strukturen med den angivna positionen och storleken. |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Initierar en ny instans av RectangleF-strukturen med den angivna positionen och storleken. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | Skapar en ny rektangel från två punkter. |
| [to_RectangleF(Rectangle r)](#to-RectangleF-com.aspose.drawing.Rectangle-) | Konverterar den angivna Rectangle-strukturen till en RectangleF-struktur. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Testar om två [RectangleF](../../com.aspose.drawing/rectanglef) strukturer har lika position och storlek. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Testar om två [RectangleF](../../com.aspose.drawing/rectanglef) strukturer skiljer sig i position eller storlek. |
| [fromLTRB(float left, float top, float right, float bottom)](#fromLTRB-float-float-float-float-) | Skapar en RectangleF-struktur med övre vänstra hörnet och nedre högra hörnet på de angivna positionerna. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.drawing.RectangleF-float-float-) | Skapar och returnerar en uppblåst kopia av den angivna [RectangleF](../../com.aspose.drawing/rectanglef) strukturen. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Returnerar en [RectangleF](../../com.aspose.drawing/rectanglef) struktur som representerar skärningspunkten mellan två rektanglar. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Skapar den minsta möjliga tredje rektangeln som kan innehålla båda två rektanglar som bildar en union. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om `RectangleF.Width` eller `RectangleF.Height`-egenskapen för denna [RectangleF](../../com.aspose.drawing/rectanglef) har värdet noll. |
| [getX()](#getX--) | Hämtar x-koordinaten för det övre vänstra hörnet av denna RectangleF-struktur. |
| [setX(float value)](#setX-float-) | Ställer in x-koordinaten för det övre vänstra hörnet av denna RectangleF-struktur. |
| [getY()](#getY--) | Hämtar x-koordinaten för det övre vänstra hörnet av denna RectangleF-struktur. |
| [setY(float value)](#setY-float-) | Ställer in x-koordinaten för det övre vänstra hörnet av denna RectangleF-struktur. |
| [getLocation()](#getLocation--) | Hämtar koordinaterna för det övre vänstra hörnet av denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur. |
| [setLocation(PointF value)](#setLocation-com.aspose.drawing.PointF-) | Ställer in koordinaterna för det övre vänstra hörnet av denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur. |
| [getWidth()](#getWidth--) | Hämtar bredden på denna RectangleF struktur. |
| [setWidth(float value)](#setWidth-float-) | Ställer in bredden på denna RectangleF struktur. |
| [getHeight()](#getHeight--) | Hämtar höjden på denna RectangleF struktur. |
| [setHeight(float value)](#setHeight-float-) | Ställer in höjden på denna RectangleF struktur. |
| [getSize()](#getSize--) | Hämtar storleken på denna [RectangleF](../../com.aspose.drawing/rectanglef). |
| [setSize(SizeF value)](#setSize-com.aspose.drawing.SizeF-) | Ställer in storleken på denna [RectangleF](../../com.aspose.drawing/rectanglef). |
| [getLeft()](#getLeft--) | Hämtar x-koordinaten för den vänstra kanten av denna RectangleF struktur. |
| [getTop()](#getTop--) | Hämtar y-koordinaten för den övre kanten av denna RectangleF struktur. |
| [getRight()](#getRight--) | Hämtar x-koordinaten som är summan av X och Width för denna RectangleF struktur. |
| [getBottom()](#getBottom--) | Hämtar y-koordinaten som är summan av Y och Height för denna RectangleF struktur. |
| [toString()](#toString--) |  |
| [inflate(float x, float y)](#inflate-float-float-) | Utökar denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur med den angivna mängden. |
| [inflate(SizeF size)](#inflate-com.aspose.drawing.SizeF-) | Utökar denna [RectangleF](../../com.aspose.drawing/rectanglef) med den angivna mängden. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Ersätter denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur med skärningspunkten mellan den själv och den angivna [RectangleF](../../com.aspose.drawing/rectanglef) strukturen. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.drawing.RectangleF-) | Avgör om detta rektangel skär med `rect`. |
| [offset(PointF pos)](#offset-com.aspose.drawing.PointF-) | Justerar placeringen av denna rektangel med den angivna mängden. |
| [offset(float x, float y)](#offset-float-float-) | Justerar placeringen av denna rektangel med den angivna mängden. |
| [contains(float x, float y)](#contains-float-float-) | Avgör om den angivna punkten finns inom denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur. |
| [contains(PointF pt)](#contains-com.aspose.drawing.PointF-) | Avgör om den angivna punkten finns inom denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur. |
| [contains(RectangleF rect)](#contains-com.aspose.drawing.RectangleF-) | Avgör om det rektangulära området som representeras av `rect` är helt innehållet inom denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur. |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om det angivna Object är lika med denna instans. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för denna instans. |
| [equals(RectangleF other)](#equals-com.aspose.drawing.RectangleF-) | Testar om en annan [RectangleF](../../com.aspose.drawing/rectanglef) struktur har samma placering och storlek som denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur. |
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


Initierar en ny instans av RectangleF-strukturen med den angivna positionen och storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location | [PointF](../../com.aspose.drawing/pointf) | En PointF som representerar det övre vänstra hörnet av det rektangulära området. |
| size | [SizeF](../../com.aspose.drawing/sizef) | En SizeF som representerar bredden och höjden på det rektangulära området. |

### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Initierar en ny instans av RectangleF-strukturen med den angivna positionen och storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | flyttal | x-koordinaten för det övre vänstra hörnet av rektangeln. |
| y | flyttal | Y-koordinaten för rektangelns övre vänstra hörn. |
| bredd | flyttal | Rektangelns bredd. |
| höjd | flyttal | Rektangelns höjd. |

### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Skapar en ny rektangel från två punkter. Den skapade rektangeln normaliseras så att (left,top) är lägre än (right,bottom).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | Den första punkten. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | Den andra punkten. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A newly created rectangle.
### to_RectangleF(Rectangle r) {#to-RectangleF-com.aspose.drawing.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle r)
```


Konverterar den angivna Rectangle-strukturen till en RectangleF-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| r | [Rectangle](../../com.aspose.drawing/rectangle) | Rectangle-strukturen att konvertera. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The RectangleF structure that is converted from the specified Rectangle structure.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Testar om två [RectangleF](../../com.aspose.drawing/rectanglef) strukturer har lika position och storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen som ligger till vänster om likhetsoperatorn. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen som ligger till höger om likhetsoperatorn. |

**Returns:**
boolean - Denna operator returnerar true om de två angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturerna har lika `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` och `RectangleF.Height`-egenskaper.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Testar om två [RectangleF](../../com.aspose.drawing/rectanglef) strukturer skiljer sig i position eller storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen som ligger till vänster om olikhetsoperatorn. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen som ligger till höger om olikhetsoperatorn. |

**Returns:**
boolean - Denna operator returnerar true om någon av `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` eller `RectangleF.Height`-egenskaperna hos de två [Rectangle](../../com.aspose.drawing/rectangle)-strukturerna är olika; annars false.
### fromLTRB(float left, float top, float right, float bottom) {#fromLTRB-float-float-float-float-}
```
public static RectangleF fromLTRB(float left, float top, float right, float bottom)
```


Skapar en RectangleF-struktur med övre vänstra hörnet och nedre högra hörnet på de angivna positionerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | flyttal | X-koordinaten för den rektangulära regionens övre vänstra hörn. |
| övre | flyttal | Y-koordinaten för den rektangulära regionens övre vänstra hörn. |
| höger | flyttal | X-koordinaten för den rektangulära regionens nedre högra hörn. |
| nedre | flyttal | Y-koordinaten för den rektangulära regionens nedre högra hörn. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The new RectangleF that this method creates.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.drawing.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Skapar och returnerar en uppblåst kopia av den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen. Kopian uppblåses med det angivna beloppet. Den ursprungliga rektangeln förblir oförändrad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef) som ska kopieras. Denna rektangel ändras inte. |
| x | flyttal | Mängden för att uppblåsa kopian av rektangeln horisontellt. |
| y | flyttal | Mängden att blåsa upp kopian av rektangeln vertikalt. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The inflated [RectangleF](../../com.aspose.drawing/rectanglef).
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Returnerar en [RectangleF](../../com.aspose.drawing/rectanglef)-struktur som representerar skärningspunkten mellan två rektanglar. Om det inte finns någon skärning returneras en tom [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Första rektangeln att skära. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Andra rektangeln att skära. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Skapar den minsta möjliga tredje rektangeln som kan innehålla båda två rektanglar som bildar en union.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Första rektangeln att förena. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Andra rektangeln att förena. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure that contains both of the two rectangles that form the union.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar ett värde som indikerar om `RectangleF.Width` eller `RectangleF.Height`-egenskapen för denna [RectangleF](../../com.aspose.drawing/rectanglef) har värdet noll.

**Returns:**
boolean - Denna egenskap returnerar true om `RectangleF.Width` eller `P:RectangleF.Height`-egenskapen för denna [RectangleF](../../com.aspose.drawing/rectanglef) har värdet noll; annars false.
### getX() {#getX--}
```
public final float getX()
```


Hämtar x-koordinaten för det övre vänstra hörnet av denna RectangleF-struktur.

**Returns:**
float - x-koordinaten för det övre vänstra hörnet av denna RectangleF-struktur.
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Ställer in x-koordinaten för det övre vänstra hörnet av denna RectangleF-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | flyttal | x-koordinaten för det övre vänstra hörnet av denna RectangleF-struktur. |

### getY() {#getY--}
```
public final float getY()
```


Hämtar x-koordinaten för det övre vänstra hörnet av denna RectangleF-struktur.

**Returns:**
float - x-koordinaten för det övre vänstra hörnet av denna RectangleF-struktur.
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Ställer in x-koordinaten för det övre vänstra hörnet av denna RectangleF-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | flyttal | x-koordinaten för det övre vänstra hörnet av denna RectangleF-struktur. |

### getLocation() {#getLocation--}
```
public final PointF getLocation()
```


Hämtar koordinaterna för det övre vänstra hörnet av denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur.

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - A [PointF](../../com.aspose.drawing/pointf) that represents the upper-left corner of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setLocation(PointF value) {#setLocation-com.aspose.drawing.PointF-}
```
public final void setLocation(PointF value)
```


Ställer in koordinaterna för det övre vänstra hörnet av denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | koordinaterna för det övre vänstra hörnet av denna [RectangleF](../../com.aspose.drawing/rectanglef)-struktur. |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Hämtar bredden på denna RectangleF struktur.

**Returns:**
float - bredden på denna RectangleF-struktur.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Ställer in bredden på denna RectangleF struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | flyttal | bredden på denna RectangleF-struktur. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Hämtar höjden på denna RectangleF struktur.

**Returns:**
float - höjden på denna RectangleF-struktur.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Ställer in höjden på denna RectangleF struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | flyttal | höjden på denna RectangleF-struktur. |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


Hämtar storleken på denna [RectangleF](../../com.aspose.drawing/rectanglef).

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that represents the width and height of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setSize(SizeF value) {#setSize-com.aspose.drawing.SizeF-}
```
public final void setSize(SizeF value)
```


Ställer in storleken på denna [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | storleken på denna [RectangleF](../../com.aspose.drawing/rectanglef). |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


Hämtar x-koordinaten för den vänstra kanten av denna RectangleF struktur.

**Returns:**
float - x-koordinaten för den vänstra kanten av denna RectangleF-struktur.
### getTop() {#getTop--}
```
public final float getTop()
```


Hämtar y-koordinaten för den övre kanten av denna RectangleF struktur.

**Returns:**
float - y-koordinaten för den övre kanten av denna RectangleF-struktur.
### getRight() {#getRight--}
```
public final float getRight()
```


Hämtar x-koordinaten som är summan av X och Width för denna RectangleF struktur.

**Returns:**
float - x-koordinaten som är summan av X och Width för denna RectangleF-struktur.
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Hämtar y-koordinaten som är summan av Y och Height för denna RectangleF struktur.

**Returns:**
float - y-koordinaten som är summan av Y och Height för denna RectangleF-struktur.
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


Utökar denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | Mängden att blåsa upp denna [RectangleF](../../com.aspose.drawing/rectanglef)-struktur horisontellt. |
| y | float | Mängden att blåsa upp denna [RectangleF](../../com.aspose.drawing/rectanglef)-struktur vertikalt. |

### inflate(SizeF size) {#inflate-com.aspose.drawing.SizeF-}
```
public final void inflate(SizeF size)
```


Utökar denna [RectangleF](../../com.aspose.drawing/rectanglef) med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | Mängden att blåsa upp denna rektangel. |

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public final void intersect(RectangleF rect)
```


Ersätter denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur med skärningspunkten mellan den själv och den angivna [RectangleF](../../com.aspose.drawing/rectanglef) strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Rektangeln att skära. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.drawing.RectangleF-}
```
public final boolean intersectsWith(RectangleF rect)
```


Avgör om detta rektangel skär med `rect`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Rektangeln att testa. |

**Returns:**
boolean - Denna metod returnerar true om det finns någon skärning.
### offset(PointF pos) {#offset-com.aspose.drawing.PointF-}
```
public final void offset(PointF pos)
```


Justerar placeringen av denna rektangel med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.drawing/pointf) | Mängden för att förskjuta platsen. |

### offset(float x, float y) {#offset-float-float-}
```
public final void offset(float x, float y)
```


Justerar placeringen av denna rektangel med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | flyttal | Mängden för att förskjuta platsen horisontellt. |
| y | flyttal | Mängden för att förskjuta platsen vertikalt. |

### contains(float x, float y) {#contains-float-float-}
```
public final boolean contains(float x, float y)
```


Avgör om den angivna punkten finns inom denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | flyttal | x-koordinaten för punkten som ska testas. |
| y | flyttal | y-koordinaten för punkten som ska testas. |

**Returns:**
boolean - Denna metod returnerar `true` om punkten definierad av x och y finns inom denna [RectangleF](../../com.aspose.drawing/rectanglef)-struktur; annars `false`.
### contains(PointF pt) {#contains-com.aspose.drawing.PointF-}
```
public final boolean contains(PointF pt)
```


Avgör om den angivna punkten finns inom denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | Den [PointF](../../com.aspose.drawing/pointf) att testa. |

**Returns:**
boolean - Denna metod returnerar `true` om punkten som representeras av parametern pt finns inom denna [RectangleF](../../com.aspose.drawing/rectanglef)-struktur; annars `false`.
### contains(RectangleF rect) {#contains-com.aspose.drawing.RectangleF-}
```
public final boolean contains(RectangleF rect)
```


Avgör om det rektangulära området som representeras av `rect` är helt innehållet inom denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef) att testa. |

**Returns:**
boolean - Denna metod returnerar `true` om det rektangulära området som representeras av `rect` är helt innehållet inom det rektangulära området som representeras av denna [RectangleF](../../com.aspose.drawing/rectanglef); annars `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Avgör om det angivna Object är lika med denna instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att jämföra med denna instans. |

**Returns:**
boolean - `true` om det angivna objektet är lika med denna instans; annars `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för denna instans.

**Returns:**
int - En hashkod för denna instans, lämplig för användning i hash-algoritmer och datastrukturer som en hash-tabell.
### equals(RectangleF other) {#equals-com.aspose.drawing.RectangleF-}
```
public final boolean equals(RectangleF other)
```


Testar om en annan [RectangleF](../../com.aspose.drawing/rectanglef) struktur har samma placering och storlek som denna [RectangleF](../../com.aspose.drawing/rectanglef) struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [RectangleF](../../com.aspose.drawing/rectanglef) | Annan rektangel att testa |

**Returns:**
boolean - Denna metod returnerar `true` om den andra [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen och dess X-, Y-, Width- och Height-egenskaper är lika med motsvarande egenskaper i denna [RectangleF](../../com.aspose.drawing/rectanglef)-struktur; annars `false`.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.drawing.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
