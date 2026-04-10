---
title: Font
second_title: Aspose.Drawing for Java API 参考
description: 定义文本的特定格式，包括字体、大小和样式属性。
type: docs
weight: 21
url: /zh/java/com.aspose.drawing/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Font implements System.IDisposable
```

定义文本的特定格式，包括字体、大小和样式属性。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.drawing.Font-int-) | 初始化 [Font](../../com.aspose.drawing/font) 类的新实例，使用指定的现有 [Font](../../com.aspose.drawing/font) 和 [FontStyle](../../com.aspose.drawing/fontstyle) 枚举。 |
| [Font(FontFamily family, float emSize)](#Font-com.aspose.drawing.FontFamily-float-) | 初始化 [Font](../../com.aspose.drawing/font) 类的新实例。 |
| [Font(FontFamily family, float emSize, int style)](#Font-com.aspose.drawing.FontFamily-float-int-) | 使用指定的大小和样式初始化 [Font](../../com.aspose.drawing/font) 类的新实例.. |
| [Font(FontFamily family, float emSize, int style, int unit)](#Font-com.aspose.drawing.FontFamily-float-int-int-) | 使用指定的大小、样式和单位初始化 [Font](../../com.aspose.drawing/font) 类的新实例。 |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-) | 使用指定的大小、样式、单位和字符集初始化 [Font](../../com.aspose.drawing/font) 类的新实例.. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-) | 使用指定的大小、样式、单位和字符集初始化 [Font](../../com.aspose.drawing/font) 类的新实例.. |
| [Font(String familyName, float emSize)](#Font-java.lang.String-float-) | 使用指定的大小初始化 [Font](../../com.aspose.drawing/font) 类的新实例。 |
| [Font(String familyName, float emSize, int style)](#Font-java.lang.String-float-int-) | 使用指定的大小和样式初始化 [Font](../../com.aspose.drawing/font) 类的新实例。 |
| [Font(String familyName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | 使用指定的大小、样式和单位初始化 [Font](../../com.aspose.drawing/font) 类的新实例。 |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)](#Font-java.lang.String-float-int-int-byte-) | 使用指定的大小、样式、单位和字符集初始化 [Font](../../com.aspose.drawing/font) 类的新实例。 |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-java.lang.String-float-int-int-byte-boolean-) | 使用指定的大小、样式、单位和字符集初始化 [Font](../../com.aspose.drawing/font) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFontFamily()](#getFontFamily--) | 获取与此 [Font](../../com.aspose.drawing/font) 关联的 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))。 |
| [getBold()](#getBold--) | 获取一个值，指示此 [Font](../../com.aspose.drawing/font) 是否为粗体。 |
| [getGdiCharSet()](#getGdiCharSet--) | 获取一个字节值，指定此 [Font](../../com.aspose.drawing/font) 使用的 GDI 字符集。 |
| [getGdiVerticalFont()](#getGdiVerticalFont--) | 获取一个值，指示此 [Font](../../com.aspose.drawing/font) 是否源自 GDI 垂直字体.. |
| [getItalic()](#getItalic--) | 获取一个值，指示此 [Font](../../com.aspose.drawing/font) 是否为斜体。 |
| [getName()](#getName--) | 获取此 [Font](../../com.aspose.drawing/font) 的字体名称。 |
| [getStrikeout()](#getStrikeout--) | 获取一个值，指示此 [Font](../../com.aspose.drawing/font) 是否指定在字体上加水平线。 |
| [getUnderline()](#getUnderline--) | 获取一个值，指示此 [Font](../../com.aspose.drawing/font) 是否带下划线。 |
| [getStyle()](#getStyle--) | 获取此 [Font](../../com.aspose.drawing/font) 的样式信息。 |
| [getSize()](#getSize--) | 获取此 [Font](../../com.aspose.drawing/font) 的 em 大小，单位由 `Font.Unit` 属性指定。 |
| [getSizeInPoints()](#getSizeInPoints--) | 获取此 [Font](../../com.aspose.drawing/font) 的 em 大小（以点为单位）。 |
| [getUnit()](#getUnit--) | 获取此 [Font](../../com.aspose.drawing/font) 的度量单位。 |
| [getHeight_Rename_Namesake()](#getHeight-Rename-Namesake--) | 获取此字体的行间距。 |
| [isSystemFont()](#isSystemFont--) | 获取一个值，指示该字体是否是 [SystemFonts](../../com.aspose.drawing/systemfonts) 的成员。 |
| [getSystemFontName()](#getSystemFontName--) | 如果 IsSystemFont 属性返回 true，则获取系统字体的名称。 |
| [getOriginalFontName()](#getOriginalFontName--) | 获取最初指定的字体名称。 |
| [deepClone()](#deepClone--) | 创建此 [Font](../../com.aspose.drawing/font) 的精确副本。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指示指定的对象是否为 [Font](../../com.aspose.drawing/font) 且其 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))、`M:GdiVerticalFont`、`M:GdiCharSet`、`M:Style`、`M:Size` 和 `M:Unit` 属性值与此 [Font](../../com.aspose.drawing/font) 相同。 |
| [hashCode()](#hashCode--) | 获取此 [Font](../../com.aspose.drawing/font) 的哈希码。 |
| [getHeight()](#getHeight--) | 返回此字体的行间距（以像素为单位）。 |
| [getHeight(Graphics graphics)](#getHeight-com.aspose.drawing.Graphics-) | 返回此字体在指定的 [Graphics](../../com.aspose.drawing/graphics) 的当前单位下的行间距。 |
| [getHeight(float dpi)](#getHeight-float-) | 返回此 [Font](../../com.aspose.drawing/font) 在使用指定垂直分辨率的设备上绘制时的高度（以像素为单位）。 |
| [dispose()](#dispose--) | 释放此 [Font](../../com.aspose.drawing/font) 使用的所有资源。 |
| [toString()](#toString--) | 返回此 [Font](../../com.aspose.drawing/font) 的可读字符串表示。 |
| [getCharacterSet()](#getCharacterSet--) | 获取一个字节值，指定此 `Font` 使用的字符集。 |
### Font(Font prototype, int newStyle) {#Font-com.aspose.drawing.Font-int-}
```
public Font(Font prototype, int newStyle)
```


初始化 [Font](../../com.aspose.drawing/font) 类的新实例，使用指定的现有 [Font](../../com.aspose.drawing/font) 和 [FontStyle](../../com.aspose.drawing/fontstyle) 枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.drawing/font) | 用于创建新 [Font](../../com.aspose.drawing/font) 的现有 [Font](../../com.aspose.drawing/font)。 |
| newStyle | int | 要应用于新 [Font](../../com.aspose.drawing/font) 的 [FontStyle](../../com.aspose.drawing/fontstyle)。可以使用 OR 运算符组合多个 [FontStyle](../../com.aspose.drawing/fontstyle) 枚举值。 |

### Font(FontFamily family, float emSize) {#Font-com.aspose.drawing.FontFamily-float-}
```
public Font(FontFamily family, float emSize)
```


初始化 [Font](../../com.aspose.drawing/font) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | 新 [Font](../../com.aspose.drawing/font) 的 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))。 |
| emSize | 浮点数 | 新字体的 em 大小（以点为单位）。 |

### Font(FontFamily family, float emSize, int style) {#Font-com.aspose.drawing.FontFamily-float-int-}
```
public Font(FontFamily family, float emSize, int style)
```


使用指定的大小和样式初始化 [Font](../../com.aspose.drawing/font) 类的新实例..

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | 新 [Font](../../com.aspose.drawing/font) 的 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))。 |
| emSize | 浮点数 | 新字体的 em 大小（以点为单位）。 |
| style | int | 新字体的 [FontStyle](../../com.aspose.drawing/fontstyle)。 |

### Font(FontFamily family, float emSize, int style, int unit) {#Font-com.aspose.drawing.FontFamily-float-int-int-}
```
public Font(FontFamily family, float emSize, int style, int unit)
```


使用指定的大小、样式和单位初始化 [Font](../../com.aspose.drawing/font) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | 新 [Font](../../com.aspose.drawing/font) 的 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))。 |
| emSize | 浮点数 | 新字体的 em 大小，单位由 `unit` 参数指定。 |
| style | int | 新字体的 [FontStyle](../../com.aspose.drawing/fontstyle)。 |
| unit | int | 新字体的 [GraphicsUnit](../../com.aspose.drawing/graphicsunit)。 |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)
```


