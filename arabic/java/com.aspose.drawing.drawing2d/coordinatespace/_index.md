---
title: CoordinateSpace
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحدد النظام المستخدم عند تقييم الإحداثيات.
type: docs
weight: 16
url: /ar/java/com.aspose.drawing.drawing2d/coordinatespace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CoordinateSpace extends System.Enum
```

يحدد النظام المستخدم عند تقييم الإحداثيات.
## الحقول

| حقل | الوصف |
| --- | --- |
| [World](#World) | يحدد أن الإحداثيات في سياق الإحداثيات العالمية. |
| [Page](#Page) | يحدد أن الإحداثيات في سياق إحداثيات الصفحة. |
| [Device](#Device) | يحدد أن الإحداثيات في سياق إحداثيات الجهاز. |
### World {#World}
```
public static final int World
```


يحدد أن الإحداثيات في سياق الإحداثيات العالمية. تُستخدم الإحداثيات العالمية في بيئة غير مادية، مثل بيئة النمذجة.

### Page {#Page}
```
public static final int Page
```


يحدد أن الإحداثيات في سياق إحداثيات الصفحة. وحداتها تُعرّف بواسطة الخاصية Graphics.PageUnit، ويجب أن تكون أحد عناصر تعداد GraphicsUnit.

### Device {#Device}
```
public static final int Device
```


يحدد أن الإحداثيات في سياق إحداثيات الجهاز. على شاشة الحاسوب تُقاس إحداثيات الجهاز عادةً بالبكسل.

