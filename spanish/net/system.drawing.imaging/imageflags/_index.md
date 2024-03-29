---
title: ImageFlags
second_title: Referencia de Aspose.Drawing para .NET API
description: Especifica los atributos de los datos de píxeles contenidos en unImage../system.drawing/image objeto. La propiedad Flags devuelve un miembro de esta enumeración. Esta enumeración tiene un atributo FlagsAttribute que permite una combinación bit a bit de sus valores de miembro.
type: docs
weight: 760
url: /es/net/system.drawing.imaging/imageflags/
---
## ImageFlags enumeration

Especifica los atributos de los datos de píxeles contenidos en un[`Image`](../../system.drawing/image) objeto. La propiedad Flags devuelve un miembro de esta enumeración. Esta enumeración tiene un atributo FlagsAttribute que permite una combinación bit a bit de sus valores de miembro.

```csharp
[Flags]
public enum ImageFlags
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | No hay información de formato |
| Scalable | `1` | Los datos de píxeles son escalables. |
| HasAlpha | `2` | Los datos de píxeles contienen información alfa. |
| HasTranslucent | `4` | Especifica que los datos de píxeles tienen valores alfa distintos de 0 (transparente) y 255 (opaco) |
| PartiallyScalable | `8` | Los datos de píxeles son parcialmente escalables, pero existen algunas limitaciones. |
| ColorSpaceRgb | `10` | Los datos de píxeles utilizan un espacio de color RGB. |
| ColorSpaceCmyk | `20` | Los datos de píxeles utilizan un espacio de color CMYK. |
| ColorSpaceGray | `40` | Los datos de píxeles están en escala de grises. |
| ColorSpaceYcbcr | `80` | Especifica que la imagen se almacena utilizando un espacio de color YCBCR. |
| ColorSpaceYcck | `100` | Especifica que la imagen se almacena usando un espacio de color YCCK. |
| HasRealDpi | `1000` | Especifica que la información de puntos por pulgada se almacena en la imagen. |
| HasRealPixelSize | `2000` | Especifica que el tamaño de píxel se almacena en la imagen. |
| ReadOnly | `10000` | Los datos de píxeles son de solo lectura. |
| Caching | `20000` | Los datos de píxeles se pueden almacenar en caché para un acceso más rápido. |

### Ver también

* espacio de nombres [System.Drawing.Imaging](../../system.drawing.imaging)
* asamblea [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
