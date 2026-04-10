---
title: PixelFormat
second_title: Aspose.Drawing for Java API 参考
description: 指定图像中每个像素的颜色数据格式。
type: docs
weight: 34
url: /zh/java/com.aspose.drawing.imaging/pixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PixelFormat extends System.Enum
```

指定图像中每个像素的颜色数据格式。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Indexed](#Indexed) | 像素数据包含颜色索引值，这意味着这些值是系统颜色表中颜色的索引，而不是单独的颜色值。 |
| [Gdi](#Gdi) | 像素数据包含 GDI 颜色。 |
| [Alpha](#Alpha) | 像素数据包含未预乘的 alpha 值。 |
| [PAlpha](#PAlpha) | 像素格式包含预乘的 alpha 值。 |
| [Extended](#Extended) | 保留值。 |
| [Canonical](#Canonical) | 默认的每像素 32 位像素格式。 |
| [Undefined](#Undefined) | 像素格式未定义。 |
| [DontCare](#DontCare) | 未指定像素格式。 |
| [Format1bppIndexed](#Format1bppIndexed) | 指定像素格式为每像素 1 位，并使用索引颜色。 |
| [Format4bppIndexed](#Format4bppIndexed) | 指定格式为每像素 4 位，使用索引颜色。 |
| [Format8bppIndexed](#Format8bppIndexed) | 指定格式为每像素 8 位，使用索引颜色。 |
| [Format16bppGrayScale](#Format16bppGrayScale) | 像素格式为每像素 16 位。 |
| [Format16bppRgb555](#Format16bppRgb555) | 指定格式为每像素 16 位；红、绿、蓝分量各使用 5 位。 |
| [Format16bppRgb565](#Format16bppRgb565) | 指定格式为每像素 16 位；红色分量使用 5 位，绿色分量使用 6 位，蓝色分量使用 5 位。 |
| [Format16bppArgb1555](#Format16bppArgb1555) | 像素格式为每像素 16 位。 |
| [Format24bppRgb](#Format24bppRgb) | 指定该格式为每像素 24 位；每个红色、绿色和蓝色分量各使用 8 位。 |
| [Format32bppRgb](#Format32bppRgb) | 指定该格式为每像素 32 位；每个红色、绿色和蓝色分量各使用 8 位。 |
| [Format32bppArgb](#Format32bppArgb) | 指定该格式为每像素 32 位；每个 alpha、红色、绿色和蓝色分量各使用 8 位。 |
| [Format32bppPArgb](#Format32bppPArgb) | 指定该格式为每像素 32 位；每个 alpha、红色、绿色和蓝色分量各使用 8 位。 |
| [Format48bppRgb](#Format48bppRgb) | 指定该格式为每像素 48 位；每个红色、绿色和蓝色分量各使用 16 位。 |
| [Format64bppArgb](#Format64bppArgb) | 指定该格式为每像素 64 位；每个 alpha、红色、绿色和蓝色分量各使用 16 位。 |
| [Format64bppPArgb](#Format64bppPArgb) | 指定该格式为每像素 64 位；每个 alpha、红色、绿色和蓝色分量各使用 16 位。 |
| [Max](#Max) | 此枚举的最大值。 |
### Indexed {#Indexed}
```
public static final int Indexed
```


像素数据包含颜色索引值，这意味着这些值是系统颜色表中颜色的索引，而不是单独的颜色值。

### Gdi {#Gdi}
```
public static final int Gdi
```


像素数据包含 GDI 颜色。

### Alpha {#Alpha}
```
public static final int Alpha
```


像素数据包含未预乘的 alpha 值。

### PAlpha {#PAlpha}
```
public static final int PAlpha
```


像素格式包含预乘的 alpha 值。

### Extended {#Extended}
```
public static final int Extended
```


保留值。

### Canonical {#Canonical}
```
public static final int Canonical
```


默认的每像素 32 位像素格式。该格式指定 24 位颜色深度和 8 位 alpha 通道。

### Undefined {#Undefined}
```
public static final int Undefined
```


像素格式未定义。

### DontCare {#DontCare}
```
public static final int DontCare
```


未指定像素格式。

### Format1bppIndexed {#Format1bppIndexed}
```
public static final int Format1bppIndexed
```


指定像素格式为每像素 1 位，并使用索引颜色。因此颜色表包含两种颜色。

### Format4bppIndexed {#Format4bppIndexed}
```
public static final int Format4bppIndexed
```


指定格式为每像素 4 位，使用索引颜色。

### Format8bppIndexed {#Format8bppIndexed}
```
public static final int Format8bppIndexed
```


指定该格式为每像素 8 位，使用索引颜色。因此颜色表包含 256 种颜色。

### Format16bppGrayScale {#Format16bppGrayScale}
```
public static final int Format16bppGrayScale
```


像素格式为每像素 16 位。颜色信息指定 65536 种灰度。

### Format16bppRgb555 {#Format16bppRgb555}
```
public static final int Format16bppRgb555
```


指定该格式为每像素 16 位；每个红色、绿色和蓝色分量各使用 5 位。剩余的 1 位未使用。

### Format16bppRgb565 {#Format16bppRgb565}
```
public static final int Format16bppRgb565
```


指定格式为每像素 16 位；红色分量使用 5 位，绿色分量使用 6 位，蓝色分量使用 5 位。

### Format16bppArgb1555 {#Format16bppArgb1555}
```
public static final int Format16bppArgb1555
```


像素格式为每像素 16 位。颜色信息指定 32,768 种颜色，其中红色 5 位，绿色 5 位，蓝色 5 位，alpha 为 1 位。

### Format24bppRgb {#Format24bppRgb}
```
public static final int Format24bppRgb
```


指定该格式为每像素 24 位；每个红色、绿色和蓝色分量各使用 8 位。

### Format32bppRgb {#Format32bppRgb}
```
public static final int Format32bppRgb
```


指定该格式为每像素 32 位；每个红色、绿色和蓝色分量各使用 8 位。剩余的 8 位未使用。

### Format32bppArgb {#Format32bppArgb}
```
public static final int Format32bppArgb
```


指定该格式为每像素 32 位；每个 alpha、红色、绿色和蓝色分量各使用 8 位。

### Format32bppPArgb {#Format32bppPArgb}
```
public static final int Format32bppPArgb
```


指定该格式为每像素 32 位；每个 alpha、红色、绿色和蓝色分量各使用 8 位。红色、绿色和蓝色分量根据 alpha 分量进行预乘。

### Format48bppRgb {#Format48bppRgb}
```
public static final int Format48bppRgb
```


指定该格式为每像素 48 位；每个红色、绿色和蓝色分量各使用 16 位。

### Format64bppArgb {#Format64bppArgb}
```
public static final int Format64bppArgb
```


指定该格式为每像素 64 位；每个 alpha、红色、绿色和蓝色分量各使用 16 位。

### Format64bppPArgb {#Format64bppPArgb}
```
public static final int Format64bppPArgb
```


指定该格式为每像素 64 位；每个 alpha、红色、绿色和蓝色分量各使用 16 位。红色、绿色和蓝色分量根据 alpha 分量进行预乘。

### Max {#Max}
```
public static final int Max
```


此枚举的最大值。

