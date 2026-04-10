---
title: Pen
second_title: Aspose.Drawing for Java API 参考
description: 定义用于绘制直线和曲线的对象。
type: docs
weight: 34
url: /zh/java/com.aspose.drawing/pen/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class Pen implements System.IDisposable
```

定义用于绘制直线和曲线的对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.drawing.Color-) | 使用指定的 `Color`（[.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)）初始化 [Pen](../../com.aspose.drawing/pen) 类的新实例。 |
| [Pen(Brush brush, float width)](#Pen-com.aspose.drawing.Brush-float-) | 使用指定的 Brush 和 Width 初始化 Pen 类的新实例。 |
| [Pen(Brush brush)](#Pen-com.aspose.drawing.Brush-) | 使用指定的 `Brush`（[.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)）初始化 [Pen](../../com.aspose.drawing/pen) 类的新实例。 |
| [Pen(Color color, float width)](#Pen-com.aspose.drawing.Color-float-) | 使用指定的 Color 和 Width 属性初始化 Pen 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor()](#getColor--) | 获取或设置此 [Pen](../../com.aspose.drawing/pen) 的颜色。 |
| [setColor(Color value)](#setColor-com.aspose.drawing.Color-) | 获取或设置此 [Pen](../../com.aspose.drawing/pen) 的颜色。 |
| [getBrush()](#getBrush--) | 获取或设置决定此 [Pen](../../com.aspose.drawing/pen) 属性的 Brush。 |
| [setBrush(Brush value)](#setBrush-com.aspose.drawing.Brush-) | 获取或设置决定此 [Pen](../../com.aspose.drawing/pen) 属性的 Brush。 |
| [getCompoundArray()](#getCompoundArray--) | 获取或设置指定复合笔的值数组。 |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | 获取或设置指定复合笔的值数组。 |
| [getWidth()](#getWidth--) | 获取或设置此 Pen 的宽度，单位为用于绘图的 Graphics 对象的单位。 |
| [setWidth(float value)](#setWidth-float-) | 获取或设置此 Pen 的宽度，单位为用于绘图的 Graphics 对象的单位。 |
| [getStartCap()](#getStartCap--) | 获取或设置使用此 Pen 绘制的线段起始端的帽子样式。 |
| [setStartCap(int value)](#setStartCap-int-) | 获取或设置使用此 Pen 绘制的线段起始端的帽子样式。 |
| [getEndCap()](#getEndCap--) | 获取或设置使用此 Pen 绘制的线段结束端的帽子样式。 |
| [setEndCap(int value)](#setEndCap-int-) | 获取或设置使用此 Pen 绘制的线段结束端的帽子样式。 |
| [getLineJoin()](#getLineJoin--) | 获取或设置使用此 Pen 绘制的两条连续线段端点的连接样式。 |
| [setLineJoin(int value)](#setLineJoin-int-) | 获取或设置使用此 Pen 绘制的两条连续线段端点的连接样式。 |
| [getMiterLimit()](#getMiterLimit--) | 获取或设置斜接角连接处厚度的限制。 |
| [setMiterLimit(float value)](#setMiterLimit-float-) | 获取或设置斜接角连接处厚度的限制。 |
| [getAlignment()](#getAlignment--) | 获取或设置此 [Pen](../../com.aspose.drawing/pen) 的对齐方式。 |
| [setAlignment(int value)](#setAlignment-int-) | 获取或设置此 [Pen](../../com.aspose.drawing/pen) 的对齐方式。 |
| [getTransform()](#getTransform--) | 获取或设置此 [Pen](../../com.aspose.drawing/pen) 的几何变换的副本。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | 获取或设置此 [Pen](../../com.aspose.drawing/pen) 的几何变换的副本。 |
| [getCustomStartCap()](#getCustomStartCap--) | 获取或设置在使用此 [Pen](../../com.aspose.drawing/pen) 绘制的线段起始端使用的自定义帽子。 |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-) | 获取或设置在使用此 [Pen](../../com.aspose.drawing/pen) 绘制的线段起始端使用的自定义帽子。 |
| [getCustomEndCap()](#getCustomEndCap--) | 获取或设置在使用此 [Pen](../../com.aspose.drawing/pen) 绘制的线段结束端使用的自定义帽子。 |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-) | 获取或设置在使用此 [Pen](../../com.aspose.drawing/pen) 绘制的线段结束端使用的自定义帽子。 |
| [getDashCap()](#getDashCap--) | 获取或设置使用此 [Pen](../../com.aspose.drawing/pen) 绘制的虚线中破折号结束端的帽子样式。 |
| [setDashCap(int value)](#setDashCap-int-) | 获取或设置使用此 [Pen](../../com.aspose.drawing/pen) 绘制的虚线中破折号结束端的帽子样式。 |
| [getDashOffset()](#getDashOffset--) | 获取或设置从线段起点到破折号模式起始点的距离。 |
| [setDashOffset(float value)](#setDashOffset-float-) | 获取或设置从线段起点到破折号模式起始点的距离。 |
| [getDashPattern()](#getDashPattern--) | 获取或设置自定义破折号和空格的数组。 |
| [setDashPattern(float[] value)](#setDashPattern-float---) | 获取或设置自定义破折号和空格的数组。 |
| [getDashStyle()](#getDashStyle--) | 获取或设置使用此 [Pen](../../com.aspose.drawing/pen) 绘制的虚线的样式。 |
| [setDashStyle(int value)](#setDashStyle-int-) | 获取或设置使用此 [Pen](../../com.aspose.drawing/pen) 绘制的虚线的样式。 |
| [getPenType()](#getPenType--) | 获取使用此 Pen 绘制的线条样式。 |
| [dispose()](#dispose--) | 释放此 Pen 使用的所有资源。 |
| [deepClone()](#deepClone--) | 创建此 [Pen](../../com.aspose.drawing/pen) 的精确副本。 |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | 设置决定此 [Pen](../../com.aspose.drawing/pen) 绘制的线条结束时帽子样式的值。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 按指定因子缩放局部几何变换。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 按指定顺序使用指定因子缩放局部几何变换。 |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 按指定尺寸平移局部几何变换。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 按指定顺序使用指定尺寸平移局部几何变换。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | 按指定角度旋转局部几何变换。 |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 按指定顺序使用指定角度旋转局部几何变换。 |
| [resetTransform()](#resetTransform--) | 将此 [Pen](../../com.aspose.drawing/pen) 的几何变换矩阵重置为单位矩阵。 |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | 将此 [Pen](../../com.aspose.drawing/pen) 的变换矩阵乘以指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | 按指定顺序将此 [Pen](../../com.aspose.drawing/pen) 的变换矩阵乘以指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)。 |
### Pen(Color color) {#Pen-com.aspose.drawing.Color-}
```
public Pen(Color color)
```


使用指定的 `Color`（[.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)）初始化 [Pen](../../com.aspose.drawing/pen) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | 一个决定此 [Pen](../../com.aspose.drawing/pen) 填充属性的 `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-))。 |

