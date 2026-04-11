---
title: PrintPageEventArgs
second_title: Aspose.Drawing voor Java API-referentie
description: Biedt gegevens voor het EPrintDocument.PrintPage‑evenement.
type: docs
weight: 13
url: /nl/java/com.aspose.drawing.printing/printpageeventargs/
---
**Inheritance:**
java.lang.Object
```
public class PrintPageEventArgs
```

Levert gegevens voor het `E:PrintDocument.PrintPage`‑evenement.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PrintPageEventArgs()](#PrintPageEventArgs--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getGraphics()](#getGraphics--) | Haalt de `Graphics`([.getGraphics](../../null/\#getGraphics)) op die wordt gebruikt om de pagina te schilderen. |
| [hasMorePages()](#hasMorePages--) | Haalt een waarde op die aangeeft of een extra pagina moet worden afgedrukt. |
| [setMorePages(boolean value)](#setMorePages-boolean-) | Stelt een waarde in die aangeeft of een extra pagina moet worden afgedrukt. |
| [getPageSettings()](#getPageSettings--) | Haalt de pagina-instellingen op voor de huidige pagina. |
### PrintPageEventArgs() {#PrintPageEventArgs--}
```
public PrintPageEventArgs()
```


### getGraphics() {#getGraphics--}
```
public final Graphics getGraphics()
```


Haalt de `Graphics`([.getGraphics](../../null/\#getGraphics)) op die wordt gebruikt om de pagina te schilderen.

**Returns:**
[Graphics](../../com.aspose.drawing/graphics) - The `Graphics`([.getGraphics](../../null/\#getGraphics)) used to paint the page.
### hasMorePages() {#hasMorePages--}
```
public final boolean hasMorePages()
```


Haalt een waarde op die aangeeft of een extra pagina moet worden afgedrukt.

**Returns:**
boolean - `true` als een extra pagina moet worden afgedrukt; anders `false`. Standaard is `false`.
### setMorePages(boolean value) {#setMorePages-boolean-}
```
public final void setMorePages(boolean value)
```


Stelt een waarde in die aangeeft of een extra pagina moet worden afgedrukt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | een waarde die aangeeft of een extra pagina moet worden afgedrukt. |

### getPageSettings() {#getPageSettings--}
```
public final PageSettings getPageSettings()
```


Haalt de pagina-instellingen op voor de huidige pagina.

**Returns:**
[PageSettings](../../com.aspose.drawing.printing/pagesettings) - The page settings for the current page.
