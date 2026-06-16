---
title: PixelFormat
second_title: Aspose.Drawing für Java API-Referenz
description: Gibt das Format der Farbdaten für jedes Pixel im Bild an.
type: docs
weight: 34
url: /de/java/com.aspose.drawing.imaging/pixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PixelFormat extends System.Enum
```

Gibt das Format der Farbdaten für jedes Pixel im Bild an.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Indexed](#Indexed) | Die Pixeldaten enthalten farbindizierte Werte, das bedeutet, dass die Werte ein Index zu Farben in der Systemfarbtabelle sind, anstatt einzelner Farbwerte. |
| [Gdi](#Gdi) | Die Pixeldaten enthalten GDI-Farben. |
| [Alpha](#Alpha) | Die Pixeldaten enthalten Alpha-Werte, die nicht vorab multipliziert sind. |
| [PAlpha](#PAlpha) | Das Pixelformat enthält vorab multiplizierte Alpha-Werte. |
| [Extended](#Extended) | Reservierter Wert. |
| [Canonical](#Canonical) | Das Standard-Pixelformat von 32 Bit pro Pixel. |
| [Undefined](#Undefined) | Das Pixelformat ist undefiniert. |
| [DontCare](#DontCare) | Kein Pixelformat angegeben. |
| [Format1bppIndexed](#Format1bppIndexed) | Gibt an, dass das Pixelformat 1 Bit pro Pixel beträgt und indizierte Farben verwendet. |
| [Format4bppIndexed](#Format4bppIndexed) | Gibt an, dass das Format 4 Bit pro Pixel beträgt, indiziert. |
| [Format8bppIndexed](#Format8bppIndexed) | Gibt an, dass das Format 8 Bit pro Pixel beträgt, indiziert. |
| [Format16bppGrayScale](#Format16bppGrayScale) | Das Pixelformat beträgt 16 Bit pro Pixel. |
| [Format16bppRgb555](#Format16bppRgb555) | Gibt an, dass das Format 16 Bit pro Pixel beträgt; jeweils 5 Bit werden für die roten, grünen und blauen Komponenten verwendet. |
| [Format16bppRgb565](#Format16bppRgb565) | Gibt an, dass das Format 16 Bit pro Pixel beträgt; 5 Bit werden für die rote Komponente, 6 Bit für die grüne Komponente und 5 Bit für die blaue Komponente verwendet. |
| [Format16bppArgb1555](#Format16bppArgb1555) | Das Pixelformat beträgt 16 Bit pro Pixel. |
| [Format24bppRgb](#Format24bppRgb) | Gibt an, dass das Format 24 Bit pro Pixel beträgt; jeweils 8 Bit für die roten, grünen und blauen Komponenten verwendet werden. |
| [Format32bppRgb](#Format32bppRgb) | Gibt an, dass das Format 32 Bit pro Pixel beträgt; jeweils 8 Bit für die roten, grünen und blauen Komponenten verwendet werden. |
| [Format32bppArgb](#Format32bppArgb) | Gibt an, dass das Format 32 Bit pro Pixel beträgt; jeweils 8 Bit für die Alpha-, Rot-, Grün- und Blaukomponenten verwendet werden. |
| [Format32bppPArgb](#Format32bppPArgb) | Gibt an, dass das Format 32 Bit pro Pixel beträgt; jeweils 8 Bit für die Alpha-, Rot-, Grün- und Blaukomponenten verwendet werden. |
| [Format48bppRgb](#Format48bppRgb) | Gibt an, dass das Format 48 Bit pro Pixel beträgt; jeweils 16 Bit für die roten, grünen und blauen Komponenten verwendet werden. |
| [Format64bppArgb](#Format64bppArgb) | Gibt an, dass das Format 64 Bit pro Pixel beträgt; jeweils 16 Bit für die Alpha-, Rot-, Grün- und Blaukomponenten verwendet werden. |
| [Format64bppPArgb](#Format64bppPArgb) | Gibt an, dass das Format 64 Bit pro Pixel beträgt; jeweils 16 Bit für die Alpha-, Rot-, Grün- und Blaukomponenten verwendet werden. |
| [Max](#Max) | Der maximale Wert für diese Aufzählung. |
### Indexed {#Indexed}
```
public static final int Indexed
```


Die Pixeldaten enthalten farbindizierte Werte, das bedeutet, dass die Werte ein Index zu Farben in der Systemfarbtabelle sind, anstatt einzelner Farbwerte.

### Gdi {#Gdi}
```
public static final int Gdi
```


Die Pixeldaten enthalten GDI-Farben.

### Alpha {#Alpha}
```
public static final int Alpha
```


Die Pixeldaten enthalten Alpha-Werte, die nicht vorab multipliziert sind.

### PAlpha {#PAlpha}
```
public static final int PAlpha
```


Das Pixelformat enthält vorab multiplizierte Alpha-Werte.

### Extended {#Extended}
```
public static final int Extended
```


Reservierter Wert.

### Canonical {#Canonical}
```
public static final int Canonical
```


Das Standard-Pixel-Format von 32 Bit pro Pixel. Das Format gibt eine Farbtiefe von 24 Bit und einen 8‑Bit‑Alpha‑Kanal an.

### Undefined {#Undefined}
```
public static final int Undefined
```


Das Pixelformat ist undefiniert.

### DontCare {#DontCare}
```
public static final int DontCare
```


Kein Pixelformat angegeben.

### Format1bppIndexed {#Format1bppIndexed}
```
public static final int Format1bppIndexed
```


Gibt an, dass das Pixel-Format 1 Bit pro Pixel beträgt und indizierte Farben verwendet. Die Farbpalette enthält daher zwei Farben.

### Format4bppIndexed {#Format4bppIndexed}
```
public static final int Format4bppIndexed
```


Gibt an, dass das Format 4 Bit pro Pixel beträgt, indiziert.

### Format8bppIndexed {#Format8bppIndexed}
```
public static final int Format8bppIndexed
```


Gibt an, dass das Format 8 Bit pro Pixel beträgt, indiziert. Die Farbpalette enthält daher 256 Farben.

### Format16bppGrayScale {#Format16bppGrayScale}
```
public static final int Format16bppGrayScale
```


Das Pixel-Format beträgt 16 Bit pro Pixel. Die Farbinformation gibt 65 536 Graustufen an.

### Format16bppRgb555 {#Format16bppRgb555}
```
public static final int Format16bppRgb555
```


Gibt an, dass das Format 16 Bit pro Pixel beträgt; jeweils 5 Bit für die roten, grünen und blauen Komponenten verwendet werden. Das verbleibende Bit wird nicht genutzt.

### Format16bppRgb565 {#Format16bppRgb565}
```
public static final int Format16bppRgb565
```


Gibt an, dass das Format 16 Bit pro Pixel beträgt; 5 Bit werden für die rote Komponente, 6 Bit für die grüne Komponente und 5 Bit für die blaue Komponente verwendet.

### Format16bppArgb1555 {#Format16bppArgb1555}
```
public static final int Format16bppArgb1555
```


Das Pixel-Format beträgt 16 Bit pro Pixel. Die Farbinformation gibt 32 768 Farbnuancen an, wobei 5 Bit Rot, 5 Bit Grün, 5 Bit Blau und 1 Bit Alpha sind.

### Format24bppRgb {#Format24bppRgb}
```
public static final int Format24bppRgb
```


Gibt an, dass das Format 24 Bit pro Pixel beträgt; jeweils 8 Bit für die roten, grünen und blauen Komponenten verwendet werden.

### Format32bppRgb {#Format32bppRgb}
```
public static final int Format32bppRgb
```


Gibt an, dass das Format 32 Bit pro Pixel beträgt; jeweils 8 Bit für die roten, grünen und blauen Komponenten verwendet werden. Die übrigen 8 Bit werden nicht genutzt.

### Format32bppArgb {#Format32bppArgb}
```
public static final int Format32bppArgb
```


Gibt an, dass das Format 32 Bit pro Pixel beträgt; jeweils 8 Bit für die Alpha-, Rot-, Grün- und Blaukomponenten verwendet werden.

### Format32bppPArgb {#Format32bppPArgb}
```
public static final int Format32bppPArgb
```


Gibt an, dass das Format 32 Bit pro Pixel beträgt; jeweils 8 Bit für die Alpha-, Rot-, Grün- und Blaukomponenten verwendet werden. Die Rot-, Grün- und Blaukomponenten sind gemäß der Alpha‑Komponente vor multipliziert.

### Format48bppRgb {#Format48bppRgb}
```
public static final int Format48bppRgb
```


Gibt an, dass das Format 48 Bit pro Pixel beträgt; jeweils 16 Bit für die roten, grünen und blauen Komponenten verwendet werden.

### Format64bppArgb {#Format64bppArgb}
```
public static final int Format64bppArgb
```


Gibt an, dass das Format 64 Bit pro Pixel beträgt; jeweils 16 Bit für die Alpha-, Rot-, Grün- und Blaukomponenten verwendet werden.

### Format64bppPArgb {#Format64bppPArgb}
```
public static final int Format64bppPArgb
```


Gibt an, dass das Format 64 Bit pro Pixel beträgt; jeweils 16 Bit für die Alpha-, Rot-, Grün- und Blaukomponenten verwendet werden. Die Rot-, Grün- und Blaukomponenten sind gemäß der Alpha‑Komponente vor multipliziert.

### Max {#Max}
```
public static final int Max
```


Der maximale Wert für diese Aufzählung.

