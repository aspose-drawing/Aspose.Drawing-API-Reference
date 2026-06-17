---
title: RectangleF
second_title: Riferimento API di Aspose.Drawing per Java
description: Memorizza un insieme di quattro numeri in virgola mobile che rappresentano la posizione e le dimensioni di un rettangolo.
type: docs
weight: 39
url: /it/java/com.aspose.drawing/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class RectangleF extends Struct<RectangleF> implements System.IEquatable<RectangleF>, Cloneable
```

Memorizza un insieme di quattro numeri a virgola mobile che rappresentano la posizione e le dimensioni di un rettangolo. Per funzioni di regione più avanzate, usa un oggetto Region.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | Inizializza una nuova istanza della struttura RectangleF con la posizione e le dimensioni specificate. |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Inizializza una nuova istanza della struttura RectangleF con la posizione e le dimensioni specificate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | Crea un nuovo rettangolo da due punti. |
| [to_RectangleF(Rectangle r)](#to-RectangleF-com.aspose.drawing.Rectangle-) | Converte la struttura Rectangle specificata in una struttura RectangleF. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Verifica se due strutture [RectangleF](../../com.aspose.drawing/rectanglef) hanno posizione e dimensioni uguali. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Verifica se due strutture [RectangleF](../../com.aspose.drawing/rectanglef) differiscono per posizione o dimensioni. |
| [fromLTRB(float left, float top, float right, float bottom)](#fromLTRB-float-float-float-float-) | Crea una struttura RectangleF con l'angolo superiore sinistro e l'angolo inferiore destro nelle posizioni specificate. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.drawing.RectangleF-float-float-) | Crea e restituisce una copia ingrandita della struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Restituisce una struttura [RectangleF](../../com.aspose.drawing/rectanglef) che rappresenta l'intersezione di due rettangoli. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Crea il terzo rettangolo più piccolo possibile che può contenere entrambi i due rettangoli che formano un'unione. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Ottiene un valore che indica se la proprietà `RectangleF.Width` o `RectangleF.Height` di questo [RectangleF](../../aspose.drawing/rectanglef) ha valore zero. |
| [getX()](#getX--) | Ottiene la coordinata x dell'angolo superiore sinistro di questa struttura RectangleF. |
| [setX(float value)](#setX-float-) | Imposta la coordinata x dell'angolo superiore sinistro di questa struttura RectangleF. |
| [getY()](#getY--) | Ottiene la coordinata x dell'angolo superiore sinistro di questa struttura RectangleF. |
| [setY(float value)](#setY-float-) | Imposta la coordinata x dell'angolo superiore sinistro di questa struttura RectangleF. |
| [getLocation()](#getLocation--) | Ottiene le coordinate dell'angolo superiore sinistro di questa struttura [RectangleF](../../aspose.drawing/rectanglef). |
| [setLocation(PointF value)](#setLocation-com.aspose.drawing.PointF-) | Imposta le coordinate dell'angolo superiore sinistro di questa struttura [RectangleF](../../com.aspose.drawing/rectanglef). |
| [getWidth()](#getWidth--) | Restituisce la larghezza di questa struttura RectangleF. |
| [setWidth(float value)](#setWidth-float-) | Imposta la larghezza di questa struttura RectangleF. |
| [getHeight()](#getHeight--) | Restituisce l'altezza di questa struttura RectangleF. |
| [setHeight(float value)](#setHeight-float-) | Imposta l'altezza di questa struttura RectangleF. |
| [getSize()](#getSize--) | Restituisce le dimensioni di questa [RectangleF](../../com.aspose.drawing/rectanglef). |
| [setSize(SizeF value)](#setSize-com.aspose.drawing.SizeF-) | Imposta le dimensioni di questa [RectangleF](../../com.aspose.drawing/rectanglef). |
| [getLeft()](#getLeft--) | Restituisce la coordinata x del bordo sinistro di questa struttura RectangleF. |
| [getTop()](#getTop--) | Restituisce la coordinata y del bordo superiore di questa struttura RectangleF. |
| [getRight()](#getRight--) | Restituisce la coordinata x che è la somma di X e Width di questa struttura RectangleF. |
| [getBottom()](#getBottom--) | Restituisce la coordinata y che è la somma di Y e Height di questa struttura RectangleF. |
| [toString()](#toString--) |  |
| [inflate(float x, float y)](#inflate-float-float-) | Ingrandisce questa struttura [RectangleF](../../com.aspose.drawing/rectanglef) dell'importo specificato. |
| [inflate(SizeF size)](#inflate-com.aspose.drawing.SizeF-) | Ingrandisce questa [RectangleF](../../com.aspose.drawing/rectanglef) dell'importo specificato. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Sostituisce questa struttura [RectangleF](../../com.aspose.drawing/rectanglef) con l'intersezione di sé stessa e della struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.drawing.RectangleF-) | Determina se questo rettangolo interseca con `rect`. |
| [offset(PointF pos)](#offset-com.aspose.drawing.PointF-) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [offset(float x, float y)](#offset-float-float-) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [contains(float x, float y)](#contains-float-float-) | Determina se il punto specificato è contenuto all'interno di questa struttura [RectangleF](../../com.aspose.drawing/rectanglef). |
| [contains(PointF pt)](#contains-com.aspose.drawing.PointF-) | Determina se il punto specificato è contenuto all'interno di questa struttura [RectangleF](../../com.aspose.drawing/rectanglef). |
| [contains(RectangleF rect)](#contains-com.aspose.drawing.RectangleF-) | Determina se la regione rettangolare rappresentata da `rect` è interamente contenuta all'interno di questa struttura [RectangleF](../../com.aspose.drawing/rectanglef). |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'Object specificato è uguale a questa istanza. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
| [equals(RectangleF other)](#equals-com.aspose.drawing.RectangleF-) | Verifica se un'altra struttura [RectangleF](../../com.aspose.drawing/rectanglef) ha la stessa posizione e dimensione di questa struttura [RectangleF](../../com.aspose.drawing/rectanglef). |
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


Inizializza una nuova istanza della struttura RectangleF con la posizione e le dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| location | [PointF](../../com.aspose.drawing/pointf) | Un PointF che rappresenta l'angolo superiore sinistro della regione rettangolare. |
| size | [SizeF](../../com.aspose.drawing/sizef) | Un SizeF che rappresenta la larghezza e l'altezza della regione rettangolare. |

### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Inizializza una nuova istanza della struttura RectangleF con la posizione e le dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x dell'angolo superiore sinistro del rettangolo. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo. |
| width | float | La larghezza del rettangolo. |
| height | float | L'altezza del rettangolo. |

### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Crea un nuovo rettangolo da due punti. Il rettangolo creato sarà normalizzato con (left,top) inferiore a (right,bottom).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | Il primo punto. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | Il secondo punto. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A newly created rectangle.
### to_RectangleF(Rectangle r) {#to-RectangleF-com.aspose.drawing.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle r)
```


