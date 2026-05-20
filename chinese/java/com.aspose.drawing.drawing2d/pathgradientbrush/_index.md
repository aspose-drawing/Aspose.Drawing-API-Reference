---
title: PathGradientBrush
second_title: Aspose.Drawing for Java API 参考
description: 封装一个对象，以渐变填充另一个对象的内部。
type: docs
weight: 36
url: /zh/java/com.aspose.drawing.drawing2d/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class PathGradientBrush extends Brush
```

封装一个 [Brush](../../com.aspose.drawing/brush) 对象，以渐变填充 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 对象的内部。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.drawing.PointF---) | 使用指定的点初始化 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 类的新实例。 |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.PointF---int-) | 使用指定的点和包装模式初始化 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 类的新实例。 |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.drawing.Point---) | 使用指定的点初始化 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 类的新实例。 |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.Point---int-) | 使用指定的点和包装模式初始化 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 类的新实例。 |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-) | 使用指定的路径初始化 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCenterColor()](#getCenterColor--) | 获取或设置路径渐变中心的颜色。 |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.drawing.Color-) | 获取或设置路径渐变中心的颜色。 |
| [getSurroundColors()](#getSurroundColors--) | 获取或设置与此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 填充的路径中的点对应的颜色数组。 |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.drawing.Color---) | 获取或设置与此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 填充的路径中的点对应的颜色数组。 |
| [getCenterPoint()](#getCenterPoint--) | 获取或设置路径渐变的中心点。 |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.drawing.PointF-) | 获取或设置路径渐变的中心点。 |
| [getRectangle()](#getRectangle--) | 获取此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 的边界矩形。 |
| [getBlend()](#getBlend--) | 获取或设置一个 `Blend`（[.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)），它指定用于定义渐变自定义衰减的位置信息和因子。 |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | 获取或设置一个 `Blend`（[.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)），它指定用于定义渐变自定义衰减的位置信息和因子。 |
| [getInterpolationColors()](#getInterpolationColors--) | 获取或设置一个 [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)，它定义多颜色线性渐变。 |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | 获取或设置一个 [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)，它定义多颜色线性渐变。 |
| [getTransform()](#getTransform--) | 获取或设置定义此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 本地几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 的副本。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | 获取或设置定义此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 本地几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 的副本。 |
| [getFocusScales()](#getFocusScales--) | 获取或设置渐变衰减的焦点。 |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.drawing.PointF-) | 获取或设置渐变衰减的焦点。 |
| [getWrapMode()](#getWrapMode--) | 获取或设置一个 `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-))，指示此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 的包装模式。 |
| [setWrapMode(int value)](#setWrapMode-int-) | 获取或设置一个 `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-))，指示此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 的包装模式。 |
| [deepClone()](#deepClone--) | 创建此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 的精确副本。 |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | 创建一种渐变画刷，使颜色从路径中心向外变化至路径边界。 |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | 创建一种渐变画刷，使颜色从路径中心向外变化至路径边界。 |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | 创建一种渐变，以中心颜色和线性衰减至一种周围颜色。 |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | 创建一个以中心颜色为起点、向每个周围颜色线性衰减的渐变。 |
| [resetTransform()](#resetTransform--) | 将 `PathGradientBrush.Transform` 属性重置为单位矩阵。 |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | 使用刷子的变换矩阵乘以另一个矩阵的乘积来更新刷子的变换矩阵。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | 使用刷子的变换矩阵乘以另一个矩阵的乘积来更新刷子的变换矩阵。 |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 将指定的平移应用于局部几何变换。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 按指定顺序将指定的平移应用于局部几何变换。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 按指定的量缩放局部几何变换。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 按指定的顺序，以指定的量缩放局部几何变换。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | 按指定的角度旋转局部几何变换。 |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 按指定的顺序，以指定的角度旋转局部几何变换。 |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.drawing.PointF---}
```
public PathGradientBrush(PointF[] points)
```


使用指定的点初始化 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | 一个由 [PointF](../../com.aspose.drawing/pointf) 结构组成的数组，表示构成路径顶点的点。 |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


使用指定的点和包装模式初始化 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | 一个由 [PointF](../../com.aspose.drawing/pointf) 结构组成的数组，表示构成路径顶点的点。 |
| wrapMode | int | 一个 `WrapMode`（[.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)）用于指定使用此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 绘制的填充如何平铺。 |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.drawing.Point---}
```
public PathGradientBrush(Point[] points)
```


使用指定的点初始化 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | 一个由 [Point](../../com.aspose.drawing/point) 结构组成的数组，表示构成路径顶点的点。 |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


使用指定的点和包装模式初始化 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | 一个由 [Point](../../com.aspose.drawing/point) 结构组成的数组，表示构成路径顶点的点。 |
| wrapMode | int | 一个 `WrapMode`（[.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)）用于指定使用此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 绘制的填充如何平铺。 |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


使用指定的路径初始化 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 定义此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 所填充区域的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)。 |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


获取或设置路径渐变中心的颜色。

**Returns:**
[Color](../../com.aspose.drawing/color)
### setCenterColor(Color value) {#setCenterColor-com.aspose.drawing.Color-}
```
public void setCenterColor(Color value)
```


获取或设置路径渐变中心的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


获取或设置与此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 填充的路径中的点对应的颜色数组。

**Returns:**
com.aspose.drawing.Color[]
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.drawing.Color---}
```
public void setSurroundColors(Color[] value)
```


