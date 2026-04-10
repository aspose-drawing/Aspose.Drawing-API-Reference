---
title: Rectangle
second_title: Riferimento API di Aspose.Drawing per Java
description: Memorizza un insieme di quattro interi che rappresentano la posizione e le dimensioni di un rettangolo.
type: docs
weight: 38
url: /it/java/com.aspose.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Rectangle extends Struct<Rectangle> implements System.IEquatable<Rectangle>, Cloneable
```

Memorizza un insieme di quattro interi che rappresentano la posizione e le dimensioni di un rettangolo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Inizializza una nuova istanza della struttura Rectangle con la posizione e le dimensioni specificate. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Inizializza una nuova istanza della struct [Rectangle](../../com.aspose.drawing/rectangle) con la posizione e le dimensioni specificate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [fromLTRB(int left, int top, int right, int bottom)](#fromLTRB-int-int-int-int-) | Crea una struttura [Rectangle](../../com.aspose.drawing/rectangle) con le posizioni dei bordi specificate. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Restituisce una terza struttura [Rectangle](../../com.aspose.drawing/rectangle) che rappresenta l'intersezione di altre due strutture [Rectangle](../../com.aspose.drawing/rectangle). |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Verifica se due strutture [Rectangle](../../com.aspose.drawing/rectangle) hanno la stessa posizione e dimensione. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Verifica se due strutture [Rectangle](../../com.aspose.drawing/rectangle) differiscono per posizione o dimensione. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.drawing.RectangleF-) | Converte la struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata in una struttura [Rectangle](../../com.aspose.drawing/rectangle) arrotondando i valori di [RectangleF](../../com.aspose.drawing/rectanglef) al successivo valore intero più alto. |
| [truncate(RectangleF value)](#truncate-com.aspose.drawing.RectangleF-) | Converte il [RectangleF](../../com.aspose.drawing/rectanglef) specificato in un [Rectangle](../../com.aspose.drawing/rectangle) troncando i valori di [RectangleF](../../com.aspose.drawing/rectanglef). |
| [round(RectangleF value)](#round-com.aspose.drawing.RectangleF-) | Converte il [RectangleF](../../com.aspose.drawing/rectanglef) specificato in un [Rectangle](../../com.aspose.drawing/rectangle) arrotondando i valori di [RectangleF](../../com.aspose.drawing/rectanglef) al valore intero più vicino. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Ottiene una struttura [Rectangle](../../com.aspose.drawing/rectangle) che contiene l'unione di due strutture [Rectangle](../../com.aspose.drawing/rectangle). |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.drawing.Rectangle-int-int-) |  |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) |  |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Crea un nuovo rettangolo da due punti. |
| [getEmpty()](#getEmpty--) | Ottiene una nuova istanza della struttura `Rectangle` con i valori `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` e `Rectangle.Height` impostati a zero. |
| [getX()](#getX--) | Ottiene la coordinata x dell'angolo superiore sinistro di questa struttura Rectangle. |
| [setX(int value)](#setX-int-) | Imposta la coordinata x dell'angolo superiore sinistro di questa struttura Rectangle. |
| [getY()](#getY--) | Ottiene la coordinata y dell'angolo superiore sinistro di questa struttura Rectangle. |
| [setY(int value)](#setY-int-) | Imposta la coordinata y dell'angolo superiore sinistro di questa struttura Rectangle. |
| [getLocation()](#getLocation--) | Ottiene le coordinate dell'angolo superiore sinistro di questa struttura [Rectangle](../../com.aspose.drawing/rectangle). |
| [setLocation(Point value)](#setLocation-com.aspose.drawing.Point-) | Imposta le coordinate dell'angolo superiore sinistro di questa struttura [Rectangle](../../com.aspose.drawing/rectangle). |
| [getWidth()](#getWidth--) | Restituisce la larghezza di questa struttura Rectangle. |
| [setWidth(int value)](#setWidth-int-) | Imposta la larghezza di questa struttura Rectangle. |
| [getHeight()](#getHeight--) | Restituisce l'altezza di questa struttura Rectangle. |
| [setHeight(int value)](#setHeight-int-) | Imposta l'altezza di questa struttura Rectangle. |
| [getSize()](#getSize--) | Restituisce le dimensioni di questa [Rectangle](../../com.aspose.drawing/rectangle). |
| [setSize(Size value)](#setSize-com.aspose.drawing.Size-) | Imposta le dimensioni di questa [Rectangle](../../com.aspose.drawing/rectangle). |
| [getLeft()](#getLeft--) | Restituisce la coordinata x del bordo sinistro di questa struttura Rectangle. |
| [getTop()](#getTop--) | Restituisce la coordinata y del bordo superiore di questa struttura Rectangle. |
| [getRight()](#getRight--) | Restituisce la coordinata x che è la somma dei valori delle proprietà X e Width di questa struttura Rectangle. |
| [getBottom()](#getBottom--) | Restituisce la coordinata y che è la somma dei valori delle proprietà Y e Height di questa struttura Rectangle. |
| [isEmpty()](#isEmpty--) | Restituisce un valore che indica se tutte le proprietà numeriche di questo [Rectangle](../../com.aspose.drawing/rectangle) hanno valore zero. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se obj è una struttura [Rectangle](../../com.aspose.drawing/rectangle) con la stessa posizione e dimensione di questa struttura [Rectangle](../../com.aspose.drawing/rectangle). |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa struttura [Rectangle](../../com.aspose.drawing/rectangle). |
| [toString()](#toString--) |  |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Sostituisce questo [Rectangle](../../com.aspose.drawing/rectangle) con l'intersezione di sé stesso e del [Rectangle](../../com.aspose.drawing/rectangle) specificato. |
| [inflate(int width, int height)](#inflate-int-int-) | Ingrandisce questo [Rectangle](../../com.aspose.drawing/rectangle) dell'importo specificato. |
| [inflate(Size size)](#inflate-com.aspose.drawing.Size-) | Ingrandisce questo [Rectangle](../../com.aspose.drawing/rectangle) dell'importo specificato. |
| [contains(int x, int y)](#contains-int-int-) | Determina se il punto specificato è contenuto all'interno di questa struttura [Rectangle](../../com.aspose.drawing/rectangle). |
| [contains(Point pt)](#contains-com.aspose.drawing.Point-) | Determina se il punto specificato è contenuto all'interno di questa struttura [Rectangle](../../com.aspose.drawing/rectangle). |
| [contains(Rectangle rect)](#contains-com.aspose.drawing.Rectangle-) |  |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.drawing.Rectangle-) | Determina se questo rettangolo interseca con `rect`. |
| [offset(int x, int y)](#offset-int-int-) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [offset(Point pos)](#offset-com.aspose.drawing.Point-) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [equals(Rectangle other)](#equals-com.aspose.drawing.Rectangle-) | Verifica se un'altra struttura [Rectangle](../../com.aspose.drawing/rectangle) ha la stessa posizione e dimensione di questa struttura [Rectangle](../../com.aspose.drawing/rectangle). |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.drawing.Rectangle-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [normalize()](#normalize--) | Normalizza il rettangolo rendendo la sua larghezza e altezza positive, sinistra minore di destra e superiore minore di inferiore. |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Inizializza una nuova istanza della struttura Rectangle con la posizione e le dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x dell'angolo superiore sinistro del rettangolo. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo. |
| width | int | La larghezza del rettangolo. |
| height | int | L'altezza del rettangolo. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public Rectangle(Point location, Size size)
```


