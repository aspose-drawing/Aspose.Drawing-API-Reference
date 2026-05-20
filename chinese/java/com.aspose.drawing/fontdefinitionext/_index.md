---
title: FontDefinitionExt
second_title: Aspose.Drawing for Java API 参考
description: 类包含字体定义
type: docs
weight: 23
url: /zh/java/com.aspose.drawing/fontdefinitionext/
---
**Inheritance:**
java.lang.Object
```
public class FontDefinitionExt
```

类包含字体定义，
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)](#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-) | 初始化一个新的 [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | 获取字体族名称。 |
| [getStyle()](#getStyle--) | 获取字体样式。 |
| [getFontName()](#getFontName--) | 获取字体的名称。 |
| [getPostscriptName()](#getPostscriptName--) | 获取字体的 PostScript 名称。 |
| [getType()](#getType--) | 获取字体类型。 |
| [getFontFile()](#getFontFile--) | 获取字体文件。 |
| [getFileName()](#getFileName--) | 获取文件的名称。 |
| [getFont()](#getFont--) | 获取字体。 |
### FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset) {#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-}
```
public FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)
```


初始化一个新的 [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 字体的名称。 |
| familyName | java.lang.String | 字体族。 |
| localizedFamilyNames | java.util.List<java.lang.String> | 本地化的字体族名称。 |
| type | int | 类型。 |
| fileName | java.lang.String | 文件的名称。 |
| offset | long | 偏移量。 |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


获取字体族名称。

值：字体族名称。

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public final String getStyle()
```


获取字体样式。

值：字体样式。

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public final String getFontName()
```


获取字体的名称。

值：字体的名称。

**Returns:**
java.lang.String
### getPostscriptName() {#getPostscriptName--}
```
public final String getPostscriptName()
```


获取字体的 PostScript 名称。

值：字体的 PostScript 名称。

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


获取字体类型。

值：字体类型。

**Returns:**
int
### getFontFile() {#getFontFile--}
```
public final FontFileDefinition getFontFile()
```


获取字体文件。

值：字体文件。

**Returns:**
com.aspose.fonts.sources.FontFileDefinition
### getFileName() {#getFileName--}
```
public final String getFileName()
```


获取文件的名称。

值：文件的名称。

**Returns:**
java.lang.String
### getFont() {#getFont--}
```
public final IFont getFont()
```


获取字体。

**Returns:**
com.aspose.fonts.IFont - 返回当前定义的字体。
