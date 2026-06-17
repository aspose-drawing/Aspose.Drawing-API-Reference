---
title: PrinterSettings
second_title: Riferimento API di Aspose.Drawing per Java
description: Specifica le informazioni su come viene stampato un documento, incluso la stampante che lo stampa quando si stampa da un'applicazione Windows Forms.
type: docs
weight: 16
url: /it/java/com.aspose.drawing.printing/printersettings/
---
**Inheritance:**
java.lang.Object
```
public class PrinterSettings
```

Specifica le informazioni su come viene stampato un documento, inclusa la stampante che lo stampa, quando si stampa da un'applicazione Windows Forms.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PrinterSettings()](#PrinterSettings--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFromPage()](#getFromPage--) | Ottiene il numero di pagina della prima pagina da stampare. |
| [getPrintRange()](#getPrintRange--) | Ottiene i numeri di pagina che l'utente ha specificato per la stampa. |
| [getToPage()](#getToPage--) | Ottiene il numero dell'ultima pagina da stampare. |
| [getPrinterName()](#getPrinterName--) | Ottiene il nome della stampante da utilizzare. |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | Imposta il nome della stampante da utilizzare. |
### PrinterSettings() {#PrinterSettings--}
```
public PrinterSettings()
```


### getFromPage() {#getFromPage--}
```
public static int getFromPage()
```


Ottiene il numero di pagina della prima pagina da stampare.

**Returns:**
int - Il numero di pagina della prima pagina da stampare.
### getPrintRange() {#getPrintRange--}
```
public static int getPrintRange()
```


Ottiene i numeri di pagina che l'utente ha specificato per la stampa.

**Returns:**
int - Uno dei valori `PrintRange`([.getPrintRange](../../null/\#getPrintRange)).
### getToPage() {#getToPage--}
```
public static int getToPage()
```


Ottiene il numero dell'ultima pagina da stampare.

**Returns:**
int - Il numero dell'ultima pagina da stampare.
### getPrinterName() {#getPrinterName--}
```
public final String getPrinterName()
```


Ottiene il nome della stampante da utilizzare.

**Returns:**
java.lang.String - Il nome della stampante da utilizzare.
### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public final void setPrinterName(String value)
```


Imposta il nome della stampante da utilizzare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String | il nome della stampante da utilizzare. |

