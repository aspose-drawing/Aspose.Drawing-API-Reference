---
title: TextureBrush
second_title: Aspose.Drawing for Java API 참조
description: 각 속성은 TextureBrush 클래스의 Brush 객체이며, 이미지를 사용해 도형 내부를 채웁니다.
type: docs
weight: 53
url: /ko/java/com.aspose.drawing/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class TextureBrush extends Brush
```

TextureBrush 클래스의 각 속성은 이미지를 사용하여 도형 내부를 채우는 Brush 객체입니다. 이 클래스는 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TextureBrush(Image bitmap)](#TextureBrush-com.aspose.drawing.Image-) | 지정된 이미지를 사용하는 [TextureBrush](../../com.aspose.drawing/texturebrush) 클래스의 새 인스턴스를 초기화합니다. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.drawing.Image-int-) | 지정된 이미지와 랩 모드를 사용하는 [TextureBrush](../../com.aspose.drawing/texturebrush) 클래스의 새 인스턴스를 초기화합니다. |
| [TextureBrush(Image image, int wrapMode, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-) | 지정된 이미지, 랩 모드 및 경계 사각형을 사용하는 [TextureBrush](../../com.aspose.drawing/texturebrush) 클래스의 새 인스턴스를 초기화합니다. |
| [TextureBrush(Image image, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-) | 지정된 이미지와 경계 사각형을 사용하는 [TextureBrush](../../com.aspose.drawing/texturebrush) 클래스의 새 인스턴스를 초기화합니다. |
| [TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-) | 지정된 이미지, 경계 사각형 및 이미지 속성을 사용하는 [TextureBrush](../../com.aspose.drawing/texturebrush) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getImage()](#getImage--) | 이 TextureBrush 객체와 연결된 Image 객체를 가져옵니다. |
| [getTransform()](#getTransform--) | 이 TextureBrush 객체와 연결된 이미지에 대한 로컬 기하 변환을 정의하는 Matrix 객체의 복사본을 가져옵니다. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | 이 TextureBrush 객체와 연결된 이미지에 대한 로컬 기하 변환을 정의하는 Matrix 객체의 복사본을 설정합니다. |
| [getWrapMode()](#getWrapMode--) | 이 TextureBrush 객체의 랩 모드를 나타내는 WrapMode 열거형을 가져옵니다. |
| [setWrapMode(int value)](#setWrapMode-int-) | 이 TextureBrush 객체의 랩 모드를 나타내는 WrapMode 열거형을 설정합니다. |
| [deepClone()](#deepClone--) | 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 정확한 복사본을 생성합니다. |
| [resetTransform()](#resetTransform--) | 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 Transform 속성을 기본값(항등)으로 재설정합니다. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환을 나타내는 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 객체에 지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 객체를 앞에 추가하여 곱합니다. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환을 나타내는 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 객체에 지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 객체를 지정된 순서대로 곱합니다. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 지정된 치수만큼 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환을 이동합니다. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 지정된 치수를 지정된 순서대로 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환에 적용하여 이동합니다. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 지정된 양만큼 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환을 확대/축소합니다. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 지정된 양을 지정된 순서대로 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환에 적용하여 확대/축소합니다. |
| [rotateTransform(float angle)](#rotateTransform-float-) | 지정된 각도만큼 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환을 회전합니다. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 지정된 각도를 지정된 순서대로 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환에 적용하여 회전합니다. |
### TextureBrush(Image bitmap) {#TextureBrush-com.aspose.drawing.Image-}
```
public TextureBrush(Image bitmap)
```


지정된 이미지를 사용하는 [TextureBrush](../../com.aspose.drawing/texturebrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bitmap | [Image](../../com.aspose.drawing/image) | `Image`([.getImage](../../null/\#getImage)) 객체로, 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체가 내부를 채우는 데 사용됩니다. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.drawing.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


지정된 이미지와 랩 모드를 사용하는 [TextureBrush](../../com.aspose.drawing/texturebrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | 이미지. |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) 열거형으로, 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체가 타일링되는 방식을 지정합니다. |

### TextureBrush(Image image, int wrapMode, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF dstRect)
```


지정된 이미지, 랩 모드 및 경계 사각형을 사용하는 [TextureBrush](../../com.aspose.drawing/texturebrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | 이미지. |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) 열거형으로, 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체가 타일링되는 방식을 지정합니다. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | [RectangleF](../../com.aspose.drawing/rectanglef) 구조체로, 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 경계 사각형을 나타냅니다. |

