---
title: مستطيل
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم المستطيل.
type: docs
weight: 38
url: /ar/java/com.aspose.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Rectangle extends Struct<Rectangle> implements System.IEquatable<Rectangle>, Cloneable
```

يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم المستطيل.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | يُنشئ مثيلًا جديدًا لبنية Rectangle بالموقع والحجم المحددين. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-) | يُنشئ مثيلًا جديدًا للـ [Rectangle](../../com.aspose.drawing/rectangle) بالموضع والحجم المحددين. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [fromLTRB(int left, int top, int right, int bottom)](#fromLTRB-int-int-int-int-) | ينشئ بنية [Rectangle](../../com.aspose.drawing/rectangle) بالمواقع المحددة للحواف. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | يعيد بنية [Rectangle](../../com.aspose.drawing/rectangle) ثالثة تمثل تقاطع بنيتين [Rectangle](../../com.aspose.drawing/rectangle) أخريين. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | يفحص ما إذا كانت بنيتان [Rectangle](../../com.aspose.drawing/rectangle) لهما نفس الموقع والحجم. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | يفحص ما إذا كانت بنيتان [Rectangle](../../com.aspose.drawing/rectangle) تختلفان في الموقع أو الحجم. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.drawing.RectangleF-) | يحوّل بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة إلى بنية [Rectangle](../../com.aspose.drawing/rectangle) عن طريق تقريب قيم [RectangleF](../../com.aspose.drawing/rectanglef) إلى أعلى قيمة صحيحة. |
| [truncate(RectangleF value)](#truncate-com.aspose.drawing.RectangleF-) | يحوّل [RectangleF](../../com.aspose.drawing/rectanglef) المحدد إلى [Rectangle](../../com.aspose.drawing/rectangle) عن طريق قطع قيم [RectangleF](../../com.aspose.drawing/rectanglef). |
| [round(RectangleF value)](#round-com.aspose.drawing.RectangleF-) | يحوّل [RectangleF](../../com.aspose.drawing/rectanglef) المحدد إلى [Rectangle](../../com.aspose.drawing/rectangle) عن طريق تقريب قيم [RectangleF](../../com.aspose.drawing/rectanglef) إلى أقرب قيمة صحيحة. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | يحصل على بنية [Rectangle](../../com.aspose.drawing/rectangle) التي تحتوي على اتحاد بنيتين [Rectangle](../../com.aspose.drawing/rectangle). |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.drawing.Rectangle-int-int-) |  |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) |  |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-) | ينشئ مستطيلًا جديدًا من نقطتين. |
| [getEmpty()](#getEmpty--) | يحصل على مثيل جديد لبنية `Rectangle` التي تكون قيم `Rectangle.X` و `Rectangle.Y` و `Rectangle.Width` و `Rectangle.Height` فيها صفرًا. |
| [getX()](#getX--) | يحصل على الإحداثي X للزاوية العليا اليسرى لهذه بنية Rectangle. |
| [setX(int value)](#setX-int-) | يضبط الإحداثي X للزاوية العليا اليسرى لهذه بنية Rectangle. |
| [getY()](#getY--) | يحصل على الإحداثي Y للزاوية العليا اليسرى لهذه بنية Rectangle. |
| [setY(int value)](#setY-int-) | يضبط الإحداثي Y للزاوية العليا اليسرى لهذه بنية Rectangle. |
| [getLocation()](#getLocation--) | يحصل على إحداثيات الزاوية العليا اليسرى لهذه بنية [Rectangle](../../com.aspose.drawing/rectangle). |
| [setLocation(Point value)](#setLocation-com.aspose.drawing.Point-) | يضبط إحداثيات الزاوية العليا اليسرى لهذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle). |
| [getWidth()](#getWidth--) | يحصل على عرض هذا الهيكل Rectangle. |
| [setWidth(int value)](#setWidth-int-) | يضبط عرض هذا الهيكل Rectangle. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع هذا الهيكل Rectangle. |
| [setHeight(int value)](#setHeight-int-) | يضبط ارتفاع هذا الهيكل Rectangle. |
| [getSize()](#getSize--) | يحصل على حجم هذا [Rectangle](../../com.aspose.drawing/rectangle). |
| [setSize(Size value)](#setSize-com.aspose.drawing.Size-) | يضبط حجم هذا [Rectangle](../../com.aspose.drawing/rectangle). |
| [getLeft()](#getLeft--) | يحصل على إحداثي x للحافة اليسرى لهذا الهيكل Rectangle. |
| [getTop()](#getTop--) | يحصل على إحداثي y للحافة العليا لهذا الهيكل Rectangle. |
| [getRight()](#getRight--) | يحصل على إحداثي x الذي هو مجموع قيم الخاصيتين X و Width لهذا الهيكل Rectangle. |
| [getBottom()](#getBottom--) | يحصل على إحداثي y الذي هو مجموع قيم الخاصيتين Y و Height لهذا الهيكل Rectangle. |
| [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كانت جميع الخصائص الرقمية لهذا [Rectangle](../../com.aspose.drawing/rectangle) لها قيم صفر. |
| [equals(Object obj)](#equals-java.lang.Object-) | يفحص ما إذا كان obj هو هيكل [Rectangle](../../com.aspose.drawing/rectangle) بنفس الموقع والحجم لهذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle). |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle). |
| [toString()](#toString--) |  |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | يستبدل هذا [Rectangle](../../com.aspose.drawing/rectangle) بالتقاطع بينه وبين [Rectangle](../../com.aspose.drawing/rectangle) المحدد. |
| [inflate(int width, int height)](#inflate-int-int-) | يوسع هذا [Rectangle](../../com.aspose.drawing/rectangle) بالمقدار المحدد. |
| [inflate(Size size)](#inflate-com.aspose.drawing.Size-) | يوسع هذا [Rectangle](../../com.aspose.drawing/rectangle) بالمقدار المحدد. |
| [contains(int x, int y)](#contains-int-int-) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle). |
| [contains(Point pt)](#contains-com.aspose.drawing.Point-) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle). |
| [contains(Rectangle rect)](#contains-com.aspose.drawing.Rectangle-) |  |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.drawing.Rectangle-) | يحدد ما إذا كان هذا المستطيل يتقاطع مع `rect`. |
| [offset(int x, int y)](#offset-int-int-) | يضبط موقع هذا المستطيل بالكمية المحددة. |
| [offset(Point pos)](#offset-com.aspose.drawing.Point-) | يضبط موقع هذا المستطيل بالكمية المحددة. |
| [equals(Rectangle other)](#equals-com.aspose.drawing.Rectangle-) | يفحص ما إذا كان هيكل [Rectangle](../../com.aspose.drawing/rectangle) الآخر له نفس الموقع والحجم لهذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle). |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.drawing.Rectangle-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [normalize()](#normalize--) | يُعَدِّل المستطيل بجعل عرضه وارتفاعه إيجابيين، واليسار أصغر من اليمين، والعليا أصغر من السفلى. |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


يُنشئ مثيلًا جديدًا لبنية Rectangle بالموقع والحجم المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | إحداثي x للزاوية العلوية اليسرى للمستطيل. |
| y | int | إحداثي y للزاوية العلوية اليسرى للمستطيل. |
| العرض | int | عرض المستطيل. |
| الارتفاع | int | ارتفاع المستطيل. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public Rectangle(Point location, Size size)
```


