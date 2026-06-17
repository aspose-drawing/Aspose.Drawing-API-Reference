---
title: LineJoin
second_title: Aspose.Drawing for Java API 참조
description: GraphicsPath 객체에 포함된 도형 서브패스에서 연속적인 선 또는 곡선 세그먼트를 연결하는 방법을 지정합니다.
type: docs
weight: 30
url: /ko/java/com.aspose.drawing.drawing2d/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineJoin extends System.Enum
```

GraphicsPath 객체에 포함된 도형(서브패스)에서 연속적인 선 또는 곡선 세그먼트를 연결하는 방법을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Miter](#Miter) | 뾰족한(각진) 조인 방식을 지정합니다. |
| [Bevel](#Bevel) | 베벨 조인 방식을 지정합니다. |
| [Round](#Round) | 원형 조인 방식을 지정합니다. |
| [MiterClipped](#MiterClipped) | 뾰족한(각진) 조인 방식을 지정합니다. |
### Miter {#Miter}
```
public static final int Miter
```


뾰족한 조인 방식을 지정합니다. 이는 마이터 길이가 마이터 제한을 초과하는지에 따라 날카로운 모서리 또는 잘린 모서리를 생성합니다.

--------------------

현재 Miter 조인은 실제로 MiterClipped처럼 동작합니다.

### Bevel {#Bevel}
```
public static final int Bevel
```


베벨 조인 방식을 지정합니다. 이는 대각선 모서리를 생성합니다.

### Round {#Round}
```
public static final int Round
```


원형 조인 방식을 지정합니다. 이는 선 사이에 부드러운 원형 호를 생성합니다.

### MiterClipped {#MiterClipped}
```
public static final int MiterClipped
```


뾰족한 조인 방식을 지정합니다. 이는 마이터 길이가 마이터 제한을 초과하는지에 따라 날카로운 모서리 또는 베벨 모서리를 생성합니다.

