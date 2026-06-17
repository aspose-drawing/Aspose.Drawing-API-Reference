---
title: Size
second_title: Riferimento API di Aspose.Drawing per Java
description: Memorizza una coppia ordinata di interi tipicamente la larghezza e l'altezza di un rettangolo.
type: docs
weight: 42
url: /it/java/com.aspose.drawing/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Size extends Struct<Size> implements System.IEquatable<Size>, Cloneable
```

Memorizza una coppia ordinata di interi, tipicamente la larghezza e l'altezza di un rettangolo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point pt)](#Size-com.aspose.drawing.Point-) | Inizializza una nuova istanza della struttura [Size](../../com.aspose.drawing/size) dal [Point](../../com.aspose.drawing/point) specificato. |
| [Size(int width, int height)](#Size-int-int-) | Inizializza una nuova istanza della struttura [Size](../../com.aspose.drawing/size) dalle dimensioni specificate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [to_SizeF(Size p)](#to-SizeF-com.aspose.drawing.Size-) | Converte il [Size](../../com.aspose.drawing/size) specificato in un [SizeF](../../com.aspose.drawing/sizef). |
| [op_Addition(Size sz1, Size sz2)](#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Aggiunge la larghezza e l'altezza di una struttura [Size](../../com.aspose.drawing/size) alla larghezza e all'altezza di un'altra struttura [Size](../../com.aspose.drawing/size). |
| [op_Subtraction(Size sz1, Size sz2)](#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Sottrae la larghezza e l'altezza di una struttura [Size](../../com.aspose.drawing/size) dalla larghezza e dall'altezza di un'altra struttura [Size](../../com.aspose.drawing/size). |
| [op_Multiply(int left, Size right)](#op-Multiply-int-com.aspose.drawing.Size-) | Moltiplica un [Size](../../com.aspose.drawing/size) per un `int` producendo [Size](../../com.aspose.drawing/size). |
| [op_Multiply(Size left, int right)](#op-Multiply-com.aspose.drawing.Size-int-) | Moltiplica [Size](../../com.aspose.drawing/size) per un `int` producendo [Size](../../com.aspose.drawing/size). |
| [op_Division(Size left, int right)](#op-Division-com.aspose.drawing.Size-int-) | Divide [Size](../../com.aspose.drawing/size) per un `int` producendo [Size](../../com.aspose.drawing/size). |
| [op_Multiply(float left, Size right)](#op-Multiply-float-com.aspose.drawing.Size-) | Moltiplica [Size](../../com.aspose.drawing/size) per un `float` producendo [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(Size left, float right)](#op-Multiply-com.aspose.drawing.Size-float-) | Moltiplica [Size](../../com.aspose.drawing/size) per un `float` producendo [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(Size left, float right)](#op-Division-com.aspose.drawing.Size-float-) | Divide [Size](../../com.aspose.drawing/size) per un `float` producendo [SizeF](../../com.aspose.drawing/sizef). |
| [op_Equality(Size sz1, Size sz2)](#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Verifica se due strutture [Size](../../com.aspose.drawing/size) sono uguali. |
| [op_Inequality(Size sz1, Size sz2)](#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Verifica se due strutture [Size](../../com.aspose.drawing/size) sono diverse. |
| [to_Point(Size size)](#to-Point-com.aspose.drawing.Size-) | Converte il [Size](../../com.aspose.drawing/size) specificato in un [Point](../../com.aspose.drawing/point). |
| [add(Size sz1, Size sz2)](#add-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Aggiunge la larghezza e l'altezza di una struttura [Size](../../com.aspose.drawing/size) alla larghezza e all'altezza di un'altra struttura [Size](../../com.aspose.drawing/size). |
| [ceiling(SizeF value)](#ceiling-com.aspose.drawing.SizeF-) | Converte la struttura [SizeF](../../com.aspose.drawing/sizef) specificata in una struttura [Size](../../com.aspose.drawing/size) arrotondando i valori della struttura [Size](../../com.aspose.drawing/size) al prossimo intero superiore. |
| [subtract(Size sz1, Size sz2)](#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Sottrae la larghezza e l'altezza di una struttura [Size](../../com.aspose.drawing/size) dalla larghezza e dall'altezza di un'altra struttura [Size](../../com.aspose.drawing/size). |
| [truncate(SizeF value)](#truncate-com.aspose.drawing.SizeF-) | Converte la struttura [SizeF](../../com.aspose.drawing/sizef) specificata in una struttura [Size](../../com.aspose.drawing/size) troncando i valori della struttura [SizeF](../../com.aspose.drawing/sizef) al prossimo intero inferiore. |
| [round(SizeF value)](#round-com.aspose.drawing.SizeF-) | Converte la struttura [SizeF](../../com.aspose.drawing/sizef) specificata in una struttura [Size](../../com.aspose.drawing/size) arrotondando i valori della struttura [SizeF](../../com.aspose.drawing/sizef) al valore intero più vicino. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Ottiene un valore che indica se questo [Size](../../com.aspose.drawing/size) ha larghezza e altezza pari a 0. |
| [getWidth()](#getWidth--) | Ottiene la componente orizzontale di questo [Size](../../com.aspose.drawing/size). |
| [setWidth(int value)](#setWidth-int-) | Imposta la componente orizzontale di questo [Size](../../com.aspose.drawing/size). |
| [getHeight()](#getHeight--) | Ottiene la componente verticale di questo [Size](../../com.aspose.drawing/size). |
| [setHeight(int value)](#setHeight-int-) | Imposta la componente verticale di questo [Size](../../com.aspose.drawing/size). |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se l'oggetto specificato è un [Size](../../com.aspose.drawing/size) con le stesse dimensioni di questo [Size](../../com.aspose.drawing/size). |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa struttura [Size](../../com.aspose.drawing/size). |
| [toString()](#toString--) |  |
| [equals(Size other)](#equals-com.aspose.drawing.Size-) | Verifica se un'altra struttura [Size](../../com.aspose.drawing/size) ha la stessa dimensione di questa struttura [Size](../../com.aspose.drawing/size). |
| [CloneTo(Size that)](#CloneTo-com.aspose.drawing.Size-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point pt) {#Size-com.aspose.drawing.Point-}
```
public Size(Point pt)
```


Inizializza una nuova istanza della struttura [Size](../../com.aspose.drawing/size) dal [Point](../../com.aspose.drawing/point) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Il [Point](../../com.aspose.drawing/point) da cui inizializzare questo [Size](../../com.aspose.drawing/size). |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Inizializza una nuova istanza della struttura [Size](../../com.aspose.drawing/size) dalle dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La componente di larghezza del nuovo [Size](../../com.aspose.drawing/size). |
| height | int | La componente di altezza del nuovo [Size](../../com.aspose.drawing/size). |

### to_SizeF(Size p) {#to-SizeF-com.aspose.drawing.Size-}
```
public static SizeF to_SizeF(Size p)
```


Converte il [Size](../../com.aspose.drawing/size) specificato in un [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| p | [Size](../../com.aspose.drawing/size) | Il [Size](../../com.aspose.drawing/size) da convertire. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - The [SizeF](../../com.aspose.drawing/sizef) structure to which this operator converts.
### op_Addition(Size sz1, Size sz2) {#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Addition(Size sz1, Size sz2)
```


