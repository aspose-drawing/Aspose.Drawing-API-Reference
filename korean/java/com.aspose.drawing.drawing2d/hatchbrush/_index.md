---
title: HatchBrush
second_title: Aspose.Drawing for Java API 참조
description: 사각형 브러시를 해치 스타일, 전경 색 및 배경 색으로 정의합니다.
type: docs
weight: 26
url: /ko/java/com.aspose.drawing.drawing2d/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class HatchBrush extends Brush
```

해치 스타일, 전경 색 및 배경 색을 가진 사각형 브러시를 정의합니다. 이 클래스는 상속될 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [HatchBrush(int hatchstyle, Color foreColor)](#HatchBrush-int-com.aspose.drawing.Color-) | 지정된 `HatchStyle`([.getHatchStyle](../../null/\\#getHatchStyle)) 열거형과 전경 색을 사용하여 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 클래스의 새 인스턴스를 초기화합니다. |
| [HatchBrush(int hatchstyle, Color foreColor, Color backColor)](#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-) | 지정된 `HatchStyle`([.getHatchStyle](../../null/\\#getHatchStyle)) 열거형, 전경 색 및 배경 색을 사용하여 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHatchStyle()](#getHatchStyle--) | 이 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 객체의 해치 스타일을 가져옵니다. |
| [getForegroundColor()](#getForegroundColor--) | 이 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 객체가 그린 해치 선의 색을 가져옵니다. |
| [getBackgroundColor()](#getBackgroundColor--) | 이 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 객체가 그린 해치 선 사이의 공간 색을 가져옵니다. |
| [deepClone()](#deepClone--) | 이 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 객체의 정확한 복사본을 생성합니다. |
### HatchBrush(int hatchstyle, Color foreColor) {#HatchBrush-int-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor)
```


지정된 `HatchStyle`([.getHatchStyle](../../null/\\#getHatchStyle)) 열거형과 전경 색을 사용하여 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| hatchstyle | int | 이 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 객체가 그린 패턴을 나타내는 `HatchStyle`([.getHatchStyle](../../null/\\#getHatchStyle)) 값 중 하나입니다. |
| foreColor | [Color](../../com.aspose.drawing/color) | 이 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 객체가 그린 선의 색을 나타내는 [Color](../../com.aspose.drawing/color) 구조체입니다. |

### HatchBrush(int hatchstyle, Color foreColor, Color backColor) {#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor, Color backColor)
```


지정된 `HatchStyle`([.getHatchStyle](../../null/\\#getHatchStyle)) 열거형, 전경 색 및 배경 색을 사용하여 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| hatchstyle | int | 이 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 객체가 그린 패턴을 나타내는 `HatchStyle`([.getHatchStyle](../../null/\\#getHatchStyle)) 값 중 하나입니다. |
| foreColor | [Color](../../com.aspose.drawing/color) | 이 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 객체가 그린 선의 색을 나타내는 [Color](../../com.aspose.drawing/color) 구조체입니다. |
| backColor | [Color](../../com.aspose.drawing/color) | 이 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 객체가 그린 선 사이의 공간 색을 나타내는 [Color](../../com.aspose.drawing/color) 구조체입니다. |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


이 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 객체의 해치 스타일을 가져옵니다.

**Returns:**
int - 이 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 객체의 해치 스타일.
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


이 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 객체가 그린 해치 선의 색을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


이 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 객체가 그린 해치 선 사이의 공간 색을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of spaces between the hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


이 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 객체의 정확한 복사본을 생성합니다.

**Returns:**
java.lang.Object - 이 메서드가 생성하고 객체로 캐스팅한 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)입니다.
