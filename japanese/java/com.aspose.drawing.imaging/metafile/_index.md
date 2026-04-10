---
title: メタファイル
second_title: Aspose.Drawing for Java API リファレンス
description: グラフィックメタファイルを定義します。
type: docs
weight: 30
url: /ja/java/com.aspose.drawing.imaging/metafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public final class Metafile extends Image
```

グラフィックメタファイルを定義します。メタファイルは、記録（構築）および再生（表示）できる一連のグラフィック操作を記述するレコードを含みます。このクラスは継承できません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Metafile(byte[] henhmetafile, boolean deleteEmf)](#Metafile-byte---boolean-) | 指定されたハンドルから [Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。 |
| [Metafile(byte[] referenceHdc, int emfType)](#Metafile-byte---int-) | デバイスコンテキストへの指定ハンドルと、[Metafile](../../com.aspose.drawing.imaging/metafile) の形式を指定する [EmfType](../../com.aspose.drawing.imaging/emftype) 列挙体から、[Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。 |
| [Metafile(String filename)](#Metafile-java.lang.String-) | 指定されたファイル名から [Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。 |
| [Metafile(String filename, byte[] referenceHdc)](#Metafile-java.lang.String-byte---) | 指定されたファイル名から [Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。 |
| [Metafile(InputStream stream)](#Metafile-java.io.InputStream-) | 指定されたデータストリームから [Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。 |
| [Metafile(InputStream stream, byte[] referenceHdc)](#Metafile-java.io.InputStream-byte---) | 指定されたデータストリームとデバイスコンテキストへの Windows ハンドルから、[Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。 |
| [Metafile(System.IO.Stream stream, int type)](#Metafile-com.aspose.ms.System.IO.Stream-int-) | 指定されたデータストリームとデバイスコンテキストへの Windows ハンドルから、[Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。 |
| [Metafile(InputStream stream, byte[] referenceHdc, int type)](#Metafile-java.io.InputStream-byte---int-) | 指定されたデータストリーム、デバイスコンテキストへの Windows ハンドル、および [Metafile](../../com.aspose.drawing.imaging/metafile) の形式を指定する [EmfType](../../com.aspose.drawing.imaging/emftype) 列挙体から、[Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。 |
| [Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)](#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-) | 指定されたデータストリーム、デバイスコンテキストへの Windows ハンドル、および [Metafile](../../com.aspose.drawing.imaging/metafile) の形式を指定する [EmfType](../../com.aspose.drawing.imaging/emftype) 列挙体から、[Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getWidth()](#getWidth--) | この [Metafile](../../com.aspose.drawing.imaging/metafile) の幅（ピクセル単位）を取得します。 |
| [getHeight()](#getHeight--) | この [Metafile](../../com.aspose.drawing.imaging/metafile) の高さ（ピクセル単位）を取得します。 |
| [getRawFormat()](#getRawFormat--) | この [Image](../../com.aspose.drawing/image) のファイル形式を取得します。 |
| [getPixelFormat()](#getPixelFormat--) | この [Image](../../com.aspose.drawing/image) のピクセル形式を取得します。 |
| [getPalette()](#getPalette--) | この [Image](../../com.aspose.drawing/image) に使用されるカラーパレットを取得または設定します。 |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | この [Image](../../com.aspose.drawing/image) に使用されるカラーパレットを取得または設定します。 |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | この [Image](../../com.aspose.drawing/image) 内のフレームの次元を表す GUID の配列を取得します。 |
| [getPropertyIdList()](#getPropertyIdList--) | この [Image](../../com.aspose.drawing/image) に格納されているプロパティ項目の ID を取得します。 |
| [getPropertyItems()](#getPropertyItems--) | この [Image](../../com.aspose.drawing/image) に格納されているすべてのプロパティ項目（メタデータの一部）を取得します。 |
| [getMetafileHeader(InputStream stream)](#getMetafileHeader-java.io.InputStream-) | 指定された [Metafile](../../com.aspose.drawing.imaging/metafile) に関連付けられた [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) を返します。 |
| [getMetafileHeader(String fileName)](#getMetafileHeader-java.lang.String-) | 指定された [Metafile](../../com.aspose.drawing.imaging/metafile) に関連付けられた [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) を返します。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | このメソッドは、[Image](../../com.aspose.drawing/image) を回転、反転、または回転と反転を行います。 |
| [getHenhmetafile()](#getHenhmetafile--) | 拡張 [Metafile](../../com.aspose.drawing.imaging/metafile) への Windows ハンドルを返します。 |
| [playRecord(int recordType, int flags, int dataSize, byte[] dataArray)](#playRecord-int-int-int-byte---) | 個々のメタファイルレコードを再生します。 |
| [getMetafileHeader()](#getMetafileHeader--) | この [Metafile](../../com.aspose.drawing.imaging/metafile) に関連付けられた [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) を返します。 |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | この [Image](../../com.aspose.drawing/image) から指定されたプロパティ項目を取得します。 |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | この [Image](../../com.aspose.drawing/image) から指定されたプロパティ項目を削除します。 |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | この [Image](../../com.aspose.drawing/image) にプロパティ項目（メタデータの一部）を格納します。 |
### Metafile(byte[] henhmetafile, boolean deleteEmf) {#Metafile-byte---boolean-}
```
public Metafile(byte[] henhmetafile, boolean deleteEmf)
```


指定されたハンドルから [Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| henhmetafile | byte[] | 拡張メタファイルへのハンドルです。 |
| deleteEmf | boolean | 拡張メタファイルのハンドルを、[Metafile](../../com.aspose.drawing.imaging/metafile) が削除されたときに削除する場合は true、そうでない場合は false。 |

### Metafile(byte[] referenceHdc, int emfType) {#Metafile-byte---int-}
```
public Metafile(byte[] referenceHdc, int emfType)
```


デバイスコンテキストへの指定ハンドルと、[Metafile](../../com.aspose.drawing.imaging/metafile) の形式を指定する [EmfType](../../com.aspose.drawing.imaging/emftype) 列挙体から、[Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| referenceHdc | byte[] | デバイスコンテキストへのハンドルです。 |
| emfType | int | [EmfType](../../com.aspose.drawing.imaging/emftype) は、[Metafile](../../com.aspose.drawing.imaging/metafile) の形式を指定します。 |

### Metafile(String filename) {#Metafile-java.lang.String-}
```
public Metafile(String filename)
```


指定されたファイル名から [Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filename | java.lang.String | 新しい [Metafile](../../com.aspose.drawing.imaging/metafile) を作成する元となるファイル名を表す文字列です。 |

### Metafile(String filename, byte[] referenceHdc) {#Metafile-java.lang.String-byte---}
```
public Metafile(String filename, byte[] referenceHdc)
```


指定されたファイル名から [Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filename | java.lang.String | 新しい [Metafile](../../com.aspose.drawing.imaging/metafile) を作成する元となるファイル名を表す文字列です。 |
| referenceHdc | byte[] | デバイスコンテキストへの Windows ハンドルです。 |

### Metafile(InputStream stream) {#Metafile-java.io.InputStream-}
```
public Metafile(InputStream stream)
```


指定されたデータストリームから [Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 新しい [Metafile](../../com.aspose.drawing.imaging/metafile) を作成する元となる InputStream です。 |

### Metafile(InputStream stream, byte[] referenceHdc) {#Metafile-java.io.InputStream-byte---}
```
public Metafile(InputStream stream, byte[] referenceHdc)
```


指定されたデータストリームとデバイスコンテキストへの Windows ハンドルから、[Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。 />。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | この [Metafile](../../com.aspose.drawing.imaging/metafile) のデータを含む InputStream です。 |
| referenceHdc | byte[] | [Metafile](../../com.aspose.drawing.imaging/metafile) オブジェクトのデバイスコンテキストへの Windows ハンドルです。 |

### Metafile(System.IO.Stream stream, int type) {#Metafile-com.aspose.ms.System.IO.Stream-int-}
```
public Metafile(System.IO.Stream stream, int type)
```


指定されたデータストリームとデバイスコンテキストへの Windows ハンドルから、[Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。 />。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | この [Metafile](../../com.aspose.drawing.imaging/metafile) のデータを含む InputStream です。 |
| タイプ | int | int 1 である必要があります。 |

### Metafile(InputStream stream, byte[] referenceHdc, int type) {#Metafile-java.io.InputStream-byte---int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, int type)
```


