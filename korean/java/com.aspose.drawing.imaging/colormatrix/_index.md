---
title: ColorMatrix
second_title: Aspose.Drawing for Java API 참조
description: RGBA 공간의 좌표를 포함하는 5 x 5 행렬을 정의합니다.
type: docs
weight: 14
url: /ko/java/com.aspose.drawing.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

RGBA 공간의 좌표를 포함하는 5 x 5 행렬을 정의합니다. [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 클래스의 여러 메서드는 컬러 매트릭스를 사용하여 이미지 색상을 조정합니다. 이 클래스는 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | 새로운 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) 클래스 인스턴스를 초기화합니다. |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | 지정된 행렬 `newColorMatrix`의 요소를 사용하여 새로운 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0(영) 행 및 0 열에 있는 요소를 가져옵니다. |
| [setMatrix00(float value)](#setMatrix00-float-) | 이 [ColorMatrix](../../com.aspose.drawing/colormatrix)의 0(영) 행 및 0 열에 있는 요소를 설정합니다. |
| [getMatrix01()](#getMatrix01--) | 이 [ColorMatrix](../../com.aspose.drawing/colormatrix)의 0(영) 행 및 첫 번째 열에 있는 요소를 가져옵니다. |
| [setMatrix01(float value)](#setMatrix01-float-) | 이 [ColorMatrix](../../com.aspose.drawing/colormatrix)의 0(영) 행 및 첫 번째 열에 있는 요소를 설정합니다. |
| [getMatrix02()](#getMatrix02--) | 이 [ColorMatrix](../../com.aspose.drawing/colormatrix)의 0(영) 행 및 두 번째 열에 있는 요소를 가져옵니다. |
| [setMatrix02(float value)](#setMatrix02-float-) | 이 [ColorMatrix](../../com.aspose.drawing/colormatrix)의 0(영) 행 및 두 번째 열에 있는 요소를 설정합니다. |
| [getMatrix03()](#getMatrix03--) | 이 [ColorMatrix](../../com.aspose.drawing/colormatrix)의 0(영) 행 및 세 번째 열에 있는 요소를 가져옵니다. |
| [setMatrix03(float value)](#setMatrix03-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0(제로) 행 및 세 번째 열에 요소를 설정합니다. |
| [getMatrix04()](#getMatrix04--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0(제로) 행 및 네 번째 열에서 요소를 가져옵니다. |
| [setMatrix04(float value)](#setMatrix04-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0(제로) 행 및 네 번째 열에 요소를 설정합니다. |
| [getMatrix10()](#getMatrix10--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 0(제로) 열에서 요소를 가져옵니다. |
| [setMatrix10(float value)](#setMatrix10-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 0(제로) 열에 요소를 설정합니다. |
| [getMatrix11()](#getMatrix11--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 첫 번째 열에서 요소를 가져옵니다. |
| [setMatrix11(float value)](#setMatrix11-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 첫 번째 열에 요소를 설정합니다. |
| [getMatrix12()](#getMatrix12--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 두 번째 열에서 요소를 가져옵니다. |
| [setMatrix12(float value)](#setMatrix12-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 두 번째 열에 요소를 설정합니다. |
| [getMatrix13()](#getMatrix13--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 세 번째 열에서 요소를 가져옵니다. |
| [setMatrix13(float value)](#setMatrix13-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 세 번째 열에 요소를 설정합니다. |
| [getMatrix14()](#getMatrix14--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 네 번째 열에서 요소를 가져옵니다. |
| [setMatrix14(float value)](#setMatrix14-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 네 번째 열에 요소를 설정합니다. |
| [getMatrix20()](#getMatrix20--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 0(제로) 열에서 요소를 가져옵니다. |
| [setMatrix20(float value)](#setMatrix20-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 0(제로) 열에 요소를 설정합니다. |
| [getMatrix21()](#getMatrix21--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 첫 번째 열에서 요소를 가져옵니다. |
| [setMatrix21(float value)](#setMatrix21-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 첫 번째 열에 요소를 설정합니다. |
| [getMatrix22()](#getMatrix22--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 두 번째 열에서 요소를 가져옵니다. |
| [setMatrix22(float value)](#setMatrix22-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 두 번째 열에 요소를 설정합니다. |
| [getMatrix23()](#getMatrix23--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 세 번째 열에서 요소를 가져옵니다. |
| [setMatrix23(float value)](#setMatrix23-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 세 번째 열에 요소를 설정합니다. |
| [getMatrix24()](#getMatrix24--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 네 번째 열에서 요소를 가져옵니다. |
| [setMatrix24(float value)](#setMatrix24-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 네 번째 열에 요소를 설정합니다. |
| [getMatrix30()](#getMatrix30--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 0(제로) 열에서 요소를 가져옵니다. |
| [setMatrix30(float value)](#setMatrix30-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 0(제로) 열에 요소를 설정합니다. |
| [getMatrix31()](#getMatrix31--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 첫 번째 열에 있는 요소를 가져옵니다. |
| [setMatrix31(float value)](#setMatrix31-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 첫 번째 열에 있는 요소를 설정합니다. |
| [getMatrix32()](#getMatrix32--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 두 번째 열에 있는 요소를 가져옵니다. |
| [setMatrix32(float value)](#setMatrix32-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 두 번째 열에 있는 요소를 설정합니다. |
| [getMatrix33()](#getMatrix33--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 세 번째 열에 있는 요소를 가져옵니다. |
| [setMatrix33(float value)](#setMatrix33-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 세 번째 열에 있는 요소를 설정합니다. |
| [getMatrix34()](#getMatrix34--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 네 번째 열에 있는 요소를 가져옵니다. |
| [setMatrix34(float value)](#setMatrix34-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 네 번째 열에 있는 요소를 설정합니다. |
| [getMatrix40()](#getMatrix40--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 0(영) 열에 있는 요소를 가져옵니다. |
| [setMatrix40(float value)](#setMatrix40-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 0(영) 열에 있는 요소를 설정합니다. |
| [getMatrix41()](#getMatrix41--) | 이 `.ColorMatrix`의 네 번째 행 및 첫 번째 열에 있는 요소를 가져옵니다. |
| [setMatrix41(float value)](#setMatrix41-float-) | 이 `.ColorMatrix`의 네 번째 행 및 첫 번째 열에 있는 요소를 설정합니다. |
| [getMatrix42()](#getMatrix42--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 두 번째 열에 있는 요소를 가져옵니다. |
| [setMatrix42(float value)](#setMatrix42-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 두 번째 열에 있는 요소를 설정합니다. |
| [getMatrix43()](#getMatrix43--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 세 번째 열에 있는 요소를 가져옵니다. |
| [setMatrix43(float value)](#setMatrix43-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 세 번째 열에 있는 요소를 설정합니다. |
| [getMatrix44()](#getMatrix44--) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 네 번째 열에 있는 요소를 가져옵니다. |
| [setMatrix44(float value)](#setMatrix44-float-) | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 네 번째 열에 있는 요소를 설정합니다. |
| [get_Item(int row, int column)](#get-Item-int-int-) | 지정된 행 및 열에 있는 요소를 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)에서 가져옵니다. |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | 지정된 행 및 열에 있는 요소를 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)에서 설정합니다. |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


새로운 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) 클래스 인스턴스를 초기화합니다.

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


지정된 행렬 `newColorMatrix`의 요소를 사용하여 새로운 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| newColorMatrix | float[][] | 새 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 요소 값들입니다. |

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0(영) 행 및 0 열에 있는 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0(영) 행 및 0 열에 있는 요소.
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


이 [ColorMatrix](../../com.aspose.drawing/colormatrix)의 0(영) 행 및 0 열에 있는 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0(영) 행 및 0 열에 있는 요소. |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


이 [ColorMatrix](../../com.aspose.drawing/colormatrix)의 0(영) 행 및 첫 번째 열에 있는 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0(영) 행 및 첫 번째 열에 있는 요소.
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


이 [ColorMatrix](../../com.aspose.drawing/colormatrix)의 0(영) 행 및 첫 번째 열에 있는 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0(영) 행 및 첫 번째 열에 있는 요소. |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


이 [ColorMatrix](../../com.aspose.drawing/colormatrix)의 0(영) 행 및 두 번째 열에 있는 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0 (zero) 행 및 두 번째 열에 있는 요소.
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


이 [ColorMatrix](../../com.aspose.drawing/colormatrix)의 0(영) 행 및 두 번째 열에 있는 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0 (zero) 행 및 두 번째 열에 있는 요소. |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


이 [ColorMatrix](../../com.aspose.drawing/colormatrix)의 0(영) 행 및 세 번째 열에 있는 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0 (zero) 행 및 세 번째 열에 있는 요소.
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0(제로) 행 및 세 번째 열에 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0 (zero) 행 및 세 번째 열에 있는 요소. |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0(제로) 행 및 네 번째 열에서 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0 (zero) 행 및 네 번째 열에 있는 요소.
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0(제로) 행 및 네 번째 열에 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 0 (zero) 행 및 네 번째 열에 있는 요소. |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 0(제로) 열에서 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 0 (zero) 열에 있는 요소.
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 0(제로) 열에 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 0 (zero) 열에 있는 요소. |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 첫 번째 열에서 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 첫 번째 열에 있는 요소.
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 첫 번째 열에 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 첫 번째 열에 있는 요소. |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 두 번째 열에서 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 두 번째 열에 있는 요소.
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 두 번째 열에 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 두 번째 열에 있는 요소. |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 세 번째 열에서 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 세 번째 열에 있는 요소.
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 세 번째 열에 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 세 번째 열에 있는 요소. |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 네 번째 열에서 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 네 번째 열에 있는 요소.
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 네 번째 열에 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 첫 번째 행 및 네 번째 열에 있는 요소. |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 0(제로) 열에서 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 0 (zero) 열에 있는 요소.
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 0(제로) 열에 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 0 (zero) 열에 있는 요소. |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 첫 번째 열에서 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 첫 번째 열에 있는 요소.
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 첫 번째 열에 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 첫 번째 열에 있는 요소. |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 두 번째 열에서 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 두 번째 열에 있는 요소.
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 두 번째 열에 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 두 번째 열에 있는 요소. |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 세 번째 열에서 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 세 번째 열에 있는 요소.
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 세 번째 열에 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 세 번째 열에 있는 요소. |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 네 번째 열에서 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 네 번째 열에 있는 요소.
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 네 번째 열에 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 두 번째 행 및 네 번째 열에 있는 요소. |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 0(제로) 열에서 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 0 (영) 열에 있는 요소.
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 0(제로) 열에 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 0 (영) 열에 있는 요소. |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 첫 번째 열에 있는 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 첫 번째 열에 있는 요소.
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 첫 번째 열에 있는 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 첫 번째 열에 있는 요소. |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 두 번째 열에 있는 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 두 번째 열에 있는 요소.
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 두 번째 열에 있는 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 두 번째 열에 있는 요소. |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 세 번째 열에 있는 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 세 번째 열에 있는 요소.
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 세 번째 열에 있는 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 세 번째 열에 있는 요소. |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 네 번째 열에 있는 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 네 번째 열에 있는 요소.
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 네 번째 열에 있는 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 세 번째 행 및 네 번째 열에 있는 요소. |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 0(영) 열에 있는 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 0 (영) 열에 있는 요소.
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 0(영) 열에 있는 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 0 (영) 열에 있는 요소. |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


이 `.ColorMatrix`의 네 번째 행 및 첫 번째 열에 있는 요소를 가져옵니다.

**Returns:**
float - 이 `.ColorMatrix`의 네 번째 행 및 첫 번째 열에 있는 요소.
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


이 `.ColorMatrix`의 네 번째 행 및 첫 번째 열에 있는 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 `.ColorMatrix`의 네 번째 행 및 첫 번째 열에 있는 요소. |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 두 번째 열에 있는 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 두 번째 열에 있는 요소.
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 두 번째 열에 있는 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 두 번째 열에 있는 요소. |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 세 번째 열에 있는 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 세 번째 열에 있는 요소.
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 세 번째 열에 있는 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 세 번째 열에 있는 요소. |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 네 번째 열에 있는 요소를 가져옵니다.

**Returns:**
float - 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 네 번째 열에 있는 요소.
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 네 번째 열에 있는 요소를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float | 이 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)의 네 번째 행 및 네 번째 열에 있는 요소. |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


지정된 행 및 열에 있는 요소를 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)에서 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 행 | int | 요소의 행. |
| 열 | int | 요소의 열. |

**Returns:**
float - 지정된 행과 열에 있는 요소.
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


지정된 행 및 열에 있는 요소를 [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)에서 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 행 | int | 요소의 행. |
| 열 | int | 요소의 열. |
| value | float | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix)에서 지정된 행과 열에 있는 요소. |

