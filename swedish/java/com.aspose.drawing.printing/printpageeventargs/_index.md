---
title: PrintPageEventArgs
second_title: Aspose.Drawing för Java API‑referens
description: Tillhandahåller data för händelsen EPrintDocument.PrintPage.
type: docs
weight: 13
url: /sv/java/com.aspose.drawing.printing/printpageeventargs/
---
**Inheritance:**
java.lang.Object
```
public class PrintPageEventArgs
```

Tillhandahåller data för händelsen `E:PrintDocument.PrintPage`.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PrintPageEventArgs()](#PrintPageEventArgs--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getGraphics()](#getGraphics--) | Hämtar `Graphics`([.getGraphics](../../null/\#getGraphics)) som används för att måla sidan. |
| [hasMorePages()](#hasMorePages--) | Hämtar ett värde som indikerar om en extra sida ska skrivas ut. |
| [setMorePages(boolean value)](#setMorePages-boolean-) | Ställer in ett värde som indikerar om en extra sida ska skrivas ut. |
| [getPageSettings()](#getPageSettings--) | Hämtar sidinställningarna för den aktuella sidan. |
### PrintPageEventArgs() {#PrintPageEventArgs--}
```
public PrintPageEventArgs()
```


### getGraphics() {#getGraphics--}
```
public final Graphics getGraphics()
```


Hämtar `Graphics`([.getGraphics](../../null/\#getGraphics)) som används för att måla sidan.

**Returns:**
[Graphics](../../com.aspose.drawing/graphics) - The `Graphics`([.getGraphics](../../null/\#getGraphics)) used to paint the page.
### hasMorePages() {#hasMorePages--}
```
public final boolean hasMorePages()
```


Hämtar ett värde som indikerar om en extra sida ska skrivas ut.

**Returns:**
boolean - `true` om en extra sida ska skrivas ut; annars `false`. Standardvärdet är `false`.
### setMorePages(boolean value) {#setMorePages-boolean-}
```
public final void setMorePages(boolean value)
```


Ställer in ett värde som indikerar om en extra sida ska skrivas ut.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | ett värde som indikerar om en extra sida ska skrivas ut. |

### getPageSettings() {#getPageSettings--}
```
public final PageSettings getPageSettings()
```


Hämtar sidinställningarna för den aktuella sidan.

**Returns:**
[PageSettings](../../com.aspose.drawing.printing/pagesettings) - The page settings for the current page.