Converte la struttura Rectangle specificata in una struttura RectangleF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| r | [Rectangle](../../com.aspose.drawing/rectangle) | La struttura Rectangle da convertire. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The RectangleF structure that is converted from the specified Rectangle structure.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Verifica se due strutture [RectangleF](../../com.aspose.drawing/rectanglef) hanno posizione e dimensioni uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | La struttura [RectangleF](../../com.aspose.drawing/rectanglef) che si trova a sinistra dell'operatore di uguaglianza. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | La struttura [RectangleF](../../com.aspose.drawing/rectanglef) che si trova a destra dell'operatore di uguaglianza. |

**Returns:**
boolean - Questo operatore restituisce true se le due strutture [RectangleF](../../com.aspose.drawing/rectanglef) specificate hanno proprietà `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` e `RectangleF.Height` uguali.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Verifica se due strutture [RectangleF](../../com.aspose.drawing/rectanglef) differiscono per posizione o dimensioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | La struttura [RectangleF](../../com.aspose.drawing/rectanglef) che si trova a sinistra dell'operatore di disuguaglianza. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | La struttura [RectangleF](../../com.aspose.drawing/rectanglef) che si trova a destra dell'operatore di disuguaglianza. |

**Returns:**
boolean - Questo operatore restituisce true se una qualsiasi delle proprietà `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` o `RectangleF.Height` delle due strutture [Rectangle](../../com.aspose.drawing/rectangle) è diversa; altrimenti false.
### fromLTRB(float left, float top, float right, float bottom) {#fromLTRB-float-float-float-float-}
```
public static RectangleF fromLTRB(float left, float top, float right, float bottom)
```


