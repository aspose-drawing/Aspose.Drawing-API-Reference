---
title: GraphicsPathIterator
second_title: Aspose.Drawing for .NET API Referansı
description: Bir dizindeki alt yollar boyunca yineleme yeteneği sağlar.GraphicsPath ve her alt yolda bulunan şekil türlerini test edin. Bu sınıf devralınamaz.
type: docs
weight: 270
url: /tr/net/system.drawing.drawing2d/graphicspathiterator/
---
## GraphicsPathIterator class

Bir dizindeki alt yollar boyunca yineleme yeteneği sağlar.GraphicsPath ve her alt yolda bulunan şekil türlerini test edin. Bu sınıf devralınamaz.

```csharp
public sealed class GraphicsPathIterator : IDisposable
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [GraphicsPathIterator](graphicspathiterator)(GraphicsPath) | Yeni bir örneğini başlatır[`GraphicsPathIterator`](../graphicspathiterator) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Count](../../system.drawing.drawing2d/graphicspathiterator/count) { get; } | Yoldaki noktaların sayısını alır. |
| [SubpathCount](../../system.drawing.drawing2d/graphicspathiterator/subpathcount) { get; } | Yoldaki alt yolların sayısını alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [CopyData](../../system.drawing.drawing2d/graphicspathiterator/copydata)(ref PointF[], ref byte[], int, int) | İlişkili öğenin GraphicsPath.PathPoints özelliğini ve GraphicsPath.PathTypes özelliğini arrays kopyalar.[`GraphicsPath`](../graphicspath) belirtilen iki diziye. |
| [Dispose](../../system.drawing.drawing2d/graphicspathiterator/dispose)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilişkili uygulama tanımlı görevleri gerçekleştirir. |
| [Enumerate](../../system.drawing.drawing2d/graphicspathiterator/enumerate)(ref PointF[], ref byte[]) | İlişkili öğenin GraphicsPath.PathPoints özelliğini ve GraphicsPath.PathTypes özelliğini arrays kopyalar.[`GraphicsPath`](../graphicspath) belirtilen iki diziye. |
| [HasCurve](../../system.drawing.drawing2d/graphicspathiterator/hascurve)() | Yolun bununla ilişkili olup olmadığını gösterir.[`GraphicsPathIterator`](../graphicspathiterator) bir eğri içerir. |
| [NextMarker](../../system.drawing.drawing2d/graphicspathiterator/nextmarker#nextmarker_1)(GraphicsPath) | Bu[`GraphicsPathIterator`](../graphicspathiterator) nesnenin bir[`GraphicsPath`](../graphicspath) onunla ilişkili nesne. Bu yöntem ilişkili nesneyi artırır.[`GraphicsPath`](../graphicspath) path içindeki bir sonraki işaretçiye ve geçerli işaretçi ile sonraki işaretçi (veya yolun sonu) arasındaki tüm noktaları bir saniyeye kopyalar[`GraphicsPath`](../graphicspath) nesne parametresine aktarıldı. |
| [NextMarker](../../system.drawing.drawing2d/graphicspathiterator/nextmarker#nextmarker)(out int, out int) | Artırır[`GraphicsPathIterator`](../graphicspathiterator)path içindeki bir sonraki işaretçiye geçer ve [out] parametreleri aracılığıyla başlangıç ve bitiş dizinlerini döndürür. |
| [NextPathType](../../system.drawing.drawing2d/graphicspathiterator/nextpathtype)(out byte, out int, out int) | Hepsi aynı türe sahip olan sonraki veri noktası grubunun başlangıç dizinini ve bitiş dizinini alır. |
| [NextSubpath](../../system.drawing.drawing2d/graphicspathiterator/nextsubpath#nextsubpath_1)(GraphicsPath, out bool) | Bunun ilişkili yolundan sonraki şekli (alt yol) alır[`GraphicsPathIterator`](../graphicspathiterator) . |
| [NextSubpath](../../system.drawing.drawing2d/graphicspathiterator/nextsubpath#nextsubpath)(out int, out int, out bool) | [`GraphicsPathIterator`](../graphicspathiterator) yoldaki bir sonraki alt yola. Sonraki alt yolun başlangıç dizini ve bitiş dizini [out] parametrelerinde bulunur. |
| [Rewind](../../system.drawing.drawing2d/graphicspathiterator/rewind)() | Bunu geri sarar[`GraphicsPathIterator`](../graphicspathiterator) ilişkili yolunun başına. |

### Ayrıca bakınız

* ad alanı [System.Drawing.Drawing2D](../../system.drawing.drawing2d)
* toplantı [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->