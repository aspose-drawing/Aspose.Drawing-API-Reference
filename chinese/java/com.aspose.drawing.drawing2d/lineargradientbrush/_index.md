---
title: LinearGradientBrush
second_title: Aspose.Drawing for Java API 参考
description: 封装一个具有线性渐变的对象。
type: docs
weight: 31
url: /zh/java/com.aspose.drawing.drawing2d/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class LinearGradientBrush extends Brush
```

封装一个带有线性渐变的 [Brush](../../com.aspose.drawing/brush)。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-) | 使用指定的点和颜色初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。 |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-) | 使用指定的点和颜色初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。 |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | 基于矩形、起始和结束颜色以及方向模式，初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。 |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | 基于矩形、起始和结束颜色以及方向，初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。 |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | 基于矩形、起始和结束颜色以及方向角，初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。 |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | 基于矩形、起始和结束颜色以及方向角，初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。 |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | 基于矩形、起始和结束颜色以及方向角，初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。 |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | 基于矩形、起始和结束颜色以及方向角，初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLinearColors()](#getLinearColors--) | 获取或设置渐变的起始和结束颜色。 |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.drawing.Color---) | 获取或设置渐变的起始和结束颜色。 |
| [getRectangle()](#getRectangle--) | 获取定义渐变起始和结束点的矩形区域。 |
| [getGammaCorrection()](#getGammaCorrection--) | 获取或设置一个值，指示是否为此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 启用伽马校正。 |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | 获取或设置一个值，指示是否为此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 启用伽马校正。 |
| [getBlend()](#getBlend--) | 获取或设置一个 `Blend`（[.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)），它指定用于定义渐变自定义衰减的位置信息和因子。 |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | 获取或设置一个 `Blend`（[.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)），它指定用于定义渐变自定义衰减的位置信息和因子。 |
| [getInterpolationColors()](#getInterpolationColors--) | 获取或设置一个 [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)，它定义多颜色线性渐变。 |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | 获取或设置一个 [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)，它定义多颜色线性渐变。 |
| [getWrapMode()](#getWrapMode--) | 获取或设置一个 `WrapMode` 枚举，指示此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 的包装模式。 |
| [setWrapMode(int value)](#setWrapMode-int-) | 获取或设置一个 `WrapMode` 枚举，指示此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 的包装模式。 |
| [getTransform()](#getTransform--) | 获取或设置一个复制的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)，它定义此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 的局部几何变换。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | 获取或设置一个复制的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)，它定义此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 的局部几何变换。 |
| [deepClone()](#deepClone--) | 创建此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 的精确副本。 |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | 基于钟形曲线创建渐变衰减。 |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | 基于钟形曲线创建渐变衰减。 |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | 创建具有中心颜色的线性渐变，并在两端线性衰减至单一颜色。 |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | 创建具有中心颜色的线性渐变，并在两端线性衰减至单一颜色。 |
| [resetTransform()](#resetTransform--) | 将 `LinearGradientBrush.Transform` 属性重置为单位矩阵。 |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | 将表示此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 局部几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 与指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 相乘，并在前面预置指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | 按照指定顺序，将表示此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 局部几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 与指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 相乘。 |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 按指定的尺寸平移局部几何变换。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 按指定的顺序，以指定的尺寸平移局部几何变换。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 按指定的量缩放局部几何变换。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 按指定的顺序，以指定的量缩放局部几何变换。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | 按指定的角度旋转局部几何变换。 |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 按指定的顺序，以指定的角度旋转局部几何变换。 |
### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


使用指定的点和颜色初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | 一个表示线性渐变起始点的 [PointF](../../com.aspose.drawing/pointf) 结构。 |
| point2 | [PointF](../../com.aspose.drawing/pointf) | 一个表示线性渐变终点的 [PointF](../../com.aspose.drawing/pointf) 结构。 |
| color1 | [Color](../../com.aspose.drawing/color) | 一个表示线性渐变起始颜色的 [Color](../../com.aspose.drawing/color) 结构。 |
| color2 | [Color](../../com.aspose.drawing/color) | 一个表示线性渐变结束颜色的 [Color](../../com.aspose.drawing/color) 结构。 |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


使用指定的点和颜色初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | 一个表示线性渐变起始点的 [Point](../../com.aspose.drawing/point) 结构。 |
| point2 | [Point](../../com.aspose.drawing/point) | 一个表示线性渐变终点的 [Point](../../com.aspose.drawing/point) 结构。 |
| color1 | [Color](../../com.aspose.drawing/color) | 一个表示线性渐变起始颜色的 [Color](../../com.aspose.drawing/color) 结构。 |
| color2 | [Color](../../com.aspose.drawing/color) | 一个表示线性渐变结束颜色的 [Color](../../com.aspose.drawing/color) 结构。 |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)
```


