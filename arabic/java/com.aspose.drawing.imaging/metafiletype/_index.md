---
title: MetafileType
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحدد أنواع ملفات الميتا.
type: docs
weight: 33
url: /ar/java/com.aspose.drawing.imaging/metafiletype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MetafileType extends System.Enum
```

يحدد أنواع ملفات الميتا.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Invalid](#Invalid) | يحدد تنسيق ميتافايل غير معترف به في GDI+. |
| [Wmf](#Wmf) | يحدد ملف WMF (Windows Metafile). |
| [WmfPlaceable](#WmfPlaceable) | يحدد ملف WMF (Windows Metafile) يحتوي على رأس ميتافايل قابل للنقل في مقدمتها. |
| [Emf](#Emf) | يحدد ملف Enhanced Metafile (EMF). |
| [EmfPlusOnly](#EmfPlusOnly) | يحدد ملف EMF+. |
| [EmfPlusDual](#EmfPlusDual) | يحدد ملف EMF+ Dual. |
### Invalid {#Invalid}
```
public static final int Invalid
```


يحدد تنسيق ميتافايل غير معترف به في GDI+.

### Wmf {#Wmf}
```
public static final int Wmf
```


يحدد ملف WMF (Windows Metafile). يحتوي هذا الملف فقط على سجلات GDI.

### WmfPlaceable {#WmfPlaceable}
```
public static final int WmfPlaceable
```


يحدد ملف WMF (Windows Metafile) يحتوي على رأس ميتافايل قابل للنقل في مقدمتها.

### Emf {#Emf}
```
public static final int Emf
```


يحدد ملف Enhanced Metafile (EMF). يحتوي هذا الملف فقط على سجلات GDI.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


يحدد ملف EMF+. يحتوي هذا الملف فقط على سجلات GDI+ ويجب عرضه باستخدام GDI+. قد يؤدي عرض السجلات باستخدام GDI إلى نتائج غير متوقعة.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


يحدد ملف EMF+ Dual. يحتوي هذا الملف على سجلات GDI+ إلى جانب سجلات GDI البديلة ويمكن عرضه باستخدام إما GDI أو GDI+. قد يؤدي عرض السجلات باستخدام GDI إلى تدهور بسيط في الجودة.

