---
title: FontFamilyDefinition
second_title: Aspose.Drawing for Java API リファレンス
description: フォント ファミリーの定義です。
type: docs
weight: 25
url: /ja/java/com.aspose.drawing/fontfamilydefinition/
---
**Inheritance:**
java.lang.Object
```
public class FontFamilyDefinition
```

フォント ファミリーの定義です。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontFamilyDefinition()](#FontFamilyDefinition--) | Initializes a new instance of the [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) class. |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addFontDefinition(int style, FontDefinitionExt fontDef)](#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-) | Adds the font definition to font family. |
| [getFontDefinition(int style)](#getFontDefinition-int-) | Gets the font definition from family for specific style. |
| [matchesLocalizedFamilyName(String localizedFamilyName)](#matchesLocalizedFamilyName-java.lang.String-) | Matches localized family names in this family. |
| [getFamilyName()](#getFamilyName--) | Gets a family name of this family. |
### FontFamilyDefinition() {#FontFamilyDefinition--}
```
public FontFamilyDefinition()
```


Initializes a new instance of the [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) class.

### addFontDefinition(int style, FontDefinitionExt fontDef) {#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-}
```
public final void addFontDefinition(int style, FontDefinitionExt fontDef)
```


Adds the font definition to font family.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| style | int | The style. |
| fontDef | [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) | The font definition. |

### getFontDefinition(int style) {#getFontDefinition-int-}
```
public final FontDefinitionExt getFontDefinition(int style)
```


Gets the font definition from family for specific style.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| style | int | The style. |

**Returns:**
[FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) - Returns font definition if exist for specified style, null otherwise.
### matchesLocalizedFamilyName(String localizedFamilyName) {#matchesLocalizedFamilyName-java.lang.String-}
```
public final boolean matchesLocalizedFamilyName(String localizedFamilyName)
```


Matches localized family names in this family.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| localizedFamilyName | java.lang.String | The localized family name. |

**Returns:**
boolean - true if this family includes the localized family name.
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Gets a family name of this family.

**Returns:**
java.lang.String - The family name, or null for an empty family.
