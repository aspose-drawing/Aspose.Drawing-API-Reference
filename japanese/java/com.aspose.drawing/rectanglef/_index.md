---
title: RectangleF
second_title: Aspose.Drawing for Java API リファレンス
description: 矩形の位置とサイズを表す 4 つの浮動小数点数のセットを格納します。
type: docs
weight: 39
url: /ja/java/com.aspose.drawing/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class RectangleF extends Struct<RectangleF> implements System.IEquatable<RectangleF>, Cloneable
```

矩形の位置とサイズを表す 4 つの浮動小数点数のセットを格納します。より高度な領域機能を使用する場合は、Region オブジェクトを使用してください。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | 指定された位置とサイズで RectangleF 構造体の新しいインスタンスを初期化します。 |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | 指定された位置とサイズで RectangleF 構造体の新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | 2 つの点から新しい矩形を作成します。 |
| [to_RectangleF(Rectangle r)](#to-RectangleF-com.aspose.drawing.Rectangle-) | 指定された Rectangle 構造体を RectangleF 構造体に変換します。 |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | 2 つの [RectangleF](../../com.aspose.drawing/rectanglef) 構造体が位置とサイズが等しいかどうかをテストします。 |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | 2 つの [RectangleF](../../com.aspose.drawing/rectanglef) 構造体が位置またはサイズが異なるかどうかをテストします。 |
| [fromLTRB(float left, float top, float right, float bottom)](#fromLTRB-float-float-float-float-) | 指定された位置に左上隅と右下隅を持つ RectangleF 構造体を作成します。 |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.drawing.RectangleF-float-float-) | 指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体の拡張コピーを作成して返します。 |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | 2 つの矩形の交差部分を表す [RectangleF](../../com.aspose.drawing/rectanglef) 構造体を返します。 |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | 結合を形成する 2 つの矩形の両方を包含できる、可能な限り最小の第 3 の矩形を作成します。 |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | この [RectangleF](../../com.aspose.drawing/rectanglef) の `RectangleF.Width` または `RectangleF.Height` プロパティが 0 であるかどうかを示す値を取得します。 |
| [getX()](#getX--) | この RectangleF 構造体の左上隅の X 座標を取得します。 |
| [setX(float value)](#setX-float-) | この RectangleF 構造体の左上隅の X 座標を設定します。 |
| [getY()](#getY--) | この RectangleF 構造体の左上隅の X 座標を取得します。 |
| [setY(float value)](#setY-float-) | この RectangleF 構造体の左上隅の X 座標を設定します。 |
| [getLocation()](#getLocation--) | この [RectangleF](../../com.aspose.drawing/rectanglef) 構造体の左上隅の座標を取得します。 |
| [setLocation(PointF value)](#setLocation-com.aspose.drawing.PointF-) | この [RectangleF](../../com.aspose.drawing/rectanglef) 構造体の左上隅の座標を設定します。 |
| [getWidth()](#getWidth--) | この RectangleF 構造体の幅を取得します。 |
| [setWidth(float value)](#setWidth-float-) | この RectangleF 構造体の幅を設定します。 |
| [getHeight()](#getHeight--) | この RectangleF 構造体の高さを取得します。 |
| [setHeight(float value)](#setHeight-float-) | この RectangleF 構造体の高さを設定します。 |
| [getSize()](#getSize--) | この [RectangleF](../../com.aspose.drawing/rectanglef) のサイズを取得します。 |
| [setSize(SizeF value)](#setSize-com.aspose.drawing.SizeF-) | この [RectangleF](../../com.aspose.drawing/rectanglef) のサイズを設定します。 |
| [getLeft()](#getLeft--) | この RectangleF 構造体の左端の x 座標を取得します。 |
| [getTop()](#getTop--) | この RectangleF 構造体の上端の y 座標を取得します。 |
| [getRight()](#getRight--) | この RectangleF 構造体の X と Width の合計である x 座標を取得します。 |
| [getBottom()](#getBottom--) | この RectangleF 構造体の Y と Height の合計である y 座標を取得します。 |
| [toString()](#toString--) |  |
| [inflate(float x, float y)](#inflate-float-float-) | この [RectangleF](../../com.aspose.drawing/rectanglef) 構造体を指定された量だけ拡大します。 |
| [inflate(SizeF size)](#inflate-com.aspose.drawing.SizeF-) | この [RectangleF](../../com.aspose.drawing/rectanglef) を指定された量だけ拡大します。 |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | この [RectangleF](../../com.aspose.drawing/rectanglef) 構造体を、自己と指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体との交差部分に置き換えます。 |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.drawing.RectangleF-) | `rect` とこの矩形が交差するかどうかを判定します。 |
| [offset(PointF pos)](#offset-com.aspose.drawing.PointF-) | この矩形の位置を指定された量だけ調整します。 |
| [offset(float x, float y)](#offset-float-float-) | この矩形の位置を指定された量だけ調整します。 |
| [contains(float x, float y)](#contains-float-float-) | 指定された点がこの [RectangleF](../../com.aspose.drawing/rectanglef) 構造体に含まれているかどうかを判定します。 |
| [contains(PointF pt)](#contains-com.aspose.drawing.PointF-) | 指定された点がこの [RectangleF](../../com.aspose.drawing/rectanglef) 構造体に含まれているかどうかを判定します。 |
| [contains(RectangleF rect)](#contains-com.aspose.drawing.RectangleF-) | `rect` で表される矩形領域がこの [RectangleF](../../com.aspose.drawing/rectanglef) 構造体に完全に含まれているかどうかを判定します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された Object がこのインスタンスと等しいかどうかを判定します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [equals(RectangleF other)](#equals-com.aspose.drawing.RectangleF-) | 他の [RectangleF](../../com.aspose.drawing/rectanglef) 構造体がこの [RectangleF](../../com.aspose.drawing/rectanglef) 構造体と同じ位置とサイズを持つかどうかをテストします。 |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.drawing.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


指定された位置とサイズで RectangleF 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| location | [PointF](../../com.aspose.drawing/pointf) | 矩形領域の左上隅を表す PointF。 |
| size | [SizeF](../../com.aspose.drawing/sizef) | 矩形領域の幅と高さを表す SizeF。 |

### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


指定された位置とサイズで RectangleF 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 矩形の左上隅の x 座標。 |
| y | float | 矩形の左上隅の y 座標です。 |
| 幅 | float | 矩形の幅です。 |
| 高さ | float | 矩形の高さです。 |

### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


2 つの点から新しい矩形を作成します。作成された矩形は (left,top) が (right,bottom) より小さいように正規化されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | 最初の点です。 |
| point2 | [PointF](../../com.aspose.drawing/pointf) | 2 番目の点です。 |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A newly created rectangle.
### to_RectangleF(Rectangle r) {#to-RectangleF-com.aspose.drawing.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle r)
```


