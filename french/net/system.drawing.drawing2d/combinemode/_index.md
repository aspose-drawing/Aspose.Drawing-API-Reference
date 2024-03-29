---
title: CombineMode
second_title: Référence de l'API Aspose.Drawing pour .NET
description: Spécifie comment différentes régions de découpage peuvent être combinées.
type: docs
weight: 160
url: /fr/net/system.drawing.drawing2d/combinemode/
---
## CombineMode enumeration

Spécifie comment différentes régions de découpage peuvent être combinées.

```csharp
public enum CombineMode
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Replace | `0` | Une zone de découpage est remplacée par une autre. |
| Intersect | `1` | Deux régions de découpage sont combinées en prenant leur intersection. |
| Union | `2` | Deux zones de découpage sont combinées en prenant l'union des deux. |
| Xor | `3` | Deux régions de découpage sont combinées en ne prenant que les zones délimitées par l'une ou l'autre région, mais pas les deux. |
| Exclude | `4` | Spécifie que la région existante est remplacée par le résultat de la suppression de la nouvelle région de la région existante. En d'autres termes, la nouvelle région est exclue de la région existante. |
| Complement | `5` | Spécifie que la région existante est remplacée par le résultat de la suppression de la région existante de la nouvelle région. En d'autres termes, la région existante est exclue de la nouvelle région. |

### Voir également

* espace de noms [System.Drawing.Drawing2D](../../system.drawing.drawing2d)
* Assemblée [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
