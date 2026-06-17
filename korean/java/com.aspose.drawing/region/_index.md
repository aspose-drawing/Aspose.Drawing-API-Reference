---
title: Region
second_title: Aspose.Drawing for Java API 참조
description: 사각형 및 경로로 구성된 그래픽 도형의 내부를 설명합니다.
type: docs
weight: 40
url: /ko/java/com.aspose.drawing/region/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Region implements System.IDisposable
```

사각형과 경로로 구성된 그래픽 형태의 내부를 설명합니다. 이 클래스는 상속될 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Region()](#Region--) | 새로운 [Region](../../com.aspose.drawing/region) 클래스 인스턴스를 초기화합니다. |
| [Region(RectangleF rect)](#Region-com.aspose.drawing.RectangleF-) | 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조에서 새로운 [Region](../../com.aspose.drawing/region) 클래스 인스턴스를 초기화합니다. |
| [Region(Rectangle rect)](#Region-com.aspose.drawing.Rectangle-) | 지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조에서 새로운 [Region](../../com.aspose.drawing/region) 클래스 인스턴스를 초기화합니다. |
| [Region(GraphicsPath path)](#Region-com.aspose.drawing.drawing2d.GraphicsPath-) | 지정된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)와 함께 새로운 [Region](../../com.aspose.drawing/region) 클래스 인스턴스를 초기화합니다. |
| [Region(RegionData rgnData)](#Region-com.aspose.drawing.drawing2d.RegionData-) | 지정된 데이터에서 새로운 [Region](../../com.aspose.drawing/region) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [dispose()](#dispose--) | 이 [Region](../../com.aspose.drawing/region)에서 사용된 모든 리소스를 해제합니다. |
| [equals(Region region, Graphics g)](#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-) | 지정된 [Region](../../com.aspose.drawing/region)이 지정된 그리기 표면에서 이 [Region](../../com.aspose.drawing/region)과 동일한지 테스트합니다. |
| [deepClone()](#deepClone--) | 이 [Region](../../com.aspose.drawing/region)의 정확한 복사본을 생성합니다. |
| [makeInfinite()](#makeInfinite--) | 이 [Region](../../com.aspose.drawing/region) 객체를 무한 내부로 초기화합니다. |
| [makeEmpty()](#makeEmpty--) | 이 [Region](../../com.aspose.drawing/region)를 빈 내부로 초기화합니다. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | 이 [Region](../../com.aspose.drawing/region)를 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조와의 교차 영역으로 업데이트합니다. |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | 이 [Region](../../com.aspose.drawing/region)를 지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조와의 교차 영역으로 업데이트합니다. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.drawing.drawing2d.GraphicsPath-) | 이 [Region](../../com.aspose.drawing/region)를 지정된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)와의 교차 영역으로 업데이트합니다. |
| [intersect(Region region)](#intersect-com.aspose.drawing.Region-) | 이 [Region](../../com.aspose.drawing/region)를 지정된 [Region](../../com.aspose.drawing/region)와의 교차 영역으로 업데이트합니다. |
| [union(RectangleF rect)](#union-com.aspose.drawing.RectangleF-) | 이 [Region](../../com.aspose.drawing/region)를 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조와의 합집합으로 업데이트합니다. |
| [union(Rectangle rect)](#union-com.aspose.drawing.Rectangle-) | 이 [Region](../../com.aspose.drawing/region)를 지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조와의 합집합으로 업데이트합니다. |
| [union(GraphicsPath path)](#union-com.aspose.drawing.drawing2d.GraphicsPath-) | 이 [Region](../../com.aspose.drawing/region)를 지정된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)와의 합집합으로 업데이트합니다. |
| [union(Region region)](#union-com.aspose.drawing.Region-) | 이 [Region](../../com.aspose.drawing/region)를 지정된 [Region](../../com.aspose.drawing/region)와의 합집합으로 업데이트합니다. |
| [getRegionData()](#getRegionData--) | 이 [Region](../../com.aspose.drawing/region)를 설명하는 정보를 나타내는 [RegionData](../../com.aspose.drawing.drawing2d/regiondata)를 반환합니다. |
| [xor(RectangleF rect)](#xor-com.aspose.drawing.RectangleF-) | 이 [Region](../../com.aspose.drawing/region)를 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조와의 교차 영역을 제외한 합집합으로 업데이트합니다. |
| [xor(Rectangle rect)](#xor-com.aspose.drawing.Rectangle-) | 이 [Region](../../com.aspose.drawing/region)를 지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조와의 교차 영역을 제외한 합집합으로 업데이트합니다. |
| [xor(GraphicsPath path)](#xor-com.aspose.drawing.drawing2d.GraphicsPath-) | 이 [Region](../../com.aspose.drawing/region)를 지정된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)와의 교차 영역을 제외한 합집합으로 업데이트합니다. |
| [xor(Region region)](#xor-com.aspose.drawing.Region-) | 이 [Region](../../com.aspose.drawing/region)를 지정된 [Region](../../com.aspose.drawing/region)와의 교차 영역을 제외한 합집합으로 업데이트합니다. |
| [exclude(RectangleF rect)](#exclude-com.aspose.drawing.RectangleF-) | 이 [Region](../../com.aspose.drawing/region)의 내부 중 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조와 교차하지 않는 부분만 포함하도록 업데이트합니다. |
| [exclude(Rectangle rect)](#exclude-com.aspose.drawing.Rectangle-) | 이 [Region](../../com.aspose.drawing/region)의 내부 중 지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조와 교차하지 않는 부분만 포함하도록 업데이트합니다. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.drawing.drawing2d.GraphicsPath-) | 이 [Region](../../com.aspose.drawing/region)의 내부 중 지정된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)와 교차하지 않는 부분만 포함하도록 업데이트합니다. |
| [exclude(Region region)](#exclude-com.aspose.drawing.Region-) | 이 [Region](../../com.aspose.drawing/region)의 내부 중 지정된 [Region](../../com.aspose.drawing/region)와 교차하지 않는 부분만 포함하도록 업데이트합니다. |
| [complement(RectangleF rect)](#complement-com.aspose.drawing.RectangleF-) | 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조 중 이 [Region](../../com.aspose.drawing/region)와 교차하지 않는 부분을 포함하도록 이 [Region](../../com.aspose.drawing/region)를 업데이트합니다. |
| [complement(Rectangle rect)](#complement-com.aspose.drawing.Rectangle-) | 지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조 중 이 [Region](../../com.aspose.drawing/region)와 교차하지 않는 부분을 포함하도록 이 [Region](../../com.aspose.drawing/region)를 업데이트합니다. |
| [complement(GraphicsPath path)](#complement-com.aspose.drawing.drawing2d.GraphicsPath-) | 지정된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 중 이 [Region](../../com.aspose.drawing/region)와 교차하지 않는 부분을 포함하도록 이 [Region](../../com.aspose.drawing/region)를 업데이트합니다. |
| [complement(Region region)](#complement-com.aspose.drawing.Region-) | 이 [Region](../../com.aspose.drawing/region)을 업데이트하여 지정된 [Region](../../com.aspose.drawing/region) 중 이 [Region](../../com.aspose.drawing/region)과 교차하지 않는 부분을 포함합니다. |
| [translate(float dx, float dy)](#translate-float-float-) | 지정된 양만큼 이 [Region](../../com.aspose.drawing/region)의 좌표를 오프셋합니다. |
| [translate(int dx, int dy)](#translate-int-int-) | 지정된 양만큼 이 [Region](../../com.aspose.drawing/region)의 좌표를 오프셋합니다. |
| [transform(Matrix matrix)](#transform-com.aspose.drawing.drawing2d.Matrix-) | 지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix)로 이 [Region](../../com.aspose.drawing/region)을 변환합니다. |
| [getBounds(Graphics g)](#getBounds-com.aspose.drawing.Graphics-) | 그림 표면의 [Graphics](../../com.aspose.drawing/graphics) 객체에서 이 [Region](../../com.aspose.drawing/region)을 둘러싸는 사각형을 나타내는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조를 가져옵니다. |
| [getRegionScans(Matrix matrix)](#getRegionScans-com.aspose.drawing.drawing2d.Matrix-) | 지정된 행렬 변환이 적용된 후 이 [Region](../../com.aspose.drawing/region)을 근사하는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조 배열을 반환합니다. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.drawing.Graphics-) | 지정된 그림 표면에서 이 [Region](../../com.aspose.drawing/region)의 내부가 비어 있는지 테스트합니다. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.drawing.Graphics-) | 지정된 그림 표면에서 이 [Region](../../com.aspose.drawing/region)의 내부가 무한한지 테스트합니다. |
| [isVisible(float x, float y)](#isVisible-float-float-) | 지정된 점이 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다. |
| [isVisible(PointF point)](#isVisible-com.aspose.drawing.PointF-) | 지정된 [PointF](../../com.aspose.drawing/pointf) 구조가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.drawing.Graphics-) | 지정된 [Graphics](../../com.aspose.drawing/graphics)를 사용하여 그릴 때 지정된 점이 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-) | 지정된 [Graphics](../../com.aspose.drawing/graphics)를 사용하여 그릴 때 지정된 [PointF](../../com.aspose.drawing/pointf) 구조가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | 지정된 사각형의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.drawing.RectangleF-) | 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.drawing.Graphics-) | 지정된 [Graphics](../../com.aspose.drawing/graphics)를 사용하여 그릴 때 지정된 사각형의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-) | 지정된 [Graphics](../../com.aspose.drawing/graphics)를 사용하여 그릴 때 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.drawing.Graphics-) | 지정된 [Graphics](../../com.aspose.drawing/graphics) 객체를 사용하여 그릴 때 지정된 점이 이 [Region](../../com.aspose.drawing/region) 객체 내부에 포함되는지 테스트합니다. |
| [isVisible(Point point)](#isVisible-com.aspose.drawing.Point-) | 지정된 [Point](../../com.aspose.drawing/point) 구조가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-) | 지정된 [Graphics](../../com.aspose.drawing/graphics)를 사용하여 그릴 때 지정된 [Point](../../com.aspose.drawing/point) 구조가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | 지정된 사각형의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.drawing.Rectangle-) | 지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.drawing.Graphics-) | 지정된 [Graphics](../../com.aspose.drawing/graphics)를 사용하여 그릴 때 지정된 사각형의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-) | 지정된 [Graphics](../../com.aspose.drawing/graphics)를 사용하여 그릴 때 지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다. |
### Region() {#Region--}
```
public Region()
```


새로운 [Region](../../com.aspose.drawing/region) 클래스 인스턴스를 초기화합니다.

### Region(RectangleF rect) {#Region-com.aspose.drawing.RectangleF-}
```
public Region(RectangleF rect)
```


지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조에서 새로운 [Region](../../com.aspose.drawing/region) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 새 [Region](../../com.aspose.drawing/region)의 내부를 정의하는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조입니다. |

### Region(Rectangle rect) {#Region-com.aspose.drawing.Rectangle-}
```
public Region(Rectangle rect)
```


지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조에서 새로운 [Region](../../com.aspose.drawing/region) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 새 [Region](../../com.aspose.drawing/region)의 내부를 정의하는 [Rectangle](../../com.aspose.drawing/rectangle) 구조입니다. |

### Region(GraphicsPath path) {#Region-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public Region(GraphicsPath path)
```


