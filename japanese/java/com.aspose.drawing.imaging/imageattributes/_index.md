---
title: ImageAttributes
second_title: Aspose.Drawing for Java API リファレンス
description: ビットマップおよびメタファイルの色がレンダリング中にどのように操作されるかに関する情報を含みます。
type: docs
weight: 24
url: /ja/java/com.aspose.drawing.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class ImageAttributes implements System.IDisposable
```

ビットマップおよびメタファイルの色がレンダリング中にどのように操作されるかに関する情報を含みます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [dispose()](#dispose--) | この [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) オブジェクトが使用しているすべてのリソースを解放します。 |
| [deepClone()](#deepClone--) | この [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) オブジェクトの正確なコピーを作成します。 |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | デフォルトカテゴリのカラー調整行列を設定します。 |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | デフォルトカテゴリのカラー調整行列を設定します。 |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | 指定されたカテゴリのカラー調整行列を設定します。 |
| [clearColorMatrix()](#clearColorMatrix--) | デフォルトカテゴリのカラー調整マトリックスをクリアします。 |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | 指定されたカテゴリのカラー調整マトリックスをクリアします。 |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | デフォルトカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。 |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | デフォルトカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。 |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | 指定されたカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。 |
| [setThreshold(float threshold)](#setThreshold-float-) | デフォルトカテゴリのしきい値（透明度範囲）を設定します。 |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | 指定されたカテゴリのしきい値（透明度範囲）を設定します。 |
| [clearThreshold()](#clearThreshold--) | デフォルトカテゴリのしきい値をクリアします。 |
| [clearThreshold(int type)](#clearThreshold-int-) | 指定されたカテゴリのしきい値をクリアします。 |
| [setGamma(float gamma)](#setGamma-float-) | デフォルトカテゴリのガンマ値を設定します。 |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | 指定されたカテゴリのガンマ値を設定します。 |
| [clearGamma()](#clearGamma--) | デフォルトカテゴリのガンマ補正を無効にします。 |
| [clearGamma(int type)](#clearGamma-int-) | 指定されたカテゴリのガンマ補正を無効にします。 |
| [setNoOp()](#setNoOp--) | デフォルトカテゴリのカラー調整をオフにします。 |
| [setNoOp(int type)](#setNoOp-int-) | 指定されたカテゴリのカラー調整をオフにします。 |
| [clearNoOp()](#clearNoOp--) | デフォルトカテゴリの NoOp 設定をクリアします。 |
| [clearNoOp(int type)](#clearNoOp-int-) | 指定されたカテゴリの NoOp 設定をクリアします。 |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-) | デフォルトカテゴリのカラキーを設定します。 |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | 指定されたカテゴリのカラキー（透明度範囲）を設定します。 |
| [clearColorKey()](#clearColorKey--) | デフォルトカテゴリのカラキー（透明度範囲）をクリアします。 |
| [clearColorKey(int type)](#clearColorKey-int-) | 指定されたカテゴリのカラキー（透明度範囲）をクリアします。 |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | デフォルトカテゴリの CMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネルを設定します。 |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | 指定されたカテゴリの CMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネルを設定します。 |
| [clearOutputChannel()](#clearOutputChannel--) | デフォルトカテゴリの CMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネル設定をクリアします。 |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | 指定されたカテゴリの（シアン・マゼンタ・イエロー・ブラック）出力チャンネル設定をクリアします。 |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | デフォルトカテゴリの出力チャンネルカラープロファイルファイルを設定します。 |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | 指定されたカテゴリの出力チャネル カラープロファイル ファイルを設定します。 |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | デフォルトカテゴリの出力チャネル カラープロファイル設定をクリアします。 |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | 指定されたカテゴリの出力チャネル カラープロファイル設定をクリアします。 |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---) | デフォルトカテゴリのカラーリマップテーブルを設定します。 |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-) | 指定されたカテゴリのカラーリマップテーブルを設定します。 |
| [clearRemapTable()](#clearRemapTable--) | デフォルトカテゴリのカラーリマップテーブルをクリアします。 |
| [clearRemapTable(int type)](#clearRemapTable-int-) | 指定されたカテゴリのカラーリマップテーブルをクリアします。 |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---) | ブラシカテゴリのカラーリマップテーブルを設定します。 |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | この [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) オブジェクトのブラシ カラーリマップテーブルをクリアします。 |
| [setWrapMode(int mode)](#setWrapMode-int-) | テクスチャをシェイプ全体またはシェイプ境界でタイル配置する方法を決定するために使用されるラップモードを設定します。 |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.drawing.Color-) | テクスチャをシェイプ全体またはシェイプ境界でタイル配置する方法を決定するために使用されるラップモードとカラーを設定します。 |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.drawing.Color-boolean-) | テクスチャをシェイプ全体またはシェイプ境界でタイル配置する方法を決定するために使用されるラップモードとカラーを設定します。 |
| [getAdjustedPalette(ColorPalette palette, int type)](#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-) | 指定されたカテゴリの調整設定に従ってパレット内の色を調整します。 |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


[ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) クラスの新しいインスタンスを初期化します。

### dispose() {#dispose--}
```
public void dispose()
```


この [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) オブジェクトが使用しているすべてのリソースを解放します。

### deepClone() {#deepClone--}
```
public Object deepClone()
```


この [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) オブジェクトの正確なコピーを作成します。

**Returns:**
java.lang.Object - このクラスが作成する [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) オブジェクトをオブジェクトとしてキャストしたものです。
### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


デフォルトカテゴリのカラー調整行列を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | カラー調整マトリックスです。 |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


デフォルトカテゴリのカラー調整行列を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | カラー調整マトリックスです。 |
| flags | int | [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) の要素で、カラー調整マトリックスの影響を受ける画像とカラーのタイプを指定します。 |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


指定されたカテゴリのカラー調整行列を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | カラー調整マトリックスです。 |
| mode | int | [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) の要素で、カラー調整マトリックスの影響を受ける画像とカラーのタイプを指定します。 |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素で、カラー調整マトリックスが設定されるカテゴリを指定します。 |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


デフォルトカテゴリのカラー調整マトリックスをクリアします。

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


指定されたカテゴリのカラー調整マトリックスをクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素で、カラー調整マトリックスがクリアされるカテゴリを指定します。 |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


デフォルトカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | カラー調整マトリックスです。 |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | グレースケール調整マトリックスです。 |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


デフォルトカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | カラー調整マトリックスです。 |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | グレースケール調整マトリックスです。 |
| flags | int | [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) の要素で、カラー調整およびグレースケール調整マトリックスの影響を受ける画像とカラーのタイプを指定します。 |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


指定されたカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | カラー調整マトリックスです。 |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | グレースケール調整マトリックスです。 |
| mode | int | [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) の要素で、カラー調整およびグレースケール調整マトリックスの影響を受ける画像とカラーのタイプを指定します。 |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素で、カラー調整およびグレースケール調整マトリックスが設定されるカテゴリを指定します。 |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


デフォルトカテゴリのしきい値（透明度範囲）を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| しきい値 | float | しきい値を指定する実数です。 |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


指定されたカテゴリのしきい値（透明度範囲）を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| しきい値 | float | 0.0 から 1.0 の範囲のしきい値で、最大値または最小値にマッピングされる色を分類するブレークポイントとして使用されます。 |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素で、カラーしきい値が設定されるカテゴリを指定します。 |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


デフォルトカテゴリのしきい値をクリアします。

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


指定されたカテゴリのしきい値をクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素で、しきい値がクリアされるカテゴリを指定します。 |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


デフォルトカテゴリのガンマ値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ガンマ | float | ガンマ補正値です。 |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


指定されたカテゴリのガンマ値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ガンマ | float | ガンマ補正値です。 |
| type | int | ガンマ値が設定されるカテゴリを指定する、[ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 列挙体の要素です。 |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


デフォルトカテゴリのガンマ補正を無効にします。

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


指定されたカテゴリのガンマ補正を無効にします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | ガンマ補正が無効になるカテゴリを指定する、[ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素です。 |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


デフォルトカテゴリのカラー調整をオフにします。 [.clearNoOp](../../null/\#clearNoOp) メソッドを呼び出すと、 [.setNoOp](../../null/\#setNoOp) メソッドを呼び出す前に設定されていたカラー調整設定を復元できます。

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


指定されたカテゴリのカラー調整をオフにします。 [.clearNoOp](../../null/\#clearNoOp) メソッドを呼び出すと、 [.setNoOp](../../null/\#setNoOp) メソッドを呼び出す前に設定されていたカラー調整設定を復元できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | カラー補正がオフになるカテゴリを指定する、[ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素です。 |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


デフォルトカテゴリの NoOp 設定をクリアします。

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


指定されたカテゴリの NoOp 設定をクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | NoOp 設定がクリアされるカテゴリを指定する、[ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素です。 |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


デフォルトカテゴリのカラキーを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | 低いカラーキー値です。 |
| colorHigh | [Color](../../com.aspose.drawing/color) | 高いカラーキー値です。 |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


指定されたカテゴリのカラキー（透明度範囲）を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | 低いカラーキー値です。 |
| colorHigh | [Color](../../com.aspose.drawing/color) | 高いカラーキー値です。 |
| type | int | カラーキーが設定されるカテゴリを指定する、[ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素です。 |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


デフォルトカテゴリのカラキー（透明度範囲）をクリアします。

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


指定されたカテゴリのカラキー（透明度範囲）をクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | カラーキーがクリアされるカテゴリを指定する、[ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素です。 |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


デフォルトカテゴリの CMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| flags | int | [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) の要素で、出力チャンネルを指定します。 |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


指定されたカテゴリの CMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| flags | int | [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) の要素で、出力チャンネルを指定します。 |
| type | int | 出力チャンネルが設定されるカテゴリを指定する、[ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素です。 |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


デフォルトカテゴリの CMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネル設定をクリアします。

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


指定されたカテゴリの（シアン・マゼンタ・イエロー・ブラック）出力チャンネル設定をクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | 出力チャンネル設定がクリアされるカテゴリを指定する、[ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素です。 |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


デフォルトカテゴリの出力チャンネルカラープロファイルファイルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | カラー プロファイル ファイルのパス名です。カラー プロファイル ファイルが %SystemRoot%\\System32\\Spool\\Drivers\\Color ディレクトリにある場合、このパラメータはファイル名を指定できます。それ以外の場合は、完全修飾パス名を指定する必要があります。 |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


指定されたカテゴリの出力チャネル カラープロファイル ファイルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | カラー プロファイル ファイルのパス名です。カラー プロファイル ファイルが %SystemRoot%\\System32\\Spool\\Drivers\\Color ディレクトリにある場合、このパラメータはファイル名を指定できます。それ以外の場合は、完全修飾パス名を指定する必要があります。 |
| type | int | 出力チャンネルのカラー プロファイル ファイルが設定されるカテゴリを指定する、[ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素です。 |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


デフォルトカテゴリの出力チャネル カラープロファイル設定をクリアします。

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


指定されたカテゴリの出力チャネル カラープロファイル設定をクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | 出力チャンネル プロファイル設定がクリアされるカテゴリを指定する、[ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素です。 |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


デフォルトカテゴリのカラーリマップテーブルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | タイプが [ColorMap](../../com.aspose.drawing.imaging/colormap) のカラー ペアの配列です。各カラー ペアは、既存のカラー（最初の値）と、マッピング先のカラー（2 番目の値）を含みます。 |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


指定されたカテゴリのカラーリマップテーブルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | タイプが [ColorMap](../../com.aspose.drawing.imaging/colormap) のカラー ペアの配列です。各カラー ペアは、既存のカラー（最初の値）と、マッピング先のカラー（2 番目の値）を含みます。 |
| type | int | カラーリマップ テーブルが設定されるカテゴリを指定する、[ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素です。 |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


デフォルトカテゴリのカラーリマップテーブルをクリアします。

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


指定されたカテゴリのカラーリマップテーブルをクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | リマップ テーブルがクリアされるカテゴリを指定する、[ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素です。 |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


ブラシカテゴリのカラーリマップテーブルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | [ColorMap](../../com.aspose.drawing.imaging/colormap) オブジェクトの配列です。 |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


この [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) オブジェクトのブラシ カラーリマップテーブルをクリアします。

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


テクスチャをシェイプ全体またはシェイプ境界にタイル配置する方法を決定するために使用されるラップ モードを設定します。テクスチャがシェイプより小さい場合、テクスチャはシェイプ全体を埋めるようにタイル配置されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mode | int | [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) の要素で、画像の繰り返しコピーを使用して領域をタイル配置する方法を指定します。 |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.drawing.Color-}
```
public void setWrapMode(int mode, Color color)
```


テクスチャを形状全体または形状の境界でタイル配置する方法を決定するために使用されるラップモードと色を設定します。テクスチャが対象の形状より小さい場合、テクスチャは形状全体にタイル配置されて埋められます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mode | int | [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) の要素で、画像の繰り返しコピーを使用して領域をタイル配置する方法を指定します。 |
| color | [Color](../../com.aspose.drawing/color) | [Color](../../com.aspose.drawing/color) オブジェクトで、レンダリングされた画像の外側のピクセルの色を指定します。モードパラメータが `WrapMode.Clamp` に設定され、`Graphics.DrawImage` に渡されるソース矩形が画像自体より大きい場合、この色が表示されます。 |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.drawing.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


テクスチャを形状全体または形状の境界でタイル配置する方法を決定するために使用されるラップモードと色を設定します。テクスチャが対象の形状より小さい場合、テクスチャは形状全体にタイル配置されて埋められます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mode | int | [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) の要素で、画像の繰り返しコピーを使用して領域をタイル配置する方法を指定します。 |
| color | [Color](../../com.aspose.drawing/color) | レンダリングされた画像の外側のピクセルの色を指定するカラーオブジェクトです。モードパラメータが `WrapMode.Clamp` に設定され、`Graphics.DrawImage` に渡されるソース矩形が画像自体より大きい場合、この色が表示されます。 |
| クランプ | boolean | このパラメータは効果がありません。false に設定してください。 |

### getAdjustedPalette(ColorPalette palette, int type) {#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-}
```
public void getAdjustedPalette(ColorPalette palette, int type)
```


指定されたカテゴリの調整設定に従ってパレット内の色を調整します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| palette | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) で、入力時には調整対象のパレットが含まれ、出力時には調整後のパレットが含まれます。 |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) の要素で、パレットに適用される調整設定のカテゴリを指定します。 |

