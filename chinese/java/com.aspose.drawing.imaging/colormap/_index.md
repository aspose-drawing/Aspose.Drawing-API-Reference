---
title: ColorMap
second_title: Aspose.Drawing for Java API 参考
description: 定义用于转换颜色的映射。
type: docs
weight: 13
url: /zh/java/com.aspose.drawing.imaging/colormap/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMap
```

定义颜色转换映射。[ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 类的多种方法通过使用颜色重新映射表（即 [ColorMap](../../com.aspose.drawing.imaging/colormap) 结构数组）来调整图像颜色。不可继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorMap()](#ColorMap--) | 初始化 [ColorMap](../../com.aspose.drawing.imaging/colormap) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOldColor()](#getOldColor--) | 获取要转换的现有 [Color](../../com.aspose.drawing/color) 结构。 |
| [setOldColor(Color value)](#setOldColor-com.aspose.drawing.Color-) | 设置要转换的现有 [Color](../../com.aspose.drawing/color) 结构。 |
| [getNewColor()](#getNewColor--) | 获取要转换到的新 [Color](../../com.aspose.drawing/color) 结构。 |
| [setNewColor(Color value)](#setNewColor-com.aspose.drawing.Color-) | 设置要转换到的新 [Color](../../com.aspose.drawing/color) 结构。 |
### ColorMap() {#ColorMap--}
```
public ColorMap()
```


初始化 [ColorMap](../../com.aspose.drawing.imaging/colormap) 类的新实例。

### getOldColor() {#getOldColor--}
```
public Color getOldColor()
```


获取要转换的现有 [Color](../../com.aspose.drawing/color) 结构。

**Returns:**
[Color](../../com.aspose.drawing/color) - The existing [Color](../../com.aspose.drawing/color) structure to be converted.
### setOldColor(Color value) {#setOldColor-com.aspose.drawing.Color-}
```
public void setOldColor(Color value)
```


设置要转换的现有 [Color](../../com.aspose.drawing/color) 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) | 要转换的现有 [Color](../../com.aspose.drawing/color) 结构。 |

### getNewColor() {#getNewColor--}
```
public Color getNewColor()
```


获取要转换到的新 [Color](../../com.aspose.drawing/color) 结构。

**Returns:**
[Color](../../com.aspose.drawing/color) - The new [Color](../../com.aspose.drawing/color) structure to which to convert.
### setNewColor(Color value) {#setNewColor-com.aspose.drawing.Color-}
```
public void setNewColor(Color value)
```


设置要转换到的新 [Color](../../com.aspose.drawing/color) 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) | 要转换到的新 [Color](../../com.aspose.drawing/color) 结构。 |

