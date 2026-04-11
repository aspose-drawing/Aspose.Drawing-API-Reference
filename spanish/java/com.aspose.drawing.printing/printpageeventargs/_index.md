---
title: PrintPageEventArgs
second_title: Referencia de la API de Aspose.Drawing para Java
description: Proporciona datos para el evento EPrintDocument.PrintPage.
type: docs
weight: 13
url: /es/java/com.aspose.drawing.printing/printpageeventargs/
---
**Inheritance:**
java.lang.Object
```
public class PrintPageEventArgs
```

Proporciona datos para el evento `E:PrintDocument.PrintPage`.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PrintPageEventArgs()](#PrintPageEventArgs--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getGraphics()](#getGraphics--) | Obtiene el `Graphics`([.getGraphics](../../null/\#getGraphics)) utilizado para dibujar la página. |
| [hasMorePages()](#hasMorePages--) | Obtiene un valor que indica si se debe imprimir una página adicional. |
| [setMorePages(boolean value)](#setMorePages-boolean-) | Establece un valor que indica si se debe imprimir una página adicional. |
| [getPageSettings()](#getPageSettings--) | Obtiene la configuración de página para la página actual. |
### PrintPageEventArgs() {#PrintPageEventArgs--}
```
public PrintPageEventArgs()
```


### getGraphics() {#getGraphics--}
```
public final Graphics getGraphics()
```


Obtiene el `Graphics`([.getGraphics](../../null/\#getGraphics)) utilizado para dibujar la página.

**Returns:**
[Graphics](../../com.aspose.drawing/graphics) - The `Graphics`([.getGraphics](../../null/\#getGraphics)) used to paint the page.
### hasMorePages() {#hasMorePages--}
```
public final boolean hasMorePages()
```


Obtiene un valor que indica si se debe imprimir una página adicional.

**Returns:**
boolean - `true` si se debe imprimir una página adicional; de lo contrario, false. El valor predeterminado es `false`.
### setMorePages(boolean value) {#setMorePages-boolean-}
```
public final void setMorePages(boolean value)
```


Establece un valor que indica si se debe imprimir una página adicional.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | un valor que indica si se debe imprimir una página adicional. |

### getPageSettings() {#getPageSettings--}
```
public final PageSettings getPageSettings()
```


Obtiene la configuración de página para la página actual.

**Returns:**
[PageSettings](../../com.aspose.drawing.printing/pagesettings) - The page settings for the current page.
