---
title: Metered
second_title: Referencia de Aspose.Drawing para .NET API
description: Proporciona métodos para configurar la clave medida.
type: docs
weight: 20
url: /es/net/aspose.drawing/metered/
---
## Metered class

Proporciona métodos para configurar la clave medida.

```csharp
public sealed class Metered : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Metered](metered)() | Inicializa una nueva instancia del[`Metered`](../metered) clase. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.drawing/metered/dispose)() | Realiza tareas definidas por la aplicación asociadas con liberar, liberar o restablecer recursos no administrados. |
| [SetMeteredKey](../../aspose.drawing/metered/setmeteredkey)(string, string) | Establece claves públicas y privadas medidas |
| static [GetConsumptionCredit](../../aspose.drawing/metered/getconsumptioncredit)() | Obtiene crédito de consumo. |
| static [GetConsumptionQuantity](../../aspose.drawing/metered/getconsumptionquantity)() | Obtiene el tamaño del archivo de consumo. |

### Ejemplos

En este ejemplo, se intentará establecer una clave pública y privada medidas

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

el archivo jar del componente:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Ver también

* espacio de nombres [Aspose.Drawing](../../aspose.drawing)
* asamblea [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->