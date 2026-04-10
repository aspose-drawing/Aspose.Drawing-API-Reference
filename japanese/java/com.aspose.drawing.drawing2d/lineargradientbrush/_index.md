---
title: LinearGradientBrush
second_title: Aspose.Drawing for Java API リファレンス
description: 線形グラデーションを使用したものをカプセル化します。
type: docs
weight: 31
url: /ja/java/com.aspose.drawing.drawing2d/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class LinearGradientBrush extends Brush
```

[Brush](../../com.aspose.drawing/brush) を線形グラデーションでカプセル化します。このクラスは継承できません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-) | 指定されたポイントとカラーで、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。 |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-) | 指定されたポイントとカラーで、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。 |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | 矩形、開始色と終了色、および方向モードに基づいて、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。 |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | 矩形、開始色と終了色、および方向に基づいて、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。 |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | 矩形、開始色と終了色、および方向角度に基づいて、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。 |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | 矩形、開始色と終了色、および方向角度に基づいて、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。 |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | 矩形、開始色と終了色、および方向角度に基づいて、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。 |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | 矩形、開始色と終了色、および方向角度に基づいて、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLinearColors()](#getLinearColors--) | グラデーションの開始色と終了色を取得または設定します。 |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.drawing.Color---) | グラデーションの開始色と終了色を取得または設定します。 |
| [getRectangle()](#getRectangle--) | グラデーションの開始点と終了点を定義する矩形領域を取得します。 |
| [getGammaCorrection()](#getGammaCorrection--) | この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) に対してガンマ補正が有効かどうかを示す値を取得または設定します。 |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) に対してガンマ補正が有効かどうかを示す値を取得または設定します。 |
| [getBlend()](#getBlend--) | `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) を取得または設定します。このブレンドは、グラデーションのカスタム減衰を定義する位置と係数を指定します。 |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) を取得または設定します。このブレンドは、グラデーションのカスタム減衰を定義する位置と係数を指定します。 |
| [getInterpolationColors()](#getInterpolationColors--) | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) を取得または設定します。これは多色線形グラデーションを定義します。 |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) を取得または設定します。これは多色線形グラデーションを定義します。 |
| [getWrapMode()](#getWrapMode--) | `WrapMode` 列挙体を取得または設定します。これはこの [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) のラップモードを示します。 |
| [setWrapMode(int value)](#setWrapMode-int-) | `WrapMode` 列挙体を取得または設定します。これはこの [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) のラップモードを示します。 |
| [getTransform()](#getTransform--) | この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) のローカル幾何変換を定義するコピー [Matrix](../../com.aspose.drawing.drawing2d/matrix) を取得または設定します。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) のローカル幾何変換を定義するコピー [Matrix](../../com.aspose.drawing.drawing2d/matrix) を取得または設定します。 |
| [deepClone()](#deepClone--) | この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) の正確なコピーを作成します。 |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | ベル型曲線に基づくグラデーションの減衰を作成します。 |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | ベル型曲線に基づくグラデーションの減衰を作成します。 |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | 中心色と、両端が単一色へ線形に減衰する線形グラデーションを作成します。 |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | 中心色と、両端が単一色へ線形に減衰する線形グラデーションを作成します。 |
| [resetTransform()](#resetTransform--) | `LinearGradientBrush.Transform` プロパティを単位行列にリセットします。 |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) のローカル幾何変換を表す [Matrix](../../com.aspose.drawing.drawing2d/matrix) に、指定された [Matrix](../../com.aspose.drawing.drawing2d/matrix) を前置して乗算します。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) のローカル幾何変換を表す [Matrix](../../com.aspose.drawing.drawing2d/matrix) に、指定された順序で指定された [Matrix](../../com.aspose.drawing.drawing2d/matrix) を乗算します。 |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | ローカル幾何変換を指定された寸法だけ平行移動します。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | ローカル幾何変換を指定された順序で、指定された寸法だけ平行移動します。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | ローカル幾何変換を指定された量だけ拡大縮小します。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | ローカル幾何変換を指定された順序で、指定された量だけ拡大縮小します。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | ローカル幾何変換を指定された角度だけ回転させます。 |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | ローカル幾何変換を指定された順序で、指定された角度だけ回転させます。 |
### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


指定されたポイントとカラーで、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | 線形グラデーションの開始点を表す [PointF](../../com.aspose.drawing/pointf) 構造体です。 |
| point2 | [PointF](../../com.aspose.drawing/pointf) | 線形グラデーションの終了点を表す [PointF](../../com.aspose.drawing/pointf) 構造体です。 |
| color1 | [Color](../../com.aspose.drawing/color) | 線形グラデーションの開始色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |
| color2 | [Color](../../com.aspose.drawing/color) | 線形グラデーションの終了色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


指定されたポイントとカラーで、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | 線形グラデーションの開始点を表す [Point](../../com.aspose.drawing/point) 構造体です。 |
| point2 | [Point](../../com.aspose.drawing/point) | 線形グラデーションの終了点を表す [Point](../../com.aspose.drawing/point) 構造体です。 |
| color1 | [Color](../../com.aspose.drawing/color) | 線形グラデーションの開始色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |
| color2 | [Color](../../com.aspose.drawing/color) | 線形グラデーションの終了色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)
```


矩形、開始色と終了色、および方向モードに基づいて、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 線形グラデーションの境界を指定する [RectangleF](../../com.aspose.drawing/rectanglef) 構造体です。 |
| color1 | [Color](../../com.aspose.drawing/color) | グラデーションの開始色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |
| color2 | [Color](../../com.aspose.drawing/color) | グラデーションの終了色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |
| linearGradientMode | int | グラデーションの向きを指定する [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) 列挙要素です。向きはグラデーションの開始点と終了点を決定します。たとえば、LinearGradientMode.ForwardDiagonal は開始点が矩形の左上隅、終了点が右下隅であることを指定します。 |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)
```


矩形、開始色と終了色、および方向に基づいて、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | `Rectangle`([.getRectangle](../../null/\#getRectangle)) 構造体で、線形グラデーションの境界を指定します。 |
| color1 | [Color](../../com.aspose.drawing/color) | グラデーションの開始色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |
| color2 | [Color](../../com.aspose.drawing/color) | グラデーションの終了色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |
| linearGradientMode | int | グラデーションの向きを指定する [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) 列挙要素です。向きはグラデーションの開始点と終了点を決定します。たとえば、LinearGradientMode.ForwardDiagonal は開始点が矩形の左上隅、終了点が右下隅であることを指定します。 |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


矩形、開始色と終了色、および方向角度に基づいて、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 線形グラデーションの境界を指定する [RectangleF](../../com.aspose.drawing/rectanglef) 構造体です。 |
| color1 | [Color](../../com.aspose.drawing/color) | グラデーションの開始色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |
| color2 | [Color](../../com.aspose.drawing/color) | グラデーションの終了色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |
| 角度 | float | グラデーションの向き線の角度で、x 軸から時計回りに測定した度数です。 |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


矩形、開始色と終了色、および方向角度に基づいて、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 線形グラデーションの境界を指定する [RectangleF](../../com.aspose.drawing/rectanglef) 構造体です。 |
| color1 | [Color](../../com.aspose.drawing/color) | グラデーションの開始色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |
| color2 | [Color](../../com.aspose.drawing/color) | グラデーションの終了色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |
| 角度 | float | グラデーションの向き線の角度で、x 軸から時計回りに測定した度数です。 |
| isAngleScaleable | boolean | true に設定すると、この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) に関連付けられた変換の影響を受けるように角度を指定します。false の場合は影響を受けません。 |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


矩形、開始色と終了色、および方向角度に基づいて、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | `Rectangle`([.getRectangle](../../null/\#getRectangle)) 構造体で、線形グラデーションの境界を指定します。 |
| color1 | [Color](../../com.aspose.drawing/color) | グラデーションの開始色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |
| color2 | [Color](../../com.aspose.drawing/color) | グラデーションの終了色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |
| 角度 | float | グラデーションの向き線の角度で、x 軸から時計回りに測定した度数です。 |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


矩形、開始色と終了色、および方向角度に基づいて、[LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | `Rectangle`([.getRectangle](../../null/\#getRectangle)) 構造体で、線形グラデーションの境界を指定します。 |
| color1 | [Color](../../com.aspose.drawing/color) | グラデーションの開始色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |
| color2 | [Color](../../com.aspose.drawing/color) | グラデーションの終了色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |
| 角度 | float | グラデーションの向き線の角度で、x 軸から時計回りに測定した度数です。 |
| isAngleScaleable | boolean | true に設定すると、この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) に関連付けられた変換の影響を受けるように角度を指定します。false の場合は影響を受けません。 |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


グラデーションの開始色と終了色を取得または設定します。

**Returns:**
com.aspose.drawing.Color[]
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.drawing.Color---}
```
public void setLinearColors(Color[] value)
```


グラデーションの開始色と終了色を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


グラデーションの開始点と終了点を定義する矩形領域を取得します。

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) に対してガンマ補正が有効かどうかを示す値を取得または設定します。

**Returns:**
boolean
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) に対してガンマ補正が有効かどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

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

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


`WrapMode` 列挙体を取得または設定します。これはこの [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) のラップモードを示します。

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


`WrapMode` 列挙体を取得または設定します。これはこの [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) のラップモードを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) のローカル幾何変換を定義するコピー [Matrix](../../com.aspose.drawing.drawing2d/matrix) を取得または設定します。

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) のローカル幾何変換を定義するコピー [Matrix](../../com.aspose.drawing.drawing2d/matrix) を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) の正確なコピーを作成します。

**Returns:**
java.lang.Object - このメソッドが作成する [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) をオブジェクトとしてキャストしたものです。
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


ベル型曲線に基づくグラデーションの減衰を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 焦点 | float | 0 から 1 の範囲の値で、グラデーションの中心（開始色と終了色が等しく混合される点）を指定します。 |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


ベル型曲線に基づくグラデーションの減衰を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 焦点 | float | 0 から 1 の範囲の値で、グラデーションの中心（グラデーションが終了色のみで構成される点）を指定します。 |
| スケール | float | 0 から 1 の範囲の値で、`focus` から色がどれだけ速く減衰するかを指定します。 |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


中心色と、両端が単一色へ線形に減衰する線形グラデーションを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 焦点 | float | 0 から 1 の範囲の値で、グラデーションの中心（グラデーションが終了色のみで構成される点）を指定します。 |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


中心色と、両端が単一色へ線形に減衰する線形グラデーションを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 焦点 | float | 0 から 1 の範囲の値で、グラデーションの中心（グラデーションが終了色のみで構成される点）を指定します。 |
| スケール | float | 0 から 1 の範囲の値で、開始色から `focus`（終了色）まで色がどれだけ速く減衰するかを指定します。 |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


`LinearGradientBrush.Transform` プロパティを単位行列にリセットします。

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) のローカル幾何変換を表す [Matrix](../../com.aspose.drawing.drawing2d/matrix) に、指定された [Matrix](../../com.aspose.drawing.drawing2d/matrix) を前置して乗算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 幾何変換に掛け算するための [Matrix](../../com.aspose.drawing.drawing2d/matrix) です。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


この [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) のローカル幾何変換を表す [Matrix](../../com.aspose.drawing.drawing2d/matrix) に、指定された順序で指定された [Matrix](../../com.aspose.drawing.drawing2d/matrix) を乗算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 幾何変換に掛け算するための [Matrix](../../com.aspose.drawing.drawing2d/matrix) です。 |
| order | int | 2 つの行列を掛け算する順序を指定する [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) です。 |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


指定された寸法でローカル幾何変換を平行移動します。このメソッドは変換の先頭に平行移動を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 方向の平行移動量です。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


ローカル幾何変換を指定された順序で、指定された寸法だけ平行移動します。

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
| sx | float | 変換を x 軸方向に拡大する量。 |
| sy | float | 変換を y 軸方向に拡大する量。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


ローカル幾何変換を指定された順序で、指定された量だけ拡大縮小します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sx | float | 変換を x 軸方向に拡大する量。 |
| sy | float | 変換を y 軸方向に拡大する量。 |
| order | int | 拡大行列を付加するか前置するかを指定する [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)。 |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


指定された量だけローカルの幾何変換を回転させます。このメソッドは回転行列を変換の先頭に追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


ローカル幾何変換を指定された順序で、指定された角度だけ回転させます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度。 |
| order | int | 回転行列を付加するか前置するかを指定する [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)。 |

