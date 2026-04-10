---
title: ColorMatrixFlag
second_title: Aspose.Drawing for Java API 참조
description: 색상 및 그레이스케일 조정 설정에 의해 영향을 받는 이미지 및 색상의 유형을 지정합니다.
type: docs
weight: 15
url: /ko/java/com.aspose.drawing.imaging/colormatrixflag/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorMatrixFlag extends System.Enum
```

색상 및 그레이스케일 조정 설정에 의해 영향을 받는 이미지 및 색상의 유형을 지정합니다 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).
## 필드

| 필드 | 설명 |
| --- | --- |
| [Default](#Default) | 회색 음영을 포함한 모든 색상 값이 동일한 색상 조정 매트릭스로 조정됩니다. |
| [SkipGrays](#SkipGrays) | 모든 색상이 조정되지만 회색 음영은 조정되지 않습니다. |
| [AltGrays](#AltGrays) | 회색 음영만 조정됩니다. |
### Default {#Default}
```
public static final int Default
```


회색 음영을 포함한 모든 색상 값이 동일한 색상 조정 매트릭스로 조정됩니다.

### SkipGrays {#SkipGrays}
```
public static final int SkipGrays
```


모든 색상이 조정되지만 회색 음영은 조정되지 않습니다. 회색 음영은 빨강, 초록, 파랑 구성 요소의 값이 동일한 모든 색상입니다.

### AltGrays {#AltGrays}
```
public static final int AltGrays
```


회색 음영만 조정됩니다.

