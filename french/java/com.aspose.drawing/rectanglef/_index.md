---
title: RectangleF
second_title: Référence de l'API Aspose.Drawing pour Java
description: Stocke un ensemble de quatre nombres à virgule flottante qui représentent la position et la taille d'un rectangle.
type: docs
weight: 39
url: /fr/java/com.aspose.drawing/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class RectangleF extends Struct<RectangleF> implements System.IEquatable<RectangleF>, Cloneable
```

Stocke un ensemble de quatre nombres à virgule flottante qui représentent la position et la taille d'un rectangle. Pour des fonctions de région plus avancées, utilisez un objet Region.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | Initialise une nouvelle instance de la structure RectangleF avec la position et la taille spécifiées. |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Initialise une nouvelle instance de la structure RectangleF avec la position et la taille spécifiées. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | Crée un nouveau rectangle à partir de deux points. |
| [to_RectangleF(Rectangle r)](#to-RectangleF-com.aspose.drawing.Rectangle-) | Convertit la structure Rectangle spécifiée en une structure RectangleF. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Teste si deux structures [RectangleF](../../com.aspose.drawing/rectanglef) ont la même position et la même taille. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Teste si deux structures [RectangleF](../../com.aspose.drawing/rectanglef) diffèrent en position ou en taille. |
| [fromLTRB(float left, float top, float right, float bottom)](#fromLTRB-float-float-float-float-) | Crée une structure RectangleF avec le coin supérieur gauche et le coin inférieur droit aux emplacements spécifiés. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.drawing.RectangleF-float-float-) | Crée et renvoie une copie gonflée de la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Renvoie une structure [RectangleF](../../com.aspose.drawing/rectanglef) qui représente l'intersection de deux rectangles. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Crée le plus petit rectangle possible qui peut contenir les deux rectangles formant une union. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si la propriété `RectangleF.Width` ou `RectangleF.Height` de ce [RectangleF](../../com.aspose.drawing/rectanglef) a une valeur de zéro. |
| [getX()](#getX--) | Obtient la coordonnée x du coin supérieur gauche de cette structure RectangleF. |
| [setX(float value)](#setX-float-) | Définit la coordonnée x du coin supérieur gauche de cette structure RectangleF. |
| [getY()](#getY--) | Obtient la coordonnée x du coin supérieur gauche de cette structure RectangleF. |
| [setY(float value)](#setY-float-) | Définit la coordonnée x du coin supérieur gauche de cette structure RectangleF. |
| [getLocation()](#getLocation--) | Obtient les coordonnées du coin supérieur gauche de cette structure [RectangleF](../../com.aspose.drawing/rectanglef). |
| [setLocation(PointF value)](#setLocation-com.aspose.drawing.PointF-) | Définit les coordonnées du coin supérieur gauche de cette structure [RectangleF](../../com.aspose.drawing/rectanglef). |
| [getWidth()](#getWidth--) | Obtient la largeur de cette structure RectangleF. |
| [setWidth(float value)](#setWidth-float-) | Définit la largeur de cette structure RectangleF. |
| [getHeight()](#getHeight--) | Obtient la hauteur de cette structure RectangleF. |
| [setHeight(float value)](#setHeight-float-) | Définit la hauteur de cette structure RectangleF. |
| [getSize()](#getSize--) | Obtient la taille de ce [RectangleF](../../com.aspose.drawing/rectanglef). |
| [setSize(SizeF value)](#setSize-com.aspose.drawing.SizeF-) | Définit la taille de ce [RectangleF](../../com.aspose.drawing/rectanglef). |
| [getLeft()](#getLeft--) | Obtient la coordonnée x du bord gauche de cette structure RectangleF. |
| [getTop()](#getTop--) | Obtient la coordonnée y du bord supérieur de cette structure RectangleF. |
| [getRight()](#getRight--) | Obtient la coordonnée x qui est la somme de X et de la largeur de cette structure RectangleF. |
| [getBottom()](#getBottom--) | Obtient la coordonnée y qui est la somme de Y et de la hauteur de cette structure RectangleF. |
| [toString()](#toString--) |  |
| [inflate(float x, float y)](#inflate-float-float-) | Agrandit cette structure [RectangleF](../../com.aspose.drawing/rectanglef) du montant spécifié. |
| [inflate(SizeF size)](#inflate-com.aspose.drawing.SizeF-) | Agrandit ce [RectangleF](../../com.aspose.drawing/rectanglef) du montant spécifié. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Remplace cette structure [RectangleF](../../com.aspose.drawing/rectanglef) par l'intersection d'elle-même et de la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.drawing.RectangleF-) | Détermine si ce rectangle intersecte `rect`. |
| [offset(PointF pos)](#offset-com.aspose.drawing.PointF-) | Ajuste la position de ce rectangle du montant spécifié. |
| [offset(float x, float y)](#offset-float-float-) | Ajuste la position de ce rectangle du montant spécifié. |
| [contains(float x, float y)](#contains-float-float-) | Détermine si le point spécifié est contenu dans cette structure [RectangleF](../../com.aspose.drawing/rectanglef). |
| [contains(PointF pt)](#contains-com.aspose.drawing.PointF-) | Détermine si le point spécifié est contenu dans cette structure [RectangleF](../../com.aspose.drawing/rectanglef). |
| [contains(RectangleF rect)](#contains-com.aspose.drawing.RectangleF-) | Détermine si la région rectangulaire représentée par `rect` est entièrement contenue dans cette structure [RectangleF](../../com.aspose.drawing/rectanglef). |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'objet spécifié est égal à cette instance. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
| [equals(RectangleF other)](#equals-com.aspose.drawing.RectangleF-) | Teste si une autre structure [RectangleF](../../com.aspose.drawing/rectanglef) a la même position et la même taille que cette structure [RectangleF](../../com.aspose.drawing/rectanglef). |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.drawing.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Initialise une nouvelle instance de la structure RectangleF avec la position et la taille spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| location | [PointF](../../com.aspose.drawing/pointf) | Un PointF qui représente le coin supérieur gauche de la région rectangulaire. |
| size | [SizeF](../../com.aspose.drawing/sizef) | Un SizeF qui représente la largeur et la hauteur de la région rectangulaire. |

### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Initialise une nouvelle instance de la structure RectangleF avec la position et la taille spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle. |
| largeur | float | La largeur du rectangle. |
| hauteur | float | La hauteur du rectangle. |

### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Crée un nouveau rectangle à partir de deux points. Le rectangle créé sera normalisé avec (left,top) inférieur à (right,bottom).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | Le premier point. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | Le deuxième point. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A newly created rectangle.
### to_RectangleF(Rectangle r) {#to-RectangleF-com.aspose.drawing.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle r)
```


