---
title: LinearGradientBrush
second_title: Aspose.Drawing for Java API 참조
description: 선형 그라디언트를 사용하여 를 캡슐화합니다.
type: docs
weight: 31
url: /ko/java/com.aspose.drawing.drawing2d/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class LinearGradientBrush extends Brush
```

[Brush](../../com.aspose.drawing/brush)를 선형 그라디언트와 함께 캡슐화합니다. 이 클래스는 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-) | 지정된 점과 색상을 사용하여 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-) | 지정된 점과 색상을 사용하여 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | 사각형, 시작 및 끝 색상, 그리고 방향 모드를 기반으로 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | 사각형, 시작 및 끝 색상, 그리고 방향을 기반으로 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | 사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | 사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | 사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | 사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLinearColors()](#getLinearColors--) | 그라디언트의 시작 색상과 끝 색상을 가져오거나 설정합니다. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.drawing.Color---) | 그라디언트의 시작 색상과 끝 색상을 가져오거나 설정합니다. |
| [getRectangle()](#getRectangle--) | 그라디언트의 시작점과 끝점을 정의하는 사각형 영역을 가져옵니다. |
| [getGammaCorrection()](#getGammaCorrection--) | 이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)에 대해 감마 보정이 활성화되어 있는지를 나타내는 값을 가져오거나 설정합니다. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | 이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)에 대해 감마 보정이 활성화되어 있는지를 나타내는 값을 가져오거나 설정합니다. |
| [getBlend()](#getBlend--) | 그라디언트에 대한 사용자 정의 감쇠를 정의하는 위치와 계수를 지정하는 `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-))를 가져오거나 설정합니다. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | 그라디언트에 대한 사용자 정의 감쇠를 정의하는 위치와 계수를 지정하는 `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-))를 가져오거나 설정합니다. |
| [getInterpolationColors()](#getInterpolationColors--) | 다중 색상 선형 그라디언트를 정의하는 [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)을 가져오거나 설정합니다. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | 다중 색상 선형 그라디언트를 정의하는 [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)을 가져오거나 설정합니다. |
| [getWrapMode()](#getWrapMode--) | 이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)의 랩 모드를 나타내는 `WrapMode` 열거형을 가져오거나 설정합니다. |
| [setWrapMode(int value)](#setWrapMode-int-) | 이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)의 랩 모드를 나타내는 `WrapMode` 열거형을 가져오거나 설정합니다. |
| [getTransform()](#getTransform--) | 이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)에 대한 로컬 기하 변환을 정의하는 복사본 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 가져오거나 설정합니다. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | 이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)에 대한 로컬 기하 변환을 정의하는 복사본 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 가져오거나 설정합니다. |
| [deepClone()](#deepClone--) | 이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)의 정확한 복사본을 생성합니다. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | 종 모양 곡선을 기반으로 하는 그라디언트 감쇠를 생성합니다. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | 종 모양 곡선을 기반으로 하는 그라디언트 감쇠를 생성합니다. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | 중심 색상과 양쪽 끝으로 단일 색상으로 선형 감쇠되는 선형 그라디언트를 생성합니다. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | 중심 색상과 양쪽 끝으로 단일 색상으로 선형 감쇠되는 선형 그라디언트를 생성합니다. |
| [resetTransform()](#resetTransform--) | `LinearGradientBrush.Transform` 속성을 단위 행렬로 재설정합니다. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | 이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)의 로컬 기하 변환을 나타내는 [Matrix](../../com.aspose.drawing.drawing2d/matrix)에 지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix)을 앞에 추가하여 곱합니다. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | 이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)의 로컬 기하 변환을 나타내는 [Matrix](../../com.aspose.drawing.drawing2d/matrix)에 지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 지정된 순서대로 곱합니다. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 지정된 치수만큼 로컬 기하 변환을 평행 이동합니다. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 지정된 순서대로 지정된 치수만큼 로컬 기하 변환을 평행 이동합니다. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 지정된 양만큼 로컬 기하 변환을 스케일링합니다. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 지정된 순서대로 지정된 양만큼 로컬 기하 변환을 스케일링합니다. |
| [rotateTransform(float angle)](#rotateTransform-float-) | 지정된 각도만큼 로컬 기하 변환을 회전시킵니다. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 지정된 순서대로 지정된 각도만큼 로컬 기하 변환을 회전시킵니다. |
### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


지정된 점과 색상을 사용하여 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | 선형 그라디언트의 시작점을 나타내는 [PointF](../../com.aspose.drawing/pointf) 구조체입니다. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | 선형 그라디언트의 끝점을 나타내는 [PointF](../../com.aspose.drawing/pointf) 구조체입니다. |
| color1 | [Color](../../com.aspose.drawing/color) | 선형 그라디언트의 시작 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체입니다. |
| color2 | [Color](../../com.aspose.drawing/color) | 선형 그라디언트의 끝 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체입니다. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


지정된 점과 색상을 사용하여 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | 선형 그라디언트의 시작점을 나타내는 [Point](../../com.aspose.drawing/point) 구조체입니다. |
| point2 | [Point](../../com.aspose.drawing/point) | 선형 그라디언트의 끝점을 나타내는 [Point](../../com.aspose.drawing/point) 구조체입니다. |
| color1 | [Color](../../com.aspose.drawing/color) | 선형 그라디언트의 시작 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체입니다. |
| color2 | [Color](../../com.aspose.drawing/color) | 선형 그라디언트의 끝 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체입니다. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)
```


