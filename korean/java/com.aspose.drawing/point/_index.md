---
title: Point
second_title: Aspose.Drawing for Java API 참조
description: 2차원 평면에서 점을 정의하는 정수 x 및 y 좌표의 순서쌍을 나타냅니다.
type: docs
weight: 36
url: /ko/java/com.aspose.drawing/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Point extends Struct<Point> implements System.IEquatable<Point>, Cloneable
```

2차원 평면에서 점을 정의하는 정수 x 및 y 좌표의 순서쌍을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | 지정된 좌표를 사용하여 [Point](../../com.aspose.drawing/point) 구조체의 새 인스턴스를 초기화합니다. |
| [Point(Size sz)](#Point-com.aspose.drawing.Size-) |  |
| [Point(int dw)](#Point-int-) | 정수 값으로 지정된 좌표를 사용하여 [Point](../../com.aspose.drawing/point) 구조체의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [EMPTY](#EMPTY) | `Point.X`와 `Point.Y` 값이 0으로 설정된 [Point](../../com.aspose.drawing/point)를 나타냅니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [to_PointF(Point p)](#to-PointF-com.aspose.drawing.Point-) | 지정된 [Point](../../com.aspose.drawing/point) 구조를 [PointF](../../com.aspose.drawing/pointf) 구조로 변환합니다. |
| [to_Size(Point p)](#to-Size-com.aspose.drawing.Point-) |  |
| [op_Addition(Point pt, Size sz)](#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Subtraction(Point pt, Size sz)](#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Equality(Point left, Point right)](#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | 두 개의 [Point](../../com.aspose.drawing/point) 객체를 비교합니다. |
| [op_Inequality(Point left, Point right)](#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | 두 개의 [Point](../../com.aspose.drawing/point) 객체를 비교합니다. |
| [add(Point pt, Size sz)](#add-com.aspose.drawing.Point-com.aspose.drawing.Size-) | 지정된 [Size](../../com.aspose.drawing/size)을 지정된 [Point](../../com.aspose.drawing/point)에 추가합니다. |
| [subtract(Point pt, Size sz)](#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [ceiling(PointF value)](#ceiling-com.aspose.drawing.PointF-) |  |
| [truncate(PointF value)](#truncate-com.aspose.drawing.PointF-) | 모든 좌표에 대해 절단 연산을 수행하여 PointF를 Point로 변환합니다. |
| [round(PointF value)](#round-com.aspose.drawing.PointF-) | 지정된 [PointF](../../com.aspose.drawing/pointf)를 [Point](../../com.aspose.drawing/point) 값들을 가장 가까운 정수로 반올림하여 Point 객체로 변환합니다. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-) |  |
| [getEmpty()](#getEmpty--) |  |
| [getX()](#getX--) | 이 Point의 x좌표를 가져옵니다. |
| [setX(int value)](#setX-int-) | 이 Point의 x좌표를 설정합니다. |
| [getY()](#getY--) | 이 Point의 y좌표를 가져옵니다. |
| [setY(int value)](#setY-int-) | 이 Point의 y좌표를 설정합니다. |
| [isEmpty()](#isEmpty--) | 이 [Point](../../com.aspose.drawing/point)가 비어 있는지 여부를 나타내는 값을 가져옵니다. |
| [hashCode()](#hashCode--) | 이 [Point](../../com.aspose.drawing/point)의 해시 코드를 반환합니다. |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 [Point](../../com.aspose.drawing/point)가 지정된 Object와 동일한 좌표를 포함하는지 여부를 지정합니다. |
| [offset(int dx, int dy)](#offset-int-int-) | 지정된 양만큼 이 [Point](../../com.aspose.drawing/point)를 변환합니다. |
| [offset(Point p)](#offset-com.aspose.drawing.Point-) | 지정된 [Point](../../com.aspose.drawing/point)만큼 이 [Point](../../com.aspose.drawing/point)를 변환합니다. |
| [equals(Point other)](#equals-com.aspose.drawing.Point-) | 다른 [Point](../../com.aspose.drawing/point) 구조가 이 [Point](../../com.aspose.drawing/point) 구조와 동일한 위치를 갖는지 테스트합니다. |
| [CloneTo(Point that)](#CloneTo-com.aspose.drawing.Point-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


지정된 좌표를 사용하여 [Point](../../com.aspose.drawing/point) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | int | 점의 수평 위치입니다. |
| y | int | 점의 수직 위치입니다. |

### Point(Size sz) {#Point-com.aspose.drawing.Size-}
```
public Point(Size sz)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sz | [Size](../../com.aspose.drawing/size) |  |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


정수 값으로 지정된 좌표를 사용하여 [Point](../../com.aspose.drawing/point) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dw | int | 정수 값. |

### EMPTY {#EMPTY}
```
public static final Point EMPTY
```


`Point.X`와 `Point.Y` 값이 0으로 설정된 [Point](../../com.aspose.drawing/point)를 나타냅니다.

### to_PointF(Point p) {#to-PointF-com.aspose.drawing.Point-}
```
public static PointF to_PointF(Point p)
```


지정된 [Point](../../com.aspose.drawing/point) 구조를 [PointF](../../com.aspose.drawing/pointf) 구조로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | 변환될 [Point](../../com.aspose.drawing/point). |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The [PointF](../../com.aspose.drawing/pointf) that results from the conversion.
### to_Size(Point p) {#to-Size-com.aspose.drawing.Point-}
```
public static Size to_Size(Point p)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
[Size](../../com.aspose.drawing/size)
### op_Addition(Point pt, Size sz) {#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Addition(Point pt, Size sz)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Subtraction(Point pt, Size sz) {#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Subtraction(Point pt, Size sz)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Equality(Point left, Point right) {#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Equality(Point left, Point right)
```


