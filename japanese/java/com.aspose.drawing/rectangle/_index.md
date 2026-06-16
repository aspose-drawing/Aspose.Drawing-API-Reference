---
title: Rectangle
second_title: Aspose.Drawing for Java API リファレンス
description: 矩形の位置とサイズを表す 4 つの整数のセットを格納します。
type: docs
weight: 38
url: /ja/java/com.aspose.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Rectangle extends Struct<Rectangle> implements System.IEquatable<Rectangle>, Cloneable
```

矩形の位置とサイズを表す 4 つの整数のセットを格納します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | 指定された位置とサイズで Rectangle 構造体の新しいインスタンスを初期化します。 |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-) | 指定された位置とサイズで [Rectangle](../../com.aspose.drawing/rectangle) 構造体の新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [fromLTRB(int left, int top, int right, int bottom)](#fromLTRB-int-int-int-int-) | 指定されたエッジ位置で [Rectangle](../../com.aspose.drawing/rectangle) 構造体を作成します。 |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | 2 つの他の [Rectangle](../../com.aspose.drawing/rectangle) 構造体の交差を表す 3 番目の [Rectangle](../../com.aspose.drawing/rectangle) 構造体を返します。 |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | 2 つの [Rectangle](../../com.aspose.drawing/rectangle) 構造体が同じ位置とサイズかどうかをテストします。 |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | 2 つの [Rectangle](../../com.aspose.drawing/rectangle) 構造体が位置またはサイズが異なるかどうかをテストします。 |
| [ceiling(RectangleF value)](#ceiling-com.aspose.drawing.RectangleF-) | 指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体を、[RectangleF](../../com.aspose.drawing/rectanglef) の値を次の整数に切り上げて [Rectangle](../../com.aspose.drawing/rectangle) 構造体に変換します。 |
| [truncate(RectangleF value)](#truncate-com.aspose.drawing.RectangleF-) | 指定された [RectangleF](../../com.aspose.drawing/rectanglef) を、[RectangleF](../../com.aspose.drawing/rectanglef) の値を切り捨てて [Rectangle](../../com.aspose.drawing/rectangle) に変換します。 |
| [round(RectangleF value)](#round-com.aspose.drawing.RectangleF-) | 指定された [RectangleF](../../com.aspose.drawing/rectanglef) を、[RectangleF](../../com.aspose.drawing/rectanglef) の値を最も近い整数に丸めて [Rectangle](../../com.aspose.drawing/rectangle) に変換します。 |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | 2 つの [Rectangle](../../com.aspose.drawing/rectangle) 構造体の合併を含む [Rectangle](../../com.aspose.drawing/rectangle) 構造体を取得します。 |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.drawing.Rectangle-int-int-) |  |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) |  |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-) | 2 つの点から新しい矩形を作成します。 |
| [getEmpty()](#getEmpty--) | `Rectangle.X`、`Rectangle.Y`、`Rectangle.Width`、`Rectangle.Height` の値がすべて 0 に設定された `Rectangle` 構造体の新しいインスタンスを取得します。 |
| [getX()](#getX--) | この Rectangle 構造体の左上隅の X 座標を取得します。 |
| [setX(int value)](#setX-int-) | この Rectangle 構造体の左上隅の X 座標を設定します。 |
| [getY()](#getY--) | この Rectangle 構造体の左上隅の Y 座標を取得します。 |
| [setY(int value)](#setY-int-) | この Rectangle 構造体の左上隅の Y 座標を設定します。 |
| [getLocation()](#getLocation--) | この [Rectangle](../../com.aspose.drawing/rectangle) 構造体の左上隅の座標を取得します。 |
| [setLocation(Point value)](#setLocation-com.aspose.drawing.Point-) | この [Rectangle](../../com.aspose.drawing/rectangle) 構造体の左上隅の座標を設定します。 |
| [getWidth()](#getWidth--) | この Rectangle 構造体の幅を取得します。 |
| [setWidth(int value)](#setWidth-int-) | この Rectangle 構造体の幅を設定します。 |
| [getHeight()](#getHeight--) | この Rectangle 構造体の高さを取得します。 |
| [setHeight(int value)](#setHeight-int-) | この Rectangle 構造体の高さを設定します。 |
| [getSize()](#getSize--) | この [Rectangle](../../com.aspose.drawing/rectangle) のサイズを取得します。 |
| [setSize(Size value)](#setSize-com.aspose.drawing.Size-) | この [Rectangle](../../com.aspose.drawing/rectangle) のサイズを設定します。 |
| [getLeft()](#getLeft--) | この Rectangle 構造体の左端の x 座標を取得します。 |
| [getTop()](#getTop--) | この Rectangle 構造体の上端の y 座標を取得します。 |
| [getRight()](#getRight--) | この Rectangle 構造体の X と Width プロパティ値の合計である x 座標を取得します。 |
| [getBottom()](#getBottom--) | この Rectangle 構造体の Y と Height プロパティ値の合計である y 座標を取得します。 |
| [isEmpty()](#isEmpty--) | この [Rectangle](../../com.aspose.drawing/rectangle) のすべての数値プロパティがゼロであるかどうかを示す値を取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | obj がこの [Rectangle](../../com.aspose.drawing/rectangle) 構造体と同じ位置とサイズを持つ [Rectangle](../../com.aspose.drawing/rectangle) 構造体かどうかをテストします。 |
| [hashCode()](#hashCode--) | この [Rectangle](../../com.aspose.drawing/rectangle) 構造体のハッシュコードを返します。 |
| [toString()](#toString--) |  |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | この [Rectangle](../../com.aspose.drawing/rectangle) をそれ自身と指定された [Rectangle](../../com.aspose.drawing/rectangle) の交差部分に置き換えます。 |
| [inflate(int width, int height)](#inflate-int-int-) | この [Rectangle](../../com.aspose.drawing/rectangle) を指定された量だけ拡大します。 |
| [inflate(Size size)](#inflate-com.aspose.drawing.Size-) | この [Rectangle](../../com.aspose.drawing/rectangle) を指定された量だけ拡大します。 |
| [contains(int x, int y)](#contains-int-int-) | 指定された点がこの [Rectangle](../../com.aspose.drawing/rectangle) 構造体内に含まれるかどうかを判断します。 |
| [contains(Point pt)](#contains-com.aspose.drawing.Point-) | 指定された点がこの [Rectangle](../../com.aspose.drawing/rectangle) 構造体内に含まれるかどうかを判断します。 |
| [contains(Rectangle rect)](#contains-com.aspose.drawing.Rectangle-) |  |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.drawing.Rectangle-) | `rect` とこの矩形が交差するかどうかを判定します。 |
| [offset(int x, int y)](#offset-int-int-) | この矩形の位置を指定された量だけ調整します。 |
| [offset(Point pos)](#offset-com.aspose.drawing.Point-) | この矩形の位置を指定された量だけ調整します。 |
| [equals(Rectangle other)](#equals-com.aspose.drawing.Rectangle-) | 他の [Rectangle](../../com.aspose.drawing/rectangle) 構造体がこの [Rectangle](../../com.aspose.drawing/rectangle) 構造体と同じ位置とサイズを持つかどうかをテストします。 |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.drawing.Rectangle-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [normalize()](#normalize--) | 矩形の幅と高さを正にし、左が右より小さく、上が下より小さくなるように正規化します。 |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


指定された位置とサイズで Rectangle 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | 矩形の左上隅の x 座標。 |
| y | int | 矩形の左上隅の y 座標です。 |
| 幅 | int | 矩形の幅です。 |
| 高さ | int | 矩形の高さです。 |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public Rectangle(Point location, Size size)
```


