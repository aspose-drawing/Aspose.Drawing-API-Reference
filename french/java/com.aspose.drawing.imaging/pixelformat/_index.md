---
title: PixelFormat
second_title: Référence de l'API Aspose.Drawing pour Java
description: Spécifie le format des données de couleur pour chaque pixel de l'image.
type: docs
weight: 34
url: /fr/java/com.aspose.drawing.imaging/pixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PixelFormat extends System.Enum
```

Spécifie le format des données de couleur pour chaque pixel de l'image.
## Champs

| Champ | Description |
| --- | --- |
| [Indexed](#Indexed) | Les données de pixel contiennent des valeurs indexées par couleur, ce qui signifie que les valeurs sont un index vers les couleurs dans la table de couleurs du système, plutôt que des valeurs de couleur individuelles. |
| [Gdi](#Gdi) | Les données de pixel contiennent des couleurs GDI. |
| [Alpha](#Alpha) | Les données de pixel contiennent des valeurs alpha qui ne sont pas prémultipliées. |
| [PAlpha](#PAlpha) | Le format de pixel contient des valeurs alpha prémultipliées. |
| [Extended](#Extended) | Valeur réservée. |
| [Canonical](#Canonical) | Le format de pixel par défaut de 32 bits par pixel. |
| [Undefined](#Undefined) | Le format de pixel est indéfini. |
| [DontCare](#DontCare) | Aucun format de pixel n'est spécifié. |
| [Format1bppIndexed](#Format1bppIndexed) | Spécifie que le format de pixel est de 1 bit par pixel et qu'il utilise une couleur indexée. |
| [Format4bppIndexed](#Format4bppIndexed) | Spécifie que le format est de 4 bits par pixel, indexé. |
| [Format8bppIndexed](#Format8bppIndexed) | Spécifie que le format est de 8 bits par pixel, indexé. |
| [Format16bppGrayScale](#Format16bppGrayScale) | Le format de pixel est de 16 bits par pixel. |
| [Format16bppRgb555](#Format16bppRgb555) | Spécifie que le format est de 16 bits par pixel ; 5 bits chacun sont utilisés pour les composantes rouge, verte et bleue. |
| [Format16bppRgb565](#Format16bppRgb565) | Spécifie que le format est de 16 bits par pixel ; 5 bits sont utilisés pour la composante rouge, 6 bits pour la composante verte et 5 bits pour la composante bleue. |
| [Format16bppArgb1555](#Format16bppArgb1555) | Le format de pixel est de 16 bits par pixel. |
| [Format24bppRgb](#Format24bppRgb) | Spécifie que le format est de 24 bits par pixel; 8 bits chacun sont utilisés pour les composants rouge, vert et bleu. |
| [Format32bppRgb](#Format32bppRgb) | Spécifie que le format est de 32 bits par pixel; 8 bits chacun sont utilisés pour les composants rouge, vert et bleu. |
| [Format32bppArgb](#Format32bppArgb) | Spécifie que le format est de 32 bits par pixel; 8 bits chacun sont utilisés pour les composants alpha, rouge, vert et bleu. |
| [Format32bppPArgb](#Format32bppPArgb) | Spécifie que le format est de 32 bits par pixel; 8 bits chacun sont utilisés pour les composants alpha, rouge, vert et bleu. |
| [Format48bppRgb](#Format48bppRgb) | Spécifie que le format est de 48 bits par pixel; 16 bits chacun sont utilisés pour les composants rouge, vert et bleu. |
| [Format64bppArgb](#Format64bppArgb) | Spécifie que le format est de 64 bits par pixel; 16 bits chacun sont utilisés pour les composants alpha, rouge, vert et bleu. |
| [Format64bppPArgb](#Format64bppPArgb) | Spécifie que le format est de 64 bits par pixel; 16 bits chacun sont utilisés pour les composants alpha, rouge, vert et bleu. |
| [Max](#Max) | La valeur maximale pour cette énumération. |
### Indexed {#Indexed}
```
public static final int Indexed
```


Les données de pixel contiennent des valeurs indexées par couleur, ce qui signifie que les valeurs sont un index vers les couleurs dans la table de couleurs du système, plutôt que des valeurs de couleur individuelles.

### Gdi {#Gdi}
```
public static final int Gdi
```


Les données de pixel contiennent des couleurs GDI.

### Alpha {#Alpha}
```
public static final int Alpha
```


Les données de pixel contiennent des valeurs alpha qui ne sont pas prémultipliées.

### PAlpha {#PAlpha}
```
public static final int PAlpha
```


Le format de pixel contient des valeurs alpha prémultipliées.

### Extended {#Extended}
```
public static final int Extended
```


Valeur réservée.

### Canonical {#Canonical}
```
public static final int Canonical
```


Le format de pixel par défaut est de 32 bits par pixel. Le format spécifie une profondeur de couleur de 24 bits et un canal alpha de 8 bits.

### Undefined {#Undefined}
```
public static final int Undefined
```


Le format de pixel est indéfini.

### DontCare {#DontCare}
```
public static final int DontCare
```


Aucun format de pixel n'est spécifié.

### Format1bppIndexed {#Format1bppIndexed}
```
public static final int Format1bppIndexed
```


Spécifie que le format de pixel est de 1 bit par pixel et qu’il utilise une couleur indexée. La table de couleurs contient donc deux couleurs.

### Format4bppIndexed {#Format4bppIndexed}
```
public static final int Format4bppIndexed
```


Spécifie que le format est de 4 bits par pixel, indexé.

### Format8bppIndexed {#Format8bppIndexed}
```
public static final int Format8bppIndexed
```


Spécifie que le format est de 8 bits par pixel, indexé. La table de couleurs contient donc 256 couleurs.

### Format16bppGrayScale {#Format16bppGrayScale}
```
public static final int Format16bppGrayScale
```


Le format de pixel est de 16 bits par pixel. L’information couleur spécifie 65 536 nuances de gris.

### Format16bppRgb555 {#Format16bppRgb555}
```
public static final int Format16bppRgb555
```


Spécifie que le format est de 16 bits par pixel; 5 bits chacun sont utilisés pour les composants rouge, vert et bleu. Le bit restant n’est pas utilisé.

### Format16bppRgb565 {#Format16bppRgb565}
```
public static final int Format16bppRgb565
```


Spécifie que le format est de 16 bits par pixel ; 5 bits sont utilisés pour la composante rouge, 6 bits pour la composante verte et 5 bits pour la composante bleue.

### Format16bppArgb1555 {#Format16bppArgb1555}
```
public static final int Format16bppArgb1555
```


Le format de pixel est de 16 bits par pixel. L’information couleur spécifie 32 768 nuances de couleur, dont 5 bits pour le rouge, 5 bits pour le vert, 5 bits pour le bleu et 1 bit pour l’alpha.

### Format24bppRgb {#Format24bppRgb}
```
public static final int Format24bppRgb
```


Spécifie que le format est de 24 bits par pixel; 8 bits chacun sont utilisés pour les composants rouge, vert et bleu.

### Format32bppRgb {#Format32bppRgb}
```
public static final int Format32bppRgb
```


Spécifie que le format est de 32 bits par pixel; 8 bits chacun sont utilisés pour les composants rouge, vert et bleu. Les 8 bits restants ne sont pas utilisés.

### Format32bppArgb {#Format32bppArgb}
```
public static final int Format32bppArgb
```


Spécifie que le format est de 32 bits par pixel; 8 bits chacun sont utilisés pour les composants alpha, rouge, vert et bleu.

### Format32bppPArgb {#Format32bppPArgb}
```
public static final int Format32bppPArgb
```


Spécifie que le format est de 32 bits par pixel; 8 bits chacun sont utilisés pour les composants alpha, rouge, vert et bleu. Les composants rouge, vert et bleu sont prémultipliés, selon le composant alpha.

### Format48bppRgb {#Format48bppRgb}
```
public static final int Format48bppRgb
```


Spécifie que le format est de 48 bits par pixel; 16 bits chacun sont utilisés pour les composants rouge, vert et bleu.

### Format64bppArgb {#Format64bppArgb}
```
public static final int Format64bppArgb
```


Spécifie que le format est de 64 bits par pixel; 16 bits chacun sont utilisés pour les composants alpha, rouge, vert et bleu.

### Format64bppPArgb {#Format64bppPArgb}
```
public static final int Format64bppPArgb
```


Spécifie que le format est de 64 bits par pixel; 16 bits chacun sont utilisés pour les composants alpha, rouge, vert et bleu. Les composants rouge, vert et bleu sont prémultipliés selon le composant alpha.

### Max {#Max}
```
public static final int Max
```


La valeur maximale pour cette énumération.

