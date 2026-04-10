---
title: 메타파일
second_title: Aspose.Drawing for Java API 참조
description: 그래픽 메타파일을 정의합니다.
type: docs
weight: 30
url: /ko/java/com.aspose.drawing.imaging/metafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public final class Metafile extends Image
```

그래픽 메타파일을 정의합니다. 메타파일은 기록(구성)되고 재생(표시)될 수 있는 그래픽 작업 순서를 설명하는 레코드를 포함합니다. 이 클래스는 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Metafile(byte[] henhmetafile, boolean deleteEmf)](#Metafile-byte---boolean-) | 지정된 핸들에서 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다. |
| [Metafile(byte[] referenceHdc, int emfType)](#Metafile-byte---int-) | 지정된 핸들을 장치 컨텍스트에 대한 핸들과 [EmfType](../../com.aspose.drawing.imaging/emftype) 열거형(이 열거형은 [Metafile](../../com.aspose.drawing.imaging/metafile)의 형식을 지정함)과 함께 사용하여 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다. |
| [Metafile(String filename)](#Metafile-java.lang.String-) | 지정된 파일 이름에서 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다. |
| [Metafile(String filename, byte[] referenceHdc)](#Metafile-java.lang.String-byte---) | 지정된 파일 이름에서 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다. |
| [Metafile(InputStream stream)](#Metafile-java.io.InputStream-) | 지정된 데이터 스트림에서 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다. |
| [Metafile(InputStream stream, byte[] referenceHdc)](#Metafile-java.io.InputStream-byte---) | 지정된 데이터 스트림과 장치 컨텍스트에 대한 Windows 핸들을 사용하여 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다. |
| [Metafile(System.IO.Stream stream, int type)](#Metafile-com.aspose.ms.System.IO.Stream-int-) | 지정된 데이터 스트림과 장치 컨텍스트에 대한 Windows 핸들을 사용하여 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다. |
| [Metafile(InputStream stream, byte[] referenceHdc, int type)](#Metafile-java.io.InputStream-byte---int-) | 지정된 데이터 스트림, 장치 컨텍스트에 대한 Windows 핸들 및 [EmfType](../../com.aspose.drawing.imaging/emftype) 열거형(이 열거형은 [Metafile](../../com.aspose.drawing.imaging/metafile)의 형식을 지정함)을 사용하여 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다. |
| [Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)](#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-) | 지정된 데이터 스트림, 장치 컨텍스트에 대한 Windows 핸들 및 [EmfType](../../com.aspose.drawing.imaging/emftype) 열거형(이 열거형은 [Metafile](../../com.aspose.drawing.imaging/metafile)의 형식을 지정함)을 사용하여 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWidth()](#getWidth--) | 이 [Metafile](../../com.aspose.drawing.imaging/metafile)의 너비(픽셀)를 가져옵니다. |
| [getHeight()](#getHeight--) | 이 [Metafile](../../com.aspose.drawing.imaging/metafile)의 높이(픽셀)를 가져옵니다. |
| [getRawFormat()](#getRawFormat--) | 이 [Image](../../com.aspose.drawing/image)의 파일 형식을 가져옵니다. |
| [getPixelFormat()](#getPixelFormat--) | 이 [Image](../../com.aspose.drawing/image)의 픽셀 형식을 가져옵니다. |
| [getPalette()](#getPalette--) | 이 [Image](../../com.aspose.drawing/image)에 사용되는 색상 팔레트를 가져오거나 설정합니다. |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | 이 [Image](../../com.aspose.drawing/image)에 사용되는 색상 팔레트를 가져오거나 설정합니다. |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | 이 [Image](../../com.aspose.drawing/image) 내 프레임의 차원을 나타내는 GUID 배열을 가져옵니다. |
| [getPropertyIdList()](#getPropertyIdList--) | 이 [Image](../../com.aspose.drawing/image)에 저장된 속성 항목의 ID를 가져옵니다. |
| [getPropertyItems()](#getPropertyItems--) | 이 [Image](../../com.aspose.drawing/image)에 저장된 모든 속성 항목(메타데이터 조각)을 가져옵니다. |
| [getMetafileHeader(InputStream stream)](#getMetafileHeader-java.io.InputStream-) | 지정된 [Metafile](../../com.aspose.drawing.imaging/metafile)와 연결된 [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader)를 반환합니다. |
| [getMetafileHeader(String fileName)](#getMetafileHeader-java.lang.String-) | 지정된 [Metafile](../../com.aspose.drawing.imaging/metafile)와 연결된 [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader)를 반환합니다. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | 이 메서드는 [Image](../../com.aspose.drawing/image)를 회전하거나 뒤집거나 회전 및 뒤집기를 수행합니다. |
| [getHenhmetafile()](#getHenhmetafile--) | 향상된 [Metafile](../../com.aspose.drawing.imaging/metafile)에 대한 Windows 핸들을 반환합니다. |
| [playRecord(int recordType, int flags, int dataSize, byte[] dataArray)](#playRecord-int-int-int-byte---) | 개별 메타파일 레코드를 재생합니다. |
| [getMetafileHeader()](#getMetafileHeader--) | 이 [Metafile](../../com.aspose.drawing.imaging/metafile)와 연결된 [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader)를 반환합니다. |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | 이 [Image](../../com.aspose.drawing/image)에서 지정된 속성 항목을 가져옵니다. |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | 이 [Image](../../com.aspose.drawing/image)에서 지정된 속성 항목을 제거합니다. |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | 이 [Image](../../com.aspose.drawing/image)에 속성 항목(메타데이터 조각)을 저장합니다. |
### Metafile(byte[] henhmetafile, boolean deleteEmf) {#Metafile-byte---boolean-}
```
public Metafile(byte[] henhmetafile, boolean deleteEmf)
```


지정된 핸들에서 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| henhmetafile | byte[] | 향상된 메타파일에 대한 핸들입니다. |
| deleteEmf | boolean | 향상된 메타파일 핸들을 [Metafile](../../com.aspose.drawing.imaging/metafile)이 삭제될 때 삭제하려면 true; 그렇지 않으면 false. |

### Metafile(byte[] referenceHdc, int emfType) {#Metafile-byte---int-}
```
public Metafile(byte[] referenceHdc, int emfType)
```


지정된 핸들을 장치 컨텍스트에 대한 핸들과 [EmfType](../../com.aspose.drawing.imaging/emftype) 열거형(이 열거형은 [Metafile](../../com.aspose.drawing.imaging/metafile)의 형식을 지정함)과 함께 사용하여 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| referenceHdc | byte[] | 디바이스 컨텍스트에 대한 핸들입니다. |
| emfType | int | [EmfType](../../com.aspose.drawing.imaging/emftype)은 [Metafile](../../com.aspose.drawing.imaging/metafile)의 형식을 지정합니다. |

### Metafile(String filename) {#Metafile-java.lang.String-}
```
public Metafile(String filename)
```


지정된 파일 이름에서 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filename | java.lang.String | 새 [Metafile](../../com.aspose.drawing.imaging/metafile)을 생성할 파일 이름을 나타내는 문자열입니다. |

### Metafile(String filename, byte[] referenceHdc) {#Metafile-java.lang.String-byte---}
```
public Metafile(String filename, byte[] referenceHdc)
```


지정된 파일 이름에서 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filename | java.lang.String | 새 [Metafile](../../com.aspose.drawing.imaging/metafile)을 생성할 파일 이름을 나타내는 문자열입니다. |
| referenceHdc | byte[] | 디바이스 컨텍스트에 대한 Windows 핸들입니다. |

### Metafile(InputStream stream) {#Metafile-java.io.InputStream-}
```
public Metafile(InputStream stream)
```


지정된 데이터 스트림에서 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 새 [Metafile](../../com.aspose.drawing.imaging/metafile)을 생성할 InputStream입니다. |

### Metafile(InputStream stream, byte[] referenceHdc) {#Metafile-java.io.InputStream-byte---}
```
public Metafile(InputStream stream, byte[] referenceHdc)
```


지정된 데이터 스트림과 디바이스 컨텍스트에 대한 Windows 핸들을 사용하여 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 이 [Metafile](../../com.aspose.drawing.imaging/metafile)의 데이터를 포함하는 InputStream입니다. |
| referenceHdc | byte[] | [Metafile](../../com.aspose.drawing.imaging/metafile) 객체의 디바이스 컨텍스트에 대한 Windows 핸들입니다. |

### Metafile(System.IO.Stream stream, int type) {#Metafile-com.aspose.ms.System.IO.Stream-int-}
```
public Metafile(System.IO.Stream stream, int type)
```


지정된 데이터 스트림과 디바이스 컨텍스트에 대한 Windows 핸들을 사용하여 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 이 [Metafile](../../com.aspose.drawing.imaging/metafile)의 데이터를 포함하는 InputStream입니다. |
| type | int | int 1이어야 합니다. |

### Metafile(InputStream stream, byte[] referenceHdc, int type) {#Metafile-java.io.InputStream-byte---int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, int type)
```


