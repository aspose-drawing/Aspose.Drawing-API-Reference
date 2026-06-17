---
title: SizeF
second_title: Référence de l'API Aspose.Drawing pour Java
description: Stocke une paire ordonnée de nombres à virgule flottante représentant généralement la largeur et la hauteur d'un rectangle.
type: docs
weight: 43
url: /fr/java/com.aspose.drawing/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class SizeF extends Struct<SizeF> implements System.IEquatable<SizeF>, Cloneable
```

Stocke une paire ordonnée de nombres à virgule flottante, généralement la largeur et la hauteur d'un rectangle.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(float width, float height)](#SizeF-float-float-) | Initialise une nouvelle instance de la structure SizeF à partir des dimensions spécifiées. |
| [SizeF(PointF pt)](#SizeF-com.aspose.drawing.PointF-) | Initialise une nouvelle instance de la structure [SizeF](../../com.aspose.drawing/sizef). |
| [SizeF(SizeF size)](#SizeF-com.aspose.drawing.SizeF-) | Initialise une nouvelle instance de la structure [SizeF](../../com.aspose.drawing/sizef). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [op_Equality(SizeF sz1, SizeF sz2)](#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Teste si deux structures [SizeF](../../com.aspose.drawing/sizef) sont égales. |
| [op_Inequality(SizeF sz1, SizeF sz2)](#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Teste si deux structures [SizeF](../../com.aspose.drawing/sizef) sont différentes. |
| [add(SizeF sz1, SizeF sz2)](#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Ajoute la largeur et la hauteur d'une structure [SizeF](../../com.aspose.drawing/sizef) à la largeur et la hauteur d'une autre structure [SizeF](../../com.aspose.drawing/sizef). |
| [subtract(SizeF sz1, SizeF sz2)](#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Soustrait la largeur et la hauteur d'une structure [SizeF](../../com.aspose.drawing/sizef) de la largeur et la hauteur d'une autre structure [SizeF](../../com.aspose.drawing/sizef). |
| [op_Addition(SizeF sz1, SizeF sz2)](#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Ajoute la largeur et la hauteur d'une structure [SizeF](../../com.aspose.drawing/sizef) à la largeur et la hauteur d'une autre structure [SizeF](../../com.aspose.drawing/sizef). |
| [op_Subtraction(SizeF sz1, SizeF sz2)](#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Soustrait la largeur et la hauteur d'une structure [SizeF](../../com.aspose.drawing/sizef) de la largeur et la hauteur d'une autre structure [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(float left, SizeF right)](#op-Multiply-float-com.aspose.drawing.SizeF-) | Multiplie [SizeF](../../com.aspose.drawing/sizef) par un `float` produisant [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(SizeF left, float right)](#op-Multiply-com.aspose.drawing.SizeF-float-) | Multiplie [SizeF](../../com.aspose.drawing/sizef) par un `float` produisant [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(SizeF left, float right)](#op-Division-com.aspose.drawing.SizeF-float-) | Divise [SizeF](../../com.aspose.drawing/sizef) par un `float` produisant [SizeF](../../com.aspose.drawing/sizef). |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si cette structure [SizeF](../../com.aspose.drawing/sizef) a une largeur et une hauteur nulles. |
| [getWidth()](#getWidth--) | Obtient le composant horizontal de cette structure SizeF. |
| [setWidth(float value)](#setWidth-float-) | Définit le composant horizontal de cette structure SizeF. |
| [getHeight()](#getHeight--) | Obtient le composant vertical de cette structure SizeF. |
| [setHeight(float value)](#setHeight-float-) | Définit le composant vertical de cette structure SizeF. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette structure [SizeF](../../com.aspose.drawing/sizef). |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Teste pour voir si l'objet spécifié est une structure [SizeF](../../com.aspose.drawing/sizef) avec les mêmes dimensions que cette structure [SizeF](../../com.aspose.drawing/sizef). |
| [toSize()](#toSize--) | Convertit une structure [SizeF](../../com.aspose.drawing/sizef) en une structure [Size](../../com.aspose.drawing/size). |
| [toPointF()](#toPointF--) | Convertit une structure [SizeF](../../com.aspose.drawing/sizef) en une structure [PointF](../../com.aspose.drawing/pointf). |
| [equals(SizeF other)](#equals-com.aspose.drawing.SizeF-) | Teste si une autre structure [SizeF](../../com.aspose.drawing/sizef) a la même taille que cette structure [SizeF](../../com.aspose.drawing/sizef). |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.drawing.SizeF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Initialise une nouvelle instance de la structure SizeF à partir des dimensions spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | float | Le composant largeur de la nouvelle structure SizeF. |
| hauteur | float | Le composant hauteur de la nouvelle structure SizeF. |

### SizeF(PointF pt) {#SizeF-com.aspose.drawing.PointF-}
```
public SizeF(PointF pt)
```


Initialise une nouvelle instance de la structure [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | La structure [PointF](../../com.aspose.drawing/pointf) à partir de laquelle initialiser cette structure [SizeF](../../com.aspose.drawing/sizef). |

### SizeF(SizeF size) {#SizeF-com.aspose.drawing.SizeF-}
```
public SizeF(SizeF size)
```


Initialise une nouvelle instance de la structure [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | La structure [SizeF](../../com.aspose.drawing/sizef) à partir de laquelle créer la nouvelle structure [SizeF](../../com.aspose.drawing/sizef). |

### op_Equality(SizeF sz1, SizeF sz2) {#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Equality(SizeF sz1, SizeF sz2)
```