Convertit la structure Rectangle spécifiée en une structure RectangleF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| r | [Rectangle](../../com.aspose.drawing/rectangle) | La structure Rectangle à convertir. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The RectangleF structure that is converted from the specified Rectangle structure.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Teste si deux structures [RectangleF](../../com.aspose.drawing/rectanglef) ont la même position et la même taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | La structure [RectangleF](../../com.aspose.drawing/rectanglef) qui se trouve à gauche de l'opérateur d'égalité. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | La structure [RectangleF](../../com.aspose.drawing/rectanglef) qui se trouve à droite de l'opérateur d'égalité. |

**Returns:**
booléen - Cet opérateur renvoie true si les deux structures [RectangleF](../../com.aspose.drawing/rectanglef) spécifiées ont des propriétés `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` et `RectangleF.Height` égales.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Teste si deux structures [RectangleF](../../com.aspose.drawing/rectanglef) diffèrent en position ou en taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | La structure [RectangleF](../../com.aspose.drawing/rectanglef) qui se trouve à gauche de l'opérateur d'inégalité. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | La structure [RectangleF](../../com.aspose.drawing/rectanglef) qui se trouve à droite de l'opérateur d'inégalité. |

**Returns:**
booléen - Cet opérateur renvoie true si l'une des propriétés `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` ou `RectangleF.Height` des deux structures [Rectangle](../../com.aspose.drawing/rectangle) est différente ; sinon false.
### fromLTRB(float left, float top, float right, float bottom) {#fromLTRB-float-float-float-float-}
```
public static RectangleF fromLTRB(float left, float top, float right, float bottom)
```


