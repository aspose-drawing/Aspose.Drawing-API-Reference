---
title: Matrix
second_title: Aspose.Drawing for Java API リファレンス
description: 幾何変換を表す 3×3 アフィン行列をカプセル化します。
type: docs
weight: 33
url: /ja/java/com.aspose.drawing.drawing2d/matrix/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Matrix implements System.IDisposable
```

幾何変換を表す 3×3 アフィン行列をカプセル化します。このクラスは継承できません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Matrix()](#Matrix--) | Matrix クラスの新しいインスタンスを単位行列として初期化します。 |
| [Matrix(float m11, float m12, float m21, float m22, float dx, float dy)](#Matrix-float-float-float-float-float-float-) | 指定された要素で Matrix クラスの新しいインスタンスを初期化します。 |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---) | 指定された矩形と点の配列で定義された幾何変換に対して、[Matrix](../../com.aspose.drawing.drawing2d/matrix) クラスの新しいインスタンスを初期化します。 |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---) | 指定された矩形と点の配列で定義された幾何変換に対して、[Matrix](../../com.aspose.drawing.drawing2d/matrix) クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [IdentityTransform](#IdentityTransform) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getElements()](#getElements--) | この Matrix の要素を表す浮動小数点値の配列を取得します。 |
| [isIdentity()](#isIdentity--) | この Matrix が単位行列かどうかを示す値を取得します。 |
| [isInvertible()](#isInvertible--) | この Matrix が可逆かどうかを示す値を取得します。 |
| [getOffsetX()](#getOffsetX--) | この Matrix の x 平行移動値（dx 値、または第3行第1列の要素）を取得します。 |
| [getOffsetY()](#getOffsetY--) | この Matrix の y 平行移動値（`dy` 値、または第3行第2列の要素）を取得します。 |
| [dispose()](#dispose--) | この Matrix が使用しているすべてのリソースを解放します。 |
| [deepClone()](#deepClone--) | この Matrix の正確なコピーを作成します。 |
| [invert()](#invert--) | この Matrix が可逆である場合、逆行列に変換します。 |
| [translate(float offsetX, float offsetY)](#translate-float-float-) | 指定された平行移動ベクトル（offsetX と offsetY）を先頭に付加する形でこの Matrix に適用します。 |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | 指定された順序で指定された平行移動ベクトルをこの Matrix に適用します。 |
| [transformVectors(PointF[] pts)](#transformVectors-com.aspose.drawing.PointF---) | 配列内の各ベクトルをこの Matrix で乗算します。 |
| [scale(float scaleX, float scaleY)](#scale-float-float-) | 指定されたスケールベクトルを先頭に付加する形でこの Matrix に適用します。 |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | 指定された順序で指定されたスケールベクトル（scaleX と scaleY）をこの Matrix に適用します。 |
| [shear(float shearX, float shearY)](#shear-float-float-) | 指定されたせん断ベクトルを先頭に付加する形でこの Matrix に適用します。 |
| [shear(float shearX, float shearY, int order)](#shear-float-float-int-) | 指定された順序で指定されたせん断ベクトルをこの Matrix に適用します。 |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.drawing.PointF-) | point パラメーターで指定された点を中心に、回転を先頭に付加する形でこの Matrix に時計回りの回転を適用します。 |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.drawing.PointF-int-) | 指定された順序で指定された点を中心に、この Matrix に時計回りの回転を適用します。 |
| [transformPoints(PointF[] pts)](#transformPoints-com.aspose.drawing.PointF---) | この [Matrix](../../com.aspose.drawing.drawing2d/matrix) が表す幾何変換を、指定された点の配列に適用します。 |
| [transformPoints(Point[] pts)](#transformPoints-com.aspose.drawing.Point---) | この [Matrix](../../com.aspose.drawing.drawing2d/matrix) が表す幾何変換を、指定された点の配列に適用します。 |
| [multiply(Matrix matrix)](#multiply-com.aspose.drawing.drawing2d.Matrix-) | この [Matrix](../../com.aspose.drawing.drawing2d/matrix) を `matrix` パラメーターで指定された行列で、指定された [Matrix](../../com.aspose.drawing.drawing2d/matrix) を先頭に付加する形で乗算します。 |
| [multiply(Matrix matrix, int order)](#multiply-com.aspose.drawing.drawing2d.Matrix-int-) | この [Matrix](../../com.aspose.drawing.drawing2d/matrix) を `matrix` パラメーターで指定された行列で乗算し、`order` パラメーターで指定された順序で適用します。 |
| [rotate(float angle)](#rotate-float-) | この [Matrix](../../com.aspose.drawing.drawing2d/matrix) の先頭に、原点を中心とし、指定された角度で時計回りの回転を付加します。 |
| [rotate(float angle, int order)](#rotate-float-int-) | この [Matrix](../../com.aspose.drawing.drawing2d/matrix) に対し、角度パラメーターで指定された量だけ、原点（x と y が 0 の位置）を中心に時計回りの回転を適用します。 |
| [reset()](#reset--) | この [Matrix](../../com.aspose.drawing.drawing2d/matrix) を単位行列の要素にリセットします。 |
### Matrix() {#Matrix--}
```
public Matrix()
```


Matrix クラスの新しいインスタンスを単位行列として初期化します。

### Matrix(float m11, float m12, float m21, float m22, float dx, float dy) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


指定された要素で Matrix クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| m11 | float | 新しい Matrix の第1行第1列の値です。 |
| m12 | float | 新しい Matrix の第1行第2列の値です。 |
| m21 | float | 新しい Matrix の第2行第1列の値です。 |
| m22 | float | 新しい Matrix の第2行第2列の値です。 |
| dx | float | 新しい Matrix の第3行第1列の値です。 |
| dy | float | 新しい Matrix の第3行第2列の値です。 |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


指定された矩形と点の配列で定義された幾何変換に対して、[Matrix](../../com.aspose.drawing.drawing2d/matrix) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 変換対象となる矩形を表す [Rectangle](../../com.aspose.drawing/rectangle) 構造体です。 |
| plgpts | [Point\[\]](../../com.aspose.drawing/point) | 矩形の左上、右上、左下の各角が変換される平行四辺形の点を表す、3つの [Point](../../com.aspose.drawing/point) 構造体の配列です。平行四辺形の右下の角は最初の3つの角から暗黙的に決定されます。 |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


指定された矩形と点の配列で定義された幾何変換に対して、[Matrix](../../com.aspose.drawing.drawing2d/matrix) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 変換対象となる矩形を表す [RectangleF](../../com.aspose.drawing/rectanglef) 構造体です。 |
| plgpts | [PointF\[\]](../../com.aspose.drawing/pointf) | 矩形の左上、右上、左下の各角が変換される平行四辺形の点を表す、3つの [PointF](../../com.aspose.drawing/pointf) 構造体の配列です。平行四辺形の右下の角は最初の3つの角から暗黙的に決定されます。 |

### IdentityTransform {#IdentityTransform}
```
public static final Matrix IdentityTransform
```


### getElements() {#getElements--}
```
public float[] getElements()
```


この Matrix の要素を表す浮動小数点値の配列を取得します。

**Returns:**
float[] - この Matrix の要素を表す浮動小数点値の配列です。
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


この Matrix が単位行列かどうかを示す値を取得します。

**Returns:**
boolean - この Matrix が単位行列かどうかを示す値です。
### isInvertible() {#isInvertible--}
```
public boolean isInvertible()
```


この Matrix が可逆かどうかを示す値を取得します。

**Returns:**
boolean - この Matrix が逆行列可能かどうかを示す値です。
### getOffsetX() {#getOffsetX--}
```
public float getOffsetX()
```


この Matrix の x 平行移動値（dx 値、または第3行第1列の要素）を取得します。

**Returns:**
float - この Matrix の x 転送値（dx 値、または第3行第1列の要素）です。
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```


