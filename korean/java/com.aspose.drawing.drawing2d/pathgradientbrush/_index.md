---
title: PathGradientBrush
second_title: Aspose.Drawing for Java API 참조
description: 그라디언트로 객체의 내부를 채우는 객체를 캡슐화합니다.
type: docs
weight: 36
url: /ko/java/com.aspose.drawing.drawing2d/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class PathGradientBrush extends Brush
```

그라디언트로 [Brush](../../com.aspose.drawing/brush) 객체가 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체의 내부를 채우도록 캡슐화합니다. 이 클래스는 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.drawing.PointF---) | 지정된 점을 사용하여 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 클래스의 새 인스턴스를 초기화합니다. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.PointF---int-) | 지정된 점 및 랩 모드를 사용하여 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 클래스의 새 인스턴스를 초기화합니다. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.drawing.Point---) | 지정된 점을 사용하여 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 클래스의 새 인스턴스를 초기화합니다. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.Point---int-) | 지정된 점 및 랩 모드를 사용하여 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 클래스의 새 인스턴스를 초기화합니다. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-) | 지정된 경로를 사용하여 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCenterColor()](#getCenterColor--) | 경로 그라디언트 중심의 색상을 가져오거나 설정합니다. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.drawing.Color-) | 경로 그라디언트 중심의 색상을 가져오거나 설정합니다. |
| [getSurroundColors()](#getSurroundColors--) | 이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 가 채우는 경로의 점에 해당하는 색상 배열을 가져오거나 설정합니다. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.drawing.Color---) | 이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 가 채우는 경로의 점에 해당하는 색상 배열을 가져오거나 설정합니다. |
| [getCenterPoint()](#getCenterPoint--) | 경로 그라디언트의 중심점을 가져오거나 설정합니다. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.drawing.PointF-) | 경로 그라디언트의 중심점을 가져오거나 설정합니다. |
| [getRectangle()](#getRectangle--) | 이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 에 대한 경계 사각형을 가져옵니다. |
| [getBlend()](#getBlend--) | 그라디언트에 대한 사용자 정의 감쇠를 정의하는 위치와 계수를 지정하는 `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-))를 가져오거나 설정합니다. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | 그라디언트에 대한 사용자 정의 감쇠를 정의하는 위치와 계수를 지정하는 `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-))를 가져오거나 설정합니다. |
| [getInterpolationColors()](#getInterpolationColors--) | 다중 색상 선형 그라디언트를 정의하는 [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)을 가져오거나 설정합니다. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | 다중 색상 선형 그라디언트를 정의하는 [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)을 가져오거나 설정합니다. |
| [getTransform()](#getTransform--) | 이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 에 대한 로컬 기하 변환을 정의하는 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 복사본을 가져오거나 설정합니다. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | 이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 에 대한 로컬 기하 변환을 정의하는 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 복사본을 가져오거나 설정합니다. |
| [getFocusScales()](#getFocusScales--) | 그라디언트 감소에 대한 초점점을 가져오거나 설정합니다. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.drawing.PointF-) | 그라디언트 감소에 대한 초점점을 가져오거나 설정합니다. |
| [getWrapMode()](#getWrapMode--) | 이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 의 랩 모드를 나타내는 `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) 를 가져오거나 설정합니다. |
| [setWrapMode(int value)](#setWrapMode-int-) | 이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 의 랩 모드를 나타내는 `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) 를 가져오거나 설정합니다. |
| [deepClone()](#deepClone--) | 이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 의 정확한 복사본을 생성합니다. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | 경로 중심에서 시작하여 경로 경계까지 색상이 변하는 그라디언트 브러시를 생성합니다. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | 경로 중심에서 시작하여 경로 경계까지 색상이 변하는 그라디언트 브러시를 생성합니다. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | 중심 색상과 주변 색상 하나로 선형 감소하는 그라디언트를 생성합니다. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | 중심 색상과 각 주변 색상으로 선형 감소가 적용된 그라디언트를 생성합니다. |
| [resetTransform()](#resetTransform--) | `PathGradientBrush.Transform` 속성을 단위 행렬로 재설정합니다. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | 브러시의 변환 행렬에 브러시 변환 행렬에 다른 행렬을 곱한 결과를 적용하여 업데이트합니다. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | 브러시의 변환 행렬에 브러시 변환 행렬에 다른 행렬을 곱한 결과를 적용하여 업데이트합니다. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 지정된 이동을 로컬 기하 변환에 적용합니다. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 지정된 순서대로 지정된 이동을 로컬 기하 변환에 적용합니다. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 지정된 양만큼 로컬 기하 변환을 스케일링합니다. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 지정된 순서대로 지정된 양만큼 로컬 기하 변환을 스케일링합니다. |
| [rotateTransform(float angle)](#rotateTransform-float-) | 지정된 각도만큼 로컬 기하 변환을 회전시킵니다. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 지정된 순서대로 지정된 각도만큼 로컬 기하 변환을 회전시킵니다. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.drawing.PointF---}
```
public PathGradientBrush(PointF[] points)
```


지정된 점을 사용하여 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | 경로의 정점들을 구성하는 점들을 나타내는 [PointF](../../com.aspose.drawing/pointf) 구조체 배열입니다. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


지정된 점 및 랩 모드를 사용하여 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | 경로의 정점들을 구성하는 점들을 나타내는 [PointF](../../com.aspose.drawing/pointf) 구조체 배열입니다. |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-))는 이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush)로 그린 채우기가 어떻게 타일링되는지를 지정합니다. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.drawing.Point---}
```
public PathGradientBrush(Point[] points)
```


