---
title: ColorPalette
second_title: Aspose.Drawing for Java API リファレンス
description: カラーパレットを構成する色の配列を定義します。
type: docs
weight: 16
url: /ja/java/com.aspose.drawing.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPalette
```

カラーパレットを構成する色の配列を定義します。色は 32 ビット ARGB カラーです。継承できません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ColorPalette(int count)](#ColorPalette-int-) | `ColorPalette` クラスの新しいインスタンスを初期化し、IsCompactPalette は false です。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEntries()](#getEntries--) | `com.aspose.drawing.Color` 構造体の配列を取得します。 |
| [isCompactPalette()](#isCompactPalette--) | コンパクトパレットが使用されているかどうかを示す値を取得または設定します。 |
| [getFlags()](#getFlags--) |  |
| [setFlags(int flags)](#setFlags-int-) |  |
| [setEntries(int i, Color color)](#setEntries-int-com.aspose.drawing.Color-) |  |
### ColorPalette(int count) {#ColorPalette-int-}
```
public ColorPalette(int count)
```


`ColorPalette` クラスの新しいインスタンスを初期化し、IsCompactPalette は false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| count | int | カラーパレットのエントリです。 |

### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


`com.aspose.drawing.Color` 構造体の配列を取得します。

**Returns:**
com.aspose.drawing.Color[] - エントリ。`com.aspose.drawing.Color` 構造体の配列で、この `Aspose.Imaging.ColorPalette` を構成します。
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


コンパクトパレットが使用されているかどうかを示す値を取得または設定します。

**Returns:**
boolean - コンパクトパレットが使用されている場合は `true`、それ以外は `false`。

コンパクトパレットとは、可能な限り指定されたパレットエントリのみを画像が含むことを意味し、言い換えれば画像がよりコンパクトになり、占有スペースが少なくなります。そうでない場合、2^BitsPerPixel のエントリが存在し、画像はすべての可能なパレットエントリ用により多くのスペースを確保します。この値を true に設定し、パレットエントリを変更すると、データの移動が発生する可能性があるためパフォーマンスにペナルティがかかることがあります。慎重に使用してください。
### getFlags() {#getFlags--}
```
public int getFlags()
```




**Returns:**
int
### setFlags(int flags) {#setFlags-int-}
```
public void setFlags(int flags)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| flags | int |  |

### setEntries(int i, Color color) {#setEntries-int-com.aspose.drawing.Color-}
```
public void setEntries(int i, Color color)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| i | int |  |
| color | [Color](../../com.aspose.drawing/color) |  |

