---
title: FontDefinitionExt
second_title: Αναφορά API του Aspose.Drawing for Java
description: Η κλάση περιέχει ορισμό γραμματοσειράς
type: docs
weight: 23
url: /el/java/com.aspose.drawing/fontdefinitionext/
---
**Inheritance:**
java.lang.Object
```
public class FontDefinitionExt
```

Η κλάση περιέχει τον ορισμό της γραμματοσειράς,
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)](#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Λαμβάνει το όνομα της οικογένειας γραμματοσειράς. |
| [getStyle()](#getStyle--) | Λαμβάνει το στυλ της γραμματοσειράς. |
| [getFontName()](#getFontName--) | Λαμβάνει το όνομα της γραμματοσειράς. |
| [getPostscriptName()](#getPostscriptName--) | Λαμβάνει το όνομα PostScript της γραμματοσειράς. |
| [getType()](#getType--) | Λαμβάνει τον τύπο της γραμματοσειράς. |
| [getFontFile()](#getFontFile--) | Λαμβάνει το αρχείο γραμματοσειράς. |
| [getFileName()](#getFileName--) | Λαμβάνει το όνομα του αρχείου. |
| [getFont()](#getFont--) | Λαμβάνει τη γραμματοσειρά. |
### FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset) {#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-}
```
public FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Όνομα της γραμματοσειράς. |
| familyName | java.lang.String | Οικογένεια της γραμματοσειράς. |
| localizedFamilyNames | java.util.List<java.lang.String> | Τοπικά ονόματα οικογένειας γραμματοσειράς. |
| τύπος | int | Ο τύπος. |
| fileName | java.lang.String | Όνομα του αρχείου. |
| offset | long | Η μετατόπιση. |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Λαμβάνει το όνομα της οικογένειας γραμματοσειράς.

Τιμή: Το όνομα της οικογένειας γραμματοσειράς.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public final String getStyle()
```


Λαμβάνει το στυλ της γραμματοσειράς.

Τιμή: Το στυλ της γραμματοσειράς.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public final String getFontName()
```


Λαμβάνει το όνομα της γραμματοσειράς.

Τιμή: Το όνομα της γραμματοσειράς.

**Returns:**
java.lang.String
### getPostscriptName() {#getPostscriptName--}
```
public final String getPostscriptName()
```


Λαμβάνει το όνομα PostScript της γραμματοσειράς.

Value: The postscript name of the font.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Λαμβάνει τον τύπο της γραμματοσειράς.

Value: The font type.

**Returns:**
int
### getFontFile() {#getFontFile--}
```
public final FontFileDefinition getFontFile()
```


Λαμβάνει το αρχείο γραμματοσειράς.

Value: The font file.

**Returns:**
com.aspose.fonts.sources.FontFileDefinition
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Λαμβάνει το όνομα του αρχείου.

Value: The name of the file.

**Returns:**
java.lang.String
### getFont() {#getFont--}
```
public final IFont getFont()
```


Λαμβάνει τη γραμματοσειρά.

**Returns:**
com.aspose.fonts.IFont - Returns font for current definition.
