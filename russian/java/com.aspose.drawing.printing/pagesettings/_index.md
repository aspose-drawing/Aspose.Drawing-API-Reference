---
title: PageSettings
second_title: Справочник API Aspose.Drawing для Java
description: Указывает параметры, применяемые к отдельной печатной странице.
type: docs
weight: 10
url: /ru/java/com.aspose.drawing.printing/pagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PageSettings
```

Указывает параметры, применяемые к отдельной печатной странице.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PageSettings()](#PageSettings--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Возвращает размер страницы с учётом ориентации, указанной в свойстве [PageSettings](../../com.aspose.drawing.printing/pagesettings). |
| [getHardMarginX()](#getHardMarginX--) | Получает координату x, в сотых дюйма, жёсткого поля слева от страницы. |
| [getHardMarginY()](#getHardMarginY--) | Получает координату y, в сотых дюйма, жёсткого поля в верхней части страницы. |
| [getPrinterResolution()](#getPrinterResolution--) | Получает разрешение принтера для страницы. |
### PageSettings() {#PageSettings--}
```
public PageSettings()
```


### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Возвращает размер страницы с учётом ориентации, указанной в свойстве [PageSettings](../../com.aspose.drawing.printing/pagesettings).

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the length and width, in hundredths of an inch, of the page.
### getHardMarginX() {#getHardMarginX--}
```
public final float getHardMarginX()
```


Получает координату x, в сотых дюйма, жёсткого поля слева от страницы.

**Returns:**
float - координата x, в сотых дюйма, левого жёсткого поля.
### getHardMarginY() {#getHardMarginY--}
```
public final float getHardMarginY()
```


Получает координату y, в сотых дюйма, жёсткого поля в верхней части страницы.

**Returns:**
float - координата y, в сотых дюйма, жёсткого поля в верхней части страницы.
### getPrinterResolution() {#getPrinterResolution--}
```
public final PrinterResolution getPrinterResolution()
```


Получает разрешение принтера для страницы.

**Returns:**
[PrinterResolution](../../com.aspose.drawing.printing/printerresolution) - A `PrinterResolution`([.getPrinterResolution](../../null/\#getPrinterResolution)) that specifies the printer resolution for the page. The default is the printer's default resolution.
