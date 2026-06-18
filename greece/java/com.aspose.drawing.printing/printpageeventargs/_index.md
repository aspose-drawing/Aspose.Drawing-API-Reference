---
title: PrintPageEventArgs
second_title: Αναφορά API του Aspose.Drawing for Java
description: Παρέχει δεδομένα για το συμβάν EPrintDocument.PrintPage.
type: docs
weight: 13
url: /el/java/com.aspose.drawing.printing/printpageeventargs/
---
**Inheritance:**
java.lang.Object
```
public class PrintPageEventArgs
```

Παρέχει δεδομένα για το συμβάν `E:PrintDocument.PrintPage`.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PrintPageEventArgs()](#PrintPageEventArgs--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getGraphics()](#getGraphics--) | Λαμβάνει το `Graphics`([.getGraphics](../../null/\#getGraphics)) που χρησιμοποιείται για τη σχεδίαση της σελίδας. |
| [hasMorePages()](#hasMorePages--) | Λαμβάνει μια τιμή που υποδεικνύει εάν πρέπει να εκτυπωθεί μια επιπλέον σελίδα. |
| [setMorePages(boolean value)](#setMorePages-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν πρέπει να εκτυπωθεί μια επιπλέον σελίδα. |
| [getPageSettings()](#getPageSettings--) | Λαμβάνει τις ρυθμίσεις σελίδας για την τρέχουσα σελίδα. |
### PrintPageEventArgs() {#PrintPageEventArgs--}
```
public PrintPageEventArgs()
```


### getGraphics() {#getGraphics--}
```
public final Graphics getGraphics()
```


Λαμβάνει το `Graphics`([.getGraphics](../../null/\#getGraphics)) που χρησιμοποιείται για τη σχεδίαση της σελίδας.

**Returns:**
[Graphics](../../com.aspose.drawing/graphics) - The `Graphics`([.getGraphics](../../null/\#getGraphics)) used to paint the page.
### hasMorePages() {#hasMorePages--}
```
public final boolean hasMorePages()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν πρέπει να εκτυπωθεί μια επιπλέον σελίδα.

**Returns:**
boolean - `true` εάν πρέπει να εκτυπωθεί μια επιπλέον σελίδα· διαφορετικά, false. Η προεπιλογή είναι `false`.
### setMorePages(boolean value) {#setMorePages-boolean-}
```
public final void setMorePages(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν πρέπει να εκτυπωθεί μια επιπλέον σελίδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | μια τιμή που υποδεικνύει εάν πρέπει να εκτυπωθεί μια επιπλέον σελίδα. |

### getPageSettings() {#getPageSettings--}
```
public final PageSettings getPageSettings()
```


Λαμβάνει τις ρυθμίσεις σελίδας για την τρέχουσα σελίδα.

**Returns:**
[PageSettings](../../com.aspose.drawing.printing/pagesettings) - The page settings for the current page.
