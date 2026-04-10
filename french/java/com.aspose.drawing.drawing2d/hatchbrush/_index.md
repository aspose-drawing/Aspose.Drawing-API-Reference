---
title: HatchBrush
second_title: Référence de l'API Aspose.Drawing pour Java
description: Définit un pinceau rectangulaire avec un style hachuré, une couleur de premier plan et une couleur d'arrière-plan.
type: docs
weight: 26
url: /fr/java/com.aspose.drawing.drawing2d/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class HatchBrush extends Brush
```

Définit un pinceau rectangulaire avec un style hachuré, une couleur de premier plan et une couleur d'arrière-plan. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HatchBrush(int hatchstyle, Color foreColor)](#HatchBrush-int-com.aspose.drawing.Color-) | Initialise une nouvelle instance de la classe [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) avec l'énumération `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) spécifiée et la couleur de premier plan. |
| [HatchBrush(int hatchstyle, Color foreColor, Color backColor)](#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Initialise une nouvelle instance de la classe [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) avec l'énumération `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) spécifiée, la couleur de premier plan et la couleur d'arrière-plan. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHatchStyle()](#getHatchStyle--) | Obtient le style hachuré de cet objet [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [getForegroundColor()](#getForegroundColor--) | Obtient la couleur des lignes hachurées dessinées par cet objet [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient la couleur des espaces entre les lignes hachurées dessinées par cet objet [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [deepClone()](#deepClone--) | Crée une copie exacte de cet objet [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
### HatchBrush(int hatchstyle, Color foreColor) {#HatchBrush-int-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor)
```


Initialise une nouvelle instance de la classe [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) avec l'énumération `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) spécifiée et la couleur de premier plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| hatchstyle | int | L'une des valeurs `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) qui représente le motif dessiné par cet [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| foreColor | [Color](../../com.aspose.drawing/color) | La structure [Color](../../com.aspose.drawing/color) qui représente la couleur des lignes dessinées par cet [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |

### HatchBrush(int hatchstyle, Color foreColor, Color backColor) {#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor, Color backColor)
```


Initialise une nouvelle instance de la classe [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) avec l'énumération `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) spécifiée, la couleur de premier plan et la couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| hatchstyle | int | L'une des valeurs `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) qui représente le motif dessiné par cet [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| foreColor | [Color](../../com.aspose.drawing/color) | La structure [Color](../../com.aspose.drawing/color) qui représente la couleur des lignes dessinées par cet [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| backColor | [Color](../../com.aspose.drawing/color) | La structure [Color](../../com.aspose.drawing/color) qui représente la couleur des espaces entre les lignes dessinées par cet [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Obtient le style hachuré de cet objet [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
int - le style hachuré de cet objet [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Obtient la couleur des lignes hachurées dessinées par cet objet [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtient la couleur des espaces entre les lignes hachurées dessinées par cet objet [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of spaces between the hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crée une copie exacte de cet objet [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
java.lang.Object - Le [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) créé par cette méthode, casté en tant qu'objet.
