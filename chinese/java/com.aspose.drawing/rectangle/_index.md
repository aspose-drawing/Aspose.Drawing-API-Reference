---
title: 矩形
second_title: Aspose.Drawing for Java API 参考
description: 存储一组四个整数，表示矩形的位置和大小。
type: docs
weight: 38
url: /zh/java/com.aspose.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Rectangle extends Struct<Rectangle> implements System.IEquatable<Rectangle>, Cloneable
```

存储一组四个整数，表示矩形的位置和大小。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | 使用指定的位置和大小初始化 Rectangle 结构的新实例。 |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-) | 使用指定的位置和大小初始化 [Rectangle](../../com.aspose.drawing/rectangle) 结构的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [fromLTRB(int left, int top, int right, int bottom)](#fromLTRB-int-int-int-int-) | 使用指定的边缘位置创建一个 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | 返回第三个 [Rectangle](../../com.aspose.drawing/rectangle) 结构，表示两个其他 [Rectangle](../../com.aspose.drawing/rectangle) 结构的交集。 |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | 测试两个 [Rectangle](../../com.aspose.drawing/rectangle) 结构的位置和大小是否相等。 |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | 测试两个 [Rectangle](../../com.aspose.drawing/rectangle) 结构的位置或大小是否不同。 |
| [ceiling(RectangleF value)](#ceiling-com.aspose.drawing.RectangleF-) | 通过将指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 值向上取整到下一个更高的整数，将其转换为 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |
| [truncate(RectangleF value)](#truncate-com.aspose.drawing.RectangleF-) | 通过截断指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 值，将其转换为 [Rectangle](../../com.aspose.drawing/rectangle)。 |
| [round(RectangleF value)](#round-com.aspose.drawing.RectangleF-) | 通过将指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 值四舍五入到最近的整数，将其转换为 [Rectangle](../../com.aspose.drawing/rectangle)。 |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | 获取一个包含两个 [Rectangle](../../com.aspose.drawing/rectangle) 结构并集的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.drawing.Rectangle-int-int-) |  |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) |  |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-) | 从两个点创建一个新矩形。 |
| [getEmpty()](#getEmpty--) | 获取一个新的 `Rectangle` 结构实例，其 `Rectangle.X`、`Rectangle.Y`、`Rectangle.Width` 和 `Rectangle.Height` 值均设为零。 |
| [getX()](#getX--) | 获取此 Rectangle 结构左上角的 x 坐标。 |
| [setX(int value)](#setX-int-) | 设置此 Rectangle 结构左上角的 x 坐标。 |
| [getY()](#getY--) | 获取此 Rectangle 结构左上角的 y 坐标。 |
| [setY(int value)](#setY-int-) | 设置此 Rectangle 结构左上角的 y 坐标。 |
| [getLocation()](#getLocation--) | 获取此 [Rectangle](../../com.aspose.drawing/rectangle) 结构左上角的坐标。 |
| [setLocation(Point value)](#setLocation-com.aspose.drawing.Point-) | 设置此 [Rectangle](../../com.aspose.drawing/rectangle) 结构左上角的坐标。 |
| [getWidth()](#getWidth--) | 获取此 Rectangle 结构的宽度。 |
| [setWidth(int value)](#setWidth-int-) | 设置此 Rectangle 结构的宽度。 |
| [getHeight()](#getHeight--) | 获取此 Rectangle 结构的高度。 |
| [setHeight(int value)](#setHeight-int-) | 设置此 Rectangle 结构的高度。 |
| [getSize()](#getSize--) | 获取此 [Rectangle](../../com.aspose.drawing/rectangle) 的大小。 |
| [setSize(Size value)](#setSize-com.aspose.drawing.Size-) | 设置此 [Rectangle](../../com.aspose.drawing/rectangle) 的大小。 |
| [getLeft()](#getLeft--) | 获取此 Rectangle 结构左边缘的 x 坐标。 |
| [getTop()](#getTop--) | 获取此 Rectangle 结构顶部边缘的 y 坐标。 |
| [getRight()](#getRight--) | 获取此 Rectangle 结构的 X 和 Width 属性值之和的 x 坐标。 |
| [getBottom()](#getBottom--) | 获取此 Rectangle 结构的 Y 和 Height 属性值之和的 y 坐标。 |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 [Rectangle](../../com.aspose.drawing/rectangle) 的所有数值属性是否为零。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 测试 obj 是否为具有与此 [Rectangle](../../com.aspose.drawing/rectangle) 结构相同位置和大小的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |
| [hashCode()](#hashCode--) | 返回此 [Rectangle](../../com.aspose.drawing/rectangle) 结构的哈希码。 |
| [toString()](#toString--) |  |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | 用此 [Rectangle](../../com.aspose.drawing/rectangle) 与指定的 [Rectangle](../../com.aspose.drawing/rectangle) 的交集替换此 [Rectangle](../../com.aspose.drawing/rectangle)。 |
| [inflate(int width, int height)](#inflate-int-int-) | 按指定的量扩大此 [Rectangle](../../com.aspose.drawing/rectangle)。 |
| [inflate(Size size)](#inflate-com.aspose.drawing.Size-) | 按指定的量扩大此 [Rectangle](../../com.aspose.drawing/rectangle)。 |
| [contains(int x, int y)](#contains-int-int-) | 确定指定的点是否包含在此 [Rectangle](../../com.aspose.drawing/rectangle) 结构中。 |
| [contains(Point pt)](#contains-com.aspose.drawing.Point-) | 确定指定的点是否包含在此 [Rectangle](../../com.aspose.drawing/rectangle) 结构中。 |
| [contains(Rectangle rect)](#contains-com.aspose.drawing.Rectangle-) |  |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.drawing.Rectangle-) | 确定此矩形是否与 `rect` 相交。 |
| [offset(int x, int y)](#offset-int-int-) | 按指定量调整此矩形的位置。 |
| [offset(Point pos)](#offset-com.aspose.drawing.Point-) | 按指定量调整此矩形的位置。 |
| [equals(Rectangle other)](#equals-com.aspose.drawing.Rectangle-) | 测试另一个 [Rectangle](../../com.aspose.drawing/rectangle) 结构是否具有与此 [Rectangle](../../com.aspose.drawing/rectangle) 结构相同的位置和大小。 |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.drawing.Rectangle-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [normalize()](#normalize--) | 通过使宽度和高度为正、左侧小于右侧、顶部小于底部来规范化矩形。 |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


使用指定的位置和大小初始化 Rectangle 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 矩形左上角的 x 坐标。 |
| y | int | 矩形左上角的 y 坐标。 |
| 宽度 | int | 矩形的宽度。 |
| 高度 | int | 矩形的高度。 |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public Rectangle(Point location, Size size)
```


