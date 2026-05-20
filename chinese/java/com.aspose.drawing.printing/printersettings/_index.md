---
title: PrinterSettings
second_title: Aspose.Drawing for Java API 参考
description: 指定有关文档打印方式的信息，包括在 Windows Forms 应用程序中打印时使用的打印机。
type: docs
weight: 16
url: /zh/java/com.aspose.drawing.printing/printersettings/
---
**Inheritance:**
java.lang.Object
```
public class PrinterSettings
```

指定有关文档打印方式的信息，包括打印它的打印机，以及从 Windows Forms 应用程序打印时的情况。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PrinterSettings()](#PrinterSettings--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFromPage()](#getFromPage--) | 获取要打印的第一页的页码。 |
| [getPrintRange()](#getPrintRange--) | 获取用户指定要打印的页码。 |
| [getToPage()](#getToPage--) | 获取要打印的最后一页的页码。 |
| [getPrinterName()](#getPrinterName--) | 获取要使用的打印机名称。 |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | 设置要使用的打印机名称。 |
### PrinterSettings() {#PrinterSettings--}
```
public PrinterSettings()
```


### getFromPage() {#getFromPage--}
```
public static int getFromPage()
```


获取要打印的第一页的页码。

**Returns:**
int - 要打印的第一页的页码。
### getPrintRange() {#getPrintRange--}
```
public static int getPrintRange()
```


获取用户指定要打印的页码。

**Returns:**
int - `PrintRange`([.getPrintRange](../../null/\#getPrintRange)) 的一个取值。
### getToPage() {#getToPage--}
```
public static int getToPage()
```


获取要打印的最后一页的页码。

**Returns:**
int - 要打印的最后一页的页码。
### getPrinterName() {#getPrinterName--}
```
public final String getPrinterName()
```


获取要使用的打印机名称。

**Returns:**
java.lang.String - 要使用的打印机名称。
### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public final void setPrinterName(String value)
```


设置要使用的打印机名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 要使用的打印机名称。 |

