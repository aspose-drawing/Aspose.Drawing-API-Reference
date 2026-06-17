---
title: StringFormatFlags
second_title: Aspose.Drawing for Java API 참조
description: 텍스트 문자열에 대한 표시 및 레이아웃 정보를 지정합니다.
type: docs
weight: 48
url: /ko/java/com.aspose.drawing/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

텍스트 문자열에 대한 표시 및 레이아웃 정보를 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | 텍스트가 오른쪽에서 왼쪽으로 표시됩니다. |
| [DirectionVertical](#DirectionVertical) | 텍스트가 수직으로 정렬됩니다. |
| [FitBlackBox](#FitBlackBox) | 문자 일부가 문자열 레이아웃 사각형을 넘어서도록 허용됩니다. |
| [DisplayFormatControl](#DisplayFormatControl) | 왼쪽에서 오른쪽으로 표시하는 마크와 같은 제어 문자는 출력에 대표 글리프로 표시됩니다. |
| [NoFontFallback](#NoFontFallback) | 요청된 글꼴에서 지원되지 않는 문자를 위한 대체 글꼴 사용이 비활성화됩니다. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | 각 행 끝의 뒤쪽 공백을 포함합니다. |
| [NoWrap](#NoWrap) | 사각형 내에서 서식 지정 시 행 사이의 텍스트 줄바꿈이 비활성화됩니다. |
| [LineLimit](#LineLimit) | 전체 행만 서식 사각형에 배치됩니다. |
| [NoClip](#NoClip) | 글리프의 넘치는 부분과 서식 사각형 밖으로 나가는 줄바꿈되지 않은 텍스트가 표시되도록 허용됩니다. |
| [ExactAlignment](#ExactAlignment) | 정확한 정렬, 올바른 패딩 GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


텍스트가 오른쪽에서 왼쪽으로 표시됩니다.

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


텍스트가 수직으로 정렬됩니다.

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


문자 일부가 문자열 레이아웃 사각형을 넘어서도록 허용됩니다. 기본적으로 문자는 넘침을 방지하도록 재배치됩니다.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


왼쪽에서 오른쪽으로 표시하는 마크와 같은 제어 문자는 출력에 대표 글리프로 표시됩니다.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


요청된 글꼴에서 지원되지 않는 문자를 위한 대체 글꼴 사용이 비활성화됩니다. 누락된 문자는 일반적으로 빈 사각형인 글꼴의 누락된 글리프로 표시됩니다.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


각 행 끝의 뒤쪽 공백을 포함합니다. 기본적으로 MeasureString 메서드가 반환하는 경계 사각형은 각 행 끝의 공백을 제외합니다. 이 플래그를 설정하면 측정에 해당 공백을 포함합니다.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


사각형 내에서 서식 지정 시 행 사이의 텍스트 줄바꿈이 비활성화됩니다. 이 플래그는 사각형 대신 점이 전달되거나 지정된 사각형의 행 길이가 0인 경우 암시됩니다.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


전체 행만이 서식 사각형에 배치됩니다. 기본적으로 레이아웃은 텍스트 끝까지 또는 클리핑으로 인해 더 이상 보이는 행이 없을 때까지, 둘 중 먼저 발생하는 시점까지 계속됩니다. 기본 설정은 행 높이의 정수 배가 아닌 서식 사각형에 의해 마지막 행이 부분적으로 가려질 수 있음을 참고하십시오. 전체 행만 보이도록 하려면 이 값을 지정하고, 최소한 한 행 높이만큼 높은 서식 사각형을 제공하도록 주의하십시오.

### NoClip {#NoClip}
```
public static final int NoClip
```


글리프의 돌출 부분과 서식 사각형 밖으로 넘어가는 래핑되지 않은 텍스트는 표시될 수 있습니다. 기본적으로 서식 사각형 밖으로 넘어가는 모든 텍스트와 글리프 부분은 클리핑됩니다.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


정확한 정렬, 올바른 패딩 GDI+

