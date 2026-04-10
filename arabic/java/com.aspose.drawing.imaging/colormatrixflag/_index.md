---
title: ColorMatrixFlag
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحدد أنواع الصور والألوان التي سيتأثر بها إعدادات تعديل اللون وتدرج الرمادي لـ .
type: docs
weight: 15
url: /ar/java/com.aspose.drawing.imaging/colormatrixflag/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorMatrixFlag extends System.Enum
```

يحدد أنواع الصور والألوان التي سيتأثر بها إعدادات تعديل اللون وتدرج الرمادي لـ [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).
## الحقول

| حقل | الوصف |
| --- | --- |
| [Default](#Default) | يتم تعديل جميع قيم اللون، بما في ذلك درجات الرمادي، باستخدام نفس مصفوفة تعديل اللون. |
| [SkipGrays](#SkipGrays) | يتم تعديل جميع الألوان، لكن درجات الرمادي لا يتم تعديلها. |
| [AltGrays](#AltGrays) | يتم تعديل درجات الرمادي فقط. |
### Default {#Default}
```
public static final int Default
```


يتم تعديل جميع قيم اللون، بما في ذلك درجات الرمادي، باستخدام نفس مصفوفة تعديل اللون.

### SkipGrays {#SkipGrays}
```
public static final int SkipGrays
```


يتم تعديل جميع الألوان، لكن درجات الرمادي لا يتم تعديلها. درجة الرمادي هي أي لون له نفس القيمة لمكوّناته الحمراء والخضراء والزرقاء.

### AltGrays {#AltGrays}
```
public static final int AltGrays
```


يتم تعديل درجات الرمادي فقط.

