---
title: Metered
second_title: Référence de l'API Aspose.Drawing pour .NET
description: Fournit des méthodes pour définir la clé mesurée.
type: docs
weight: 20
url: /fr/net/aspose.drawing/metered/
---
## Metered class

Fournit des méthodes pour définir la clé mesurée.

```csharp
public sealed class Metered : IDisposable
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Metered](metered)() | Initialise une nouvelle instance du[`Metered`](../metered) classe. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Dispose](../../aspose.drawing/metered/dispose)() | Effectue des tâches définies par l'application associées à la libération, à la libération ou à la réinitialisation des ressources non gérées. |
| [SetMeteredKey](../../aspose.drawing/metered/setmeteredkey)(string, string) | Définit les clés publiques et privées mesurées |
| static [GetConsumptionCredit](../../aspose.drawing/metered/getconsumptioncredit)() | Obtient un crédit de consommation. |
| static [GetConsumptionQuantity](../../aspose.drawing/metered/getconsumptionquantity)() | Obtient la taille du fichier de consommation. |

### Exemples

Dans cet exemple, une tentative sera faite pour définir des clés publiques et privées mesurées

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

le fichier jar du composant :

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Voir également

* espace de noms [Aspose.Drawing](../../aspose.drawing)
* Assemblée [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
