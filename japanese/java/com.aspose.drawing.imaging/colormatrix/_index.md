---
title: ColorMatrix
second_title: Aspose.Drawing for Java API リファレンス
description: RGBA 空間の座標を含む 5 x 5 行列を定義します。
type: docs
weight: 14
url: /ja/java/com.aspose.drawing.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

RGBA 空間の座標を含む 5 x 5 行列を定義します。[ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) クラスのいくつかのメソッドは、カラー行列を使用して画像の色を調整します。このクラスは継承できません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | 新しい [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) クラスのインスタンスを初期化します。 |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | 指定された行列 `newColorMatrix` の要素を使用して、新しい [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の 0（ゼロ）行 0 列の要素を取得します。 |
| [setMatrix00(float value)](#setMatrix00-float-) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の 0（ゼロ）行 0 列の要素を設定します。 |
| [getMatrix01()](#getMatrix01--) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の 0（ゼロ）行の最初の列の要素を取得します。 |
| [setMatrix01(float value)](#setMatrix01-float-) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の 0（ゼロ）行の最初の列の要素を設定します。 |
| [getMatrix02()](#getMatrix02--) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の 0（ゼロ）行の2番目の列の要素を取得します。 |
| [setMatrix02(float value)](#setMatrix02-float-) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の 0（ゼロ）行の2番目の列の要素を設定します。 |
| [getMatrix03()](#getMatrix03--) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の 0（ゼロ）行の3番目の列の要素を取得します。 |
| [setMatrix03(float value)](#setMatrix03-float-) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目と第3列の要素を設定します。 |
| [getMatrix04()](#getMatrix04--) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目と第4列の要素を取得します。 |
| [setMatrix04(float value)](#setMatrix04-float-) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目と第4列の要素を設定します。 |
| [getMatrix10()](#getMatrix10--) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と0（ゼロ）列の要素を取得します。 |
| [setMatrix10(float value)](#setMatrix10-float-) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と0（ゼロ）列の要素を設定します。 |
| [getMatrix11()](#getMatrix11--) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第1列の要素を取得します。 |
| [setMatrix11(float value)](#setMatrix11-float-) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第1列の要素を設定します。 |
| [getMatrix12()](#getMatrix12--) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第2列の要素を取得します。 |
| [setMatrix12(float value)](#setMatrix12-float-) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第2列の要素を設定します。 |
| [getMatrix13()](#getMatrix13--) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第3列の要素を取得します。 |
| [setMatrix13(float value)](#setMatrix13-float-) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第3列の要素を設定します。 |
| [getMatrix14()](#getMatrix14--) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第4列の要素を取得します。 |
| [setMatrix14(float value)](#setMatrix14-float-) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第4列の要素を設定します。 |
| [getMatrix20()](#getMatrix20--) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と0（ゼロ）列の要素を取得します。 |
| [setMatrix20(float value)](#setMatrix20-float-) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と0（ゼロ）列の要素を設定します。 |
| [getMatrix21()](#getMatrix21--) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第1列の要素を取得します。 |
| [setMatrix21(float value)](#setMatrix21-float-) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第1列の要素を設定します。 |
| [getMatrix22()](#getMatrix22--) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第2列の要素を取得します。 |
| [setMatrix22(float value)](#setMatrix22-float-) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第2列の要素を設定します。 |
| [getMatrix23()](#getMatrix23--) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第3列の要素を取得します。 |
| [setMatrix23(float value)](#setMatrix23-float-) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第3列の要素を設定します。 |
| [getMatrix24()](#getMatrix24--) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第4列の要素を取得します。 |
| [setMatrix24(float value)](#setMatrix24-float-) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第4列の要素を設定します。 |
| [getMatrix30()](#getMatrix30--) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目と0（ゼロ）列の要素を取得します。 |
| [setMatrix30(float value)](#setMatrix30-float-) | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目と0（ゼロ）列の要素を設定します。 |
| [getMatrix31()](#getMatrix31--) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第1列目の要素を取得します。 |
| [setMatrix31(float value)](#setMatrix31-float-) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第1列目の要素を設定します。 |
| [getMatrix32()](#getMatrix32--) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第2列目の要素を取得します。 |
| [setMatrix32(float value)](#setMatrix32-float-) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第2列目の要素を設定します。 |
| [getMatrix33()](#getMatrix33--) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第3列目の要素を取得します。 |
| [setMatrix33(float value)](#setMatrix33-float-) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第3列目の要素を設定します。 |
| [getMatrix34()](#getMatrix34--) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第4列目の要素を取得します。 |
| [setMatrix34(float value)](#setMatrix34-float-) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第4列目の要素を設定します。 |
| [getMatrix40()](#getMatrix40--) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ0（ゼロ）列目の要素を取得します。 |
| [setMatrix40(float value)](#setMatrix40-float-) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ0（ゼロ）列目の要素を設定します。 |
| [getMatrix41()](#getMatrix41--) | この `.ColorMatrix` の第4行目かつ第1列目の要素を取得します。 |
| [setMatrix41(float value)](#setMatrix41-float-) | この `.ColorMatrix` の第4行目かつ第1列目の要素を設定します。 |
| [getMatrix42()](#getMatrix42--) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ第2列目の要素を取得します。 |
| [setMatrix42(float value)](#setMatrix42-float-) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ第2列目の要素を設定します。 |
| [getMatrix43()](#getMatrix43--) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ第3列目の要素を取得します。 |
| [setMatrix43(float value)](#setMatrix43-float-) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ第3列目の要素を設定します。 |
| [getMatrix44()](#getMatrix44--) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ第4列目の要素を取得します。 |
| [setMatrix44(float value)](#setMatrix44-float-) | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ第4列目の要素を設定します。 |
| [get_Item(int row, int column)](#get-Item-int-int-) | 指定された行と列の要素をこの [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) から取得します。 |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | 指定された行と列の要素をこの [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) に設定します。 |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


新しい [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) クラスのインスタンスを初期化します。

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


指定された行列 `newColorMatrix` の要素を使用して、新しい [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorMatrix | float[][] | 新しい [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の要素の値です。 |

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の 0（ゼロ）行 0 列の要素を取得します。

**Returns:**
float - この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目かつ0列目の要素です。
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の 0（ゼロ）行 0 列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目かつ0列目の要素です。 |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の 0（ゼロ）行の最初の列の要素を取得します。

**Returns:**
float - この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目かつ第1列目の要素です。
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の 0（ゼロ）行の最初の列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目かつ第1列目の要素です。 |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の 0（ゼロ）行の2番目の列の要素を取得します。

**Returns:**
float - この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目と第2列目の要素。
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の 0（ゼロ）行の2番目の列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目と第2列目の要素。 |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の 0（ゼロ）行の3番目の列の要素を取得します。

**Returns:**
float - この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目と第3列目の要素。
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目と第3列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目と第3列目の要素。 |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目と第4列の要素を取得します。

**Returns:**
float - この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目と第4列目の要素。
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目と第4列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の0（ゼロ）行目と第4列目の要素。 |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と0（ゼロ）列の要素を取得します。

**Returns:**
float - この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と0（ゼロ）列目の要素。
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と0（ゼロ）列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と0（ゼロ）列目の要素。 |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第1列の要素を取得します。

**Returns:**
float - この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第1列目の要素。
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第1列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第1列目の要素。 |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第2列の要素を取得します。

**Returns:**
float - この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第2列目の要素。
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第2列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第2列目の要素。 |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第3列の要素を取得します。

**Returns:**
float - この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第3列目の要素。
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第3列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第3列目の要素。 |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第4列の要素を取得します。

**Returns:**
float - この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第4列目の要素。
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第4列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第1行目と第4列目の要素。 |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と0（ゼロ）列の要素を取得します。

**Returns:**
float - この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と0（ゼロ）列目の要素。
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と0（ゼロ）列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と0（ゼロ）列目の要素。 |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第1列の要素を取得します。

**Returns:**
float - この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第1列目の要素。
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第1列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第1列目の要素。 |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第2列の要素を取得します。

**Returns:**
float - この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第2列目の要素。
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第2列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第2列目の要素。 |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第3列の要素を取得します。

**Returns:**
float - この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第3列目の要素。
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第3列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第3列目の要素。 |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第4列の要素を取得します。

**Returns:**
float - この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第4列目の要素。
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第2行目と第4列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第2行第4列の要素。 |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目と0（ゼロ）列の要素を取得します。

**Returns:**
float - この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第3行0（ゼロ）列の要素。
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目と0（ゼロ）列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第3行0（ゼロ）列の要素。 |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第1列目の要素を取得します。

**Returns:**
float - この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第3行第1列の要素。
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第1列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第3行第1列の要素。 |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第2列目の要素を取得します。

**Returns:**
float - この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第3行第2列の要素。
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第2列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第3行第2列の要素。 |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第3列目の要素を取得します。

**Returns:**
float - この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第3行第3列の要素。
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第3列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第3行第3列の要素。 |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第4列目の要素を取得します。

**Returns:**
float - この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第3行第4列の要素。
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第3行目かつ第4列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第3行第4列の要素。 |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ0（ゼロ）列目の要素を取得します。

**Returns:**
float - この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第4行0（ゼロ）列の要素。
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ0（ゼロ）列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第4行0（ゼロ）列の要素。 |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


この `.ColorMatrix` の第4行目かつ第1列目の要素を取得します。

**Returns:**
float - この`.ColorMatrix`の第4行第1列の要素。
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


この `.ColorMatrix` の第4行目かつ第1列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この`.ColorMatrix`の第4行第1列の要素。 |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ第2列目の要素を取得します。

**Returns:**
float - この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第4行第2列の要素。
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ第2列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第4行第2列の要素。 |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ第3列目の要素を取得します。

**Returns:**
float - この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第4行第3列の要素。
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ第3列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第4行第3列の要素。 |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ第4列目の要素を取得します。

**Returns:**
float - この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第4行第4列の要素。
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


この [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) の第4行目かつ第4列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float | この[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)の第4行第4列の要素。 |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


指定された行と列の要素をこの [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) から取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 行 | int | 要素の行。 |
| 列 | int | 要素の列。 |

**Returns:**
float - 指定された行と列の要素です。
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


指定された行と列の要素をこの [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) に設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 行 | int | 要素の行。 |
| 列 | int | 要素の列。 |
| value | float | 指定された行と列の要素は [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) にあります。 |

