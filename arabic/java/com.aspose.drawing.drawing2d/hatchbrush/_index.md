---
title: HatchBrush
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يعرّف فرشاة مستطيلة بنمط التظليل ولون أمامي ولون خلفي.
type: docs
weight: 26
url: /ar/java/com.aspose.drawing.drawing2d/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class HatchBrush extends Brush
```

يعرّف فرشاة مستطيلة بنمط التظليل، ولون أمامي، ولون خلفي. لا يمكن وراثة هذه الفئة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [HatchBrush(int hatchstyle, Color foreColor)](#HatchBrush-int-com.aspose.drawing.Color-) | ينشئ مثيلاً جديداً من الفئة [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) باستخدام تعداد `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) واللون الأمامي. |
| [HatchBrush(int hatchstyle, Color foreColor, Color backColor)](#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-) | ينشئ مثيلاً جديداً من الفئة [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) باستخدام تعداد `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle))، اللون الأمامي، واللون الخلفي. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHatchStyle()](#getHatchStyle--) | يحصل على نمط التظليل لهذا الكائن [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [getForegroundColor()](#getForegroundColor--) | يحصل على لون خطوط التظليل المرسومة بواسطة هذا الكائن [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون الفراغات بين خطوط التظليل المرسومة بواسطة هذا الكائن [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [deepClone()](#deepClone--) | ينشئ نسخة مطابقة تماماً من هذا الكائن [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
### HatchBrush(int hatchstyle, Color foreColor) {#HatchBrush-int-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor)
```


ينشئ مثيلاً جديداً من الفئة [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) باستخدام تعداد `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) واللون الأمامي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| hatchstyle | int | إحدى قيم `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) التي تمثل النمط المرسوم بواسطة هذا [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| foreColor | [Color](../../com.aspose.drawing/color) | البنية [Color](../../com.aspose.drawing/color) التي تمثل لون الخطوط المرسومة بواسطة هذا [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |

### HatchBrush(int hatchstyle, Color foreColor, Color backColor) {#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor, Color backColor)
```


ينشئ مثيلاً جديداً من الفئة [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) باستخدام تعداد `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle))، اللون الأمامي، واللون الخلفي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| hatchstyle | int | إحدى قيم `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) التي تمثل النمط المرسوم بواسطة هذا [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| foreColor | [Color](../../com.aspose.drawing/color) | البنية [Color](../../com.aspose.drawing/color) التي تمثل لون الخطوط المرسومة بواسطة هذا [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| backColor | [Color](../../com.aspose.drawing/color) | البنية [Color](../../com.aspose.drawing/color) التي تمثل لون الفراغات بين الخطوط المرسومة بواسطة هذا [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


يحصل على نمط التظليل لهذا الكائن [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
int - نمط التظليل لهذا الكائن [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


يحصل على لون خطوط التظليل المرسومة بواسطة هذا الكائن [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


يحصل على لون الفراغات بين خطوط التظليل المرسومة بواسطة هذا الكائن [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of spaces between the hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


ينشئ نسخة مطابقة تماماً من هذا الكائن [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
java.lang.Object - الـ [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) الذي تُنشئه هذه الطريقة، مُحوَّل إلى كائن.
