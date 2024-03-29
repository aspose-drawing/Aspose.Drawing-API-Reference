---
title: ImageLockMode
second_title: Referencia de Aspose.Drawing para .NET API
description: Especifica banderas que se pasan al parámetro de banderas delLockBits../system.drawing/bitmap/lockbits método. ElLockBits../system.drawing/bitmap/lockbits El método bloquea una parte de una imagen para que pueda leer o escribir los datos de píxeles.
type: docs
weight: 780
url: /es/net/system.drawing.imaging/imagelockmode/
---
## ImageLockMode enumeration

Especifica banderas que se pasan al parámetro de banderas del[`LockBits`](../../system.drawing/bitmap/lockbits) método. El[`LockBits`](../../system.drawing/bitmap/lockbits) El método bloquea una parte de una imagen para que pueda leer o escribir los datos de píxeles.

```csharp
public enum ImageLockMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| ReadOnly | `1` | Especifica que una parte de la imagen está bloqueada para lectura. |
| WriteOnly | `2` | Especifica que una parte de la imagen está bloqueada para escritura. |
| ReadWrite | `3` | Especifica que una parte de la imagen está bloqueada para lectura o escritura. |
| UserInputBuffer | `4` | Especifica que el usuario asigna el búfer utilizado para leer o escribir datos de píxeles. Si se establece este indicador, el*flags* parámetro de la[`LockBits`](../../system.drawing/bitmap/lockbits) El método sirve como parámetro de entrada (y posiblemente como parámetro de salida). Si se borra este indicador, entonces el*flags* El parámetro solo sirve como parámetro de salida. |

### Ver también

* espacio de nombres [System.Drawing.Imaging](../../system.drawing.imaging)
* asamblea [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
