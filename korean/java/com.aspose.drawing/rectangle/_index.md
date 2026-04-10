---
title: Rectangle
second_title: Aspose.Drawing for Java API 참조
description: 사각형의 위치와 크기를 나타내는 네 개의 정수를 저장합니다.
type: docs
weight: 38
url: /ko/java/com.aspose.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Rectangle extends Struct<Rectangle> implements System.IEquatable<Rectangle>, Cloneable
```

사각형의 위치와 크기를 나타내는 네 개의 정수를 저장합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | 지정된 위치와 크기로 Rectangle 구조의 새 인스턴스를 초기화합니다. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-) | 지정된 위치와 크기로 [Rectangle](../../com.aspose.drawing/rectangle) 구조체의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [fromLTRB(int left, int top, int right, int bottom)](#fromLTRB-int-int-int-int-) | 지정된 가장자리 위치로 [Rectangle](../../com.aspose.drawing/rectangle) 구조를 생성합니다. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | 두 다른 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 교차점을 나타내는 세 번째 [Rectangle](../../com.aspose.drawing/rectangle) 구조를 반환합니다. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | 두 [Rectangle](../../com.aspose.drawing/rectangle) 구조가 동일한 위치와 크기를 갖는지 테스트합니다. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | 두 [Rectangle](../../com.aspose.drawing/rectangle) 구조가 위치 또는 크기가 다른지 테스트합니다. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.drawing.RectangleF-) | 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조를 [Rectangle](../../com.aspose.drawing/rectangle) 구조로 변환하며, [RectangleF](../../com.aspose.drawing/rectanglef) 값들을 다음 높은 정수값으로 반올림합니다. |
| [truncate(RectangleF value)](#truncate-com.aspose.drawing.RectangleF-) | 지정된 [RectangleF](../../com.aspose.drawing/rectanglef)를 [Rectangle](../../com.aspose.drawing/rectangle)으로 변환하며, [RectangleF](../../com.aspose.drawing/rectanglef) 값을 잘라냅니다. |
| [round(RectangleF value)](#round-com.aspose.drawing.RectangleF-) | 지정된 [RectangleF](../../com.aspose.drawing/rectanglef)를 [Rectangle](../../com.aspose.drawing/rectangle)으로 변환하며, [RectangleF](../../com.aspose.drawing/rectanglef) 값을 가장 가까운 정수값으로 반올림합니다. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | 두 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 합집합을 포함하는 [Rectangle](../../com.aspose.drawing/rectangle) 구조를 가져옵니다. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.drawing.Rectangle-int-int-) |  |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) |  |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-) | 두 점으로부터 새로운 사각형을 생성합니다. |
| [getEmpty()](#getEmpty--) | `Rectangle` 구조의 새 인스턴스를 가져오며, `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width`, `Rectangle.Height` 값이 0으로 설정됩니다. |
| [getX()](#getX--) | 이 Rectangle 구조의 왼쪽 위 모서리의 x 좌표를 가져옵니다. |
| [setX(int value)](#setX-int-) | 이 Rectangle 구조의 왼쪽 위 모서리의 x 좌표를 설정합니다. |
| [getY()](#getY--) | 이 Rectangle 구조의 왼쪽 위 모서리의 y 좌표를 가져옵니다. |
| [setY(int value)](#setY-int-) | 이 Rectangle 구조의 왼쪽 위 모서리의 y 좌표를 설정합니다. |
| [getLocation()](#getLocation--) | 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 왼쪽 위 모서리 좌표를 가져옵니다. |
| [setLocation(Point value)](#setLocation-com.aspose.drawing.Point-) | 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 왼쪽 위 모서리 좌표를 설정합니다. |
| [getWidth()](#getWidth--) | 이 Rectangle 구조의 너비를 가져옵니다. |
| [setWidth(int value)](#setWidth-int-) | 이 Rectangle 구조의 너비를 설정합니다. |
| [getHeight()](#getHeight--) | 이 Rectangle 구조의 높이를 가져옵니다. |
| [setHeight(int value)](#setHeight-int-) | 이 Rectangle 구조의 높이를 설정합니다. |
| [getSize()](#getSize--) | 이 [Rectangle](../../com.aspose.drawing/rectangle)의 크기를 가져옵니다. |
| [setSize(Size value)](#setSize-com.aspose.drawing.Size-) | 이 [Rectangle](../../com.aspose.drawing/rectangle)의 크기를 설정합니다. |
| [getLeft()](#getLeft--) | 이 Rectangle 구조의 왼쪽 가장자리 x좌표를 가져옵니다. |
| [getTop()](#getTop--) | 이 Rectangle 구조의 위쪽 가장자리 y좌표를 가져옵니다. |
| [getRight()](#getRight--) | 이 Rectangle 구조의 X와 Width 속성 값을 합한 x좌표를 가져옵니다. |
| [getBottom()](#getBottom--) | 이 Rectangle 구조의 Y와 Height 속성 값을 합한 y좌표를 가져옵니다. |
| [isEmpty()](#isEmpty--) | 이 [Rectangle](../../com.aspose.drawing/rectangle)의 모든 숫자 속성이 0인지 여부를 나타내는 값을 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | obj가 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조와 동일한 위치와 크기를 가진 [Rectangle](../../com.aspose.drawing/rectangle) 구조인지 테스트합니다. |
| [hashCode()](#hashCode--) | 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 해시 코드를 반환합니다. |
| [toString()](#toString--) |  |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | 이 [Rectangle](../../com.aspose.drawing/rectangle)를 자체와 지정된 [Rectangle](../../com.aspose.drawing/rectangle)의 교차 영역으로 교체합니다. |
| [inflate(int width, int height)](#inflate-int-int-) | 이 [Rectangle](../../com.aspose.drawing/rectangle)를 지정된 양만큼 확대합니다. |
| [inflate(Size size)](#inflate-com.aspose.drawing.Size-) | 이 [Rectangle](../../com.aspose.drawing/rectangle)를 지정된 양만큼 확대합니다. |
| [contains(int x, int y)](#contains-int-int-) | 지정된 점이 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조에 포함되는지 확인합니다. |
| [contains(Point pt)](#contains-com.aspose.drawing.Point-) | 지정된 점이 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조에 포함되는지 확인합니다. |
| [contains(Rectangle rect)](#contains-com.aspose.drawing.Rectangle-) |  |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.drawing.Rectangle-) | `rect`와 이 사각형이 교차하는지 확인합니다. |
| [offset(int x, int y)](#offset-int-int-) | 지정된 양만큼 이 사각형의 위치를 조정합니다. |
| [offset(Point pos)](#offset-com.aspose.drawing.Point-) | 지정된 양만큼 이 사각형의 위치를 조정합니다. |
| [equals(Rectangle other)](#equals-com.aspose.drawing.Rectangle-) | 다른 [Rectangle](../../com.aspose.drawing/rectangle) 구조가 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조와 동일한 위치와 크기를 가지고 있는지 테스트합니다. |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.drawing.Rectangle-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [normalize()](#normalize--) | 사각형의 너비와 높이를 양수로 만들고, 왼쪽이 오른쪽보다 작으며 위쪽이 아래쪽보다 작도록 정규화합니다. |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


지정된 위치와 크기로 Rectangle 구조의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | int | 사각형의 왼쪽 위 모서리 x 좌표. |
| y | int | 직사각형의 왼쪽 위 모서리의 y 좌표. |
| 너비 | int | 직사각형의 너비. |
| 높이 | int | 직사각형의 높이. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public Rectangle(Point location, Size size)
```


