---
title: Size
second_title: Aspose.Drawing for Java API 참조
description: 보통 사각형의 너비와 높이를 나타내는 정수 쌍을 저장합니다.
type: docs
weight: 42
url: /ko/java/com.aspose.drawing/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Size extends Struct<Size> implements System.IEquatable<Size>, Cloneable
```

보통 사각형의 너비와 높이를 나타내는 정수 순서쌍을 저장합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point pt)](#Size-com.aspose.drawing.Point-) | 지정된 [Point](../../com.aspose.drawing/point)에서 새로운 [Size](../../com.aspose.drawing/size) 구조체 인스턴스를 초기화합니다. |
| [Size(int width, int height)](#Size-int-int-) | 지정된 차원에서 새로운 [Size](../../com.aspose.drawing/size) 구조체 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [to_SizeF(Size p)](#to-SizeF-com.aspose.drawing.Size-) | 지정된 [Size](../../com.aspose.drawing/size)을 [SizeF](../../com.aspose.drawing/sizef)로 변환합니다. |
| [op_Addition(Size sz1, Size sz2)](#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-) | 한 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이를 다른 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이에 더합니다. |
| [op_Subtraction(Size sz1, Size sz2)](#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-) | 한 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이를 다른 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이에서 뺍니다. |
| [op_Multiply(int left, Size right)](#op-Multiply-int-com.aspose.drawing.Size-) | [Size](../../com.aspose.drawing/size)를 `int`와 곱하여 [Size](../../com.aspose.drawing/size)를 생성합니다. |
| [op_Multiply(Size left, int right)](#op-Multiply-com.aspose.drawing.Size-int-) | [Size](../../com.aspose.drawing/size)를 `int`와 곱하여 [Size](../../com.aspose.drawing/size)를 생성합니다. |
| [op_Division(Size left, int right)](#op-Division-com.aspose.drawing.Size-int-) | [Size](../../com.aspose.drawing/size)를 `int`로 나누어 [Size](../../com.aspose.drawing/size)를 생성합니다. |
| [op_Multiply(float left, Size right)](#op-Multiply-float-com.aspose.drawing.Size-) | [Size](../../com.aspose.drawing/size)를 `float`와 곱하여 [SizeF](../../com.aspose.drawing/sizef)를 생성합니다. |
| [op_Multiply(Size left, float right)](#op-Multiply-com.aspose.drawing.Size-float-) | [Size](../../com.aspose.drawing/size)를 `float`와 곱하여 [SizeF](../../com.aspose.drawing/sizef)를 생성합니다. |
| [op_Division(Size left, float right)](#op-Division-com.aspose.drawing.Size-float-) | `float` 로 [Size](../../com.aspose.drawing/size)를 나누어 [SizeF](../../com.aspose.drawing/sizef)를 생성합니다. |
| [op_Equality(Size sz1, Size sz2)](#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | 두 개의 [Size](../../com.aspose.drawing/size) 구조가 같은지 테스트합니다. |
| [op_Inequality(Size sz1, Size sz2)](#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | 두 개의 [Size](../../com.aspose.drawing/size) 구조가 다른지 테스트합니다. |
| [to_Point(Size size)](#to-Point-com.aspose.drawing.Size-) | 지정된 [Size](../../com.aspose.drawing/size)을 [Point](../../com.aspose.drawing/point)로 변환합니다. |
| [add(Size sz1, Size sz2)](#add-com.aspose.drawing.Size-com.aspose.drawing.Size-) | 한 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이를 다른 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이에 더합니다. |
| [ceiling(SizeF value)](#ceiling-com.aspose.drawing.SizeF-) | 지정된 [SizeF](../../com.aspose.drawing/sizef) 구조를 [Size](../../com.aspose.drawing/size) 구조로 변환하며, [Size](../../com.aspose.drawing/size) 구조의 값을 올림하여 다음 큰 정수 값으로 만듭니다. |
| [subtract(Size sz1, Size sz2)](#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-) | 한 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이를 다른 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이에서 뺍니다. |
| [truncate(SizeF value)](#truncate-com.aspose.drawing.SizeF-) | 지정된 [SizeF](../../com.aspose.drawing/sizef) 구조를 [Size](../../com.aspose.drawing/size) 구조로 변환하며, [SizeF](../../com.aspose.drawing/sizef) 구조의 값을 내림하여 다음 작은 정수 값으로 만듭니다. |
| [round(SizeF value)](#round-com.aspose.drawing.SizeF-) | 지정된 [SizeF](../../com.aspose.drawing/sizef) 구조를 [Size](../../com.aspose.drawing/size) 구조로 변환하며, [SizeF](../../com.aspose.drawing/sizef) 구조의 값을 가장 가까운 정수로 반올림합니다. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | 이 [Size](../../com.aspose.drawing/size)의 너비와 높이가 0인지 나타내는 값을 가져옵니다. |
| [getWidth()](#getWidth--) | 이 [Size](../../com.aspose.drawing/size)의 가로 구성 요소를 가져옵니다. |
| [setWidth(int value)](#setWidth-int-) | 이 [Size](../../com.aspose.drawing/size)의 가로 구성 요소를 설정합니다. |
| [getHeight()](#getHeight--) | 이 [Size](../../com.aspose.drawing/size)의 세로 구성 요소를 가져옵니다. |
| [setHeight(int value)](#setHeight-int-) | 이 [Size](../../com.aspose.drawing/size)의 세로 구성 요소를 설정합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체가 이 [Size](../../com.aspose.drawing/size)와 동일한 차원을 가진 [Size](../../com.aspose.drawing/size)인지 테스트합니다. |
| [hashCode()](#hashCode--) | 이 [Size](../../com.aspose.drawing/size) 구조에 대한 해시 코드를 반환합니다. |
| [toString()](#toString--) |  |
| [equals(Size other)](#equals-com.aspose.drawing.Size-) | 다른 [Size](../../com.aspose.drawing/size) 구조가 이 [Size](../../com.aspose.drawing/size) 구조와 같은 크기인지 테스트합니다. |
| [CloneTo(Size that)](#CloneTo-com.aspose.drawing.Size-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point pt) {#Size-com.aspose.drawing.Point-}
```
public Size(Point pt)
```


지정된 [Point](../../com.aspose.drawing/point)에서 새로운 [Size](../../com.aspose.drawing/size) 구조체 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | 이 [Size](../../com.aspose.drawing/size)을 초기화할 [Point](../../com.aspose.drawing/point)입니다. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


지정된 차원에서 새로운 [Size](../../com.aspose.drawing/size) 구조체 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| width | int | 새 [Size](../../com.aspose.drawing/size)의 너비 구성 요소입니다. |
| height | int | 새 [Size](../../com.aspose.drawing/size)의 높이 구성 요소입니다. |

### to_SizeF(Size p) {#to-SizeF-com.aspose.drawing.Size-}
```
public static SizeF to_SizeF(Size p)
```


지정된 [Size](../../com.aspose.drawing/size)을 [SizeF](../../com.aspose.drawing/sizef)로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| p | [Size](../../com.aspose.drawing/size) | 변환할 [Size](../../com.aspose.drawing/size). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - The [SizeF](../../com.aspose.drawing/sizef) structure to which this operator converts.
### op_Addition(Size sz1, Size sz2) {#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Addition(Size sz1, Size sz2)
```


