---
title: Size
second_title: Aspose.Drawing for Java API 参考
description: 存储一对有序整数，通常表示矩形的宽度和高度。
type: docs
weight: 42
url: /zh/java/com.aspose.drawing/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Size extends Struct<Size> implements System.IEquatable<Size>, Cloneable
```

存储一对整数，通常表示矩形的宽度和高度。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point pt)](#Size-com.aspose.drawing.Point-) | 根据指定的 [Point](../../com.aspose.drawing/point) 初始化一个新的 [Size](../../com.aspose.drawing/size) 结构实例。 |
| [Size(int width, int height)](#Size-int-int-) | 根据指定的尺寸初始化一个新的 [Size](../../com.aspose.drawing/size) 结构实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [to_SizeF(Size p)](#to-SizeF-com.aspose.drawing.Size-) | 将指定的 [Size](../../com.aspose.drawing/size) 转换为 [SizeF](../../com.aspose.drawing/sizef)。 |
| [op_Addition(Size sz1, Size sz2)](#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-) | 将一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度加到另一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度上。 |
| [op_Subtraction(Size sz1, Size sz2)](#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-) | 从另一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度中减去一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度。 |
| [op_Multiply(int left, Size right)](#op-Multiply-int-com.aspose.drawing.Size-) | 将一个 [Size](../../com.aspose.drawing/size) 与 `int` 相乘，生成 [Size](../../com.aspose.drawing/size)。 |
| [op_Multiply(Size left, int right)](#op-Multiply-com.aspose.drawing.Size-int-) | 将 [Size](../../com.aspose.drawing/size) 与 `int` 相乘，生成 [Size](../../com.aspose.drawing/size)。 |
| [op_Division(Size left, int right)](#op-Division-com.aspose.drawing.Size-int-) | 将 [Size](../../com.aspose.drawing/size) 除以 `int`，生成 [Size](../../com.aspose.drawing/size)。 |
| [op_Multiply(float left, Size right)](#op-Multiply-float-com.aspose.drawing.Size-) | 将 [Size](../../com.aspose.drawing/size) 与 `float` 相乘，生成 [SizeF](../../com.aspose.drawing/sizef)。 |
| [op_Multiply(Size left, float right)](#op-Multiply-com.aspose.drawing.Size-float-) | 将 [Size](../../com.aspose.drawing/size) 与 `float` 相乘，生成 [SizeF](../../com.aspose.drawing/sizef)。 |
| [op_Division(Size left, float right)](#op-Division-com.aspose.drawing.Size-float-) | 将 [Size](../../com.aspose.drawing/size) 除以 `float`，生成 [SizeF](../../com.aspose.drawing/sizef)。 |
| [op_Equality(Size sz1, Size sz2)](#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | 测试两个 [Size](../../com.aspose.drawing/size) 结构是否相等。 |
| [op_Inequality(Size sz1, Size sz2)](#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | 测试两个 [Size](../../com.aspose.drawing/size) 结构是否不同。 |
| [to_Point(Size size)](#to-Point-com.aspose.drawing.Size-) | 将指定的 [Size](../../com.aspose.drawing/size) 转换为 [Point](../../com.aspose.drawing/point)。 |
| [add(Size sz1, Size sz2)](#add-com.aspose.drawing.Size-com.aspose.drawing.Size-) | 将一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度加到另一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度上。 |
| [ceiling(SizeF value)](#ceiling-com.aspose.drawing.SizeF-) | 将指定的 [SizeF](../../com.aspose.drawing/sizef) 结构转换为 [Size](../../com.aspose.drawing/size) 结构，方法是将 [Size](../../com.aspose.drawing/size) 结构的值向上取整到下一个整数。 |
| [subtract(Size sz1, Size sz2)](#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-) | 从另一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度中减去一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度。 |
| [truncate(SizeF value)](#truncate-com.aspose.drawing.SizeF-) | 将指定的 [SizeF](../../com.aspose.drawing/sizef) 结构转换为 [Size](../../com.aspose.drawing/size) 结构，方法是将 [SizeF](../../com.aspose.drawing/sizef) 结构的值截断到下一个较低的整数。 |
| [round(SizeF value)](#round-com.aspose.drawing.SizeF-) | 将指定的 [SizeF](../../com.aspose.drawing/sizef) 结构转换为 [Size](../../com.aspose.drawing/size) 结构，方法是将 [SizeF](../../com.aspose.drawing/sizef) 结构的值四舍五入到最近的整数。 |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 [Size](../../com.aspose.drawing/size) 的宽度和高度是否为 0。 |
| [getWidth()](#getWidth--) | 获取此 [Size](../../com.aspose.drawing/size) 的水平分量。 |
| [setWidth(int value)](#setWidth-int-) | 设置此 [Size](../../com.aspose.drawing/size) 的水平分量。 |
| [getHeight()](#getHeight--) | 获取此 [Size](../../com.aspose.drawing/size) 的垂直分量。 |
| [setHeight(int value)](#setHeight-int-) | 设置此 [Size](../../com.aspose.drawing/size) 的垂直分量。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 测试指定的对象是否为具有与此 [Size](../../com.aspose.drawing/size) 相同尺寸的 [Size](../../com.aspose.drawing/size)。 |
| [hashCode()](#hashCode--) | 返回此 [Size](../../com.aspose.drawing/size) 结构的哈希码。 |
| [toString()](#toString--) |  |
| [equals(Size other)](#equals-com.aspose.drawing.Size-) | 测试另一个 [Size](../../com.aspose.drawing/size) 结构是否与此 [Size](../../com.aspose.drawing/size) 结构具有相同的大小。 |
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


根据指定的 [Point](../../com.aspose.drawing/point) 初始化一个新的 [Size](../../com.aspose.drawing/size) 结构实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | 用于初始化此 [Size](../../com.aspose.drawing/size) 的 [Point](../../com.aspose.drawing/point)。 |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


根据指定的尺寸初始化一个新的 [Size](../../com.aspose.drawing/size) 结构实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 新 [Size](../../com.aspose.drawing/size) 的宽度分量。 |
| height | int | 新 [Size](../../com.aspose.drawing/size) 的高度分量。 |

### to_SizeF(Size p) {#to-SizeF-com.aspose.drawing.Size-}
```
public static SizeF to_SizeF(Size p)
```


将指定的 [Size](../../com.aspose.drawing/size) 转换为 [SizeF](../../com.aspose.drawing/sizef)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| p | [Size](../../com.aspose.drawing/size) | 要转换的 [Size](../../com.aspose.drawing/size)。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - The [SizeF](../../com.aspose.drawing/sizef) structure to which this operator converts.
### op_Addition(Size sz1, Size sz2) {#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Addition(Size sz1, Size sz2)
```


