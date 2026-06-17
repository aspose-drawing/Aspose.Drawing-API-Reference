---
title: ColorPalette
second_title: Référence de l'API Aspose.Drawing pour Java
description: Définit un tableau de couleurs qui compose une palette de couleurs.
type: docs
weight: 16
url: /fr/java/com.aspose.drawing.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPalette
```

Définit un tableau de couleurs qui composent une palette de couleurs. Les couleurs sont des couleurs ARGB 32 bits. Non héritable.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ColorPalette(int count)](#ColorPalette-int-) | Initialise une nouvelle instance de la classe `ColorPalette` et IsCompactPalette est false. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEntries()](#getEntries--) | Obtient un tableau de structures `com.aspose.drawing.Color`. |
| [isCompactPalette()](#isCompactPalette--) | Obtient ou définit une valeur indiquant si la palette compacte est utilisée. |
| [getFlags()](#getFlags--) |  |
| [setFlags(int flags)](#setFlags-int-) |  |
| [setEntries(int i, Color color)](#setEntries-int-com.aspose.drawing.Color-) |  |
### ColorPalette(int count) {#ColorPalette-int-}
```
public ColorPalette(int count)
```


Initialise une nouvelle instance de la classe `ColorPalette` et IsCompactPalette est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| count | int | Les entrées de la palette de couleurs. |

### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Obtient un tableau de structures `com.aspose.drawing.Color`.

**Returns:**
com.aspose.drawing.Color[] - Les entrées. Le tableau de structures `com.aspose.drawing.Color` qui composent ce `Aspose.Imaging.ColorPalette`.
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Obtient ou définit une valeur indiquant si la palette compacte est utilisée.

**Returns:**
boolean - `true` si la palette compacte est utilisée ; sinon, `false`.

Une palette compacte signifie que l'image ne contiendra que les entrées de palette spécifiées si possible, autrement dit l'image sera plus compacte et occupera moins d'espace ; sinon il y aura 2^BitsPerPixel entrées et l'image réservera plus d'espace pour toutes les entrées de palette possibles. Mettre cette valeur à true et modifier les entrées de palette peut entraîner une pénalité de performance puisque des déplacements de données peuvent survenir, utilisez-le donc avec précaution.
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
| Paramètre | Type | Description |
| --- | --- | --- |
| flags | int |  |

### setEntries(int i, Color color) {#setEntries-int-com.aspose.drawing.Color-}
```
public void setEntries(int i, Color color)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| i | int |  |
| color | [Color](../../com.aspose.drawing/color) |  |

