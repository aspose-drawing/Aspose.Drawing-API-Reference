---
title: SizeF
second_title: Aspose.Drawing for Java API リファレンス
description: 通常は矩形の幅と高さを表す、浮動小数点数の順序付きペアを格納します。
type: docs
weight: 43
url: /ja/java/com.aspose.drawing/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class SizeF extends Struct<SizeF> implements System.IEquatable<SizeF>, Cloneable
```

通常は矩形の幅と高さを表す浮動小数点数の順序付きペアを格納します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(float width, float height)](#SizeF-float-float-) | 指定された寸法から SizeF 構造体の新しいインスタンスを初期化します。 |
| [SizeF(PointF pt)](#SizeF-com.aspose.drawing.PointF-) | 新しい [SizeF](../../com.aspose.drawing/sizef) 構造体のインスタンスを初期化します。 |
| [SizeF(SizeF size)](#SizeF-com.aspose.drawing.SizeF-) | 新しい [SizeF](../../com.aspose.drawing/sizef) 構造体のインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [op_Equality(SizeF sz1, SizeF sz2)](#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | 2 つの [SizeF](../../com.aspose.drawing/sizef) 構造体が等しいかどうかをテストします。 |
| [op_Inequality(SizeF sz1, SizeF sz2)](#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | 2 つの [SizeF](../../com.aspose.drawing/sizef) 構造体が異なるかどうかをテストします。 |
| [add(SizeF sz1, SizeF sz2)](#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | ある [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さを別の [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さに加算します。 |
| [subtract(SizeF sz1, SizeF sz2)](#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | ある [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さを別の [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さから減算します。 |
| [op_Addition(SizeF sz1, SizeF sz2)](#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | ある [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さを別の [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さに加算します。 |
| [op_Subtraction(SizeF sz1, SizeF sz2)](#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | ある [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さを別の [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さから減算します。 |
| [op_Multiply(float left, SizeF right)](#op-Multiply-float-com.aspose.drawing.SizeF-) | `float` によって [SizeF](../../com.aspose.drawing/sizef) を乗算し、[SizeF](../../com.aspose.drawing/sizef) を生成します。 |
| [op_Multiply(SizeF left, float right)](#op-Multiply-com.aspose.drawing.SizeF-float-) | `float` によって [SizeF](../../com.aspose.drawing/sizef) を乗算し、[SizeF](../../com.aspose.drawing/sizef) を生成します。 |
| [op_Division(SizeF left, float right)](#op-Division-com.aspose.drawing.SizeF-float-) | `float` によって [SizeF](../../com.aspose.drawing/sizef) を除算し、[SizeF](../../com.aspose.drawing/sizef) を生成します。 |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | この [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さがゼロかどうかを示す値を取得します。 |
| [getWidth()](#getWidth--) | この SizeF 構造体の水平成分を取得します。 |
| [setWidth(float value)](#setWidth-float-) | この SizeF 構造体の水平成分を設定します。 |
| [getHeight()](#getHeight--) | この SizeF 構造体の垂直成分を取得します。 |
| [setHeight(float value)](#setHeight-float-) | この SizeF 構造体の垂直成分を設定します。 |
| [hashCode()](#hashCode--) | この [SizeF](../../com.aspose.drawing/sizef) 構造体のハッシュコードを返します。 |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトがこの [SizeF](../../com.aspose.drawing/sizef) 構造体と同じ寸法を持つ [SizeF](../../com.aspose.drawing/sizef) 構造体かどうかをテストします。 |
| [toSize()](#toSize--) | [SizeF](../../com.aspose.drawing/sizef) 構造体を [Size](../../com.aspose.drawing/size) 構造体に変換します。 |
| [toPointF()](#toPointF--) | [SizeF](../../com.aspose.drawing/sizef) 構造体を [PointF](../../com.aspose.drawing/pointf) 構造体に変換します。 |
| [equals(SizeF other)](#equals-com.aspose.drawing.SizeF-) | 他の [SizeF](../../com.aspose.drawing/sizef) 構造体がこの [SizeF](../../com.aspose.drawing/sizef) 構造体と同じサイズかどうかをテストします。 |
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


指定された寸法から SizeF 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 | float | 新しい SizeF 構造体の幅成分。 |
| 高さ | float | 新しい SizeF 構造体の高さ成分。 |

### SizeF(PointF pt) {#SizeF-com.aspose.drawing.PointF-}
```
public SizeF(PointF pt)
```


新しい [SizeF](../../com.aspose.drawing/sizef) 構造体のインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | この [SizeF](../../com.aspose.drawing/sizef) 構造体を初期化するための [PointF](../../com.aspose.drawing/pointf) 構造体。 |

### SizeF(SizeF size) {#SizeF-com.aspose.drawing.SizeF-}
```
public SizeF(SizeF size)
```


新しい [SizeF](../../com.aspose.drawing/sizef) 構造体のインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | 新しい [SizeF](../../com.aspose.drawing/sizef) 構造体を作成する元となる [SizeF](../../com.aspose.drawing/sizef) 構造体。 |

### op_Equality(SizeF sz1, SizeF sz2) {#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Equality(SizeF sz1, SizeF sz2)
```


