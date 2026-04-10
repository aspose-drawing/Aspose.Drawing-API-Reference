---
title: Size
second_title: Aspose.Drawing for Java API リファレンス
description: 通常は矩形の幅と高さを表す、整数の順序付きペアを格納します。
type: docs
weight: 42
url: /ja/java/com.aspose.drawing/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Size extends Struct<Size> implements System.IEquatable<Size>, Cloneable
```

通常は矩形の幅と高さを表す整数の順序付きペアを格納します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point pt)](#Size-com.aspose.drawing.Point-) | 指定された [Point](../../com.aspose.drawing/point) から [Size](../../com.aspose.drawing/size) 構造体の新しいインスタンスを初期化します。 |
| [Size(int width, int height)](#Size-int-int-) | 指定された寸法から [Size](../../com.aspose.drawing/size) 構造体の新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [to_SizeF(Size p)](#to-SizeF-com.aspose.drawing.Size-) | 指定された [Size](../../com.aspose.drawing/size) を [SizeF](../../com.aspose.drawing/sizef) に変換します。 |
| [op_Addition(Size sz1, Size sz2)](#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-) | ある [Size](../../com.aspose.drawing/size) 構造体の幅と高さを、別の [Size](../../com.aspose.drawing/size) 構造体の幅と高さに加算します。 |
| [op_Subtraction(Size sz1, Size sz2)](#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-) | ある [Size](../../com.aspose.drawing/size) 構造体の幅と高さを、別の [Size](../../com.aspose.drawing/size) 構造体の幅と高さから減算します。 |
| [op_Multiply(int left, Size right)](#op-Multiply-int-com.aspose.drawing.Size-) | [Size](../../com.aspose.drawing/size) を `int` で乗算し、[Size](../../com.aspose.drawing/size) を生成します。 |
| [op_Multiply(Size left, int right)](#op-Multiply-com.aspose.drawing.Size-int-) | [Size](../../com.aspose.drawing/size) を `int` で乗算し、[Size](../../com.aspose.drawing/size) を生成します。 |
| [op_Division(Size left, int right)](#op-Division-com.aspose.drawing.Size-int-) | [Size](../../com.aspose.drawing/size) を `int` で除算し、[Size](../../com.aspose.drawing/size) を生成します。 |
| [op_Multiply(float left, Size right)](#op-Multiply-float-com.aspose.drawing.Size-) | [Size](../../com.aspose.drawing/size) を `float` で乗算し、[SizeF](../../com.aspose.drawing/sizef) を生成します。 |
| [op_Multiply(Size left, float right)](#op-Multiply-com.aspose.drawing.Size-float-) | [Size](../../com.aspose.drawing/size) を `float` で乗算し、[SizeF](../../com.aspose.drawing/sizef) を生成します。 |
| [op_Division(Size left, float right)](#op-Division-com.aspose.drawing.Size-float-) | `float` で [Size](../../com.aspose.drawing/size) を除算し、[SizeF](../../com.aspose.drawing/sizef) を生成します。 |
| [op_Equality(Size sz1, Size sz2)](#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | 2つの [Size](../../com.aspose.drawing/size) 構造体が等しいかどうかをテストします。 |
| [op_Inequality(Size sz1, Size sz2)](#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | 2つの [Size](../../com.aspose.drawing/size) 構造体が異なるかどうかをテストします。 |
| [to_Point(Size size)](#to-Point-com.aspose.drawing.Size-) | 指定された [Size](../../com.aspose.drawing/size) を [Point](../../com.aspose.drawing/point) に変換します。 |
| [add(Size sz1, Size sz2)](#add-com.aspose.drawing.Size-com.aspose.drawing.Size-) | ある [Size](../../com.aspose.drawing/size) 構造体の幅と高さを、別の [Size](../../com.aspose.drawing/size) 構造体の幅と高さに加算します。 |
| [ceiling(SizeF value)](#ceiling-com.aspose.drawing.SizeF-) | 指定された [SizeF](../../com.aspose.drawing/sizef) 構造体を、[Size](../../com.aspose.drawing/size) 構造体の値を次の整数に切り上げて、[Size](../../com.aspose.drawing/size) 構造体に変換します。 |
| [subtract(Size sz1, Size sz2)](#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-) | ある [Size](../../com.aspose.drawing/size) 構造体の幅と高さを、別の [Size](../../com.aspose.drawing/size) 構造体の幅と高さから減算します。 |
| [truncate(SizeF value)](#truncate-com.aspose.drawing.SizeF-) | 指定された [SizeF](../../com.aspose.drawing/sizef) 構造体を、[SizeF](../../com.aspose.drawing/sizef) 構造体の値を次の整数に切り捨てて、[Size](../../com.aspose.drawing/size) 構造体に変換します。 |
| [round(SizeF value)](#round-com.aspose.drawing.SizeF-) | 指定された [SizeF](../../com.aspose.drawing/sizef) 構造体を、[SizeF](../../com.aspose.drawing/sizef) 構造体の値を最も近い整数に丸めて、[Size](../../com.aspose.drawing/size) 構造体に変換します。 |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | この [Size](../../com.aspose.drawing/size) の幅と高さが 0 であるかどうかを示す値を取得します。 |
| [getWidth()](#getWidth--) | この [Size](../../com.aspose.drawing/size) の水平方向のコンポーネントを取得します。 |
| [setWidth(int value)](#setWidth-int-) | この [Size](../../com.aspose.drawing/size) の水平方向のコンポーネントを設定します。 |
| [getHeight()](#getHeight--) | この [Size](../../com.aspose.drawing/size) の垂直方向のコンポーネントを取得します。 |
| [setHeight(int value)](#setHeight-int-) | この [Size](../../com.aspose.drawing/size) の垂直方向のコンポーネントを設定します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトが、この [Size](../../com.aspose.drawing/size) と同じ寸法の [Size](../../com.aspose.drawing/size) かどうかをテストします。 |
| [hashCode()](#hashCode--) | この [Size](../../com.aspose.drawing/size) 構造体のハッシュコードを返します。 |
| [toString()](#toString--) |  |
| [equals(Size other)](#equals-com.aspose.drawing.Size-) | 他の [Size](../../com.aspose.drawing/size) 構造体が、この [Size](../../com.aspose.drawing/size) 構造体と同じサイズかどうかをテストします。 |
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


指定された [Point](../../com.aspose.drawing/point) から [Size](../../com.aspose.drawing/size) 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | この [Size](../../com.aspose.drawing/size) を初期化する元となる [Point](../../com.aspose.drawing/point)。 |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


指定された寸法から [Size](../../com.aspose.drawing/size) 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| width | int | 新しい [Size](../../com.aspose.drawing/size) の幅コンポーネント。 |
| height | int | 新しい [Size](../../com.aspose.drawing/size) の高さコンポーネント。 |

### to_SizeF(Size p) {#to-SizeF-com.aspose.drawing.Size-}
```
public static SizeF to_SizeF(Size p)
```


指定された [Size](../../com.aspose.drawing/size) を [SizeF](../../com.aspose.drawing/sizef) に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| p | [Size](../../com.aspose.drawing/size) | 変換する [Size](../../com.aspose.drawing/size)。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - The [SizeF](../../com.aspose.drawing/sizef) structure to which this operator converts.
### op_Addition(Size sz1, Size sz2) {#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Addition(Size sz1, Size sz2)
```


