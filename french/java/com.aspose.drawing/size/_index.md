---
title: Size
second_title: Référence de l'API Aspose.Drawing pour Java
description: Stocke une paire ordonnée d'entiers représentant généralement la largeur et la hauteur d'un rectangle.
type: docs
weight: 42
url: /fr/java/com.aspose.drawing/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Size extends Struct<Size> implements System.IEquatable<Size>, Cloneable
```

Stocke une paire ordonnée d'entiers, généralement la largeur et la hauteur d'un rectangle.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point pt)](#Size-com.aspose.drawing.Point-) | Initialise une nouvelle instance de la structure [Size](../../com.aspose.drawing/size) à partir du [Point](../../com.aspose.drawing/point) spécifié. |
| [Size(int width, int height)](#Size-int-int-) | Initialise une nouvelle instance de la structure [Size](../../com.aspose.drawing/size) à partir des dimensions spécifiées. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [to_SizeF(Size p)](#to-SizeF-com.aspose.drawing.Size-) | Convertit le [Size](../../com.aspose.drawing/size) spécifié en [SizeF](../../com.aspose.drawing/sizef). |
| [op_Addition(Size sz1, Size sz2)](#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Ajoute la largeur et la hauteur d'une structure [Size](../../com.aspose.drawing/size) à la largeur et la hauteur d'une autre structure [Size](../../com.aspose.drawing/size). |
| [op_Subtraction(Size sz1, Size sz2)](#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Soustrait la largeur et la hauteur d'une structure [Size](../../com.aspose.drawing/size) de la largeur et la hauteur d'une autre structure [Size](../../com.aspose.drawing/size). |
| [op_Multiply(int left, Size right)](#op-Multiply-int-com.aspose.drawing.Size-) | Multiplie un [Size](../../com.aspose.drawing/size) par un `int` produisant un [Size](../../com.aspose.drawing/size). |
| [op_Multiply(Size left, int right)](#op-Multiply-com.aspose.drawing.Size-int-) | Multiplie le [Size](../../com.aspose.drawing/size) par un `int` produisant un [Size](../../com.aspose.drawing/size). |
| [op_Division(Size left, int right)](#op-Division-com.aspose.drawing.Size-int-) | Divise le [Size](../../com.aspose.drawing/size) par un `int` produisant un [Size](../../com.aspose.drawing/size). |
| [op_Multiply(float left, Size right)](#op-Multiply-float-com.aspose.drawing.Size-) | Multiplie le [Size](../../com.aspose.drawing/size) par un `float` produisant un [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(Size left, float right)](#op-Multiply-com.aspose.drawing.Size-float-) | Multiplie le [Size](../../com.aspose.drawing/size) par un `float` produisant un [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(Size left, float right)](#op-Division-com.aspose.drawing.Size-float-) | Divise [Size](../../com.aspose.drawing/size) par un `float` produisant [SizeF](../../com.aspose.drawing/sizef). |
| [op_Equality(Size sz1, Size sz2)](#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Teste si deux structures [Size](../../com.aspose.drawing/size) sont égales. |
| [op_Inequality(Size sz1, Size sz2)](#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Teste si deux structures [Size](../../com.aspose.drawing/size) sont différentes. |
| [to_Point(Size size)](#to-Point-com.aspose.drawing.Size-) | Convertit le [Size](../../com.aspose.drawing/size) spécifié en un [Point](../../com.aspose.drawing/point). |
| [add(Size sz1, Size sz2)](#add-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Ajoute la largeur et la hauteur d'une structure [Size](../../com.aspose.drawing/size) à la largeur et la hauteur d'une autre structure [Size](../../com.aspose.drawing/size). |
| [ceiling(SizeF value)](#ceiling-com.aspose.drawing.SizeF-) | Convertit la structure [SizeF](../../com.aspose.drawing/sizef) spécifiée en une structure [Size](../../com.aspose.drawing/size) en arrondissant les valeurs de la structure [Size](../../com.aspose.drawing/size) à l'entier supérieur suivant. |
| [subtract(Size sz1, Size sz2)](#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Soustrait la largeur et la hauteur d'une structure [Size](../../com.aspose.drawing/size) de la largeur et la hauteur d'une autre structure [Size](../../com.aspose.drawing/size). |
| [truncate(SizeF value)](#truncate-com.aspose.drawing.SizeF-) | Convertit la structure [SizeF](../../com.aspose.drawing/sizef) spécifiée en une structure [Size](../../com.aspose.drawing/size) en tronquant les valeurs de la structure [SizeF](../../com.aspose.drawing/sizef) à l'entier inférieur suivant. |
| [round(SizeF value)](#round-com.aspose.drawing.SizeF-) | Convertit la structure [SizeF](../../com.aspose.drawing/sizef) spécifiée en une structure [Size](../../com.aspose.drawing/size) en arrondissant les valeurs de la structure [SizeF](../../com.aspose.drawing/sizef) à l'entier le plus proche. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si ce [Size](../../com.aspose.drawing/size) a une largeur et une hauteur de 0. |
| [getWidth()](#getWidth--) | Obtient le composant horizontal de ce [Size](../../com.aspose.drawing/size). |
| [setWidth(int value)](#setWidth-int-) | Définit le composant horizontal de ce [Size](../../com.aspose.drawing/size). |
| [getHeight()](#getHeight--) | Obtient le composant vertical de ce [Size](../../com.aspose.drawing/size). |
| [setHeight(int value)](#setHeight-int-) | Définit le composant vertical de ce [Size](../../com.aspose.drawing/size). |
| [equals(Object obj)](#equals-java.lang.Object-) | Teste pour voir si l'objet spécifié est un [Size](../../com.aspose.drawing/size) avec les mêmes dimensions que ce [Size](../../com.aspose.drawing/size). |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette structure [Size](../../com.aspose.drawing/size). |
| [toString()](#toString--) |  |
| [equals(Size other)](#equals-com.aspose.drawing.Size-) | Teste si une autre structure [Size](../../com.aspose.drawing/size) a la même taille que cette structure [Size](../../com.aspose.drawing/size). |
| [CloneTo(Size that)](#CloneTo-com.aspose.drawing.Size-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point pt) {#Size-com.aspose.drawing.Point-}
```
public Size(Point pt)
```


Initialise une nouvelle instance de la structure [Size](../../com.aspose.drawing/size) à partir du [Point](../../com.aspose.drawing/point) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Le [Point](../../com.aspose.drawing/point) à partir duquel initialiser ce [Size](../../com.aspose.drawing/size). |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Initialise une nouvelle instance de la structure [Size](../../com.aspose.drawing/size) à partir des dimensions spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | Le composant largeur du nouveau [Size](../../com.aspose.drawing/size). |
| height | int | Le composant hauteur du nouveau [Size](../../com.aspose.drawing/size). |

### to_SizeF(Size p) {#to-SizeF-com.aspose.drawing.Size-}
```
public static SizeF to_SizeF(Size p)
```


Convertit le [Size](../../com.aspose.drawing/size) spécifié en [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| p | [Size](../../com.aspose.drawing/size) | Le [Size](../../com.aspose.drawing/size) à convertir. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - The [SizeF](../../com.aspose.drawing/sizef) structure to which this operator converts.
### op_Addition(Size sz1, Size sz2) {#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Addition(Size sz1, Size sz2)
```


