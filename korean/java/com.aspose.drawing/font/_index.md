---
title: Font
second_title: Aspose.Drawing for Java API 참조
description: 텍스트에 대한 특정 형식을 정의하며, 글꼴, 크기 및 스타일 속성을 포함합니다.
type: docs
weight: 21
url: /ko/java/com.aspose.drawing/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Font implements System.IDisposable
```

텍스트에 대한 특정 형식을 정의하며, 글꼴, 크기 및 스타일 속성을 포함합니다. 이 클래스는 상속될 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.drawing.Font-int-) | 새로운 [Font](../../com.aspose.drawing/font) 클래스 인스턴스를 초기화하고 지정된 기존 [Font](../../com.aspose.drawing/font) 및 [FontStyle](../../com.aspose.drawing/fontstyle) 열거형을 사용합니다. |
| [Font(FontFamily family, float emSize)](#Font-com.aspose.drawing.FontFamily-float-) | 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다. |
| [Font(FontFamily family, float emSize, int style)](#Font-com.aspose.drawing.FontFamily-float-int-) | 지정된 크기와 스타일을 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다.. |
| [Font(FontFamily family, float emSize, int style, int unit)](#Font-com.aspose.drawing.FontFamily-float-int-int-) | 지정된 크기, 스타일 및 단위를 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-) | 지정된 크기, 스타일, 단위 및 문자 집합을 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다.. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-) | 지정된 크기, 스타일, 단위 및 문자 집합을 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다.. |
| [Font(String familyName, float emSize)](#Font-java.lang.String-float-) | 지정된 크기를 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다. |
| [Font(String familyName, float emSize, int style)](#Font-java.lang.String-float-int-) | 지정된 크기와 스타일을 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다. |
| [Font(String familyName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | 지정된 크기, 스타일 및 단위를 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)](#Font-java.lang.String-float-int-int-byte-) | 지정된 크기, 스타일, 단위 및 문자 집합을 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-java.lang.String-float-int-int-byte-boolean-) | 지정된 크기, 스타일, 단위 및 문자 집합을 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFontFamily()](#getFontFamily--) | 이 [Font](../../com.aspose.drawing/font)와 연결된 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))를 가져옵니다. |
| [getBold()](#getBold--) | 이 [Font](../../com.aspose.drawing/font)이 굵게 표시되는지 여부를 나타내는 값을 가져옵니다. |
| [getGdiCharSet()](#getGdiCharSet--) | 이 [Font](../../com.aspose.drawing/font)이 사용하는 GDI 문자 집합을 지정하는 바이트 값을 가져옵니다. |
| [getGdiVerticalFont()](#getGdiVerticalFont--) | 이 [Font](../../com.aspose.drawing/font)이 GDI 수직 글꼴에서 파생되었는지 여부를 나타내는 값을 가져옵니다.. |
| [getItalic()](#getItalic--) | 이 [Font](../../com.aspose.drawing/font)이 이탤릭인지 여부를 나타내는 값을 가져옵니다. |
| [getName()](#getName--) | 이 [Font](../../com.aspose.drawing/font)의 글꼴 이름을 가져옵니다. |
| [getStrikeout()](#getStrikeout--) | 이 [Font](../../com.aspose.drawing/font)이 글꼴에 가로선을 지정하는지 여부를 나타내는 값을 가져옵니다. |
| [getUnderline()](#getUnderline--) | 이 [Font](../../com.aspose.drawing/font)이 밑줄이 있는지 여부를 나타내는 값을 가져옵니다. |
| [getStyle()](#getStyle--) | 이 [Font](../../com.aspose.drawing/font)의 스타일 정보를 가져옵니다. |
| [getSize()](#getSize--) | `Font.Unit` 속성에서 지정한 단위로 측정된 이 [Font](../../com.aspose.drawing/font)의 em 크기를 가져옵니다. |
| [getSizeInPoints()](#getSizeInPoints--) | 이 [Font](../../com.aspose.drawing/font)의 포인트 단위 em 크기를 가져옵니다. |
| [getUnit()](#getUnit--) | 이 [Font](../../com.aspose.drawing/font)의 측정 단위를 가져옵니다. |
| [getHeight_Rename_Namesake()](#getHeight-Rename-Namesake--) | 이 글꼴의 줄 간격을 가져옵니다. |
| [isSystemFont()](#isSystemFont--) | 글꼴이 [SystemFonts](../../com.aspose.drawing/systemfonts)의 멤버인지 여부를 나타내는 값을 가져옵니다. |
| [getSystemFontName()](#getSystemFontName--) | IsSystemFont 속성이 true를 반환하면 시스템 글꼴의 이름을 가져옵니다. |
| [getOriginalFontName()](#getOriginalFontName--) | 원래 지정된 글꼴의 이름을 가져옵니다. |
| [deepClone()](#deepClone--) | 이 [Font](../../com.aspose.drawing/font)의 정확한 복사본을 생성합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체가 [Font](../../com.aspose.drawing/font)인지 여부와 이 [Font](../../com.aspose.drawing/font)와 동일한 `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size`, `M:Unit` 속성 값을 가지고 있는지 나타냅니다. |
| [hashCode()](#hashCode--) | 이 [Font](../../com.aspose.drawing/font)의 해시 코드를 가져옵니다. |
| [getHeight()](#getHeight--) | 이 폰트의 줄 간격을 픽셀 단위로 반환합니다. |
| [getHeight(Graphics graphics)](#getHeight-com.aspose.drawing.Graphics-) | 지정된 [Graphics](../../com.aspose.drawing/graphics)의 현재 단위로 이 폰트의 줄 간격을 반환합니다. |
| [getHeight(float dpi)](#getHeight-float-) | 지정된 수직 해상도를 가진 장치에 그려질 때 이 [Font](../../com.aspose.drawing/font)의 높이를 픽셀 단위로 반환합니다. |
| [dispose()](#dispose--) | 이 [Font](../../com.aspose.drawing/font)에서 사용된 모든 리소스를 해제합니다. |
| [toString()](#toString--) | 이 [Font](../../com.aspose.drawing/font)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [getCharacterSet()](#getCharacterSet--) | 이 `Font`이 사용하는 문자 집합을 지정하는 바이트 값을 가져옵니다. |
### Font(Font prototype, int newStyle) {#Font-com.aspose.drawing.Font-int-}
```
public Font(Font prototype, int newStyle)
```


새로운 [Font](../../com.aspose.drawing/font) 클래스 인스턴스를 초기화하고 지정된 기존 [Font](../../com.aspose.drawing/font) 및 [FontStyle](../../com.aspose.drawing/fontstyle) 열거형을 사용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.drawing/font) | 새 [Font](../../com.aspose.drawing/font)을 생성할 기존 [Font](../../com.aspose.drawing/font)입니다. |
| newStyle | int | 새 [Font](../../com.aspose.drawing/font)에 적용할 [FontStyle](../../com.aspose.drawing/fontstyle)입니다. [FontStyle](../../com.aspose.drawing/fontstyle) 열거형의 여러 값을 OR 연산자로 결합할 수 있습니다. |

### Font(FontFamily family, float emSize) {#Font-com.aspose.drawing.FontFamily-float-}
```
public Font(FontFamily family, float emSize)
```


새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | 새 [Font](../../com.aspose.drawing/font)의 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))입니다. |
| emSize | float | 새 폰트의 em-크기(포인트)입니다. |

### Font(FontFamily family, float emSize, int style) {#Font-com.aspose.drawing.FontFamily-float-int-}
```
public Font(FontFamily family, float emSize, int style)
```


지정된 크기와 스타일을 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다..

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | 새 [Font](../../com.aspose.drawing/font)의 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))입니다. |
| emSize | float | 새 폰트의 em-크기(포인트)입니다. |
| style | int | 새 폰트의 [FontStyle](../../com.aspose.drawing/fontstyle)입니다. |

### Font(FontFamily family, float emSize, int style, int unit) {#Font-com.aspose.drawing.FontFamily-float-int-int-}
```
public Font(FontFamily family, float emSize, int style, int unit)
```


지정된 크기, 스타일 및 단위를 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | 새 [Font](../../com.aspose.drawing/font)의 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))입니다. |
| emSize | float | `unit` 매개변수에 지정된 단위로 새 폰트의 em-크기입니다. |
| style | int | 새 폰트의 [FontStyle](../../com.aspose.drawing/fontstyle)입니다. |
| unit | int | 새 폰트의 [GraphicsUnit](../../com.aspose.drawing/graphicsunit)입니다. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)
```


