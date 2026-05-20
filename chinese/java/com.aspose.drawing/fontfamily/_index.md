---
title: FontFamily
second_title: Aspose.Drawing for Java API 参考
description: 定义一组具有相似基本设计和某些样式变体的字体族。
type: docs
weight: 24
url: /zh/java/com.aspose.drawing/fontfamily/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class FontFamily implements System.IDisposable
```

定义一组具有相似基本设计和某些样式变体的字体族。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontFamily(String name)](#FontFamily-java.lang.String-) | 使用指定的名称初始化 [FontFamily](../../com.aspose.drawing/fontfamily) 类的新实例。 |
| [FontFamily(String name, FontCollection fontCollection)](#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-) | 初始化 [FontFamily](../../com.aspose.drawing/fontfamily) 类的新实例。 |
| [FontFamily(String name, FontFamilyDefinition definition)](#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-) | 初始化 [FontFamily](../../com.aspose.drawing/fontfamily) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFamilies()](#getFamilies--) | 获取一个数组，其中包含与当前图形上下文关联的所有 [FontFamily](../../com.aspose.drawing/fontfamily) 对象。 |
| [getGenericSansSerif()](#getGenericSansSerif--) | 获取一个通用无衬线 [FontFamily](../../com.aspose.drawing/fontfamily) 对象。 |
| [getGenericSerif()](#getGenericSerif--) | 获取一个通用衬线 [FontFamily](../../com.aspose.drawing/fontfamily) 对象。 |
| [getGenericMonospace()](#getGenericMonospace--) | 获取一个通用等宽 [FontFamily](../../com.aspose.drawing/fontfamily) 对象。 |
| [getName()](#getName--) | 获取此 [FontFamily](../../com.aspose.drawing/fontfamily) 的名称。 |
| [dispose()](#dispose--) | 释放此 [FontFamily](../../com.aspose.drawing/fontfamily) 使用的所有资源。 |
| [getName(int language)](#getName-int-) | 返回此 [FontFamily](../../com.aspose.drawing/fontfamily) 在指定语言中的名称。 |
| [isStyleAvailable(int style)](#isStyleAvailable-int-) | 指示指定的 [FontStyle](../../com.aspose.drawing/fontstyle) 枚举是否可用。 |
| [getEmHeight(int style)](#getEmHeight-int-) | 获取指定样式的 EM 方块的高度（以字体设计单位计）。 |
| [getCellAscent(int style)](#getCellAscent-int-) | 返回指定样式的 [FontFamily](../../com.aspose.drawing/fontfamily) 的单元上升高度（以设计单位计）。 |
| [getCellDescent(int style)](#getCellDescent-int-) | 返回指定样式的 [FontFamily](../../com.aspose.drawing/fontfamily) 的单元下降高度（以设计单位计）。 |
| [hashCode()](#hashCode--) | 获取此 [FontFamily](../../com.aspose.drawing/fontfamily) 的哈希码。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指示指定的对象是否为 [FontFamily](../../com.aspose.drawing/fontfamily) 且与此 [FontFamily](../../com.aspose.drawing/fontfamily) 完全相同。 |
| [getLineSpacing(int style)](#getLineSpacing-int-) | 返回指定样式的 [FontFamily](../../com.aspose.drawing/fontfamily) 的行间距（以设计单位计）。 |
### FontFamily(String name) {#FontFamily-java.lang.String-}
```
public FontFamily(String name)
```


使用指定的名称初始化 [FontFamily](../../com.aspose.drawing/fontfamily) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 新 [FontFamily](../../com.aspose.drawing/fontfamily) 的名称。 |

### FontFamily(String name, FontCollection fontCollection) {#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-}
```
public FontFamily(String name, FontCollection fontCollection)
```


初始化 [FontFamily](../../com.aspose.drawing/fontfamily) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 字体系列的名称。 |
| fontCollection | [FontCollection](../../com.aspose.drawing/fontcollection) | 字体集合。 |

### FontFamily(String name, FontFamilyDefinition definition) {#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-}
```
public FontFamily(String name, FontFamilyDefinition definition)
```


初始化 [FontFamily](../../com.aspose.drawing/fontfamily) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 字体系列的名称。 |
| definition | [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) | 定义。 |

### getFamilies() {#getFamilies--}
```
public static FontFamily[] getFamilies()
```


获取一个数组，其中包含与当前图形上下文关联的所有 [FontFamily](../../com.aspose.drawing/fontfamily) 对象。

**Returns:**
com.aspose.drawing.FontFamily[] - 与当前图形上下文关联的 [FontFamily](../../com.aspose.drawing/fontfamily) 对象数组。
### getGenericSansSerif() {#getGenericSansSerif--}
```
public static FontFamily getGenericSansSerif()
```


获取一个通用无衬线 [FontFamily](../../com.aspose.drawing/fontfamily) 对象。

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) object that represents a generic sans serif font.
### getGenericSerif() {#getGenericSerif--}
```
public static FontFamily getGenericSerif()
```


获取一个通用衬线 [FontFamily](../../com.aspose.drawing/fontfamily) 对象。

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic serif font.
### getGenericMonospace() {#getGenericMonospace--}
```
public static FontFamily getGenericMonospace()
```


获取一个通用等宽 [FontFamily](../../com.aspose.drawing/fontfamily) 对象。

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic monospace font.
### getName() {#getName--}
```
public String getName()
```


获取此 [FontFamily](../../com.aspose.drawing/fontfamily) 的名称。

**Returns:**
java.lang.String - 表示此 [FontFamily](../../com.aspose.drawing/fontfamily) 名称的字符串。
### dispose() {#dispose--}
```
public void dispose()
```


释放此 [FontFamily](../../com.aspose.drawing/fontfamily) 使用的所有资源。

### getName(int language) {#getName-int-}
```
public String getName(int language)
```


返回此 [FontFamily](../../com.aspose.drawing/fontfamily) 在指定语言中的名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 语言 | int | 返回名称的语言。 |

**Returns:**
java.lang.String - 表示此 [FontFamily](../../com.aspose.drawing/fontfamily) 在指定语言中的名称的字符串。
### isStyleAvailable(int style) {#isStyleAvailable-int-}
```
public boolean isStyleAvailable(int style)
```


指示指定的 [FontStyle](../../com.aspose.drawing/fontstyle) 枚举是否可用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| style | int | 要测试的 [FontStyle](../../com.aspose.drawing/fontstyle)。 |

**Returns:**
boolean - 如果指定的 [FontStyle](../../com.aspose.drawing/fontstyle) 可用则为 true；否则为 false。
### getEmHeight(int style) {#getEmHeight-int-}
```
public int getEmHeight(int style)
```


获取指定样式的 EM 方块的高度（以字体设计单位计）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| style | int | 要获取 EM 高度的 [FontStyle](../../com.aspose.drawing/fontstyle)。 |

**Returns:**
int - EM 方块的高度。
### getCellAscent(int style) {#getCellAscent-int-}
```
public int getCellAscent(int style)
```


返回指定样式的 [FontFamily](../../com.aspose.drawing/fontfamily) 的单元上升高度（以设计单位计）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| style | int | 包含字体样式信息的 [FontStyle](../../com.aspose.drawing/fontstyle)。 |

**Returns:**
int - 使用指定 [FontStyle](../../com.aspose.drawing/fontstyle) 的此 [FontFamily](../../com.aspose.drawing/fontfamily) 的单元上升高度。
### getCellDescent(int style) {#getCellDescent-int-}
```
public int getCellDescent(int style)
```


返回指定样式的 [FontFamily](../../com.aspose.drawing/fontfamily) 的单元下降高度（以设计单位计）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| style | int | 包含字体样式信息的 [FontStyle](../../com.aspose.drawing/fontstyle)。 |

**Returns:**
int - 使用指定 [FontStyle](../../com.aspose.drawing/fontstyle) 的此 [FontFamily](../../com.aspose.drawing/fontfamily) 的单元下降度量。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取此 [FontFamily](../../com.aspose.drawing/fontfamily) 的哈希码。

**Returns:**
int - 此 [FontFamily](../../com.aspose.drawing/fontfamily) 的哈希码。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指示指定的对象是否为 [FontFamily](../../com.aspose.drawing/fontfamily) 且与此 [FontFamily](../../com.aspose.drawing/fontfamily) 完全相同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要测试的对象。 |

**Returns:**
boolean - 如果 `obj` 是 [FontFamily](../../com.aspose.drawing/fontfamily) 且与此 [FontFamily](../../com.aspose.drawing/fontfamily) 完全相同，则为 `true`；否则为 `false`。
### getLineSpacing(int style) {#getLineSpacing-int-}
```
public int getLineSpacing(int style)
```


返回指定样式的 [FontFamily](../../com.aspose.drawing/fontfamily) 的行间距（以设计单位计）。行间距是两行连续文本基线之间的垂直距离。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| style | int | 要应用的 [FontStyle](../../com.aspose.drawing/fontstyle)。 |

**Returns:**
int - 两行连续文本之间的距离。
