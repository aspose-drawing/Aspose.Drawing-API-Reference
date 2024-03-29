---
title: License
second_title: Aspose.Drawing per .NET API Reference
description: Fornisce i metodi per concedere in licenza il componente.
type: docs
weight: 10
url: /it/net/aspose.drawing/license/
---
## License class

Fornisce i metodi per concedere in licenza il componente.

```csharp
public class License
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [License](license)() | Inizializza una nuova istanza di questa classe. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetLicense](../../aspose.drawing/license/setlicense#setlicense)(Stream) | concede in licenza il componente. |
| [SetLicense](../../aspose.drawing/license/setlicense#setlicense_1)(string) | concede in licenza il componente. |

### Esempi

In questo esempio, verrà effettuato un tentativo di trovare un file di licenza denominato MyLicense.lic nella cartella che contiene  il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e quindi nelle risorse incorporate dell'assembly chiamante.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");

```

### Guarda anche

* spazio dei nomi [Aspose.Drawing](../../aspose.drawing)
* assemblea [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
