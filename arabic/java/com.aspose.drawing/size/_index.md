---
title: Size
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يخزن زوجًا مرتبًا من الأعداد الصحيحة عادةً العرض والارتفاع لمستطيل.
type: docs
weight: 42
url: /ar/java/com.aspose.drawing/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Size extends Struct<Size> implements System.IEquatable<Size>, Cloneable
```

يخزن زوجًا مرتبًا من الأعداد الصحيحة، عادةً عرض وارتفاع المستطيل.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point pt)](#Size-com.aspose.drawing.Point-) | ينشئ نسخة جديدة من بنية [Size](../../com.aspose.drawing/size) من الـ [Point](../../com.aspose.drawing/point) المحدد. |
| [Size(int width, int height)](#Size-int-int-) | ينشئ نسخة جديدة من بنية [Size](../../com.aspose.drawing/size) من الأبعاد المحددة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [to_SizeF(Size p)](#to-SizeF-com.aspose.drawing.Size-) | يحوّل الـ [Size](../../com.aspose.drawing/size) المحدد إلى [SizeF](../../com.aspose.drawing/sizef). |
| [op_Addition(Size sz1, Size sz2)](#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-) | يضيف العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) واحد إلى العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) آخر. |
| [op_Subtraction(Size sz1, Size sz2)](#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-) | يطرح العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) واحد من العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) آخر. |
| [op_Multiply(int left, Size right)](#op-Multiply-int-com.aspose.drawing.Size-) | يضرب [Size](../../com.aspose.drawing/size) في `int` منتجًا [Size](../../com.aspose.drawing/size). |
| [op_Multiply(Size left, int right)](#op-Multiply-com.aspose.drawing.Size-int-) | يضرب [Size](../../com.aspose.drawing/size) في `int` منتجًا [Size](../../com.aspose.drawing/size). |
| [op_Division(Size left, int right)](#op-Division-com.aspose.drawing.Size-int-) | يقسم [Size](../../com.aspose.drawing/size) على `int` منتجًا [Size](../../com.aspose.drawing/size). |
| [op_Multiply(float left, Size right)](#op-Multiply-float-com.aspose.drawing.Size-) | يضرب [Size](../../com.aspose.drawing/size) في `float` منتجًا [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(Size left, float right)](#op-Multiply-com.aspose.drawing.Size-float-) | يضرب [Size](../../com.aspose.drawing/size) في `float` منتجًا [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(Size left, float right)](#op-Division-com.aspose.drawing.Size-float-) | يقسم [Size](../../com.aspose.drawing/size) على `float` منتجًا [SizeF](../../com.aspose.drawing/sizef). |
| [op_Equality(Size sz1, Size sz2)](#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | يفحص ما إذا كان هيكلا [Size](../../com.aspose.drawing/size) متساويين. |
| [op_Inequality(Size sz1, Size sz2)](#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | يفحص ما إذا كان هيكلا [Size](../../com.aspose.drawing/size) مختلفين. |
| [to_Point(Size size)](#to-Point-com.aspose.drawing.Size-) | يحوّل [Size](../../com.aspose.drawing/size) المحدد إلى [Point](../../com.aspose.drawing/point). |
| [add(Size sz1, Size sz2)](#add-com.aspose.drawing.Size-com.aspose.drawing.Size-) | يضيف العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) واحد إلى العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) آخر. |
| [ceiling(SizeF value)](#ceiling-com.aspose.drawing.SizeF-) | يحوّل الهيكل [SizeF](../../com.aspose.drawing/sizef) المحدد إلى هيكل [Size](../../com.aspose.drawing/size) عن طريق تقريب قيم هيكل [Size](../../com.aspose.drawing/size) إلى القيم الصحيحة الأعلى التالية. |
| [subtract(Size sz1, Size sz2)](#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-) | يطرح العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) واحد من العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) آخر. |
| [truncate(SizeF value)](#truncate-com.aspose.drawing.SizeF-) | يحوّل الهيكل [SizeF](../../com.aspose.drawing/sizef) المحدد إلى هيكل [Size](../../com.aspose.drawing/size) عن طريق قطع قيم الهيكل [SizeF](../../com.aspose.drawing/sizef) إلى القيم الصحيحة الأدنى التالية. |
| [round(SizeF value)](#round-com.aspose.drawing.SizeF-) | يحوّل الهيكل [SizeF](../../com.aspose.drawing/sizef) المحدد إلى هيكل [Size](../../com.aspose.drawing/size) عن طريق تقريب قيم الهيكل [SizeF](../../com.aspose.drawing/sizef) إلى أقرب قيمة صحيحة. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كان هذا [Size](../../com.aspose.drawing/size) له عرض وارتفاع يساويان 0. |
| [getWidth()](#getWidth--) | يحصل على المكوّن الأفقي لهذا [Size](../../com.aspose.drawing/size). |
| [setWidth(int value)](#setWidth-int-) | يضبط المكوّن الأفقي لهذا [Size](../../com.aspose.drawing/size). |
| [getHeight()](#getHeight--) | يحصل على المكوّن العمودي لهذا [Size](../../com.aspose.drawing/size). |
| [setHeight(int value)](#setHeight-int-) | يضبط المكوّن العمودي لهذا [Size](../../com.aspose.drawing/size). |
| [equals(Object obj)](#equals-java.lang.Object-) | يفحص لمعرفة ما إذا كان الكائن المحدد هو [Size](../../com.aspose.drawing/size) له نفس الأبعاد مثل هذا [Size](../../com.aspose.drawing/size). |
| [hashCode()](#hashCode--) | يعيد رمز تجزئة لهذا الهيكل [Size](../../com.aspose.drawing/size). |
| [toString()](#toString--) |  |
| [equals(Size other)](#equals-com.aspose.drawing.Size-) | يفحص ما إذا كان هيكل [Size](../../com.aspose.drawing/size) آخر له نفس حجم هذا الهيكل [Size](../../com.aspose.drawing/size). |
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


ينشئ نسخة جديدة من بنية [Size](../../com.aspose.drawing/size) من الـ [Point](../../com.aspose.drawing/point) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | نقطة [Point](../../com.aspose.drawing/point) التي تُستخدم لتهيئة هذا [Size](../../com.aspose.drawing/size). |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


ينشئ نسخة جديدة من بنية [Size](../../com.aspose.drawing/size) من الأبعاد المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | المكوّن العرضي للـ [Size](../../com.aspose.drawing/size) الجديد. |
| height | int | المكوّن الارتفاعي للـ [Size](../../com.aspose.drawing/size) الجديد. |

### to_SizeF(Size p) {#to-SizeF-com.aspose.drawing.Size-}
```
public static SizeF to_SizeF(Size p)
```


يحوّل الـ [Size](../../com.aspose.drawing/size) المحدد إلى [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| p | [Size](../../com.aspose.drawing/size) | الـ [Size](../../com.aspose.drawing/size) للتحويل. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - The [SizeF](../../com.aspose.drawing/sizef) structure to which this operator converts.
### op_Addition(Size sz1, Size sz2) {#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Addition(Size sz1, Size sz2)
```


