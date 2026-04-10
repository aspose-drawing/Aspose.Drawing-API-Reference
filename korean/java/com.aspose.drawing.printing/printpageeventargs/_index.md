---
title: PrintPageEventArgs
second_title: Aspose.Drawing for Java API 참조
description: EPrintDocument.PrintPage 이벤트에 대한 데이터를 제공합니다.
type: docs
weight: 13
url: /ko/java/com.aspose.drawing.printing/printpageeventargs/
---
**Inheritance:**
java.lang.Object
```
public class PrintPageEventArgs
```

`E:PrintDocument.PrintPage` 이벤트에 대한 데이터를 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PrintPageEventArgs()](#PrintPageEventArgs--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getGraphics()](#getGraphics--) | `Graphics`([.getGraphics](../../null/\#getGraphics))를 사용하여 페이지를 그리는 데 가져옵니다. |
| [hasMorePages()](#hasMorePages--) | 추가 페이지를 인쇄해야 하는지 여부를 나타내는 값을 가져옵니다. |
| [setMorePages(boolean value)](#setMorePages-boolean-) | 추가 페이지를 인쇄해야 하는지 여부를 나타내는 값을 설정합니다. |
| [getPageSettings()](#getPageSettings--) | 현재 페이지에 대한 페이지 설정을 가져옵니다. |
### PrintPageEventArgs() {#PrintPageEventArgs--}
```
public PrintPageEventArgs()
```


### getGraphics() {#getGraphics--}
```
public final Graphics getGraphics()
```


`Graphics`([.getGraphics](../../null/\#getGraphics))를 사용하여 페이지를 그리는 데 가져옵니다.

**Returns:**
[Graphics](../../com.aspose.drawing/graphics) - The `Graphics`([.getGraphics](../../null/\#getGraphics)) used to paint the page.
### hasMorePages() {#hasMorePages--}
```
public final boolean hasMorePages()
```


추가 페이지를 인쇄해야 하는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 추가 페이지를 인쇄해야 하면 `true`; 그렇지 않으면 false. 기본값은 `false`입니다.
### setMorePages(boolean value) {#setMorePages-boolean-}
```
public final void setMorePages(boolean value)
```


추가 페이지를 인쇄해야 하는지 여부를 나타내는 값을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | 추가 페이지를 인쇄해야 하는지 여부를 나타내는 값. |

### getPageSettings() {#getPageSettings--}
```
public final PageSettings getPageSettings()
```


현재 페이지에 대한 페이지 설정을 가져옵니다.

**Returns:**
[PageSettings](../../com.aspose.drawing.printing/pagesettings) - The page settings for the current page.
