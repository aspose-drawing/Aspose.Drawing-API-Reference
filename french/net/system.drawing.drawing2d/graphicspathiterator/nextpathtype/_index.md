---
title: NextPathType
second_title: Référence de l'API Aspose.Drawing pour .NET
description: Obtient lindex de départ et lindex de fin du prochain groupe de points de données qui ont tous le même type.
type: docs
weight: 90
url: /fr/net/system.drawing.drawing2d/graphicspathiterator/nextpathtype/
---
## GraphicsPathIterator.NextPathType method

Obtient l'index de départ et l'index de fin du prochain groupe de points de données qui ont tous le même type.

```csharp
public int NextPathType(out byte pathType, out int startIndex, out int endIndex)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pathType | Byte& | [out] Reçoit le type de point partagé par tous les points du groupe. Les types possibles peuvent être récupérés à partir duPathPointType énumération. |
| startIndex | Int32& | [out] Reçoit l'indice de départ du groupe de points. |
| endIndex | Int32& | [out] Reçoit l'indice de fin du groupe de points. |

### Return_Value

Cette méthode renvoie le nombre de points de données dans le groupe. S'il n'y a plus de groupes dans le chemin, cette méthode renvoie 0.

### Voir également

* class [GraphicsPathIterator](../../graphicspathiterator)
* espace de noms [System.Drawing.Drawing2D](../../graphicspathiterator)
* Assemblée [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
