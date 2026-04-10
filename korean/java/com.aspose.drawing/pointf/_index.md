---
title: PointF
second_title: Aspose.Drawing for Java API 참조
description: 2차원 평면에서 점을 정의하는 부동소수점 x 및 y 좌표의 순서쌍을 나타냅니다.
type: docs
weight: 37
url: /ko/java/com.aspose.drawing/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class PointF extends Struct<PointF> implements System.IEquatable<PointF>, Cloneable
```

2차원 평면에서 점을 정의하는 부동소수점 x 및 y 좌표의 순서쌍을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | 지정된 좌표를 사용하여 PointF 구조체의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [op_Addition(PointF pt, Size sz)](#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [op_Subtraction(PointF pt, Size sz)](#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [op_Addition(PointF pt, SizeF sz)](#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [op_Subtraction(PointF pt, SizeF sz)](#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [op_Equality(PointF left, PointF right)](#op-Equality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | 두 개의 [PointF](../../com.aspose.drawing/pointf) 구조체를 비교합니다. |
| [op_Inequality(PointF left, PointF right)](#op-Inequality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | 지정된 점들의 좌표가 서로 다른지 여부를 결정합니다. |
| [add(PointF orig, Size size)](#add-com.aspose.drawing.PointF-com.aspose.drawing.Size-) | 주어진 [PointF](../../com.aspose.drawing/pointf)를 지정된 [SizeF](../../com.aspose.drawing/sizef)만큼 변환합니다. |
| [subtract(PointF pt, Size sz)](#subtract-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [add(PointF orig, SizeF sizeF)](#add-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | 주어진 [PointF](../../com.aspose.drawing/pointf)를 지정된 [SizeF](../../com.aspose.drawing/sizef)만큼 변환합니다. |
| [subtract(PointF pt, SizeF sz)](#subtract-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | 이 [PointF](../../com.aspose.drawing/pointf)가 비어 있는지 여부를 나타내는 값을 가져옵니다. |
| [getX()](#getX--) | 이 PointF의 x 좌표를 가져옵니다. |
| [setX(float value)](#setX-float-) | 이 PointF의 x 좌표를 설정합니다. |
| [getY()](#getY--) | 이 PointF의 y 좌표를 가져옵니다. |
| [setY(float value)](#setY-float-) | 이 PointF의 y 좌표를 설정합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 [PointF](../../com.aspose.drawing/pointf)가 지정된 객체와 동일한 좌표를 포함하는지 여부를 지정합니다. |
| [hashCode()](#hashCode--) | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| [toString()](#toString--) |  |
| [equals(PointF other)](#equals-com.aspose.drawing.PointF-) | 다른 [PointF](../../com.aspose.drawing/pointf) 구조체가 이 [PointF](../../com.aspose.drawing/pointf) 구조체와 동일한 위치를 갖는지 테스트합니다. |
| [CloneTo(PointF that)](#CloneTo-com.aspose.drawing.PointF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


지정된 좌표를 사용하여 PointF 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 점의 수평 위치입니다. |
| y | float | 점의 수직 위치입니다. |

### op_Addition(PointF pt, Size sz) {#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF op_Addition(PointF pt, Size sz)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Subtraction(PointF pt, Size sz) {#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF op_Subtraction(PointF pt, Size sz)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Addition(PointF pt, SizeF sz) {#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF op_Addition(PointF pt, SizeF sz)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Subtraction(PointF pt, SizeF sz) {#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF op_Subtraction(PointF pt, SizeF sz)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Equality(PointF left, PointF right) {#op-Equality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean op_Equality(PointF left, PointF right)
```


두 개의 [PointF](../../com.aspose.drawing/pointf) 구조체를 비교합니다. 결과는 두 [PointF](../../com.aspose.drawing/pointf) 구조체의 `PointF.X` 및 `PointF.Y` 속성 값이 동일한지 여부를 지정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [PointF](../../com.aspose.drawing/pointf) | 비교할 첫 번째 [PointF](../../com.aspose.drawing/pointf)입니다. |
| right | [PointF](../../com.aspose.drawing/pointf) | 비교할 두 번째 [PointF](../../com.aspose.drawing/pointf)입니다. |

