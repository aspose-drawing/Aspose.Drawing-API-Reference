---
title: InterpolationMode
second_title: Aspose.Drawing voor Java API-referentie
description: De enumeratie InterpolationMode specificeert het algoritme dat wordt gebruikt wanneer afbeeldingen worden geschaald of geroteerd.
type: docs
weight: 28
url: /nl/java/com.aspose.drawing.drawing2d/interpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class InterpolationMode extends System.Enum
```

De enumeratie InterpolationMode specificeert het algoritme dat wordt gebruikt wanneer afbeeldingen worden geschaald of geroteerd.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Invalid](#Invalid) | Gelijk aan het Invalid-element van de QualityMode-enumeratie. |
| [Default](#Default) | Specificeert de standaardmodus. |
| [Low](#Low) | Specificeert interpolatie van lage kwaliteit. |
| [High](#High) | Specificeert interpolatie van hoge kwaliteit. |
| [Bilinear](#Bilinear) | Specificeert bilineaire interpolatie. |
| [Bicubic](#Bicubic) | Specificeert bicubische interpolatie. |
| [NearestNeighbor](#NearestNeighbor) | Specificeert nearest-neighbor interpolatie. |
| [HighQualityBilinear](#HighQualityBilinear) | Specificeert hoge kwaliteit, bilineaire interpolatie. |
| [HighQualityBicubic](#HighQualityBicubic) | Specificeert hoge kwaliteit, bicubische interpolatie. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Gelijk aan het Invalid-element van de QualityMode-enumeratie.

### Default {#Default}
```
public static final int Default
```


Specificeert de standaardmodus.

### Low {#Low}
```
public static final int Low
```


Specificeert interpolatie van lage kwaliteit.

### High {#High}
```
public static final int High
```


Specificeert interpolatie van hoge kwaliteit.

### Bilinear {#Bilinear}
```
public static final int Bilinear
```


Specificeert bilineaire interpolatie. Er wordt geen prefiltering uitgevoerd. Deze modus is niet geschikt om een afbeelding te verkleinen tot minder dan 50 procent van de oorspronkelijke grootte.

### Bicubic {#Bicubic}
```
public static final int Bicubic
```


Specificeert bicubische interpolatie. Er wordt geen prefiltering uitgevoerd. Deze modus is niet geschikt om een afbeelding te verkleinen tot minder dan 25 procent van de oorspronkelijke grootte.

### NearestNeighbor {#NearestNeighbor}
```
public static final int NearestNeighbor
```


Specificeert nearest-neighbor interpolatie.

### HighQualityBilinear {#HighQualityBilinear}
```
public static final int HighQualityBilinear
```


Specificeert hoge kwaliteit, bilineaire interpolatie. Prefiltering wordt uitgevoerd om een verkleining van hoge kwaliteit te garanderen.

### HighQualityBicubic {#HighQualityBicubic}
```
public static final int HighQualityBicubic
```


Specificeert hoge kwaliteit, bicubische interpolatie. Prefiltering wordt uitgevoerd om een verkleining van hoge kwaliteit te garanderen. Deze modus levert de hoogste kwaliteit getransformeerde afbeeldingen op.

