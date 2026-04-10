---
title: LinearGradientBrush
second_title: Référence de l'API Aspose.Drawing pour Java
description: Encapsule un  avec un dégradé linéaire.
type: docs
weight: 31
url: /fr/java/com.aspose.drawing.drawing2d/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class LinearGradientBrush extends Brush
```

Encapsule un [Brush](../../com.aspose.drawing/brush) avec un dégradé linéaire. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) avec les points et les couleurs spécifiés. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) avec les points et les couleurs spécifiés. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basée sur un rectangle, des couleurs de départ et d'arrivée, et un mode d'orientation. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basée sur un rectangle, des couleurs de départ et d'arrivée, et une orientation. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLinearColors()](#getLinearColors--) | Obtient ou définit les couleurs de départ et d'arrivée du dégradé. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.drawing.Color---) | Obtient ou définit les couleurs de départ et d'arrivée du dégradé. |
| [getRectangle()](#getRectangle--) | Obtient une région rectangulaire qui définit les points de départ et d'arrivée du dégradé. |
| [getGammaCorrection()](#getGammaCorrection--) | Obtient ou définit une valeur indiquant si la correction gamma est activée pour ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Obtient ou définit une valeur indiquant si la correction gamma est activée pour ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getBlend()](#getBlend--) | Obtient ou définit un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) qui spécifie les positions et les facteurs qui définissent une atténuation personnalisée pour le dégradé. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Obtient ou définit un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) qui spécifie les positions et les facteurs qui définissent une atténuation personnalisée pour le dégradé. |
| [getInterpolationColors()](#getInterpolationColors--) | Obtient ou définit un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) qui définit un dégradé linéaire multicolore. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Obtient ou définit un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) qui définit un dégradé linéaire multicolore. |
| [getWrapMode()](#getWrapMode--) | Obtient ou définit une énumération `WrapMode` qui indique le mode d'enroulement pour ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtient ou définit une énumération `WrapMode` qui indique le mode d'enroulement pour ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getTransform()](#getTransform--) | Obtient ou définit une copie de [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui définit une transformation géométrique locale pour ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Obtient ou définit une copie de [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui définit une transformation géométrique locale pour ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [deepClone()](#deepClone--) | Crée une copie exacte de ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crée une atténuation du dégradé basée sur une courbe en cloche. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crée une atténuation du dégradé basée sur une courbe en cloche. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une couleur unique aux deux extrémités. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une couleur unique aux deux extrémités. |
| [resetTransform()](#resetTransform--) | Réinitialise la propriété `LinearGradientBrush.Transform` à l'identité. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Multiplie la [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui représente la transformation géométrique locale de ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) par la [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifiée en préfixant la [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifiée. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Multiplie la [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui représente la transformation géométrique locale de ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) par la [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifiée dans l'ordre spécifié. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Translater la transformation géométrique locale par les dimensions spécifiées. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Translater la transformation géométrique locale par les dimensions spécifiées dans l'ordre spécifié. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Met à l'échelle la transformation géométrique locale par les quantités spécifiées. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Met à l'échelle la transformation géométrique locale par les quantités spécifiées dans l'ordre spécifié. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Fait pivoter la transformation géométrique locale par la quantité spécifiée. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Fait pivoter la transformation géométrique locale par la quantité spécifiée dans l'ordre spécifié. |
### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) avec les points et les couleurs spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | Une structure [PointF](../../com.aspose.drawing/pointf) qui représente le point de départ du dégradé linéaire. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | Une structure [PointF](../../com.aspose.drawing/pointf) qui représente le point final du dégradé linéaire. |
| color1 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur de départ du dégradé linéaire. |
| color2 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur finale du dégradé linéaire. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) avec les points et les couleurs spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | Une structure [Point](../../com.aspose.drawing/point) qui représente le point de départ du dégradé linéaire. |
| point2 | [Point](../../com.aspose.drawing/point) | Une structure [Point](../../com.aspose.drawing/point) qui représente le point final du dégradé linéaire. |
| color1 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur de départ du dégradé linéaire. |
| color2 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur finale du dégradé linéaire. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)
```


Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basée sur un rectangle, des couleurs de départ et d'arrivée, et un mode d'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Une structure [RectangleF](../../com.aspose.drawing/rectanglef) qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur de départ du dégradé. |
| color2 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur finale du dégradé. |
| linearGradientMode | int | Un élément d'énumération [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) qui spécifie l'orientation du dégradé. L'orientation détermine les points de départ et d'arrivée du dégradé. Par exemple, LinearGradientMode.ForwardDiagonal indique que le point de départ est le coin supérieur gauche du rectangle et que le point d'arrivée est le coin inférieur droit du rectangle. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)
```


Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basée sur un rectangle, des couleurs de départ et d'arrivée, et une orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Une structure `Rectangle`([.getRectangle](../../null/\#getRectangle)) qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur de départ du dégradé. |
| color2 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur finale du dégradé. |
| linearGradientMode | int | Un élément d'énumération [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) qui spécifie l'orientation du dégradé. L'orientation détermine les points de départ et d'arrivée du dégradé. Par exemple, LinearGradientMode.ForwardDiagonal indique que le point de départ est le coin supérieur gauche du rectangle et que le point d'arrivée est le coin inférieur droit du rectangle. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Une structure [RectangleF](../../com.aspose.drawing/rectanglef) qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur de départ du dégradé. |
| color2 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur finale du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens des aiguilles d'une montre à partir de l'axe x, de la ligne d'orientation du dégradé. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Une structure [RectangleF](../../com.aspose.drawing/rectanglef) qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur de départ du dégradé. |
| color2 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur finale du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens des aiguilles d'une montre à partir de l'axe x, de la ligne d'orientation du dégradé. |
| isAngleScaleable | boolean | Définissez à true pour indiquer que l'angle est affecté par la transformation associée à ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) ; sinon, false. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Une structure `Rectangle`([.getRectangle](../../null/\#getRectangle)) qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur de départ du dégradé. |
| color2 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur finale du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens des aiguilles d'une montre à partir de l'axe x, de la ligne d'orientation du dégradé. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Une structure `Rectangle`([.getRectangle](../../null/\#getRectangle)) qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur de départ du dégradé. |
| color2 | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur finale du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens des aiguilles d'une montre à partir de l'axe x, de la ligne d'orientation du dégradé. |
| isAngleScaleable | boolean | Définissez à true pour indiquer que l'angle est affecté par la transformation associée à ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) ; sinon, false. |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Obtient ou définit les couleurs de départ et d'arrivée du dégradé.

**Returns:**
com.aspose.drawing.Color[]
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.drawing.Color---}
```
public void setLinearColors(Color[] value)
```


Obtient ou définit les couleurs de départ et d'arrivée du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Obtient une région rectangulaire qui définit les points de départ et d'arrivée du dégradé.

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Obtient ou définit une valeur indiquant si la correction gamma est activée pour ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
boolean
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Obtient ou définit une valeur indiquant si la correction gamma est activée pour ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtient ou définit une énumération `WrapMode` qui indique le mode d'enroulement pour ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtient ou définit une énumération `WrapMode` qui indique le mode d'enroulement pour ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtient ou définit une copie de [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui définit une transformation géométrique locale pour ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Obtient ou définit une copie de [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui définit une transformation géométrique locale pour ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crée une copie exacte de ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
java.lang.Object - Le [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) créé par cette méthode, casté en tant qu'objet.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Crée une atténuation du dégradé basée sur une courbe en cloche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où la couleur de départ et la couleur d'arrivée sont mélangées à parts égales). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crée une atténuation du dégradé basée sur une courbe en cloche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où le dégradé est composé uniquement de la couleur d'arrivée). |
| scale | float | Une valeur comprise entre 0 et 1 qui spécifie la rapidité avec laquelle les couleurs diminuent à partir du `focus`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une couleur unique aux deux extrémités.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où le dégradé est composé uniquement de la couleur d'arrivée). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une couleur unique aux deux extrémités.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où le dégradé est composé uniquement de la couleur d'arrivée). |
| scale | float | Une valeur comprise entre 0 et 1 qui spécifie la rapidité avec laquelle les couleurs diminuent de la couleur de départ vers le `focus` (couleur d'arrivée). |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Réinitialise la propriété `LinearGradientBrush.Transform` à l'identité.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplie la [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui représente la transformation géométrique locale de ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) par la [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifiée en préfixant la [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | La [Matrix](../../com.aspose.drawing.drawing2d/matrix) par laquelle multiplier la transformation géométrique. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplie la [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui représente la transformation géométrique locale de ce [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) par la [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifiée dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | La [Matrix](../../com.aspose.drawing.drawing2d/matrix) par laquelle multiplier la transformation géométrique. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) qui spécifie dans quel ordre multiplier les deux matrices. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Translater la transformation géométrique locale selon les dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Translater la transformation géométrique locale par les dimensions spécifiées dans l'ordre spécifié.

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
| sx | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Met à l'échelle la transformation géométrique locale par les quantités spécifiées dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe y. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) qui indique s'il faut ajouter ou préfixer la matrice d'échelle. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Fait pivoter la transformation géométrique locale de la quantité spécifiée. Cette méthode préfixe la rotation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Fait pivoter la transformation géométrique locale par la quantité spécifiée dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) qui indique s'il faut ajouter ou préfixer la matrice de rotation. |

