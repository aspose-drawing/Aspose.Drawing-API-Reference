---
title: Clone
second_title: Aspose.Drawing for .NET API Referansı
description: Bunun bölümünün bir kopyasını oluştururBitmap tarafından tanımlananRectangle Structure ve belirtilen birPixelFormat numaralandırma.
type: docs
weight: 100
url: /tr/net/system.drawing/bitmap/clone/
---
## Clone(Rectangle, PixelFormat) {#clone}

Bunun bölümünün bir kopyasını oluştururBitmap tarafından tanımlananRectangle Structure ve belirtilen birPixelFormat numaralandırma.

```csharp
public Bitmap Clone(Rectangle rect, PixelFormat format)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rect | Rectangle | Bu kısmı tanımlarBitmap kopyalamak için. Koordinatlar buna göredirBitmap. |
| format | PixelFormat | belirtirPixelFormat the hedefi için numaralandırmaBitmap. |

### Geri dönüş değeri

YeniBitmap bu yöntemin oluşturduğunu.

### Ayrıca bakınız

* struct [Rectangle](../../rectangle)
* enum [PixelFormat](../../../system.drawing.imaging/pixelformat)
* class [Bitmap](../../bitmap)
* ad alanı [System.Drawing](../../bitmap)
* toplantı [Aspose.Drawing](../../../)

---

## Clone(RectangleF, PixelFormat) {#clone_1}

Bunun bölümünün bir kopyasını oluştururBitmap belirli bir tanımlaPixelFormat numaralandırma.

```csharp
public Bitmap Clone(RectangleF rect, PixelFormat format)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rect | RectangleF | Bu kısmı tanımlarBitmap kopyalamak. |
| format | PixelFormat | belirtirPixelFormat hedef için numaralandırmaBitmap. |

### Geri dönüş değeri

buBitmap bu yöntemin oluşturduğunu.

### istisnalar

| istisna | şart |
| --- | --- |
| OutOfMemoryException | *rect* kaynak bitmap sınırlarının dışında. |
| ArgumentException | yüksekliği veya genişliği*rect* 0. |

### Ayrıca bakınız

* struct [RectangleF](../../rectanglef)
* enum [PixelFormat](../../../system.drawing.imaging/pixelformat)
* class [Bitmap](../../bitmap)
* ad alanı [System.Drawing](../../bitmap)
* toplantı [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->