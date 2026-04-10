---
title: Point
second_title: Aspose.Drawing for Java API リファレンス
description: 2 次元平面上の点を定義する整数の x および y 座標の順序付きペアを表します。
type: docs
weight: 36
url: /ja/java/com.aspose.drawing/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Point extends Struct<Point> implements System.IEquatable<Point>, Cloneable
```

2 次元平面上の点を定義する整数の x および y 座標の順序付きペアを表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | 指定された座標で [Point](../../com.aspose.drawing/point) 構造体の新しいインスタンスを初期化します。 |
| [Point(Size sz)](#Point-com.aspose.drawing.Size-) |  |
| [Point(int dw)](#Point-int-) | 整数値で指定された座標を使用して [Point](../../com.aspose.drawing/point) 構造体の新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [EMPTY](#EMPTY) | `Point.X` と `Point.Y` の値がゼロに設定された [Point](../../com.aspose.drawing/point) を表します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [to_PointF(Point p)](#to-PointF-com.aspose.drawing.Point-) | 指定された [Point](../../com.aspose.drawing/point) 構造体を [PointF](../../com.aspose.drawing/pointf) 構造体に変換します。 |
| [to_Size(Point p)](#to-Size-com.aspose.drawing.Point-) |  |
| [op_Addition(Point pt, Size sz)](#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Subtraction(Point pt, Size sz)](#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Equality(Point left, Point right)](#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | 2 つの [Point](../../com.aspose.drawing/point) オブジェクトを比較します。 |
| [op_Inequality(Point left, Point right)](#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | 2 つの [Point](../../com.aspose.drawing/point) オブジェクトを比較します。 |
| [add(Point pt, Size sz)](#add-com.aspose.drawing.Point-com.aspose.drawing.Size-) | 指定された [Size](../../com.aspose.drawing/size) を指定された [Point](../../com.aspose.drawing/point) に加算します。 |
| [subtract(Point pt, Size sz)](#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [ceiling(PointF value)](#ceiling-com.aspose.drawing.PointF-) |  |
| [truncate(PointF value)](#truncate-com.aspose.drawing.PointF-) | すべての座標に対して切り捨て操作を行い、PointF を Point に変換します。 |
| [round(PointF value)](#round-com.aspose.drawing.PointF-) | 指定された [PointF](../../com.aspose.drawing/pointf) を、[Point](../../com.aspose.drawing/point) の値を最も近い整数に丸めて Point オブジェクトに変換します。 |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-) |  |
| [getEmpty()](#getEmpty--) |  |
| [getX()](#getX--) | この Point の X 座標を取得します。 |
| [setX(int value)](#setX-int-) | この Point の X 座標を設定します。 |
| [getY()](#getY--) | この Point の Y 座標を取得します。 |
| [setY(int value)](#setY-int-) | この Point の Y 座標を設定します。 |
| [isEmpty()](#isEmpty--) | この [Point](../../com.aspose.drawing/point) が空かどうかを示す値を取得します。 |
| [hashCode()](#hashCode--) | この [Point](../../com.aspose.drawing/point) のハッシュコードを返します。 |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | この [Point](../../com.aspose.drawing/point) が指定されたオブジェクトと同じ座標を含むかどうかを指定します。 |
| [offset(int dx, int dy)](#offset-int-int-) | 指定された量だけこの [Point](../../com.aspose.drawing/point) を平行移動します。 |
| [offset(Point p)](#offset-com.aspose.drawing.Point-) | 指定された [Point](../../com.aspose.drawing/point) だけこの [Point](../../com.aspose.drawing/point) を平行移動します。 |
| [equals(Point other)](#equals-com.aspose.drawing.Point-) | 他の [Point](../../com.aspose.drawing/point) 構造体がこの [Point](../../com.aspose.drawing/point) 構造体と同じ位置かどうかをテストします。 |
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


指定された座標で [Point](../../com.aspose.drawing/point) 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | ポイントの水平位置。 |
| y | int | ポイントの垂直位置。 |

### Point(Size sz) {#Point-com.aspose.drawing.Size-}
```
public Point(Size sz)
```


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sz | [Size](../../com.aspose.drawing/size) |  |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


整数値で指定された座標を使用して [Point](../../com.aspose.drawing/point) 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dw | int | 整数値です。 |

### EMPTY {#EMPTY}
```
public static final Point EMPTY
```


`Point.X` と `Point.Y` の値がゼロに設定された [Point](../../com.aspose.drawing/point) を表します。

### to_PointF(Point p) {#to-PointF-com.aspose.drawing.Point-}
```
public static PointF to_PointF(Point p)
```


指定された [Point](../../com.aspose.drawing/point) 構造体を [PointF](../../com.aspose.drawing/pointf) 構造体に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | 変換する [Point](../../com.aspose.drawing/point) です。 |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The [PointF](../../com.aspose.drawing/pointf) that results from the conversion.
### to_Size(Point p) {#to-Size-com.aspose.drawing.Point-}
```
public static Size to_Size(Point p)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
[Size](../../com.aspose.drawing/size)
### op_Addition(Point pt, Size sz) {#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Addition(Point pt, Size sz)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Equality(Point left, Point right) {#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Equality(Point left, Point right)
```


2つの[Point](../../com.aspose.drawing/point)オブジェクトを比較します。結果は、2つの[Point](../../com.aspose.drawing/point)オブジェクトの`Point.X`および`Point.Y`プロパティの値が等しいかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | 比較する最初の[Point](../../com.aspose.drawing/point)。 |
| right | [Point](../../com.aspose.drawing/point) | 比較する2番目の[Point](../../com.aspose.drawing/point)。 |

**Returns:**
boolean - `left` と `right` の `Point.X` および `Point.Y` の値が等しい場合は true、そうでなければ false。
### op_Inequality(Point left, Point right) {#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Inequality(Point left, Point right)
```