### Pen(Brush brush, float width) {#Pen-com.aspose.drawing.Brush-float-}
```
public Pen(Brush brush, float width)
```


使用指定的 Brush 和 Width 初始化 Pen 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | 一个决定此 Pen 特性的 Brush。 |
| 宽度 | 浮点数 | 新 Pen 的宽度。 |

### Pen(Brush brush) {#Pen-com.aspose.drawing.Brush-}
```
public Pen(Brush brush)
```


使用指定的 `Brush`（[.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)）初始化 [Pen](../../com.aspose.drawing/pen) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | 一个决定此 [Pen](../../com.aspose.drawing/pen) 填充属性的 `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-))。 |

### Pen(Color color, float width) {#Pen-com.aspose.drawing.Color-float-}
```
public Pen(Color color, float width)
```


使用指定的 Color 和 Width 属性初始化 Pen 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | 一个指示此 Pen 颜色的 Color 结构。 |
| 宽度 | 浮点数 | 一个指示此 Pen 宽度的值。 |

### getColor() {#getColor--}
```
public final Color getColor()
```


获取或设置此 [Pen](../../com.aspose.drawing/pen) 的颜色。

值：一个表示此 [Pen](../../com.aspose.drawing/pen) 颜色的 `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) 结构。

**Returns:**
[Color](../../com.aspose.drawing/color)
### setColor(Color value) {#setColor-com.aspose.drawing.Color-}
```
public final void setColor(Color value)
```


获取或设置此 [Pen](../../com.aspose.drawing/pen) 的颜色。

值：一个表示此 [Pen](../../com.aspose.drawing/pen) 颜色的 `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


获取或设置决定此 [Pen](../../com.aspose.drawing/pen) 属性的 Brush。

**Returns:**
[Brush](../../com.aspose.drawing/brush)
### setBrush(Brush value) {#setBrush-com.aspose.drawing.Brush-}
```
public final void setBrush(Brush value)
```


获取或设置决定此 [Pen](../../com.aspose.drawing/pen) 属性的 Brush。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Brush](../../com.aspose.drawing/brush) |  |

### getCompoundArray() {#getCompoundArray--}
```
public final float[] getCompoundArray()
```


获取或设置指定复合笔的值数组。复合笔绘制由平行线和间隔组成的复合线。

**Returns:**
float[] - 指定复合数组的实数数组。数组中的元素必须递增，且不小于 0，且不大于 1。
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public final void setCompoundArray(float[] value)
```


