---
title: PrinterSettings
second_title: Aspose.Drawing voor Java API-referentie
description: Specificeert informatie over hoe een document wordt afgedrukt, inclusief de printer die het afdrukt bij het afdrukken vanuit een Windows Forms‑applicatie.
type: docs
weight: 16
url: /nl/java/com.aspose.drawing.printing/printersettings/
---
**Inheritance:**
java.lang.Object
```
public class PrinterSettings
```

Specificeert informatie over hoe een document wordt afgedrukt, inclusief de printer die het afdrukt, bij het afdrukken vanuit een Windows Forms-toepassing.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PrinterSettings()](#PrinterSettings--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFromPage()](#getFromPage--) | Haalt het paginanummer op van de eerste pagina die moet worden afgedrukt. |
| [getPrintRange()](#getPrintRange--) | Haalt de paginanummers op die de gebruiker heeft opgegeven om af te drukken. |
| [getToPage()](#getToPage--) | Haalt het nummer op van de laatste pagina die moet worden afgedrukt. |
| [getPrinterName()](#getPrinterName--) | Haalt de naam op van de te gebruiken printer. |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | Stelt de naam in van de te gebruiken printer. |
### PrinterSettings() {#PrinterSettings--}
```
public PrinterSettings()
```


### getFromPage() {#getFromPage--}
```
public static int getFromPage()
```


Haalt het paginanummer op van de eerste pagina die moet worden afgedrukt.

**Returns:**
int - Het paginanummer van de eerste pagina die moet worden afgedrukt.
### getPrintRange() {#getPrintRange--}
```
public static int getPrintRange()
```


Haalt de paginanummers op die de gebruiker heeft opgegeven om af te drukken.

**Returns:**
int - Een van de `PrintRange`([.getPrintRange](../../null/\#getPrintRange)) waarden.
### getToPage() {#getToPage--}
```
public static int getToPage()
```


Haalt het nummer op van de laatste pagina die moet worden afgedrukt.

**Returns:**
int - Het nummer van de laatste pagina die moet worden afgedrukt.
### getPrinterName() {#getPrinterName--}
```
public final String getPrinterName()
```


Haalt de naam op van de te gebruiken printer.

**Returns:**
java.lang.String - De naam van de te gebruiken printer.
### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public final void setPrinterName(String value)
```


Stelt de naam in van de te gebruiken printer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String | de naam van de te gebruiken printer. |

