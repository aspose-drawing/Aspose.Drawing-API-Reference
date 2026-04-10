---
title: GraphicsPathIterator
second_title: Aspose.Drawing for Java API 참조
description: 하위 경로를 반복하고 각 하위 경로에 포함된 도형 유형을 테스트할 수 있는 기능을 제공합니다.
type: docs
weight: 24
url: /ko/java/com.aspose.drawing.drawing2d/graphicspathiterator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class GraphicsPathIterator implements System.IDisposable
```

하위 경로를 반복하고 각 하위 경로에 포함된 도형 유형을 테스트할 수 있는 기능을 제공하는 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)입니다. 이 클래스는 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GraphicsPathIterator(GraphicsPath path)](#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-) | [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCount()](#getCount--) | 경로에 있는 점의 수를 가져옵니다. |
| [getSubpathCount()](#getSubpathCount--) | 경로에 있는 하위 경로의 수를 가져옵니다. |
| [dispose()](#dispose--) | 관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다. |
| [copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)](#copyData-com.aspose.drawing.PointF-----byte-----int-int-) | 연관된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)의 GraphicsPath.PathPoints 속성과 GraphicsPath.PathTypes 속성 배열을 지정된 두 배열에 복사합니다. |
| [enumerate(PointF[][] points, byte[][] types)](#enumerate-com.aspose.drawing.PointF-----byte-----) | 연관된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)의 GraphicsPath.PathPoints 속성과 GraphicsPath.PathTypes 속성 배열을 지정된 두 배열에 복사합니다. |
| [hasCurve()](#hasCurve--) | 이 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator)와 연결된 경로에 곡선이 포함되어 있는지 여부를 나타냅니다. |
| [nextMarker(int[] startIndex, int[] endIndex)](#nextMarker-int---int---) | [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator)를 경로의 다음 마커로 이동하고 [out] 매개변수를 통해 시작 및 종료 인덱스를 반환합니다. |
| [nextMarker(GraphicsPath path)](#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-) | 이 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 객체에는 연관된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체가 있습니다. |
| [nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)](#nextPathType-byte---int---int---) | 같은 유형을 가진 다음 데이터 포인트 그룹의 시작 인덱스와 종료 인덱스를 가져옵니다. |
| [nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)](#nextSubpath-int---int---boolean---) | [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator)를 경로의 다음 하위 경로로 이동합니다. |
| [nextSubpath(GraphicsPath path, boolean[] isClosed)](#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---) | 이 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator)의 연관된 경로에서 다음 도형(하위 경로)을 가져옵니다. |
| [rewind()](#rewind--) | 이 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator)를 연관된 경로의 시작으로 되감습니다. |
### GraphicsPathIterator(GraphicsPath path) {#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public GraphicsPathIterator(GraphicsPath path)
```


[GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 이 도우미 클래스를 초기화할 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체입니다. |

### getCount() {#getCount--}
```
public int getCount()
```


경로에 있는 점의 수를 가져옵니다.

**Returns:**
int - 경로에 있는 점의 수.
### getSubpathCount() {#getSubpathCount--}
```
public int getSubpathCount()
```


경로에 있는 하위 경로의 수를 가져옵니다.

**Returns:**
int - 경로에 있는 하위 경로의 수.
### dispose() {#dispose--}
```
public void dispose()
```


관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다.

### copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex) {#copyData-com.aspose.drawing.PointF-----byte-----int-int-}
```
public int copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)
```


연관된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)의 GraphicsPath.PathPoints 속성과 GraphicsPath.PathTypes 속성 배열을 지정된 두 배열에 복사합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | 반환 시, 경로의 점을 나타내는 System.Drawing.PointF 구조체 배열을 포함합니다. |
| 유형 | byte[][] | 반환 시, 경로의 점 유형을 나타내는 바이트 배열을 포함합니다. |
| startIndex | int | 배열의 시작 인덱스를 지정합니다. |
| endIndex | int | 배열의 종료 인덱스를 지정합니다. |

**Returns:**
int - 복사된 점의 수.
### enumerate(PointF[][] points, byte[][] types) {#enumerate-com.aspose.drawing.PointF-----byte-----}
```
public int enumerate(PointF[][] points, byte[][] types)
```


