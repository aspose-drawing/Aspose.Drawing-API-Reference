---
title: AddCurve
second_title: Aspose.Drawing per .NET API Reference
description: Aggiunge una curva spline alla figura corrente. Viene utilizzata una curva spline cardinale perché la curva viaggia attraverso ciascuno dei punti nellarray.
type: docs
weight: 110
url: /it/net/system.drawing.drawing2d/graphicspath/addcurve/
---
## AddCurve(Point[]) {#addcurve_3}

Aggiunge una curva spline alla figura corrente. Viene utilizzata una curva spline cardinale perché la curva viaggia attraverso ciascuno dei punti nell'array.

```csharp
public void AddCurve(Point[] points)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | Point[] | Una matrice diPoint strutture che rappresentano i punti che definiscono la curva. |

### Guarda anche

* struct [Point](../../../system.drawing/point)
* class [GraphicsPath](../../graphicspath)
* spazio dei nomi [System.Drawing.Drawing2D](../../graphicspath)
* assemblea [Aspose.Drawing](../../../)

---

## AddCurve(PointF[]) {#addcurve}

Aggiunge una curva spline alla figura corrente. Viene utilizzata una curva spline cardinale perché la curva viaggia attraverso ciascuno dei punti nell'array.

```csharp
public void AddCurve(PointF[] points)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | PointF[] | Una matrice diPointF strutture che rappresentano i punti che definiscono la curva. |

### Guarda anche

* struct [PointF](../../../system.drawing/pointf)
* class [GraphicsPath](../../graphicspath)
* spazio dei nomi [System.Drawing.Drawing2D](../../graphicspath)
* assemblea [Aspose.Drawing](../../../)

---

## AddCurve(PointF[], float) {#addcurve_2}

Aggiunge una curva spline alla figura corrente.

```csharp
public void AddCurve(PointF[] points, float tension)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | PointF[] | Una matrice di strutture PointF che rappresenta i punti che definiscono la curva. |
| tension | Single | Un valore che specifica la quantità di piegatura della curva tra i punti di controllo. Valori maggiori di 1 producono risultati imprevedibili. |

### Guarda anche

* struct [PointF](../../../system.drawing/pointf)
* class [GraphicsPath](../../graphicspath)
* spazio dei nomi [System.Drawing.Drawing2D](../../graphicspath)
* assemblea [Aspose.Drawing](../../../)

---

## AddCurve(PointF[], int, int, float) {#addcurve_1}

Aggiunge una curva spline alla figura corrente.

```csharp
public void AddCurve(PointF[] points, int offset, int numberOfSegments, float tension)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | PointF[] | Una matrice diPointF strutture che rappresentano i punti che definiscono la curva. |
| offset | Int32 | L'indice dell'elemento in*points* array utilizzato come primo punto della curva. |
| numberOfSegments | Int32 | Il numero di segmenti utilizzati per disegnare la curva. Un segmento può essere pensato come una linea che collega due punti. |
| tension | Single | Un valore che specifica la quantità di piegatura della curva tra i punti di controllo. Valori maggiori di 1 producono risultati imprevedibili. |

### Guarda anche

* struct [PointF](../../../system.drawing/pointf)
* class [GraphicsPath](../../graphicspath)
* spazio dei nomi [System.Drawing.Drawing2D](../../graphicspath)
* assemblea [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->