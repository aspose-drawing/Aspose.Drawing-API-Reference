---
title: FontFamilyDefinition
second_title: Riferimento API di Aspose.Drawing per Java
description: La definizione della famiglia di font.
type: docs
weight: 25
url: /it/java/com.aspose.drawing/fontfamilydefinition/
---
**Inheritance:**
java.lang.Object
```
public class FontFamilyDefinition
```

La definizione della famiglia di font.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontFamilyDefinition()](#FontFamilyDefinition--) | Inizializza una nuova istanza della classe [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addFontDefinition(int style, FontDefinitionExt fontDef)](#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-) | Aggiunge la definizione del carattere alla famiglia di caratteri. |
| [getFontDefinition(int style)](#getFontDefinition-int-) | Ottiene la definizione del carattere dalla famiglia per uno stile specifico. |
| [matchesLocalizedFamilyName(String localizedFamilyName)](#matchesLocalizedFamilyName-java.lang.String-) | Confronta i nomi di famiglia localizzati in questa famiglia. |
| [getFamilyName()](#getFamilyName--) | Ottiene un nome di famiglia di questa famiglia. |
### FontFamilyDefinition() {#FontFamilyDefinition--}
```
public FontFamilyDefinition()
```


Inizializza una nuova istanza della classe [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition).

### addFontDefinition(int style, FontDefinitionExt fontDef) {#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-}
```
public final void addFontDefinition(int style, FontDefinitionExt fontDef)
```


Aggiunge la definizione del carattere alla famiglia di caratteri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| style | int | Lo stile. |
| fontDef | [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) | La definizione del carattere. |

### getFontDefinition(int style) {#getFontDefinition-int-}
```
public final FontDefinitionExt getFontDefinition(int style)
```


Ottiene la definizione del carattere dalla famiglia per uno stile specifico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| style | int | Lo stile. |

**Returns:**
[FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) - Returns font definition if exist for specified style, null otherwise.
### matchesLocalizedFamilyName(String localizedFamilyName) {#matchesLocalizedFamilyName-java.lang.String-}
```
public final boolean matchesLocalizedFamilyName(String localizedFamilyName)
```


Confronta i nomi di famiglia localizzati in questa famiglia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localizedFamilyName | java.lang.String | Il nome di famiglia localizzato. |

**Returns:**
boolean - true se questa famiglia include il nome di famiglia localizzato.
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Ottiene un nome di famiglia di questa famiglia.

**Returns:**
java.lang.String - Il nome della famiglia, o null per una famiglia vuota.
