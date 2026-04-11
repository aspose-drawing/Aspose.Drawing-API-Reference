---
title: FontFamilyDefinition
second_title: Aspose.Drawing voor Java API-referentie
description: De definitie van de lettertypefamilie.
type: docs
weight: 25
url: /nl/java/com.aspose.drawing/fontfamilydefinition/
---
**Inheritance:**
java.lang.Object
```
public class FontFamilyDefinition
```

De definitie van de lettertypefamilie.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FontFamilyDefinition()](#FontFamilyDefinition--) | Initialiseert een nieuw exemplaar van de [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addFontDefinition(int style, FontDefinitionExt fontDef)](#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-) | Voegt de lettertype‑definitie toe aan de lettertypefamilie. |
| [getFontDefinition(int style)](#getFontDefinition-int-) | Haalt de lettertype‑definitie op uit de familie voor een specifieke stijl. |
| [matchesLocalizedFamilyName(String localizedFamilyName)](#matchesLocalizedFamilyName-java.lang.String-) | Zoekt overeen met gelokaliseerde familienaam in deze familie. |
| [getFamilyName()](#getFamilyName--) | Haalt een familienaam van deze familie op. |
### FontFamilyDefinition() {#FontFamilyDefinition--}
```
public FontFamilyDefinition()
```


Initialiseert een nieuw exemplaar van de [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) klasse.

### addFontDefinition(int style, FontDefinitionExt fontDef) {#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-}
```
public final void addFontDefinition(int style, FontDefinitionExt fontDef)
```


Voegt de lettertype‑definitie toe aan de lettertypefamilie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| style | int | De stijl. |
| fontDef | [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) | De lettertype‑definitie. |

### getFontDefinition(int style) {#getFontDefinition-int-}
```
public final FontDefinitionExt getFontDefinition(int style)
```


Haalt de lettertype‑definitie op uit de familie voor een specifieke stijl.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| style | int | De stijl. |

**Returns:**
[FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) - Returns font definition if exist for specified style, null otherwise.
### matchesLocalizedFamilyName(String localizedFamilyName) {#matchesLocalizedFamilyName-java.lang.String-}
```
public final boolean matchesLocalizedFamilyName(String localizedFamilyName)
```


Zoekt overeen met gelokaliseerde familienaam in deze familie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localizedFamilyName | java.lang.String | De gelokaliseerde familienaam. |

**Returns:**
boolean - true als deze familie de gelokaliseerde familienaam bevat.
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Haalt een familienaam van deze familie op.

**Returns:**
java.lang.String - De familienaam, of null voor een lege familie.