지정된 데이터 스트림, 장치 컨텍스트에 대한 Windows 핸들 및 [EmfType](../../com.aspose.drawing.imaging/emftype) 열거형(이 열거형은 [Metafile](../../com.aspose.drawing.imaging/metafile)의 형식을 지정함)을 사용하여 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 이 [Metafile](../../com.aspose.drawing.imaging/metafile)의 데이터를 포함하는 InputStream입니다. |
| referenceHdc | byte[] | 디바이스 컨텍스트에 대한 Windows 핸들입니다. |
| type | int | [EmfType](../../com.aspose.drawing.imaging/emftype)은 [Metafile](../../com.aspose.drawing.imaging/metafile)의 형식을 지정합니다. |

### Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type) {#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)
```


지정된 데이터 스트림, 장치 컨텍스트에 대한 Windows 핸들 및 [EmfType](../../com.aspose.drawing.imaging/emftype) 열거형(이 열거형은 [Metafile](../../com.aspose.drawing.imaging/metafile)의 형식을 지정함)을 사용하여 [Metafile](../../com.aspose.drawing.imaging/metafile) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 이 [Metafile](../../com.aspose.drawing.imaging/metafile)의 데이터를 포함하는 InputStream입니다. |
| referenceHdc | byte[] | 디바이스 컨텍스트에 대한 Windows 핸들입니다. |
| frameRect | [RectangleF](../../com.aspose.drawing/rectanglef) | 새 [Metafile](../../com.aspose.drawing.imaging/metafile)을 둘러싸는 사각형을 나타내는 [Rectangle](../../com.aspose.drawing/rectangle). |
| frameUnit | int | [MetafileFrameUnit](../../com.aspose.drawing.imaging/metafileframeunit)은 frameRect의 측정 단위를 지정합니다. |
| type | int | [EmfType](../../com.aspose.drawing.imaging/emftype)은 [Metafile](../../com.aspose.drawing.imaging/metafile)의 형식을 지정합니다. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


이 [Metafile](../../com.aspose.drawing.imaging/metafile)의 너비(픽셀)를 가져옵니다.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


이 [Metafile](../../com.aspose.drawing.imaging/metafile)의 높이(픽셀)를 가져옵니다.

**Returns:**
int - 이 [Metafile](../../com.aspose.drawing.imaging/metafile)의 높이(픽셀 단위)입니다.
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
### getMetafileHeader(InputStream stream) {#getMetafileHeader-java.io.InputStream-}
```
public static MetafileHeader getMetafileHeader(InputStream stream)
```


지정된 [Metafile](../../com.aspose.drawing.imaging/metafile)와 연결된 [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader)를 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 헤더를 검색할 [Metafile](../../com.aspose.drawing.imaging/metafile)을 포함하는 InputStream입니다. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### getMetafileHeader(String fileName) {#getMetafileHeader-java.lang.String-}
```
public static MetafileHeader getMetafileHeader(String fileName)
```


지정된 [Metafile](../../com.aspose.drawing.imaging/metafile)와 연결된 [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader)를 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 헤더를 검색할 [Metafile](../../com.aspose.drawing.imaging/metafile)의 이름을 포함하는 문자열입니다. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


이 메서드는 [Image](../../com.aspose.drawing/image)를 회전하거나 뒤집거나 회전 및 뒤집기를 수행합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rotateFlipType | int | [RotateFlipType](../../com.aspose.drawing/rotatefliptype) 멤버는 이미지에 적용할 회전 및 뒤집기 유형을 지정합니다. |

### getHenhmetafile() {#getHenhmetafile--}
```
public System.IntPtr getHenhmetafile()
```


향상된 [Metafile](../../com.aspose.drawing.imaging/metafile)에 대한 Windows 핸들을 반환합니다.

**Returns:**
com.aspose.ms.System.IntPtr - 이 향상된 [Metafile](../../com.aspose.drawing.imaging/metafile)에 대한 Windows 핸들입니다.
### playRecord(int recordType, int flags, int dataSize, byte[] dataArray) {#playRecord-int-int-int-byte---}
```
public void playRecord(int recordType, int flags, int dataSize, byte[] dataArray)
```


개별 메타파일 레코드를 재생합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| recordType | int | 재생 중인 메타파일 레코드 유형을 지정하는 [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype)의 요소. |
| flags | int | 레코드의 속성을 지정하는 플래그 집합. |
| dataSize | int | 레코드 데이터의 바이트 수. |
| dataArray | byte[] | 레코드 데이터를 포함하는 바이트 배열. |

### getMetafileHeader() {#getMetafileHeader--}
```
public MetafileHeader getMetafileHeader()
```


이 [Metafile](../../com.aspose.drawing.imaging/metafile)와 연결된 [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader)를 반환합니다.

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile).
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

