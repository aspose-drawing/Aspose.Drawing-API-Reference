---
title: WmfPlaceableFileHeader
second_title: Aspose.Drawing for Java API 참조
description: 배치 가능한 메타파일을 정의합니다.
type: docs
weight: 37
url: /ko/java/com.aspose.drawing.imaging/wmfplaceablefileheader/
---
**Inheritance:**
java.lang.Object
```
public final class WmfPlaceableFileHeader
```

배치 가능한 메타파일을 정의합니다. 상속되지 않습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WmfPlaceableFileHeader()](#WmfPlaceableFileHeader--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getKey()](#getKey--) | 배치 가능한 메타파일 헤더의 존재 여부를 나타내는 값을 가져옵니다. |
| [setKey(int value)](#setKey-int-) | 배치 가능한 메타파일 헤더의 존재 여부를 나타내는 값을 설정합니다. |
| [getHmf()](#getHmf--) | 메모리 내 메타파일의 핸들을 가져옵니다. |
| [setHmf(short value)](#setHmf-short-) | 메모리에서 메타파일의 핸들을 설정합니다. |
| [getBboxLeft()](#getBboxLeft--) | 출력 장치에서 메타파일 이미지의 경계 사각형 왼쪽 위 모서리의 x 좌표를 가져옵니다. |
| [setBboxLeft(short value)](#setBboxLeft-short-) | 출력 장치에서 메타파일 이미지의 경계 사각형 왼쪽 위 모서리의 x 좌표를 설정합니다. |
| [getBboxTop()](#getBboxTop--) | 출력 장치에서 메타파일 이미지의 경계 사각형 왼쪽 위 모서리의 y 좌표를 가져옵니다. |
| [setBboxTop(short value)](#setBboxTop-short-) | 출력 장치에서 메타파일 이미지의 경계 사각형 왼쪽 위 모서리의 y 좌표를 설정합니다. |
| [getBboxRight()](#getBboxRight--) | 출력 장치에서 메타파일 이미지의 경계 사각형 오른쪽 아래 모서리의 x 좌표를 가져옵니다. |
| [setBboxRight(short value)](#setBboxRight-short-) | 출력 장치에서 메타파일 이미지의 경계 사각형 오른쪽 아래 모서리의 x 좌표를 설정합니다. |
| [getBboxBottom()](#getBboxBottom--) | 출력 장치에서 메타파일 이미지의 경계 사각형 오른쪽 아래 모서리의 y 좌표를 가져옵니다. |
| [setBboxBottom(short value)](#setBboxBottom-short-) | 출력 장치에서 메타파일 이미지의 경계 사각형 오른쪽 아래 모서리의 y 좌표를 설정합니다. |
| [getInch()](#getInch--) | 인치당 twip 수를 가져옵니다. |
| [setInch(short value)](#setInch-short-) | 인치당 twip 수를 설정합니다. |
| [getReserved()](#getReserved--) | 예약됨. |
| [setReserved(int value)](#setReserved-int-) | 예약됨. |
| [getChecksum()](#getChecksum--) | 헤더에서 이전 10개의 WORD에 대한 체크섬 값을 가져옵니다. |
| [setChecksum(short value)](#setChecksum-short-) | 헤더에서 이전 10개의 WORD에 대한 체크섬 값을 설정합니다. |
### WmfPlaceableFileHeader() {#WmfPlaceableFileHeader--}
```
public WmfPlaceableFileHeader()
```


### getKey() {#getKey--}
```
public int getKey()
```


배치 가능한 메타파일 헤더의 존재 여부를 나타내는 값을 가져옵니다.

**Returns:**
int - 배치 가능한 메타파일 헤더가 존재함을 나타내는 값.
### setKey(int value) {#setKey-int-}
```
public void setKey(int value)
```


배치 가능한 메타파일 헤더의 존재 여부를 나타내는 값을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 배치 가능한 메타파일 헤더가 존재함을 나타내는 값. |

### getHmf() {#getHmf--}
```
public short getHmf()
```


메모리 내 메타파일의 핸들을 가져옵니다.

**Returns:**
short - 메모리에서 메타파일의 핸들.
### setHmf(short value) {#setHmf-short-}
```
public void setHmf(short value)
```


메모리에서 메타파일의 핸들을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | short | 메모리에서 메타파일의 핸들. |

### getBboxLeft() {#getBboxLeft--}
```
public short getBboxLeft()
```


출력 장치에서 메타파일 이미지의 경계 사각형 왼쪽 위 모서리의 x 좌표를 가져옵니다.

**Returns:**
short - 출력 장치에서 메타파일 이미지의 경계 사각형 왼쪽 위 모서리의 x 좌표.
### setBboxLeft(short value) {#setBboxLeft-short-}
```
public void setBboxLeft(short value)
```


출력 장치에서 메타파일 이미지의 경계 사각형 왼쪽 위 모서리의 x 좌표를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | short | 출력 장치에서 메타파일 이미지의 경계 사각형 왼쪽 위 모서리의 x 좌표. |

### getBboxTop() {#getBboxTop--}
```
public short getBboxTop()
```


출력 장치에서 메타파일 이미지의 경계 사각형 왼쪽 위 모서리의 y 좌표를 가져옵니다.

**Returns:**
short - 출력 장치에서 메타파일 이미지의 경계 사각형 왼쪽 위 모서리의 y 좌표.
### setBboxTop(short value) {#setBboxTop-short-}
```
public void setBboxTop(short value)
```


출력 장치에서 메타파일 이미지의 경계 사각형 왼쪽 위 모서리의 y 좌표를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | short | 출력 장치에서 메타파일 이미지의 경계 사각형 왼쪽 위 모서리의 y 좌표. |

### getBboxRight() {#getBboxRight--}
```
public short getBboxRight()
```


출력 장치에서 메타파일 이미지의 경계 사각형 오른쪽 아래 모서리의 x 좌표를 가져옵니다.

**Returns:**
short - 출력 장치에서 메타파일 이미지의 경계 사각형 오른쪽 아래 모서리의 x 좌표.
### setBboxRight(short value) {#setBboxRight-short-}
```
public void setBboxRight(short value)
```


출력 장치에서 메타파일 이미지의 경계 사각형 오른쪽 아래 모서리의 x 좌표를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | short | 출력 장치에서 메타파일 이미지의 경계 사각형 오른쪽 아래 모서리의 x 좌표. |

### getBboxBottom() {#getBboxBottom--}
```
public short getBboxBottom()
```


출력 장치에서 메타파일 이미지의 경계 사각형 오른쪽 아래 모서리의 y 좌표를 가져옵니다.

**Returns:**
short - 출력 장치의 메타파일 이미지에 대한 경계 사각형 오른쪽 아래 모서리의 y좌표.
### setBboxBottom(short value) {#setBboxBottom-short-}
```
public void setBboxBottom(short value)
```


출력 장치에서 메타파일 이미지의 경계 사각형 오른쪽 아래 모서리의 y 좌표를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | short | 출력 장치의 메타파일 이미지에 대한 경계 사각형 오른쪽 아래 모서리의 y좌표. |

### getInch() {#getInch--}
```
public short getInch()
```


인치당 twip 수를 가져옵니다.

**Returns:**
short - 인치당 twip 수.
### setInch(short value) {#setInch-short-}
```
public void setInch(short value)
```


인치당 twip 수를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | short | 인치당 twip 수. |

### getReserved() {#getReserved--}
```
public int getReserved()
```


예약됨. 사용하지 마십시오.

**Returns:**
int - 예약됨. 사용하지 마십시오.
### setReserved(int value) {#setReserved-int-}
```
public void setReserved(int value)
```


예약됨. 사용하지 마십시오.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getChecksum() {#getChecksum--}
```
public short getChecksum()
```


헤더에서 이전 10개의 WORD에 대한 체크섬 값을 가져옵니다.

**Returns:**
short - 헤더에 있는 이전 10개의 WORD에 대한 체크섬 값.
### setChecksum(short value) {#setChecksum-short-}
```
public void setChecksum(short value)
```


헤더에서 이전 10개의 WORD에 대한 체크섬 값을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | short | 헤더에 있는 이전 10개의 WORD에 대한 체크섬 값. |

