---
title: ペン
second_title: Aspose.Drawing for Java API リファレンス
description: 線や曲線を描画するために使用されるオブジェクトを定義します。
type: docs
weight: 34
url: /ja/java/com.aspose.drawing/pen/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class Pen implements System.IDisposable
```

線や曲線を描画するために使用されるオブジェクトを定義します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.drawing.Color-) | 指定された `Color`（[.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)）で、[Pen](../../com.aspose.drawing/pen) クラスの新しいインスタンスを初期化します。 |
| [Pen(Brush brush, float width)](#Pen-com.aspose.drawing.Brush-float-) | 指定された Brush と Width を使用して、Pen クラスの新しいインスタンスを初期化します。 |
| [Pen(Brush brush)](#Pen-com.aspose.drawing.Brush-) | 指定された `Brush`（[.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)）で、[Pen](../../com.aspose.drawing/pen) クラスの新しいインスタンスを初期化します。 |
| [Pen(Color color, float width)](#Pen-com.aspose.drawing.Color-float-) | 指定された Color と Width プロパティを使用して、Pen クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColor()](#getColor--) | この [Pen](../../com.aspose.drawing/pen) の色を取得または設定します。 |
| [setColor(Color value)](#setColor-com.aspose.drawing.Color-) | この [Pen](../../com.aspose.drawing/pen) の色を取得または設定します。 |
| [getBrush()](#getBrush--) | この [Pen](../../com.aspose.drawing/pen) の属性を決定する Brush を取得または設定します。 |
| [setBrush(Brush value)](#setBrush-com.aspose.drawing.Brush-) | この [Pen](../../com.aspose.drawing/pen) の属性を決定する Brush を取得または設定します。 |
| [getCompoundArray()](#getCompoundArray--) | 複合ペンを指定する値の配列を取得または設定します。 |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | 複合ペンを指定する値の配列を取得または設定します。 |
| [getWidth()](#getWidth--) | 描画に使用される Graphics オブジェクトの単位で、この Pen の幅を取得または設定します。 |
| [setWidth(float value)](#setWidth-float-) | 描画に使用される Graphics オブジェクトの単位で、この Pen の幅を取得または設定します。 |
| [getStartCap()](#getStartCap--) | この Pen で描画された線の開始部に使用されるキャップスタイルを取得または設定します。 |
| [setStartCap(int value)](#setStartCap-int-) | この Pen で描画された線の開始部に使用されるキャップスタイルを取得または設定します。 |
| [getEndCap()](#getEndCap--) | この Pen で描画された線の終端に使用されるキャップスタイルを取得または設定します。 |
| [setEndCap(int value)](#setEndCap-int-) | この Pen で描画された線の終端に使用されるキャップスタイルを取得または設定します。 |
| [getLineJoin()](#getLineJoin--) | この Pen で描画された連続する2本の線の端部の結合スタイルを取得または設定します。 |
| [setLineJoin(int value)](#setLineJoin-int-) | この Pen で描画された連続する2本の線の端部の結合スタイルを取得または設定します。 |
| [getMiterLimit()](#getMiterLimit--) | 斜め角の結合部分の厚さの上限を取得または設定します。 |
| [setMiterLimit(float value)](#setMiterLimit-float-) | 斜め角の結合部分の厚さの上限を取得または設定します。 |
| [getAlignment()](#getAlignment--) | この [Pen](../../com.aspose.drawing/pen) の配置を取得または設定します。 |
| [setAlignment(int value)](#setAlignment-int-) | この [Pen](../../com.aspose.drawing/pen) の配置を取得または設定します。 |
| [getTransform()](#getTransform--) | この [Pen](../../com.aspose.drawing/pen) の幾何変換のコピーを取得または設定します。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | この [Pen](../../com.aspose.drawing/pen) の幾何変換のコピーを取得または設定します。 |
| [getCustomStartCap()](#getCustomStartCap--) | この [Pen](../../com.aspose.drawing/pen) で描画された線の開始部に使用するカスタムキャップを取得または設定します。 |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-) | この [Pen](../../com.aspose.drawing/pen) で描画された線の開始部に使用するカスタムキャップを取得または設定します。 |
| [getCustomEndCap()](#getCustomEndCap--) | この [Pen](../../com.aspose.drawing/pen) で描画された線の終端に使用するカスタムキャップを取得または設定します。 |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-) | この [Pen](../../com.aspose.drawing/pen) で描画された線の終端に使用するカスタムキャップを取得または設定します。 |
| [getDashCap()](#getDashCap--) | この [Pen](../../com.aspose.drawing/pen) で描画された破線のダッシュの終端に使用されるキャップスタイルを取得または設定します。 |
| [setDashCap(int value)](#setDashCap-int-) | この [Pen](../../com.aspose.drawing/pen) で描画された破線のダッシュの終端に使用されるキャップスタイルを取得または設定します。 |
| [getDashOffset()](#getDashOffset--) | 線の開始点からダッシュパターンの開始点までの距離を取得または設定します。 |
| [setDashOffset(float value)](#setDashOffset-float-) | 線の開始点からダッシュパターンの開始点までの距離を取得または設定します。 |
| [getDashPattern()](#getDashPattern--) | カスタムダッシュとスペースの配列を取得または設定します。 |
| [setDashPattern(float[] value)](#setDashPattern-float---) | カスタムダッシュとスペースの配列を取得または設定します。 |
| [getDashStyle()](#getDashStyle--) | この [Pen](../../com.aspose.drawing/pen) で描画された破線に使用されるスタイルを取得または設定します。 |
| [setDashStyle(int value)](#setDashStyle-int-) | この [Pen](../../com.aspose.drawing/pen) で描画された破線に使用されるスタイルを取得または設定します。 |
| [getPenType()](#getPenType--) | この Pen で描画された線のスタイルを取得します。 |
| [dispose()](#dispose--) | この Pen が使用しているすべてのリソースを解放します。 |
| [deepClone()](#deepClone--) | この [Pen](../../com.aspose.drawing/pen) の正確なコピーを作成します。 |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | この [Pen](../../com.aspose.drawing/pen) で描画された線の終端に使用されるキャップのスタイルを決定する値を設定します。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 指定された係数でローカルの幾何変換を拡大縮小します。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 指定された順序で指定された係数によりローカルの幾何変換を拡大縮小します。 |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 指定された寸法でローカルの幾何変換を平行移動します。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 指定された順序で指定された寸法によりローカルの幾何変換を平行移動します。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | 指定された角度でローカルの幾何変換を回転させます。 |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 指定された順序で指定された角度によりローカルの幾何変換を回転させます。 |
| [resetTransform()](#resetTransform--) | この [Pen](../../com.aspose.drawing/pen) の幾何変換行列を単位行列にリセットします。 |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | この [Pen](../../com.aspose.drawing/pen) の変換行列に指定された [Matrix](../../com.aspose.drawing.drawing2d/matrix) を掛け算します。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | この [Pen](../../com.aspose.drawing/pen) の変換行列に、指定された順序で指定された [Matrix](../../com.aspose.drawing.drawing2d/matrix) を掛け算します。 |
### Pen(Color color) {#Pen-com.aspose.drawing.Color-}
```
public Pen(Color color)
```


指定された `Color`（[.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)）で、[Pen](../../com.aspose.drawing/pen) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) は、この [Pen](../../com.aspose.drawing/pen) の塗りプロパティを決定します。 |

### Pen(Brush brush, float width) {#Pen-com.aspose.drawing.Brush-float-}
```
public Pen(Brush brush, float width)
```


指定された Brush と Width を使用して、Pen クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | この Pen の特性を決定する Brush。 |
| 幅 | float | 新しい Pen の幅。 |

### Pen(Brush brush) {#Pen-com.aspose.drawing.Brush-}
```
public Pen(Brush brush)
```


指定された `Brush`（[.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)）で、[Pen](../../com.aspose.drawing/pen) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)) は、この [Pen](../../com.aspose.drawing/pen) の塗りプロパティを決定します。 |

### Pen(Color color, float width) {#Pen-com.aspose.drawing.Color-float-}
```
public Pen(Color color, float width)
```


指定された Color と Width プロパティを使用して、Pen クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | この Pen の色を示す Color 構造体。 |
| 幅 | float | この Pen の幅を示す値。 |

### getColor() {#getColor--}
```
public final Color getColor()
```


この [Pen](../../com.aspose.drawing/pen) の色を取得または設定します。

値: この [Pen](../../com.aspose.drawing/pen) の色を表す `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) 構造体。

