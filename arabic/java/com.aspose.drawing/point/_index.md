---
title: Point
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يمثل زوجًا مرتبًا من إحداثيات x و y صحيحة يحدد نقطة في مستوى ثنائي الأبعاد.
type: docs
weight: 36
url: /ar/java/com.aspose.drawing/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Point extends Struct<Point> implements System.IEquatable<Point>, Cloneable
```

يمثل زوجًا مرتبًا من إحداثيات x و y صحيحة يحدد نقطة في مستوى ثنائي الأبعاد.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | ينشئ مثيلاً جديدًا للهيكل [Point](../../com.aspose.drawing/point) باستخدام الإحداثيات المحددة. |
| [Point(Size sz)](#Point-com.aspose.drawing.Size-) |  |
| [Point(int dw)](#Point-int-) | ينشئ مثيلاً جديدًا للهيكل [Point](../../com.aspose.drawing/point) باستخدام إحداثيات محددة بقيمة عدد صحيح. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [EMPTY](#EMPTY) | يمثل [Point](../../com.aspose.drawing/point) يحتوي على قيم `Point.X` و `Point.Y` مضبوطة على الصفر. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [to_PointF(Point p)](#to-PointF-com.aspose.drawing.Point-) | يحوّل الهيكل [Point](../../com.aspose.drawing/point) المحدد إلى هيكل [PointF](../../com.aspose.drawing/pointf). |
| [to_Size(Point p)](#to-Size-com.aspose.drawing.Point-) |  |
| [op_Addition(Point pt, Size sz)](#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Subtraction(Point pt, Size sz)](#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Equality(Point left, Point right)](#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | يقارن كائنين من نوع [Point](../../com.aspose.drawing/point). |
| [op_Inequality(Point left, Point right)](#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | يقارن كائنين من نوع [Point](../../com.aspose.drawing/point). |
| [add(Point pt, Size sz)](#add-com.aspose.drawing.Point-com.aspose.drawing.Size-) | يضيف [Size](../../com.aspose.drawing/size) المحدد إلى [Point](../../com.aspose.drawing/point) المحدد. |
| [subtract(Point pt, Size sz)](#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [ceiling(PointF value)](#ceiling-com.aspose.drawing.PointF-) |  |
| [truncate(PointF value)](#truncate-com.aspose.drawing.PointF-) | يحوّل PointF إلى Point عن طريق تنفيذ عملية تقليم على جميع الإحداثيات. |
| [round(PointF value)](#round-com.aspose.drawing.PointF-) | يحوّل [PointF](../../com.aspose.drawing/pointf) المحدد إلى كائن Point عن طريق تقريب قيم [Point](../../com.aspose.drawing/point) إلى أقرب عدد صحيح. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-) |  |
| [getEmpty()](#getEmpty--) |  |
| [getX()](#getX--) | يحصل على الإحداثي x لهذا Point. |
| [setX(int value)](#setX-int-) | يضبط الإحداثي x لهذا Point. |
| [getY()](#getY--) | يحصل على الإحداثي y لهذا Point. |
| [setY(int value)](#setY-int-) | يضبط الإحداثي y لهذا Point. |
| [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كان هذا [Point](../../com.aspose.drawing/point) فارغًا. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذا [Point](../../com.aspose.drawing/point). |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان هذا [Point](../../com.aspose.drawing/point) يحتوي على نفس الإحداثيات كما في الكائن المحدد. |
| [offset(int dx, int dy)](#offset-int-int-) | يحوّل هذا [Point](../../com.aspose.drawing/point) بالمقدار المحدد. |
| [offset(Point p)](#offset-com.aspose.drawing.Point-) | يحوّل هذا [Point](../../com.aspose.drawing/point) بالنقطة [Point](../../com.aspose.drawing/point) المحددة. |
| [equals(Point other)](#equals-com.aspose.drawing.Point-) | يفحص ما إذا كان هيكل [Point](../../com.aspose.drawing/point) الآخر يملك نفس الموقع لهيكل [Point](../../com.aspose.drawing/point) هذا. |
| [CloneTo(Point that)](#CloneTo-com.aspose.drawing.Point-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


ينشئ مثيلاً جديدًا للهيكل [Point](../../com.aspose.drawing/point) باستخدام الإحداثيات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الموضع الأفقي للنقطة. |
| y | int | الموضع العمودي للنقطة. |

### Point(Size sz) {#Point-com.aspose.drawing.Size-}
```
public Point(Size sz)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sz | [Size](../../com.aspose.drawing/size) |  |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


ينشئ مثيلاً جديدًا للهيكل [Point](../../com.aspose.drawing/point) باستخدام إحداثيات محددة بقيمة عدد صحيح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dw | int | القيمة الصحيحة. |

### EMPTY {#EMPTY}
```
public static final Point EMPTY
```


يمثل [Point](../../com.aspose.drawing/point) يحتوي على قيم `Point.X` و `Point.Y` مضبوطة على الصفر.

### to_PointF(Point p) {#to-PointF-com.aspose.drawing.Point-}
```
public static PointF to_PointF(Point p)
```


يحوّل الهيكل [Point](../../com.aspose.drawing/point) المحدد إلى هيكل [PointF](../../com.aspose.drawing/pointf).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | الـ [Point](../../com.aspose.drawing/point) المراد تحويله. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The [PointF](../../com.aspose.drawing/pointf) that results from the conversion.
### to_Size(Point p) {#to-Size-com.aspose.drawing.Point-}
```
public static Size to_Size(Point p)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
[Size](../../com.aspose.drawing/size)
### op_Addition(Point pt, Size sz) {#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Addition(Point pt, Size sz)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Subtraction(Point pt, Size sz) {#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Subtraction(Point pt, Size sz)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Equality(Point left, Point right) {#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Equality(Point left, Point right)
```


