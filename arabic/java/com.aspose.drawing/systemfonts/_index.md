---
title: SystemFonts
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحدد الخطوط المستخدمة لعرض النص في عناصر عرض Windows.
type: docs
weight: 51
url: /ar/java/com.aspose.drawing/systemfonts/
---
**Inheritance:**
java.lang.Object
```
public final class SystemFonts
```

يحدد الخطوط المستخدمة لعرض النص في عناصر عرض Windows.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCaptionFont()](#getCaptionFont--) | يحصل على [Font](../../com.aspose.drawing/font) يُستخدم لعرض النص في أشرطة عنوان النوافذ. |
| [getSmallCaptionFont()](#getSmallCaptionFont--) | يحصل على [Font](../../com.aspose.drawing/font) يُستخدم لعرض النص في أشرطة عنوان النوافذ الصغيرة، مثل نوافذ الأدوات. |
| [getMenuFont()](#getMenuFont--) | يحصل على [Font](../../com.aspose.drawing/font) يُستخدم للقوائم. |
| [getStatusFont()](#getStatusFont--) | يحصل على [Font](../../com.aspose.drawing/font) يُستخدم لعرض النص في شريط الحالة. |
| [getMessageBoxFont()](#getMessageBoxFont--) | يحصل على [Font](../../com.aspose.drawing/font) يُستخدم لمربعات الرسائل. |
| [getIconTitleFont()](#getIconTitleFont--) | يحصل على [Font](../../com.aspose.drawing/font) يُستخدم لعناوين الأيقونات. |
| [getDefaultFont()](#getDefaultFont--) | يحصل على الخط الافتراضي الذي يمكن للتطبيقات استخدامه في صناديق الحوار والنماذج. |
| [getDefaultImageFont()](#getDefaultImageFont--) | يحصل على الخط الافتراضي الذي يمكن للتطبيقات استخدامه في صناديق الحوار والنماذج. |
| [getDialogFont()](#getDialogFont--) | يحصل على خط يمكن للتطبيقات استخدامه في صناديق الحوار والنماذج. |
| [getFontByName(String systemFontName)](#getFontByName-java.lang.String-) | يعيد كائن خط يتطابق مع اسم الخط النظامي المحدد. |
### getCaptionFont() {#getCaptionFont--}
```
public static Font getCaptionFont()
```


يحصل على [Font](../../com.aspose.drawing/font) يُستخدم لعرض النص في أشرطة عنوان النوافذ.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of windows.
### getSmallCaptionFont() {#getSmallCaptionFont--}
```
public static Font getSmallCaptionFont()
```


يحصل على [Font](../../com.aspose.drawing/font) يُستخدم لعرض النص في أشرطة عنوان النوافذ الصغيرة، مثل نوافذ الأدوات.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of small windows, such as tool windows.
### getMenuFont() {#getMenuFont--}
```
public static Font getMenuFont()
```


يحصل على [Font](../../com.aspose.drawing/font) يُستخدم للقوائم.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for menus.
### getStatusFont() {#getStatusFont--}
```
public static Font getStatusFont()
```


يحصل على [Font](../../com.aspose.drawing/font) يُستخدم لعرض النص في شريط الحالة.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the status bar.
### getMessageBoxFont() {#getMessageBoxFont--}
```
public static Font getMessageBoxFont()
```


يحصل على [Font](../../com.aspose.drawing/font) يُستخدم لمربعات الرسائل.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for message boxes.
### getIconTitleFont() {#getIconTitleFont--}
```
public static Font getIconTitleFont()
```


يحصل على [Font](../../com.aspose.drawing/font) يُستخدم لعناوين الأيقونات.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for icon titles.
### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


يحصل على الخط الافتراضي الذي يمكن للتطبيقات استخدامه في صناديق الحوار والنماذج.

**Returns:**
[Font](../../com.aspose.drawing/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDefaultImageFont() {#getDefaultImageFont--}
```
public static Font getDefaultImageFont()
```


يحصل على الخط الافتراضي الذي يمكن للتطبيقات استخدامه في صناديق الحوار والنماذج.

**Returns:**
[Font](../../com.aspose.imaging/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDialogFont() {#getDialogFont--}
```
public static Font getDialogFont()
```


يحصل على خط يمكن للتطبيقات استخدامه في صناديق الحوار والنماذج.

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) that can be used for dialog boxes and forms, depending on the operating system and local culture setting of the system.
### getFontByName(String systemFontName) {#getFontByName-java.lang.String-}
```
public static Font getFontByName(String systemFontName)
```


يعيد كائن خط يتطابق مع اسم الخط النظامي المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| systemFontName | java.lang.String | اسم الخط النظامي الذي تحتاج إلى كائن خط له. |

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) if the specified name matches a value in [SystemFonts](../../com.aspose.drawing/systemfonts); otherwise, null.
