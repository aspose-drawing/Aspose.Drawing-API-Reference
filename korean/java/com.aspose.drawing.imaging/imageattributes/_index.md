---
title: ImageAttributes
second_title: Aspose.Drawing for Java API 참조
description: 렌더링 중 비트맵 및 메타파일 색상이 어떻게 조작되는지에 대한 정보를 포함합니다.
type: docs
weight: 24
url: /ko/java/com.aspose.drawing.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class ImageAttributes implements System.IDisposable
```

렌더링 중 비트맵 및 메타파일 색상이 어떻게 조작되는지에 대한 정보를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [dispose()](#dispose--) | 이 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 객체가 사용한 모든 리소스를 해제합니다. |
| [deepClone()](#deepClone--) | 이 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 객체의 정확한 복사본을 생성합니다. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | 기본 카테고리에 대한 색상 보정 매트릭스를 설정합니다. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | 기본 카테고리에 대한 색상 보정 매트릭스를 설정합니다. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | 지정된 카테고리에 대한 색상 보정 매트릭스를 설정합니다. |
| [clearColorMatrix()](#clearColorMatrix--) | 기본 카테고리의 색상 조정 매트릭스를 지웁니다. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | 지정된 카테고리의 색상 조정 매트릭스를 지웁니다. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | 기본 카테고리의 색상 조정 매트릭스와 그레이스케일 조정 매트릭스를 설정합니다. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | 기본 카테고리의 색상 조정 매트릭스와 그레이스케일 조정 매트릭스를 설정합니다. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | 지정된 카테고리의 색상 조정 매트릭스와 그레이스케일 조정 매트릭스를 설정합니다. |
| [setThreshold(float threshold)](#setThreshold-float-) | 기본 카테고리의 임계값(투명도 범위)을 설정합니다. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | 지정된 카테고리의 임계값(투명도 범위)을 설정합니다. |
| [clearThreshold()](#clearThreshold--) | 기본 카테고리의 임계값을 지웁니다. |
| [clearThreshold(int type)](#clearThreshold-int-) | 지정된 카테고리의 임계값을 지웁니다. |
| [setGamma(float gamma)](#setGamma-float-) | 기본 카테고리의 감마 값을 설정합니다. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | 지정된 카테고리의 감마 값을 설정합니다. |
| [clearGamma()](#clearGamma--) | 기본 카테고리의 감마 보정을 비활성화합니다. |
| [clearGamma(int type)](#clearGamma-int-) | 지정된 카테고리의 감마 보정을 비활성화합니다. |
| [setNoOp()](#setNoOp--) | 기본 카테고리의 색상 조정을 끕니다. |
| [setNoOp(int type)](#setNoOp-int-) | 지정된 카테고리의 색상 조정을 끕니다. |
| [clearNoOp()](#clearNoOp--) | 기본 카테고리의 NoOp 설정을 지웁니다. |
| [clearNoOp(int type)](#clearNoOp-int-) | 지정된 카테고리의 NoOp 설정을 지웁니다. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-) | 기본 카테고리의 컬러 키를 설정합니다. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | 지정된 카테고리의 컬러 키(투명도 범위)를 설정합니다. |
| [clearColorKey()](#clearColorKey--) | 기본 카테고리의 컬러 키(투명도 범위)를 지웁니다. |
| [clearColorKey(int type)](#clearColorKey-int-) | 지정된 카테고리의 컬러 키(투명도 범위)를 지웁니다. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | 기본 카테고리의 CMYK(시안-마젠타-옐로우-블랙) 출력 채널을 설정합니다. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | 지정된 카테고리의 CMYK(시안-마젠타-옐로우-블랙) 출력 채널을 설정합니다. |
| [clearOutputChannel()](#clearOutputChannel--) | 기본 카테고리의 CMYK(시안-마젠타-옐로우-블랙) 출력 채널 설정을 지웁니다. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | 지정된 카테고리의 (시안-마젠타-옐로우-블랙) 출력 채널 설정을 지웁니다. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | 기본 카테고리의 출력 채널 색상 프로파일 파일을 설정합니다. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | 지정된 카테고리에 대한 출력 채널 색상 프로파일 파일을 설정합니다. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | 기본 카테고리에 대한 출력 채널 색상 프로파일 설정을 지웁니다. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | 지정된 카테고리에 대한 출력 채널 색상 프로파일 설정을 지웁니다. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---) | 기본 카테고리에 대한 색상 재매핑 테이블을 설정합니다. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-) | 지정된 카테고리에 대한 색상 재매핑 테이블을 설정합니다. |
| [clearRemapTable()](#clearRemapTable--) | 기본 카테고리에 대한 색상 재매핑 테이블을 지웁니다. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | 지정된 카테고리에 대한 색상 재매핑 테이블을 지웁니다. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---) | 브러시 카테고리에 대한 색상 재매핑 테이블을 설정합니다. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | 이 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 객체의 브러시 색상 재매핑 테이블을 지웁니다. |
| [setWrapMode(int mode)](#setWrapMode-int-) | 텍스처를 도형 전체에 타일링하거나 도형 경계에서 어떻게 타일링할지 결정하는 데 사용되는 랩 모드를 설정합니다. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.drawing.Color-) | 텍스처를 도형 전체에 타일링하거나 도형 경계에서 어떻게 타일링할지 결정하는 데 사용되는 랩 모드와 색상을 설정합니다. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.drawing.Color-boolean-) | 텍스처를 도형 전체에 타일링하거나 도형 경계에서 어떻게 타일링할지 결정하는 데 사용되는 랩 모드와 색상을 설정합니다. |
| [getAdjustedPalette(ColorPalette palette, int type)](#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-) | 지정된 카테고리의 조정 설정에 따라 팔레트의 색상을 조정합니다. |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


[ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 클래스의 새 인스턴스를 초기화합니다.

### dispose() {#dispose--}
```
public void dispose()
```


이 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 객체가 사용한 모든 리소스를 해제합니다.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


이 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 객체의 정확한 복사본을 생성합니다.

**Returns:**
java.lang.Object - 이 클래스가 생성하는 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 객체를 객체로 캐스팅한 것입니다.
### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


기본 카테고리에 대한 색상 보정 매트릭스를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 색상 조정 매트릭스. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


기본 카테고리에 대한 색상 보정 매트릭스를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 색상 조정 매트릭스. |
| flags | int | [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag)의 요소로, 색상 조정 매트릭스에 의해 영향을 받는 이미지 및 색상의 유형을 지정합니다. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


지정된 카테고리에 대한 색상 보정 매트릭스를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 색상 조정 매트릭스. |
| mode | int | [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag)의 요소로, 색상 조정 매트릭스에 의해 영향을 받는 이미지 및 색상의 유형을 지정합니다. |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype)의 요소로, 색상 조정 매트릭스가 설정되는 카테고리를 지정합니다. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


기본 카테고리의 색상 조정 매트릭스를 지웁니다.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


지정된 카테고리의 색상 조정 매트릭스를 지웁니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype)의 요소로, 색상 조정 매트릭스가 지워지는 카테고리를 지정합니다. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


기본 카테고리의 색상 조정 매트릭스와 그레이스케일 조정 매트릭스를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 색상 조정 매트릭스. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 그레이스케일 조정 매트릭스. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


기본 카테고리의 색상 조정 매트릭스와 그레이스케일 조정 매트릭스를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 색상 조정 매트릭스. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 그레이스케일 조정 매트릭스. |
| flags | int | [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag)의 요소로, 색상 조정 및 그레이스케일 조정 매트릭스에 의해 영향을 받는 이미지 및 색상의 유형을 지정합니다. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


지정된 카테고리의 색상 조정 매트릭스와 그레이스케일 조정 매트릭스를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 색상 조정 매트릭스. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 그레이스케일 조정 매트릭스. |
| mode | int | [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag)의 요소로, 색상 조정 및 그레이스케일 조정 매트릭스에 의해 영향을 받는 이미지 및 색상의 유형을 지정합니다. |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype)의 요소로, 색상 조정 및 그레이스케일 조정 매트릭스가 설정되는 카테고리를 지정합니다. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


기본 카테고리의 임계값(투명도 범위)을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 임계값 | float | 임계값을 지정하는 실수입니다. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


지정된 카테고리의 임계값(투명도 범위)을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 임계값 | float | 0.0에서 1.0 사이의 임계값으로, 최대값 또는 최소값으로 매핑될 색상을 정렬하는 분기점으로 사용됩니다. |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype)의 요소로, 색상 임계값이 설정되는 카테고리를 지정합니다. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


기본 카테고리의 임계값을 지웁니다.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


지정된 카테고리의 임계값을 지웁니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype)의 요소로, 임계값이 지워지는 카테고리를 지정합니다. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


기본 카테고리의 감마 값을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 감마 | float | 감마 보정 값입니다. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


지정된 카테고리의 감마 값을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 감마 | float | 감마 보정 값입니다. |
| type | int | 감마 값이 설정되는 범주를 지정하는 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 열거형의 요소입니다. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


기본 카테고리의 감마 보정을 비활성화합니다.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


지정된 카테고리의 감마 보정을 비활성화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | int | 감마 보정이 비활성화되는 범주를 지정하는 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 요소입니다. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


기본 범주에 대한 색상 조정을 끕니다. [.clearNoOp](../../null/\#clearNoOp) 메서드를 호출하면 [.setNoOp](../../null/\#setNoOp) 메서드를 호출하기 전의 색상 조정 설정을 복원할 수 있습니다.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


지정된 범주에 대한 색상 조정을 끕니다. [.clearNoOp](../../null/\#clearNoOp) 메서드를 호출하면 [.setNoOp](../../null/\#setNoOp) 메서드를 호출하기 전의 색상 조정 설정을 복원할 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | int | 색상 보정이 꺼지는 범주를 지정하는 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 요소입니다. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


기본 카테고리의 NoOp 설정을 지웁니다.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


지정된 카테고리의 NoOp 설정을 지웁니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | int | NoOp 설정이 해제되는 범주를 지정하는 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 요소입니다. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


기본 카테고리의 컬러 키를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | 낮은 컬러 키 값입니다. |
| colorHigh | [Color](../../com.aspose.drawing/color) | 높은 컬러 키 값입니다. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


지정된 카테고리의 컬러 키(투명도 범위)를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | 낮은 컬러 키 값입니다. |
| colorHigh | [Color](../../com.aspose.drawing/color) | 높은 컬러 키 값입니다. |
| type | int | 컬러 키가 설정되는 범주를 지정하는 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 요소입니다. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


기본 카테고리의 컬러 키(투명도 범위)를 지웁니다.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


지정된 카테고리의 컬러 키(투명도 범위)를 지웁니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | int | 컬러 키가 해제되는 범주를 지정하는 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 요소입니다. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


기본 카테고리의 CMYK(시안-마젠타-옐로우-블랙) 출력 채널을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| flags | int | [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) 요소로, 출력 채널을 지정합니다. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


지정된 카테고리의 CMYK(시안-마젠타-옐로우-블랙) 출력 채널을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| flags | int | [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) 요소로, 출력 채널을 지정합니다. |
| type | int | 출력 채널이 설정되는 범주를 지정하는 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 요소입니다. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


기본 카테고리의 CMYK(시안-마젠타-옐로우-블랙) 출력 채널 설정을 지웁니다.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


지정된 카테고리의 (시안-마젠타-옐로우-블랙) 출력 채널 설정을 지웁니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | int | 출력 채널 설정이 해제되는 범주를 지정하는 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 요소입니다. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


기본 카테고리의 출력 채널 색상 프로파일 파일을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | 컬러 프로파일 파일의 경로 이름입니다. 컬러 프로파일 파일이 %SystemRoot%\\System32\\Spool\\Drivers\\Color 디렉터리에 있는 경우 이 매개변수는 파일 이름일 수 있습니다. 그렇지 않으면 이 매개변수는 전체 경로 이름이어야 합니다. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


지정된 카테고리에 대한 출력 채널 색상 프로파일 파일을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | 컬러 프로파일 파일의 경로 이름입니다. 컬러 프로파일 파일이 %SystemRoot%\\System32\\Spool\\Drivers\\Color 디렉터리에 있는 경우 이 매개변수는 파일 이름일 수 있습니다. 그렇지 않으면 이 매개변수는 전체 경로 이름이어야 합니다. |
| type | int | 출력 채널 컬러 프로파일 파일이 설정되는 범주를 지정하는 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 요소입니다. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


기본 카테고리에 대한 출력 채널 색상 프로파일 설정을 지웁니다.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


지정된 카테고리에 대한 출력 채널 색상 프로파일 설정을 지웁니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | int | 출력 채널 프로파일 설정이 해제되는 범주를 지정하는 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 요소입니다. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


기본 카테고리에 대한 색상 재매핑 테이블을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | 타입이 [ColorMap](../../com.aspose.drawing.imaging/colormap)인 색상 쌍 배열입니다. 각 색상 쌍은 기존 색상(첫 번째 값)과 매핑될 색상(두 번째 값)을 포함합니다. |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


지정된 카테고리에 대한 색상 재매핑 테이블을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | 타입이 [ColorMap](../../com.aspose.drawing.imaging/colormap)인 색상 쌍 배열입니다. 각 색상 쌍은 기존 색상(첫 번째 값)과 매핑될 색상(두 번째 값)을 포함합니다. |
| type | int | 색상 재매핑 테이블이 설정되는 범주를 지정하는 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 요소입니다. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


기본 카테고리에 대한 색상 재매핑 테이블을 지웁니다.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


지정된 카테고리에 대한 색상 재매핑 테이블을 지웁니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | int | 재매핑 테이블이 해제되는 범주를 지정하는 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 요소입니다. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


브러시 카테고리에 대한 색상 재매핑 테이블을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | [ColorMap](../../com.aspose.drawing.imaging/colormap) 객체 배열입니다. |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


이 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 객체의 브러시 색상 재매핑 테이블을 지웁니다.

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


텍스처를 도형 전체 또는 도형 경계에 타일링하는 방법을 결정하는 랩 모드를 설정합니다. 텍스처가 채우려는 도형보다 작을 때 텍스처가 도형 전체에 타일링되어 채워집니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mode | int | [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) 요소로, 이미지의 반복 복사본이 영역에 타일링되는 방식을 지정합니다. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.drawing.Color-}
```
public void setWrapMode(int mode, Color color)
```


텍스처를 도형 전체에 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드와 색상을 설정합니다. 텍스처가 도형보다 작을 때 텍스처가 도형을 채우도록 타일링됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mode | int | [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) 요소로, 이미지의 반복 복사본이 영역에 타일링되는 방식을 지정합니다. |
| color | [Color](../../com.aspose.drawing/color) | [Color](../../com.aspose.drawing/color) 객체는 렌더링된 이미지 외부 픽셀의 색상을 지정합니다. 이 색상은 mode 매개변수가 `WrapMode.Clamp` 로 설정되고 `Graphics.DrawImage`에 전달된 소스 사각형이 이미지 자체보다 클 때 표시됩니다. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.drawing.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


텍스처를 도형 전체에 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드와 색상을 설정합니다. 텍스처가 도형보다 작을 때 텍스처가 도형을 채우도록 타일링됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mode | int | [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) 요소로, 이미지의 반복 복사본이 영역에 타일링되는 방식을 지정합니다. |
| color | [Color](../../com.aspose.drawing/color) | 색상 객체는 렌더링된 이미지 외부 픽셀의 색상을 지정합니다. 이 색상은 mode 매개변수가 `WrapMode.Clamp` 로 설정되고 `Graphics.DrawImage`에 전달된 소스 사각형이 이미지 자체보다 클 때 표시됩니다. |
| 클램프 | boolean | 이 매개변수는 효과가 없습니다. false 로 설정하십시오. |

### getAdjustedPalette(ColorPalette palette, int type) {#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-}
```
public void getAdjustedPalette(ColorPalette palette, int type)
```


지정된 카테고리의 조정 설정에 따라 팔레트의 색상을 조정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| palette | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) 은 입력 시 조정될 팔레트를 포함하고, 출력 시 조정된 팔레트를 포함합니다. |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 의 요소로, 팔레트에 적용될 조정 설정이 있는 카테고리를 지정합니다. |

