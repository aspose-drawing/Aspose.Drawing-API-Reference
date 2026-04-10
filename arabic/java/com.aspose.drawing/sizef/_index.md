---
title: SizeF
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يخزن زوجًا مرتبًا من الأعداد ذات الفاصلة العائمة عادةً العرض والارتفاع لمستطيل.
type: docs
weight: 43
url: /ar/java/com.aspose.drawing/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class SizeF extends Struct<SizeF> implements System.IEquatable<SizeF>, Cloneable
```

يخزن زوجًا مرتبًا من الأعداد ذات نقطة عائمة، عادةً عرض وارتفاع المستطيل.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(float width, float height)](#SizeF-float-float-) | ينشئ مثيلًا جديدًا لبنية SizeF من الأبعاد المحددة. |
| [SizeF(PointF pt)](#SizeF-com.aspose.drawing.PointF-) | ينشئ مثيلًا جديدًا للهيكل [SizeF](../../com.aspose.drawing/sizef). |
| [SizeF(SizeF size)](#SizeF-com.aspose.drawing.SizeF-) | ينشئ مثيلًا جديدًا للهيكل [SizeF](../../com.aspose.drawing/sizef). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [op_Equality(SizeF sz1, SizeF sz2)](#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | يفحص ما إذا كان بنائي [SizeF](../../com.aspose.drawing/sizef) متساويين. |
| [op_Inequality(SizeF sz1, SizeF sz2)](#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | يفحص ما إذا كان بنائي [SizeF](../../com.aspose.drawing/sizef) مختلفين. |
| [add(SizeF sz1, SizeF sz2)](#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | يضيف العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) واحدة إلى العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) أخرى. |
| [subtract(SizeF sz1, SizeF sz2)](#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | يطرح العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) واحدة من العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) أخرى. |
| [op_Addition(SizeF sz1, SizeF sz2)](#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | يضيف العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) واحدة إلى العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) أخرى. |
| [op_Subtraction(SizeF sz1, SizeF sz2)](#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | يطرح العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) واحدة من العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) أخرى. |
| [op_Multiply(float left, SizeF right)](#op-Multiply-float-com.aspose.drawing.SizeF-) | يضرب [SizeF](../../com.aspose.drawing/sizef) في `float` منتجًا [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(SizeF left, float right)](#op-Multiply-com.aspose.drawing.SizeF-float-) | يضرب [SizeF](../../com.aspose.drawing/sizef) في `float` منتجًا [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(SizeF left, float right)](#op-Division-com.aspose.drawing.SizeF-float-) | يقسم [SizeF](../../com.aspose.drawing/sizef) على `float` منتجًا [SizeF](../../com.aspose.drawing/sizef). |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كان هيكل [SizeF](../../com.aspose.drawing/sizef) هذا له عرض وارتفاع صفر. |
| [getWidth()](#getWidth--) | يحصل على المكوّن الأفقي لهذا الهيكل SizeF. |
| [setWidth(float value)](#setWidth-float-) | يضبط المكوّن الأفقي لهذا الهيكل SizeF. |
| [getHeight()](#getHeight--) | يحصل على المكوّن الرأسي لهذا الهيكل SizeF. |
| [setHeight(float value)](#setHeight-float-) | يضبط المكوّن الرأسي لهذا الهيكل SizeF. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذا الهيكل [SizeF](../../com.aspose.drawing/sizef). |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يفحص لمعرفة ما إذا كان الكائن المحدد هو هيكل [SizeF](../../com.aspose.drawing/sizef) له نفس الأبعاد مثل هذا الهيكل [SizeF](../../com.aspose.drawing/sizef). |
| [toSize()](#toSize--) | يحوّل هيكل [SizeF](../../com.aspose.drawing/sizef) إلى هيكل [Size](../../com.aspose.drawing/size). |
| [toPointF()](#toPointF--) | يحوّل هيكل [SizeF](../../com.aspose.drawing/sizef) إلى هيكل [PointF](../../com.aspose.drawing/pointf). |
| [equals(SizeF other)](#equals-com.aspose.drawing.SizeF-) | يفحص ما إذا كان هيكل [SizeF](../../com.aspose.drawing/sizef) الآخر له نفس حجم هذا الهيكل [SizeF](../../com.aspose.drawing/sizef). |
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


ينشئ مثيلًا جديدًا لبنية SizeF من الأبعاد المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | float | المكوّن العرضي للهيكل SizeF الجديد. |
| الارتفاع | float | المكوّن الارتفاعي للهيكل SizeF الجديد. |

### SizeF(PointF pt) {#SizeF-com.aspose.drawing.PointF-}
```
public SizeF(PointF pt)
```


ينشئ مثيلًا جديدًا للهيكل [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | هيكل [PointF](../../com.aspose.drawing/pointf) الذي يُستخدم لتهيئة هذا الهيكل [SizeF](../../com.aspose.drawing/sizef). |

### SizeF(SizeF size) {#SizeF-com.aspose.drawing.SizeF-}
```
public SizeF(SizeF size)
```


ينشئ مثيلًا جديدًا للهيكل [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | هيكل [SizeF](../../com.aspose.drawing/sizef) الذي يُستخدم لإنشاء الهيكل [SizeF](../../com.aspose.drawing/sizef) الجديد. |

### op_Equality(SizeF sz1, SizeF sz2) {#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Equality(SizeF sz1, SizeF sz2)
```


