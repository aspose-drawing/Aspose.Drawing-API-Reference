---
title: RectangleF
second_title: Aspose.Drawing for Java API 参考
description: 存储一组四个浮点数，表示矩形的位置和大小。
type: docs
weight: 39
url: /zh/java/com.aspose.drawing/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class RectangleF extends Struct<RectangleF> implements System.IEquatable<RectangleF>, Cloneable
```

存储一组四个浮点数，表示矩形的位置和大小。对于更高级的区域功能，请使用 Region 对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | 使用指定的位置和大小初始化 RectangleF 结构的新实例。 |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | 使用指定的位置和大小初始化 RectangleF 结构的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | 从两个点创建一个新矩形。 |
| [to_RectangleF(Rectangle r)](#to-RectangleF-com.aspose.drawing.Rectangle-) | 将指定的 Rectangle 结构转换为 RectangleF 结构。 |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | 测试两个 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的位置和大小是否相等。 |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | 测试两个 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的位置或大小是否不同。 |
| [fromLTRB(float left, float top, float right, float bottom)](#fromLTRB-float-float-float-float-) | 使用指定的位置创建一个左上角和右下角位于指定位置的 RectangleF 结构。 |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.drawing.RectangleF-float-float-) | 创建并返回指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的膨胀副本。 |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | 返回一个表示两个矩形交集的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | 创建能够容纳两个矩形并形成并集的最小可能的第三个矩形。 |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 [RectangleF](../../com.aspose.drawing/rectanglef) 的 `RectangleF.Width` 或 `RectangleF.Height` 属性是否为零。 |
| [getX()](#getX--) | 获取此 RectangleF 结构左上角的 x 坐标。 |
| [setX(float value)](#setX-float-) | 设置此 RectangleF 结构左上角的 x 坐标。 |
| [getY()](#getY--) | 获取此 RectangleF 结构左上角的 x 坐标。 |
| [setY(float value)](#setY-float-) | 设置此 RectangleF 结构左上角的 x 坐标。 |
| [getLocation()](#getLocation--) | 获取此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构左上角的坐标。 |
| [setLocation(PointF value)](#setLocation-com.aspose.drawing.PointF-) | 设置此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的左上角坐标。 |
| [getWidth()](#getWidth--) | 获取此 RectangleF 结构的宽度。 |
| [setWidth(float value)](#setWidth-float-) | 设置此 RectangleF 结构的宽度。 |
| [getHeight()](#getHeight--) | 获取此 RectangleF 结构的高度。 |
| [setHeight(float value)](#setHeight-float-) | 设置此 RectangleF 结构的高度。 |
| [getSize()](#getSize--) | 获取此 [RectangleF](../../com.aspose.drawing/rectanglef) 的大小。 |
| [setSize(SizeF value)](#setSize-com.aspose.drawing.SizeF-) | 设置此 [RectangleF](../../com.aspose.drawing/rectanglef) 的大小。 |
| [getLeft()](#getLeft--) | 获取此 RectangleF 结构左边缘的 x 坐标。 |
| [getTop()](#getTop--) | 获取此 RectangleF 结构上边缘的 y 坐标。 |
| [getRight()](#getRight--) | 获取此 RectangleF 结构的 X 与 Width 相加后的 x 坐标。 |
| [getBottom()](#getBottom--) | 获取此 RectangleF 结构的 Y 与 Height 相加后的 y 坐标。 |
| [toString()](#toString--) |  |
| [inflate(float x, float y)](#inflate-float-float-) | 按指定量膨胀此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |
| [inflate(SizeF size)](#inflate-com.aspose.drawing.SizeF-) | 按指定量膨胀此 [RectangleF](../../com.aspose.drawing/rectanglef)。 |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | 用自身与指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的交集替换此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.drawing.RectangleF-) | 确定此矩形是否与 `rect` 相交。 |
| [offset(PointF pos)](#offset-com.aspose.drawing.PointF-) | 按指定量调整此矩形的位置。 |
| [offset(float x, float y)](#offset-float-float-) | 按指定量调整此矩形的位置。 |
| [contains(float x, float y)](#contains-float-float-) | 确定指定的点是否包含在此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构中。 |
| [contains(PointF pt)](#contains-com.aspose.drawing.PointF-) | 确定指定的点是否包含在此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构中。 |
| [contains(RectangleF rect)](#contains-com.aspose.drawing.RectangleF-) | 确定由 `rect` 表示的矩形区域是否完全包含在此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构中。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的对象是否等于此实例。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [equals(RectangleF other)](#equals-com.aspose.drawing.RectangleF-) | 测试另一个 [RectangleF](../../com.aspose.drawing/rectanglef) 结构是否具有与此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构相同的位置和大小。 |
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


使用指定的位置和大小初始化 RectangleF 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| location | [PointF](../../com.aspose.drawing/pointf) | 表示矩形区域左上角的 PointF。 |
| size | [SizeF](../../com.aspose.drawing/sizef) | 表示矩形区域宽度和高度的 SizeF。 |

### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


使用指定的位置和大小初始化 RectangleF 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | 浮点数 | 矩形左上角的 x 坐标。 |
| y | 浮点数 | 矩形左上角的 y 坐标。 |
| 宽度 | 浮点数 | 矩形的宽度。 |
| 高度 | 浮点数 | 矩形的高度。 |

### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


从两个点创建一个新矩形。创建的矩形将被标准化，使 (left,top) 小于 (right,bottom)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | 第一个点。 |
| point2 | [PointF](../../com.aspose.drawing/pointf) | 第二个点。 |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A newly created rectangle.
### to_RectangleF(Rectangle r) {#to-RectangleF-com.aspose.drawing.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle r)
```