使用指定的大小、样式、单位和字符集初始化 [Font](../../com.aspose.drawing/font) 类的新实例..

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | 新 [Font](../../com.aspose.drawing/font) 的 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))。 |
| emSize | 浮点数 | 新字体的 em 大小，单位由 `unit` 参数指定。 |
| style | int | 新字体的 [FontStyle](../../com.aspose.drawing/fontstyle)。 |
| unit | int | 新字体的 [GraphicsUnit](../../com.aspose.drawing/graphicsunit)。 |
| gdiCharSet | byte | 用于新字体的 GDI 字符集。 |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


使用指定的大小、样式、单位和字符集初始化 [Font](../../com.aspose.drawing/font) 类的新实例..

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | 新 [Font](../../com.aspose.drawing/font) 的 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))。 |
| emSize | 浮点数 | 新字体的 em 大小，单位由 `unit` 参数指定。 |
| style | int | 新字体的 [FontStyle](../../com.aspose.drawing/fontstyle)。 |
| unit | int | 新字体的 [GraphicsUnit](../../com.aspose.drawing/graphicsunit)。 |
| gdiCharSet | byte | 用于新字体的 GDI 字符集。 |
| gdiVerticalFont | 布尔型 | 一个布尔值，指示新字体是否来源于 GDI 垂直字体。 |