指定された位置とサイズで [Rectangle](../../com.aspose.drawing/rectangle) 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| location | [Point](../../com.aspose.drawing/point) | 矩形領域の左上隅を表す [Point](../../com.aspose.drawing/point)。 |
| size | [Size](../../com.aspose.drawing/size) | `Size`([.getSize](../../null/\#getSize)/[.setSize(Size)](../../null/\#setSize-Size-)) は矩形領域の幅と高さを表します。 |

### fromLTRB(int left, int top, int right, int bottom) {#fromLTRB-int-int-int-int-}
```
public static Rectangle fromLTRB(int left, int top, int right, int bottom)
```


指定されたエッジ位置で [Rectangle](../../com.aspose.drawing/rectangle) 構造体を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | int | この [Rectangle](../../com.aspose.drawing/rectangle) 構造体の左上隅の x 座標。 |
| top | int | この [Rectangle](../../com.aspose.drawing/rectangle) 構造体の左上隅の y 座標。 |
| right | int | この [Rectangle](../../com.aspose.drawing/rectangle) 構造体の右下隅の x 座標。 |
| bottom | int | この [Rectangle](../../com.aspose.drawing/rectangle) 構造体の右下隅の y 座標。 |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The new [Rectangle](../../com.aspose.drawing/rectangle) that this method creates.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


2つの他の[Rectangle](../../com.aspose.drawing/rectangle)構造体の交差を表す、3番目の[Rectangle](../../com.aspose.drawing/rectangle)構造体を返します。交差がない場合は、空の[Rectangle](../../com.aspose.drawing/rectangle)が返されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | 交差させる最初の矩形です。 |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | 交差させる2番目の矩形です。 |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the intersection of `a` and `b`.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


2 つの [Rectangle](../../com.aspose.drawing/rectangle) 構造体が同じ位置とサイズかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | 等価演算子の左側にある[Rectangle](../../com.aspose.drawing/rectangle)構造体です。 |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | 等価演算子の右側にある[Rectangle](../../com.aspose.drawing/rectangle)構造体です。 |

**Returns:**
boolean - 2つの[Rectangle](../../com.aspose.drawing/rectangle)構造体の X、Y、Width、Height プロパティが等しい場合、この演算子は `true` を返します。
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


2 つの [Rectangle](../../com.aspose.drawing/rectangle) 構造体が位置またはサイズが異なるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | 不等価演算子の左側にある[Rectangle](../../com.aspose.drawing/rectangle)構造体です。 |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | 不等価演算子の右側にある[Rectangle](../../com.aspose.drawing/rectangle)構造体です。 |

**Returns:**
boolean - 2つの[Rectangle](../../com.aspose.drawing/rectangle)構造体の X、Y、Width、Height のいずれかのプロパティが等しくない場合、この演算子は `true` を返し、そうでなければ `false` を返します。
### ceiling(RectangleF value) {#ceiling-com.aspose.drawing.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体を、[RectangleF](../../com.aspose.drawing/rectanglef) の値を次の整数に切り上げて [Rectangle](../../com.aspose.drawing/rectangle) 構造体に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | 変換対象の[RectangleF](../../com.aspose.drawing/rectanglef)構造体です。 |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - Returns a [Rectangle](../../com.aspose.drawing/rectangle).
### truncate(RectangleF value) {#truncate-com.aspose.drawing.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


指定された [RectangleF](../../com.aspose.drawing/rectanglef) を、[RectangleF](../../com.aspose.drawing/rectanglef) の値を切り捨てて [Rectangle](../../com.aspose.drawing/rectangle) に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | 変換対象の[RectangleF](../../com.aspose.drawing/rectanglef)です。 |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The truncated value of the [Rectangle](../../com.aspose.drawing/rectangle).
### round(RectangleF value) {#round-com.aspose.drawing.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


指定された [RectangleF](../../com.aspose.drawing/rectanglef) を、[RectangleF](../../com.aspose.drawing/rectanglef) の値を最も近い整数に丸めて [Rectangle](../../com.aspose.drawing/rectangle) に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | 変換対象の[RectangleF](../../com.aspose.drawing/rectanglef)です。 |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle).
### union(Rectangle a, Rectangle b) {#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


2 つの [Rectangle](../../com.aspose.drawing/rectangle) 構造体の合併を含む [Rectangle](../../com.aspose.drawing/rectangle) 構造体を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | 結合する最初の矩形です。 |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | 結合する2番目の矩形です。 |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) structure that bounds the union of the two [Rectangle](../../com.aspose.drawing/rectangle) structures.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.drawing.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| x | int |  |
| y | int |  |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


