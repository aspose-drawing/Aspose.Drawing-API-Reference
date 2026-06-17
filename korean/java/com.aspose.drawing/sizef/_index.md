---
title: SizeF
second_title: Aspose.Drawing for Java API 참조
description: 보통 사각형의 너비와 높이를 나타내는 부동 소수점 숫자 쌍을 저장합니다.
type: docs
weight: 43
url: /ko/java/com.aspose.drawing/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class SizeF extends Struct<SizeF> implements System.IEquatable<SizeF>, Cloneable
```

보통 사각형의 너비와 높이를 나타내는 부동소수점 숫자 순서쌍을 저장합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(float width, float height)](#SizeF-float-float-) | 지정된 차원으로 SizeF 구조의 새 인스턴스를 초기화합니다. |
| [SizeF(PointF pt)](#SizeF-com.aspose.drawing.PointF-) | [SizeF](../../com.aspose.drawing/sizef) 구조체의 새 인스턴스를 초기화합니다. |
| [SizeF(SizeF size)](#SizeF-com.aspose.drawing.SizeF-) | [SizeF](../../com.aspose.drawing/sizef) 구조체의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [op_Equality(SizeF sz1, SizeF sz2)](#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | 두 [SizeF](../../com.aspose.drawing/sizef) 구조가 같은지 테스트합니다. |
| [op_Inequality(SizeF sz1, SizeF sz2)](#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | 두 [SizeF](../../com.aspose.drawing/sizef) 구조가 다른지 테스트합니다. |
| [add(SizeF sz1, SizeF sz2)](#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | 한 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이를 다른 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이에 더합니다. |
| [subtract(SizeF sz1, SizeF sz2)](#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | 한 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이를 다른 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이에서 뺍니다. |
| [op_Addition(SizeF sz1, SizeF sz2)](#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | 한 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이를 다른 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이에 더합니다. |
| [op_Subtraction(SizeF sz1, SizeF sz2)](#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | 한 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이를 다른 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이에서 뺍니다. |
| [op_Multiply(float left, SizeF right)](#op-Multiply-float-com.aspose.drawing.SizeF-) | `float` 로 [SizeF](../../com.aspose.drawing/sizef)를 곱하여 [SizeF](../../com.aspose.drawing/sizef)를 생성합니다. |
| [op_Multiply(SizeF left, float right)](#op-Multiply-com.aspose.drawing.SizeF-float-) | `float` 로 [SizeF](../../com.aspose.drawing/sizef)를 곱하여 [SizeF](../../com.aspose.drawing/sizef)를 생성합니다. |
| [op_Division(SizeF left, float right)](#op-Division-com.aspose.drawing.SizeF-float-) | `float` 로 [SizeF](../../com.aspose.drawing/sizef)를 나누어 [SizeF](../../com.aspose.drawing/sizef)를 생성합니다. |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | 이 [SizeF](../../com.aspose.drawing/sizef) 구조체가 너비와 높이가 0인지 여부를 나타내는 값을 가져옵니다. |
| [getWidth()](#getWidth--) | 이 SizeF 구조체의 가로 구성 요소를 가져옵니다. |
| [setWidth(float value)](#setWidth-float-) | 이 SizeF 구조체의 가로 구성 요소를 설정합니다. |
| [getHeight()](#getHeight--) | 이 SizeF 구조체의 세로 구성 요소를 가져옵니다. |
| [setHeight(float value)](#setHeight-float-) | 이 SizeF 구조체의 세로 구성 요소를 설정합니다. |
| [hashCode()](#hashCode--) | 이 [SizeF](../../com.aspose.drawing/sizef) 구조체에 대한 해시 코드를 반환합니다. |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체가 이 [SizeF](../../com.aspose.drawing/sizef) 구조체와 동일한 차원을 가진 [SizeF](../../com.aspose.drawing/sizef) 구조체인지 테스트합니다. |
| [toSize()](#toSize--) | [SizeF](../../com.aspose.drawing/sizef) 구조체를 [Size](../../com.aspose.drawing/size) 구조체로 변환합니다. |
| [toPointF()](#toPointF--) | [SizeF](../../com.aspose.drawing/sizef) 구조체를 [PointF](../../com.aspose.drawing/pointf) 구조체로 변환합니다. |
| [equals(SizeF other)](#equals-com.aspose.drawing.SizeF-) | 다른 [SizeF](../../com.aspose.drawing/sizef) 구조체가 이 [SizeF](../../com.aspose.drawing/sizef) 구조체와 동일한 크기인지 테스트합니다. |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.drawing.SizeF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


지정된 차원으로 SizeF 구조의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 너비 | float | 새 SizeF 구조체의 너비 구성 요소. |
| 높이 | float | 새 SizeF 구조체의 높이 구성 요소. |

### SizeF(PointF pt) {#SizeF-com.aspose.drawing.PointF-}
```
public SizeF(PointF pt)
```


[SizeF](../../com.aspose.drawing/sizef) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | 이 [SizeF](../../com.aspose.drawing/sizef) 구조체를 초기화할 [PointF](../../com.aspose.drawing/pointf) 구조체. |

### SizeF(SizeF size) {#SizeF-com.aspose.drawing.SizeF-}
```
public SizeF(SizeF size)
```


[SizeF](../../com.aspose.drawing/sizef) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | 새 [SizeF](../../com.aspose.drawing/sizef) 구조체를 만들기 위한 원본 [SizeF](../../com.aspose.drawing/sizef) 구조체. |

### op_Equality(SizeF sz1, SizeF sz2) {#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Equality(SizeF sz1, SizeF sz2)
```


