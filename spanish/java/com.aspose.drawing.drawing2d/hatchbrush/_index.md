---
title: HatchBrush
second_title: Referencia de la API de Aspose.Drawing para Java
description: Define una brocha rectangular con un estilo de trama, un color de primer plano y un color de fondo.
type: docs
weight: 26
url: /es/java/com.aspose.drawing.drawing2d/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class HatchBrush extends Brush
```

Define una brocha rectangular con un estilo de trama, un color de primer plano y un color de fondo. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [HatchBrush(int hatchstyle, Color foreColor)](#HatchBrush-int-com.aspose.drawing.Color-) | Inicializa una nueva instancia de la clase [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) con la enumeración `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) especificada y el color de primer plano. |
| [HatchBrush(int hatchstyle, Color foreColor, Color backColor)](#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Inicializa una nueva instancia de la clase [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) con la enumeración `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) especificada, el color de primer plano y el color de fondo. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getHatchStyle()](#getHatchStyle--) | Obtiene el estilo de trama de este objeto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [getForegroundColor()](#getForegroundColor--) | Obtiene el color de las líneas de trama dibujadas por este objeto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene el color de los espacios entre las líneas de trama dibujadas por este objeto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [deepClone()](#deepClone--) | Crea una copia exacta de este objeto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
### HatchBrush(int hatchstyle, Color foreColor) {#HatchBrush-int-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor)
```


Inicializa una nueva instancia de la clase [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) con la enumeración `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) especificada y el color de primer plano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hatchstyle | int | Uno de los valores `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) que representa el patrón dibujado por este [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| foreColor | [Color](../../com.aspose.drawing/color) | La estructura [Color](../../com.aspose.drawing/color) que representa el color de las líneas dibujadas por este [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |

### HatchBrush(int hatchstyle, Color foreColor, Color backColor) {#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor, Color backColor)
```


Inicializa una nueva instancia de la clase [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) con la enumeración `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) especificada, el color de primer plano y el color de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hatchstyle | int | Uno de los valores `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) que representa el patrón dibujado por este [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| foreColor | [Color](../../com.aspose.drawing/color) | La estructura [Color](../../com.aspose.drawing/color) que representa el color de las líneas dibujadas por este [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| backColor | [Color](../../com.aspose.drawing/color) | La estructura [Color](../../com.aspose.drawing/color) que representa el color de los espacios entre las líneas dibujadas por este [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Obtiene el estilo de trama de este objeto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
int - el estilo de trama de este objeto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Obtiene el color de las líneas de trama dibujadas por este objeto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtiene el color de los espacios entre las líneas de trama dibujadas por este objeto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of spaces between the hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia exacta de este objeto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
java.lang.Object - El [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) que este método crea, convertido a objeto.