Crea una struttura RectangleF con l'angolo superiore sinistro e l'angolo inferiore destro nelle posizioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sinistra | float | La coordinata x dell'angolo superiore sinistro della regione rettangolare. |
| superiore | float | La coordinata y dell'angolo superiore sinistro della regione rettangolare. |
| destra | float | La coordinata x dell'angolo inferiore destro della regione rettangolare. |
| inferiore | float | La coordinata y dell'angolo inferiore destro della regione rettangolare. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The new RectangleF that this method creates.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.drawing.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Crea e restituisce una copia ingrandita della struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata. La copia è ingrandita della quantità specificata. Il rettangolo originale rimane invariato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Il [RectangleF](../../com.aspose.drawing/rectanglef) da copiare. Questo rettangolo non viene modificato. |
| x | float | La quantità con cui ingrandire orizzontalmente la copia del rettangolo. |
| y | float | La quantità per ingrandire verticalmente la copia del rettangolo. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The inflated [RectangleF](../../com.aspose.drawing/rectanglef).
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Restituisce una struttura [RectangleF](../../com.aspose.drawing/rectanglef) che rappresenta l'intersezione di due rettangoli. Se non vi è alcuna intersezione, viene restituita una [RectangleF](../../com.aspose.drawing/rectanglef) vuota.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Primo rettangolo da intersecare. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Secondo rettangolo da intersecare. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Crea il terzo rettangolo più piccolo possibile che può contenere entrambi i due rettangoli che formano un'unione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Primo rettangolo da unire. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Secondo rettangolo da unire. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure that contains both of the two rectangles that form the union.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Ottiene un valore che indica se la proprietà `RectangleF.Width` o `RectangleF.Height` di questo [RectangleF](../../aspose.drawing/rectanglef) ha valore zero.

**Returns:**
boolean - Questa proprietà restituisce true se la proprietà `RectangleF.Width` o `P:RectangleF.Height` di questa [RectangleF](../../com.aspose.drawing/rectanglef) ha valore zero; altrimenti, false.
### getX() {#getX--}
```
public final float getX()
```


Ottiene la coordinata x dell'angolo superiore sinistro di questa struttura RectangleF.

**Returns:**
float - la coordinata x dell'angolo superiore sinistro di questa struttura RectangleF.
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Imposta la coordinata x dell'angolo superiore sinistro di questa struttura RectangleF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float | la coordinata x dell'angolo superiore sinistro di questa struttura RectangleF. |

### getY() {#getY--}
```
public final float getY()
```


Ottiene la coordinata x dell'angolo superiore sinistro di questa struttura RectangleF.

**Returns:**
float - la coordinata x dell'angolo superiore sinistro di questa struttura RectangleF.
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Imposta la coordinata x dell'angolo superiore sinistro di questa struttura RectangleF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float | la coordinata x dell'angolo superiore sinistro di questa struttura RectangleF. |

### getLocation() {#getLocation--}
```
public final PointF getLocation()
```


