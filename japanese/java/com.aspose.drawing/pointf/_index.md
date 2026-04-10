---
title: PointF
second_title: Aspose.Drawing for Java API リファレンス
description: 2 次元平面上の点を定義する浮動小数点の x および y 座標の順序付きペアを表します。
type: docs
weight: 37
url: /ja/java/com.aspose.drawing/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class PointF extends Struct<PointF> implements System.IEquatable<PointF>, Cloneable
```

2 次元平面上の点を定義する浮動小数点の x および y 座標の順序付きペアを表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | 指定された座標で PointF 構造体の新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [op_Addition(PointF pt, Size sz)](#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [op_Subtraction(PointF pt, Size sz)](#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [op_Addition(PointF pt, SizeF sz)](#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [op_Subtraction(PointF pt, SizeF sz)](#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [op_Equality(PointF left, PointF right)](#op-Equality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | 2 つの [PointF](../../com.aspose.drawing/pointf) 構造体を比較します。 |
| [op_Inequality(PointF left, PointF right)](#op-Inequality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | 指定されたポイントの座標が等しくないかどうかを判定します。 |
| [add(PointF orig, Size size)](#add-com.aspose.drawing.PointF-com.aspose.drawing.Size-) | 指定された [SizeF](../../com.aspose.drawing/sizef) によって、指定された [PointF](../../com.aspose.drawing/pointf) を平行移動します。 |
| [subtract(PointF pt, Size sz)](#subtract-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [add(PointF orig, SizeF sizeF)](#add-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | 指定された [SizeF](../../com.aspose.drawing/sizef) によって、指定された [PointF](../../com.aspose.drawing/pointf) を平行移動します。 |
| [subtract(PointF pt, SizeF sz)](#subtract-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | この [PointF](../../com.aspose.drawing/pointf) が空かどうかを示す値を取得します。 |
| [getX()](#getX--) | この PointF の X 座標を取得します。 |
| [setX(float value)](#setX-float-) | この PointF の X 座標を設定します。 |
| [getY()](#getY--) | この PointF の Y 座標を取得します。 |
| [setY(float value)](#setY-float-) | この PointF の Y 座標を設定します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | この [PointF](../../com.aspose.drawing/pointf) が指定されたオブジェクトと同じ座標を含むかどうかを指定します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [toString()](#toString--) |  |
| [equals(PointF other)](#equals-com.aspose.drawing.PointF-) | 他の [PointF](../../com.aspose.drawing/pointf) 構造体がこの [PointF](../../com.aspose.drawing/pointf) 構造体と同じ位置かどうかをテストします。 |
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


指定された座標で PointF 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | ポイントの水平位置。 |
| y | float | ポイントの垂直位置。 |

### op_Addition(PointF pt, Size sz) {#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF op_Addition(PointF pt, Size sz)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Equality(PointF left, PointF right) {#op-Equality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean op_Equality(PointF left, PointF right)
```


2 つの [PointF](../../com.aspose.drawing/pointf) 構造体を比較します。結果は、2 つの [PointF](../../com.aspose.drawing/pointf) 構造体の `PointF.X` および `PointF.Y` プロパティの値が等しいかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [PointF](../../com.aspose.drawing/pointf) | 比較する最初の [PointF](../../com.aspose.drawing/pointf)。 |
| right | [PointF](../../com.aspose.drawing/pointf) | 比較する 2 番目の [PointF](../../com.aspose.drawing/pointf)。 |

**Returns:**
boolean - 左右の [PointF](../../com.aspose.drawing/pointf) 構造体の `PointF.X` と `PointF.Y` の値が等しい場合は true、そうでない場合は false。
### op_Inequality(PointF left, PointF right) {#op-Inequality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean op_Inequality(PointF left, PointF right)
```


指定されたポイントの座標が等しくないかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [PointF](../../com.aspose.drawing/pointf) | 比較する最初の [PointF](../../com.aspose.drawing/pointf)。 |
| right | [PointF](../../com.aspose.drawing/pointf) | 比較する 2 番目の [PointF](../../com.aspose.drawing/pointf)。 |

**Returns:**
boolean - `left` と `right` の `PointF.X` と `PointF.Y` の値が等しくないことを示す場合は true、そうでない場合は false。
### add(PointF orig, Size size) {#add-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF add(PointF orig, Size size)
```


指定された [SizeF](../../com.aspose.drawing/sizef) によって、指定された [PointF](../../com.aspose.drawing/pointf) を平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| orig | [PointF](../../com.aspose.drawing/pointf) | 平行移動する [PointF](../../com.aspose.drawing/pointf)。 |
| size | [Size](../../com.aspose.drawing/size) | `orig` の座標に加える数値を指定する [Size](../../com.aspose.drawing/size)。 |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The translated [PointF](../../com.aspose.drawing/pointf).
### subtract(PointF pt, Size sz) {#subtract-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF subtract(PointF pt, Size sz)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### add(PointF orig, SizeF sizeF) {#add-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF add(PointF orig, SizeF sizeF)
```


指定された [SizeF](../../com.aspose.drawing/sizef) によって、指定された [PointF](../../com.aspose.drawing/pointf) を平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| orig | [PointF](../../com.aspose.drawing/pointf) | 平行移動する [PointF](../../com.aspose.drawing/pointf)。 |
| sizeF | [SizeF](../../com.aspose.drawing/sizef) | `orig` の座標に加える数値を指定する [SizeF](../../com.aspose.drawing/sizef)。 |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The translated [PointF](../../com.aspose.drawing/pointf).
### subtract(PointF pt, SizeF sz) {#subtract-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF subtract(PointF pt, SizeF sz)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.drawing/pointf) |  |
| obj2 | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
boolean
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


この [PointF](../../com.aspose.drawing/pointf) が空かどうかを示す値を取得します。

**Returns:**
boolean - この [PointF](../../com.aspose.drawing/pointf) が空かどうかを示す値。
### getX() {#getX--}
```
public final float getX()
```


この PointF の X 座標を取得します。

**Returns:**
float - この PointF の X 座標。
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


この PointF の X 座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この PointF の X 座標。 |

### getY() {#getY--}
```
public final float getY()
```


この PointF の Y 座標を取得します。

**Returns:**
float - この PointF の Y 座標。
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


この PointF の Y 座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この PointF の Y 座標。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


この [PointF](../../com.aspose.drawing/pointf) が指定されたオブジェクトと同じ座標を含むかどうかを指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | The Object to test. |

**Returns:**
boolean - `obj` が [PointF](../../com.aspose.drawing/pointf) であり、この [Point](../../com.aspose.drawing/point) と同じ座標を持つ場合に true を返します。
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - ハッシュテーブルなどのハッシュアルゴリズムやデータ構造で使用できる、このインスタンスのハッシュコード。
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


他の [PointF](../../com.aspose.drawing/pointf) 構造体がこの [PointF](../../com.aspose.drawing/pointf) 構造体と同じ位置かどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [PointF](../../com.aspose.drawing/pointf) | テストする他のポイント |

**Returns:**
boolean - 他の [PointF](../../com.aspose.drawing/pointf) 構造体とその X および Y プロパティがこの [PointF](../../com.aspose.drawing/pointf) 構造体の対応するプロパティと等しい場合は `true` を返し、そうでない場合は `false` を返します。
### CloneTo(PointF that) {#CloneTo-com.aspose.drawing.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