ある [Size](../../com.aspose.drawing/size) 構造体の幅と高さを、別の [Size](../../com.aspose.drawing/size) 構造体の幅と高さに加算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 加算する最初の [Size](../../com.aspose.drawing/size)。 |
| sz2 | [Size](../../com.aspose.drawing/size) | 加算する2番目の [Size](../../com.aspose.drawing/size)。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(Size sz1, Size sz2) {#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Subtraction(Size sz1, Size sz2)
```


ある [Size](../../com.aspose.drawing/size) 構造体の幅と高さを、別の [Size](../../com.aspose.drawing/size) 構造体の幅と高さから減算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 減算演算子の左側にある [Size](../../com.aspose.drawing/size) 構造体。 |
| sz2 | [Size](../../com.aspose.drawing/size) | 減算演算子の右側にある [Size](../../com.aspose.drawing/size) 構造体。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the subtraction operation.
### op_Multiply(int left, Size right) {#op-Multiply-int-com.aspose.drawing.Size-}
```
public static Size op_Multiply(int left, Size right)
```


[Size](../../com.aspose.drawing/size) を `int` で乗算し、[Size](../../com.aspose.drawing/size) を生成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 左 | int | `int` 型の乗数。 |
| right | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) 型の被乗数。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Multiply(Size left, int right) {#op-Multiply-com.aspose.drawing.Size-int-}
```
public static Size op_Multiply(Size left, int right)
```


[Size](../../com.aspose.drawing/size) を `int` で乗算し、[Size](../../com.aspose.drawing/size) を生成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) 型の被乗数。 |
| 右 | int | `int` 型の乗数。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Division(Size left, int right) {#op-Division-com.aspose.drawing.Size-int-}
```
public static Size op_Division(Size left, int right)
```


[Size](../../com.aspose.drawing/size) を `int` で除算し、[Size](../../com.aspose.drawing/size) を生成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividend of type [Size](../../com.aspose.drawing/size). |
| 右 | int | Divisor of type `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Result of type [Size](../../com.aspose.drawing/size).
### op_Multiply(float left, Size right) {#op-Multiply-float-com.aspose.drawing.Size-}
```
public static SizeF op_Multiply(float left, Size right)
```


[Size](../../com.aspose.drawing/size) を `float` で乗算し、[SizeF](../../com.aspose.drawing/sizef) を生成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 左 | float | Multiplier of type `float`. |
| right | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) 型の被乗数。 |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(Size left, float right) {#op-Multiply-com.aspose.drawing.Size-float-}
```
public static SizeF op_Multiply(Size left, float right)
```


[Size](../../com.aspose.drawing/size) を `float` で乗算し、[SizeF](../../com.aspose.drawing/sizef) を生成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) 型の被乗数。 |
| 右 | float | Multiplier of type `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(Size left, float right) {#op-Division-com.aspose.drawing.Size-float-}
```
public static SizeF op_Division(Size left, float right)
```


`float` で [Size](../../com.aspose.drawing/size) を除算し、[SizeF](../../com.aspose.drawing/sizef) を生成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividend of type [Size](../../com.aspose.drawing/size). |
| 右 | float | Divisor of type `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### op_Equality(Size sz1, Size sz2) {#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Equality(Size sz1, Size sz2)
```


2つの [Size](../../com.aspose.drawing/size) 構造体が等しいかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | The [Size](../../com.aspose.drawing/size) structure on the left side of the equality operator. |
| sz2 | [Size](../../com.aspose.drawing/size) | The [Size](../../com.aspose.drawing/size) structure on the right of the equality operator. |

**Returns:**
boolean - true if `sz1` and `sz2` have equal width and height; otherwise, false.
### op_Inequality(Size sz1, Size sz2) {#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Inequality(Size sz1, Size sz2)
```


