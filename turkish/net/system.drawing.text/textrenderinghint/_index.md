---
title: TextRenderingHint
second_title: Aspose.Drawing for .NET API Referansı
description: Metin oluşturma kalitesini belirtir.
type: docs
weight: 1250
url: /tr/net/system.drawing.text/textrenderinghint/
---
## TextRenderingHint enumeration

Metin oluşturma kalitesini belirtir.

```csharp
public enum TextRenderingHint
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| SystemDefault | `0` | Her karakter, sistem varsayılan oluşturma ipucu ile kendi glif bit eşlemi kullanılarak çizilir. Metin, kullanıcının sistem için seçtiği yazı tipi yumuşatma ayarları kullanılarak çizilecektir. |
| SingleBitPerPixelGridFit | `1` | Her karakter kendi glif bitmap'i kullanılarak çizilir. İpuçları, karakterin gövde ve eğrilik üzerindeki görünümünü iyileştirmek için kullanılır. |
| SingleBitPerPixel | `2` | Her karakter, kendi glif bit eşlemi kullanılarak çizilir. İpucu kullanılmaz. |
| AntiAliasGridFit | `3` | Her karakter, kendi kenar yumuşatılmış glif bit eşlemi kullanılarak ipucu ile çizilir. Kenar yumuşatma nedeniyle çok daha iyi kalite, ancak daha yüksek performans maliyetiyle. |
| AntiAlias | `4` | Her karakter, kendi kenar yumuşatılmış glif bit eşlemi kullanılarak ipucu verilmeden çizilir. Kenar yumuşatma nedeniyle daha iyi kalite. İpucu kapatıldığından gövde genişliği farklılıkları fark edilebilir. |
| ClearTypeGridFit | `5` | Her karakter, ipucu içeren ClearType bit eşlemi kullanılarak çizilir. En yüksek kalite ayarı. ClearType yazı tipi özelliklerinden yararlanmak için kullanılır. |

### Ayrıca bakınız

* ad alanı [System.Drawing.Text](../../system.drawing.text)
* toplantı [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->