基于矩形、起始和结束颜色以及方向模式，初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 一个指定线性渐变边界的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |
| color1 | [Color](../../com.aspose.drawing/color) | 一个表示渐变起始颜色的 [Color](../../com.aspose.drawing/color) 结构。 |
| color2 | [Color](../../com.aspose.drawing/color) | 表示渐变结束颜色的 [Color](../../com.aspose.drawing/color) 结构。 |
| linearGradientMode | int | 指定渐变方向的 [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) 枚举元素。方向决定渐变的起始点和结束点。例如，LinearGradientMode.ForwardDiagonal 指定起始点为矩形的左上角，结束点为矩形的右下角。 |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)
```


基于矩形、起始和结束颜色以及方向，初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 指定线性渐变边界的 `Rectangle`([.getRectangle](../../null/\#getRectangle)) 结构。 |
| color1 | [Color](../../com.aspose.drawing/color) | 一个表示渐变起始颜色的 [Color](../../com.aspose.drawing/color) 结构。 |
| color2 | [Color](../../com.aspose.drawing/color) | 表示渐变结束颜色的 [Color](../../com.aspose.drawing/color) 结构。 |
| linearGradientMode | int | 指定渐变方向的 [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) 枚举元素。方向决定渐变的起始点和结束点。例如，LinearGradientMode.ForwardDiagonal 指定起始点为矩形的左上角，结束点为矩形的右下角。 |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


基于矩形、起始和结束颜色以及方向角，初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 一个指定线性渐变边界的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |
| color1 | [Color](../../com.aspose.drawing/color) | 一个表示渐变起始颜色的 [Color](../../com.aspose.drawing/color) 结构。 |
| color2 | [Color](../../com.aspose.drawing/color) | 表示渐变结束颜色的 [Color](../../com.aspose.drawing/color) 结构。 |
| 角度 | 浮点数 | 渐变方向线的角度，以顺时针方向从 x 轴测量的度数。 |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


基于矩形、起始和结束颜色以及方向角，初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 一个指定线性渐变边界的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |
| color1 | [Color](../../com.aspose.drawing/color) | 一个表示渐变起始颜色的 [Color](../../com.aspose.drawing/color) 结构。 |
| color2 | [Color](../../com.aspose.drawing/color) | 表示渐变结束颜色的 [Color](../../com.aspose.drawing/color) 结构。 |
| 角度 | 浮点数 | 渐变方向线的角度，以顺时针方向从 x 轴测量的度数。 |
| isAngleScaleable | boolean | 设置为 true 以指定该角度受与此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 关联的变换影响；否则为 false。 |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


基于矩形、起始和结束颜色以及方向角，初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 指定线性渐变边界的 `Rectangle`([.getRectangle](../../null/\#getRectangle)) 结构。 |
| color1 | [Color](../../com.aspose.drawing/color) | 一个表示渐变起始颜色的 [Color](../../com.aspose.drawing/color) 结构。 |
| color2 | [Color](../../com.aspose.drawing/color) | 表示渐变结束颜色的 [Color](../../com.aspose.drawing/color) 结构。 |
| 角度 | 浮点数 | 渐变方向线的角度，以顺时针方向从 x 轴测量的度数。 |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


基于矩形、起始和结束颜色以及方向角，初始化 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 指定线性渐变边界的 `Rectangle`([.getRectangle](../../null/\#getRectangle)) 结构。 |
| color1 | [Color](../../com.aspose.drawing/color) | 一个表示渐变起始颜色的 [Color](../../com.aspose.drawing/color) 结构。 |
| color2 | [Color](../../com.aspose.drawing/color) | 表示渐变结束颜色的 [Color](../../com.aspose.drawing/color) 结构。 |
| 角度 | 浮点数 | 渐变方向线的角度，以顺时针方向从 x 轴测量的度数。 |
| isAngleScaleable | boolean | 设置为 true 以指定该角度受与此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 关联的变换影响；否则为 false。 |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


获取或设置渐变的起始和结束颜色。

**Returns:**
com.aspose.drawing.Color[]
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.drawing.Color---}
```
public void setLinearColors(Color[] value)
```


获取或设置渐变的起始和结束颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


获取定义渐变起始和结束点的矩形区域。

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


获取或设置一个值，指示是否为此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 启用伽马校正。

**Returns:**
布尔型
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


获取或设置一个值，指示是否为此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 启用伽马校正。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 布尔型 |  |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


获取或设置一个 `Blend`（[.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)），它指定用于定义渐变自定义衰减的位置信息和因子。

**Returns:**
[Blend](../../com.aspose.drawing.drawing2d/blend)
### setBlend(Blend value) {#setBlend-com.aspose.drawing.drawing2d.Blend-}
```
public void setBlend(Blend value)
```


获取或设置一个 `Blend`（[.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)），它指定用于定义渐变自定义衰减的位置信息和因子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Blend](../../com.aspose.drawing.drawing2d/blend) |  |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


获取或设置一个 [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)，它定义多颜色线性渐变。

**Returns:**
[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


获取或设置一个 [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)，它定义多颜色线性渐变。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


获取或设置一个 `WrapMode` 枚举，指示此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 的包装模式。

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


获取或设置一个 `WrapMode` 枚举，指示此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 的包装模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


获取或设置一个复制的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)，它定义此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 的局部几何变换。

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


获取或设置一个复制的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)，它定义此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 的局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


创建此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 的精确副本。

**Returns:**
java.lang.Object - 此方法创建的 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)，作为对象进行强制转换。
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


基于钟形曲线创建渐变衰减。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 焦点 | 浮点数 | 取值范围为 0 到 1，指定渐变的中心（起始颜色和结束颜色等比例混合的点）。 |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


基于钟形曲线创建渐变衰减。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 焦点 | 浮点数 | 取值范围为 0 到 1，指定渐变的中心（仅由结束颜色组成的点）。 |
| 比例 | 浮点数 | 取值范围为 0 到 1，指定颜色从 `focus` 衰减的速度。 |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


创建具有中心颜色的线性渐变，并在两端线性衰减至单一颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 焦点 | 浮点数 | 取值范围为 0 到 1，指定渐变的中心（仅由结束颜色组成的点）。 |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


创建具有中心颜色的线性渐变，并在两端线性衰减至单一颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 焦点 | 浮点数 | 取值范围为 0 到 1，指定渐变的中心（仅由结束颜色组成的点）。 |
| 比例 | 浮点数 | 取值范围为 0 到 1，指定颜色从起始颜色到 `focus`（结束颜色）的衰减速度。 |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


将 `LinearGradientBrush.Transform` 属性重置为单位矩阵。

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


将表示此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 局部几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 与指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 相乘，并在前面预置指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 用于乘以几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


按照指定顺序，将表示此 [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) 局部几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 与指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 相乘。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 用于乘以几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)。 |
| order | int | 指定两个矩阵相乘顺序的 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)。 |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


按指定尺寸平移本地几何变换。此方法将在变换前预先添加平移。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | 浮点数 | x 方向的平移值。 |
| dy | 浮点数 | y 方向的平移值。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


按指定的顺序，以指定的尺寸平移局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | 浮点数 | x 方向的平移值。 |
| dy | 浮点数 | y 方向的平移值。 |
| 顺序 | int | 应用平移的顺序（预先或追加）。 |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


按指定的量缩放本地几何变换。此方法将缩放矩阵预先添加到变换中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | 浮点数 | 在 x 轴方向上缩放变换的量。 |
| sy | 浮点数 | 在 y 轴方向上缩放变换的量。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


按指定的顺序，以指定的量缩放局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | 浮点数 | 在 x 轴方向上缩放变换的量。 |
| sy | 浮点数 | 在 y 轴方向上缩放变换的量。 |
| order | int | 一个 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)，用于指定是追加还是预置缩放矩阵。 |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


按指定的量旋转本地几何变换。此方法将旋转矩阵预先添加到变换中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 浮点数 | 旋转角度。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


按指定的顺序，以指定的角度旋转局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 浮点数 | 旋转角度。 |
| order | int | 一个 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)，用于指定是追加还是预置旋转矩阵。 |