**Returns:**
[Color](../../com.aspose.drawing/color)
### setColor(Color value) {#setColor-com.aspose.drawing.Color-}
```
public final void setColor(Color value)
```


この [Pen](../../com.aspose.drawing/pen) の色を取得または設定します。

値: この [Pen](../../com.aspose.drawing/pen) の色を表す `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) 構造体。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


この [Pen](../../com.aspose.drawing/pen) の属性を決定する Brush を取得または設定します。

**Returns:**
[Brush](../../com.aspose.drawing/brush)
### setBrush(Brush value) {#setBrush-com.aspose.drawing.Brush-}
```
public final void setBrush(Brush value)
```


この [Pen](../../com.aspose.drawing/pen) の属性を決定する Brush を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Brush](../../com.aspose.drawing/brush) |  |

### getCompoundArray() {#getCompoundArray--}
```
public final float[] getCompoundArray()
```


複合ペンを指定する値の配列を取得または設定します。複合ペンは、平行線と間隔で構成された複合線を描画します。

**Returns:**
float[] - 複合配列を指定する実数の配列です。配列の要素は昇順で、0 未満でなく、1 を超えてはいけません。
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public final void setCompoundArray(float[] value)
```


複合ペンを指定する値の配列を取得または設定します。複合ペンは、平行線と間隔で構成された複合線を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


