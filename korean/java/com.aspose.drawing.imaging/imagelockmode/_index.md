---
title: ImageLockMode
second_title: Aspose.Drawing for Java API 참조
description: 플래그 매개변수에 전달되는 플래그를 지정합니다.
type: docs
weight: 28
url: /ko/java/com.aspose.drawing.imaging/imagelockmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageLockMode extends System.Enum
```

플래그 매개변수에 전달되는 플래그를 지정합니다. [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) 메서드는 이미지의 일부를 잠궈 픽셀 데이터를 읽거나 쓸 수 있도록 합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [ReadOnly](#ReadOnly) | 이미지의 일부가 읽기 전용으로 잠겼다는 것을 지정합니다. |
| [WriteOnly](#WriteOnly) | 이미지의 일부가 쓰기 전용으로 잠겼다는 것을 지정합니다. |
| [ReadWrite](#ReadWrite) | 이미지의 일부가 읽기 또는 쓰기용으로 잠겼다는 것을 지정합니다. |
| [UserInputBuffer](#UserInputBuffer) | 픽셀 데이터를 읽거나 쓰는 데 사용되는 버퍼가 사용자가 할당한다는 것을 지정합니다. |
### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


이미지의 일부가 읽기 전용으로 잠겼다는 것을 지정합니다.

### WriteOnly {#WriteOnly}
```
public static final int WriteOnly
```


이미지의 일부가 쓰기 전용으로 잠겼다는 것을 지정합니다.

### ReadWrite {#ReadWrite}
```
public static final int ReadWrite
```


이미지의 일부가 읽기 또는 쓰기용으로 잠겼다는 것을 지정합니다.

### UserInputBuffer {#UserInputBuffer}
```
public static final int UserInputBuffer
```


픽셀 데이터를 읽거나 쓰는 데 사용되는 버퍼가 사용자가 할당한다는 것을 지정합니다. 이 플래그가 설정된 경우, [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) 메서드의 `flags` 매개변수는 입력 매개변수(그리고 경우에 따라 출력 매개변수)로 사용됩니다. 이 플래그가 해제된 경우, `flags` 매개변수는 출력 매개변수로만 사용됩니다.

