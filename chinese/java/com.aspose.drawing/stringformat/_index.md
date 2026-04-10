---
title: StringFormat
second_title: Aspose.Drawing for Java API 参考
description: 封装文本布局信息，例如对齐方向、制表位显示以及省略号插入、数字本地化替换和 OpenType 功能等操作。
type: docs
weight: 47
url: /zh/java/com.aspose.drawing/stringformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class StringFormat implements System.IDisposable
```

封装文本布局信息（例如对齐、方向和制表位）、显示操作（例如省略号插入和本地数字替换）以及 OpenType 功能。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StringFormat()](#StringFormat--) | 初始化一个新的 [StringFormat](../../com.aspose.drawing/stringformat) 类实例。 |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.drawing.StringFormat-) | 从指定的现有 [StringFormat](../../com.aspose.drawing/stringformat) 对象初始化一个新的 [StringFormat](../../com.aspose.drawing/stringformat) 类实例。 |
| [StringFormat(int options, int language)](#StringFormat-int-int-) | 使用指定的 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 枚举和语言初始化一个新的 [StringFormat](../../com.aspose.drawing/stringformat) 类实例。 |
| [StringFormat(int options)](#StringFormat-int-) | 使用指定的 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 枚举初始化一个新的 [StringFormat](../../com.aspose.drawing/stringformat) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) |  |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) |  |
| [getFirstTabOffset()](#getFirstTabOffset--) |  |
| [getGenericDefault()](#getGenericDefault--) | 获取一个通用的默认 [StringFormat](../../com.aspose.drawing/stringformat) 对象。 |
| [getGenericTypographic()](#getGenericTypographic--) | 获取一个通用的排版 [StringFormat](../../com.aspose.drawing/stringformat) 对象。 |
| [getFormatFlags()](#getFormatFlags--) | 获取或设置包含格式信息的 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 枚举。 |
| [setFormatFlags(int value)](#setFormatFlags-int-) | 获取或设置包含格式信息的 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 枚举。 |
| [getAlignment()](#getAlignment--) | 获取或设置垂直平面上的文本对齐信息。 |
| [setAlignment(int value)](#setAlignment-int-) | 获取或设置垂直平面上的文本对齐信息。 |
| [getLineAlignment()](#getLineAlignment--) | 获取或设置水平平面上的行对齐方式。 |
| [setLineAlignment(int value)](#setLineAlignment-int-) | 获取或设置水平平面上的行对齐方式。 |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | 获取或设置此 [StringFormat](../../com.aspose.drawing/stringformat) 对象的 `HotkeyPrefix`（[.getHotkeyPrefix](../../null/\\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\\#setHotkeyPrefix-int-)）对象。 |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | 获取或设置此 [StringFormat](../../com.aspose.drawing/stringformat) 对象的 `HotkeyPrefix`（[.getHotkeyPrefix](../../null/\\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\\#setHotkeyPrefix-int-)）对象。 |
| [getTrimming()](#getTrimming--) | 获取或设置此 [StringFormat](../../com.aspose.drawing/stringformat) 对象的 [StringTrimming](../../com.aspose.drawing/stringtrimming) 枚举。 |
| [setTrimming(int value)](#setTrimming-int-) | 获取或设置此 [StringFormat](../../com.aspose.drawing/stringformat) 对象的 [StringTrimming](../../com.aspose.drawing/stringtrimming) 枚举。 |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | 获取在本地数字替换为西方数字时使用的语言。 |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | 获取用于数字替换的方法。 |
| [dispose()](#dispose--) | 释放此 [StringFormat](../../com.aspose.drawing/stringformat) 对象使用的所有资源。 |
| [deepClone()](#deepClone--) | 创建此 [StringFormat](../../com.aspose.drawing/stringformat) 对象的精确副本。 |
| [getTabStops(float[] firstTabOffset)](#getTabStops-float---) | 获取此 [StringFormat](../../com.aspose.drawing/stringformat) 对象的制表位。 |
| [getTabStops()](#getTabStops--) | 获取一个数组，包含制表位之间的距离，单位由 `Aspose.Imaging.getGraphics().PageUnit` 属性指定。 |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | 为此 [StringFormat](../../com.aspose.drawing/stringformat) 对象设置制表位。 |
| [setDigitSubstitution(int language, int substitute)](#setDigitSubstitution-int-int-) | 指定在本地数字替换为西方数字时使用的语言和方法。 |
| [setMeasurableCharacterRanges(CharacterRange[] ranges)](#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---) | 指定一个 [CharacterRange](../../com.aspose.drawing/characterrange) 结构数组，表示通过调用 `MeasureCharacterRanges` 方法测量的字符范围。 |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


初始化一个新的 [StringFormat](../../com.aspose.drawing/stringformat) 类实例。

### StringFormat(StringFormat format) {#StringFormat-com.aspose.drawing.StringFormat-}
```
public StringFormat(StringFormat format)
```


从指定的现有 [StringFormat](../../com.aspose.drawing/stringformat) 对象初始化一个新的 [StringFormat](../../com.aspose.drawing/stringformat) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.drawing/stringformat) | 用于初始化新 [StringFormat](../../com.aspose.drawing/stringformat) 对象的 [StringFormat](../../com.aspose.drawing/stringformat) 对象。 |

### StringFormat(int options, int language) {#StringFormat-int-int-}
```
public StringFormat(int options, int language)
```


使用指定的 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 枚举和语言初始化一个新的 [StringFormat](../../com.aspose.drawing/stringformat) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | int | 新 [StringFormat](../../com.aspose.drawing/stringformat) 对象的 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 枚举。 |
| 语言 | int | 指示文本语言的值。 |

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


使用指定的 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 枚举初始化一个新的 [StringFormat](../../com.aspose.drawing/stringformat) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | int | 新 [StringFormat](../../com.aspose.drawing/stringformat) 对象的 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 枚举。 |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```




