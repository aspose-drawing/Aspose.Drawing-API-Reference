---
title: ColorMap
second_title: Référence de l'API Aspose.Drawing pour Java
description: Définit une table de correspondance pour la conversion des couleurs.
type: docs
weight: 13
url: /fr/java/com.aspose.drawing.imaging/colormap/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMap
```

Définit une table de correspondance pour convertir les couleurs. Plusieurs méthodes de la classe [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) ajustent les couleurs d’image en utilisant une table de remappage des couleurs, qui est un tableau de structures [ColorMap](../../com.aspose.drawing.imaging/colormap). Non héritable.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ColorMap()](#ColorMap--) | Initialise une nouvelle instance de la classe [ColorMap](../../com.aspose.drawing.imaging/colormap). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOldColor()](#getOldColor--) | Obtient la structure [Color](../../com.aspose.drawing/color) existante à convertir. |
| [setOldColor(Color value)](#setOldColor-com.aspose.drawing.Color-) | Définit la structure [Color](../../com.aspose.drawing/color) existante à convertir. |
| [getNewColor()](#getNewColor--) | Obtient la nouvelle structure [Color](../../com.aspose.drawing/color) vers laquelle convertir. |
| [setNewColor(Color value)](#setNewColor-com.aspose.drawing.Color-) | Définit la nouvelle structure [Color](../../com.aspose.drawing/color) vers laquelle convertir. |
### ColorMap() {#ColorMap--}
```
public ColorMap()
```


Initialise une nouvelle instance de la classe [ColorMap](../../com.aspose.drawing.imaging/colormap).

### getOldColor() {#getOldColor--}
```
public Color getOldColor()
```


Obtient la structure [Color](../../com.aspose.drawing/color) existante à convertir.

**Returns:**
[Color](../../com.aspose.drawing/color) - The existing [Color](../../com.aspose.drawing/color) structure to be converted.
### setOldColor(Color value) {#setOldColor-com.aspose.drawing.Color-}
```
public void setOldColor(Color value)
```


Définit la structure [Color](../../com.aspose.drawing/color) existante à convertir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) | la structure [Color](../../com.aspose.drawing/color) existante à convertir. |

### getNewColor() {#getNewColor--}
```
public Color getNewColor()
```


Obtient la nouvelle structure [Color](../../com.aspose.drawing/color) vers laquelle convertir.

**Returns:**
[Color](../../com.aspose.drawing/color) - The new [Color](../../com.aspose.drawing/color) structure to which to convert.
### setNewColor(Color value) {#setNewColor-com.aspose.drawing.Color-}
```
public void setNewColor(Color value)
```


Définit la nouvelle structure [Color](../../com.aspose.drawing/color) vers laquelle convertir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) | la nouvelle structure [Color](../../com.aspose.drawing/color) vers laquelle convertir. |

