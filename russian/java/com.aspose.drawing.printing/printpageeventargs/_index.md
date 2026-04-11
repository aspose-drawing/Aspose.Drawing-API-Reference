---
title: PrintPageEventArgs
second_title: Справочник API Aspose.Drawing для Java
description: Предоставляет данные для события EPrintDocument.PrintPage.
type: docs
weight: 13
url: /ru/java/com.aspose.drawing.printing/printpageeventargs/
---
**Inheritance:**
java.lang.Object
```
public class PrintPageEventArgs
```

Предоставляет данные для события `E:PrintDocument.PrintPage`.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PrintPageEventArgs()](#PrintPageEventArgs--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getGraphics()](#getGraphics--) | Получает `Graphics`([.getGraphics](../../null/\#getGraphics)), используемый для отрисовки страницы. |
| [hasMorePages()](#hasMorePages--) | Получает значение, указывающее, следует ли печатать дополнительную страницу. |
| [setMorePages(boolean value)](#setMorePages-boolean-) | Устанавливает значение, указывающее, следует ли печатать дополнительную страницу. |
| [getPageSettings()](#getPageSettings--) | Получает параметры страницы для текущей страницы. |
### PrintPageEventArgs() {#PrintPageEventArgs--}
```
public PrintPageEventArgs()
```


### getGraphics() {#getGraphics--}
```
public final Graphics getGraphics()
```


Получает `Graphics`([.getGraphics](../../null/\#getGraphics)), используемый для отрисовки страницы.

**Returns:**
[Graphics](../../com.aspose.drawing/graphics) - The `Graphics`([.getGraphics](../../null/\#getGraphics)) used to paint the page.
### hasMorePages() {#hasMorePages--}
```
public final boolean hasMorePages()
```


Получает значение, указывающее, следует ли печатать дополнительную страницу.

**Returns:**
boolean — `true`, если следует печатать дополнительную страницу; иначе — false. По умолчанию `false`.
### setMorePages(boolean value) {#setMorePages-boolean-}
```
public final void setMorePages(boolean value)
```


Устанавливает значение, указывающее, следует ли печатать дополнительную страницу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, следует ли печатать дополнительную страницу. |

### getPageSettings() {#getPageSettings--}
```
public final PageSettings getPageSettings()
```


Получает параметры страницы для текущей страницы.

**Returns:**
[PageSettings](../../com.aspose.drawing.printing/pagesettings) - The page settings for the current page.