يضيف العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) واحد إلى العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | الـ [Size](../../com.aspose.drawing/size) الأول للإضافة. |
| sz2 | [Size](../../com.aspose.drawing/size) | الـ [Size](../../com.aspose.drawing/size) الثاني للإضافة. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(Size sz1, Size sz2) {#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Subtraction(Size sz1, Size sz2)
```


يطرح العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) واحد من العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | هيكل [Size](../../com.aspose.drawing/size) على الجانب الأيسر من عامل الطرح. |
| sz2 | [Size](../../com.aspose.drawing/size) | هيكل [Size](../../com.aspose.drawing/size) على الجانب الأيمن من عامل الطرح. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the subtraction operation.
### op_Multiply(int left, Size right) {#op-Multiply-int-com.aspose.drawing.Size-}
```
public static Size op_Multiply(int left, Size right)
```


يضرب [Size](../../com.aspose.drawing/size) في `int` منتجًا [Size](../../com.aspose.drawing/size).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | int | المضاعف من النوع `int`. |
| right | [Size](../../com.aspose.drawing/size) | المضروب من النوع [Size](../../com.aspose.drawing/size). |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Multiply(Size left, int right) {#op-Multiply-com.aspose.drawing.Size-int-}
```
public static Size op_Multiply(Size left, int right)
```


يضرب [Size](../../com.aspose.drawing/size) في `int` منتجًا [Size](../../com.aspose.drawing/size).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | المضروب من النوع [Size](../../com.aspose.drawing/size). |
| right | int | المضاعف من النوع `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Division(Size left, int right) {#op-Division-com.aspose.drawing.Size-int-}
```
public static Size op_Division(Size left, int right)
```


يقسم [Size](../../com.aspose.drawing/size) على `int` منتجًا [Size](../../com.aspose.drawing/size).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | المقسوم من النوع [Size](../../com.aspose.drawing/size). |
| right | int | المقسوم عليه من النوع `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Result of type [Size](../../com.aspose.drawing/size).
### op_Multiply(float left, Size right) {#op-Multiply-float-com.aspose.drawing.Size-}
```
public static SizeF op_Multiply(float left, Size right)
```


يضرب [Size](../../com.aspose.drawing/size) في `float` منتجًا [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | float | المضاعف من النوع `float`. |
| right | [Size](../../com.aspose.drawing/size) | المضروب من النوع [Size](../../com.aspose.drawing/size). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(Size left, float right) {#op-Multiply-com.aspose.drawing.Size-float-}
```
public static SizeF op_Multiply(Size left, float right)
```


يضرب [Size](../../com.aspose.drawing/size) في `float` منتجًا [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | المضروب من النوع [Size](../../com.aspose.drawing/size). |
| right | float | المضاعف من النوع `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(Size left, float right) {#op-Division-com.aspose.drawing.Size-float-}
```
public static SizeF op_Division(Size left, float right)
```


يقسم [Size](../../com.aspose.drawing/size) على `float` منتجًا [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | المقسوم من النوع [Size](../../com.aspose.drawing/size). |
| right | float | المقسوم عليه من النوع `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### op_Equality(Size sz1, Size sz2) {#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Equality(Size sz1, Size sz2)
```


يفحص ما إذا كان هيكلا [Size](../../com.aspose.drawing/size) متساويين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | الهيكل [Size](../../com.aspose.drawing/size) على الجانب الأيسر من عامل المساواة. |
| sz2 | [Size](../../com.aspose.drawing/size) | الهيكل [Size](../../com.aspose.drawing/size) على الجانب الأيمن من عامل المساواة. |

**Returns:**
منطقي - صحيح إذا كان `sz1` و `sz2` لهما عرض وارتفاع متساويين؛ وإلا، خطأ.
### op_Inequality(Size sz1, Size sz2) {#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Inequality(Size sz1, Size sz2)
```


يفحص ما إذا كان هيكلا [Size](../../com.aspose.drawing/size) مختلفين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | الهيكل [Size](../../com.aspose.drawing/size) على الجانب الأيسر من عامل عدم المساواة. |
| sz2 | [Size](../../com.aspose.drawing/size) | الهيكل [Size](../../com.aspose.drawing/size) على الجانب الأيمن من عامل عدم المساواة. |

**Returns:**
منطقي - صحيح إذا كان `sz1` و `sz2` يختلفان إما في العرض أو الارتفاع؛ خطأ إذا كان `sz1` و `sz2` متساويين.
### to_Point(Size size) {#to-Point-com.aspose.drawing.Size-}
```
public static Point to_Point(Size size)
```


يحوّل [Size](../../com.aspose.drawing/size) المحدد إلى [Point](../../com.aspose.drawing/point).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | الـ [Size](../../com.aspose.drawing/size) للتحويل. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) structure to which this operator converts.
### add(Size sz1, Size sz2) {#add-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size add(Size sz1, Size sz2)
```


يضيف العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) واحد إلى العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | الـ [Size](../../com.aspose.drawing/size) الأول للإضافة. |
| sz2 | [Size](../../com.aspose.drawing/size) | الـ [Size](../../com.aspose.drawing/size) الثاني للإضافة. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### ceiling(SizeF value) {#ceiling-com.aspose.drawing.SizeF-}
```
public static Size ceiling(SizeF value)
```


يحوّل الهيكل [SizeF](../../com.aspose.drawing/sizef) المحدد إلى هيكل [Size](../../com.aspose.drawing/size) عن طريق تقريب قيم هيكل [Size](../../com.aspose.drawing/size) إلى القيم الصحيحة الأعلى التالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | الهيكل [SizeF](../../com.aspose.drawing/sizef) للتحويل. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### subtract(Size sz1, Size sz2) {#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size subtract(Size sz1, Size sz2)
```


يطرح العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) واحد من العرض والارتفاع لهيكل [Size](../../com.aspose.drawing/size) آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | هيكل [Size](../../com.aspose.drawing/size) على الجانب الأيسر من عامل الطرح. |
| sz2 | [Size](../../com.aspose.drawing/size) | هيكل [Size](../../com.aspose.drawing/size) على الجانب الأيمن من عامل الطرح. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) that is a result of the subtraction operation.
### truncate(SizeF value) {#truncate-com.aspose.drawing.SizeF-}
```
public static Size truncate(SizeF value)
```


يحوّل الهيكل [SizeF](../../com.aspose.drawing/sizef) المحدد إلى هيكل [Size](../../com.aspose.drawing/size) عن طريق قطع قيم الهيكل [SizeF](../../com.aspose.drawing/sizef) إلى القيم الصحيحة الأدنى التالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | الهيكل [SizeF](../../com.aspose.drawing/sizef) للتحويل. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### round(SizeF value) {#round-com.aspose.drawing.SizeF-}
```
public static Size round(SizeF value)
```


يحوّل الهيكل [SizeF](../../com.aspose.drawing/sizef) المحدد إلى هيكل [Size](../../com.aspose.drawing/size) عن طريق تقريب قيم الهيكل [SizeF](../../com.aspose.drawing/sizef) إلى أقرب قيمة صحيحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | الهيكل [SizeF](../../com.aspose.drawing/sizef) للتحويل. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
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


يحصل على قيمة تشير إلى ما إذا كان هذا [Size](../../com.aspose.drawing/size) له عرض وارتفاع يساويان 0.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان هذا [Size](../../com.aspose.drawing/size) له عرض وارتفاع يساوي 0.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل على المكوّن الأفقي لهذا [Size](../../com.aspose.drawing/size).

**Returns:**
int - المكوّن الأفقي لهذا [Size](../../com.aspose.drawing/size).
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


يضبط المكوّن الأفقي لهذا [Size](../../com.aspose.drawing/size).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | المكوّن الأفقي لهذا [Size](../../com.aspose.drawing/size). |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل على المكوّن العمودي لهذا [Size](../../com.aspose.drawing/size).

**Returns:**
int - المكوّن العمودي لهذا [Size](../../com.aspose.drawing/size).
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


يضبط المكوّن العمودي لهذا [Size](../../com.aspose.drawing/size).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | المكوّن العمودي لهذا [Size](../../com.aspose.drawing/size). |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يفحص لمعرفة ما إذا كان الكائن المحدد هو [Size](../../com.aspose.drawing/size) له نفس الأبعاد مثل هذا [Size](../../com.aspose.drawing/size).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للاختبار. |

**Returns:**
منطقي - صحيح إذا كان `obj` هو [Size](../../com.aspose.drawing/size) وله نفس العرض والارتفاع مثل هذا [Size](../../com.aspose.drawing/size)؛ وإلا، خطأ.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز تجزئة لهذا الهيكل [Size](../../com.aspose.drawing/size).

**Returns:**
int - قيمة عددية تحدد قيمة تجزئة لهذا الهيكل [Size](../../com.aspose.drawing/size).
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


يفحص ما إذا كان هيكل [Size](../../com.aspose.drawing/size) آخر له نفس حجم هذا الهيكل [Size](../../com.aspose.drawing/size).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [Size](../../com.aspose.drawing/size) | حجم آخر للاختبار |

**Returns:**
منطقي - تُعيد هذه الطريقة `true` إذا كان هيكل [Size](../../com.aspose.drawing/size) الآخر وخصائص العرض والارتفاع الخاصة به مساوية للخصائص المقابلة لهذا الهيكل [Size](../../com.aspose.drawing/size)؛ وإلا، `false`.
### CloneTo(Size that) {#CloneTo-com.aspose.drawing.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| معامل | نوع | الوصف |
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