Ottiene le coordinate dell'angolo superiore sinistro di questa struttura [RectangleF](../../aspose.drawing/rectanglef).

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - A [PointF](../../com.aspose.drawing/pointf) that represents the upper-left corner of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setLocation(PointF value) {#setLocation-com.aspose.drawing.PointF-}
```
public final void setLocation(PointF value)
```


Imposta le coordinate dell'angolo superiore sinistro di questa struttura [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | le coordinate dell'angolo superiore sinistro di questa struttura [RectangleF](../../com.aspose.drawing/rectanglef). |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Restituisce la larghezza di questa struttura RectangleF.

**Returns:**
float - la larghezza di questa struttura RectangleF.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Imposta la larghezza di questa struttura RectangleF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float | la larghezza di questa struttura RectangleF. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Restituisce l'altezza di questa struttura RectangleF.

**Returns:**
float - l'altezza di questa struttura RectangleF.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Imposta l'altezza di questa struttura RectangleF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float | l'altezza di questa struttura RectangleF. |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


Restituisce le dimensioni di questa [RectangleF](../../com.aspose.drawing/rectanglef).

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that represents the width and height of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setSize(SizeF value) {#setSize-com.aspose.drawing.SizeF-}
```
public final void setSize(SizeF value)
```


Imposta le dimensioni di questa [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | la dimensione di questa [RectangleF](../../com.aspose.drawing/rectanglef). |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


Restituisce la coordinata x del bordo sinistro di questa struttura RectangleF.

**Returns:**
float - la coordinata x del bordo sinistro di questa struttura RectangleF.
### getTop() {#getTop--}
```
public final float getTop()
```


Restituisce la coordinata y del bordo superiore di questa struttura RectangleF.

**Returns:**
float - la coordinata y del bordo superiore di questa struttura RectangleF.
### getRight() {#getRight--}
```
public final float getRight()
```


Restituisce la coordinata x che è la somma di X e Width di questa struttura RectangleF.

**Returns:**
float - la coordinata x che è la somma di X e Width di questa struttura RectangleF.
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Restituisce la coordinata y che è la somma di Y e Height di questa struttura RectangleF.

**Returns:**
float - la coordinata y che è la somma di Y e Height di questa struttura RectangleF.
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


Ingrandisce questa struttura [RectangleF](../../com.aspose.drawing/rectanglef) dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La quantità per ingrandire orizzontalmente questa struttura [RectangleF](../../com.aspose.drawing/rectanglef). |
| y | float | La quantità per ingrandire verticalmente questa struttura [RectangleF](../../com.aspose.drawing/rectanglef). |

### inflate(SizeF size) {#inflate-com.aspose.drawing.SizeF-}
```
public final void inflate(SizeF size)
```


Ingrandisce questa [RectangleF](../../com.aspose.drawing/rectanglef) dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | La quantità per ingrandire questo rettangolo. |

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public final void intersect(RectangleF rect)
```


Sostituisce questa struttura [RectangleF](../../com.aspose.drawing/rectanglef) con l'intersezione di sé stessa e della struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Il rettangolo da intersecare. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.drawing.RectangleF-}
```
public final boolean intersectsWith(RectangleF rect)
```


Determina se questo rettangolo interseca con `rect`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Il rettangolo da testare. |

**Returns:**
boolean - Questo metodo restituisce true se esiste qualche intersezione.
### offset(PointF pos) {#offset-com.aspose.drawing.PointF-}
```
public final void offset(PointF pos)
```


Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.drawing/pointf) | La quantità di spostamento della posizione. |

### offset(float x, float y) {#offset-float-float-}
```
public final void offset(float x, float y)
```


Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La quantità di spostamento della posizione orizzontalmente. |
| y | float | La quantità di spostamento della posizione verticalmente. |

### contains(float x, float y) {#contains-float-float-}
```
public final boolean contains(float x, float y)
```


Determina se il punto specificato è contenuto all'interno di questa struttura [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns:**
boolean - Questo metodo restituisce `true` se il punto definito da x e y è contenuto all'interno di questa struttura [RectangleF](../../com.aspose.drawing/rectanglef); altrimenti `false`.
### contains(PointF pt) {#contains-com.aspose.drawing.PointF-}
```
public final boolean contains(PointF pt)
```


Determina se il punto specificato è contenuto all'interno di questa struttura [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | Il [PointF](../../com.aspose.drawing/pointf) da testare. |

**Returns:**
boolean - Questo metodo restituisce `true` se il punto rappresentato dal parametro pt è contenuto all'interno di questa struttura [RectangleF](../../com.aspose.drawing/rectanglef); altrimenti `false`.
### contains(RectangleF rect) {#contains-com.aspose.drawing.RectangleF-}
```
public final boolean contains(RectangleF rect)
```


Determina se la regione rettangolare rappresentata da `rect` è interamente contenuta all'interno di questa struttura [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Il [RectangleF](../../com.aspose.drawing/rectanglef) da testare. |

**Returns:**
boolean - Questo metodo restituisce `true` se la regione rettangolare rappresentata da `rect` è interamente contenuta nella regione rettangolare rappresentata da questa [RectangleF](../../com.aspose.drawing/rectanglef); altrimenti `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'Object specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'Object da confrontare con questa istanza. |

**Returns:**
boolean - `true` se l'Object specificato è uguale a questa istanza; altrimenti, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
### equals(RectangleF other) {#equals-com.aspose.drawing.RectangleF-}
```
public final boolean equals(RectangleF other)
```


Verifica se un'altra struttura [RectangleF](../../com.aspose.drawing/rectanglef) ha la stessa posizione e dimensione di questa struttura [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [RectangleF](../../com.aspose.drawing/rectanglef) | Altro rettangolo da testare |

**Returns:**
boolean - Questo metodo restituisce `true` se l'altra struttura [RectangleF](../../com.aspose.drawing/rectanglef) e le sue proprietà X, Y, Width e Height sono uguali alle proprietà corrispondenti di questa struttura [RectangleF](../../com.aspose.drawing/rectanglef); altrimenti, `false`.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.drawing.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
