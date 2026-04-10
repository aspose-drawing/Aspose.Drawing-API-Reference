---
title: FontDefinitionExt
second_title: Riferimento API di Aspose.Drawing per Java
description: La classe contiene la definizione del font
type: docs
weight: 23
url: /it/java/com.aspose.drawing/fontdefinitionext/
---
**Inheritance:**
java.lang.Object
```
public class FontDefinitionExt
```

La classe contiene la definizione del font,
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)](#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-) | Inizializza una nuova istanza della classe [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Ottiene il nome della famiglia del font. |
| [getStyle()](#getStyle--) | Ottiene lo stile del font. |
| [getFontName()](#getFontName--) | Ottiene il nome del font. |
| [getPostscriptName()](#getPostscriptName--) | Ottiene il nome PostScript del font. |
| [getType()](#getType--) | Ottiene il tipo di font. |
| [getFontFile()](#getFontFile--) | Ottiene il file del font. |
| [getFileName()](#getFileName--) | Ottiene il nome del file. |
| [getFont()](#getFont--) | Ottiene il font. |
### FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset) {#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-}
```
public FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)
```


Inizializza una nuova istanza della classe [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Nome del font. |
| familyName | java.lang.String | Famiglia del font. |
| localizedFamilyNames | java.util.List<java.lang.String> | Nomi della famiglia del font localizzati. |
| type | int | Il tipo. |
| fileName | java.lang.String | Nome del file. |
| offset | long | L'offset. |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Ottiene il nome della famiglia del font.

Valore: Il nome della famiglia del font.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public final String getStyle()
```


Ottiene lo stile del font.

Valore: Lo stile del font.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public final String getFontName()
```


Ottiene il nome del font.

Valore: Il nome del font.

**Returns:**
java.lang.String
### getPostscriptName() {#getPostscriptName--}
```
public final String getPostscriptName()
```


Ottiene il nome PostScript del font.

Valore: il nome PostScript del carattere.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Ottiene il tipo di font.

Valore: il tipo di carattere.

**Returns:**
int
### getFontFile() {#getFontFile--}
```
public final FontFileDefinition getFontFile()
```


Ottiene il file del font.

Valore: il file del carattere.

**Returns:**
com.aspose.fonts.sources.FontFileDefinition
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Ottiene il nome del file.

Valore: il nome del file.

**Returns:**
java.lang.String
### getFont() {#getFont--}
```
public final IFont getFont()
```


Ottiene il font.

**Returns:**
com.aspose.fonts.IFont - Restituisce il carattere per la definizione corrente.
