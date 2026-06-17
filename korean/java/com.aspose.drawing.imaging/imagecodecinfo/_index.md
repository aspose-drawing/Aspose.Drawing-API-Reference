---
title: ImageCodecInfo
second_title: Aspose.Drawing for Java API 참조
description: 이 클래스는 코덱이라고 불리는 설치된 이미지 인코더 및 디코더에 대한 모든 관련 정보를 검색하기 위한 필요한 저장 멤버와 메서드를 제공합니다.
type: docs
weight: 25
url: /ko/java/com.aspose.drawing.imaging/imagecodecinfo/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCodecInfo
```

이 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 클래스는 설치된 이미지 인코더 및 디코더(코덱이라고 함)에 대한 모든 관련 정보를 검색하기 위해 필요한 저장 멤버와 메서드를 제공합니다. 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ImageCodecInfo()](#ImageCodecInfo--) | 새로운 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 클래스 인스턴스를 초기화합니다. |
| [ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)](#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getClsid()](#getClsid--) | 특정 코덱을 식별하는 GUID를 포함하는 java.util.UUID 구조체를 가져옵니다. |
| [setClsid(UUID value)](#setClsid-java.util.UUID-) | 특정 코덱을 식별하는 GUID를 포함하는 java.util.UUID 구조체를 설정합니다. |
| [getFormatID()](#getFormatID--) | 코덱 형식을 식별하는 GUID를 포함하는 java.util.UUID 구조체를 가져옵니다. |
| [setFormatID(UUID value)](#setFormatID-java.util.UUID-) | 코덱 형식을 식별하는 GUID를 포함하는 java.util.UUID 구조체를 설정합니다. |
| [getCodecName()](#getCodecName--) | 코덱 이름을 포함하는 문자열을 가져오거나 설정합니다. |
| [setCodecName(String value)](#setCodecName-java.lang.String-) | 코덱 이름을 포함하는 문자열을 가져오거나 설정합니다. |
| [getFormatDescription()](#getFormatDescription--) | 코덱 파일 형식을 설명하는 문자열을 가져오거나 설정합니다. |
| [setFormatDescription(String value)](#setFormatDescription-java.lang.String-) | 코덱 파일 형식을 설명하는 문자열을 가져오거나 설정합니다. |
| [getFilenameExtension()](#getFilenameExtension--) | 코덱에서 사용되는 파일 이름 확장자를 포함하는 문자열을 가져오거나 설정합니다. |
| [setFilenameExtension(String value)](#setFilenameExtension-java.lang.String-) | 코덱에서 사용되는 파일 이름 확장자를 포함하는 문자열을 가져오거나 설정합니다. |
| [getMimeType()](#getMimeType--) | 코덱의 멀티퍼포스 인터넷 메일 확장(MIME) 유형을 포함하는 문자열을 가져오거나 설정합니다. |
| [setMimeType(String value)](#setMimeType-java.lang.String-) | 코덱의 멀티퍼포스 인터넷 메일 확장(MIME) 유형을 포함하는 문자열을 가져오거나 설정합니다. |
| [getVersion()](#getVersion--) | 코덱의 버전 번호를 가져오거나 설정합니다. |
| [setVersion(int value)](#setVersion-int-) | 코덱의 버전 번호를 가져오거나 설정합니다. |
| [getSignaturePatterns()](#getSignaturePatterns--) | 코덱 서명을 나타내는 바이트의 2차원 배열을 가져오거나 설정합니다. |
| [setSignaturePatterns(byte[][] value)](#setSignaturePatterns-byte-----) | 코덱 서명을 나타내는 바이트의 2차원 배열을 가져오거나 설정합니다. |
| [getSignatureMasks()](#getSignatureMasks--) | 필터로 사용할 수 있는 바이트의 2차원 배열을 가져오거나 설정합니다. |
| [setSignatureMasks(byte[][] value)](#setSignatureMasks-byte-----) | 필터로 사용할 수 있는 바이트의 2차원 배열을 가져오거나 설정합니다. |
| [getImageDecoders()](#getImageDecoders--) | GDI+에 내장된 이미지 디코더에 대한 정보를 포함하는 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 객체 배열을 반환합니다. |
| [getImageEncoders()](#getImageEncoders--) | GDI+에 내장된 이미지 인코더에 대한 정보를 포함하는 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 객체 배열을 반환합니다. |
### ImageCodecInfo() {#ImageCodecInfo--}
```
public ImageCodecInfo()
```


새로운 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 클래스 인스턴스를 초기화합니다.

### ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version) {#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-}
```
public ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| clsid | java.util.UUID |  |
| codecName | java.lang.String |  |
| filenameExtension | java.lang.String |  |
| formatDescription | java.lang.String |  |
| formatID | java.util.UUID |  |
| mimeType | java.lang.String |  |
| version | int |  |

