---
title: Pen
second_title: Aspose.Drawing for Java API 참조
description: 선과 곡선을 그리는 데 사용되는 객체를 정의합니다.
type: docs
weight: 34
url: /ko/java/com.aspose.drawing/pen/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class Pen implements System.IDisposable
```

선과 곡선을 그리는 데 사용되는 객체를 정의합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.drawing.Color-) | 지정된 `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-))를 사용하여 [Pen](../../com.aspose.drawing/pen) 클래스의 새 인스턴스를 초기화합니다. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.drawing.Brush-float-) | 지정된 Brush와 Width를 사용하여 Pen 클래스의 새 인스턴스를 초기화합니다. |
| [Pen(Brush brush)](#Pen-com.aspose.drawing.Brush-) | 지정된 `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-))를 사용하여 [Pen](../../com.aspose.drawing/pen) 클래스의 새 인스턴스를 초기화합니다. |
| [Pen(Color color, float width)](#Pen-com.aspose.drawing.Color-float-) | 지정된 Color 및 Width 속성을 사용하여 Pen 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getColor()](#getColor--) | 이 [Pen](../../com.aspose.drawing/pen)의 색상을 가져오거나 설정합니다. |
| [setColor(Color value)](#setColor-com.aspose.drawing.Color-) | 이 [Pen](../../com.aspose.drawing/pen)의 색상을 가져오거나 설정합니다. |
| [getBrush()](#getBrush--) | 이 [Pen](../../com.aspose.drawing/pen)의 속성을 결정하는 Brush를 가져오거나 설정합니다. |
| [setBrush(Brush value)](#setBrush-com.aspose.drawing.Brush-) | 이 [Pen](../../com.aspose.drawing/pen)의 속성을 결정하는 Brush를 가져오거나 설정합니다. |
| [getCompoundArray()](#getCompoundArray--) | 복합 펜을 지정하는 값 배열을 가져오거나 설정합니다. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | 복합 펜을 지정하는 값 배열을 가져오거나 설정합니다. |
| [getWidth()](#getWidth--) | 그리기에 사용되는 Graphics 객체의 단위로 이 Pen의 너비를 가져오거나 설정합니다. |
| [setWidth(float value)](#setWidth-float-) | 그리기에 사용되는 Graphics 객체의 단위로 이 Pen의 너비를 가져오거나 설정합니다. |
| [getStartCap()](#getStartCap--) | 이 Pen으로 그린 선의 시작 부분에 사용되는 캡 스타일을 가져오거나 설정합니다. |
| [setStartCap(int value)](#setStartCap-int-) | 이 Pen으로 그린 선의 시작 부분에 사용되는 캡 스타일을 가져오거나 설정합니다. |
| [getEndCap()](#getEndCap--) | 이 Pen으로 그린 선의 끝 부분에 사용되는 캡 스타일을 가져오거나 설정합니다. |
| [setEndCap(int value)](#setEndCap-int-) | 이 Pen으로 그린 선의 끝 부분에 사용되는 캡 스타일을 가져오거나 설정합니다. |
| [getLineJoin()](#getLineJoin--) | 이 Pen으로 그린 두 연속 선의 끝에 대한 조인 스타일을 가져오거나 설정합니다. |
| [setLineJoin(int value)](#setLineJoin-int-) | 이 Pen으로 그린 두 연속 선의 끝에 대한 조인 스타일을 가져오거나 설정합니다. |
| [getMiterLimit()](#getMiterLimit--) | 마이터 코너에서 조인의 두께 제한을 가져오거나 설정합니다. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | 마이터 코너에서 조인의 두께 제한을 가져오거나 설정합니다. |
| [getAlignment()](#getAlignment--) | 이 [Pen](../../com.aspose.drawing/pen)의 정렬을 가져오거나 설정합니다. |
| [setAlignment(int value)](#setAlignment-int-) | 이 [Pen](../../com.aspose.drawing/pen)의 정렬을 가져오거나 설정합니다. |
| [getTransform()](#getTransform--) | 이 [Pen](../../com.aspose.drawing/pen)의 기하학적 변환 복사본을 가져오거나 설정합니다. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | 이 [Pen](../../com.aspose.drawing/pen)의 기하학적 변환 복사본을 가져오거나 설정합니다. |
| [getCustomStartCap()](#getCustomStartCap--) | 이 [Pen](../../com.aspose.drawing/pen)으로 그린 선의 시작 부분에 사용할 사용자 정의 캡을 가져오거나 설정합니다. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-) | 이 [Pen](../../com.aspose.drawing/pen)으로 그린 선의 시작 부분에 사용할 사용자 정의 캡을 가져오거나 설정합니다. |
| [getCustomEndCap()](#getCustomEndCap--) | 이 [Pen](../../com.aspose.drawing/pen)으로 그린 선의 끝 부분에 사용할 사용자 정의 캡을 가져오거나 설정합니다. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-) | 이 [Pen](../../com.aspose.drawing/pen)으로 그린 선의 끝 부분에 사용할 사용자 정의 캡을 가져오거나 설정합니다. |
| [getDashCap()](#getDashCap--) | 이 [Pen](../../com.aspose.drawing/pen)으로 그린 점선의 대시 끝에 사용되는 캡 스타일을 가져오거나 설정합니다. |
| [setDashCap(int value)](#setDashCap-int-) | 이 [Pen](../../com.aspose.drawing/pen)으로 그린 점선의 대시 끝에 사용되는 캡 스타일을 가져오거나 설정합니다. |
| [getDashOffset()](#getDashOffset--) | 선의 시작부터 대시 패턴 시작까지의 거리를 가져오거나 설정합니다. |
| [setDashOffset(float value)](#setDashOffset-float-) | 선의 시작부터 대시 패턴 시작까지의 거리를 가져오거나 설정합니다. |
| [getDashPattern()](#getDashPattern--) | 사용자 정의 대시와 공백 배열을 가져오거나 설정합니다. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | 사용자 정의 대시와 공백 배열을 가져오거나 설정합니다. |
| [getDashStyle()](#getDashStyle--) | 이 [Pen](../../com.aspose.drawing/pen)으로 그린 점선에 사용되는 스타일을 가져오거나 설정합니다. |
| [setDashStyle(int value)](#setDashStyle-int-) | 이 [Pen](../../com.aspose.drawing/pen)으로 그린 점선에 사용되는 스타일을 가져오거나 설정합니다. |
| [getPenType()](#getPenType--) | 이 Pen으로 그린 선의 스타일을 가져옵니다. |
| [dispose()](#dispose--) | 이 Pen이 사용한 모든 리소스를 해제합니다. |
| [deepClone()](#deepClone--) | 이 [Pen](../../com.aspose.drawing/pen)의 정확한 복사본을 생성합니다. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | 이 [Pen](../../com.aspose.drawing/pen)으로 그린 선을 끝낼 때 사용되는 캡 스타일을 결정하는 값을 설정합니다. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 지정된 계수로 로컬 기하 변환을 스케일링합니다. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 지정된 순서대로 지정된 계수로 로컬 기하 변환을 스케일링합니다. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 지정된 순서대로 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. |
| [rotateTransform(float angle)](#rotateTransform-float-) | 지정된 각도로 로컬 기하 변환을 회전시킵니다. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 지정된 순서대로 지정된 각도로 로컬 기하 변환을 회전시킵니다. |
| [resetTransform()](#resetTransform--) | 이 [Pen](../../com.aspose.drawing/pen)의 기하 변환 행렬을 단위 행렬로 재설정합니다. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | 이 [Pen](../../com.aspose.drawing/pen)의 변환 행렬에 지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 곱합니다. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | 이 [Pen](../../com.aspose.drawing/pen)의 변환 행렬에 지정된 순서대로 지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 곱합니다. |
### Pen(Color color) {#Pen-com.aspose.drawing.Color-}
```
public Pen(Color color)
```


지정된 `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-))를 사용하여 [Pen](../../com.aspose.drawing/pen) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | 이 [Pen](../../com.aspose.drawing/pen)의 채우기 속성을 결정하는 `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-))입니다. |

### Pen(Brush brush, float width) {#Pen-com.aspose.drawing.Brush-float-}
```
public Pen(Brush brush, float width)
```


지정된 Brush와 Width를 사용하여 Pen 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | 이 Pen의 특성을 결정하는 Brush입니다. |
| 너비 | float | 새 Pen의 너비입니다. |

### Pen(Brush brush) {#Pen-com.aspose.drawing.Brush-}
```
public Pen(Brush brush)
```


지정된 `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-))를 사용하여 [Pen](../../com.aspose.drawing/pen) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | 이 [Pen](../../com.aspose.drawing/pen)의 채우기 속성을 결정하는 `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-))입니다. |

### Pen(Color color, float width) {#Pen-com.aspose.drawing.Color-float-}
```
public Pen(Color color, float width)
```


지정된 Color 및 Width 속성을 사용하여 Pen 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | 이 Pen의 색을 나타내는 Color 구조체입니다. |
| 너비 | float | 이 Pen의 너비를 나타내는 값입니다. |

### getColor() {#getColor--}
```
public final Color getColor()
```


이 [Pen](../../com.aspose.drawing/pen)의 색상을 가져오거나 설정합니다.

값: 이 [Pen](../../com.aspose.drawing/pen)의 색을 나타내는 `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) 구조체입니다.

**Returns:**
[Color](../../com.aspose.drawing/color)
### setColor(Color value) {#setColor-com.aspose.drawing.Color-}
```
public final void setColor(Color value)
```


이 [Pen](../../com.aspose.drawing/pen)의 색상을 가져오거나 설정합니다.

값: 이 [Pen](../../com.aspose.drawing/pen)의 색을 나타내는 `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) 구조체입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


이 [Pen](../../com.aspose.drawing/pen)의 속성을 결정하는 Brush를 가져오거나 설정합니다.

**Returns:**
[Brush](../../com.aspose.drawing/brush)
### setBrush(Brush value) {#setBrush-com.aspose.drawing.Brush-}
```
public final void setBrush(Brush value)
```


이 [Pen](../../com.aspose.drawing/pen)의 속성을 결정하는 Brush를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Brush](../../com.aspose.drawing/brush) |  |

### getCompoundArray() {#getCompoundArray--}
```
public final float[] getCompoundArray()
```


복합 펜을 지정하는 값 배열을 가져오거나 설정합니다. 복합 펜은 평행선과 간격으로 구성된 복합 라인을 그립니다.

**Returns:**
float[] - 복합 배열을 지정하는 실수 배열입니다. 배열의 요소는 오름차순이어야 하며 0보다 작지 않고 1보다 크지 않아야 합니다.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public final void setCompoundArray(float[] value)
```


복합 펜을 지정하는 값 배열을 가져오거나 설정합니다. 복합 펜은 평행선과 간격으로 구성된 복합 라인을 그립니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float[] |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


그리기에 사용되는 Graphics 객체의 단위로 이 Pen의 너비를 가져오거나 설정합니다.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


그리기에 사용되는 Graphics 객체의 단위로 이 Pen의 너비를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getStartCap() {#getStartCap--}
```
public final int getStartCap()
```


이 Pen으로 그린 선의 시작 부분에 사용되는 캡 스타일을 가져오거나 설정합니다.

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public final void setStartCap(int value)
```


이 Pen으로 그린 선의 시작 부분에 사용되는 캡 스타일을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public final int getEndCap()
```


이 Pen으로 그린 선의 끝 부분에 사용되는 캡 스타일을 가져오거나 설정합니다.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public final void setEndCap(int value)
```


이 Pen으로 그린 선의 끝 부분에 사용되는 캡 스타일을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public final int getLineJoin()
```


이 Pen으로 그린 두 연속 선의 끝에 대한 조인 스타일을 가져오거나 설정합니다.

--------------------

현재 Miter 조인은 실제로 MiterClipped처럼 동작합니다.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public final void setLineJoin(int value)
```


이 Pen으로 그린 두 연속 선의 끝에 대한 조인 스타일을 가져오거나 설정합니다.

--------------------

현재 Miter 조인은 실제로 MiterClipped처럼 동작합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


마이터 코너에서 조인의 두께 제한을 가져오거나 설정합니다.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


마이터 코너에서 조인의 두께 제한을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


이 [Pen](../../com.aspose.drawing/pen)의 정렬을 가져오거나 설정합니다.

**Returns:**
int - 이 [Pen](../../com.aspose.drawing/pen)의 정렬을 나타내는 [PenAlignment](../../com.aspose.drawing.drawing2d/penalignment)입니다.
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


이 [Pen](../../com.aspose.drawing/pen)의 정렬을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public final Matrix getTransform()
```


이 [Pen](../../com.aspose.drawing/pen)의 기하학적 변환 복사본을 가져오거나 설정합니다.

값: 이 [Pen](../../com.aspose.drawing/pen)의 기하 변환을 나타내는 [Matrix](../../com.aspose.drawing.drawing2d/matrix)의 복사본입니다.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void setTransform(Matrix value)
```


이 [Pen](../../com.aspose.drawing/pen)의 기하학적 변환 복사본을 가져오거나 설정합니다.

값: 이 [Pen](../../com.aspose.drawing/pen)의 기하 변환을 나타내는 [Matrix](../../com.aspose.drawing.drawing2d/matrix)의 복사본입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getCustomStartCap() {#getCustomStartCap--}
```
public final CustomLineCap getCustomStartCap()
```


이 [Pen](../../com.aspose.drawing/pen)으로 그린 선의 시작 부분에 사용할 사용자 정의 캡을 가져오거나 설정합니다.

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the beginning of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomStartCap(CustomLineCap value)
```


이 [Pen](../../com.aspose.drawing/pen)으로 그린 선의 시작 부분에 사용할 사용자 정의 캡을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getCustomEndCap() {#getCustomEndCap--}
```
public final CustomLineCap getCustomEndCap()
```


이 [Pen](../../com.aspose.drawing/pen)으로 그린 선의 끝 부분에 사용할 사용자 정의 캡을 가져오거나 설정합니다.

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the end of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomEndCap(CustomLineCap value)
```


이 [Pen](../../com.aspose.drawing/pen)으로 그린 선의 끝 부분에 사용할 사용자 정의 캡을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getDashCap() {#getDashCap--}
```
public final int getDashCap()
```


이 [Pen](../../com.aspose.drawing/pen)으로 그린 점선의 대시 끝에 사용되는 캡 스타일을 가져오거나 설정합니다.

**Returns:**
int - 이 [Pen](../../com.aspose.drawing/pen)으로 그린 점선의 대시 시작 및 끝에 사용되는 캡 스타일을 나타내는 `DashCap`([.getDashCap](../../null/\#getDashCap)/[.setDashCap(int)](../../null/\#setDashCap-int-)) 값 중 하나입니다.
### setDashCap(int value) {#setDashCap-int-}
```
public final void setDashCap(int value)
```


이 [Pen](../../com.aspose.drawing/pen)으로 그린 점선의 대시 끝에 사용되는 캡 스타일을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public final float getDashOffset()
```


선의 시작부터 대시 패턴 시작까지의 거리를 가져오거나 설정합니다.

**Returns:**
float - 선의 시작점부터 대시 패턴 시작점까지의 거리입니다.
### setDashOffset(float value) {#setDashOffset-float-}
```
public final void setDashOffset(float value)
```


선의 시작부터 대시 패턴 시작까지의 거리를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getDashPattern() {#getDashPattern--}
```
public final float[] getDashPattern()
```


사용자 정의 대시와 공백 배열을 가져오거나 설정합니다.

**Returns:**
float[] - 점선에서 교대로 나타나는 대시와 공백의 길이를 지정하는 실수 배열입니다.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public final void setDashPattern(float[] value)
```


사용자 정의 대시와 공백 배열을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float[] |  |

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


이 [Pen](../../com.aspose.drawing/pen)으로 그린 점선에 사용되는 스타일을 가져오거나 설정합니다.

**Returns:**
int - `DashStyle`([.getDashStyle](../../null/\#getDashStyle)/[.setDashStyle(int)](../../null/\#setDashStyle-int-)) 은 이 [Pen](../../com.aspose.drawing/pen)으로 그려지는 점선에 사용되는 스타일을 나타냅니다.
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


이 [Pen](../../com.aspose.drawing/pen)으로 그린 점선에 사용되는 스타일을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPenType() {#getPenType--}
```
public final int getPenType()
```


이 Pen으로 그린 선의 스타일을 가져옵니다.

값: `PenType`([.getPenType](../../null/\#getPenType)) 열거형은 이 [Pen](../../com.aspose.drawing/pen)으로 그려지는 선의 스타일을 지정합니다.

**Returns:**
int
### dispose() {#dispose--}
```
public final void dispose()
```


이 Pen이 사용한 모든 리소스를 해제합니다.

--------------------

이 메서드는 실제로 아무 작업도 수행하지 않습니다. System.Drawing API와의 호환성을 위해 제공됩니다.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


이 [Pen](../../com.aspose.drawing/pen)의 정확한 복사본을 생성합니다.

**Returns:**
java.lang.Object - [Pen](../../com.aspose.drawing/pen)으로 캐스팅할 수 있는 객체입니다.
### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public final void setLineCap(int startCap, int endCap, int dashCap)
```


이 [Pen](../../com.aspose.drawing/pen)으로 그린 선을 끝낼 때 사용되는 캡 스타일을 결정하는 값을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| startCap | int | [LineCap](../../com.aspose.drawing.drawing2d/linecap) 은 이 [Pen](../../com.aspose.drawing/pen)으로 그려지는 선의 시작 부분에 사용할 캡 스타일을 나타냅니다. |
| endCap | int | [LineCap](../../com.aspose.drawing.drawing2d/linecap) 은 이 [Pen](../../com.aspose.drawing/pen)으로 그려지는 선의 끝 부분에 사용할 캡 스타일을 나타냅니다. |
| dashCap | int | [LineCap](../../com.aspose.drawing.drawing2d/linecap) 은 이 [Pen](../../com.aspose.drawing/pen)으로 그려지는 점선의 시작 또는 끝에 사용할 캡 스타일을 나타냅니다. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public final void scaleTransform(float sx, float sy)
```


지정된 인수에 따라 로컬 기하 변환을 스케일합니다. 이 메서드는 스케일링 행렬을 변환 앞에 추가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sx | float | x축 방향으로 변환을 스케일할 인수입니다. |
| sy | float | y축 방향으로 변환을 스케일할 인수입니다. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public final void scaleTransform(float sx, float sy, int order)
```


지정된 순서대로 지정된 계수로 로컬 기하 변환을 스케일링합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sx | float | x축 방향으로 변환을 스케일할 인수입니다. |
| sy | float | y축 방향으로 변환을 스케일할 인수입니다. |
| order | int | 스케일링 행렬을 추가하거나 앞에 삽입할지 지정하는 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)입니다. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public final void translateTransform(float dx, float dy)
```


지정된 차원에 따라 로컬 기하 변환을 평행 이동합니다. 이 메서드는 평행 이동을 변환 앞에 추가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dx | float | x 방향 평행 이동 값입니다. |
| dy | float | y 방향 평행 이동 값입니다. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public final void translateTransform(float dx, float dy, int order)
```


지정된 순서대로 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dx | float | x 방향 평행 이동 값입니다. |
| dy | float | y 방향 평행 이동 값입니다. |
| order | int | 평행 이동을 적용할 순서(앞에 추가 또는 뒤에 추가)입니다. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public final void rotateTransform(float angle)
```


지정된 각도만큼 로컬 기하 변환을 회전합니다. 이 메서드는 회전을 변환 앞에 추가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public final void rotateTransform(float angle, int order)
```


지정된 순서대로 지정된 각도로 로컬 기하 변환을 회전시킵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도. |
| order | int | 회전 행렬을 추가하거나 앞에 삽입할지 지정하는 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)입니다. |

### resetTransform() {#resetTransform--}
```
public final void resetTransform()
```


이 [Pen](../../com.aspose.drawing/pen)의 기하 변환 행렬을 단위 행렬로 재설정합니다.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void multiplyTransform(Matrix matrix)
```


이 [Pen](../../com.aspose.drawing/pen)의 변환 행렬에 지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 곱합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 변환 행렬을 곱할 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 객체입니다. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public final void multiplyTransform(Matrix matrix, int order)
```


이 [Pen](../../com.aspose.drawing/pen)의 변환 행렬에 지정된 순서대로 지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 곱합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 변환 행렬을 곱할 java.awt.geom.AffineTransform입니다. |
| order | int | 곱셈 연산을 수행할 순서입니다. |

