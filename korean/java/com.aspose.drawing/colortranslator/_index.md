---
title: ColorTranslator
second_title: Aspose.Drawing for Java API 참조
description: 색상을 GDI 구조로 변환하거나 그 반대로 변환합니다.
type: docs
weight: 16
url: /ko/java/com.aspose.drawing/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

색상을 GDI+ [Color](../../com.aspose.drawing/color) 구조로 변환하거나 그 반대로 변환합니다. 이 클래스는 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ColorTranslator()](#ColorTranslator--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | HTML 색상 표현을 GDI+ [Color](../../com.aspose.drawing/color) 구조로 변환합니다. |
| [toHtml(Color c)](#toHtml-com.aspose.drawing.Color-) | 지정된 [Color](../../com.aspose.drawing/color) 구조를 HTML 문자열 색상 표현으로 변환합니다. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Windows 색상 값을 GDI+ [Color](../../com.aspose.drawing/color) 구조로 변환합니다. |
| [fromOle(int oleColor)](#fromOle-int-) | OLE 색상 값을 GDI+ [Color](../../com.aspose.drawing/color) 구조로 변환합니다. |
| [toWin32(Color c)](#toWin32-com.aspose.drawing.Color-) | [Color](../../com.aspose.drawing/color) 구조를 Win32 색상 표현으로 변환합니다. |
| [toOle(Color c)](#toOle-com.aspose.drawing.Color-) | [Color](../../com.aspose.drawing/color) 구조를 OLE 색상 표현으로 변환합니다. |
### ColorTranslator() {#ColorTranslator--}
```
public ColorTranslator()
```


### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


HTML 색상 표현을 GDI+ [Color](../../com.aspose.drawing/color) 구조로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| htmlColor | java.lang.String | 변환할 Html 색상의 문자열 표현입니다. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated HTML color or `Empty` if htmlColor is null.
### toHtml(Color c) {#toHtml-com.aspose.drawing.Color-}
```
public static String toHtml(Color c)
```


지정된 [Color](../../com.aspose.drawing/color) 구조를 HTML 문자열 색상 표현으로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | 번역할 [Color](../../com.aspose.drawing/color) 구조입니다. |

**Returns:**
java.lang.String - HTML 색상을 나타내는 문자열입니다.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Windows 색상 값을 GDI+ [Color](../../com.aspose.drawing/color) 구조로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| win32Color | int | 번역할 Windows 색상입니다. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated Windows color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


OLE 색상 값을 GDI+ [Color](../../com.aspose.drawing/color) 구조로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| oleColor | int | 번역할 OLE 색상입니다. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated OLE color.
### toWin32(Color c) {#toWin32-com.aspose.drawing.Color-}
```
public static int toWin32(Color c)
```


[Color](../../com.aspose.drawing/color) 구조를 Win32 색상 표현으로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | 변환할 [Color](../../com.aspose.drawing/color) 구조입니다. |

**Returns:**
int - 색상의 Win32 형식을 나타내는 값입니다.
### toOle(Color c) {#toOle-com.aspose.drawing.Color-}
```
public static int toOle(Color c)
```


[Color](../../com.aspose.drawing/color) 구조를 OLE 색상 표현으로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | 변환할 [Color](../../com.aspose.drawing/color) 구조입니다. |

**Returns:**
int - 색상의 OLE 형식을 나타내는 값입니다.