사각형, 시작 및 끝 색상, 그리고 방향 모드를 기반으로 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 선형 그라디언트의 경계를 지정하는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체입니다. |
| color1 | [Color](../../com.aspose.drawing/color) | 그라디언트의 시작 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체입니다. |
| color2 | [Color](../../com.aspose.drawing/color) | 그라디언트의 종료 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체. |
| linearGradientMode | int | [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) 열거형 요소로, 그라디언트의 방향을 지정합니다. 방향은 그라디언트의 시작점과 종료점을 결정합니다. 예를 들어, LinearGradientMode.ForwardDiagonal는 시작점이 사각형의 왼쪽 위 모서리이고 종료점이 사각형의 오른쪽 아래 모서리임을 지정합니다. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)
```


사각형, 시작 및 끝 색상, 그리고 방향을 기반으로 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | `Rectangle`([.getRectangle](../../null/\#getRectangle)) 구조체로, 선형 그라디언트의 경계를 지정합니다. |
| color1 | [Color](../../com.aspose.drawing/color) | 그라디언트의 시작 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체입니다. |
| color2 | [Color](../../com.aspose.drawing/color) | 그라디언트의 종료 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체. |
| linearGradientMode | int | [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) 열거형 요소로, 그라디언트의 방향을 지정합니다. 방향은 그라디언트의 시작점과 종료점을 결정합니다. 예를 들어, LinearGradientMode.ForwardDiagonal는 시작점이 사각형의 왼쪽 위 모서리이고 종료점이 사각형의 오른쪽 아래 모서리임을 지정합니다. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 선형 그라디언트의 경계를 지정하는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체입니다. |
| color1 | [Color](../../com.aspose.drawing/color) | 그라디언트의 시작 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체입니다. |
| color2 | [Color](../../com.aspose.drawing/color) | 그라디언트의 종료 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체. |
| 각도 | float | 그라디언트 방향선의 각도이며, x축을 기준으로 시계 방향으로 측정한 도(degree) 단위입니다. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 선형 그라디언트의 경계를 지정하는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체입니다. |
| color1 | [Color](../../com.aspose.drawing/color) | 그라디언트의 시작 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체입니다. |
| color2 | [Color](../../com.aspose.drawing/color) | 그라디언트의 종료 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체. |
| 각도 | float | 그라디언트 방향선의 각도이며, x축을 기준으로 시계 방향으로 측정한 도(degree) 단위입니다. |
| isAngleScaleable | boolean | true로 설정하면 이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)와 연결된 변환에 의해 각도가 영향을 받도록 지정합니다; 그렇지 않으면 false입니다. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | `Rectangle`([.getRectangle](../../null/\#getRectangle)) 구조체로, 선형 그라디언트의 경계를 지정합니다. |
| color1 | [Color](../../com.aspose.drawing/color) | 그라디언트의 시작 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체입니다. |
| color2 | [Color](../../com.aspose.drawing/color) | 그라디언트의 종료 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체. |
| 각도 | float | 그라디언트 방향선의 각도이며, x축을 기준으로 시계 방향으로 측정한 도(degree) 단위입니다. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | `Rectangle`([.getRectangle](../../null/\#getRectangle)) 구조체로, 선형 그라디언트의 경계를 지정합니다. |
| color1 | [Color](../../com.aspose.drawing/color) | 그라디언트의 시작 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체입니다. |
| color2 | [Color](../../com.aspose.drawing/color) | 그라디언트의 종료 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체. |
| 각도 | float | 그라디언트 방향선의 각도이며, x축을 기준으로 시계 방향으로 측정한 도(degree) 단위입니다. |
| isAngleScaleable | boolean | true로 설정하면 이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)와 연결된 변환에 의해 각도가 영향을 받도록 지정합니다; 그렇지 않으면 false입니다. |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


그라디언트의 시작 색상과 끝 색상을 가져오거나 설정합니다.

**Returns:**
com.aspose.drawing.Color[]
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.drawing.Color---}
```
public void setLinearColors(Color[] value)
```


그라디언트의 시작 색상과 끝 색상을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


그라디언트의 시작점과 끝점을 정의하는 사각형 영역을 가져옵니다.

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)에 대해 감마 보정이 활성화되어 있는지를 나타내는 값을 가져오거나 설정합니다.

**Returns:**
boolean
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)에 대해 감마 보정이 활성화되어 있는지를 나타내는 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


그라디언트에 대한 사용자 정의 감쇠를 정의하는 위치와 계수를 지정하는 `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-))를 가져오거나 설정합니다.

