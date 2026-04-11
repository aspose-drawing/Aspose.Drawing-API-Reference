---
title: PageSettings
second_title: Aspose.Drawing voor Java API-referentie
description: Specificeert instellingen die van toepassing zijn op een enkele afgedrukte pagina.
type: docs
weight: 10
url: /nl/java/com.aspose.drawing.printing/pagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PageSettings
```

Specificeert instellingen die van toepassing zijn op een enkele, afgedrukte pagina.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PageSettings()](#PageSettings--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBounds()](#getBounds--) | Haalt de grootte van de pagina op, rekening houdend met de paginarichting die is gespecificeerd door de [PageSettings](../../com.aspose.drawing.printing/pagesettings)-eigenschap. |
| [getHardMarginX()](#getHardMarginX--) | Haalt de x-coördinaat, in honderdsten van een inch, van de harde marge aan de linkerkant van de pagina op. |
| [getHardMarginY()](#getHardMarginY--) | Haalt de y-coördinaat, in honderdsten van een inch, van de harde marge aan de bovenkant van de pagina op. |
| [getPrinterResolution()](#getPrinterResolution--) | Haalt de printerresolutie voor de pagina op. |
### PageSettings() {#PageSettings--}
```
public PageSettings()
```


### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Haalt de grootte van de pagina op, rekening houdend met de paginarichting die is gespecificeerd door de [PageSettings](../../com.aspose.drawing.printing/pagesettings)-eigenschap.

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the length and width, in hundredths of an inch, of the page.
### getHardMarginX() {#getHardMarginX--}
```
public final float getHardMarginX()
```


Haalt de x-coördinaat, in honderdsten van een inch, van de harde marge aan de linkerkant van de pagina op.

**Returns:**
float - De x-coördinaat, in honderdsten van een inch, van de harde marge aan de linkerkant.
### getHardMarginY() {#getHardMarginY--}
```
public final float getHardMarginY()
```


Haalt de y-coördinaat, in honderdsten van een inch, van de harde marge aan de bovenkant van de pagina op.

**Returns:**
float - De y-coördinaat, in honderdsten van een inch, van de harde marge aan de bovenkant van de pagina.
### getPrinterResolution() {#getPrinterResolution--}
```
public final PrinterResolution getPrinterResolution()
```


Haalt de printerresolutie voor de pagina op.

**Returns:**
[PrinterResolution](../../com.aspose.drawing.printing/printerresolution) - A `PrinterResolution`([.getPrinterResolution](../../null/\#getPrinterResolution)) that specifies the printer resolution for the page. The default is the printer's default resolution.
