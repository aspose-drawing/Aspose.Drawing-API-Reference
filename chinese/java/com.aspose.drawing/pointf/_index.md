---
title: PointF
second_title: Aspose.Drawing for Java API 参考
description: 表示一对浮点数 x 和 y 坐标，定义二维平面中的一个点。
type: docs
weight: 37
url: /zh/java/com.aspose.drawing/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class PointF extends Struct<PointF> implements System.IEquatable<PointF>, Cloneable
```

表示一对浮点数 x 和 y 坐标，定义二维平面中的一个点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | 使用指定坐标初始化 PointF 结构的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [op_Addition(PointF pt, Size sz)](#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [op_Subtraction(PointF pt, Size sz)](#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [op_Addition(PointF pt, SizeF sz)](#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [op_Subtraction(PointF pt, SizeF sz)](#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [op_Equality(PointF left, PointF right)](#op-Equality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | 比较两个 [PointF](../../com.aspose.drawing/pointf) 结构。 |
| [op_Inequality(PointF left, PointF right)](#op-Inequality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | 确定指定点的坐标是否不相等。 |
| [add(PointF orig, Size size)](#add-com.aspose.drawing.PointF-com.aspose.drawing.Size-) | 按指定的 [SizeF](../../com.aspose.drawing/sizef) 平移给定的 [PointF](../../com.aspose.drawing/pointf)。 |
| [subtract(PointF pt, Size sz)](#subtract-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [add(PointF orig, SizeF sizeF)](#add-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | 按指定的 [SizeF](../../com.aspose.drawing/sizef) 平移给定的 [PointF](../../com.aspose.drawing/pointf)。 |
| [subtract(PointF pt, SizeF sz)](#subtract-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 [PointF](../../com.aspose.drawing/pointf) 是否为空。 |
| [getX()](#getX--) | 获取此 PointF 的 x 坐标。 |
| [setX(float value)](#setX-float-) | 设置此 PointF 的 x 坐标。 |
| [getY()](#getY--) | 获取此 PointF 的 y 坐标。 |
| [setY(float value)](#setY-float-) | 设置此 PointF 的 y 坐标。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定此 [PointF](../../com.aspose.drawing/pointf) 是否包含与指定对象相同的坐标。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [toString()](#toString--) |  |
| [equals(PointF other)](#equals-com.aspose.drawing.PointF-) | 测试另一个 [PointF](../../com.aspose.drawing/pointf) 结构是否具有与此 [PointF](../../com.aspose.drawing/pointf) 结构相同的位置。 |
| [CloneTo(PointF that)](#CloneTo-com.aspose.drawing.PointF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


使用指定坐标初始化 PointF 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | 浮点数 | 点的水平位置。 |
| y | 浮点数 | 点的垂直位置。 |

### op_Addition(PointF pt, Size sz) {#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF op_Addition(PointF pt, Size sz)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Subtraction(PointF pt, Size sz) {#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF op_Subtraction(PointF pt, Size sz)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Addition(PointF pt, SizeF sz) {#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF op_Addition(PointF pt, SizeF sz)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Subtraction(PointF pt, SizeF sz) {#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF op_Subtraction(PointF pt, SizeF sz)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Equality(PointF left, PointF right) {#op-Equality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean op_Equality(PointF left, PointF right)
```


比较两个 [PointF](../../com.aspose.drawing/pointf) 结构。结果指定两个 [PointF](../../com.aspose.drawing/pointf) 结构的 `PointF.X` 和 `PointF.Y` 属性值是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [PointF](../../com.aspose.drawing/pointf) | 要比较的第一个 [PointF](../../com.aspose.drawing/pointf)。 |
| right | [PointF](../../com.aspose.drawing/pointf) | 要比较的第二个 [PointF](../../com.aspose.drawing/pointf)。 |