지정된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)와 함께 새로운 [Region](../../com.aspose.drawing/region) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 새 [Region](../../com.aspose.drawing/region)을 정의하는 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)입니다. |

### Region(RegionData rgnData) {#Region-com.aspose.drawing.drawing2d.RegionData-}
```
public Region(RegionData rgnData)
```


지정된 데이터에서 새로운 [Region](../../com.aspose.drawing/region) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rgnData | [RegionData](../../com.aspose.drawing.drawing2d/regiondata) | 새 [Region](../../com.aspose.drawing/region)의 내부를 정의하는 [RegionData](../../com.aspose.drawing.drawing2d/regiondata)입니다. |

### dispose() {#dispose--}
```
public void dispose()
```


이 [Region](../../com.aspose.drawing/region)에서 사용된 모든 리소스를 해제합니다.

### equals(Region region, Graphics g) {#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-}
```
public boolean equals(Region region, Graphics g)
```


지정된 [Region](../../com.aspose.drawing/region)이 지정된 그리기 표면에서 이 [Region](../../com.aspose.drawing/region)과 동일한지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | 테스트할 [Region](../../com.aspose.drawing/region)입니다. |
| g | [Graphics](../../com.aspose.drawing/graphics) | 그리기 표면을 나타내는 [Graphics](../../com.aspose.drawing/graphics). |