描画に使用される Graphics オブジェクトの単位で、この Pen の幅を取得または設定します。

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


描画に使用される Graphics オブジェクトの単位で、この Pen の幅を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getStartCap() {#getStartCap--}
```
public final int getStartCap()
```


この Pen で描画された線の開始部に使用されるキャップスタイルを取得または設定します。

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public final void setStartCap(int value)
```


この Pen で描画された線の開始部に使用されるキャップスタイルを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public final int getEndCap()
```


この Pen で描画された線の終端に使用されるキャップスタイルを取得または設定します。

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public final void setEndCap(int value)
```


この Pen で描画された線の終端に使用されるキャップスタイルを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public final int getLineJoin()
```


この Pen で描画された連続する2本の線の端部の結合スタイルを取得または設定します。

--------------------

現在、マイター結合は実際には MiterClipped として機能します。

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public final void setLineJoin(int value)
```


この Pen で描画された連続する2本の線の端部の結合スタイルを取得または設定します。

--------------------

現在、マイター結合は実際には MiterClipped として機能します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


斜め角の結合部分の厚さの上限を取得または設定します。

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


斜め角の結合部分の厚さの上限を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


この [Pen](../../com.aspose.drawing/pen) の配置を取得または設定します。

**Returns:**
int - この [Pen](../../com.aspose.drawing/pen) の配置を表す [PenAlignment](../../com.aspose.drawing.drawing2d/penalignment)。
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


この [Pen](../../com.aspose.drawing/pen) の配置を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public final Matrix getTransform()
```


この [Pen](../../com.aspose.drawing/pen) の幾何変換のコピーを取得または設定します。

値: この [Pen](../../com.aspose.drawing/pen) の幾何変換を表す [Matrix](../../com.aspose.drawing.drawing2d/matrix) のコピー。

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void setTransform(Matrix value)
```


この [Pen](../../com.aspose.drawing/pen) の幾何変換のコピーを取得または設定します。

値: この [Pen](../../com.aspose.drawing/pen) の幾何変換を表す [Matrix](../../com.aspose.drawing.drawing2d/matrix) のコピー。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getCustomStartCap() {#getCustomStartCap--}
```
public final CustomLineCap getCustomStartCap()
```


この [Pen](../../com.aspose.drawing/pen) で描画された線の開始部に使用するカスタムキャップを取得または設定します。

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the beginning of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomStartCap(CustomLineCap value)
```


この [Pen](../../com.aspose.drawing/pen) で描画された線の開始部に使用するカスタムキャップを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getCustomEndCap() {#getCustomEndCap--}
```
public final CustomLineCap getCustomEndCap()
```


この [Pen](../../com.aspose.drawing/pen) で描画された線の終端に使用するカスタムキャップを取得または設定します。

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the end of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomEndCap(CustomLineCap value)
```


この [Pen](../../com.aspose.drawing/pen) で描画された線の終端に使用するカスタムキャップを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getDashCap() {#getDashCap--}
```
public final int getDashCap()
```


この [Pen](../../com.aspose.drawing/pen) で描画された破線のダッシュの終端に使用されるキャップスタイルを取得または設定します。

**Returns:**
int - この [Pen](../../com.aspose.drawing/pen) で描画される破線のダッシュの開始と終了に使用されるキャップスタイルを表す `DashCap`([.getDashCap](../../null/\#getDashCap)/[.setDashCap(int)](../../null/\#setDashCap-int-)) のいずれかの値。
### setDashCap(int value) {#setDashCap-int-}
```
public final void setDashCap(int value)
```


この [Pen](../../com.aspose.drawing/pen) で描画された破線のダッシュの終端に使用されるキャップスタイルを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public final float getDashOffset()
```


線の開始点からダッシュパターンの開始点までの距離を取得または設定します。

**Returns:**
float - 線の開始点からダッシュパターンの開始点までの距離。
### setDashOffset(float value) {#setDashOffset-float-}
```
public final void setDashOffset(float value)
```


線の開始点からダッシュパターンの開始点までの距離を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getDashPattern() {#getDashPattern--}
```
public final float[] getDashPattern()
```


カスタムダッシュとスペースの配列を取得または設定します。

**Returns:**
float[] - 破線における交互のダッシュとスペースの長さを指定する実数の配列。
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public final void setDashPattern(float[] value)
```


カスタムダッシュとスペースの配列を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


この [Pen](../../com.aspose.drawing/pen) で描画された破線に使用されるスタイルを取得または設定します。

**Returns:**
int - ダッシュ線のスタイルを表す `DashStyle`([.getDashStyle](../../null/\#getDashStyle)/[.setDashStyle(int)](../../null/\#setDashStyle-int-)) で、この [Pen](../../com.aspose.drawing/pen) で描画された破線に使用されます。
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


この [Pen](../../com.aspose.drawing/pen) で描画された破線に使用されるスタイルを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPenType() {#getPenType--}
```
public final int getPenType()
```


この Pen で描画された線のスタイルを取得します。

Value: この [Pen](../../com.aspose.drawing/pen) で描画される線のスタイルを指定する `PenType`([.getPenType](../../null/\#getPenType)) 列挙型です。

**Returns:**
int
### dispose() {#dispose--}
```
public final void dispose()
```


この Pen が使用しているすべてのリソースを解放します。

--------------------

このメソッドは実際には何もしません。System.Drawing API との互換性のためだけに用意されています。

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


この [Pen](../../com.aspose.drawing/pen) の正確なコピーを作成します。

**Returns:**
java.lang.Object - [Pen](../../com.aspose.drawing/pen) にキャストできるオブジェクトです。
### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public final void setLineCap(int startCap, int endCap, int dashCap)
```


この [Pen](../../com.aspose.drawing/pen) で描画された線の終端に使用されるキャップのスタイルを決定する値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startCap | int | この [Pen](../../com.aspose.drawing/pen) で描画された線の開始点で使用するキャップスタイルを表す [LineCap](../../com.aspose.drawing.drawing2d/linecap) です。 |
| endCap | int | この [Pen](../../com.aspose.drawing/pen) で描画された線の終点で使用するキャップスタイルを表す [LineCap](../../com.aspose.drawing.drawing2d/linecap) です。 |
| dashCap | int | この [Pen](../../com.aspose.drawing/pen) で描画された破線の開始点または終点で使用するキャップスタイルを表す [LineCap](../../com.aspose.drawing.drawing2d/linecap) です。 |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public final void scaleTransform(float sx, float sy)
```


指定された係数でローカル幾何変換を拡大縮小します。このメソッドは拡大縮小行列を変換の先頭に追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sx | float | x 軸方向に変換を拡大縮小する係数です。 |
| sy | float | y 軸方向に変換を拡大縮小する係数です。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public final void scaleTransform(float sx, float sy, int order)
```


指定された順序で指定された係数によりローカルの幾何変換を拡大縮小します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sx | float | x 軸方向に変換を拡大縮小する係数です。 |
| sy | float | y 軸方向に変換を拡大縮小する係数です。 |
| order | int | 拡大行列を付加するか前置するかを指定する [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)。 |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public final void translateTransform(float dx, float dy)
```


指定された寸法でローカル幾何変換を平行移動します。このメソッドは平行移動を変換の先頭に追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 方向の平行移動量です。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public final void translateTransform(float dx, float dy, int order)
```


指定された順序で指定された寸法によりローカルの幾何変換を平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 方向の平行移動量です。 |
| 順序 | int | 平行移動を適用する順序（先頭に追加するか末尾に追加するか）です。 |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public final void rotateTransform(float angle)
```


指定された角度でローカル幾何変換を回転させます。このメソッドは回転を変換の先頭に追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public final void rotateTransform(float angle, int order)
```


指定された順序で指定された角度によりローカルの幾何変換を回転させます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度。 |
| order | int | 回転行列を付加するか前置するかを指定する [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)。 |

### resetTransform() {#resetTransform--}
```
public final void resetTransform()
```


この [Pen](../../com.aspose.drawing/pen) の幾何変換行列を単位行列にリセットします。

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void multiplyTransform(Matrix matrix)
```


この [Pen](../../com.aspose.drawing/pen) の変換行列に指定された [Matrix](../../com.aspose.drawing.drawing2d/matrix) を掛け算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 変換行列を掛け合わせるための [Matrix](../../com.aspose.drawing.drawing2d/matrix) オブジェクトです。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public final void multiplyTransform(Matrix matrix, int order)
```


この [Pen](../../com.aspose.drawing/pen) の変換行列に、指定された順序で指定された [Matrix](../../com.aspose.drawing.drawing2d/matrix) を掛け算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 変換行列を掛け合わせるための java.awt.geom.AffineTransform です。 |
| 順序 | int | 掛け算操作を実行する順序です。 |

