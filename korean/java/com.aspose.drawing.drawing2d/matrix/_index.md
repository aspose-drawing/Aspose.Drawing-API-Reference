---
title: Matrix
second_title: Aspose.Drawing for Java API 참조
description: 기하학적 변환을 나타내는 3x3 어파인 행렬을 캡슐화합니다.
type: docs
weight: 33
url: /ko/java/com.aspose.drawing.drawing2d/matrix/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Matrix implements System.IDisposable
```

기하학적 변환을 나타내는 3x3 어파인 행렬을 캡슐화합니다. 이 클래스는 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Matrix()](#Matrix--) | Matrix 클래스의 새 인스턴스를 단위 행렬로 초기화합니다. |
| [Matrix(float m11, float m12, float m21, float m22, float dx, float dy)](#Matrix-float-float-float-float-float-float-) | Matrix 클래스의 새 인스턴스를 지정된 요소로 초기화합니다. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---) | [Matrix](../../com.aspose.drawing.drawing2d/matrix) 클래스의 새 인스턴스를 지정된 사각형 및 점 배열에 의해 정의된 기하학적 변환으로 초기화합니다. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---) | [Matrix](../../com.aspose.drawing.drawing2d/matrix) 클래스의 새 인스턴스를 지정된 사각형 및 점 배열에 의해 정의된 기하학적 변환으로 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [IdentityTransform](#IdentityTransform) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getElements()](#getElements--) | 이 Matrix의 요소를 나타내는 부동 소수점 값 배열을 가져옵니다. |
| [isIdentity()](#isIdentity--) | 이 Matrix가 단위 행렬인지 여부를 나타내는 값을 가져옵니다. |
| [isInvertible()](#isInvertible--) | 이 Matrix가 역행 가능인지 여부를 나타내는 값을 가져옵니다. |
| [getOffsetX()](#getOffsetX--) | 이 Matrix의 x 변환값(dx 값 또는 3번째 행 1번째 열의 요소)을 가져옵니다. |
| [getOffsetY()](#getOffsetY--) | 이 Matrix의 y 변환값(`dy` 값 또는 3번째 행 2번째 열의 요소)을 가져옵니다. |
| [dispose()](#dispose--) | 이 Matrix가 사용한 모든 리소스를 해제합니다. |
| [deepClone()](#deepClone--) | 이 Matrix의 정확한 복사본을 생성합니다. |
| [invert()](#invert--) | 이 Matrix가 가역이면 역행렬을 구합니다. |
| [translate(float offsetX, float offsetY)](#translate-float-float-) | 지정된 변환 벡터(offsetX 및 offsetY)를 앞에 추가하여 이 Matrix에 적용합니다. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | 지정된 순서대로 지정된 변환 벡터를 이 Matrix에 적용합니다. |
| [transformVectors(PointF[] pts)](#transformVectors-com.aspose.drawing.PointF---) | 배열에 있는 각 벡터에 매트릭스를 곱합니다. |
| [scale(float scaleX, float scaleY)](#scale-float-float-) | 지정된 스케일 벡터를 앞에 추가하여 이 Matrix에 적용합니다. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | 지정된 순서를 사용하여 지정된 스케일 벡터(scaleX 및 scaleY)를 이 Matrix에 적용합니다. |
| [shear(float shearX, float shearY)](#shear-float-float-) | 지정된 전단 변환을 앞에 추가하여 이 Matrix에 지정된 전단 벡터를 적용합니다. |
| [shear(float shearX, float shearY, int order)](#shear-float-float-int-) | 지정된 순서대로 지정된 전단 벡터를 이 Matrix에 적용합니다. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.drawing.PointF-) | point 매개변수에 지정된 점을 중심으로 시계 방향 회전을 앞에 추가하여 이 Matrix에 적용합니다. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.drawing.PointF-int-) | 지정된 순서대로 지정된 점을 중심으로 시계 방향 회전을 이 Matrix에 적용합니다. |
| [transformPoints(PointF[] pts)](#transformPoints-com.aspose.drawing.PointF---) | 이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)로 표현된 기하 변환을 지정된 점 배열에 적용합니다. |
| [transformPoints(Point[] pts)](#transformPoints-com.aspose.drawing.Point---) | 이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)로 표현된 기하 변환을 지정된 점 배열에 적용합니다. |
| [multiply(Matrix matrix)](#multiply-com.aspose.drawing.drawing2d.Matrix-) | 이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 `matrix` 매개변수에 지정된 매트릭스로 앞에 추가하여 곱합니다(지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 앞에 추가). |
| [multiply(Matrix matrix, int order)](#multiply-com.aspose.drawing.drawing2d.Matrix-int-) | 이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 `matrix` 매개변수에 지정된 매트릭스로 곱하고, `order` 매개변수에 지정된 순서대로 적용합니다. |
| [rotate(float angle)](#rotate-float-) | 원점을 중심으로 지정된 각도만큼 시계 방향 회전을 앞에 추가하여 이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)에 적용합니다. |
| [rotate(float angle, int order)](#rotate-float-int-) | angle 매개변수에 지정된 양만큼 원점(좌표 x와 y가 0) 주위에서 시계 방향 회전을 이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)에 적용합니다. |
| [reset()](#reset--) | 이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 단위 행렬의 요소로 재설정합니다. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Matrix 클래스의 새 인스턴스를 단위 행렬로 초기화합니다.

### Matrix(float m11, float m12, float m21, float m22, float dx, float dy) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


Matrix 클래스의 새 인스턴스를 지정된 요소로 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| m11 | float | 새 Matrix의 첫 번째 행 첫 번째 열에 있는 값. |
| m12 | float | 새 Matrix의 첫 번째 행 두 번째 열에 있는 값. |
| m21 | float | 새 매트릭스의 두 번째 행 첫 번째 열에 있는 값. |
| m22 | float | 새 매트릭스의 두 번째 행 두 번째 열에 있는 값. |
| dx | float | 새 매트릭스의 세 번째 행 첫 번째 열에 있는 값. |
| dy | float | 새 매트릭스의 세 번째 행 두 번째 열에 있는 값. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


[Matrix](../../com.aspose.drawing.drawing2d/matrix) 클래스의 새 인스턴스를 지정된 사각형 및 점 배열에 의해 정의된 기하학적 변환으로 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 변환될 사각형을 나타내는 [Rectangle](../../com.aspose.drawing/rectangle) 구조체. |
| plgpts | [Point\[\]](../../com.aspose.drawing/point) | 사각형의 왼쪽 위, 오른쪽 위, 왼쪽 아래 모서리가 변환될 평행사변형의 점들을 나타내는 세 개의 [Point](../../com.aspose.drawing/point) 구조체 배열입니다. 평행사변형의 오른쪽 아래 모서리는 첫 세 모서리로부터 유추됩니다. |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


[Matrix](../../com.aspose.drawing.drawing2d/matrix) 클래스의 새 인스턴스를 지정된 사각형 및 점 배열에 의해 정의된 기하학적 변환으로 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 변환될 사각형을 나타내는 [RectangleF](../../com.aspose.drawing/rectanglef) 구조체. |
| plgpts | [PointF\[\]](../../com.aspose.drawing/pointf) | 사각형의 왼쪽 위, 오른쪽 위, 왼쪽 아래 모서리가 변환될 평행사변형의 점들을 나타내는 세 개의 [PointF](../../com.aspose.drawing/pointf) 구조체 배열입니다. 평행사변형의 오른쪽 아래 모서리는 첫 세 모서리로부터 유추됩니다. |

### IdentityTransform {#IdentityTransform}
```
public static final Matrix IdentityTransform
```


### getElements() {#getElements--}
```
public float[] getElements()
```


이 Matrix의 요소를 나타내는 부동 소수점 값 배열을 가져옵니다.

**Returns:**
float[] - 이 매트릭스의 요소를 나타내는 부동 소수점 값 배열입니다.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


이 Matrix가 단위 행렬인지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 매트릭스가 항등 매트릭스인지 여부를 나타내는 값입니다.
### isInvertible() {#isInvertible--}
```
public boolean isInvertible()
```


이 Matrix가 역행 가능인지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 매트릭스가 역행 가능한지 여부를 나타내는 값입니다.
### getOffsetX() {#getOffsetX--}
```
public float getOffsetX()
```


이 Matrix의 x 변환값(dx 값 또는 3번째 행 1번째 열의 요소)을 가져옵니다.

**Returns:**
float - 이 매트릭스의 x 변환값(dx 값 또는 세 번째 행 첫 번째 열의 요소)입니다.
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```