使用指定的位置和大小初始化 [Rectangle](../../com.aspose.drawing/rectangle) 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| location | [Point](../../com.aspose.drawing/point) | 表示矩形区域左上角的 [Point](../../com.aspose.drawing/point)。 |
| size | [Size](../../com.aspose.drawing/size) | 表示矩形区域宽度和高度的 `Size`([.getSize](../../null/\#getSize)/[.setSize(Size)](../../null/\#setSize-Size-))。 |

### fromLTRB(int left, int top, int right, int bottom) {#fromLTRB-int-int-int-int-}
```
public static Rectangle fromLTRB(int left, int top, int right, int bottom)
```


使用指定的边缘位置创建一个 [Rectangle](../../com.aspose.drawing/rectangle) 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | int | 此 [Rectangle](../../com.aspose.drawing/rectangle) 结构左上角的 x 坐标。 |
| top | int | 此 [Rectangle](../../com.aspose.drawing/rectangle) 结构左上角的 y 坐标。 |
| right | int | 此 [Rectangle](../../com.aspose.drawing/rectangle) 结构右下角的 x 坐标。 |
| bottom | int | 此 [Rectangle](../../com.aspose.drawing/rectangle) 结构右下角的 y 坐标。 |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The new [Rectangle](../../com.aspose.drawing/rectangle) that this method creates.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


返回第三个 [Rectangle](../../com.aspose.drawing/rectangle) 结构，表示两个其他 [Rectangle](../../com.aspose.drawing/rectangle) 结构的交集。如果没有交集，则返回一个空的 [Rectangle](../../com.aspose.drawing/rectangle)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | 第一个要相交的矩形。 |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | 第二个要相交的矩形。 |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the intersection of `a` and `b`.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


测试两个 [Rectangle](../../com.aspose.drawing/rectangle) 结构的位置和大小是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | 等号运算符左侧的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | 等号运算符右侧的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |

**Returns:**
boolean - 如果两个 [Rectangle](../../com.aspose.drawing/rectangle) 结构的 X、Y、Width 和 Height 属性相等，则此运算符返回 `true`。
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


测试两个 [Rectangle](../../com.aspose.drawing/rectangle) 结构的位置或大小是否不同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | 不等号运算符左侧的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | 不等号运算符右侧的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |

**Returns:**
boolean - 如果两个 [Rectangle](../../com.aspose.drawing/rectangle) 结构的 X、Y、Width 或 Height 属性中有任意不相等，则此运算符返回 `true`；否则返回 `false`。
### ceiling(RectangleF value) {#ceiling-com.aspose.drawing.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


通过将指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 值向上取整到下一个更高的整数，将其转换为 [Rectangle](../../com.aspose.drawing/rectangle) 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | 待转换的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - Returns a [Rectangle](../../com.aspose.drawing/rectangle).
### truncate(RectangleF value) {#truncate-com.aspose.drawing.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


通过截断指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 值，将其转换为 [Rectangle](../../com.aspose.drawing/rectangle)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | 待转换的 [RectangleF](../../com.aspose.drawing/rectanglef)。 |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The truncated value of the [Rectangle](../../com.aspose.drawing/rectangle).
### round(RectangleF value) {#round-com.aspose.drawing.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


通过将指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 值四舍五入到最近的整数，将其转换为 [Rectangle](../../com.aspose.drawing/rectangle)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | 待转换的 [RectangleF](../../com.aspose.drawing/rectanglef)。 |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle).
### union(Rectangle a, Rectangle b) {#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


获取一个包含两个 [Rectangle](../../com.aspose.drawing/rectangle) 结构并集的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | 第一个要合并的矩形。 |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | 第二个要合并的矩形。 |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) structure that bounds the union of the two [Rectangle](../../com.aspose.drawing/rectangle) structures.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.drawing.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
布尔型
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


