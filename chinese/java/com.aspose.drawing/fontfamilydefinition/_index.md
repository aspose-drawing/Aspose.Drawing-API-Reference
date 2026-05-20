---
title: FontFamilyDefinition
second_title: Aspose.Drawing for Java API 参考
description: 字体族的定义。
type: docs
weight: 25
url: /zh/java/com.aspose.drawing/fontfamilydefinition/
---
**Inheritance:**
java.lang.Object
```
public class FontFamilyDefinition
```

字体族的定义。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontFamilyDefinition()](#FontFamilyDefinition--) | 初始化一个新的 [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addFontDefinition(int style, FontDefinitionExt fontDef)](#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-) | 将字体定义添加到字体族中。 |
| [getFontDefinition(int style)](#getFontDefinition-int-) | 获取特定样式的字体族中的字体定义。 |
| [matchesLocalizedFamilyName(String localizedFamilyName)](#matchesLocalizedFamilyName-java.lang.String-) | 匹配此族中的本地化族名称。 |
| [getFamilyName()](#getFamilyName--) | 获取此族的族名称。 |
### FontFamilyDefinition() {#FontFamilyDefinition--}
```
public FontFamilyDefinition()
```


初始化一个新的 [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) 类实例。

### addFontDefinition(int style, FontDefinitionExt fontDef) {#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-}
```
public final void addFontDefinition(int style, FontDefinitionExt fontDef)
```


将字体定义添加到字体族中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| style | int | 该样式。 |
| fontDef | [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) | 该字体定义。 |

### getFontDefinition(int style) {#getFontDefinition-int-}
```
public final FontDefinitionExt getFontDefinition(int style)
```


获取特定样式的字体族中的字体定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| style | int | 该样式。 |

**Returns:**
[FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) - Returns font definition if exist for specified style, null otherwise.
### matchesLocalizedFamilyName(String localizedFamilyName) {#matchesLocalizedFamilyName-java.lang.String-}
```
public final boolean matchesLocalizedFamilyName(String localizedFamilyName)
```


匹配此族中的本地化族名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localizedFamilyName | java.lang.String | 本地化的族名称。 |

**Returns:**
boolean - 如果此族包含本地化的族名称则为 true。
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


获取此族的族名称。

**Returns:**
java.lang.String - 族名称，若为空族则为 null。
