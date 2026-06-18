---
title: ImageAttributes
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحتوي على معلومات حول كيفية تعديل ألوان الصورة النقطية وملف الميتا أثناء العرض.
type: docs
weight: 24
url: /ar/java/com.aspose.drawing.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class ImageAttributes implements System.IDisposable
```

يحتوي على معلومات حول كيفية تعديل ألوان الصورة النقطية وملف الميتا أثناء العرض.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | ينشئ مثيلاً جديداً من الفئة [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [dispose()](#dispose--) | يطلق جميع الموارد المستخدمة من قبل هذا الكائن [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [deepClone()](#deepClone--) | ينشئ نسخة مطابقة تمامًا من هذا الكائن [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | يضبط مصفوفة تعديل اللون للفئة الافتراضية. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | يضبط مصفوفة تعديل اللون للفئة الافتراضية. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | يضبط مصفوفة تعديل اللون لفئة محددة. |
| [clearColorMatrix()](#clearColorMatrix--) | يمسح مصفوفة تعديل اللون للفئة الافتراضية. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | يمسح مصفوفة تعديل اللون لفئة محددة. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي لفئة محددة. |
| [setThreshold(float threshold)](#setThreshold-float-) | يضبط العتبة (نطاق الشفافية) للفئة الافتراضية. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | يضبط العتبة (نطاق الشفافية) لفئة محددة. |
| [clearThreshold()](#clearThreshold--) | يمسح قيمة العتبة للفئة الافتراضية. |
| [clearThreshold(int type)](#clearThreshold-int-) | يمسح قيمة العتبة لفئة محددة. |
| [setGamma(float gamma)](#setGamma-float-) | يضبط قيمة جاما للفئة الافتراضية. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | يضبط قيمة جاما لفئة محددة. |
| [clearGamma()](#clearGamma--) | يعطل تصحيح الجاما للفئة الافتراضية. |
| [clearGamma(int type)](#clearGamma-int-) | يعطل تصحيح الجاما لفئة محددة. |
| [setNoOp()](#setNoOp--) | يقوم بإيقاف تعديل اللون للفئة الافتراضية. |
| [setNoOp(int type)](#setNoOp-int-) | يقوم بإيقاف تعديل اللون لفئة محددة. |
| [clearNoOp()](#clearNoOp--) | يمسح إعداد NoOp للفئة الافتراضية. |
| [clearNoOp(int type)](#clearNoOp-int-) | يمسح إعداد NoOp لفئة محددة. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-) | يضبط مفتاح اللون للفئة الافتراضية. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | يضبط مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| [clearColorKey()](#clearColorKey--) | يمسح مفتاح اللون (نطاق الشفافية) للفئة الافتراضية. |
| [clearColorKey(int type)](#clearColorKey-int-) | يمسح مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | يضبط قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | يضبط قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) لفئة محددة. |
| [clearOutputChannel()](#clearOutputChannel--) | يمسح إعداد قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | يمسح إعداد قناة الإخراج (سماوي-ماجنتا-أصفر-أسود) لفئة محددة. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | يضبط ملف ملف تعريف ألوان قناة الإخراج للفئة الافتراضية. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | يضبط ملف تعريف ألوان قناة الإخراج لفئة محددة. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | يمسح إعداد ملف تعريف ألوان قناة الإخراج للفئة الافتراضية. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | يمسح إعداد ملف تعريف ألوان قناة الإخراج لفئة محددة. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---) | يضبط جدول إعادة تعيين الألوان للفئة الافتراضية. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-) | يضبط جدول إعادة تعيين الألوان لفئة محددة. |
| [clearRemapTable()](#clearRemapTable--) | يمسح جدول إعادة تعيين الألوان للفئة الافتراضية. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | يمسح جدول إعادة تعيين الألوان لفئة محددة. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---) | يضبط جدول إعادة تعيين الألوان لفئة الفرشاة. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | يمسح جدول إعادة تعيين ألوان الفرشاة لهذا الكائن [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [setWrapMode(int mode)](#setWrapMode-int-) | يضبط وضع الالتفاف المستخدم لتحديد كيفية تكرار النسيج عبر الشكل أو عند حدود الشكل. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.drawing.Color-) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تكرار النسيج عبر الشكل أو عند حدود الشكل. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.drawing.Color-boolean-) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تكرار النسيج عبر الشكل أو عند حدود الشكل. |
| [getAdjustedPalette(ColorPalette palette, int type)](#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-) | يضبط الألوان في لوحة الألوان وفقًا لإعدادات الضبط لفئة محددة. |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


ينشئ مثيلاً جديداً من الفئة [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### dispose() {#dispose--}
```
public void dispose()
```


يطلق جميع الموارد المستخدمة من قبل هذا الكائن [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### deepClone() {#deepClone--}
```
public Object deepClone()
```


ينشئ نسخة مطابقة تمامًا من هذا الكائن [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

**Returns:**
java.lang.Object - كائن [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) الذي تنشئه هذه الفئة، محول إلى كائن.
### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


يضبط مصفوفة تعديل اللون للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | مصفوفة تعديل اللون. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


يضبط مصفوفة تعديل اللون للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | مصفوفة تعديل اللون. |
| flags | int | عنصر من [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) يحدد نوع الصورة واللون الذي سيتأثر بمصفوفة تعديل اللون. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


يضبط مصفوفة تعديل اللون لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | مصفوفة تعديل اللون. |
| mode | int | عنصر من [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) يحدد نوع الصورة واللون الذي سيتأثر بمصفوفة تعديل اللون. |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي تم تعيين مصفوفة تعديل اللون لها. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


يمسح مصفوفة تعديل اللون للفئة الافتراضية.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


يمسح مصفوفة تعديل اللون لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي تم مسح مصفوفة تعديل اللون منها. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | مصفوفة تعديل اللون. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | مصفوفة تعديل التدرج الرمادي. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | مصفوفة تعديل اللون. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | مصفوفة تعديل التدرج الرمادي. |
| flags | int | عنصر من [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) يحدد نوع الصورة واللون الذي سيتأثر بمصفوفات تعديل اللون وتعديل التدرج الرمادي. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | مصفوفة تعديل اللون. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | مصفوفة تعديل التدرج الرمادي. |
| mode | int | عنصر من [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) يحدد نوع الصورة واللون الذي سيتأثر بمصفوفات تعديل اللون وتعديل التدرج الرمادي. |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي تم تعيين مصفوفات تعديل اللون وتعديل التدرج الرمادي لها. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


يضبط العتبة (نطاق الشفافية) للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الحدّ | float | عدد حقيقي يحدد قيمة الحدّ. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


يضبط العتبة (نطاق الشفافية) لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الحدّ | float | قيمة حدّ من 0.0 إلى 1.0 تُستخدم كنقطة فاصل لتصنيف الألوان التي سيتم تعيينها إما إلى قيمة قصوى أو دنيا. |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي تم تعيين حدّ اللون لها. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


يمسح قيمة العتبة للفئة الافتراضية.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


يمسح قيمة العتبة لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي تم مسح الحدّ منها. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


يضبط قيمة جاما للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| جاما | float | قيمة تصحيح الجاما. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


يضبط قيمة جاما لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| جاما | float | قيمة تصحيح الجاما. |
| type | int | عنصر من تعداد [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي يتم فيها تعيين قيمة الجاما. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


يعطل تصحيح الجاما للفئة الافتراضية.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


يعطل تصحيح الجاما لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي يتم فيها تعطيل تصحيح الجاما. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


يقوم بإيقاف تعديل اللون للفئة الافتراضية. يمكنك استدعاء طريقة [.clearNoOp](../../null/\#clearNoOp) لاستعادة إعدادات تعديل اللون التي كانت سارية قبل استدعاء طريقة [.setNoOp](../../null/\#setNoOp).

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


يقوم بإيقاف تعديل اللون لفئة محددة. يمكنك استدعاء طريقة [.clearNoOp](../../null/\#clearNoOp) لاستعادة إعدادات تعديل اللون التي كانت سارية قبل استدعاء طريقة [.setNoOp](../../null/\#setNoOp).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي يتم فيها إيقاف تصحيح اللون. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


يمسح إعداد NoOp للفئة الافتراضية.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


يمسح إعداد NoOp لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي يتم فيها مسح إعداد NoOp. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


يضبط مفتاح اللون للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | قيمة مفتاح اللون المنخفض. |
| colorHigh | [Color](../../com.aspose.drawing/color) | قيمة مفتاح اللون العالي. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


يضبط مفتاح اللون (نطاق الشفافية) لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | قيمة مفتاح اللون المنخفض. |
| colorHigh | [Color](../../com.aspose.drawing/color) | قيمة مفتاح اللون العالي. |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي يتم فيها تعيين مفتاح اللون. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


يمسح مفتاح اللون (نطاق الشفافية) للفئة الافتراضية.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


يمسح مفتاح اللون (نطاق الشفافية) لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي يتم فيها مسح مفتاح اللون. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


يضبط قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| flags | int | عنصر من [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) يحدد قناة الإخراج. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


يضبط قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| flags | int | عنصر من [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) يحدد قناة الإخراج. |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي يتم فيها تعيين قناة الإخراج. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


يمسح إعداد قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


يمسح إعداد قناة الإخراج (سماوي-ماجنتا-أصفر-أسود) لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي يتم فيها مسح إعداد قناة الإخراج. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


يضبط ملف ملف تعريف ألوان قناة الإخراج للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | اسم المسار لملف ملف تعريف اللون. إذا كان ملف تعريف اللون موجودًا في الدليل %SystemRoot%\\System32\\Spool\\Drivers\\Color، يمكن أن يكون هذا المعامل اسم الملف. وإلا، يجب أن يكون هذا المعامل اسم المسار الكامل المؤهل. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


يضبط ملف تعريف ألوان قناة الإخراج لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | اسم المسار لملف ملف تعريف اللون. إذا كان ملف تعريف اللون موجودًا في الدليل %SystemRoot%\\System32\\Spool\\Drivers\\Color، يمكن أن يكون هذا المعامل اسم الملف. وإلا، يجب أن يكون هذا المعامل اسم المسار الكامل المؤهل. |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي يتم فيها تعيين ملف تعريف لون قناة الإخراج. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


يمسح إعداد ملف تعريف ألوان قناة الإخراج للفئة الافتراضية.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


يمسح إعداد ملف تعريف ألوان قناة الإخراج لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي يتم فيها مسح إعداد ملف تعريف قناة الإخراج. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


يضبط جدول إعادة تعيين الألوان للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | مصفوفة من أزواج الألوان من النوع [ColorMap](../../com.aspose.drawing.imaging/colormap). يحتوي كل زوج ألوان على لون موجود (القيمة الأولى) واللون الذي سيتم تحويله إليه (القيمة الثانية). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


يضبط جدول إعادة تعيين الألوان لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | مصفوفة من أزواج الألوان من النوع [ColorMap](../../com.aspose.drawing.imaging/colormap). يحتوي كل زوج ألوان على لون موجود (القيمة الأولى) واللون الذي سيتم تحويله إليه (القيمة الثانية). |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي يتم فيها تعيين جدول إعادة تعيين اللون. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


يمسح جدول إعادة تعيين الألوان للفئة الافتراضية.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


يمسح جدول إعادة تعيين الألوان لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي يتم فيها مسح جدول إعادة التعيين. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


يضبط جدول إعادة تعيين الألوان لفئة الفرشاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | مصفوفة من كائنات [ColorMap](../../com.aspose.drawing.imaging/colormap). |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


يمسح جدول إعادة تعيين ألوان الفرشاة لهذا الكائن [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


يضبط وضع الالتفاف المستخدم لتحديد كيفية تكرار النسيج عبر الشكل أو عند حدود الشكل. يتم تكرار النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يملأه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mode | int | عنصر من [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) يحدد كيفية استخدام نسخ مكررة من الصورة لتغطية منطقة. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.drawing.Color-}
```
public void setWrapMode(int mode, Color color)
```


يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تكرار النسيج عبر الشكل، أو عند حدود الشكل. يتم تكرار النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم ملئه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mode | int | عنصر من [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) يحدد كيفية استخدام نسخ مكررة من الصورة لتغطية منطقة. |
| color | [Color](../../com.aspose.drawing/color) | كائن [Color](../../com.aspose.drawing/color) يحدد لون البكسلات خارج الصورة المرسومة. يكون هذا اللون مرئيًا إذا تم ضبط معامل الوضع على `WrapMode.Clamp` وكان المستطيل المصدر الممرّر إلى `Graphics.DrawImage` أكبر من الصورة نفسها. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.drawing.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تكرار النسيج عبر الشكل، أو عند حدود الشكل. يتم تكرار النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم ملئه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mode | int | عنصر من [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) يحدد كيفية استخدام نسخ مكررة من الصورة لتغطية منطقة. |
| color | [Color](../../com.aspose.drawing/color) | كائن لون يحدد لون البكسلات خارج الصورة المرسومة. يكون هذا اللون مرئيًا إذا تم ضبط معامل الوضع على `WrapMode.Clamp` وكان المستطيل المصدر الممرّر إلى `Graphics.DrawImage` أكبر من الصورة نفسها. |
| clamp | boolean | هذا المعامل لا يؤثر. اضبطه على false. |

### getAdjustedPalette(ColorPalette palette, int type) {#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-}
```
public void getAdjustedPalette(ColorPalette palette, int type)
```


يضبط الألوان في لوحة الألوان وفقًا لإعدادات الضبط لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) | كائن [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) يحتوي عند الإدخال على لوحة الألوان التي سيتم تعديلها، وعند الإخراج يحتوي على لوحة الألوان المعدلة. |
| type | int | عنصر من [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) يحدد الفئة التي سيتم تطبيق إعدادات التعديل الخاصة بها على لوحة الألوان. |

