---
title: TextureBrush
second_title: Référence de l'API Aspose.Drawing pour Java
description: Chaque propriété de la classe TextureBrush est un objet Brush qui utilise une image pour remplir l'intérieur d'une forme.
type: docs
weight: 53
url: /fr/java/com.aspose.drawing/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class TextureBrush extends Brush
```

Chaque propriété de la classe TextureBrush est un objet Brush qui utilise une image pour remplir l'intérieur d'une forme. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextureBrush(Image bitmap)](#TextureBrush-com.aspose.drawing.Image-) | Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.drawing/texturebrush) qui utilise l'image spécifiée. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.drawing.Image-int-) | Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.drawing/texturebrush) qui utilise l'image spécifiée et le mode d'enroulement. |
| [TextureBrush(Image image, int wrapMode, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-) | Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.drawing/texturebrush) qui utilise l'image spécifiée, le mode d'enroulement et le rectangle de délimitation. |
| [TextureBrush(Image image, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-) | Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.drawing/texturebrush) qui utilise l'image spécifiée, et le rectangle englobant. |
| [TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-) | Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.drawing/texturebrush) qui utilise l'image spécifiée, le rectangle englobant et les attributs d'image. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getImage()](#getImage--) | Obtient l'objet Image associé à cet objet TextureBrush. |
| [getTransform()](#getTransform--) | Obtient une copie de l'objet Matrix qui définit une transformation géométrique locale pour l'image associée à cet objet TextureBrush. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Définit une copie de l'objet Matrix qui définit une transformation géométrique locale pour l'image associée à cet objet TextureBrush. |
| [getWrapMode()](#getWrapMode--) | Obtient une énumération WrapMode qui indique le mode d'habillage pour cet objet TextureBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | Définit une énumération WrapMode qui indique le mode d'habillage pour cet objet TextureBrush. |
| [deepClone()](#deepClone--) | Crée une copie exacte de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush). |
| [resetTransform()](#resetTransform--) | Réinitialise la propriété Transform de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) à l'identité. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Multiplie l'objet [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui représente la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) par l'objet [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifié en le préfixant. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Multiplie l'objet [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui représente la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) par l'objet [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifié dans l'ordre indiqué. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Déplace la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) selon les dimensions spécifiées. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Déplace la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) selon les dimensions spécifiées dans l'ordre indiqué. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Redimensionne la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) selon les valeurs spécifiées. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Redimensionne la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) selon les valeurs spécifiées dans l'ordre indiqué. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Fait pivoter la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) de la valeur spécifiée. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Fait pivoter la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) de la valeur spécifiée dans l'ordre indiqué. |
### TextureBrush(Image bitmap) {#TextureBrush-com.aspose.drawing.Image-}
```
public TextureBrush(Image bitmap)
```


Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.drawing/texturebrush) qui utilise l'image spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitmap | [Image](../../com.aspose.drawing/image) | L'objet `Image`([.getImage](../../null/\#getImage)) avec lequel cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) remplit les intérieurs. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.drawing.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.drawing/texturebrush) qui utilise l'image spécifiée et le mode d'enroulement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | L'image. |
| wrapMode | int | Une énumération `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) qui spécifie comment cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) est disposé en mosaïque. |

### TextureBrush(Image image, int wrapMode, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF dstRect)
```


Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.drawing/texturebrush) qui utilise l'image spécifiée, le mode d'enroulement et le rectangle de délimitation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | L'image. |
| wrapMode | int | Une énumération `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) qui spécifie comment cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) est disposé en mosaïque. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Une structure [RectangleF](../../com.aspose.drawing/rectanglef) qui représente le rectangle englobant de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush). |

