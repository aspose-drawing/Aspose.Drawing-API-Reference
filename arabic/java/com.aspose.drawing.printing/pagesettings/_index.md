---
title: PageSettings
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحدد الإعدادات التي تُطبّق على صفحة مطبوعة واحدة.
type: docs
weight: 10
url: /ar/java/com.aspose.drawing.printing/pagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PageSettings
```

يحدد الإعدادات التي تُطبق على صفحة مطبوعة واحدة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PageSettings()](#PageSettings--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل على حجم الصفحة مع مراعاة اتجاه الصفحة المحدد بواسطة خاصية [PageSettings](../../com.aspose.drawing.printing/pagesettings). |
| [getHardMarginX()](#getHardMarginX--) | يحصل على الإحداثي X، بوحدات مئوية من البوصة، للهوامش الصلبة على الجانب الأيسر من الصفحة. |
| [getHardMarginY()](#getHardMarginY--) | يحصل على الإحداثي Y، بوحدات مئوية من البوصة، للهوامش الصلبة في أعلى الصفحة. |
| [getPrinterResolution()](#getPrinterResolution--) | يحصل على دقة الطابعة للصفحة. |
### PageSettings() {#PageSettings--}
```
public PageSettings()
```


### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


يحصل على حجم الصفحة مع مراعاة اتجاه الصفحة المحدد بواسطة خاصية [PageSettings](../../com.aspose.drawing.printing/pagesettings).

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the length and width, in hundredths of an inch, of the page.
### getHardMarginX() {#getHardMarginX--}
```
public final float getHardMarginX()
```


يحصل على الإحداثي X، بوحدات مئوية من البوصة، للهوامش الصلبة على الجانب الأيسر من الصفحة.

**Returns:**
float - الإحداثي X، بوحدات مئوية من البوصة، للهوامش الصلبة اليسرى.
### getHardMarginY() {#getHardMarginY--}
```
public final float getHardMarginY()
```


يحصل على الإحداثي Y، بوحدات مئوية من البوصة، للهوامش الصلبة في أعلى الصفحة.

**Returns:**
float - الإحداثي Y، بوحدات مئوية من البوصة، للهوامش الصلبة في أعلى الصفحة.
### getPrinterResolution() {#getPrinterResolution--}
```
public final PrinterResolution getPrinterResolution()
```


يحصل على دقة الطابعة للصفحة.

**Returns:**
[PrinterResolution](../../com.aspose.drawing.printing/printerresolution) - A `PrinterResolution`([.getPrinterResolution](../../null/\#getPrinterResolution)) that specifies the printer resolution for the page. The default is the printer's default resolution.