지정된 점을 사용하여 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | 경로의 정점들을 구성하는 점들을 나타내는 [Point](../../com.aspose.drawing/point) 구조체 배열입니다. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


지정된 점 및 랩 모드를 사용하여 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | 경로의 정점들을 구성하는 점들을 나타내는 [Point](../../com.aspose.drawing/point) 구조체 배열입니다. |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-))는 이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush)로 그린 채우기가 어떻게 타일링되는지를 지정합니다. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


지정된 경로를 사용하여 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush)로 채워지는 영역을 정의하는 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)입니다. |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


경로 그라디언트 중심의 색상을 가져오거나 설정합니다.

**Returns:**
[Color](../../com.aspose.drawing/color)
### setCenterColor(Color value) {#setCenterColor-com.aspose.drawing.Color-}
```
public void setCenterColor(Color value)
```


경로 그라디언트 중심의 색상을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 가 채우는 경로의 점에 해당하는 색상 배열을 가져오거나 설정합니다.

**Returns:**
com.aspose.drawing.Color[]
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.drawing.Color---}
```
public void setSurroundColors(Color[] value)
```


이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 가 채우는 경로의 점에 해당하는 색상 배열을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


경로 그라디언트의 중심점을 가져오거나 설정합니다.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.drawing.PointF-}
```
public void setCenterPoint(PointF value)
```


경로 그라디언트의 중심점을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 에 대한 경계 사각형을 가져옵니다.

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
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

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 에 대한 로컬 기하 변환을 정의하는 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 복사본을 가져오거나 설정합니다.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 에 대한 로컬 기하 변환을 정의하는 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 복사본을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


그라디언트 감소에 대한 초점점을 가져오거나 설정합니다.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setFocusScales(PointF value) {#setFocusScales-com.aspose.drawing.PointF-}
```
public void setFocusScales(PointF value)
```


그라디언트 감소에 대한 초점점을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 의 랩 모드를 나타내는 `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) 를 가져오거나 설정합니다.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 의 랩 모드를 나타내는 `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) 를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


이 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 의 정확한 복사본을 생성합니다.

**Returns:**
java.lang.Object - 이 메서드가 생성하는 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush)를 객체로 캐스팅한 것입니다.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