**Returns:**
boolean - `g` 매개변수와 연관된 변환이 적용될 때 영역 내부가 이 영역 내부와 동일하면 true; 그렇지 않으면 false.
### deepClone() {#deepClone--}
```
public Region deepClone()
```


이 [Region](../../com.aspose.drawing/region)의 정확한 복사본을 생성합니다.

**Returns:**
[Region](../../com.aspose.drawing/region) - The [Region](../../com.aspose.drawing/region) that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


이 [Region](../../com.aspose.drawing/region) 객체를 무한 내부로 초기화합니다.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


이 [Region](../../com.aspose.drawing/region)를 빈 내부로 초기화합니다.

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public void intersect(RectangleF rect)
```


이 [Region](../../com.aspose.drawing/region)를 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조와의 교차 영역으로 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 이 [Region](../../com.aspose.drawing/region)와 교차할 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체. |

### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public void intersect(Rectangle rect)
```


이 [Region](../../com.aspose.drawing/region)를 지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조와의 교차 영역으로 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 이 [Region](../../com.aspose.drawing/region)와 교차할 [Rectangle](../../com.aspose.drawing/rectangle) 구조체. |

### intersect(GraphicsPath path) {#intersect-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


이 [Region](../../com.aspose.drawing/region)를 지정된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)와의 교차 영역으로 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 이 [Region](../../com.aspose.drawing/region)와 교차할 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체. |