将一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度加到另一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度上。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 要相加的第一个 [Size](../../com.aspose.drawing/size)。 |
| sz2 | [Size](../../com.aspose.drawing/size) | 要相加的第二个 [Size](../../com.aspose.drawing/size)。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(Size sz1, Size sz2) {#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Subtraction(Size sz1, Size sz2)
```


从另一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度中减去一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 减法运算符左侧的 [Size](../../com.aspose.drawing/size) 结构。 |
| sz2 | [Size](../../com.aspose.drawing/size) | 减法运算符右侧的 [Size](../../com.aspose.drawing/size) 结构。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the subtraction operation.
### op_Multiply(int left, Size right) {#op-Multiply-int-com.aspose.drawing.Size-}
```
public static Size op_Multiply(int left, Size right)
```


将一个 [Size](../../com.aspose.drawing/size) 与 `int` 相乘，生成 [Size](../../com.aspose.drawing/size)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 左 | int | 类型为 `int` 的乘数。 |
| right | [Size](../../com.aspose.drawing/size) | 类型为 [Size](../../com.aspose.drawing/size) 的被乘数。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Multiply(Size left, int right) {#op-Multiply-com.aspose.drawing.Size-int-}
```
public static Size op_Multiply(Size left, int right)
```


将 [Size](../../com.aspose.drawing/size) 与 `int` 相乘，生成 [Size](../../com.aspose.drawing/size)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | 类型为 [Size](../../com.aspose.drawing/size) 的被乘数。 |
| 右 | int | 类型为 `int` 的乘数。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Division(Size left, int right) {#op-Division-com.aspose.drawing.Size-int-}
```
public static Size op_Division(Size left, int right)
```


将 [Size](../../com.aspose.drawing/size) 除以 `int`，生成 [Size](../../com.aspose.drawing/size)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | 被除数的类型为 [Size](../../com.aspose.drawing/size)。 |
| 右 | int | 除数的类型为 `int`。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - Result of type [Size](../../com.aspose.drawing/size).
### op_Multiply(float left, Size right) {#op-Multiply-float-com.aspose.drawing.Size-}
```
public static SizeF op_Multiply(float left, Size right)
```


将 [Size](../../com.aspose.drawing/size) 与 `float` 相乘，生成 [SizeF](../../com.aspose.drawing/sizef)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 左 | 浮点数 | 乘数的类型为 `float`。 |
| right | [Size](../../com.aspose.drawing/size) | 类型为 [Size](../../com.aspose.drawing/size) 的被乘数。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(Size left, float right) {#op-Multiply-com.aspose.drawing.Size-float-}
```
public static SizeF op_Multiply(Size left, float right)
```


将 [Size](../../com.aspose.drawing/size) 与 `float` 相乘，生成 [SizeF](../../com.aspose.drawing/sizef)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | 类型为 [Size](../../com.aspose.drawing/size) 的被乘数。 |
| 右 | 浮点数 | 乘数的类型为 `float`。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(Size left, float right) {#op-Division-com.aspose.drawing.Size-float-}
```
public static SizeF op_Division(Size left, float right)
```


将 [Size](../../com.aspose.drawing/size) 除以 `float`，生成 [SizeF](../../com.aspose.drawing/sizef)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | 被除数的类型为 [Size](../../com.aspose.drawing/size)。 |
| 右 | 浮点数 | 除数的类型为 `int`。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### op_Equality(Size sz1, Size sz2) {#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Equality(Size sz1, Size sz2)
```


测试两个 [Size](../../com.aspose.drawing/size) 结构是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 等号运算符左侧的 [Size](../../com.aspose.drawing/size) 结构。 |
| sz2 | [Size](../../com.aspose.drawing/size) | 等号运算符右侧的 [Size](../../com.aspose.drawing/size) 结构。 |

**Returns:**
布尔值 - 如果 `sz1` 和 `sz2` 的宽度和高度相等则为 true；否则为 false。
### op_Inequality(Size sz1, Size sz2) {#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Inequality(Size sz1, Size sz2)
```


测试两个 [Size](../../com.aspose.drawing/size) 结构是否不同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 不等号运算符左侧的 [Size](../../com.aspose.drawing/size) 结构。 |
| sz2 | [Size](../../com.aspose.drawing/size) | 不等号运算符右侧的 [Size](../../com.aspose.drawing/size) 结构。 |

**Returns:**
布尔值 - 如果 `sz1` 和 `sz2` 在宽度或高度任意一项上不同则为 true；如果 `sz1` 和 `sz2` 相等则为 false。
### to_Point(Size size) {#to-Point-com.aspose.drawing.Size-}
```
public static Point to_Point(Size size)
```


将指定的 [Size](../../com.aspose.drawing/size) 转换为 [Point](../../com.aspose.drawing/point)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | 要转换的 [Size](../../com.aspose.drawing/size)。 |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) structure to which this operator converts.
### add(Size sz1, Size sz2) {#add-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size add(Size sz1, Size sz2)
```


将一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度加到另一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度上。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 要相加的第一个 [Size](../../com.aspose.drawing/size)。 |
| sz2 | [Size](../../com.aspose.drawing/size) | 要相加的第二个 [Size](../../com.aspose.drawing/size)。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### ceiling(SizeF value) {#ceiling-com.aspose.drawing.SizeF-}
```
public static Size ceiling(SizeF value)
```


将指定的 [SizeF](../../com.aspose.drawing/sizef) 结构转换为 [Size](../../com.aspose.drawing/size) 结构，方法是将 [Size](../../com.aspose.drawing/size) 结构的值向上取整到下一个整数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | 要转换的 [SizeF](../../com.aspose.drawing/sizef) 结构。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### subtract(Size sz1, Size sz2) {#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size subtract(Size sz1, Size sz2)
```


从另一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度中减去一个 [Size](../../com.aspose.drawing/size) 结构的宽度和高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 减法运算符左侧的 [Size](../../com.aspose.drawing/size) 结构。 |
| sz2 | [Size](../../com.aspose.drawing/size) | 减法运算符右侧的 [Size](../../com.aspose.drawing/size) 结构。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) that is a result of the subtraction operation.
### truncate(SizeF value) {#truncate-com.aspose.drawing.SizeF-}
```
public static Size truncate(SizeF value)
```


将指定的 [SizeF](../../com.aspose.drawing/sizef) 结构转换为 [Size](../../com.aspose.drawing/size) 结构，方法是将 [SizeF](../../com.aspose.drawing/sizef) 结构的值截断到下一个较低的整数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | 要转换的 [SizeF](../../com.aspose.drawing/sizef) 结构。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### round(SizeF value) {#round-com.aspose.drawing.SizeF-}
```
public static Size round(SizeF value)
```


将指定的 [SizeF](../../com.aspose.drawing/sizef) 结构转换为 [Size](../../com.aspose.drawing/size) 结构，方法是将 [SizeF](../../com.aspose.drawing/sizef) 结构的值四舍五入到最近的整数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | 要转换的 [SizeF](../../com.aspose.drawing/sizef) 结构。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.drawing/size) |  |
| obj2 | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
布尔型
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


获取一个值，指示此 [Size](../../com.aspose.drawing/size) 的宽度和高度是否为 0。

**Returns:**
布尔值 - 指示此 [Size](../../com.aspose.drawing/size) 的宽度和高度是否为 0 的值。
### getWidth() {#getWidth--}
```
public final int getWidth()
```


获取此 [Size](../../com.aspose.drawing/size) 的水平分量。

**Returns:**
int - 此 [Size](../../com.aspose.drawing/size) 的水平分量。
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


设置此 [Size](../../com.aspose.drawing/size) 的水平分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 此 [Size](../../com.aspose.drawing/size) 的水平分量。 |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取此 [Size](../../com.aspose.drawing/size) 的垂直分量。

**Returns:**
int - 此 [Size](../../com.aspose.drawing/size) 的垂直分量。
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


设置此 [Size](../../com.aspose.drawing/size) 的垂直分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 此 [Size](../../com.aspose.drawing/size) 的垂直分量。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


测试指定的对象是否为具有与此 [Size](../../com.aspose.drawing/size) 相同尺寸的 [Size](../../com.aspose.drawing/size)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要测试的对象。 |

**Returns:**
布尔值 - 如果 `obj` 是一个 [Size](../../com.aspose.drawing/size) 并且其宽度和高度与此 [Size](../../com.aspose.drawing/size) 相同则为 true；否则为 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此 [Size](../../com.aspose.drawing/size) 结构的哈希码。

**Returns:**
int - 指定此 [Size](../../com.aspose.drawing/size) 结构的哈希值的整数。
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


测试另一个 [Size](../../com.aspose.drawing/size) 结构是否与此 [Size](../../com.aspose.drawing/size) 结构具有相同的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [Size](../../com.aspose.drawing/size) | 要测试的其他尺寸 |

**Returns:**
布尔值 - 如果其他 [Size](../../com.aspose.drawing/size) 结构及其 Width 和 Height 属性等于此 [Size](../../com.aspose.drawing/size) 结构的相应属性，则此方法返回 `true`；否则返回 `false`。
### CloneTo(Size that) {#CloneTo-com.aspose.drawing.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
