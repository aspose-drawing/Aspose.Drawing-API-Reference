---
title: Punto
second_title: Riferimento API di Aspose.Drawing per Java
description: Rappresenta una coppia ordinata di coordinate intere x e y che definisce un punto in un piano bidimensionale.
type: docs
weight: 36
url: /it/java/com.aspose.drawing/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Point extends Struct<Point> implements System.IEquatable<Point>, Cloneable
```

Rappresenta una coppia ordinata di coordinate intere x e y che definisce un punto in un piano bidimensionale.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Inizializza una nuova istanza della struct [Point](../../com.aspose.drawing/point) con le coordinate specificate. |
| [Point(Size sz)](#Point-com.aspose.drawing.Size-) |  |
| [Point(int dw)](#Point-int-) | Inizializza una nuova istanza della struct [Point](../../com.aspose.drawing/point) utilizzando coordinate specificate da un valore intero. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [EMPTY](#EMPTY) | Rappresenta un [Point](../../com.aspose.drawing/point) che ha i valori `Point.X` e `Point.Y` impostati a zero. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [to_PointF(Point p)](#to-PointF-com.aspose.drawing.Point-) | Converte la struttura [Point](../../com.aspose.drawing/point) specificata in una struttura [PointF](../../com.aspose.drawing/pointf). |
| [to_Size(Point p)](#to-Size-com.aspose.drawing.Point-) |  |
| [op_Addition(Point pt, Size sz)](#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Subtraction(Point pt, Size sz)](#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Equality(Point left, Point right)](#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Confronta due oggetti [Point](../../com.aspose.drawing/point). |
| [op_Inequality(Point left, Point right)](#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Confronta due oggetti [Point](../../com.aspose.drawing/point). |
| [add(Point pt, Size sz)](#add-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Aggiunge la [Size](../../com.aspose.drawing/size) specificata al [Point](../../com.aspose.drawing/point) specificato. |
| [subtract(Point pt, Size sz)](#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [ceiling(PointF value)](#ceiling-com.aspose.drawing.PointF-) |  |
| [truncate(PointF value)](#truncate-com.aspose.drawing.PointF-) | Converte un PointF in un Point eseguendo un'operazione di troncamento su tutte le coordinate. |
| [round(PointF value)](#round-com.aspose.drawing.PointF-) | Converte il [PointF](../../com.aspose.drawing/pointf) specificato in un oggetto Point arrotondando i valori del [Point](../../com.aspose.drawing/point) al numero intero più vicino. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-) |  |
| [getEmpty()](#getEmpty--) |  |
| [getX()](#getX--) | Restituisce la coordinata x di questo Point. |
| [setX(int value)](#setX-int-) | Imposta la coordinata x di questo Point. |
| [getY()](#getY--) | Restituisce la coordinata y di questo Point. |
| [setY(int value)](#setY-int-) | Imposta la coordinata y di questo Point. |
| [isEmpty()](#isEmpty--) | Restituisce un valore che indica se questo [Point](../../com.aspose.drawing/point) è vuoto. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questo [Point](../../com.aspose.drawing/point). |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Specifica se questo [Point](../../com.aspose.drawing/point) contiene le stesse coordinate dell'oggetto specificato. |
| [offset(int dx, int dy)](#offset-int-int-) | Trasla questo [Point](../../com.aspose.drawing/point) dell'importo specificato. |
| [offset(Point p)](#offset-com.aspose.drawing.Point-) | Trasla questo [Point](../../com.aspose.drawing/point) del [Point](../../com.aspose.drawing/point) specificato. |
| [equals(Point other)](#equals-com.aspose.drawing.Point-) | Verifica se un'altra struttura [Point](../../com.aspose.drawing/point) ha la stessa posizione di questa struttura [Point](../../com.aspose.drawing/point). |
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


Inizializza una nuova istanza della struct [Point](../../com.aspose.drawing/point) con le coordinate specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La posizione orizzontale del punto. |
| y | int | La posizione verticale del punto. |

### Point(Size sz) {#Point-com.aspose.drawing.Size-}
```
public Point(Size sz)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sz | [Size](../../com.aspose.drawing/size) |  |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Inizializza una nuova istanza della struct [Point](../../com.aspose.drawing/point) utilizzando coordinate specificate da un valore intero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dw | int | Il valore intero. |

### EMPTY {#EMPTY}
```
public static final Point EMPTY
```


Rappresenta un [Point](../../com.aspose.drawing/point) che ha i valori `Point.X` e `Point.Y` impostati a zero.

### to_PointF(Point p) {#to-PointF-com.aspose.drawing.Point-}
```
public static PointF to_PointF(Point p)
```


Converte la struttura [Point](../../com.aspose.drawing/point) specificata in una struttura [PointF](../../com.aspose.drawing/pointf).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | Il [Point](../../com.aspose.drawing/point) da convertire. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The [PointF](../../com.aspose.drawing/pointf) that results from the conversion.
### to_Size(Point p) {#to-Size-com.aspose.drawing.Point-}
```
public static Size to_Size(Point p)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
[Size](../../com.aspose.drawing/size)
### op_Addition(Point pt, Size sz) {#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Addition(Point pt, Size sz)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Equality(Point left, Point right) {#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Equality(Point left, Point right)
```