**Returns:**
boolean - 왼쪽 및 오른쪽 [PointF](../../com.aspose.drawing/pointf) 구조체의 `PointF.X`와 `PointF.Y` 값이 동일하면 true; 그렇지 않으면 false.
### op_Inequality(PointF left, PointF right) {#op-Inequality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean op_Inequality(PointF left, PointF right)
```


지정된 점들의 좌표가 서로 다른지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [PointF](../../com.aspose.drawing/pointf) | 비교할 첫 번째 [PointF](../../com.aspose.drawing/pointf)입니다. |
| right | [PointF](../../com.aspose.drawing/pointf) | 비교할 두 번째 [PointF](../../com.aspose.drawing/pointf)입니다. |

**Returns:**
boolean - `left`와 `right`의 `PointF.X` 및 `PointF.Y` 값이 서로 다름을 나타내면 true; 그렇지 않으면 false.
### add(PointF orig, Size size) {#add-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF add(PointF orig, Size size)
```


주어진 [PointF](../../com.aspose.drawing/pointf)를 지정된 [SizeF](../../com.aspose.drawing/sizef)만큼 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| orig | [PointF](../../com.aspose.drawing/pointf) | 변환할 [PointF](../../com.aspose.drawing/pointf)입니다. |
| size | [Size](../../com.aspose.drawing/size) | `orig`의 좌표에 더할 숫자를 지정하는 [Size](../../com.aspose.drawing/size)입니다. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The translated [PointF](../../com.aspose.drawing/pointf).
### subtract(PointF pt, Size sz) {#subtract-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF subtract(PointF pt, Size sz)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### add(PointF orig, SizeF sizeF) {#add-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF add(PointF orig, SizeF sizeF)
```


주어진 [PointF](../../com.aspose.drawing/pointf)를 지정된 [SizeF](../../com.aspose.drawing/sizef)만큼 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| orig | [PointF](../../com.aspose.drawing/pointf) | 변환할 [PointF](../../com.aspose.drawing/pointf)입니다. |
| sizeF | [SizeF](../../com.aspose.drawing/sizef) | `orig`의 좌표에 더할 숫자를 지정하는 [SizeF](../../com.aspose.drawing/sizef)입니다. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The translated [PointF](../../com.aspose.drawing/pointf).
### subtract(PointF pt, SizeF sz) {#subtract-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF subtract(PointF pt, SizeF sz)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.drawing/pointf) |  |
| obj2 | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```




**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


이 [PointF](../../com.aspose.drawing/pointf)가 비어 있는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 [PointF](../../com.aspose.drawing/pointf)가 비어 있는지 여부를 나타내는 값입니다.
### getX() {#getX--}
```
public final float getX()
```


이 PointF의 x 좌표를 가져옵니다.

**Returns:**
float - 이 PointF의 x 좌표입니다.
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


이 PointF의 x 좌표를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 PointF의 x 좌표. |

### getY() {#getY--}
```
public final float getY()
```


이 PointF의 y 좌표를 가져옵니다.

**Returns:**
float - 이 PointF의 y 좌표입니다.
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


이 PointF의 y 좌표를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 PointF의 y 좌표. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 [PointF](../../com.aspose.drawing/pointf)가 지정된 객체와 동일한 좌표를 포함하는지 여부를 지정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 테스트할 객체. |

**Returns:**
boolean - `obj`가 [PointF](../../com.aspose.drawing/pointf)이며 이 [Point](../../com.aspose.drawing/point)와 동일한 좌표를 가지고 있으면 true를 반환합니다.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스에 대한 해시 코드를 반환합니다.

**Returns:**
int - 이 인스턴스에 대한 해시 코드로, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용하기에 적합합니다.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(PointF other) {#equals-com.aspose.drawing.PointF-}
```
public final boolean equals(PointF other)
```


다른 [PointF](../../com.aspose.drawing/pointf) 구조체가 이 [PointF](../../com.aspose.drawing/pointf) 구조체와 동일한 위치를 갖는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [PointF](../../com.aspose.drawing/pointf) | 테스트할 다른 점 |

**Returns:**
boolean - 다른 [PointF](../../com.aspose.drawing/pointf) 구조와 그 X 및 Y 속성이 이 [PointF](../../com.aspose.drawing/pointf) 구조의 해당 속성과 동일하면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.
### CloneTo(PointF that) {#CloneTo-com.aspose.drawing.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| that | [PointF](../../com.aspose.drawing/pointf) |  |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
