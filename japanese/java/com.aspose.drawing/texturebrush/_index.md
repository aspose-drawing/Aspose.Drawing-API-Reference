---
title: TextureBrush
second_title: Aspose.Drawing for Java API リファレンス
description: 各プロパティは、TextureBrush クラスのもので、画像を使用して形状の内部を塗りつぶす Brush オブジェクトです。
type: docs
weight: 53
url: /ja/java/com.aspose.drawing/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class TextureBrush extends Brush
```

Each property of the TextureBrush class is a Brush object that uses an image to fill the interior of a shape. This class cannot be inherited.
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextureBrush(Image bitmap)](#TextureBrush-com.aspose.drawing.Image-) | Initializes a new instance of the [TextureBrush](../../com.aspose.drawing/texturebrush) class that uses the specified image. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.drawing.Image-int-) | Initializes a new instance of the [TextureBrush](../../com.aspose.drawing/texturebrush) class that uses the specified image and wrap mode. |
| [TextureBrush(Image image, int wrapMode, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-) | Initializes a new instance of the [TextureBrush](../../com.aspose.drawing/texturebrush) class that uses the specified image, wrap mode, and bounding rectangle. |
| [TextureBrush(Image image, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-) | 指定された画像と境界矩形を使用する [TextureBrush](../../com.aspose.drawing/texturebrush) クラスの新しいインスタンスを初期化します。 |
| [TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-) | 指定された画像、境界矩形、および画像属性を使用する [TextureBrush](../../com.aspose.drawing/texturebrush) クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getImage()](#getImage--) | この TextureBrush オブジェクトに関連付けられた Image オブジェクトを取得します。 |
| [getTransform()](#getTransform--) | この TextureBrush オブジェクトに関連付けられた画像のローカル幾何変換を定義する Matrix オブジェクトのコピーを取得します。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | この TextureBrush オブジェクトに関連付けられた画像のローカル幾何変換を定義する Matrix オブジェクトのコピーを設定します。 |
| [getWrapMode()](#getWrapMode--) | この TextureBrush オブジェクトのラップモードを示す WrapMode 列挙体を取得します。 |
| [setWrapMode(int value)](#setWrapMode-int-) | この TextureBrush オブジェクトのラップモードを示す WrapMode 列挙体を設定します。 |
| [deepClone()](#deepClone--) | この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトの正確なコピーを作成します。 |
| [resetTransform()](#resetTransform--) | この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトの Transform プロパティを単位行列にリセットします。 |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を表す [Matrix](../../com.aspose.drawing.drawing2d/matrix) オブジェクトに、指定された [Matrix](../../com.aspose.drawing.drawing2d/matrix) オブジェクトを前置して乗算します。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を表す [Matrix](../../com.aspose.drawing.drawing2d/matrix) オブジェクトに、指定された順序で指定された [Matrix](../../com.aspose.drawing.drawing2d/matrix) オブジェクトを乗算します。 |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を、指定された寸法だけ平行移動します。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を、指定された順序で指定された寸法だけ平行移動します。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を、指定された量だけ拡大縮小します。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を、指定された順序で指定された量だけ拡大縮小します。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を、指定された角度だけ回転させます。 |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を、指定された順序で指定された角度だけ回転させます。 |
### TextureBrush(Image bitmap) {#TextureBrush-com.aspose.drawing.Image-}
```
public TextureBrush(Image bitmap)
```


Initializes a new instance of the [TextureBrush](../../com.aspose.drawing/texturebrush) class that uses the specified image.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitmap | [Image](../../com.aspose.drawing/image) | `Image`([.getImage](../../null/\#getImage)) オブジェクトは、この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトが内部を塗りつぶす際に使用されます。 |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.drawing.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Initializes a new instance of the [TextureBrush](../../com.aspose.drawing/texturebrush) class that uses the specified image and wrap mode.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | 画像。 |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) 列挙体は、この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのタイル方式を指定します。 |

### TextureBrush(Image image, int wrapMode, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF dstRect)
```


Initializes a new instance of the [TextureBrush](../../com.aspose.drawing/texturebrush) class that uses the specified image, wrap mode, and bounding rectangle.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | 画像。 |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) 列挙体は、この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのタイル方式を指定します。 |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | [RectangleF](../../com.aspose.drawing/rectanglef) 構造体は、この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトの境界矩形を表します。 |