Confronta due oggetti [Point](../../com.aspose.drawing/point). Il risultato specifica se i valori delle proprietà `Point.X` e `Point.Y` dei due oggetti [Point](../../com.aspose.drawing/point) sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Primo [Point](../../com.aspose.drawing/point) da confrontare. |
| right | [Point](../../com.aspose.drawing/point) | Secondo [Point](../../com.aspose.drawing/point) da confrontare. |

**Returns:**
boolean - true se i valori `Point.X` e `Point.Y` di `left` e `right` sono uguali; altrimenti, false.
### op_Inequality(Point left, Point right) {#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Inequality(Point left, Point right)
```


Confronta due oggetti [Point](../../com.aspose.drawing/point). Il risultato specifica se i valori delle proprietà `Point.X` o `Point.Y` dei due oggetti [Point](../../com.aspose.drawing/point) sono diversi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Primo [Point](../../com.aspose.drawing/point) da confrontare. |
| right | [Point](../../com.aspose.drawing/point) | Secondo [Point](../../com.aspose.drawing/point) da confrontare. |

**Returns:**
boolean - true se i valori di una delle proprietà `Point.X` o `Point.Y` di `left` e `right` differiscono; altrimenti, false.
### add(Point pt, Size sz) {#add-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point add(Point pt, Size sz)
```


Aggiunge la [Size](../../com.aspose.drawing/size) specificata al [Point](../../com.aspose.drawing/point) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Il [Point](../../com.aspose.drawing/point) da aggiungere. |
| sz | [Size](../../com.aspose.drawing/size) | Il [Size](../../com.aspose.drawing/size) da aggiungere |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the addition operation.
### subtract(Point pt, Size sz) {#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point subtract(Point pt, Size sz)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### truncate(PointF value) {#truncate-com.aspose.drawing.PointF-}
```
public static Point truncate(PointF value)
```


Converte un PointF in un Point eseguendo un'operazione di troncamento su tutte le coordinate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Il [PointF](../../com.aspose.drawing/pointf) da troncare. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the truncate operation.
### round(PointF value) {#round-com.aspose.drawing.PointF-}
```
public static Point round(PointF value)
```


Converte il [PointF](../../com.aspose.drawing/pointf) specificato in un oggetto Point arrotondando i valori del [Point](../../com.aspose.drawing/point) al numero intero più vicino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Il [PointF](../../com.aspose.drawing/pointf) da convertire. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) this method converts to.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Restituisce la coordinata x di questo Point.

**Returns:**
int - la coordinata x di questo Point.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Imposta la coordinata x di questo Point.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | la coordinata x di questo Point. |

### getY() {#getY--}
```
public final int getY()
```


Restituisce la coordinata y di questo Point.

**Returns:**
int - la coordinata y di questo Point.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Imposta la coordinata y di questo Point.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | la coordinata y di questo Point. |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Restituisce un valore che indica se questo [Point](../../com.aspose.drawing/point) è vuoto.

Valore: `true` se sia X che Y sono 0; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se questo [Point](../../com.aspose.drawing/point) è vuoto.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questo [Point](../../com.aspose.drawing/point).

**Returns:**
int - Un valore intero che specifica un valore hash per questo [Point](../../com.aspose.drawing/point).
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


Specifica se questo [Point](../../com.aspose.drawing/point) contiene le stesse coordinate dell'oggetto specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'Object da testare. |

**Returns:**
boolean - `true` se obj è un Point e ha le stesse coordinate di questo [Point](../../com.aspose.drawing/point).
### offset(int dx, int dy) {#offset-int-int-}
```
public final void offset(int dx, int dy)
```


Trasla questo [Point](../../com.aspose.drawing/point) dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | int | La quantità per spostare la coordinata x. |
| dy | int | La quantità per spostare la coordinata y. |

### offset(Point p) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point p)
```


Trasla questo [Point](../../com.aspose.drawing/point) del [Point](../../com.aspose.drawing/point) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | Il [Point](../../com.aspose.drawing/point) usato per spostare questo [Point](../../com.aspose.drawing/point). |

### equals(Point other) {#equals-com.aspose.drawing.Point-}
```
public final boolean equals(Point other)
```


Verifica se un'altra struttura [Point](../../com.aspose.drawing/point) ha la stessa posizione di questa struttura [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [Point](../../com.aspose.drawing/point) | Altro punto da testare |

**Returns:**
boolean - Questo metodo restituisce `true` se la struttura [Point](../../com.aspose.drawing/point) esterna e le sue proprietà X e Y sono uguali alle corrispondenti proprietà di questa struttura [Point](../../com.aspose.drawing/point); altrimenti, `false`.
### CloneTo(Point that) {#CloneTo-com.aspose.drawing.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
