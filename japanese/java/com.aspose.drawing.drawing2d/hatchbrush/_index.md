---
title: HatchBrush
second_title: Aspose.Drawing for Java API リファレンス
description: ハッチスタイル、前景色、背景色を持つ矩形ブラシを定義します。
type: docs
weight: 26
url: /ja/java/com.aspose.drawing.drawing2d/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class HatchBrush extends Brush
```

ハッチスタイル、前景色、背景色を持つ矩形ブラシを定義します。このクラスは継承できません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HatchBrush(int hatchstyle, Color foreColor)](#HatchBrush-int-com.aspose.drawing.Color-) | 指定された `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) 列挙体と前景色を使用して、[HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) クラスの新しいインスタンスを初期化します。 |
| [HatchBrush(int hatchstyle, Color foreColor, Color backColor)](#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-) | 指定された `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) 列挙体、前景色、および背景色を使用して、[HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHatchStyle()](#getHatchStyle--) | この [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) オブジェクトのハッチスタイルを取得します。 |
| [getForegroundColor()](#getForegroundColor--) | この [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) オブジェクトが描画するハッチ線の色を取得します。 |
| [getBackgroundColor()](#getBackgroundColor--) | この [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) オブジェクトが描画するハッチ線間の空白の色を取得します。 |
| [deepClone()](#deepClone--) | この [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) オブジェクトの正確なコピーを作成します。 |
### HatchBrush(int hatchstyle, Color foreColor) {#HatchBrush-int-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor)
```


指定された `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) 列挙体と前景色を使用して、[HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| hatchstyle | int | この [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) が描画するパターンを表す `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) の値の一つです。 |
| foreColor | [Color](../../com.aspose.drawing/color) | この [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) が描画する線の色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |

### HatchBrush(int hatchstyle, Color foreColor, Color backColor) {#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor, Color backColor)
```


指定された `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) 列挙体、前景色、および背景色を使用して、[HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| hatchstyle | int | この [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) が描画するパターンを表す `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) の値の一つです。 |
| foreColor | [Color](../../com.aspose.drawing/color) | この [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) が描画する線の色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |
| backColor | [Color](../../com.aspose.drawing/color) | この [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) が描画する線間の空白の色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


この [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) オブジェクトのハッチスタイルを取得します。

**Returns:**
int - この [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) オブジェクトのハッチスタイルです。
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


この [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) オブジェクトが描画するハッチ線の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


この [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) オブジェクトが描画するハッチ線間の空白の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of spaces between the hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


この [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) オブジェクトの正確なコピーを作成します。

**Returns:**
java.lang.Object - このメソッドが作成し、オブジェクトとしてキャストされた [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) です。
