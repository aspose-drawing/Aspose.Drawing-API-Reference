---
title: GetThumbnailImage
second_title: Aspose.Drawing لمرجع NET API
description: إرجاع صورة مصغرة لهذاImage .
type: docs
weight: 230
url: /ar/net/system.drawing/image/getthumbnailimage/
---
## Image.GetThumbnailImage method

إرجاع صورة مصغرة لهذاImage .

```csharp
public Image GetThumbnailImage(int thumbWidth, int thumbHeight, GetThumbnailImageAbort callback, 
    IntPtr callbackData)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| thumbWidth | Int32 | عرض الصورة المصغرة المطلوبة بالبكسل. |
| thumbHeight | Int32 | ارتفاع الصورة المصغرة المطلوبة بالبكسل. |
| callback | GetThumbnailImageAbort | أ[`GetThumbnailImageAbort`](../../image.getthumbnailimageabort) مندوب. ملاحظة يجب عليك إنشاء مفوض وتمرير مرجع إلى المفوض باسم*callback* المعلمة ، لكن المفوض غير مستخدم. |
| callbackData | IntPtr | لا بد وأنZero . |

### قيمة الإرجاع

أنImage التي تمثل الصورة المصغرة.

### أنظر أيضا

* delegate [GetThumbnailImageAbort](../../image.getthumbnailimageabort)
* class [Image](../../image)
* مساحة الاسم [System.Drawing](../../image)
* المجسم [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
