---
title: ColorMap
second_title: Aspose.Drawing for Java API 참조
description: 색상을 변환하기 위한 매핑을 정의합니다.
type: docs
weight: 13
url: /ko/java/com.aspose.drawing.imaging/colormap/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMap
```

색상을 변환하기 위한 매핑을 정의합니다. [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 클래스의 여러 메서드는 색상 재매핑 테이블(즉, [ColorMap](../../com.aspose.drawing.imaging/colormap) 구조체 배열)을 사용하여 이미지 색상을 조정합니다. 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ColorMap()](#ColorMap--) | [ColorMap](../../com.aspose.drawing.imaging/colormap) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getOldColor()](#getOldColor--) | 변환될 기존 [Color](../../com.aspose.drawing/color) 구조체를 가져옵니다. |
| [setOldColor(Color value)](#setOldColor-com.aspose.drawing.Color-) | 변환될 기존 [Color](../../com.aspose.drawing/color) 구조체를 설정합니다. |
| [getNewColor()](#getNewColor--) | 변환 대상이 되는 새 [Color](../../com.aspose.drawing/color) 구조체를 가져옵니다. |
| [setNewColor(Color value)](#setNewColor-com.aspose.drawing.Color-) | 변환 대상이 되는 새 [Color](../../com.aspose.drawing/color) 구조체를 설정합니다. |
### ColorMap() {#ColorMap--}
```
public ColorMap()
```


[ColorMap](../../com.aspose.drawing.imaging/colormap) 클래스의 새 인스턴스를 초기화합니다.

### getOldColor() {#getOldColor--}
```
public Color getOldColor()
```


변환될 기존 [Color](../../com.aspose.drawing/color) 구조체를 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - The existing [Color](../../com.aspose.drawing/color) structure to be converted.
### setOldColor(Color value) {#setOldColor-com.aspose.drawing.Color-}
```
public void setOldColor(Color value)
```


변환될 기존 [Color](../../com.aspose.drawing/color) 구조체를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) | 변환될 기존 [Color](../../com.aspose.drawing/color) 구조체 |

### getNewColor() {#getNewColor--}
```
public Color getNewColor()
```


변환 대상이 되는 새 [Color](../../com.aspose.drawing/color) 구조체를 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - The new [Color](../../com.aspose.drawing/color) structure to which to convert.
### setNewColor(Color value) {#setNewColor-com.aspose.drawing.Color-}
```
public void setNewColor(Color value)
```


변환 대상이 되는 새 [Color](../../com.aspose.drawing/color) 구조체를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) | 변환 대상이 되는 새 [Color](../../com.aspose.drawing/color) 구조체 |

