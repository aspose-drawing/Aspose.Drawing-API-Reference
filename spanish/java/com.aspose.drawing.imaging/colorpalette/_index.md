---
title: ColorPalette
second_title: Referencia de la API de Aspose.Drawing para Java
description: Define una matriz de colores que forman una paleta de colores.
type: docs
weight: 16
url: /es/java/com.aspose.drawing.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPalette
```

Define una matriz de colores que forman una paleta de colores. Los colores son colores ARGB de 32 bits. No heredable.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ColorPalette(int count)](#ColorPalette-int-) | Inicializa una nueva instancia de la clase `ColorPalette` y IsCompactPalette es false. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getEntries()](#getEntries--) | Obtiene una matriz de estructuras `com.aspose.drawing.Color`. |
| [isCompactPalette()](#isCompactPalette--) | Obtiene o establece un valor que indica si se usa una paleta compacta. |
| [getFlags()](#getFlags--) |  |
| [setFlags(int flags)](#setFlags-int-) |  |
| [setEntries(int i, Color color)](#setEntries-int-com.aspose.drawing.Color-) |  |
### ColorPalette(int count) {#ColorPalette-int-}
```
public ColorPalette(int count)
```


Inicializa una nueva instancia de la clase `ColorPalette` y IsCompactPalette es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| count | int | Las entradas de la paleta de colores. |

### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Obtiene una matriz de estructuras `com.aspose.drawing.Color`.

**Returns:**
com.aspose.drawing.Color[] - Las entradas. La matriz de estructuras `com.aspose.drawing.Color` que forman este `Aspose.Imaging.ColorPalette`.
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Obtiene o establece un valor que indica si se usa una paleta compacta.

**Returns:**
boolean - `true` si se usa una paleta compacta; de lo contrario, `false`.

Una paleta compacta significa que la imagen contendrá solo las entradas de paleta especificadas si es posible; en otras palabras, la imagen será más compacta y ocupará menos espacio. De lo contrario, habrá 2^BitsPerPixel entradas y la imagen reservará más espacio para todas las posibles entradas de paleta. Establecer este valor en true y cambiar las entradas de la paleta puede causar una penalización de rendimiento ya que puede producirse movimiento de datos, por lo que debe usarse con cuidado.
### getFlags() {#getFlags--}
```
public int getFlags()
```




**Returns:**
int
### setFlags(int flags) {#setFlags-int-}
```
public void setFlags(int flags)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flags | int |  |

### setEntries(int i, Color color) {#setEntries-int-com.aspose.drawing.Color-}
```
public void setEntries(int i, Color color)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | int |  |
| color | [Color](../../com.aspose.drawing/color) |  |

