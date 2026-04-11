---
title: FontDefinitionExt
second_title: Справочник API Aspose.Drawing для Java
description: Класс содержит определение шрифта
type: docs
weight: 23
url: /ru/java/com.aspose.drawing/fontdefinitionext/
---
**Inheritance:**
java.lang.Object
```
public class FontDefinitionExt
```

Класс содержит определение шрифта,
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)](#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-) | Инициализирует новый экземпляр класса [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext). |
## Методы

| Метод | Описание |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Получает название семейства шрифта. |
| [getStyle()](#getStyle--) | Получает стиль шрифта. |
| [getFontName()](#getFontName--) | Получает название шрифта. |
| [getPostscriptName()](#getPostscriptName--) | Получает postscript‑название шрифта. |
| [getType()](#getType--) | Получает тип шрифта. |
| [getFontFile()](#getFontFile--) | Получает файл шрифта. |
| [getFileName()](#getFileName--) | Получает название файла. |
| [getFont()](#getFont--) | Получает шрифт. |
### FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset) {#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-}
```
public FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)
```


Инициализирует новый экземпляр класса [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Название шрифта. |
| familyName | java.lang.String | Семейство шрифта. |
| localizedFamilyNames | java.util.List<java.lang.String> | Локализованные названия семейств шрифтов. |
| тип | int | Тип. |
| fileName | java.lang.String | Название файла. |
| offset | long | Смещение. |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Получает название семейства шрифта.

Значение: название семейства шрифта.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public final String getStyle()
```


Получает стиль шрифта.

Значение: стиль шрифта.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public final String getFontName()
```


Получает название шрифта.

Значение: название шрифта.

**Returns:**
java.lang.String
### getPostscriptName() {#getPostscriptName--}
```
public final String getPostscriptName()
```


Получает postscript‑название шрифта.

Значение: postscript‑имя шрифта.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Получает тип шрифта.

Значение: тип шрифта.

**Returns:**
int
### getFontFile() {#getFontFile--}
```
public final FontFileDefinition getFontFile()
```


Получает файл шрифта.

Значение: файл шрифта.

**Returns:**
com.aspose.fonts.sources.FontFileDefinition
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Получает название файла.

Значение: имя файла.

**Returns:**
java.lang.String
### getFont() {#getFont--}
```
public final IFont getFont()
```


Получает шрифт.

**Returns:**
com.aspose.fonts.IFont - Возвращает шрифт для текущего определения.
