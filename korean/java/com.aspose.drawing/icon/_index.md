---
title: 아이콘
second_title: Aspose.Drawing for Java API 참조
description: Windows 아이콘을 나타내며, 객체를 나타내는 작은 비트맵 이미지입니다.
type: docs
weight: 29
url: /ko/java/com.aspose.drawing/icon/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.ms.System.IDisposable
```
public final class Icon implements System.ICloneable, System.IDisposable
```

Windows 아이콘을 나타내며, 이는 객체를 나타내는 작은 비트맵 이미지입니다. 아이콘은 투명 비트맵으로 생각할 수 있지만, 크기는 시스템에 의해 결정됩니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Icon(String fileName)](#Icon-java.lang.String-) | 지정된 파일 이름에서 [Icon](../../com.aspose.drawing/icon) 클래스의 새 인스턴스를 초기화합니다. |
| [Icon(InputStream stream)](#Icon-java.io.InputStream-) | 지정된 데이터 스트림에서 [Icon](../../com.aspose.drawing/icon) 클래스의 새 인스턴스를 초기화합니다. |
| [Icon(String fileName, Size size)](#Icon-java.lang.String-com.aspose.drawing.Size-) | 지정된 파일에서 지정된 크기의 [Icon](../../com.aspose.drawing/icon) 클래스 새 인스턴스를 초기화합니다. |
| [Icon(Icon original, Size size)](#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-) | [Icon](../../com.aspose.drawing/icon) 클래스의 새 인스턴스를 초기화하고 요청된 크기에 맞는 아이콘 버전을 찾으려고 시도합니다. |
| [Icon(Object type, String resource)](#Icon-java.lang.Object-java.lang.String-) | 지정된 어셈블리의 리소스에서 [Icon](../../com.aspose.drawing/icon) 클래스의 새 인스턴스를 초기화합니다. |
| [Icon(InputStream stream, Size size)](#Icon-java.io.InputStream-com.aspose.drawing.Size-) | 지정된 스트림에서 지정된 크기의 [Icon](../../com.aspose.drawing/icon) 클래스 새 인스턴스를 초기화합니다. |
| [Icon(String fileName, int width, int height)](#Icon-java.lang.String-int-int-) | 지정된 파일에서 지정된 너비와 높이로 [Icon](../../com.aspose.drawing/icon) 클래스를 새 인스턴스로 초기화합니다. |
| [Icon(Icon original, int width, int height)](#Icon-com.aspose.drawing.Icon-int-int-) | 새 인스턴스로 [Icon](../../com.aspose.drawing/icon) 클래스를 초기화하고 요청된 크기에 맞는 아이콘 버전을 찾으려고 시도합니다. |
| [Icon(InputStream stream, int width, int height)](#Icon-java.io.InputStream-int-int-) | 지정된 데이터 스트림에서 [Icon](../../com.aspose.drawing/icon) 클래스를 새 인스턴스로 초기화하고 지정된 너비와 높이를 적용합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHandle()](#getHandle--) | 이 [Icon](../../com.aspose.drawing/icon)의 핸들을 가져옵니다. |
| [getHeight()](#getHeight--) | 이 [Icon](../../com.aspose.drawing/icon)의 높이를 가져옵니다. |
| [getSize()](#getSize--) | 이 [Icon](../../com.aspose.drawing/icon)의 크기를 가져옵니다. |
| [getWidth()](#getWidth--) | 이 [Icon](../../com.aspose.drawing/icon)의 너비를 가져옵니다. |
| [extractAssociatedIcon(String filePath)](#extractAssociatedIcon-java.lang.String-) | 지정된 파일에 포함된 이미지의 아이콘 표현을 반환합니다. |
| [fromHandle(byte[] handle)](#fromHandle-byte---) | 지정된 아이콘 Windows 핸들(HICON)에서 GDI+ [Icon](../../com.aspose.drawing/icon)을 생성합니다. |
| [deepClone()](#deepClone--) | [Icon](../../com.aspose.drawing/icon)을 복제하여 중복 이미지를 생성합니다. |
| [dispose()](#dispose--) | 관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | 이 [Icon](../../com.aspose.drawing/icon)을 지정된 출력 java.io.InputStream에 저장합니다. |
| [toBitmap()](#toBitmap--) | 이 [Icon](../../com.aspose.drawing/icon)을 GDI+ [Bitmap](../../com.aspose.drawing/bitmap)으로 변환합니다. |
| [toString()](#toString--) | [Icon](../../com.aspose.drawing/icon)을 설명하는 사람이 읽을 수 있는 문자열을 가져옵니다. |
### Icon(String fileName) {#Icon-java.lang.String-}
```
public Icon(String fileName)
```


지정된 파일 이름에서 [Icon](../../com.aspose.drawing/icon) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | [Icon](../../com.aspose.drawing/icon)을 로드할 파일입니다. |

### Icon(InputStream stream) {#Icon-java.io.InputStream-}
```
public Icon(InputStream stream)
```


지정된 데이터 스트림에서 [Icon](../../com.aspose.drawing/icon) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | [Icon](../../com.aspose.drawing/icon)을 로드할 데이터 스트림입니다. |

### Icon(String fileName, Size size) {#Icon-java.lang.String-com.aspose.drawing.Size-}
```
public Icon(String fileName, Size size)
```


지정된 파일에서 지정된 크기의 [Icon](../../com.aspose.drawing/icon) 클래스 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 아이콘 데이터를 포함하는 파일의 이름과 경로입니다. |
| size | [Size](../../com.aspose.drawing/size) | 아이콘의 원하는 크기입니다. |

### Icon(Icon original, Size size) {#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-}
```
public Icon(Icon original, Size size)
```


[Icon](../../com.aspose.drawing/icon) 클래스의 새 인스턴스를 초기화하고 요청된 크기에 맞는 아이콘 버전을 찾으려고 시도합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | 새로 크기가 조정된 아이콘을 로드할 [Icon](../../com.aspose.drawing/icon)입니다. |
| size | [Size](../../com.aspose.drawing/size) | 새 [Icon](../../com.aspose.drawing/icon)의 높이와 너비를 지정하는 `Size`([.getSize](../../null/\#getSize)) 구조체입니다. |

### Icon(Object type, String resource) {#Icon-java.lang.Object-java.lang.String-}
```
public Icon(Object type, String resource)
```


지정된 어셈블리의 리소스에서 [Icon](../../com.aspose.drawing/icon) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | java.lang.Object | 리소스를 찾을 어셈블리를 지정하는 Type입니다. |
| 리소스 | java.lang.String | 로드할 리소스 이름입니다. |

### Icon(InputStream stream, Size size) {#Icon-java.io.InputStream-com.aspose.drawing.Size-}
```
public Icon(InputStream stream, Size size)
```


지정된 스트림에서 지정된 크기의 [Icon](../../com.aspose.drawing/icon) 클래스 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 아이콘 데이터를 포함하는 스트림입니다. |
| size | [Size](../../com.aspose.drawing/size) | 아이콘의 원하는 크기입니다. |

### Icon(String fileName, int width, int height) {#Icon-java.lang.String-int-int-}
```
public Icon(String fileName, int width, int height)
```


지정된 파일에서 지정된 너비와 높이로 [Icon](../../com.aspose.drawing/icon) 클래스를 새 인스턴스로 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | [Icon](../../com.aspose.drawing/icon) 데이터를 포함하는 파일의 이름과 경로입니다. |
| width | int | [Icon](../../com.aspose.drawing/icon)의 원하는 너비입니다. |
| height | int | 원하는 [Icon](../../com.aspose.drawing/icon)의 높이. |

### Icon(Icon original, int width, int height) {#Icon-com.aspose.drawing.Icon-int-int-}
```
public Icon(Icon original, int width, int height)
```


새 인스턴스로 [Icon](../../com.aspose.drawing/icon) 클래스를 초기화하고 요청된 크기에 맞는 아이콘 버전을 찾으려고 시도합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | 다른 크기를 로드할 아이콘. |
| 너비 | int | 새 아이콘의 너비. |
| 높이 | int | 새 아이콘의 높이. |

### Icon(InputStream stream, int width, int height) {#Icon-java.io.InputStream-int-int-}
```
public Icon(InputStream stream, int width, int height)
```


지정된 데이터 스트림에서 [Icon](../../com.aspose.drawing/icon) 클래스를 새 인스턴스로 초기화하고 지정된 너비와 높이를 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 아이콘을 로드할 데이터 스트림. |
| 너비 | int | 아이콘의 너비(픽셀 단위). |
| 높이 | int | 아이콘의 높이(픽셀 단위). |

### getHandle() {#getHandle--}
```
public System.IntPtr getHandle()
```


이 [Icon](../../com.aspose.drawing/icon)의 핸들을 가져옵니다. 이 핸들은 복사본이 아니므로 해제하지 마십시오.

값: 아이콘의 Windows 핸들.

**Returns:**
com.aspose.ms.System.IntPtr
### getHeight() {#getHeight--}
```
public int getHeight()
```


이 [Icon](../../com.aspose.drawing/icon)의 높이를 가져옵니다.

값: 이 [Icon](../../com.aspose.drawing/icon)의 높이.

**Returns:**
int
### getSize() {#getSize--}
```
public Size getSize()
```


이 [Icon](../../com.aspose.drawing/icon)의 크기를 가져옵니다.

값: 이 [Icon](../../com.aspose.drawing/icon)의 너비와 높이를 지정하는 `Size`([.getSize](../../null/\#getSize)) 구조체.

**Returns:**
[Size](../../com.aspose.drawing/size)
### getWidth() {#getWidth--}
```
public int getWidth()
```


이 [Icon](../../com.aspose.drawing/icon)의 너비를 가져옵니다.

값: 이 [Icon](../../com.aspose.drawing/icon)의 너비.

**Returns:**
int
### extractAssociatedIcon(String filePath) {#extractAssociatedIcon-java.lang.String-}
```
public static Icon extractAssociatedIcon(String filePath)
```


지정된 파일에 포함된 이미지의 아이콘 표현을 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 이미지를 포함하는 파일의 경로. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) representation of the image that is contained in the specified file.
### fromHandle(byte[] handle) {#fromHandle-byte---}
```
public static Icon fromHandle(byte[] handle)
```


지정된 아이콘 Windows 핸들(HICON)에서 GDI+ [Icon](../../com.aspose.drawing/icon)을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| handle | byte[] | 아이콘에 대한 Windows 핸들. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) this method creates.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


[Icon](../../com.aspose.drawing/icon)을 복제하여 중복 이미지를 생성합니다.

**Returns:**
java.lang.Object - [Icon](../../com.aspose.drawing/icon)으로 캐스팅할 수 있는 객체.
### dispose() {#dispose--}
```
public void dispose()
```


관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다.

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


이 [Icon](../../com.aspose.drawing/icon)을 지정된 출력 java.io.InputStream에 저장합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 저장할 java.io.InputStream. |

### toBitmap() {#toBitmap--}
```
public Bitmap toBitmap()
```


이 [Icon](../../com.aspose.drawing/icon)을 GDI+ [Bitmap](../../com.aspose.drawing/bitmap)으로 변환합니다.

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - A [Bitmap](../../com.aspose.drawing/bitmap) that represents the converted [Icon](../../com.aspose.drawing/icon).
### toString() {#toString--}
```
public String toString()
```


[Icon](../../com.aspose.drawing/icon)을 설명하는 사람이 읽을 수 있는 문자열을 가져옵니다.

**Returns:**
java.lang.String - [Icon](../../com.aspose.drawing/icon)을 설명하는 문자열.
