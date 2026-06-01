---
title: FontFamilyDefinition
second_title: Справочник API Aspose.Drawing для Java
description: Определение семейства шрифтов.
type: docs
weight: 25
url: /ru/java/com.aspose.drawing/fontfamilydefinition/
---
**Inheritance:**
java.lang.Object
```
public class FontFamilyDefinition
```

Определение семейства шрифтов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontFamilyDefinition()](#FontFamilyDefinition--) | Инициализирует новый экземпляр класса [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition). |
## Методы

| Метод | Описание |
| --- | --- |
| [addFontDefinition(int style, FontDefinitionExt fontDef)](#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-) | Добавляет определение шрифта в семейство шрифтов. |
| [getFontDefinition(int style)](#getFontDefinition-int-) | Получает определение шрифта из семейства для конкретного стиля. |
| [matchesLocalizedFamilyName(String localizedFamilyName)](#matchesLocalizedFamilyName-java.lang.String-) | Сравнивает локализованные имена семейства в этом семействе. |
| [getFamilyName()](#getFamilyName--) | Получает имя семейства этого семейства. |
### FontFamilyDefinition() {#FontFamilyDefinition--}
```
public FontFamilyDefinition()
```


Инициализирует новый экземпляр класса [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition).

### addFontDefinition(int style, FontDefinitionExt fontDef) {#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-}
```
public final void addFontDefinition(int style, FontDefinitionExt fontDef)
```


Добавляет определение шрифта в семейство шрифтов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| стиль | int | Стиль. |
| fontDef | [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) | Определение шрифта. |

### getFontDefinition(int style) {#getFontDefinition-int-}
```
public final FontDefinitionExt getFontDefinition(int style)
```


Получает определение шрифта из семейства для конкретного стиля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| стиль | int | Стиль. |

**Returns:**
[FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) - Returns font definition if exist for specified style, null otherwise.
### matchesLocalizedFamilyName(String localizedFamilyName) {#matchesLocalizedFamilyName-java.lang.String-}
```
public final boolean matchesLocalizedFamilyName(String localizedFamilyName)
```


Сравнивает локализованные имена семейства в этом семействе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| localizedFamilyName | java.lang.String | Локализованное имя семейства. |

**Returns:**
boolean — true, если это семейство включает локализованное имя семейства.
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Получает имя семейства этого семейства.

**Returns:**
java.lang.String — имя семейства или null для пустого семейства.