この Matrix の y 平行移動値（`dy` 値、または第3行第2列の要素）を取得します。

**Returns:**
float - この Matrix の y 転送値（`dy` 値、または第3行第2列の要素）です。
### dispose() {#dispose--}
```
public void dispose()
```


この Matrix が使用しているすべてのリソースを解放します。

--------------------

このメソッドは実際には何もしません。System.Drawing API との互換性のためだけに用意されています。

### deepClone() {#deepClone--}
```
public Matrix deepClone()
```


この Matrix の正確なコピーを作成します。

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - The Matrix that this method creates.
### invert() {#invert--}
```
public void invert()
```


この Matrix が可逆である場合、逆行列に変換します。

### translate(float offsetX, float offsetY) {#translate-float-float-}
```
public void translate(float offsetX, float offsetY)
```


指定された平行移動ベクトル（offsetX と offsetY）を先頭に付加する形でこの Matrix に適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| offsetX | float | この Matrix を平行移動させる x 値です。 |
| offsetY | float | この Matrix を平行移動させる y 値です。 |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


指定された順序で指定された平行移動ベクトルをこの Matrix に適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| offsetX | float | この Matrix を平行移動させる x 値です。 |
| offsetY | float | この Matrix を平行移動させる y 値です。 |
| 順序 | int | この Matrix に平行移動を適用する順序（追加または前置）を指定する MatrixOrder です。 |

### transformVectors(PointF[] pts) {#transformVectors-com.aspose.drawing.PointF---}
```
public void transformVectors(PointF[] pts)
```


