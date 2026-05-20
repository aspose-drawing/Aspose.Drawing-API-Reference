---
title: CustomLineCap
second_title: Aspose.Drawing for Java API 参考
description: 封装自定义用户定义的线帽。
type: docs
weight: 17
url: /zh/java/com.aspose.drawing.drawing2d/customlinecap/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class CustomLineCap implements System.IDisposable
```

封装自定义用户定义的线帽。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-) | 使用指定的轮廓和填充初始化 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 类的新实例。 |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-) | 从指定的现有 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 枚举，并使用指定的轮廓和填充，初始化 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 类的新实例。 |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-) | 从指定的现有 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 枚举，并使用指定的轮廓、填充和内嵌，初始化 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStrokeJoin()](#getStrokeJoin--) | 获取或设置决定组成此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 对象的线段如何连接的 [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) 枚举。 |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | 获取或设置决定组成此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 对象的线段如何连接的 [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) 枚举。 |
| [getBaseCap()](#getBaseCap--) | 获取或设置此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 所基于的 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 枚举。 |
| [setBaseCap(int value)](#setBaseCap-int-) | 获取或设置此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 所基于的 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 枚举。 |
| [getBaseInset()](#getBaseInset--) | 获取或设置帽子与线之间的距离。 |
| [setBaseInset(float value)](#setBaseInset-float-) | 获取或设置帽子与线之间的距离。 |
| [getWidthScale()](#getWidthScale--) | 获取或设置相对于 [Pen](../../com.aspose.drawing/pen) 对象宽度，对此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 类对象进行缩放的量。 |
| [setWidthScale(float value)](#setWidthScale-float-) | 获取或设置相对于 [Pen](../../com.aspose.drawing/pen) 对象宽度，对此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 类对象进行缩放的量。 |
| [dispose()](#dispose--) | 释放此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 对象使用的所有资源。 |
| [deepClone()](#deepClone--) | 创建此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 的精确副本。 |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | 设置用于开始和结束构成此自定义帽的线的端帽。 |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | 获取用于开始和结束构成此自定义帽的线的端帽。 |
| [getFillPath()](#getFillPath--) |  |
| [getStrokePath()](#getStrokePath--) | 获取定义此自定义帽轮廓的对象。 |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


使用指定的轮廓和填充初始化 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 一个定义此自定义帽填充的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 对象。 |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 一个定义此自定义帽轮廓的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 对象。 |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


从指定的现有 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 枚举，并使用指定的轮廓和填充，初始化 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 一个定义此自定义帽填充的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 对象。 |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 一个定义此自定义帽轮廓的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 对象。 |
| baseCap | int | 用于创建自定义帽的线帽。 |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


从指定的现有 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 枚举，并使用指定的轮廓、填充和内嵌，初始化 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 一个定义此自定义帽填充的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 对象。 |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 一个定义此自定义帽轮廓的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 对象。 |
| baseCap | int | 用于创建自定义帽的线帽。 |
| baseInset | 浮点数 | 帽子与线之间的距离。 |

### getStrokeJoin() {#getStrokeJoin--}
```
public final int getStrokeJoin()
```


获取或设置决定组成此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 对象的线段如何连接的 [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) 枚举。

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public final void setStrokeJoin(int value)
```


获取或设置决定组成此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 对象的线段如何连接的 [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) 枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public final int getBaseCap()
```


获取或设置此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 所基于的 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 枚举。

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public final void setBaseCap(int value)
```


获取或设置此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 所基于的 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public final float getBaseInset()
```


获取或设置帽子与线之间的距离。

**Returns:**
浮点数
### setBaseInset(float value) {#setBaseInset-float-}
```
public final void setBaseInset(float value)
```


获取或设置帽子与线之间的距离。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 浮点数 |  |

### getWidthScale() {#getWidthScale--}
```
public final float getWidthScale()
```


获取或设置相对于 [Pen](../../com.aspose.drawing/pen) 对象宽度，对此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 类对象进行缩放的量。

**Returns:**
浮点数
### setWidthScale(float value) {#setWidthScale-float-}
```
public final void setWidthScale(float value)
```


获取或设置相对于 [Pen](../../com.aspose.drawing/pen) 对象宽度，对此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 类对象进行缩放的量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 浮点数 |  |

### dispose() {#dispose--}
```
public final void dispose()
```


释放此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 对象使用的所有资源。

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


创建此 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) 的精确副本。

**Returns:**
java.lang.Object - 此方法创建的 [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)，作为对象进行强制转换。
### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public final void setStrokeCaps(int startCap, int endCap)
```


设置用于开始和结束构成此自定义帽的线的端帽。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startCap | int | 在此帽子内用于线段起始的 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 枚举。 |
| endCap | int | 在此帽子内用于线段结束的 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 枚举。 |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public final void getStrokeCaps(int[] startCap, int[] endCap)
```


获取用于开始和结束构成此自定义帽的线的端帽。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startCap | int[] | 在此帽子内用于线段起始的 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 枚举。 |
| endCap | int[] | 在此帽子内用于线段结束的 [LineCap](../../com.aspose.drawing.drawing2d/linecap) 枚举。 |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```




**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


获取定义此自定义帽轮廓的对象。

**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) - The object that defines the outline of the custom cap.