지정된 크기, 스타일, 단위 및 문자 집합을 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다..

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | 새 [Font](../../com.aspose.drawing/font)의 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))입니다. |
| emSize | float | `unit` 매개변수에 지정된 단위로 새 폰트의 em-크기입니다. |
| style | int | 새 폰트의 [FontStyle](../../com.aspose.drawing/fontstyle)입니다. |
| unit | int | 새 폰트의 [GraphicsUnit](../../com.aspose.drawing/graphicsunit)입니다. |
| gdiCharSet | byte | 새 폰트에 사용할 GDI 문자 집합입니다. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


지정된 크기, 스타일, 단위 및 문자 집합을 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다..

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | 새 [Font](../../com.aspose.drawing/font)의 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))입니다. |
| emSize | float | `unit` 매개변수에 지정된 단위로 새 폰트의 em-크기입니다. |
| style | int | 새 폰트의 [FontStyle](../../com.aspose.drawing/fontstyle)입니다. |
| unit | int | 새 폰트의 [GraphicsUnit](../../com.aspose.drawing/graphicsunit)입니다. |
| gdiCharSet | byte | 새 폰트에 사용할 GDI 문자 집합입니다. |
| gdiVerticalFont | boolean | 새 폰트가 GDI 수직 폰트에서 파생되었는지 여부를 나타내는 Boolean 값입니다. |

