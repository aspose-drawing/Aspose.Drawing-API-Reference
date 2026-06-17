---
title: PrinterSettings
second_title: Aspose.Drawing for Java API 참조
description: Windows Forms 애플리케이션에서 인쇄할 때 문서를 인쇄하는 방법 및 인쇄기를 포함한 정보를 지정합니다.
type: docs
weight: 16
url: /ko/java/com.aspose.drawing.printing/printersettings/
---
**Inheritance:**
java.lang.Object
```
public class PrinterSettings
```

Windows Forms 애플리케이션에서 인쇄할 때, 인쇄되는 프린터를 포함하여 문서가 인쇄되는 방식에 대한 정보를 지정합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PrinterSettings()](#PrinterSettings--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFromPage()](#getFromPage--) | 인쇄할 첫 번째 페이지 번호를 가져옵니다. |
| [getPrintRange()](#getPrintRange--) | 사용자가 인쇄하도록 지정한 페이지 번호를 가져옵니다. |
| [getToPage()](#getToPage--) | 인쇄할 마지막 페이지 번호를 가져옵니다. |
| [getPrinterName()](#getPrinterName--) | 사용할 프린터 이름을 가져옵니다. |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | 사용할 프린터 이름을 설정합니다. |
### PrinterSettings() {#PrinterSettings--}
```
public PrinterSettings()
```


### getFromPage() {#getFromPage--}
```
public static int getFromPage()
```


인쇄할 첫 번째 페이지 번호를 가져옵니다.

**Returns:**
int - 인쇄할 첫 번째 페이지 번호.
### getPrintRange() {#getPrintRange--}
```
public static int getPrintRange()
```


사용자가 인쇄하도록 지정한 페이지 번호를 가져옵니다.

**Returns:**
int - `PrintRange`([.getPrintRange](../../null/\#getPrintRange)) 값 중 하나.
### getToPage() {#getToPage--}
```
public static int getToPage()
```


인쇄할 마지막 페이지 번호를 가져옵니다.

**Returns:**
int - 인쇄할 마지막 페이지 번호.
### getPrinterName() {#getPrinterName--}
```
public final String getPrinterName()
```


사용할 프린터 이름을 가져옵니다.

**Returns:**
java.lang.String - 사용할 프린터 이름.
### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public final void setPrinterName(String value)
```


사용할 프린터 이름을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String | 사용할 프린터 이름. |