지정된 위치와 크기로 [Rectangle](../../com.aspose.drawing/rectangle) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| location | [Point](../../com.aspose.drawing/point) | 직사각형 영역의 왼쪽 위 모서리를 나타내는 [Point](../../com.aspose.drawing/point)입니다. |
| size | [Size](../../com.aspose.drawing/size) | 직사각형 영역의 너비와 높이를 나타내는 `Size`([.getSize](../../null/\#getSize)/[.setSize(Size)](../../null/\#setSize-Size-))입니다. |

### fromLTRB(int left, int top, int right, int bottom) {#fromLTRB-int-int-int-int-}
```
public static Rectangle fromLTRB(int left, int top, int right, int bottom)
```


지정된 가장자리 위치로 [Rectangle](../../com.aspose.drawing/rectangle) 구조를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | int | 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 왼쪽 위 모서리 x좌표. |
| top | int | 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 왼쪽 위 모서리 y좌표. |
| right | int | 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 오른쪽 아래 모서리 x좌표. |
| bottom | int | 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 오른쪽 아래 모서리 y좌표. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The new [Rectangle](../../com.aspose.drawing/rectangle) that this method creates.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


두 개의 다른 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 교차점을 나타내는 세 번째 [Rectangle](../../com.aspose.drawing/rectangle) 구조를 반환합니다. 교차점이 없으면 빈 [Rectangle](../../com.aspose.drawing/rectangle)이 반환됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | 교차할 첫 번째 직사각형. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | 교차할 두 번째 직사각형. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the intersection of `a` and `b`.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


두 [Rectangle](../../com.aspose.drawing/rectangle) 구조가 동일한 위치와 크기를 갖는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | 동등 연산자의 왼쪽에 있는 [Rectangle](../../com.aspose.drawing/rectangle) 구조. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | 동등 연산자의 오른쪽에 있는 [Rectangle](../../com.aspose.drawing/rectangle) 구조. |

**Returns:**
boolean - 두 [Rectangle](../../com.aspose.drawing/rectangle) 구조가 X, Y, Width, Height 속성이 모두 동일하면 이 연산자는 `true`를 반환합니다.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


두 [Rectangle](../../com.aspose.drawing/rectangle) 구조가 위치 또는 크기가 다른지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | 부등 연산자의 왼쪽에 있는 [Rectangle](../../com.aspose.drawing/rectangle) 구조. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | 부등 연산자의 오른쪽에 있는 [Rectangle](../../com.aspose.drawing/rectangle) 구조. |

**Returns:**
boolean - 두 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 X, Y, Width 또는 Height 속성 중 하나라도 서로 다르면 이 연산자는 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.
### ceiling(RectangleF value) {#ceiling-com.aspose.drawing.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조를 [Rectangle](../../com.aspose.drawing/rectangle) 구조로 변환하며, [RectangleF](../../com.aspose.drawing/rectanglef) 값들을 다음 높은 정수값으로 반올림합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | 변환할 [RectangleF](../../com.aspose.drawing/rectanglef) 구조. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - Returns a [Rectangle](../../com.aspose.drawing/rectangle).
### truncate(RectangleF value) {#truncate-com.aspose.drawing.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


지정된 [RectangleF](../../com.aspose.drawing/rectanglef)를 [Rectangle](../../com.aspose.drawing/rectangle)으로 변환하며, [RectangleF](../../com.aspose.drawing/rectanglef) 값을 잘라냅니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | 변환할 [RectangleF](../../com.aspose.drawing/rectanglef). |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The truncated value of the [Rectangle](../../com.aspose.drawing/rectangle).
### round(RectangleF value) {#round-com.aspose.drawing.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


지정된 [RectangleF](../../com.aspose.drawing/rectanglef)를 [Rectangle](../../com.aspose.drawing/rectangle)으로 변환하며, [RectangleF](../../com.aspose.drawing/rectanglef) 값을 가장 가까운 정수값으로 반올림합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | 변환할 [RectangleF](../../com.aspose.drawing/rectanglef). |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle).
### union(Rectangle a, Rectangle b) {#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


두 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 합집합을 포함하는 [Rectangle](../../com.aspose.drawing/rectangle) 구조를 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | 합집합할 첫 번째 사각형. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | 합집합할 두 번째 사각형. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) structure that bounds the union of the two [Rectangle](../../com.aspose.drawing/rectangle) structures.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.drawing.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| x | int |  |
| y | int |  |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