### Font(String familyName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String familyName, float emSize)
```


使用指定的大小初始化 [Font](../../com.aspose.drawing/font) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| familyName | java.lang.String | 新 [Font](../../com.aspose.drawing/font) 的 FontFamily 的字符串表示。 |
| emSize | 浮点数 | 新字体的 em 大小（以点为单位）。 |

### Font(String familyName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String familyName, float emSize, int style)
```


使用指定的大小和样式初始化 [Font](../../com.aspose.drawing/font) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| familyName | java.lang.String | 新 [Font](../../com.aspose.drawing/font) 的 FontFamily 的字符串表示。 |
| emSize | 浮点数 | 新字体的 em 大小（以点为单位）。 |
| style | int | 新字体的 [FontStyle](../../com.aspose.drawing/fontstyle)。 |

### Font(String familyName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String familyName, float emSize, int style, int unit)
```


使用指定的大小、样式和单位初始化 [Font](../../com.aspose.drawing/font) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| familyName | java.lang.String | 新 [Font](../../com.aspose.drawing/font) 的 `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) 的字符串表示。 |
| emSize | 浮点数 | 新字体的 em 大小，单位由 `unit` 参数指定。 |
| style | int | 新字体的 [FontStyle](../../com.aspose.drawing/fontstyle)。 |
| unit | int | 新字体的 [GraphicsUnit](../../com.aspose.drawing/graphicsunit)。 |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet) {#Font-java.lang.String-float-int-int-byte-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)
```


使用指定的大小、样式、单位和字符集初始化 [Font](../../com.aspose.drawing/font) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| familyName | java.lang.String | 新 [Font](../../com.aspose.drawing/font) 的 FontFamily 的字符串表示。 |
| emSize | 浮点数 | 新字体的 em 大小，单位由 `unit` 参数指定。 |
| style | int | 新字体的 [FontStyle](../../com.aspose.drawing/fontstyle)。 |
| unit | int | 新字体的 [GraphicsUnit](../../com.aspose.drawing/graphicsunit)。 |
| gdiCharSet | byte | 一个字节，指定此字体使用的 GDI 字符集。 |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-java.lang.String-float-int-int-byte-boolean-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


使用指定的大小、样式、单位和字符集初始化 [Font](../../com.aspose.drawing/font) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| familyName | java.lang.String | 新 [Font](../../com.aspose.drawing/font) 的 FontFamily 的字符串表示。 |
| emSize | 浮点数 | 新字体的 em 大小，单位由 `unit` 参数指定。 |
| style | int | 新字体的 [FontStyle](../../com.aspose.drawing/fontstyle)。 |
| unit | int | 新字体的 [GraphicsUnit](../../com.aspose.drawing/graphicsunit)。 |
| gdiCharSet | byte | 一个字节，指定此字体使用的 GDI 字符集。 |
| gdiVerticalFont | boolean | 一个布尔值，指示新 [Font](../../com.aspose.drawing/font) 是否来源于 GDI 垂直字体。 |

### getFontFamily() {#getFontFamily--}
```
public FontFamily getFontFamily()
```


获取与此 [Font](../../com.aspose.drawing/font) 关联的 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))。

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - The `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font).
### getBold() {#getBold--}
```
public boolean getBold()
```


