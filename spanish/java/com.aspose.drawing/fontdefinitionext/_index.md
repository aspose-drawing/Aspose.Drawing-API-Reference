---
title: FontDefinitionExt
second_title: Referencia de la API de Aspose.Drawing para Java
description: La clase contiene la definición de fuente
type: docs
weight: 23
url: /es/java/com.aspose.drawing/fontdefinitionext/
---
**Inheritance:**
java.lang.Object
```
public class FontDefinitionExt
```

Clase que contiene la definición de fuente,
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)](#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-) | Inicializa una nueva instancia de la clase [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Obtiene el nombre de la familia de fuentes. |
| [getStyle()](#getStyle--) | Obtiene el estilo de la fuente. |
| [getFontName()](#getFontName--) | Obtiene el nombre de la fuente. |
| [getPostscriptName()](#getPostscriptName--) | Obtiene el nombre PostScript de la fuente. |
| [getType()](#getType--) | Obtiene el tipo de fuente. |
| [getFontFile()](#getFontFile--) | Obtiene el archivo de fuente. |
| [getFileName()](#getFileName--) | Obtiene el nombre del archivo. |
| [getFont()](#getFont--) | Obtiene la fuente. |
### FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset) {#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-}
```
public FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)
```


Inicializa una nueva instancia de la clase [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Nombre de la fuente. |
| familyName | java.lang.String | Familia de la fuente. |
| localizedFamilyNames | java.util.List<java.lang.String> | Nombres de familia de fuentes localizados. |
| type | int | El tipo. |
| fileName | java.lang.String | Nombre del archivo. |
| offset | long | El desplazamiento. |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Obtiene el nombre de la familia de fuentes.

Valor: El nombre de la familia de fuentes.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public final String getStyle()
```


Obtiene el estilo de la fuente.

Valor: El estilo de la fuente.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public final String getFontName()
```


Obtiene el nombre de la fuente.

Valor: El nombre de la fuente.

**Returns:**
java.lang.String
### getPostscriptName() {#getPostscriptName--}
```
public final String getPostscriptName()
```


Obtiene el nombre PostScript de la fuente.

Valor: El nombre PostScript de la fuente.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Obtiene el tipo de fuente.

Valor: El tipo de fuente.

**Returns:**
int
### getFontFile() {#getFontFile--}
```
public final FontFileDefinition getFontFile()
```


Obtiene el archivo de fuente.

Valor: El archivo de fuente.

**Returns:**
com.aspose.fonts.sources.FontFileDefinition
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Obtiene el nombre del archivo.

Valor: El nombre del archivo.

**Returns:**
java.lang.String
### getFont() {#getFont--}
```
public final IFont getFont()
```


Obtiene la fuente.

**Returns:**
com.aspose.fonts.IFont - Devuelve la fuente para la definición actual.
