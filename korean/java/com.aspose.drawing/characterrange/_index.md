---
title: CharacterRange
second_title: Aspose.Drawing for Java API 참조
description: 문자열 내 문자 위치 범위를 지정합니다.
type: docs
weight: 13
url: /ko/java/com.aspose.drawing/characterrange/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class CharacterRange extends Struct<CharacterRange> implements Cloneable
```

문자열 내 문자 위치 범위를 지정합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CharacterRange()](#CharacterRange--) |  |
| [CharacterRange(int first, int length)](#CharacterRange-int-int-) | [CharacterRange](../../com.aspose.drawing/characterrange) 구조체의 새 인스턴스를 초기화하고, 문자열 내 문자 위치 범위를 지정합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFirst()](#getFirst--) | 이 [CharacterRange](../../com.aspose.drawing/characterrange)의 첫 번째 문자의 문자열 내 위치를 가져오거나 설정합니다. |
| [setFirst(int value)](#setFirst-int-) | 이 [CharacterRange](../../com.aspose.drawing/characterrange)의 첫 번째 문자의 문자열 내 위치를 가져오거나 설정합니다. |
| [getLength()](#getLength--) | 이 [CharacterRange](../../com.aspose.drawing/characterrange) 내 위치 수를 가져오거나 설정합니다. |
| [setLength(int value)](#setLength-int-) | 이 [CharacterRange](../../com.aspose.drawing/characterrange) 내 위치 수를 가져오거나 설정합니다. |
| [op_Equality(CharacterRange cr1, CharacterRange cr2)](#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | 두 [CharacterRange](../../com.aspose.drawing/characterrange) 객체를 비교합니다. |
| [op_Inequality(CharacterRange cr1, CharacterRange cr2)](#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | 두 [CharacterRange](../../com.aspose.drawing/characterrange) 객체를 비교합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 객체가 지정된 객체와 동등한지 여부를 나타내는 값을 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [CloneTo(CharacterRange that)](#CloneTo-com.aspose.drawing.CharacterRange-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### CharacterRange() {#CharacterRange--}
```
public CharacterRange()
```


### CharacterRange(int first, int length) {#CharacterRange-int-int-}
```
public CharacterRange(int first, int length)
```


[CharacterRange](../../com.aspose.drawing/characterrange) 구조체의 새 인스턴스를 초기화하고, 문자열 내 문자 위치 범위를 지정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| first | int | 범위 내 첫 번째 문자의 위치입니다. 예를 들어, First가 0으로 설정되면 범위의 첫 번째 위치는 문자열의 위치 0이 됩니다. |
| length | int | 범위 내 위치 수입니다. |

### getFirst() {#getFirst--}
```
public final int getFirst()
```


이 [CharacterRange](../../com.aspose.drawing/characterrange)의 첫 번째 문자의 문자열 내 위치를 가져오거나 설정합니다.

값: 이 [CharacterRange](../../com.aspose.drawing/characterrange)의 첫 번째 위치.

**Returns:**
int
### setFirst(int value) {#setFirst-int-}
```
public final void setFirst(int value)
```


이 [CharacterRange](../../com.aspose.drawing/characterrange)의 첫 번째 문자의 문자열 내 위치를 가져오거나 설정합니다.

값: 이 [CharacterRange](../../com.aspose.drawing/characterrange)의 첫 번째 위치.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getLength() {#getLength--}
```
public final int getLength()
```


이 [CharacterRange](../../com.aspose.drawing/characterrange) 내 위치 수를 가져오거나 설정합니다.

값: 이 [CharacterRange](../../com.aspose.drawing/characterrange) 내 위치 수.

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


이 [CharacterRange](../../com.aspose.drawing/characterrange) 내 위치 수를 가져오거나 설정합니다.

값: 이 [CharacterRange](../../com.aspose.drawing/characterrange) 내 위치 수.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### op_Equality(CharacterRange cr1, CharacterRange cr2) {#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Equality(CharacterRange cr1, CharacterRange cr2)
```


두 [CharacterRange](../../com.aspose.drawing/characterrange) 객체를 비교합니다. 두 [CharacterRange](../../com.aspose.drawing/characterrange) 객체의 First와 Length 값이 동일한지 여부를 나타내는 값을 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | 동등성을 비교하기 위한 [CharacterRange](../../com.aspose.drawing/characterrange)입니다. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | 동등성을 비교하기 위한 [CharacterRange](../../com.aspose.drawing/characterrange)입니다. |

**Returns:**
boolean - 두 CharacterRange 객체가 동일한 First와 Length 값을 갖는 경우 `true`를, 그렇지 않으면 `false`를 나타냅니다.
### op_Inequality(CharacterRange cr1, CharacterRange cr2) {#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Inequality(CharacterRange cr1, CharacterRange cr2)
```


두 [CharacterRange](../../com.aspose.drawing/characterrange) 객체를 비교합니다. 두 [CharacterRange](../../com.aspose.drawing/characterrange) 객체의 First 또는 Length 값이 동일하지 않은지 여부를 나타내는 값을 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | 불일치를 비교하기 위한 [CharacterRange](../../com.aspose.drawing/characterrange)입니다. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | 불일치를 비교하기 위한 [CharacterRange](../../com.aspose.drawing/characterrange)입니다. |

**Returns:**
boolean - 두 CharacterRange 객체의 First 또는 Length 값 중 하나라도 다른 경우 `true`를, 그렇지 않으면 `false`를 나타냅니다.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 객체가 지정된 객체와 동등한지 여부를 나타내는 값을 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 동등성을 비교할 객체입니다.. |

**Returns:**
boolean - `true`는 지정된 객체가 이 인스턴스와 동일한 First 및 Length 값을 가진 인스턴스임을 나타내며, 그렇지 않으면 `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

**Returns:**
int - 이 인스턴스의 해시 코드인 32비트 부호 있는 정수.
### CloneTo(CharacterRange that) {#CloneTo-com.aspose.drawing.CharacterRange-}
```
public void CloneTo(CharacterRange that)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| that | [CharacterRange](../../com.aspose.drawing/characterrange) |  |

### Clone() {#Clone--}
```
public CharacterRange Clone()
```




**Returns:**
[CharacterRange](../../com.aspose.drawing/characterrange)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