Crée une structure RectangleF avec le coin supérieur gauche et le coin inférieur droit aux emplacements spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gauche | float | La coordonnée x du coin supérieur gauche de la région rectangulaire. |
| haut | float | La coordonnée y du coin supérieur gauche de la région rectangulaire. |
| droite | float | La coordonnée x du coin inférieur droit de la région rectangulaire. |
| bas | float | La coordonnée y du coin inférieur droit de la région rectangulaire. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The new RectangleF that this method creates.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.drawing.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Crée et renvoie une copie gonflée de la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée. La copie est gonflée du montant indiqué. Le rectangle original reste inchangé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Le [RectangleF](../../com.aspose.drawing/rectanglef) à copier. Ce rectangle n'est pas modifié. |
| x | float | Le montant pour gonfler horizontalement la copie du rectangle. |
| y | float | La quantité à gonfler la copie du rectangle verticalement. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The inflated [RectangleF](../../com.aspose.drawing/rectanglef).
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Renvoie une structure [RectangleF](../../com.aspose.drawing/rectanglef) qui représente l'intersection de deux rectangles. S'il n'y a pas d'intersection, une [RectangleF](../../com.aspose.drawing/rectanglef) vide est renvoyée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Premier rectangle à intersecter. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Deuxième rectangle à intersecter. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Crée le plus petit rectangle possible qui peut contenir les deux rectangles formant une union.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Premier rectangle à unir. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Deuxième rectangle à unir. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure that contains both of the two rectangles that form the union.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Obtient une valeur indiquant si la propriété `RectangleF.Width` ou `RectangleF.Height` de ce [RectangleF](../../com.aspose.drawing/rectanglef) a une valeur de zéro.

**Returns:**
booléen - Cette propriété renvoie true si la propriété `RectangleF.Width` ou `P:RectangleF.Height` de ce [RectangleF](../../com.aspose.drawing/rectanglef) a une valeur de zéro ; sinon, false.
### getX() {#getX--}
```
public final float getX()
```


Obtient la coordonnée x du coin supérieur gauche de cette structure RectangleF.

**Returns:**
float - la coordonnée x du coin supérieur gauche de cette structure RectangleF.
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Définit la coordonnée x du coin supérieur gauche de cette structure RectangleF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | la coordonnée x du coin supérieur gauche de cette structure RectangleF. |

### getY() {#getY--}
```
public final float getY()
```


Obtient la coordonnée x du coin supérieur gauche de cette structure RectangleF.

**Returns:**
float - la coordonnée x du coin supérieur gauche de cette structure RectangleF.
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Définit la coordonnée x du coin supérieur gauche de cette structure RectangleF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | la coordonnée x du coin supérieur gauche de cette structure RectangleF. |

### getLocation() {#getLocation--}
```
public final PointF getLocation()
```


