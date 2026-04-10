---
title: FontDefinitionExt
second_title: Référence de l'API Aspose.Drawing pour Java
description: Class contains font definition
type: docs
weight: 23
url: /fr/java/com.aspose.drawing/fontdefinitionext/
---
**Inheritance:**
java.lang.Object
```
public class FontDefinitionExt
```

La classe contient la définition de police,
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)](#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-) | Initializes a new instance of the [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) class. |
## Méthodes

| Méthode | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Name of the font. |
| familyName | java.lang.String | Family of the font. |
| localizedFamilyNames | java.util.List<java.lang.String> | Localized font family names. |
| type | int | The type. |
| fileName | java.lang.String | Name of the file. |
| offset | long | Le décalage. |

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

Valeur : le nom PostScript de la police.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Gets the font type.

Valeur : le type de police.

**Returns:**
int
### getFontFile() {#getFontFile--}
```
public final FontFileDefinition getFontFile()
```


Gets the font file.

Valeur : le fichier de police.

**Returns:**
com.aspose.fonts.sources.FontFileDefinition
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Gets the name of the file.

Valeur : le nom du fichier.

**Returns:**
java.lang.String
### getFont() {#getFont--}
```
public final IFont getFont()
```


Gets the font.

**Returns:**
com.aspose.fonts.IFont - Retourne la police pour la définition actuelle.