**Returns:**
[Blend](../../com.aspose.drawing.drawing2d/blend)
### setBlend(Blend value) {#setBlend-com.aspose.drawing.drawing2d.Blend-}
```
public void setBlend(Blend value)
```


그라디언트에 대한 사용자 정의 감쇠를 정의하는 위치와 계수를 지정하는 `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-))를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Blend](../../com.aspose.drawing.drawing2d/blend) |  |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


다중 색상 선형 그라디언트를 정의하는 [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)을 가져오거나 설정합니다.

**Returns:**
[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


다중 색상 선형 그라디언트를 정의하는 [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)의 랩 모드를 나타내는 `WrapMode` 열거형을 가져오거나 설정합니다.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)의 랩 모드를 나타내는 `WrapMode` 열거형을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)에 대한 로컬 기하 변환을 정의하는 복사본 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 가져오거나 설정합니다.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)에 대한 로컬 기하 변환을 정의하는 복사본 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)의 정확한 복사본을 생성합니다.

**Returns:**
java.lang.Object - 이 메서드가 생성하는 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)를 객체로 캐스팅한 것입니다.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


종 모양 곡선을 기반으로 하는 그라디언트 감쇠를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| focus | float | 0부터 1까지의 값으로, 그라디언트의 중심을 지정합니다(시작 색과 종료 색이 동일하게 혼합되는 지점). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


종 모양 곡선을 기반으로 하는 그라디언트 감쇠를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| focus | float | 0부터 1까지의 값으로, 그라디언트의 중심을 지정합니다(그라디언트가 오직 종료 색으로만 구성되는 지점). |
| scale | float | 0부터 1까지의 값으로, 색상이 `focus`에서 얼마나 빠르게 감소하는지를 지정합니다. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


중심 색상과 양쪽 끝으로 단일 색상으로 선형 감쇠되는 선형 그라디언트를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| focus | float | 0부터 1까지의 값으로, 그라디언트의 중심을 지정합니다(그라디언트가 오직 종료 색으로만 구성되는 지점). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


중심 색상과 양쪽 끝으로 단일 색상으로 선형 감쇠되는 선형 그라디언트를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| focus | float | 0부터 1까지의 값으로, 그라디언트의 중심을 지정합니다(그라디언트가 오직 종료 색으로만 구성되는 지점). |
| scale | float | 0부터 1까지의 값으로, 시작 색에서 `focus`(종료 색)까지 색상이 얼마나 빠르게 감소하는지를 지정합니다. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


`LinearGradientBrush.Transform` 속성을 단위 행렬로 재설정합니다.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)의 로컬 기하 변환을 나타내는 [Matrix](../../com.aspose.drawing.drawing2d/matrix)에 지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix)을 앞에 추가하여 곱합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 기하학적 변환에 곱할 [Matrix](../../com.aspose.drawing.drawing2d/matrix)입니다. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


이 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)의 로컬 기하 변환을 나타내는 [Matrix](../../com.aspose.drawing.drawing2d/matrix)에 지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 지정된 순서대로 곱합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 기하학적 변환에 곱할 [Matrix](../../com.aspose.drawing.drawing2d/matrix)입니다. |
| order | int | 두 행렬을 곱하는 순서를 지정하는 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)입니다. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


지정된 치수만큼 로컬 기하학적 변환을 평행 이동합니다. 이 메서드는 변환 앞에 평행 이동을 추가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dx | float | x 방향 평행 이동 값입니다. |
| dy | float | y 방향 평행 이동 값입니다. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


지정된 순서대로 지정된 치수만큼 로컬 기하 변환을 평행 이동합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dx | float | x 방향 평행 이동 값입니다. |
| dy | float | y 방향 평행 이동 값입니다. |
| order | int | 평행 이동을 적용할 순서(앞에 추가 또는 뒤에 추가)입니다. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


지정된 양만큼 로컬 기하 변환을 스케일합니다. 이 메서드는 스케일링 행렬을 변환 앞에 추가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sx | float | x축 방향으로 변환을 스케일링할 양. |
| sy | float | y축 방향으로 변환을 스케일링할 양. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


지정된 순서대로 지정된 양만큼 로컬 기하 변환을 스케일링합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sx | float | x축 방향으로 변환을 스케일링할 양. |
| sy | float | y축 방향으로 변환을 스케일링할 양. |
| order | int | 스케일링 행렬을 추가하거나 앞에 삽입할지 지정하는 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)입니다. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


지정된 양만큼 로컬 기하 변환을 회전합니다. 이 메서드는 회전 행렬을 변환 앞에 추가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


지정된 순서대로 지정된 각도만큼 로컬 기하 변환을 회전시킵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도. |
| order | int | 회전 행렬을 추가하거나 앞에 삽입할지 지정하는 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)입니다. |

