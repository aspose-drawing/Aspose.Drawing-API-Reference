---
title: PageSettings
second_title: Aspose.Drawing för Java API‑referens
description: Specificerar inställningar som gäller för en enskild utskriven sida.
type: docs
weight: 10
url: /sv/java/com.aspose.drawing.printing/pagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PageSettings
```

Anger inställningar som gäller för en enskild, utskriven sida.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PageSettings()](#PageSettings--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar sidans storlek med hänsyn till sidorienteringen som specificeras av egenskapen [PageSettings](../../com.aspose.drawing.printing/pagesettings). |
| [getHardMarginX()](#getHardMarginX--) | Hämtar x-koordinaten, i hundradelar av en tum, för den hårda marginalen till vänster på sidan. |
| [getHardMarginY()](#getHardMarginY--) | Hämtar y-koordinaten, i hundradelar av en tum, för den hårda marginalen högst upp på sidan. |
| [getPrinterResolution()](#getPrinterResolution--) | Hämtar skrivarupplösningen för sidan. |
### PageSettings() {#PageSettings--}
```
public PageSettings()
```


### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Hämtar sidans storlek med hänsyn till sidorienteringen som specificeras av egenskapen [PageSettings](../../com.aspose.drawing.printing/pagesettings).

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the length and width, in hundredths of an inch, of the page.
### getHardMarginX() {#getHardMarginX--}
```
public final float getHardMarginX()
```


Hämtar x-koordinaten, i hundradelar av en tum, för den hårda marginalen till vänster på sidan.

**Returns:**
float - X-koordinaten, i hundradelar av en tum, för den vänstra hårda marginalen.
### getHardMarginY() {#getHardMarginY--}
```
public final float getHardMarginY()
```


Hämtar y-koordinaten, i hundradelar av en tum, för den hårda marginalen högst upp på sidan.

**Returns:**
float - Y-koordinaten, i hundradelar av en tum, för den hårda marginalen högst upp på sidan.
### getPrinterResolution() {#getPrinterResolution--}
```
public final PrinterResolution getPrinterResolution()
```


Hämtar skrivarupplösningen för sidan.

**Returns:**
[PrinterResolution](../../com.aspose.drawing.printing/printerresolution) - A `PrinterResolution`([.getPrinterResolution](../../null/\#getPrinterResolution)) that specifies the printer resolution for the page. The default is the printer's default resolution.
