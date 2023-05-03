---
title: DrawPie
second_title: Référence de l'API Aspose.Drawing pour .NET
description: Dessine une forme circulaire définie par une ellipse spécifiée par une structure RectangleF et deux lignes radiales.
type: docs
weight: 400
url: /fr/net/system.drawing/graphics/drawpie/
---
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

Dessine une forme circulaire définie par une ellipse spécifiée par une structure RectangleF et deux lignes radiales.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | Stylo qui détermine la couleur, la largeur et le style de la forme circulaire. |
| rect | RectangleF | Structure RectangleF qui représente le rectangle englobant qui définit l'ellipse d'où provient la forme circulaire. |
| startAngle | Single | Angle mesuré en degrés dans le sens des aiguilles d'une montre entre l'axe des x et le premier côté de la forme circulaire. |
| sweepAngle | Single | Angle mesuré en degrés dans le sens des aiguilles d'une montre à partir du paramètre startAngle jusqu'au deuxième côté de la forme circulaire. |

### Voir également

* class [Pen](../../pen)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* espace de noms [System.Drawing](../../graphics)
* Assemblée [Aspose.Drawing](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie}

Dessine une forme circulaire définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | Pen qui détermine la couleur, la largeur et le style de la forme circulaire. |
| x | Single | Coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse d'où provient la forme circulaire. |
| y | Single | Coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse d'où provient la forme circulaire. |
| width | Single | Largeur du rectangle englobant qui définit l'ellipse d'où provient la forme circulaire. |
| height | Single | Hauteur du rectangle englobant qui définit l'ellipse d'où provient la forme circulaire. |
| startAngle | Single | Angle mesuré en degrés dans le sens des aiguilles d'une montre entre l'axe des x et le premier côté de la forme circulaire. |
| sweepAngle | Single | Angle mesuré en degrés dans le sens des aiguilles d'une montre entre le paramètre startAngle et le deuxième côté de la forme du secteur. |

### Voir également

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* espace de noms [System.Drawing](../../graphics)
* Assemblée [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->