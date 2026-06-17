---
title: CustomLineCap
second_title: Aspose.Drawing for Java API 참조
description: 사용자 정의 라인 캡을 캡슐화합니다.
type: docs
weight: 17
url: /ko/java/com.aspose.drawing.drawing2d/customlinecap/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class CustomLineCap implements System.IDisposable
```

사용자 정의 라인 캡을 캡슐화합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-) | 지정된 외곽선과 채우기로 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 클래스의 새 인스턴스를 초기화합니다. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-) | 지정된 외곽선과 채우기로 지정된 기존 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 열거형에서 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 클래스의 새 인스턴스를 초기화합니다. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-) | 지정된 외곽선, 채우기 및 삽입값으로 지정된 기존 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 열거형에서 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getStrokeJoin()](#getStrokeJoin--) | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 객체를 구성하는 선들이 결합되는 방식을 결정하는 [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) 열거형을 가져오거나 설정합니다. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 객체를 구성하는 선들이 결합되는 방식을 결정하는 [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) 열거형을 가져오거나 설정합니다. |
| [getBaseCap()](#getBaseCap--) | 이 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)의 기반이 되는 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 열거형을 가져오거나 설정합니다. |
| [setBaseCap(int value)](#setBaseCap-int-) | 이 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)의 기반이 되는 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 열거형을 가져오거나 설정합니다. |
| [getBaseInset()](#getBaseInset--) | 캡과 선 사이의 거리를 가져오거나 설정합니다. |
| [setBaseInset(float value)](#setBaseInset-float-) | 캡과 선 사이의 거리를 가져오거나 설정합니다. |
| [getWidthScale()](#getWidthScale--) | [Pen](../../com.aspose.drawing/pen) 객체의 너비에 대한 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 클래스 객체의 스케일 비율을 가져오거나 설정합니다. |
| [setWidthScale(float value)](#setWidthScale-float-) | [Pen](../../com.aspose.drawing/pen) 객체의 너비에 대한 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 클래스 객체의 스케일 비율을 가져오거나 설정합니다. |
| [dispose()](#dispose--) | 이 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 객체가 사용한 모든 리소스를 해제합니다. |
| [deepClone()](#deepClone--) | 이 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)의 정확한 복사본을 생성합니다. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | 이 사용자 정의 캡을 구성하는 선의 시작 및 끝에 사용되는 캡을 설정합니다. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | 이 사용자 정의 캡을 구성하는 선의 시작 및 끝에 사용되는 캡을 가져옵니다. |
| [getFillPath()](#getFillPath--) |  |
| [getStrokePath()](#getStrokePath--) | 사용자 정의 캡의 외곽선을 정의하는 객체를 가져옵니다. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


지정된 외곽선과 채우기로 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 사용자 정의 캡의 채우기를 정의하는 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 사용자 정의 캡의 외곽선을 정의하는 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


지정된 외곽선과 채우기로 지정된 기존 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 열거형에서 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 사용자 정의 캡의 채우기를 정의하는 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 사용자 정의 캡의 외곽선을 정의하는 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체. |
| baseCap | int | 사용자 정의 캡을 생성할 기준이 되는 선 캡입니다. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


지정된 외곽선, 채우기 및 삽입값으로 지정된 기존 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 열거형에서 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 사용자 정의 캡의 채우기를 정의하는 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 사용자 정의 캡의 외곽선을 정의하는 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체. |
| baseCap | int | 사용자 정의 캡을 생성할 기준이 되는 선 캡입니다. |
| baseInset | float | 캡과 선 사이의 거리입니다. |

### getStrokeJoin() {#getStrokeJoin--}
```
public final int getStrokeJoin()
```


[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 객체를 구성하는 선들이 결합되는 방식을 결정하는 [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) 열거형을 가져오거나 설정합니다.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public final void setStrokeJoin(int value)
```


[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 객체를 구성하는 선들이 결합되는 방식을 결정하는 [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) 열거형을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public final int getBaseCap()
```


이 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)의 기반이 되는 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 열거형을 가져오거나 설정합니다.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public final void setBaseCap(int value)
```


이 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)의 기반이 되는 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 열거형을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public final float getBaseInset()
```


캡과 선 사이의 거리를 가져오거나 설정합니다.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public final void setBaseInset(float value)
```


캡과 선 사이의 거리를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public final float getWidthScale()
```


[Pen](../../com.aspose.drawing/pen) 객체의 너비에 대한 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 클래스 객체의 스케일 비율을 가져오거나 설정합니다.

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public final void setWidthScale(float value)
```


[Pen](../../com.aspose.drawing/pen) 객체의 너비에 대한 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 클래스 객체의 스케일 비율을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### dispose() {#dispose--}
```
public final void dispose()
```


이 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 객체가 사용한 모든 리소스를 해제합니다.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


이 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)의 정확한 복사본을 생성합니다.

**Returns:**
java.lang.Object - 이 메서드가 생성하는 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)을 객체로 캐스팅한 것입니다.
### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public final void setStrokeCaps(int startCap, int endCap)
```


이 사용자 정의 캡을 구성하는 선의 시작 및 끝에 사용되는 캡을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| startCap | int | 이 캡 내에서 선의 시작 부분에 사용되는 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 열거형입니다. |
| endCap | int | 이 캡 내에서 선의 끝 부분에 사용되는 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 열거형입니다. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public final void getStrokeCaps(int[] startCap, int[] endCap)
```


이 사용자 정의 캡을 구성하는 선의 시작 및 끝에 사용되는 캡을 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| startCap | int[] | 이 캡 내에서 선의 시작 부분에 사용되는 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 열거형입니다. |
| endCap | int[] | 이 캡 내에서 선의 끝 부분에 사용되는 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 열거형입니다. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```




**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


사용자 정의 캡의 외곽선을 정의하는 객체를 가져옵니다.

**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) - The object that defines the outline of the custom cap.