从两个点创建一个新矩形。创建的矩形将被标准化，使 (left,top) 小于 (right,bottom)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | 第一个点。 |
| point2 | [Point](../../com.aspose.drawing/point) | 第二个点。 |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A newly created rectangle.
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


获取一个新的 `Rectangle` 结构实例，其 `Rectangle.X`、`Rectangle.Y`、`Rectangle.Width` 和 `Rectangle.Height` 值均设为零。

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### getX() {#getX--}
```
public final int getX()
```


获取此 Rectangle 结构左上角的 x 坐标。

**Returns:**
int - 此 Rectangle 结构左上角的 x 坐标。
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


设置此 Rectangle 结构左上角的 x 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 此 Rectangle 结构左上角的 x 坐标。 |

### getY() {#getY--}
```
public final int getY()
```


获取此 Rectangle 结构左上角的 y 坐标。

**Returns:**
int - 此 Rectangle 结构左上角的 y 坐标。
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


设置此 Rectangle 结构左上角的 y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 此 Rectangle 结构左上角的 y 坐标。 |

### getLocation() {#getLocation--}
```
public final Point getLocation()
```


获取此 [Rectangle](../../com.aspose.drawing/rectangle) 结构左上角的坐标。

**Returns:**
[Point](../../com.aspose.drawing/point) - the coordinates of the upper-left corner of this [Rectangle](../../com.aspose.drawing/rectangle) structure.
### setLocation(Point value) {#setLocation-com.aspose.drawing.Point-}
```
public final void setLocation(Point value)
```


设置此 [Rectangle](../../com.aspose.drawing/rectangle) 结构左上角的坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.drawing/point) | 此 [Rectangle](../../com.aspose.drawing/rectangle) 结构左上角的坐标。 |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


获取此 Rectangle 结构的宽度。

**Returns:**
int - 此 Rectangle 结构的宽度。
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


设置此 Rectangle 结构的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 此 Rectangle 结构的宽度。 |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取此 Rectangle 结构的高度。

**Returns:**
int - 此 Rectangle 结构的高度。
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


设置此 Rectangle 结构的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 此 Rectangle 结构的高度。 |

### getSize() {#getSize--}
```
public final Size getSize()
```


获取此 [Rectangle](../../com.aspose.drawing/rectangle) 的大小。

**Returns:**
[Size](../../com.aspose.drawing/size) - the size of this [Rectangle](../../com.aspose.drawing/rectangle).
### setSize(Size value) {#setSize-com.aspose.drawing.Size-}
```
public final void setSize(Size value)
```


设置此 [Rectangle](../../com.aspose.drawing/rectangle) 的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Size](../../com.aspose.drawing/size) | 此 [Rectangle](../../com.aspose.drawing/rectangle) 的大小。 |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


获取此 Rectangle 结构左边缘的 x 坐标。

**Returns:**
int - 此 Rectangle 结构左边缘的 x 坐标。
### getTop() {#getTop--}
```
public final int getTop()
```


获取此 Rectangle 结构顶部边缘的 y 坐标。

**Returns:**
int - 此 Rectangle 结构上边缘的 y 坐标。
### getRight() {#getRight--}
```
public final int getRight()
```


获取此 Rectangle 结构的 X 和 Width 属性值之和的 x 坐标。

**Returns:**
int - 此 Rectangle 结构的 X 与 Width 属性值之和的 x 坐标。
### getBottom() {#getBottom--}
```
public final int getBottom()
```


获取此 Rectangle 结构的 Y 和 Height 属性值之和的 y 坐标。

**Returns:**
int - 此 Rectangle 结构的 Y 与 Height 属性值之和的 y 坐标。
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