두 개의 [Point](../../com.aspose.drawing/point) 객체를 비교합니다. 결과는 두 [Point](../../com.aspose.drawing/point) 객체의 `Point.X` 및 `Point.Y` 속성 값이 동일한지 여부를 지정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | 비교할 첫 번째 [Point](../../com.aspose.drawing/point). |
| right | [Point](../../com.aspose.drawing/point) | 비교할 두 번째 [Point](../../com.aspose.drawing/point). |

**Returns:**
boolean - `left`와 `right`의 `Point.X` 및 `Point.Y` 값이 동일하면 true; 그렇지 않으면 false.
### op_Inequality(Point left, Point right) {#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Inequality(Point left, Point right)
```


두 개의 [Point](../../com.aspose.drawing/point) 객체를 비교합니다. 결과는 두 [Point](../../com.aspose.drawing/point) 객체의 `Point.X` 또는 `Point.Y` 속성 값이 서로 다른지 여부를 지정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | 비교할 첫 번째 [Point](../../com.aspose.drawing/point). |
| right | [Point](../../com.aspose.drawing/point) | 비교할 두 번째 [Point](../../com.aspose.drawing/point). |

**Returns:**
boolean - `left`와 `right`의 `Point.X` 속성값 또는 `Point.Y` 속성값 중 하나라도 다르면 true; 그렇지 않으면 false.
### add(Point pt, Size sz) {#add-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point add(Point pt, Size sz)
```


지정된 [Size](../../com.aspose.drawing/size)을 지정된 [Point](../../com.aspose.drawing/point)에 추가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | 추가할 [Point](../../com.aspose.drawing/point). |
| sz | [Size](../../com.aspose.drawing/size) | 추가할 [Size](../../com.aspose.drawing/size) |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the addition operation.
### subtract(Point pt, Size sz) {#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point subtract(Point pt, Size sz)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### ceiling(PointF value) {#ceiling-com.aspose.drawing.PointF-}
```
public static Point ceiling(PointF value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### truncate(PointF value) {#truncate-com.aspose.drawing.PointF-}
```
public static Point truncate(PointF value)
```


모든 좌표에 대해 절단 연산을 수행하여 PointF를 Point로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | 잘라낼 [PointF](../../com.aspose.drawing/pointf). |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the truncate operation.
### round(PointF value) {#round-com.aspose.drawing.PointF-}
```
public static Point round(PointF value)
```


지정된 [PointF](../../com.aspose.drawing/pointf)를 [Point](../../com.aspose.drawing/point) 값들을 가장 가까운 정수로 반올림하여 Point 객체로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | 변환할 [PointF](../../com.aspose.drawing/pointf). |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) this method converts to.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.drawing/point) |  |
| obj2 | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### getX() {#getX--}
```
public final int getX()
```


이 Point의 x좌표를 가져옵니다.

**Returns:**
int - 이 Point의 x좌표.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


이 Point의 x좌표를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 이 Point의 x좌표. |

### getY() {#getY--}
```
public final int getY()
```


이 Point의 y좌표를 가져옵니다.

**Returns:**
int - 이 Point의 y좌표.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


이 Point의 y좌표를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 이 Point의 y좌표. |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


이 [Point](../../com.aspose.drawing/point)가 비어 있는지 여부를 나타내는 값을 가져옵니다.

값: X와 Y가 모두 0이면 `true`; 그렇지 않으면 `false`.

**Returns:**
boolean - 이 [Point](../../com.aspose.drawing/point)가 비어 있는지 여부를 나타내는 값.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 [Point](../../com.aspose.drawing/point)의 해시 코드를 반환합니다.

**Returns:**
int - 이 [Point](../../com.aspose.drawing/point)의 해시 값을 지정하는 정수 값.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 [Point](../../com.aspose.drawing/point)가 지정된 Object와 동일한 좌표를 포함하는지 여부를 지정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 테스트할 객체. |

**Returns:**
boolean - `obj`가 Point이며 이 [Point](../../com.aspose.drawing/point)와 동일한 좌표를 가지고 있으면 `true`.
### offset(int dx, int dy) {#offset-int-int-}
```
public final void offset(int dx, int dy)
```


지정된 양만큼 이 [Point](../../com.aspose.drawing/point)를 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dx | int | x좌표를 오프셋할 양. |
| dy | int | y좌표를 오프셋할 양. |

### offset(Point p) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point p)
```


지정된 [Point](../../com.aspose.drawing/point)만큼 이 [Point](../../com.aspose.drawing/point)를 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | 이 [Point](../../com.aspose.drawing/point)를 오프셋하는 데 사용된 [Point](../../com.aspose.drawing/point). |

### equals(Point other) {#equals-com.aspose.drawing.Point-}
```
public final boolean equals(Point other)
```


다른 [Point](../../com.aspose.drawing/point) 구조가 이 [Point](../../com.aspose.drawing/point) 구조와 동일한 위치를 갖는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [Point](../../com.aspose.drawing/point) | 테스트할 다른 점 |

**Returns:**
boolean - 다른 [Point](../../com.aspose.drawing/point) 구조와 그 X 및 Y 속성이 이 [Point](../../com.aspose.drawing/point) 구조의 해당 속성과 동일하면 `true`; 그렇지 않으면 `false`.
### CloneTo(Point that) {#CloneTo-com.aspose.drawing.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| that | [Point](../../com.aspose.drawing/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
