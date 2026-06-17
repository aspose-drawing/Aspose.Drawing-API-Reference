---
title: InterpolationMode
second_title: Aspose.Drawing for Java API 참조
description: InterpolationMode 열거형은 이미지가 확대 또는 회전될 때 사용되는 알고리즘을 지정합니다.
type: docs
weight: 28
url: /ko/java/com.aspose.drawing.drawing2d/interpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class InterpolationMode extends System.Enum
```

InterpolationMode 열거형은 이미지가 확대 또는 회전될 때 사용되는 알고리즘을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Invalid](#Invalid) | QualityMode 열거형의 Invalid 요소와 동일합니다. |
| [Default](#Default) | 기본 모드를 지정합니다. |
| [Low](#Low) | 낮은 품질 보간을 지정합니다. |
| [High](#High) | 높은 품질 보간을 지정합니다. |
| [Bilinear](#Bilinear) | 양선형 보간을 지정합니다. |
| [Bicubic](#Bicubic) | 삼차 보간을 지정합니다. |
| [NearestNeighbor](#NearestNeighbor) | 최근접 이웃 보간을 지정합니다. |
| [HighQualityBilinear](#HighQualityBilinear) | 고품질 양선형 보간을 지정합니다. |
| [HighQualityBicubic](#HighQualityBicubic) | 고품질 삼차 보간을 지정합니다. |
### Invalid {#Invalid}
```
public static final int Invalid
```


QualityMode 열거형의 Invalid 요소와 동일합니다.

### Default {#Default}
```
public static final int Default
```


기본 모드를 지정합니다.

### Low {#Low}
```
public static final int Low
```


낮은 품질 보간을 지정합니다.

### High {#High}
```
public static final int High
```


높은 품질 보간을 지정합니다.

### Bilinear {#Bilinear}
```
public static final int Bilinear
```


양선형 보간을 지정합니다. 사전 필터링이 수행되지 않습니다. 이 모드는 이미지 크기를 원본 크기의 50% 이하로 축소하는 경우에 적합하지 않습니다.

### Bicubic {#Bicubic}
```
public static final int Bicubic
```


삼차 보간을 지정합니다. 사전 필터링이 수행되지 않습니다. 이 모드는 이미지 크기를 원본 크기의 25% 이하로 축소하는 경우에 적합하지 않습니다.

### NearestNeighbor {#NearestNeighbor}
```
public static final int NearestNeighbor
```


최근접 이웃 보간을 지정합니다.

### HighQualityBilinear {#HighQualityBilinear}
```
public static final int HighQualityBilinear
```


고품질 양선형 보간을 지정합니다. 고품질 축소를 보장하기 위해 사전 필터링이 수행됩니다.

### HighQualityBicubic {#HighQualityBicubic}
```
public static final int HighQualityBicubic
```


고품질 삼차 보간을 지정합니다. 고품질 축소를 보장하기 위해 사전 필터링이 수행됩니다. 이 모드는 가장 높은 품질의 변환된 이미지를 생성합니다.