获取或设置指定复合笔的值数组。复合笔绘制由平行线和间隔组成的复合线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float[] |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


获取或设置此 Pen 的宽度，单位为用于绘图的 Graphics 对象的单位。

**Returns:**
浮点数
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


获取或设置此 Pen 的宽度，单位为用于绘图的 Graphics 对象的单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 浮点数 |  |

### getStartCap() {#getStartCap--}
```
public final int getStartCap()
```


获取或设置使用此 Pen 绘制的线段起始端的帽子样式。

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public final void setStartCap(int value)
```


获取或设置使用此 Pen 绘制的线段起始端的帽子样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public final int getEndCap()
```


获取或设置使用此 Pen 绘制的线段结束端的帽子样式。

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public final void setEndCap(int value)
```


获取或设置使用此 Pen 绘制的线段结束端的帽子样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public final int getLineJoin()
```


获取或设置使用此 Pen 绘制的两条连续线段端点的连接样式。

--------------------

目前，斜接连接实际上表现为 MiterClipped。

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public final void setLineJoin(int value)
```


获取或设置使用此 Pen 绘制的两条连续线段端点的连接样式。

--------------------

目前，斜接连接实际上表现为 MiterClipped。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


获取或设置斜接角连接处厚度的限制。

**Returns:**
浮点数
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


获取或设置斜接角连接处厚度的限制。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 浮点数 |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


获取或设置此 [Pen](../../com.aspose.drawing/pen) 的对齐方式。

**Returns:**
int - 表示此 [Pen](../../com.aspose.drawing/pen) 对齐方式的 [PenAlignment](../../com.aspose.drawing.drawing2d/penalignment)。
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


获取或设置此 [Pen](../../com.aspose.drawing/pen) 的对齐方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public final Matrix getTransform()
```


获取或设置此 [Pen](../../com.aspose.drawing/pen) 的几何变换的副本。

值：一个表示此 [Pen](../../com.aspose.drawing/pen) 几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 的副本。

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void setTransform(Matrix value)
```


获取或设置此 [Pen](../../com.aspose.drawing/pen) 的几何变换的副本。

值：一个表示此 [Pen](../../com.aspose.drawing/pen) 几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 的副本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getCustomStartCap() {#getCustomStartCap--}
```
public final CustomLineCap getCustomStartCap()
```


获取或设置在使用此 [Pen](../../com.aspose.drawing/pen) 绘制的线段起始端使用的自定义帽子。

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the beginning of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomStartCap(CustomLineCap value)
```


