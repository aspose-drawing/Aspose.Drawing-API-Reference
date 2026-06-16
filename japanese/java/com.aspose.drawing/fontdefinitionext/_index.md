---
title: FontDefinitionExt
second_title: Aspose.Drawing for Java API リファレンス
description: クラスはフォント定義を含みます
type: docs
weight: 23
url: /ja/java/com.aspose.drawing/fontdefinitionext/
---
**Inheritance:**
java.lang.Object
```
public class FontDefinitionExt
```

クラスはフォント定義を含みます、
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)](#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-) | 新しいインスタンスを初期化します [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) クラス。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | フォントファミリ名を取得します。 |
| [getStyle()](#getStyle--) | フォントスタイルを取得します。 |
| [getFontName()](#getFontName--) | フォントの名前を取得します。 |
| [getPostscriptName()](#getPostscriptName--) | フォントのPostScript名を取得します。 |
| [getType()](#getType--) | フォントタイプを取得します。 |
| [getFontFile()](#getFontFile--) | フォントファイルを取得します。 |
| [getFileName()](#getFileName--) | ファイル名を取得します。 |
| [getFont()](#getFont--) | フォントを取得します。 |
### FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset) {#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-}
```
public FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)
```


新しいインスタンスを初期化します [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) クラス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | フォントの名前。 |
| familyName | java.lang.String | フォントのファミリ。 |
| localizedFamilyNames | java.util.List<java.lang.String> | ローカライズされたフォントファミリ名。 |
| タイプ | int | タイプです。 |
| fileName | java.lang.String | ファイルの名前。 |
| offset | long | オフセット。 |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


フォントファミリ名を取得します。

値: フォントファミリ名です。

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public final String getStyle()
```


フォントスタイルを取得します。

値: フォントスタイルです。

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public final String getFontName()
```


フォントの名前を取得します。

値: フォントの名前です。

**Returns:**
java.lang.String
### getPostscriptName() {#getPostscriptName--}
```
public final String getPostscriptName()
```


フォントのPostScript名を取得します。

値: フォントのPostScript名です。

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


フォントタイプを取得します。

値: フォントの種類です。

**Returns:**
int
### getFontFile() {#getFontFile--}
```
public final FontFileDefinition getFontFile()
```


フォントファイルを取得します。

値: フォントファイルです。

**Returns:**
com.aspose.fonts.sources.FontFileDefinition
### getFileName() {#getFileName--}
```
public final String getFileName()
```


ファイル名を取得します。

値: ファイルの名前です。

**Returns:**
java.lang.String
### getFont() {#getFont--}
```
public final IFont getFont()
```


フォントを取得します。

**Returns:**
com.aspose.fonts.IFont - 現在の定義に対するフォントを返します。
