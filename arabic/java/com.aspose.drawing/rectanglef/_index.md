---
title: RectangleF
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يخزن مجموعة من أربعة أعداد ذات نقطة عائمة تمثل موقع وحجم المستطيل.
type: docs
weight: 39
url: /ar/java/com.aspose.drawing/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class RectangleF extends Struct<RectangleF> implements System.IEquatable<RectangleF>, Cloneable
```

يخزن مجموعة من أربعة أعداد عائمة تمثل موقع وحجم المستطيل. للحصول على وظائف منطقة أكثر تقدمًا، استخدم كائن Region.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | يُهيئ نسخة جديدة من بنية RectangleF بالموقع والحجم المحددين. |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | يُهيئ نسخة جديدة من بنية RectangleF بالموقع والحجم المحددين. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | ينشئ مستطيلًا جديدًا من نقطتين. |
| [to_RectangleF(Rectangle r)](#to-RectangleF-com.aspose.drawing.Rectangle-) | يحوّل بنية Rectangle المحددة إلى بنية RectangleF. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | يفحص ما إذا كانت بنية [RectangleF](../../com.aspose.drawing/rectanglef) اثنتين لهما موقع وحجم متساويين. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | يفحص ما إذا كانت بنية [RectangleF](../../com.aspose.drawing/rectanglef) اثنتين تختلفان في الموقع أو الحجم. |
| [fromLTRB(float left, float top, float right, float bottom)](#fromLTRB-float-float-float-float-) | ينشئ بنية RectangleF بزواية أعلى اليسار وأسفل اليمين في المواقع المحددة. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.drawing.RectangleF-float-float-) | ينشئ ويعيد نسخة موسعة من بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | يعيد بنية [RectangleF](../../com.aspose.drawing/rectanglef) تمثل تقاطع مستطيلين. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | ينشئ أصغر مستطيل ثالث ممكن يمكنه احتواء المستطيلين الذين يشكلان اتحادًا. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كانت الخاصية `RectangleF.Width` أو `RectangleF.Height` لهذا [RectangleF](../../aspose.drawing/rectanglef) تساوي الصفر. |
| [getX()](#getX--) | يحصل على إحداثي x للزاوية العليا اليسرى لهذه البنية RectangleF. |
| [setX(float value)](#setX-float-) | يضبط إحداثي x للزاوية العليا اليسرى لهذه البنية RectangleF. |
| [getY()](#getY--) | يحصل على إحداثي x للزاوية العليا اليسرى لهذه البنية RectangleF. |
| [setY(float value)](#setY-float-) | يضبط إحداثي x للزاوية العليا اليسرى لهذه البنية RectangleF. |
| [getLocation()](#getLocation--) | يحصل على إحداثيات الزاوية العليا اليسرى لهذه البنية [RectangleF](../../com.aspose.drawing/rectanglef). |
| [setLocation(PointF value)](#setLocation-com.aspose.drawing.PointF-) | يضبط إحداثيات الزاوية العلوية اليسرى لهذا الهيكل [RectangleF](../../com.aspose.drawing/rectanglef). |
| [getWidth()](#getWidth--) | يحصل على عرض هذا الهيكل RectangleF. |
| [setWidth(float value)](#setWidth-float-) | يضبط عرض هذا الهيكل RectangleF. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع هذا الهيكل RectangleF. |
| [setHeight(float value)](#setHeight-float-) | يضبط ارتفاع هذا الهيكل RectangleF. |
| [getSize()](#getSize--) | يحصل على حجم هذا [RectangleF](../../com.aspose.drawing/rectanglef). |
| [setSize(SizeF value)](#setSize-com.aspose.drawing.SizeF-) | يضبط حجم هذا [RectangleF](../../com.aspose.drawing/rectanglef). |
| [getLeft()](#getLeft--) | يحصل على إحداثي x للحافة اليسرى لهذا الهيكل RectangleF. |
| [getTop()](#getTop--) | يحصل على إحداثي y للحافة العلوية لهذا الهيكل RectangleF. |
| [getRight()](#getRight--) | يحصل على إحداثي x الذي هو مجموع X والعرض لهذا الهيكل RectangleF. |
| [getBottom()](#getBottom--) | يحصل على إحداثي y الذي هو مجموع Y والارتفاع لهذا الهيكل RectangleF. |
| [toString()](#toString--) |  |
| [inflate(float x, float y)](#inflate-float-float-) | يوسع هذا [RectangleF](../../com.aspose.drawing/rectanglef) بالكمية المحددة. |
| [inflate(SizeF size)](#inflate-com.aspose.drawing.SizeF-) | يوسع هذا [RectangleF](../../com.aspose.drawing/rectanglef) بالكمية المحددة. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | يستبدل هذا [RectangleF](../../com.aspose.drawing/rectanglef) بالتقاطع بينه وبين الهيكل [RectangleF](../../com.aspose.drawing/rectanglef) المحدد. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.drawing.RectangleF-) | يحدد ما إذا كان هذا المستطيل يتقاطع مع `rect`. |
| [offset(PointF pos)](#offset-com.aspose.drawing.PointF-) | يضبط موقع هذا المستطيل بالكمية المحددة. |
| [offset(float x, float y)](#offset-float-float-) | يضبط موقع هذا المستطيل بالكمية المحددة. |
| [contains(float x, float y)](#contains-float-float-) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [RectangleF](../../com.aspose.drawing/rectanglef). |
| [contains(PointF pt)](#contains-com.aspose.drawing.PointF-) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [RectangleF](../../com.aspose.drawing/rectanglef). |
| [contains(RectangleF rect)](#contains-com.aspose.drawing.RectangleF-) | يحدد ما إذا كانت المنطقة المستطيلة الممثلة بـ `rect` موجودة بالكامل داخل هذا [RectangleF](../../com.aspose.drawing/rectanglef). |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد يساوي هذه الحالة. |
| [hashCode()](#hashCode--) | يعيد رمز تجزئة لهذه الحالة. |
| [equals(RectangleF other)](#equals-com.aspose.drawing.RectangleF-) | يفحص ما إذا كان الهيكل [RectangleF](../../com.aspose.drawing/rectanglef) الآخر له نفس الموقع والحجم لهذا الهيكل [RectangleF](../../com.aspose.drawing/rectanglef). |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.drawing.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


يُهيئ نسخة جديدة من بنية RectangleF بالموقع والحجم المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| location | [PointF](../../com.aspose.drawing/pointf) | نقطة PointF تمثل الزاوية العلوية اليسرى للمنطقة المستطيلة. |
| size | [SizeF](../../com.aspose.drawing/sizef) | حجم SizeF يمثل العرض والارتفاع للمنطقة المستطيلة. |

### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


يُهيئ نسخة جديدة من بنية RectangleF بالموقع والحجم المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للزاوية العلوية اليسرى للمستطيل. |
| y | float | إحداثي y للزاوية العلوية اليسرى للمستطيل. |
| العرض | float | عرض المستطيل. |
| الارتفاع | float | ارتفاع المستطيل. |

### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


ينشئ مستطيلًا جديدًا من نقطتين. سيتم تطبيع المستطيل المُنشأ بحيث يكون (left,top) أقل من (right,bottom).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | النقطة الأولى. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | النقطة الثانية. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A newly created rectangle.
### to_RectangleF(Rectangle r) {#to-RectangleF-com.aspose.drawing.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle r)
```


