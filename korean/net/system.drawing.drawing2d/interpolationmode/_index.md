---
title: Enum InterpolationMode
second_title: .NET API 참조용 Aspose.Drawing
description: System.Drawing.Drawing2D.InterpolationMode 열거형. InterpolationMode 열거형은 이미지 크기를 조정하거나 회전할 때 사용되는 알고리즘을 지정합니다.
type: docs
weight: 310
url: /ko/net/system.drawing.drawing2d/interpolationmode/
---
## InterpolationMode enumeration

InterpolationMode 열거형은 이미지 크기를 조정하거나 회전할 때 사용되는 알고리즘을 지정합니다.

```csharp
public enum InterpolationMode
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Invalid | `-1` | QualityMode 열거형의 잘못된 요소에 해당합니다. |
| Default | `0` | 기본 모드를 지정합니다. |
| Low | `1` | 낮은 품질의 보간을 지정합니다. |
| High | `2` | 고품질 보간을 지정합니다. |
| Bilinear | `3` | 쌍선형 보간을 지정합니다. 사전 필터링이 수행되지 않습니다. 이 모드는 이미지를 원래 크기의 50% 미만으로 축소하는 데 적합하지 않습니다. |
| Bicubic | `4` | 쌍입방 보간을 지정합니다. 사전 필터링이 수행되지 않습니다. 이 모드는 이미지를 원래 크기의 25% 미만으로 축소하는 데 적합하지 않습니다. |
| NearestNeighbor | `5` | 가장 가까운 이웃 보간법을 지정합니다. |
| HighQualityBilinear | `6` | 고품질의 쌍선형 보간법을 지정합니다. 고품질 수축을 보장하기 위해 사전 필터링이 수행됩니다. |
| HighQualityBicubic | `7` | 고품질 쌍입방 보간법을 지정합니다. 고품질 수축을 보장하기 위해 사전 필터링이 수행됩니다. 이 모드는 최고 품질의 변환된 이미지를 생성합니다. |

### 또한보십시오

* 네임스페이스 [System.Drawing.Drawing2D](../../system.drawing.drawing2d/)
* 집회 [Aspose.Drawing](../../)


