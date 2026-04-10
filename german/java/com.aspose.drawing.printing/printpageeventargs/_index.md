---
title: PrintPageEventArgs
second_title: Aspose.Drawing für Java API-Referenz
description: Stellt Daten für das Ereignis EPrintDocument.PrintPage bereit.
type: docs
weight: 13
url: /de/java/com.aspose.drawing.printing/printpageeventargs/
---
**Inheritance:**
java.lang.Object
```
public class PrintPageEventArgs
```

Stellt Daten für das Ereignis `E:PrintDocument.PrintPage` bereit.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PrintPageEventArgs()](#PrintPageEventArgs--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getGraphics()](#getGraphics--) | Ermittelt die `Graphics`([.getGraphics](../../null/\#getGraphics)), die zum Zeichnen der Seite verwendet wird. |
| [hasMorePages()](#hasMorePages--) | Liest einen Wert, der angibt, ob eine zusätzliche Seite gedruckt werden soll. |
| [setMorePages(boolean value)](#setMorePages-boolean-) | Setzt einen Wert, der angibt, ob eine zusätzliche Seite gedruckt werden soll. |
| [getPageSettings()](#getPageSettings--) | Liest die Seiteneinstellungen für die aktuelle Seite. |
### PrintPageEventArgs() {#PrintPageEventArgs--}
```
public PrintPageEventArgs()
```


### getGraphics() {#getGraphics--}
```
public final Graphics getGraphics()
```


Ermittelt die `Graphics`([.getGraphics](../../null/\#getGraphics)), die zum Zeichnen der Seite verwendet wird.

**Returns:**
[Graphics](../../com.aspose.drawing/graphics) - The `Graphics`([.getGraphics](../../null/\#getGraphics)) used to paint the page.
### hasMorePages() {#hasMorePages--}
```
public final boolean hasMorePages()
```


Liest einen Wert, der angibt, ob eine zusätzliche Seite gedruckt werden soll.

**Returns:**
boolean - `true`, wenn eine zusätzliche Seite gedruckt werden soll; andernfalls `false`. Der Standardwert ist `false`.
### setMorePages(boolean value) {#setMorePages-boolean-}
```
public final void setMorePages(boolean value)
```


Setzt einen Wert, der angibt, ob eine zusätzliche Seite gedruckt werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | ein Wert, der angibt, ob eine zusätzliche Seite gedruckt werden soll. |

### getPageSettings() {#getPageSettings--}
```
public final PageSettings getPageSettings()
```


Liest die Seiteneinstellungen für die aktuelle Seite.

**Returns:**
[PageSettings](../../com.aspose.drawing.printing/pagesettings) - The page settings for the current page.