Teste si deux structures [SizeF](../../com.aspose.drawing/sizef) sont égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La structure [SizeF](../../com.aspose.drawing/sizef) du côté gauche de l'opérateur d'égalité. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La structure [SizeF](../../com.aspose.drawing/sizef) du côté droit de l'opérateur d'égalité. |

**Returns:**
booléen - Cet opérateur renvoie vrai si `sz1` et `sz2` ont une largeur et une hauteur égales ; sinon, faux.
### op_Inequality(SizeF sz1, SizeF sz2) {#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Inequality(SizeF sz1, SizeF sz2)
```


Teste si deux structures [SizeF](../../com.aspose.drawing/sizef) sont différentes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La structure [SizeF](../../com.aspose.drawing/sizef) du côté gauche de l'opérateur d'inégalité. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La structure [SizeF](../../com.aspose.drawing/sizef) du côté droit de l'opérateur d'inégalité. |

**Returns:**
booléen - Cet opérateur renvoie vrai si `sz1` et `sz2` diffèrent soit en largeur, soit en hauteur ; faux si `sz1` et `sz2` sont égaux.
### add(SizeF sz1, SizeF sz2) {#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF add(SizeF sz1, SizeF sz2)
```


Ajoute la largeur et la hauteur d'une structure [SizeF](../../com.aspose.drawing/sizef) à la largeur et la hauteur d'une autre structure [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La première structure [SizeF](../../com.aspose.drawing/sizef) à ajouter. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La deuxième structure [SizeF](../../com.aspose.drawing/sizef) à ajouter. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is the result of the addition operation.
### subtract(SizeF sz1, SizeF sz2) {#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF subtract(SizeF sz1, SizeF sz2)
```


Soustrait la largeur et la hauteur d'une structure [SizeF](../../com.aspose.drawing/sizef) de la largeur et la hauteur d'une autre structure [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La structure [SizeF](../../com.aspose.drawing/sizef) du côté gauche de l'opérateur de soustraction. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La structure [SizeF](../../com.aspose.drawing/sizef) du côté droit de l'opérateur de soustraction. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is a result of the subtraction operation.
### op_Addition(SizeF sz1, SizeF sz2) {#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Addition(SizeF sz1, SizeF sz2)
```


Ajoute la largeur et la hauteur d'une structure [SizeF](../../com.aspose.drawing/sizef) à la largeur et la hauteur d'une autre structure [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La première structure [SizeF](../../com.aspose.drawing/sizef) à ajouter. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La deuxième structure [SizeF](../../com.aspose.drawing/sizef) à ajouter. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(SizeF sz1, SizeF sz2) {#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Subtraction(SizeF sz1, SizeF sz2)
```


Soustrait la largeur et la hauteur d'une structure [SizeF](../../com.aspose.drawing/sizef) de la largeur et la hauteur d'une autre structure [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | La structure [SizeF](../../com.aspose.drawing/sizef) du côté gauche de l'opérateur de soustraction. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | La structure [SizeF](../../com.aspose.drawing/sizef) du côté droit de l'opérateur de soustraction. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that is the result of the subtraction operation.
### op_Multiply(float left, SizeF right) {#op-Multiply-float-com.aspose.drawing.SizeF-}
```
public static SizeF op_Multiply(float left, SizeF right)
```


Multiplie [SizeF](../../com.aspose.drawing/sizef) par un `float` produisant [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gauche | float | Multiplicateur de type `float`. |
| right | [SizeF](../../com.aspose.drawing/sizef) | Multiplicande de type [SizeF](../../com.aspose.drawing/sizef). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(SizeF left, float right) {#op-Multiply-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Multiply(SizeF left, float right)
```


Multiplie [SizeF](../../com.aspose.drawing/sizef) par un `float` produisant [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Multiplicande de type [SizeF](../../com.aspose.drawing/sizef). |
| droite | float | Multiplicateur de type `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(SizeF left, float right) {#op-Division-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Division(SizeF left, float right)
```


Divise [SizeF](../../com.aspose.drawing/sizef) par un `float` produisant [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Dividende de type [SizeF](../../com.aspose.drawing/sizef). |
| droite | float | Diviseur de type `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### to_PointF(SizeF size) {#to-PointF-com.aspose.drawing.SizeF-}
```
public static PointF to_PointF(SizeF size)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.drawing/sizef) |  |
| obj2 | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Obtient une valeur indiquant si cette structure [SizeF](../../com.aspose.drawing/sizef) a une largeur et une hauteur nulles.

**Returns:**
booléen - une valeur indiquant si cette structure [SizeF](../../com.aspose.drawing/sizef) a une largeur et une hauteur nulles.
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Obtient le composant horizontal de cette structure SizeF.

**Returns:**
float - le composant horizontal de cette structure SizeF.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Définit le composant horizontal de cette structure SizeF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | le composant horizontal de cette structure SizeF. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Obtient le composant vertical de cette structure SizeF.

**Returns:**
float - le composant vertical de cette structure SizeF.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Définit le composant vertical de cette structure SizeF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | le composant vertical de cette structure SizeF. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette structure [SizeF](../../com.aspose.drawing/sizef).

**Returns:**
int - Une valeur entière qui spécifie une valeur de hachage pour cette structure [SizeF](../../com.aspose.drawing/sizef).
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


Teste pour voir si l'objet spécifié est une structure [SizeF](../../com.aspose.drawing/sizef) avec les mêmes dimensions que cette structure [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'Object à tester. |

**Returns:**
booléen - Cette méthode renvoie `true` si obj est un [SizeF](../../com.aspose.drawing/sizef) et possède la même largeur et hauteur que ce SizeF ; sinon, `false`.
### toSize() {#toSize--}
```
public final Size toSize()
```


Convertit une structure [SizeF](../../com.aspose.drawing/sizef) en une structure [Size](../../com.aspose.drawing/size).

**Returns:**
[Size](../../com.aspose.drawing/size) - Returns a [Size](../../com.aspose.drawing/size) structure.
### toPointF() {#toPointF--}
```
public final PointF toPointF()
```


Convertit une structure [SizeF](../../com.aspose.drawing/sizef) en une structure [PointF](../../com.aspose.drawing/pointf).

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - Returns a [PointF](../../com.aspose.drawing/pointf) structure.
### equals(SizeF other) {#equals-com.aspose.drawing.SizeF-}
```
public final boolean equals(SizeF other)
```


Teste si une autre structure [SizeF](../../com.aspose.drawing/sizef) a la même taille que cette structure [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [SizeF](../../com.aspose.drawing/sizef) | Autre taille à tester |

**Returns:**
booléen - Cette méthode renvoie `true` si l'autre structure [SizeF](../../com.aspose.drawing/sizef) et ses propriétés Width et Height sont égales aux propriétés correspondantes de cette structure [SizeF](../../com.aspose.drawing/sizef) ; sinon, `false`.
### CloneTo(SizeF that) {#CloneTo-com.aspose.drawing.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.drawing/sizef) |  |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