두 점으로부터 새로운 직사각형을 생성합니다. 생성된 직사각형은 (left,top)이 (right,bottom)보다 작도록 정규화됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | 첫 번째 점. |
| point2 | [Point](../../com.aspose.drawing/point) | 두 번째 점. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A newly created rectangle.
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


`Rectangle` 구조의 새 인스턴스를 가져오며, `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width`, `Rectangle.Height` 값이 0으로 설정됩니다.

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### getX() {#getX--}
```
public final int getX()
```


이 Rectangle 구조의 왼쪽 위 모서리의 x 좌표를 가져옵니다.

**Returns:**
int - 이 Rectangle 구조의 왼쪽 위 모서리의 x 좌표.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


이 Rectangle 구조의 왼쪽 위 모서리의 x 좌표를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 이 Rectangle 구조의 왼쪽 위 모서리의 x 좌표. |

### getY() {#getY--}
```
public final int getY()
```


이 Rectangle 구조의 왼쪽 위 모서리의 y 좌표를 가져옵니다.

**Returns:**
int - 이 Rectangle 구조의 왼쪽 위 모서리의 y 좌표.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


이 Rectangle 구조의 왼쪽 위 모서리의 y 좌표를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 이 Rectangle 구조의 왼쪽 위 모서리의 y 좌표. |

