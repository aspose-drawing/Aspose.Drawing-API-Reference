---
title: BitmapData
second_title: Aspose.Drawing for Java API リファレンス
description: ビットマップ画像の属性を指定します。
type: docs
weight: 10
url: /ja/java/com.aspose.drawing.imaging/bitmapdata/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapData
```

ビットマップ画像の属性を指定します。[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) クラスは、[Bitmap](../../com.aspose.drawing/bitmap) クラスの `E:Bitmap.LockBits` および `M:Bitmap.UnlockBits(BitmapData)` メソッドで使用されます。継承できません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BitmapData()](#BitmapData--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getWidth()](#getWidth--) | [Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのピクセル幅を取得します。 |
| [setWidth(int value)](#setWidth-int-) | [Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのピクセル幅を設定します。 |
| [getHeight()](#getHeight--) | [Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのピクセル高さを取得します。 |
| [setHeight(int value)](#setHeight-int-) | [Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのピクセル高さを設定します。 |
| [getStride()](#getStride--) | [Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのストライド幅（スキャン幅とも呼ばれます）を取得します。 |
| [setStride(int value)](#setStride-int-) | [Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのストライド幅（スキャン幅とも呼ばれます）を設定します。 |
| [getPixelFormat()](#getPixelFormat--) | この [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) オブジェクトを返した [Bitmap](../../com.aspose.drawing/bitmap) オブジェクト内のピクセル情報の形式を取得します。 |
| [setPixelFormat(int value)](#setPixelFormat-int-) | この [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) オブジェクトを返した [Bitmap](../../com.aspose.drawing/bitmap) オブジェクト内のピクセル情報の形式を設定します。 |
| [getScan0()](#getScan0--) | ビットマップ内の最初のピクセルデータのアドレスを取得します。 |
| [setScan0(int[] value)](#setScan0-int---) | ビットマップ内の最初のピクセルデータのアドレスを設定します。 |
### BitmapData() {#BitmapData--}
```
public BitmapData()
```


### getWidth() {#getWidth--}
```
public int getWidth()
```


[Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのピクセル幅を取得します。これは 1 スキャンライン内のピクセル数と考えることもできます。

**Returns:**
int - [Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのピクセル幅。
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


[Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのピクセル幅を設定します。これは 1 行のスキャンラインあたりのピクセル数と考えることもできます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int | [Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのピクセル幅。 |

### getHeight() {#getHeight--}
```
public int getHeight()
```


[Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのピクセル高さを取得します。また、スキャンライン数と呼ばれることもあります。

**Returns:**
int - [Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのピクセル高さ。
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


[Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのピクセル高さを設定します。また、スキャンライン数と呼ばれることもあります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int | [Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのピクセル高さ。 |

### getStride() {#getStride--}
```
public int getStride()
```


[Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのストライド幅（スキャン幅とも呼ばれます）を取得します。

**Returns:**
int - [Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのストライド幅（バイト単位）。
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


[Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのストライド幅（スキャン幅とも呼ばれます）を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int | [Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのストライド幅（スキャン幅とも呼ばれます）。 |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


この [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) オブジェクトを返した [Bitmap](../../com.aspose.drawing/bitmap) オブジェクト内のピクセル情報の形式を取得します。

**Returns:**
int - 関連付けられた [Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのピクセル情報の形式を指定する `PixelFormat`（[.getPixelFormat](../../null/\#getPixelFormat)/[.setPixelFormat(int)](../../null/\#setPixelFormat-int-)）。
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


この [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) オブジェクトを返した [Bitmap](../../com.aspose.drawing/bitmap) オブジェクト内のピクセル情報の形式を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int | この [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) オブジェクトを返した [Bitmap](../../com.aspose.drawing/bitmap) オブジェクトのピクセル情報の形式。 |

### getScan0() {#getScan0--}
```
public int[] getScan0()
```


ビットマップ内の最初のピクセルデータのアドレスを取得します。これはビットマップの最初のスキャンラインと考えることもできます。

**Returns:**
int[] - ビットマップ内の最初のピクセルデータのアドレス。
### setScan0(int[] value) {#setScan0-int---}
```
public void setScan0(int[] value)
```


ビットマップ内の最初のピクセルデータのアドレスを設定します。これはビットマップの最初のスキャンラインと考えることもできます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int[] | ビットマップ内の最初のピクセルデータのアドレス。 |

