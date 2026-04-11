---
title: ColorPalette
second_title: Aspose.Drawing för Java API‑referens
description: Definierar en array av färger som utgör en färgpalett.
type: docs
weight: 16
url: /sv/java/com.aspose.drawing.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPalette
```

Definierar en array av färger som utgör en färgpalett. Färgerna är 32-bitars ARGB-färger. Ej ärftlig.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ColorPalette(int count)](#ColorPalette-int-) | Initierar en ny instans av klassen `ColorPalette` och IsCompactPalette är falskt. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEntries()](#getEntries--) | Hämtar en array av `com.aspose.drawing.Color`-strukturer. |
| [isCompactPalette()](#isCompactPalette--) | Hämtar eller anger ett värde som indikerar om kompakt palett används. |
| [getFlags()](#getFlags--) |  |
| [setFlags(int flags)](#setFlags-int-) |  |
| [setEntries(int i, Color color)](#setEntries-int-com.aspose.drawing.Color-) |  |
### ColorPalette(int count) {#ColorPalette-int-}
```
public ColorPalette(int count)
```


Initierar en ny instans av klassen `ColorPalette` och IsCompactPalette är falskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| count | int | Färgpalettens poster. |

### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Hämtar en array av `com.aspose.drawing.Color`-strukturer.

**Returns:**
com.aspose.drawing.Color[] - Poster. Arrayen av `com.aspose.drawing.Color`-strukturer som utgör denna `Aspose.Imaging.ColorPalette`.
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Hämtar eller anger ett värde som indikerar om kompakt palett används.

**Returns:**
boolean - `true` om kompakt palett används; annars `false`.

Kompakt palett betyder att bilden endast kommer att innehålla de angivna palettposterna om möjligt, med andra ord blir bilden mer kompakt och tar mindre utrymme; annars kommer det att finnas 2^BitsPerPixel poster och bilden kommer att reservera mer utrymme för alla möjliga palettposter. Att sätta detta värde till true och ändra palettposter kan medföra prestandapåverkan eftersom dataförflyttning kan ske, så använd det försiktigt.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| flaggor | int |  |

### setEntries(int i, Color color) {#setEntries-int-com.aspose.drawing.Color-}
```
public void setEntries(int i, Color color)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | int |  |
| color | [Color](../../com.aspose.drawing/color) |  |