연관된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)의 GraphicsPath.PathPoints 속성과 GraphicsPath.PathTypes 속성 배열을 지정된 두 배열에 복사합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | 반환 시, 경로의 점을 나타내는 System.Drawing.PointF 구조체 배열을 포함합니다. |
| 유형 | byte[][] | 반환 시, 경로의 점 유형을 나타내는 바이트 배열을 포함합니다. |

**Returns:**
int - 복사된 점의 수.
### hasCurve() {#hasCurve--}
```
public boolean hasCurve()
```


이 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator)와 연결된 경로에 곡선이 포함되어 있는지 여부를 나타냅니다.

**Returns:**
boolean - 이 메서드는 현재 서브패스에 곡선이 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### nextMarker(int[] startIndex, int[] endIndex) {#nextMarker-int---int---}
```
public int nextMarker(int[] startIndex, int[] endIndex)
```


[GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator)를 경로의 다음 마커로 이동하고 [out] 매개변수를 통해 시작 및 종료 인덱스를 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| startIndex | int[] | [out] 이 매개변수에 제공된 정수 참조는 서브패스를 시작하는 점의 인덱스를 받습니다. |
| endIndex | int[] | [out] 이 매개변수에 제공된 정수 참조는 startIndex가 가리키는 서브패스의 끝점 인덱스를 받습니다. |

**Returns:**
int - 이 마커와 다음 마커 사이의 점 개수입니다.
### nextMarker(GraphicsPath path) {#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public int nextMarker(GraphicsPath path)
```


이 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 객체는 연관된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체를 가지고 있습니다. 이 메서드는 연관된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)를 경로의 다음 마커로 이동시키고 현재 마커와 다음 마커(또는 경로 끝) 사이에 포함된 모든 점을 매개변수로 전달된 두 번째 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체에 복사합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 점이 복사될 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체입니다. |

**Returns:**
int - 이 마커와 다음 마커 사이의 점 개수입니다.
### nextPathType(byte[] pathType, int[] startIndex, int[] endIndex) {#nextPathType-byte---int---int---}
```
public int nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)
```


같은 유형을 가진 다음 데이터 포인트 그룹의 시작 인덱스와 종료 인덱스를 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pathType | byte[] | [out] 그룹 내 모든 점이 공유하는 점 유형을 받습니다. 가능한 유형은 [PathPointType](../../com.aspose.drawing.drawing2d/pathpointtype) 열거형에서 가져올 수 있습니다. |
| startIndex | int[] | [out] 점 그룹의 시작 인덱스를 받습니다. |
| endIndex | int[] | [out] 점 그룹의 끝 인덱스를 받습니다. |

**Returns:**
int - 이 메서드는 그룹에 포함된 데이터 점의 개수를 반환합니다. 경로에 더 이상 그룹이 없으면 이 메서드는 0을 반환합니다.
### nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed) {#nextSubpath-int---int---boolean---}
```
public int nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)
```


[GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator)를 경로의 다음 서브패스로 이동합니다. 다음 서브패스의 시작 인덱스와 끝 인덱스는 [out] 매개변수에 포함됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| startIndex | int[] | [out] 다음 서브패스의 시작 인덱스를 받습니다. |
| endIndex | int[] | [out] 다음 서브패스의 끝 인덱스를 받습니다. |
| isClosed | boolean[] | [out] 서브패스가 닫혀 있는지 여부를 나타냅니다. |

**Returns:**
int - 검색된 도형(서브패스) 내 데이터 점의 개수입니다. 더 이상 검색할 도형이 없으면 0이 반환됩니다.
### nextSubpath(GraphicsPath path, boolean[] isClosed) {#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---}
```
public int nextSubpath(GraphicsPath path, boolean[] isClosed)
```


이 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator)의 연관된 경로에서 다음 도형(하위 경로)을 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 이 반복기에 대해 검색된 도형(서브패스)의 데이터 점과 일치하도록 데이터 점이 설정될 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)입니다. |
| isClosed | boolean[] | [out] 현재 서브패스가 닫혀 있는지 여부를 나타냅니다. 도형이 닫혀 있으면 true이며, 그렇지 않으면 false입니다. |

**Returns:**
int - 검색된 도형(서브패스) 내 데이터 점의 개수입니다. 더 이상 검색할 도형이 없으면 0이 반환됩니다.
### rewind() {#rewind--}
```
public void rewind()
```


이 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator)를 연관된 경로의 시작으로 되감습니다.