获取或设置与此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 填充的路径中的点对应的颜色数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


获取或设置路径渐变的中心点。

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.drawing.PointF-}
```
public void setCenterPoint(PointF value)
```


获取或设置路径渐变的中心点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


获取此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 的边界矩形。

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
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

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


获取或设置定义此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 本地几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 的副本。

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


获取或设置定义此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 本地几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 的副本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


获取或设置渐变衰减的焦点。

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setFocusScales(PointF value) {#setFocusScales-com.aspose.drawing.PointF-}
```
public void setFocusScales(PointF value)
```


获取或设置渐变衰减的焦点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


获取或设置一个 `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-))，指示此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 的包装模式。

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


获取或设置一个 `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-))，指示此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 的包装模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


创建此 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) 的精确副本。

**Returns:**
java.lang.Object - 此方法创建的 [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush)，作为对象进行强制转换。
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


创建一种渐变画刷，从路径中心向路径边界逐渐改变颜色。颜色之间的过渡基于钟形曲线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 焦点 | 浮点数 | 一个介于 0 到 1 之间的值，指定沿从路径中心到路径边界的任意径向，中心颜色达到最高强度的位置。值为 1（默认）时，最高强度位于路径中心。 |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


创建一种渐变画刷，从路径中心向路径边界逐渐改变颜色。颜色之间的过渡基于钟形曲线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 焦点 | 浮点数 | 一个介于 0 到 1 之间的值，指定沿从路径中心到路径边界的任意径向，中心颜色达到最高强度的位置。值为 1（默认）时，最高强度位于路径中心。 |
| 比例 | 浮点数 | 一个介于 0 到 1 之间的值，指定中心颜色与边界颜色混合时的最大强度。值为 1 时会产生中心颜色的最高可能强度，这是默认值。 |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


创建一种渐变，以中心颜色和线性衰减至一种周围颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 焦点 | 浮点数 | 一个介于 0 到 1 之间的值，指定沿从路径中心到路径边界的任意径向，中心颜色达到最高强度的位置。值为 1（默认）时，最高强度位于路径中心。 |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


创建一个以中心颜色为起点、向每个周围颜色线性衰减的渐变。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 焦点 | 浮点数 | 一个介于 0 到 1 之间的值，指定沿从路径中心到路径边界的任意径向，中心颜色达到最高强度的位置。值为 1（默认）时，最高强度位于路径中心。 |
| 比例 | 浮点数 | 一个介于 0 到 1 之间的值，指定中心颜色与边界颜色混合时的最大强度。值为 1 时会产生中心颜色的最高可能强度，这是默认值。 |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


将 `PathGradientBrush.Transform` 属性重置为单位矩阵。

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


使用刷子的变换矩阵乘以另一个矩阵的乘积来更新刷子的变换矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 将与刷子当前变换矩阵相乘的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


使用刷子的变换矩阵乘以另一个矩阵的乘积来更新刷子的变换矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 将与刷子当前变换矩阵相乘的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)。 |
| order | int | 指定两个矩阵相乘顺序的 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)。 |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


将指定的平移应用于局部几何变换。此方法将在变换前置平移。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | 浮点数 | x 方向的平移值。 |
| dy | 浮点数 | y 方向的平移值。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


按指定顺序将指定的平移应用于局部几何变换。

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
| sx | 浮点数 | X 轴方向的变换缩放因子。 |
| sy | 浮点数 | Y 轴方向的变换缩放因子。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


按指定的顺序，以指定的量缩放局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | 浮点数 | X 轴方向的变换缩放因子。 |
| sy | 浮点数 | Y 轴方向的变换缩放因子。 |
| order | int | 一个 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)，用于指定是追加还是预置缩放矩阵。 |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


按指定的量旋转本地几何变换。此方法将旋转矩阵预先添加到变换中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 浮点数 | 旋转的角度（范围）。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


按指定的顺序，以指定的角度旋转局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 浮点数 | 旋转的角度（范围）。 |
| order | int | 一个 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)，用于指定是追加还是预置旋转矩阵。 |

