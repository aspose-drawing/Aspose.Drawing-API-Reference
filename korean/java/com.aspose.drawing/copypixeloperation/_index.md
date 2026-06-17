---
title: CopyPixelOperation
second_title: Aspose.Drawing for Java API 참조
description: 복사 픽셀 작업에서 원본 색상이 대상 색상과 결합되어 최종 색상을 생성하는 방식을 결정합니다.
type: docs
weight: 18
url: /ko/java/com.aspose.drawing/copypixeloperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CopyPixelOperation extends System.Enum
```

복사 픽셀 작업에서 원본 색상이 대상 색상과 결합되어 최종 색상을 생성하는 방식을 결정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [NoMirrorBitmap](#NoMirrorBitmap) | 비트맵이 반사되지 않습니다. |
| [Blackness](#Blackness) | 대상 영역은 물리 팔레트의 인덱스 0에 연결된 색상을 사용하여 채워집니다. |
| [NotSourceErase](#NotSourceErase) | 소스와 대상 색상은 Boolean `OR` 연산자를 사용해 결합된 후, 결과 색상이 반전됩니다. |
| [NotSourceCopy](#NotSourceCopy) | 반전된 소스 영역이 대상에 복사됩니다. |
| [SourceErase](#SourceErase) | 대상 영역의 반전된 색상이 Boolean `AND` 연산자를 사용해 소스 영역의 색상과 결합됩니다. |
| [DestinationInvert](#DestinationInvert) | 대상 영역이 반전됩니다. |
| [PatInvert](#PatInvert) | 대상 디바이스 컨텍스트에서 현재 선택된 브러시의 색상이 Boolean `XOR` 연산자를 사용해 대상 색상과 결합됩니다. |
| [SourceInvert](#SourceInvert) | 소스와 대상 영역의 색상이 Boolean `XOR` 연산자를 사용해 결합됩니다. |
| [SourceAnd](#SourceAnd) | 소스와 대상 영역의 색상이 Boolean `AND` 연산자를 사용해 결합됩니다. |
| [MergePaint](#MergePaint) | 반전된 소스 영역의 색상이 Boolean `OR` 연산자를 사용해 대상 영역의 색상과 병합됩니다. |
| [MergeCopy](#MergeCopy) | 소스 영역의 색상이 Boolean `AND` 연산자를 사용해 대상 디바이스 컨텍스트의 선택된 브러시 색상과 병합됩니다. |
| [SourceCopy](#SourceCopy) | 소스 영역이 직접 대상 영역에 복사됩니다. |
| [SourcePaint](#SourcePaint) | 소스와 대상 영역의 색상이 Boolean `OR` 연산자를 사용해 결합됩니다. |
| [PatCopy](#PatCopy) | 대상 디바이스 컨텍스트에서 현재 선택된 브러시가 대상 비트맵에 복사됩니다. |
| [PatPaint](#PatPaint) | 대상 디바이스 컨텍스트에서 현재 선택된 브러시의 색상이 Boolean `OR` 연산자를 사용해 반전된 소스 영역의 색상과 결합됩니다. |
| [Whiteness](#Whiteness) | 대상 영역은 물리 팔레트의 인덱스 1에 연결된 색상을 사용해 채워집니다. |
| [CaptureBlt](#CaptureBlt) | 귀하의 창 위에 레이어된 윈도우가 결과 이미지에 포함됩니다. |
### NoMirrorBitmap {#NoMirrorBitmap}
```
public static final int NoMirrorBitmap
```


비트맵이 반사되지 않습니다.

### Blackness {#Blackness}
```
public static final int Blackness
```


대상 영역은 물리 팔레트의 인덱스 0에 연결된 색상을 사용해 채워집니다. (이 색상은 기본 물리 팔레트에서 검은색입니다.)

### NotSourceErase {#NotSourceErase}
```
public static final int NotSourceErase
```


소스와 대상 색상은 Boolean `OR` 연산자를 사용해 결합된 후, 결과 색상이 반전됩니다.

### NotSourceCopy {#NotSourceCopy}
```
public static final int NotSourceCopy
```


반전된 소스 영역이 대상에 복사됩니다.

### SourceErase {#SourceErase}
```
public static final int SourceErase
```


대상 영역의 반전된 색상이 Boolean `AND` 연산자를 사용해 소스 영역의 색상과 결합됩니다.

### DestinationInvert {#DestinationInvert}
```
public static final int DestinationInvert
```


대상 영역이 반전됩니다.

### PatInvert {#PatInvert}
```
public static final int PatInvert
```


대상 디바이스 컨텍스트에서 현재 선택된 브러시의 색상이 Boolean `XOR` 연산자를 사용해 대상 색상과 결합됩니다.

### SourceInvert {#SourceInvert}
```
public static final int SourceInvert
```


소스와 대상 영역의 색상이 Boolean `XOR` 연산자를 사용해 결합됩니다.

### SourceAnd {#SourceAnd}
```
public static final int SourceAnd
```


소스와 대상 영역의 색상이 Boolean `AND` 연산자를 사용해 결합됩니다.

### MergePaint {#MergePaint}
```
public static final int MergePaint
```


반전된 소스 영역의 색상이 Boolean `OR` 연산자를 사용해 대상 영역의 색상과 병합됩니다.

### MergeCopy {#MergeCopy}
```
public static final int MergeCopy
```


소스 영역의 색상이 Boolean `AND` 연산자를 사용해 대상 디바이스 컨텍스트의 선택된 브러시 색상과 병합됩니다.

### SourceCopy {#SourceCopy}
```
public static final int SourceCopy
```


소스 영역이 직접 대상 영역에 복사됩니다.

### SourcePaint {#SourcePaint}
```
public static final int SourcePaint
```


소스와 대상 영역의 색상이 Boolean `OR` 연산자를 사용해 결합됩니다.

### PatCopy {#PatCopy}
```
public static final int PatCopy
```


대상 디바이스 컨텍스트에서 현재 선택된 브러시가 대상 비트맵에 복사됩니다.

### PatPaint {#PatPaint}
```
public static final int PatPaint
```


대상 장치 컨텍스트에서 현재 선택된 브러시의 색상은 부울 `OR` 연산자를 사용하여 반전된 소스 영역의 색상과 결합됩니다. 이 연산의 결과는 부울 `OR` 연산자를 사용하여 대상 영역의 색상과 결합됩니다.

### Whiteness {#Whiteness}
```
public static final int Whiteness
```


대상 영역은 물리 팔레트에서 인덱스 1에 연결된 색상을 사용하여 채워집니다. (기본 물리 팔레트의 경우 이 색상은 흰색입니다.)

### CaptureBlt {#CaptureBlt}
```
public static final int CaptureBlt
```


귀하의 창 위에 레이어된 창이 결과 이미지에 포함됩니다. 기본적으로 이미지에는 귀하의 창만 포함됩니다. 일반적으로 이것은 인쇄 장치 컨텍스트에 사용할 수 없다는 점에 유의하십시오.

