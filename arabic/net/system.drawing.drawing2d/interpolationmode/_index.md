---
title: InterpolationMode
second_title: Aspose.Drawing لمرجع NET API
description: يحدد تعداد وضع الاستيفاء الخوارزمية المستخدمة عند تحجيم الصور أو تدويرها.
type: docs
weight: 310
url: /ar/net/system.drawing.drawing2d/interpolationmode/
---
## InterpolationMode enumeration

يحدد تعداد وضع الاستيفاء الخوارزمية المستخدمة عند تحجيم الصور أو تدويرها.

```csharp
public enum InterpolationMode
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| Invalid | `-1` | ما يعادل العنصر غير صالح لتعداد QualityMode. |
| Default | `0` | تحديد الوضع الافتراضي . |
| Low | `1` | تحديد الاستيفاء منخفض الجودة . |
| High | `2` | تحديد الاستيفاء عالي الجودة . |
| Bilinear | `3` | تحديد الاستيفاء ثنائي الخطوط. لم يتم إجراء تصفية مسبقة. هذا الوضع غير مناسب لتقليص الصورة إلى أقل من 50 بالمائة من حجمها الأصلي. |
| Bicubic | `4` | تحديد الاستيفاء التكعيبي. لم يتم إجراء تصفية مسبقة. هذا الوضع غير مناسب لتقليص صورة أقل من 25 بالمائة من حجمها الأصلي. |
| NearestNeighbor | `5` | تحديد استيفاء أقرب الجيران . |
| HighQualityBilinear | `6` | تحديد جودة عالية واستيفاء ثنائي الخطوط. يتم إجراء التصفية المسبقة لضمان انكماش عالي الجودة. |
| HighQualityBicubic | `7` | تحديد جودة عالية ، واستكمال تكعيبي. يتم إجراء التصفية المسبقة لضمان تقليص عالي الجودة . ينتج عن هذا الوضع أعلى جودة للصور المحولة. |

### أنظر أيضا

* مساحة الاسم [System.Drawing.Drawing2D](../../system.drawing.drawing2d)
* المجسم [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
