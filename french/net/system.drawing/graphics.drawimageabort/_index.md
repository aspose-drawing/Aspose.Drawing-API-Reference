---
title: Graphics.DrawImageAbort
second_title: Référence de l'API Aspose.Drawing pour .NET
description: Fournit une méthode de rappel pour décider quand leDrawImage./graphics/drawimage La méthode doit annuler prématurément lexécution et arrêter de dessiner une image.
type: docs
weight: 540
url: /fr/net/system.drawing/graphics.drawimageabort/
---
## Graphics.DrawImageAbort delegate

Fournit une méthode de rappel pour décider quand le[`DrawImage`](../graphics/drawimage) La méthode doit annuler prématurément l'exécution et arrêter de dessiner une image.

```csharp
public delegate bool DrawImageAbort(IntPtr callbackdata);
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| callbackdata | IntPtr | Pointeur interne qui spécifie les données pour la méthode de rappel. Ce paramètre n'est pas passé par tous[`DrawImage`](../graphics/drawimage) surcharges. Vous pouvez tester son absence en vérifiant la valeurZero . |

### Return_Value

Cette méthode renvoie true si elle décide que le[`DrawImage`](../graphics/drawimage) La méthode doit arrêter prématurément l'exécution. Sinon, il renvoie false pour indiquer que le[`DrawImage`](../graphics/drawimage) La méthode doit continuer son exécution.

### Voir également

* class [Graphics](../graphics)
* espace de noms [System.Drawing](../../system.drawing)
* Assemblée [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
