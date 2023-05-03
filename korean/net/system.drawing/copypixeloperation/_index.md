---
title: Enum CopyPixelOperation
second_title: .NET API 참조용 Aspose.Drawing
description: System.Drawing.CopyPixelOperation 열거형. 최종 색상을 생성하기 위해 복사 픽셀 작업의 소스 색상이 대상 색상과 결합되는 방식을 결정합니다.
type: docs
weight: 120
url: /ko/net/system.drawing/copypixeloperation/
---
## CopyPixelOperation enumeration

최종 색상을 생성하기 위해 복사 픽셀 작업의 소스 색상이 대상 색상과 결합되는 방식을 결정합니다.

```csharp
public enum CopyPixelOperation
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| NoMirrorBitmap | `-2147483648` | 비트맵이 미러링되지 않았습니다. |
| Blackness | `66` | 대상 영역은 물리적 팔레트의 인덱스 0과 연결된 색상을 사용하여 채워집니다. (이 색상은 기본 물리적 팔레트의 경우 검은색입니다.) |
| NotSourceErase | `1114278` | 소스 및 대상 색상은 부울을 사용하여 결합됩니다.`또는` 연산자를 사용한 다음 결과 색상이 반전됩니다. |
| NotSourceCopy | `3342344` | 반전된 원본 영역이 대상에 복사됩니다. |
| SourceErase | `4457256` | 대상 영역의 반전된 색상은 부울을 사용하여 원본 영역의 색상과 결합됩니다.`그리고` 연산자. |
| DestinationInvert | `5570569` | 대상 영역이 반전됩니다. |
| PatInvert | `5898313` | 대상 장치 컨텍스트에서 현재 선택된 브러시의 색상은 다음과 결합됩니다. 대상의 색상은 부울을 사용합니다.`XOR` 연산자. |
| SourceInvert | `6684742` | 소스 및 대상 영역의 색상은 부울을 사용하여 결합됩니다.`XOR` 연산자. |
| SourceAnd | `8913094` | 소스 및 대상 영역의 색상은 부울을 사용하여 결합됩니다.`그리고` 연산자. |
| MergePaint | `12255782` | 반전된 소스 영역의 색상은 부울을 사용하여 대상 영역의 색상과 병합됩니다.`또는` 연산자. |
| MergeCopy | `12583114` | 소스 영역의 색상은 부울을 사용하여 대상 장치 컨텍스트의 선택된 브러시 색상과 병합됩니다.`그리고` 연산자. |
| SourceCopy | `13369376` | 원본 영역이 대상 영역에 직접 복사됩니다. |
| SourcePaint | `15597702` | 소스 및 대상 영역의 색상은 부울을 사용하여 결합됩니다.`또는` 연산자. |
| PatCopy | `15728673` | 대상 장치 컨텍스트에서 현재 선택된 브러시가 대상 비트맵에 복사됩니다. |
| PatPaint | `16452105` | 대상 장치 컨텍스트에서 현재 선택된 브러시의 색상은 부울을 사용하여 반전된 소스 영역의 colors 와 결합됩니다.`또는` 운영자. 이 작업의 결과는 부울을 사용하여 대상 영역의 색상과 결합됩니다.`또는` 연산자. |
| Whiteness | `16711778` | 물리적 팔레트의 인덱스 1과 관련된 색상을 사용하여 대상 영역을 채웁니다. (이 색상은 기본 물리적 팔레트의 경우 흰색입니다.) |
| CaptureBlt | `1073741824` | 창 위에 겹쳐진 창은 결과 이미지에 포함됩니다. 기본적으로 이미지에는 창만 포함됩니다. 이것은 일반적으로 인쇄 장치 컨텍스트에 사용할 수 없습니다. |

### 또한보십시오

* 네임스페이스 [System.Drawing](../../system.drawing/)
* 집회 [Aspose.Drawing](../../)