2つの [Size](../../com.aspose.drawing/size) 構造体が異なるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | The [Size](../../com.aspose.drawing/size) structure on the left of the inequality operator. |
| sz2 | [Size](../../com.aspose.drawing/size) | The [Size](../../com.aspose.drawing/size) structure on the right of the inequality operator. |

**Returns:**
boolean - true if `sz1` and `sz2` differ either in width or height; false if `sz1` and `sz2` are equal.
### to_Point(Size size) {#to-Point-com.aspose.drawing.Size-}
```
public static Point to_Point(Size size)
```


指定された [Size](../../com.aspose.drawing/size) を [Point](../../com.aspose.drawing/point) に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | 変換する [Size](../../com.aspose.drawing/size)。 |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) structure to which this operator converts.
### add(Size sz1, Size sz2) {#add-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size add(Size sz1, Size sz2)
```


ある [Size](../../com.aspose.drawing/size) 構造体の幅と高さを、別の [Size](../../com.aspose.drawing/size) 構造体の幅と高さに加算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 加算する最初の [Size](../../com.aspose.drawing/size)。 |
| sz2 | [Size](../../com.aspose.drawing/size) | 加算する2番目の [Size](../../com.aspose.drawing/size)。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### ceiling(SizeF value) {#ceiling-com.aspose.drawing.SizeF-}
```
public static Size ceiling(SizeF value)
```


指定された [SizeF](../../com.aspose.drawing/sizef) 構造体を、[Size](../../com.aspose.drawing/size) 構造体の値を次の整数に切り上げて、[Size](../../com.aspose.drawing/size) 構造体に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | The [SizeF](../../com.aspose.drawing/sizef) structure to convert. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### subtract(Size sz1, Size sz2) {#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size subtract(Size sz1, Size sz2)
```


