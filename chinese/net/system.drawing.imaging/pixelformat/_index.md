---
title: PixelFormat
second_title: Aspose.Drawing for .NET API 参考
description: 指定图像中每个像素的颜色数据格式
type: docs
weight: 850
url: /zh/net/system.drawing.imaging/pixelformat/
---
## PixelFormat enumeration

指定图像中每个像素的颜色数据格式。

```csharp
public enum PixelFormat
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Indexed | `65536` | 像素数据包含颜色索引值，这意味着这些值是 系统颜色表中颜色的索引，而不是单个颜色值。 |
| Gdi | `131072` | 像素数据包含 GDI 颜色。 |
| Alpha | `262144` | 像素数据包含未预乘的 alpha 值。 |
| PAlpha | `524288` | 像素格式包含预乘的 alpha 值。 |
| Extended | `1048576` | 保留值。 |
| Canonical | `2097152` | 每个像素 32 位的默认像素格式。 格式指定 24 位颜色深度和 8 位 alpha 通道。 |
| Undefined | `0` | 像素格式未定义。 |
| DontCare | `0` | 未指定像素格式。 |
| Format1bppIndexed | `196865` | 指定像素格式为每像素 1 位，并使用索引颜色。 因此颜色表中有两种颜色。 |
| Format4bppIndexed | `197634` | 指定格式为每像素 4 位，索引。 |
| Format8bppIndexed | `198659` | 指定格式为每像素 8 位，索引。 因此颜色表中有 256 种颜色。 |
| Format16bppGrayScale | `1052676` | 像素格式为每像素 16 位。 颜色信息指定 65536 种灰度。 |
| Format16bppRgb555 | `135173` | 指定格式为每像素 16 位； 各 5 位用于红色、绿色和蓝色分量。 剩余位不使用。 |
| Format16bppRgb565 | `135174` | 指定格式为每像素 16 位； 5 位用于红色分量， 6 位用于绿色分量，5 位用于蓝色分量。 |
| Format16bppArgb1555 | `397319` | 像素格式为每像素 16 位。颜色信息指定了 32,768 种颜色， 其中 5 位是红色，5 位是绿色，5 位是蓝色，1 位是 alpha。 |
| Format24bppRgb | `137224` | 指定格式为每像素 24 位；每个 8 位用于红色、 绿色和蓝色分量。 |
| Format32bppRgb | `139273` | 指定格式为每像素 32 位；红色、绿色和蓝色分量各使用 8 位。 其余 8 位不使用。 |
| Format32bppArgb | `2498570` | 指定格式为每像素 32 位；每个 8 位用于 alpha、 红色、绿色和蓝色分量。 |
| Format32bppPArgb | `925707` | 指定格式为每像素 32 位；每个 8 位用于 alpha、 红色、绿色和蓝色分量。红绿蓝分量预乘， 根据alpha分量 |
| Format48bppRgb | `1060876` | 指定格式为每像素 48 位；每个 16 位用于红色、 绿色和蓝色分量。 |
| Format64bppArgb | `3424269` | 指定格式为每像素 64 位；每个 16 位用于 alpha、 红色、绿色和蓝色分量。 |
| Format64bppPArgb | `1851406` | 指定格式为每像素 64 位；每个 16 位用于 alpha、 红色、绿色和蓝色分量。红绿蓝分量根据alpha分量预乘 。 |
| Max | `15` | 此枚举的最大值。 |

### 也可以看看

* 命名空间 [System.Drawing.Imaging](../../system.drawing.imaging)
* 部件 [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->