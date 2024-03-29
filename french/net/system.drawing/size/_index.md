---
title: Size
second_title: Référence de l'API Aspose.Drawing pour .NET
description: Stocke une paire ordonnée dentiers généralement la largeur et la hauteur dun rectangle.
type: docs
weight: 1080
url: /fr/net/system.drawing/size/
---
## Size structure

Stocke une paire ordonnée d'entiers, généralement la largeur et la hauteur d'un rectangle.

```csharp
public struct Size : IEquatable<Size>
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Size](size#constructor_1)(Point) | Initialise une nouvelle instance du[`Size`](../size) structure à partir du spécifiéPoint . |
| [Size](size#constructor)(int, int) | Initialise une nouvelle instance du[`Size`](../size) structure à partir des dimensions spécifiées. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Height](../../system.drawing/size/height) { get; set; } | Obtient ou définit la composante verticale de cetteSize . |
| [IsEmpty](../../system.drawing/size/isempty) { get; } | Obtient une valeur indiquant si celaSize a une largeur et une hauteur de 0. |
| [Width](../../system.drawing/size/width) { get; set; } | Obtient ou définit la composante horizontale de cetteSize . |

## Méthodes

| Nom | La description |
| --- | --- |
| static [Add](../../system.drawing/size/add)(Size, Size) | Ajoute la largeur et la hauteur d'unSize structure à la largeur et à la hauteur de une autreSize structure. |
| static [Ceiling](../../system.drawing/size/ceiling)(SizeF) | Convertit le spécifiéSizeF structurer à unSize structure en arrondissant les valeurs de laSize structure aux valeurs entières immédiatement supérieures. |
| static [Round](../../system.drawing/size/round)(SizeF) | Convertit le spécifiéSizeF structurer à unSize structure en arrondissant les valeurs de laSizeF structure aux valeurs entières les plus proches. |
| static [Subtract](../../system.drawing/size/subtract)(Size, Size) | Soustrait la largeur et la hauteur d'unSize structure de la largeur et de la hauteur de une autreSize structure. |
| static [Truncate](../../system.drawing/size/truncate)(SizeF) | Convertit le spécifiéSizeF structurer à unSize structure en tronquant les valeurs desSizeF structure aux valeurs entières inférieures suivantes. |
| override [Equals](../../system.drawing/size/equals#equals_1)(object) | Teste pour voir si l'objet spécifié est unSize avec les mêmes dimensions que celle-ciSize . |
| [Equals](../../system.drawing/size/equals#equals)(Size) | Teste si d'autres[`Size`](../size) structure a la même taille que celle-ci[`Size`](../size) structure. |
| override [GetHashCode](../../system.drawing/size/gethashcode)() | Renvoie un code de hachage pour celaSize structure. |
| override [ToString](../../system.drawing/size/tostring)() | Convertit les attributs de ce[`Size`](../size) en une chaîne lisible par l'homme. |
| [operator +](../../system.drawing/size/op_addition) | Ajoute la largeur et la hauteur d'unSize structure à la largeur et à la hauteur de une autreSize structure. |
| [operator /](../../system.drawing/size/op_division#op_division) | divise[`Size`](../size) par unInt32 produire[`Size`](../size) . (2 operators) |
| [operator ==](../../system.drawing/size/op_equality) | Teste si deuxSize les structures sont égales. |
| [explicit operator](../../system.drawing/size/op_explicit) | Convertit le spécifiéSize à unPoint . |
| [implicit operator](../../system.drawing/size/op_implicit) | Convertit le spécifiéSize à unSizeF . |
| [operator !=](../../system.drawing/size/op_inequality) | Teste si deuxSize les structures sont différentes. |
| [operator *](../../system.drawing/size/op_multiply#op_multiply) | Multiplie un[`Size`](../size) par unInt32 produire[`Size`](../size) . (4 operators) |
| [operator -](../../system.drawing/size/op_subtraction) | Soustrait la largeur et la hauteur d'unSize structure de la largeur et de la hauteur de une autreSize structure. |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Empty](../../system.drawing/size/empty) | Obtient unSize structure qui a unHeight etWidth valeur de 0. |

### Voir également

* espace de noms [System.Drawing](../../system.drawing)
* Assemblée [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