2つの[Point](../../com.aspose.drawing/point)オブジェクトを比較します。結果は、2つの[Point](../../com.aspose.drawing/point)オブジェクトの`Point.X`または`Point.Y`プロパティの値が等しくないかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | 比較する最初の[Point](../../com.aspose.drawing/point)。 |
| right | [Point](../../com.aspose.drawing/point) | 比較する2番目の[Point](../../com.aspose.drawing/point)。 |

**Returns:**
boolean - `left` と `right` の `Point.X` プロパティまたは `Point.Y` プロパティのいずれかの値が異なる場合は true、そうでなければ false。
### add(Point pt, Size sz) {#add-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point add(Point pt, Size sz)
```


指定された [Size](../../com.aspose.drawing/size) を指定された [Point](../../com.aspose.drawing/point) に加算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | 追加する[Point](../../com.aspose.drawing/point)。 |
| sz | [Size](../../com.aspose.drawing/size) | 追加する[Size](../../com.aspose.drawing/size) |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the addition operation.
### subtract(Point pt, Size sz) {#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point subtract(Point pt, Size sz)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### truncate(PointF value) {#truncate-com.aspose.drawing.PointF-}
```
public static Point truncate(PointF value)
```


すべての座標に対して切り捨て操作を行い、PointF を Point に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | 切り捨てる[PointF](../../com.aspose.drawing/pointf)。 |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the truncate operation.
### round(PointF value) {#round-com.aspose.drawing.PointF-}
```
public static Point round(PointF value)
```


指定された [PointF](../../com.aspose.drawing/pointf) を、[Point](../../com.aspose.drawing/point) の値を最も近い整数に丸めて Point オブジェクトに変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | 変換する[PointF](../../com.aspose.drawing/pointf)。 |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) this method converts to.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.drawing/point) |  |
| obj2 | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
boolean
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


この Point の X 座標を取得します。

**Returns:**
int - この Point の x 座標。
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


この Point の X 座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int | この Point の x 座標。 |

### getY() {#getY--}
```
public final int getY()
```


この Point の Y 座標を取得します。

**Returns:**
int - この Point の y 座標。
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


この Point の Y 座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int | この Point の y 座標。 |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


この [Point](../../com.aspose.drawing/point) が空かどうかを示す値を取得します。

値: X と Y の両方が 0 の場合は `true`、それ以外は `false`。

**Returns:**
boolean - この[Point](../../com.aspose.drawing/point)が空であるかどうかを示す値。
### hashCode() {#hashCode--}
```
public int hashCode()
```


この [Point](../../com.aspose.drawing/point) のハッシュコードを返します。

**Returns:**
int - この[Point](../../com.aspose.drawing/point)のハッシュ値を指定する整数値。
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


この [Point](../../com.aspose.drawing/point) が指定されたオブジェクトと同じ座標を含むかどうかを指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | The Object to test. |

**Returns:**
boolean - `obj` が Point であり、この[Point](../../com.aspose.drawing/point)と同じ座標を持つ場合は `true`。
### offset(int dx, int dy) {#offset-int-int-}
```
public final void offset(int dx, int dy)
```


指定された量だけこの [Point](../../com.aspose.drawing/point) を平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | int | x 座標をオフセットする量。 |
| dy | int | y 座標をオフセットする量。 |

### offset(Point p) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point p)
```


指定された [Point](../../com.aspose.drawing/point) だけこの [Point](../../com.aspose.drawing/point) を平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | この[Point](../../com.aspose.drawing/point)をオフセットするために使用される[Point](../../com.aspose.drawing/point)。 |

### equals(Point other) {#equals-com.aspose.drawing.Point-}
```
public final boolean equals(Point other)
```


他の [Point](../../com.aspose.drawing/point) 構造体がこの [Point](../../com.aspose.drawing/point) 構造体と同じ位置かどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [Point](../../com.aspose.drawing/point) | テストする他のポイント |

**Returns:**
boolean - 他の[Point](../../com.aspose.drawing/point)構造体とその X および Y プロパティが、この[Point](../../com.aspose.drawing/point)構造体の対応するプロパティと等しい場合は `true` を返し、そうでなければ `false` を返します。
### CloneTo(Point that) {#CloneTo-com.aspose.drawing.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