ある [Size](../../com.aspose.drawing/size) 構造体の幅と高さを、別の [Size](../../com.aspose.drawing/size) 構造体の幅と高さから減算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 減算演算子の左側にある [Size](../../com.aspose.drawing/size) 構造体。 |
| sz2 | [Size](../../com.aspose.drawing/size) | 減算演算子の右側にある [Size](../../com.aspose.drawing/size) 構造体。 |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) that is a result of the subtraction operation.
### truncate(SizeF value) {#truncate-com.aspose.drawing.SizeF-}
```
public static Size truncate(SizeF value)
```


指定された [SizeF](../../com.aspose.drawing/sizef) 構造体を、[SizeF](../../com.aspose.drawing/sizef) 構造体の値を次の整数に切り捨てて、[Size](../../com.aspose.drawing/size) 構造体に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | The [SizeF](../../com.aspose.drawing/sizef) structure to convert. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### round(SizeF value) {#round-com.aspose.drawing.SizeF-}
```
public static Size round(SizeF value)
```


指定された [SizeF](../../com.aspose.drawing/sizef) 構造体を、[SizeF](../../com.aspose.drawing/sizef) 構造体の値を最も近い整数に丸めて、[Size](../../com.aspose.drawing/size) 構造体に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | The [SizeF](../../com.aspose.drawing/sizef) structure to convert. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.drawing/size) |  |
| obj2 | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
boolean
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


この [Size](../../com.aspose.drawing/size) の幅と高さが 0 であるかどうかを示す値を取得します。

**Returns:**
boolean - a value indicating whether this [Size](../../com.aspose.drawing/size) has width and height of 0.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


この [Size](../../com.aspose.drawing/size) の水平方向のコンポーネントを取得します。

**Returns:**
int - the horizontal component of this [Size](../../com.aspose.drawing/size).
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


この [Size](../../com.aspose.drawing/size) の水平方向のコンポーネントを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int | the horizontal component of this [Size](../../com.aspose.drawing/size). |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


この [Size](../../com.aspose.drawing/size) の垂直方向のコンポーネントを取得します。

**Returns:**
int - the vertical component of this [Size](../../com.aspose.drawing/size).
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


この [Size](../../com.aspose.drawing/size) の垂直方向のコンポーネントを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int | the vertical component of this [Size](../../com.aspose.drawing/size). |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトが、この [Size](../../com.aspose.drawing/size) と同じ寸法の [Size](../../com.aspose.drawing/size) かどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | The Object to test. |

**Returns:**
boolean - true if `obj` is a [Size](../../com.aspose.drawing/size) and has the same width and height as this [Size](../../com.aspose.drawing/size); otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


この [Size](../../com.aspose.drawing/size) 構造体のハッシュコードを返します。

**Returns:**
int - An integer value that specifies a hash value for this [Size](../../com.aspose.drawing/size) structure.
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


他の [Size](../../com.aspose.drawing/size) 構造体が、この [Size](../../com.aspose.drawing/size) 構造体と同じサイズかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [Size](../../com.aspose.drawing/size) | Other size to test |

**Returns:**
boolean - This method returns `true` if other [Size](../../com.aspose.drawing/size) structure and its Width and Height properties are equal to the corresponding properties of this [Size](../../com.aspose.drawing/size) structure; otherwise, `false`.
### CloneTo(Size that) {#CloneTo-com.aspose.drawing.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