경로의 중심에서 경계까지 색상이 변하는 그라디언트 브러시를 생성합니다. 색상 간 전환은 종 모양 곡선을 기반으로 합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| focus | float | 0에서 1 사이의 값으로, 경로의 중심에서 경계까지의 방사선 상에서 중심 색상의 최대 강도가 위치하는 지점을 지정합니다. 값이 1(기본값)인 경우 최대 강도가 경로의 중심에 배치됩니다. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


경로의 중심에서 경계까지 색상이 변하는 그라디언트 브러시를 생성합니다. 색상 간 전환은 종 모양 곡선을 기반으로 합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| focus | float | 0에서 1 사이의 값으로, 경로의 중심에서 경계까지의 방사선 상에서 중심 색상의 최대 강도가 위치하는 지점을 지정합니다. 값이 1(기본값)인 경우 최대 강도가 경로의 중심에 배치됩니다. |
| scale | float | 0에서 1 사이의 값으로, 경계 색상과 혼합되는 중심 색상의 최대 강도를 지정합니다. 값이 1이면 중심 색상의 가능한 가장 높은 강도가 적용되며, 이는 기본값입니다. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


중심 색상과 주변 색상 하나로 선형 감소하는 그라디언트를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| focus | float | 0에서 1 사이의 값으로, 경로의 중심에서 경계까지의 방사선 상에서 중심 색상의 최대 강도가 위치하는 지점을 지정합니다. 값이 1(기본값)인 경우 최대 강도가 경로의 중심에 배치됩니다. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


중심 색상과 각 주변 색상으로 선형 감소가 적용된 그라디언트를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| focus | float | 0에서 1 사이의 값으로, 경로의 중심에서 경계까지의 방사선 상에서 중심 색상의 최대 강도가 위치하는 지점을 지정합니다. 값이 1(기본값)인 경우 최대 강도가 경로의 중심에 배치됩니다. |
| scale | float | 0에서 1 사이의 값으로, 경계 색상과 혼합되는 중심 색상의 최대 강도를 지정합니다. 값이 1이면 중심 색상의 가능한 가장 높은 강도가 적용되며, 이는 기본값입니다. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


`PathGradientBrush.Transform` 속성을 단위 행렬로 재설정합니다.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


브러시의 변환 행렬에 브러시 변환 행렬에 다른 행렬을 곱한 결과를 적용하여 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 브러시의 현재 변환 행렬에 곱해질 [Matrix](../../com.aspose.drawing.drawing2d/matrix)입니다. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


브러시의 변환 행렬에 브러시 변환 행렬에 다른 행렬을 곱한 결과를 적용하여 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 브러시의 현재 변환 행렬에 곱해질 [Matrix](../../com.aspose.drawing.drawing2d/matrix)입니다. |
| order | int | 두 행렬을 곱하는 순서를 지정하는 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)입니다. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


지정된 이동을 로컬 기하 변환에 적용합니다. 이 메서드는 변환에 이동을 앞에 삽입합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dx | float | x 방향 평행 이동 값입니다. |
| dy | float | y 방향 평행 이동 값입니다. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


지정된 순서대로 지정된 이동을 로컬 기하 변환에 적용합니다.

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
| sx | float | x축 방향의 변환 스케일 계수입니다. |
| sy | float | y축 방향의 변환 스케일 계수입니다. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


지정된 순서대로 지정된 양만큼 로컬 기하 변환을 스케일링합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sx | float | x축 방향의 변환 스케일 계수입니다. |
| sy | float | y축 방향의 변환 스케일 계수입니다. |
| order | int | 스케일링 행렬을 추가하거나 앞에 삽입할지 지정하는 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)입니다. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


지정된 양만큼 로컬 기하 변환을 회전합니다. 이 메서드는 회전 행렬을 변환 앞에 추가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도(범위)입니다. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


지정된 순서대로 지정된 각도만큼 로컬 기하 변환을 회전시킵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도(범위)입니다. |
| order | int | 회전 행렬을 추가하거나 앞에 삽입할지 지정하는 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)입니다. |

