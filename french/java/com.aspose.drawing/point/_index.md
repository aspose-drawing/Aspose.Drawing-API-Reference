---
title: Point
second_title: Référence de l'API Aspose.Drawing pour Java
description: Représente une paire ordonnée de coordonnées x et y entières qui définit un point dans un plan bidimensionnel.
type: docs
weight: 36
url: /fr/java/com.aspose.drawing/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Point extends Struct<Point> implements System.IEquatable<Point>, Cloneable
```

Représente une paire ordonnée de coordonnées x et y entières qui définit un point dans un plan bidimensionnel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Initialise une nouvelle instance de la structure [Point](../../com.aspose.drawing/point) avec les coordonnées spécifiées. |
| [Point(Size sz)](#Point-com.aspose.drawing.Size-) |  |
| [Point(int dw)](#Point-int-) | Initialise une nouvelle instance de la structure [Point](../../com.aspose.drawing/point) en utilisant des coordonnées spécifiées par une valeur entière. |
## Champs

| Champ | Description |
| --- | --- |
| [EMPTY](#EMPTY) | Représente un [Point](../../com.aspose.drawing/point) dont les valeurs `Point.X` et `Point.Y` sont définies à zéro. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [to_PointF(Point p)](#to-PointF-com.aspose.drawing.Point-) | Convertit la structure [Point](../../com.aspose.drawing/point) spécifiée en une structure [PointF](../../com.aspose.drawing/pointf). |
| [to_Size(Point p)](#to-Size-com.aspose.drawing.Point-) |  |
| [op_Addition(Point pt, Size sz)](#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Subtraction(Point pt, Size sz)](#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Equality(Point left, Point right)](#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Compare deux objets [Point](../../com.aspose.drawing/point). |
| [op_Inequality(Point left, Point right)](#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Compare deux objets [Point](../../com.aspose.drawing/point). |
| [add(Point pt, Size sz)](#add-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Ajoute le [Size](../../com.aspose.drawing/size) spécifié au [Point](../../com.aspose.drawing/point) spécifié. |
| [subtract(Point pt, Size sz)](#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [ceiling(PointF value)](#ceiling-com.aspose.drawing.PointF-) |  |
| [truncate(PointF value)](#truncate-com.aspose.drawing.PointF-) | Convertit un PointF en Point en effectuant une opération de troncature sur toutes les coordonnées. |
| [round(PointF value)](#round-com.aspose.drawing.PointF-) | Convertit le [PointF](../../com.aspose.drawing/pointf) spécifié en un objet Point en arrondissant les valeurs du [Point](../../com.aspose.drawing/point) à l’entier le plus proche. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-) |  |
| [getEmpty()](#getEmpty--) |  |
| [getX()](#getX--) | Obtient la coordonnée x de ce Point. |
| [setX(int value)](#setX-int-) | Définit la coordonnée x de ce Point. |
| [getY()](#getY--) | Obtient la coordonnée y de ce Point. |
| [setY(int value)](#setY-int-) | Définit la coordonnée y de ce Point. |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si ce [Point](../../com.aspose.drawing/point) est vide. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour ce [Point](../../com.aspose.drawing/point). |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Spécifie si ce [Point](../../com.aspose.drawing/point) contient les mêmes coordonnées que l’objet spécifié. |
| [offset(int dx, int dy)](#offset-int-int-) | Déplace ce [Point](../../com.aspose.drawing/point) du montant spécifié. |
| [offset(Point p)](#offset-com.aspose.drawing.Point-) | Déplace ce [Point](../../com.aspose.drawing/point) du [Point](../../com.aspose.drawing/point) spécifié. |
| [equals(Point other)](#equals-com.aspose.drawing.Point-) | Teste si une autre structure [Point](../../com.aspose.drawing/point) a la même position que la structure [Point](../../com.aspose.drawing/point) de cet objet. |
| [CloneTo(Point that)](#CloneTo-com.aspose.drawing.Point-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Initialise une nouvelle instance de la structure [Point](../../com.aspose.drawing/point) avec les coordonnées spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La position horizontale du point. |
| y | int | La position verticale du point. |

### Point(Size sz) {#Point-com.aspose.drawing.Size-}
```
public Point(Size sz)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sz | [Size](../../com.aspose.drawing/size) |  |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Initialise une nouvelle instance de la structure [Point](../../com.aspose.drawing/point) en utilisant des coordonnées spécifiées par une valeur entière.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dw | int | La valeur entière. |

### EMPTY {#EMPTY}
```
public static final Point EMPTY
```


Représente un [Point](../../com.aspose.drawing/point) dont les valeurs `Point.X` et `Point.Y` sont définies à zéro.

### to_PointF(Point p) {#to-PointF-com.aspose.drawing.Point-}
```
public static PointF to_PointF(Point p)
```


Convertit la structure [Point](../../com.aspose.drawing/point) spécifiée en une structure [PointF](../../com.aspose.drawing/pointf).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | Le [Point](../../com.aspose.drawing/point) à convertir. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The [PointF](../../com.aspose.drawing/pointf) that results from the conversion.
### to_Size(Point p) {#to-Size-com.aspose.drawing.Point-}
```
public static Size to_Size(Point p)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
[Size](../../com.aspose.drawing/size)
### op_Addition(Point pt, Size sz) {#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Addition(Point pt, Size sz)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Subtraction(Point pt, Size sz) {#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Subtraction(Point pt, Size sz)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Equality(Point left, Point right) {#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Equality(Point left, Point right)
```


