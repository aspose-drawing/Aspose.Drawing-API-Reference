---
title: HatchBrush
second_title: Aspose.Drawing for Java API 参考
description: 定义一种具有网格样式、前景色和背景色的矩形画刷。
type: docs
weight: 26
url: /zh/java/com.aspose.drawing.drawing2d/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class HatchBrush extends Brush
```

定义一种具有网格样式、前景色和背景色的矩形画刷。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HatchBrush(int hatchstyle, Color foreColor)](#HatchBrush-int-com.aspose.drawing.Color-) | 使用指定的 `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) 枚举和前景色，初始化 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 类的新实例。 |
| [HatchBrush(int hatchstyle, Color foreColor, Color backColor)](#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-) | 使用指定的 `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) 枚举、前景色和背景色，初始化 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHatchStyle()](#getHatchStyle--) | 获取此 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 对象的网格样式。 |
| [getForegroundColor()](#getForegroundColor--) | 获取此 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 对象绘制的网格线的颜色。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取此 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 对象绘制的网格线之间空隙的颜色。 |
| [deepClone()](#deepClone--) | 创建此 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 对象的精确副本。 |
### HatchBrush(int hatchstyle, Color foreColor) {#HatchBrush-int-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor)
```


使用指定的 `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) 枚举和前景色，初始化 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hatchstyle | int | 表示此 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 绘制的图案的 `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) 值之一。 |
| foreColor | [Color](../../com.aspose.drawing/color) | 表示此 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 绘制的线条颜色的 [Color](../../com.aspose.drawing/color) 结构。 |

### HatchBrush(int hatchstyle, Color foreColor, Color backColor) {#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor, Color backColor)
```


使用指定的 `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) 枚举、前景色和背景色，初始化 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hatchstyle | int | 表示此 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 绘制的图案的 `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) 值之一。 |
| foreColor | [Color](../../com.aspose.drawing/color) | 表示此 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 绘制的线条颜色的 [Color](../../com.aspose.drawing/color) 结构。 |
| backColor | [Color](../../com.aspose.drawing/color) | 表示此 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 绘制的线条之间空隙颜色的 [Color](../../com.aspose.drawing/color) 结构。 |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


获取此 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 对象的网格样式。

**Returns:**
int - 此 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 对象的网格样式。
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


获取此 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 对象绘制的网格线的颜色。

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


获取此 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 对象绘制的网格线之间空隙的颜色。

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of spaces between the hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


创建此 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 对象的精确副本。

**Returns:**
java.lang.Object - 此方法创建的 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)，作为对象进行强制转换。
