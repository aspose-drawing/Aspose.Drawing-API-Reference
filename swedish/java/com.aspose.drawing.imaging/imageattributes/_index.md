---
title: ImageAttributes
second_title: Aspose.Drawing för Java API‑referens
description: Innehåller information om hur bitmap- och metafilfärger manipuleras under rendering.
type: docs
weight: 24
url: /sv/java/com.aspose.drawing.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class ImageAttributes implements System.IDisposable
```

Innehåller information om hur bitmap- och metafilfärger manipuleras under rendering.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Initierar en ny instans av klassen [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [dispose()](#dispose--) | Frigör alla resurser som används av detta [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes)-objekt. |
| [deepClone()](#deepClone--) | Skapar en exakt kopia av detta [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes)-objekt. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Ställer in färgjusteringsmatrisen för standardkategorin. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Ställer in färgjusteringsmatrisen för standardkategorin. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Ställer in färgjusteringsmatrisen för en specificerad kategori. |
| [clearColorMatrix()](#clearColorMatrix--) | Rensar färgjusteringsmatrisen för standardkategorin. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Rensar färgjusteringsmatrisen för en specificerad kategori. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för standardkategorin. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för standardkategorin. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för en specificerad kategori. |
| [setThreshold(float threshold)](#setThreshold-float-) | Ställer in tröskelvärdet (transparentintervall) för standardkategorin. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Ställer in tröskelvärdet (transparentintervall) för en specificerad kategori. |
| [clearThreshold()](#clearThreshold--) | Rensar tröskelvärdet för standardkategorin. |
| [clearThreshold(int type)](#clearThreshold-int-) | Rensar tröskelvärdet för en specificerad kategori. |
| [setGamma(float gamma)](#setGamma-float-) | Ställer in gamma-värdet för standardkategorin. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Ställer in gamma-värdet för en specificerad kategori. |
| [clearGamma()](#clearGamma--) | Inaktiverar gamma-korrigering för standardkategorin. |
| [clearGamma(int type)](#clearGamma-int-) | Inaktiverar gamma-korrigering för en specificerad kategori. |
| [setNoOp()](#setNoOp--) | Stänger av färgjustering för standardkategorin. |
| [setNoOp(int type)](#setNoOp-int-) | Stänger av färgjustering för en specificerad kategori. |
| [clearNoOp()](#clearNoOp--) | Rensar NoOp-inställningen för standardkategorin. |
| [clearNoOp(int type)](#clearNoOp-int-) | Rensar NoOp-inställningen för en specificerad kategori. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Ställer in färgnyckeln för standardkategorin. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Ställer in färgnyckeln (transparentintervall) för en specificerad kategori. |
| [clearColorKey()](#clearColorKey--) | Rensar färgnyckeln (transparentintervall) för standardkategorin. |
| [clearColorKey(int type)](#clearColorKey-int-) | Rensar färgnyckeln (transparentintervall) för en specificerad kategori. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Ställer in CMYK (cyan-magenta-gul-svart) utgångskanal för standardkategorin. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Ställer in CMYK (cyan-magenta-gul-svart) utgångskanal för en specificerad kategori. |
| [clearOutputChannel()](#clearOutputChannel--) | Rensar CMYK (cyan-magenta-gul-svart) utgångskanalinställning för standardkategorin. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Rensar (cyan-magenta-gul-svart) utgångskanalinställning för en specificerad kategori. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Ställer in färgprofilfilen för utgångskanalen för standardkategorin. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Ställer in färgprofilfilen för utgångskanalen för en angiven kategori. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Rensar inställningen för färgprofil för utgångskanalen för standardkategorin. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Rensar inställningen för färgprofil för utgångskanalen för en angiven kategori. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---) | Ställer in färg‑omkartningstabellen för standardkategorin. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-) | Ställer in färg‑omkartningstabellen för en angiven kategori. |
| [clearRemapTable()](#clearRemapTable--) | Rensar färg‑omkartningstabellen för standardkategorin. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Rensar färg‑omkartningstabellen för en angiven kategori. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---) | Ställer in färg‑omkartningstabellen för penselkategorin. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Rensar penselns färg‑omkartningstabell för detta [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes)-objekt. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Ställer in omslagsläget som används för att avgöra hur en textur ska tileas över en form eller vid formgränser. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.drawing.Color-) | Ställer in omslagsläget och färgen som används för att avgöra hur en textur ska tileas över en form eller vid formgränser. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.drawing.Color-boolean-) | Ställer in omslagsläget och färgen som används för att avgöra hur en textur ska tileas över en form eller vid formgränser. |
| [getAdjustedPalette(ColorPalette palette, int type)](#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-) | Justera färgerna i en palett enligt justeringsinställningarna för en angiven kategori. |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Initierar en ny instans av klassen [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### dispose() {#dispose--}
```
public void dispose()
```


Frigör alla resurser som används av detta [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes)-objekt.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar en exakt kopia av detta [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes)-objekt.

**Returns:**
java.lang.Object – Det [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes)-objekt som denna klass skapar, kastat som ett objekt.
### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Ställer in färgjusteringsmatrisen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Färgjusteringsmatrisen. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Ställer in färgjusteringsmatrisen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Färgjusteringsmatrisen. |
| flags | int | Ett element av [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) som specificerar bild- och färgtypen som kommer att påverkas av färgjusteringsmatrisen. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Ställer in färgjusteringsmatrisen för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Färgjusteringsmatrisen. |
| mode | int | Ett element av [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) som specificerar bild- och färgtypen som kommer att påverkas av färgjusteringsmatrisen. |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken färgjusteringsmatrisen är inställd. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Rensar färgjusteringsmatrisen för standardkategorin.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Rensar färgjusteringsmatrisen för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken färgjusteringsmatrisen rensas. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Färgjusteringsmatrisen. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Gråskala‑justeringsmatrisen. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Färgjusteringsmatrisen. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Gråskala‑justeringsmatrisen. |
| flags | int | Ett element av [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) som specificerar bild- och färgtypen som kommer att påverkas av färgjusterings‑ och gråskalajusteringsmatriserna. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Färgjusteringsmatrisen. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Gråskala‑justeringsmatrisen. |
| mode | int | Ett element av [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) som specificerar bild- och färgtypen som kommer att påverkas av färgjusterings‑ och gråskalajusteringsmatriserna. |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken färgjusterings‑ och gråskalajusteringsmatriserna är inställda. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Ställer in tröskelvärdet (transparentintervall) för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tröskel | flyttal | Ett reellt tal som specificerar tröskelvärdet. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Ställer in tröskelvärdet (transparentintervall) för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tröskel | flyttal | Ett tröskelvärde från 0,0 till 1,0 som används som brytpunkt för att sortera färger som kommer att mappas till antingen ett maximalt eller ett minimalt värde. |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken färgtröskeln är inställd. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Rensar tröskelvärdet för standardkategorin.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Rensar tröskelvärdet för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken tröskeln rensas. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Ställer in gamma-värdet för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gamma | flyttal | Gamma-korrigeringsvärdet. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Ställer in gamma-värdet för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gamma | flyttal | Gamma-korrigeringsvärdet. |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype)-enumerationen som specificerar den kategori för vilken gamma-värdet sätts. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Inaktiverar gamma-korrigering för standardkategorin.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Inaktiverar gamma-korrigering för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken gamma-korrektion är inaktiverad. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Stänger av färgjustering för standardkategorin. Du kan anropa metoden [.clearNoOp](../../null/\#clearNoOp) för att återställa färgjusteringsinställningarna som fanns innan anropet av metoden [.setNoOp](../../null/\#setNoOp).

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Stänger av färgjustering för en specificerad kategori. Du kan anropa metoden [.clearNoOp](../../null/\#clearNoOp) för att återställa färgjusteringsinställningarna som fanns innan anropet av metoden [.setNoOp](../../null/\#setNoOp).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken färgkorrigering är avstängd. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Rensar NoOp-inställningen för standardkategorin.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Rensar NoOp-inställningen för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken NoOp-inställningen rensas. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Ställer in färgnyckeln för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | Det låga färgnyckelvärdet. |
| colorHigh | [Color](../../com.aspose.drawing/color) | Det höga färgnyckelvärdet. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Ställer in färgnyckeln (transparentintervall) för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | Det låga färgnyckelvärdet. |
| colorHigh | [Color](../../com.aspose.drawing/color) | Det höga färgnyckelvärdet. |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken färgnyckeln sätts. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Rensar färgnyckeln (transparentintervall) för standardkategorin.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Rensar färgnyckeln (transparentintervall) för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken färgnyckeln rensas. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Ställer in CMYK (cyan-magenta-gul-svart) utgångskanal för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| flags | int | Ett element av [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) som specificerar utgångskanalen. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Ställer in CMYK (cyan-magenta-gul-svart) utgångskanal för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| flags | int | Ett element av [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) som specificerar utgångskanalen. |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken utgångskanalen sätts. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Rensar CMYK (cyan-magenta-gul-svart) utgångskanalinställning för standardkategorin.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Rensar (cyan-magenta-gul-svart) utgångskanalinställning för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken utgångskanalsinställningen rensas. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Ställer in färgprofilfilen för utgångskanalen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Sökvägsnamnet för en färgprofilfil. Om färgprofilfilen finns i katalogen %SystemRoot%\\System32\\Spool\\Drivers\\Color kan denna parameter vara filnamnet. Annars måste denna parameter vara det fullständiga sökvägsnamnet. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Ställer in färgprofilfilen för utgångskanalen för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Sökvägsnamnet för en färgprofilfil. Om färgprofilfilen finns i katalogen %SystemRoot%\\System32\\Spool\\Drivers\\Color kan denna parameter vara filnamnet. Annars måste denna parameter vara det fullständiga sökvägsnamnet. |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken utgångskanalens färgprofilfil sätts. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Rensar inställningen för färgprofil för utgångskanalen för standardkategorin.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Rensar inställningen för färgprofil för utgångskanalen för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken utgångskanalens profilinställning rensas. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Ställer in färg‑omkartningstabellen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | En matris av färgpar av typen [ColorMap](../../com.aspose.drawing.imaging/colormap). Varje färgpar innehåller en befintlig färg (det första värdet) och den färg som den kommer att avbildas till (det andra värdet). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Ställer in färg‑omkartningstabellen för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | En matris av färgpar av typen [ColorMap](../../com.aspose.drawing.imaging/colormap). Varje färgpar innehåller en befintlig färg (det första värdet) och den färg som den kommer att avbildas till (det andra värdet). |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken färg-omkartningstabellen sätts. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Rensar färg‑omkartningstabellen för standardkategorin.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Rensar färg‑omkartningstabellen för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori för vilken omkartningstabellen rensas. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Ställer in färg‑omkartningstabellen för penselkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | En matris av [ColorMap](../../com.aspose.drawing.imaging/colormap)-objekt. |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Rensar penselns färg‑omkartningstabell för detta [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes)-objekt.

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Ställer in omslagsläget som används för att bestämma hur en textur ska tileas över en form, eller vid formens gränser. En textur tileas över en form för att fylla i den när texturen är mindre än den form den fyller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | int | Ett element av [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) som specificerar hur upprepade kopior av en bild används för att tilea ett område. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.drawing.Color-}
```
public void setWrapMode(int mode, Color color)
```


Ställer in omslagsläget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formens kanter. En textur tileas över en form för att fylla i den när texturen är mindre än formen den fyller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | int | Ett element av [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) som specificerar hur upprepade kopior av en bild används för att tilea ett område. |
| color | [Color](../../com.aspose.drawing/color) | Ett [Color](../../com.aspose.drawing/color)-objekt som specificerar färgen på pixlar utanför en renderad bild. Denna färg är synlig om lägesparametern är inställd på `WrapMode.Clamp` och källrektangeln som skickas till `Graphics.DrawImage` är större än själva bilden. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.drawing.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Ställer in omslagsläget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formens kanter. En textur tileas över en form för att fylla i den när texturen är mindre än formen den fyller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | int | Ett element av [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) som specificerar hur upprepade kopior av en bild används för att tilea ett område. |
| color | [Color](../../com.aspose.drawing/color) | Ett färgobjekt som specificerar färgen på pixlar utanför en renderad bild. Denna färg är synlig om lägesparametern är inställd på `WrapMode.Clamp` och källrektangeln som skickas till `Graphics.DrawImage` är större än själva bilden. |
| klämma | boolean | Denna parameter har ingen effekt. Sätt den till false. |

### getAdjustedPalette(ColorPalette palette, int type) {#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-}
```
public void getAdjustedPalette(ColorPalette palette, int type)
```


Justera färgerna i en palett enligt justeringsinställningarna för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palette | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) | En [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) som vid inmatning innehåller paletten som ska justeras, och vid utmatning innehåller den justerade paletten. |
| type | int | Ett element av [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) som specificerar den kategori vars justeringsinställningar kommer att tillämpas på paletten. |