### intersect(Region region) {#intersect-com.aspose.drawing.Region-}
```
public void intersect(Region region)
```


이 [Region](../../com.aspose.drawing/region)를 지정된 [Region](../../com.aspose.drawing/region)와의 교차 영역으로 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | 이 [Region](../../com.aspose.drawing/region)와 교차할 [Region](../../com.aspose.drawing/region) 객체. |

### union(RectangleF rect) {#union-com.aspose.drawing.RectangleF-}
```
public void union(RectangleF rect)
```


이 [Region](../../com.aspose.drawing/region)를 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조와의 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 이 [Region](../../com.aspose.drawing/region)와 합칠 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체. |

--------------------

Union은 무한 영역을 무한하게 유지합니다. |

### union(Rectangle rect) {#union-com.aspose.drawing.Rectangle-}
```
public void union(Rectangle rect)
```


이 [Region](../../com.aspose.drawing/region)를 지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조와의 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | rect | [Rectangle](../../com.aspose.drawing/rectangle) | 이 [Region](../../com.aspose.drawing/region)와 합칠 [Rectangle](../../com.aspose.drawing/rectangle) 구조체. |

--------------------

Union은 무한 영역을 무한하게 유지합니다. |

### union(GraphicsPath path) {#union-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void union(GraphicsPath path)
```


이 [Region](../../com.aspose.drawing/region)를 지정된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)와의 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 이 [Region](../../com.aspose.drawing/region)와 합칠 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체. |

--------------------

Union은 무한 영역을 무한하게 유지합니다. |

### union(Region region) {#union-com.aspose.drawing.Region-}
```
public void union(Region region)
```


이 [Region](../../com.aspose.drawing/region)를 지정된 [Region](../../com.aspose.drawing/region)와의 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | region | [Region](../../com.aspose.drawing/region) | 이 [Region](../../com.aspose.drawing/region)와 합칠 [Region](../../com.aspose.drawing/region) 객체. |

--------------------

Union은 무한 영역을 무한하게 유지합니다. |

### getRegionData() {#getRegionData--}
```
public RegionData getRegionData()
```


이 [Region](../../com.aspose.drawing/region)를 설명하는 정보를 나타내는 [RegionData](../../com.aspose.drawing.drawing2d/regiondata)를 반환합니다.

**Returns:**
[RegionData](../../com.aspose.drawing.drawing2d/regiondata) - A [RegionData](../../com.aspose.drawing.drawing2d/regiondata) that represents the information that describes this [Region](../../com.aspose.drawing/region).
### xor(RectangleF rect) {#xor-com.aspose.drawing.RectangleF-}
```
public void xor(RectangleF rect)
```


이 [Region](../../com.aspose.drawing/region)를 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조와의 교차 영역을 제외한 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 이 [Region](../../com.aspose.drawing/region)와 `M:Region.Xor(Drawing2D.GraphicsPath)` 연산을 수행할 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체. |

### xor(Rectangle rect) {#xor-com.aspose.drawing.Rectangle-}
```
public void xor(Rectangle rect)
```


이 [Region](../../com.aspose.drawing/region)를 지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조와의 교차 영역을 제외한 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 이 [Region](../../com.aspose.drawing/region)와 `M:Region.Xor(Rectangle)` 연산을 수행할 [Rectangle](../../com.aspose.drawing/rectangle) 구조체. |

### xor(GraphicsPath path) {#xor-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


이 [Region](../../com.aspose.drawing/region)를 지정된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)와의 교차 영역을 제외한 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 이 [Region](../../com.aspose.drawing/region)와 `M:Region.Xor(GraphicsPath)` 연산을 수행할 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체. |

### xor(Region region) {#xor-com.aspose.drawing.Region-}
```
public void xor(Region region)
```


이 [Region](../../com.aspose.drawing/region)를 지정된 [Region](../../com.aspose.drawing/region)와의 교차 영역을 제외한 합집합으로 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | 이 [Region](../../com.aspose.drawing/region)와 `M:Region.Xor(Region)` 연산을 수행할 [Region](../../com.aspose.drawing/region) 객체. |

### exclude(RectangleF rect) {#exclude-com.aspose.drawing.RectangleF-}
```
public void exclude(RectangleF rect)
```


이 [Region](../../com.aspose.drawing/region)의 내부 중 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조와 교차하지 않는 부분만 포함하도록 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 이 [Region](../../com.aspose.drawing/region)에서 제외할 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체. |

### exclude(Rectangle rect) {#exclude-com.aspose.drawing.Rectangle-}
```
public void exclude(Rectangle rect)
```


이 [Region](../../com.aspose.drawing/region)의 내부 중 지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조와 교차하지 않는 부분만 포함하도록 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 이 [Region](../../com.aspose.drawing/region)에서 제외할 [Rectangle](../../com.aspose.drawing/rectangle) 구조체. |

### exclude(GraphicsPath path) {#exclude-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


이 [Region](../../com.aspose.drawing/region)의 내부 중 지정된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)와 교차하지 않는 부분만 포함하도록 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 이 [Region](../../com.aspose.drawing/region)에서 제외할 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체. |

### exclude(Region region) {#exclude-com.aspose.drawing.Region-}
```
public void exclude(Region region)
```


이 [Region](../../com.aspose.drawing/region)의 내부 중 지정된 [Region](../../com.aspose.drawing/region)와 교차하지 않는 부분만 포함하도록 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | 이 [Region](../../com.aspose.drawing/region)에서 제외할 [Region](../../com.aspose.drawing/region) 객체. |

### complement(RectangleF rect) {#complement-com.aspose.drawing.RectangleF-}
```
public void complement(RectangleF rect)
```


지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조 중 이 [Region](../../com.aspose.drawing/region)와 교차하지 않는 부분을 포함하도록 이 [Region](../../com.aspose.drawing/region)를 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 이 [Region](../../com.aspose.drawing/region)를 보완할 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체. |

### complement(Rectangle rect) {#complement-com.aspose.drawing.Rectangle-}
```
public void complement(Rectangle rect)
```


지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조 중 이 [Region](../../com.aspose.drawing/region)와 교차하지 않는 부분을 포함하도록 이 [Region](../../com.aspose.drawing/region)를 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 이 [Region](../../com.aspose.drawing/region)를 보완할 [Rectangle](../../com.aspose.drawing/rectangle) 구조체. |

### complement(GraphicsPath path) {#complement-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


지정된 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 중 이 [Region](../../com.aspose.drawing/region)와 교차하지 않는 부분을 포함하도록 이 [Region](../../com.aspose.drawing/region)를 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 이 [Region](../../com.aspose.drawing/region)를 보완할 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 객체. |

### complement(Region region) {#complement-com.aspose.drawing.Region-}
```
public void complement(Region region)
```


이 [Region](../../com.aspose.drawing/region)을 업데이트하여 지정된 [Region](../../com.aspose.drawing/region) 중 이 [Region](../../com.aspose.drawing/region)과 교차하지 않는 부분을 포함합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | 이 [Region](../../com.aspose.drawing/region) 객체를 보완할 [Region](../../com.aspose.drawing/region) 객체. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


지정된 양만큼 이 [Region](../../com.aspose.drawing/region)의 좌표를 오프셋합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dx | float | 이 [Region](../../com.aspose.drawing/region)를 수평으로 오프셋하는 양. |
| dy | float | 이 [Region](../../com.aspose.drawing/region)를 수직으로 오프셋하는 양. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


지정된 양만큼 이 [Region](../../com.aspose.drawing/region)의 좌표를 오프셋합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dx | int | 이 [Region](../../com.aspose.drawing/region)을 수평으로 오프셋할 양 |
| dy | int | 이 [Region](../../com.aspose.drawing/region)를 수직으로 오프셋하는 양. |

### transform(Matrix matrix) {#transform-com.aspose.drawing.drawing2d.Matrix-}
```
public void transform(Matrix matrix)
```


지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix)로 이 [Region](../../com.aspose.drawing/region)을 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 이 [Region](../../com.aspose.drawing/region)를 변환하는 데 사용할 [Matrix](../../com.aspose.drawing.drawing2d/matrix). |

### getBounds(Graphics g) {#getBounds-com.aspose.drawing.Graphics-}
```
public RectangleF getBounds(Graphics g)
```


그림 표면의 [Graphics](../../com.aspose.drawing/graphics) 객체에서 이 [Region](../../com.aspose.drawing/region)을 둘러싸는 사각형을 나타내는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조를 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | 이 [Region](../../com.aspose.drawing/region)가 그려지는 [Graphics](../../com.aspose.drawing/graphics). |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents the bounding rectangle for this [Region](../../com.aspose.drawing/region) on the specified drawing surface.
### getRegionScans(Matrix matrix) {#getRegionScans-com.aspose.drawing.drawing2d.Matrix-}
```
public RectangleF[] getRegionScans(Matrix matrix)
```


지정된 행렬 변환이 적용된 후 이 [Region](../../com.aspose.drawing/region)을 근사하는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조 배열을 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 영역에 적용할 기하학적 변환을 나타내는 [Matrix](../../com.aspose.drawing.drawing2d/matrix). |

**Returns:**
com.aspose.drawing.RectangleF[] - 지정된 매트릭스 변환이 적용된 후 이 [Region](../../com.aspose.drawing/region)를 근사하는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체 배열.
### isEmpty(Graphics g) {#isEmpty-com.aspose.drawing.Graphics-}
```
public boolean isEmpty(Graphics g)
```


지정된 그림 표면에서 이 [Region](../../com.aspose.drawing/region)의 내부가 비어 있는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | 그리기 표면을 나타내는 [Graphics](../../com.aspose.drawing/graphics). |

**Returns:**
boolean - `g`와 연관된 변환이 적용될 때 이 [Region](../../com.aspose.drawing/region)의 내부가 비어 있으면 true; 그렇지 않으면 false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.drawing.Graphics-}
```
public boolean isInfinite(Graphics g)
```


지정된 그림 표면에서 이 [Region](../../com.aspose.drawing/region)의 내부가 무한한지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | 그리기 표면을 나타내는 [Graphics](../../com.aspose.drawing/graphics). |

**Returns:**
boolean - `g`와 연관된 변환이 적용될 때 이 [Region](../../com.aspose.drawing/region)의 내부가 무한하면 true; 그렇지 않으면 false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


지정된 점이 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y좌표. |

**Returns:**
boolean - 지정된 점이 이 [Region](../../com.aspose.drawing/region)에 포함되면 true; 그렇지 않으면 false.
### isVisible(PointF point) {#isVisible-com.aspose.drawing.PointF-}
```
public boolean isVisible(PointF point)
```


지정된 [PointF](../../com.aspose.drawing/pointf) 구조가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | 테스트할 [PointF](../../com.aspose.drawing/pointf) 구조체. |

**Returns:**
boolean - `point`가 이 [Region](../../com.aspose.drawing/region)에 포함되면 true; 그렇지 않으면 false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


지정된 [Graphics](../../com.aspose.drawing/graphics)를 사용하여 그릴 때 지정된 점이 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y좌표. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) 은 그래픽 컨텍스트를 나타냅니다. |

**Returns:**
boolean - 지정된 점이 이 [Region](../../com.aspose.drawing/region)에 포함되면 true; 그렇지 않으면 false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


지정된 [Graphics](../../com.aspose.drawing/graphics)를 사용하여 그릴 때 지정된 [PointF](../../com.aspose.drawing/pointf) 구조가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | 테스트할 [PointF](../../com.aspose.drawing/pointf) 구조체. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) 은 그래픽 컨텍스트를 나타냅니다. |

**Returns:**
boolean - `point`가 이 [Region](../../com.aspose.drawing/region)에 포함되면 true; 그렇지 않으면 false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


지정된 사각형의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 테스트할 사각형의 왼쪽 위 모서리 x 좌표. |
| y | float | 테스트할 사각형의 왼쪽 위 모서리 y 좌표. |
| 너비 | float | 테스트할 사각형의 너비. |
| 높이 | float | 테스트할 사각형의 높이. |

**Returns:**
boolean - 지정된 사각형의 일부라도 이 [Region](../../com.aspose.drawing/region) 객체에 포함되면 true; 그렇지 않으면 false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.drawing.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 테스트할 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체. |

**Returns:**
boolean - `rect`의 일부라도 이 [Region](../../com.aspose.drawing/region)에 포함되면 true; 그렇지 않으면 false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


지정된 [Graphics](../../com.aspose.drawing/graphics)를 사용하여 그릴 때 지정된 사각형의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 테스트할 사각형의 왼쪽 위 모서리 x 좌표. |
| y | float | 테스트할 사각형의 왼쪽 위 모서리 y 좌표. |
| 너비 | float | 테스트할 사각형의 너비. |
| 높이 | float | 테스트할 사각형의 높이. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) 은 그래픽 컨텍스트를 나타냅니다. |

**Returns:**
boolean - 지정된 사각형의 일부라도 이 [Region](../../com.aspose.drawing/region)에 포함되면 true; 그렇지 않으면 false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


지정된 [Graphics](../../com.aspose.drawing/graphics)를 사용하여 그릴 때 지정된 [RectangleF](../../com.aspose.drawing/rectanglef) 구조의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 테스트할 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) 은 그래픽 컨텍스트를 나타냅니다. |

**Returns:**
boolean - `rect`가 이 [Region](../../com.aspose.drawing/region)에 포함되면 true; 그렇지 않으면 false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


지정된 [Graphics](../../com.aspose.drawing/graphics) 객체를 사용하여 그릴 때 지정된 점이 이 [Region](../../com.aspose.drawing/region) 객체 내부에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | int | 테스트할 점의 x 좌표입니다. |
| y | int | 테스트할 점의 y좌표. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) 은 그래픽 컨텍스트를 나타냅니다. |

**Returns:**
boolean - 지정된 점이 이 [Region](../../com.aspose.drawing/region)에 포함되면 true; 그렇지 않으면 false.
### isVisible(Point point) {#isVisible-com.aspose.drawing.Point-}
```
public boolean isVisible(Point point)
```


지정된 [Point](../../com.aspose.drawing/point) 구조가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | 테스트할 [Point](../../com.aspose.drawing/point) 구조체. |

**Returns:**
boolean - `point`가 이 [Region](../../com.aspose.drawing/region)에 포함되면 true; 그렇지 않으면 false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


지정된 [Graphics](../../com.aspose.drawing/graphics)를 사용하여 그릴 때 지정된 [Point](../../com.aspose.drawing/point) 구조가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | 테스트할 [Point](../../com.aspose.drawing/point) 구조체. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) 은 그래픽 컨텍스트를 나타냅니다. |

**Returns:**
boolean - `point`가 이 [Region](../../com.aspose.drawing/region)에 포함되면 true; 그렇지 않으면 false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


지정된 사각형의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | int | 테스트할 사각형의 왼쪽 위 모서리 x 좌표. |
| y | int | 테스트할 사각형의 왼쪽 위 모서리 y 좌표. |
| 너비 | int | 테스트할 사각형의 너비. |
| 높이 | int | 테스트할 사각형의 높이. |

**Returns:**
boolean - 지정된 사각형의 일부라도 이 [Region](../../com.aspose.drawing/region)에 포함되면 true; 그렇지 않으면 false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.drawing.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 테스트할 [Rectangle](../../com.aspose.drawing/rectangle) 구조체. |

**Returns:**
boolean - 이 메서드는 `rect`의 일부라도 이 [Region](../../com.aspose.drawing/region)에 포함되면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


지정된 [Graphics](../../com.aspose.drawing/graphics)를 사용하여 그릴 때 지정된 사각형의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | int | 테스트할 사각형의 왼쪽 위 모서리 x 좌표. |
| y | int | 테스트할 사각형의 왼쪽 위 모서리 y 좌표. |
| 너비 | int | 테스트할 사각형의 너비. |
| 높이 | int | 테스트할 사각형의 높이. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) 은 그래픽 컨텍스트를 나타냅니다. |

**Returns:**
boolean - 지정된 사각형의 일부라도 이 [Region](../../com.aspose.drawing/region)에 포함되면 true; 그렇지 않으면 false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


지정된 [Graphics](../../com.aspose.drawing/graphics)를 사용하여 그릴 때 지정된 [Rectangle](../../com.aspose.drawing/rectangle) 구조의 일부가 이 [Region](../../com.aspose.drawing/region) 내부에 포함되는지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 테스트할 [Rectangle](../../com.aspose.drawing/rectangle) 구조체. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) 은 그래픽 컨텍스트를 나타냅니다. |

**Returns:**
boolean - `rect`의 일부라도 이 [Region](../../com.aspose.drawing/region)에 포함되면 true; 그렇지 않으면 false.