### getLocation() {#getLocation--}
```
public final Point getLocation()
```


이 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 왼쪽 위 모서리 좌표를 가져옵니다.

**Returns:**
[Point](../../com.aspose.drawing/point) - the coordinates of the upper-left corner of this [Rectangle](../../com.aspose.drawing/rectangle) structure.
### setLocation(Point value) {#setLocation-com.aspose.drawing.Point-}
```
public final void setLocation(Point value)
```


이 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 왼쪽 위 모서리 좌표를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Point](../../com.aspose.drawing/point) | 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 왼쪽 위 모서리 좌표. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


이 Rectangle 구조의 너비를 가져옵니다.

**Returns:**
int - 이 Rectangle 구조의 너비.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


이 Rectangle 구조의 너비를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 이 Rectangle 구조의 너비. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


이 Rectangle 구조의 높이를 가져옵니다.

**Returns:**
int - 이 Rectangle 구조의 높이.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


이 Rectangle 구조의 높이를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 이 Rectangle 구조의 높이. |

### getSize() {#getSize--}
```
public final Size getSize()
```


이 [Rectangle](../../com.aspose.drawing/rectangle)의 크기를 가져옵니다.

**Returns:**
[Size](../../com.aspose.drawing/size) - the size of this [Rectangle](../../com.aspose.drawing/rectangle).
### setSize(Size value) {#setSize-com.aspose.drawing.Size-}
```
public final void setSize(Size value)
```


이 [Rectangle](../../com.aspose.drawing/rectangle)의 크기를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Size](../../com.aspose.drawing/size) | 이 [Rectangle](../../com.aspose.drawing/rectangle)의 크기. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


이 Rectangle 구조의 왼쪽 가장자리 x좌표를 가져옵니다.

**Returns:**
int - 이 Rectangle 구조의 왼쪽 가장자리의 x 좌표.
### getTop() {#getTop--}
```
public final int getTop()
```


이 Rectangle 구조의 위쪽 가장자리 y좌표를 가져옵니다.

**Returns:**
int - 이 Rectangle 구조의 위쪽 가장자리의 y 좌표.
### getRight() {#getRight--}
```
public final int getRight()
```


이 Rectangle 구조의 X와 Width 속성 값을 합한 x좌표를 가져옵니다.

**Returns:**
int - 이 Rectangle 구조의 X와 Width 속성값을 합한 x 좌표.
### getBottom() {#getBottom--}
```
public final int getBottom()
```


이 Rectangle 구조의 Y와 Height 속성 값을 합한 y좌표를 가져옵니다.

**Returns:**
int - 이 Rectangle 구조의 Y와 Height 속성값을 합한 y 좌표.
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


이 [Rectangle](../../com.aspose.drawing/rectangle)의 모든 숫자 속성이 0인지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 속성은 이 [Rectangle](../../com.aspose.drawing/rectangle)의 `Rectangle.Width`, `Rectangle.Height`, `Rectangle.X`, `Rectangle.Y` 속성이 모두 0인 경우 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


