---
title: Matrix
second_title: Référence de l'API Aspose.Drawing pour Java
description: Encapsule une matrice affine 3 × 3 qui représente une transformation géométrique.
type: docs
weight: 33
url: /fr/java/com.aspose.drawing.drawing2d/matrix/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Matrix implements System.IDisposable
```

Encapsule une matrice affine 3 × 3 qui représente une transformation géométrique. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Matrix()](#Matrix--) | Initialise une nouvelle instance de la classe Matrix comme matrice identité. |
| [Matrix(float m11, float m12, float m21, float m22, float dx, float dy)](#Matrix-float-float-float-float-float-float-) | Initialise une nouvelle instance de la classe Matrix avec les éléments spécifiés. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---) | Initialise une nouvelle instance de la classe [Matrix](../../com.aspose.drawing.drawing2d/matrix) correspondant à la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---) | Initialise une nouvelle instance de la classe [Matrix](../../com.aspose.drawing.drawing2d/matrix) correspondant à la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
## Champs

| Champ | Description |
| --- | --- |
| [IdentityTransform](#IdentityTransform) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getElements()](#getElements--) | Obtient un tableau de valeurs à virgule flottante qui représente les éléments de cette Matrix. |
| [isIdentity()](#isIdentity--) | Obtient une valeur indiquant si cette Matrix est la matrice identité. |
| [isInvertible()](#isInvertible--) | Obtient une valeur indiquant si cette Matrix est inversible. |
| [getOffsetX()](#getOffsetX--) | Obtient la valeur de translation x (la valeur dx, ou l'élément de la troisième ligne et première colonne) de cette Matrix. |
| [getOffsetY()](#getOffsetY--) | Obtient la valeur de translation y (la valeur `dy`, ou l'élément de la troisième ligne et deuxième colonne) de cette Matrix. |
| [dispose()](#dispose--) | Libère toutes les ressources utilisées par cette Matrix. |
| [deepClone()](#deepClone--) | Crée une copie exacte de cette Matrix. |
| [invert()](#invert--) | Inverse cette Matrix, si elle est inversible. |
| [translate(float offsetX, float offsetY)](#translate-float-float-) | Applique le vecteur de translation spécifié (offsetX et offsetY) à cette Matrix en préfixant le vecteur de translation. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Applique le vecteur de translation spécifié à cette Matrix dans l'ordre spécifié. |
| [transformVectors(PointF[] pts)](#transformVectors-com.aspose.drawing.PointF---) | Multiplie chaque vecteur d'un tableau par cette Matrix. |
| [scale(float scaleX, float scaleY)](#scale-float-float-) | Applique le vecteur d'échelle spécifié à cette Matrix en préfixant le vecteur d'échelle. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette Matrix en utilisant l'ordre spécifié. |
| [shear(float shearX, float shearY)](#shear-float-float-) | Applique le vecteur de cisaillement spécifié à cette Matrix en préfixant la transformation de cisaillement. |
| [shear(float shearX, float shearY, int order)](#shear-float-float-int-) | Applique le vecteur de cisaillement spécifié à cette Matrix dans l'ordre spécifié. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.drawing.PointF-) | Applique une rotation horaire à cette Matrix autour du point spécifié dans le paramètre point, et en préfixant la rotation. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.drawing.PointF-int-) | Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre spécifié. |
| [transformPoints(PointF[] pts)](#transformPoints-com.aspose.drawing.PointF---) | Applique la transformation géométrique représentée par cette [Matrix](../../com.aspose.drawing.drawing2d/matrix) à un tableau de points spécifié. |
| [transformPoints(Point[] pts)](#transformPoints-com.aspose.drawing.Point---) | Applique la transformation géométrique représentée par cette [Matrix](../../com.aspose.drawing.drawing2d/matrix) à un tableau de points spécifié. |
| [multiply(Matrix matrix)](#multiply-com.aspose.drawing.drawing2d.Matrix-) | Multiplie cette [Matrix](../../com.aspose.drawing.drawing2d/matrix) par la matrice spécifiée dans le paramètre `matrix`, en préfixant la [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifiée. |
| [multiply(Matrix matrix, int order)](#multiply-com.aspose.drawing.drawing2d.Matrix-int-) | Multiplie cette [Matrix](../../com.aspose.drawing.drawing2d/matrix) par la matrice spécifiée dans le paramètre `matrix`, et dans l'ordre spécifié dans le paramètre `order`. |
| [rotate(float angle)](#rotate-float-) | Préfixe à cette [Matrix](../../com.aspose.drawing.drawing2d/matrix) une rotation horaire, autour de l'origine et selon l'angle spécifié. |
| [rotate(float angle, int order)](#rotate-float-int-) | Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [reset()](#reset--) | Réinitialise cette [Matrix](../../com.aspose.drawing.drawing2d/matrix) pour qu'elle contienne les éléments de la matrice identité. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Initialise une nouvelle instance de la classe Matrix comme matrice identité.

### Matrix(float m11, float m12, float m21, float m22, float dx, float dy) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


Initialise une nouvelle instance de la classe Matrix avec les éléments spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| m11 | float | La valeur de la première ligne et première colonne de la nouvelle Matrix. |
| m12 | float | La valeur de la première ligne et deuxième colonne de la nouvelle Matrix. |
| m21 | float | La valeur dans la deuxième ligne et première colonne de la nouvelle Matrix. |
| m22 | float | La valeur dans la deuxième ligne et deuxième colonne de la nouvelle Matrix. |
| dx | float | La valeur dans la troisième ligne et première colonne de la nouvelle Matrix. |
| dy | float | La valeur dans la troisième ligne et deuxième colonne de la nouvelle Matrix. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Initialise une nouvelle instance de la classe [Matrix](../../com.aspose.drawing.drawing2d/matrix) correspondant à la transformation géométrique définie par le rectangle spécifié et le tableau de points.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Une structure [Rectangle](../../com.aspose.drawing/rectangle) qui représente le rectangle à transformer. |
| plgpts | [Point\[\]](../../com.aspose.drawing/point) | Un tableau de trois structures [Point](../../com.aspose.drawing/point) qui représente les points d'un parallélogramme vers lequel les coins supérieur gauche, supérieur droit et inférieur gauche du rectangle doivent être transformés. Le coin inférieur droit du parallélogramme est implicite à partir des trois premiers coins. |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Initialise une nouvelle instance de la classe [Matrix](../../com.aspose.drawing.drawing2d/matrix) correspondant à la transformation géométrique définie par le rectangle spécifié et le tableau de points.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Une structure [RectangleF](../../com.aspose.drawing/rectanglef) qui représente le rectangle à transformer. |
| plgpts | [PointF\[\]](../../com.aspose.drawing/pointf) | Un tableau de trois structures [PointF](../../com.aspose.drawing/pointf) qui représente les points d'un parallélogramme vers lequel les coins supérieur gauche, supérieur droit et inférieur gauche du rectangle doivent être transformés. Le coin inférieur droit du parallélogramme est implicite à partir des trois premiers coins. |

### IdentityTransform {#IdentityTransform}
```
public static final Matrix IdentityTransform
```


### getElements() {#getElements--}
```
public float[] getElements()
```


Obtient un tableau de valeurs à virgule flottante qui représente les éléments de cette Matrix.

**Returns:**
float[] - un tableau de valeurs à virgule flottante qui représente les éléments de cette Matrix.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Obtient une valeur indiquant si cette Matrix est la matrice identité.

**Returns:**
boolean - une valeur indiquant si cette Matrix est la matrice identité.
### isInvertible() {#isInvertible--}
```
public boolean isInvertible()
```


Obtient une valeur indiquant si cette Matrix est inversible.

**Returns:**
boolean - une valeur indiquant si cette Matrix est inversible.
### getOffsetX() {#getOffsetX--}
```
public float getOffsetX()
```


Obtient la valeur de translation x (la valeur dx, ou l'élément de la troisième ligne et première colonne) de cette Matrix.

**Returns:**
float - la valeur de translation x (la valeur dx, ou l'élément de la troisième ligne et première colonne) de cette Matrix.
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```


