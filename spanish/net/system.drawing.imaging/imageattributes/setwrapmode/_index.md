---
title: SetWrapMode
second_title: Referencia de Aspose.Drawing para .NET API
description: Establece el modo de ajuste que se utiliza para decidir cómo colocar una textura en mosaico en una forma o en los límites de la forma. Una textura se coloca en mosaico en una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.
type: docs
weight: 240
url: /es/net/system.drawing.imaging/imageattributes/setwrapmode/
---
## SetWrapMode(WrapMode) {#setwrapmode}

Establece el modo de ajuste que se utiliza para decidir cómo colocar una textura en mosaico en una forma o en los límites de la forma. Una textura se coloca en mosaico en una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

```csharp
public void SetWrapMode(WrapMode mode)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| mode | WrapMode | un elemento deWrapMode que especifica cómo se utilizan las copias repetidas de una imagen para colocar en mosaico un área. |

### Ver también

* enum [WrapMode](../../../system.drawing.drawing2d/wrapmode)
* class [ImageAttributes](../../imageattributes)
* espacio de nombres [System.Drawing.Imaging](../../imageattributes)
* asamblea [Aspose.Drawing](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

Establece el modo de ajuste y el color utilizado para decidir cómo colocar una textura en mosaico en una forma o en los límites de la forma. Una textura se coloca en mosaico en una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| mode | WrapMode | un elemento deWrapMode que especifica cómo se utilizan las copias repetidas de una imagen para colocar en mosaico un área. |
| color | Color | UnColorobjeto que especifica el color de los píxeles fuera de una imagen renderizada. Este color es visible si el parámetro de modo se establece enClamp y el rectángulo de origen pasó a[`DrawImage`](../../../system.drawing/graphics/drawimage) es más grande que la imagen misma. |

### Ver también

* enum [WrapMode](../../../system.drawing.drawing2d/wrapmode)
* struct [Color](../../../system.drawing/color)
* class [ImageAttributes](../../imageattributes)
* espacio de nombres [System.Drawing.Imaging](../../imageattributes)
* asamblea [Aspose.Drawing](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

Establece el modo de ajuste y el color utilizado para decidir cómo colocar una textura en mosaico en una forma o en los límites de la forma. Una textura se coloca en mosaico en una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| mode | WrapMode | un elemento deWrapMode que especifica cómo se utilizan las copias repetidas de una imagen para colocar en mosaico un área. |
| color | Color | Un objeto de color que especifica el color de los píxeles fuera de una imagen renderizada. Este color es visible si el parámetro de modo se establece enClamp y el rectángulo de origen pasado a[`DrawImage`](../../../system.drawing/graphics/drawimage) es más grande que la imagen misma. |
| clamp | Boolean | Este parámetro no tiene efecto. Establézcalo en falso. |

### Ver también

* enum [WrapMode](../../../system.drawing.drawing2d/wrapmode)
* struct [Color](../../../system.drawing/color)
* class [ImageAttributes](../../imageattributes)
* espacio de nombres [System.Drawing.Imaging](../../imageattributes)
* asamblea [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
