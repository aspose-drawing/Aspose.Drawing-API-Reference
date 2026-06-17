---
title: CharacterRange
second_title: Aspose.Drawing för Java API‑referens
description: Anger ett intervall av teckenpositioner inom en sträng.
type: docs
weight: 13
url: /sv/java/com.aspose.drawing/characterrange/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class CharacterRange extends Struct<CharacterRange> implements Cloneable
```

Anger ett intervall av teckenpositioner inom en sträng.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CharacterRange()](#CharacterRange--) |  |
| [CharacterRange(int first, int length)](#CharacterRange-int-int-) | Initierar en ny instans av strukturen [CharacterRange](../../com.aspose.drawing/characterrange), som specificerar ett intervall av teckenpositioner i en sträng. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFirst()](#getFirst--) | Hämtar eller anger positionen i strängen för det första tecknet i detta [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setFirst(int value)](#setFirst-int-) | Hämtar eller anger positionen i strängen för det första tecknet i detta [CharacterRange](../../com.aspose.drawing/characterrange). |
| [getLength()](#getLength--) | Hämtar eller anger antalet positioner i detta [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setLength(int value)](#setLength-int-) | Hämtar eller anger antalet positioner i detta [CharacterRange](../../com.aspose.drawing/characterrange). |
| [op_Equality(CharacterRange cr1, CharacterRange cr2)](#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Jämför två [CharacterRange](../../com.aspose.drawing/characterrange)-objekt. |
| [op_Inequality(CharacterRange cr1, CharacterRange cr2)](#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Jämför två [CharacterRange](../../com.aspose.drawing/characterrange)-objekt. |
| [equals(Object obj)](#equals-java.lang.Object-) | Hämtar ett värde som indikerar om detta objekt är ekvivalent med det angivna objektet. |
| [hashCode()](#hashCode--) | Returnerar hashkoden för den här instansen. |
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


Initierar en ny instans av strukturen [CharacterRange](../../com.aspose.drawing/characterrange), som specificerar ett intervall av teckenpositioner i en sträng.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| första | int | Positionen för det första tecknet i intervallet. Till exempel, om First är satt till 0, är den första positionen i intervallet position 0 i strängen. |
| längd | int | Antalet positioner i intervallet. |

### getFirst() {#getFirst--}
```
public final int getFirst()
```


Hämtar eller anger positionen i strängen för det första tecknet i detta [CharacterRange](../../com.aspose.drawing/characterrange).

Värde: Den första positionen för detta [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setFirst(int value) {#setFirst-int-}
```
public final void setFirst(int value)
```


Hämtar eller anger positionen i strängen för det första tecknet i detta [CharacterRange](../../com.aspose.drawing/characterrange).

Värde: Den första positionen för detta [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getLength() {#getLength--}
```
public final int getLength()
```


Hämtar eller anger antalet positioner i detta [CharacterRange](../../com.aspose.drawing/characterrange).

Värde: Antalet positioner i detta [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


Hämtar eller anger antalet positioner i detta [CharacterRange](../../com.aspose.drawing/characterrange).

Värde: Antalet positioner i detta [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### op_Equality(CharacterRange cr1, CharacterRange cr2) {#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Equality(CharacterRange cr1, CharacterRange cr2)
```


Jämför två [CharacterRange](../../com.aspose.drawing/characterrange)-objekt. Hämtar ett värde som indikerar om First- och Length-värdena för de två [CharacterRange](../../com.aspose.drawing/characterrange)-objekten är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Ett [CharacterRange](../../com.aspose.drawing/characterrange) att jämföra för likhet. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Ett [CharacterRange](../../com.aspose.drawing/characterrange) att jämföra för likhet. |

**Returns:**
boolean - `true` för att indikera att de två CharacterRange-objekten har samma First- och Length-värden; annars `false`.
### op_Inequality(CharacterRange cr1, CharacterRange cr2) {#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Inequality(CharacterRange cr1, CharacterRange cr2)
```


Jämför två [CharacterRange](../../com.aspose.drawing/characterrange)-objekt. Hämtar ett värde som indikerar om First- eller Length-värdena för de två [CharacterRange](../../com.aspose.drawing/characterrange)-objekten inte är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Ett [CharacterRange](../../com.aspose.drawing/characterrange) att jämföra för ojämlikhet. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Ett [CharacterRange](../../com.aspose.drawing/characterrange) att jämföra för ojämlikhet. |

**Returns:**
boolean - `true` för att indikera att antingen First- eller Length-värdena för de två CharacterRange-objekten skiljer sig; annars `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Hämtar ett värde som indikerar om detta objekt är ekvivalent med det angivna objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att jämföra med för likhet.. |

**Returns:**
boolean - `true` för att indikera att det angivna objektet är en instans med samma First och Length värde som denna instans; annars `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hashkoden för den här instansen.

**Returns:**
int - Ett 32‑bitars signerat heltal som är hash‑koden för denna instans.
### CloneTo(CharacterRange that) {#CloneTo-com.aspose.drawing.CharacterRange-}
```
public void CloneTo(CharacterRange that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