**Returns:**
浮点数
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


获取一个通用的默认 [StringFormat](../../com.aspose.drawing/stringformat) 对象。

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat)
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


获取一个通用的排版 [StringFormat](../../com.aspose.drawing/stringformat) 对象。

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - A generic typographic [StringFormat](../../com.aspose.drawing/stringformat) object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


获取或设置包含格式信息的 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 枚举。

**Returns:**
int
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


获取或设置包含格式信息的 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


获取或设置垂直平面上的文本对齐信息。

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


获取或设置垂直平面上的文本对齐信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


获取或设置水平平面上的行对齐方式。

**Returns:**
int
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


获取或设置水平平面上的行对齐方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


获取或设置此 [StringFormat](../../com.aspose.drawing/stringformat) 对象的 `HotkeyPrefix`（[.getHotkeyPrefix](../../null/\\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\\#setHotkeyPrefix-int-)）对象。

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


获取或设置此 [StringFormat](../../com.aspose.drawing/stringformat) 对象的 `HotkeyPrefix`（[.getHotkeyPrefix](../../null/\\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\\#setHotkeyPrefix-int-)）对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


获取或设置此 [StringFormat](../../com.aspose.drawing/stringformat) 对象的 [StringTrimming](../../com.aspose.drawing/stringtrimming) 枚举。

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


获取或设置此 [StringFormat](../../com.aspose.drawing/stringformat) 对象的 [StringTrimming](../../com.aspose.drawing/stringtrimming) 枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


获取在本地数字替换为西方数字时使用的语言。

**Returns:**
int - 一个国家语言支持 (NLS) 语言标识符，用于标识在本地数字替换为西方数字时将使用的语言。您可以将 java.util.Locale 对象的 `System.Globalization.CultureInfo.LCID` 属性作为 NLS 语言标识符传递。例如，假设您通过将字符串 "ar-EG" 传递给 java.util.Locale 构造函数来创建一个 java.util.Locale 对象。如果您将该 java.util.Locale 对象的 `System.Globalization.CultureInfo.LCID` 属性与`StringDigitSubstitute.Traditional`一起传递给 [.setDigitSubstitution(int,int)](../../null/\#setDigitSubstitution-int-int-) 方法，则阿拉伯-印度数字将在显示时被替换为西方数字。
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


获取用于数字替换的方法。

**Returns:**
int - 一个 [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) 枚举值，指定如何替换因当前字体不支持而无法显示的字符串中的字符。
### dispose() {#dispose--}
```
public void dispose()
```


释放此 [StringFormat](../../com.aspose.drawing/stringformat) 对象使用的所有资源。

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


创建此 [StringFormat](../../com.aspose.drawing/stringformat) 对象的精确副本。

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - The [StringFormat](../../com.aspose.drawing/stringformat) object this method creates.
### getTabStops(float[] firstTabOffset) {#getTabStops-float---}
```
public float[] getTabStops(float[] firstTabOffset)
```


获取此 [StringFormat](../../com.aspose.drawing/stringformat) 对象的制表位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstTabOffset | float[] | 文本行起始位置与第一个制表位之间的空格数。 |

**Returns:**
float[] - 一个数组，表示制表位之间的距离（以空格数计）。
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


获取一个数组，包含制表位之间的距离，单位由 `Aspose.Imaging.getGraphics().PageUnit` 属性指定。

**Returns:**
float[] - 制表位。

该属性是为已移除的方法 GetTabStops 引入的。
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


为此 [StringFormat](../../com.aspose.drawing/stringformat) 对象设置制表位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstTabOffset | 浮点数 | 文本行起始位置与第一个制表位之间的空格数。 |
| tabStops | float[] | 一个数组，表示制表位之间的距离，单位由 Graphics.PageUnit 属性指定。 |

### setDigitSubstitution(int language, int substitute) {#setDigitSubstitution-int-int-}
```
public void setDigitSubstitution(int language, int substitute)
```


指定在本地数字替换为西方数字时使用的语言和方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 语言 | int | 一个国家语言支持 (NLS) 语言标识符，用于标识在本地数字替换为西方数字时将使用的语言。您可以将 java.util.Locale 对象的 `System.Globalization.CultureInfo.LCID` 属性作为 NLS 语言标识符传递。例如，假设您通过将字符串 `"ar-EG"` 传递给 java.util.Locale 构造函数来创建一个 java.util.Locale 对象。如果您将该 java.util.Locale 对象的 `System.Globalization.CultureInfo.LCID` 属性与 `StringDigitSubstitute.Traditional` 一起传递给 `M:StringFormat.SetDigitSubstitution(System.Int32,StringDigitSubstitute)` 方法，则阿拉伯-印度数字将在显示时被替换为西方数字。 |
| substitute | int | 一个 [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) 枚举的元素，指定数字的显示方式。 |

### setMeasurableCharacterRanges(CharacterRange[] ranges) {#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---}
```
public void setMeasurableCharacterRanges(CharacterRange[] ranges)
```


指定一个 [CharacterRange](../../com.aspose.drawing/characterrange) 结构数组，表示通过调用 `MeasureCharacterRanges` 方法测量的字符范围。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ranges | [CharacterRange\[\]](../../com.aspose.drawing/characterrange) | 一个 [CharacterRange](../../com.aspose.drawing/characterrange) 结构的数组，指定通过调用 `MeasureCharacterRanges` 方法测量的字符范围。 |

