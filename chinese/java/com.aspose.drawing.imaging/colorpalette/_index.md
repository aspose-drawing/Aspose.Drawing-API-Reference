---
title: ColorPalette
second_title: Aspose.Drawing for Java API 参考
description: 定义组成颜色调色板的颜色数组。
type: docs
weight: 16
url: /zh/java/com.aspose.drawing.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPalette
```

定义组成颜色调色板的颜色数组。颜色为 32 位 ARGB 颜色。不可继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorPalette(int count)](#ColorPalette-int-) | 初始化 `ColorPalette` 类的新实例，且 IsCompactPalette 为 false。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEntries()](#getEntries--) | 获取 `com.aspose.drawing.Color` 结构的数组。 |
| [isCompactPalette()](#isCompactPalette--) | 获取或设置指示是否使用紧凑调色板的值。 |
| [getFlags()](#getFlags--) |  |
| [setFlags(int flags)](#setFlags-int-) |  |
| [setEntries(int i, Color color)](#setEntries-int-com.aspose.drawing.Color-) |  |
### ColorPalette(int count) {#ColorPalette-int-}
```
public ColorPalette(int count)
```


初始化 `ColorPalette` 类的新实例，且 IsCompactPalette 为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| count | int | 颜色调色板条目。 |

### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


获取 `com.aspose.drawing.Color` 结构的数组。

**Returns:**
com.aspose.drawing.Color[] - 条目。由 `com.aspose.drawing.Color` 结构组成的数组，构成此 `Aspose.Imaging.ColorPalette`。
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


获取或设置指示是否使用紧凑调色板的值。

**Returns:**
boolean - 如果使用紧凑调色板则为 `true`；否则为 `false`。

紧凑调色板意味着图像将在可能的情况下仅包含指定的调色板条目，换句话说，图像将更紧凑并占用更少空间；否则将有 2^BitsPerPixel 条目，图像将为所有可能的调色板条目保留更多空间。将此值设为 true 并更改调色板条目可能会导致性能惩罚，因为可能会发生数据移动，所以请谨慎使用。
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| flags | int |  |

### setEntries(int i, Color color) {#setEntries-int-com.aspose.drawing.Color-}
```
public void setEntries(int i, Color color)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | int |  |
| color | [Color](../../com.aspose.drawing/color) |  |

