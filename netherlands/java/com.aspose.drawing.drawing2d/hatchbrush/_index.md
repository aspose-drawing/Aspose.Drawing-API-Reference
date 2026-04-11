---
title: HatchBrush
second_title: Aspose.Drawing voor Java API-referentie
description: Definieert een rechthoekige penseel met een hatch-stijl, een voorgrondkleur en een achtergrondkleur.
type: docs
weight: 26
url: /nl/java/com.aspose.drawing.drawing2d/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class HatchBrush extends Brush
```

Definieert een rechthoekige penseel met een hatch-stijl, een voorgrondkleur en een achtergrondkleur. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [HatchBrush(int hatchstyle, Color foreColor)](#HatchBrush-int-com.aspose.drawing.Color-) | Initialiseert een nieuw exemplaar van de [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) klasse met de opgegeven `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) enumeratie en voorgrondkleur. |
| [HatchBrush(int hatchstyle, Color foreColor, Color backColor)](#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Initialiseert een nieuw exemplaar van de [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) klasse met de opgegeven `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) enumeratie, voorgrondkleur en achtergrondkleur. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHatchStyle()](#getHatchStyle--) | Haalt de hatch-stijl op van dit [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object. |
| [getForegroundColor()](#getForegroundColor--) | Haalt de kleur op van de hatch-lijnen die door dit [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object worden getekend. |
| [getBackgroundColor()](#getBackgroundColor--) | Haalt de kleur op van de ruimtes tussen de hatch-lijnen die door dit [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object worden getekend. |
| [deepClone()](#deepClone--) | Maakt een exacte kopie van dit [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object. |
### HatchBrush(int hatchstyle, Color foreColor) {#HatchBrush-int-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor)
```


Initialiseert een nieuw exemplaar van de [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) klasse met de opgegeven `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) enumeratie en voorgrondkleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hatchstyle | int | Een van de `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) waarden die het patroon vertegenwoordigt dat door dit [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) wordt getekend. |
| foreColor | [Color](../../com.aspose.drawing/color) | De [Color](../../com.aspose.drawing/color) structuur die de kleur van de door dit [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) getekende lijnen vertegenwoordigt. |

### HatchBrush(int hatchstyle, Color foreColor, Color backColor) {#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor, Color backColor)
```


Initialiseert een nieuw exemplaar van de [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) klasse met de opgegeven `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) enumeratie, voorgrondkleur en achtergrondkleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hatchstyle | int | Een van de `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) waarden die het patroon vertegenwoordigt dat door dit [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) wordt getekend. |
| foreColor | [Color](../../com.aspose.drawing/color) | De [Color](../../com.aspose.drawing/color) structuur die de kleur van de door dit [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) getekende lijnen vertegenwoordigt. |
| backColor | [Color](../../com.aspose.drawing/color) | De [Color](../../com.aspose.drawing/color) structuur die de kleur van de ruimtes tussen de door dit [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) getekende lijnen vertegenwoordigt. |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Haalt de hatch-stijl op van dit [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.

**Returns:**
int - de hatch-stijl van dit [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Haalt de kleur op van de hatch-lijnen die door dit [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object worden getekend.

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Haalt de kleur op van de ruimtes tussen de hatch-lijnen die door dit [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object worden getekend.

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of spaces between the hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Maakt een exacte kopie van dit [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.

**Returns:**
java.lang.Object - De [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) die deze methode maakt, gecast als een object.
