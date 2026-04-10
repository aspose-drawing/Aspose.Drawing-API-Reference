---
title: PrintPageEventArgs
second_title: Aspose.Drawing for Java API 参考
description: 提供 EPrintDocument.PrintPage 事件的数据。
type: docs
weight: 13
url: /zh/java/com.aspose.drawing.printing/printpageeventargs/
---
**Inheritance:**
java.lang.Object
```
public class PrintPageEventArgs
```

提供 `E:PrintDocument.PrintPage` 事件的数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PrintPageEventArgs()](#PrintPageEventArgs--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getGraphics()](#getGraphics--) | 获取用于绘制页面的 `Graphics`([.getGraphics](../../null/\#getGraphics))。 |
| [hasMorePages()](#hasMorePages--) | 获取指示是否应打印附加页面的值。 |
| [setMorePages(boolean value)](#setMorePages-boolean-) | 设置指示是否应打印附加页面的值。 |
| [getPageSettings()](#getPageSettings--) | 获取当前页面的页面设置。 |
### PrintPageEventArgs() {#PrintPageEventArgs--}
```
public PrintPageEventArgs()
```


### getGraphics() {#getGraphics--}
```
public final Graphics getGraphics()
```


获取用于绘制页面的 `Graphics`([.getGraphics](../../null/\#getGraphics))。

**Returns:**
[Graphics](../../com.aspose.drawing/graphics) - The `Graphics`([.getGraphics](../../null/\#getGraphics)) used to paint the page.
### hasMorePages() {#hasMorePages--}
```
public final boolean hasMorePages()
```


获取指示是否应打印附加页面的值。

**Returns:**
布尔型 - 如果应打印附加页面则为 `true`；否则为 false。默认值为 `false`。
### setMorePages(boolean value) {#setMorePages-boolean-}
```
public final void setMorePages(boolean value)
```


设置指示是否应打印附加页面的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 布尔型 | 指示是否应打印附加页面的值。 |

### getPageSettings() {#getPageSettings--}
```
public final PageSettings getPageSettings()
```


获取当前页面的页面设置。

**Returns:**
[PageSettings](../../com.aspose.drawing.printing/pagesettings) - The page settings for the current page.
