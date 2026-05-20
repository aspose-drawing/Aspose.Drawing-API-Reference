---
title: CharacterRange
second_title: Aspose.Drawing for Java API 参考
description: 指定字符串中字符位置的范围。
type: docs
weight: 13
url: /zh/java/com.aspose.drawing/characterrange/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class CharacterRange extends Struct<CharacterRange> implements Cloneable
```

指定字符串中字符位置的范围。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CharacterRange()](#CharacterRange--) |  |
| [CharacterRange(int first, int length)](#CharacterRange-int-int-) | 初始化一个新的 [CharacterRange](../../com.aspose.drawing/characterrange) 结构体实例，指定字符串中字符位置的范围。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFirst()](#getFirst--) | 获取或设置此 [CharacterRange](../../com.aspose.drawing/characterrange) 中第一个字符在字符串中的位置。 |
| [setFirst(int value)](#setFirst-int-) | 获取或设置此 [CharacterRange](../../com.aspose.drawing/characterrange) 中第一个字符在字符串中的位置。 |
| [getLength()](#getLength--) | 获取或设置此 [CharacterRange](../../com.aspose.drawing/characterrange) 中的位置数量。 |
| [setLength(int value)](#setLength-int-) | 获取或设置此 [CharacterRange](../../com.aspose.drawing/characterrange) 中的位置数量。 |
| [op_Equality(CharacterRange cr1, CharacterRange cr2)](#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | 比较两个 [CharacterRange](../../com.aspose.drawing/characterrange) 对象。 |
| [op_Inequality(CharacterRange cr1, CharacterRange cr2)](#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | 比较两个 [CharacterRange](../../com.aspose.drawing/characterrange) 对象。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 获取一个值，指示此对象是否等价于指定的对象。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [CloneTo(CharacterRange that)](#CloneTo-com.aspose.drawing.CharacterRange-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### CharacterRange() {#CharacterRange--}
```
public CharacterRange()
```


### CharacterRange(int first, int length) {#CharacterRange-int-int-}
```
public CharacterRange(int first, int length)
```


初始化一个新的 [CharacterRange](../../com.aspose.drawing/characterrange) 结构体实例，指定字符串中字符位置的范围。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| first | int | 范围内第一个字符的位置。例如，如果 First 设置为 0，则范围的第一个位置是字符串中的位置 0。 |
| length | int | 范围内的位置数量。 |

### getFirst() {#getFirst--}
```
public final int getFirst()
```


获取或设置此 [CharacterRange](../../com.aspose.drawing/characterrange) 中第一个字符在字符串中的位置。

值：此 [CharacterRange](../../com.aspose.drawing/characterrange) 的第一个位置。

**Returns:**
int
### setFirst(int value) {#setFirst-int-}
```
public final void setFirst(int value)
```


获取或设置此 [CharacterRange](../../com.aspose.drawing/characterrange) 中第一个字符在字符串中的位置。

值：此 [CharacterRange](../../com.aspose.drawing/characterrange) 的第一个位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getLength() {#getLength--}
```
public final int getLength()
```


获取或设置此 [CharacterRange](../../com.aspose.drawing/characterrange) 中的位置数量。

值：此 [CharacterRange](../../com.aspose.drawing/characterrange) 中的位置数量。

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


获取或设置此 [CharacterRange](../../com.aspose.drawing/characterrange) 中的位置数量。

值：此 [CharacterRange](../../com.aspose.drawing/characterrange) 中的位置数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### op_Equality(CharacterRange cr1, CharacterRange cr2) {#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Equality(CharacterRange cr1, CharacterRange cr2)
```


比较两个 [CharacterRange](../../com.aspose.drawing/characterrange) 对象。获取一个值，指示这两个 [CharacterRange](../../com.aspose.drawing/characterrange) 对象的 First 和 Length 值是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | 用于比较相等性的 [CharacterRange](../../com.aspose.drawing/characterrange)。 |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | 用于比较相等性的 [CharacterRange](../../com.aspose.drawing/characterrange)。 |

**Returns:**
boolean - `true` 表示两个 CharacterRange 对象具有相同的 First 和 Length 值；否则为 `false`。
### op_Inequality(CharacterRange cr1, CharacterRange cr2) {#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Inequality(CharacterRange cr1, CharacterRange cr2)
```


比较两个 [CharacterRange](../../com.aspose.drawing/characterrange) 对象。获取一个值，指示这两个 [CharacterRange](../../com.aspose.drawing/characterrange) 对象的 First 或 Length 值是否不相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | 用于比较不等性的 [CharacterRange](../../com.aspose.drawing/characterrange)。 |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | 用于比较不等性的 [CharacterRange](../../com.aspose.drawing/characterrange)。 |

**Returns:**
boolean - `true` 表示两个 CharacterRange 对象的 First 或 Length 值任一不同；否则为 `false`。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


获取一个值，指示此对象是否等价于指定的对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于比较相等性的对象。 |

**Returns:**
boolean - `true` 表示指定的对象是具有与此实例相同的 First 和 Length 值的实例；否则为 `false`。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 一个 32 位有符号整数，作为此实例的哈希码。
### CloneTo(CharacterRange that) {#CloneTo-com.aspose.drawing.CharacterRange-}
```
public void CloneTo(CharacterRange that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| that | [CharacterRange](../../com.aspose.drawing/characterrange) |  |

### Clone() {#Clone--}
```
public CharacterRange Clone()
```




**Returns:**
[CharacterRange](../../com.aspose.drawing/characterrange)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
