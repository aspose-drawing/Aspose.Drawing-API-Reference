---
title: Rectangle
second_title: Référence de l'API Aspose.Drawing pour Java
description: Stocke un ensemble de quatre entiers qui représentent la position et la taille d'un rectangle.
type: docs
weight: 38
url: /fr/java/com.aspose.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Rectangle extends Struct<Rectangle> implements System.IEquatable<Rectangle>, Cloneable
```

Stocke un ensemble de quatre entiers qui représentent la position et la taille d'un rectangle.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Initialise une nouvelle instance de la structure Rectangle avec l'emplacement et la taille spécifiés. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Initialise une nouvelle instance du struct [Rectangle](../../com.aspose.drawing/rectangle) avec l'emplacement et la taille spécifiés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [fromLTRB(int left, int top, int right, int bottom)](#fromLTRB-int-int-int-int-) | Crée une structure [Rectangle](../../com.aspose.drawing/rectangle) avec les emplacements des bords spécifiés. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Renvoie une troisième structure [Rectangle](../../com.aspose.drawing/rectangle) qui représente l'intersection de deux autres structures [Rectangle](../../com.aspose.drawing/rectangle). |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Teste si deux structures [Rectangle](../../com.aspose.drawing/rectangle) ont le même emplacement et la même taille. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Teste si deux structures [Rectangle](../../com.aspose.drawing/rectangle) diffèrent par l'emplacement ou la taille. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.drawing.RectangleF-) | Convertit la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée en une structure [Rectangle](../../com.aspose.drawing/rectangle) en arrondissant les valeurs de [RectangleF](../../com.aspose.drawing/rectanglef) à l'entier supérieur suivant. |
| [truncate(RectangleF value)](#truncate-com.aspose.drawing.RectangleF-) | Convertit le [RectangleF](../../com.aspose.drawing/rectanglef) spécifié en un [Rectangle](../../com.aspose.drawing/rectangle) en tronquant les valeurs de [RectangleF](../../com.aspose.drawing/rectanglef). |
| [round(RectangleF value)](#round-com.aspose.drawing.RectangleF-) | Convertit le [RectangleF](../../com.aspose.drawing/rectanglef) spécifié en un [Rectangle](../../com.aspose.drawing/rectangle) en arrondissant les valeurs de [RectangleF](../../com.aspose.drawing/rectanglef) à l'entier le plus proche. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Obtient une structure [Rectangle](../../com.aspose.drawing/rectangle) qui contient l'union de deux structures [Rectangle](../../com.aspose.drawing/rectangle). |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.drawing.Rectangle-int-int-) |  |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) |  |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Crée un nouveau rectangle à partir de deux points. |
| [getEmpty()](#getEmpty--) | Obtient une nouvelle instance de la structure `Rectangle` dont les valeurs `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` et `Rectangle.Height` sont définies à zéro. |
| [getX()](#getX--) | Obtient la coordonnée x du coin supérieur gauche de cette structure Rectangle. |
| [setX(int value)](#setX-int-) | Définit la coordonnée x du coin supérieur gauche de cette structure Rectangle. |
| [getY()](#getY--) | Obtient la coordonnée y du coin supérieur gauche de cette structure Rectangle. |
| [setY(int value)](#setY-int-) | Définit la coordonnée y du coin supérieur gauche de cette structure Rectangle. |
| [getLocation()](#getLocation--) | Obtient les coordonnées du coin supérieur gauche de cette structure [Rectangle](../../com.aspose.drawing/rectangle). |
| [setLocation(Point value)](#setLocation-com.aspose.drawing.Point-) | Définit les coordonnées du coin supérieur gauche de cette structure [Rectangle](../../com.aspose.drawing/rectangle). |
| [getWidth()](#getWidth--) | Obtient la largeur de cette structure Rectangle. |
| [setWidth(int value)](#setWidth-int-) | Définit la largeur de cette structure Rectangle. |
| [getHeight()](#getHeight--) | Obtient la hauteur de cette structure Rectangle. |
| [setHeight(int value)](#setHeight-int-) | Définit la hauteur de cette structure Rectangle. |
| [getSize()](#getSize--) | Obtient la taille de ce [Rectangle](../../com.aspose.drawing/rectangle). |
| [setSize(Size value)](#setSize-com.aspose.drawing.Size-) | Définit la taille de ce [Rectangle](../../com.aspose.drawing/rectangle). |
| [getLeft()](#getLeft--) | Obtient la coordonnée x du bord gauche de cette structure Rectangle. |
| [getTop()](#getTop--) | Obtient la coordonnée y du bord supérieur de cette structure Rectangle. |
| [getRight()](#getRight--) | Obtient la coordonnée x qui est la somme des valeurs des propriétés X et Width de cette structure Rectangle. |
| [getBottom()](#getBottom--) | Obtient la coordonnée y qui est la somme des valeurs des propriétés Y et Height de cette structure Rectangle. |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si toutes les propriétés numériques de ce [Rectangle](../../com.aspose.drawing/rectangle) ont des valeurs zéro. |
| [equals(Object obj)](#equals-java.lang.Object-) | Teste si obj est une structure [Rectangle](../../com.aspose.drawing/rectangle) avec la même position et la même taille que cette structure [Rectangle](../../com.aspose.drawing/rectangle). |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette structure [Rectangle](../../com.aspose.drawing/rectangle). |
| [toString()](#toString--) |  |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Remplace ce [Rectangle](../../com.aspose.drawing/rectangle) par l'intersection de lui-même et du [Rectangle](../../com.aspose.drawing/rectangle) spécifié. |
| [inflate(int width, int height)](#inflate-int-int-) | Agrandit ce [Rectangle](../../com.aspose.drawing/rectangle) du montant spécifié. |
| [inflate(Size size)](#inflate-com.aspose.drawing.Size-) | Agrandit ce [Rectangle](../../com.aspose.drawing/rectangle) du montant spécifié. |
| [contains(int x, int y)](#contains-int-int-) | Détermine si le point spécifié est contenu dans cette structure [Rectangle](../../com.aspose.drawing/rectangle). |
| [contains(Point pt)](#contains-com.aspose.drawing.Point-) | Détermine si le point spécifié est contenu dans cette structure [Rectangle](../../com.aspose.drawing/rectangle). |
| [contains(Rectangle rect)](#contains-com.aspose.drawing.Rectangle-) |  |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.drawing.Rectangle-) | Détermine si ce rectangle intersecte `rect`. |
| [offset(int x, int y)](#offset-int-int-) | Ajuste la position de ce rectangle du montant spécifié. |
| [offset(Point pos)](#offset-com.aspose.drawing.Point-) | Ajuste la position de ce rectangle du montant spécifié. |
| [equals(Rectangle other)](#equals-com.aspose.drawing.Rectangle-) | Teste si une autre structure [Rectangle](../../com.aspose.drawing/rectangle) a la même position et la même taille que cette structure [Rectangle](../../com.aspose.drawing/rectangle). |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.drawing.Rectangle-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [normalize()](#normalize--) | Normalise le rectangle en rendant sa largeur et sa hauteur positives, le côté gauche inférieur au côté droit et le haut inférieur au bas. |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Initialise une nouvelle instance de la structure Rectangle avec l'emplacement et la taille spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle. |
| largeur | int | La largeur du rectangle. |
| hauteur | int | La hauteur du rectangle. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public Rectangle(Point location, Size size)
```