### TextureBrush(Image image, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, RectangleF dstRect)
```


지정된 이미지와 경계 사각형을 사용하는 [TextureBrush](../../com.aspose.drawing/texturebrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | `Image`([.getImage](../../null/\#getImage)) 객체로, 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체가 내부를 채우는 데 사용됩니다. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | [RectangleF](../../com.aspose.drawing/rectanglef) 구조체로, 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 경계 사각형을 나타냅니다. |

### TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)
```


지정된 이미지, 경계 사각형 및 이미지 속성을 사용하는 [TextureBrush](../../com.aspose.drawing/texturebrush) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | 이 TextureBrush 객체가 내부를 채우는 Image 객체. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | 이 TextureBrush 객체의 경계 사각형을 나타내는 RectangleF 구조체. |
| imageAttr | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) | 이 TextureBrush 객체에서 사용되는 이미지에 대한 추가 정보를 포함하는 ImageAttributes 객체. |

### getImage() {#getImage--}
```
public Image getImage()
```


이 TextureBrush 객체와 연결된 Image 객체를 가져옵니다.

**Returns:**
[Image](../../com.aspose.drawing/image) - the Image object associated with this TextureBrush object.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


이 TextureBrush 객체와 연결된 이미지에 대한 로컬 기하 변환을 정의하는 Matrix 객체의 복사본을 가져옵니다.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - a copy of the Matrix object that defines a local geometric transformation for the image associated with this TextureBrush object.
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


이 TextureBrush 객체와 연결된 이미지에 대한 로컬 기하 변환을 정의하는 Matrix 객체의 복사본을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 이 TextureBrush 객체와 연결된 이미지에 대한 로컬 기하 변환을 정의하는 Matrix 객체의 복사본을 가져옵니다. |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


이 TextureBrush 객체의 랩 모드를 나타내는 WrapMode 열거형을 가져옵니다.

**Returns:**
int - 이 TextureBrush 객체의 랩 모드를 나타내는 WrapMode 열거형입니다.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


이 TextureBrush 객체의 랩 모드를 나타내는 WrapMode 열거형을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 이 TextureBrush 객체의 랩 모드를 나타내는 WrapMode 열거형. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 정확한 복사본을 생성합니다.

**Returns:**
java.lang.Object - 이 메서드가 생성하는 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체를 Object 객체로 캐스팅한 것입니다.
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 Transform 속성을 기본값(항등)으로 재설정합니다.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환을 나타내는 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 객체에 지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 객체를 앞에 추가하여 곱합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 기하학적 변환을 곱할 때 사용하는 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 객체입니다. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환을 나타내는 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 객체에 지정된 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 객체를 지정된 순서대로 곱합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 기하학적 변환을 곱할 때 사용하는 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 객체입니다. |
| order | int | 두 행렬을 곱하는 순서를 지정하는 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) 열거형입니다. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환을 지정된 차원만큼 이동시킵니다. 이 메서드는 변환 앞에 이동을 추가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dx | float | x 방향으로 변환을 이동시킬 차원입니다. |
| dy | float | y 방향으로 변환을 이동시킬 차원입니다. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


지정된 치수를 지정된 순서대로 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환에 적용하여 이동합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dx | float | x 방향으로 변환을 이동시킬 차원입니다. |
| dy | float | y 방향으로 변환을 이동시킬 차원입니다. |
| order | int | 평행 이동을 적용할 순서(앞에 추가 또는 뒤에 추가)입니다. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환을 지정된 양만큼 스케일링합니다. 이 메서드는 변환 앞에 스케일링 행렬을 추가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sx | float | x 방향으로 변환을 스케일링할 양입니다. |
| sy | float | y 방향으로 변환을 스케일링할 양입니다. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


지정된 양을 지정된 순서대로 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환에 적용하여 확대/축소합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sx | float | x 방향으로 변환을 스케일링할 양입니다. |
| sy | float | y 방향으로 변환을 스케일링할 양입니다. |
| order | int | 스케일링 행렬을 추가하거나 앞에 삽입할지를 지정하는 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) 열거형입니다. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환을 지정된 각도만큼 회전시킵니다. 이 메서드는 변환 앞에 회전을 추가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


지정된 각도를 지정된 순서대로 이 [TextureBrush](../../com.aspose.drawing/texturebrush) 객체의 로컬 기하 변환에 적용하여 회전합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도. |
| order | int | 회전 행렬을 추가하거나 앞에 삽입할지를 지정하는 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) 열거형입니다. |

