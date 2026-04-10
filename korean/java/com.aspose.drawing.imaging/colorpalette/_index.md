---
title: ColorPalette
second_title: Aspose.Drawing for Java API 참조
description: 색상 팔레트를 구성하는 색상의 배열을 정의합니다.
type: docs
weight: 16
url: /ko/java/com.aspose.drawing.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPalette
```

색상 팔레트를 구성하는 색상의 배열을 정의합니다. 색상은 32비트 ARGB 색상입니다. 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ColorPalette(int count)](#ColorPalette-int-) | 새 `ColorPalette` 클래스 인스턴스를 초기화하고 IsCompactPalette는 false입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEntries()](#getEntries--) | `com.aspose.drawing.Color` 구조체 배열을 가져옵니다. |
| [isCompactPalette()](#isCompactPalette--) | 컴팩트 팔레트를 사용하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getFlags()](#getFlags--) |  |
| [setFlags(int flags)](#setFlags-int-) |  |
| [setEntries(int i, Color color)](#setEntries-int-com.aspose.drawing.Color-) |  |
### ColorPalette(int count) {#ColorPalette-int-}
```
public ColorPalette(int count)
```


새 `ColorPalette` 클래스 인스턴스를 초기화하고 IsCompactPalette는 false입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| count | int | 색상 팔레트 항목. |

### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


`com.aspose.drawing.Color` 구조체 배열을 가져옵니다.

**Returns:**
com.aspose.drawing.Color[] - 항목들. 이 `Aspose.Imaging.ColorPalette`를 구성하는 `com.aspose.drawing.Color` 구조체 배열입니다.
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


컴팩트 팔레트를 사용하는지 여부를 나타내는 값을 가져오거나 설정합니다.

**Returns:**
boolean - 컴팩트 팔레트를 사용하면 `true`; 그렇지 않으면 `false`.

컴팩트 팔레트는 이미지가 가능한 경우 지정된 팔레트 항목만 포함한다는 의미이며, 즉 이미지가 더 컴팩트해져 차지하는 공간이 적어집니다; 그렇지 않으면 2^BitsPerPixel 개의 항목이 존재하고 이미지가 모든 가능한 팔레트 항목을 위해 더 많은 공간을 예약합니다. 이 값을 true로 설정하고 팔레트 항목을 변경하면 데이터 이동이 발생할 수 있어 성능 저하가 발생할 수 있으므로 주의해서 사용하십시오.
### getFlags() {#getFlags--}
```
public int getFlags()
```




**Returns:**
int
### setFlags(int flags) {#setFlags-int-}
```
public void setFlags(int flags)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| flags | int |  |

### setEntries(int i, Color color) {#setEntries-int-com.aspose.drawing.Color-}
```
public void setEntries(int i, Color color)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| i | int |  |
| color | [Color](../../com.aspose.drawing/color) |  |