Initialise une nouvelle instance du struct [Rectangle](../../com.aspose.drawing/rectangle) avec l'emplacement et la taille spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| location | [Point](../../com.aspose.drawing/point) | Un [Point](../../com.aspose.drawing/point) qui représente le coin supérieur gauche de la région rectangulaire. |
| size | [Size](../../com.aspose.drawing/size) | Un `Size`([.getSize](../../null/\#getSize)/[.setSize(Size)](../../null/\#setSize-Size-)) qui représente la largeur et la hauteur de la région rectangulaire. |

### fromLTRB(int left, int top, int right, int bottom) {#fromLTRB-int-int-int-int-}
```
public static Rectangle fromLTRB(int left, int top, int right, int bottom)
```


Crée une structure [Rectangle](../../com.aspose.drawing/rectangle) avec les emplacements des bords spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | int | La coordonnée x du coin supérieur gauche de cette structure [Rectangle](../../com.aspose.drawing/rectangle). |
| top | int | La coordonnée y du coin supérieur gauche de cette structure [Rectangle](../../com.aspose.drawing/rectangle). |
| right | int | La coordonnée x du coin inférieur droit de cette structure [Rectangle](../../com.aspose.drawing/rectangle). |
| bottom | int | La coordonnée y du coin inférieur droit de cette structure [Rectangle](../../com.aspose.drawing/rectangle). |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The new [Rectangle](../../com.aspose.drawing/rectangle) that this method creates.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Renvoie une troisième structure [Rectangle](../../com.aspose.drawing/rectangle) qui représente l'intersection de deux autres structures [Rectangle](../../com.aspose.drawing/rectangle). S'il n'y a pas d'intersection, une [Rectangle](../../com.aspose.drawing/rectangle) vide est renvoyée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | Premier rectangle à intersecter. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | Deuxième rectangle à intersecter. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the intersection of `a` and `b`.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Teste si deux structures [Rectangle](../../com.aspose.drawing/rectangle) ont le même emplacement et la même taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | La structure [Rectangle](../../com.aspose.drawing/rectangle) qui se trouve à gauche de l'opérateur d'égalité. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | La structure [Rectangle](../../com.aspose.drawing/rectangle) qui se trouve à droite de l'opérateur d'égalité. |

**Returns:**
booléen - Cet opérateur renvoie `true` si les deux structures [Rectangle](../../com.aspose.drawing/rectangle) ont des propriétés X, Y, Width et Height égales.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Teste si deux structures [Rectangle](../../com.aspose.drawing/rectangle) diffèrent par l'emplacement ou la taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | La structure [Rectangle](../../com.aspose.drawing/rectangle) qui se trouve à gauche de l'opérateur d'inégalité. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | La structure [Rectangle](../../com.aspose.drawing/rectangle) qui se trouve à droite de l'opérateur d'inégalité. |

**Returns:**
booléen - Cet opérateur renvoie `true` si l'une des propriétés X, Y, Width ou Height des deux structures [Rectangle](../../com.aspose.drawing/rectangle) est différente ; sinon `false`.
### ceiling(RectangleF value) {#ceiling-com.aspose.drawing.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Convertit la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée en une structure [Rectangle](../../com.aspose.drawing/rectangle) en arrondissant les valeurs de [RectangleF](../../com.aspose.drawing/rectanglef) à l'entier supérieur suivant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | La structure [RectangleF](../../com.aspose.drawing/rectanglef) à convertir. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - Returns a [Rectangle](../../com.aspose.drawing/rectangle).
### truncate(RectangleF value) {#truncate-com.aspose.drawing.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Convertit le [RectangleF](../../com.aspose.drawing/rectanglef) spécifié en un [Rectangle](../../com.aspose.drawing/rectangle) en tronquant les valeurs de [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | Le [RectangleF](../../com.aspose.drawing/rectanglef) à convertir. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The truncated value of the [Rectangle](../../com.aspose.drawing/rectangle).
### round(RectangleF value) {#round-com.aspose.drawing.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Convertit le [RectangleF](../../com.aspose.drawing/rectanglef) spécifié en un [Rectangle](../../com.aspose.drawing/rectangle) en arrondissant les valeurs de [RectangleF](../../com.aspose.drawing/rectanglef) à l'entier le plus proche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | Le [RectangleF](../../com.aspose.drawing/rectanglef) à convertir. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle).
### union(Rectangle a, Rectangle b) {#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Obtient une structure [Rectangle](../../com.aspose.drawing/rectangle) qui contient l'union de deux structures [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | Un premier rectangle à unir. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | Un deuxième rectangle à unir. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) structure that bounds the union of the two [Rectangle](../../com.aspose.drawing/rectangle) structures.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.drawing.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| x | int |  |
| y | int |  |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Crée un nouveau rectangle à partir de deux points. Le rectangle créé sera normalisé avec (left,top) inférieur à (right,bottom).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | Le premier point. |
| point2 | [Point](../../com.aspose.drawing/point) | Le deuxième point. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A newly created rectangle.
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Obtient une nouvelle instance de la structure `Rectangle` dont les valeurs `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` et `Rectangle.Height` sont définies à zéro.

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### getX() {#getX--}
```
public final int getX()
```


Obtient la coordonnée x du coin supérieur gauche de cette structure Rectangle.

**Returns:**
int - la coordonnée x du coin supérieur gauche de cette structure Rectangle.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Définit la coordonnée x du coin supérieur gauche de cette structure Rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | la coordonnée x du coin supérieur gauche de cette structure Rectangle. |

### getY() {#getY--}
```
public final int getY()
```


Obtient la coordonnée y du coin supérieur gauche de cette structure Rectangle.

**Returns:**
int - la coordonnée y du coin supérieur gauche de cette structure Rectangle.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Définit la coordonnée y du coin supérieur gauche de cette structure Rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | la coordonnée y du coin supérieur gauche de cette structure Rectangle. |

### getLocation() {#getLocation--}
```
public final Point getLocation()
```


Obtient les coordonnées du coin supérieur gauche de cette structure [Rectangle](../../com.aspose.drawing/rectangle).

**Returns:**
[Point](../../com.aspose.drawing/point) - the coordinates of the upper-left corner of this [Rectangle](../../com.aspose.drawing/rectangle) structure.
### setLocation(Point value) {#setLocation-com.aspose.drawing.Point-}
```
public final void setLocation(Point value)
```


Définit les coordonnées du coin supérieur gauche de cette structure [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.drawing/point) | les coordonnées du coin supérieur gauche de cette structure [Rectangle](../../com.aspose.drawing/rectangle). |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtient la largeur de cette structure Rectangle.

**Returns:**
int - la largeur de cette structure Rectangle.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Définit la largeur de cette structure Rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | la largeur de cette structure Rectangle. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtient la hauteur de cette structure Rectangle.

**Returns:**
int - la hauteur de cette structure Rectangle.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Définit la hauteur de cette structure Rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | la hauteur de cette structure Rectangle. |

### getSize() {#getSize--}
```
public final Size getSize()
```


Obtient la taille de ce [Rectangle](../../com.aspose.drawing/rectangle).

**Returns:**
[Size](../../com.aspose.drawing/size) - the size of this [Rectangle](../../com.aspose.drawing/rectangle).
### setSize(Size value) {#setSize-com.aspose.drawing.Size-}
```
public final void setSize(Size value)
```


Définit la taille de ce [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.drawing/size) | la taille de ce [Rectangle](../../com.aspose.drawing/rectangle). |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Obtient la coordonnée x du bord gauche de cette structure Rectangle.

**Returns:**
int - la coordonnée x du bord gauche de cette structure Rectangle.
### getTop() {#getTop--}
```
public final int getTop()
```


Obtient la coordonnée y du bord supérieur de cette structure Rectangle.

**Returns:**
int - la coordonnée y du bord supérieur de cette structure Rectangle.
### getRight() {#getRight--}
```
public final int getRight()
```


Obtient la coordonnée x qui est la somme des valeurs des propriétés X et Width de cette structure Rectangle.

**Returns:**
int - la coordonnée x qui est la somme des valeurs des propriétés X et Width de cette structure Rectangle.
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Obtient la coordonnée y qui est la somme des valeurs des propriétés Y et Height de cette structure Rectangle.

**Returns:**
int - la coordonnée y qui est la somme des valeurs des propriétés Y et Height de cette structure Rectangle.
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Obtient une valeur indiquant si toutes les propriétés numériques de ce [Rectangle](../../com.aspose.drawing/rectangle) ont des valeurs zéro.

**Returns:**
booléen - Cette propriété renvoie `true` si les propriétés `Rectangle.Width`, `Rectangle.Height`, `Rectangle.X` et `Rectangle.Y` de ce [Rectangle](../../com.aspose.drawing/rectangle) ont toutes la valeur zéro ; sinon, `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Teste si obj est une structure [Rectangle](../../com.aspose.drawing/rectangle) avec la même position et la même taille que cette structure [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'Object à tester. |

**Returns:**
booléen - Cette méthode renvoie `true` si obj est une structure [Rectangle](../../com.aspose.drawing/rectangle) et que ses propriétés X, Y, Width et Height sont égales aux propriétés correspondantes de cette structure [Rectangle](../../com.aspose.drawing/rectangle) ; sinon, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette structure [Rectangle](../../com.aspose.drawing/rectangle). Pour plus d'informations sur l'utilisation des codes de hachage, voir GetHashCode.

**Returns:**
int - Un entier qui représente le code de hachage pour ce rectangle.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public final void intersect(Rectangle rect)
```


Remplace ce [Rectangle](../../com.aspose.drawing/rectangle) par l'intersection de lui-même et du [Rectangle](../../com.aspose.drawing/rectangle) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Le [Rectangle](../../com.aspose.drawing/rectangle) avec lequel intersecter. |

### inflate(int width, int height) {#inflate-int-int-}
```
public final void inflate(int width, int height)
```


Agrandit ce [Rectangle](../../com.aspose.drawing/rectangle) du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La quantité à agrandir ce [Rectangle](../../com.aspose.drawing/rectangle) horizontalement. |
| height | int | La quantité à agrandir ce [Rectangle](../../com.aspose.drawing/rectangle) verticalement. |

### inflate(Size size) {#inflate-com.aspose.drawing.Size-}
```
public final void inflate(Size size)
```


Agrandit ce [Rectangle](../../com.aspose.drawing/rectangle) du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | La taille à agrandir ce [Rectangle](../../com.aspose.drawing/rectangle). |

### contains(int x, int y) {#contains-int-int-}
```
public final boolean contains(int x, int y)
```


Détermine si le point spécifié est contenu dans cette structure [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |

**Returns:**
booléen - Cette méthode renvoie `true` si le point défini par `x` et `y` est contenu dans cette structure [Rectangle](../../com.aspose.drawing/rectangle) ; sinon `false`.
### contains(Point pt) {#contains-com.aspose.drawing.Point-}
```
public final boolean contains(Point pt)
```


Détermine si le point spécifié est contenu dans cette structure [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Le [Point](../../com.aspose.drawing/point) à tester. |

**Returns:**
booléen - Cette méthode renvoie `true` si le point représenté par `pt` est contenu dans cette structure [Rectangle](../../com.aspose.drawing/rectangle) ; sinon `false`.
### contains(Rectangle rect) {#contains-com.aspose.drawing.Rectangle-}
```
public final boolean contains(Rectangle rect)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.drawing.Rectangle-}
```
public final boolean intersectsWith(Rectangle rect)
```


Détermine si ce rectangle intersecte `rect`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Le rectangle à tester. |

**Returns:**
booléen - Cette méthode renvoie true s'il y a une intersection quelconque, sinon false.
### offset(int x, int y) {#offset-int-int-}
```
public final void offset(int x, int y)
```


Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | Le décalage horizontal. |
| y | int | Le décalage vertical. |

### offset(Point pos) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point pos)
```


Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pos | [Point](../../com.aspose.drawing/point) | Le décalage. |

### equals(Rectangle other) {#equals-com.aspose.drawing.Rectangle-}
```
public final boolean equals(Rectangle other)
```


Teste si une autre structure [Rectangle](../../com.aspose.drawing/rectangle) a la même position et la même taille que cette structure [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.drawing/rectangle) | Autre rectangle à tester |

**Returns:**
booléen - Cette méthode renvoie `true` si l'autre structure [Rectangle](../../com.aspose.drawing/rectangle) et ses propriétés X, Y, Width et Height sont égales aux propriétés correspondantes de cette structure [Rectangle](../../com.aspose.drawing/rectangle) ; sinon, `false`.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.drawing.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.drawing/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### normalize() {#normalize--}
```
public void normalize()
```


Normalise le rectangle en rendant sa largeur et sa hauteur positives, le côté gauche inférieur au côté droit et le haut inférieur au bas.