يفحص ما إذا كان بنائي [SizeF](../../com.aspose.drawing/sizef) متساويين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | هيكل [SizeF](../../com.aspose.drawing/sizef) على الجانب الأيسر من عامل المساواة. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | هيكل [SizeF](../../com.aspose.drawing/sizef) على الجانب الأيمن من عامل المساواة. |

**Returns:**
منطقي - يُعيد هذا العامل true إذا كان `sz1` و `sz2` لهما عرض وارتفاع متساويين؛ وإلا false.
### op_Inequality(SizeF sz1, SizeF sz2) {#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Inequality(SizeF sz1, SizeF sz2)
```


يفحص ما إذا كان بنائي [SizeF](../../com.aspose.drawing/sizef) مختلفين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | هيكل [SizeF](../../com.aspose.drawing/sizef) على الجانب الأيسر من عامل عدم المساواة. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | هيكل [SizeF](../../com.aspose.drawing/sizef) على الجانب الأيمن من عامل عدم المساواة. |

**Returns:**
منطقي - يُعيد هذا العامل true إذا كان `sz1` و `sz2` يختلفان إما في العرض أو الارتفاع؛ false إذا كان `sz1` و `sz2` متساويين.
### add(SizeF sz1, SizeF sz2) {#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF add(SizeF sz1, SizeF sz2)
```


يضيف العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) واحدة إلى العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) أخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | الهيكل [SizeF](../../com.aspose.drawing/sizef) الأول للإضافة. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | الهيكل [SizeF](../../com.aspose.drawing/sizef) الثاني للإضافة. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is the result of the addition operation.
### subtract(SizeF sz1, SizeF sz2) {#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF subtract(SizeF sz1, SizeF sz2)
```


يطرح العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) واحدة من العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) أخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | هيكل [SizeF](../../com.aspose.drawing/sizef) على الجانب الأيسر من عامل الطرح. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | البنية [SizeF](../../com.aspose.drawing/sizef) على الجانب الأيمن من عامل الطرح. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is a result of the subtraction operation.
### op_Addition(SizeF sz1, SizeF sz2) {#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Addition(SizeF sz1, SizeF sz2)
```


