---
title: PrinterSettings
second_title: Referencia de la API de Aspose.Drawing para Java
description: Especifica información sobre cómo se imprime un documento, incluida la impresora que lo imprime al imprimir desde una aplicación Windows Forms.
type: docs
weight: 16
url: /es/java/com.aspose.drawing.printing/printersettings/
---
**Inheritance:**
java.lang.Object
```
public class PrinterSettings
```

Especifica información sobre cómo se imprime un documento, incluida la impresora que lo imprime, al imprimir desde una aplicación Windows Forms .
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PrinterSettings()](#PrinterSettings--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFromPage()](#getFromPage--) | Obtiene el número de página de la primera página a imprimir. |
| [getPrintRange()](#getPrintRange--) | Obtiene los números de página que el usuario ha especificado para imprimir. |
| [getToPage()](#getToPage--) | Obtiene el número de la última página a imprimir. |
| [getPrinterName()](#getPrinterName--) | Obtiene el nombre de la impresora a usar. |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | Establece el nombre de la impresora a usar. |
### PrinterSettings() {#PrinterSettings--}
```
public PrinterSettings()
```


### getFromPage() {#getFromPage--}
```
public static int getFromPage()
```


Obtiene el número de página de la primera página a imprimir.

**Returns:**
int - El número de página de la primera página a imprimir.
### getPrintRange() {#getPrintRange--}
```
public static int getPrintRange()
```


Obtiene los números de página que el usuario ha especificado para imprimir.

**Returns:**
int - Uno de los valores de `PrintRange`([.getPrintRange](../../null/\#getPrintRange)).
### getToPage() {#getToPage--}
```
public static int getToPage()
```


Obtiene el número de la última página a imprimir.

**Returns:**
int - El número de la última página a imprimir.
### getPrinterName() {#getPrinterName--}
```
public final String getPrinterName()
```


Obtiene el nombre de la impresora a usar.

**Returns:**
java.lang.String - El nombre de la impresora a usar.
### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public final void setPrinterName(String value)
```


Establece el nombre de la impresora a usar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String | el nombre de la impresora a usar. |

