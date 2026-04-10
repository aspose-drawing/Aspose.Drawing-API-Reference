---
title: ColorPalette
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يعرف مصفوفة من الألوان التي تشكل لوحة ألوان.
type: docs
weight: 16
url: /ar/java/com.aspose.drawing.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPalette
```

يُعرّف مصفوفة من الألوان التي تُكوّن لوحة ألوان. الألوان هي ألوان ARGB 32‑بت. غير قابل للوراثة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ColorPalette(int count)](#ColorPalette-int-) | يُنشئ مثيلاً جديداً من الفئة `ColorPalette` وتكون IsCompactPalette قيمتها false. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEntries()](#getEntries--) | يحصل على مصفوفة من هياكل `com.aspose.drawing.Color`. |
| [isCompactPalette()](#isCompactPalette--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يتم استخدام لوحة ألوان مدمجة. |
| [getFlags()](#getFlags--) |  |
| [setFlags(int flags)](#setFlags-int-) |  |
| [setEntries(int i, Color color)](#setEntries-int-com.aspose.drawing.Color-) |  |
### ColorPalette(int count) {#ColorPalette-int-}
```
public ColorPalette(int count)
```


يُنشئ مثيلاً جديداً من الفئة `ColorPalette` وتكون IsCompactPalette قيمتها false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| count | int | مدخلات لوحة الألوان. |

### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


يحصل على مصفوفة من هياكل `com.aspose.drawing.Color`.

**Returns:**
com.aspose.drawing.Color[] - المدخلات. مصفوفة من هياكل `com.aspose.drawing.Color` التي تُكوّن هذا `Aspose.Imaging.ColorPalette`.
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان يتم استخدام لوحة ألوان مدمجة.

**Returns:**
منطقي - `true` إذا تم استخدام لوحة ألوان مدمجة؛ وإلا `false`.

تعني لوحة الألوان المدمجة أن الصورة ستحتوي فقط على مدخلات اللوحة المحددة إذا كان ذلك ممكنًا، أو بعبارة أخرى ستكون الصورة أكثر دمجًا وتشغل مساحة أقل؛ وإلا سيكون هناك 2^BitsPerPixel مدخلًا وستحجز الصورة مساحة أكبر لجميع مدخلات اللوحة الممكنة. ضبط هذه القيمة إلى true وتغيير مدخلات اللوحة قد يسبب عقوبة أداء لأن حركة البيانات قد تحدث، لذا استخدمها بحذر.
### getFlags() {#getFlags--}
```
public int getFlags()
```




**Returns:**
int
### setFlags(int flags) {#setFlags-int-}
```
public void setFlags(int flags)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| flags | int |  |

### setEntries(int i, Color color) {#setEntries-int-com.aspose.drawing.Color-}
```
public void setEntries(int i, Color color)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| i | int |  |
| color | [Color](../../com.aspose.drawing/color) |  |