**Returns:**
boolean - 如果左侧和右侧 [PointF](../../com.aspose.drawing/pointf) 结构的 `PointF.X` 和 `PointF.Y` 值相等，则为 true；否则为 false。
### op_Inequality(PointF left, PointF right) {#op-Inequality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean op_Inequality(PointF left, PointF right)
```


确定指定点的坐标是否不相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [PointF](../../com.aspose.drawing/pointf) | 要比较的第一个 [PointF](../../com.aspose.drawing/pointf)。 |
| right | [PointF](../../com.aspose.drawing/pointf) | 要比较的第二个 [PointF](../../com.aspose.drawing/pointf)。 |

**Returns:**
boolean - true 表示 `left` 和 `right` 的 `PointF.X` 与 `PointF.Y` 值不相等；否则为 false。
### add(PointF orig, Size size) {#add-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF add(PointF orig, Size size)
```


按指定的 [SizeF](../../com.aspose.drawing/sizef) 平移给定的 [PointF](../../com.aspose.drawing/pointf)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| orig | [PointF](../../com.aspose.drawing/pointf) | 要平移的 [PointF](../../com.aspose.drawing/pointf)。 |
| size | [Size](../../com.aspose.drawing/size) | 指定要添加到 `orig` 坐标的数值的 [Size](../../com.aspose.drawing/size)。 |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The translated [PointF](../../com.aspose.drawing/pointf).
### subtract(PointF pt, Size sz) {#subtract-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF subtract(PointF pt, Size sz)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### add(PointF orig, SizeF sizeF) {#add-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF add(PointF orig, SizeF sizeF)
```


按指定的 [SizeF](../../com.aspose.drawing/sizef) 平移给定的 [PointF](../../com.aspose.drawing/pointf)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| orig | [PointF](../../com.aspose.drawing/pointf) | 要平移的 [PointF](../../com.aspose.drawing/pointf)。 |
| sizeF | [SizeF](../../com.aspose.drawing/sizef) | 指定要添加到 `orig` 坐标的数值的 [SizeF](../../com.aspose.drawing/sizef)。 |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The translated [PointF](../../com.aspose.drawing/pointf).
### subtract(PointF pt, SizeF sz) {#subtract-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF subtract(PointF pt, SizeF sz)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.drawing/pointf) |  |
| obj2 | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
布尔型
### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```




**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


获取一个值，指示此 [PointF](../../com.aspose.drawing/pointf) 是否为空。

**Returns:**
boolean - 一个指示此 [PointF](../../com.aspose.drawing/pointf) 是否为空的值。
### getX() {#getX--}
```
public final float getX()
```


获取此 PointF 的 x 坐标。

**Returns:**
float - 此 PointF 的 x 坐标。
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


设置此 PointF 的 x 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 浮点数 | 此 PointF 的 x 坐标。 |

### getY() {#getY--}
```
public final float getY()
```


获取此 PointF 的 y 坐标。

**Returns:**
float - 此 PointF 的 y 坐标。
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


设置此 PointF 的 y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 浮点数 | 此 PointF 的 y 坐标。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定此 [PointF](../../com.aspose.drawing/pointf) 是否包含与指定对象相同的坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要测试的对象。 |

**Returns:**
boolean - 如果 `obj` 是一个 [PointF](../../com.aspose.drawing/pointf) 并且坐标与此 [Point](../../com.aspose.drawing/point) 相同，则此方法返回 true。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(PointF other) {#equals-com.aspose.drawing.PointF-}
```
public final boolean equals(PointF other)
```


测试另一个 [PointF](../../com.aspose.drawing/pointf) 结构是否具有与此 [PointF](../../com.aspose.drawing/pointf) 结构相同的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [PointF](../../com.aspose.drawing/pointf) | 其他要测试的点 |

**Returns:**
boolean - 如果其他 [PointF](../../com.aspose.drawing/pointf) 结构及其 X 和 Y 属性等于此 [PointF](../../com.aspose.drawing/pointf) 结构的对应属性，则此方法返回 `true`；否则返回 `false`。
### CloneTo(PointF that) {#CloneTo-com.aspose.drawing.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| that | [PointF](../../com.aspose.drawing/pointf) |  |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