Ajoute la largeur et la hauteur d'une structure [Size](../../com.aspose.drawing/size) à la largeur et la hauteur d'une autre structure [Size](../../com.aspose.drawing/size).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Le premier [Size](../../com.aspose.drawing/size) à ajouter. |
| sz2 | [Size](../../com.aspose.drawing/size) | Le deuxième [Size](../../com.aspose.drawing/size) à ajouter. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(Size sz1, Size sz2) {#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Subtraction(Size sz1, Size sz2)
```


Soustrait la largeur et la hauteur d'une structure [Size](../../com.aspose.drawing/size) de la largeur et la hauteur d'une autre structure [Size](../../com.aspose.drawing/size).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | La structure [Size](../../com.aspose.drawing/size) du côté gauche de l'opérateur de soustraction. |
| sz2 | [Size](../../com.aspose.drawing/size) | La structure [Size](../../com.aspose.drawing/size) du côté droit de l'opérateur de soustraction. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the subtraction operation.
### op_Multiply(int left, Size right) {#op-Multiply-int-com.aspose.drawing.Size-}
```
public static Size op_Multiply(int left, Size right)
```


Multiplie un [Size](../../com.aspose.drawing/size) par un `int` produisant un [Size](../../com.aspose.drawing/size).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gauche | int | Multiplicateur de type `int`. |
| right | [Size](../../com.aspose.drawing/size) | Multiplicande de type [Size](../../com.aspose.drawing/size). |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Multiply(Size left, int right) {#op-Multiply-com.aspose.drawing.Size-int-}
```
public static Size op_Multiply(Size left, int right)
```


Multiplie le [Size](../../com.aspose.drawing/size) par un `int` produisant un [Size](../../com.aspose.drawing/size).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Multiplicande de type [Size](../../com.aspose.drawing/size). |
| droite | int | Multiplicateur de type `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Division(Size left, int right) {#op-Division-com.aspose.drawing.Size-int-}
```
public static Size op_Division(Size left, int right)
```


Divise le [Size](../../com.aspose.drawing/size) par un `int` produisant un [Size](../../com.aspose.drawing/size).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividende de type [Size](../../com.aspose.drawing/size). |
| droite | int | Diviseur de type `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Result of type [Size](../../com.aspose.drawing/size).
### op_Multiply(float left, Size right) {#op-Multiply-float-com.aspose.drawing.Size-}
```
public static SizeF op_Multiply(float left, Size right)
```


Multiplie le [Size](../../com.aspose.drawing/size) par un `float` produisant un [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gauche | float | Multiplicateur de type `float`. |
| right | [Size](../../com.aspose.drawing/size) | Multiplicande de type [Size](../../com.aspose.drawing/size). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(Size left, float right) {#op-Multiply-com.aspose.drawing.Size-float-}
```
public static SizeF op_Multiply(Size left, float right)
```


Multiplie le [Size](../../com.aspose.drawing/size) par un `float` produisant un [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Multiplicande de type [Size](../../com.aspose.drawing/size). |
| droite | float | Multiplicateur de type `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(Size left, float right) {#op-Division-com.aspose.drawing.Size-float-}
```
public static SizeF op_Division(Size left, float right)
```


Divise [Size](../../com.aspose.drawing/size) par un `float` produisant [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividende de type [Size](../../com.aspose.drawing/size). |
| droite | float | Diviseur de type `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### op_Equality(Size sz1, Size sz2) {#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Equality(Size sz1, Size sz2)
```


Teste si deux structures [Size](../../com.aspose.drawing/size) sont égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | La structure [Size](../../com.aspose.drawing/size) du côté gauche de l'opérateur d'égalité. |
| sz2 | [Size](../../com.aspose.drawing/size) | La structure [Size](../../com.aspose.drawing/size) du côté droit de l'opérateur d'égalité. |

**Returns:**
booléen - vrai si `sz1` et `sz2` ont la même largeur et hauteur ; sinon, faux.
### op_Inequality(Size sz1, Size sz2) {#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Inequality(Size sz1, Size sz2)
```


Teste si deux structures [Size](../../com.aspose.drawing/size) sont différentes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | La structure [Size](../../com.aspose.drawing/size) du côté gauche de l'opérateur d'inégalité. |
| sz2 | [Size](../../com.aspose.drawing/size) | La structure [Size](../../com.aspose.drawing/size) du côté droit de l'opérateur d'inégalité. |

**Returns:**
booléen - vrai si `sz1` et `sz2` diffèrent soit en largeur soit en hauteur ; faux si `sz1` et `sz2` sont égaux.
### to_Point(Size size) {#to-Point-com.aspose.drawing.Size-}
```
public static Point to_Point(Size size)
```


Convertit le [Size](../../com.aspose.drawing/size) spécifié en un [Point](../../com.aspose.drawing/point).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | Le [Size](../../com.aspose.drawing/size) à convertir. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) structure to which this operator converts.
### add(Size sz1, Size sz2) {#add-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size add(Size sz1, Size sz2)
```


Ajoute la largeur et la hauteur d'une structure [Size](../../com.aspose.drawing/size) à la largeur et la hauteur d'une autre structure [Size](../../com.aspose.drawing/size).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Le premier [Size](../../com.aspose.drawing/size) à ajouter. |
| sz2 | [Size](../../com.aspose.drawing/size) | Le deuxième [Size](../../com.aspose.drawing/size) à ajouter. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### ceiling(SizeF value) {#ceiling-com.aspose.drawing.SizeF-}
```
public static Size ceiling(SizeF value)
```


Convertit la structure [SizeF](../../com.aspose.drawing/sizef) spécifiée en une structure [Size](../../com.aspose.drawing/size) en arrondissant les valeurs de la structure [Size](../../com.aspose.drawing/size) à l'entier supérieur suivant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | La structure [SizeF](../../com.aspose.drawing/sizef) à convertir. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### subtract(Size sz1, Size sz2) {#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size subtract(Size sz1, Size sz2)
```


Soustrait la largeur et la hauteur d'une structure [Size](../../com.aspose.drawing/size) de la largeur et la hauteur d'une autre structure [Size](../../com.aspose.drawing/size).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | La structure [Size](../../com.aspose.drawing/size) du côté gauche de l'opérateur de soustraction. |
| sz2 | [Size](../../com.aspose.drawing/size) | La structure [Size](../../com.aspose.drawing/size) du côté droit de l'opérateur de soustraction. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) that is a result of the subtraction operation.
### truncate(SizeF value) {#truncate-com.aspose.drawing.SizeF-}
```
public static Size truncate(SizeF value)
```


Convertit la structure [SizeF](../../com.aspose.drawing/sizef) spécifiée en une structure [Size](../../com.aspose.drawing/size) en tronquant les valeurs de la structure [SizeF](../../com.aspose.drawing/sizef) à l'entier inférieur suivant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | La structure [SizeF](../../com.aspose.drawing/sizef) à convertir. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### round(SizeF value) {#round-com.aspose.drawing.SizeF-}
```
public static Size round(SizeF value)
```


Convertit la structure [SizeF](../../com.aspose.drawing/sizef) spécifiée en une structure [Size](../../com.aspose.drawing/size) en arrondissant les valeurs de la structure [SizeF](../../com.aspose.drawing/sizef) à l'entier le plus proche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | La structure [SizeF](../../com.aspose.drawing/sizef) à convertir. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.drawing/size) |  |
| obj2 | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Obtient une valeur indiquant si ce [Size](../../com.aspose.drawing/size) a une largeur et une hauteur de 0.

**Returns:**
booléen - une valeur indiquant si ce [Size](../../com.aspose.drawing/size) a une largeur et une hauteur de 0.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtient le composant horizontal de ce [Size](../../com.aspose.drawing/size).

**Returns:**
int - le composant horizontal de ce [Size](../../com.aspose.drawing/size).
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Définit le composant horizontal de ce [Size](../../com.aspose.drawing/size).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | le composant horizontal de ce [Size](../../com.aspose.drawing/size). |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtient le composant vertical de ce [Size](../../com.aspose.drawing/size).

**Returns:**
int - le composant vertical de ce [Size](../../com.aspose.drawing/size).
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Définit le composant vertical de ce [Size](../../com.aspose.drawing/size).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | le composant vertical de ce [Size](../../com.aspose.drawing/size). |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Teste pour voir si l'objet spécifié est un [Size](../../com.aspose.drawing/size) avec les mêmes dimensions que ce [Size](../../com.aspose.drawing/size).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'Object à tester. |

**Returns:**
booléen - vrai si `obj` est un [Size](../../com.aspose.drawing/size) et a la même largeur et hauteur que ce [Size](../../com.aspose.drawing/size) ; sinon, faux.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette structure [Size](../../com.aspose.drawing/size).

**Returns:**
int - Une valeur entière qui spécifie une valeur de hachage pour cette structure [Size](../../com.aspose.drawing/size).
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Size other) {#equals-com.aspose.drawing.Size-}
```
public final boolean equals(Size other)
```


Teste si une autre structure [Size](../../com.aspose.drawing/size) a la même taille que cette structure [Size](../../com.aspose.drawing/size).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [Size](../../com.aspose.drawing/size) | Autre taille à tester |

**Returns:**
booléen - Cette méthode renvoie `true` si l'autre structure [Size](../../com.aspose.drawing/size) et ses propriétés Width et Height sont égales aux propriétés correspondantes de cette structure [Size](../../com.aspose.drawing/size) ; sinon, `false`.
### CloneTo(Size that) {#CloneTo-com.aspose.drawing.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [Size](../../com.aspose.drawing/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### clone() {#clone--}
```
public Size clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
