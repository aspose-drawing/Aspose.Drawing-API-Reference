---
title: SizeF
second_title: Aspose.Drawing for Java API 参考
description: 存储一对有序的浮点数，通常表示矩形的宽度和高度。
type: docs
weight: 43
url: /zh/java/com.aspose.drawing/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class SizeF extends Struct<SizeF> implements System.IEquatable<SizeF>, Cloneable
```

存储一对浮点数，通常表示矩形的宽度和高度。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(float width, float height)](#SizeF-float-float-) | 使用指定的尺寸初始化 SizeF 结构的新实例。 |
| [SizeF(PointF pt)](#SizeF-com.aspose.drawing.PointF-) | 初始化 [SizeF](../../com.aspose.drawing/sizef) 结构的新实例。 |
| [SizeF(SizeF size)](#SizeF-com.aspose.drawing.SizeF-) | 初始化 [SizeF](../../com.aspose.drawing/sizef) 结构的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [op_Equality(SizeF sz1, SizeF sz2)](#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | 测试两个 [SizeF](../../com.aspose.drawing/sizef) 结构是否相等。 |
| [op_Inequality(SizeF sz1, SizeF sz2)](#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | 测试两个 [SizeF](../../com.aspose.drawing/sizef) 结构是否不同。 |
| [add(SizeF sz1, SizeF sz2)](#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | 将一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度加到另一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度上。 |
| [subtract(SizeF sz1, SizeF sz2)](#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | 从另一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度中减去一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度。 |
| [op_Addition(SizeF sz1, SizeF sz2)](#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | 将一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度加到另一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度上。 |
| [op_Subtraction(SizeF sz1, SizeF sz2)](#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | 从另一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度中减去一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度。 |
| [op_Multiply(float left, SizeF right)](#op-Multiply-float-com.aspose.drawing.SizeF-) | 将 [SizeF](../../com.aspose.drawing/sizef) 乘以 `float`，生成 [SizeF](../../com.aspose.drawing/sizef)。 |
| [op_Multiply(SizeF left, float right)](#op-Multiply-com.aspose.drawing.SizeF-float-) | 将 [SizeF](../../com.aspose.drawing/sizef) 乘以 `float`，生成 [SizeF](../../com.aspose.drawing/sizef)。 |
| [op_Division(SizeF left, float right)](#op-Division-com.aspose.drawing.SizeF-float-) | 将 [SizeF](../../com.aspose.drawing/sizef) 除以 `float`，生成 [SizeF](../../com.aspose.drawing/sizef)。 |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 [SizeF](../../com.aspose.drawing/sizef) 结构是否具有宽度和高度为零。 |
| [getWidth()](#getWidth--) | 获取此 SizeF 结构的水平分量。 |
| [setWidth(float value)](#setWidth-float-) | 设置此 SizeF 结构的水平分量。 |
| [getHeight()](#getHeight--) | 获取此 SizeF 结构的垂直分量。 |
| [setHeight(float value)](#setHeight-float-) | 设置此 SizeF 结构的垂直分量。 |
| [hashCode()](#hashCode--) | 返回此 [SizeF](../../com.aspose.drawing/sizef) 结构的哈希码。 |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 测试指定的对象是否为具有与此 [SizeF](../../com.aspose.drawing/sizef) 结构相同尺寸的 [SizeF](../../com.aspose.drawing/sizef) 结构。 |
| [toSize()](#toSize--) | 将 [SizeF](../../com.aspose.drawing/sizef) 结构转换为 [Size](../../com.aspose.drawing/size) 结构。 |
| [toPointF()](#toPointF--) | 将 [SizeF](../../com.aspose.drawing/sizef) 结构转换为 [PointF](../../com.aspose.drawing/pointf) 结构。 |
| [equals(SizeF other)](#equals-com.aspose.drawing.SizeF-) | 测试另一个 [SizeF](../../com.aspose.drawing/sizef) 结构是否具有与此 [SizeF](../../com.aspose.drawing/sizef) 结构相同的大小。 |
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


使用指定的尺寸初始化 SizeF 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | 浮点数 | 新 SizeF 结构的宽度分量。 |
| 高度 | 浮点数 | 新 SizeF 结构的高度分量。 |

### SizeF(PointF pt) {#SizeF-com.aspose.drawing.PointF-}
```
public SizeF(PointF pt)
```


初始化 [SizeF](../../com.aspose.drawing/sizef) 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | 用于初始化此 [SizeF](../../com.aspose.drawing/sizef) 结构的 [PointF](../../com.aspose.drawing/pointf) 结构。 |

### SizeF(SizeF size) {#SizeF-com.aspose.drawing.SizeF-}
```
public SizeF(SizeF size)
```


初始化 [SizeF](../../com.aspose.drawing/sizef) 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | 用于创建新 [SizeF](../../com.aspose.drawing/sizef) 结构的 [SizeF](../../com.aspose.drawing/sizef) 结构。 |

### op_Equality(SizeF sz1, SizeF sz2) {#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Equality(SizeF sz1, SizeF sz2)
```