Compare deux objets [Point](../../com.aspose.drawing/point). Le résultat indique si les valeurs des propriétés `Point.X` et `Point.Y` des deux objets [Point](../../com.aspose.drawing/point) sont égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Premier [Point](../../com.aspose.drawing/point) à comparer. |
| right | [Point](../../com.aspose.drawing/point) | Deuxième [Point](../../com.aspose.drawing/point) à comparer. |

**Returns:**
booléen - vrai si les valeurs `Point.X` et `Point.Y` de `left` et `right` sont égales ; sinon, faux.
### op_Inequality(Point left, Point right) {#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Inequality(Point left, Point right)
```


Compare deux objets [Point](../../com.aspose.drawing/point). Le résultat indique si les valeurs des propriétés `Point.X` ou `Point.Y` des deux objets [Point](../../com.aspose.drawing/point) sont différentes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Premier [Point](../../com.aspose.drawing/point) à comparer. |
| right | [Point](../../com.aspose.drawing/point) | Deuxième [Point](../../com.aspose.drawing/point) à comparer. |

**Returns:**
booléen - vrai si les valeurs de l'une ou l'autre des propriétés `Point.X` ou `Point.Y` de `left` et `right` diffèrent ; sinon, faux.
### add(Point pt, Size sz) {#add-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point add(Point pt, Size sz)
```


Ajoute le [Size](../../com.aspose.drawing/size) spécifié au [Point](../../com.aspose.drawing/point) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Le [Point](../../com.aspose.drawing/point) à ajouter. |
| sz | [Size](../../com.aspose.drawing/size) | Le [Size](../../com.aspose.drawing/size) à ajouter |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the addition operation.
### subtract(Point pt, Size sz) {#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point subtract(Point pt, Size sz)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### ceiling(PointF value) {#ceiling-com.aspose.drawing.PointF-}
```
public static Point ceiling(PointF value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### truncate(PointF value) {#truncate-com.aspose.drawing.PointF-}
```
public static Point truncate(PointF value)
```


Convertit un PointF en Point en effectuant une opération de troncature sur toutes les coordonnées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Le [PointF](../../com.aspose.drawing/pointf) à tronquer. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the truncate operation.
### round(PointF value) {#round-com.aspose.drawing.PointF-}
```
public static Point round(PointF value)
```


Convertit le [PointF](../../com.aspose.drawing/pointf) spécifié en un objet Point en arrondissant les valeurs du [Point](../../com.aspose.drawing/point) à l’entier le plus proche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Le [PointF](../../com.aspose.drawing/pointf) à convertir. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) this method converts to.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.drawing/point) |  |
| obj2 | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### getX() {#getX--}
```
public final int getX()
```


Obtient la coordonnée x de ce Point.

**Returns:**
int - la coordonnée x de ce Point.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Définit la coordonnée x de ce Point.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | la coordonnée x de ce Point. |

### getY() {#getY--}
```
public final int getY()
```


Obtient la coordonnée y de ce Point.

**Returns:**
int - la coordonnée y de ce Point.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Définit la coordonnée y de ce Point.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | la coordonnée y de ce Point. |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Obtient une valeur indiquant si ce [Point](../../com.aspose.drawing/point) est vide.

Valeur : `true` si X et Y sont tous deux 0 ; sinon, `false`.

**Returns:**
booléen - une valeur indiquant si ce ce [Point](../../com.aspose.drawing/point) est vide.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour ce [Point](../../com.aspose.drawing/point).

**Returns:**
int - Une valeur entière qui spécifie une valeur de hachage pour ce [Point](../../com.aspose.drawing/point).
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Spécifie si ce [Point](../../com.aspose.drawing/point) contient les mêmes coordonnées que l’objet spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'Object à tester. |

**Returns:**
booléen - `true` si obj est un Point et possède les mêmes coordonnées que ce [Point](../../com.aspose.drawing/point).
### offset(int dx, int dy) {#offset-int-int-}
```
public final void offset(int dx, int dy)
```


Déplace ce [Point](../../com.aspose.drawing/point) du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | int | La quantité pour décaler la coordonnée x. |
| dy | int | La quantité pour décaler la coordonnée y. |

### offset(Point p) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point p)
```


Déplace ce [Point](../../com.aspose.drawing/point) du [Point](../../com.aspose.drawing/point) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | Le [Point](../../com.aspose.drawing/point) utilisé pour décaler ce [Point](../../com.aspose.drawing/point). |

### equals(Point other) {#equals-com.aspose.drawing.Point-}
```
public final boolean equals(Point other)
```


Teste si une autre structure [Point](../../com.aspose.drawing/point) a la même position que la structure [Point](../../com.aspose.drawing/point) de cet objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [Point](../../com.aspose.drawing/point) | Autre point à tester |

**Returns:**
booléen - Cette méthode renvoie `true` si l'autre structure [Point](../../com.aspose.drawing/point) et ses propriétés X et Y sont égales aux propriétés correspondantes de cette structure [Point](../../com.aspose.drawing/point) ; sinon, `false`.
### CloneTo(Point that) {#CloneTo-com.aspose.drawing.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [Point](../../com.aspose.drawing/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