Aggiunge la larghezza e l'altezza di una struttura [Size](../../com.aspose.drawing/size) alla larghezza e all'altezza di un'altra struttura [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Il primo [Size](../../com.aspose.drawing/size) da aggiungere. |
| sz2 | [Size](../../com.aspose.drawing/size) | Il secondo [Size](../../com.aspose.drawing/size) da aggiungere. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(Size sz1, Size sz2) {#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Subtraction(Size sz1, Size sz2)
```


Sottrae la larghezza e l'altezza di una struttura [Size](../../com.aspose.drawing/size) dalla larghezza e dall'altezza di un'altra struttura [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | La struttura [Size](../../com.aspose.drawing/size) sul lato sinistro dell'operatore di sottrazione. |
| sz2 | [Size](../../com.aspose.drawing/size) | La struttura [Size](../../com.aspose.drawing/size) sul lato destro dell'operatore di sottrazione. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the subtraction operation.
### op_Multiply(int left, Size right) {#op-Multiply-int-com.aspose.drawing.Size-}
```
public static Size op_Multiply(int left, Size right)
```


Moltiplica un [Size](../../com.aspose.drawing/size) per un `int` producendo [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sinistra | int | Moltiplicatore di tipo `int`. |
| right | [Size](../../com.aspose.drawing/size) | Moltiplicando di tipo [Size](../../com.aspose.drawing/size). |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Multiply(Size left, int right) {#op-Multiply-com.aspose.drawing.Size-int-}
```
public static Size op_Multiply(Size left, int right)
```


Moltiplica [Size](../../com.aspose.drawing/size) per un `int` producendo [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Moltiplicando di tipo [Size](../../com.aspose.drawing/size). |
| destra | int | Moltiplicatore di tipo `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Division(Size left, int right) {#op-Division-com.aspose.drawing.Size-int-}
```
public static Size op_Division(Size left, int right)
```


Divide [Size](../../com.aspose.drawing/size) per un `int` producendo [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividendo di tipo [Size](../../com.aspose.drawing/size). |
| destra | int | Divisore di tipo `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Result of type [Size](../../com.aspose.drawing/size).
### op_Multiply(float left, Size right) {#op-Multiply-float-com.aspose.drawing.Size-}
```
public static SizeF op_Multiply(float left, Size right)
```


Moltiplica [Size](../../com.aspose.drawing/size) per un `float` producendo [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sinistra | float | Moltiplicatore di tipo `float`. |
| right | [Size](../../com.aspose.drawing/size) | Moltiplicando di tipo [Size](../../com.aspose.drawing/size). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(Size left, float right) {#op-Multiply-com.aspose.drawing.Size-float-}
```
public static SizeF op_Multiply(Size left, float right)
```


Moltiplica [Size](../../com.aspose.drawing/size) per un `float` producendo [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Moltiplicando di tipo [Size](../../com.aspose.drawing/size). |
| destra | float | Moltiplicatore di tipo `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(Size left, float right) {#op-Division-com.aspose.drawing.Size-float-}
```
public static SizeF op_Division(Size left, float right)
```


Divide [Size](../../com.aspose.drawing/size) per un `float` producendo [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividendo di tipo [Size](../../com.aspose.drawing/size). |
| destra | float | Divisore di tipo `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### op_Equality(Size sz1, Size sz2) {#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Equality(Size sz1, Size sz2)
```


Verifica se due strutture [Size](../../com.aspose.drawing/size) sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | La struttura [Size](../../com.aspose.drawing/size) sul lato sinistro dell'operatore di uguaglianza. |
| sz2 | [Size](../../com.aspose.drawing/size) | La struttura [Size](../../com.aspose.drawing/size) sul lato destro dell'operatore di uguaglianza. |

**Returns:**
boolean - true se `sz1` e `sz2` hanno larghezza e altezza uguali; altrimenti, false.
### op_Inequality(Size sz1, Size sz2) {#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Inequality(Size sz1, Size sz2)
```


Verifica se due strutture [Size](../../com.aspose.drawing/size) sono diverse.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | La struttura [Size](../../com.aspose.drawing/size) sul lato sinistro dell'operatore di disuguaglianza. |
| sz2 | [Size](../../com.aspose.drawing/size) | La struttura [Size](../../com.aspose.drawing/size) sul lato destro dell'operatore di disuguaglianza. |

**Returns:**
boolean - true se `sz1` e `sz2` differiscono per larghezza o altezza; false se `sz1` e `sz2` sono uguali.
### to_Point(Size size) {#to-Point-com.aspose.drawing.Size-}
```
public static Point to_Point(Size size)
```


Converte il [Size](../../com.aspose.drawing/size) specificato in un [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | Il [Size](../../com.aspose.drawing/size) da convertire. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) structure to which this operator converts.
### add(Size sz1, Size sz2) {#add-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size add(Size sz1, Size sz2)
```


Aggiunge la larghezza e l'altezza di una struttura [Size](../../com.aspose.drawing/size) alla larghezza e all'altezza di un'altra struttura [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Il primo [Size](../../com.aspose.drawing/size) da aggiungere. |
| sz2 | [Size](../../com.aspose.drawing/size) | Il secondo [Size](../../com.aspose.drawing/size) da aggiungere. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### ceiling(SizeF value) {#ceiling-com.aspose.drawing.SizeF-}
```
public static Size ceiling(SizeF value)
```


Converte la struttura [SizeF](../../com.aspose.drawing/sizef) specificata in una struttura [Size](../../com.aspose.drawing/size) arrotondando i valori della struttura [Size](../../com.aspose.drawing/size) al prossimo intero superiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | La struttura [SizeF](../../com.aspose.drawing/sizef) da convertire. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### subtract(Size sz1, Size sz2) {#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size subtract(Size sz1, Size sz2)
```


Sottrae la larghezza e l'altezza di una struttura [Size](../../com.aspose.drawing/size) dalla larghezza e dall'altezza di un'altra struttura [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | La struttura [Size](../../com.aspose.drawing/size) sul lato sinistro dell'operatore di sottrazione. |
| sz2 | [Size](../../com.aspose.drawing/size) | La struttura [Size](../../com.aspose.drawing/size) sul lato destro dell'operatore di sottrazione. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) that is a result of the subtraction operation.
### truncate(SizeF value) {#truncate-com.aspose.drawing.SizeF-}
```
public static Size truncate(SizeF value)
```


Converte la struttura [SizeF](../../com.aspose.drawing/sizef) specificata in una struttura [Size](../../com.aspose.drawing/size) troncando i valori della struttura [SizeF](../../com.aspose.drawing/sizef) al prossimo intero inferiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | La struttura [SizeF](../../com.aspose.drawing/sizef) da convertire. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### round(SizeF value) {#round-com.aspose.drawing.SizeF-}
```
public static Size round(SizeF value)
```


Converte la struttura [SizeF](../../com.aspose.drawing/sizef) specificata in una struttura [Size](../../com.aspose.drawing/size) arrotondando i valori della struttura [SizeF](../../com.aspose.drawing/sizef) al valore intero più vicino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | La struttura [SizeF](../../com.aspose.drawing/sizef) da convertire. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.drawing/size) |  |
| obj2 | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Ottiene un valore che indica se questo [Size](../../com.aspose.drawing/size) ha larghezza e altezza pari a 0.

**Returns:**
boolean - un valore che indica se questo [Size](../../com.aspose.drawing/size) ha larghezza e altezza pari a 0.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ottiene la componente orizzontale di questo [Size](../../com.aspose.drawing/size).

**Returns:**
int - la componente orizzontale di questo [Size](../../com.aspose.drawing/size).
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Imposta la componente orizzontale di questo [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | la componente orizzontale di questo [Size](../../com.aspose.drawing/size). |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ottiene la componente verticale di questo [Size](../../com.aspose.drawing/size).

**Returns:**
int - la componente verticale di questo [Size](../../com.aspose.drawing/size).
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Imposta la componente verticale di questo [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | la componente verticale di questo [Size](../../com.aspose.drawing/size). |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se l'oggetto specificato è un [Size](../../com.aspose.drawing/size) con le stesse dimensioni di questo [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'Object da testare. |

**Returns:**
boolean - true se `obj` è un [Size](../../com.aspose.drawing/size) e ha la stessa larghezza e altezza di questo [Size](../../com.aspose.drawing/size); altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa struttura [Size](../../com.aspose.drawing/size).

**Returns:**
int - Un valore intero che specifica un valore hash per questa struttura [Size](../../com.aspose.drawing/size).
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Size other) {#equals-com.aspose.drawing.Size-}
```
public final boolean equals(Size other)
```


Verifica se un'altra struttura [Size](../../com.aspose.drawing/size) ha la stessa dimensione di questa struttura [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [Size](../../com.aspose.drawing/size) | Altra dimensione da testare |

**Returns:**
boolean - Questo metodo restituisce `true` se l'altra struttura [Size](../../com.aspose.drawing/size) e le sue proprietà Width e Height sono uguali alle proprietà corrispondenti di questa struttura [Size](../../com.aspose.drawing/size); altrimenti, `false`.
### CloneTo(Size that) {#CloneTo-com.aspose.drawing.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [Size](../../com.aspose.drawing/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### clone() {#clone--}
```
public Size clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