2 つの [SizeF](../../com.aspose.drawing/sizef) 構造体が等しいかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 等価演算子の左側にある [SizeF](../../com.aspose.drawing/sizef) 構造体。 |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 等価演算子の右側にある [SizeF](../../com.aspose.drawing/sizef) 構造体。 |

**Returns:**
boolean - この演算子は `sz1` と `sz2` の幅と高さが等しい場合に true を返し、そうでない場合は false を返します。
### op_Inequality(SizeF sz1, SizeF sz2) {#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Inequality(SizeF sz1, SizeF sz2)
```


2 つの [SizeF](../../com.aspose.drawing/sizef) 構造体が異なるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 不等価演算子の左側にある [SizeF](../../com.aspose.drawing/sizef) 構造体。 |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 不等価演算子の右側にある [SizeF](../../com.aspose.drawing/sizef) 構造体。 |

**Returns:**
boolean - この演算子は `sz1` と `sz2` の幅または高さのいずれかが異なる場合に true を返し、`sz1` と `sz2` が等しい場合は false を返します。
### add(SizeF sz1, SizeF sz2) {#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF add(SizeF sz1, SizeF sz2)
```


ある [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さを別の [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さに加算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 加算する最初の [SizeF](../../com.aspose.drawing/sizef) 構造体。 |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 加算する2番目の [SizeF](../../com.aspose.drawing/sizef) 構造体。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is the result of the addition operation.
### subtract(SizeF sz1, SizeF sz2) {#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF subtract(SizeF sz1, SizeF sz2)
```


ある [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さを別の [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さから減算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 減算演算子の左側にある [SizeF](../../com.aspose.drawing/sizef) 構造体。 |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 減算演算子の右側にある [SizeF](../../com.aspose.drawing/sizef) 構造体。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is a result of the subtraction operation.
### op_Addition(SizeF sz1, SizeF sz2) {#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Addition(SizeF sz1, SizeF sz2)
```


ある [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さを別の [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さに加算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 加算する最初の [SizeF](../../com.aspose.drawing/sizef) 構造体。 |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 加算する2番目の [SizeF](../../com.aspose.drawing/sizef) 構造体。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(SizeF sz1, SizeF sz2) {#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Subtraction(SizeF sz1, SizeF sz2)
```


ある [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さを別の [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さから減算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 減算演算子の左側にある [SizeF](../../com.aspose.drawing/sizef) 構造体。 |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 減算演算子の右側にある [SizeF](../../com.aspose.drawing/sizef) 構造体。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that is the result of the subtraction operation.
### op_Multiply(float left, SizeF right) {#op-Multiply-float-com.aspose.drawing.SizeF-}
```
public static SizeF op_Multiply(float left, SizeF right)
```


`float` によって [SizeF](../../com.aspose.drawing/sizef) を乗算し、[SizeF](../../com.aspose.drawing/sizef) を生成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 左 | float | Multiplier of type `float`. |
| right | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef) 型の乗数。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(SizeF left, float right) {#op-Multiply-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Multiply(SizeF left, float right)
```


`float` によって [SizeF](../../com.aspose.drawing/sizef) を乗算し、[SizeF](../../com.aspose.drawing/sizef) を生成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef) 型の乗数。 |
| 右 | float | Multiplier of type `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(SizeF left, float right) {#op-Division-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Division(SizeF left, float right)
```


`float` によって [SizeF](../../com.aspose.drawing/sizef) を除算し、[SizeF](../../com.aspose.drawing/sizef) を生成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef) 型の被除数。 |
| 右 | float | Divisor of type `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### to_PointF(SizeF size) {#to-PointF-com.aspose.drawing.SizeF-}
```
public static PointF to_PointF(SizeF size)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.drawing/sizef) |  |
| obj2 | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
boolean
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


この [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さがゼロかどうかを示す値を取得します。

**Returns:**
boolean - この [SizeF](../../com.aspose.drawing/sizef) 構造体の幅と高さがゼロであるかどうかを示す値。
### getWidth() {#getWidth--}
```
public final float getWidth()
```


この SizeF 構造体の水平成分を取得します。

**Returns:**
float - この SizeF 構造体の水平成分。
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


この SizeF 構造体の水平成分を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この SizeF 構造体の水平成分。 |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


この SizeF 構造体の垂直成分を取得します。

**Returns:**
float - この SizeF 構造体の垂直成分。
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


この SizeF 構造体の垂直成分を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この SizeF 構造体の垂直成分。 |

### hashCode() {#hashCode--}
```
public int hashCode()
```


この [SizeF](../../com.aspose.drawing/sizef) 構造体のハッシュコードを返します。

**Returns:**
int - この [SizeF](../../com.aspose.drawing/sizef) 構造体のハッシュ値を指定する整数値。
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


指定されたオブジェクトがこの [SizeF](../../com.aspose.drawing/sizef) 構造体と同じ寸法を持つ [SizeF](../../com.aspose.drawing/sizef) 構造体かどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | The Object to test. |

**Returns:**
boolean - obj が [SizeF](../../com.aspose.drawing/sizef) であり、この SizeF と同じ幅と高さを持つ場合は `true` を返し、そうでない場合は `false` を返します。
### toSize() {#toSize--}
```
public final Size toSize()
```


[SizeF](../../com.aspose.drawing/sizef) 構造体を [Size](../../com.aspose.drawing/size) 構造体に変換します。

**Returns:**
[Size](../../com.aspose.drawing/size) - Returns a [Size](../../com.aspose.drawing/size) structure.
### toPointF() {#toPointF--}
```
public final PointF toPointF()
```


[SizeF](../../com.aspose.drawing/sizef) 構造体を [PointF](../../com.aspose.drawing/pointf) 構造体に変換します。

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - Returns a [PointF](../../com.aspose.drawing/pointf) structure.
### equals(SizeF other) {#equals-com.aspose.drawing.SizeF-}
```
public final boolean equals(SizeF other)
```


他の [SizeF](../../com.aspose.drawing/sizef) 構造体がこの [SizeF](../../com.aspose.drawing/sizef) 構造体と同じサイズかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [SizeF](../../com.aspose.drawing/sizef) | Other size to test |

**Returns:**
boolean - other [SizeF](../../com.aspose.drawing/sizef) 構造体とその Width および Height プロパティがこの [SizeF](../../com.aspose.drawing/sizef) 構造体の対応するプロパティと等しい場合は `true` を返し、そうでない場合は `false` を返します。
### CloneTo(SizeF that) {#CloneTo-com.aspose.drawing.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