يُنشئ مثيلًا جديدًا للـ [Rectangle](../../com.aspose.drawing/rectangle) بالموضع والحجم المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| location | [Point](../../com.aspose.drawing/point) | [Point](../../com.aspose.drawing/point) يمثل الزاوية العليا اليسرى للمنطقة المستطيلة. |
| size | [Size](../../com.aspose.drawing/size) | `Size`([.getSize](../../null/\#getSize)/[.setSize(Size)](../../null/\#setSize-Size-)) يمثل عرض وارتفاع المنطقة المستطيلة. |

### fromLTRB(int left, int top, int right, int bottom) {#fromLTRB-int-int-int-int-}
```
public static Rectangle fromLTRB(int left, int top, int right, int bottom)
```


ينشئ بنية [Rectangle](../../com.aspose.drawing/rectangle) بالمواقع المحددة للحواف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | int | إحداثي x للزاوية العليا اليسرى لهذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle). |
| top | int | إحداثي y للزاوية العليا اليسرى لهذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle). |
| right | int | إحداثي x للزاوية السفلى اليمنى لهذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle). |
| bottom | int | إحداثي y للزاوية السفلى اليمنى لهذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle). |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The new [Rectangle](../../com.aspose.drawing/rectangle) that this method creates.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


