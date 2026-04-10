---
title: Pen
second_title: Référence de l'API Aspose.Drawing pour Java
description: Définit un objet utilisé pour dessiner des lignes et des courbes.
type: docs
weight: 34
url: /fr/java/com.aspose.drawing/pen/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class Pen implements System.IDisposable
```

Définit un objet utilisé pour dessiner des lignes et des courbes.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.drawing.Color-) | Initialise une nouvelle instance de la classe [Pen](../../com.aspose.drawing/pen) avec la `Color` spécifiée([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)). |
| [Pen(Brush brush, float width)](#Pen-com.aspose.drawing.Brush-float-) | Initialise une nouvelle instance de la classe Pen avec le Brush et la Width spécifiés. |
| [Pen(Brush brush)](#Pen-com.aspose.drawing.Brush-) | Initialise une nouvelle instance de la classe [Pen](../../com.aspose.drawing/pen) avec le `Brush` spécifié([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)). |
| [Pen(Color color, float width)](#Pen-com.aspose.drawing.Color-float-) | Initialise une nouvelle instance de la classe Pen avec les propriétés Color et Width spécifiées. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColor()](#getColor--) | Obtient ou définit la couleur de ce [Pen](../../com.aspose.drawing/pen). |
| [setColor(Color value)](#setColor-com.aspose.drawing.Color-) | Obtient ou définit la couleur de ce [Pen](../../com.aspose.drawing/pen). |
| [getBrush()](#getBrush--) | Obtient ou définit le Brush qui détermine les attributs de ce [Pen](../../com.aspose.drawing/pen). |
| [setBrush(Brush value)](#setBrush-com.aspose.drawing.Brush-) | Obtient ou définit le Brush qui détermine les attributs de ce [Pen](../../com.aspose.drawing/pen). |
| [getCompoundArray()](#getCompoundArray--) | Obtient ou définit un tableau de valeurs qui spécifie un pen composé. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Obtient ou définit un tableau de valeurs qui spécifie un pen composé. |
| [getWidth()](#getWidth--) | Obtient ou définit la largeur de ce Pen, en unités de l'objet Graphics utilisé pour le dessin. |
| [setWidth(float value)](#setWidth-float-) | Obtient ou définit la largeur de ce Pen, en unités de l'objet Graphics utilisé pour le dessin. |
| [getStartCap()](#getStartCap--) | Obtient ou définit le style de bouchon utilisé au début des lignes tracées avec ce Pen. |
| [setStartCap(int value)](#setStartCap-int-) | Obtient ou définit le style de bouchon utilisé au début des lignes tracées avec ce Pen. |
| [getEndCap()](#getEndCap--) | Obtient ou définit le style de bouchon utilisé à la fin des lignes tracées avec ce Pen. |
| [setEndCap(int value)](#setEndCap-int-) | Obtient ou définit le style de bouchon utilisé à la fin des lignes tracées avec ce Pen. |
| [getLineJoin()](#getLineJoin--) | Obtient ou définit le style de jointure pour les extrémités de deux lignes consécutives tracées avec ce Pen. |
| [setLineJoin(int value)](#setLineJoin-int-) | Obtient ou définit le style de jointure pour les extrémités de deux lignes consécutives tracées avec ce Pen. |
| [getMiterLimit()](#getMiterLimit--) | Obtient ou définit la limite de l'épaisseur de la jointure sur un coin en onglet. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Obtient ou définit la limite de l'épaisseur de la jointure sur un coin en onglet. |
| [getAlignment()](#getAlignment--) | Obtient ou définit l'alignement de ce [Pen](../../com.aspose.drawing/pen). |
| [setAlignment(int value)](#setAlignment-int-) | Obtient ou définit l'alignement de ce [Pen](../../com.aspose.drawing/pen). |
| [getTransform()](#getTransform--) | Obtient ou définit une copie de la transformation géométrique de ce [Pen](../../com.aspose.drawing/pen). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Obtient ou définit une copie de la transformation géométrique de ce [Pen](../../com.aspose.drawing/pen). |
| [getCustomStartCap()](#getCustomStartCap--) | Obtient ou définit un bouchon personnalisé à utiliser au début des lignes tracées avec ce [Pen](../../com.aspose.drawing/pen). |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Obtient ou définit un bouchon personnalisé à utiliser au début des lignes tracées avec ce [Pen](../../com.aspose.drawing/pen). |
| [getCustomEndCap()](#getCustomEndCap--) | Obtient ou définit un bouchon personnalisé à utiliser à la fin des lignes tracées avec ce [Pen](../../com.aspose.drawing/pen). |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Obtient ou définit un bouchon personnalisé à utiliser à la fin des lignes tracées avec ce [Pen](../../com.aspose.drawing/pen). |
| [getDashCap()](#getDashCap--) | Obtient ou définit le style de bouchon utilisé à la fin des tirets qui composent les lignes pointillées tracées avec ce [Pen](../../com.aspose.drawing/pen). |
| [setDashCap(int value)](#setDashCap-int-) | Obtient ou définit le style de bouchon utilisé à la fin des tirets qui composent les lignes pointillées tracées avec ce [Pen](../../com.aspose.drawing/pen). |
| [getDashOffset()](#getDashOffset--) | Obtient ou définit la distance du début d'une ligne au commencement d'un motif de tiret. |
| [setDashOffset(float value)](#setDashOffset-float-) | Obtient ou définit la distance du début d'une ligne au commencement d'un motif de tiret. |
| [getDashPattern()](#getDashPattern--) | Obtient ou définit un tableau de tirets et d'espaces personnalisés. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Obtient ou définit un tableau de tirets et d'espaces personnalisés. |
| [getDashStyle()](#getDashStyle--) | Obtient ou définit le style utilisé pour les lignes pointillées tracées avec ce [Pen](../../com.aspose.drawing/pen). |
| [setDashStyle(int value)](#setDashStyle-int-) | Obtient ou définit le style utilisé pour les lignes pointillées tracées avec ce [Pen](../../com.aspose.drawing/pen). |
| [getPenType()](#getPenType--) | Obtient le style des lignes tracées avec ce Pen. |
| [dispose()](#dispose--) | Libère toutes les ressources utilisées par ce Pen. |
| [deepClone()](#deepClone--) | Crée une copie exacte de ce [Pen](../../com.aspose.drawing/pen). |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Définit les valeurs qui déterminent le style de cap utilisé pour terminer les lignes tracées par ce [Pen](../../com.aspose.drawing/pen). |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Met à l'échelle la transformation géométrique locale par les facteurs spécifiés. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Met à l'échelle la transformation géométrique locale par les facteurs spécifiés dans l'ordre spécifié. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Translater la transformation géométrique locale par les dimensions spécifiées. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Translater la transformation géométrique locale par les dimensions spécifiées dans l'ordre spécifié. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Pivote la transformation géométrique locale de l'angle spécifié. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Pivote la transformation géométrique locale de l'angle spécifié dans l'ordre spécifié. |
| [resetTransform()](#resetTransform--) | Réinitialise la matrice de transformation géométrique de ce [Pen](../../com.aspose.drawing/pen) à l'identité. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Multiplie la matrice de transformation de ce [Pen](../../com.aspose.drawing/pen) par la [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifiée. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Multiplie la matrice de transformation de ce [Pen](../../com.aspose.drawing/pen) par la [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifiée dans l'ordre spécifié. |
### Pen(Color color) {#Pen-com.aspose.drawing.Color-}
```
public Pen(Color color)
```


Initialise une nouvelle instance de la classe [Pen](../../com.aspose.drawing/pen) avec la `Color` spécifiée([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Un `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) qui détermine les propriétés de remplissage de ce [Pen](../../com.aspose.drawing/pen). |