测试两个 [SizeF](../../com.aspose.drawing/sizef) 结构是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 等号运算符左侧的 [SizeF](../../com.aspose.drawing/sizef) 结构。 |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 等号运算符右侧的 [SizeF](../../com.aspose.drawing/sizef) 结构。 |

**Returns:**
boolean - 如果 `sz1` 和 `sz2` 的宽度和高度相等，则此运算符返回 true；否则返回 false。
### op_Inequality(SizeF sz1, SizeF sz2) {#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Inequality(SizeF sz1, SizeF sz2)
```


测试两个 [SizeF](../../com.aspose.drawing/sizef) 结构是否不同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 不等号运算符左侧的 [SizeF](../../com.aspose.drawing/sizef) 结构。 |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 不等号运算符右侧的 [SizeF](../../com.aspose.drawing/sizef) 结构。 |

**Returns:**
boolean - 如果 `sz1` 和 `sz2` 在宽度或高度任一方面不同，则此运算符返回 true；如果 `sz1` 和 `sz2` 相等，则返回 false。
### add(SizeF sz1, SizeF sz2) {#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF add(SizeF sz1, SizeF sz2)
```


将一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度加到另一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度上。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 要相加的第一个 [SizeF](../../com.aspose.drawing/sizef) 结构。 |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 要相加的第二个 [SizeF](../../com.aspose.drawing/sizef) 结构。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is the result of the addition operation.
### subtract(SizeF sz1, SizeF sz2) {#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF subtract(SizeF sz1, SizeF sz2)
```


从另一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度中减去一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 减法运算符左侧的 [SizeF](../../com.aspose.drawing/sizef) 结构。 |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 减法运算符右侧的 [SizeF](../../com.aspose.drawing/sizef) 结构。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is a result of the subtraction operation.
### op_Addition(SizeF sz1, SizeF sz2) {#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Addition(SizeF sz1, SizeF sz2)
```


