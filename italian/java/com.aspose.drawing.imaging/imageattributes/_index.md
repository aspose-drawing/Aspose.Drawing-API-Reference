---
title: ImageAttributes
second_title: Riferimento API di Aspose.Drawing per Java
description: Contiene informazioni su come i colori bitmap e metafile vengono manipolati durante il rendering.
type: docs
weight: 24
url: /it/java/com.aspose.drawing.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class ImageAttributes implements System.IDisposable
```

Contiene informazioni su come i colori bitmap e metafile vengono manipolati durante il rendering.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Inizializza una nuova istanza della classe [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [dispose()](#dispose--) | Rilascia tutte le risorse utilizzate da questo oggetto [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [deepClone()](#deepClone--) | Crea una copia esatta di questo oggetto [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Imposta la matrice di correzione del colore per la categoria predefinita. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Imposta la matrice di correzione del colore per la categoria predefinita. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Imposta la matrice di correzione del colore per una categoria specificata. |
| [clearColorMatrix()](#clearColorMatrix--) | Cancella la matrice di regolazione del colore per la categoria predefinita. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Cancella la matrice di regolazione del colore per una categoria specificata. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per la categoria predefinita. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per la categoria predefinita. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per una categoria specificata. |
| [setThreshold(float threshold)](#setThreshold-float-) | Imposta la soglia (intervallo di trasparenza) per la categoria predefinita. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Imposta la soglia (intervallo di trasparenza) per una categoria specificata. |
| [clearThreshold()](#clearThreshold--) | Cancella il valore della soglia per la categoria predefinita. |
| [clearThreshold(int type)](#clearThreshold-int-) | Cancella il valore della soglia per una categoria specificata. |
| [setGamma(float gamma)](#setGamma-float-) | Imposta il valore gamma per la categoria predefinita. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Imposta il valore gamma per una categoria specificata. |
| [clearGamma()](#clearGamma--) | Disabilita la correzione gamma per la categoria predefinita. |
| [clearGamma(int type)](#clearGamma-int-) | Disabilita la correzione gamma per una categoria specificata. |
| [setNoOp()](#setNoOp--) | Disattiva la regolazione del colore per la categoria predefinita. |
| [setNoOp(int type)](#setNoOp-int-) | Disattiva la regolazione del colore per una categoria specificata. |
| [clearNoOp()](#clearNoOp--) | Cancella l'impostazione NoOp per la categoria predefinita. |
| [clearNoOp(int type)](#clearNoOp-int-) | Cancella l'impostazione NoOp per una categoria specificata. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Imposta la chiave colore per la categoria predefinita. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Imposta la chiave colore (intervallo di trasparenza) per una categoria specificata. |
| [clearColorKey()](#clearColorKey--) | Cancella la chiave colore (intervallo di trasparenza) per la categoria predefinita. |
| [clearColorKey(int type)](#clearColorKey-int-) | Cancella la chiave colore (intervallo di trasparenza) per una categoria specificata. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Imposta il canale di output CMYK (ciano-magenta-giallo-nero) per la categoria predefinita. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Imposta il canale di output CMYK (ciano-magenta-giallo-nero) per una categoria specificata. |
| [clearOutputChannel()](#clearOutputChannel--) | Cancella l'impostazione del canale di output CMYK (ciano-magenta-giallo-nero) per la categoria predefinita. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Cancella l'impostazione del canale di output (ciano-magenta-giallo-nero) per una categoria specificata. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Imposta il file del profilo colore del canale di output per la categoria predefinita. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Imposta il file del profilo colore del canale di output per una categoria specificata. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Cancella l'impostazione del profilo colore del canale di output per la categoria predefinita. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Cancella l'impostazione del profilo colore del canale di output per una categoria specificata. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---) | Imposta la tabella di rimappatura colore per la categoria predefinita. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-) | Imposta la tabella di rimappatura colore per una categoria specificata. |
| [clearRemapTable()](#clearRemapTable--) | Cancella la tabella di rimappatura colore per la categoria predefinita. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Cancella la tabella di rimappatura colore per una categoria specificata. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---) | Imposta la tabella di rimappatura colore per la categoria pennello. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Cancella la tabella di rimappatura colore del pennello di questo oggetto [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [setWrapMode(int mode)](#setWrapMode-int-) | Imposta la modalità di avvolgimento utilizzata per decidere come ripetere una texture su una forma o ai bordi della forma. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.drawing.Color-) | Imposta la modalità di avvolgimento e il colore utilizzati per decidere come ripetere una texture su una forma o ai bordi della forma. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.drawing.Color-boolean-) | Imposta la modalità di avvolgimento e il colore utilizzati per decidere come ripetere una texture su una forma o ai bordi della forma. |
| [getAdjustedPalette(ColorPalette palette, int type)](#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-) | Regola i colori in una tavolozza in base alle impostazioni di regolazione di una categoria specificata. |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Inizializza una nuova istanza della classe [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### dispose() {#dispose--}
```
public void dispose()
```


Rilascia tutte le risorse utilizzate da questo oggetto [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia esatta di questo oggetto [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

**Returns:**
java.lang.Object - L'oggetto [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) creato da questa classe, convertito in un oggetto.
### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Imposta la matrice di correzione del colore per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice di regolazione colore. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Imposta la matrice di correzione del colore per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice di regolazione colore. |
| flags | int | Un elemento di [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) che specifica il tipo di immagine e colore che saranno influenzati dalla matrice di regolazione colore. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Imposta la matrice di correzione del colore per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice di regolazione colore. |
| mode | int | Un elemento di [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) che specifica il tipo di immagine e colore che saranno influenzati dalla matrice di regolazione colore. |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale la matrice di regolazione colore è impostata. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Cancella la matrice di regolazione del colore per la categoria predefinita.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Cancella la matrice di regolazione del colore per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale la matrice di regolazione colore è cancellata. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice di regolazione colore. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice di regolazione in scala di grigi. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice di regolazione colore. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice di regolazione in scala di grigi. |
| flags | int | Un elemento di [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) che specifica il tipo di immagine e colore che saranno influenzati dalle matrici di regolazione colore e in scala di grigi. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice di regolazione colore. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice di regolazione in scala di grigi. |
| mode | int | Un elemento di [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) che specifica il tipo di immagine e colore che saranno influenzati dalle matrici di regolazione colore e in scala di grigi. |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale le matrici di regolazione colore e in scala di grigi sono impostate. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Imposta la soglia (intervallo di trasparenza) per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| soglia | float | Un numero reale che specifica il valore di soglia. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Imposta la soglia (intervallo di trasparenza) per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| soglia | float | Un valore di soglia da 0,0 a 1,0 utilizzato come punto di interruzione per ordinare i colori che saranno mappati a un valore massimo o minimo. |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale la soglia colore è impostata. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Cancella il valore della soglia per la categoria predefinita.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Cancella il valore della soglia per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale la soglia è cancellata. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Imposta il valore gamma per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gamma | float | Il valore di correzione gamma. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Imposta il valore gamma per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gamma | float | Il valore di correzione gamma. |
| type | int | Un elemento dell'enumerazione [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale è impostato il valore gamma. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Disabilita la correzione gamma per la categoria predefinita.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Disabilita la correzione gamma per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale la correzione gamma è disabilitata. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Disattiva la regolazione del colore per la categoria predefinita. È possibile chiamare il metodo [.clearNoOp](../../null/\#clearNoOp) per ripristinare le impostazioni di regolazione del colore presenti prima della chiamata al metodo [.setNoOp](../../null/\#setNoOp).

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Disattiva la regolazione del colore per una categoria specificata. È possibile chiamare il metodo [.clearNoOp](../../null/\#clearNoOp) per ripristinare le impostazioni di regolazione del colore presenti prima della chiamata al metodo [.setNoOp](../../null/\#setNoOp).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale la correzione del colore è disattivata. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Cancella l'impostazione NoOp per la categoria predefinita.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Cancella l'impostazione NoOp per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale l'impostazione NoOp viene cancellata. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Imposta la chiave colore per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | Il valore basso della chiave colore. |
| colorHigh | [Color](../../com.aspose.drawing/color) | Il valore alto della chiave colore. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Imposta la chiave colore (intervallo di trasparenza) per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | Il valore basso della chiave colore. |
| colorHigh | [Color](../../com.aspose.drawing/color) | Il valore alto della chiave colore. |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale la chiave colore è impostata. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Cancella la chiave colore (intervallo di trasparenza) per la categoria predefinita.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Cancella la chiave colore (intervallo di trasparenza) per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale la chiave colore viene cancellata. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Imposta il canale di output CMYK (ciano-magenta-giallo-nero) per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flags | int | Un elemento di [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) che specifica il canale di output. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Imposta il canale di output CMYK (ciano-magenta-giallo-nero) per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flags | int | Un elemento di [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) che specifica il canale di output. |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale il canale di output è impostato. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Cancella l'impostazione del canale di output CMYK (ciano-magenta-giallo-nero) per la categoria predefinita.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Cancella l'impostazione del canale di output (ciano-magenta-giallo-nero) per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale l'impostazione del canale di output viene cancellata. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Imposta il file del profilo colore del canale di output per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Il percorso di un file di profilo colore. Se il file di profilo colore si trova nella directory %SystemRoot%\\System32\\Spool\\Drivers\\Color, questo parametro può essere il nome del file. Altrimenti, il parametro deve essere il percorso completo. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Imposta il file del profilo colore del canale di output per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Il percorso di un file di profilo colore. Se il file di profilo colore si trova nella directory %SystemRoot%\\System32\\Spool\\Drivers\\Color, questo parametro può essere il nome del file. Altrimenti, il parametro deve essere il percorso completo. |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale è impostato il file di profilo colore del canale di output. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Cancella l'impostazione del profilo colore del canale di output per la categoria predefinita.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Cancella l'impostazione del profilo colore del canale di output per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale l'impostazione del profilo del canale di output viene cancellata. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Imposta la tabella di rimappatura colore per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Un array di coppie di colori di tipo [ColorMap](../../com.aspose.drawing.imaging/colormap). Ogni coppia di colori contiene un colore esistente (il primo valore) e il colore a cui verrà mappato (il secondo valore). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Imposta la tabella di rimappatura colore per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Un array di coppie di colori di tipo [ColorMap](../../com.aspose.drawing.imaging/colormap). Ogni coppia di colori contiene un colore esistente (il primo valore) e il colore a cui verrà mappato (il secondo valore). |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale la tabella di rimappatura colore è impostata. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Cancella la tabella di rimappatura colore per la categoria predefinita.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Cancella la tabella di rimappatura colore per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria per la quale la tabella di rimappatura viene cancellata. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Imposta la tabella di rimappatura colore per la categoria pennello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Un array di oggetti [ColorMap](../../com.aspose.drawing.imaging/colormap). |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Cancella la tabella di rimappatura colore del pennello di questo oggetto [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Imposta la modalità di avvolgimento utilizzata per decidere come ripetere una texture su una forma, o ai bordi della forma. Una texture viene ripetuta su una forma per riempirla quando la texture è più piccola della forma da riempire.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mode | int | Un elemento di [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) che specifica come le copie ripetute di un'immagine vengono utilizzate per riempire un'area. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.drawing.Color-}
```
public void setWrapMode(int mode, Color color)
```


Imposta la modalità di avvolgimento e il colore usati per decidere come ripetere una texture su una forma, o ai bordi della forma. Una texture viene ripetuta su una forma per riempirla quando la texture è più piccola della forma da riempire.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mode | int | Un elemento di [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) che specifica come le copie ripetute di un'immagine vengono utilizzate per riempire un'area. |
| color | [Color](../../com.aspose.drawing/color) | Un oggetto [Color](../../com.aspose.drawing/color) che specifica il colore dei pixel al di fuori di un'immagine renderizzata. Questo colore è visibile se il parametro mode è impostato su `WrapMode.Clamp` e il rettangolo di origine passato a `Graphics.DrawImage` è più grande dell'immagine stessa. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.drawing.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Imposta la modalità di avvolgimento e il colore usati per decidere come ripetere una texture su una forma, o ai bordi della forma. Una texture viene ripetuta su una forma per riempirla quando la texture è più piccola della forma da riempire.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mode | int | Un elemento di [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) che specifica come le copie ripetute di un'immagine vengono utilizzate per riempire un'area. |
| color | [Color](../../com.aspose.drawing/color) | Un oggetto colore che specifica il colore dei pixel al di fuori di un'immagine renderizzata. Questo colore è visibile se il parametro mode è impostato su `WrapMode.Clamp` e il rettangolo di origine passato a `Graphics.DrawImage` è più grande dell'immagine stessa. |
| blocco | boolean | Questo parametro non ha alcun effetto. Impostalo su false. |

### getAdjustedPalette(ColorPalette palette, int type) {#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-}
```
public void getAdjustedPalette(ColorPalette palette, int type)
```


Regola i colori in una tavolozza in base alle impostazioni di regolazione di una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| palette | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) | Una [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) che in ingresso contiene la tavolozza da regolare e in uscita contiene la tavolozza regolata. |
| type | int | Un elemento di [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) che specifica la categoria le cui impostazioni di regolazione saranno applicate alla tavolozza. |

