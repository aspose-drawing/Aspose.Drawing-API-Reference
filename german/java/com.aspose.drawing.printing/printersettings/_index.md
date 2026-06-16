---
title: PrinterSettings
second_title: Aspose.Drawing für Java API-Referenz
description: Gibt Informationen darüber an, wie ein Dokument gedruckt wird, einschließlich des Druckers, der es beim Drucken aus einer Windows Forms-Anwendung ausgibt.
type: docs
weight: 16
url: /de/java/com.aspose.drawing.printing/printersettings/
---
**Inheritance:**
java.lang.Object
```
public class PrinterSettings
```

Gibt Informationen darüber an, wie ein Dokument gedruckt wird, einschließlich des Druckers, der es druckt, beim Drucken aus einer Windows Forms-Anwendung.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PrinterSettings()](#PrinterSettings--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFromPage()](#getFromPage--) | Liest die Seitenzahl der ersten zu druckenden Seite. |
| [getPrintRange()](#getPrintRange--) | Liest die Seitenzahlen, die der Benutzer zum Drucken angegeben hat. |
| [getToPage()](#getToPage--) | Liest die Nummer der letzten zu druckenden Seite. |
| [getPrinterName()](#getPrinterName--) | Liest den Namen des zu verwendenden Druckers. |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | Setzt den Namen des zu verwendenden Druckers. |
### PrinterSettings() {#PrinterSettings--}
```
public PrinterSettings()
```


### getFromPage() {#getFromPage--}
```
public static int getFromPage()
```


Liest die Seitenzahl der ersten zu druckenden Seite.

**Returns:**
int - Die Seitenzahl der ersten zu druckenden Seite.
### getPrintRange() {#getPrintRange--}
```
public static int getPrintRange()
```


Liest die Seitenzahlen, die der Benutzer zum Drucken angegeben hat.

**Returns:**
int - Einer der Werte von `PrintRange`([.getPrintRange](../../null/\#getPrintRange)).
### getToPage() {#getToPage--}
```
public static int getToPage()
```


Liest die Nummer der letzten zu druckenden Seite.

**Returns:**
int - Die Nummer der letzten zu druckenden Seite.
### getPrinterName() {#getPrinterName--}
```
public final String getPrinterName()
```


Liest den Namen des zu verwendenden Druckers.

**Returns:**
java.lang.String - Der Name des zu verwendenden Druckers.
### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public final void setPrinterName(String value)
```


Setzt den Namen des zu verwendenden Druckers.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String | der Name des zu verwendenden Druckers. |

