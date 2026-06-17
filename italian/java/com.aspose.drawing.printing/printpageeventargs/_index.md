---
title: PrintPageEventArgs
second_title: Riferimento API di Aspose.Drawing per Java
description: Fornisce dati per l'evento EPrintDocument.PrintPage.
type: docs
weight: 13
url: /it/java/com.aspose.drawing.printing/printpageeventargs/
---
**Inheritance:**
java.lang.Object
```
public class PrintPageEventArgs
```

Fornisce i dati per l'evento `E:PrintDocument.PrintPage`.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PrintPageEventArgs()](#PrintPageEventArgs--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getGraphics()](#getGraphics--) | Ottiene il `Graphics`([.getGraphics](../../null/\#getGraphics)) usato per disegnare la pagina. |
| [hasMorePages()](#hasMorePages--) | Ottiene un valore che indica se una pagina aggiuntiva deve essere stampata. |
| [setMorePages(boolean value)](#setMorePages-boolean-) | Imposta un valore che indica se una pagina aggiuntiva deve essere stampata. |
| [getPageSettings()](#getPageSettings--) | Ottiene le impostazioni della pagina per la pagina corrente. |
### PrintPageEventArgs() {#PrintPageEventArgs--}
```
public PrintPageEventArgs()
```


### getGraphics() {#getGraphics--}
```
public final Graphics getGraphics()
```


Ottiene il `Graphics`([.getGraphics](../../null/\#getGraphics)) usato per disegnare la pagina.

**Returns:**
[Graphics](../../com.aspose.drawing/graphics) - The `Graphics`([.getGraphics](../../null/\#getGraphics)) used to paint the page.
### hasMorePages() {#hasMorePages--}
```
public final boolean hasMorePages()
```


Ottiene un valore che indica se una pagina aggiuntiva deve essere stampata.

**Returns:**
boolean - `true` se una pagina aggiuntiva deve essere stampata; altrimenti, false. Il valore predefinito è `false`.
### setMorePages(boolean value) {#setMorePages-boolean-}
```
public final void setMorePages(boolean value)
```


Imposta un valore che indica se una pagina aggiuntiva deve essere stampata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean | un valore che indica se una pagina aggiuntiva deve essere stampata. |

### getPageSettings() {#getPageSettings--}
```
public final PageSettings getPageSettings()
```


Ottiene le impostazioni della pagina per la pagina corrente.

**Returns:**
[PageSettings](../../com.aspose.drawing.printing/pagesettings) - The page settings for the current page.
