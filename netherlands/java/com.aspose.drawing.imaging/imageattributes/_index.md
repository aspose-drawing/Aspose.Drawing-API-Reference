---
title: ImageAttributes
second_title: Aspose.Drawing voor Java API-referentie
description: Bevat informatie over hoe bitmap- en metafile-kleuren worden gemanipuleerd tijdens het renderen.
type: docs
weight: 24
url: /nl/java/com.aspose.drawing.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class ImageAttributes implements System.IDisposable
```

Bevat informatie over hoe bitmap- en metafile-kleuren worden gemanipuleerd tijdens het renderen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Initialiseert een nieuw exemplaar van de [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [dispose()](#dispose--) | Geeft alle bronnen vrij die door dit [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) object worden gebruikt. |
| [deepClone()](#deepClone--) | Maakt een exacte kopie van dit [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) object. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Stelt de kleurcorrectiematrix in voor de standaardcategorie. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Stelt de kleurcorrectiematrix in voor de standaardcategorie. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Stelt de kleurcorrectiematrix in voor een opgegeven categorie. |
| [clearColorMatrix()](#clearColorMatrix--) | Wis de kleur‑aanpassingsmatrix voor de standaardcategorie. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Wis de kleur‑aanpassingsmatrix voor een opgegeven categorie. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Stelt de kleur‑aanpassingsmatrix en de grijswaarden‑aanpassingsmatrix in voor de standaardcategorie. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Stelt de kleur‑aanpassingsmatrix en de grijswaarden‑aanpassingsmatrix in voor de standaardcategorie. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Stelt de kleur‑aanpassingsmatrix en de grijswaarden‑aanpassingsmatrix in voor een opgegeven categorie. |
| [setThreshold(float threshold)](#setThreshold-float-) | Stelt de drempel (transparantiebereik) in voor de standaardcategorie. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Stelt de drempel (transparantiebereik) in voor een opgegeven categorie. |
| [clearThreshold()](#clearThreshold--) | Wis de drempelwaarde voor de standaardcategorie. |
| [clearThreshold(int type)](#clearThreshold-int-) | Wis de drempelwaarde voor een opgegeven categorie. |
| [setGamma(float gamma)](#setGamma-float-) | Stelt de gammawaarde in voor de standaardcategorie. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Stelt de gammawaarde in voor een opgegeven categorie. |
| [clearGamma()](#clearGamma--) | Schakelt gamma‑correctie uit voor de standaardcategorie. |
| [clearGamma(int type)](#clearGamma-int-) | Schakelt gamma‑correctie uit voor een opgegeven categorie. |
| [setNoOp()](#setNoOp--) | Schakelt kleurcorrectie uit voor de standaardcategorie. |
| [setNoOp(int type)](#setNoOp-int-) | Schakelt kleurcorrectie uit voor een opgegeven categorie. |
| [clearNoOp()](#clearNoOp--) | Wis de NoOp‑instelling voor de standaardcategorie. |
| [clearNoOp(int type)](#clearNoOp-int-) | Wis de NoOp‑instelling voor een opgegeven categorie. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Stelt de kleurensleutel in voor de standaardcategorie. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Stelt de kleurensleutel (transparantiebereik) in voor een opgegeven categorie. |
| [clearColorKey()](#clearColorKey--) | Wis de kleurensleutel (transparantiebereik) voor de standaardcategorie. |
| [clearColorKey(int type)](#clearColorKey-int-) | Wis de kleurensleutel (transparantiebereik) voor een opgegeven categorie. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Stelt het CMYK (cyaan‑magenta‑geel‑zwart) uitvoerkanaal in voor de standaardcategorie. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Stelt het CMYK (cyaan‑magenta‑geel‑zwart) uitvoerkanaal in voor een opgegeven categorie. |
| [clearOutputChannel()](#clearOutputChannel--) | Wis de CMYK (cyaan‑magenta‑geel‑zwart) uitvoerkanaalinstelling voor de standaardcategorie. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Wis de (cyaan‑magenta‑geel‑zwart) uitvoerkanaalinstelling voor een opgegeven categorie. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Stelt het kleurprofielbestand van het uitvoerkanaal in voor de standaardcategorie. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Stelt het kleurprofielbestand van het uitvoerkanaal in voor een opgegeven categorie. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Wis de kleurprofielinstelling van het uitvoerkanaal voor de standaardcategorie. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Wis de kleurprofielinstelling van het uitvoerkanaal voor een opgegeven categorie. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---) | Stelt de kleurherkaartabel in voor de standaardcategorie. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-) | Stelt de kleurherkaartabel in voor een opgegeven categorie. |
| [clearRemapTable()](#clearRemapTable--) | Wis de kleurherkaartabel voor de standaardcategorie. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Wis de kleurherkaartabel voor een opgegeven categorie. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---) | Stelt de kleurherkaartabel in voor de penseelcategorie. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Wis de kleurherkaartabel van de penseel van dit [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) object. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Stelt de wrap-modus in die wordt gebruikt om te bepalen hoe een textuur over een vorm wordt getegeld, of bij vormranden. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.drawing.Color-) | Stelt de wrap-modus en kleur in die worden gebruikt om te bepalen hoe een textuur over een vorm wordt getegeld, of bij vormranden. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.drawing.Color-boolean-) | Stelt de wrap-modus en kleur in die worden gebruikt om te bepalen hoe een textuur over een vorm wordt getegeld, of bij vormranden. |
| [getAdjustedPalette(ColorPalette palette, int type)](#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-) | Past de kleuren in een palet aan volgens de aanpassingsinstellingen van een opgegeven categorie. |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Initialiseert een nieuw exemplaar van de [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) klasse.

### dispose() {#dispose--}
```
public void dispose()
```


Geeft alle bronnen vrij die door dit [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) object worden gebruikt.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Maakt een exacte kopie van dit [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) object.

**Returns:**
java.lang.Object - Het [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) object dat deze klasse maakt, gecast als een object.
### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Stelt de kleurcorrectiematrix in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | De kleuraanpassingsmatrix. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Stelt de kleurcorrectiematrix in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | De kleuraanpassingsmatrix. |
| flags | int | Een element van [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) dat het type afbeelding en kleur specificeert dat wordt beïnvloed door de kleuraanpassingsmatrix. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Stelt de kleurcorrectiematrix in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | De kleuraanpassingsmatrix. |
| mode | int | Een element van [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) dat het type afbeelding en kleur specificeert dat wordt beïnvloed door de kleuraanpassingsmatrix. |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor de kleuraanpassingsmatrix is ingesteld. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Wis de kleur‑aanpassingsmatrix voor de standaardcategorie.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Wis de kleur‑aanpassingsmatrix voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor de kleuraanpassingsmatrix wordt gewist. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Stelt de kleur‑aanpassingsmatrix en de grijswaarden‑aanpassingsmatrix in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | De kleuraanpassingsmatrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | De grijswaardenaanpassingsmatrix. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Stelt de kleur‑aanpassingsmatrix en de grijswaarden‑aanpassingsmatrix in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | De kleuraanpassingsmatrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | De grijswaardenaanpassingsmatrix. |
| flags | int | Een element van [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) dat het type afbeelding en kleur specificeert dat wordt beïnvloed door de kleur- en grijswaardenaanpassingsmatrixen. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Stelt de kleur‑aanpassingsmatrix en de grijswaarden‑aanpassingsmatrix in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | De kleuraanpassingsmatrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | De grijswaardenaanpassingsmatrix. |
| mode | int | Een element van [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) dat het type afbeelding en kleur specificeert dat wordt beïnvloed door de kleur- en grijswaardenaanpassingsmatrixen. |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor de kleur- en grijswaardenaanpassingsmatrixen zijn ingesteld. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Stelt de drempel (transparantiebereik) in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| drempel | float | Een reëel getal dat de drempelwaarde specificeert. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Stelt de drempel (transparantiebereik) in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| drempel | float | Een drempelwaarde van 0.0 tot 1.0 die wordt gebruikt als een breekpunt om kleuren te sorteren die worden gemapt naar een maximale of minimale waarde. |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor de kleurdrempel is ingesteld. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Wis de drempelwaarde voor de standaardcategorie.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Wis de drempelwaarde voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor de drempel wordt gewist. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Stelt de gammawaarde in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gamma | float | De gamma-correctiewaarde. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Stelt de gammawaarde in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gamma | float | De gamma-correctiewaarde. |
| type | int | Een element van de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) enumeratie die de categorie specificeert waarvoor de gamma-waarde is ingesteld. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Schakelt gamma‑correctie uit voor de standaardcategorie.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Schakelt gamma‑correctie uit voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor gamma-correctie is uitgeschakeld. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Schakelt kleuraanpassing uit voor de standaardcategorie. Je kunt de [.clearNoOp](../../null/\#clearNoOp) methode aanroepen om de kleuraanpassingsinstellingen te herstellen die van kracht waren vóór de aanroep van de [.setNoOp](../../null/\#setNoOp) methode.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Schakelt kleuraanpassing uit voor een opgegeven categorie. Je kunt de [.clearNoOp](../../null/\#clearNoOp) methode aanroepen om de kleuraanpassingsinstellingen te herstellen die van kracht waren vóór de aanroep van de [.setNoOp](../../null/\#setNoOp) methode.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor kleurcorrectie is uitgeschakeld. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Wis de NoOp‑instelling voor de standaardcategorie.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Wis de NoOp‑instelling voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor de NoOp-instelling wordt gewist. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Stelt de kleurensleutel in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | De lage kleurtoetswaarde. |
| colorHigh | [Color](../../com.aspose.drawing/color) | De hoge kleurtoetswaarde. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Stelt de kleurensleutel (transparantiebereik) in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | De lage kleurtoetswaarde. |
| colorHigh | [Color](../../com.aspose.drawing/color) | De hoge kleurtoetswaarde. |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor de kleurtoets is ingesteld. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Wis de kleurensleutel (transparantiebereik) voor de standaardcategorie.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Wis de kleurensleutel (transparantiebereik) voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor de kleurtoets wordt gewist. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Stelt het CMYK (cyaan‑magenta‑geel‑zwart) uitvoerkanaal in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| flags | int | Een element van [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) dat het uitvoerkanaal specificeert. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Stelt het CMYK (cyaan‑magenta‑geel‑zwart) uitvoerkanaal in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| flags | int | Een element van [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) dat het uitvoerkanaal specificeert. |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor het uitvoerkanaal is ingesteld. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Wis de CMYK (cyaan‑magenta‑geel‑zwart) uitvoerkanaalinstelling voor de standaardcategorie.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Wis de (cyaan‑magenta‑geel‑zwart) uitvoerkanaalinstelling voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor de uitvoerkanaalinstelling wordt gewist. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Stelt het kleurprofielbestand van het uitvoerkanaal in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | De padnaam van een kleurprofielbestand. Als het kleurprofielbestand zich bevindt in de %SystemRoot%\\System32\\Spool\\Drivers\\Color map, kan deze parameter de bestandsnaam zijn. Anders moet deze parameter de volledig gekwalificeerde padnaam zijn. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Stelt het kleurprofielbestand van het uitvoerkanaal in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | De padnaam van een kleurprofielbestand. Als het kleurprofielbestand zich bevindt in de %SystemRoot%\\System32\\Spool\\Drivers\\Color map, kan deze parameter de bestandsnaam zijn. Anders moet deze parameter de volledig gekwalificeerde padnaam zijn. |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor het kleurprofielbestand van het uitvoerkanaal is ingesteld. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Wis de kleurprofielinstelling van het uitvoerkanaal voor de standaardcategorie.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Wis de kleurprofielinstelling van het uitvoerkanaal voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor de uitvoerkanaalprofielinstelling wordt gewist. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Stelt de kleurherkaartabel in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Een array van kleurparen van het type [ColorMap](../../com.aspose.drawing.imaging/colormap). Elk kleurpaar bevat een bestaande kleur (de eerste waarde) en de kleur waarnaar deze wordt gemapt (de tweede waarde). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Stelt de kleurherkaartabel in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Een array van kleurparen van het type [ColorMap](../../com.aspose.drawing.imaging/colormap). Elk kleurpaar bevat een bestaande kleur (de eerste waarde) en de kleur waarnaar deze wordt gemapt (de tweede waarde). |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor de kleur-herkaartabel is ingesteld. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Wis de kleurherkaartabel voor de standaardcategorie.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Wis de kleurherkaartabel voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvoor de herkaartabel wordt gewist. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Stelt de kleurherkaartabel in voor de penseelcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Een array van [ColorMap](../../com.aspose.drawing.imaging/colormap) objecten. |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Wis de kleurherkaartabel van de penseel van dit [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) object.

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Stelt de wrap-modus in die wordt gebruikt om te bepalen hoe een textuur over een vorm wordt getegeld, of bij vormranden. Een textuur wordt over een vorm getegeld om deze op te vullen wanneer de textuur kleiner is dan de vorm die wordt gevuld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mode | int | Een element van [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) dat specificeert hoe herhaalde kopieën van een afbeelding worden gebruikt om een gebied te tegelen. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.drawing.Color-}
```
public void setWrapMode(int mode, Color color)
```


Stelt de wrap-modus en kleur in die worden gebruikt om te bepalen hoe een textuur over een vorm wordt getegeld, of op de randen van de vorm. Een textuur wordt over een vorm getegeld om deze op te vullen wanneer de textuur kleiner is dan de vorm die wordt gevuld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mode | int | Een element van [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) dat specificeert hoe herhaalde kopieën van een afbeelding worden gebruikt om een gebied te tegelen. |
| color | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color) object dat de kleur van pixels buiten een gerenderde afbeelding specificeert. Deze kleur is zichtbaar als de modusparameter is ingesteld op `WrapMode.Clamp` en de bronrechthoek die aan `Graphics.DrawImage` wordt doorgegeven groter is dan de afbeelding zelf. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.drawing.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Stelt de wrap-modus en kleur in die worden gebruikt om te bepalen hoe een textuur over een vorm wordt getegeld, of op de randen van de vorm. Een textuur wordt over een vorm getegeld om deze op te vullen wanneer de textuur kleiner is dan de vorm die wordt gevuld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mode | int | Een element van [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) dat specificeert hoe herhaalde kopieën van een afbeelding worden gebruikt om een gebied te tegelen. |
| color | [Color](../../com.aspose.drawing/color) | Een kleurobject dat de kleur van pixels buiten een gerenderde afbeelding specificeert. Deze kleur is zichtbaar als de modusparameter is ingesteld op `WrapMode.Clamp` en de bronrechthoek die aan `Graphics.DrawImage` wordt doorgegeven groter is dan de afbeelding zelf. |
| clamp | boolean | Deze parameter heeft geen effect. Stel deze in op false. |

### getAdjustedPalette(ColorPalette palette, int type) {#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-}
```
public void getAdjustedPalette(ColorPalette palette, int type)
```


Past de kleuren in een palet aan volgens de aanpassingsinstellingen van een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| palette | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) | Een [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) die bij invoer de aan te passen palet bevat, en bij uitvoer het aangepaste palet bevat. |
| type | int | Een element van [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) dat de categorie specificeert waarvan de aanpassingsinstellingen op het palet worden toegepast. |

