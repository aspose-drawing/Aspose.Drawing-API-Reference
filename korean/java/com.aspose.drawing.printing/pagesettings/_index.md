---
title: PageSettings
second_title: Aspose.Drawing for Java API 참조
description: 단일 인쇄 페이지에 적용되는 설정을 지정합니다.
type: docs
weight: 10
url: /ko/java/com.aspose.drawing.printing/pagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PageSettings
```

단일 인쇄 페이지에 적용되는 설정을 지정합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PageSettings()](#PageSettings--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBounds()](#getBounds--) | [PageSettings](../../com.aspose.drawing.printing/pagesettings) 속성에 지정된 페이지 방향을 고려하여 페이지 크기를 가져옵니다. |
| [getHardMarginX()](#getHardMarginX--) | 페이지 왼쪽의 하드 여백에 대한 x좌표를 인치의 백분의 일 단위로 가져옵니다. |
| [getHardMarginY()](#getHardMarginY--) | 페이지 상단의 하드 여백에 대한 y좌표를 인치의 백분의 일 단위로 가져옵니다. |
| [getPrinterResolution()](#getPrinterResolution--) | 페이지에 대한 프린터 해상도를 가져옵니다. |
### PageSettings() {#PageSettings--}
```
public PageSettings()
```


### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


[PageSettings](../../com.aspose.drawing.printing/pagesettings) 속성에 지정된 페이지 방향을 고려하여 페이지 크기를 가져옵니다.

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the length and width, in hundredths of an inch, of the page.
### getHardMarginX() {#getHardMarginX--}
```
public final float getHardMarginX()
```


페이지 왼쪽의 하드 여백에 대한 x좌표를 인치의 백분의 일 단위로 가져옵니다.

**Returns:**
float - 왼쪽 하드 여백의 x좌표를 인치의 백분의 일 단위로 나타냅니다.
### getHardMarginY() {#getHardMarginY--}
```
public final float getHardMarginY()
```


페이지 상단의 하드 여백에 대한 y좌표를 인치의 백분의 일 단위로 가져옵니다.

**Returns:**
float - 페이지 상단 하드 여백의 y좌표를 인치의 백분의 일 단위로 나타냅니다.
### getPrinterResolution() {#getPrinterResolution--}
```
public final PrinterResolution getPrinterResolution()
```


페이지에 대한 프린터 해상도를 가져옵니다.

**Returns:**
[PrinterResolution](../../com.aspose.drawing.printing/printerresolution) - A `PrinterResolution`([.getPrinterResolution](../../null/\#getPrinterResolution)) that specifies the printer resolution for the page. The default is the printer's default resolution.
