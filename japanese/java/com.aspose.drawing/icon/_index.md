---
title: アイコン
second_title: Aspose.Drawing for Java API リファレンス
description: オブジェクトを表すために使用される小さなビットマップ画像である Windows アイコンを表します。
type: docs
weight: 29
url: /ja/java/com.aspose.drawing/icon/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.ms.System.IDisposable
```
public final class Icon implements System.ICloneable, System.IDisposable
```

オブジェクトを表すために使用される小さなビットマップ画像である Windows アイコンを表します。アイコンは透明ビットマップと考えることができ、サイズはシステムによって決定されます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Icon(String fileName)](#Icon-java.lang.String-) | 指定されたファイル名から [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを初期化します。 |
| [Icon(InputStream stream)](#Icon-java.io.InputStream-) | 指定されたデータストリームから [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを初期化します。 |
| [Icon(String fileName, Size size)](#Icon-java.lang.String-com.aspose.drawing.Size-) | 指定されたサイズの [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを、指定されたファイルから初期化します。 |
| [Icon(Icon original, Size size)](#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-) | [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを初期化し、要求されたサイズに一致するアイコンのバージョンを探します。 |
| [Icon(Object type, String resource)](#Icon-java.lang.Object-java.lang.String-) | 指定されたアセンブリ内のリソースから [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを初期化します。 |
| [Icon(InputStream stream, Size size)](#Icon-java.io.InputStream-com.aspose.drawing.Size-) | 指定されたサイズの [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを、指定されたストリームから初期化します。 |
| [Icon(String fileName, int width, int height)](#Icon-java.lang.String-int-int-) | 指定されたファイルから、指定された幅と高さで [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを初期化します。 |
| [Icon(Icon original, int width, int height)](#Icon-com.aspose.drawing.Icon-int-int-) | [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを初期化し、要求されたサイズに一致するアイコンのバージョンを検索しようとします.. |
| [Icon(InputStream stream, int width, int height)](#Icon-java.io.InputStream-int-int-) | 指定されたデータストリームから、指定された幅と高さで [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHandle()](#getHandle--) | この [Icon](../../com.aspose.drawing/icon) のハンドルを取得します。 |
| [getHeight()](#getHeight--) | この [Icon](../../com.aspose.drawing/icon) の高さを取得します。 |
| [getSize()](#getSize--) | この [Icon](../../com.aspose.drawing/icon) のサイズを取得します。 |
| [getWidth()](#getWidth--) | この [Icon](../../com.aspose.drawing/icon) の幅を取得します。 |
| [extractAssociatedIcon(String filePath)](#extractAssociatedIcon-java.lang.String-) | 指定されたファイルに含まれる画像のアイコン表現を返します。 |
| [fromHandle(byte[] handle)](#fromHandle-byte---) | 指定されたアイコンの Windows ハンドル (HICON) から GDI+ [Icon](../../com.aspose.drawing/icon) を作成します。 |
| [deepClone()](#deepClone--) | [Icon](../../com.aspose.drawing/icon) をクローンし、重複した画像を作成します。 |
| [dispose()](#dispose--) | アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | この [Icon](../../com.aspose.drawing/icon) を指定された出力 java.io.InputStream に保存します。 |
| [toBitmap()](#toBitmap--) | この [Icon](../../com.aspose.drawing/icon) を GDI+ [Bitmap](../../com.aspose.drawing/bitmap) に変換します。 |
| [toString()](#toString--) | [Icon](../../com.aspose.drawing/icon) を説明する人間が読める文字列を取得します。 |
### Icon(String fileName) {#Icon-java.lang.String-}
```
public Icon(String fileName)
```


指定されたファイル名から [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | [Icon](../../com.aspose.drawing/icon) を読み込むファイル。 |

### Icon(InputStream stream) {#Icon-java.io.InputStream-}
```
public Icon(InputStream stream)
```


指定されたデータストリームから [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | [Icon](../../com.aspose.drawing/icon) を読み込むデータストリーム。 |

### Icon(String fileName, Size size) {#Icon-java.lang.String-com.aspose.drawing.Size-}
```
public Icon(String fileName, Size size)
```


指定されたサイズの [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを、指定されたファイルから初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | アイコンデータを含むファイルの名前とパス。 |
| size | [Size](../../com.aspose.drawing/size) | アイコンの希望サイズ。 |

### Icon(Icon original, Size size) {#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-}
```
public Icon(Icon original, Size size)
```


[Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを初期化し、要求されたサイズに一致するアイコンのバージョンを探します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | 新しいサイズのアイコンを読み込む元となる [Icon](../../com.aspose.drawing/icon)。 |
| size | [Size](../../com.aspose.drawing/size) | 新しい [Icon](../../com.aspose.drawing/icon) の高さと幅を指定する `Size`([.getSize](../../null/\#getSize)) 構造体。 |

### Icon(Object type, String resource) {#Icon-java.lang.Object-java.lang.String-}
```
public Icon(Object type, String resource)
```


指定されたアセンブリ内のリソースから [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| タイプ | java.lang.Object | リソースを検索するアセンブリを指定する Type。 |
| リソース | java.lang.String | 読み込むリソース名。 |

### Icon(InputStream stream, Size size) {#Icon-java.io.InputStream-com.aspose.drawing.Size-}
```
public Icon(InputStream stream, Size size)
```


指定されたサイズの [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを、指定されたストリームから初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | アイコンデータを含むストリーム。 |
| size | [Size](../../com.aspose.drawing/size) | アイコンの希望サイズ。 |

### Icon(String fileName, int width, int height) {#Icon-java.lang.String-int-int-}
```
public Icon(String fileName, int width, int height)
```


指定されたファイルから、指定された幅と高さで [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | [Icon](../../com.aspose.drawing/icon) データを含むファイルの名前とパス。 |
| width | int | [Icon](../../com.aspose.drawing/icon) の希望幅。 |
| height | int | 目的の高さは [Icon](../../com.aspose.drawing/icon) のものです。 |

### Icon(Icon original, int width, int height) {#Icon-com.aspose.drawing.Icon-int-int-}
```
public Icon(Icon original, int width, int height)
```


[Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを初期化し、要求されたサイズに一致するアイコンのバージョンを検索しようとします..

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | 異なるサイズを読み込む元となるアイコン。 |
| 幅 | int | 新しいアイコンの幅。 |
| 高さ | int | 新しいアイコンの高さ。 |

### Icon(InputStream stream, int width, int height) {#Icon-java.io.InputStream-int-int-}
```
public Icon(InputStream stream, int width, int height)
```


指定されたデータストリームから、指定された幅と高さで [Icon](../../com.aspose.drawing/icon) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | アイコンを読み込むためのデータストリーム。 |
| 幅 | int | アイコンの幅（ピクセル単位）。 |
| 高さ | int | アイコンの高さ（ピクセル単位）。 |

### getHandle() {#getHandle--}
```
public System.IntPtr getHandle()
```


この [Icon](../../com.aspose.drawing/icon) のハンドルを取得します。これはハンドルのコピーではありません。解放しないでください。

値: アイコンの Windows ハンドル。

**Returns:**
com.aspose.ms.System.IntPtr
### getHeight() {#getHeight--}
```
public int getHeight()
```


この [Icon](../../com.aspose.drawing/icon) の高さを取得します。

値: この [Icon](../../com.aspose.drawing/icon) の高さ。

**Returns:**
int
### getSize() {#getSize--}
```
public Size getSize()
```


この [Icon](../../com.aspose.drawing/icon) のサイズを取得します。

値: この [Icon](../../com.aspose.drawing/icon) の幅と高さを指定する `Size`([.getSize](../../null/\#getSize)) 構造体。

**Returns:**
[Size](../../com.aspose.drawing/size)
### getWidth() {#getWidth--}
```
public int getWidth()
```


この [Icon](../../com.aspose.drawing/icon) の幅を取得します。

値: この [Icon](../../com.aspose.drawing/icon) の幅。

**Returns:**
int
### extractAssociatedIcon(String filePath) {#extractAssociatedIcon-java.lang.String-}
```
public static Icon extractAssociatedIcon(String filePath)
```


指定されたファイルに含まれる画像のアイコン表現を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 画像を含むファイルへのパス。 |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) representation of the image that is contained in the specified file.
### fromHandle(byte[] handle) {#fromHandle-byte---}
```
public static Icon fromHandle(byte[] handle)
```


指定されたアイコンの Windows ハンドル (HICON) から GDI+ [Icon](../../com.aspose.drawing/icon) を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| handle | byte[] | アイコンへの Windows ハンドル。 |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) this method creates.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


[Icon](../../com.aspose.drawing/icon) をクローンし、重複した画像を作成します。

**Returns:**
java.lang.Object - [Icon](../../com.aspose.drawing/icon) にキャストできるオブジェクト。
### dispose() {#dispose--}
```
public void dispose()
```


アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


この [Icon](../../com.aspose.drawing/icon) を指定された出力 java.io.InputStream に保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存先の java.io.InputStream。 |

### toBitmap() {#toBitmap--}
```
public Bitmap toBitmap()
```


この [Icon](../../com.aspose.drawing/icon) を GDI+ [Bitmap](../../com.aspose.drawing/bitmap) に変換します。

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - A [Bitmap](../../com.aspose.drawing/bitmap) that represents the converted [Icon](../../com.aspose.drawing/icon).
### toString() {#toString--}
```
public String toString()
```


[Icon](../../com.aspose.drawing/icon) を説明する人間が読める文字列を取得します。

**Returns:**
java.lang.String - [Icon](../../com.aspose.drawing/icon) を記述する文字列。