يضيف العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) واحدة إلى العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) أخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | الهيكل [SizeF](../../com.aspose.drawing/sizef) الأول للإضافة. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | الهيكل [SizeF](../../com.aspose.drawing/sizef) الثاني للإضافة. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(SizeF sz1, SizeF sz2) {#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Subtraction(SizeF sz1, SizeF sz2)
```


يطرح العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) واحدة من العرض والارتفاع لبنية [SizeF](../../com.aspose.drawing/sizef) أخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | هيكل [SizeF](../../com.aspose.drawing/sizef) على الجانب الأيسر من عامل الطرح. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | البنية [SizeF](../../com.aspose.drawing/sizef) على الجانب الأيمن من عامل الطرح. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that is the result of the subtraction operation.
### op_Multiply(float left, SizeF right) {#op-Multiply-float-com.aspose.drawing.SizeF-}
```
public static SizeF op_Multiply(float left, SizeF right)
```


يضرب [SizeF](../../com.aspose.drawing/sizef) في `float` منتجًا [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | float | المضاعف من النوع `float`. |
| right | [SizeF](../../com.aspose.drawing/sizef) | المضاعف من النوع [SizeF](../../com.aspose.drawing/sizef). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(SizeF left, float right) {#op-Multiply-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Multiply(SizeF left, float right)
```


يضرب [SizeF](../../com.aspose.drawing/sizef) في `float` منتجًا [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | المضاعف من النوع [SizeF](../../com.aspose.drawing/sizef). |
| right | float | المضاعف من النوع `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(SizeF left, float right) {#op-Division-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Division(SizeF left, float right)
```


يقسم [SizeF](../../com.aspose.drawing/sizef) على `float` منتجًا [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | المقسوم من النوع [SizeF](../../com.aspose.drawing/sizef). |
| right | float | المقسوم عليه من النوع `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### to_PointF(SizeF size) {#to-PointF-com.aspose.drawing.SizeF-}
```
public static PointF to_PointF(SizeF size)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
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


يحصل على قيمة تشير إلى ما إذا كان هيكل [SizeF](../../com.aspose.drawing/sizef) هذا له عرض وارتفاع صفر.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كانت البنية [SizeF](../../com.aspose.drawing/sizef) لها عرض وارتفاع صفر.
### getWidth() {#getWidth--}
```
public final float getWidth()
```


يحصل على المكوّن الأفقي لهذا الهيكل SizeF.

**Returns:**
عائم - المكوّن الأفقي لهذه البنية SizeF.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


يضبط المكوّن الأفقي لهذا الهيكل SizeF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | المكوّن الأفقي لهذه البنية SizeF. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


يحصل على المكوّن الرأسي لهذا الهيكل SizeF.

**Returns:**
عائم - المكوّن العمودي لهذه البنية SizeF.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


يضبط المكوّن الرأسي لهذا الهيكل SizeF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | المكوّن العمودي لهذه البنية SizeF. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة لهذا الهيكل [SizeF](../../com.aspose.drawing/sizef).

**Returns:**
عدد صحيح - قيمة عددية تحدد قيمة تجزئة لهذه البنية [SizeF](../../com.aspose.drawing/sizef).
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


يفحص لمعرفة ما إذا كان الكائن المحدد هو هيكل [SizeF](../../com.aspose.drawing/sizef) له نفس الأبعاد مثل هذا الهيكل [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للاختبار. |

**Returns:**
منطقي - تُعيد هذه الطريقة `true` إذا كان obj هو [SizeF](../../com.aspose.drawing/sizef) وله نفس العرض والارتفاع مثل هذا SizeF؛ وإلا `false`.
### toSize() {#toSize--}
```
public final Size toSize()
```


يحوّل هيكل [SizeF](../../com.aspose.drawing/sizef) إلى هيكل [Size](../../com.aspose.drawing/size).

**Returns:**
[Size](../../com.aspose.drawing/size) - Returns a [Size](../../com.aspose.drawing/size) structure.
### toPointF() {#toPointF--}
```
public final PointF toPointF()
```


يحوّل هيكل [SizeF](../../com.aspose.drawing/sizef) إلى هيكل [PointF](../../com.aspose.drawing/pointf).

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - Returns a [PointF](../../com.aspose.drawing/pointf) structure.
### equals(SizeF other) {#equals-com.aspose.drawing.SizeF-}
```
public final boolean equals(SizeF other)
```


يفحص ما إذا كان هيكل [SizeF](../../com.aspose.drawing/sizef) الآخر له نفس حجم هذا الهيكل [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [SizeF](../../com.aspose.drawing/sizef) | حجم آخر للاختبار |

**Returns:**
منطقي - تُعيد هذه الطريقة `true` إذا كانت بنية [SizeF](../../com.aspose.drawing/sizef) الأخرى وخصائص Width و Height الخاصة بها مساوية للخصائص المقابلة في بنية [SizeF](../../com.aspose.drawing/sizef) هذه؛ وإلا `false`.
### CloneTo(SizeF that) {#CloneTo-com.aspose.drawing.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| معامل | نوع | الوصف |
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
