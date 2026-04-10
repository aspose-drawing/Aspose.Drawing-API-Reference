---
title: InterpolationMode
second_title: Aspose.Drawing für Java API-Referenz
description: Die Aufzählung InterpolationMode gibt den Algorithmus an, der verwendet wird, wenn Bilder skaliert oder rotiert werden.
type: docs
weight: 28
url: /de/java/com.aspose.drawing.drawing2d/interpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class InterpolationMode extends System.Enum
```

Die Aufzählung InterpolationMode gibt den Algorithmus an, der verwendet wird, wenn Bilder skaliert oder rotiert werden.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Invalid](#Invalid) | Entspricht dem Element Invalid der Aufzählung QualityMode. |
| [Default](#Default) | Gibt den Standardmodus an. |
| [Low](#Low) | Gibt eine Interpolation von niedriger Qualität an. |
| [High](#High) | Gibt eine Interpolation von hoher Qualität an. |
| [Bilinear](#Bilinear) | Gibt bilineare Interpolation an. |
| [Bicubic](#Bicubic) | Gibt bikubische Interpolation an. |
| [NearestNeighbor](#NearestNeighbor) | Gibt nächster-Nachbar-Interpolation an. |
| [HighQualityBilinear](#HighQualityBilinear) | Gibt hochqualitative, bilineare Interpolation an. |
| [HighQualityBicubic](#HighQualityBicubic) | Gibt hochqualitative, bikubische Interpolation an. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Entspricht dem Element Invalid der Aufzählung QualityMode.

### Default {#Default}
```
public static final int Default
```


Gibt den Standardmodus an.

### Low {#Low}
```
public static final int Low
```


Gibt eine Interpolation von niedriger Qualität an.

### High {#High}
```
public static final int High
```


Gibt eine Interpolation von hoher Qualität an.

### Bilinear {#Bilinear}
```
public static final int Bilinear
```


Gibt bilineare Interpolation an. Es wird keine Vorfilterung durchgeführt. Dieser Modus ist nicht geeignet, ein Bild unter 50 % seiner Originalgröße zu verkleinern.

### Bicubic {#Bicubic}
```
public static final int Bicubic
```


Gibt bikubische Interpolation an. Es wird keine Vorfilterung durchgeführt. Dieser Modus ist nicht geeignet, ein Bild unter 25 % seiner Originalgröße zu verkleinern.

### NearestNeighbor {#NearestNeighbor}
```
public static final int NearestNeighbor
```


Gibt nächster-Nachbar-Interpolation an.

### HighQualityBilinear {#HighQualityBilinear}
```
public static final int HighQualityBilinear
```


Gibt hochqualitative, bilineare Interpolation an. Vorfilterung wird durchgeführt, um ein hochwertiges Verkleinern zu gewährleisten.

### HighQualityBicubic {#HighQualityBicubic}
```
public static final int HighQualityBicubic
```


Gibt hochqualitative, bikubische Interpolation an. Vorfilterung wird durchgeführt, um ein hochwertiges Verkleinern zu gewährleisten. Dieser Modus erzeugt die qualitativ hochwertigsten transformierten Bilder.