Inizializza una nuova istanza della struct [Rectangle](../../com.aspose.drawing/rectangle) con la posizione e le dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| location | [Point](../../com.aspose.drawing/point) | Un [Point](../../com.aspose.drawing/point) che rappresenta l'angolo superiore sinistro della regione rettangolare. |
| size | [Size](../../com.aspose.drawing/size) | Un `Size`([.getSize](../../null/\#getSize)/[.setSize(Size)](../../null/\#setSize-Size-)) che rappresenta la larghezza e l'altezza della regione rettangolare. |

### fromLTRB(int left, int top, int right, int bottom) {#fromLTRB-int-int-int-int-}
```
public static Rectangle fromLTRB(int left, int top, int right, int bottom)
```


Crea una struttura [Rectangle](../../com.aspose.drawing/rectangle) con le posizioni dei bordi specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | int | La coordinata x dell'angolo superiore sinistro di questa struttura [Rectangle](../../com.aspose.drawing/rectangle). |
| top | int | La coordinata y dell'angolo superiore sinistro di questa struttura [Rectangle](../../com.aspose.drawing/rectangle). |
| right | int | La coordinata x dell'angolo inferiore destro di questa struttura [Rectangle](../../com.aspose.drawing/rectangle). |
| bottom | int | La coordinata y dell'angolo inferiore destro di questa struttura [Rectangle](../../com.aspose.drawing/rectangle). |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The new [Rectangle](../../com.aspose.drawing/rectangle) that this method creates.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Restituisce una terza struttura [Rectangle](../../com.aspose.drawing/rectangle) che rappresenta l'intersezione di altre due strutture [Rectangle](../../com.aspose.drawing/rectangle). Se non vi è alcuna intersezione, viene restituita una [Rectangle](../../com.aspose.drawing/rectangle) vuota.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | Primo rettangolo da intersecare. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | Secondo rettangolo da intersecare. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the intersection of `a` and `b`.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Verifica se due strutture [Rectangle](../../com.aspose.drawing/rectangle) hanno la stessa posizione e dimensione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | La struttura [Rectangle](../../com.aspose.drawing/rectangle) che si trova a sinistra dell'operatore di uguaglianza. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | La struttura [Rectangle](../../com.aspose.drawing/rectangle) che si trova a destra dell'operatore di uguaglianza. |

**Returns:**
boolean - Questo operatore restituisce `true` se le due strutture [Rectangle](../../com.aspose.drawing/rectangle) hanno proprietà X, Y, Width e Height uguali.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Verifica se due strutture [Rectangle](../../com.aspose.drawing/rectangle) differiscono per posizione o dimensione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | La struttura [Rectangle](../../com.aspose.drawing/rectangle) che si trova a sinistra dell'operatore di disuguaglianza. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | La struttura [Rectangle](../../com.aspose.drawing/rectangle) che si trova a destra dell'operatore di disuguaglianza. |

**Returns:**
boolean - Questo operatore restituisce `true` se una qualsiasi delle proprietà X, Y, Width o Height delle due strutture [Rectangle](../../com.aspose.drawing/rectangle) è diversa; altrimenti `false`.
### ceiling(RectangleF value) {#ceiling-com.aspose.drawing.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Converte la struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata in una struttura [Rectangle](../../com.aspose.drawing/rectangle) arrotondando i valori di [RectangleF](../../com.aspose.drawing/rectanglef) al successivo valore intero più alto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | La struttura [RectangleF](../../com.aspose.drawing/rectanglef) da convertire. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - Returns a [Rectangle](../../com.aspose.drawing/rectangle).
### truncate(RectangleF value) {#truncate-com.aspose.drawing.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Converte il [RectangleF](../../com.aspose.drawing/rectanglef) specificato in un [Rectangle](../../com.aspose.drawing/rectangle) troncando i valori di [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | Il [RectangleF](../../com.aspose.drawing/rectanglef) da convertire. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The truncated value of the [Rectangle](../../com.aspose.drawing/rectangle).
### round(RectangleF value) {#round-com.aspose.drawing.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Converte il [RectangleF](../../com.aspose.drawing/rectanglef) specificato in un [Rectangle](../../com.aspose.drawing/rectangle) arrotondando i valori di [RectangleF](../../com.aspose.drawing/rectanglef) al valore intero più vicino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | Il [RectangleF](../../com.aspose.drawing/rectanglef) da convertire. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle).
### union(Rectangle a, Rectangle b) {#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Ottiene una struttura [Rectangle](../../com.aspose.drawing/rectangle) che contiene l'unione di due strutture [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | Il primo rettangolo da unire. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | Il secondo rettangolo da unire. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) structure that bounds the union of the two [Rectangle](../../com.aspose.drawing/rectangle) structures.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.drawing.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Crea un nuovo rettangolo da due punti. Il rettangolo creato sarà normalizzato con (left,top) inferiore a (right,bottom).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | Il primo punto. |
| point2 | [Point](../../com.aspose.drawing/point) | Il secondo punto. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A newly created rectangle.
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Ottiene una nuova istanza della struttura `Rectangle` con i valori `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` e `Rectangle.Height` impostati a zero.

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### getX() {#getX--}
```
public final int getX()
```


Ottiene la coordinata x dell'angolo superiore sinistro di questa struttura Rectangle.

**Returns:**
int - la coordinata x dell'angolo superiore sinistro di questa struttura Rectangle.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Imposta la coordinata x dell'angolo superiore sinistro di questa struttura Rectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | la coordinata x dell'angolo superiore sinistro di questa struttura Rectangle. |

### getY() {#getY--}
```
public final int getY()
```


Ottiene la coordinata y dell'angolo superiore sinistro di questa struttura Rectangle.

**Returns:**
int - la coordinata y dell'angolo superiore sinistro di questa struttura Rectangle.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Imposta la coordinata y dell'angolo superiore sinistro di questa struttura Rectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | la coordinata y dell'angolo superiore sinistro di questa struttura Rectangle. |

### getLocation() {#getLocation--}
```
public final Point getLocation()
```


Ottiene le coordinate dell'angolo superiore sinistro di questa struttura [Rectangle](../../com.aspose.drawing/rectangle).

**Returns:**
[Point](../../com.aspose.drawing/point) - the coordinates of the upper-left corner of this [Rectangle](../../com.aspose.drawing/rectangle) structure.
### setLocation(Point value) {#setLocation-com.aspose.drawing.Point-}
```
public final void setLocation(Point value)
```


Imposta le coordinate dell'angolo superiore sinistro di questa struttura [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.drawing/point) | le coordinate dell'angolo superiore sinistro di questa struttura [Rectangle](../../com.aspose.drawing/rectangle). |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Restituisce la larghezza di questa struttura Rectangle.

**Returns:**
int - la larghezza di questa struttura Rectangle.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Imposta la larghezza di questa struttura Rectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | la larghezza di questa struttura Rectangle. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Restituisce l'altezza di questa struttura Rectangle.

**Returns:**
int - l'altezza di questa struttura Rectangle.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Imposta l'altezza di questa struttura Rectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | l'altezza di questa struttura Rectangle. |

### getSize() {#getSize--}
```
public final Size getSize()
```


Restituisce le dimensioni di questa [Rectangle](../../com.aspose.drawing/rectangle).

**Returns:**
[Size](../../com.aspose.drawing/size) - the size of this [Rectangle](../../com.aspose.drawing/rectangle).
### setSize(Size value) {#setSize-com.aspose.drawing.Size-}
```
public final void setSize(Size value)
```


Imposta le dimensioni di questa [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Size](../../com.aspose.drawing/size) | la dimensione di questo [Rectangle](../../com.aspose.drawing/rectangle). |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Restituisce la coordinata x del bordo sinistro di questa struttura Rectangle.

**Returns:**
int - la coordinata x del bordo sinistro di questa struttura Rectangle.
### getTop() {#getTop--}
```
public final int getTop()
```


Restituisce la coordinata y del bordo superiore di questa struttura Rectangle.

**Returns:**
int - la coordinata y del bordo superiore di questa struttura Rectangle.
### getRight() {#getRight--}
```
public final int getRight()
```


Restituisce la coordinata x che è la somma dei valori delle proprietà X e Width di questa struttura Rectangle.

**Returns:**
int - la coordinata x che è la somma dei valori delle proprietà X e Width di questa struttura Rectangle.
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Restituisce la coordinata y che è la somma dei valori delle proprietà Y e Height di questa struttura Rectangle.

**Returns:**
int - la coordinata y che è la somma dei valori delle proprietà Y e Height di questa struttura Rectangle.
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Restituisce un valore che indica se tutte le proprietà numeriche di questo [Rectangle](../../com.aspose.drawing/rectangle) hanno valore zero.

**Returns:**
boolean - Questa proprietà restituisce `true` se le proprietà `Rectangle.Width`, `Rectangle.Height`, `Rectangle.X` e `Rectangle.Y` di questo [Rectangle](../../com.aspose.drawing/rectangle) hanno tutti valore zero; altrimenti, `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se obj è una struttura [Rectangle](../../com.aspose.drawing/rectangle) con la stessa posizione e dimensione di questa struttura [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'Object da testare. |

**Returns:**
boolean - Questo metodo restituisce `true` se obj è una struttura [Rectangle](../../com.aspose.drawing/rectangle) e le sue proprietà X, Y, Width e Height sono uguali alle corrispondenti proprietà di questa struttura [Rectangle](../../com.aspose.drawing/rectangle); altrimenti, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa struttura [Rectangle](../../com.aspose.drawing/rectangle). Per informazioni sull'uso dei codici hash, vedere GetHashCode.

**Returns:**
int - Un intero che rappresenta il codice hash per questo rettangolo.
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


Sostituisce questo [Rectangle](../../com.aspose.drawing/rectangle) con l'intersezione di sé stesso e del [Rectangle](../../com.aspose.drawing/rectangle) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Il [Rectangle](../../com.aspose.drawing/rectangle) con cui eseguire l'intersezione. |

### inflate(int width, int height) {#inflate-int-int-}
```
public final void inflate(int width, int height)
```


Ingrandisce questo [Rectangle](../../com.aspose.drawing/rectangle) dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La quantità di espansione orizzontale di questo [Rectangle](../../com.aspose.drawing/rectangle). |
| height | int | La quantità di espansione verticale di questo [Rectangle](../../com.aspose.drawing/rectangle). |

### inflate(Size size) {#inflate-com.aspose.drawing.Size-}
```
public final void inflate(Size size)
```


Ingrandisce questo [Rectangle](../../com.aspose.drawing/rectangle) dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | La dimensione dell'espansione di questo [Rectangle](../../com.aspose.drawing/rectangle). |

### contains(int x, int y) {#contains-int-int-}
```
public final boolean contains(int x, int y)
```


Determina se il punto specificato è contenuto all'interno di questa struttura [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |

**Returns:**
boolean - Questo metodo restituisce `true` se il punto definito da `x` e `y` è contenuto all'interno di questa struttura [Rectangle](../../com.aspose.drawing/rectangle); altrimenti `false`.
### contains(Point pt) {#contains-com.aspose.drawing.Point-}
```
public final boolean contains(Point pt)
```


Determina se il punto specificato è contenuto all'interno di questa struttura [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Il [Point](../../com.aspose.drawing/point) da testare. |

**Returns:**
boolean - Questo metodo restituisce `true` se il punto rappresentato da `pt` è contenuto all'interno di questa struttura [Rectangle](../../com.aspose.drawing/rectangle); altrimenti `false`.
### contains(Rectangle rect) {#contains-com.aspose.drawing.Rectangle-}
```
public final boolean contains(Rectangle rect)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.drawing.Rectangle-}
```
public final boolean intersectsWith(Rectangle rect)
```


Determina se questo rettangolo interseca con `rect`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Il rettangolo da testare. |

**Returns:**
boolean - Questo metodo restituisce true se esiste qualche intersezione, altrimenti false.
### offset(int x, int y) {#offset-int-int-}
```
public final void offset(int x, int y)
```


Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | L'offset orizzontale. |
| y | int | L'offset verticale. |

### offset(Point pos) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point pos)
```


Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pos | [Point](../../com.aspose.drawing/point) | L'offset. |

### equals(Rectangle other) {#equals-com.aspose.drawing.Rectangle-}
```
public final boolean equals(Rectangle other)
```


Verifica se un'altra struttura [Rectangle](../../com.aspose.drawing/rectangle) ha la stessa posizione e dimensione di questa struttura [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.drawing/rectangle) | Altro rettangolo da testare |

**Returns:**
boolean - Questo metodo restituisce `true` se l'altra struttura [Rectangle](../../com.aspose.drawing/rectangle) e le sue proprietà X, Y, Width e Height sono uguali alle corrispondenti proprietà di questa struttura [Rectangle](../../com.aspose.drawing/rectangle); altrimenti, `false`.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.drawing.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Normalizza il rettangolo rendendo la sua larghezza e altezza positive, sinistra minore di destra e superiore minore di inferiore.