获取一个值，指示此 [Font](../../com.aspose.drawing/font) 是否为粗体。

**Returns:**
boolean - 一个指示此 [Font](../../com.aspose.drawing/font) 是否加粗的值。
### getGdiCharSet() {#getGdiCharSet--}
```
public byte getGdiCharSet()
```


获取一个字节值，指定此 [Font](../../com.aspose.drawing/font) 使用的 GDI 字符集。

**Returns:**
byte - 指定此 [Font](../../com.aspose.drawing/font) 使用的 GDI 字符集的字节值。
### getGdiVerticalFont() {#getGdiVerticalFont--}
```
public boolean getGdiVerticalFont()
```


获取一个值，指示此 [Font](../../com.aspose.drawing/font) 是否源自 GDI 垂直字体..

值：如果此 [Font](../../com.aspose.drawing/font) 源自 GDI 垂直字体，则为 `true`；否则为 `false`。

**Returns:**
boolean - 一个指示此 [Font](../../com.aspose.drawing/font) 是否源自 GDI 垂直字体的值。
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


获取一个值，指示此 [Font](../../com.aspose.drawing/font) 是否为斜体。

**Returns:**
boolean - 一个指示此 [Font](../../com.aspose.drawing/font) 是否斜体的值。
### getName() {#getName--}
```
public String getName()
```


获取此 [Font](../../com.aspose.drawing/font) 的字体名称。

**Returns:**
java.lang.String - 此 [Font](../../com.aspose.drawing/font) 的字体名称。
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


获取一个值，指示此 [Font](../../com.aspose.drawing/font) 是否指定在字体上加水平线。

**Returns:**
boolean - 一个指示此 [Font](../../com.aspose.drawing/font) 是否在字体上绘制水平线的值。
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


获取一个值，指示此 [Font](../../com.aspose.drawing/font) 是否带下划线。

**Returns:**
boolean - 一个指示此 [Font](../../com.aspose.drawing/font) 是否带下划线的值。
### getStyle() {#getStyle--}
```
public int getStyle()
```


获取此 [Font](../../com.aspose.drawing/font) 的样式信息。

**Returns:**
int - 此 [Font](../../com.aspose.drawing/font) 的样式信息。
### getSize() {#getSize--}
```
public float getSize()
```


获取此 [Font](../../com.aspose.drawing/font) 的 em 大小，单位由 `Font.Unit` 属性指定。