### TextureBrush(Image image, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, RectangleF dstRect)
```


Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.drawing/texturebrush) qui utilise l'image spécifiée, et le rectangle englobant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | L'objet `Image`([.getImage](../../null/\#getImage)) avec lequel cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) remplit les intérieurs. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Une structure [RectangleF](../../com.aspose.drawing/rectanglef) qui représente le rectangle englobant de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush). |

### TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)
```


Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.drawing/texturebrush) qui utilise l'image spécifiée, le rectangle englobant et les attributs d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | L'objet Image avec lequel cet objet TextureBrush remplit les intérieurs. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Une structure RectangleF qui représente le rectangle englobant de cet objet TextureBrush. |
| imageAttr | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) | Un objet ImageAttributes qui contient des informations supplémentaires sur l'image utilisée par cet objet TextureBrush. |

### getImage() {#getImage--}
```
public Image getImage()
```


Obtient l'objet Image associé à cet objet TextureBrush.

**Returns:**
[Image](../../com.aspose.drawing/image) - the Image object associated with this TextureBrush object.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtient une copie de l'objet Matrix qui définit une transformation géométrique locale pour l'image associée à cet objet TextureBrush.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - a copy of the Matrix object that defines a local geometric transformation for the image associated with this TextureBrush object.
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Définit une copie de l'objet Matrix qui définit une transformation géométrique locale pour l'image associée à cet objet TextureBrush.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | une copie de l'objet Matrix qui définit une transformation géométrique locale pour l'image associée à cet objet TextureBrush. |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtient une énumération WrapMode qui indique le mode d'habillage pour cet objet TextureBrush.

**Returns:**
int - une énumération WrapMode qui indique le mode d'enroulement pour cet objet TextureBrush.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Définit une énumération WrapMode qui indique le mode d'habillage pour cet objet TextureBrush.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | une énumération WrapMode qui indique le mode d'enroulement pour cet objet TextureBrush. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crée une copie exacte de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush).

**Returns:**
java.lang.Object - L'objet [TextureBrush](../../com.aspose.drawing/texturebrush) que cette méthode crée, casté en tant qu'objet Object.
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Réinitialise la propriété Transform de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) à l'identité.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplie l'objet [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui représente la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) par l'objet [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifié en le préfixant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | L'objet [Matrix](../../com.aspose.drawing.drawing2d/matrix) par lequel multiplier la transformation géométrique. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplie l'objet [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui représente la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) par l'objet [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifié dans l'ordre indiqué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | L'objet [Matrix](../../com.aspose.drawing.drawing2d/matrix) par lequel multiplier la transformation géométrique. |
| order | int | Une énumération [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) qui spécifie l'ordre dans lequel multiplier les deux matrices. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Translater la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) selon les dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La dimension selon laquelle déplacer la transformation dans la direction x. |
| dy | float | La dimension selon laquelle déplacer la transformation dans la direction y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Déplace la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) selon les dimensions spécifiées dans l'ordre indiqué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La dimension selon laquelle déplacer la transformation dans la direction x. |
| dy | float | La dimension selon laquelle déplacer la transformation dans la direction y. |
| order | int | L'ordre (préfixer ou ajouter) dans lequel appliquer la translation. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Met à l'échelle la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) selon les valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | La quantité selon laquelle mettre à l'échelle la transformation dans la direction x. |
| sy | float | La quantité selon laquelle mettre à l'échelle la transformation dans la direction y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Redimensionne la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) selon les valeurs spécifiées dans l'ordre indiqué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | La quantité selon laquelle mettre à l'échelle la transformation dans la direction x. |
| sy | float | La quantité selon laquelle mettre à l'échelle la transformation dans la direction y. |
| order | int | Une énumération [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) qui spécifie s'il faut ajouter ou préfixer la matrice d'échelle. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Faire pivoter la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) selon la quantité spécifiée. Cette méthode préfixe la rotation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Fait pivoter la transformation géométrique locale de cet objet [TextureBrush](../../com.aspose.drawing/texturebrush) de la valeur spécifiée dans l'ordre indiqué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |
| order | int | Une énumération [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) qui spécifie s'il faut ajouter ou préfixer la matrice de rotation. |