한 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이를 다른 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이에 더합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 더할 첫 번째 [Size](../../com.aspose.drawing/size). |
| sz2 | [Size](../../com.aspose.drawing/size) | 더할 두 번째 [Size](../../com.aspose.drawing/size). |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(Size sz1, Size sz2) {#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Subtraction(Size sz1, Size sz2)
```


한 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이를 다른 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이에서 뺍니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 뺄셈 연산자의 왼쪽에 있는 [Size](../../com.aspose.drawing/size) 구조입니다. |
| sz2 | [Size](../../com.aspose.drawing/size) | 뺄셈 연산자의 오른쪽에 있는 [Size](../../com.aspose.drawing/size) 구조입니다. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the subtraction operation.
### op_Multiply(int left, Size right) {#op-Multiply-int-com.aspose.drawing.Size-}
```
public static Size op_Multiply(int left, Size right)
```


[Size](../../com.aspose.drawing/size)를 `int`와 곱하여 [Size](../../com.aspose.drawing/size)를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 왼쪽 | int | `int` 형식의 곱셈 인자입니다. |
| right | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) 형식의 피곱입니다. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Multiply(Size left, int right) {#op-Multiply-com.aspose.drawing.Size-int-}
```
public static Size op_Multiply(Size left, int right)
```


[Size](../../com.aspose.drawing/size)를 `int`와 곱하여 [Size](../../com.aspose.drawing/size)를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) 형식의 피곱입니다. |
| 오른쪽 | int | `int` 형식의 곱셈 인자입니다. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Division(Size left, int right) {#op-Division-com.aspose.drawing.Size-int-}
```
public static Size op_Division(Size left, int right)
```


[Size](../../com.aspose.drawing/size)를 `int`로 나누어 [Size](../../com.aspose.drawing/size)를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | 형식이 [Size](../../com.aspose.drawing/size)인 피제수. |
| 오른쪽 | int | 형식이 `int`인 제수. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Result of type [Size](../../com.aspose.drawing/size).
### op_Multiply(float left, Size right) {#op-Multiply-float-com.aspose.drawing.Size-}
```
public static SizeF op_Multiply(float left, Size right)
```


[Size](../../com.aspose.drawing/size)를 `float`와 곱하여 [SizeF](../../com.aspose.drawing/sizef)를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 왼쪽 | float | 형식이 `float`인 곱셈인자. |
| right | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) 형식의 피곱입니다. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(Size left, float right) {#op-Multiply-com.aspose.drawing.Size-float-}
```
public static SizeF op_Multiply(Size left, float right)
```


[Size](../../com.aspose.drawing/size)를 `float`와 곱하여 [SizeF](../../com.aspose.drawing/sizef)를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) 형식의 피곱입니다. |
| 오른쪽 | float | 형식이 `float`인 곱셈인자. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(Size left, float right) {#op-Division-com.aspose.drawing.Size-float-}
```
public static SizeF op_Division(Size left, float right)
```


`float` 로 [Size](../../com.aspose.drawing/size)를 나누어 [SizeF](../../com.aspose.drawing/sizef)를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | 형식이 [Size](../../com.aspose.drawing/size)인 피제수. |
| 오른쪽 | float | 형식이 `int`인 제수. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### op_Equality(Size sz1, Size sz2) {#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Equality(Size sz1, Size sz2)
```


두 개의 [Size](../../com.aspose.drawing/size) 구조가 같은지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 동등 연산자 왼쪽에 있는 [Size](../../com.aspose.drawing/size) 구조체. |
| sz2 | [Size](../../com.aspose.drawing/size) | 동등 연산자 오른쪽에 있는 [Size](../../com.aspose.drawing/size) 구조체. |

**Returns:**
boolean - `sz1`과 `sz2`의 너비와 높이가 동일하면 true; 그렇지 않으면 false.
### op_Inequality(Size sz1, Size sz2) {#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Inequality(Size sz1, Size sz2)
```


두 개의 [Size](../../com.aspose.drawing/size) 구조가 다른지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 부등 연산자 왼쪽에 있는 [Size](../../com.aspose.drawing/size) 구조체. |
| sz2 | [Size](../../com.aspose.drawing/size) | 부등 연산자 오른쪽에 있는 [Size](../../com.aspose.drawing/size) 구조체. |

**Returns:**
boolean - `sz1`과 `sz2`가 너비 또는 높이 중 하나라도 다르면 true; `sz1`과 `sz2`가 동일하면 false.
### to_Point(Size size) {#to-Point-com.aspose.drawing.Size-}
```
public static Point to_Point(Size size)
```


지정된 [Size](../../com.aspose.drawing/size)을 [Point](../../com.aspose.drawing/point)로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | 변환할 [Size](../../com.aspose.drawing/size). |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) structure to which this operator converts.
### add(Size sz1, Size sz2) {#add-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size add(Size sz1, Size sz2)
```


한 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이를 다른 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이에 더합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 더할 첫 번째 [Size](../../com.aspose.drawing/size). |
| sz2 | [Size](../../com.aspose.drawing/size) | 더할 두 번째 [Size](../../com.aspose.drawing/size). |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### ceiling(SizeF value) {#ceiling-com.aspose.drawing.SizeF-}
```
public static Size ceiling(SizeF value)
```


지정된 [SizeF](../../com.aspose.drawing/sizef) 구조를 [Size](../../com.aspose.drawing/size) 구조로 변환하며, [Size](../../com.aspose.drawing/size) 구조의 값을 올림하여 다음 큰 정수 값으로 만듭니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | 변환할 [SizeF](../../com.aspose.drawing/sizef) 구조체. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### subtract(Size sz1, Size sz2) {#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size subtract(Size sz1, Size sz2)
```


한 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이를 다른 [Size](../../com.aspose.drawing/size) 구조체의 너비와 높이에서 뺍니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | 뺄셈 연산자의 왼쪽에 있는 [Size](../../com.aspose.drawing/size) 구조입니다. |
| sz2 | [Size](../../com.aspose.drawing/size) | 뺄셈 연산자의 오른쪽에 있는 [Size](../../com.aspose.drawing/size) 구조입니다. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) that is a result of the subtraction operation.
### truncate(SizeF value) {#truncate-com.aspose.drawing.SizeF-}
```
public static Size truncate(SizeF value)
```


지정된 [SizeF](../../com.aspose.drawing/sizef) 구조를 [Size](../../com.aspose.drawing/size) 구조로 변환하며, [SizeF](../../com.aspose.drawing/sizef) 구조의 값을 내림하여 다음 작은 정수 값으로 만듭니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | 변환할 [SizeF](../../com.aspose.drawing/sizef) 구조체. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### round(SizeF value) {#round-com.aspose.drawing.SizeF-}
```
public static Size round(SizeF value)
```


지정된 [SizeF](../../com.aspose.drawing/sizef) 구조를 [Size](../../com.aspose.drawing/size) 구조로 변환하며, [SizeF](../../com.aspose.drawing/sizef) 구조의 값을 가장 가까운 정수로 반올림합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | 변환할 [SizeF](../../com.aspose.drawing/sizef) 구조체. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.drawing/size) |  |
| obj2 | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


이 [Size](../../com.aspose.drawing/size)의 너비와 높이가 0인지 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 [Size](../../com.aspose.drawing/size)의 너비와 높이가 0인지 여부를 나타내는 값.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


이 [Size](../../com.aspose.drawing/size)의 가로 구성 요소를 가져옵니다.

**Returns:**
int - 이 [Size](../../com.aspose.drawing/size)의 가로 구성 요소.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


이 [Size](../../com.aspose.drawing/size)의 가로 구성 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 이 [Size](../../com.aspose.drawing/size)의 가로 구성 요소. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


이 [Size](../../com.aspose.drawing/size)의 세로 구성 요소를 가져옵니다.

**Returns:**
int - 이 [Size](../../com.aspose.drawing/size)의 세로 구성 요소.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


이 [Size](../../com.aspose.drawing/size)의 세로 구성 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 이 [Size](../../com.aspose.drawing/size)의 세로 구성 요소. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 객체가 이 [Size](../../com.aspose.drawing/size)와 동일한 차원을 가진 [Size](../../com.aspose.drawing/size)인지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 테스트할 객체. |

**Returns:**
boolean - `obj`가 [Size](../../com.aspose.drawing/size)이며 이 [Size](../../com.aspose.drawing/size)와 동일한 너비와 높이를 가지면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 [Size](../../com.aspose.drawing/size) 구조에 대한 해시 코드를 반환합니다.

**Returns:**
int - 이 [Size](../../com.aspose.drawing/size) 구조체에 대한 해시 값을 지정하는 정수값.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Size other) {#equals-com.aspose.drawing.Size-}
```
public final boolean equals(Size other)
```


다른 [Size](../../com.aspose.drawing/size) 구조가 이 [Size](../../com.aspose.drawing/size) 구조와 같은 크기인지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [Size](../../com.aspose.drawing/size) | 테스트할 다른 크기 |

**Returns:**
boolean - 다른 [Size](../../com.aspose.drawing/size) 구조체와 그 Width 및 Height 속성이 이 [Size](../../com.aspose.drawing/size) 구조체의 해당 속성과 동일하면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.
### CloneTo(Size that) {#CloneTo-com.aspose.drawing.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| that | [Size](../../com.aspose.drawing/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### clone() {#clone--}
```
public Size clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
