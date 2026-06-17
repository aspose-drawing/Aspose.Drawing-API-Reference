---
title: BitmapData
second_title: Aspose.Drawing for Java API 참조
description: 비트맵 이미지의 속성을 지정합니다.
type: docs
weight: 10
url: /ko/java/com.aspose.drawing.imaging/bitmapdata/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapData
```

비트맵 이미지의 속성을 지정합니다. [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) 클래스는 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 `E:Bitmap.LockBits` 및 `M:Bitmap.UnlockBits(BitmapData)` 메서드에서 사용됩니다. 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [BitmapData()](#BitmapData--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWidth()](#getWidth--) | [Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 너비를 가져옵니다. |
| [setWidth(int value)](#setWidth-int-) | [Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 너비를 설정합니다. |
| [getHeight()](#getHeight--) | [Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 높이를 가져옵니다. |
| [setHeight(int value)](#setHeight-int-) | [Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 높이를 설정합니다. |
| [getStride()](#getStride--) | [Bitmap](../../com.aspose.drawing/bitmap) 객체의 스트라이드 너비(스캔 너비라고도 함)를 가져옵니다. |
| [setStride(int value)](#setStride-int-) | [Bitmap](../../com.aspose.drawing/bitmap) 객체의 스트라이드 너비(스캔 너비라고도 함)를 설정합니다. |
| [getPixelFormat()](#getPixelFormat--) | 이 [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) 객체를 반환한 [Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 정보 형식을 가져옵니다. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | 이 [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) 객체를 반환한 [Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 정보 형식을 설정합니다. |
| [getScan0()](#getScan0--) | 비트맵에서 첫 번째 픽셀 데이터의 주소를 가져옵니다. |
| [setScan0(int[] value)](#setScan0-int---) | 비트맵에서 첫 번째 픽셀 데이터의 주소를 설정합니다. |
### BitmapData() {#BitmapData--}
```
public BitmapData()
```


### getWidth() {#getWidth--}
```
public int getWidth()
```


[Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 너비를 가져옵니다. 이는 한 스캔 라인에 있는 픽셀 수로도 생각할 수 있습니다.

**Returns:**
int - [Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 너비.
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


[Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 너비를 설정합니다. 이는 한 스캔 라인의 픽셀 수로도 생각할 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | [Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 너비. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


[Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 높이를 가져옵니다. 또한 스캔 라인 수라고도 합니다.

**Returns:**
int - [Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 높이.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


[Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 높이를 설정합니다. 또한 스캔 라인 수라고도 합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | [Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 높이. |

### getStride() {#getStride--}
```
public int getStride()
```


[Bitmap](../../com.aspose.drawing/bitmap) 객체의 스트라이드 너비(스캔 너비라고도 함)를 가져옵니다.

**Returns:**
int - [Bitmap](../../com.aspose.drawing/bitmap) 객체의 바이트 단위 스트라이드 너비.
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


[Bitmap](../../com.aspose.drawing/bitmap) 객체의 스트라이드 너비(스캔 너비라고도 함)를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | [Bitmap](../../com.aspose.drawing/bitmap) 객체의 스트라이드 너비(스캔 너비라고도 함). |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


이 [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) 객체를 반환한 [Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 정보 형식을 가져옵니다.

**Returns:**
int - 연관된 [Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 정보 형식을 지정하는 `PixelFormat`([.getPixelFormat](../../null/\#getPixelFormat)/[.setPixelFormat(int)](../../null/\#setPixelFormat-int-)).
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


이 [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) 객체를 반환한 [Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 정보 형식을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 이 [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) 객체를 반환한 [Bitmap](../../com.aspose.drawing/bitmap) 객체의 픽셀 정보 형식. |

### getScan0() {#getScan0--}
```
public int[] getScan0()
```


비트맵에서 첫 번째 픽셀 데이터의 주소를 가져옵니다. 이는 비트맵의 첫 번째 스캔 라인으로도 생각할 수 있습니다.

**Returns:**
int[] - 비트맵에서 첫 번째 픽셀 데이터의 주소.
### setScan0(int[] value) {#setScan0-int---}
```
public void setScan0(int[] value)
```


비트맵에서 첫 번째 픽셀 데이터의 주소를 설정합니다. 이는 비트맵의 첫 번째 스캔 라인으로도 생각할 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int[] | 비트맵에서 첫 번째 픽셀 데이터의 주소. |

