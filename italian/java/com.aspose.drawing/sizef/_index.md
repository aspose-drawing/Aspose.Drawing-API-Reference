---
title: SizeF
second_title: Riferimento API di Aspose.Drawing per Java
description: Memorizza una coppia ordinata di numeri a virgola mobile tipicamente la larghezza e l'altezza di un rettangolo.
type: docs
weight: 43
url: /it/java/com.aspose.drawing/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class SizeF extends Struct<SizeF> implements System.IEquatable<SizeF>, Cloneable
```

Memorizza una coppia ordinata di numeri in virgola mobile, tipicamente la larghezza e l'altezza di un rettangolo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(float width, float height)](#SizeF-float-float-) | Inizializza una nuova istanza della struttura SizeF dalle dimensioni specificate. |
| [SizeF(PointF pt)](#SizeF-com.aspose.drawing.PointF-) | Inizializza una nuova istanza della struct [SizeF](../../com.aspose.drawing/sizef). |
| [SizeF(SizeF size)](#SizeF-com.aspose.drawing.SizeF-) | Inizializza una nuova istanza della struct [SizeF](../../com.aspose.drawing/sizef). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [op_Equality(SizeF sz1, SizeF sz2)](#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Verifica se due strutture [SizeF](../../com.aspose.drawing/sizef) sono uguali. |
| [op_Inequality(SizeF sz1, SizeF sz2)](#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Verifica se due strutture [SizeF](../../com.aspose.drawing/sizef) sono diverse. |
| [add(SizeF sz1, SizeF sz2)](#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Aggiunge la larghezza e l'altezza di una struttura [SizeF](../../com.aspose.drawing/sizef) alla larghezza e all'altezza di un'altra struttura [SizeF](../../com.aspose.drawing/sizef). |
| [subtract(SizeF sz1, SizeF sz2)](#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Sottrae la larghezza e l'altezza di una struttura [SizeF](../../com.aspose.drawing/sizef) dalla larghezza e dall'altezza di un'altra struttura [SizeF](../../com.aspose.drawing/sizef). |
| [op_Addition(SizeF sz1, SizeF sz2)](#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Aggiunge la larghezza e l'altezza di una struttura [SizeF](../../com.aspose.drawing/sizef) alla larghezza e all'altezza di un'altra struttura [SizeF](../../com.aspose.drawing/sizef). |
| [op_Subtraction(SizeF sz1, SizeF sz2)](#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Sottrae la larghezza e l'altezza di una struttura [SizeF](../../com.aspose.drawing/sizef) dalla larghezza e dall'altezza di un'altra struttura [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(float left, SizeF right)](#op-Multiply-float-com.aspose.drawing.SizeF-) | Moltiplica [SizeF](../../com.aspose.drawing/sizef) per un `float` producendo [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(SizeF left, float right)](#op-Multiply-com.aspose.drawing.SizeF-float-) | Moltiplica [SizeF](../../com.aspose.drawing/sizef) per un `float` producendo [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(SizeF left, float right)](#op-Division-com.aspose.drawing.SizeF-float-) | Divide [SizeF](../../com.aspose.drawing/sizef) per un `float` producendo [SizeF](../../com.aspose.drawing/sizef). |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Restituisce un valore che indica se questa struttura [SizeF](../../com.aspose.drawing/sizef) ha larghezza e altezza zero. |
| [getWidth()](#getWidth--) | Restituisce la componente orizzontale di questa struttura SizeF. |
| [setWidth(float value)](#setWidth-float-) | Imposta la componente orizzontale di questa struttura SizeF. |
| [getHeight()](#getHeight--) | Restituisce la componente verticale di questa struttura SizeF. |
| [setHeight(float value)](#setHeight-float-) | Imposta la componente verticale di questa struttura SizeF. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa struttura [SizeF](../../com.aspose.drawing/sizef). |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se l'oggetto specificato è una struttura [SizeF](../../com.aspose.drawing/sizef) con le stesse dimensioni di questa struttura [SizeF](../../com.aspose.drawing/sizef). |
| [toSize()](#toSize--) | Converte una struttura [SizeF](../../com.aspose.drawing/sizef) in una struttura [Size](../../com.aspose.drawing/size). |
| [toPointF()](#toPointF--) | Converte una struttura [SizeF](../../com.aspose.drawing/sizef) in una struttura [PointF](../../com.aspose.drawing/pointf). |
| [equals(SizeF other)](#equals-com.aspose.drawing.SizeF-) | Verifica se un'altra struttura [SizeF](../../com.aspose.drawing/sizef) ha le stesse dimensioni di questa struttura [SizeF](../../com.aspose.drawing/sizef). |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.drawing.SizeF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Inizializza una nuova istanza della struttura SizeF dalle dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | float | La componente di larghezza della nuova struttura SizeF. |
| height | float | La componente di altezza della nuova struttura SizeF. |

### SizeF(PointF pt) {#SizeF-com.aspose.drawing.PointF-}
```
public SizeF(PointF pt)
```


Inizializza una nuova istanza della struct [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | La struttura [PointF](../../com.aspose.drawing/pointf) da cui inizializzare questa struttura [SizeF](../../com.aspose.drawing/sizef). |

### SizeF(SizeF size) {#SizeF-com.aspose.drawing.SizeF-}
```
public SizeF(SizeF size)
```


Inizializza una nuova istanza della struct [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | La struttura [SizeF](../../com.aspose.drawing/sizef) da cui creare la nuova struttura [SizeF](../../com.aspose.drawing/sizef). |

### op_Equality(SizeF sz1, SizeF sz2) {#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Equality(SizeF sz1, SizeF sz2)
```


