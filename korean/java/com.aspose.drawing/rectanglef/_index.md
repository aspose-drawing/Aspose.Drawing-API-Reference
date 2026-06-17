---
title: RectangleF
second_title: Aspose.Drawing for Java API 참조
description: 사각형의 위치와 크기를 나타내는 네 개의 부동소수점 숫자를 저장합니다.
type: docs
weight: 39
url: /ko/java/com.aspose.drawing/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class RectangleF extends Struct<RectangleF> implements System.IEquatable<RectangleF>, Cloneable
```

사각형의 위치와 크기를 나타내는 네 개의 부동 소수점 숫자 집합을 저장합니다. 보다 고급 영역 기능을 위해서는 Region 객체를 사용하십시오.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | 지정된 위치와 크기로 RectangleF 구조의 새 인스턴스를 초기화합니다. |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | 지정된 위치와 크기로 RectangleF 구조의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | 두 점으로부터 새로운 사각형을 생성합니다. |
| [to_RectangleF(Rectangle r)](#to-RectangleF-com.aspose.drawing.Rectangle-) | 지정된 Rectangle 구조를 RectangleF 구조로 변환합니다. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | 두 [RectangleF](../../com.aspose.drawing/rectanglef) 구조가 위치와 크기가 같은지 테스트합니다. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | 두 [RectangleF](../../com.aspose.drawing/rectanglef) 구조가 위치 또는 크기가 다른지 테스트합니다. |
| [fromLTRB(float left, float top, float right, float bottom)](#fromLTRB-float-float-float-float-) | 지정된 위치에 좌상단과 우하단 모서리를 갖는 RectangleF 구조를 생성합니다. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.drawing.RectangleF-float-float-) | 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조의 확대된 복사본을 생성하고 반환합니다. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | 두 사각형의 교차점을 나타내는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조를 반환합니다. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | 두 사각형을 합친 영역을 포함할 수 있는 가장 작은 세 번째 사각형을 생성합니다. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | 이 [RectangleF](../../com.aspose.drawing/rectanglef)의 `RectangleF.Width` 또는 `RectangleF.Height` 속성이 0인지 여부를 나타내는 값을 가져옵니다. |
| [getX()](#getX--) | 이 RectangleF 구조의 좌상단 모서리 x좌표를 가져옵니다. |
| [setX(float value)](#setX-float-) | 이 RectangleF 구조의 좌상단 모서리 x좌표를 설정합니다. |
| [getY()](#getY--) | 이 RectangleF 구조의 좌상단 모서리 x좌표를 가져옵니다. |
| [setY(float value)](#setY-float-) | 이 RectangleF 구조의 좌상단 모서리 x좌표를 설정합니다. |
| [getLocation()](#getLocation--) | 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조의 좌상단 모서리 좌표를 가져옵니다. |
| [setLocation(PointF value)](#setLocation-com.aspose.drawing.PointF-) | 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조의 왼쪽 위 모서리 좌표를 설정합니다. |
| [getWidth()](#getWidth--) | 이 RectangleF 구조의 너비를 가져옵니다. |
| [setWidth(float value)](#setWidth-float-) | 이 RectangleF 구조의 너비를 설정합니다. |
| [getHeight()](#getHeight--) | 이 RectangleF 구조의 높이를 가져옵니다. |
| [setHeight(float value)](#setHeight-float-) | 이 RectangleF 구조의 높이를 설정합니다. |
| [getSize()](#getSize--) | 이 [RectangleF](../../com.aspose.drawing/rectanglef)의 크기를 가져옵니다. |
| [setSize(SizeF value)](#setSize-com.aspose.drawing.SizeF-) | 이 [RectangleF](../../com.aspose.drawing/rectanglef)의 크기를 설정합니다. |
| [getLeft()](#getLeft--) | 이 RectangleF 구조의 왼쪽 가장자리 x 좌표를 가져옵니다. |
| [getTop()](#getTop--) | 이 RectangleF 구조의 위쪽 가장자리 y 좌표를 가져옵니다. |
| [getRight()](#getRight--) | 이 RectangleF 구조의 X와 Width를 합한 x 좌표를 가져옵니다. |
| [getBottom()](#getBottom--) | 이 RectangleF 구조의 Y와 Height를 합한 y 좌표를 가져옵니다. |
| [toString()](#toString--) |  |
| [inflate(float x, float y)](#inflate-float-float-) | 지정된 양만큼 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조를 확장합니다. |
| [inflate(SizeF size)](#inflate-com.aspose.drawing.SizeF-) | 지정된 양만큼 이 [RectangleF](../../com.aspose.drawing/rectanglef)를 확장합니다. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조를 자체와 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조의 교차 영역으로 교체합니다. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.drawing.RectangleF-) | `rect`와 이 사각형이 교차하는지 확인합니다. |
| [offset(PointF pos)](#offset-com.aspose.drawing.PointF-) | 지정된 양만큼 이 사각형의 위치를 조정합니다. |
| [offset(float x, float y)](#offset-float-float-) | 지정된 양만큼 이 사각형의 위치를 조정합니다. |
| [contains(float x, float y)](#contains-float-float-) | 지정된 점이 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조에 포함되는지 확인합니다. |
| [contains(PointF pt)](#contains-com.aspose.drawing.PointF-) | 지정된 점이 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조에 포함되는지 확인합니다. |
| [contains(RectangleF rect)](#contains-com.aspose.drawing.RectangleF-) | `rect`가 나타내는 사각형 영역이 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조에 완전히 포함되는지 확인합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 Object가 이 인스턴스와 같은지 여부를 확인합니다. |
| [hashCode()](#hashCode--) | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| [equals(RectangleF other)](#equals-com.aspose.drawing.RectangleF-) | 다른 [RectangleF](../../com.aspose.drawing/rectanglef) 구조가 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조와 동일한 위치와 크기를 가지고 있는지 테스트합니다. |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.drawing.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


지정된 위치와 크기로 RectangleF 구조의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| location | [PointF](../../com.aspose.drawing/pointf) | 사각형 영역의 왼쪽 위 모서리를 나타내는 PointF. |
| size | [SizeF](../../com.aspose.drawing/sizef) | 사각형 영역의 너비와 높이를 나타내는 SizeF. |

### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


지정된 위치와 크기로 RectangleF 구조의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 사각형의 왼쪽 위 모서리 x 좌표. |
| y | float | 직사각형의 왼쪽 위 모서리의 y 좌표. |
| 너비 | float | 직사각형의 너비. |
| 높이 | float | 직사각형의 높이. |

### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


두 점으로부터 새로운 직사각형을 생성합니다. 생성된 직사각형은 (left,top)이 (right,bottom)보다 작도록 정규화됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | 첫 번째 점. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | 두 번째 점. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A newly created rectangle.
### to_RectangleF(Rectangle r) {#to-RectangleF-com.aspose.drawing.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle r)
```