指定された Rectangle 構造体を RectangleF 構造体に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| r | [Rectangle](../../com.aspose.drawing/rectangle) | 変換する Rectangle 構造体です。 |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The RectangleF structure that is converted from the specified Rectangle structure.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


2 つの [RectangleF](../../com.aspose.drawing/rectanglef) 構造体が位置とサイズが等しいかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | 等価演算子の左側にある [RectangleF](../../com.aspose.drawing/rectanglef) 構造体です。 |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | 等価演算子の右側にある [RectangleF](../../com.aspose.drawing/rectanglef) 構造体です。 |

**Returns:**
boolean - 2 つの指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体の `RectangleF.X`、`RectangleF.Y`、`RectangleF.Width`、`RectangleF.Height` プロパティがすべて等しい場合に true を返します。
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


2 つの [RectangleF](../../com.aspose.drawing/rectanglef) 構造体が位置またはサイズが異なるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | 不等価演算子の左側にある [RectangleF](../../com.aspose.drawing/rectanglef) 構造体です。 |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | 不等価演算子の右側にある [RectangleF](../../com.aspose.drawing/rectanglef) 構造体です。 |

**Returns:**
boolean - 2 つの [Rectangle](../../com.aspose.drawing/rectangle) 構造体の `RectangleF.X`、`RectangleF.Y`、`RectangleF.Width`、`RectangleF.Height` のいずれかのプロパティが等しくない場合に true を返し、そうでなければ false を返します。
### fromLTRB(float left, float top, float right, float bottom) {#fromLTRB-float-float-float-float-}
```
public static RectangleF fromLTRB(float left, float top, float right, float bottom)
```


