---
title: PageSettings
second_title: Referencia de la API de Aspose.Drawing para Java
description: Especifica la configuración que se aplica a una sola página impresa.
type: docs
weight: 10
url: /es/java/com.aspose.drawing.printing/pagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PageSettings
```

Especifica la configuración que se aplica a una única página impresa.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PageSettings()](#PageSettings--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene el tamaño de la página, teniendo en cuenta la orientación de la página especificada por la propiedad [PageSettings](../../com.aspose.drawing.printing/pagesettings). |
| [getHardMarginX()](#getHardMarginX--) | Obtiene la coordenada x, en centésimas de pulgada, del margen rígido en el lado izquierdo de la página. |
| [getHardMarginY()](#getHardMarginY--) | Obtiene la coordenada y, en centésimas de pulgada, del margen rígido en la parte superior de la página. |
| [getPrinterResolution()](#getPrinterResolution--) | Obtiene la resolución de la impresora para la página. |
### PageSettings() {#PageSettings--}
```
public PageSettings()
```


### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Obtiene el tamaño de la página, teniendo en cuenta la orientación de la página especificada por la propiedad [PageSettings](../../com.aspose.drawing.printing/pagesettings).

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the length and width, in hundredths of an inch, of the page.
### getHardMarginX() {#getHardMarginX--}
```
public final float getHardMarginX()
```


Obtiene la coordenada x, en centésimas de pulgada, del margen rígido en el lado izquierdo de la página.

**Returns:**
float - La coordenada x, en centésimas de pulgada, del margen rígido izquierdo.
### getHardMarginY() {#getHardMarginY--}
```
public final float getHardMarginY()
```


Obtiene la coordenada y, en centésimas de pulgada, del margen rígido en la parte superior de la página.

**Returns:**
float - La coordenada y, en centésimas de pulgada, del margen rígido en la parte superior de la página.
### getPrinterResolution() {#getPrinterResolution--}
```
public final PrinterResolution getPrinterResolution()
```


Obtiene la resolución de la impresora para la página.

**Returns:**
[PrinterResolution](../../com.aspose.drawing.printing/printerresolution) - A `PrinterResolution`([.getPrinterResolution](../../null/\#getPrinterResolution)) that specifies the printer resolution for the page. The default is the printer's default resolution.
