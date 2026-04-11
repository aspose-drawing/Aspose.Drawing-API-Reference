---
title: HatchBrush
second_title: Aspose.Drawing för Java API‑referens
description: Definierar en rektangulär pensel med ett korsningsmönster, en förgrundsfärg och en bakgrundsfärg.
type: docs
weight: 26
url: /sv/java/com.aspose.drawing.drawing2d/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class HatchBrush extends Brush
```

Definierar en rektangulär pensel med ett korsningsmönster, en förgrundsfärg och en bakgrundsfärg. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [HatchBrush(int hatchstyle, Color foreColor)](#HatchBrush-int-com.aspose.drawing.Color-) | Initierar en ny instans av klassen [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) med den angivna `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle))‑enumerationen och förgrundsfärgen. |
| [HatchBrush(int hatchstyle, Color foreColor, Color backColor)](#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Initierar en ny instans av klassen [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) med den angivna `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle))‑enumerationen, förgrundsfärgen och bakgrundsfärgen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHatchStyle()](#getHatchStyle--) | Hämtar korsningsmönstret för detta [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-objekt. |
| [getForegroundColor()](#getForegroundColor--) | Hämtar färgen på korsningslinjerna som ritas av detta [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-objekt. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar färgen på utrymmena mellan korsningslinjerna som ritas av detta [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-objekt. |
| [deepClone()](#deepClone--) | Skapar en exakt kopia av detta [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-objekt. |
### HatchBrush(int hatchstyle, Color foreColor) {#HatchBrush-int-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor)
```


Initierar en ny instans av klassen [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) med den angivna `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle))‑enumerationen och förgrundsfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hatchstyle | int | Ett av `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle))-värdena som representerar mönstret som ritas av detta [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| foreColor | [Color](../../com.aspose.drawing/color) | Den [Color](../../com.aspose.drawing/color)-struktur som representerar färgen på linjerna som ritas av detta [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |

### HatchBrush(int hatchstyle, Color foreColor, Color backColor) {#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor, Color backColor)
```


Initierar en ny instans av klassen [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) med den angivna `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle))‑enumerationen, förgrundsfärgen och bakgrundsfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hatchstyle | int | Ett av `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle))-värdena som representerar mönstret som ritas av detta [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| foreColor | [Color](../../com.aspose.drawing/color) | Den [Color](../../com.aspose.drawing/color)-struktur som representerar färgen på linjerna som ritas av detta [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| backColor | [Color](../../com.aspose.drawing/color) | Den [Color](../../com.aspose.drawing/color)-struktur som representerar färgen på utrymmena mellan linjerna som ritas av detta [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Hämtar korsningsmönstret för detta [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-objekt.

**Returns:**
int – korsningsmönstret för detta [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-objekt.
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Hämtar färgen på korsningslinjerna som ritas av detta [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-objekt.

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar färgen på utrymmena mellan korsningslinjerna som ritas av detta [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-objekt.

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of spaces between the hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar en exakt kopia av detta [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-objekt.

**Returns:**
java.lang.Object – Det [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) som denna metod skapar, kastat som ett objekt.