يحوّل بنية Rectangle المحددة إلى بنية RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| r | [Rectangle](../../com.aspose.drawing/rectangle) | هيكل Rectangle للتحويل. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The RectangleF structure that is converted from the specified Rectangle structure.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


يفحص ما إذا كانت بنية [RectangleF](../../com.aspose.drawing/rectanglef) اثنتين لهما موقع وحجم متساويين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | الهيكل [RectangleF](../../com.aspose.drawing/rectanglef) الموجود إلى يسار عامل المساواة. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | الهيكل [RectangleF](../../com.aspose.drawing/rectanglef) الموجود إلى يمين عامل المساواة. |

**Returns:**
boolean - يُعيد هذا العامل true إذا كان الهيكلان المحددان [RectangleF](../../com.aspose.drawing/rectanglef) يمتلكان خصائص `RectangleF.X`، `RectangleF.Y`، `RectangleF.Width`، و`RectangleF.Height` متساوية.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


يفحص ما إذا كانت بنية [RectangleF](../../com.aspose.drawing/rectanglef) اثنتين تختلفان في الموقع أو الحجم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | الهيكل [RectangleF](../../com.aspose.drawing/rectanglef) الموجود إلى يسار عامل عدم المساواة. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | الهيكل [RectangleF](../../com.aspose.drawing/rectanglef) الموجود إلى يمين عامل عدم المساواة. |