إرجاع هيكل [Rectangle](../../com.aspose.drawing/rectangle) ثالث يمثل تقاطع هيكلي [Rectangle](../../com.aspose.drawing/rectangle) آخرين. إذا لم يكن هناك تقاطع، يتم إرجاع [Rectangle](../../com.aspose.drawing/rectangle) فارغ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | المستطيل الأول للتقاطع. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | المستطيل الثاني للتقاطع. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the intersection of `a` and `b`.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


يفحص ما إذا كانت بنيتان [Rectangle](../../com.aspose.drawing/rectangle) لهما نفس الموقع والحجم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | الـ [Rectangle](../../com.aspose.drawing/rectangle) هو الهيكل الموجود إلى يسار عامل المساواة. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | الـ [Rectangle](../../com.aspose.drawing/rectangle) هو الهيكل الموجود إلى يمين عامل المساواة. |

**Returns:**
منطقي - يرجع هذا العامل `true` إذا كان الهيكلان [Rectangle](../../com.aspose.drawing/rectangle) يمتلكان خصائص X و Y و Width و Height متساوية.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


يفحص ما إذا كانت بنيتان [Rectangle](../../com.aspose.drawing/rectangle) تختلفان في الموقع أو الحجم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | الـ [Rectangle](../../com.aspose.drawing/rectangle) هو الهيكل الموجود إلى يسار عامل عدم المساواة. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | الـ [Rectangle](../../com.aspose.drawing/rectangle) هو الهيكل الموجود إلى يمين عامل عدم المساواة. |

**Returns:**
منطقي - يرجع هذا العامل `true` إذا كان أي من خصائص X أو Y أو Width أو Height للهيكلين [Rectangle](../../com.aspose.drawing/rectangle) غير متساوية؛ وإلا `false`.
### ceiling(RectangleF value) {#ceiling-com.aspose.drawing.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


يحوّل بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة إلى بنية [Rectangle](../../com.aspose.drawing/rectangle) عن طريق تقريب قيم [RectangleF](../../com.aspose.drawing/rectanglef) إلى أعلى قيمة صحيحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | الـ [RectangleF](../../com.aspose.drawing/rectanglef) هو الهيكل الذي سيُحوَّل. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - Returns a [Rectangle](../../com.aspose.drawing/rectangle).
### truncate(RectangleF value) {#truncate-com.aspose.drawing.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


يحوّل [RectangleF](../../com.aspose.drawing/rectanglef) المحدد إلى [Rectangle](../../com.aspose.drawing/rectangle) عن طريق قطع قيم [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | الـ [RectangleF](../../com.aspose.drawing/rectanglef) الذي سيُحوَّل. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The truncated value of the [Rectangle](../../com.aspose.drawing/rectangle).
### round(RectangleF value) {#round-com.aspose.drawing.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


يحوّل [RectangleF](../../com.aspose.drawing/rectanglef) المحدد إلى [Rectangle](../../com.aspose.drawing/rectangle) عن طريق تقريب قيم [RectangleF](../../com.aspose.drawing/rectanglef) إلى أقرب قيمة صحيحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | الـ [RectangleF](../../com.aspose.drawing/rectanglef) الذي سيُحوَّل. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle).
### union(Rectangle a, Rectangle b) {#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


يحصل على بنية [Rectangle](../../com.aspose.drawing/rectangle) التي تحتوي على اتحاد بنيتين [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | مستطيل أول للدمج. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | مستطيل ثانٍ للدمج. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) structure that bounds the union of the two [Rectangle](../../com.aspose.drawing/rectangle) structures.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.drawing.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| x | int |  |
| y | int |  |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


ينشئ مستطيلًا جديدًا من نقطتين. سيتم تطبيع المستطيل المُنشأ بحيث يكون (left,top) أقل من (right,bottom).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | النقطة الأولى. |
| point2 | [Point](../../com.aspose.drawing/point) | النقطة الثانية. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A newly created rectangle.
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


يحصل على مثيل جديد لبنية `Rectangle` التي تكون قيم `Rectangle.X` و `Rectangle.Y` و `Rectangle.Width` و `Rectangle.Height` فيها صفرًا.

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### getX() {#getX--}
```
public final int getX()
```


يحصل على الإحداثي X للزاوية العليا اليسرى لهذه بنية Rectangle.

