---
title: Metered
second_title: Aspose.Drawing für .NET-API-Referenz
description: Bietet Methoden zum Festlegen von gemessenen Schlüsseln.
type: docs
weight: 20
url: /de/net/aspose.drawing/metered/
---
## Metered class

Bietet Methoden zum Festlegen von gemessenen Schlüsseln.

```csharp
public sealed class Metered : IDisposable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Metered](metered)() | Initialisiert eine neue Instanz von[`Metered`](../metered) Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.drawing/metered/dispose)() | Führt anwendungsdefinierte Aufgaben aus, die mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [SetMeteredKey](../../aspose.drawing/metered/setmeteredkey)(string, string) | Legt gemessene öffentliche und private Schlüssel fest |
| static [GetConsumptionCredit](../../aspose.drawing/metered/getconsumptioncredit)() | erhält Verbrauchsguthaben. |
| static [GetConsumptionQuantity](../../aspose.drawing/metered/getconsumptionquantity)() | Ruft die Größe der Verbrauchsdatei ab. |

### Beispiele

In diesem Beispiel wird versucht, einen getakteten öffentlichen und privaten Schlüssel zu setzen

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

die Komponenten-JAR-Datei:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Siehe auch

* namensraum [Aspose.Drawing](../../aspose.drawing)
* Montage [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