### Pen(Brush brush, float width) {#Pen-com.aspose.drawing.Brush-float-}
```
public Pen(Brush brush, float width)
```


Initialise une nouvelle instance de la classe Pen avec le Brush et la Width spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Un Brush qui détermine les caractéristiques de ce Pen. |
| largeur | float | La largeur du nouveau Pen. |

### Pen(Brush brush) {#Pen-com.aspose.drawing.Brush-}
```
public Pen(Brush brush)
```


Initialise une nouvelle instance de la classe [Pen](../../com.aspose.drawing/pen) avec le `Brush` spécifié([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Un `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)) qui détermine les propriétés de remplissage de ce [Pen](../../com.aspose.drawing/pen). |

### Pen(Color color, float width) {#Pen-com.aspose.drawing.Color-float-}
```
public Pen(Color color, float width)
```


Initialise une nouvelle instance de la classe Pen avec les propriétés Color et Width spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Une structure Color qui indique la couleur de ce Pen. |
| largeur | float | Une valeur indiquant la largeur de ce Pen. |

### getColor() {#getColor--}
```
public final Color getColor()
```


Obtient ou définit la couleur de ce [Pen](../../com.aspose.drawing/pen).

Valeur : une structure `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) qui représente la couleur de ce [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Color](../../com.aspose.drawing/color)
### setColor(Color value) {#setColor-com.aspose.drawing.Color-}
```
public final void setColor(Color value)
```


Obtient ou définit la couleur de ce [Pen](../../com.aspose.drawing/pen).

Valeur : une structure `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) qui représente la couleur de ce [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Obtient ou définit le Brush qui détermine les attributs de ce [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Brush](../../com.aspose.drawing/brush)
### setBrush(Brush value) {#setBrush-com.aspose.drawing.Brush-}
```
public final void setBrush(Brush value)
```


Obtient ou définit le Brush qui détermine les attributs de ce [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Brush](../../com.aspose.drawing/brush) |  |

### getCompoundArray() {#getCompoundArray--}
```
public final float[] getCompoundArray()
```


Obtient ou définit un tableau de valeurs qui spécifie un stylo composé. Un stylo composé trace une ligne composée de lignes parallèles et d'espaces.

**Returns:**
float[] - Un tableau de nombres réels qui spécifie le tableau composé. Les éléments du tableau doivent être en ordre croissant, pas inférieurs à 0, et pas supérieurs à 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public final void setCompoundArray(float[] value)
```


Obtient ou définit un tableau de valeurs qui spécifie un stylo composé. Un stylo composé trace une ligne composée de lignes parallèles et d'espaces.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Obtient ou définit la largeur de ce Pen, en unités de l'objet Graphics utilisé pour le dessin.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Obtient ou définit la largeur de ce Pen, en unités de l'objet Graphics utilisé pour le dessin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStartCap() {#getStartCap--}
```
public final int getStartCap()
```


Obtient ou définit le style de bouchon utilisé au début des lignes tracées avec ce Pen.

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public final void setStartCap(int value)
```


Obtient ou définit le style de bouchon utilisé au début des lignes tracées avec ce Pen.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public final int getEndCap()
```


Obtient ou définit le style de bouchon utilisé à la fin des lignes tracées avec ce Pen.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public final void setEndCap(int value)
```


Obtient ou définit le style de bouchon utilisé à la fin des lignes tracées avec ce Pen.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public final int getLineJoin()
```


Obtient ou définit le style de jointure pour les extrémités de deux lignes consécutives tracées avec ce Pen.

--------------------

Pour le moment, la jointure en onglet fonctionne en fait comme MiterClipped.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public final void setLineJoin(int value)
```


Obtient ou définit le style de jointure pour les extrémités de deux lignes consécutives tracées avec ce Pen.

--------------------

Pour le moment, la jointure en onglet fonctionne en fait comme MiterClipped.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


Obtient ou définit la limite de l'épaisseur de la jointure sur un coin en onglet.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


Obtient ou définit la limite de l'épaisseur de la jointure sur un coin en onglet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Obtient ou définit l'alignement de ce [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - Un [PenAlignment](../../com.aspose.drawing.drawing2d/penalignment) qui représente l'alignement de ce [Pen](../../com.aspose.drawing/pen).
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Obtient ou définit l'alignement de ce [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public final Matrix getTransform()
```


Obtient ou définit une copie de la transformation géométrique de ce [Pen](../../com.aspose.drawing/pen).

Valeur : une copie de la [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui représente la transformation géométrique de ce [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void setTransform(Matrix value)
```


Obtient ou définit une copie de la transformation géométrique de ce [Pen](../../com.aspose.drawing/pen).

Valeur : une copie de la [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui représente la transformation géométrique de ce [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getCustomStartCap() {#getCustomStartCap--}
```
public final CustomLineCap getCustomStartCap()
```


Obtient ou définit un bouchon personnalisé à utiliser au début des lignes tracées avec ce [Pen](../../com.aspose.drawing/pen).

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the beginning of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomStartCap(CustomLineCap value)
```


Obtient ou définit un bouchon personnalisé à utiliser au début des lignes tracées avec ce [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getCustomEndCap() {#getCustomEndCap--}
```
public final CustomLineCap getCustomEndCap()
```


Obtient ou définit un bouchon personnalisé à utiliser à la fin des lignes tracées avec ce [Pen](../../com.aspose.drawing/pen).

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the end of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomEndCap(CustomLineCap value)
```


Obtient ou définit un bouchon personnalisé à utiliser à la fin des lignes tracées avec ce [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getDashCap() {#getDashCap--}
```
public final int getDashCap()
```


Obtient ou définit le style de bouchon utilisé à la fin des tirets qui composent les lignes pointillées tracées avec ce [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - L'une des valeurs `DashCap`([.getDashCap](../../null/\#getDashCap)/[.setDashCap(int)](../../null/\#setDashCap-int-)) qui représente le style de cap utilisé au début et à la fin des tirets qui composent les lignes pointillées tracées avec ce [Pen](../../com.aspose.drawing/pen).
### setDashCap(int value) {#setDashCap-int-}
```
public final void setDashCap(int value)
```


Obtient ou définit le style de bouchon utilisé à la fin des tirets qui composent les lignes pointillées tracées avec ce [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public final float getDashOffset()
```


Obtient ou définit la distance du début d'une ligne au commencement d'un motif de tiret.

**Returns:**
float - La distance du début d'une ligne au début d'un motif de tirets.
### setDashOffset(float value) {#setDashOffset-float-}
```
public final void setDashOffset(float value)
```


Obtient ou définit la distance du début d'une ligne au commencement d'un motif de tiret.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDashPattern() {#getDashPattern--}
```
public final float[] getDashPattern()
```


Obtient ou définit un tableau de tirets et d'espaces personnalisés.

**Returns:**
float[] - Un tableau de nombres réels qui spécifie les longueurs des tirets et espaces alternés dans les lignes pointillées.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public final void setDashPattern(float[] value)
```


Obtient ou définit un tableau de tirets et d'espaces personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Obtient ou définit le style utilisé pour les lignes pointillées tracées avec ce [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - Un `DashStyle`([.getDashStyle](../../null/\#getDashStyle)/[.setDashStyle(int)](../../null/\#setDashStyle-int-)) qui représente le style utilisé pour les lignes pointillées tracées avec ce [Pen](../../com.aspose.drawing/pen).
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Obtient ou définit le style utilisé pour les lignes pointillées tracées avec ce [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPenType() {#getPenType--}
```
public final int getPenType()
```


Obtient le style des lignes tracées avec ce Pen.

Valeur : une énumération `PenType`([.getPenType](../../null/\#getPenType)) qui spécifie le style des lignes tracées avec ce [Pen](../../com.aspose.drawing/pen).

**Returns:**
int
### dispose() {#dispose--}
```
public final void dispose()
```


Libère toutes les ressources utilisées par ce Pen.

--------------------

Cette méthode ne fait en fait rien. Elle n'est là que pour la compatibilité avec l'API System.Drawing.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Crée une copie exacte de ce [Pen](../../com.aspose.drawing/pen).

**Returns:**
java.lang.Object - Un objet qui peut être converti en un [Pen](../../com.aspose.drawing/pen).
### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public final void setLineCap(int startCap, int endCap, int dashCap)
```


Définit les valeurs qui déterminent le style de cap utilisé pour terminer les lignes tracées par ce [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startCap | int | Un [LineCap](../../com.aspose.drawing.drawing2d/linecap) qui représente le style de terminaison à utiliser au début des lignes tracées avec ce [Pen](../../com.aspose.drawing/pen). |
| endCap | int | Un [LineCap](../../com.aspose.drawing.drawing2d/linecap) qui représente le style de terminaison à utiliser à la fin des lignes tracées avec ce [Pen](../../com.aspose.drawing/pen). |
| dashCap | int | Un [LineCap](../../com.aspose.drawing.drawing2d/linecap) qui représente le style de terminaison à utiliser au début ou à la fin des lignes pointillées tracées avec ce [Pen](../../com.aspose.drawing/pen). |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public final void scaleTransform(float sx, float sy)
```


Met à l'échelle la transformation géométrique locale par les facteurs spécifiés. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public final void scaleTransform(float sx, float sy, int order)
```


Met à l'échelle la transformation géométrique locale par les facteurs spécifiés dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe y. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) qui indique s'il faut ajouter ou préfixer la matrice d'échelle. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public final void translateTransform(float dx, float dy)
```


Effectue une translation de la transformation géométrique locale selon les dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public final void translateTransform(float dx, float dy, int order)
```


Translater la transformation géométrique locale par les dimensions spécifiées dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |
| order | int | L'ordre (préfixer ou ajouter) dans lequel appliquer la translation. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public final void rotateTransform(float angle)
```


Fait pivoter la transformation géométrique locale selon l'angle spécifié. Cette méthode préfixe la rotation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public final void rotateTransform(float angle, int order)
```


Pivote la transformation géométrique locale de l'angle spécifié dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) qui indique s'il faut ajouter ou préfixer la matrice de rotation. |

### resetTransform() {#resetTransform--}
```
public final void resetTransform()
```


Réinitialise la matrice de transformation géométrique de ce [Pen](../../com.aspose.drawing/pen) à l'identité.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void multiplyTransform(Matrix matrix)
```


Multiplie la matrice de transformation de ce [Pen](../../com.aspose.drawing/pen) par la [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | L'objet [Matrix](../../com.aspose.drawing.drawing2d/matrix) par lequel multiplier la matrice de transformation. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public final void multiplyTransform(Matrix matrix, int order)
```


Multiplie la matrice de transformation de ce [Pen](../../com.aspose.drawing/pen) par la [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifiée dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Le java.awt.geom.AffineTransform par lequel multiplier la matrice de transformation. |
| order | int | L'ordre dans lequel effectuer l'opération de multiplication. |

