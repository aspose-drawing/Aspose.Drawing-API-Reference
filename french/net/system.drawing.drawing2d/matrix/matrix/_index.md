---
title: Matrix
second_title: Référence de l'API Aspose.Drawing pour .NET
description: Initialise une nouvelle instance de la classe Matrix en tant que matrice didentité.
type: docs
weight: 10
url: /fr/net/system.drawing.drawing2d/matrix/matrix/
---
## Matrix() {#constructor}

Initialise une nouvelle instance de la classe Matrix en tant que matrice d'identité.

```csharp
public Matrix()
```

### Voir également

* class [Matrix](../../matrix)
* espace de noms [System.Drawing.Drawing2D](../../matrix)
* Assemblée [Aspose.Drawing](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_1}

Initialise une nouvelle instance de la classe Matrix avec les éléments spécifiés.

```csharp
public Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| m11 | Single | La valeur de la première ligne et de la première colonne de la nouvelle matrice. |
| m12 | Single | La valeur de la première ligne et de la deuxième colonne de la nouvelle matrice. |
| m21 | Single | La valeur de la deuxième ligne et de la première colonne de la nouvelle matrice. |
| m22 | Single | La valeur de la deuxième ligne et de la deuxième colonne de la nouvelle matrice. |
| dx | Single | La valeur de la troisième ligne et de la première colonne de la nouvelle matrice. |
| dy | Single | La valeur de la troisième ligne et de la deuxième colonne de la nouvelle matrice. |

### Voir également

* class [Matrix](../../matrix)
* espace de noms [System.Drawing.Drawing2D](../../matrix)
* Assemblée [Aspose.Drawing](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_2}

Initialise une nouvelle instance du[`Matrix`](../../matrix) class à la transformation géométrique définie par le rectangle et le tableau de points spécifiés.

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rect | Rectangle | UNRectangle structure qui représente le rectangle à transformer. |
| plgpts | Point[] | Un tableau de troisPoint structures qui représentent les points d'un parallélogramme vers lesquels les coins supérieur gauche, supérieur droit et inférieur gauche du rectangle doivent être transformés. Le coin inférieur droit du parallélogramme est impliqué par les trois premiers coins. |

### Voir également

* struct [Rectangle](../../../system.drawing/rectangle)
* struct [Point](../../../system.drawing/point)
* class [Matrix](../../matrix)
* espace de noms [System.Drawing.Drawing2D](../../matrix)
* Assemblée [Aspose.Drawing](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_3}

Initialise une nouvelle instance du[`Matrix`](../../matrix) class à la transformation géométrique définie par le rectangle et le tableau de points spécifiés.

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rect | RectangleF | UNRectangleF structure qui représente le rectangle à transformer. |
| plgpts | PointF[] | Un tableau de troisPointF structures qui représentent les points d'un parallélogramme vers lesquels les coins supérieur gauche, supérieur droit et inférieur gauche du rectangle doivent être transformés. Le coin inférieur droit du parallélogramme est impliqué par les trois premiers coins. |

### Voir également

* struct [RectangleF](../../../system.drawing/rectanglef)
* struct [PointF](../../../system.drawing/pointf)
* class [Matrix](../../matrix)
* espace de noms [System.Drawing.Drawing2D](../../matrix)
* Assemblée [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
