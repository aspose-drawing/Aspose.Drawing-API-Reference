---
title: FontFamilyDefinition
second_title: Aspose.Drawing för Java API‑referens
description: Teckensnittsfamiljens definition.
type: docs
weight: 25
url: /sv/java/com.aspose.drawing/fontfamilydefinition/
---
**Inheritance:**
java.lang.Object
```
public class FontFamilyDefinition
```

Teckensnittsfamiljens definition.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontFamilyDefinition()](#FontFamilyDefinition--) | Initierar en ny instans av klassen [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addFontDefinition(int style, FontDefinitionExt fontDef)](#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-) | Lägger till teckensnittdefinitionen till teckensnittsfamiljen. |
| [getFontDefinition(int style)](#getFontDefinition-int-) | Hämtar teckensnittdefinitionen från familjen för en specifik stil. |
| [matchesLocalizedFamilyName(String localizedFamilyName)](#matchesLocalizedFamilyName-java.lang.String-) | Matchar lokalanpassade familjenamn i denna familj. |
| [getFamilyName()](#getFamilyName--) | Hämtar ett familjenamn för denna familj. |
### FontFamilyDefinition() {#FontFamilyDefinition--}
```
public FontFamilyDefinition()
```


Initierar en ny instans av klassen [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition).

### addFontDefinition(int style, FontDefinitionExt fontDef) {#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-}
```
public final void addFontDefinition(int style, FontDefinitionExt fontDef)
```


Lägger till teckensnittdefinitionen till teckensnittsfamiljen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stil | int | Stilen. |
| fontDef | [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) | Teckensnittdefinitionen. |

### getFontDefinition(int style) {#getFontDefinition-int-}
```
public final FontDefinitionExt getFontDefinition(int style)
```


Hämtar teckensnittdefinitionen från familjen för en specifik stil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stil | int | Stilen. |

**Returns:**
[FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) - Returns font definition if exist for specified style, null otherwise.
### matchesLocalizedFamilyName(String localizedFamilyName) {#matchesLocalizedFamilyName-java.lang.String-}
```
public final boolean matchesLocalizedFamilyName(String localizedFamilyName)
```


Matchar lokalanpassade familjenamn i denna familj.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localizedFamilyName | java.lang.String | Det lokalanpassade familjenamnet. |

**Returns:**
boolean - true om denna familj inkluderar det lokalanpassade familjenamnet.
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Hämtar ett familjenamn för denna familj.

**Returns:**
java.lang.String - Familjenamnet, eller null för en tom familj.
