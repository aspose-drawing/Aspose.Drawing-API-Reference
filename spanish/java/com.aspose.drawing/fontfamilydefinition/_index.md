---
title: FontFamilyDefinition
second_title: Referencia de la API de Aspose.Drawing para Java
description: La definición de la familia tipográfica.
type: docs
weight: 25
url: /es/java/com.aspose.drawing/fontfamilydefinition/
---
**Inheritance:**
java.lang.Object
```
public class FontFamilyDefinition
```

La definición de la familia tipográfica.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontFamilyDefinition()](#FontFamilyDefinition--) | Inicializa una nueva instancia de la clase [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition). |
## Métodos

| Método | Descripción |
| --- | --- |
| [addFontDefinition(int style, FontDefinitionExt fontDef)](#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-) | Agrega la definición de fuente a la familia de fuentes. |
| [getFontDefinition(int style)](#getFontDefinition-int-) | Obtiene la definición de fuente de la familia para un estilo específico. |
| [matchesLocalizedFamilyName(String localizedFamilyName)](#matchesLocalizedFamilyName-java.lang.String-) | Coincide con los nombres de familia localizados en esta familia. |
| [getFamilyName()](#getFamilyName--) | Obtiene un nombre de familia de esta familia. |
### FontFamilyDefinition() {#FontFamilyDefinition--}
```
public FontFamilyDefinition()
```


Inicializa una nueva instancia de la clase [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition).

### addFontDefinition(int style, FontDefinitionExt fontDef) {#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-}
```
public final void addFontDefinition(int style, FontDefinitionExt fontDef)
```


Agrega la definición de fuente a la familia de fuentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| style | int | El estilo. |
| fontDef | [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) | La definición de fuente. |

### getFontDefinition(int style) {#getFontDefinition-int-}
```
public final FontDefinitionExt getFontDefinition(int style)
```


Obtiene la definición de fuente de la familia para un estilo específico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| style | int | El estilo. |

**Returns:**
[FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) - Returns font definition if exist for specified style, null otherwise.
### matchesLocalizedFamilyName(String localizedFamilyName) {#matchesLocalizedFamilyName-java.lang.String-}
```
public final boolean matchesLocalizedFamilyName(String localizedFamilyName)
```


Coincide con los nombres de familia localizados en esta familia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localizedFamilyName | java.lang.String | El nombre de familia localizado. |

**Returns:**
boolean - true si esta familia incluye el nombre de familia localizado.
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Obtiene un nombre de familia de esta familia.

**Returns:**
java.lang.String - El nombre de familia, o null para una familia vacía.
