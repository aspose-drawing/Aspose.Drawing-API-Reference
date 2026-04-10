---
title: PixelFormat
second_title: Aspose.Drawing for Java API 참조
description: 이미지의 각 픽셀에 대한 색상 데이터 형식을 지정합니다.
type: docs
weight: 34
url: /ko/java/com.aspose.drawing.imaging/pixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PixelFormat extends System.Enum
```

이미지의 각 픽셀에 대한 색상 데이터 형식을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Indexed](#Indexed) | 픽셀 데이터는 색인된 색상 값을 포함하며, 이는 개별 색상 값이 아니라 시스템 색상 테이블의 색상에 대한 인덱스임을 의미합니다. |
| [Gdi](#Gdi) | 픽셀 데이터는 GDI 색상을 포함합니다. |
| [Alpha](#Alpha) | 픽셀 데이터는 사전 곱셈되지 않은 알파 값을 포함합니다. |
| [PAlpha](#PAlpha) | 픽셀 형식은 사전 곱셈된 알파 값을 포함합니다. |
| [Extended](#Extended) | 예약된 값. |
| [Canonical](#Canonical) | 픽셀당 32비트의 기본 픽셀 형식. |
| [Undefined](#Undefined) | 픽셀 형식이 정의되지 않았습니다. |
| [DontCare](#DontCare) | 픽셀 형식이 지정되지 않았습니다. |
| [Format1bppIndexed](#Format1bppIndexed) | 픽셀 형식이 픽셀당 1비트이며 인덱스 색상을 사용한다는 것을 지정합니다. |
| [Format4bppIndexed](#Format4bppIndexed) | 형식이 픽셀당 4비트이며 인덱스 색상임을 지정합니다. |
| [Format8bppIndexed](#Format8bppIndexed) | 형식이 픽셀당 8비트이며 인덱스 색상임을 지정합니다. |
| [Format16bppGrayScale](#Format16bppGrayScale) | 픽셀 형식은 픽셀당 16비트입니다. |
| [Format16bppRgb555](#Format16bppRgb555) | 형식이 픽셀당 16비트이며, 빨강, 초록, 파랑 구성 요소마다 5비트가 사용된다는 것을 지정합니다. |
| [Format16bppRgb565](#Format16bppRgb565) | 형식이 픽셀당 16비트이며, 빨강 구성 요소에 5비트, 초록 구성 요소에 6비트, 파랑 구성 요소에 5비트가 사용된다는 것을 지정합니다. |
| [Format16bppArgb1555](#Format16bppArgb1555) | 픽셀 형식은 픽셀당 16비트입니다. |
| [Format24bppRgb](#Format24bppRgb) | 포맷이 픽셀당 24비트임을 지정합니다; 빨강, 초록, 파랑 구성 요소마다 8비트가 사용됩니다. |
| [Format32bppRgb](#Format32bppRgb) | 포맷이 픽셀당 32비트임을 지정합니다; 빨강, 초록, 파랑 구성 요소마다 8비트가 사용됩니다. |
| [Format32bppArgb](#Format32bppArgb) | 포맷이 픽셀당 32비트임을 지정합니다; 알파, 빨강, 초록, 파랑 구성 요소마다 8비트가 사용됩니다. |
| [Format32bppPArgb](#Format32bppPArgb) | 포맷이 픽셀당 32비트임을 지정합니다; 알파, 빨강, 초록, 파랑 구성 요소마다 8비트가 사용됩니다. |
| [Format48bppRgb](#Format48bppRgb) | 포맷이 픽셀당 48비트임을 지정합니다; 빨강, 초록, 파랑 구성 요소마다 16비트가 사용됩니다. |
| [Format64bppArgb](#Format64bppArgb) | 포맷이 픽셀당 64비트임을 지정합니다; 알파, 빨강, 초록, 파랑 구성 요소마다 16비트가 사용됩니다. |
| [Format64bppPArgb](#Format64bppPArgb) | 포맷이 픽셀당 64비트임을 지정합니다; 알파, 빨강, 초록, 파랑 구성 요소마다 16비트가 사용됩니다. |
| [Max](#Max) | 이 열거형의 최대값입니다. |
### Indexed {#Indexed}
```
public static final int Indexed
```


픽셀 데이터는 색인된 색상 값을 포함하며, 이는 개별 색상 값이 아니라 시스템 색상 테이블의 색상에 대한 인덱스임을 의미합니다.

### Gdi {#Gdi}
```
public static final int Gdi
```


픽셀 데이터는 GDI 색상을 포함합니다.

### Alpha {#Alpha}
```
public static final int Alpha
```


픽셀 데이터는 사전 곱셈되지 않은 알파 값을 포함합니다.

### PAlpha {#PAlpha}
```
public static final int PAlpha
```


픽셀 형식은 사전 곱셈된 알파 값을 포함합니다.

### Extended {#Extended}
```
public static final int Extended
```


예약된 값.

### Canonical {#Canonical}
```
public static final int Canonical
```


기본 픽셀 포맷은 픽셀당 32비트입니다. 이 포맷은 24비트 색 깊이와 8비트 알파 채널을 지정합니다.

### Undefined {#Undefined}
```
public static final int Undefined
```


픽셀 형식이 정의되지 않았습니다.

### DontCare {#DontCare}
```
public static final int DontCare
```


픽셀 형식이 지정되지 않았습니다.

### Format1bppIndexed {#Format1bppIndexed}
```
public static final int Format1bppIndexed
```


픽셀 포맷이 픽셀당 1비트이며 인덱스 색상을 사용함을 지정합니다. 따라서 색상표에는 두 가지 색상이 포함됩니다.

### Format4bppIndexed {#Format4bppIndexed}
```
public static final int Format4bppIndexed
```


형식이 픽셀당 4비트이며 인덱스 색상임을 지정합니다.

### Format8bppIndexed {#Format8bppIndexed}
```
public static final int Format8bppIndexed
```


포맷이 픽셀당 8비트이며 인덱스 방식임을 지정합니다. 따라서 색상표에는 256가지 색상이 포함됩니다.

### Format16bppGrayScale {#Format16bppGrayScale}
```
public static final int Format16bppGrayScale
```


픽셀 포맷은 픽셀당 16비트입니다. 색상 정보는 65,536가지 회색 음영을 지정합니다.

### Format16bppRgb555 {#Format16bppRgb555}
```
public static final int Format16bppRgb555
```


포맷이 픽셀당 16비트이며, 빨강, 초록, 파랑 구성 요소마다 5비트가 사용됩니다. 남은 1비트는 사용되지 않습니다.

### Format16bppRgb565 {#Format16bppRgb565}
```
public static final int Format16bppRgb565
```


형식이 픽셀당 16비트이며, 빨강 구성 요소에 5비트, 초록 구성 요소에 6비트, 파랑 구성 요소에 5비트가 사용된다는 것을 지정합니다.

### Format16bppArgb1555 {#Format16bppArgb1555}
```
public static final int Format16bppArgb1555
```


픽셀 포맷은 픽셀당 16비트입니다. 색상 정보는 32,768가지 색상 음영을 지정하며, 그 중 빨강 5비트, 초록 5비트, 파랑 5비트, 알파 1비트로 구성됩니다.

### Format24bppRgb {#Format24bppRgb}
```
public static final int Format24bppRgb
```


포맷이 픽셀당 24비트임을 지정합니다; 빨강, 초록, 파랑 구성 요소마다 8비트가 사용됩니다.

### Format32bppRgb {#Format32bppRgb}
```
public static final int Format32bppRgb
```


포맷이 픽셀당 32비트이며, 빨강, 초록, 파랑 구성 요소마다 8비트가 사용됩니다. 남은 8비트는 사용되지 않습니다.

### Format32bppArgb {#Format32bppArgb}
```
public static final int Format32bppArgb
```


포맷이 픽셀당 32비트임을 지정합니다; 알파, 빨강, 초록, 파랑 구성 요소마다 8비트가 사용됩니다.

### Format32bppPArgb {#Format32bppPArgb}
```
public static final int Format32bppPArgb
```


포맷이 픽셀당 32비트이며, 알파, 빨강, 초록, 파랑 구성 요소마다 8비트가 사용됩니다. 빨강, 초록, 파랑 구성 요소는 알파 구성 요소에 따라 사전 곱셈됩니다.

### Format48bppRgb {#Format48bppRgb}
```
public static final int Format48bppRgb
```


포맷이 픽셀당 48비트임을 지정합니다; 빨강, 초록, 파랑 구성 요소마다 16비트가 사용됩니다.

### Format64bppArgb {#Format64bppArgb}
```
public static final int Format64bppArgb
```


포맷이 픽셀당 64비트임을 지정합니다; 알파, 빨강, 초록, 파랑 구성 요소마다 16비트가 사용됩니다.

### Format64bppPArgb {#Format64bppPArgb}
```
public static final int Format64bppPArgb
```


포맷이 픽셀당 64비트이며, 알파, 빨강, 초록, 파랑 구성 요소마다 16비트가 사용됩니다. 빨강, 초록, 파랑 구성 요소는 알파 구성 요소에 따라 사전 곱셈됩니다.

### Max {#Max}
```
public static final int Max
```


이 열거형의 최대값입니다.