2 つの点から新しい矩形を作成します。作成された矩形は (left,top) が (right,bottom) より小さいように正規化されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | 最初の点です。 |
| point2 | [Point](../../com.aspose.drawing/point) | 2 番目の点です。 |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A newly created rectangle.
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


`Rectangle.X`、`Rectangle.Y`、`Rectangle.Width`、`Rectangle.Height` の値がすべて 0 に設定された `Rectangle` 構造体の新しいインスタンスを取得します。

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### getX() {#getX--}
```
public final int getX()
```


この Rectangle 構造体の左上隅の X 座標を取得します。

**Returns:**
int - このRectangle構造体の左上隅の x 座標です。
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


この Rectangle 構造体の左上隅の X 座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int | このRectangle構造体の左上隅の x 座標です。 |

### getY() {#getY--}
```
public final int getY()
```


この Rectangle 構造体の左上隅の Y 座標を取得します。

**Returns:**
int - このRectangle構造体の左上隅の y 座標です。
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


この Rectangle 構造体の左上隅の Y 座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int | このRectangle構造体の左上隅の y 座標です。 |

### getLocation() {#getLocation--}
```
public final Point getLocation()
```


この [Rectangle](../../com.aspose.drawing/rectangle) 構造体の左上隅の座標を取得します。