이 Matrix의 y 변환값(`dy` 값 또는 3번째 행 2번째 열의 요소)을 가져옵니다.

**Returns:**
float - 이 매트릭스의 y 변환값(`dy` 값 또는 세 번째 행 두 번째 열의 요소)입니다.
### dispose() {#dispose--}
```
public void dispose()
```


이 Matrix가 사용한 모든 리소스를 해제합니다.

--------------------

이 메서드는 실제로 아무 작업도 수행하지 않습니다. System.Drawing API와의 호환성을 위해 제공됩니다.

### deepClone() {#deepClone--}
```
public Matrix deepClone()
```


이 Matrix의 정확한 복사본을 생성합니다.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - The Matrix that this method creates.
### invert() {#invert--}
```
public void invert()
```


이 Matrix가 가역이면 역행렬을 구합니다.

### translate(float offsetX, float offsetY) {#translate-float-float-}
```
public void translate(float offsetX, float offsetY)
```


지정된 변환 벡터(offsetX 및 offsetY)를 앞에 추가하여 이 Matrix에 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| offsetX | float | 이 매트릭스를 변환할 x 값입니다. |
| offsetY | float | 이 매트릭스를 변환할 y 값입니다. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


지정된 순서대로 지정된 변환 벡터를 이 Matrix에 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| offsetX | float | 이 매트릭스를 변환할 x 값입니다. |
| offsetY | float | 이 매트릭스를 변환할 y 값입니다. |
| order | int | 변환이 이 매트릭스에 적용되는 순서(추가 또는 앞에 삽입)를 지정하는 MatrixOrder입니다. |

