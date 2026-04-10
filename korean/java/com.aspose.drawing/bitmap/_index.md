---
title: 비트맵
second_title: Aspose.Drawing for Java API 참조
description: 그래픽 이미지의 픽셀 데이터와 해당 속성으로 구성된 비트맵을 캡슐화합니다.
type: docs
weight: 10
url: /ko/java/com.aspose.drawing/bitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public class Bitmap extends Image
```

그래픽 이미지의 픽셀 데이터와 해당 속성으로 구성된 비트맵을 캡슐화합니다. [Bitmap](../../com.aspose.drawing/bitmap)은 픽셀 데이터로 정의된 이미지를 다루는 데 사용되는 객체입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Bitmap(int width, int height)](#Bitmap-int-int-) | 지정된 크기로 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다. |
| [Bitmap(String filename)](#Bitmap-java.lang.String-) | 지정된 파일에서 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다. |
| [Bitmap(String filename, boolean useIcm)](#Bitmap-java.lang.String-boolean-) | 지정된 파일에서 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다. |
| [Bitmap(InputStream stream)](#Bitmap-java.io.InputStream-) | 지정된 데이터 스트림에서 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다. |
| [Bitmap(InputStream stream, boolean useIcm)](#Bitmap-java.io.InputStream-boolean-) | 지정된 데이터 스트림에서 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다. |
| [Bitmap(int width, int height, int format)](#Bitmap-int-int-int-) | 지정된 크기와 형식으로 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다. |
| [Bitmap(int width, int height, int stride, int format, int[] data)](#Bitmap-int-int-int-int-int---) | 지정된 크기와 픽셀 데이터로 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다. |
| [Bitmap(Image original)](#Bitmap-com.aspose.drawing.Image-) | 지정된 기존 이미지에서 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다. |
| [Bitmap(Image original, Size newSize)](#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-) | 지정된 기존 이미지를 지정된 크기로 스케일링하여 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다. |
| [Bitmap(Image original, int width, int height)](#Bitmap-com.aspose.drawing.Image-int-int-) | 지정된 기존 이미지를 지정된 크기로 스케일링하여 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWidth()](#getWidth--) | 이 비트맵의 너비(픽셀)를 가져옵니다. |
| [getHeight()](#getHeight--) | 이 비트맵의 높이(픽셀)를 가져옵니다. |
| [getRawFormat()](#getRawFormat--) | 이 [Image](../../com.aspose.drawing/image)의 파일 형식을 가져옵니다. |
| [getPixelFormat()](#getPixelFormat--) | 이 [Image](../../com.aspose.drawing/image)의 픽셀 형식을 가져옵니다. |
| [getPalette()](#getPalette--) | 이 [Image](../../com.aspose.drawing/image)에 사용되는 색상 팔레트를 가져오거나 설정합니다. |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | 이 [Image](../../com.aspose.drawing/image)에 사용되는 색상 팔레트를 가져오거나 설정합니다. |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | 이 [Image](../../com.aspose.drawing/image) 내 프레임의 차원을 나타내는 GUID 배열을 가져옵니다. |
| [getPropertyIdList()](#getPropertyIdList--) | 이 [Image](../../com.aspose.drawing/image)에 저장된 속성 항목의 ID를 가져옵니다. |
| [getPropertyItems()](#getPropertyItems--) | 이 [Image](../../com.aspose.drawing/image)에 저장된 모든 속성 항목(메타데이터 조각)을 가져옵니다. |
| [deepClone(Rectangle rect, int format)](#deepClone-com.aspose.drawing.Rectangle-int-) | 이 [Bitmap](../../com.aspose.drawing/bitmap)의 [Rectangle](../../com.aspose.drawing/rectangle) 구조로 정의된 섹션을 지정된 `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 열거형을 사용하여 복사합니다. |
| [deepClone(RectangleF rect, int format)](#deepClone-com.aspose.drawing.RectangleF-int-) | 지정된 [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) 열거형으로 정의된 이 [Bitmap](../../com.aspose.drawing/bitmap)의 섹션을 복사합니다. |
| [setResolution(float xDpi, float yDpi)](#setResolution-float-float-) | 이 [Bitmap](../../com.aspose.drawing/bitmap)의 해상도를 설정합니다. |
| [lockBits(Rectangle rect, int flags, int format)](#lockBits-com.aspose.drawing.Rectangle-int-int-) | 시스템 메모리에 [Bitmap](../../com.aspose.drawing/bitmap)을 잠급니다. |
| [unlockBits(BitmapData bitmapData)](#unlockBits-com.aspose.drawing.imaging.BitmapData-) | 시스템 메모리에서 이 [Bitmap](../../com.aspose.drawing/bitmap)의 잠금을 해제합니다. |
| [getPixel(int x, int y)](#getPixel-int-int-) | 이 [Bitmap](../../com.aspose.drawing/bitmap)에서 지정된 픽셀의 색상을 가져옵니다. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.drawing.Color-) | 이 [Bitmap](../../com.aspose.drawing/bitmap)에서 지정된 픽셀의 색상을 설정합니다. |
| [readArgb32Pixels(int[] pixels)](#readArgb32Pixels-int---) | 주어진 배열에 ARGB32 형식의 비트맵 픽셀을 읽어들입니다. |
| [writeArgb32Pixels(int[] pixels)](#writeArgb32Pixels-int---) | 픽셀을 비트맵에 씁니다. |
| [makeTransparent()](#makeTransparent--) | 이 [Bitmap](../../com.aspose.drawing/bitmap)에서 지정된 색상을 투명하게 만듭니다. |
| [makeTransparent(Color transparentColor)](#makeTransparent-com.aspose.drawing.Color-) | 이 [Bitmap](../../com.aspose.drawing/bitmap)에서 지정된 색상을 투명하게 만듭니다. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | 이 메서드는 [Image](../../com.aspose.drawing/image)를 회전하거나 뒤집거나 회전 및 뒤집기를 수행합니다. |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | 이 [Image](../../com.aspose.drawing/image)에서 지정된 속성 항목을 가져옵니다. |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | 이 [Image](../../com.aspose.drawing/image)에서 지정된 속성 항목을 제거합니다. |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | 이 [Image](../../com.aspose.drawing/image)에 속성 항목(메타데이터 조각)을 저장합니다. |
### Bitmap(int width, int height) {#Bitmap-int-int-}
```
public Bitmap(int width, int height)
```


지정된 크기로 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 너비 | int | 새 Bitmap의 너비(픽셀 단위)입니다. |
|  | 높이 | int | 새 Bitmap의 높이(픽셀 단위)입니다. |

--------------------

현재 지원되는 유일한 내부 비트맵 형식은 `PixelFormat.Format32bppPArgb`와 동일합니다. |

### Bitmap(String filename) {#Bitmap-java.lang.String-}
```
public Bitmap(String filename)
```


지정된 파일에서 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filename | java.lang.String | 비트맵 파일의 이름입니다. |

### Bitmap(String filename, boolean useIcm) {#Bitmap-java.lang.String-boolean-}
```
public Bitmap(String filename, boolean useIcm)
```


지정된 파일에서 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filename | java.lang.String | 비트맵 파일의 이름입니다. |
| useIcm | boolean | 이 [Bitmap](../../com.aspose.drawing/bitmap)에 색 보정을 사용하려면 true, 그렇지 않으면 false. |

### Bitmap(InputStream stream) {#Bitmap-java.io.InputStream-}
```
public Bitmap(InputStream stream)
```


지정된 데이터 스트림에서 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 이미지를 로드하는 데 사용되는 데이터 스트림입니다. |

### Bitmap(InputStream stream, boolean useIcm) {#Bitmap-java.io.InputStream-boolean-}
```
public Bitmap(InputStream stream, boolean useIcm)
```


지정된 데이터 스트림에서 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 이미지를 로드하는 데 사용되는 데이터 스트림입니다. |
| useIcm | boolean | `true`이면 이 [Bitmap](../../com.aspose.drawing/bitmap)에 색 보정을 사용하고, 그렇지 않으면 `false`. |

### Bitmap(int width, int height, int format) {#Bitmap-int-int-int-}
```
public Bitmap(int width, int height, int format)
```


지정된 크기와 형식으로 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| width | int | 새 [Bitmap](../../com.aspose.drawing/bitmap)의 너비(픽셀 단위)입니다. |
| height | int | 새 [Bitmap](../../com.aspose.drawing/bitmap)의 높이(픽셀 단위)입니다. |
| format | int | 새 [Bitmap](../../com.aspose.drawing/bitmap)의 `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 열거형입니다. |

### Bitmap(int width, int height, int stride, int format, int[] data) {#Bitmap-int-int-int-int-int---}
```
public Bitmap(int width, int height, int stride, int format, int[] data)
```


지정된 크기와 픽셀 데이터로 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| width | int | 새 [Bitmap](../../com.aspose.drawing/bitmap)의 너비(픽셀 단위)입니다. |
| height | int | 새 [Bitmap](../../com.aspose.drawing/bitmap)의 높이(픽셀 단위)입니다. |
| stride | int | 한 스캔 라인 시작과 다음 라인 시작 사이의 바이트 오프셋이며, 4의 배수여야 합니다. |
| format | int | 새 [Bitmap](../../com.aspose.drawing/bitmap)의 `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 열거형입니다. |
| 데이터 | int[] | 픽셀 데이터입니다. |

### Bitmap(Image original) {#Bitmap-com.aspose.drawing.Image-}
```
public Bitmap(Image original)
```


지정된 기존 이미지에서 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | 새 [Bitmap](../../com.aspose.drawing/bitmap)을 생성할 [Image](../../com.aspose.drawing/image)입니다. |

### Bitmap(Image original, Size newSize) {#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-}
```
public Bitmap(Image original, Size newSize)
```


지정된 기존 이미지를 지정된 크기로 스케일링하여 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | 새 [Bitmap](../../com.aspose.drawing/bitmap)을 생성할 [Image](../../com.aspose.drawing/image) |
| newSize | [Size](../../com.aspose.drawing/size) | The 새로운 [Bitmap](../../com.aspose.drawing/bitmap)의 크기를 나타내는 `Size`([Image.getSize](../../com.aspose.drawing/image\#getSize)) 구조체. |

### Bitmap(Image original, int width, int height) {#Bitmap-com.aspose.drawing.Image-int-int-}
```
public Bitmap(Image original, int width, int height)
```


지정된 기존 이미지를 지정된 크기로 스케일링하여 [Bitmap](../../com.aspose.drawing/bitmap) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | 새 [Bitmap](../../com.aspose.drawing/bitmap)을 생성할 [Image](../../com.aspose.drawing/image)입니다. |
| width | int | 새 [Bitmap](../../com.aspose.drawing/bitmap)의 너비(픽셀 단위)입니다. |
| height | int | 새 [Bitmap](../../com.aspose.drawing/bitmap)의 높이(픽셀 단위)입니다. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


이 비트맵의 너비(픽셀)를 가져옵니다.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


이 비트맵의 높이(픽셀)를 가져옵니다.

**Returns:**
int
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


이 [Image](../../com.aspose.drawing/image)의 파일 형식을 가져옵니다.

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


이 [Image](../../com.aspose.drawing/image)의 픽셀 형식을 가져옵니다.

**Returns:**
int - 이 [Image](../../com.aspose.drawing/image)의 픽셀 형식을 나타내는 `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)).
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


이 [Image](../../com.aspose.drawing/image)에 사용되는 색상 팔레트를 가져오거나 설정합니다.

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


이 [Image](../../com.aspose.drawing/image)에 사용되는 색상 팔레트를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


이 [Image](../../com.aspose.drawing/image) 내 프레임의 차원을 나타내는 GUID 배열을 가져옵니다.

**Returns:**
java.util.UUID[] - 가장 중요한 것부터 가장 덜 중요한 것까지 이 [Image](../../com.aspose.drawing/image) 내 프레임의 차원을 지정하는 GUID 배열입니다.
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


이 [Image](../../com.aspose.drawing/image)에 저장된 속성 항목의 ID를 가져옵니다.

**Returns:**
int[] - 이 이미지에 저장된 각 속성 항목에 대한 속성 ID 배열입니다.
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


이 [Image](../../com.aspose.drawing/image)에 저장된 모든 속성 항목(메타데이터 조각)을 가져옵니다.

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] - 이미지에 저장된 각 속성 항목에 대한 [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) 객체 배열입니다.
### deepClone(Rectangle rect, int format) {#deepClone-com.aspose.drawing.Rectangle-int-}
```
public final Bitmap deepClone(Rectangle rect, int format)
```


이 [Bitmap](../../com.aspose.drawing/bitmap)의 [Rectangle](../../com.aspose.drawing/rectangle) 구조로 정의된 섹션을 지정된 `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 열거형을 사용하여 복사합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 이 [Bitmap](../../com.aspose.drawing/bitmap)에서 복사할 영역을 정의합니다. 좌표는 이 [Bitmap](../../com.aspose.drawing/bitmap)을 기준으로 합니다. |
| format | int | 대상 [Bitmap](../../com.aspose.drawing/bitmap)의 `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 열거형을 지정합니다. |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The new [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### deepClone(RectangleF rect, int format) {#deepClone-com.aspose.drawing.RectangleF-int-}
```
public final Bitmap deepClone(RectangleF rect, int format)
```


지정된 [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) 열거형으로 정의된 이 [Bitmap](../../com.aspose.drawing/bitmap)의 섹션을 복사합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 이 [Bitmap](../../com.aspose.drawing/bitmap)에서 복사할 영역을 정의합니다. |
| format | int | 대상 [Bitmap](../../com.aspose.drawing/bitmap)의 [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) 열거형을 지정합니다. |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### setResolution(float xDpi, float yDpi) {#setResolution-float-float-}
```
public final void setResolution(float xDpi, float yDpi)
```


이 [Bitmap](../../com.aspose.drawing/bitmap)의 해상도를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xDpi | float | [Bitmap](../../com.aspose.drawing/bitmap)의 가로 해상도(인치당 도트 수)입니다. |
| yDpi | float | [Bitmap](../../com.aspose.drawing/bitmap)의 세로 해상도(인치당 도트 수)입니다. |

### lockBits(Rectangle rect, int flags, int format) {#lockBits-com.aspose.drawing.Rectangle-int-int-}
```
public final BitmapData lockBits(Rectangle rect, int flags, int format)
```


시스템 메모리에 [Bitmap](../../com.aspose.drawing/bitmap)을 잠급니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 잠글 [Bitmap](../../com.aspose.drawing/bitmap)의 영역을 지정하는 [Rectangle](../../com.aspose.drawing/rectangle) 구조체입니다. |
| flags | int | [Bitmap](../../com.aspose.drawing/bitmap)의 접근 수준(읽기/쓰기)을 지정하는 [ImageLockMode](../../com.aspose.drawing.imaging/imagelockmode) 열거형입니다. |
| format | int | 이 [Bitmap](../../com.aspose.drawing/bitmap)의 데이터 형식을 지정하는 `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 열거형입니다. |

**Returns:**
[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) - A [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) containing information about this lock operation.
### unlockBits(BitmapData bitmapData) {#unlockBits-com.aspose.drawing.imaging.BitmapData-}
```
public final void unlockBits(BitmapData bitmapData)
```


시스템 메모리에서 이 [Bitmap](../../com.aspose.drawing/bitmap)의 잠금을 해제합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bitmapData | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) | 잠금 작업에 대한 정보를 지정하는 [BitmapData](../../com.aspose.drawing.imaging/bitmapdata)입니다. |

### getPixel(int x, int y) {#getPixel-int-int-}
```
public final Color getPixel(int x, int y)
```


이 [Bitmap](../../com.aspose.drawing/bitmap)에서 지정된 픽셀의 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | int | 검색할 픽셀의 x 좌표입니다. |
| y | int | 검색할 픽셀의 y 좌표입니다. |

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) structure that represents the color of the specified pixel.
### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.drawing.Color-}
```
public final void setPixel(int x, int y, Color color)
```


이 [Bitmap](../../com.aspose.drawing/bitmap)에서 지정된 픽셀의 색상을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | int | 설정할 픽셀의 x 좌표입니다. |
| y | int | 설정할 픽셀의 y 좌표입니다. |
| color | [Color](../../com.aspose.drawing/color) | 지정된 픽셀에 할당할 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체입니다. |

### readArgb32Pixels(int[] pixels) {#readArgb32Pixels-int---}
```
public final void readArgb32Pixels(int[] pixels)
```


주어진 배열에 ARGB32 형식의 비트맵 픽셀을 읽어들입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 픽셀 | int[] | 비트맵 픽셀을 배치할 배열입니다. 충분한 용량이 있어야 합니다. |

### writeArgb32Pixels(int[] pixels) {#writeArgb32Pixels-int---}
```
public final void writeArgb32Pixels(int[] pixels)
```


픽셀을 비트맵에 씁니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 픽셀 | int[] | ARGB32 형식의 원본 픽셀이 포함된 배열입니다. 충분한 길이가 필요합니다. |

### makeTransparent() {#makeTransparent--}
```
public final void makeTransparent()
```


이 [Bitmap](../../com.aspose.drawing/bitmap)에서 지정된 색상을 투명하게 만듭니다.

### makeTransparent(Color transparentColor) {#makeTransparent-com.aspose.drawing.Color-}
```
public final void makeTransparent(Color transparentColor)
```


이 [Bitmap](../../com.aspose.drawing/bitmap)에서 지정된 색상을 투명하게 만듭니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| transparentColor | [Color](../../com.aspose.drawing/color) | 투명하게 만들 색상을 나타내는 [Color](../../com.aspose.drawing/color) 구조체입니다. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


이 메서드는 [Image](../../com.aspose.drawing/image)를 회전하거나 뒤집거나 회전 및 뒤집기를 수행합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rotateFlipType | int | [RotateFlipType](../../com.aspose.drawing/rotatefliptype) 멤버는 이미지에 적용할 회전 및 뒤집기 유형을 지정합니다. |

### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


이 [Image](../../com.aspose.drawing/image)에서 지정된 속성 항목을 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| propid | int | 가져올 속성 항목의 ID. |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


이 [Image](../../com.aspose.drawing/image)에서 지정된 속성 항목을 제거합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| propid | int | 제거할 속성 항목의 ID. |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


이 [Image](../../com.aspose.drawing/image)에 속성 항목(메타데이터 조각)을 저장합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | 저장될 [PropertyItem](../../com.aspose.drawing.imaging/propertyitem). |

