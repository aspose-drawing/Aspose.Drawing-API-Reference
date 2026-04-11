---
title: CharacterRange
second_title: Справочник API Aspose.Drawing для Java
description: Указывает диапазон позиций символов в строке.
type: docs
weight: 13
url: /ru/java/com.aspose.drawing/characterrange/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class CharacterRange extends Struct<CharacterRange> implements Cloneable
```

Указывает диапазон позиций символов в строке.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CharacterRange()](#CharacterRange--) |  |
| [CharacterRange(int first, int length)](#CharacterRange-int-int-) | Инициализирует новый экземпляр структуры [CharacterRange](../../com.aspose.drawing/characterrange), указывая диапазон позиций символов в строке. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFirst()](#getFirst--) | Получает или задает позицию в строке первого символа этого [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setFirst(int value)](#setFirst-int-) | Получает или задает позицию в строке первого символа этого [CharacterRange](../../com.aspose.drawing/characterrange). |
| [getLength()](#getLength--) | Получает или задает количество позиций в этом [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setLength(int value)](#setLength-int-) | Получает или задает количество позиций в этом [CharacterRange](../../com.aspose.drawing/characterrange). |
| [op_Equality(CharacterRange cr1, CharacterRange cr2)](#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Сравнивает два объекта [CharacterRange](../../com.aspose.drawing/characterrange). |
| [op_Inequality(CharacterRange cr1, CharacterRange cr2)](#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Сравнивает два объекта [CharacterRange](../../com.aspose.drawing/characterrange). |
| [equals(Object obj)](#equals-java.lang.Object-) | Получает значение, указывающее, эквивалентен ли этот объект указанному объекту. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
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


Инициализирует новый экземпляр структуры [CharacterRange](../../com.aspose.drawing/characterrange), указывая диапазон позиций символов в строке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| first | int | Позиция первого символа в диапазоне. Например, если First установлен в 0, первая позиция диапазона — позиция 0 в строке. |
| length | int | Количество позиций в диапазоне. |

### getFirst() {#getFirst--}
```
public final int getFirst()
```


Получает или задает позицию в строке первого символа этого [CharacterRange](../../com.aspose.drawing/characterrange).

Значение: первая позиция этого [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setFirst(int value) {#setFirst-int-}
```
public final void setFirst(int value)
```


Получает или задает позицию в строке первого символа этого [CharacterRange](../../com.aspose.drawing/characterrange).

Значение: первая позиция этого [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLength() {#getLength--}
```
public final int getLength()
```


Получает или задает количество позиций в этом [CharacterRange](../../com.aspose.drawing/characterrange).

Значение: количество позиций в этом [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


Получает или задает количество позиций в этом [CharacterRange](../../com.aspose.drawing/characterrange).

Значение: количество позиций в этом [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### op_Equality(CharacterRange cr1, CharacterRange cr2) {#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Equality(CharacterRange cr1, CharacterRange cr2)
```


Сравнивает два объекта [CharacterRange](../../com.aspose.drawing/characterrange). Получает значение, указывающее, равны ли значения First и Length у двух объектов [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Объект [CharacterRange](../../com.aspose.drawing/characterrange) для сравнения на равенство. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Объект [CharacterRange](../../com.aspose.drawing/characterrange) для сравнения на равенство. |

**Returns:**
boolean - `true`, если два объекта CharacterRange имеют одинаковые значения First и Length; иначе `false`.
### op_Inequality(CharacterRange cr1, CharacterRange cr2) {#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Inequality(CharacterRange cr1, CharacterRange cr2)
```


Сравнивает два объекта [CharacterRange](../../com.aspose.drawing/characterrange). Получает значение, указывающее, не равны ли значения First или Length у двух объектов [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Объект [CharacterRange](../../com.aspose.drawing/characterrange) для сравнения на неравенство. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Объект [CharacterRange](../../com.aspose.drawing/characterrange) для сравнения на неравенство. |

**Returns:**
boolean - `true`, если значения First или Length у двух объектов CharacterRange различаются; иначе `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Получает значение, указывающее, эквивалентен ли этот объект указанному объекту.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения на равенство. |

**Returns:**
boolean - `true`, если указанный объект является экземпляром с тем же значением First и Length, что и этот экземпляр; иначе `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int - 32-битное знаковое целое, которое является хеш-кодом для этого экземпляра.
### CloneTo(CharacterRange that) {#CloneTo-com.aspose.drawing.CharacterRange-}
```
public void CloneTo(CharacterRange that)
```




**Parameters:**
| Параметр | Тип | Описание |
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
