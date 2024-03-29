---
title: Clone
second_title: Aspose.Drawing لمرجع NET API
description: لإنشاء نسخة من هذا القسمBitmap المعرفة من قبلRectangle هيكل ومع المحددPixelFormat التعداد .
type: docs
weight: 100
url: /ar/net/system.drawing/bitmap/clone/
---
## Clone(Rectangle, PixelFormat) {#clone}

لإنشاء نسخة من هذا القسمBitmap المعرفة من قبلRectangle هيكل ومع المحددPixelFormat التعداد .

```csharp
public Bitmap Clone(Rectangle rect, PixelFormat format)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | Rectangle | يحدد الجزء من هذاBitmap لنسخ. الإحداثيات ذات صلة بهذاBitmap. |
| format | PixelFormat | يحدد الPixelFormat تعداد للوجهة Bitmap. |

### قيمة الإرجاع

الجديدBitmap التي تخلقها هذه الطريقة.

### أنظر أيضا

* struct [Rectangle](../../rectangle)
* enum [PixelFormat](../../../system.drawing.imaging/pixelformat)
* class [Bitmap](../../bitmap)
* مساحة الاسم [System.Drawing](../../bitmap)
* المجسم [Aspose.Drawing](../../../)

---

## Clone(RectangleF, PixelFormat) {#clone_1}

لإنشاء نسخة من هذا القسمBitmap المعرفة مع المحددPixelFormat التعداد .

```csharp
public Bitmap Clone(RectangleF rect, PixelFormat format)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | RectangleF | يحدد الجزء من هذاBitmap لنسخ. |
| format | PixelFormat | يحدد الPixelFormat تعداد للوجهةBitmap. |

### قيمة الإرجاع

الBitmap التي تخلقها هذه الطريقة.

### استثناءات

| استثناء | حالة |
| --- | --- |
| OutOfMemoryException | *rect* خارج حدود الصورة النقطية المصدر. |
| ArgumentException | ارتفاع أو عرض*rect* هو 0. |

### أنظر أيضا

* struct [RectangleF](../../rectanglef)
* enum [PixelFormat](../../../system.drawing.imaging/pixelformat)
* class [Bitmap](../../bitmap)
* مساحة الاسم [System.Drawing](../../bitmap)
* المجسم [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