将一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度加到另一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度上。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 要相加的第一个 [SizeF](../../com.aspose.drawing/sizef) 结构。 |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 要相加的第二个 [SizeF](../../com.aspose.drawing/sizef) 结构。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(SizeF sz1, SizeF sz2) {#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Subtraction(SizeF sz1, SizeF sz2)
```


从另一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度中减去一个 [SizeF](../../com.aspose.drawing/sizef) 结构的宽度和高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 减法运算符左侧的 [SizeF](../../com.aspose.drawing/sizef) 结构。 |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 减法运算符右侧的 [SizeF](../../com.aspose.drawing/sizef) 结构。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that is the result of the subtraction operation.
### op_Multiply(float left, SizeF right) {#op-Multiply-float-com.aspose.drawing.SizeF-}
```
public static SizeF op_Multiply(float left, SizeF right)
```


将 [SizeF](../../com.aspose.drawing/sizef) 乘以 `float`，生成 [SizeF](../../com.aspose.drawing/sizef)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 左 | 浮点数 | 乘数的类型为 `float`。 |
| right | [SizeF](../../com.aspose.drawing/sizef) | 乘数类型为 [SizeF](../../com.aspose.drawing/sizef)。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(SizeF left, float right) {#op-Multiply-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Multiply(SizeF left, float right)
```


将 [SizeF](../../com.aspose.drawing/sizef) 乘以 `float`，生成 [SizeF](../../com.aspose.drawing/sizef)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | 乘数类型为 [SizeF](../../com.aspose.drawing/sizef)。 |
| 右 | 浮点数 | 乘数的类型为 `float`。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(SizeF left, float right) {#op-Division-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Division(SizeF left, float right)
```


将 [SizeF](../../com.aspose.drawing/sizef) 除以 `float`，生成 [SizeF](../../com.aspose.drawing/sizef)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | 被除数类型为 [SizeF](../../com.aspose.drawing/sizef)。 |
| 右 | 浮点数 | 除数的类型为 `int`。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### to_PointF(SizeF size) {#to-PointF-com.aspose.drawing.SizeF-}
```
public static PointF to_PointF(SizeF size)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.drawing/sizef) |  |
| obj2 | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
布尔型
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


获取一个值，指示此 [SizeF](../../com.aspose.drawing/sizef) 结构是否具有宽度和高度为零。

**Returns:**
boolean - 一个指示此 [SizeF](../../com.aspose.drawing/sizef) 结构是否宽度和高度为零的值。
### getWidth() {#getWidth--}
```
public final float getWidth()
```


获取此 SizeF 结构的水平分量。

**Returns:**
float - 此 SizeF 结构的水平分量。
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


设置此 SizeF 结构的水平分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 浮点数 | 此 SizeF 结构的水平分量。 |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


获取此 SizeF 结构的垂直分量。

**Returns:**
float - 此 SizeF 结构的垂直分量。
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


设置此 SizeF 结构的垂直分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 浮点数 | 此 SizeF 结构的垂直分量。 |

### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此 [SizeF](../../com.aspose.drawing/sizef) 结构的哈希码。

**Returns:**
int - 一个指定此 [SizeF](../../com.aspose.drawing/sizef) 结构哈希值的整数。
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


测试指定的对象是否为具有与此 [SizeF](../../com.aspose.drawing/sizef) 结构相同尺寸的 [SizeF](../../com.aspose.drawing/sizef) 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要测试的对象。 |

**Returns:**
boolean - 如果 obj 是一个 [SizeF](../../com.aspose.drawing/sizef) 且宽度和高度与此 SizeF 相同，则此方法返回 `true`；否则返回 `false`。
### toSize() {#toSize--}
```
public final Size toSize()
```


将 [SizeF](../../com.aspose.drawing/sizef) 结构转换为 [Size](../../com.aspose.drawing/size) 结构。

**Returns:**
[Size](../../com.aspose.drawing/size) - Returns a [Size](../../com.aspose.drawing/size) structure.
### toPointF() {#toPointF--}
```
public final PointF toPointF()
```


将 [SizeF](../../com.aspose.drawing/sizef) 结构转换为 [PointF](../../com.aspose.drawing/pointf) 结构。

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - Returns a [PointF](../../com.aspose.drawing/pointf) structure.
### equals(SizeF other) {#equals-com.aspose.drawing.SizeF-}
```
public final boolean equals(SizeF other)
```


测试另一个 [SizeF](../../com.aspose.drawing/sizef) 结构是否具有与此 [SizeF](../../com.aspose.drawing/sizef) 结构相同的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [SizeF](../../com.aspose.drawing/sizef) | 要测试的其他尺寸 |

**Returns:**
boolean - 如果 other [SizeF](../../com.aspose.drawing/sizef) 结构及其 Width 和 Height 属性等于此 [SizeF](../../com.aspose.drawing/sizef) 结构的相应属性，则此方法返回 `true`；否则返回 `false`。
### CloneTo(SizeF that) {#CloneTo-com.aspose.drawing.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
