---
title: InterpolationMode
second_title: Référence de l'API Aspose.Drawing pour Java
description: L'énumération InterpolationMode spécifie l'algorithme utilisé lorsque les images sont redimensionnées ou tournées.
type: docs
weight: 28
url: /fr/java/com.aspose.drawing.drawing2d/interpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class InterpolationMode extends System.Enum
```

L'énumération InterpolationMode spécifie l'algorithme utilisé lorsque les images sont redimensionnées ou tournées.
## Champs

| Champ | Description |
| --- | --- |
| [Invalid](#Invalid) | Équivalent à l'élément Invalid de l'énumération QualityMode. |
| [Default](#Default) | Spécifie le mode par défaut. |
| [Low](#Low) | Spécifie une interpolation de basse qualité. |
| [High](#High) | Spécifie une interpolation de haute qualité. |
| [Bilinear](#Bilinear) | Spécifie une interpolation bilinéaire. |
| [Bicubic](#Bicubic) | Spécifie une interpolation bicubique. |
| [NearestNeighbor](#NearestNeighbor) | Spécifie une interpolation du plus proche voisin. |
| [HighQualityBilinear](#HighQualityBilinear) | Spécifie une interpolation bilinéaire de haute qualité. |
| [HighQualityBicubic](#HighQualityBicubic) | Spécifie une interpolation bicubique de haute qualité. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Équivalent à l'élément Invalid de l'énumération QualityMode.

### Default {#Default}
```
public static final int Default
```


Spécifie le mode par défaut.

### Low {#Low}
```
public static final int Low
```


Spécifie une interpolation de basse qualité.

### High {#High}
```
public static final int High
```


Spécifie une interpolation de haute qualité.

### Bilinear {#Bilinear}
```
public static final int Bilinear
```


Spécifie une interpolation bilinéaire. Aucun préfiltrage n'est effectué. Ce mode n'est pas adapté à la réduction d'une image en dessous de 50 % de sa taille originale.

### Bicubic {#Bicubic}
```
public static final int Bicubic
```


Spécifie une interpolation bicubique. Aucun préfiltrage n'est effectué. Ce mode n'est pas adapté à la réduction d'une image en dessous de 25 % de sa taille originale.

### NearestNeighbor {#NearestNeighbor}
```
public static final int NearestNeighbor
```


Spécifie une interpolation du plus proche voisin.

### HighQualityBilinear {#HighQualityBilinear}
```
public static final int HighQualityBilinear
```


Spécifie une interpolation bilinéaire de haute qualité. Un préfiltrage est effectué pour garantir une réduction de haute qualité.

### HighQualityBicubic {#HighQualityBicubic}
```
public static final int HighQualityBicubic
```


Spécifie une interpolation bicubique de haute qualité. Un préfiltrage est effectué pour garantir une réduction de haute qualité. Ce mode produit les images transformées de la plus haute qualité.