**Returns:**
[Point](../../com.aspose.drawing/point) - the coordinates of the upper-left corner of this [Rectangle](../../com.aspose.drawing/rectangle) structure.
### setLocation(Point value) {#setLocation-com.aspose.drawing.Point-}
```
public final void setLocation(Point value)
```


この [Rectangle](../../com.aspose.drawing/rectangle) 構造体の左上隅の座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Point](../../com.aspose.drawing/point) | この[Rectangle](../../com.aspose.drawing/rectangle)構造体の左上隅の座標です。 |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


この Rectangle 構造体の幅を取得します。

**Returns:**
int - このRectangle構造体の幅です。
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


この Rectangle 構造体の幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int | このRectangle構造体の幅です。 |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


この Rectangle 構造体の高さを取得します。

**Returns:**
int - このRectangle構造体の高さです。
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


この Rectangle 構造体の高さを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int | このRectangle構造体の高さです。 |

### getSize() {#getSize--}
```
public final Size getSize()
```


この [Rectangle](../../com.aspose.drawing/rectangle) のサイズを取得します。

**Returns:**
[Size](../../com.aspose.drawing/size) - the size of this [Rectangle](../../com.aspose.drawing/rectangle).
### setSize(Size value) {#setSize-com.aspose.drawing.Size-}
```
public final void setSize(Size value)
```


この [Rectangle](../../com.aspose.drawing/rectangle) のサイズを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Size](../../com.aspose.drawing/size) | この[Rectangle](../../com.aspose.drawing/rectangle)のサイズです。 |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


この Rectangle 構造体の左端の x 座標を取得します。

**Returns:**
int - このRectangle構造体の左端の x 座標です。
### getTop() {#getTop--}
```
public final int getTop()
```


この Rectangle 構造体の上端の y 座標を取得します。

**Returns:**
int - このRectangle構造体の上端の y 座標です。
### getRight() {#getRight--}
```
public final int getRight()
```


この Rectangle 構造体の X と Width プロパティ値の合計である x 座標を取得します。

**Returns:**
int - このRectangle構造体の X と Width プロパティ値の合計である x 座標です。
### getBottom() {#getBottom--}
```
public final int getBottom()
```


この Rectangle 構造体の Y と Height プロパティ値の合計である y 座標を取得します。

**Returns:**
int - このRectangle構造体の Y と Height プロパティ値の合計である y 座標です。
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


この [Rectangle](../../com.aspose.drawing/rectangle) のすべての数値プロパティがゼロであるかどうかを示す値を取得します。

**Returns:**
boolean - このプロパティは、この [Rectangle](../../com.aspose.drawing/rectangle) の `Rectangle.Width`、`Rectangle.Height`、`Rectangle.X`、`Rectangle.Y` プロパティがすべてゼロの値である場合に `true` を返し、そうでない場合は `false` を返します。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


obj がこの [Rectangle](../../com.aspose.drawing/rectangle) 構造体と同じ位置とサイズを持つ [Rectangle](../../com.aspose.drawing/rectangle) 構造体かどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | The Object to test. |

**Returns:**
boolean - このメソッドは、obj が [Rectangle](../../com.aspose.drawing/rectangle) 構造体であり、その X、Y、Width、Height プロパティがこの [Rectangle](../../com.aspose.drawing/rectangle) 構造体の対応するプロパティと等しい場合に `true` を返し、そうでない場合は `false` を返します。
### hashCode() {#hashCode--}
```
public int hashCode()
```