### TextureBrush(Image image, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, RectangleF dstRect)
```


指定された画像と境界矩形を使用する [TextureBrush](../../com.aspose.drawing/texturebrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | `Image`([.getImage](../../null/\#getImage)) オブジェクトは、この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトが内部を塗りつぶす際に使用されます。 |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | [RectangleF](../../com.aspose.drawing/rectanglef) 構造体は、この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトの境界矩形を表します。 |

### TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)
```


指定された画像、境界矩形、および画像属性を使用する [TextureBrush](../../com.aspose.drawing/texturebrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | この TextureBrush オブジェクトが内部を塗りつぶす際に使用される Image オブジェクトです。 |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | この TextureBrush オブジェクトの境界矩形を表す RectangleF 構造体です。 |
| imageAttr | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) | この TextureBrush オブジェクトで使用される画像に関する追加情報を含む ImageAttributes オブジェクトです。 |

### getImage() {#getImage--}
```
public Image getImage()
```


この TextureBrush オブジェクトに関連付けられた Image オブジェクトを取得します。

**Returns:**
[Image](../../com.aspose.drawing/image) - the Image object associated with this TextureBrush object.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


この TextureBrush オブジェクトに関連付けられた画像のローカル幾何変換を定義する Matrix オブジェクトのコピーを取得します。

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - a copy of the Matrix object that defines a local geometric transformation for the image associated with this TextureBrush object.
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


この TextureBrush オブジェクトに関連付けられた画像のローカル幾何変換を定義する Matrix オブジェクトのコピーを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | この TextureBrush オブジェクトに関連付けられた画像のローカル幾何変換を定義する Matrix オブジェクトのコピーです。 |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


この TextureBrush オブジェクトのラップモードを示す WrapMode 列挙体を取得します。

**Returns:**
int - この TextureBrush オブジェクトのラップモードを示す WrapMode 列挙型です。
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


この TextureBrush オブジェクトのラップモードを示す WrapMode 列挙体を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int | この TextureBrush オブジェクトのラップモードを示す WrapMode 列挙型です。 |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトの正確なコピーを作成します。

**Returns:**
java.lang.Object - このメソッドが作成する [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトを Object オブジェクトとしてキャストしたものです。
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトの Transform プロパティを単位行列にリセットします。

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を表す [Matrix](../../com.aspose.drawing.drawing2d/matrix) オブジェクトに、指定された [Matrix](../../com.aspose.drawing.drawing2d/matrix) オブジェクトを前置して乗算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 幾何変換を乗算するための [Matrix](../../com.aspose.drawing.drawing2d/matrix) オブジェクトです。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を表す [Matrix](../../com.aspose.drawing.drawing2d/matrix) オブジェクトに、指定された順序で指定された [Matrix](../../com.aspose.drawing.drawing2d/matrix) オブジェクトを乗算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 幾何変換を乗算するための [Matrix](../../com.aspose.drawing.drawing2d/matrix) オブジェクトです。 |
| order | int | 2 つの行列を乗算する順序を指定する [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) 列挙型です。 |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を指定された寸法だけ平行移動します。このメソッドは変換の先頭に平行移動を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | float | 変換を x 方向に平行移動させる寸法です。 |
| dy | float | 変換を y 方向に平行移動させる寸法です。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を、指定された順序で指定された寸法だけ平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | float | 変換を x 方向に平行移動させる寸法です。 |
| dy | float | 変換を y 方向に平行移動させる寸法です。 |
| 順序 | int | 平行移動を適用する順序（先頭に追加するか末尾に追加するか）です。 |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を指定された量だけ拡大縮小します。このメソッドは変換の先頭に拡大縮小行列を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sx | float | 変換を x 方向に拡大縮小する量です。 |
| sy | float | 変換を y 方向に拡大縮小する量です。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を、指定された順序で指定された量だけ拡大縮小します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sx | float | 変換を x 方向に拡大縮小する量です。 |
| sy | float | 変換を y 方向に拡大縮小する量です。 |
| order | int | 拡大縮小行列を追加するか先頭に付加するかを指定する [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) 列挙型です。 |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を指定された角度だけ回転させます。このメソッドは変換の先頭に回転を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


この [TextureBrush](../../com.aspose.drawing/texturebrush) オブジェクトのローカル幾何変換を、指定された順序で指定された角度だけ回転させます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度。 |
| order | int | 回転行列を追加するか先頭に付加するかを指定する [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) 列挙型です。 |