指定されたデータストリーム、デバイスコンテキストへの Windows ハンドル、および [Metafile](../../com.aspose.drawing.imaging/metafile) の形式を指定する [EmfType](../../com.aspose.drawing.imaging/emftype) 列挙体から、[Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | この [Metafile](../../com.aspose.drawing.imaging/metafile) のデータを含む InputStream です。 |
| referenceHdc | byte[] | デバイスコンテキストへの Windows ハンドルです。 |
| type | int | [EmfType](../../com.aspose.drawing.imaging/emftype) は、[Metafile](../../com.aspose.drawing.imaging/metafile) の形式を指定します。 |

### Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type) {#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)
```


指定されたデータストリーム、デバイスコンテキストへの Windows ハンドル、および [Metafile](../../com.aspose.drawing.imaging/metafile) の形式を指定する [EmfType](../../com.aspose.drawing.imaging/emftype) 列挙体から、[Metafile](../../com.aspose.drawing.imaging/metafile) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | この [Metafile](../../com.aspose.drawing.imaging/metafile) のデータを含む InputStream です。 |
| referenceHdc | byte[] | デバイスコンテキストへの Windows ハンドルです。 |
| frameRect | [RectangleF](../../com.aspose.drawing/rectanglef) | 新しい [Metafile](../../com.aspose.drawing.imaging/metafile) を囲む矩形を表す [Rectangle](../../com.aspose.drawing/rectangle) です。 |
| frameUnit | int | frameRect の測定単位を指定する [MetafileFrameUnit](../../com.aspose.drawing.imaging/metafileframeunit) です。 |
| type | int | [EmfType](../../com.aspose.drawing.imaging/emftype) は、[Metafile](../../com.aspose.drawing.imaging/metafile) の形式を指定します。 |

### getWidth() {#getWidth--}
```
public int getWidth()
```


この [Metafile](../../com.aspose.drawing.imaging/metafile) の幅（ピクセル単位）を取得します。

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


この [Metafile](../../com.aspose.drawing.imaging/metafile) の高さ（ピクセル単位）を取得します。

**Returns:**
int - この [Metafile](../../com.aspose.drawing.imaging/metafile) の高さ（ピクセル単位）。
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
### getMetafileHeader(InputStream stream) {#getMetafileHeader-java.io.InputStream-}
```
public static MetafileHeader getMetafileHeader(InputStream stream)
```


指定された [Metafile](../../com.aspose.drawing.imaging/metafile) に関連付けられた [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | ヘッダーが取得される [Metafile](../../com.aspose.drawing.imaging/metafile) を含む InputStream です。 |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### getMetafileHeader(String fileName) {#getMetafileHeader-java.lang.String-}
```
public static MetafileHeader getMetafileHeader(String fileName)
```


指定された [Metafile](../../com.aspose.drawing.imaging/metafile) に関連付けられた [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ヘッダーが取得される [Metafile](../../com.aspose.drawing.imaging/metafile) の名前を含む文字列です。 |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


このメソッドは、[Image](../../com.aspose.drawing/image) を回転、反転、または回転と反転を行います。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rotateFlipType | int | 画像に適用する回転とフリップのタイプを指定する [RotateFlipType](../../com.aspose.drawing/rotatefliptype) メンバーです。 |

### getHenhmetafile() {#getHenhmetafile--}
```
public System.IntPtr getHenhmetafile()
```


拡張 [Metafile](../../com.aspose.drawing.imaging/metafile) への Windows ハンドルを返します。

**Returns:**
com.aspose.ms.System.IntPtr - この拡張 [Metafile](../../com.aspose.drawing.imaging/metafile) への Windows ハンドルです。
### playRecord(int recordType, int flags, int dataSize, byte[] dataArray) {#playRecord-int-int-int-byte---}
```
public void playRecord(int recordType, int flags, int dataSize, byte[] dataArray)
```


個々のメタファイルレコードを再生します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| recordType | int | 再生中のメタファイルレコードのタイプを指定する [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) の要素です。 |
| flags | int | レコードの属性を指定するフラグの集合です。 |
| dataSize | int | レコードデータのバイト数です。 |
| dataArray | byte[] | レコードデータを含むバイト配列です。 |

### getMetafileHeader() {#getMetafileHeader--}
```
public MetafileHeader getMetafileHeader()
```


この [Metafile](../../com.aspose.drawing.imaging/metafile) に関連付けられた [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) を返します。

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile).
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