Obtient les coordonnées du coin supérieur gauche de cette structure [RectangleF](../../com.aspose.drawing/rectanglef).

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - A [PointF](../../com.aspose.drawing/pointf) that represents the upper-left corner of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setLocation(PointF value) {#setLocation-com.aspose.drawing.PointF-}
```
public final void setLocation(PointF value)
```


Définit les coordonnées du coin supérieur gauche de cette structure [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | les coordonnées du coin supérieur gauche de cette structure [RectangleF](../../com.aspose.drawing/rectanglef). |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Obtient la largeur de cette structure RectangleF.

**Returns:**
float - la largeur de cette structure RectangleF.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Définit la largeur de cette structure RectangleF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | la largeur de cette structure RectangleF. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Obtient la hauteur de cette structure RectangleF.

**Returns:**
float - la hauteur de cette structure RectangleF.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Définit la hauteur de cette structure RectangleF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | la hauteur de cette structure RectangleF. |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


Obtient la taille de ce [RectangleF](../../com.aspose.drawing/rectanglef).

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that represents the width and height of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setSize(SizeF value) {#setSize-com.aspose.drawing.SizeF-}
```
public final void setSize(SizeF value)
```


Définit la taille de ce [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | la taille de ce [RectangleF](../../com.aspose.drawing/rectanglef). |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


Obtient la coordonnée x du bord gauche de cette structure RectangleF.

**Returns:**
float - la coordonnée x du bord gauche de cette structure RectangleF.
### getTop() {#getTop--}
```
public final float getTop()
```


Obtient la coordonnée y du bord supérieur de cette structure RectangleF.

**Returns:**
float - la coordonnée y du bord supérieur de cette structure RectangleF.
### getRight() {#getRight--}
```
public final float getRight()
```


Obtient la coordonnée x qui est la somme de X et de la largeur de cette structure RectangleF.

**Returns:**
float - la coordonnée x qui est la somme de X et de la largeur de cette structure RectangleF.
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Obtient la coordonnée y qui est la somme de Y et de la hauteur de cette structure RectangleF.

**Returns:**
float - la coordonnée y qui est la somme de Y et de la hauteur de cette structure RectangleF.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### inflate(float x, float y) {#inflate-float-float-}
```
public final void inflate(float x, float y)
```


Agrandit cette structure [RectangleF](../../com.aspose.drawing/rectanglef) du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La quantité à gonfler cette structure [RectangleF](../../com.aspose.drawing/rectanglef) horizontalement. |
| y | float | La quantité à gonfler cette structure [RectangleF](../../com.aspose.drawing/rectanglef) verticalement. |

### inflate(SizeF size) {#inflate-com.aspose.drawing.SizeF-}
```
public final void inflate(SizeF size)
```


Agrandit ce [RectangleF](../../com.aspose.drawing/rectanglef) du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | La quantité à gonfler ce rectangle. |

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public final void intersect(RectangleF rect)
```


Remplace cette structure [RectangleF](../../com.aspose.drawing/rectanglef) par l'intersection d'elle-même et de la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Le rectangle à intersecter. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.drawing.RectangleF-}
```
public final boolean intersectsWith(RectangleF rect)
```


Détermine si ce rectangle intersecte `rect`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Le rectangle à tester. |

**Returns:**
booléen - Cette méthode renvoie true s'il y a une quelconque intersection.
### offset(PointF pos) {#offset-com.aspose.drawing.PointF-}
```
public final void offset(PointF pos)
```


Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.drawing/pointf) | Quantité de décalage de l'emplacement. |

### offset(float x, float y) {#offset-float-float-}
```
public final void offset(float x, float y)
```


Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | Quantité de décalage horizontal de l'emplacement. |
| y | float | Quantité de décalage vertical de l'emplacement. |

### contains(float x, float y) {#contains-float-float-}
```
public final boolean contains(float x, float y)
```


Détermine si le point spécifié est contenu dans cette structure [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns:**
booléen - Cette méthode renvoie `true` si le point défini par x et y est contenu dans cette structure [RectangleF](../../com.aspose.drawing/rectanglef) ; sinon `false`.
### contains(PointF pt) {#contains-com.aspose.drawing.PointF-}
```
public final boolean contains(PointF pt)
```


Détermine si le point spécifié est contenu dans cette structure [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | Le [PointF](../../com.aspose.drawing/pointf) à tester. |

**Returns:**
booléen - Cette méthode renvoie `true` si le point représenté par le paramètre pt est contenu dans cette structure [RectangleF](../../com.aspose.drawing/rectanglef) ; sinon `false`.
### contains(RectangleF rect) {#contains-com.aspose.drawing.RectangleF-}
```
public final boolean contains(RectangleF rect)
```


Détermine si la région rectangulaire représentée par `rect` est entièrement contenue dans cette structure [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Le [RectangleF](../../com.aspose.drawing/rectanglef) à tester. |

**Returns:**
booléen - Cette méthode renvoie `true` si la région rectangulaire représentée par `rect` est entièrement contenue dans la région rectangulaire représentée par ce [RectangleF](../../com.aspose.drawing/rectanglef) ; sinon `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'objet spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à comparer avec cette instance. |

**Returns:**
booléen - `true` si l'objet spécifié est égal à cette instance ; sinon, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
### equals(RectangleF other) {#equals-com.aspose.drawing.RectangleF-}
```
public final boolean equals(RectangleF other)
```


Teste si une autre structure [RectangleF](../../com.aspose.drawing/rectanglef) a la même position et la même taille que cette structure [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [RectangleF](../../com.aspose.drawing/rectanglef) | Autre rectangle à tester |

**Returns:**
booléen - Cette méthode renvoie `true` si l'autre structure [RectangleF](../../com.aspose.drawing/rectanglef) et ses propriétés X, Y, Width et Height sont égales aux propriétés correspondantes de cette structure [RectangleF](../../com.aspose.drawing/rectanglef) ; sinon, `false`.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.drawing.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
