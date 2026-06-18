---
title: EmfType
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحدد طبيعة السجلات التي تُوضع في ملف Enhanced Metafile EMF.
type: docs
weight: 18
url: /ar/java/com.aspose.drawing.imaging/emftype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfType extends System.Enum
```

يحدد طبيعة السجلات التي تُوضع في ملف Enhanced Metafile (EMF). تُستخدم هذه التعدادات بواسطة عدة مُنشئات في الفئة [Metafile](../../com.aspose.drawing.imaging/metafile).
## الحقول

| حقل | الوصف |
| --- | --- |
| [EmfOnly](#EmfOnly) | يحدد أن جميع السجلات في ملف التعريف هي سجلات EMF، والتي يمكن عرضها بواسطة GDI أو GDI+. |
| [EmfPlusOnly](#EmfPlusOnly) | يحدد أن جميع السجلات في ملف التعريف هي سجلات EMF+، والتي يمكن عرضها بواسطة GDI+ ولكن ليس بواسطة GDI. |
| [EmfPlusDual](#EmfPlusDual) | يحدد أن جميع سجلات EMF+ في ملف التعريف مرتبطة بسجل EMF بديل. |
### EmfOnly {#EmfOnly}
```
public static final int EmfOnly
```


يحدد أن جميع السجلات في ملف التعريف هي سجلات EMF، والتي يمكن عرضها بواسطة GDI أو GDI+.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


يحدد أن جميع السجلات في ملف التعريف هي سجلات EMF+، والتي يمكن عرضها بواسطة GDI+ ولكن ليس بواسطة GDI.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


يحدد أن جميع سجلات EMF+ في ملف التعريف مرتبطة بسجل EMF بديل. يمكن عرض ملفات التعريف من النوع `EmfType.EmfPlusDual` بواسطة GDI أو GDI+.

