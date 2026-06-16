---
title: PathGradientBrush
second_title: Aspose.Drawing for Java API リファレンス
description: グラデーションで内部を塗りつぶすオブジェクトをカプセル化します。
type: docs
weight: 36
url: /ja/java/com.aspose.drawing.drawing2d/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class PathGradientBrush extends Brush
```

グラデーションで内部を塗りつぶす [Brush](../../com.aspose.drawing/brush) オブジェクトをカプセル化し、[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) オブジェクトの内部を塗りつぶします。このクラスは継承できません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.drawing.PointF---) | 指定されたポイントで [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) クラスの新しいインスタンスを初期化します。 |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.PointF---int-) | 指定されたポイントとラップモードで [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) クラスの新しいインスタンスを初期化します。 |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.drawing.Point---) | 指定されたポイントで [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) クラスの新しいインスタンスを初期化します。 |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.Point---int-) | 指定されたポイントとラップモードで [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) クラスの新しいインスタンスを初期化します。 |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-) | 指定されたパスで [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCenterColor()](#getCenterColor--) | パスグラデーションの中心の色を取得または設定します。 |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.drawing.Color-) | パスグラデーションの中心の色を取得または設定します。 |
| [getSurroundColors()](#getSurroundColors--) | この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) が塗りつぶすパスのポイントに対応する色の配列を取得または設定します。 |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.drawing.Color---) | この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) が塗りつぶすパスのポイントに対応する色の配列を取得または設定します。 |
| [getCenterPoint()](#getCenterPoint--) | パスグラデーションの中心点を取得または設定します。 |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.drawing.PointF-) | パスグラデーションの中心点を取得または設定します。 |
| [getRectangle()](#getRectangle--) | この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) のバウンディング矩形を取得します。 |
| [getBlend()](#getBlend--) | `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) を取得または設定します。このブレンドは、グラデーションのカスタム減衰を定義する位置と係数を指定します。 |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) を取得または設定します。このブレンドは、グラデーションのカスタム減衰を定義する位置と係数を指定します。 |
| [getInterpolationColors()](#getInterpolationColors--) | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) を取得または設定します。これは多色線形グラデーションを定義します。 |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) を取得または設定します。これは多色線形グラデーションを定義します。 |
| [getTransform()](#getTransform--) | この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) のローカル幾何変換を定義する [Matrix](../../com.aspose.drawing.drawing2d/matrix) のコピーを取得または設定します。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) のローカル幾何変換を定義する [Matrix](../../com.aspose.drawing.drawing2d/matrix) のコピーを取得または設定します。 |
| [getFocusScales()](#getFocusScales--) | グラデーションの減衰の焦点位置を取得または設定します。 |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.drawing.PointF-) | グラデーションの減衰の焦点位置を取得または設定します。 |
| [getWrapMode()](#getWrapMode--) | この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) のラップモードを示す `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) を取得または設定します。 |
| [setWrapMode(int value)](#setWrapMode-int-) | この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) のラップモードを示す `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) を取得または設定します。 |
| [deepClone()](#deepClone--) | この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) の正確なコピーを作成します。 |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | パスの中心から外側の境界まで色が変化するグラデーションブラシを作成します。 |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | パスの中心から外側の境界まで色が変化するグラデーションブラシを作成します。 |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | 中心色から周囲の1色へ線形に減衰するグラデーションを作成します。 |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | 中心色と各周囲色への線形減衰を持つグラデーションを作成します。 |
| [resetTransform()](#resetTransform--) | `PathGradientBrush.Transform` プロパティを単位行列にリセットします。 |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | ブラシの変換行列を、ブラシの変換行列と別の行列との積で更新します。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | ブラシの変換行列を、ブラシの変換行列と別の行列との積で更新します。 |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 指定された平行移動をローカル幾何変換に適用します。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 指定された順序で、指定された平行移動をローカル幾何変換に適用します。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | ローカル幾何変換を指定された量だけ拡大縮小します。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | ローカル幾何変換を指定された順序で、指定された量だけ拡大縮小します。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | ローカル幾何変換を指定された角度だけ回転させます。 |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | ローカル幾何変換を指定された順序で、指定された角度だけ回転させます。 |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.drawing.PointF---}
```
public PathGradientBrush(PointF[] points)
```


指定されたポイントで [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | パスの頂点を構成する点を表す [PointF](../../com.aspose.drawing/pointf) 構造体の配列です。 |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


指定されたポイントとラップモードで [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | パスの頂点を構成する点を表す [PointF](../../com.aspose.drawing/pointf) 構造体の配列です。 |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) は、この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) で描画された塗りがどのようにタイル状に配置されるかを指定します。 |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.drawing.Point---}
```
public PathGradientBrush(Point[] points)
```


指定されたポイントで [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | パスの頂点を構成する点を表す [Point](../../com.aspose.drawing/point) 構造体の配列です。 |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


指定されたポイントとラップモードで [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | パスの頂点を構成する点を表す [Point](../../com.aspose.drawing/point) 構造体の配列です。 |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) は、この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) で描画された塗りがどのようにタイル状に配置されるかを指定します。 |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


指定されたパスで [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) によって塗りつぶされる領域を定義する [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) です。 |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


パスグラデーションの中心の色を取得または設定します。

**Returns:**
[Color](../../com.aspose.drawing/color)
### setCenterColor(Color value) {#setCenterColor-com.aspose.drawing.Color-}
```
public void setCenterColor(Color value)
```


パスグラデーションの中心の色を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) が塗りつぶすパスのポイントに対応する色の配列を取得または設定します。

**Returns:**
com.aspose.drawing.Color[]
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.drawing.Color---}
```
public void setSurroundColors(Color[] value)
```


この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) が塗りつぶすパスのポイントに対応する色の配列を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


パスグラデーションの中心点を取得または設定します。

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.drawing.PointF-}
```
public void setCenterPoint(PointF value)
```


パスグラデーションの中心点を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) のバウンディング矩形を取得します。

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


`Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) を取得または設定します。このブレンドは、グラデーションのカスタム減衰を定義する位置と係数を指定します。

**Returns:**
[Blend](../../com.aspose.drawing.drawing2d/blend)
### setBlend(Blend value) {#setBlend-com.aspose.drawing.drawing2d.Blend-}
```
public void setBlend(Blend value)
```


`Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) を取得または設定します。このブレンドは、グラデーションのカスタム減衰を定義する位置と係数を指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Blend](../../com.aspose.drawing.drawing2d/blend) |  |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) を取得または設定します。これは多色線形グラデーションを定義します。

