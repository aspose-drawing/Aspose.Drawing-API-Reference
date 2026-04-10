---
title: TextRenderingHint
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحدد جودة عرض النص.
type: docs
weight: 14
url: /ar/java/com.aspose.drawing.text/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

يحدد جودة عرض النص.
## الحقول

| حقل | الوصف |
| --- | --- |
| [SystemDefault](#SystemDefault) | يتم رسم كل حرف باستخدام صورة البكسل الخاصة به، مع تلميح العرض الافتراضي للنظام. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | يتم رسم كل حرف باستخدام صورة البكسل الخاصة به. |
| [SingleBitPerPixel](#SingleBitPerPixel) | يتم رسم كل حرف باستخدام صورة البكسل الخاصة به. |
| [AntiAliasGridFit](#AntiAliasGridFit) | يتم رسم كل حرف باستخدام صورة البكسل المضادة للتمويه مع التلميح. |
| [AntiAlias](#AntiAlias) | يتم رسم كل حرف باستخدام صورة البكسل المضادة للتمويه بدون التلميح. |
| [ClearTypeGridFit](#ClearTypeGridFit) | يتم رسم كل حرف باستخدام صورة البكسل ClearType الخاصة به مع التلميح. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


يتم رسم كل حرف باستخدام صورة البكسل الخاصة به، مع تلميح العرض الافتراضي للنظام. سيُرسم النص باستخدام أي إعدادات تنعيم للخط اختارها المستخدم للنظام.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


يتم رسم كل حرف باستخدام صورة البكسل الخاصة به. يُستخدم التلميح لتحسين مظهر الحرف على الجذوع والانحناءات.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


يتم رسم كل حرف باستخدام صورة البت الخاصة بالرمز. لا يتم استخدام التلميح.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


يتم رسم كل حرف باستخدام صورة البت المضادة للتمويه الخاصة بالرمز مع التلميح. جودة أفضل بكثير بفضل مضاد التمويه، لكن بتكلفة أداء أعلى.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


يتم رسم كل حرف باستخدام صورة البت المضادة للتمويه الخاصة بالرمز بدون التلميح. جودة أفضل بفضل مضاد التمويه. قد تكون اختلافات عرض الجذع ملحوظة لأن التلميح مُعطل.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


يتم رسم كل حرف باستخدام صورة البت ClearType الخاصة بالرمز مع التلميح. أعلى إعداد للجودة. يُستخدم للاستفادة من ميزات خطوط ClearType.

