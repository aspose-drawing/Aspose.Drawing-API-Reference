---
title: CharacterRange
second_title: Aspose.Drawing voor Java API-referentie
description: Specificeert een bereik van tekenposities binnen een tekenreeks.
type: docs
weight: 13
url: /nl/java/com.aspose.drawing/characterrange/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class CharacterRange extends Struct<CharacterRange> implements Cloneable
```

Specificeert een bereik van tekenposities binnen een tekenreeks.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CharacterRange()](#CharacterRange--) |  |
| [CharacterRange(int first, int length)](#CharacterRange-int-int-) | Initialiseert een nieuw exemplaar van de [CharacterRange](../../com.aspose.drawing/characterrange) struct, die een bereik van tekenposities binnen een tekenreeks specificeert. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFirst()](#getFirst--) | Haalt of stelt de positie in de tekenreeks van het eerste teken van deze [CharacterRange](../../com.aspose.drawing/characterrange) in. |
| [setFirst(int value)](#setFirst-int-) | Haalt of stelt de positie in de tekenreeks van het eerste teken van deze [CharacterRange](../../com.aspose.drawing/characterrange) in. |
| [getLength()](#getLength--) | Haalt of stelt het aantal posities in deze [CharacterRange](../../com.aspose.drawing/characterrange) in. |
| [setLength(int value)](#setLength-int-) | Haalt of stelt het aantal posities in deze [CharacterRange](../../com.aspose.drawing/characterrange) in. |
| [op_Equality(CharacterRange cr1, CharacterRange cr2)](#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Vergelijkt twee [CharacterRange](../../com.aspose.drawing/characterrange) objecten. |
| [op_Inequality(CharacterRange cr1, CharacterRange cr2)](#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Vergelijkt twee [CharacterRange](../../com.aspose.drawing/characterrange) objecten. |
| [equals(Object obj)](#equals-java.lang.Object-) | Haalt een waarde op die aangeeft of dit object gelijk is aan het opgegeven object. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
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


Initialiseert een nieuw exemplaar van de [CharacterRange](../../com.aspose.drawing/characterrange) struct, die een bereik van tekenposities binnen een tekenreeks specificeert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eerste | int | De positie van het eerste teken in het bereik. Bijvoorbeeld, als First is ingesteld op 0, is de eerste positie van het bereik positie 0 in de tekenreeks. |
| lengte | int | Het aantal posities in het bereik. |

### getFirst() {#getFirst--}
```
public final int getFirst()
```


Haalt of stelt de positie in de tekenreeks van het eerste teken van deze [CharacterRange](../../com.aspose.drawing/characterrange) in.

Waarde: De eerste positie van deze [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setFirst(int value) {#setFirst-int-}
```
public final void setFirst(int value)
```


Haalt of stelt de positie in de tekenreeks van het eerste teken van deze [CharacterRange](../../com.aspose.drawing/characterrange) in.

Waarde: De eerste positie van deze [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getLength() {#getLength--}
```
public final int getLength()
```


Haalt of stelt het aantal posities in deze [CharacterRange](../../com.aspose.drawing/characterrange) in.

Waarde: Het aantal posities in deze [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


Haalt of stelt het aantal posities in deze [CharacterRange](../../com.aspose.drawing/characterrange) in.

Waarde: Het aantal posities in deze [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### op_Equality(CharacterRange cr1, CharacterRange cr2) {#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Equality(CharacterRange cr1, CharacterRange cr2)
```


Vergelijkt twee [CharacterRange](../../com.aspose.drawing/characterrange) objecten. Haalt een waarde op die aangeeft of de First- en Length-waarden van de twee [CharacterRange](../../com.aspose.drawing/characterrange) objecten gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Een [CharacterRange](../../com.aspose.drawing/characterrange) om op gelijkheid te vergelijken. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Een [CharacterRange](../../com.aspose.drawing/characterrange) om op gelijkheid te vergelijken. |

**Returns:**
boolean - `true` om aan te geven dat de twee CharacterRange-objecten dezelfde First- en Length-waarden hebben; anders `false`.
### op_Inequality(CharacterRange cr1, CharacterRange cr2) {#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Inequality(CharacterRange cr1, CharacterRange cr2)
```


Vergelijkt twee [CharacterRange](../../com.aspose.drawing/characterrange) objecten. Haalt een waarde op die aangeeft of de First- of Length-waarden van de twee [CharacterRange](../../com.aspose.drawing/characterrange) objecten niet gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Een [CharacterRange](../../com.aspose.drawing/characterrange) om op ongelijkheid te vergelijken. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Een [CharacterRange](../../com.aspose.drawing/characterrange) om op ongelijkheid te vergelijken. |

**Returns:**
boolean - `true` om aan te geven dat ofwel de First- of Length-waarden van de twee CharacterRange-objecten verschillen; anders `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Haalt een waarde op die aangeeft of dit object gelijk is aan het opgegeven object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om op gelijkheid mee te vergelijken.. |

**Returns:**
boolean - `true` om aan te geven dat het opgegeven object een instantie is met dezelfde First- en Length-waarde als deze instantie; anders `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

**Returns:**
int - Een 32-bits ondertekend geheel getal dat de hashcode voor deze instantie is.
### CloneTo(CharacterRange that) {#CloneTo-com.aspose.drawing.CharacterRange-}
```
public void CloneTo(CharacterRange that)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