Verifica se due strutture [SizeF](../../com.aspose.drawing/sizef) sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La struttura [SizeF](../../com.aspose.drawing/sizef) sul lato sinistro dell'operatore di uguaglianza. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La struttura [SizeF](../../com.aspose.drawing/sizef) sul lato destro dell'operatore di uguaglianza. |

**Returns:**
boolean - Questo operatore restituisce true se `sz1` e `sz2` hanno larghezza e altezza uguali; altrimenti, false.
### op_Inequality(SizeF sz1, SizeF sz2) {#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Inequality(SizeF sz1, SizeF sz2)
```


Verifica se due strutture [SizeF](../../com.aspose.drawing/sizef) sono diverse.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La struttura [SizeF](../../com.aspose.drawing/sizef) sul lato sinistro dell'operatore di disuguaglianza. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La struttura [SizeF](../../com.aspose.drawing/sizef) sul lato destro dell'operatore di disuguaglianza. |

**Returns:**
boolean - Questo operatore restituisce true se `sz1` e `sz2` differiscono per larghezza o altezza; false se `sz1` e `sz2` sono uguali.
### add(SizeF sz1, SizeF sz2) {#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF add(SizeF sz1, SizeF sz2)
```


Aggiunge la larghezza e l'altezza di una struttura [SizeF](../../com.aspose.drawing/sizef) alla larghezza e all'altezza di un'altra struttura [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La prima struttura [SizeF](../../com.aspose.drawing/sizef) da aggiungere. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La seconda struttura [SizeF](../../com.aspose.drawing/sizef) da aggiungere. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is the result of the addition operation.
### subtract(SizeF sz1, SizeF sz2) {#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF subtract(SizeF sz1, SizeF sz2)
```


Sottrae la larghezza e l'altezza di una struttura [SizeF](../../com.aspose.drawing/sizef) dalla larghezza e dall'altezza di un'altra struttura [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La struttura [SizeF](../../com.aspose.drawing/sizef) sul lato sinistro dell'operatore di sottrazione. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La struttura [SizeF](../../com.aspose.drawing/sizef) sul lato destro dell'operatore di sottrazione. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is a result of the subtraction operation.
### op_Addition(SizeF sz1, SizeF sz2) {#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Addition(SizeF sz1, SizeF sz2)
```


