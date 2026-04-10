---
title: CopyPixelOperation
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحدد كيفية دمج لون المصدر في عملية نسخ البكسل مع لون الوجهة للحصول على اللون النهائي.
type: docs
weight: 18
url: /ar/java/com.aspose.drawing/copypixeloperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CopyPixelOperation extends System.Enum
```

يحدد كيفية دمج لون المصدر في عملية نسخ البكسل مع لون الوجهة للحصول على اللون النهائي.
## الحقول

| حقل | الوصف |
| --- | --- |
| [NoMirrorBitmap](#NoMirrorBitmap) | الصورة النقطية غير معكوسة. |
| [Blackness](#Blackness) | يتم ملء المنطقة الوجهة باستخدام اللون المرتبط بالفهرس 0 في لوحة الألوان الفيزيائية. |
| [NotSourceErase](#NotSourceErase) | يتم دمج ألوان المصدر والوجهة باستخدام العامل البولياني `OR`، ثم يتم عكس اللون الناتج. |
| [NotSourceCopy](#NotSourceCopy) | يتم نسخ المنطقة المصدر المعكوسة إلى الوجهة. |
| [SourceErase](#SourceErase) | يتم دمج الألوان المعكوسة للمنطقة الوجهة مع ألوان المنطقة المصدر باستخدام العامل البولياني `AND`. |
| [DestinationInvert](#DestinationInvert) | يتم عكس المنطقة الوجهة. |
| [PatInvert](#PatInvert) | يتم دمج ألوان الفرشاة المحددة حاليًا في سياق جهاز الوجهة مع ألوان الوجهة باستخدام العامل البولياني `XOR`. |
| [SourceInvert](#SourceInvert) | يتم دمج ألوان مناطق المصدر والوجهة باستخدام العامل البولياني `XOR`. |
| [SourceAnd](#SourceAnd) | يتم دمج ألوان مناطق المصدر والوجهة باستخدام العامل البولياني `AND`. |
| [MergePaint](#MergePaint) | يتم دمج ألوان المنطقة المصدر المعكوسة مع ألوان المنطقة الوجهة باستخدام العامل البولياني `OR`. |
| [MergeCopy](#MergeCopy) | يتم دمج ألوان المنطقة المصدر مع ألوان الفرشاة المحددة في سياق جهاز الوجهة باستخدام العامل البولياني `AND`. |
| [SourceCopy](#SourceCopy) | يتم نسخ المنطقة المصدر مباشرةً إلى المنطقة الوجهة. |
| [SourcePaint](#SourcePaint) | يتم دمج ألوان مناطق المصدر والوجهة باستخدام العامل البولياني `OR`. |
| [PatCopy](#PatCopy) | يتم نسخ الفرشاة المحددة حاليًا في سياق جهاز الوجهة إلى الصورة النقطية الوجهة. |
| [PatPaint](#PatPaint) | يتم دمج ألوان الفرشاة المحددة حاليًا في سياق جهاز الوجهة مع ألوان المنطقة المصدر المعكوسة باستخدام العامل البولياني `OR`. |
| [Whiteness](#Whiteness) | يتم ملء المنطقة الوجهة باستخدام اللون المرتبط بالفهرس 1 في لوحة الألوان الفيزيائية. |
| [CaptureBlt](#CaptureBlt) | النوافذ التي تُرصّ فوق نافذتك تُدرج في الصورة الناتجة. |
### NoMirrorBitmap {#NoMirrorBitmap}
```
public static final int NoMirrorBitmap
```


الصورة النقطية غير معكوسة.

### Blackness {#Blackness}
```
public static final int Blackness
```


يتم ملء المنطقة الوجهة باستخدام اللون المرتبط بالفهرس 0 في لوحة الألوان الفيزيائية. (هذا اللون هو الأسود للوحة الألوان الفيزيائية الافتراضية.)

### NotSourceErase {#NotSourceErase}
```
public static final int NotSourceErase
```


يتم دمج ألوان المصدر والوجهة باستخدام العامل البولياني `OR`، ثم يتم عكس اللون الناتج.

### NotSourceCopy {#NotSourceCopy}
```
public static final int NotSourceCopy
```


يتم نسخ المنطقة المصدر المعكوسة إلى الوجهة.

### SourceErase {#SourceErase}
```
public static final int SourceErase
```


يتم دمج الألوان المعكوسة للمنطقة الوجهة مع ألوان المنطقة المصدر باستخدام العامل البولياني `AND`.

### DestinationInvert {#DestinationInvert}
```
public static final int DestinationInvert
```


يتم عكس المنطقة الوجهة.

### PatInvert {#PatInvert}
```
public static final int PatInvert
```


يتم دمج ألوان الفرشاة المحددة حاليًا في سياق جهاز الوجهة مع ألوان الوجهة باستخدام العامل البولياني `XOR`.

### SourceInvert {#SourceInvert}
```
public static final int SourceInvert
```


يتم دمج ألوان مناطق المصدر والوجهة باستخدام العامل البولياني `XOR`.

### SourceAnd {#SourceAnd}
```
public static final int SourceAnd
```


يتم دمج ألوان مناطق المصدر والوجهة باستخدام العامل البولياني `AND`.

### MergePaint {#MergePaint}
```
public static final int MergePaint
```


يتم دمج ألوان المنطقة المصدر المعكوسة مع ألوان المنطقة الوجهة باستخدام العامل البولياني `OR`.

### MergeCopy {#MergeCopy}
```
public static final int MergeCopy
```


يتم دمج ألوان المنطقة المصدر مع ألوان الفرشاة المحددة في سياق جهاز الوجهة باستخدام العامل البولياني `AND`.

### SourceCopy {#SourceCopy}
```
public static final int SourceCopy
```


يتم نسخ المنطقة المصدر مباشرةً إلى المنطقة الوجهة.

### SourcePaint {#SourcePaint}
```
public static final int SourcePaint
```


يتم دمج ألوان مناطق المصدر والوجهة باستخدام العامل البولياني `OR`.

### PatCopy {#PatCopy}
```
public static final int PatCopy
```


يتم نسخ الفرشاة المحددة حاليًا في سياق جهاز الوجهة إلى الصورة النقطية الوجهة.

### PatPaint {#PatPaint}
```
public static final int PatPaint
```


يتم دمج ألوان الفرشاة المحددة حاليًا في سياق جهاز الوجهة مع ألوان المنطقة المصدر المعكوسة باستخدام عامل Boolean `OR`. يتم دمج نتيجة هذه العملية مع ألوان منطقة الوجهة باستخدام عامل Boolean `OR`.

### Whiteness {#Whiteness}
```
public static final int Whiteness
```


يتم ملء منطقة الوجهة باستخدام اللون المرتبط بالفهرس 1 في اللوحة الفيزيائية. (هذا اللون أبيض للوحة الفيزيائية الافتراضية.)

### CaptureBlt {#CaptureBlt}
```
public static final int CaptureBlt
```


تُدرج النوافذ المتراكبة فوق نافذتك في الصورة الناتجة. بشكل افتراضي، تحتوي الصورة على نافذتك فقط. لاحظ أن هذا لا يمكن عادةً استخدامه لسياقات أجهزة الطباعة.