**Returns:**
int - إحداثي x للزاوية العليا اليسرى لهذا الهيكل Rectangle.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


يضبط الإحداثي X للزاوية العليا اليسرى لهذه بنية Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | إحداثي x للزاوية العليا اليسرى لهذا الهيكل Rectangle. |

### getY() {#getY--}
```
public final int getY()
```


يحصل على الإحداثي Y للزاوية العليا اليسرى لهذه بنية Rectangle.

**Returns:**
int - إحداثي y للزاوية العليا اليسرى لهذا الهيكل Rectangle.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


يضبط الإحداثي Y للزاوية العليا اليسرى لهذه بنية Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | إحداثي y للزاوية العليا اليسرى لهذا الهيكل Rectangle. |

### getLocation() {#getLocation--}
```
public final Point getLocation()
```


يحصل على إحداثيات الزاوية العليا اليسرى لهذه بنية [Rectangle](../../com.aspose.drawing/rectangle).

**Returns:**
[Point](../../com.aspose.drawing/point) - the coordinates of the upper-left corner of this [Rectangle](../../com.aspose.drawing/rectangle) structure.
### setLocation(Point value) {#setLocation-com.aspose.drawing.Point-}
```
public final void setLocation(Point value)
```


يضبط إحداثيات الزاوية العليا اليسرى لهذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.drawing/point) | إحداثيات الزاوية العليا اليسرى لهذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle). |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل على عرض هذا الهيكل Rectangle.

**Returns:**
int - عرض هذا الهيكل Rectangle.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


يضبط عرض هذا الهيكل Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | عرض هذا الهيكل Rectangle. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل على ارتفاع هذا الهيكل Rectangle.

**Returns:**
int - ارتفاع هذا الهيكل Rectangle.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


يضبط ارتفاع هذا الهيكل Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | ارتفاع هذا الهيكل Rectangle. |

### getSize() {#getSize--}
```
public final Size getSize()
```


يحصل على حجم هذا [Rectangle](../../com.aspose.drawing/rectangle).

**Returns:**
[Size](../../com.aspose.drawing/size) - the size of this [Rectangle](../../com.aspose.drawing/rectangle).
### setSize(Size value) {#setSize-com.aspose.drawing.Size-}
```
public final void setSize(Size value)
```


يضبط حجم هذا [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Size](../../com.aspose.drawing/size) | حجم هذا [Rectangle](../../com.aspose.drawing/rectangle). |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


يحصل على إحداثي x للحافة اليسرى لهذا الهيكل Rectangle.

**Returns:**
int - إحداثي x للحافة اليسرى لهذا الهيكل Rectangle.
### getTop() {#getTop--}
```
public final int getTop()
```


يحصل على إحداثي y للحافة العليا لهذا الهيكل Rectangle.

**Returns:**
int - إحداثي y للحافة العليا لهذا الهيكل Rectangle.
### getRight() {#getRight--}
```
public final int getRight()
```


يحصل على إحداثي x الذي هو مجموع قيم الخاصيتين X و Width لهذا الهيكل Rectangle.

**Returns:**
int - إحداثي x الذي هو مجموع قيم خصائص X و Width لهذا الهيكل Rectangle.
### getBottom() {#getBottom--}
```
public final int getBottom()
```


يحصل على إحداثي y الذي هو مجموع قيم الخاصيتين Y و Height لهذا الهيكل Rectangle.

**Returns:**
int - إحداثي y الذي هو مجموع قيم خصائص Y و Height لهذا الهيكل Rectangle.
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


يحصل على قيمة تشير إلى ما إذا كانت جميع الخصائص الرقمية لهذا [Rectangle](../../com.aspose.drawing/rectangle) لها قيم صفر.

**Returns:**
منطقي - تُعيد هذه الخاصية `true` إذا كانت خصائص `Rectangle.Width` و `Rectangle.Height` و `Rectangle.X` و `Rectangle.Y` لهذا [Rectangle](../../com.aspose.drawing/rectangle) جميعها تساوي الصفر؛ وإلا `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يفحص ما إذا كان obj هو هيكل [Rectangle](../../com.aspose.drawing/rectangle) بنفس الموقع والحجم لهذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للاختبار. |

**Returns:**
منطقي - تُعيد هذه الطريقة `true` إذا كان obj بنية [Rectangle](../../com.aspose.drawing/rectangle) وكانت خصائص X و Y و Width و Height الخاصة به مساوية للخصائص المقابلة لهذه البنية [Rectangle](../../com.aspose.drawing/rectangle)؛ وإلا `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


