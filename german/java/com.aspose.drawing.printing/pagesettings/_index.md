---
title: PageSettings
second_title: Aspose.Drawing für Java API-Referenz
description: Gibt Einstellungen an, die für eine einzelne gedruckte Seite gelten.
type: docs
weight: 10
url: /de/java/com.aspose.drawing.printing/pagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PageSettings
```

Gibt Einstellungen an, die für eine einzelne, gedruckte Seite gelten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PageSettings()](#PageSettings--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Ermittelt die Größe der Seite unter Berücksichtigung der durch die Eigenschaft [PageSettings](../../com.aspose.drawing.printing/pagesettings) angegebenen Seitenausrichtung. |
| [getHardMarginX()](#getHardMarginX--) | Liefert die x‑Koordinate, in Hundertstel Zoll, des harten Randes links auf der Seite. |
| [getHardMarginY()](#getHardMarginY--) | Liefert die y‑Koordinate, in Hundertstel Zoll, des harten Randes oben auf der Seite. |
| [getPrinterResolution()](#getPrinterResolution--) | Liefert die Druckerauflösung für die Seite. |
### PageSettings() {#PageSettings--}
```
public PageSettings()
```


### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Ermittelt die Größe der Seite unter Berücksichtigung der durch die Eigenschaft [PageSettings](../../com.aspose.drawing.printing/pagesettings) angegebenen Seitenausrichtung.

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the length and width, in hundredths of an inch, of the page.
### getHardMarginX() {#getHardMarginX--}
```
public final float getHardMarginX()
```


Liefert die x‑Koordinate, in Hundertstel Zoll, des harten Randes links auf der Seite.

**Returns:**
float - Die x‑Koordinate, in Hundertstel Zoll, des linken harten Randes.
### getHardMarginY() {#getHardMarginY--}
```
public final float getHardMarginY()
```


Liefert die y‑Koordinate, in Hundertstel Zoll, des harten Randes oben auf der Seite.

**Returns:**
float - Die y‑Koordinate, in Hundertstel Zoll, des harten Randes oben auf der Seite.
### getPrinterResolution() {#getPrinterResolution--}
```
public final PrinterResolution getPrinterResolution()
```


Liefert die Druckerauflösung für die Seite.

**Returns:**
[PrinterResolution](../../com.aspose.drawing.printing/printerresolution) - A `PrinterResolution`([.getPrinterResolution](../../null/\#getPrinterResolution)) that specifies the printer resolution for the page. The default is the printer's default resolution.
