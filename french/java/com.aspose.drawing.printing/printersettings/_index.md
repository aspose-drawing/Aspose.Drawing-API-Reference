---
title: PrinterSettings
second_title: Référence de l'API Aspose.Drawing pour Java
description: Spécifie les informations sur la façon dont un document est imprimé, y compris l'imprimante qui l'imprime lors de l'impression depuis une application Windows Forms.
type: docs
weight: 16
url: /fr/java/com.aspose.drawing.printing/printersettings/
---
**Inheritance:**
java.lang.Object
```
public class PrinterSettings
```

Spécifie les informations sur la façon dont un document est imprimé, y compris l'imprimante qui l'imprime, lors de l'impression depuis une application Windows Forms.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PrinterSettings()](#PrinterSettings--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFromPage()](#getFromPage--) | Obtient le numéro de page de la première page à imprimer. |
| [getPrintRange()](#getPrintRange--) | Obtient les numéros de page que l'utilisateur a spécifiés pour l'impression. |
| [getToPage()](#getToPage--) | Obtient le numéro de la dernière page à imprimer. |
| [getPrinterName()](#getPrinterName--) | Obtient le nom de l'imprimante à utiliser. |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | Définit le nom de l'imprimante à utiliser. |
### PrinterSettings() {#PrinterSettings--}
```
public PrinterSettings()
```


### getFromPage() {#getFromPage--}
```
public static int getFromPage()
```


Obtient le numéro de page de la première page à imprimer.

**Returns:**
int - Le numéro de page de la première page à imprimer.
### getPrintRange() {#getPrintRange--}
```
public static int getPrintRange()
```


Obtient les numéros de page que l'utilisateur a spécifiés pour l'impression.

**Returns:**
int - L'une des valeurs de `PrintRange`([.getPrintRange](../../null/\#getPrintRange)).
### getToPage() {#getToPage--}
```
public static int getToPage()
```


Obtient le numéro de la dernière page à imprimer.

**Returns:**
int - Le numéro de la dernière page à imprimer.
### getPrinterName() {#getPrinterName--}
```
public final String getPrinterName()
```


Obtient le nom de l'imprimante à utiliser.

**Returns:**
java.lang.String - Le nom de l'imprimante à utiliser.
### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public final void setPrinterName(String value)
```


Définit le nom de l'imprimante à utiliser.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String | le nom de l'imprimante à utiliser. |

