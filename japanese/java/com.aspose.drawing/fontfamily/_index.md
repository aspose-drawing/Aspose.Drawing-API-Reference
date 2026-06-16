---
title: FontFamily
second_title: Aspose.Drawing for Java API リファレンス
description: 基本的なデザインが似ており、スタイルにいくつかのバリエーションがあるタイプフェイスのグループを定義します。
type: docs
weight: 24
url: /ja/java/com.aspose.drawing/fontfamily/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class FontFamily implements System.IDisposable
```

類似した基本デザインといくつかのスタイルバリエーションを持つ書体のグループを定義します。このクラスは継承できません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontFamily(String name)](#FontFamily-java.lang.String-) | 指定された名前で [FontFamily](../../com.aspose.drawing/fontfamily) クラスの新しいインスタンスを初期化します。 |
| [FontFamily(String name, FontCollection fontCollection)](#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-) | [FontFamily](../../com.aspose.drawing/fontfamily) クラスの新しいインスタンスを初期化します。 |
| [FontFamily(String name, FontFamilyDefinition definition)](#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-) | [FontFamily](../../com.aspose.drawing/fontfamily) クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFamilies()](#getFamilies--) | 現在のグラフィックコンテキストに関連付けられたすべての [FontFamily](../../com.aspose.drawing/fontfamily) オブジェクトを含む配列を取得します。 |
| [getGenericSansSerif()](#getGenericSansSerif--) | 汎用のサンセリフ [FontFamily](../../com.aspose.drawing/fontfamily) オブジェクトを取得します。 |
| [getGenericSerif()](#getGenericSerif--) | 汎用のセリフ [FontFamily](../../com.aspose.drawing/fontfamily) を取得します。 |
| [getGenericMonospace()](#getGenericMonospace--) | 汎用の等幅 [FontFamily](../../com.aspose.drawing/fontfamily) を取得します。 |
| [getName()](#getName--) | この [FontFamily](../../com.aspose.drawing/fontfamily) の名前を取得します。 |
| [dispose()](#dispose--) | この [FontFamily](../../com.aspose.drawing/fontfamily) が使用しているすべてのリソースを解放します。 |
| [getName(int language)](#getName-int-) | 指定された言語でこの [FontFamily](../../com.aspose.drawing/fontfamily) の名前を返します。 |
| [isStyleAvailable(int style)](#isStyleAvailable-int-) | 指定された[FontStyle](../../com.aspose.drawing/fontstyle)列挙体が利用可能かどうかを示します。 |
| [getEmHeight(int style)](#getEmHeight-int-) | 指定されたスタイルのEM正方形の高さ（フォント設計単位）を取得します。 |
| [getCellAscent(int style)](#getCellAscent-int-) | 指定されたスタイルの[FontFamily](../../com.aspose.drawing/fontfamily)のセル上昇量（設計単位）を返します。 |
| [getCellDescent(int style)](#getCellDescent-int-) | 指定されたスタイルの[FontFamily](../../com.aspose.drawing/fontfamily)のセル下降量（設計単位）を返します。 |
| [hashCode()](#hashCode--) | この[FontFamily](../../com.aspose.drawing/fontfamily)のハッシュコードを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトが[FontFamily](../../com.aspose.drawing/fontfamily)であり、かつこの[FontFamily](../../com.aspose.drawing/fontfamily)と同一かどうかを示します。 |
| [getLineSpacing(int style)](#getLineSpacing-int-) | 指定されたスタイルの[FontFamily](../../com.aspose.drawing/fontfamily)の行間隔（設計単位）を返します。 |
### FontFamily(String name) {#FontFamily-java.lang.String-}
```
public FontFamily(String name)
```


指定された名前で [FontFamily](../../com.aspose.drawing/fontfamily) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 新しい[FontFamily](../../com.aspose.drawing/fontfamily)の名前です。 |

### FontFamily(String name, FontCollection fontCollection) {#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-}
```
public FontFamily(String name, FontCollection fontCollection)
```


[FontFamily](../../com.aspose.drawing/fontfamily) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String | フォントファミリの名前です。 |
| fontCollection | [FontCollection](../../com.aspose.drawing/fontcollection) | フォントコレクションです。 |

### FontFamily(String name, FontFamilyDefinition definition) {#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-}
```
public FontFamily(String name, FontFamilyDefinition definition)
```


[FontFamily](../../com.aspose.drawing/fontfamily) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String | フォントファミリの名前です。 |
| definition | [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) | 定義です。 |

### getFamilies() {#getFamilies--}
```
public static FontFamily[] getFamilies()
```


現在のグラフィックコンテキストに関連付けられたすべての [FontFamily](../../com.aspose.drawing/fontfamily) オブジェクトを含む配列を取得します。

**Returns:**
com.aspose.drawing.FontFamily[] - 現在のグラフィック コンテキストに関連付けられた[FontFamily](../../com.aspose.drawing/fontfamily)オブジェクトの配列です。
### getGenericSansSerif() {#getGenericSansSerif--}
```
public static FontFamily getGenericSansSerif()
```


汎用のサンセリフ [FontFamily](../../com.aspose.drawing/fontfamily) オブジェクトを取得します。

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) object that represents a generic sans serif font.
### getGenericSerif() {#getGenericSerif--}
```
public static FontFamily getGenericSerif()
```


汎用のセリフ [FontFamily](../../com.aspose.drawing/fontfamily) を取得します。

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic serif font.
### getGenericMonospace() {#getGenericMonospace--}
```
public static FontFamily getGenericMonospace()
```


汎用の等幅 [FontFamily](../../com.aspose.drawing/fontfamily) を取得します。

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic monospace font.
### getName() {#getName--}
```
public String getName()
```


この [FontFamily](../../com.aspose.drawing/fontfamily) の名前を取得します。

**Returns:**
java.lang.String - この[FontFamily](../../com.aspose.drawing/fontfamily)の名前を表す文字列です。
### dispose() {#dispose--}
```
public void dispose()
```


この [FontFamily](../../com.aspose.drawing/fontfamily) が使用しているすべてのリソースを解放します。

### getName(int language) {#getName-int-}
```
public String getName(int language)
```


指定された言語でこの [FontFamily](../../com.aspose.drawing/fontfamily) の名前を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 言語 | int | 名前が返される言語です。 |

**Returns:**
java.lang.String - 指定された言語でこの[FontFamily](../../com.aspose.drawing/fontfamily)の名前を表す文字列です。
### isStyleAvailable(int style) {#isStyleAvailable-int-}
```
public boolean isStyleAvailable(int style)
```


指定された[FontStyle](../../com.aspose.drawing/fontstyle)列挙体が利用可能かどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| style | int | テスト対象の[FontStyle](../../com.aspose.drawing/fontstyle)です。 |

**Returns:**
boolean - 指定された[FontStyle](../../com.aspose.drawing/fontstyle)が利用可能な場合は true、そうでない場合は false です。
### getEmHeight(int style) {#getEmHeight-int-}
```
public int getEmHeight(int style)
```


指定されたスタイルのEM正方形の高さ（フォント設計単位）を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| style | int | EM の高さを取得する対象の[FontStyle](../../com.aspose.drawing/fontstyle)です。 |

**Returns:**
int - EM 正方形の高さです。
### getCellAscent(int style) {#getCellAscent-int-}
```
public int getCellAscent(int style)
```


指定されたスタイルの[FontFamily](../../com.aspose.drawing/fontfamily)のセル上昇量（設計単位）を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| style | int | フォントのスタイル情報を含む[FontStyle](../../com.aspose.drawing/fontstyle)です。 |

**Returns:**
int - 指定された[FontStyle](../../com.aspose.drawing/fontstyle)を使用するこの[FontFamily](../../com.aspose.drawing/fontfamily)のセル上昇量です。
### getCellDescent(int style) {#getCellDescent-int-}
```
public int getCellDescent(int style)
```


指定されたスタイルの[FontFamily](../../com.aspose.drawing/fontfamily)のセル下降量（設計単位）を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| style | int | フォントのスタイル情報を含む[FontStyle](../../com.aspose.drawing/fontstyle)です。 |

**Returns:**
int - 指定された[FontStyle](../../com.aspose.drawing/fontstyle)を使用するこの[FontFamily](../../com.aspose.drawing/fontfamily)のセル下降指標です。
### hashCode() {#hashCode--}
```
public int hashCode()
```


この[FontFamily](../../com.aspose.drawing/fontfamily)のハッシュコードを取得します。

**Returns:**
int - この[FontFamily](../../com.aspose.drawing/fontfamily)のハッシュコードです。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトが[FontFamily](../../com.aspose.drawing/fontfamily)であり、かつこの[FontFamily](../../com.aspose.drawing/fontfamily)と同一かどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | テスト対象のオブジェクトです。 |

**Returns:**
boolean - `obj` が[FontFamily](../../com.aspose.drawing/fontfamily)であり、この[FontFamily](../../com.aspose.drawing/fontfamily)と同一である場合は `true`、それ以外の場合は `false` です。
### getLineSpacing(int style) {#getLineSpacing-int-}
```
public int getLineSpacing(int style)
```


指定されたスタイルの [FontFamily](../../com.aspose.drawing/fontfamily) の行間（デザイン単位）を返します。行間は、連続する 2 行のテキストのベースライン間の垂直距離です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| style | int | 適用する [FontStyle](../../com.aspose.drawing/fontstyle) 。 |

**Returns:**
int - 連続する 2 行のテキスト間の距離。