두 [SizeF](../../com.aspose.drawing/sizef) 구조가 같은지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 동등 연산자 왼쪽에 있는 [SizeF](../../com.aspose.drawing/sizef) 구조체. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 동등 연산자 오른쪽에 있는 [SizeF](../../com.aspose.drawing/sizef) 구조체. |

**Returns:**
boolean - `sz1`과 `sz2`의 너비와 높이가 동일하면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### op_Inequality(SizeF sz1, SizeF sz2) {#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Inequality(SizeF sz1, SizeF sz2)
```


두 [SizeF](../../com.aspose.drawing/sizef) 구조가 다른지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 부등 연산자 왼쪽에 있는 [SizeF](../../com.aspose.drawing/sizef) 구조체. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 부등 연산자 오른쪽에 있는 [SizeF](../../com.aspose.drawing/sizef) 구조체. |

**Returns:**
boolean - `sz1`과 `sz2`가 너비 또는 높이 중 하나라도 다르면 true를 반환하고, `sz1`과 `sz2`가 동일하면 false를 반환합니다.
### add(SizeF sz1, SizeF sz2) {#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF add(SizeF sz1, SizeF sz2)
```


한 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이를 다른 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이에 더합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 첫 번째로 더할 [SizeF](../../com.aspose.drawing/sizef) 구조체. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 두 번째로 더할 [SizeF](../../com.aspose.drawing/sizef) 구조체. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is the result of the addition operation.
### subtract(SizeF sz1, SizeF sz2) {#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF subtract(SizeF sz1, SizeF sz2)
```


한 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이를 다른 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이에서 뺍니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 뺄셈 연산자 왼쪽에 있는 [SizeF](../../com.aspose.drawing/sizef) 구조체. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 뺄셈 연산자의 오른쪽에 있는 [SizeF](../../com.aspose.drawing/sizef) 구조. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is a result of the subtraction operation.
### op_Addition(SizeF sz1, SizeF sz2) {#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Addition(SizeF sz1, SizeF sz2)
```


