---
title: ColorTranslator
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يترجم الألوان من وإلى هياكل GDI.
type: docs
weight: 16
url: /ar/java/com.aspose.drawing/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

يترجم الألوان من وإلى هياكل GDI+ [Color](../../com.aspose.drawing/color). لا يمكن وراثة هذه الفئة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ColorTranslator()](#ColorTranslator--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | يترجم تمثيل لون HTML إلى هيكل GDI+ [Color](../../com.aspose.drawing/color). |
| [toHtml(Color c)](#toHtml-com.aspose.drawing.Color-) | يترجم هيكل [Color](../../com.aspose.drawing/color) المحدد إلى تمثيل لون سلسلة HTML. |
| [fromWin32(int win32Color)](#fromWin32-int-) | يترجم قيمة لون Windows إلى هيكل GDI+ [Color](../../com.aspose.drawing/color). |
| [fromOle(int oleColor)](#fromOle-int-) | يترجم قيمة لون OLE إلى هيكل GDI+ [Color](../../com.aspose.drawing/color). |
| [toWin32(Color c)](#toWin32-com.aspose.drawing.Color-) | يحوّل هيكل [Color](../../com.aspose.drawing/color) إلى تمثيل Win32 للون. |
| [toOle(Color c)](#toOle-com.aspose.drawing.Color-) | يحوّل هيكل [Color](../../com.aspose.drawing/color) إلى تمثيل OLE للون. |
### ColorTranslator() {#ColorTranslator--}
```
public ColorTranslator()
```


### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


يترجم تمثيل لون HTML إلى هيكل GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| htmlColor | java.lang.String | التمثيل النصي للون Html المراد ترجمته. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated HTML color or `Empty` if htmlColor is null.
### toHtml(Color c) {#toHtml-com.aspose.drawing.Color-}
```
public static String toHtml(Color c)
```


يترجم هيكل [Color](../../com.aspose.drawing/color) المحدد إلى تمثيل لون سلسلة HTML.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | بنية [Color](../../com.aspose.drawing/color) للترجمة. |

**Returns:**
java.lang.String - السلسلة التي تمثل لون HTML.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


يترجم قيمة لون Windows إلى هيكل GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| win32Color | int | لون Windows للترجمة. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated Windows color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


يترجم قيمة لون OLE إلى هيكل GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| oleColor | int | لون OLE للترجمة. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated OLE color.
### toWin32(Color c) {#toWin32-com.aspose.drawing.Color-}
```
public static int toWin32(Color c)
```


يحوّل هيكل [Color](../../com.aspose.drawing/color) إلى تمثيل Win32 للون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | بنية [Color](../../com.aspose.drawing/color) للتحويل. |

**Returns:**
int - القيمة التي تمثل تنسيق Win32 للون.
### toOle(Color c) {#toOle-com.aspose.drawing.Color-}
```
public static int toOle(Color c)
```


يحوّل هيكل [Color](../../com.aspose.drawing/color) إلى تمثيل OLE للون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | بنية [Color](../../com.aspose.drawing/color) للتحويل. |

**Returns:**
int - القيمة التي تمثل تنسيق OLE للون.
