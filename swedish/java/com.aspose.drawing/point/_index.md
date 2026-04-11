---
title: Point
second_title: Aspose.Drawing för Java API‑referens
description: Representerar ett ordnat par av heltals‑x‑ och y‑koordinater som definierar en punkt i ett tvådimensionellt plan.
type: docs
weight: 36
url: /sv/java/com.aspose.drawing/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Point extends Struct<Point> implements System.IEquatable<Point>, Cloneable
```

Representerar ett ordnat par av heltals‑x‑ och y‑koordinater som definierar en punkt i ett tvådimensionellt plan.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Initierar en ny instans av strukturen [Point](../../com.aspose.drawing/point) med de angivna koordinaterna. |
| [Point(Size sz)](#Point-com.aspose.drawing.Size-) |  |
| [Point(int dw)](#Point-int-) | Initierar en ny instans av strukturen [Point](../../com.aspose.drawing/point) med koordinater som anges av ett heltalsvärde. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [EMPTY](#EMPTY) | Representerar en [Point](../../com.aspose.drawing/point) som har `Point.X`- och `Point.Y`-värden satta till noll. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [to_PointF(Point p)](#to-PointF-com.aspose.drawing.Point-) | Konverterar den angivna [Point](../../com.aspose.drawing/point)-strukturen till en [PointF](../../com.aspose.drawing/pointf)-struktur. |
| [to_Size(Point p)](#to-Size-com.aspose.drawing.Point-) |  |
| [op_Addition(Point pt, Size sz)](#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Subtraction(Point pt, Size sz)](#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Equality(Point left, Point right)](#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Jämför två [Point](../../com.aspose.drawing/point)-objekt. |
| [op_Inequality(Point left, Point right)](#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Jämför två [Point](../../com.aspose.drawing/point)-objekt. |
| [add(Point pt, Size sz)](#add-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Lägger till den angivna [Size](../../com.aspose.drawing/size) till den angivna [Point](../../com.aspose.drawing/point). |
| [subtract(Point pt, Size sz)](#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [ceiling(PointF value)](#ceiling-com.aspose.drawing.PointF-) |  |
| [truncate(PointF value)](#truncate-com.aspose.drawing.PointF-) | Konverterar en PointF till en Point genom att utföra en trunkeringsoperation på alla koordinater. |
| [round(PointF value)](#round-com.aspose.drawing.PointF-) | Konverterar den angivna [PointF](../../com.aspose.drawing/pointf) till ett Point-objekt genom att avrunda [Point](../../com.aspose.drawing/point)-värdena till närmaste heltal. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-) |  |
| [getEmpty()](#getEmpty--) |  |
| [getX()](#getX--) | Hämtar x-koordinaten för detta Point. |
| [setX(int value)](#setX-int-) | Ställer in x-koordinaten för detta Point. |
| [getY()](#getY--) | Hämtar y-koordinaten för detta Point. |
| [setY(int value)](#setY-int-) | Ställer in y-koordinaten för detta Point. |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om detta detta [Point](../../com.aspose.drawing/point) är tomt. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta [Point](../../com.aspose.drawing/point). |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Anger om detta [Point](../../com.aspose.drawing/point) innehåller samma koordinater som det angivna objektet. |
| [offset(int dx, int dy)](#offset-int-int-) | Översätter detta [Point](../../com.aspose.drawing/point) med den angivna mängden. |
| [offset(Point p)](#offset-com.aspose.drawing.Point-) | Översätter detta [Point](../../com.aspose.drawing/point) med den angivna [Point](../../com.aspose.drawing/point). |
| [equals(Point other)](#equals-com.aspose.drawing.Point-) | Testar om en annan [Point](../../com.aspose.drawing/point)-struktur har samma plats som denna [Point](../../com.aspose.drawing/point)-struktur. |
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


Initierar en ny instans av strukturen [Point](../../com.aspose.drawing/point) med de angivna koordinaterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Den horisontella positionen för punkten. |
| y | int | Den vertikala positionen för punkten. |

### Point(Size sz) {#Point-com.aspose.drawing.Size-}
```
public Point(Size sz)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sz | [Size](../../com.aspose.drawing/size) |  |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Initierar en ny instans av strukturen [Point](../../com.aspose.drawing/point) med koordinater som anges av ett heltalsvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dw | int | Det heltalsvärdet. |

### EMPTY {#EMPTY}
```
public static final Point EMPTY
```


Representerar en [Point](../../com.aspose.drawing/point) som har `Point.X`- och `Point.Y`-värden satta till noll.

### to_PointF(Point p) {#to-PointF-com.aspose.drawing.Point-}
```
public static PointF to_PointF(Point p)
```


Konverterar den angivna [Point](../../com.aspose.drawing/point)-strukturen till en [PointF](../../com.aspose.drawing/pointf)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | Den [Point](../../com.aspose.drawing/point) som ska konverteras. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The [PointF](../../com.aspose.drawing/pointf) that results from the conversion.
### to_Size(Point p) {#to-Size-com.aspose.drawing.Point-}
```
public static Size to_Size(Point p)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
[Size](../../com.aspose.drawing/size)
### op_Addition(Point pt, Size sz) {#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Addition(Point pt, Size sz)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Equality(Point left, Point right) {#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Equality(Point left, Point right)
```