Aggiunge la larghezza e l'altezza di una struttura [SizeF](../../com.aspose.drawing/sizef) alla larghezza e all'altezza di un'altra struttura [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La prima struttura [SizeF](../../com.aspose.drawing/sizef) da aggiungere. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La seconda struttura [SizeF](../../com.aspose.drawing/sizef) da aggiungere. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(SizeF sz1, SizeF sz2) {#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Subtraction(SizeF sz1, SizeF sz2)
```


Sottrae la larghezza e l'altezza di una struttura [SizeF](../../com.aspose.drawing/sizef) dalla larghezza e dall'altezza di un'altra struttura [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La struttura [SizeF](../../com.aspose.drawing/sizef) sul lato sinistro dell'operatore di sottrazione. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La struttura [SizeF](../../com.aspose.drawing/sizef) sul lato destro dell'operatore di sottrazione. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that is the result of the subtraction operation.
### op_Multiply(float left, SizeF right) {#op-Multiply-float-com.aspose.drawing.SizeF-}
```
public static SizeF op_Multiply(float left, SizeF right)
```


Moltiplica [SizeF](../../com.aspose.drawing/sizef) per un `float` producendo [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sinistra | float | Moltiplicatore di tipo `float`. |
| right | [SizeF](../../com.aspose.drawing/sizef) | Moltiplicando di tipo [SizeF](../../com.aspose.drawing/sizef). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(SizeF left, float right) {#op-Multiply-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Multiply(SizeF left, float right)
```


Moltiplica [SizeF](../../com.aspose.drawing/sizef) per un `float` producendo [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Moltiplicando di tipo [SizeF](../../com.aspose.drawing/sizef). |
| destra | float | Moltiplicatore di tipo `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(SizeF left, float right) {#op-Division-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Division(SizeF left, float right)
```


Divide [SizeF](../../com.aspose.drawing/sizef) per un `float` producendo [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Dividendo di tipo [SizeF](../../com.aspose.drawing/sizef). |
| destra | float | Divisore di tipo `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### to_PointF(SizeF size) {#to-PointF-com.aspose.drawing.SizeF-}
```
public static PointF to_PointF(SizeF size)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.drawing/sizef) |  |
| obj2 | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Restituisce un valore che indica se questa struttura [SizeF](../../com.aspose.drawing/sizef) ha larghezza e altezza zero.

**Returns:**
boolean - un valore che indica se questa struttura [SizeF](../../com.aspose.drawing/sizef) ha larghezza e altezza zero.
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Restituisce la componente orizzontale di questa struttura SizeF.

**Returns:**
float - la componente orizzontale di questa struttura SizeF.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Imposta la componente orizzontale di questa struttura SizeF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float | la componente orizzontale di questa struttura SizeF. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Restituisce la componente verticale di questa struttura SizeF.

**Returns:**
float - la componente verticale di questa struttura SizeF.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Imposta la componente verticale di questa struttura SizeF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float | la componente verticale di questa struttura SizeF. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa struttura [SizeF](../../com.aspose.drawing/sizef).

**Returns:**
int - Un valore intero che specifica un valore hash per questa struttura [SizeF](../../com.aspose.drawing/sizef).
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


Verifica se l'oggetto specificato è una struttura [SizeF](../../com.aspose.drawing/sizef) con le stesse dimensioni di questa struttura [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'Object da testare. |

**Returns:**
boolean - Questo metodo restituisce `true` se obj è un [SizeF](../../com.aspose.drawing/sizef) e ha la stessa larghezza e altezza di questo SizeF; altrimenti, `false`.
### toSize() {#toSize--}
```
public final Size toSize()
```


Converte una struttura [SizeF](../../com.aspose.drawing/sizef) in una struttura [Size](../../com.aspose.drawing/size).

**Returns:**
[Size](../../com.aspose.drawing/size) - Returns a [Size](../../com.aspose.drawing/size) structure.
### toPointF() {#toPointF--}
```
public final PointF toPointF()
```


Converte una struttura [SizeF](../../com.aspose.drawing/sizef) in una struttura [PointF](../../com.aspose.drawing/pointf).

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - Returns a [PointF](../../com.aspose.drawing/pointf) structure.
### equals(SizeF other) {#equals-com.aspose.drawing.SizeF-}
```
public final boolean equals(SizeF other)
```


Verifica se un'altra struttura [SizeF](../../com.aspose.drawing/sizef) ha le stesse dimensioni di questa struttura [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [SizeF](../../com.aspose.drawing/sizef) | Altra dimensione da testare |

**Returns:**
boolean - Questo metodo restituisce `true` se l'altra struttura [SizeF](../../com.aspose.drawing/sizef) e le sue proprietà Width e Height sono uguali alle corrispondenti proprietà di questa struttura [SizeF](../../com.aspose.drawing/sizef); altrimenti, `false`.
### CloneTo(SizeF that) {#CloneTo-com.aspose.drawing.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.drawing/sizef) |  |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
