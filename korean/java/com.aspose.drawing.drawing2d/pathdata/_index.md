---
title: PathData
second_title: Aspose.Drawing for Java API 참조
description: 객체를 구성하는 그래픽 데이터를 포함합니다.
type: docs
weight: 35
url: /ko/java/com.aspose.drawing.drawing2d/pathdata/
---
**Inheritance:**
java.lang.Object
```
public final class PathData
```

[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체를 구성하는 그래픽 데이터를 포함합니다. 이 클래스는 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PathData()](#PathData--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPoints()](#getPoints--) | 경로가 구성되는 점들을 나타내는 [PointF](../../com.aspose.drawing/pointf) 구조체 배열을 가져옵니다. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.drawing.PointF---) | 경로가 구성되는 점들을 나타내는 [PointF](../../com.aspose.drawing/pointf) 구조체 배열을 설정합니다. |
| [getTypes()](#getTypes--) | 경로 내 해당 점들의 유형을 가져옵니다. |
| [setTypes(byte[] value)](#setTypes-byte---) | 경로 내 해당 점들의 유형을 설정합니다. |
### PathData() {#PathData--}
```
public PathData()
```


### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


경로가 구성되는 점들을 나타내는 [PointF](../../com.aspose.drawing/pointf) 구조체 배열을 가져옵니다.

값: 경로가 구성되는 점들을 나타내는 [PointF](../../com.aspose.drawing/pointf) 객체 배열입니다.

**Returns:**
com.aspose.drawing.PointF[] - 경로가 구성되는 점들을 나타내는 [PointF](../../com.aspose.drawing/pointf) 구조체 배열입니다.
### setPoints(PointF[] value) {#setPoints-com.aspose.drawing.PointF---}
```
public void setPoints(PointF[] value)
```


경로가 구성되는 점들을 나타내는 [PointF](../../com.aspose.drawing/pointf) 구조체 배열을 설정합니다.

값: 경로가 구성되는 점들을 나타내는 [PointF](../../com.aspose.drawing/pointf) 객체 배열입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.drawing/pointf) | 경로가 구성되는 점들을 나타내는 [PointF](../../com.aspose.drawing/pointf) 구조체 배열. |

### getTypes() {#getTypes--}
```
public byte[] getTypes()
```


경로 내 해당 점들의 유형을 가져옵니다.

값: 경로 내 해당 점들의 유형을 지정하는 바이트 배열입니다.

**Returns:**
byte[] - 경로 내 해당 점들의 유형입니다.
### setTypes(byte[] value) {#setTypes-byte---}
```
public void setTypes(byte[] value)
```


경로 내 해당 점들의 유형을 설정합니다.

값: 경로 내 해당 점들의 유형을 지정하는 바이트 배열입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte[] | 경로에 있는 해당 점들의 유형. |

