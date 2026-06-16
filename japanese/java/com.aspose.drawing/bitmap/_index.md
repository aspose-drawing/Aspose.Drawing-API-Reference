---
title: ビットマップ
second_title: Aspose.Drawing for Java API リファレンス
description: グラフィック画像のピクセルデータと属性で構成されるビットマップをカプセル化します。
type: docs
weight: 10
url: /ja/java/com.aspose.drawing/bitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public class Bitmap extends Image
```

グラフィック画像のピクセルデータと属性で構成されるビットマップをカプセル化します。[Bitmap](../../com.aspose.drawing/bitmap) は、ピクセルデータで定義された画像を操作するために使用されるオブジェクトです。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Bitmap(int width, int height)](#Bitmap-int-int-) | 指定されたサイズで [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。 |
| [Bitmap(String filename)](#Bitmap-java.lang.String-) | 指定されたファイルから [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。 |
| [Bitmap(String filename, boolean useIcm)](#Bitmap-java.lang.String-boolean-) | 指定されたファイルから [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。 |
| [Bitmap(InputStream stream)](#Bitmap-java.io.InputStream-) | 指定されたデータストリームから [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。 |
| [Bitmap(InputStream stream, boolean useIcm)](#Bitmap-java.io.InputStream-boolean-) | 指定されたデータストリームから [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。 |
| [Bitmap(int width, int height, int format)](#Bitmap-int-int-int-) | 指定されたサイズとフォーマットで [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。 |
| [Bitmap(int width, int height, int stride, int format, int[] data)](#Bitmap-int-int-int-int-int---) | 指定されたサイズとピクセルデータで [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。 |
| [Bitmap(Image original)](#Bitmap-com.aspose.drawing.Image-) | 指定された既存の画像から [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。 |
| [Bitmap(Image original, Size newSize)](#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-) | 指定された既存の画像から、指定されたサイズにスケーリングされた [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。 |
| [Bitmap(Image original, int width, int height)](#Bitmap-com.aspose.drawing.Image-int-int-) | 指定された既存の画像から、指定されたサイズにスケーリングされた [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getWidth()](#getWidth--) | このビットマップの幅（ピクセル単位）を取得します。 |
| [getHeight()](#getHeight--) | このビットマップの高さ（ピクセル単位）を取得します。 |
| [getRawFormat()](#getRawFormat--) | この [Image](../../com.aspose.drawing/image) のファイル形式を取得します。 |
| [getPixelFormat()](#getPixelFormat--) | この [Image](../../com.aspose.drawing/image) のピクセル形式を取得します。 |
| [getPalette()](#getPalette--) | この [Image](../../com.aspose.drawing/image) に使用されるカラーパレットを取得または設定します。 |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | この [Image](../../com.aspose.drawing/image) に使用されるカラーパレットを取得または設定します。 |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | この [Image](../../com.aspose.drawing/image) 内のフレームの次元を表す GUID の配列を取得します。 |
| [getPropertyIdList()](#getPropertyIdList--) | この [Image](../../com.aspose.drawing/image) に格納されているプロパティ項目の ID を取得します。 |
| [getPropertyItems()](#getPropertyItems--) | この [Image](../../com.aspose.drawing/image) に格納されているすべてのプロパティ項目（メタデータの一部）を取得します。 |
| [deepClone(Rectangle rect, int format)](#deepClone-com.aspose.drawing.Rectangle-int-) | この [Bitmap](../../com.aspose.drawing/bitmap) の、[Rectangle](../../com.aspose.drawing/rectangle) 構造で定義されたセクションのコピーを作成し、指定された `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 列挙体を使用します。 |
| [deepClone(RectangleF rect, int format)](#deepClone-com.aspose.drawing.RectangleF-int-) | この [Bitmap](../../com.aspose.drawing/bitmap) の、指定された [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) 列挙体で定義されたセクションのコピーを作成します。 |
| [setResolution(float xDpi, float yDpi)](#setResolution-float-float-) | この [Bitmap](../../com.aspose.drawing/bitmap) の解像度を設定します。 |
| [lockBits(Rectangle rect, int flags, int format)](#lockBits-com.aspose.drawing.Rectangle-int-int-) | システムメモリに [Bitmap](../../com.aspose.drawing/bitmap) をロックします。 |
| [unlockBits(BitmapData bitmapData)](#unlockBits-com.aspose.drawing.imaging.BitmapData-) | システムメモリからこの [Bitmap](../../com.aspose.drawing/bitmap) のロックを解除します。 |
| [getPixel(int x, int y)](#getPixel-int-int-) | この [Bitmap](../../com.aspose.drawing/bitmap) の指定されたピクセルの色を取得します。 |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.drawing.Color-) | この [Bitmap](../../com.aspose.drawing/bitmap) の指定されたピクセルの色を設定します。 |
| [readArgb32Pixels(int[] pixels)](#readArgb32Pixels-int---) | ビットマップのピクセルを ARGB32 形式で指定された配列に読み取ります。 |
| [writeArgb32Pixels(int[] pixels)](#writeArgb32Pixels-int---) | ビットマップにピクセルを書き込みます。 |
| [makeTransparent()](#makeTransparent--) | この [Bitmap](../../com.aspose.drawing/bitmap) の指定された色を透明にします。 |
| [makeTransparent(Color transparentColor)](#makeTransparent-com.aspose.drawing.Color-) | この [Bitmap](../../com.aspose.drawing/bitmap) の指定された色を透明にします。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | このメソッドは、[Image](../../com.aspose.drawing/image) を回転、反転、または回転と反転を行います。 |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | この [Image](../../com.aspose.drawing/image) から指定されたプロパティ項目を取得します。 |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | この [Image](../../com.aspose.drawing/image) から指定されたプロパティ項目を削除します。 |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | この [Image](../../com.aspose.drawing/image) にプロパティ項目（メタデータの一部）を格納します。 |
### Bitmap(int width, int height) {#Bitmap-int-int-}
```
public Bitmap(int width, int height)
```


指定されたサイズで [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 | int | 新しい Bitmap の幅（ピクセル単位）。 |
|  | 高さ | int | 新しい Bitmap の高さ（ピクセル単位）。 |

--------------------

現在サポートされている唯一の内部ビットマップ形式は `PixelFormat.Format32bppPArgb` と同等です。 |

### Bitmap(String filename) {#Bitmap-java.lang.String-}
```
public Bitmap(String filename)
```


指定されたファイルから [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | java.lang.String | ビットマップファイルの名前です。 |

### Bitmap(String filename, boolean useIcm) {#Bitmap-java.lang.String-boolean-}
```
public Bitmap(String filename, boolean useIcm)
```


指定されたファイルから [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | java.lang.String | ビットマップファイルの名前です。 |
| useIcm | boolean | この [Bitmap](../../com.aspose.drawing/bitmap) にカラー補正を使用する場合は true、そうでない場合は false。 |

### Bitmap(InputStream stream) {#Bitmap-java.io.InputStream-}
```
public Bitmap(InputStream stream)
```


指定されたデータストリームから [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 画像の読み込みに使用されるデータストリームです。 |

### Bitmap(InputStream stream, boolean useIcm) {#Bitmap-java.io.InputStream-boolean-}
```
public Bitmap(InputStream stream, boolean useIcm)
```


指定されたデータストリームから [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 画像の読み込みに使用されるデータストリームです。 |
| useIcm | boolean | `true` はこの [Bitmap](../../com.aspose.drawing/bitmap) にカラー補正を使用することを意味し、`false` は使用しないことを意味します。 |

### Bitmap(int width, int height, int format) {#Bitmap-int-int-int-}
```
public Bitmap(int width, int height, int format)
```


指定されたサイズとフォーマットで [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| width | int | 新しい [Bitmap](../../com.aspose.drawing/bitmap) の幅（ピクセル単位）。 |
| height | int | 新しい [Bitmap](../../com.aspose.drawing/bitmap) の高さ（ピクセル単位）。 |
| format | int | 新しい [Bitmap](../../com.aspose.drawing/bitmap) の `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 列挙です。 |

### Bitmap(int width, int height, int stride, int format, int[] data) {#Bitmap-int-int-int-int-int---}
```
public Bitmap(int width, int height, int stride, int format, int[] data)
```


指定されたサイズとピクセルデータで [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| width | int | 新しい [Bitmap](../../com.aspose.drawing/bitmap) の幅（ピクセル単位）。 |
| height | int | 新しい [Bitmap](../../com.aspose.drawing/bitmap) の高さ（ピクセル単位）。 |
| ストライド | int | 1 行の開始位置と次の行の開始位置との間のバイトオフセットで、4 の倍数である必要があります。 |
| format | int | 新しい [Bitmap](../../com.aspose.drawing/bitmap) の `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 列挙です。 |
| データ | int[] | ピクセルデータです。 |

### Bitmap(Image original) {#Bitmap-com.aspose.drawing.Image-}
```
public Bitmap(Image original)
```


指定された既存の画像から [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | 新しい [Bitmap](../../com.aspose.drawing/bitmap) を作成する元となる [Image](../../com.aspose.drawing/image)です。 |

### Bitmap(Image original, Size newSize) {#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-}
```
public Bitmap(Image original, Size newSize)
```


指定された既存の画像から、指定されたサイズにスケーリングされた [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | 新しい [Bitmap](../../com.aspose.drawing/bitmap) を作成する元となる [Image](../../com.aspose.drawing/image) |
| newSize | [Size](../../com.aspose.drawing/size) | 新しい [Bitmap](../../com.aspose.drawing/bitmap) のサイズを表す `Size`([Image.getSize](../../com.aspose.drawing/image\#getSize)) 構造体です。 |

### Bitmap(Image original, int width, int height) {#Bitmap-com.aspose.drawing.Image-int-int-}
```
public Bitmap(Image original, int width, int height)
```


指定された既存の画像から、指定されたサイズにスケーリングされた [Bitmap](../../com.aspose.drawing/bitmap) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | 新しい [Bitmap](../../com.aspose.drawing/bitmap) を作成する元となる [Image](../../com.aspose.drawing/image)です。 |
| width | int | 新しい [Bitmap](../../com.aspose.drawing/bitmap) の幅（ピクセル単位）。 |
| height | int | 新しい [Bitmap](../../com.aspose.drawing/bitmap) の高さ（ピクセル単位）。 |

### getWidth() {#getWidth--}
```
public int getWidth()
```


このビットマップの幅（ピクセル単位）を取得します。

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


このビットマップの高さ（ピクセル単位）を取得します。

**Returns:**
int
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


この [Image](../../com.aspose.drawing/image) のファイル形式を取得します。

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


この [Image](../../com.aspose.drawing/image) のピクセル形式を取得します。

**Returns:**
int - この [Image](../../com.aspose.drawing/image) のピクセル形式を表す `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) です。
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


この [Image](../../com.aspose.drawing/image) に使用されるカラーパレットを取得または設定します。

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


この [Image](../../com.aspose.drawing/image) に使用されるカラーパレットを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


この [Image](../../com.aspose.drawing/image) 内のフレームの次元を表す GUID の配列を取得します。

**Returns:**
java.util.UUID[] - この [Image](../../com.aspose.drawing/image) 内のフレームの次元を、最上位から最下位へ指定する GUID の配列です。
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


この [Image](../../com.aspose.drawing/image) に格納されているプロパティ項目の ID を取得します。

**Returns:**
int[] - この画像に保存されている各プロパティ項目に対応するプロパティ ID の配列です。
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


この [Image](../../com.aspose.drawing/image) に格納されているすべてのプロパティ項目（メタデータの一部）を取得します。

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] - 画像に保存されている各プロパティ項目に対応する [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) オブジェクトの配列です。
### deepClone(Rectangle rect, int format) {#deepClone-com.aspose.drawing.Rectangle-int-}
```
public final Bitmap deepClone(Rectangle rect, int format)
```


この [Bitmap](../../com.aspose.drawing/bitmap) の、[Rectangle](../../com.aspose.drawing/rectangle) 構造で定義されたセクションのコピーを作成し、指定された `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 列挙体を使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | この [Bitmap](../../com.aspose.drawing/bitmap) からコピーする領域を定義します。座標はこの [Bitmap](../../com.aspose.drawing/bitmap) を基準とします。 |
| format | int | 宛先の [Bitmap](../../com.aspose.drawing/bitmap) 用の `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 列挙体を指定します。 |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The new [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### deepClone(RectangleF rect, int format) {#deepClone-com.aspose.drawing.RectangleF-int-}
```
public final Bitmap deepClone(RectangleF rect, int format)
```


この [Bitmap](../../com.aspose.drawing/bitmap) の、指定された [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) 列挙体で定義されたセクションのコピーを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | この [Bitmap](../../com.aspose.drawing/bitmap) からコピーする領域を定義します。 |
| format | int | 宛先の [Bitmap](../../com.aspose.drawing/bitmap) 用の [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) 列挙体を指定します。 |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### setResolution(float xDpi, float yDpi) {#setResolution-float-float-}
```
public final void setResolution(float xDpi, float yDpi)
```


この [Bitmap](../../com.aspose.drawing/bitmap) の解像度を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xDpi | float | [Bitmap](../../com.aspose.drawing/bitmap) の水平解像度（dpi）です。 |
| yDpi | float | [Bitmap](../../com.aspose.drawing/bitmap) の垂直解像度（dpi）です。 |

### lockBits(Rectangle rect, int flags, int format) {#lockBits-com.aspose.drawing.Rectangle-int-int-}
```
public final BitmapData lockBits(Rectangle rect, int flags, int format)
```


システムメモリに [Bitmap](../../com.aspose.drawing/bitmap) をロックします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | ロックする [Bitmap](../../com.aspose.drawing/bitmap) の領域を指定する [Rectangle](../../com.aspose.drawing/rectangle) 構造体です。 |
| flags | int | [Bitmap](../../com.aspose.drawing/bitmap) のアクセスレベル（読み取り/書き込み）を指定する [ImageLockMode](../../com.aspose.drawing.imaging/imagelockmode) 列挙体です。 |
| format | int | この [Bitmap](../../com.aspose.drawing/bitmap) のデータ形式を指定する `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 列挙体です。 |

**Returns:**
[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) - A [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) containing information about this lock operation.
### unlockBits(BitmapData bitmapData) {#unlockBits-com.aspose.drawing.imaging.BitmapData-}
```
public final void unlockBits(BitmapData bitmapData)
```


システムメモリからこの [Bitmap](../../com.aspose.drawing/bitmap) のロックを解除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitmapData | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) | ロック操作に関する情報を指定する [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) です。 |

### getPixel(int x, int y) {#getPixel-int-int-}
```
public final Color getPixel(int x, int y)
```


この [Bitmap](../../com.aspose.drawing/bitmap) の指定されたピクセルの色を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | 取得するピクセルの x 座標です。 |
| y | int | 取得するピクセルの y 座標です。 |

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) structure that represents the color of the specified pixel.
### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.drawing.Color-}
```
public final void setPixel(int x, int y, Color color)
```


この [Bitmap](../../com.aspose.drawing/bitmap) の指定されたピクセルの色を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | 設定するピクセルの x 座標です。 |
| y | int | 設定するピクセルの y 座標です。 |
| color | [Color](../../com.aspose.drawing/color) | 指定されたピクセルに割り当てる色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |

### readArgb32Pixels(int[] pixels) {#readArgb32Pixels-int---}
```
public final void readArgb32Pixels(int[] pixels)
```


ビットマップのピクセルを ARGB32 形式で指定された配列に読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ピクセル | int[] | ビットマップピクセルを配置する配列です。十分な容量が必要です。 |

### writeArgb32Pixels(int[] pixels) {#writeArgb32Pixels-int---}
```
public final void writeArgb32Pixels(int[] pixels)
```


ビットマップにピクセルを書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ピクセル | int[] | ARGB32 形式のソースピクセルを含む配列です。十分な長さが必要です。 |

### makeTransparent() {#makeTransparent--}
```
public final void makeTransparent()
```


この [Bitmap](../../com.aspose.drawing/bitmap) の指定された色を透明にします。

### makeTransparent(Color transparentColor) {#makeTransparent-com.aspose.drawing.Color-}
```
public final void makeTransparent(Color transparentColor)
```


この [Bitmap](../../com.aspose.drawing/bitmap) の指定された色を透明にします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| transparentColor | [Color](../../com.aspose.drawing/color) | 透明にする色を表す [Color](../../com.aspose.drawing/color) 構造体です。 |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


このメソッドは、[Image](../../com.aspose.drawing/image) を回転、反転、または回転と反転を行います。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rotateFlipType | int | 画像に適用する回転とフリップのタイプを指定する [RotateFlipType](../../com.aspose.drawing/rotatefliptype) メンバーです。 |

### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


この [Image](../../com.aspose.drawing/image) から指定されたプロパティ項目を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| propid | int | 取得するプロパティ項目の ID です。 |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


この [Image](../../com.aspose.drawing/image) から指定されたプロパティ項目を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| propid | int | 削除するプロパティ項目の ID です。 |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


この [Image](../../com.aspose.drawing/image) にプロパティ項目（メタデータの一部）を格納します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | 保存する [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) です。 |