### getClsid() {#getClsid--}
```
public UUID getClsid()
```


특정 코덱을 식별하는 GUID를 포함하는 java.util.UUID 구조체를 가져옵니다.

**Returns:**
java.util.UUID - java.util.UUID
### setClsid(UUID value) {#setClsid-java.util.UUID-}
```
public void setClsid(UUID value)
```


특정 코덱을 식별하는 GUID를 포함하는 java.util.UUID 구조체를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.util.UUID | java.util.UUID |

### getFormatID() {#getFormatID--}
```
public UUID getFormatID()
```


코덱 형식을 식별하는 GUID를 포함하는 java.util.UUID 구조체를 가져옵니다.

**Returns:**
java.util.UUID - java.util.UUID
### setFormatID(UUID value) {#setFormatID-java.util.UUID-}
```
public void setFormatID(UUID value)
```


코덱 형식을 식별하는 GUID를 포함하는 java.util.UUID 구조체를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.util.UUID | java.util.UUID |

### getCodecName() {#getCodecName--}
```
public String getCodecName()
```


코덱 이름을 포함하는 문자열을 가져오거나 설정합니다.

**Returns:**
java.lang.String
### setCodecName(String value) {#setCodecName-java.lang.String-}
```
public void setCodecName(String value)
```


코덱 이름을 포함하는 문자열을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormatDescription() {#getFormatDescription--}
```
public String getFormatDescription()
```


코덱 파일 형식을 설명하는 문자열을 가져오거나 설정합니다.

**Returns:**
java.lang.String
### setFormatDescription(String value) {#setFormatDescription-java.lang.String-}
```
public void setFormatDescription(String value)
```


코덱 파일 형식을 설명하는 문자열을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFilenameExtension() {#getFilenameExtension--}
```
public String getFilenameExtension()
```


코덱에서 사용되는 파일 이름 확장자를 포함하는 문자열을 가져오거나 설정합니다. 확장자는 세미콜론으로 구분됩니다.

**Returns:**
java.lang.String
### setFilenameExtension(String value) {#setFilenameExtension-java.lang.String-}
```
public void setFilenameExtension(String value)
```


코덱에서 사용되는 파일 이름 확장자를 포함하는 문자열을 가져오거나 설정합니다. 확장자는 세미콜론으로 구분됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getMimeType() {#getMimeType--}
```
public String getMimeType()
```


코덱의 멀티퍼포스 인터넷 메일 확장(MIME) 유형을 포함하는 문자열을 가져오거나 설정합니다.

**Returns:**
java.lang.String
### setMimeType(String value) {#setMimeType-java.lang.String-}
```
public void setMimeType(String value)
```


코덱의 멀티퍼포스 인터넷 메일 확장(MIME) 유형을 포함하는 문자열을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


코덱의 버전 번호를 가져오거나 설정합니다.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


코덱의 버전 번호를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSignaturePatterns() {#getSignaturePatterns--}
```
public byte[][] getSignaturePatterns()
```


코덱 서명을 나타내는 바이트의 2차원 배열을 가져오거나 설정합니다.

**Returns:**
byte[][]
### setSignaturePatterns(byte[][] value) {#setSignaturePatterns-byte-----}
```
public void setSignaturePatterns(byte[][] value)
```


코덱 서명을 나타내는 바이트의 2차원 배열을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte[][] |  |

### getSignatureMasks() {#getSignatureMasks--}
```
public byte[][] getSignatureMasks()
```


필터로 사용할 수 있는 바이트의 2차원 배열을 가져오거나 설정합니다.

**Returns:**
byte[][]
### setSignatureMasks(byte[][] value) {#setSignatureMasks-byte-----}
```
public void setSignatureMasks(byte[][] value)
```


필터로 사용할 수 있는 바이트의 2차원 배열을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte[][] |  |

### getImageDecoders() {#getImageDecoders--}
```
public static ImageCodecInfo[] getImageDecoders()
```


GDI+에 내장된 이미지 디코더에 대한 정보를 포함하는 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 객체 배열을 반환합니다.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 객체의 배열입니다. 배열의 각 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 객체는 내장 이미지 디코더 중 하나에 대한 정보를 포함합니다.
### getImageEncoders() {#getImageEncoders--}
```
public static ImageCodecInfo[] getImageEncoders()
```


GDI+에 내장된 이미지 인코더에 대한 정보를 포함하는 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 객체 배열을 반환합니다.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 객체의 배열입니다. 배열의 각 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 객체는 내장 이미지 인코더 중 하나에 대한 정보를 포함합니다.