**Returns:**
boolean - يُعيد هذا العامل true إذا كان أي من خصائص `RectangleF.X` أو `RectangleF.Y` أو `RectangleF.Width` أو `RectangleF.Height` للهيكلين [Rectangle](../../com.aspose.drawing/rectangle) غير متساوية؛ وإلا false.
### fromLTRB(float left, float top, float right, float bottom) {#fromLTRB-float-float-float-float-}
```
public static RectangleF fromLTRB(float left, float top, float right, float bottom)
```


ينشئ بنية RectangleF بزواية أعلى اليسار وأسفل اليمين في المواقع المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | float | إحداثي x للزاوية العلوية اليسرى للمنطقة المستطيلة. |
| top | float | إحداثي y للزاوية العلوية اليسرى للمنطقة المستطيلة. |
| right | float | إحداثي x للزاوية السفلية اليمنى للمنطقة المستطيلة. |
| bottom | float | إحداثي y للزاوية السفلية اليمنى للمنطقة المستطيلة. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The new RectangleF that this method creates.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.drawing.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


ينشئ ويعيد نسخة مُضخمة من الهيكل [RectangleF](../../com.aspose.drawing/rectanglef) المحدد. يتم تضخيم النسخة بالمقدار المحدد. يظل المستطيل الأصلي غير معدل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | الـ [RectangleF](../../com.aspose.drawing/rectanglef) الذي سيُنسخ. هذا المستطيل غير معدل. |
| x | float | المقدار لتضخيم نسخة المستطيل أفقياً. |
| y | float | المقدار لتوسيع نسخة المستطيل عموديًا. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The inflated [RectangleF](../../com.aspose.drawing/rectanglef).
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


يعيد بنية [RectangleF](../../com.aspose.drawing/rectanglef) تمثل تقاطع مستطيلين. إذا لم يكن هناك تقاطع، يتم إرجاع [RectangleF](../../com.aspose.drawing/rectanglef) فارغ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | المستطيل الأول للتقاطع. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | المستطيل الثاني للتقاطع. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


ينشئ أصغر مستطيل ثالث ممكن يمكنه احتواء المستطيلين الذين يشكلان اتحادًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | المستطيل الأول للاتحاد. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | المستطيل الثاني للاتحاد. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure that contains both of the two rectangles that form the union.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


يحصل على قيمة تشير إلى ما إذا كانت الخاصية `RectangleF.Width` أو `RectangleF.Height` لهذا [RectangleF](../../aspose.drawing/rectanglef) تساوي الصفر.

**Returns:**
منطقي - تُعيد هذه الخاصية true إذا كانت خاصية `RectangleF.Width` أو `P:RectangleF.Height` لهذا [RectangleF](../../com.aspose.drawing/rectanglef) تساوي صفرًا؛ وإلا false.
### getX() {#getX--}
```
public final float getX()
```


يحصل على إحداثي x للزاوية العليا اليسرى لهذه البنية RectangleF.

