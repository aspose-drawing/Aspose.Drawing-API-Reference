---
title: NextMarker
second_title: Referencia de Aspose.Drawing para .NET API
description: Incrementa elGraphicsPathIteratorsystem.drawing.drawing2d/graphicspathiteratoral siguiente marcador en la ruta y devuelve los índices de inicio y fin por medio de los parámetros out.
type: docs
weight: 80
url: /es/net/system.drawing.drawing2d/graphicspathiterator/nextmarker/
---
## NextMarker(out int, out int) {#nextmarker}

Incrementa el[`GraphicsPathIterator`](../../graphicspathiterator)al siguiente marcador en la ruta y devuelve los índices de inicio y fin por medio de los parámetros [out].

```csharp
public int NextMarker(out int startIndex, out int endIndex)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startIndex | Int32& | [out] La referencia entera proporcionada a este parámetro recibe el índice del punto que inicia un subtrayecto. |
| endIndex | Int32& | [out] La referencia entera suministrada a este parámetro recibe el índice del punto que finaliza la subruta a la que apunta startIndex. |

### Valor_devuelto

El número de puntos entre este marcador y el siguiente.

### Ver también

* class [GraphicsPathIterator](../../graphicspathiterator)
* espacio de nombres [System.Drawing.Drawing2D](../../graphicspathiterator)
* asamblea [Aspose.Drawing](../../../)

---

## NextMarker(GraphicsPath) {#nextmarker_1}

Esto[`GraphicsPathIterator`](../../graphicspathiterator) objeto tiene un[`GraphicsPath`](../../graphicspath) objeto asociado con él. Este método incrementa el asociado[`GraphicsPath`](../../graphicspath) al siguiente marcador en su ruta y copia todos los puntos contenidos entre el marcador actual y el siguiente marcador (o final de ruta) a un segundo[`GraphicsPath`](../../graphicspath) objeto pasado al parámetro.

```csharp
public int NextMarker(GraphicsPath path)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | GraphicsPath | los[`GraphicsPath`](../../graphicspath) objeto al que se copiarán los puntos. |

### Valor_devuelto

El número de puntos entre este marcador y el siguiente.

### Ver también

* class [GraphicsPath](../../graphicspath)
* class [GraphicsPathIterator](../../graphicspathiterator)
* espacio de nombres [System.Drawing.Drawing2D](../../graphicspathiterator)
* asamblea [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
