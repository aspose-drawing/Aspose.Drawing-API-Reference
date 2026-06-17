---
title: PrinterSettings
second_title: Aspose.Drawing för Java API‑referens
description: Anger information om hur ett dokument skrivs ut, inklusive skrivaren som skriver ut det när utskrift sker från en Windows Forms-applikation.
type: docs
weight: 16
url: /sv/java/com.aspose.drawing.printing/printersettings/
---
**Inheritance:**
java.lang.Object
```
public class PrinterSettings
```

Anger information om hur ett dokument skrivs ut, inklusive skrivaren som skriver ut det, när utskrift sker från en Windows Forms-applikation.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PrinterSettings()](#PrinterSettings--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFromPage()](#getFromPage--) | Hämtar sidnumret för den första sidan som ska skrivas ut. |
| [getPrintRange()](#getPrintRange--) | Hämtar sidnumren som användaren har angett för utskrift. |
| [getToPage()](#getToPage--) | Hämtar numret på den sista sidan som ska skrivas ut. |
| [getPrinterName()](#getPrinterName--) | Hämtar namnet på den skrivare som ska användas. |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | Ställer in namnet på den skrivare som ska användas. |
### PrinterSettings() {#PrinterSettings--}
```
public PrinterSettings()
```


### getFromPage() {#getFromPage--}
```
public static int getFromPage()
```


Hämtar sidnumret för den första sidan som ska skrivas ut.

**Returns:**
int - Sidnumret för den första sidan som ska skrivas ut.
### getPrintRange() {#getPrintRange--}
```
public static int getPrintRange()
```


Hämtar sidnumren som användaren har angett för utskrift.

**Returns:**
int - Ett av värdena i `PrintRange`([.getPrintRange](../../null/\#getPrintRange)).
### getToPage() {#getToPage--}
```
public static int getToPage()
```


Hämtar numret på den sista sidan som ska skrivas ut.

**Returns:**
int - Numret på den sista sidan som ska skrivas ut.
### getPrinterName() {#getPrinterName--}
```
public final String getPrinterName()
```


Hämtar namnet på den skrivare som ska användas.

**Returns:**
java.lang.String - Namnet på den skrivare som ska användas.
### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public final void setPrinterName(String value)
```


Ställer in namnet på den skrivare som ska användas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String | namnet på den skrivare som ska användas. |