obj가 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조와 동일한 위치와 크기를 가진 [Rectangle](../../com.aspose.drawing/rectangle) 구조인지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 테스트할 객체. |

**Returns:**
boolean - 이 메서드는 obj가 [Rectangle](../../com.aspose.drawing/rectangle) 구조이며 그 X, Y, Width, Height 속성이 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 해당 속성과 동일하면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 해시 코드를 반환합니다. 해시 코드 사용에 대한 정보는 GetHashCode를 참조하십시오.

**Returns:**
int - 이 사각형의 해시 코드를 나타내는 정수입니다.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public final void intersect(Rectangle rect)
```


이 [Rectangle](../../com.aspose.drawing/rectangle)를 자체와 지정된 [Rectangle](../../com.aspose.drawing/rectangle)의 교차 영역으로 교체합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 교차할 [Rectangle](../../com.aspose.drawing/rectangle)입니다. |

### inflate(int width, int height) {#inflate-int-int-}
```
public final void inflate(int width, int height)
```


이 [Rectangle](../../com.aspose.drawing/rectangle)를 지정된 양만큼 확대합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| width | int | 이 [Rectangle](../../com.aspose.drawing/rectangle)를 수평으로 확장할 양입니다. |
| height | int | 이 [Rectangle](../../com.aspose.drawing/rectangle)를 수직으로 확장할 양입니다. |

### inflate(Size size) {#inflate-com.aspose.drawing.Size-}
```
public final void inflate(Size size)
```


이 [Rectangle](../../com.aspose.drawing/rectangle)를 지정된 양만큼 확대합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | 이 [Rectangle](../../com.aspose.drawing/rectangle)를 확장할 크기입니다. |

### contains(int x, int y) {#contains-int-int-}
```
public final boolean contains(int x, int y)
```


지정된 점이 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조에 포함되는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | int | 테스트할 점의 x 좌표입니다. |
| y | int | 테스트할 점의 y좌표. |

**Returns:**
boolean - `x`와 `y`로 정의된 점이 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조 안에 포함되어 있으면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.
### contains(Point pt) {#contains-com.aspose.drawing.Point-}
```
public final boolean contains(Point pt)
```


지정된 점이 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조에 포함되는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | 테스트할 [Point](../../com.aspose.drawing/point)입니다. |

**Returns:**
boolean - `pt`가 나타내는 점이 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조 안에 포함되어 있으면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.
### contains(Rectangle rect) {#contains-com.aspose.drawing.Rectangle-}
```
public final boolean contains(Rectangle rect)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.drawing.Rectangle-}
```
public final boolean intersectsWith(Rectangle rect)
```


`rect`와 이 사각형이 교차하는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 테스트할 직사각형. |

**Returns:**
boolean - 교차가 하나라도 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### offset(int x, int y) {#offset-int-int-}
```
public final void offset(int x, int y)
```


지정된 양만큼 이 사각형의 위치를 조정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | int | 수평 오프셋입니다. |
| y | int | 수직 오프셋입니다. |

### offset(Point pos) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point pos)
```


지정된 양만큼 이 사각형의 위치를 조정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pos | [Point](../../com.aspose.drawing/point) | 오프셋입니다. |

### equals(Rectangle other) {#equals-com.aspose.drawing.Rectangle-}
```
public final boolean equals(Rectangle other)
```


다른 [Rectangle](../../com.aspose.drawing/rectangle) 구조가 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조와 동일한 위치와 크기를 가지고 있는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.drawing/rectangle) | 테스트할 다른 사각형 |

**Returns:**
boolean - 다른 [Rectangle](../../com.aspose.drawing/rectangle) 구조와 그 X, Y, Width, Height 속성이 이 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 해당 속성과 동일하면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.drawing.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.drawing/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### normalize() {#normalize--}
```
public void normalize()
```


사각형의 너비와 높이를 양수로 만들고, 왼쪽이 오른쪽보다 작으며 위쪽이 아래쪽보다 작도록 정규화합니다.

