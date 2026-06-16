---
title: ColorPalette
second_title: Aspose.Drawing voor Java API-referentie
description: Definieert een array van kleuren die een kleurenpalet vormen.
type: docs
weight: 16
url: /nl/java/com.aspose.drawing.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPalette
```

Definieert een array van kleuren die een kleurenpalet vormen. De kleuren zijn 32-bit ARGB-kleuren. Niet overerfbaar.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ColorPalette(int count)](#ColorPalette-int-) | Initialiseert een nieuw exemplaar van de `ColorPalette`-klasse en IsCompactPalette is false. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getEntries()](#getEntries--) | Haalt een array op van `com.aspose.drawing.Color`-structuren. |
| [isCompactPalette()](#isCompactPalette--) | Haalt op of stelt een waarde in die aangeeft of een compact palet wordt gebruikt. |
| [getFlags()](#getFlags--) |  |
| [setFlags(int flags)](#setFlags-int-) |  |
| [setEntries(int i, Color color)](#setEntries-int-com.aspose.drawing.Color-) |  |
### ColorPalette(int count) {#ColorPalette-int-}
```
public ColorPalette(int count)
```


Initialiseert een nieuw exemplaar van de `ColorPalette`-klasse en IsCompactPalette is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| count | int | De kleurenpalet-items. |

### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Haalt een array op van `com.aspose.drawing.Color`-structuren.

**Returns:**
com.aspose.drawing.Color[] - De items. De array van `com.aspose.drawing.Color`-structuur die dit `Aspose.Imaging.ColorPalette` vormt.
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Haalt op of stelt een waarde in die aangeeft of een compact palet wordt gebruikt.

**Returns:**
boolean - `true` als een compact palet wordt gebruikt; anders `false`.

Een compact palet betekent dat de afbeelding alleen de gespecificeerde paletitems bevat, indien mogelijk; met andere woorden wordt de afbeelding compacter en neemt minder ruimte in beslag. Anders zullen er 2^BitsPerPixel items zijn en reserveert de afbeelding meer ruimte voor alle mogelijke paletitems. Het instellen van deze waarde op true en het wijzigen van paletitems kan een prestatiepenalty veroorzaken omdat gegevensverplaatsing kan optreden, dus gebruik het voorzichtig.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| flags | int |  |

### setEntries(int i, Color color) {#setEntries-int-com.aspose.drawing.Color-}
```
public void setEntries(int i, Color color)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | int |  |
| color | [Color](../../com.aspose.drawing/color) |  |

