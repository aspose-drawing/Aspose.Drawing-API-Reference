---
title: Point
second_title: Aspose.Drawing for Java API 参考
description: 表示一对整数 x 和 y 坐标，定义二维平面中的一个点。
type: docs
weight: 36
url: /zh/java/com.aspose.drawing/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Point extends Struct<Point> implements System.IEquatable<Point>, Cloneable
```

表示一对整数 x 和 y 坐标，定义二维平面中的一个点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | 使用指定坐标初始化 [Point](../../com.aspose.drawing/point) 结构的新实例。 |
| [Point(Size sz)](#Point-com.aspose.drawing.Size-) |  |
| [Point(int dw)](#Point-int-) | 使用整数值指定的坐标初始化 [Point](../../com.aspose.drawing/point) 结构的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [EMPTY](#EMPTY) | 表示一个 `Point.X` 和 `Point.Y` 值均为零的 [Point](../../com.aspose.drawing/point)。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [to_PointF(Point p)](#to-PointF-com.aspose.drawing.Point-) | 将指定的 [Point](../../com.aspose.drawing/point) 结构转换为 [PointF](../../com.aspose.drawing/pointf) 结构。 |
| [to_Size(Point p)](#to-Size-com.aspose.drawing.Point-) |  |
| [op_Addition(Point pt, Size sz)](#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Subtraction(Point pt, Size sz)](#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Equality(Point left, Point right)](#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | 比较两个 [Point](../../com.aspose.drawing/point) 对象。 |
| [op_Inequality(Point left, Point right)](#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | 比较两个 [Point](../../com.aspose.drawing/point) 对象。 |
| [add(Point pt, Size sz)](#add-com.aspose.drawing.Point-com.aspose.drawing.Size-) | 将指定的 [Size](../../com.aspose.drawing/size) 添加到指定的 [Point](../../com.aspose.drawing/point) 中。 |
| [subtract(Point pt, Size sz)](#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [ceiling(PointF value)](#ceiling-com.aspose.drawing.PointF-) |  |
| [truncate(PointF value)](#truncate-com.aspose.drawing.PointF-) | 通过对所有坐标执行截断操作，将 PointF 转换为 Point。 |
| [round(PointF value)](#round-com.aspose.drawing.PointF-) | 通过将 [Point](../../com.aspose.drawing/point) 值四舍五入到最近的整数，将指定的 [PointF](../../com.aspose.drawing/pointf) 转换为 Point 对象。 |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-) |  |
| [getEmpty()](#getEmpty--) |  |
| [getX()](#getX--) | 获取此 Point 的 x 坐标。 |
| [setX(int value)](#setX-int-) | 设置此 Point 的 x 坐标。 |
| [getY()](#getY--) | 获取此 Point 的 y 坐标。 |
| [setY(int value)](#setY-int-) | 设置此 Point 的 y 坐标。 |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 [Point](../../com.aspose.drawing/point) 是否为空。 |
| [hashCode()](#hashCode--) | 返回此 [Point](../../com.aspose.drawing/point) 的哈希码。 |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定此 [Point](../../com.aspose.drawing/point) 是否包含与指定对象相同的坐标。 |
| [offset(int dx, int dy)](#offset-int-int-) | 按指定的量平移此 [Point](../../com.aspose.drawing/point)。 |
| [offset(Point p)](#offset-com.aspose.drawing.Point-) | 按指定的 [Point](../../com.aspose.drawing/point) 平移此 [Point](../../com.aspose.drawing/point)。 |
| [equals(Point other)](#equals-com.aspose.drawing.Point-) | 测试另一个 [Point](../../com.aspose.drawing/point) 结构是否具有与此 [Point](../../com.aspose.drawing/point) 结构相同的位置。 |
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


使用指定坐标初始化 [Point](../../com.aspose.drawing/point) 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 点的水平位置。 |
| y | int | 点的垂直位置。 |

### Point(Size sz) {#Point-com.aspose.drawing.Size-}
```
public Point(Size sz)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sz | [Size](../../com.aspose.drawing/size) |  |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


使用整数值指定的坐标初始化 [Point](../../com.aspose.drawing/point) 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dw | int | 整数值。 |

### EMPTY {#EMPTY}
```
public static final Point EMPTY
```


表示一个 `Point.X` 和 `Point.Y` 值均为零的 [Point](../../com.aspose.drawing/point)。

### to_PointF(Point p) {#to-PointF-com.aspose.drawing.Point-}
```
public static PointF to_PointF(Point p)
```


将指定的 [Point](../../com.aspose.drawing/point) 结构转换为 [PointF](../../com.aspose.drawing/pointf) 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | 要转换的 [Point](../../com.aspose.drawing/point)。 |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The [PointF](../../com.aspose.drawing/pointf) that results from the conversion.
### to_Size(Point p) {#to-Size-com.aspose.drawing.Point-}
```
public static Size to_Size(Point p)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
[Size](../../com.aspose.drawing/size)
### op_Addition(Point pt, Size sz) {#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Addition(Point pt, Size sz)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Equality(Point left, Point right) {#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Equality(Point left, Point right)
```


