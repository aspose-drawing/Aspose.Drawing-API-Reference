---
title: InterpolationMode
second_title: Aspose.Drawing för Java API‑referens
description: Enumerationen InterpolationMode specificerar den algoritm som används när bilder skalas eller roteras.
type: docs
weight: 28
url: /sv/java/com.aspose.drawing.drawing2d/interpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class InterpolationMode extends System.Enum
```

Enumerationen InterpolationMode specificerar den algoritm som används när bilder skalas eller roteras.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Invalid](#Invalid) | Motsvarar Invalid-elementet i QualityMode-enumerationen. |
| [Default](#Default) | Anger standardläge. |
| [Low](#Low) | Anger interpolering med låg kvalitet. |
| [High](#High) | Anger interpolering med hög kvalitet. |
| [Bilinear](#Bilinear) | Anger bilinjär interpolation. |
| [Bicubic](#Bicubic) | Anger bikubisk interpolation. |
| [NearestNeighbor](#NearestNeighbor) | Anger närmaste-granne interpolation. |
| [HighQualityBilinear](#HighQualityBilinear) | Anger högkvalitativ, bilinjär interpolation. |
| [HighQualityBicubic](#HighQualityBicubic) | Anger högkvalitativ, bikubisk interpolation. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Motsvarar Invalid-elementet i QualityMode-enumerationen.

### Default {#Default}
```
public static final int Default
```


Anger standardläge.

### Low {#Low}
```
public static final int Low
```


Anger interpolering med låg kvalitet.

### High {#High}
```
public static final int High
```


Anger interpolering med hög kvalitet.

### Bilinear {#Bilinear}
```
public static final int Bilinear
```


Anger bilinjär interpolation. Ingen förfiltrering utförs. Detta läge är inte lämpligt för att minska en bild till under 50 procent av dess ursprungliga storlek.

### Bicubic {#Bicubic}
```
public static final int Bicubic
```


Anger bikubisk interpolation. Ingen förfiltrering utförs. Detta läge är inte lämpligt för att minska en bild till under 25 procent av dess ursprungliga storlek.

### NearestNeighbor {#NearestNeighbor}
```
public static final int NearestNeighbor
```


Anger närmaste-granne interpolation.

### HighQualityBilinear {#HighQualityBilinear}
```
public static final int HighQualityBilinear
```


Anger högkvalitativ, bilinjär interpolation. Förfiltrering utförs för att säkerställa högkvalitativ krympning.

### HighQualityBicubic {#HighQualityBicubic}
```
public static final int HighQualityBicubic
```


Anger högkvalitativ, bikubisk interpolation. Förfiltrering utförs för att säkerställa högkvalitativ krympning. Detta läge producerar de högsta kvaliteten på transformerade bilder.

