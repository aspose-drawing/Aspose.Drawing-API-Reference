---
title: PageSettings
second_title: Αναφορά API του Aspose.Drawing for Java
description: Καθορίζει ρυθμίσεις που εφαρμόζονται σε μια μόνο εκτυπωμένη σελίδα.
type: docs
weight: 10
url: /el/java/com.aspose.drawing.printing/pagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PageSettings
```

Καθορίζει ρυθμίσεις που εφαρμόζονται σε μια μόνο εκτυπωμένη σελίδα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PageSettings()](#PageSettings--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBounds()](#getBounds--) | Λαμβάνει το μέγεθος της σελίδας, λαμβάνοντας υπόψη τον προσανατολισμό της σελίδας που καθορίζεται από την ιδιότητα [PageSettings](../../com.aspose.drawing.printing/pagesettings). |
| [getHardMarginX()](#getHardMarginX--) | Gets the x-coordinate, in hundredths of an inch, of the hard margin at the left of the page. |
| [getHardMarginY()](#getHardMarginY--) | Gets the y-coordinate, in hundredths of an inch, of the hard margin at the top of the page. |
| [getPrinterResolution()](#getPrinterResolution--) | Gets the printer resolution for the page. |
### PageSettings() {#PageSettings--}
```
public PageSettings()
```


### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Λαμβάνει το μέγεθος της σελίδας, λαμβάνοντας υπόψη τον προσανατολισμό της σελίδας που καθορίζεται από την ιδιότητα [PageSettings](../../com.aspose.drawing.printing/pagesettings).

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the length and width, in hundredths of an inch, of the page.
### getHardMarginX() {#getHardMarginX--}
```
public final float getHardMarginX()
```


Gets the x-coordinate, in hundredths of an inch, of the hard margin at the left of the page.

**Returns:**
float - The x-coordinate, in hundredths of an inch, of the left-hand hard margin.
### getHardMarginY() {#getHardMarginY--}
```
public final float getHardMarginY()
```


Gets the y-coordinate, in hundredths of an inch, of the hard margin at the top of the page.

**Returns:**
float - The y-coordinate, in hundredths of an inch, of the hard margin at the top of the page.
### getPrinterResolution() {#getPrinterResolution--}
```
public final PrinterResolution getPrinterResolution()
```


Gets the printer resolution for the page.

**Returns:**
[PrinterResolution](../../com.aspose.drawing.printing/printerresolution) - A `PrinterResolution`([.getPrinterResolution](../../null/\#getPrinterResolution)) that specifies the printer resolution for the page. The default is the printer's default resolution.
