---
title: FontFamilyDefinition
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: تعريف عائلة الخط.
type: docs
weight: 25
url: /ar/java/com.aspose.drawing/fontfamilydefinition/
---
**Inheritance:**
java.lang.Object
```
public class FontFamilyDefinition
```

تعريف عائلة الخط.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FontFamilyDefinition()](#FontFamilyDefinition--) | يُنشئ مثيلًا جديدًا من الفئة [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addFontDefinition(int style, FontDefinitionExt fontDef)](#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-) | يضيف تعريف الخط إلى عائلة الخط. |
| [getFontDefinition(int style)](#getFontDefinition-int-) | يحصل على تعريف الخط من العائلة لنمط معين. |
| [matchesLocalizedFamilyName(String localizedFamilyName)](#matchesLocalizedFamilyName-java.lang.String-) | يطابق أسماء العائلات المحلية في هذه العائلة. |
| [getFamilyName()](#getFamilyName--) | يحصل على اسم عائلة لهذه العائلة. |
### FontFamilyDefinition() {#FontFamilyDefinition--}
```
public FontFamilyDefinition()
```


يُنشئ مثيلًا جديدًا من الفئة [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition).

### addFontDefinition(int style, FontDefinitionExt fontDef) {#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-}
```
public final void addFontDefinition(int style, FontDefinitionExt fontDef)
```


يضيف تعريف الخط إلى عائلة الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نمط | int | النمط. |
| fontDef | [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) | تعريف الخط. |

### getFontDefinition(int style) {#getFontDefinition-int-}
```
public final FontDefinitionExt getFontDefinition(int style)
```


يحصل على تعريف الخط من العائلة لنمط معين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نمط | int | النمط. |

**Returns:**
[FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) - Returns font definition if exist for specified style, null otherwise.
### matchesLocalizedFamilyName(String localizedFamilyName) {#matchesLocalizedFamilyName-java.lang.String-}
```
public final boolean matchesLocalizedFamilyName(String localizedFamilyName)
```


يطابق أسماء العائلات المحلية في هذه العائلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| localizedFamilyName | java.lang.String | اسم العائلة المحلي. |

**Returns:**
boolean - true إذا كانت هذه العائلة تشمل اسم العائلة المحلي.
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


يحصل على اسم عائلة لهذه العائلة.

**Returns:**
java.lang.String - اسم العائلة، أو null لعائلة فارغة.
