---
title: ImageCodecInfo
second_title: Aspose.Drawing for Java API リファレンス
description: このクラスは、インストールされた画像エンコーダーおよびデコーダー（コーデックと呼ばれる）に関するすべての関連情報を取得するために必要なストレージ メンバーとメソッドを提供します。
type: docs
weight: 25
url: /ja/java/com.aspose.drawing.imaging/imagecodecinfo/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCodecInfo
```

この [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) クラスは、インストールされている画像エンコーダーおよびデコーダー（コーデックと呼ばれる）に関するすべての関連情報を取得するために必要なストレージ メンバーとメソッドを提供します。継承できません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ImageCodecInfo()](#ImageCodecInfo--) | 新しい [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) クラスのインスタンスを初期化します。 |
| [ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)](#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getClsid()](#getClsid--) | 特定のコーデックを識別する GUID を含む java.util.UUID 構造体を取得します。 |
| [setClsid(UUID value)](#setClsid-java.util.UUID-) | 特定のコーデックを識別する GUID を含む java.util.UUID 構造体を設定します。 |
| [getFormatID()](#getFormatID--) | コーデックの形式を識別する GUID を含む java.util.UUID 構造体を取得します。 |
| [setFormatID(UUID value)](#setFormatID-java.util.UUID-) | コーデックの形式を識別する GUID を含む java.util.UUID 構造体を設定します。 |
| [getCodecName()](#getCodecName--) | コーデックの名前を含む文字列を取得または設定します。 |
| [setCodecName(String value)](#setCodecName-java.lang.String-) | コーデックの名前を含む文字列を取得または設定します。 |
| [getFormatDescription()](#getFormatDescription--) | コーデックのファイル形式を説明する文字列を取得または設定します。 |
| [setFormatDescription(String value)](#setFormatDescription-java.lang.String-) | コーデックのファイル形式を説明する文字列を取得または設定します。 |
| [getFilenameExtension()](#getFilenameExtension--) | コーデックで使用されるファイル名拡張子を含む文字列を取得または設定します。 |
| [setFilenameExtension(String value)](#setFilenameExtension-java.lang.String-) | コーデックで使用されるファイル名拡張子を含む文字列を取得または設定します。 |
| [getMimeType()](#getMimeType--) | コーデックのマルチパーパスインターネットメール拡張 (MIME) タイプを含む文字列を取得または設定します。 |
| [setMimeType(String value)](#setMimeType-java.lang.String-) | コーデックのマルチパーパスインターネットメール拡張 (MIME) タイプを含む文字列を取得または設定します。 |
| [getVersion()](#getVersion--) | コーデックのバージョン番号を取得または設定します。 |
| [setVersion(int value)](#setVersion-int-) | コーデックのバージョン番号を取得または設定します。 |
| [getSignaturePatterns()](#getSignaturePatterns--) | コーデックのシグネチャを表すバイトの二次元配列を取得または設定します。 |
| [setSignaturePatterns(byte[][] value)](#setSignaturePatterns-byte-----) | コーデックのシグネチャを表すバイトの二次元配列を取得または設定します。 |
| [getSignatureMasks()](#getSignatureMasks--) | フィルタとして使用できるバイトの二次元配列を取得または設定します。 |
| [setSignatureMasks(byte[][] value)](#setSignatureMasks-byte-----) | フィルタとして使用できるバイトの二次元配列を取得または設定します。 |
| [getImageDecoders()](#getImageDecoders--) | GDI+ に組み込まれた画像デコーダーに関する情報を含む [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) オブジェクトの配列を返します。 |
| [getImageEncoders()](#getImageEncoders--) | GDI+ に組み込まれた画像エンコーダーに関する情報を含む [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) オブジェクトの配列を返します。 |
### ImageCodecInfo() {#ImageCodecInfo--}
```
public ImageCodecInfo()
```


新しい [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) クラスのインスタンスを初期化します。

### ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version) {#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-}
```
public ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)
```


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| clsid | java.util.UUID |  |
| codecName | java.lang.String |  |
| filenameExtension | java.lang.String |  |
| formatDescription | java.lang.String |  |
| formatID | java.util.UUID |  |
| mimeType | java.lang.String |  |
| version | int |  |

### getClsid() {#getClsid--}
```
public UUID getClsid()
```


特定のコーデックを識別する GUID を含む java.util.UUID 構造体を取得します。

**Returns:**
java.util.UUID - java.util.UUID
### setClsid(UUID value) {#setClsid-java.util.UUID-}
```
public void setClsid(UUID value)
```


特定のコーデックを識別する GUID を含む java.util.UUID 構造体を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.util.UUID | java.util.UUID |

### getFormatID() {#getFormatID--}
```
public UUID getFormatID()
```


コーデックの形式を識別する GUID を含む java.util.UUID 構造体を取得します。

**Returns:**
java.util.UUID - java.util.UUID
### setFormatID(UUID value) {#setFormatID-java.util.UUID-}
```
public void setFormatID(UUID value)
```


コーデックの形式を識別する GUID を含む java.util.UUID 構造体を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.util.UUID | java.util.UUID |

### getCodecName() {#getCodecName--}
```
public String getCodecName()
```


コーデックの名前を含む文字列を取得または設定します。

**Returns:**
java.lang.String
### setCodecName(String value) {#setCodecName-java.lang.String-}
```
public void setCodecName(String value)
```


コーデックの名前を含む文字列を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormatDescription() {#getFormatDescription--}
```
public String getFormatDescription()
```


コーデックのファイル形式を説明する文字列を取得または設定します。

**Returns:**
java.lang.String
### setFormatDescription(String value) {#setFormatDescription-java.lang.String-}
```
public void setFormatDescription(String value)
```


コーデックのファイル形式を説明する文字列を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFilenameExtension() {#getFilenameExtension--}
```
public String getFilenameExtension()
```


コーデックで使用されるファイル名拡張子を含む文字列を取得または設定します。拡張子はセミコロンで区切られます。

**Returns:**
java.lang.String
### setFilenameExtension(String value) {#setFilenameExtension-java.lang.String-}
```
public void setFilenameExtension(String value)
```


コーデックで使用されるファイル名拡張子を含む文字列を取得または設定します。拡張子はセミコロンで区切られます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getMimeType() {#getMimeType--}
```
public String getMimeType()
```


コーデックのマルチパーパスインターネットメール拡張 (MIME) タイプを含む文字列を取得または設定します。

**Returns:**
java.lang.String
### setMimeType(String value) {#setMimeType-java.lang.String-}
```
public void setMimeType(String value)
```


コーデックのマルチパーパスインターネットメール拡張 (MIME) タイプを含む文字列を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


コーデックのバージョン番号を取得または設定します。

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


コーデックのバージョン番号を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSignaturePatterns() {#getSignaturePatterns--}
```
public byte[][] getSignaturePatterns()
```


コーデックのシグネチャを表すバイトの二次元配列を取得または設定します。

**Returns:**
byte[][]
### setSignaturePatterns(byte[][] value) {#setSignaturePatterns-byte-----}
```
public void setSignaturePatterns(byte[][] value)
```


コーデックのシグネチャを表すバイトの二次元配列を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte[][] |  |

### getSignatureMasks() {#getSignatureMasks--}
```
public byte[][] getSignatureMasks()
```


フィルタとして使用できるバイトの二次元配列を取得または設定します。

**Returns:**
byte[][]
### setSignatureMasks(byte[][] value) {#setSignatureMasks-byte-----}
```
public void setSignatureMasks(byte[][] value)
```


フィルタとして使用できるバイトの二次元配列を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte[][] |  |

### getImageDecoders() {#getImageDecoders--}
```
public static ImageCodecInfo[] getImageDecoders()
```


GDI+ に組み込まれた画像デコーダーに関する情報を含む [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) オブジェクトの配列を返します。

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) オブジェクトの配列です。配列内の各 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) オブジェクトは、組み込み画像デコーダのいずれかに関する情報を含みます。
### getImageEncoders() {#getImageEncoders--}
```
public static ImageCodecInfo[] getImageEncoders()
```


GDI+ に組み込まれた画像エンコーダーに関する情報を含む [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) オブジェクトの配列を返します。

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) オブジェクトの配列です。配列内の各 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) オブジェクトは、組み込み画像エンコーダのいずれかに関する情報を含みます。