获取一个值，指示此 [Rectangle](../../com.aspose.drawing/rectangle) 的所有数值属性是否为零。

**Returns:**
boolean - 如果此 [Rectangle](../../com.aspose.drawing/rectangle) 的 `Rectangle.Width`、`Rectangle.Height`、`Rectangle.X` 和 `Rectangle.Y` 属性全部为零，则此属性返回 `true`；否则返回 `false`。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


测试 obj 是否为具有与此 [Rectangle](../../com.aspose.drawing/rectangle) 结构相同位置和大小的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要测试的对象。 |

**Returns:**
boolean - 如果 obj 是一个 [Rectangle](../../com.aspose.drawing/rectangle) 结构且其 X、Y、Width 和 Height 属性等于此 [Rectangle](../../com.aspose.drawing/rectangle) 结构的相应属性，则此方法返回 `true`；否则返回 `false`。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此 [Rectangle](../../com.aspose.drawing/rectangle) 结构的哈希码。有关哈希码使用的说明，请参阅 GetHashCode。

**Returns:**
int - 表示此矩形哈希码的整数。
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


用此 [Rectangle](../../com.aspose.drawing/rectangle) 与指定的 [Rectangle](../../com.aspose.drawing/rectangle) 的交集替换此 [Rectangle](../../com.aspose.drawing/rectangle)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 用于相交的 [Rectangle](../../com.aspose.drawing/rectangle)。 |

### inflate(int width, int height) {#inflate-int-int-}
```
public final void inflate(int width, int height)
```


按指定的量扩大此 [Rectangle](../../com.aspose.drawing/rectangle)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 水平膨胀此 [Rectangle](../../com.aspose.drawing/rectangle) 的量。 |
| height | int | 垂直膨胀此 [Rectangle](../../com.aspose.drawing/rectangle) 的量。 |

### inflate(Size size) {#inflate-com.aspose.drawing.Size-}
```
public final void inflate(Size size)
```


按指定的量扩大此 [Rectangle](../../com.aspose.drawing/rectangle)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | 膨胀此 [Rectangle](../../com.aspose.drawing/rectangle) 的尺寸。 |

### contains(int x, int y) {#contains-int-int-}
```
public final boolean contains(int x, int y)
```


确定指定的点是否包含在此 [Rectangle](../../com.aspose.drawing/rectangle) 结构中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |

**Returns:**
boolean - 如果由 `x` 和 `y` 定义的点位于此 [Rectangle](../../com.aspose.drawing/rectangle) 结构内部，则此方法返回 `true`；否则返回 `false`。
### contains(Point pt) {#contains-com.aspose.drawing.Point-}
```
public final boolean contains(Point pt)
```


确定指定的点是否包含在此 [Rectangle](../../com.aspose.drawing/rectangle) 结构中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | 要测试的 [Point](../../com.aspose.drawing/point)。 |

**Returns:**
boolean - 如果由 `pt` 表示的点位于此 [Rectangle](../../com.aspose.drawing/rectangle) 结构内部，则此方法返回 `true`；否则返回 `false`。
### contains(Rectangle rect) {#contains-com.aspose.drawing.Rectangle-}
```
public final boolean contains(Rectangle rect)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
布尔型
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.drawing.Rectangle-}
```
public final boolean intersectsWith(Rectangle rect)
```


确定此矩形是否与 `rect` 相交。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 要测试的矩形。 |

**Returns:**
boolean - 如果存在任何相交，则此方法返回 true；否则返回 false。
### offset(int x, int y) {#offset-int-int-}
```
public final void offset(int x, int y)
```


按指定量调整此矩形的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 水平偏移量。 |
| y | int | 垂直偏移量。 |

### offset(Point pos) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point pos)
```


按指定量调整此矩形的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pos | [Point](../../com.aspose.drawing/point) | 偏移量。 |

### equals(Rectangle other) {#equals-com.aspose.drawing.Rectangle-}
```
public final boolean equals(Rectangle other)
```


测试另一个 [Rectangle](../../com.aspose.drawing/rectangle) 结构是否具有与此 [Rectangle](../../com.aspose.drawing/rectangle) 结构相同的位置和大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.drawing/rectangle) | 要测试的其他矩形 |

**Returns:**
boolean - 如果另一个 [Rectangle](../../com.aspose.drawing/rectangle) 结构及其 X、Y、Width 和 Height 属性等于此 [Rectangle](../../com.aspose.drawing/rectangle) 结构的相应属性，则此方法返回 `true`；否则返回 `false`。
### CloneTo(Rectangle that) {#CloneTo-com.aspose.drawing.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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


通过使宽度和高度为正、左侧小于右侧、顶部小于底部来规范化矩形。