**Returns:**
[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) を取得または設定します。これは多色線形グラデーションを定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) のローカル幾何変換を定義する [Matrix](../../com.aspose.drawing.drawing2d/matrix) のコピーを取得または設定します。

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) のローカル幾何変換を定義する [Matrix](../../com.aspose.drawing.drawing2d/matrix) のコピーを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


グラデーションの減衰の焦点位置を取得または設定します。

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setFocusScales(PointF value) {#setFocusScales-com.aspose.drawing.PointF-}
```
public void setFocusScales(PointF value)
```


グラデーションの減衰の焦点位置を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) のラップモードを示す `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) を取得または設定します。

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) のラップモードを示す `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


この [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) の正確なコピーを作成します。

**Returns:**
java.lang.Object - このメソッドが作成する [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) をオブジェクトとしてキャストしたものです。
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


パスの中心から境界へ向かって色が変化するグラデーションブラシを作成します。色の遷移はベル形曲線に基づいています。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 焦点 | float | 0 から 1 の値で、パスの中心から境界へ向かう任意の半径上で中心色が最高強度になる位置を指定します。デフォルトの 1 の値は、中心色の最高強度をパスの中心に配置します。 |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


パスの中心から境界へ向かって色が変化するグラデーションブラシを作成します。色の遷移はベル形曲線に基づいています。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 焦点 | float | 0 から 1 の値で、パスの中心から境界へ向かう任意の半径上で中心色が最高強度になる位置を指定します。デフォルトの 1 の値は、中心色の最高強度をパスの中心に配置します。 |
| スケール | float | 0 から 1 の値で、中心色が境界色とブレンドされる最大強度を指定します。1 の値は中心色の可能な限り最高の強度を与え、デフォルト値です。 |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


中心色から周囲の1色へ線形に減衰するグラデーションを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 焦点 | float | 0 から 1 の値で、パスの中心から境界へ向かう任意の半径上で中心色が最高強度になる位置を指定します。デフォルトの 1 の値は、中心色の最高強度をパスの中心に配置します。 |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


中心色と各周囲色への線形減衰を持つグラデーションを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 焦点 | float | 0 から 1 の値で、パスの中心から境界へ向かう任意の半径上で中心色が最高強度になる位置を指定します。デフォルトの 1 の値は、中心色の最高強度をパスの中心に配置します。 |
| スケール | float | 0 から 1 の値で、中心色が境界色とブレンドされる最大強度を指定します。1 の値は中心色の可能な限り最高の強度を与え、デフォルト値です。 |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


`PathGradientBrush.Transform` プロパティを単位行列にリセットします。

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


ブラシの変換行列を、ブラシの変換行列と別の行列との積で更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | ブラシの現在の変換行列と掛け合わされる [Matrix](../../com.aspose.drawing.drawing2d/matrix) です。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


ブラシの変換行列を、ブラシの変換行列と別の行列との積で更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | ブラシの現在の変換行列と掛け合わされる [Matrix](../../com.aspose.drawing.drawing2d/matrix) です。 |
| order | int | 2 つの行列を掛け算する順序を指定する [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) です。 |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


指定された平行移動をローカル幾何変換に適用します。このメソッドは変換の先頭に平行移動を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 方向の平行移動量です。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


指定された順序で、指定された平行移動をローカル幾何変換に適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 方向の平行移動量です。 |
| 順序 | int | 平行移動を適用する順序（先頭に追加するか末尾に追加するか）です。 |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


指定された量でローカルの幾何変換を拡大します。このメソッドは拡大行列を変換の先頭に追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sx | float | x 軸方向の変換スケール係数です。 |
| sy | float | y 軸方向の変換スケール係数です。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


ローカル幾何変換を指定された順序で、指定された量だけ拡大縮小します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sx | float | x 軸方向の変換スケール係数です。 |
| sy | float | y 軸方向の変換スケール係数です。 |
| order | int | 拡大行列を付加するか前置するかを指定する [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)。 |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


指定された量だけローカルの幾何変換を回転させます。このメソッドは回転行列を変換の先頭に追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転の角度（範囲）です。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


ローカル幾何変換を指定された順序で、指定された角度だけ回転させます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転の角度（範囲）です。 |
| order | int | 回転行列を付加するか前置するかを指定する [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)。 |

