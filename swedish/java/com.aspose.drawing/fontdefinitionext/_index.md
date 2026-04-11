---
title: FontDefinitionExt
second_title: Aspose.Drawing för Java API‑referens
description: Class contains font definition
type: docs
weight: 23
url: /sv/java/com.aspose.drawing/fontdefinitionext/
---
**Inheritance:**
java.lang.Object
```
public class FontDefinitionExt
```

Klassen innehåller teckensnittsdefinition,
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)](#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-) | Initializes a new instance of the [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) class. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Gets the font family name. |
| [getStyle()](#getStyle--) | Gets the font style. |
| [getFontName()](#getFontName--) | Gets the name of the font. |
| [getPostscriptName()](#getPostscriptName--) | Gets the postscript name of the font. |
| [getType()](#getType--) | Gets the font type. |
| [getFontFile()](#getFontFile--) | Gets the font file. |
| [getFileName()](#getFileName--) | Gets the name of the file. |
| [getFont()](#getFont--) | Gets the font. |
### FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset) {#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-}
```
public FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)
```


Initializes a new instance of the [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) class.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | Name of the font. |
| familyName | java.lang.String | Family of the font. |
| localizedFamilyNames | java.util.List<java.lang.String> | Localized font family names. |
| type | int | The type. |
| fileName | java.lang.String | Name of the file. |
| offset | long | Förskjutningen. |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Gets the font family name.

Value: The font family name.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public final String getStyle()
```


Gets the font style.

Value: The font style.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public final String getFontName()
```


Gets the name of the font.

Value: The name of the font.

**Returns:**
java.lang.String
### getPostscriptName() {#getPostscriptName--}
```
public final String getPostscriptName()
```


Gets the postscript name of the font.

Värde: Postscript-namnet på teckensnittet.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Gets the font type.

Värde: Teckensnittstypen.

**Returns:**
int
### getFontFile() {#getFontFile--}
```
public final FontFileDefinition getFontFile()
```


Gets the font file.

Värde: Teckensnittsfilen.

**Returns:**
com.aspose.fonts.sources.FontFileDefinition
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Gets the name of the file.

Värde: Filens namn.

**Returns:**
java.lang.String
### getFont() {#getFont--}
```
public final IFont getFont()
```


Gets the font.

**Returns:**
com.aspose.fonts.IFont - Returnerar teckensnitt för aktuell definition.
