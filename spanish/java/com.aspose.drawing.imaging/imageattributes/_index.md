---
title: ImageAttributes
second_title: Referencia de la API de Aspose.Drawing para Java
description: Contiene información sobre cómo se manipulan los colores de bitmap y metafile durante el renderizado.
type: docs
weight: 24
url: /es/java/com.aspose.drawing.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class ImageAttributes implements System.IDisposable
```

Contiene información sobre cómo se manipulan los colores de bitmap y metafile durante el renderizado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Inicializa una nueva instancia de la clase [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
## Métodos

| Método | Descripción |
| --- | --- |
| [dispose()](#dispose--) | Libera todos los recursos utilizados por este objeto [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [deepClone()](#deepClone--) | Crea una copia exacta de este objeto [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Establece la matriz de ajuste de color para la categoría predeterminada. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Establece la matriz de ajuste de color para la categoría predeterminada. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Establece la matriz de ajuste de color para una categoría especificada. |
| [clearColorMatrix()](#clearColorMatrix--) | Borra la matriz de ajuste de color para la categoría predeterminada. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Borra la matriz de ajuste de color para una categoría especificada. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para una categoría especificada. |
| [setThreshold(float threshold)](#setThreshold-float-) | Establece el umbral (rango de transparencia) para la categoría predeterminada. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Establece el umbral (rango de transparencia) para una categoría especificada. |
| [clearThreshold()](#clearThreshold--) | Borra el valor del umbral para la categoría predeterminada. |
| [clearThreshold(int type)](#clearThreshold-int-) | Borra el valor del umbral para una categoría especificada. |
| [setGamma(float gamma)](#setGamma-float-) | Establece el valor gamma para la categoría predeterminada. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Establece el valor gamma para una categoría especificada. |
| [clearGamma()](#clearGamma--) | Desactiva la corrección gamma para la categoría predeterminada. |
| [clearGamma(int type)](#clearGamma-int-) | Desactiva la corrección gamma para una categoría especificada. |
| [setNoOp()](#setNoOp--) | Desactiva el ajuste de color para la categoría predeterminada. |
| [setNoOp(int type)](#setNoOp-int-) | Desactiva el ajuste de color para una categoría especificada. |
| [clearNoOp()](#clearNoOp--) | Borra la configuración NoOp para la categoría predeterminada. |
| [clearNoOp(int type)](#clearNoOp-int-) | Borra la configuración NoOp para una categoría especificada. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Establece la clave de color para la categoría predeterminada. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Establece la clave de color (rango de transparencia) para una categoría especificada. |
| [clearColorKey()](#clearColorKey--) | Borra la clave de color (rango de transparencia) para la categoría predeterminada. |
| [clearColorKey(int type)](#clearColorKey-int-) | Borra la clave de color (rango de transparencia) para una categoría especificada. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para una categoría especificada. |
| [clearOutputChannel()](#clearOutputChannel--) | Borra la configuración del canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Borra la configuración del canal de salida (cian-magenta-amarillo-negro) para una categoría especificada. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Establece el archivo de perfil de color del canal de salida para la categoría predeterminada. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Establece el archivo de perfil de color del canal de salida para una categoría especificada. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Borra la configuración del perfil de color del canal de salida para la categoría predeterminada. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Borra la configuración del perfil de color del canal de salida para una categoría especificada. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---) | Establece la tabla de remapeo de color para la categoría predeterminada. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-) | Establece la tabla de remapeo de color para una categoría especificada. |
| [clearRemapTable()](#clearRemapTable--) | Borra la tabla de remapeo de color para la categoría predeterminada. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Borra la tabla de remapeo de color para una categoría especificada. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---) | Establece la tabla de remapeo de color para la categoría de pincel. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Borra la tabla de remapeo de color del pincel de este objeto [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [setWrapMode(int mode)](#setWrapMode-int-) | Establece el modo de ajuste que se utiliza para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.drawing.Color-) | Establece el modo de ajuste y el color utilizados para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.drawing.Color-boolean-) | Establece el modo de ajuste y el color utilizados para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. |
| [getAdjustedPalette(ColorPalette palette, int type)](#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-) | Ajusta los colores en una paleta según la configuración de ajuste de una categoría especificada. |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Inicializa una nueva instancia de la clase [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### dispose() {#dispose--}
```
public void dispose()
```


Libera todos los recursos utilizados por este objeto [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia exacta de este objeto [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

**Returns:**
java.lang.Object - El objeto [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) que crea esta clase, convertido a objeto.
### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Establece la matriz de ajuste de color para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matriz de ajuste de color. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Establece la matriz de ajuste de color para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matriz de ajuste de color. |
| flags | int | Un elemento de [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) que especifica el tipo de imagen y color que será afectado por la matriz de ajuste de color. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Establece la matriz de ajuste de color para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matriz de ajuste de color. |
| mode | int | Un elemento de [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) que especifica el tipo de imagen y color que será afectado por la matriz de ajuste de color. |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la cual se establece la matriz de ajuste de color. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Borra la matriz de ajuste de color para la categoría predeterminada.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Borra la matriz de ajuste de color para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la cual se borra la matriz de ajuste de color. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matriz de ajuste de color. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matriz de ajuste de escala de grises. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matriz de ajuste de color. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matriz de ajuste de escala de grises. |
| flags | int | Un elemento de [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) que especifica el tipo de imagen y color que será afectado por las matrices de ajuste de color y de escala de grises. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matriz de ajuste de color. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matriz de ajuste de escala de grises. |
| mode | int | Un elemento de [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) que especifica el tipo de imagen y color que será afectado por las matrices de ajuste de color y de escala de grises. |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la cual se establecen las matrices de ajuste de color y de escala de grises. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Establece el umbral (rango de transparencia) para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| umbral | float | Un número real que especifica el valor del umbral. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Establece el umbral (rango de transparencia) para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| umbral | float | Un valor de umbral de 0.0 a 1.0 que se utiliza como punto de ruptura para ordenar los colores que se asignarán a un valor máximo o mínimo. |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la cual se establece el umbral de color. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Borra el valor del umbral para la categoría predeterminada.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Borra el valor del umbral para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la cual se borra el umbral. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Establece el valor gamma para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gamma | float | El valor de corrección gamma. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Establece el valor gamma para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gamma | float | El valor de corrección gamma. |
| type | int | Un elemento de la enumeración [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la que se establece el valor gamma. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Desactiva la corrección gamma para la categoría predeterminada.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Desactiva la corrección gamma para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la que la corrección gamma está deshabilitada. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Desactiva el ajuste de color para la categoría predeterminada. Puede llamar al método [.clearNoOp](../../null/\#clearNoOp) para restablecer la configuración de ajuste de color que estaba activa antes de la llamada al método [.setNoOp](../../null/\#setNoOp).

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Desactiva el ajuste de color para una categoría especificada. Puede llamar al método [.clearNoOp](../../null/\#clearNoOp) para restablecer la configuración de ajuste de color que estaba activa antes de la llamada al método [.setNoOp](../../null/\#setNoOp).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la que la corrección de color está desactivada. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Borra la configuración NoOp para la categoría predeterminada.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Borra la configuración NoOp para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la que se elimina la configuración NoOp. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Establece la clave de color para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | El valor bajo de la clave de color. |
| colorHigh | [Color](../../com.aspose.drawing/color) | El valor alto de la clave de color. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Establece la clave de color (rango de transparencia) para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | El valor bajo de la clave de color. |
| colorHigh | [Color](../../com.aspose.drawing/color) | El valor alto de la clave de color. |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la que se establece la clave de color. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Borra la clave de color (rango de transparencia) para la categoría predeterminada.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Borra la clave de color (rango de transparencia) para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la que se elimina la clave de color. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flags | int | Un elemento de [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) que especifica el canal de salida. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flags | int | Un elemento de [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) que especifica el canal de salida. |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la que se establece el canal de salida. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Borra la configuración del canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Borra la configuración del canal de salida (cian-magenta-amarillo-negro) para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la que se elimina la configuración del canal de salida. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Establece el archivo de perfil de color del canal de salida para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | La ruta de un archivo de perfil de color. Si el archivo de perfil de color está en el directorio %SystemRoot%\\System32\\Spool\\Drivers\\Color, este parámetro puede ser el nombre del archivo. De lo contrario, este parámetro debe ser la ruta completa. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Establece el archivo de perfil de color del canal de salida para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | La ruta de un archivo de perfil de color. Si el archivo de perfil de color está en el directorio %SystemRoot%\\System32\\Spool\\Drivers\\Color, este parámetro puede ser el nombre del archivo. De lo contrario, este parámetro debe ser la ruta completa. |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la que se establece el archivo de perfil de color del canal de salida. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Borra la configuración del perfil de color del canal de salida para la categoría predeterminada.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Borra la configuración del perfil de color del canal de salida para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la que se elimina la configuración del perfil del canal de salida. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Establece la tabla de remapeo de color para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Una matriz de pares de colores del tipo [ColorMap](../../com.aspose.drawing.imaging/colormap). Cada par de colores contiene un color existente (el primer valor) y el color al que se mapeará (el segundo valor). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Establece la tabla de remapeo de color para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Una matriz de pares de colores del tipo [ColorMap](../../com.aspose.drawing.imaging/colormap). Cada par de colores contiene un color existente (el primer valor) y el color al que se mapeará (el segundo valor). |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la que se establece la tabla de remapeo de colores. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Borra la tabla de remapeo de color para la categoría predeterminada.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Borra la tabla de remapeo de color para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría para la que se elimina la tabla de remapeo. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Establece la tabla de remapeo de color para la categoría de pincel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Una matriz de objetos [ColorMap](../../com.aspose.drawing.imaging/colormap). |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Borra la tabla de remapeo de color del pincel de este objeto [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Establece el modo de ajuste que se utiliza para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | int | Un elemento de [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) que especifica cómo se utilizan copias repetidas de una imagen para mosaicar un área. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.drawing.Color-}
```
public void setWrapMode(int mode, Color color)
```


Establece el modo de ajuste y el color que se usan para decidir cómo mosaicar una textura a lo largo de una forma, o en los bordes de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | int | Un elemento de [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) que especifica cómo se utilizan copias repetidas de una imagen para mosaicar un área. |
| color | [Color](../../com.aspose.drawing/color) | Un objeto [Color](../../com.aspose.drawing/color) que especifica el color de los píxeles fuera de una imagen renderizada. Este color es visible si el parámetro mode se establece en `WrapMode.Clamp` y el rectángulo de origen pasado a `Graphics.DrawImage` es más grande que la propia imagen. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.drawing.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Establece el modo de ajuste y el color que se usan para decidir cómo mosaicar una textura a lo largo de una forma, o en los bordes de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | int | Un elemento de [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) que especifica cómo se utilizan copias repetidas de una imagen para mosaicar un área. |
| color | [Color](../../com.aspose.drawing/color) | Un objeto de color que especifica el color de los píxeles fuera de una imagen renderizada. Este color es visible si el parámetro mode se establece en `WrapMode.Clamp` y el rectángulo de origen pasado a `Graphics.DrawImage` es más grande que la propia imagen. |
| clamp | boolean | Este parámetro no tiene efecto. Establécelo en false. |

### getAdjustedPalette(ColorPalette palette, int type) {#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-}
```
public void getAdjustedPalette(ColorPalette palette, int type)
```


Ajusta los colores en una paleta según la configuración de ajuste de una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| palette | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) | Una [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) que en la entrada contiene la paleta a ajustar, y en la salida contiene la paleta ajustada. |
| type | int | Un elemento de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) que especifica la categoría cuyas configuraciones de ajuste se aplicarán a la paleta. |