### transformVectors(PointF[] pts) {#transformVectors-com.aspose.drawing.PointF---}
```
public void transformVectors(PointF[] pts)
```


배열의 각 벡터에 매트릭스를 곱합니다. 이 매트릭스의 변환 요소(세 번째 행)는 무시됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | 변환할 점들을 나타내는 [PointF](../../com.aspose.drawing/pointf) 구조체 배열입니다. |

### scale(float scaleX, float scaleY) {#scale-float-float-}
```
public void scale(float scaleX, float scaleY)
```


지정된 스케일 벡터를 앞에 추가하여 이 Matrix에 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| scaleX | float | 이 매트릭스를 x축 방향으로 스케일링할 값입니다. |
| scaleY | float | y축 방향으로 이 매트릭스를 스케일링하는 값. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


지정된 순서를 사용하여 지정된 스케일 벡터(scaleX 및 scaleY)를 이 Matrix에 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| scaleX | float | 이 매트릭스를 x축 방향으로 스케일링할 값입니다. |
| scaleY | float | y축 방향으로 이 매트릭스를 스케일링하는 값. |
| order | int | 스케일 벡터가 이 매트릭스에 적용되는 순서(추가 또는 앞에 삽입)를 지정하는 MatrixOrder. |

### shear(float shearX, float shearY) {#shear-float-float-}
```
public void shear(float shearX, float shearY)
```


지정된 전단 변환을 앞에 추가하여 이 Matrix에 지정된 전단 벡터를 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shearX | float | 수평 전단 계수. |
| shearY | float | 수직 전단 계수. |

### shear(float shearX, float shearY, int order) {#shear-float-float-int-}
```
public void shear(float shearX, float shearY, int order)
```


지정된 순서대로 지정된 전단 벡터를 이 Matrix에 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shearX | float | 수평 전단 계수. |
| shearY | float | 수직 전단 계수. |
| order | int | 전단이 적용되는 순서(추가 또는 앞에 삽입)를 지정하는 MatrixOrder. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.drawing.PointF-}
```
public void rotateAt(float angle, PointF point)
```


point 매개변수에 지정된 점을 중심으로 시계 방향 회전을 앞에 추가하여 이 Matrix에 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 각도 | float | 도 단위의 회전 각도(범위). |
| point | [PointF](../../com.aspose.drawing/pointf) | 회전 중심을 나타내는 PointF. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.drawing.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


지정된 순서대로 지정된 점을 중심으로 시계 방향 회전을 이 Matrix에 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 각도 | float | 도 단위의 회전 각도. |
| point | [PointF](../../com.aspose.drawing/pointf) | 회전 중심을 나타내는 PointF. |
| order | int | 회전이 적용되는 순서(추가 또는 앞에 삽입)를 지정하는 MatrixOrder. |

### transformPoints(PointF[] pts) {#transformPoints-com.aspose.drawing.PointF---}
```
public void transformPoints(PointF[] pts)
```


이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)로 표현된 기하 변환을 지정된 점 배열에 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | 변환할 점들을 나타내는 [PointF](../../com.aspose.drawing/pointf) 구조체 배열입니다. |

### transformPoints(Point[] pts) {#transformPoints-com.aspose.drawing.Point---}
```
public void transformPoints(Point[] pts)
```


이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)로 표현된 기하 변환을 지정된 점 배열에 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pts | [Point\[\]](../../com.aspose.drawing/point) | 변환할 점들을 나타내는 [Point](../../com.aspose.drawing/point) 구조체 배열. |

### multiply(Matrix matrix) {#multiply-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiply(Matrix matrix)
```


이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 `matrix` 매개변수에 지정된 매트릭스로 앞에 추가하여 곱합니다(지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 앞에 추가).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 곱할 [Matrix](../../com.aspose.drawing.drawing2d/matrix). |

### multiply(Matrix matrix, int order) {#multiply-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiply(Matrix matrix, int order)
```


이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 `matrix` 매개변수에 지정된 매트릭스로 곱하고, `order` 매개변수에 지정된 순서대로 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 곱할 [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| order | int | 곱셈 순서를 나타내는 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder). |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


원점을 중심으로 지정된 각도만큼 시계 방향 회전을 앞에 추가하여 이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)에 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 각도 | float | 도 단위의 회전 각도. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


angle 매개변수에 지정된 양만큼 원점(좌표 x와 y가 0) 주위에서 시계 방향 회전을 이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)에 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 각도 | float | 도 단위의 회전 각도. |
| order | int | 회전이 이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)에 적용되는 순서(추가 또는 앞에 삽입)를 지정하는 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder). |

### reset() {#reset--}
```
public void reset()
```


이 [Matrix](../../com.aspose.drawing.drawing2d/matrix)를 단위 행렬의 요소로 재설정합니다.