指定された位置に左上隅と右下隅を持つ RectangleF 構造体を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 左 | float | 矩形領域の左上隅の x 座標です。 |
| 上 | float | 矩形領域の左上隅の y 座標です。 |
| 右 | float | 矩形領域の右下隅の x 座標です。 |
| 下 | float | 矩形領域の右下隅の y 座標です。 |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The new RectangleF that this method creates.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.drawing.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体の膨張したコピーを作成して返します。コピーは指定された量だけ膨張します。元の矩形は変更されません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | コピー対象の [RectangleF](../../com.aspose.drawing/rectanglef) です。この矩形は変更されません。 |
| x | float | 矩形のコピーを水平方向に膨張させる量です。 |
| y | float | 矩形のコピーを垂直方向に拡張する量です。 |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The inflated [RectangleF](../../com.aspose.drawing/rectanglef).
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


2つの矩形の交差を表す [RectangleF](../../com.aspose.drawing/rectanglef) 構造体を返します。交差がない場合は、空の [RectangleF](../../com.aspose.drawing/rectanglef) が返されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | 交差させる最初の矩形です。 |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | 交差させる2番目の矩形です。 |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


結合を形成する 2 つの矩形の両方を包含できる、可能な限り最小の第 3 の矩形を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | 結合する最初の矩形です。 |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | 結合する2番目の矩形です。 |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure that contains both of the two rectangles that form the union.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


この [RectangleF](../../com.aspose.drawing/rectanglef) の `RectangleF.Width` または `RectangleF.Height` プロパティが 0 であるかどうかを示す値を取得します。

**Returns:**
boolean - このプロパティは、この [RectangleF](../../com.aspose.drawing/rectanglef) の `RectangleF.Width` または `P:RectangleF.Height` プロパティの値がゼロの場合に true を返し、そうでない場合は false を返します。
### getX() {#getX--}
```
public final float getX()
```


この RectangleF 構造体の左上隅の X 座標を取得します。

**Returns:**
float - この RectangleF 構造体の左上隅の X 座標です。
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


この RectangleF 構造体の左上隅の X 座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この RectangleF 構造体の左上隅の X 座標です。 |

### getY() {#getY--}
```
public final float getY()
```


この RectangleF 構造体の左上隅の X 座標を取得します。

**Returns:**
float - この RectangleF 構造体の左上隅の X 座標です。
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


この RectangleF 構造体の左上隅の X 座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この RectangleF 構造体の左上隅の X 座標です。 |

### getLocation() {#getLocation--}
```
public final PointF getLocation()
```