**Returns:**
عائم - إحداثي x للزاوية العليا اليسرى لهذه بنية RectangleF.
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


يضبط إحداثي x للزاوية العليا اليسرى لهذه البنية RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | إحداثي x للزاوية العليا اليسرى لهذه بنية RectangleF. |

### getY() {#getY--}
```
public final float getY()
```


يحصل على إحداثي x للزاوية العليا اليسرى لهذه البنية RectangleF.

**Returns:**
عائم - إحداثي x للزاوية العليا اليسرى لهذه بنية RectangleF.
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


يضبط إحداثي x للزاوية العليا اليسرى لهذه البنية RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | إحداثي x للزاوية العليا اليسرى لهذه بنية RectangleF. |

### getLocation() {#getLocation--}
```
public final PointF getLocation()
```


يحصل على إحداثيات الزاوية العليا اليسرى لهذه البنية [RectangleF](../../com.aspose.drawing/rectanglef).

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - A [PointF](../../com.aspose.drawing/pointf) that represents the upper-left corner of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setLocation(PointF value) {#setLocation-com.aspose.drawing.PointF-}
```
public final void setLocation(PointF value)
```


يضبط إحداثيات الزاوية العلوية اليسرى لهذا الهيكل [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | إحداثيات الزاوية العليا اليسرى لهذه بنية [RectangleF](../../com.aspose.drawing/rectanglef). |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


يحصل على عرض هذا الهيكل RectangleF.

**Returns:**
عائم - عرض هذه بنية RectangleF.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


يضبط عرض هذا الهيكل RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | عرض هذه بنية RectangleF. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


يحصل على ارتفاع هذا الهيكل RectangleF.

**Returns:**
عائم - ارتفاع هذه بنية RectangleF.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


يضبط ارتفاع هذا الهيكل RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | ارتفاع هذه بنية RectangleF. |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


يحصل على حجم هذا [RectangleF](../../com.aspose.drawing/rectanglef).

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that represents the width and height of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setSize(SizeF value) {#setSize-com.aspose.drawing.SizeF-}
```
public final void setSize(SizeF value)
```


يضبط حجم هذا [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | حجم هذه [RectangleF](../../com.aspose.drawing/rectanglef). |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


يحصل على إحداثي x للحافة اليسرى لهذا الهيكل RectangleF.

**Returns:**
عائم - إحداثي x للحافة اليسرى لهذه بنية RectangleF.
### getTop() {#getTop--}
```
public final float getTop()
```


يحصل على إحداثي y للحافة العلوية لهذا الهيكل RectangleF.

**Returns:**
عائم - إحداثي y للحافة العليا لهذه بنية RectangleF.
### getRight() {#getRight--}
```
public final float getRight()
```


يحصل على إحداثي x الذي هو مجموع X والعرض لهذا الهيكل RectangleF.

**Returns:**
عائم - إحداثي x الذي هو مجموع X وعرض هذه بنية RectangleF.
### getBottom() {#getBottom--}
```
public final float getBottom()
```


يحصل على إحداثي y الذي هو مجموع Y والارتفاع لهذا الهيكل RectangleF.

**Returns:**
عائم - إحداثي y الذي هو مجموع Y وارتفاع هذه بنية RectangleF.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### inflate(float x, float y) {#inflate-float-float-}
```
public final void inflate(float x, float y)
```


يوسع هذا [RectangleF](../../com.aspose.drawing/rectanglef) بالكمية المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | المقدار لتوسيع هذه بنية [RectangleF](../../com.aspose.drawing/rectanglef) أفقياً. |
| y | float | المقدار لتوسيع هذه بنية [RectangleF](../../com.aspose.drawing/rectanglef) عموديًا. |

### inflate(SizeF size) {#inflate-com.aspose.drawing.SizeF-}
```
public final void inflate(SizeF size)
```


يوسع هذا [RectangleF](../../com.aspose.drawing/rectanglef) بالكمية المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | المقدار لتوسيع هذا المستطيل. |

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public final void intersect(RectangleF rect)
```


يستبدل هذا [RectangleF](../../com.aspose.drawing/rectanglef) بالتقاطع بينه وبين الهيكل [RectangleF](../../com.aspose.drawing/rectanglef) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | المستطيل للتقاطع. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.drawing.RectangleF-}
```
public final boolean intersectsWith(RectangleF rect)
```


يحدد ما إذا كان هذا المستطيل يتقاطع مع `rect`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | المستطيل للاختبار. |

**Returns:**
منطقي - تُعيد هذه الطريقة true إذا كان هناك أي تقاطع.
### offset(PointF pos) {#offset-com.aspose.drawing.PointF-}
```
public final void offset(PointF pos)
```


يضبط موقع هذا المستطيل بالكمية المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.drawing/pointf) | المقدار لإزاحة الموقع. |

### offset(float x, float y) {#offset-float-float-}
```
public final void offset(float x, float y)
```


يضبط موقع هذا المستطيل بالكمية المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | المقدار لإزاحة الموقع أفقياً. |
| y | float | المقدار لإزاحة الموقع عمودياً. |

### contains(float x, float y) {#contains-float-float-}
```
public final boolean contains(float x, float y)
```


يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني للنقطة لاختبارها. |
| y | float | الإحداثي الصادي للنقطة لاختبارها. |

**Returns:**
منطقي - تُرجع هذه الطريقة `true` إذا كانت النقطة المحددة بـ x و y موجودة داخل بنية [RectangleF](../../com.aspose.drawing/rectanglef) هذه؛ وإلا `false`.
### contains(PointF pt) {#contains-com.aspose.drawing.PointF-}
```
public final boolean contains(PointF pt)
```


يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | الـ[PointF](../../com.aspose.drawing/pointf) لاختبارها. |

**Returns:**
منطقي - تُرجع هذه الطريقة `true` إذا كانت النقطة الممثلة بالمعامل pt موجودة داخل بنية [RectangleF](../../com.aspose.drawing/rectanglef) هذه؛ وإلا `false`.
### contains(RectangleF rect) {#contains-com.aspose.drawing.RectangleF-}
```
public final boolean contains(RectangleF rect)
```


يحدد ما إذا كانت المنطقة المستطيلة الممثلة بـ `rect` موجودة بالكامل داخل هذا [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | الـ[RectangleF](../../com.aspose.drawing/rectanglef) لاختبارها. |

**Returns:**
منطقي - تُرجع هذه الطريقة `true` إذا كانت المنطقة المستطيلة الممثلة بـ `rect` موجودة بالكامل داخل المنطقة المستطيلة الممثلة بهذه الـ[RectangleF](../../com.aspose.drawing/rectanglef)؛ وإلا `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الكائن المحدد يساوي هذه الحالة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة مع هذه الحالة. |

**Returns:**
منطقي - `true` إذا كان الكائن المحدد يساوي هذه الحالة؛ وإلا `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز تجزئة لهذه الحالة.

**Returns:**
عدد صحيح - رمز تجزئة (hash code) لهذه الحالة، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
### equals(RectangleF other) {#equals-com.aspose.drawing.RectangleF-}
```
public final boolean equals(RectangleF other)
```


يفحص ما إذا كان الهيكل [RectangleF](../../com.aspose.drawing/rectanglef) الآخر له نفس الموقع والحجم لهذا الهيكل [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [RectangleF](../../com.aspose.drawing/rectanglef) | المستطيل الآخر لاختباره |

**Returns:**
منطقي - تُرجع هذه الطريقة `true` إذا كانت بنية [RectangleF](../../com.aspose.drawing/rectanglef) الأخرى وخصائص X و Y و Width و Height الخاصة بها مساوية للخصائص المقابلة في بنية [RectangleF](../../com.aspose.drawing/rectanglef) هذه؛ وإلا `false`.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.drawing.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
