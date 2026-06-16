---
title: ColorPalette
second_title: Aspose.Drawing für Java API-Referenz
description: Definiert ein Array von Farben, das eine Farbpalette bildet.
type: docs
weight: 16
url: /de/java/com.aspose.drawing.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPalette
```

Definiert ein Array von Farben, die eine Farbpalette bilden. Die Farben sind 32‑Bit‑ARGB‑Farben. Nicht vererbbar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ColorPalette(int count)](#ColorPalette-int-) | Initialisiert eine neue Instanz der `ColorPalette`‑Klasse und IsCompactPalette ist false. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEntries()](#getEntries--) | Ruft ein Array von `com.aspose.drawing.Color`‑Strukturen ab. |
| [isCompactPalette()](#isCompactPalette--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob eine kompakte Palette verwendet wird. |
| [getFlags()](#getFlags--) |  |
| [setFlags(int flags)](#setFlags-int-) |  |
| [setEntries(int i, Color color)](#setEntries-int-com.aspose.drawing.Color-) |  |
### ColorPalette(int count) {#ColorPalette-int-}
```
public ColorPalette(int count)
```


Initialisiert eine neue Instanz der `ColorPalette`‑Klasse und IsCompactPalette ist false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| count | int | Die Einträge der Farbpalette. |

### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Ruft ein Array von `com.aspose.drawing.Color`‑Strukturen ab.

**Returns:**
com.aspose.drawing.Color[] – Die Einträge. Das Array von `com.aspose.drawing.Color`‑Strukturen, die diese `Aspose.Imaging.ColorPalette` bilden.
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob eine kompakte Palette verwendet wird.

**Returns:**
boolean – `true`, wenn eine kompakte Palette verwendet wird; andernfalls `false`.

Eine kompakte Palette bedeutet, dass das Bild nur die angegebenen Paletteneinträge enthält, wenn dies möglich ist – mit anderen Worten, das Bild wird kompakter und belegt weniger Speicher; andernfalls gibt es 2^BitsPerPixel‑Einträge und das Bild reserviert mehr Platz für alle möglichen Paletteneinträge. Das Setzen dieses Wertes auf true und das Ändern von Paletteneinträgen kann zu Leistungseinbußen führen, da Datenbewegungen auftreten können, daher sollte es vorsichtig verwendet werden.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| flags | int |  |

### setEntries(int i, Color color) {#setEntries-int-com.aspose.drawing.Color-}
```
public void setEntries(int i, Color color)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | int |  |
| color | [Color](../../com.aspose.drawing/color) |  |