配列内の各ベクトルに行列を掛け算します。この行列の平行移動要素（第3行）は無視されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | 変換対象の点を表す [PointF](../../com.aspose.drawing/pointf) 構造体の配列です。 |

### scale(float scaleX, float scaleY) {#scale-float-float-}
```
public void scale(float scaleX, float scaleY)
```


指定されたスケールベクトルを先頭に付加する形でこの Matrix に適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scaleX | float | この Matrix を x 軸方向に拡大縮小する値です。 |
| scaleY | float | この Matrix を y 軸方向に拡大するための値。 |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


指定された順序で指定されたスケールベクトル（scaleX と scaleY）をこの Matrix に適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scaleX | float | この Matrix を x 軸方向に拡大縮小する値です。 |
| scaleY | float | この Matrix を y 軸方向に拡大するための値。 |
| 順序 | int | この Matrix にスケールベクトルが適用される順序（追加または前置）を指定する MatrixOrder。 |

### shear(float shearX, float shearY) {#shear-float-float-}
```
public void shear(float shearX, float shearY)
```


指定されたせん断ベクトルを先頭に付加する形でこの Matrix に適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shearX | float | 水平せん断係数。 |
| shearY | float | 垂直せん断係数。 |

### shear(float shearX, float shearY, int order) {#shear-float-float-int-}
```
public void shear(float shearX, float shearY, int order)
```


指定された順序で指定されたせん断ベクトルをこの Matrix に適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shearX | float | 水平せん断係数。 |
| shearY | float | 垂直せん断係数。 |
| 順序 | int | せん断が適用される順序（追加または前置）を指定する MatrixOrder。 |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.drawing.PointF-}
```
public void rotateAt(float angle, PointF point)
```


point パラメーターで指定された点を中心に、回転を先頭に付加する形でこの Matrix に時計回りの回転を適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転の角度（範囲）、度単位です。 |
| point | [PointF](../../com.aspose.drawing/pointf) | 回転の中心を表す PointF。 |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.drawing.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


指定された順序で指定された点を中心に、この Matrix に時計回りの回転を適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転の角度、度単位です。 |
| point | [PointF](../../com.aspose.drawing/pointf) | 回転の中心を表す PointF。 |
| 順序 | int | 回転が適用される順序（追加または前置）を指定する MatrixOrder。 |

### transformPoints(PointF[] pts) {#transformPoints-com.aspose.drawing.PointF---}
```
public void transformPoints(PointF[] pts)
```


この [Matrix](../../com.aspose.drawing.drawing2d/matrix) が表す幾何変換を、指定された点の配列に適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | 変換対象の点を表す [PointF](../../com.aspose.drawing/pointf) 構造体の配列です。 |

### transformPoints(Point[] pts) {#transformPoints-com.aspose.drawing.Point---}
```
public void transformPoints(Point[] pts)
```


この [Matrix](../../com.aspose.drawing.drawing2d/matrix) が表す幾何変換を、指定された点の配列に適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pts | [Point\[\]](../../com.aspose.drawing/point) | 変換対象の点を表す [Point](../../com.aspose.drawing/point) 構造体の配列。 |

### multiply(Matrix matrix) {#multiply-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiply(Matrix matrix)
```


この [Matrix](../../com.aspose.drawing.drawing2d/matrix) を `matrix` パラメーターで指定された行列で、指定された [Matrix](../../com.aspose.drawing.drawing2d/matrix) を先頭に付加する形で乗算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | この [Matrix](../../com.aspose.drawing.drawing2d/matrix) を掛け合わせるための [Matrix](../../com.aspose.drawing.drawing2d/matrix)。 |

### multiply(Matrix matrix, int order) {#multiply-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiply(Matrix matrix, int order)
```


この [Matrix](../../com.aspose.drawing.drawing2d/matrix) を `matrix` パラメーターで指定された行列で乗算し、`order` パラメーターで指定された順序で適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | この [Matrix](../../com.aspose.drawing.drawing2d/matrix) を掛け合わせるための [Matrix](../../com.aspose.drawing.drawing2d/matrix)。 |
| order | int | 乗算の順序を表す [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)。 |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


この [Matrix](../../com.aspose.drawing.drawing2d/matrix) の先頭に、原点を中心とし、指定された角度で時計回りの回転を付加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転の角度、度単位です。 |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


この [Matrix](../../com.aspose.drawing.drawing2d/matrix) に対し、角度パラメーターで指定された量だけ、原点（x と y が 0 の位置）を中心に時計回りの回転を適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転の角度、度単位です。 |
| order | int | この [Matrix](../../com.aspose.drawing.drawing2d/matrix) に回転が適用される順序（追加または前置）を指定する [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)。 |

### reset() {#reset--}
```
public void reset()
```


この [Matrix](../../com.aspose.drawing.drawing2d/matrix) を単位行列の要素にリセットします。

