---
title: FontFamilyDefinition
second_title: Referensi API Aspose.Drawing for Java
description: Definisi keluarga font.
type: docs
weight: 25
url: /id/java/com.aspose.drawing/fontfamilydefinition/
---
**Inheritance:**
java.lang.Object
```
public class FontFamilyDefinition
```

Definisi keluarga font.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FontFamilyDefinition()](#FontFamilyDefinition--) | Menginisialisasi sebuah instance baru dari kelas [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addFontDefinition(int style, FontDefinitionExt fontDef)](#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-) | Menambahkan definisi font ke keluarga font. |
| [getFontDefinition(int style)](#getFontDefinition-int-) | Mendapatkan definisi font dari keluarga untuk gaya tertentu. |
| [matchesLocalizedFamilyName(String localizedFamilyName)](#matchesLocalizedFamilyName-java.lang.String-) | Mencocokkan nama keluarga yang dilokalisasi dalam keluarga ini. |
| [getFamilyName()](#getFamilyName--) | Mendapatkan nama keluarga dari keluarga ini. |
### FontFamilyDefinition() {#FontFamilyDefinition--}
```
public FontFamilyDefinition()
```


Menginisialisasi sebuah instance baru dari kelas [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition).

### addFontDefinition(int style, FontDefinitionExt fontDef) {#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-}
```
public final void addFontDefinition(int style, FontDefinitionExt fontDef)
```


Menambahkan definisi font ke keluarga font.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gaya | int | Gaya tersebut. |
| fontDef | [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) | Definisi font. |

### getFontDefinition(int style) {#getFontDefinition-int-}
```
public final FontDefinitionExt getFontDefinition(int style)
```


Mendapatkan definisi font dari keluarga untuk gaya tertentu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gaya | int | Gaya tersebut. |

**Returns:**
[FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) - Returns font definition if exist for specified style, null otherwise.
### matchesLocalizedFamilyName(String localizedFamilyName) {#matchesLocalizedFamilyName-java.lang.String-}
```
public final boolean matchesLocalizedFamilyName(String localizedFamilyName)
```


Mencocokkan nama keluarga yang dilokalisasi dalam keluarga ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localizedFamilyName | java.lang.String | Nama keluarga yang dilokalisasi. |

**Returns:**
boolean - true jika keluarga ini mencakup nama keluarga yang dilokalisasi.
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Mendapatkan nama keluarga dari keluarga ini.

**Returns:**
java.lang.String - Nama keluarga, atau null untuk keluarga kosong.
