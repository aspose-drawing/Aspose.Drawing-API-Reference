---
title: ImageAttributes
second_title: Aspose.Drawing für Java API-Referenz
description: Enthält Informationen darüber, wie Bitmap- und Metadatei-Farben während des Renderns manipuliert werden.
type: docs
weight: 24
url: /de/java/com.aspose.drawing.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class ImageAttributes implements System.IDisposable
```

Enthält Informationen darüber, wie Bitmap- und Metadatei-Farben während des Renderns manipuliert werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Initialisiert eine neue Instanz der Klasse [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [dispose()](#dispose--) | Gibt alle von diesem [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes)-Objekt verwendeten Ressourcen frei. |
| [deepClone()](#deepClone--) | Erstellt eine exakte Kopie dieses [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes)-Objekts. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Setzt die Farbkorrekturmatrix für die Standardkategorie. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Setzt die Farbkorrekturmatrix für die Standardkategorie. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Setzt die Farbkorrekturmatrix für eine angegebene Kategorie. |
| [clearColorMatrix()](#clearColorMatrix--) | Löscht die Farbkorrekturmatrix für die Standardkategorie. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Löscht die Farbkorrekturmatrix für eine angegebene Kategorie. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Setzt die Farbkorrekturmatrix und die Graustufen‑Korrekturmatrix für die Standardkategorie. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Setzt die Farbkorrekturmatrix und die Graustufen‑Korrekturmatrix für die Standardkategorie. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Setzt die Farbkorrekturmatrix und die Graustufen‑Korrekturmatrix für eine angegebene Kategorie. |
| [setThreshold(float threshold)](#setThreshold-float-) | Setzt den Schwellenwert (Transparenzbereich) für die Standardkategorie. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Setzt den Schwellenwert (Transparenzbereich) für eine angegebene Kategorie. |
| [clearThreshold()](#clearThreshold--) | Löscht den Schwellenwert für die Standardkategorie. |
| [clearThreshold(int type)](#clearThreshold-int-) | Löscht den Schwellenwert für eine angegebene Kategorie. |
| [setGamma(float gamma)](#setGamma-float-) | Setzt den Gamma‑Wert für die Standardkategorie. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Setzt den Gamma‑Wert für eine angegebene Kategorie. |
| [clearGamma()](#clearGamma--) | Deaktiviert die Gammakorrektur für die Standardkategorie. |
| [clearGamma(int type)](#clearGamma-int-) | Deaktiviert die Gammakorrektur für eine angegebene Kategorie. |
| [setNoOp()](#setNoOp--) | Schaltet die Farbkorrektur für die Standardkategorie aus. |
| [setNoOp(int type)](#setNoOp-int-) | Schaltet die Farbkorrektur für eine angegebene Kategorie aus. |
| [clearNoOp()](#clearNoOp--) | Löscht die NoOp‑Einstellung für die Standardkategorie. |
| [clearNoOp(int type)](#clearNoOp-int-) | Löscht die NoOp‑Einstellung für eine angegebene Kategorie. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Setzt den Farbschlüssel für die Standardkategorie. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Setzt den Farbschlüssel (Transparenzbereich) für eine angegebene Kategorie. |
| [clearColorKey()](#clearColorKey--) | Löscht den Farbschlüssel (Transparenzbereich) für die Standardkategorie. |
| [clearColorKey(int type)](#clearColorKey-int-) | Löscht den Farbschlüssel (Transparenzbereich) für eine angegebene Kategorie. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Setzt den CMYK‑Ausgabekanal (cyan‑magenta‑gelb‑schwarz) für die Standardkategorie. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Setzt den CMYK‑Ausgabekanal (cyan‑magenta‑gelb‑schwarz) für eine angegebene Kategorie. |
| [clearOutputChannel()](#clearOutputChannel--) | Löscht die CMYK‑Ausgabekanal‑Einstellung für die Standardkategorie. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Löscht die (cyan‑magenta‑gelb‑schwarz) Ausgabekanal‑Einstellung für eine angegebene Kategorie. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Setzt die Farbprofil‑Datei des Ausgabekanals für die Standardkategorie. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Legt die Ausgabekanal‑Farbprofildatei für eine bestimmte Kategorie fest. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Löscht die Einstellung des Ausgabekanal‑Farbprofils für die Standardkategorie. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Löscht die Einstellung des Ausgabekanal‑Farbprofils für eine bestimmte Kategorie. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---) | Legt die Farb‑Remap‑Tabelle für die Standardkategorie fest. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-) | Legt die Farb‑Remap‑Tabelle für eine bestimmte Kategorie fest. |
| [clearRemapTable()](#clearRemapTable--) | Löscht die Farb‑Remap‑Tabelle für die Standardkategorie. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Löscht die Farb‑Remap‑Tabelle für eine bestimmte Kategorie. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---) | Legt die Farb‑Remap‑Tabelle für die Pinselkategorie fest. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Löscht die Pinsel‑Farb‑Remap‑Tabelle dieses [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes)-Objekts. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Legt den Wrap‑Modus fest, der verwendet wird, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.drawing.Color-) | Legt den Wrap‑Modus und die Farbe fest, die verwendet werden, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.drawing.Color-boolean-) | Legt den Wrap‑Modus und die Farbe fest, die verwendet werden, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. |
| [getAdjustedPalette(ColorPalette palette, int type)](#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-) | Passt die Farben in einer Palette gemäß den Anpassungseinstellungen einer bestimmten Kategorie an. |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Initialisiert eine neue Instanz der Klasse [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### dispose() {#dispose--}
```
public void dispose()
```


Gibt alle von diesem [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes)-Objekt verwendeten Ressourcen frei.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Erstellt eine exakte Kopie dieses [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes)-Objekts.

**Returns:**
java.lang.Object - Das [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes)-Objekt, das diese Klasse erstellt, als Objekt umgewandelt.
### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Setzt die Farbkorrekturmatrix für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Die Farb‑Anpassungsmatrix. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Setzt die Farbkorrekturmatrix für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Die Farb‑Anpassungsmatrix. |
| flags | int | Ein Element von [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag), das den Bild‑ und Farbtyp angibt, der von der Farb‑Anpassungsmatrix betroffen ist. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Setzt die Farbkorrekturmatrix für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Die Farb‑Anpassungsmatrix. |
| mode | int | Ein Element von [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag), das den Bild‑ und Farbtyp angibt, der von der Farb‑Anpassungsmatrix betroffen ist. |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die die Farb‑Anpassungsmatrix festgelegt wird. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Löscht die Farbkorrekturmatrix für die Standardkategorie.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Löscht die Farbkorrekturmatrix für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die die Farb‑Anpassungsmatrix gelöscht wird. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Setzt die Farbkorrekturmatrix und die Graustufen‑Korrekturmatrix für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Die Farb‑Anpassungsmatrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Die Graustufen‑Anpassungsmatrix. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Setzt die Farbkorrekturmatrix und die Graustufen‑Korrekturmatrix für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Die Farb‑Anpassungsmatrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Die Graustufen‑Anpassungsmatrix. |
| flags | int | Ein Element von [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag), das den Bild‑ und Farbtyp angibt, der von den Farb‑Anpassungs‑ und Graustufen‑Anpassungsmatrizen betroffen ist. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Setzt die Farbkorrekturmatrix und die Graustufen‑Korrekturmatrix für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Die Farb‑Anpassungsmatrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Die Graustufen‑Anpassungsmatrix. |
| mode | int | Ein Element von [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag), das den Bild‑ und Farbtyp angibt, der von den Farb‑Anpassungs‑ und Graustufen‑Anpassungsmatrizen betroffen ist. |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die die Farb‑Anpassungs‑ und Graustufen‑Anpassungsmatrizen festgelegt werden. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Setzt den Schwellenwert (Transparenzbereich) für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schwellenwert | float | Eine reelle Zahl, die den Schwellenwert angibt. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Setzt den Schwellenwert (Transparenzbereich) für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schwellenwert | float | Ein Schwellenwert von 0.0 bis 1.0, der als Trennstelle verwendet wird, um Farben zu sortieren, die entweder einem maximalen oder einem minimalen Wert zugeordnet werden. |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die der Farb‑Schwellenwert festgelegt wird. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Löscht den Schwellenwert für die Standardkategorie.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Löscht den Schwellenwert für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die der Schwellenwert gelöscht wird. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Setzt den Gamma‑Wert für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gamma | float | Der Gamma-Korrekturwert. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Setzt den Gamma‑Wert für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gamma | float | Der Gamma-Korrekturwert. |
| type | int | Ein Element der [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype)-Aufzählung, das die Kategorie angibt, für die der Gamma-Wert festgelegt wird. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Deaktiviert die Gammakorrektur für die Standardkategorie.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Deaktiviert die Gammakorrektur für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die die Gamma-Korrektur deaktiviert ist. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Deaktiviert die Farbkorrektur für die Standardkategorie. Sie können die Methode [.clearNoOp](../../null/\#clearNoOp) aufrufen, um die Farbkorrektureinstellungen wiederherzustellen, die vor dem Aufruf der Methode [.setNoOp](../../null/\#setNoOp) aktiv waren.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Deaktiviert die Farbkorrektur für eine angegebene Kategorie. Sie können die Methode [.clearNoOp](../../null/\#clearNoOp) aufrufen, um die Farbkorrektureinstellungen wiederherzustellen, die vor dem Aufruf der Methode [.setNoOp](../../null/\#setNoOp) aktiv waren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die die Farbkorrektur deaktiviert ist. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Löscht die NoOp‑Einstellung für die Standardkategorie.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Löscht die NoOp‑Einstellung für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die die NoOp-Einstellung zurückgesetzt wird. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Setzt den Farbschlüssel für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | Der niedrige Farbschlüsselwert. |
| colorHigh | [Color](../../com.aspose.drawing/color) | Der hohe Farbschlüsselwert. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Setzt den Farbschlüssel (Transparenzbereich) für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | Der niedrige Farbschlüsselwert. |
| colorHigh | [Color](../../com.aspose.drawing/color) | Der hohe Farbschlüsselwert. |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die der Farbschlüssel festgelegt ist. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Löscht den Farbschlüssel (Transparenzbereich) für die Standardkategorie.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Löscht den Farbschlüssel (Transparenzbereich) für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die der Farbschlüssel zurückgesetzt wird. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Setzt den CMYK‑Ausgabekanal (cyan‑magenta‑gelb‑schwarz) für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| flags | int | Ein Element von [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag), das den Ausgabekanal angibt. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Setzt den CMYK‑Ausgabekanal (cyan‑magenta‑gelb‑schwarz) für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| flags | int | Ein Element von [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag), das den Ausgabekanal angibt. |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die der Ausgabekanal festgelegt ist. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Löscht die CMYK‑Ausgabekanal‑Einstellung für die Standardkategorie.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Löscht die (cyan‑magenta‑gelb‑schwarz) Ausgabekanal‑Einstellung für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die die Ausgabekanal-Einstellung zurückgesetzt wird. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Setzt die Farbprofil‑Datei des Ausgabekanals für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Der Pfadname einer Farbprofildatei. Befindet sich die Farbprofildatei im Verzeichnis %SystemRoot%\\System32\\Spool\\Drivers\\Color, kann dieser Parameter der Dateiname sein. Andernfalls muss dieser Parameter den vollständig qualifizierten Pfadnamen enthalten. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Legt die Ausgabekanal‑Farbprofildatei für eine bestimmte Kategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Der Pfadname einer Farbprofildatei. Befindet sich die Farbprofildatei im Verzeichnis %SystemRoot%\\System32\\Spool\\Drivers\\Color, kann dieser Parameter der Dateiname sein. Andernfalls muss dieser Parameter den vollständig qualifizierten Pfadnamen enthalten. |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die die Farbprofildatei des Ausgabekanals festgelegt ist. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Löscht die Einstellung des Ausgabekanal‑Farbprofils für die Standardkategorie.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Löscht die Einstellung des Ausgabekanal‑Farbprofils für eine bestimmte Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die die Ausgabekanal-Profil-Einstellung zurückgesetzt wird. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Legt die Farb‑Remap‑Tabelle für die Standardkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Ein Array von Farbpaaren vom Typ [ColorMap](../../com.aspose.drawing.imaging/colormap). Jedes Farbpaar enthält eine vorhandene Farbe (den ersten Wert) und die Farbe, auf die sie abgebildet wird (den zweiten Wert). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Legt die Farb‑Remap‑Tabelle für eine bestimmte Kategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Ein Array von Farbpaaren vom Typ [ColorMap](../../com.aspose.drawing.imaging/colormap). Jedes Farbpaar enthält eine vorhandene Farbe (den ersten Wert) und die Farbe, auf die sie abgebildet wird (den zweiten Wert). |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die die Farb-Remap-Tabelle festgelegt ist. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Löscht die Farb‑Remap‑Tabelle für die Standardkategorie.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Löscht die Farb‑Remap‑Tabelle für eine bestimmte Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, für die die Remap-Tabelle zurückgesetzt wird. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Legt die Farb‑Remap‑Tabelle für die Pinselkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Ein Array von [ColorMap](../../com.aspose.drawing.imaging/colormap)-Objekten. |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Löscht die Pinsel‑Farb‑Remap‑Tabelle dieses [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes)-Objekts.

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Legt den Wrap-Modus fest, der bestimmt, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mode | int | Ein Element von [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode), das angibt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.drawing.Color-}
```
public void setWrapMode(int mode, Color color)
```


Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form gekachelt wird, bzw. an Formgrenzen. Eine Textur wird über eine Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mode | int | Ein Element von [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode), das angibt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |
| color | [Color](../../com.aspose.drawing/color) | Ein [Color](../../com.aspose.drawing/color)-Objekt, das die Farbe der Pixel außerhalb eines gerenderten Bildes angibt. Diese Farbe ist sichtbar, wenn der Modusparameter auf `WrapMode.Clamp` gesetzt ist und das an `Graphics.DrawImage` übergebene Quellrechteck größer ist als das Bild selbst. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.drawing.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form gekachelt wird, bzw. an Formgrenzen. Eine Textur wird über eine Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mode | int | Ein Element von [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode), das angibt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |
| color | [Color](../../com.aspose.drawing/color) | Ein Farbobjekt, das die Farbe der Pixel außerhalb eines gerenderten Bildes angibt. Diese Farbe ist sichtbar, wenn der Modusparameter auf `WrapMode.Clamp` gesetzt ist und das an `Graphics.DrawImage` übergebene Quellrechteck größer ist als das Bild selbst. |
| clamp | boolean | Dieser Parameter hat keine Wirkung. Setzen Sie ihn auf false. |

### getAdjustedPalette(ColorPalette palette, int type) {#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-}
```
public void getAdjustedPalette(ColorPalette palette, int type)
```


Passt die Farben in einer Palette gemäß den Anpassungseinstellungen einer bestimmten Kategorie an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| palette | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) | Eine [ColorPalette](../../com.aspose.drawing.imaging/colorpalette), die bei der Eingabe die anzupassende Palette enthält und bei der Ausgabe die angepasste Palette enthält. |
| type | int | Ein Element von [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), das die Kategorie angibt, deren Anpassungseinstellungen auf die Palette angewendet werden. |