Obtient la valeur de translation y (la valeur `dy`, ou l'élément de la troisième ligne et deuxième colonne) de cette Matrix.

**Returns:**
float - la valeur de translation y (la valeur `dy`, ou l'élément de la troisième ligne et deuxième colonne) de cette Matrix.
### dispose() {#dispose--}
```
public void dispose()
```


Libère toutes les ressources utilisées par cette Matrix.

--------------------

Cette méthode ne fait en fait rien. Elle n'est là que pour la compatibilité avec l'API System.Drawing.

### deepClone() {#deepClone--}
```
public Matrix deepClone()
```


Crée une copie exacte de cette Matrix.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - The Matrix that this method creates.
### invert() {#invert--}
```
public void invert()
```


Inverse cette Matrix, si elle est inversible.

### translate(float offsetX, float offsetY) {#translate-float-float-}
```
public void translate(float offsetX, float offsetY)
```


Applique le vecteur de translation spécifié (offsetX et offsetY) à cette Matrix en préfixant le vecteur de translation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| offsetX | float | La valeur x par laquelle translater cette Matrix. |
| offsetY | float | La valeur y par laquelle translater cette Matrix. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Applique le vecteur de translation spécifié à cette Matrix dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| offsetX | float | La valeur x par laquelle translater cette Matrix. |
| offsetY | float | La valeur y par laquelle translater cette Matrix. |
| order | int | Un MatrixOrder qui spécifie l'ordre (ajout ou insertion) dans lequel la translation est appliquée à cette Matrix. |

### transformVectors(PointF[] pts) {#transformVectors-com.aspose.drawing.PointF---}
```
public void transformVectors(PointF[] pts)
```


Multiplie chaque vecteur d'un tableau par la Matrix. Les éléments de translation de cette Matrix (troisième ligne) sont ignorés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Un tableau de structures [PointF](../../com.aspose.drawing/pointf) qui représente les points à transformer. |

### scale(float scaleX, float scaleY) {#scale-float-float-}
```
public void scale(float scaleX, float scaleY)
```


Applique le vecteur d'échelle spécifié à cette Matrix en préfixant le vecteur d'échelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scaleX | float | La valeur par laquelle mettre à l'échelle cette Matrix dans la direction de l'axe x. |
| scaleY | float | La valeur par laquelle mettre à l'échelle cette matrice dans la direction de l'axe y. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette Matrix en utilisant l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scaleX | float | La valeur par laquelle mettre à l'échelle cette Matrix dans la direction de l'axe x. |
| scaleY | float | La valeur par laquelle mettre à l'échelle cette matrice dans la direction de l'axe y. |
| order | int | Un MatrixOrder qui spécifie l'ordre (ajout ou préfixe) dans lequel le vecteur d'échelle est appliqué à cette matrice. |

### shear(float shearX, float shearY) {#shear-float-float-}
```
public void shear(float shearX, float shearY)
```


Applique le vecteur de cisaillement spécifié à cette Matrix en préfixant la transformation de cisaillement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shearX | float | Le facteur de cisaillement horizontal. |
| shearY | float | Le facteur de cisaillement vertical. |

### shear(float shearX, float shearY, int order) {#shear-float-float-int-}
```
public void shear(float shearX, float shearY, int order)
```


Applique le vecteur de cisaillement spécifié à cette Matrix dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shearX | float | Le facteur de cisaillement horizontal. |
| shearY | float | Le facteur de cisaillement vertical. |
| order | int | Un MatrixOrder qui spécifie l'ordre (ajout ou préfixe) dans lequel le cisaillement est appliqué. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.drawing.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Applique une rotation horaire à cette Matrix autour du point spécifié dans le paramètre point, et en préfixant la rotation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle (amplitude) de la rotation, en degrés. |
| point | [PointF](../../com.aspose.drawing/pointf) | Un PointF qui représente le centre de la rotation. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.drawing.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de la rotation, en degrés. |
| point | [PointF](../../com.aspose.drawing/pointf) | Un PointF qui représente le centre de la rotation. |
| order | int | Un MatrixOrder qui spécifie l'ordre (ajout ou préfixe) dans lequel la rotation est appliquée. |

### transformPoints(PointF[] pts) {#transformPoints-com.aspose.drawing.PointF---}
```
public void transformPoints(PointF[] pts)
```


Applique la transformation géométrique représentée par cette [Matrix](../../com.aspose.drawing.drawing2d/matrix) à un tableau de points spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Un tableau de structures [PointF](../../com.aspose.drawing/pointf) qui représente les points à transformer. |

### transformPoints(Point[] pts) {#transformPoints-com.aspose.drawing.Point---}
```
public void transformPoints(Point[] pts)
```


Applique la transformation géométrique représentée par cette [Matrix](../../com.aspose.drawing.drawing2d/matrix) à un tableau de points spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pts | [Point\[\]](../../com.aspose.drawing/point) | Un tableau de structures [Point](../../com.aspose.drawing/point) qui représente les points à transformer. |

### multiply(Matrix matrix) {#multiply-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiply(Matrix matrix)
```


Multiplie cette [Matrix](../../com.aspose.drawing.drawing2d/matrix) par la matrice spécifiée dans le paramètre `matrix`, en préfixant la [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Le [Matrix](../../com.aspose.drawing.drawing2d/matrix) par lequel ce [Matrix](../../com.aspose.drawing.drawing2d/matrix) doit être multiplié. |

### multiply(Matrix matrix, int order) {#multiply-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiply(Matrix matrix, int order)
```


Multiplie cette [Matrix](../../com.aspose.drawing.drawing2d/matrix) par la matrice spécifiée dans le paramètre `matrix`, et dans l'ordre spécifié dans le paramètre `order`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Le [Matrix](../../com.aspose.drawing.drawing2d/matrix) par lequel ce [Matrix](../../com.aspose.drawing.drawing2d/matrix) doit être multiplié. |
| order | int | Le [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) qui représente l'ordre de la multiplication. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Préfixe à cette [Matrix](../../com.aspose.drawing.drawing2d/matrix) une rotation horaire, autour de l'origine et selon l'angle spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de la rotation, en degrés. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de la rotation, en degrés. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) qui spécifie l'ordre (ajout ou préfixe) dans lequel la rotation est appliquée à ce [Matrix](../../com.aspose.drawing.drawing2d/matrix). |

### reset() {#reset--}
```
public void reset()
```


Réinitialise cette [Matrix](../../com.aspose.drawing.drawing2d/matrix) pour qu'elle contienne les éléments de la matrice identité.