يقارن كائنين من نوع [Point](../../com.aspose.drawing/point). النتيجة تحدد ما إذا كانت قيم خصائص `Point.X` و `Point.Y` لكائنين [Point](../../com.aspose.drawing/point) متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | أول [Point](../../com.aspose.drawing/point) للمقارنة. |
| right | [Point](../../com.aspose.drawing/point) | ثاني [Point](../../com.aspose.drawing/point) للمقارنة. |

**Returns:**
boolean - true إذا كانت قيم `Point.X` و `Point.Y` للمتغيرين `left` و `right` متساوية؛ وإلا false.
### op_Inequality(Point left, Point right) {#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Inequality(Point left, Point right)
```


يقارن كائنين من نوع [Point](../../com.aspose.drawing/point). النتيجة تحدد ما إذا كانت قيم خصائص `Point.X` أو `Point.Y` لكائنين [Point](../../com.aspose.drawing/point) غير متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | أول [Point](../../com.aspose.drawing/point) للمقارنة. |
| right | [Point](../../com.aspose.drawing/point) | ثاني [Point](../../com.aspose.drawing/point) للمقارنة. |

**Returns:**
boolean - true إذا اختلفت قيم خصائص `Point.X` أو خصائص `Point.Y` للمتغيرين `left` و `right`؛ وإلا false.
### add(Point pt, Size sz) {#add-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point add(Point pt, Size sz)
```


يضيف [Size](../../com.aspose.drawing/size) المحدد إلى [Point](../../com.aspose.drawing/point) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | النقطة [Point](../../com.aspose.drawing/point) لإضافتها. |
| sz | [Size](../../com.aspose.drawing/size) | الحجم [Size](../../com.aspose.drawing/size) لإضافته |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the addition operation.
### subtract(Point pt, Size sz) {#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point subtract(Point pt, Size sz)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### ceiling(PointF value) {#ceiling-com.aspose.drawing.PointF-}
```
public static Point ceiling(PointF value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### truncate(PointF value) {#truncate-com.aspose.drawing.PointF-}
```
public static Point truncate(PointF value)
```


يحوّل PointF إلى Point عن طريق تنفيذ عملية تقليم على جميع الإحداثيات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | النقطة [PointF](../../com.aspose.drawing/pointf) للقطع. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the truncate operation.
### round(PointF value) {#round-com.aspose.drawing.PointF-}
```
public static Point round(PointF value)
```


يحوّل [PointF](../../com.aspose.drawing/pointf) المحدد إلى كائن Point عن طريق تقريب قيم [Point](../../com.aspose.drawing/point) إلى أقرب عدد صحيح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | النقطة [PointF](../../com.aspose.drawing/pointf) للتحويل. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) this method converts to.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.drawing/point) |  |
| obj2 | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### getX() {#getX--}
```
public final int getX()
```


يحصل على الإحداثي x لهذا Point.

**Returns:**
int - إحداثي x لهذا Point.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


يضبط الإحداثي x لهذا Point.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | إحداثي x لهذا Point. |

### getY() {#getY--}
```
public final int getY()
```


يحصل على الإحداثي y لهذا Point.

**Returns:**
int - إحداثي y لهذا Point.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


يضبط الإحداثي y لهذا Point.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | إحداثي y لهذا Point. |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


يحصل على قيمة تشير إلى ما إذا كان هذا [Point](../../com.aspose.drawing/point) فارغًا.

القيمة: `true` إذا كان كل من X و Y يساوي 0؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان هذا [Point](../../com.aspose.drawing/point) فارغًا.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة لهذا [Point](../../com.aspose.drawing/point).

**Returns:**
int - قيمة عددية تحدد قيمة تجزئة لهذا [Point](../../com.aspose.drawing/point).
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


يحدد ما إذا كان هذا [Point](../../com.aspose.drawing/point) يحتوي على نفس الإحداثيات كما في الكائن المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للاختبار. |

**Returns:**
boolean - `true` إذا كان obj من نوع Point وله نفس الإحداثيات مثل هذا [Point](../../com.aspose.drawing/point).
### offset(int dx, int dy) {#offset-int-int-}
```
public final void offset(int dx, int dy)
```


يحوّل هذا [Point](../../com.aspose.drawing/point) بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | int | القيمة لإزاحة إحداثي x. |
| dy | int | القيمة لإزاحة إحداثي y. |

### offset(Point p) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point p)
```


يحوّل هذا [Point](../../com.aspose.drawing/point) بالنقطة [Point](../../com.aspose.drawing/point) المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | النقطة [Point](../../com.aspose.drawing/point) المستخدمة لإزاحة هذه [Point](../../com.aspose.drawing/point). |

### equals(Point other) {#equals-com.aspose.drawing.Point-}
```
public final boolean equals(Point other)
```


يفحص ما إذا كان هيكل [Point](../../com.aspose.drawing/point) الآخر يملك نفس الموقع لهيكل [Point](../../com.aspose.drawing/point) هذا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [Point](../../com.aspose.drawing/point) | نقطة أخرى للاختبار |

**Returns:**
boolean - تُعيد هذه الطريقة `true` إذا كانت بنية [Point](../../com.aspose.drawing/point) الأخرى وخصائص X و Y الخاصة بها مساوية للخصائص المقابلة في بنية هذا [Point](../../com.aspose.drawing/point); وإلا `false`.
### CloneTo(Point that) {#CloneTo-com.aspose.drawing.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| that | [Point](../../com.aspose.drawing/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