比较两个[Point](../../com.aspose.drawing/point)对象。结果指定这两个[Point](../../com.aspose.drawing/point)对象的 `Point.X` 和 `Point.Y` 属性的值是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | 第一个要比较的[Point](../../com.aspose.drawing/point)。 |
| right | [Point](../../com.aspose.drawing/point) | 第二个要比较的[Point](../../com.aspose.drawing/point)。 |

**Returns:**
boolean - 如果 `left` 和 `right` 的 `Point.X` 与 `Point.Y` 值相等则为 true；否则为 false。
### op_Inequality(Point left, Point right) {#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Inequality(Point left, Point right)
```


比较两个[Point](../../com.aspose.drawing/point)对象。结果指定这两个[Point](../../com.aspose.drawing/point)对象的 `Point.X` 或 `Point.Y` 属性的值是否不相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | 第一个要比较的[Point](../../com.aspose.drawing/point)。 |
| right | [Point](../../com.aspose.drawing/point) | 第二个要比较的[Point](../../com.aspose.drawing/point)。 |

**Returns:**
boolean - 如果 `left` 和 `right` 的 `Point.X` 属性或 `Point.Y` 属性的值任一不同则为 true；否则为 false。
### add(Point pt, Size sz) {#add-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point add(Point pt, Size sz)
```


将指定的 [Size](../../com.aspose.drawing/size) 添加到指定的 [Point](../../com.aspose.drawing/point) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | 要添加的[Point](../../com.aspose.drawing/point)。 |
| sz | [Size](../../com.aspose.drawing/size) | 要添加的[Size](../../com.aspose.drawing/size) |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the addition operation.
### subtract(Point pt, Size sz) {#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point subtract(Point pt, Size sz)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### truncate(PointF value) {#truncate-com.aspose.drawing.PointF-}
```
public static Point truncate(PointF value)
```


通过对所有坐标执行截断操作，将 PointF 转换为 Point。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | 要截断的[PointF](../../com.aspose.drawing/pointf)。 |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the truncate operation.
### round(PointF value) {#round-com.aspose.drawing.PointF-}
```
public static Point round(PointF value)
```


通过将 [Point](../../com.aspose.drawing/point) 值四舍五入到最近的整数，将指定的 [PointF](../../com.aspose.drawing/pointf) 转换为 Point 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | 要转换的[PointF](../../com.aspose.drawing/pointf)。 |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) this method converts to.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.drawing/point) |  |
| obj2 | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
布尔型
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


获取此 Point 的 x 坐标。

**Returns:**
int - 此 Point 的 x 坐标。
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


设置此 Point 的 x 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 此 Point 的 x 坐标。 |

### getY() {#getY--}
```
public final int getY()
```


获取此 Point 的 y 坐标。

**Returns:**
int - 此 Point 的 y 坐标。
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


设置此 Point 的 y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 此 Point 的 y 坐标。 |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


获取一个值，指示此 [Point](../../com.aspose.drawing/point) 是否为空。

值：如果 X 和 Y 均为 0 则为 `true`；否则为 `false`。

**Returns:**
boolean - 指示此此[Point](../../com.aspose.drawing/point)是否为空的值。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此 [Point](../../com.aspose.drawing/point) 的哈希码。

**Returns:**
int - 指定此[Point](../../com.aspose.drawing/point)的哈希值的整数。
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


指定此 [Point](../../com.aspose.drawing/point) 是否包含与指定对象相同的坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要测试的对象。 |

**Returns:**
boolean - 如果 obj 是 Point 并且其坐标与此[Point](../../com.aspose.drawing/point)相同则为 `true`。
### offset(int dx, int dy) {#offset-int-int-}
```
public final void offset(int dx, int dy)
```


按指定的量平移此 [Point](../../com.aspose.drawing/point)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | int | 用于偏移 x 坐标的量。 |
| dy | int | 用于偏移 y 坐标的量。 |

### offset(Point p) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point p)
```


按指定的 [Point](../../com.aspose.drawing/point) 平移此 [Point](../../com.aspose.drawing/point)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | 用于偏移此[Point](../../com.aspose.drawing/point)的[Point](../../com.aspose.drawing/point)。 |

### equals(Point other) {#equals-com.aspose.drawing.Point-}
```
public final boolean equals(Point other)
```


测试另一个 [Point](../../com.aspose.drawing/point) 结构是否具有与此 [Point](../../com.aspose.drawing/point) 结构相同的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [Point](../../com.aspose.drawing/point) | 其他要测试的点 |

**Returns:**
boolean - 如果其他[Point](../../com.aspose.drawing/point)结构及其 X 和 Y 属性等于此[Point](../../com.aspose.drawing/point)结构的相应属性，则此方法返回 `true`；否则返回 `false`。
### CloneTo(Point that) {#CloneTo-com.aspose.drawing.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