지정된 Rectangle 구조를 RectangleF 구조로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| r | [Rectangle](../../com.aspose.drawing/rectangle) | 변환할 Rectangle 구조체. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The RectangleF structure that is converted from the specified Rectangle structure.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


두 [RectangleF](../../com.aspose.drawing/rectanglef) 구조가 위치와 크기가 같은지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | 동등 연산자 왼쪽에 있는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | 동등 연산자 오른쪽에 있는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체. |

**Returns:**
boolean - 두 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체의 `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width`, `RectangleF.Height` 속성이 모두 동일하면 true를 반환합니다.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


두 [RectangleF](../../com.aspose.drawing/rectanglef) 구조가 위치 또는 크기가 다른지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | 부등 연산자 왼쪽에 있는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | 부등 연산자 오른쪽에 있는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체. |

**Returns:**
boolean - 두 [Rectangle](../../com.aspose.drawing/rectangle) 구조체의 `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width`, `RectangleF.Height` 속성 중 하나라도 다르면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### fromLTRB(float left, float top, float right, float bottom) {#fromLTRB-float-float-float-float-}
```
public static RectangleF fromLTRB(float left, float top, float right, float bottom)
```


지정된 위치에 좌상단과 우하단 모서리를 갖는 RectangleF 구조를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 왼쪽 | float | 사각형 영역의 왼쪽 위 모서리의 x 좌표. |
| 위쪽 | float | 사각형 영역의 왼쪽 위 모서리의 y 좌표. |
| 오른쪽 | float | 사각형 영역의 오른쪽 아래 모서리의 x 좌표. |
| 아래쪽 | float | 사각형 영역의 오른쪽 아래 모서리의 y 좌표. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The new RectangleF that this method creates.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.drawing.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체의 확대된 복사본을 생성하고 반환합니다. 복사본은 지정된 양만큼 확대됩니다. 원본 직사각형은 수정되지 않습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 복사할 [RectangleF](../../com.aspose.drawing/rectanglef)입니다. 이 직사각형은 수정되지 않습니다. |
| x | float | 직사각형 복사본을 수평으로 확대할 양. |
| y | float | 직사각형 복사본을 수직으로 확장하는 양. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The inflated [RectangleF](../../com.aspose.drawing/rectanglef).
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


