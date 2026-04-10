---
title: CharacterRange
second_title: Riferimento API di Aspose.Drawing per Java
description: Specifica un intervallo di posizioni di caratteri all'interno di una stringa.
type: docs
weight: 13
url: /it/java/com.aspose.drawing/characterrange/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class CharacterRange extends Struct<CharacterRange> implements Cloneable
```

Specifica un intervallo di posizioni di caratteri all'interno di una stringa.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CharacterRange()](#CharacterRange--) |  |
| [CharacterRange(int first, int length)](#CharacterRange-int-int-) | Inizializza una nuova istanza della struct [CharacterRange](../../com.aspose.drawing/characterrange), specificando un intervallo di posizioni di caratteri all'interno di una stringa. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFirst()](#getFirst--) | Ottiene o imposta la posizione nella stringa del primo carattere di questo [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setFirst(int value)](#setFirst-int-) | Ottiene o imposta la posizione nella stringa del primo carattere di questo [CharacterRange](../../com.aspose.drawing/characterrange). |
| [getLength()](#getLength--) | Ottiene o imposta il numero di posizioni in questo [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setLength(int value)](#setLength-int-) | Ottiene o imposta il numero di posizioni in questo [CharacterRange](../../com.aspose.drawing/characterrange). |
| [op_Equality(CharacterRange cr1, CharacterRange cr2)](#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Confronta due oggetti [CharacterRange](../../com.aspose.drawing/characterrange). |
| [op_Inequality(CharacterRange cr1, CharacterRange cr2)](#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Confronta due oggetti [CharacterRange](../../com.aspose.drawing/characterrange). |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questo oggetto è equivalente all'oggetto specificato. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [CloneTo(CharacterRange that)](#CloneTo-com.aspose.drawing.CharacterRange-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### CharacterRange() {#CharacterRange--}
```
public CharacterRange()
```


### CharacterRange(int first, int length) {#CharacterRange-int-int-}
```
public CharacterRange(int first, int length)
```


Inizializza una nuova istanza della struct [CharacterRange](../../com.aspose.drawing/characterrange), specificando un intervallo di posizioni di caratteri all'interno di una stringa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| primo | int | La posizione del primo carattere nell'intervallo. Ad esempio, se First è impostato a 0, la prima posizione dell'intervallo è la posizione 0 nella stringa. |
| lunghezza | int | Il numero di posizioni nell'intervallo. |

### getFirst() {#getFirst--}
```
public final int getFirst()
```


Ottiene o imposta la posizione nella stringa del primo carattere di questo [CharacterRange](../../com.aspose.drawing/characterrange).

Valore: La prima posizione di questo [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setFirst(int value) {#setFirst-int-}
```
public final void setFirst(int value)
```


Ottiene o imposta la posizione nella stringa del primo carattere di questo [CharacterRange](../../com.aspose.drawing/characterrange).

Valore: La prima posizione di questo [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getLength() {#getLength--}
```
public final int getLength()
```


Ottiene o imposta il numero di posizioni in questo [CharacterRange](../../com.aspose.drawing/characterrange).

Valore: Il numero di posizioni in questo [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


Ottiene o imposta il numero di posizioni in questo [CharacterRange](../../com.aspose.drawing/characterrange).

Valore: Il numero di posizioni in questo [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### op_Equality(CharacterRange cr1, CharacterRange cr2) {#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Equality(CharacterRange cr1, CharacterRange cr2)
```


Confronta due oggetti [CharacterRange](../../com.aspose.drawing/characterrange). Restituisce un valore che indica se i valori First e Length dei due oggetti [CharacterRange](../../com.aspose.drawing/characterrange) sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Un [CharacterRange](../../com.aspose.drawing/characterrange) da confrontare per uguaglianza. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Un [CharacterRange](../../com.aspose.drawing/characterrange) da confrontare per uguaglianza. |

**Returns:**
boolean - `true` per indicare che i due oggetti CharacterRange hanno gli stessi valori First e Length; altrimenti, `false`.
### op_Inequality(CharacterRange cr1, CharacterRange cr2) {#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Inequality(CharacterRange cr1, CharacterRange cr2)
```


Confronta due oggetti [CharacterRange](../../com.aspose.drawing/characterrange). Restituisce un valore che indica se i valori First o Length dei due oggetti [CharacterRange](../../com.aspose.drawing/characterrange) non sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Un [CharacterRange](../../com.aspose.drawing/characterrange) da confrontare per disuguaglianza. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Un [CharacterRange](../../com.aspose.drawing/characterrange) da confrontare per disuguaglianza. |

**Returns:**
boolean - `true` per indicare che o il valore First o il valore Length dei due oggetti CharacterRange differiscono; altrimenti, `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questo oggetto è equivalente all'oggetto specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da confrontare per uguaglianza.. |

**Returns:**
boolean - `true` per indicare che l'oggetto specificato è un'istanza con lo stesso valore First e Length di questa istanza; altrimenti, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa istanza.

**Returns:**
int - Un intero con segno a 32 bit che è il codice hash per questa istanza.
### CloneTo(CharacterRange that) {#CloneTo-com.aspose.drawing.CharacterRange-}
```
public void CloneTo(CharacterRange that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [CharacterRange](../../com.aspose.drawing/characterrange) |  |

### Clone() {#Clone--}
```
public CharacterRange Clone()
```




**Returns:**
[CharacterRange](../../com.aspose.drawing/characterrange)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
