---
title: GraphicsPath.Warp
second_title: Aspose.Drawing untuk Referensi .NET API
description: GraphicsPath metode. Menerapkan transformasi warp ditentukan oleh persegi panjang dan jajaran genjang untuk iniGraphicsPath .
type: docs
weight: 350
url: /id/net/system.drawing.drawing2d/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

Menerapkan transformasi warp, ditentukan oleh persegi panjang dan jajaran genjang, untuk ini[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| destPoints | PointF[] | Array dariPointF struktur yang mendefinisikan jajaran genjang yang didefinisikan oleh persegi panjang*srcRect* diubah. Array dapat berisi tiga atau empat elemen. Jika larik berisi tiga elemen, sudut kanan bawah jajaran genjang tersirat oleh tiga titik pertama. |
| srcRect | RectangleF | ARectangleF yang mewakili persegi panjang yang diubah menjadi jajaran genjang yang ditentukan oleh*destPoints* . |

### Lihat juga

* struct [PointF](../../../system.drawing/pointf/)
* struct [RectangleF](../../../system.drawing/rectanglef/)
* class [GraphicsPath](../)
* ruang nama [System.Drawing.Drawing2D](../../graphicspath/)
* perakitan [Aspose.Drawing](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Menerapkan transformasi warp, ditentukan oleh persegi panjang dan jajaran genjang, untuk ini[`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| destPoints | PointF[] | Array dariPointF struktur yang mendefinisikan jajaran genjang yang didefinisikan oleh persegi panjang*srcRect* diubah. Array dapat berisi tiga atau empat elemen. Jika larik berisi tiga elemen, sudut kanan bawah jajaran genjang tersirat oleh tiga titik pertama. |
| srcRect | RectangleF | ARectangleF yang mewakili persegi panjang yang diubah menjadi jajaran genjang yang ditentukan oleh*destPoints* . |
| matrix | Matrix | A[`Matrix`](../../matrix/) yang menentukan transformasi geometris untuk diterapkan ke jalur. |

### Lihat juga

* struct [PointF](../../../system.drawing/pointf/)
* struct [RectangleF](../../../system.drawing/rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* ruang nama [System.Drawing.Drawing2D](../../graphicspath/)
* perakitan [Aspose.Drawing](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Menerapkan transformasi warp, ditentukan oleh persegi panjang dan jajaran genjang, untuk ini[`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| destPoints | PointF[] | Array dariPointF struktur yang mendefinisikan jajaran genjang yang didefinisikan oleh persegi panjang*srcRect* diubah. Larik dapat berisi tiga atau empat elemen. Jika larik berisi tiga elemen, sudut kanan bawah jajaran genjang ditunjukkan oleh tiga titik pertama. |
| srcRect | RectangleF | ARectangleF yang mewakili persegi panjang yang diubah menjadi jajaran genjang yang ditentukan oleh*destPoints* . |
| matrix | Matrix | A[`Matrix`](../../matrix/) yang menentukan transformasi geometris untuk diterapkan ke jalur. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode/) pencacahan yang menentukan apakah operasi warp ini menggunakan mode perspektif atau bilinear. |

### Lihat juga

* struct [PointF](../../../system.drawing/pointf/)
* struct [RectangleF](../../../system.drawing/rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* ruang nama [System.Drawing.Drawing2D](../../graphicspath/)
* perakitan [Aspose.Drawing](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Menerapkan transformasi warp, ditentukan oleh persegi panjang dan jajaran genjang, untuk ini[`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| destPoints | PointF[] | Array dariPointF struktur yang mendefinisikan jajaran genjang yang didefinisikan oleh persegi panjang*srcRect* diubah. Larik dapat berisi tiga atau empat elemen. Jika larik berisi tiga elemen, sudut kanan bawah jajaran genjang ditunjukkan oleh tiga titik pertama. |
| srcRect | RectangleF | ARectangleF yang mewakili persegi panjang yang diubah menjadi jajaran genjang yang ditentukan oleh*destPoints* . |
| matrix | Matrix | A[`Matrix`](../../matrix/) yang menentukan transformasi geometris untuk diterapkan ke jalur. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode/) pencacahan yang menentukan apakah operasi warp ini menggunakan mode perspektif atau bilinear. |
| flatness | Single | Nilai dari 0 hingga 1 yang menentukan seberapa datar jalur yang dihasilkan. Untuk informasi lebih lanjut, lihat[`Flatten`](../flatten/) metode. |

### Lihat juga

* struct [PointF](../../../system.drawing/pointf/)
* struct [RectangleF](../../../system.drawing/rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* ruang nama [System.Drawing.Drawing2D](../../graphicspath/)
* perakitan [Aspose.Drawing](../../../)