この [RectangleF](../../com.aspose.drawing/rectanglef) 構造体の左上隅の座標を取得します。

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - A [PointF](../../com.aspose.drawing/pointf) that represents the upper-left corner of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setLocation(PointF value) {#setLocation-com.aspose.drawing.PointF-}
```
public final void setLocation(PointF value)
```


この [RectangleF](../../com.aspose.drawing/rectanglef) 構造体の左上隅の座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | この [RectangleF](../../com.aspose.drawing/rectanglef) 構造体の左上隅の座標です。 |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


この RectangleF 構造体の幅を取得します。

**Returns:**
float - この RectangleF 構造体の幅です。
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


この RectangleF 構造体の幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この RectangleF 構造体の幅です。 |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


この RectangleF 構造体の高さを取得します。

**Returns:**
float - この RectangleF 構造体の高さです。
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


この RectangleF 構造体の高さを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この RectangleF 構造体の高さです。 |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


この [RectangleF](../../com.aspose.drawing/rectanglef) のサイズを取得します。

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that represents the width and height of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setSize(SizeF value) {#setSize-com.aspose.drawing.SizeF-}
```
public final void setSize(SizeF value)
```


この [RectangleF](../../com.aspose.drawing/rectanglef) のサイズを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | この [RectangleF](../../com.aspose.drawing/rectanglef) のサイズです。 |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


この RectangleF 構造体の左端の x 座標を取得します。

**Returns:**
float - この RectangleF 構造体の左端の X 座標です。
### getTop() {#getTop--}
```
public final float getTop()
```


この RectangleF 構造体の上端の y 座標を取得します。

**Returns:**
float - この RectangleF 構造体の上端の Y 座標です。
### getRight() {#getRight--}
```
public final float getRight()
```


この RectangleF 構造体の X と Width の合計である x 座標を取得します。

**Returns:**
float - この RectangleF 構造体の X と Width の合計となる X 座標です。
### getBottom() {#getBottom--}
```
public final float getBottom()
```


この RectangleF 構造体の Y と Height の合計である y 座標を取得します。

**Returns:**
float - この RectangleF 構造体の Y と Height の合計となる Y 座標です。
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### inflate(float x, float y) {#inflate-float-float-}
```
public final void inflate(float x, float y)
```


この [RectangleF](../../com.aspose.drawing/rectanglef) 構造体を指定された量だけ拡大します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | この [RectangleF](../../com.aspose.drawing/rectanglef) 構造体を水平方向に拡張する量です。 |
| y | float | この [RectangleF](../../com.aspose.drawing/rectanglef) 構造体を垂直方向に拡張する量です。 |

### inflate(SizeF size) {#inflate-com.aspose.drawing.SizeF-}
```
public final void inflate(SizeF size)
```


この [RectangleF](../../com.aspose.drawing/rectanglef) を指定された量だけ拡大します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | この矩形を拡張する量です。 |

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public final void intersect(RectangleF rect)
```


この [RectangleF](../../com.aspose.drawing/rectanglef) 構造体を、自己と指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体との交差部分に置き換えます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 交差させる矩形です。 |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.drawing.RectangleF-}
```
public final boolean intersectsWith(RectangleF rect)
```


`rect` とこの矩形が交差するかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | テストする矩形です。 |

**Returns:**
boolean - 交差がある場合は true を返します。
### offset(PointF pos) {#offset-com.aspose.drawing.PointF-}
```
public final void offset(PointF pos)
```


この矩形の位置を指定された量だけ調整します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.drawing/pointf) | 位置をオフセットする量。 |

### offset(float x, float y) {#offset-float-float-}
```
public final void offset(float x, float y)
```


この矩形の位置を指定された量だけ調整します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 位置を水平方向にオフセットする量。 |
| y | float | 位置を垂直方向にオフセットする量。 |

### contains(float x, float y) {#contains-float-float-}
```
public final boolean contains(float x, float y)
```


指定された点がこの [RectangleF](../../com.aspose.drawing/rectanglef) 構造体に含まれているかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | テスト対象ポイントの x 座標。 |
| y | float | テスト対象ポイントの y 座標。 |

**Returns:**
boolean - このメソッドは、x と y で定義された点がこの [RectangleF](../../com.aspose.drawing/rectanglef) 構造体に含まれている場合は `true` を返し、そうでない場合は `false` を返します。
### contains(PointF pt) {#contains-com.aspose.drawing.PointF-}
```
public final boolean contains(PointF pt)
```


指定された点がこの [RectangleF](../../com.aspose.drawing/rectanglef) 構造体に含まれているかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | テスト対象の [PointF](../../com.aspose.drawing/pointf)。 |

**Returns:**
boolean - このメソッドは、pt パラメータで表される点がこの [RectangleF](../../com.aspose.drawing/rectanglef) 構造体に含まれている場合は `true` を返し、そうでない場合は `false` を返します。
### contains(RectangleF rect) {#contains-com.aspose.drawing.RectangleF-}
```
public final boolean contains(RectangleF rect)
```


`rect` で表される矩形領域がこの [RectangleF](../../com.aspose.drawing/rectanglef) 構造体に完全に含まれているかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | テスト対象の [RectangleF](../../com.aspose.drawing/rectanglef)。 |

**Returns:**
boolean - このメソッドは、`rect` で表される矩形領域がこの [RectangleF](../../com.aspose.drawing/rectanglef) で表される矩形領域に完全に含まれている場合は `true` を返し、そうでない場合は `false` を返します。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定された Object がこのインスタンスと等しいかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較する Object。 |

**Returns:**
boolean - 指定された Object がこのインスタンスと等しい場合は `true`、それ以外は `false`。
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - ハッシュテーブルなどのハッシュアルゴリズムやデータ構造で使用できる、このインスタンスのハッシュコード。
### equals(RectangleF other) {#equals-com.aspose.drawing.RectangleF-}
```
public final boolean equals(RectangleF other)
```


他の [RectangleF](../../com.aspose.drawing/rectanglef) 構造体がこの [RectangleF](../../com.aspose.drawing/rectanglef) 構造体と同じ位置とサイズを持つかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [RectangleF](../../com.aspose.drawing/rectanglef) | テスト対象の他の矩形 |

**Returns:**
boolean - このメソッドは、他の [RectangleF](../../com.aspose.drawing/rectanglef) 構造体とその X、Y、Width、Height プロパティがこの [RectangleF](../../com.aspose.drawing/rectanglef) 構造体の対応するプロパティと等しい場合は `true` を返し、そうでない場合は `false` を返します。
### CloneTo(RectangleF that) {#CloneTo-com.aspose.drawing.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
