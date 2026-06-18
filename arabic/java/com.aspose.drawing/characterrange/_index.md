---
title: CharacterRange
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحدد نطاقًا من مواضع الأحرف داخل سلسلة.
type: docs
weight: 13
url: /ar/java/com.aspose.drawing/characterrange/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class CharacterRange extends Struct<CharacterRange> implements Cloneable
```

يحدد نطاقًا من مواضع الأحرف داخل سلسلة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [CharacterRange()](#CharacterRange--) |  |
| [CharacterRange(int first, int length)](#CharacterRange-int-int-) | يُنشئ مثيلًا جديدًا من بنية [CharacterRange](../../com.aspose.drawing/characterrange) ، محددًا نطاقًا من مواضع الأحرف داخل سلسلة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFirst()](#getFirst--) | يحصل أو يعيّن موضع الحرف الأول في السلسلة لهذا [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setFirst(int value)](#setFirst-int-) | يحصل أو يعيّن موضع الحرف الأول في السلسلة لهذا [CharacterRange](../../com.aspose.drawing/characterrange). |
| [getLength()](#getLength--) | يحصل أو يعيّن عدد المواضع في هذا [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setLength(int value)](#setLength-int-) | يحصل أو يعيّن عدد المواضع في هذا [CharacterRange](../../com.aspose.drawing/characterrange). |
| [op_Equality(CharacterRange cr1, CharacterRange cr2)](#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | يقارن كائنين من نوع [CharacterRange](../../com.aspose.drawing/characterrange). |
| [op_Inequality(CharacterRange cr1, CharacterRange cr2)](#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | يقارن كائنين من نوع [CharacterRange](../../com.aspose.drawing/characterrange). |
| [equals(Object obj)](#equals-java.lang.Object-) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن مكافئًا للكائن المحدد. |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذا المثيل. |
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


يُنشئ مثيلًا جديدًا من بنية [CharacterRange](../../com.aspose.drawing/characterrange) ، محددًا نطاقًا من مواضع الأحرف داخل سلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الأول | int | موضع الحرف الأول في النطاق. على سبيل المثال، إذا تم تعيين First إلى 0، فإن الموضع الأول للنطاق هو الموضع 0 في السلسلة. |
| الطول | int | عدد المواضع في النطاق. |

### getFirst() {#getFirst--}
```
public final int getFirst()
```


يحصل أو يعيّن موضع الحرف الأول في السلسلة لهذا [CharacterRange](../../com.aspose.drawing/characterrange).

القيمة: الموضع الأول لهذا [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setFirst(int value) {#setFirst-int-}
```
public final void setFirst(int value)
```


يحصل أو يعيّن موضع الحرف الأول في السلسلة لهذا [CharacterRange](../../com.aspose.drawing/characterrange).

القيمة: الموضع الأول لهذا [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLength() {#getLength--}
```
public final int getLength()
```


يحصل أو يعيّن عدد المواضع في هذا [CharacterRange](../../com.aspose.drawing/characterrange).

القيمة: عدد المواضع في هذا [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


يحصل أو يعيّن عدد المواضع في هذا [CharacterRange](../../com.aspose.drawing/characterrange).

القيمة: عدد المواضع في هذا [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### op_Equality(CharacterRange cr1, CharacterRange cr2) {#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Equality(CharacterRange cr1, CharacterRange cr2)
```


يقارن كائنين من نوع [CharacterRange](../../com.aspose.drawing/characterrange). يحصل على قيمة تشير إلى ما إذا كانت قيمتي First و Length لكائنين من نوع [CharacterRange](../../com.aspose.drawing/characterrange) متساويتين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | كائن [CharacterRange](../../com.aspose.drawing/characterrange) للمقارنة من أجل المساواة. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | كائن [CharacterRange](../../com.aspose.drawing/characterrange) للمقارنة من أجل المساواة. |

**Returns:**
boolean - `true` للإشارة إلى أن كائنين CharacterRange لهما نفس قيمتي First و Length؛ وإلا `false`.
### op_Inequality(CharacterRange cr1, CharacterRange cr2) {#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Inequality(CharacterRange cr1, CharacterRange cr2)
```


يقارن كائنين من نوع [CharacterRange](../../com.aspose.drawing/characterrange). يحصل على قيمة تشير إلى ما إذا كانت قيمتي First أو Length لكائنين من نوع [CharacterRange](../../com.aspose.drawing/characterrange) غير متساويتين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | كائن [CharacterRange](../../com.aspose.drawing/characterrange) للمقارنة من أجل عدم المساواة. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | كائن [CharacterRange](../../com.aspose.drawing/characterrange) للمقارنة من أجل عدم المساواة. |

**Returns:**
boolean - `true` للإشارة إلى أن إما قيمة First أو Length لكائنين CharacterRange تختلف؛ وإلا `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن مكافئًا للكائن المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة من أجل المساواة.. |

**Returns:**
منطقي - `true` للإشارة إلى أن الكائن المحدد هو نسخة ذات نفس قيمة First و Length كما هذه النسخة؛ وإلا، `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز التجزئة لهذا المثيل.

**Returns:**
int - عدد صحيح 32-بت موقع يُستخدم كرمز تجزئة (hash code) لهذه النسخة.
### CloneTo(CharacterRange that) {#CloneTo-com.aspose.drawing.CharacterRange-}
```
public void CloneTo(CharacterRange that)
```




**Parameters:**
| معامل | نوع | الوصف |
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