### Font(String familyName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String familyName, float emSize)
```


지정된 크기를 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| familyName | java.lang.String | 새 [Font](../../com.aspose.drawing/font)의 FontFamily에 대한 문자열 표현입니다. |
| emSize | float | 새 폰트의 em-크기(포인트)입니다. |

### Font(String familyName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String familyName, float emSize, int style)
```


지정된 크기와 스타일을 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| familyName | java.lang.String | 새 [Font](../../com.aspose.drawing/font)의 FontFamily에 대한 문자열 표현입니다. |
| emSize | float | 새 폰트의 em-크기(포인트)입니다. |
| style | int | 새 폰트의 [FontStyle](../../com.aspose.drawing/fontstyle)입니다. |

### Font(String familyName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String familyName, float emSize, int style, int unit)
```


지정된 크기, 스타일 및 단위를 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| familyName | java.lang.String | 새 [Font](../../com.aspose.drawing/font)의 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))에 대한 문자열 표현입니다. |
| emSize | float | `unit` 매개변수에 지정된 단위로 새 폰트의 em-크기입니다. |
| style | int | 새 폰트의 [FontStyle](../../com.aspose.drawing/fontstyle)입니다. |
| unit | int | 새 폰트의 [GraphicsUnit](../../com.aspose.drawing/graphicsunit)입니다. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet) {#Font-java.lang.String-float-int-int-byte-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)
```


지정된 크기, 스타일, 단위 및 문자 집합을 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| familyName | java.lang.String | 새 [Font](../../com.aspose.drawing/font)의 FontFamily에 대한 문자열 표현입니다. |
| emSize | float | `unit` 매개변수에 지정된 단위로 새 폰트의 em-크기입니다. |
| style | int | 새 폰트의 [FontStyle](../../com.aspose.drawing/fontstyle)입니다. |
| unit | int | 새 폰트의 [GraphicsUnit](../../com.aspose.drawing/graphicsunit)입니다. |
| gdiCharSet | byte | 이 폰트에 사용할 GDI 문자 집합을 지정하는 바이트입니다. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-java.lang.String-float-int-int-byte-boolean-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


지정된 크기, 스타일, 단위 및 문자 집합을 사용하여 새로운 [Font](../../com.aspose.drawing/font) 클래스의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| familyName | java.lang.String | 새 [Font](../../com.aspose.drawing/font)의 FontFamily에 대한 문자열 표현입니다. |
| emSize | float | `unit` 매개변수에 지정된 단위로 새 폰트의 em-크기입니다. |
| style | int | 새 폰트의 [FontStyle](../../com.aspose.drawing/fontstyle)입니다. |
| unit | int | 새 폰트의 [GraphicsUnit](../../com.aspose.drawing/graphicsunit)입니다. |
| gdiCharSet | byte | 이 폰트에 사용할 GDI 문자 집합을 지정하는 바이트입니다. |
| gdiVerticalFont | boolean | 새 [Font](../../com.aspose.drawing/font)이 GDI 수직 폰트에서 파생되었는지 여부를 나타내는 Boolean 값입니다. |

