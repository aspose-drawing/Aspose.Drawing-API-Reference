---
title: FontFamilyDefinition
second_title: Référence de l'API Aspose.Drawing pour Java
description: La définition de la famille de polices.
type: docs
weight: 25
url: /fr/java/com.aspose.drawing/fontfamilydefinition/
---
**Inheritance:**
java.lang.Object
```
public class FontFamilyDefinition
```

La définition de la famille de polices.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontFamilyDefinition()](#FontFamilyDefinition--) | Initialise une nouvelle instance de la classe [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addFontDefinition(int style, FontDefinitionExt fontDef)](#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-) | Ajoute la définition de police à la famille de polices. |
| [getFontDefinition(int style)](#getFontDefinition-int-) | Obtient la définition de police de la famille pour un style spécifique. |
| [matchesLocalizedFamilyName(String localizedFamilyName)](#matchesLocalizedFamilyName-java.lang.String-) | Correspond aux noms de famille localisés dans cette famille. |
| [getFamilyName()](#getFamilyName--) | Obtient un nom de famille de cette famille. |
### FontFamilyDefinition() {#FontFamilyDefinition--}
```
public FontFamilyDefinition()
```


Initialise une nouvelle instance de la classe [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition).

### addFontDefinition(int style, FontDefinitionExt fontDef) {#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-}
```
public final void addFontDefinition(int style, FontDefinitionExt fontDef)
```


Ajoute la définition de police à la famille de polices.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| style | int | Le style. |
| fontDef | [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) | La définition de police. |

### getFontDefinition(int style) {#getFontDefinition-int-}
```
public final FontDefinitionExt getFontDefinition(int style)
```


Obtient la définition de police de la famille pour un style spécifique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| style | int | Le style. |

**Returns:**
[FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) - Returns font definition if exist for specified style, null otherwise.
### matchesLocalizedFamilyName(String localizedFamilyName) {#matchesLocalizedFamilyName-java.lang.String-}
```
public final boolean matchesLocalizedFamilyName(String localizedFamilyName)
```


Correspond aux noms de famille localisés dans cette famille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| localizedFamilyName | java.lang.String | Le nom de famille localisé. |

**Returns:**
boolean - true si cette famille inclut le nom de famille localisé.
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Obtient un nom de famille de cette famille.

**Returns:**
java.lang.String - Le nom de famille, ou null pour une famille vide.