この [Rectangle](../../com.aspose.drawing/rectangle) 構造体のハッシュコードを返します。ハッシュコードの使用に関する情報については、GetHashCode を参照してください。

**Returns:**
int - この矩形のハッシュコードを表す整数です。
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public final void intersect(Rectangle rect)
```


この [Rectangle](../../com.aspose.drawing/rectangle) をそれ自身と指定された [Rectangle](../../com.aspose.drawing/rectangle) の交差部分に置き換えます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 交差させる対象の [Rectangle](../../com.aspose.drawing/rectangle)。 |

### inflate(int width, int height) {#inflate-int-int-}
```
public final void inflate(int width, int height)
```


この [Rectangle](../../com.aspose.drawing/rectangle) を指定された量だけ拡大します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| width | int | この [Rectangle](../../com.aspose.drawing/rectangle) を水平方向に拡大する量。 |
| height | int | この [Rectangle](../../com.aspose.drawing/rectangle) を垂直方向に拡大する量。 |

### inflate(Size size) {#inflate-com.aspose.drawing.Size-}
```
public final void inflate(Size size)
```


この [Rectangle](../../com.aspose.drawing/rectangle) を指定された量だけ拡大します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | この [Rectangle](../../com.aspose.drawing/rectangle) を拡大するサイズ。 |

### contains(int x, int y) {#contains-int-int-}
```
public final boolean contains(int x, int y)
```


指定された点がこの [Rectangle](../../com.aspose.drawing/rectangle) 構造体内に含まれるかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | テスト対象の点の x 座標。 |
| y | int | テスト対象ポイントの y 座標。 |

**Returns:**
boolean - `x` と `y` で定義された点がこの [Rectangle](../../com.aspose.drawing/rectangle) 構造体に含まれる場合に `true` を返し、そうでない場合は `false` を返します。
### contains(Point pt) {#contains-com.aspose.drawing.Point-}
```
public final boolean contains(Point pt)
```


指定された点がこの [Rectangle](../../com.aspose.drawing/rectangle) 構造体内に含まれるかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | テスト対象の [Point](../../com.aspose.drawing/point)。 |

**Returns:**
boolean - `pt` で表される点がこの [Rectangle](../../com.aspose.drawing/rectangle) 構造体に含まれる場合に `true` を返し、そうでない場合は `false` を返します。
### contains(Rectangle rect) {#contains-com.aspose.drawing.Rectangle-}
```
public final boolean contains(Rectangle rect)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.drawing.Rectangle-}
```
public final boolean intersectsWith(Rectangle rect)
```


`rect` とこの矩形が交差するかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | テストする矩形です。 |

**Returns:**
boolean - 交差がある場合に true を返し、そうでない場合は false を返します。
### offset(int x, int y) {#offset-int-int-}
```
public final void offset(int x, int y)
```


この矩形の位置を指定された量だけ調整します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | 水平オフセット。 |
| y | int | 垂直オフセット。 |

### offset(Point pos) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point pos)
```


この矩形の位置を指定された量だけ調整します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pos | [Point](../../com.aspose.drawing/point) | オフセット。 |

### equals(Rectangle other) {#equals-com.aspose.drawing.Rectangle-}
```
public final boolean equals(Rectangle other)
```


他の [Rectangle](../../com.aspose.drawing/rectangle) 構造体がこの [Rectangle](../../com.aspose.drawing/rectangle) 構造体と同じ位置とサイズを持つかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.drawing/rectangle) | テスト対象の他の矩形 |

**Returns:**
boolean - 他の [Rectangle](../../com.aspose.drawing/rectangle) 構造体とその X、Y、Width、Height プロパティがこの [Rectangle](../../com.aspose.drawing/rectangle) 構造体の対応するプロパティと等しい場合に `true` を返し、そうでない場合は `false` を返します。
### CloneTo(Rectangle that) {#CloneTo-com.aspose.drawing.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.drawing/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### normalize() {#normalize--}
```
public void normalize()
```


矩形の幅と高さを正にし、左が右より小さく、上が下より小さくなるように正規化します。

