---
title: ColorTranslator
second_title: Aspose.Drawing for Java API 参考
description: 在 GDI 结构之间转换颜色。
type: docs
weight: 16
url: /zh/java/com.aspose.drawing/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

在 GDI+ [Color](../../com.aspose.drawing/color) 结构之间转换颜色。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorTranslator()](#ColorTranslator--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | 将 HTML 颜色表示转换为 GDI+ [Color](../../com.aspose.drawing/color) 结构。 |
| [toHtml(Color c)](#toHtml-com.aspose.drawing.Color-) | 将指定的 [Color](../../com.aspose.drawing/color) 结构转换为 HTML 字符串颜色表示。 |
| [fromWin32(int win32Color)](#fromWin32-int-) | 将 Windows 颜色值转换为 GDI+ [Color](../../com.aspose.drawing/color) 结构。 |
| [fromOle(int oleColor)](#fromOle-int-) | 将 OLE 颜色值转换为 GDI+ [Color](../../com.aspose.drawing/color) 结构。 |
| [toWin32(Color c)](#toWin32-com.aspose.drawing.Color-) | 将 [Color](../../com.aspose.drawing/color) 结构转换为 Win32 颜色表示。 |
| [toOle(Color c)](#toOle-com.aspose.drawing.Color-) | 将 [Color](../../com.aspose.drawing/color) 结构转换为 OLE 颜色表示。 |
### ColorTranslator() {#ColorTranslator--}
```
public ColorTranslator()
```


### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


将 HTML 颜色表示转换为 GDI+ [Color](../../com.aspose.drawing/color) 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlColor | java.lang.String | 要转换的 Html 颜色的字符串表示形式。 |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated HTML color or `Empty` if htmlColor is null.
### toHtml(Color c) {#toHtml-com.aspose.drawing.Color-}
```
public static String toHtml(Color c)
```


将指定的 [Color](../../com.aspose.drawing/color) 结构转换为 HTML 字符串颜色表示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | 要翻译的 [Color](../../com.aspose.drawing/color) 结构。 |

**Returns:**
java.lang.String - 表示 HTML 颜色的字符串。
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


将 Windows 颜色值转换为 GDI+ [Color](../../com.aspose.drawing/color) 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| win32Color | int | 要翻译的 Windows 颜色。 |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated Windows color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


将 OLE 颜色值转换为 GDI+ [Color](../../com.aspose.drawing/color) 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oleColor | int | 要翻译的 OLE 颜色。 |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated OLE color.
### toWin32(Color c) {#toWin32-com.aspose.drawing.Color-}
```
public static int toWin32(Color c)
```


将 [Color](../../com.aspose.drawing/color) 结构转换为 Win32 颜色表示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | 要转换的 [Color](../../com.aspose.drawing/color) 结构。 |

**Returns:**
int - 表示 Win32 颜色格式的值。
### toOle(Color c) {#toOle-com.aspose.drawing.Color-}
```
public static int toOle(Color c)
```


将 [Color](../../com.aspose.drawing/color) 结构转换为 OLE 颜色表示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | 要转换的 [Color](../../com.aspose.drawing/color) 结构。 |

**Returns:**
int - 表示 OLE 颜色格式的值。
