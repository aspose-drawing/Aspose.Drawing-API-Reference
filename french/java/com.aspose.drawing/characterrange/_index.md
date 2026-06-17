---
title: CharacterRange
second_title: Référence de l'API Aspose.Drawing pour Java
description: Spécifie une plage de positions de caractères dans une chaîne.
type: docs
weight: 13
url: /fr/java/com.aspose.drawing/characterrange/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class CharacterRange extends Struct<CharacterRange> implements Cloneable
```

Spécifie une plage de positions de caractères dans une chaîne.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CharacterRange()](#CharacterRange--) |  |
| [CharacterRange(int first, int length)](#CharacterRange-int-int-) | Initialise une nouvelle instance de la structure [CharacterRange](../../com.aspose.drawing/characterrange), en spécifiant une plage de positions de caractères dans une chaîne. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFirst()](#getFirst--) | Obtient ou définit la position dans la chaîne du premier caractère de ce [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setFirst(int value)](#setFirst-int-) | Obtient ou définit la position dans la chaîne du premier caractère de ce [CharacterRange](../../com.aspose.drawing/characterrange). |
| [getLength()](#getLength--) | Obtient ou définit le nombre de positions dans ce [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setLength(int value)](#setLength-int-) | Obtient ou définit le nombre de positions dans ce [CharacterRange](../../com.aspose.drawing/characterrange). |
| [op_Equality(CharacterRange cr1, CharacterRange cr2)](#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Compare deux objets [CharacterRange](../../com.aspose.drawing/characterrange). |
| [op_Inequality(CharacterRange cr1, CharacterRange cr2)](#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Compare deux objets [CharacterRange](../../com.aspose.drawing/characterrange). |
| [equals(Object obj)](#equals-java.lang.Object-) | Obtient une valeur indiquant si cet objet est équivalent à l'objet spécifié. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
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


Initialise une nouvelle instance de la structure [CharacterRange](../../com.aspose.drawing/characterrange), en spécifiant une plage de positions de caractères dans une chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| premier | int | La position du premier caractère dans la plage. Par exemple, si First est défini à 0, la première position de la plage est la position 0 dans la chaîne. |
| longueur | int | Le nombre de positions dans la plage. |

### getFirst() {#getFirst--}
```
public final int getFirst()
```


Obtient ou définit la position dans la chaîne du premier caractère de ce [CharacterRange](../../com.aspose.drawing/characterrange).

Valeur : La première position de ce [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setFirst(int value) {#setFirst-int-}
```
public final void setFirst(int value)
```


Obtient ou définit la position dans la chaîne du premier caractère de ce [CharacterRange](../../com.aspose.drawing/characterrange).

Valeur : La première position de ce [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLength() {#getLength--}
```
public final int getLength()
```


Obtient ou définit le nombre de positions dans ce [CharacterRange](../../com.aspose.drawing/characterrange).

Valeur : Le nombre de positions dans ce [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


Obtient ou définit le nombre de positions dans ce [CharacterRange](../../com.aspose.drawing/characterrange).

Valeur : Le nombre de positions dans ce [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### op_Equality(CharacterRange cr1, CharacterRange cr2) {#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Equality(CharacterRange cr1, CharacterRange cr2)
```


Compare deux objets [CharacterRange](../../com.aspose.drawing/characterrange). Obtient une valeur indiquant si les valeurs First et Length des deux objets [CharacterRange](../../com.aspose.drawing/characterrange) sont égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Un [CharacterRange](../../com.aspose.drawing/characterrange) à comparer pour l'égalité. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Un [CharacterRange](../../com.aspose.drawing/characterrange) à comparer pour l'égalité. |

**Returns:**
boolean - `true` pour indiquer que les deux objets CharacterRange ont les mêmes valeurs First et Length ; sinon, `false`.
### op_Inequality(CharacterRange cr1, CharacterRange cr2) {#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Inequality(CharacterRange cr1, CharacterRange cr2)
```


Compare deux objets [CharacterRange](../../com.aspose.drawing/characterrange). Obtient une valeur indiquant si les valeurs First ou Length des deux objets [CharacterRange](../../com.aspose.drawing/characterrange) ne sont pas égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Un [CharacterRange](../../com.aspose.drawing/characterrange) à comparer pour l'inégalité. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Un [CharacterRange](../../com.aspose.drawing/characterrange) à comparer pour l'inégalité. |

**Returns:**
boolean - `true` pour indiquer que soit la valeur First, soit la valeur Length des deux objets CharacterRange diffèrent ; sinon, `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Obtient une valeur indiquant si cet objet est équivalent à l'objet spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à comparer pour l'égalité.. |

**Returns:**
booléen - `true` pour indiquer que l'objet spécifié est une instance avec la même valeur First et Length que cette instance ; sinon, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette instance.

**Returns:**
int - Un entier signé de 32 bits qui est le code de hachage de cette instance.
### CloneTo(CharacterRange that) {#CloneTo-com.aspose.drawing.CharacterRange-}
```
public void CloneTo(CharacterRange that)
```




**Parameters:**
| Paramètre | Type | Description |
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