تُعيد قيمة التجزئة (hash code) لهذه البنية [Rectangle](../../com.aspose.drawing/rectangle). لمزيد من المعلومات حول استخدام قيم التجزئة، راجع GetHashCode.

**Returns:**
int - عدد صحيح يمثل قيمة التجزئة لهذا المستطيل.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public final void intersect(Rectangle rect)
```


يستبدل هذا [Rectangle](../../com.aspose.drawing/rectangle) بالتقاطع بينه وبين [Rectangle](../../com.aspose.drawing/rectangle) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | الـ [Rectangle](../../com.aspose.drawing/rectangle) الذي سيتم التقاطع معه. |

### inflate(int width, int height) {#inflate-int-int-}
```
public final void inflate(int width, int height)
```


يوسع هذا [Rectangle](../../com.aspose.drawing/rectangle) بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | القيمة لتوسيع هذا [Rectangle](../../com.aspose.drawing/rectangle) أفقياً. |
| height | int | القيمة لتوسيع هذا [Rectangle](../../com.aspose.drawing/rectangle) رأسياً. |

### inflate(Size size) {#inflate-com.aspose.drawing.Size-}
```
public final void inflate(Size size)
```


يوسع هذا [Rectangle](../../com.aspose.drawing/rectangle) بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | الحجم لتوسيع هذا [Rectangle](../../com.aspose.drawing/rectangle). |

### contains(int x, int y) {#contains-int-int-}
```
public final boolean contains(int x, int y)
```


يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي x للنقطة المراد اختبارها. |
| y | int | الإحداثي الصادي للنقطة لاختبارها. |

**Returns:**
منطقي - تُعيد هذه الطريقة `true` إذا كانت النقطة المحددة بـ `x` و `y` موجودة داخل بنية هذا [Rectangle](../../com.aspose.drawing/rectangle)؛ وإلا `false`.
### contains(Point pt) {#contains-com.aspose.drawing.Point-}
```
public final boolean contains(Point pt)
```


يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | الـ [Point](../../com.aspose.drawing/point) المراد اختباره. |

**Returns:**
منطقي - تُعيد هذه الطريقة `true` إذا كانت النقطة الممثلة بـ `pt` موجودة داخل بنية هذا [Rectangle](../../com.aspose.drawing/rectangle)؛ وإلا `false`.
### contains(Rectangle rect) {#contains-com.aspose.drawing.Rectangle-}
```
public final boolean contains(Rectangle rect)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.drawing.Rectangle-}
```
public final boolean intersectsWith(Rectangle rect)
```


يحدد ما إذا كان هذا المستطيل يتقاطع مع `rect`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | المستطيل للاختبار. |

**Returns:**
منطقي - تُعيد هذه الطريقة true إذا كان هناك أي تقاطع، وإلا false.
### offset(int x, int y) {#offset-int-int-}
```
public final void offset(int x, int y)
```


يضبط موقع هذا المستطيل بالكمية المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإزاحة الأفقية. |
| y | int | الإزاحة الرأسية. |

### offset(Point pos) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point pos)
```


يضبط موقع هذا المستطيل بالكمية المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pos | [Point](../../com.aspose.drawing/point) | الإزاحة. |

### equals(Rectangle other) {#equals-com.aspose.drawing.Rectangle-}
```
public final boolean equals(Rectangle other)
```


يفحص ما إذا كان هيكل [Rectangle](../../com.aspose.drawing/rectangle) الآخر له نفس الموقع والحجم لهذا الهيكل [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.drawing/rectangle) | المستطيل الآخر لاختباره |

**Returns:**
منطقي - تُعيد هذه الطريقة `true` إذا كانت بنية [Rectangle](../../com.aspose.drawing/rectangle) الأخرى وخصائص X و Y و Width و Height الخاصة بها مساوية للخصائص المقابلة لهذه البنية [Rectangle](../../com.aspose.drawing/rectangle)؛ وإلا `false`.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.drawing.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.drawing/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### normalize() {#normalize--}
```
public void normalize()
```


يُعَدِّل المستطيل بجعل عرضه وارتفاعه إيجابيين، واليسار أصغر من اليمين، والعليا أصغر من السفلى.