将指定的 Rectangle 结构转换为 RectangleF 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| r | [Rectangle](../../com.aspose.drawing/rectangle) | 要转换的 Rectangle 结构。 |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The RectangleF structure that is converted from the specified Rectangle structure.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


测试两个 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的位置和大小是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | 等于运算符左侧的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | 等于运算符右侧的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |

**Returns:**
boolean - 如果两个指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的 `RectangleF.X`、`RectangleF.Y`、`RectangleF.Width` 和 `RectangleF.Height` 属性相等，则此运算符返回 true。
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


测试两个 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的位置或大小是否不同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | 不等于运算符左侧的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | 不等于运算符右侧的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |

**Returns:**
boolean - 如果两个 [Rectangle](../../com.aspose.drawing/rectangle) 结构的 `RectangleF.X`、`RectangleF.Y`、`RectangleF.Width` 或 `RectangleF.Height` 属性中任意一个不相等，则此运算符返回 true；否则返回 false。
### fromLTRB(float left, float top, float right, float bottom) {#fromLTRB-float-float-float-float-}
```
public static RectangleF fromLTRB(float left, float top, float right, float bottom)
```


使用指定的位置创建一个左上角和右下角位于指定位置的 RectangleF 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 左 | 浮点数 | 矩形区域左上角的 x 坐标。 |
| 上 | 浮点数 | 矩形区域左上角的 y 坐标。 |
| 右 | 浮点数 | 矩形区域右下角的 x 坐标。 |
| 下 | 浮点数 | 矩形区域右下角的 y 坐标。 |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The new RectangleF that this method creates.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.drawing.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


创建并返回指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的膨胀副本。该副本按指定的量进行膨胀。原始矩形保持不变。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 要复制的 [RectangleF](../../com.aspose.drawing/rectanglef)。此矩形未被修改。 |
| x | 浮点数 | 水平膨胀矩形副本的量。 |
| y | 浮点数 | 垂直膨胀矩形副本的量。 |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The inflated [RectangleF](../../com.aspose.drawing/rectanglef).
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


返回一个表示两个矩形交集的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。如果没有交集，则返回一个空的 [RectangleF](../../com.aspose.drawing/rectanglef)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | 第一个要相交的矩形。 |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | 第二个要相交的矩形。 |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


创建能够容纳两个矩形并形成并集的最小可能的第三个矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | 第一个要合并的矩形。 |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | 第二个要合并的矩形。 |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure that contains both of the two rectangles that form the union.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

**Returns:**
布尔型
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


获取一个值，指示此 [RectangleF](../../com.aspose.drawing/rectanglef) 的 `RectangleF.Width` 或 `RectangleF.Height` 属性是否为零。

**Returns:**
boolean - 如果此 [RectangleF](../../com.aspose.drawing/rectanglef) 的 `RectangleF.Width` 或 `P:RectangleF.Height` 属性的值为零，则此属性返回 true；否则返回 false。
### getX() {#getX--}
```
public final float getX()
```


获取此 RectangleF 结构左上角的 x 坐标。

**Returns:**
float - 此 RectangleF 结构左上角的 x 坐标。
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


设置此 RectangleF 结构左上角的 x 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 浮点数 | 此 RectangleF 结构左上角的 x 坐标。 |

### getY() {#getY--}
```
public final float getY()
```


获取此 RectangleF 结构左上角的 x 坐标。

**Returns:**
float - 此 RectangleF 结构左上角的 x 坐标。
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


设置此 RectangleF 结构左上角的 x 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 浮点数 | 此 RectangleF 结构左上角的 x 坐标。 |

### getLocation() {#getLocation--}
```
public final PointF getLocation()
```