获取或设置在使用此 [Pen](../../com.aspose.drawing/pen) 绘制的线段起始端使用的自定义帽子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getCustomEndCap() {#getCustomEndCap--}
```
public final CustomLineCap getCustomEndCap()
```


获取或设置在使用此 [Pen](../../com.aspose.drawing/pen) 绘制的线段结束端使用的自定义帽子。

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the end of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomEndCap(CustomLineCap value)
```


获取或设置在使用此 [Pen](../../com.aspose.drawing/pen) 绘制的线段结束端使用的自定义帽子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getDashCap() {#getDashCap--}
```
public final int getDashCap()
```


获取或设置使用此 [Pen](../../com.aspose.drawing/pen) 绘制的虚线中破折号结束端的帽子样式。

**Returns:**
int - 表示此 [Pen](../../com.aspose.drawing/pen) 绘制的虚线起始和结束处帽子样式的 `DashCap`([.getDashCap](../../null/\#getDashCap)/[.setDashCap(int)](../../null/\#setDashCap-int-)) 值之一。
### setDashCap(int value) {#setDashCap-int-}
```
public final void setDashCap(int value)
```


获取或设置使用此 [Pen](../../com.aspose.drawing/pen) 绘制的虚线中破折号结束端的帽子样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public final float getDashOffset()
```


获取或设置从线段起点到破折号模式起始点的距离。

**Returns:**
float - 从线条起点到破折号模式开始的距离。
### setDashOffset(float value) {#setDashOffset-float-}
```
public final void setDashOffset(float value)
```


获取或设置从线段起点到破折号模式起始点的距离。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 浮点数 |  |

### getDashPattern() {#getDashPattern--}
```
public final float[] getDashPattern()
```


获取或设置自定义破折号和空格的数组。

**Returns:**
float[] - 指定虚线中交替破折号和间隔长度的实数数组。
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public final void setDashPattern(float[] value)
```


获取或设置自定义破折号和空格的数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float[] |  |

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


获取或设置使用此 [Pen](../../com.aspose.drawing/pen) 绘制的虚线的样式。

**Returns:**
int - 一个 `DashStyle`([.getDashStyle](../../null/\#getDashStyle)/[.setDashStyle(int)](../../null/\#setDashStyle-int-))，表示使用此 [Pen](../../com.aspose.drawing/pen) 绘制的虚线的样式。
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


获取或设置使用此 [Pen](../../com.aspose.drawing/pen) 绘制的虚线的样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPenType() {#getPenType--}
```
public final int getPenType()
```


获取使用此 Pen 绘制的线条样式。

Value: 一个 `PenType`([.getPenType](../../null/\#getPenType)) 枚举，指定使用此 [Pen](../../com.aspose.drawing/pen) 绘制的线条样式。

**Returns:**
int
### dispose() {#dispose--}
```
public final void dispose()
```


释放此 Pen 使用的所有资源。

--------------------

此方法实际上不执行任何操作。它仅用于与 System.Drawing API 的兼容性。

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


创建此 [Pen](../../com.aspose.drawing/pen) 的精确副本。

**Returns:**
java.lang.Object - 一个可以强制转换为 [Pen](../../com.aspose.drawing/pen) 的对象。
### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public final void setLineCap(int startCap, int endCap, int dashCap)
```


设置决定此 [Pen](../../com.aspose.drawing/pen) 绘制的线条结束时帽子样式的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startCap | int | 一个 [LineCap](../../com.aspose.drawing.drawing2d/linecap)，表示使用此 [Pen](../../com.aspose.drawing/pen) 绘制的线条起始端的帽子样式。 |
| endCap | int | 一个 [LineCap](../../com.aspose.drawing.drawing2d/linecap)，表示使用此 [Pen](../../com.aspose.drawing/pen) 绘制的线条末端的帽子样式。 |
| dashCap | int | 一个 [LineCap](../../com.aspose.drawing.drawing2d/linecap)，表示使用此 [Pen](../../com.aspose.drawing/pen) 绘制的虚线的起始或结束端的帽子样式。 |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public final void scaleTransform(float sx, float sy)
```


按指定因子缩放局部几何变换。此方法将在变换前预置缩放矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | 浮点数 | 在 x 轴方向上用于缩放变换的因子。 |
| sy | 浮点数 | 在 y 轴方向上用于缩放变换的因子。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public final void scaleTransform(float sx, float sy, int order)
```


按指定顺序使用指定因子缩放局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | 浮点数 | 在 x 轴方向上用于缩放变换的因子。 |
| sy | 浮点数 | 在 y 轴方向上用于缩放变换的因子。 |
| order | int | 一个 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)，用于指定是追加还是预置缩放矩阵。 |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public final void translateTransform(float dx, float dy)
```


按指定尺寸平移局部几何变换。此方法将在变换前预置平移。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | 浮点数 | x 方向的平移值。 |
| dy | 浮点数 | y 方向的平移值。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public final void translateTransform(float dx, float dy, int order)
```


按指定顺序使用指定尺寸平移局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | 浮点数 | x 方向的平移值。 |
| dy | 浮点数 | y 方向的平移值。 |
| 顺序 | int | 应用平移的顺序（预先或追加）。 |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public final void rotateTransform(float angle)
```


按指定角度旋转局部几何变换。此方法将在变换前预置旋转。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 浮点数 | 旋转角度。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public final void rotateTransform(float angle, int order)
```


按指定顺序使用指定角度旋转局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 浮点数 | 旋转角度。 |
| order | int | 一个 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)，用于指定是追加还是预置旋转矩阵。 |

### resetTransform() {#resetTransform--}
```
public final void resetTransform()
```


将此 [Pen](../../com.aspose.drawing/pen) 的几何变换矩阵重置为单位矩阵。

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void multiplyTransform(Matrix matrix)
```


将此 [Pen](../../com.aspose.drawing/pen) 的变换矩阵乘以指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 用于乘以变换矩阵的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 对象。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public final void multiplyTransform(Matrix matrix, int order)
```


按指定顺序将此 [Pen](../../com.aspose.drawing/pen) 的变换矩阵乘以指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 用于乘以变换矩阵的 java.awt.geom.AffineTransform。 |
| 顺序 | int | 执行乘法操作的顺序。 |

