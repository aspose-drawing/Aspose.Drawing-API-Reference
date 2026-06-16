---
title: FontFamilyDefinition
second_title: Aspose.Drawing für Java API-Referenz
description: Die Schriftfamilien‑Definition.
type: docs
weight: 25
url: /de/java/com.aspose.drawing/fontfamilydefinition/
---
**Inheritance:**
java.lang.Object
```
public class FontFamilyDefinition
```

Die Schriftfamilien‑Definition.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontFamilyDefinition()](#FontFamilyDefinition--) | Initialisiert eine neue Instanz der Klasse [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addFontDefinition(int style, FontDefinitionExt fontDef)](#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-) | Fügt die Schriftdefinition zur Schriftfamilie hinzu. |
| [getFontDefinition(int style)](#getFontDefinition-int-) | Ruft die Schriftdefinition aus der Familie für einen bestimmten Stil ab. |
| [matchesLocalizedFamilyName(String localizedFamilyName)](#matchesLocalizedFamilyName-java.lang.String-) | Vergleicht lokalisierte Familiennamen in dieser Familie. |
| [getFamilyName()](#getFamilyName--) | Gibt einen Familiennamen dieser Familie zurück. |
### FontFamilyDefinition() {#FontFamilyDefinition--}
```
public FontFamilyDefinition()
```


Initialisiert eine neue Instanz der Klasse [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition).

### addFontDefinition(int style, FontDefinitionExt fontDef) {#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-}
```
public final void addFontDefinition(int style, FontDefinitionExt fontDef)
```


Fügt die Schriftdefinition zur Schriftfamilie hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| style | int | Der Stil. |
| fontDef | [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) | Die Schriftdefinition. |

### getFontDefinition(int style) {#getFontDefinition-int-}
```
public final FontDefinitionExt getFontDefinition(int style)
```


Ruft die Schriftdefinition aus der Familie für einen bestimmten Stil ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| style | int | Der Stil. |

**Returns:**
[FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) - Returns font definition if exist for specified style, null otherwise.
### matchesLocalizedFamilyName(String localizedFamilyName) {#matchesLocalizedFamilyName-java.lang.String-}
```
public final boolean matchesLocalizedFamilyName(String localizedFamilyName)
```


Vergleicht lokalisierte Familiennamen in dieser Familie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localizedFamilyName | java.lang.String | Der lokalisierte Familienname. |

**Returns:**
boolean – true, wenn diese Familie den lokalisierten Familiennamen enthält.
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Gibt einen Familiennamen dieser Familie zurück.

**Returns:**
java.lang.String – Der Familienname oder null für eine leere Familie.
