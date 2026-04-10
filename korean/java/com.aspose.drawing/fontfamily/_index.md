---
title: FontFamily
second_title: Aspose.Drawing for Java API 참조
description: 유사한 기본 디자인과 스타일의 일부 변형을 가진 타입 페이스 그룹을 정의합니다.
type: docs
weight: 24
url: /ko/java/com.aspose.drawing/fontfamily/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class FontFamily implements System.IDisposable
```

유사한 기본 디자인과 스타일의 일부 변형을 가진 글꼴 그룹을 정의합니다. 이 클래스는 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontFamily(String name)](#FontFamily-java.lang.String-) | 지정된 이름으로 [FontFamily](../../com.aspose.drawing/fontfamily) 클래스의 새 인스턴스를 초기화합니다. |
| [FontFamily(String name, FontCollection fontCollection)](#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-) | [FontFamily](../../com.aspose.drawing/fontfamily) 클래스의 새 인스턴스를 초기화합니다. |
| [FontFamily(String name, FontFamilyDefinition definition)](#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-) | [FontFamily](../../com.aspose.drawing/fontfamily) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFamilies()](#getFamilies--) | 현재 그래픽 컨텍스트와 연결된 모든 [FontFamily](../../com.aspose.drawing/fontfamily) 객체를 포함하는 배열을 가져옵니다. |
| [getGenericSansSerif()](#getGenericSansSerif--) | 일반적인 산세리프 [FontFamily](../../com.aspose.drawing/fontfamily) 객체를 가져옵니다. |
| [getGenericSerif()](#getGenericSerif--) | 일반적인 세리프 [FontFamily](../../com.aspose.drawing/fontfamily) 객체를 가져옵니다. |
| [getGenericMonospace()](#getGenericMonospace--) | 일반적인 고정폭 [FontFamily](../../com.aspose.drawing/fontfamily) 객체를 가져옵니다. |
| [getName()](#getName--) | 이 [FontFamily](../../com.aspose.drawing/fontfamily)의 이름을 가져옵니다. |
| [dispose()](#dispose--) | 이 [FontFamily](../../com.aspose.drawing/fontfamily)에서 사용된 모든 리소스를 해제합니다. |
| [getName(int language)](#getName-int-) | 지정된 언어로 이 [FontFamily](../../com.aspose.drawing/fontfamily)의 이름을 반환합니다. |
| [isStyleAvailable(int style)](#isStyleAvailable-int-) | 지정된 [FontStyle](../../com.aspose.drawing/fontstyle) 열거형이 사용 가능한지 나타냅니다. |
| [getEmHeight(int style)](#getEmHeight-int-) | 지정된 스타일에 대한 EM 사각형의 높이를 글꼴 디자인 단위로 가져옵니다. |
| [getCellAscent(int style)](#getCellAscent-int-) | 지정된 스타일의 [FontFamily](../../com.aspose.drawing/fontfamily) 셀 상승값을 디자인 단위로 반환합니다. |
| [getCellDescent(int style)](#getCellDescent-int-) | 지정된 스타일의 [FontFamily](../../com.aspose.drawing/fontfamily) 셀 하강값을 디자인 단위로 반환합니다. |
| [hashCode()](#hashCode--) | 이 [FontFamily](../../com.aspose.drawing/fontfamily)의 해시 코드를 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체가 [FontFamily](../../com.aspose.drawing/fontfamily)이며 이 [FontFamily](../../com.aspose.drawing/fontfamily)와 동일한지 여부를 나타냅니다. |
| [getLineSpacing(int style)](#getLineSpacing-int-) | 지정된 스타일의 [FontFamily](../../com.aspose.drawing/fontfamily) 줄 간격을 디자인 단위로 반환합니다. |
### FontFamily(String name) {#FontFamily-java.lang.String-}
```
public FontFamily(String name)
```


지정된 이름으로 [FontFamily](../../com.aspose.drawing/fontfamily) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 새 [FontFamily](../../com.aspose.drawing/fontfamily)의 이름입니다. |

### FontFamily(String name, FontCollection fontCollection) {#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-}
```
public FontFamily(String name, FontCollection fontCollection)
```


[FontFamily](../../com.aspose.drawing/fontfamily) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 글꼴 패밀리의 이름입니다. |
| fontCollection | [FontCollection](../../com.aspose.drawing/fontcollection) | 글꼴 컬렉션입니다. |

### FontFamily(String name, FontFamilyDefinition definition) {#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-}
```
public FontFamily(String name, FontFamilyDefinition definition)
```


[FontFamily](../../com.aspose.drawing/fontfamily) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 글꼴 패밀리의 이름입니다. |
| definition | [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) | 정의입니다. |

### getFamilies() {#getFamilies--}
```
public static FontFamily[] getFamilies()
```


현재 그래픽 컨텍스트와 연결된 모든 [FontFamily](../../com.aspose.drawing/fontfamily) 객체를 포함하는 배열을 가져옵니다.

**Returns:**
com.aspose.drawing.FontFamily[] - 현재 그래픽 컨텍스트와 연결된 [FontFamily](../../com.aspose.drawing/fontfamily) 객체 배열입니다.
### getGenericSansSerif() {#getGenericSansSerif--}
```
public static FontFamily getGenericSansSerif()
```


일반적인 산세리프 [FontFamily](../../com.aspose.drawing/fontfamily) 객체를 가져옵니다.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) object that represents a generic sans serif font.
### getGenericSerif() {#getGenericSerif--}
```
public static FontFamily getGenericSerif()
```


일반적인 세리프 [FontFamily](../../com.aspose.drawing/fontfamily) 객체를 가져옵니다.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic serif font.
### getGenericMonospace() {#getGenericMonospace--}
```
public static FontFamily getGenericMonospace()
```


일반적인 고정폭 [FontFamily](../../com.aspose.drawing/fontfamily) 객체를 가져옵니다.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic monospace font.
### getName() {#getName--}
```
public String getName()
```


이 [FontFamily](../../com.aspose.drawing/fontfamily)의 이름을 가져옵니다.

**Returns:**
java.lang.String - 이 [FontFamily](../../com.aspose.drawing/fontfamily)의 이름을 나타내는 문자열입니다.
### dispose() {#dispose--}
```
public void dispose()
```


이 [FontFamily](../../com.aspose.drawing/fontfamily)에서 사용된 모든 리소스를 해제합니다.

### getName(int language) {#getName-int-}
```
public String getName(int language)
```


지정된 언어로 이 [FontFamily](../../com.aspose.drawing/fontfamily)의 이름을 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 언어 | int | 이름이 반환되는 언어입니다. |

**Returns:**
java.lang.String - 지정된 언어로 이 [FontFamily](../../com.aspose.drawing/fontfamily)의 이름을 나타내는 문자열입니다.
### isStyleAvailable(int style) {#isStyleAvailable-int-}
```
public boolean isStyleAvailable(int style)
```


지정된 [FontStyle](../../com.aspose.drawing/fontstyle) 열거형이 사용 가능한지 나타냅니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| style | int | 테스트할 [FontStyle](../../com.aspose.drawing/fontstyle)입니다. |

**Returns:**
boolean - 지정된 [FontStyle](../../com.aspose.drawing/fontstyle)이 사용 가능한 경우 true; 그렇지 않으면 false.
### getEmHeight(int style) {#getEmHeight-int-}
```
public int getEmHeight(int style)
```


지정된 스타일에 대한 EM 사각형의 높이를 글꼴 디자인 단위로 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| style | int | EM 높이를 가져올 [FontStyle](../../com.aspose.drawing/fontstyle)입니다. |

**Returns:**
int - EM 사각형의 높이입니다.
### getCellAscent(int style) {#getCellAscent-int-}
```
public int getCellAscent(int style)
```


지정된 스타일의 [FontFamily](../../com.aspose.drawing/fontfamily) 셀 상승값을 디자인 단위로 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| style | int | 글꼴에 대한 스타일 정보를 포함하는 [FontStyle](../../com.aspose.drawing/fontstyle)입니다. |

**Returns:**
int - 지정된 [FontStyle](../../com.aspose.drawing/fontstyle)을 사용하는 이 [FontFamily](../../com.aspose.drawing/fontfamily)의 셀 상승값입니다.
### getCellDescent(int style) {#getCellDescent-int-}
```
public int getCellDescent(int style)
```


지정된 스타일의 [FontFamily](../../com.aspose.drawing/fontfamily) 셀 하강값을 디자인 단위로 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| style | int | 글꼴에 대한 스타일 정보를 포함하는 [FontStyle](../../com.aspose.drawing/fontstyle)입니다. |

**Returns:**
int - 지정된 [FontStyle](../../com.aspose.drawing/fontstyle)을 사용하는 이 [FontFamily](../../com.aspose.drawing/fontfamily)의 셀 하강 메트릭입니다.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 [FontFamily](../../com.aspose.drawing/fontfamily)의 해시 코드를 가져옵니다.

**Returns:**
int - 이 [FontFamily](../../com.aspose.drawing/fontfamily)의 해시 코드입니다.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 객체가 [FontFamily](../../com.aspose.drawing/fontfamily)이며 이 [FontFamily](../../com.aspose.drawing/fontfamily)와 동일한지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 테스트할 객체입니다. |

**Returns:**
boolean - `obj`가 [FontFamily](../../com.aspose.drawing/fontfamily)이며 이 [FontFamily](../../com.aspose.drawing/fontfamily)와 동일한 경우 `true`; 그렇지 않으면 `false`.
### getLineSpacing(int style) {#getLineSpacing-int-}
```
public int getLineSpacing(int style)
```


지정된 스타일의 [FontFamily](../../com.aspose.drawing/fontfamily)의 줄 간격을 디자인 단위로 반환합니다. 줄 간격은 연속된 두 텍스트 줄의 기준선 사이의 수직 거리입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| style | int | 적용할 [FontStyle](../../com.aspose.drawing/fontstyle)입니다. |

**Returns:**
int - 연속된 두 텍스트 줄 사이의 거리입니다.
