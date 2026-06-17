---
title: 좌표공간
second_title: Aspose.Drawing for Java API 참조
description: 좌표를 평가할 때 사용할 시스템을 지정합니다.
type: docs
weight: 16
url: /ko/java/com.aspose.drawing.drawing2d/coordinatespace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CoordinateSpace extends System.Enum
```

좌표를 평가할 때 사용할 시스템을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [World](#World) | 좌표가 월드 좌표 컨텍스트에 있음을 지정합니다. |
| [Page](#Page) | 좌표가 페이지 좌표 컨텍스트에 있음을 지정합니다. |
| [Device](#Device) | 좌표가 디바이스 좌표 컨텍스트에 있음을 지정합니다. |
### World {#World}
```
public static final int World
```


좌표가 월드 좌표 컨텍스트에 있음을 지정합니다. 월드 좌표는 모델링 환경과 같은 비물리적 환경에서 사용됩니다.

### Page {#Page}
```
public static final int Page
```


좌표가 페이지 좌표 컨텍스트에 있음을 지정합니다. 해당 단위는 Graphics.PageUnit 속성에 의해 정의되며, GraphicsUnit 열거형의 요소 중 하나여야 합니다.

### Device {#Device}
```
public static final int Device
```


좌표가 디바이스 좌표 컨텍스트에 있음을 지정합니다. 컴퓨터 화면에서는 디바이스 좌표가 일반적으로 픽셀 단위로 측정됩니다.