한 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이를 다른 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이에 더합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 첫 번째로 더할 [SizeF](../../com.aspose.drawing/sizef) 구조체. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 두 번째로 더할 [SizeF](../../com.aspose.drawing/sizef) 구조체. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(SizeF sz1, SizeF sz2) {#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Subtraction(SizeF sz1, SizeF sz2)
```


한 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이를 다른 [SizeF](../../com.aspose.drawing/sizef) 구조의 너비와 높이에서 뺍니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | 뺄셈 연산자 왼쪽에 있는 [SizeF](../../com.aspose.drawing/sizef) 구조체. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | 뺄셈 연산자의 오른쪽에 있는 [SizeF](../../com.aspose.drawing/sizef) 구조. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that is the result of the subtraction operation.
### op_Multiply(float left, SizeF right) {#op-Multiply-float-com.aspose.drawing.SizeF-}
```
public static SizeF op_Multiply(float left, SizeF right)
```


`float` 로 [SizeF](../../com.aspose.drawing/sizef)를 곱하여 [SizeF](../../com.aspose.drawing/sizef)를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 왼쪽 | float | 형식이 `float`인 곱셈인자. |
| right | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef) 형식의 피승수. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(SizeF left, float right) {#op-Multiply-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Multiply(SizeF left, float right)
```


`float` 로 [SizeF](../../com.aspose.drawing/sizef)를 곱하여 [SizeF](../../com.aspose.drawing/sizef)를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef) 형식의 피승수. |
| 오른쪽 | float | 형식이 `float`인 곱셈인자. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(SizeF left, float right) {#op-Division-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Division(SizeF left, float right)
```


`float` 로 [SizeF](../../com.aspose.drawing/sizef)를 나누어 [SizeF](../../com.aspose.drawing/sizef)를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef) 형식의 피제수. |
| 오른쪽 | float | 형식이 `int`인 제수. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### to_PointF(SizeF size) {#to-PointF-com.aspose.drawing.SizeF-}
```
public static PointF to_PointF(SizeF size)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.drawing/sizef) |  |
| obj2 | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


이 [SizeF](../../com.aspose.drawing/sizef) 구조체가 너비와 높이가 0인지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 [SizeF](../../com.aspose.drawing/sizef) 구조가 너비와 높이가 0인지 여부를 나타내는 값.
### getWidth() {#getWidth--}
```
public final float getWidth()
```


이 SizeF 구조체의 가로 구성 요소를 가져옵니다.

**Returns:**
float - 이 SizeF 구조의 수평 성분.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


이 SizeF 구조체의 가로 구성 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 SizeF 구조의 수평 성분. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


이 SizeF 구조체의 세로 구성 요소를 가져옵니다.

**Returns:**
float - 이 SizeF 구조의 수직 성분.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


이 SizeF 구조체의 세로 구성 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 SizeF 구조의 수직 성분. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


이 [SizeF](../../com.aspose.drawing/sizef) 구조체에 대한 해시 코드를 반환합니다.

**Returns:**
int - 이 [SizeF](../../com.aspose.drawing/sizef) 구조에 대한 해시 값을 지정하는 정수 값.
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


지정된 객체가 이 [SizeF](../../com.aspose.drawing/sizef) 구조체와 동일한 차원을 가진 [SizeF](../../com.aspose.drawing/sizef) 구조체인지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 테스트할 객체. |

**Returns:**
boolean - obj가 [SizeF](../../com.aspose.drawing/sizef)이며 이 SizeF와 동일한 너비와 높이를 가지고 있으면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.
### toSize() {#toSize--}
```
public final Size toSize()
```


[SizeF](../../com.aspose.drawing/sizef) 구조체를 [Size](../../com.aspose.drawing/size) 구조체로 변환합니다.

**Returns:**
[Size](../../com.aspose.drawing/size) - Returns a [Size](../../com.aspose.drawing/size) structure.
### toPointF() {#toPointF--}
```
public final PointF toPointF()
```


[SizeF](../../com.aspose.drawing/sizef) 구조체를 [PointF](../../com.aspose.drawing/pointf) 구조체로 변환합니다.

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - Returns a [PointF](../../com.aspose.drawing/pointf) structure.
### equals(SizeF other) {#equals-com.aspose.drawing.SizeF-}
```
public final boolean equals(SizeF other)
```


다른 [SizeF](../../com.aspose.drawing/sizef) 구조체가 이 [SizeF](../../com.aspose.drawing/sizef) 구조체와 동일한 크기인지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [SizeF](../../com.aspose.drawing/sizef) | 테스트할 다른 크기 |

**Returns:**
boolean - other [SizeF](../../com.aspose.drawing/sizef) 구조와 그 Width 및 Height 속성이 이 [SizeF](../../com.aspose.drawing/sizef) 구조의 해당 속성과 같으면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.
### CloneTo(SizeF that) {#CloneTo-com.aspose.drawing.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.drawing/sizef) |  |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
