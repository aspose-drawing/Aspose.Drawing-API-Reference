---
title: PageSettings
second_title: Riferimento API di Aspose.Drawing per Java
description: Specifica le impostazioni che si applicano a una singola pagina stampata.
type: docs
weight: 10
url: /it/java/com.aspose.drawing.printing/pagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PageSettings
```

Specifica le impostazioni che si applicano a una singola pagina stampata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PageSettings()](#PageSettings--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds()](#getBounds--) | Ottiene le dimensioni della pagina, tenendo conto dell'orientamento della pagina specificato dalla proprietà [PageSettings](../../com.aspose.drawing.printing/pagesettings). |
| [getHardMarginX()](#getHardMarginX--) | Restituisce la coordinata x, in centesimi di pollice, del margine fisso a sinistra della pagina. |
| [getHardMarginY()](#getHardMarginY--) | Restituisce la coordinata y, in centesimi di pollice, del margine fisso nella parte superiore della pagina. |
| [getPrinterResolution()](#getPrinterResolution--) | Restituisce la risoluzione della stampante per la pagina. |
### PageSettings() {#PageSettings--}
```
public PageSettings()
```


### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Ottiene le dimensioni della pagina, tenendo conto dell'orientamento della pagina specificato dalla proprietà [PageSettings](../../com.aspose.drawing.printing/pagesettings).

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the length and width, in hundredths of an inch, of the page.
### getHardMarginX() {#getHardMarginX--}
```
public final float getHardMarginX()
```


Restituisce la coordinata x, in centesimi di pollice, del margine fisso a sinistra della pagina.

**Returns:**
float - La coordinata x, in centesimi di pollice, del margine fisso sinistro.
### getHardMarginY() {#getHardMarginY--}
```
public final float getHardMarginY()
```


Restituisce la coordinata y, in centesimi di pollice, del margine fisso nella parte superiore della pagina.

**Returns:**
float - La coordinata y, in centesimi di pollice, del margine fisso nella parte superiore della pagina.
### getPrinterResolution() {#getPrinterResolution--}
```
public final PrinterResolution getPrinterResolution()
```


Restituisce la risoluzione della stampante per la pagina.

**Returns:**
[PrinterResolution](../../com.aspose.drawing.printing/printerresolution) - A `PrinterResolution`([.getPrinterResolution](../../null/\#getPrinterResolution)) that specifies the printer resolution for the page. The default is the printer's default resolution.