두 직사각형의 교차점을 나타내는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체를 반환합니다. 교차점이 없으면 빈 [RectangleF](../../com.aspose.drawing/rectanglef)가 반환됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | 교차할 첫 번째 직사각형. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | 교차할 두 번째 직사각형. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


두 사각형을 합친 영역을 포함할 수 있는 가장 작은 세 번째 사각형을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | 합집합에 사용할 첫 번째 직사각형. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | 합집합에 사용할 두 번째 직사각형. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure that contains both of the two rectangles that form the union.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


이 [RectangleF](../../com.aspose.drawing/rectanglef)의 `RectangleF.Width` 또는 `RectangleF.Height` 속성이 0인지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 속성은 이 [RectangleF](../../com.aspose.drawing/rectanglef)의 `RectangleF.Width` 또는 `P:RectangleF.Height` 속성 값이 0이면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### getX() {#getX--}
```
public final float getX()
```


이 RectangleF 구조의 좌상단 모서리 x좌표를 가져옵니다.

**Returns:**
float - 이 RectangleF 구조체의 왼쪽 위 모서리의 x 좌표.
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


이 RectangleF 구조의 좌상단 모서리 x좌표를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 RectangleF 구조체의 왼쪽 위 모서리의 x 좌표. |

### getY() {#getY--}
```
public final float getY()
```


이 RectangleF 구조의 좌상단 모서리 x좌표를 가져옵니다.

**Returns:**
float - 이 RectangleF 구조체의 왼쪽 위 모서리의 x 좌표.
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


이 RectangleF 구조의 좌상단 모서리 x좌표를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 RectangleF 구조체의 왼쪽 위 모서리의 x 좌표. |

### getLocation() {#getLocation--}
```
public final PointF getLocation()
```


