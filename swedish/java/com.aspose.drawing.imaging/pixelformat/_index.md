---
title: PixelFormat
second_title: Aspose.Drawing för Java API‑referens
description: Anger formatet för färgdata för varje pixel i bilden.
type: docs
weight: 34
url: /sv/java/com.aspose.drawing.imaging/pixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PixelFormat extends System.Enum
```

Anger formatet för färgdata för varje pixel i bilden.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Indexed](#Indexed) | Pixeldata innehåller färgindexerade värden, vilket betyder att värdena är ett index till färger i systemets färgtabell, snarare än enskilda färgvärden. |
| [Gdi](#Gdi) | Pixeldata innehåller GDI-färger. |
| [Alpha](#Alpha) | Pixeldata innehåller alfavärden som inte är förmultiplicerade. |
| [PAlpha](#PAlpha) | Pixelformatet innehåller förmultiplicerade alfavärden. |
| [Extended](#Extended) | Reserverat värde. |
| [Canonical](#Canonical) | Standardpixelformatet är 32 bitar per pixel. |
| [Undefined](#Undefined) | Pixelformatet är odefinierat. |
| [DontCare](#DontCare) | Ingen pixelformat är angivet. |
| [Format1bppIndexed](#Format1bppIndexed) | Anger att pixelformatet är 1 bit per pixel och att det använder indexerad färg. |
| [Format4bppIndexed](#Format4bppIndexed) | Anger att formatet är 4 bitar per pixel, indexerat. |
| [Format8bppIndexed](#Format8bppIndexed) | Anger att formatet är 8 bitar per pixel, indexerat. |
| [Format16bppGrayScale](#Format16bppGrayScale) | Pixelformatet är 16 bitar per pixel. |
| [Format16bppRgb555](#Format16bppRgb555) | Anger att formatet är 16 bitar per pixel; 5 bitar vardera används för de röda, gröna och blå komponenterna. |
| [Format16bppRgb565](#Format16bppRgb565) | Anger att formatet är 16 bitar per pixel; 5 bitar används för den röda komponenten, 6 bitar används för den gröna komponenten och 5 bitar används för den blå komponenten. |
| [Format16bppArgb1555](#Format16bppArgb1555) | Pixelformatet är 16 bitar per pixel. |
| [Format24bppRgb](#Format24bppRgb) | Anger att formatet är 24 bitar per pixel; 8 bitar vardera används för de röda, gröna och blå komponenterna. |
| [Format32bppRgb](#Format32bppRgb) | Anger att formatet är 32 bitar per pixel; 8 bitar vardera används för de röda, gröna och blå komponenterna. |
| [Format32bppArgb](#Format32bppArgb) | Anger att formatet är 32 bitar per pixel; 8 bitar vardera används för alpha-, röd-, grön- och blåkomponenterna. |
| [Format32bppPArgb](#Format32bppPArgb) | Anger att formatet är 32 bitar per pixel; 8 bitar vardera används för alpha-, röd-, grön- och blåkomponenterna. |
| [Format48bppRgb](#Format48bppRgb) | Anger att formatet är 48 bitar per pixel; 16 bitar vardera används för de röda, gröna och blå komponenterna. |
| [Format64bppArgb](#Format64bppArgb) | Anger att formatet är 64 bitar per pixel; 16 bitar vardera används för alpha-, röd-, grön- och blåkomponenterna. |
| [Format64bppPArgb](#Format64bppPArgb) | Anger att formatet är 64 bitar per pixel; 16 bitar vardera används för alpha-, röd-, grön- och blåkomponenterna. |
| [Max](#Max) | Det maximala värdet för den här uppräkningen. |
### Indexed {#Indexed}
```
public static final int Indexed
```


Pixeldata innehåller färgindexerade värden, vilket betyder att värdena är ett index till färger i systemets färgtabell, snarare än enskilda färgvärden.

### Gdi {#Gdi}
```
public static final int Gdi
```


Pixeldata innehåller GDI-färger.

### Alpha {#Alpha}
```
public static final int Alpha
```


Pixeldata innehåller alfavärden som inte är förmultiplicerade.

### PAlpha {#PAlpha}
```
public static final int PAlpha
```


Pixelformatet innehåller förmultiplicerade alfavärden.

### Extended {#Extended}
```
public static final int Extended
```


Reserverat värde.

### Canonical {#Canonical}
```
public static final int Canonical
```


Standardpixelformatet är 32 bitar per pixel. Formatet anger 24‑bitars färgdjup och en 8‑bitars alpha‑kanal.

### Undefined {#Undefined}
```
public static final int Undefined
```


Pixelformatet är odefinierat.

### DontCare {#DontCare}
```
public static final int DontCare
```


Ingen pixelformat är angivet.

### Format1bppIndexed {#Format1bppIndexed}
```
public static final int Format1bppIndexed
```


Anger att pixelformatet är 1 bit per pixel och att det använder indexerad färg. Färgtabellen har därför två färger.

### Format4bppIndexed {#Format4bppIndexed}
```
public static final int Format4bppIndexed
```


Anger att formatet är 4 bitar per pixel, indexerat.

### Format8bppIndexed {#Format8bppIndexed}
```
public static final int Format8bppIndexed
```


Anger att formatet är 8 bitar per pixel, indexerat. Färgtabellen har därför 256 färger.

### Format16bppGrayScale {#Format16bppGrayScale}
```
public static final int Format16bppGrayScale
```


Pixelformatet är 16 bitar per pixel. Färginformationen anger 65 536 nyanser av grått.

### Format16bppRgb555 {#Format16bppRgb555}
```
public static final int Format16bppRgb555
```


Anger att formatet är 16 bitar per pixel; 5 bitar vardera används för de röda, gröna och blå komponenterna. Den återstående biten används inte.

### Format16bppRgb565 {#Format16bppRgb565}
```
public static final int Format16bppRgb565
```


Anger att formatet är 16 bitar per pixel; 5 bitar används för den röda komponenten, 6 bitar används för den gröna komponenten och 5 bitar används för den blå komponenten.

### Format16bppArgb1555 {#Format16bppArgb1555}
```
public static final int Format16bppArgb1555
```


Pixelformatet är 16 bitar per pixel. Färginformationen anger 32 768 färgnyanser, varav 5 bitar är röda, 5 bitar är gröna, 5 bitar är blå och 1 bit är alpha.

### Format24bppRgb {#Format24bppRgb}
```
public static final int Format24bppRgb
```


Anger att formatet är 24 bitar per pixel; 8 bitar vardera används för de röda, gröna och blå komponenterna.

### Format32bppRgb {#Format32bppRgb}
```
public static final int Format32bppRgb
```


Anger att formatet är 32 bitar per pixel; 8 bitar vardera används för de röda, gröna och blå komponenterna. De återstående 8 bitarna används inte.

### Format32bppArgb {#Format32bppArgb}
```
public static final int Format32bppArgb
```


Anger att formatet är 32 bitar per pixel; 8 bitar vardera används för alpha-, röd-, grön- och blåkomponenterna.

### Format32bppPArgb {#Format32bppPArgb}
```
public static final int Format32bppPArgb
```


Anger att formatet är 32 bitar per pixel; 8 bitar vardera används för alpha-, röd-, grön- och blåkomponenterna. De röda, gröna och blå komponenterna är förmultiplikerade enligt alpha‑komponenten.

### Format48bppRgb {#Format48bppRgb}
```
public static final int Format48bppRgb
```


Anger att formatet är 48 bitar per pixel; 16 bitar vardera används för de röda, gröna och blå komponenterna.

### Format64bppArgb {#Format64bppArgb}
```
public static final int Format64bppArgb
```


Anger att formatet är 64 bitar per pixel; 16 bitar vardera används för alpha-, röd-, grön- och blåkomponenterna.

### Format64bppPArgb {#Format64bppPArgb}
```
public static final int Format64bppPArgb
```


Anger att formatet är 64 bitar per pixel; 16 bitar vardera används för alpha-, röd-, grön- och blåkomponenterna. De röda, gröna och blå komponenterna är förmultiplikerade enligt alpha‑komponenten.

### Max {#Max}
```
public static final int Max
```


Det maximala värdet för den här uppräkningen.

