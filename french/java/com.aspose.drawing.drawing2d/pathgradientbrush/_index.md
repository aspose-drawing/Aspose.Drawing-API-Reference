---
title: PathGradientBrush
second_title: Référence de l'API Aspose.Drawing pour Java
description: Encapsule un objet qui remplit l'intérieur d'un objet avec un dégradé.
type: docs
weight: 36
url: /fr/java/com.aspose.drawing.drawing2d/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class PathGradientBrush extends Brush
```

Encapsule un objet [Brush](../../com.aspose.drawing/brush) qui remplit l'intérieur d'un objet [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) avec un dégradé. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.drawing.PointF---) | Initialise une nouvelle instance de la classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) avec les points spécifiés. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.PointF---int-) | Initialise une nouvelle instance de la classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) avec les points spécifiés et le mode d'enroulement. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.drawing.Point---) | Initialise une nouvelle instance de la classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) avec les points spécifiés. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.Point---int-) | Initialise une nouvelle instance de la classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) avec les points spécifiés et le mode d'enroulement. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-) | Initialise une nouvelle instance de la classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) avec le chemin spécifié. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCenterColor()](#getCenterColor--) | Obtient ou définit la couleur au centre du dégradé de chemin. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.drawing.Color-) | Obtient ou définit la couleur au centre du dégradé de chemin. |
| [getSurroundColors()](#getSurroundColors--) | Obtient ou définit un tableau de couleurs correspondant aux points du chemin que ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) remplit. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.drawing.Color---) | Obtient ou définit un tableau de couleurs correspondant aux points du chemin que ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) remplit. |
| [getCenterPoint()](#getCenterPoint--) | Obtient ou définit le point central du dégradé de chemin. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.drawing.PointF-) | Obtient ou définit le point central du dégradé de chemin. |
| [getRectangle()](#getRectangle--) | Obtient un rectangle englobant pour ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getBlend()](#getBlend--) | Obtient ou définit un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) qui spécifie les positions et les facteurs qui définissent une atténuation personnalisée pour le dégradé. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Obtient ou définit un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) qui spécifie les positions et les facteurs qui définissent une atténuation personnalisée pour le dégradé. |
| [getInterpolationColors()](#getInterpolationColors--) | Obtient ou définit un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) qui définit un dégradé linéaire multicolore. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Obtient ou définit un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) qui définit un dégradé linéaire multicolore. |
| [getTransform()](#getTransform--) | Obtient ou définit une copie de la [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui définit une transformation géométrique locale pour ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Obtient ou définit une copie de la [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui définit une transformation géométrique locale pour ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getFocusScales()](#getFocusScales--) | Obtient ou définit le point de focalisation pour la décroissance du dégradé. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.drawing.PointF-) | Obtient ou définit le point de focalisation pour la décroissance du dégradé. |
| [getWrapMode()](#getWrapMode--) | Obtient ou définit un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) qui indique le mode d'enroulement pour ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtient ou définit un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) qui indique le mode d'enroulement pour ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [deepClone()](#deepClone--) | Crée une copie exacte de ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crée un pinceau de dégradé qui change de couleur en partant du centre du chemin vers la bordure du chemin. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crée un pinceau de dégradé qui change de couleur en partant du centre du chemin vers la bordure du chemin. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crée un dégradé avec une couleur centrale et une décroissance linéaire vers une couleur environnante. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crée un dégradé avec une couleur centrale et une décroissance linéaire vers chaque couleur environnante. |
| [resetTransform()](#resetTransform--) | Réinitialise la propriété `PathGradientBrush.Transform` à l'identité. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Met à jour la matrice de transformation du pinceau avec le produit de la matrice de transformation du pinceau multipliée par une autre matrice. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Met à jour la matrice de transformation du pinceau avec le produit de la matrice de transformation du pinceau multipliée par une autre matrice. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Applique la translation spécifiée à la transformation géométrique locale. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Applique la translation spécifiée à la transformation géométrique locale dans l'ordre spécifié. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Met à l'échelle la transformation géométrique locale par les quantités spécifiées. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Met à l'échelle la transformation géométrique locale par les quantités spécifiées dans l'ordre spécifié. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Fait pivoter la transformation géométrique locale par la quantité spécifiée. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Fait pivoter la transformation géométrique locale par la quantité spécifiée dans l'ordre spécifié. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.drawing.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Initialise une nouvelle instance de la classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) avec les points spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Un tableau de structures [PointF](../../com.aspose.drawing/pointf) qui représente les points constituant les sommets du chemin. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Initialise une nouvelle instance de la classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) avec les points spécifiés et le mode d'enroulement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Un tableau de structures [PointF](../../com.aspose.drawing/pointf) qui représente les points constituant les sommets du chemin. |
| wrapMode | int | Un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) qui spécifie comment les remplissages dessinés avec ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) sont mosaïqués. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.drawing.Point---}
```
public PathGradientBrush(Point[] points)
```


Initialise une nouvelle instance de la classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) avec les points spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Un tableau de structures [Point](../../com.aspose.drawing/point) qui représente les points constituant les sommets du chemin. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Initialise une nouvelle instance de la classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) avec les points spécifiés et le mode d'enroulement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Un tableau de structures [Point](../../com.aspose.drawing/point) qui représente les points constituant les sommets du chemin. |
| wrapMode | int | Un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) qui spécifie comment les remplissages dessinés avec ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) sont mosaïqués. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Initialise une nouvelle instance de la classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) avec le chemin spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) qui définit la zone remplie par ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Obtient ou définit la couleur au centre du dégradé de chemin.

**Returns:**
[Color](../../com.aspose.drawing/color)
### setCenterColor(Color value) {#setCenterColor-com.aspose.drawing.Color-}
```
public void setCenterColor(Color value)
```


Obtient ou définit la couleur au centre du dégradé de chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Obtient ou définit un tableau de couleurs correspondant aux points du chemin que ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) remplit.

**Returns:**
com.aspose.drawing.Color[]
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.drawing.Color---}
```
public void setSurroundColors(Color[] value)
```


Obtient ou définit un tableau de couleurs correspondant aux points du chemin que ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) remplit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Obtient ou définit le point central du dégradé de chemin.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.drawing.PointF-}
```
public void setCenterPoint(PointF value)
```


Obtient ou définit le point central du dégradé de chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Obtient un rectangle englobant pour ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Obtient ou définit un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) qui spécifie les positions et les facteurs qui définissent une atténuation personnalisée pour le dégradé.

**Returns:**
[Blend](../../com.aspose.drawing.drawing2d/blend)
### setBlend(Blend value) {#setBlend-com.aspose.drawing.drawing2d.Blend-}
```
public void setBlend(Blend value)
```


Obtient ou définit un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) qui spécifie les positions et les facteurs qui définissent une atténuation personnalisée pour le dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Blend](../../com.aspose.drawing.drawing2d/blend) |  |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Obtient ou définit un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) qui définit un dégradé linéaire multicolore.

**Returns:**
[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Obtient ou définit un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) qui définit un dégradé linéaire multicolore.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtient ou définit une copie de la [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui définit une transformation géométrique locale pour ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Obtient ou définit une copie de la [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui définit une transformation géométrique locale pour ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Obtient ou définit le point de focalisation pour la décroissance du dégradé.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setFocusScales(PointF value) {#setFocusScales-com.aspose.drawing.PointF-}
```
public void setFocusScales(PointF value)
```


Obtient ou définit le point de focalisation pour la décroissance du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtient ou définit un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) qui indique le mode d'enroulement pour ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtient ou définit un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) qui indique le mode d'enroulement pour ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crée une copie exacte de ce [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
java.lang.Object - Le [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) que cette méthode crée, converti en objet.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Crée un pinceau de dégradé qui change de couleur en partant du centre du chemin vers la bordure du chemin. La transition d'une couleur à l'autre est basée sur une courbe en forme de cloche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur de 0 à 1 qui spécifie où, le long de n'importe quel rayon du centre du chemin jusqu'à la bordure du chemin, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (la valeur par défaut) place l'intensité maximale au centre du chemin. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crée un pinceau de dégradé qui change de couleur en partant du centre du chemin vers la bordure du chemin. La transition d'une couleur à l'autre est basée sur une courbe en forme de cloche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur de 0 à 1 qui spécifie où, le long de n'importe quel rayon du centre du chemin jusqu'à la bordure du chemin, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (la valeur par défaut) place l'intensité maximale au centre du chemin. |
| scale | float | Une valeur de 0 à 1 qui spécifie l'intensité maximale de la couleur centrale qui se mélange avec la couleur de bordure. Une valeur de 1 entraîne l'intensité la plus élevée possible de la couleur centrale, et c'est la valeur par défaut. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Crée un dégradé avec une couleur centrale et une décroissance linéaire vers une couleur environnante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur de 0 à 1 qui spécifie où, le long de n'importe quel rayon du centre du chemin jusqu'à la bordure du chemin, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (la valeur par défaut) place l'intensité maximale au centre du chemin. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crée un dégradé avec une couleur centrale et une décroissance linéaire vers chaque couleur environnante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur de 0 à 1 qui spécifie où, le long de n'importe quel rayon du centre du chemin jusqu'à la bordure du chemin, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (la valeur par défaut) place l'intensité maximale au centre du chemin. |
| scale | float | Une valeur de 0 à 1 qui spécifie l'intensité maximale de la couleur centrale qui se mélange avec la couleur de bordure. Une valeur de 1 entraîne l'intensité la plus élevée possible de la couleur centrale, et c'est la valeur par défaut. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Réinitialise la propriété `PathGradientBrush.Transform` à l'identité.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Met à jour la matrice de transformation du pinceau avec le produit de la matrice de transformation du pinceau multipliée par une autre matrice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Le [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui sera multiplié par la matrice de transformation actuelle du pinceau. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Met à jour la matrice de transformation du pinceau avec le produit de la matrice de transformation du pinceau multipliée par une autre matrice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Le [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui sera multiplié par la matrice de transformation actuelle du pinceau. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) qui spécifie dans quel ordre multiplier les deux matrices. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Applique la translation spécifiée à la transformation géométrique locale. Cette méthode préfixe la translation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Applique la translation spécifiée à la transformation géométrique locale dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |
| order | int | L'ordre (préfixer ou ajouter) dans lequel appliquer la translation. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Met à l'échelle la transformation géométrique locale selon les quantités spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | Le facteur d'échelle de la transformation dans la direction de l'axe x. |
| sy | float | Le facteur d'échelle de la transformation dans la direction de l'axe y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Met à l'échelle la transformation géométrique locale par les quantités spécifiées dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | Le facteur d'échelle de la transformation dans la direction de l'axe x. |
| sy | float | Le facteur d'échelle de la transformation dans la direction de l'axe y. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) qui indique s'il faut ajouter ou préfixer la matrice d'échelle. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Fait pivoter la transformation géométrique locale de la quantité spécifiée. Cette méthode préfixe la rotation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle (étendue) de rotation. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Fait pivoter la transformation géométrique locale par la quantité spécifiée dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle (étendue) de rotation. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) qui indique s'il faut ajouter ou préfixer la matrice de rotation. |

