---
title: PrinterSettings
second_title: Αναφορά API του Aspose.Drawing for Java
description: Καθορίζει πληροφορίες σχετικά με το πώς εκτυπώνεται ένα έγγραφο, συμπεριλαμβανομένου του εκτυπωτή που το εκτυπώνει όταν γίνεται εκτύπωση από μια εφαρμογή Windows Forms.
type: docs
weight: 16
url: /el/java/com.aspose.drawing.printing/printersettings/
---
**Inheritance:**
java.lang.Object
```
public class PrinterSettings
```

Καθορίζει πληροφορίες σχετικά με το πώς εκτυπώνεται ένα έγγραφο, συμπεριλαμβανομένου του εκτυπωτή που το εκτυπώνει, όταν γίνεται εκτύπωση από μια εφαρμογή Windows Forms.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PrinterSettings()](#PrinterSettings--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFromPage()](#getFromPage--) | Λαμβάνει τον αριθμό σελίδας της πρώτης σελίδας προς εκτύπωση. |
| [getPrintRange()](#getPrintRange--) | Λαμβάνει τους αριθμούς σελίδων που έχει καθορίσει ο χρήστης για εκτύπωση. |
| [getToPage()](#getToPage--) | Λαμβάνει τον αριθμό της τελευταίας σελίδας προς εκτύπωση. |
| [getPrinterName()](#getPrinterName--) | Λαμβάνει το όνομα του εκτυπωτή που θα χρησιμοποιηθεί. |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | Ορίζει το όνομα του εκτυπωτή που θα χρησιμοποιηθεί. |
### PrinterSettings() {#PrinterSettings--}
```
public PrinterSettings()
```


### getFromPage() {#getFromPage--}
```
public static int getFromPage()
```


Λαμβάνει τον αριθμό σελίδας της πρώτης σελίδας προς εκτύπωση.

**Returns:**
int - Ο αριθμός σελίδας της πρώτης σελίδας προς εκτύπωση.
### getPrintRange() {#getPrintRange--}
```
public static int getPrintRange()
```


Λαμβάνει τους αριθμούς σελίδων που έχει καθορίσει ο χρήστης για εκτύπωση.

**Returns:**
int - Μία από τις τιμές του `PrintRange`([.getPrintRange](../../null/\#getPrintRange)).
### getToPage() {#getToPage--}
```
public static int getToPage()
```


Λαμβάνει τον αριθμό της τελευταίας σελίδας προς εκτύπωση.

**Returns:**
int - Ο αριθμός της τελευταίας σελίδας προς εκτύπωση.
### getPrinterName() {#getPrinterName--}
```
public final String getPrinterName()
```


Λαμβάνει το όνομα του εκτυπωτή που θα χρησιμοποιηθεί.

**Returns:**
java.lang.String - Το όνομα του εκτυπωτή που θα χρησιμοποιηθεί.
### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public final void setPrinterName(String value)
```


Ορίζει το όνομα του εκτυπωτή που θα χρησιμοποιηθεί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String | το όνομα του εκτυπωτή που θα χρησιμοποιηθεί. |