**Returns:**
float - 以 \\{@code Font 指定的单位测量的此 [Font](../../com.aspose.drawing/font) 的 em 大小。
### getSizeInPoints() {#getSizeInPoints--}
```
public float getSizeInPoints()
```


获取此 [Font](../../com.aspose.drawing/font) 的 em 大小（以点为单位）。

**Returns:**
float - 此 [Font](../../com.aspose.drawing/font) 的 em 大小（单位为点）。
### getUnit() {#getUnit--}
```
public int getUnit()
```


获取此 [Font](../../com.aspose.drawing/font) 的度量单位。

**Returns:**
int - 此 [Font](../../com.aspose.drawing/font) 的度量单位。
### getHeight_Rename_Namesake() {#getHeight-Rename-Namesake--}
```
public int getHeight_Rename_Namesake()
```


获取此字体的行间距。

值：此字体的行间距（像素）。

**Returns:**
int - 此字体的行间距。
### isSystemFont() {#isSystemFont--}
```
public boolean isSystemFont()
```


获取一个值，指示该字体是否是 [SystemFonts](../../com.aspose.drawing/systemfonts) 的成员。

值：如果该字体是 [SystemFonts](../../com.aspose.drawing/systemfonts) 的成员，则为 `true`；否则为 `false`。

**Returns:**
boolean - 一个指示该字体是否是 [SystemFonts](../../com.aspose.drawing/systemfonts) 成员的值。
### getSystemFontName() {#getSystemFontName--}
```
public String getSystemFontName()
```


如果 IsSystemFont 属性返回 true，则获取系统字体的名称。

值：如果 IsSystemFont 返回 true，则为系统字体的名称；否则为空字符串（\"\"）。

**Returns:**
java.lang.String - 如果 IsSystemFont 属性返回 true，则为系统字体的名称。
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


获取最初指定的字体名称。

值：表示最初指定的字体名称的字符串。

**Returns:**
java.lang.String - 最初指定的字体名称。
### deepClone() {#deepClone--}
```
public Font deepClone()
```


创建此 [Font](../../com.aspose.drawing/font) 的精确副本。

**Returns:**
[Font](../../com.aspose.drawing/font) - The [Font](../../com.aspose.drawing/font) this method creates, cast as an Object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指示指定的对象是否为 [Font](../../com.aspose.drawing/font) 且其 `FontFamily`([.getFontFamily](../../null/\#getFontFamily))、`M:GdiVerticalFont`、`M:GdiCharSet`、`M:Style`、`M:Size` 和 `M:Unit` 属性值与此 [Font](../../com.aspose.drawing/font) 相同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要测试的对象。 |

**Returns:**
boolean - 如果 obj 参数是 [Font](../../com.aspose.drawing/font) 且其 `FontFamily`（[.getFontFamily](../../null/\\#getFontFamily)）、`M:GdiVerticalFont`、`M:GdiCharSet`、`M:Style`、`M:Size` 和 `M:Unit` 属性值与此 [Font](../../com.aspose.drawing/font) 相同，则为 `true`；否则为 `false`。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取此 [Font](../../com.aspose.drawing/font) 的哈希码。

**Returns:**
int - 此 [Font](../../com.aspose.drawing/font) 的哈希码。
### getHeight() {#getHeight--}
```
public int getHeight()
```


返回此字体的行间距（以像素为单位）。

**Returns:**
int - 此字体的行间距（像素）。
### getHeight(Graphics graphics) {#getHeight-com.aspose.drawing.Graphics-}
```
public float getHeight(Graphics graphics)
```


返回此字体在指定的 [Graphics](../../com.aspose.drawing/graphics) 的当前单位下的行间距。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| graphics | [Graphics](../../com.aspose.drawing/graphics) | 一个 [Graphics](../../com.aspose.drawing/graphics)，它保存显示设备的垂直分辨率（每英寸点数），以及页面单位和页面比例的设置。 |

**Returns:**
float - 此字体的行间距（像素）。
### getHeight(float dpi) {#getHeight-float-}
```
public int getHeight(float dpi)
```


返回此 [Font](../../com.aspose.drawing/font) 在使用指定垂直分辨率的设备上绘制时的高度（以像素为单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dpi | 浮点数 | 垂直分辨率（每英寸点数），用于计算字体的高度。 |

**Returns:**
int - 此 [Font](../../com.aspose.drawing/font) 的高度（以像素为单位）。
### dispose() {#dispose--}
```
public void dispose()
```


释放此 [Font](../../com.aspose.drawing/font) 使用的所有资源。

### toString() {#toString--}
```
public String toString()
```


返回此 [Font](../../com.aspose.drawing/font) 的可读字符串表示。

**Returns:**
java.lang.String - 表示此 [Font](../../com.aspose.drawing/font) 的字符串。
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


获取一个字节值，指定此 `Font` 使用的字符集。

**Returns:**
int - 此 `Font` 使用的字符集。