获取此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构左上角的坐标。

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - A [PointF](../../com.aspose.drawing/pointf) that represents the upper-left corner of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setLocation(PointF value) {#setLocation-com.aspose.drawing.PointF-}
```
public final void setLocation(PointF value)
```


设置此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的左上角坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | 此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构左上角的坐标。 |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


获取此 RectangleF 结构的宽度。

**Returns:**
float - 此 RectangleF 结构的宽度。
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


设置此 RectangleF 结构的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 浮点数 | 此 RectangleF 结构的宽度。 |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


获取此 RectangleF 结构的高度。

**Returns:**
float - 此 RectangleF 结构的高度。
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


设置此 RectangleF 结构的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 浮点数 | 此 RectangleF 结构的高度。 |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


获取此 [RectangleF](../../com.aspose.drawing/rectanglef) 的大小。

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that represents the width and height of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setSize(SizeF value) {#setSize-com.aspose.drawing.SizeF-}
```
public final void setSize(SizeF value)
```


设置此 [RectangleF](../../com.aspose.drawing/rectanglef) 的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | 此 [RectangleF](../../com.aspose.drawing/rectanglef) 的大小。 |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


获取此 RectangleF 结构左边缘的 x 坐标。

**Returns:**
float - 此 RectangleF 结构左边缘的 x 坐标。
### getTop() {#getTop--}
```
public final float getTop()
```


获取此 RectangleF 结构上边缘的 y 坐标。

**Returns:**
float - 此 RectangleF 结构上边缘的 y 坐标。
### getRight() {#getRight--}
```
public final float getRight()
```


获取此 RectangleF 结构的 X 与 Width 相加后的 x 坐标。

**Returns:**
float - 此 RectangleF 结构的 X 与 Width 相加得到的 x 坐标。
### getBottom() {#getBottom--}
```
public final float getBottom()
```


获取此 RectangleF 结构的 Y 与 Height 相加后的 y 坐标。

**Returns:**
float - 此 RectangleF 结构的 Y 与 Height 相加得到的 y 坐标。
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


按指定量膨胀此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 水平膨胀此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的量。 |
| y | float | 垂直膨胀此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的量。 |

### inflate(SizeF size) {#inflate-com.aspose.drawing.SizeF-}
```
public final void inflate(SizeF size)
```


按指定量膨胀此 [RectangleF](../../com.aspose.drawing/rectanglef)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | 膨胀此矩形的量。 |

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public final void intersect(RectangleF rect)
```


用自身与指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的交集替换此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 要相交的矩形。 |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.drawing.RectangleF-}
```
public final boolean intersectsWith(RectangleF rect)
```


确定此矩形是否与 `rect` 相交。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 要测试的矩形。 |

**Returns:**
boolean - 如果存在任何交集，此方法返回 true。
### offset(PointF pos) {#offset-com.aspose.drawing.PointF-}
```
public final void offset(PointF pos)
```


按指定量调整此矩形的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.drawing/pointf) | 用于偏移位置的量。 |

### offset(float x, float y) {#offset-float-float-}
```
public final void offset(float x, float y)
```


按指定量调整此矩形的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | 浮点数 | 用于水平偏移位置的量。 |
| y | 浮点数 | 用于垂直偏移位置的量。 |

### contains(float x, float y) {#contains-float-float-}
```
public final boolean contains(float x, float y)
```


确定指定的点是否包含在此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | 浮点数 | 要测试的点的 x 坐标。 |
| y | 浮点数 | 要测试的点的 y 坐标。 |

**Returns:**
boolean - 如果由 x 和 y 定义的点位于此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构中，则此方法返回 `true`；否则返回 `false`。
### contains(PointF pt) {#contains-com.aspose.drawing.PointF-}
```
public final boolean contains(PointF pt)
```


确定指定的点是否包含在此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | 要测试的 [PointF](../../com.aspose.drawing/pointf)。 |

**Returns:**
boolean - 如果由 pt 参数表示的点位于此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构中，则此方法返回 `true`；否则返回 `false`。
### contains(RectangleF rect) {#contains-com.aspose.drawing.RectangleF-}
```
public final boolean contains(RectangleF rect)
```


确定由 `rect` 表示的矩形区域是否完全包含在此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 要测试的 [RectangleF](../../com.aspose.drawing/rectanglef)。 |

**Returns:**
boolean - 如果由 `rect` 表示的矩形区域完全包含在此 [RectangleF](../../com.aspose.drawing/rectanglef) 表示的矩形区域中，则此方法返回 `true`；否则返回 `false`。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的对象是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 Object。 |

**Returns:**
boolean - 如果指定的 Object 等于此实例，则为 `true`；否则为 `false`。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
### equals(RectangleF other) {#equals-com.aspose.drawing.RectangleF-}
```
public final boolean equals(RectangleF other)
```


测试另一个 [RectangleF](../../com.aspose.drawing/rectanglef) 结构是否具有与此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构相同的位置和大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [RectangleF](../../com.aspose.drawing/rectanglef) | 要测试的其他矩形 |

**Returns:**
boolean - 如果其他 [RectangleF](../../com.aspose.drawing/rectanglef) 结构及其 X、Y、Width 和 Height 属性等于此 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的相应属性，则此方法返回 `true`；否则返回 `false`。
### CloneTo(RectangleF that) {#CloneTo-com.aspose.drawing.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