Jämför två [Point](../../com.aspose.drawing/point)-objekt. Resultatet anger om värdena för `Point.X`- och `Point.Y`-egenskaperna för de två [Point](../../com.aspose.drawing/point)-objekten är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Första [Point](../../com.aspose.drawing/point) att jämföra. |
| right | [Point](../../com.aspose.drawing/point) | Andra [Point](../../com.aspose.drawing/point) att jämföra. |

**Returns:**
boolean - sant om `Point.X`- och `Point.Y`-värdena för `left` och `right` är lika; annars falskt.
### op_Inequality(Point left, Point right) {#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Inequality(Point left, Point right)
```


Jämför två [Point](../../com.aspose.drawing/point)-objekt. Resultatet anger om värdena för `Point.X`- eller `Point.Y`-egenskaperna för de två [Point](../../com.aspose.drawing/point)-objekten är olika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Första [Point](../../com.aspose.drawing/point) att jämföra. |
| right | [Point](../../com.aspose.drawing/point) | Andra [Point](../../com.aspose.drawing/point) att jämföra. |

**Returns:**
boolean - sant om värdena för antingen `Point.X`-egenskaperna eller `Point.Y`-egenskaperna för `left` och `right` skiljer sig; annars falskt.
### add(Point pt, Size sz) {#add-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point add(Point pt, Size sz)
```


Lägger till den angivna [Size](../../com.aspose.drawing/size) till den angivna [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Den [Point](../../com.aspose.drawing/point) som ska läggas till. |
| sz | [Size](../../com.aspose.drawing/size) | Den [Size](../../com.aspose.drawing/size) som ska läggas till. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the addition operation.
### subtract(Point pt, Size sz) {#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point subtract(Point pt, Size sz)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### truncate(PointF value) {#truncate-com.aspose.drawing.PointF-}
```
public static Point truncate(PointF value)
```


Konverterar en PointF till en Point genom att utföra en trunkeringsoperation på alla koordinater.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Den [PointF](../../com.aspose.drawing/pointf) som ska trunkeras. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the truncate operation.
### round(PointF value) {#round-com.aspose.drawing.PointF-}
```
public static Point round(PointF value)
```


Konverterar den angivna [PointF](../../com.aspose.drawing/pointf) till ett Point-objekt genom att avrunda [Point](../../com.aspose.drawing/point)-värdena till närmaste heltal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Den [PointF](../../com.aspose.drawing/pointf) som ska konverteras. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) this method converts to.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar x-koordinaten för detta Point.

**Returns:**
int - x-koordinaten för detta Point.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Ställer in x-koordinaten för detta Point.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | x-koordinaten för detta Point. |

### getY() {#getY--}
```
public final int getY()
```


Hämtar y-koordinaten för detta Point.

**Returns:**
int - y-koordinaten för detta Point.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Ställer in y-koordinaten för detta Point.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | y-koordinaten för detta Point. |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Hämtar ett värde som indikerar om detta detta [Point](../../com.aspose.drawing/point) är tomt.

Värde: `true` om både X och Y är 0; annars `false`.

**Returns:**
boolean - ett värde som indikerar om detta [Point](../../com.aspose.drawing/point) är tomt.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta [Point](../../com.aspose.drawing/point).

**Returns:**
int - ett heltalsvärde som specificerar ett hashvärde för detta [Point](../../com.aspose.drawing/point).
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


Anger om detta [Point](../../com.aspose.drawing/point) innehåller samma koordinater som det angivna objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att testa. |

**Returns:**
boolean - `true` om obj är ett Point och har samma koordinater som detta [Point](../../com.aspose.drawing/point).
### offset(int dx, int dy) {#offset-int-int-}
```
public final void offset(int dx, int dy)
```


Översätter detta [Point](../../com.aspose.drawing/point) med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | int | Mängden att förskjuta x-koordinaten. |
| dy | int | Mängden att förskjuta y-koordinaten. |

### offset(Point p) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point p)
```


Översätter detta [Point](../../com.aspose.drawing/point) med den angivna [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | Den [Point](../../com.aspose.drawing/point) som används för att förskjuta detta [Point](../../com.aspose.drawing/point). |

### equals(Point other) {#equals-com.aspose.drawing.Point-}
```
public final boolean equals(Point other)
```


Testar om en annan [Point](../../com.aspose.drawing/point)-struktur har samma plats som denna [Point](../../com.aspose.drawing/point)-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [Point](../../com.aspose.drawing/point) | Annan punkt att testa |

**Returns:**
boolean - Denna metod returnerar `true` om en annan [Point](../../com.aspose.drawing/point)-struktur och dess X- och Y-egenskaper är lika med motsvarande egenskaper i denna [Point](../../com.aspose.drawing/point)-struktur; annars `false`.
### CloneTo(Point that) {#CloneTo-com.aspose.drawing.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