### getFontFamily() {#getFontFamily--}
```
public FontFamily getFontFamily()
```


이 [Font](../../com.aspose.drawing/font)와 연결된 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))를 가져옵니다.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - The `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font).
### getBold() {#getBold--}
```
public boolean getBold()
```


이 [Font](../../com.aspose.drawing/font)이 굵게 표시되는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 [Font](../../com.aspose.drawing/font)이 굵게 표시되는지 여부를 나타내는 값입니다.
### getGdiCharSet() {#getGdiCharSet--}
```
public byte getGdiCharSet()
```


이 [Font](../../com.aspose.drawing/font)이 사용하는 GDI 문자 집합을 지정하는 바이트 값을 가져옵니다.

**Returns:**
byte - 이 [Font](../../com.aspose.drawing/font)이 사용하는 GDI 문자 집합을 지정하는 바이트 값입니다.
### getGdiVerticalFont() {#getGdiVerticalFont--}
```
public boolean getGdiVerticalFont()
```


이 [Font](../../com.aspose.drawing/font)이 GDI 수직 글꼴에서 파생되었는지 여부를 나타내는 값을 가져옵니다..

값: 이 [Font](../../com.aspose.drawing/font)이 GDI 수직 글꼴에서 파생된 경우 `true`; 그렇지 않으면 `false`.

**Returns:**
boolean - 이 [Font](../../com.aspose.drawing/font)이 GDI 수직 글꼴에서 파생되었는지 여부를 나타내는 값입니다.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


이 [Font](../../com.aspose.drawing/font)이 이탤릭인지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 [Font](../../com.aspose.drawing/font)이 이탤릭인지 여부를 나타내는 값입니다.
### getName() {#getName--}
```
public String getName()
```


이 [Font](../../com.aspose.drawing/font)의 글꼴 이름을 가져옵니다.

**Returns:**
java.lang.String - 이 [Font](../../com.aspose.drawing/font)의 글꼴 이름입니다.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


이 [Font](../../com.aspose.drawing/font)이 글꼴에 가로선을 지정하는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 [Font](../../com.aspose.drawing/font)이 글꼴에 가로선을 지정하는지 여부를 나타내는 값입니다.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


이 [Font](../../com.aspose.drawing/font)이 밑줄이 있는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 [Font](../../com.aspose.drawing/font)이 밑줄이 있는지 여부를 나타내는 값입니다.
### getStyle() {#getStyle--}
```
public int getStyle()
```


이 [Font](../../com.aspose.drawing/font)의 스타일 정보를 가져옵니다.

**Returns:**
int - 이 [Font](../../com.aspose.drawing/font)의 스타일 정보입니다.
### getSize() {#getSize--}
```
public float getSize()
```


`Font.Unit` 속성에서 지정한 단위로 측정된 이 [Font](../../com.aspose.drawing/font)의 em 크기를 가져옵니다.

**Returns:**
float - 이 [Font](../../com.aspose.drawing/font)의 em 크기를 \\{@code Font}에서 지정한 단위로 측정한 값입니다.
### getSizeInPoints() {#getSizeInPoints--}
```
public float getSizeInPoints()
```


이 [Font](../../com.aspose.drawing/font)의 포인트 단위 em 크기를 가져옵니다.

**Returns:**
float - 이 [Font](../../com.aspose.drawing/font)의 포인트 단위 em 크기입니다.
### getUnit() {#getUnit--}
```
public int getUnit()
```


이 [Font](../../com.aspose.drawing/font)의 측정 단위를 가져옵니다.

**Returns:**
int - 이 [Font](../../com.aspose.drawing/font)의 측정 단위입니다.
### getHeight_Rename_Namesake() {#getHeight-Rename-Namesake--}
```
public int getHeight_Rename_Namesake()
```


이 글꼴의 줄 간격을 가져옵니다.

값: 이 글꼴의 줄 간격(픽셀 단위)입니다.

**Returns:**
int - 이 글꼴의 줄 간격입니다.
### isSystemFont() {#isSystemFont--}
```
public boolean isSystemFont()
```


글꼴이 [SystemFonts](../../com.aspose.drawing/systemfonts)의 멤버인지 여부를 나타내는 값을 가져옵니다.

값: 글꼴이 [SystemFonts](../../com.aspose.drawing/systemfonts)의 구성원인 경우 `true`; 그렇지 않으면 `false`.

**Returns:**
boolean - 글꼴이 [SystemFonts](../../com.aspose.drawing/systemfonts)의 구성원인지 여부를 나타내는 값입니다.
### getSystemFontName() {#getSystemFontName--}
```
public String getSystemFontName()
```


IsSystemFont 속성이 true를 반환하면 시스템 글꼴의 이름을 가져옵니다.

값: IsSystemFont가 true를 반환하면 시스템 글꼴 이름을 반환하고, 그렇지 않으면 빈 문자열(\"\")을 반환합니다.

**Returns:**
java.lang.String - IsSystemFont 속성이 true를 반환할 경우 시스템 글꼴 이름입니다.
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


원래 지정된 글꼴의 이름을 가져옵니다.

값: 원래 지정된 글꼴 이름을 나타내는 문자열입니다.

**Returns:**
java.lang.String - 원래 지정된 글꼴 이름입니다.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


이 [Font](../../com.aspose.drawing/font)의 정확한 복사본을 생성합니다.

**Returns:**
[Font](../../com.aspose.drawing/font) - The [Font](../../com.aspose.drawing/font) this method creates, cast as an Object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 객체가 [Font](../../com.aspose.drawing/font)인지 여부와 이 [Font](../../com.aspose.drawing/font)와 동일한 `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size`, `M:Unit` 속성 값을 가지고 있는지 나타냅니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 테스트할 객체입니다. |

**Returns:**
boolean - `true`이면 obj 매개변수가 [Font](../../com.aspose.drawing/font)이며 이 [Font](../../com.aspose.drawing/font)과 동일한 `FontFamily`([.getFontFamily](../../null/\\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size`, `M:Unit` 속성 값을 가지고 있습니다; 그렇지 않으면 `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 [Font](../../com.aspose.drawing/font)의 해시 코드를 가져옵니다.

**Returns:**
int - 이 [Font](../../com.aspose.drawing/font)의 해시 코드입니다.
### getHeight() {#getHeight--}
```
public int getHeight()
```


이 폰트의 줄 간격을 픽셀 단위로 반환합니다.

**Returns:**
int - 이 글꼴의 줄 간격(픽셀 단위)입니다.
### getHeight(Graphics graphics) {#getHeight-com.aspose.drawing.Graphics-}
```
public float getHeight(Graphics graphics)
```


지정된 [Graphics](../../com.aspose.drawing/graphics)의 현재 단위로 이 폰트의 줄 간격을 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| graphics | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics)로, 디스플레이 장치의 인치당 도트 수로 표시되는 수직 해상도와 페이지 단위 및 페이지 배율 설정을 보유합니다. |

**Returns:**
float - 이 글꼴의 줄 간격(픽셀 단위)입니다.
### getHeight(float dpi) {#getHeight-float-}
```
public int getHeight(float dpi)
```


지정된 수직 해상도를 가진 장치에 그려질 때 이 [Font](../../com.aspose.drawing/font)의 높이를 픽셀 단위로 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dpi | float | 글꼴의 높이를 계산하는 데 사용되는 인치당 점 수(dpi) 단위의 수직 해상도입니다. |

**Returns:**
int - 이 [Font](../../com.aspose.drawing/font)의 높이(픽셀 단위)입니다.
### dispose() {#dispose--}
```
public void dispose()
```


이 [Font](../../com.aspose.drawing/font)에서 사용된 모든 리소스를 해제합니다.

### toString() {#toString--}
```
public String toString()
```


이 [Font](../../com.aspose.drawing/font)의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 [Font](../../com.aspose.drawing/font)을 나타내는 문자열입니다.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


이 `Font`이 사용하는 문자 집합을 지정하는 바이트 값을 가져옵니다.

**Returns:**
int - 이 `Font`이 사용하는 문자 집합입니다.
