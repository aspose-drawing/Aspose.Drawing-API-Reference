---
title: 页面设置
second_title: Aspose.Drawing for Java API 参考
description: 指定适用于单个打印页面的设置。
type: docs
weight: 10
url: /zh/java/com.aspose.drawing.printing/pagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PageSettings
```

指定适用于单个打印页的设置。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PageSettings()](#PageSettings--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取页面大小，考虑由 [PageSettings](../../com.aspose.drawing.printing/pagesettings) 属性指定的页面方向。 |
| [getHardMarginX()](#getHardMarginX--) | 获取页面左侧硬边距的 x 坐标（单位为百分之一英寸）。 |
| [getHardMarginY()](#getHardMarginY--) | 获取页面顶部硬边距的 y 坐标（单位为百分之一英寸）。 |
| [getPrinterResolution()](#getPrinterResolution--) | 获取页面的打印机分辨率。 |
### PageSettings() {#PageSettings--}
```
public PageSettings()
```


### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


获取页面大小，考虑由 [PageSettings](../../com.aspose.drawing.printing/pagesettings) 属性指定的页面方向。

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the length and width, in hundredths of an inch, of the page.
### getHardMarginX() {#getHardMarginX--}
```
public final float getHardMarginX()
```


获取页面左侧硬边距的 x 坐标（单位为百分之一英寸）。

**Returns:**
float - 左侧硬边距的 x 坐标（单位为百分之一英寸）。
### getHardMarginY() {#getHardMarginY--}
```
public final float getHardMarginY()
```


获取页面顶部硬边距的 y 坐标（单位为百分之一英寸）。

**Returns:**
float - 页面顶部硬边距的 y 坐标（单位为百分之一英寸）。
### getPrinterResolution() {#getPrinterResolution--}
```
public final PrinterResolution getPrinterResolution()
```


获取页面的打印机分辨率。

**Returns:**
[PrinterResolution](../../com.aspose.drawing.printing/printerresolution) - A `PrinterResolution`([.getPrinterResolution](../../null/\#getPrinterResolution)) that specifies the printer resolution for the page. The default is the printer's default resolution.
