---
title: PrinterSettings
second_title: Справочник API Aspose.Drawing для Java
description: Указывает информацию о том, как документ печатается, включая принтер, который используется при печати из приложения Windows Forms.
type: docs
weight: 16
url: /ru/java/com.aspose.drawing.printing/printersettings/
---
**Inheritance:**
java.lang.Object
```
public class PrinterSettings
```

Указывает информацию о том, как печатается документ, включая принтер, который его печатает, при печати из приложения Windows Forms.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PrinterSettings()](#PrinterSettings--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getFromPage()](#getFromPage--) | Получает номер первой страницы для печати. |
| [getPrintRange()](#getPrintRange--) | Получает номера страниц, указанные пользователем для печати. |
| [getToPage()](#getToPage--) | Получает номер последней страницы для печати. |
| [getPrinterName()](#getPrinterName--) | Получает имя принтера, который будет использоваться. |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | Устанавливает имя принтера, который будет использоваться. |
### PrinterSettings() {#PrinterSettings--}
```
public PrinterSettings()
```


### getFromPage() {#getFromPage--}
```
public static int getFromPage()
```


Получает номер первой страницы для печати.

**Returns:**
int — номер первой страницы для печати.
### getPrintRange() {#getPrintRange--}
```
public static int getPrintRange()
```


Получает номера страниц, указанные пользователем для печати.

**Returns:**
int — одно из значений `PrintRange`([.getPrintRange](../../null/\#getPrintRange)).
### getToPage() {#getToPage--}
```
public static int getToPage()
```


Получает номер последней страницы для печати.

**Returns:**
int — номер последней страницы для печати.
### getPrinterName() {#getPrinterName--}
```
public final String getPrinterName()
```


Получает имя принтера, который будет использоваться.

**Returns:**
java.lang.String — имя принтера, который будет использоваться.
### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public final void setPrinterName(String value)
```


Устанавливает имя принтера, который будет использоваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | имя принтера, который будет использоваться. |