이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조의 좌상단 모서리 좌표를 가져옵니다.

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - A [PointF](../../com.aspose.drawing/pointf) that represents the upper-left corner of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setLocation(PointF value) {#setLocation-com.aspose.drawing.PointF-}
```
public final void setLocation(PointF value)
```


이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조의 왼쪽 위 모서리 좌표를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체의 왼쪽 위 모서리 좌표. |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


이 RectangleF 구조의 너비를 가져옵니다.

**Returns:**
float - 이 RectangleF 구조체의 너비.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


이 RectangleF 구조의 너비를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 RectangleF 구조체의 너비. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


이 RectangleF 구조의 높이를 가져옵니다.

**Returns:**
float - 이 RectangleF 구조체의 높이.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


이 RectangleF 구조의 높이를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 RectangleF 구조체의 높이. |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


이 [RectangleF](../../com.aspose.drawing/rectanglef)의 크기를 가져옵니다.

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that represents the width and height of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setSize(SizeF value) {#setSize-com.aspose.drawing.SizeF-}
```
public final void setSize(SizeF value)
```


이 [RectangleF](../../com.aspose.drawing/rectanglef)의 크기를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | 이 [RectangleF](../../com.aspose.drawing/rectanglef)의 크기. |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


이 RectangleF 구조의 왼쪽 가장자리 x 좌표를 가져옵니다.

**Returns:**
float - 이 RectangleF 구조체의 왼쪽 가장자리 x 좌표.
### getTop() {#getTop--}
```
public final float getTop()
```


이 RectangleF 구조의 위쪽 가장자리 y 좌표를 가져옵니다.

**Returns:**
float - 이 RectangleF 구조체의 위쪽 가장자리 y 좌표.
### getRight() {#getRight--}
```
public final float getRight()
```


이 RectangleF 구조의 X와 Width를 합한 x 좌표를 가져옵니다.

**Returns:**
float - 이 RectangleF 구조체의 X와 Width를 합한 x 좌표.
### getBottom() {#getBottom--}
```
public final float getBottom()
```


이 RectangleF 구조의 Y와 Height를 합한 y 좌표를 가져옵니다.

**Returns:**
float - 이 RectangleF 구조체의 Y와 Height를 합한 y 좌표.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### inflate(float x, float y) {#inflate-float-float-}
```
public final void inflate(float x, float y)
```


지정된 양만큼 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조를 확장합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체를 수평으로 확장하는 양. |
| y | float | 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체를 수직으로 확장하는 양. |

### inflate(SizeF size) {#inflate-com.aspose.drawing.SizeF-}
```
public final void inflate(SizeF size)
```


지정된 양만큼 이 [RectangleF](../../com.aspose.drawing/rectanglef)를 확장합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | 이 직사각형을 확장하는 양. |

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public final void intersect(RectangleF rect)
```


이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조를 자체와 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조의 교차 영역으로 교체합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 교차할 직사각형. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.drawing.RectangleF-}
```
public final boolean intersectsWith(RectangleF rect)
```


`rect`와 이 사각형이 교차하는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 테스트할 직사각형. |

**Returns:**
boolean - 교차점이 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### offset(PointF pos) {#offset-com.aspose.drawing.PointF-}
```
public final void offset(PointF pos)
```


지정된 양만큼 이 사각형의 위치를 조정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.drawing/pointf) | 위치를 오프셋하는 양. |

### offset(float x, float y) {#offset-float-float-}
```
public final void offset(float x, float y)
```


지정된 양만큼 이 사각형의 위치를 조정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 위치를 수평으로 오프셋하는 양. |
| y | float | 위치를 수직으로 오프셋하는 양. |

### contains(float x, float y) {#contains-float-float-}
```
public final boolean contains(float x, float y)
```


지정된 점이 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조에 포함되는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 테스트할 점의 x좌표. |
| y | float | 테스트할 점의 y좌표. |

**Returns:**
boolean - 이 메서드는 x와 y로 정의된 점이 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조에 포함되어 있으면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.
### contains(PointF pt) {#contains-com.aspose.drawing.PointF-}
```
public final boolean contains(PointF pt)
```


지정된 점이 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조에 포함되는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | 테스트할 [PointF](../../com.aspose.drawing/pointf). |

**Returns:**
boolean - 이 메서드는 pt 매개변수로 표현된 점이 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조에 포함되어 있으면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.
### contains(RectangleF rect) {#contains-com.aspose.drawing.RectangleF-}
```
public final boolean contains(RectangleF rect)
```


`rect`가 나타내는 사각형 영역이 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조에 완전히 포함되는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 테스트할 [RectangleF](../../com.aspose.drawing/rectanglef). |

**Returns:**
boolean - 이 메서드는 `rect`로 표현된 사각형 영역이 이 [RectangleF](../../com.aspose.drawing/rectanglef)로 표현된 사각형 영역에 완전히 포함되어 있으면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 Object가 이 인스턴스와 같은지 여부를 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 Object. |

**Returns:**
boolean - 지정된 Object가 이 인스턴스와 동일하면 `true`, 그렇지 않으면 `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스에 대한 해시 코드를 반환합니다.

**Returns:**
int - 이 인스턴스에 대한 해시 코드로, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용하기에 적합합니다.
### equals(RectangleF other) {#equals-com.aspose.drawing.RectangleF-}
```
public final boolean equals(RectangleF other)
```


다른 [RectangleF](../../com.aspose.drawing/rectanglef) 구조가 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조와 동일한 위치와 크기를 가지고 있는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [RectangleF](../../com.aspose.drawing/rectanglef) | 테스트할 다른 사각형 |

**Returns:**
boolean - 이 메서드는 다른 [RectangleF](../../com.aspose.drawing/rectanglef) 구조와 그 X, Y, Width, Height 속성이 이 [RectangleF](../../com.aspose.drawing/rectanglef) 구조의 해당 속성과 동일하면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.drawing.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
