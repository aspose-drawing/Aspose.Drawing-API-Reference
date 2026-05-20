---
title: Region
second_title: Aspose.Drawing for Java API 参考
description: 描述由矩形和路径组成的图形形状的内部。
type: docs
weight: 40
url: /zh/java/com.aspose.drawing/region/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Region implements System.IDisposable
```

描述由矩形和路径组成的图形形状的内部。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Region()](#Region--) | 初始化 [Region](../../com.aspose.drawing/region) 类的新实例。 |
| [Region(RectangleF rect)](#Region-com.aspose.drawing.RectangleF-) | 从指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构初始化 [Region](../../com.aspose.drawing/region) 类的新实例。 |
| [Region(Rectangle rect)](#Region-com.aspose.drawing.Rectangle-) | 从指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构初始化 [Region](../../com.aspose.drawing/region) 类的新实例。 |
| [Region(GraphicsPath path)](#Region-com.aspose.drawing.drawing2d.GraphicsPath-) | 使用指定的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 初始化 [Region](../../com.aspose.drawing/region) 类的新实例。 |
| [Region(RegionData rgnData)](#Region-com.aspose.drawing.drawing2d.RegionData-) | 从指定的数据初始化 [Region](../../com.aspose.drawing/region) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [dispose()](#dispose--) | 释放此 [Region](../../com.aspose.drawing/region) 使用的所有资源。 |
| [equals(Region region, Graphics g)](#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-) | 测试指定的 [Region](../../com.aspose.drawing/region) 是否在指定的绘图表面上与此 [Region](../../com.aspose.drawing/region) 完全相同。 |
| [deepClone()](#deepClone--) | 创建此 [Region](../../com.aspose.drawing/region) 的精确副本。 |
| [makeInfinite()](#makeInfinite--) | 将此 [Region](../../com.aspose.drawing/region) 对象初始化为无限内部。 |
| [makeEmpty()](#makeEmpty--) | 将此 [Region](../../com.aspose.drawing/region) 初始化为空内部。 |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | 将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的交集。 |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | 将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构的交集。 |
| [intersect(GraphicsPath path)](#intersect-com.aspose.drawing.drawing2d.GraphicsPath-) | 将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 的交集。 |
| [intersect(Region region)](#intersect-com.aspose.drawing.Region-) | 将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [Region](../../com.aspose.drawing/region) 的交集。 |
| [union(RectangleF rect)](#union-com.aspose.drawing.RectangleF-) | 将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的并集。 |
| [union(Rectangle rect)](#union-com.aspose.drawing.Rectangle-) | 将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构的并集。 |
| [union(GraphicsPath path)](#union-com.aspose.drawing.drawing2d.GraphicsPath-) | 将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 的并集。 |
| [union(Region region)](#union-com.aspose.drawing.Region-) | 将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [Region](../../com.aspose.drawing/region) 的并集。 |
| [getRegionData()](#getRegionData--) | 返回一个表示描述此 [Region](../../com.aspose.drawing/region) 信息的 [RegionData](../../com.aspose.drawing.drawing2d/regiondata)。 |
| [xor(RectangleF rect)](#xor-com.aspose.drawing.RectangleF-) | 将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的并集减去交集。 |
| [xor(Rectangle rect)](#xor-com.aspose.drawing.Rectangle-) | 将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构的并集减去交集。 |
| [xor(GraphicsPath path)](#xor-com.aspose.drawing.drawing2d.GraphicsPath-) | 将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 的并集减去交集。 |
| [xor(Region region)](#xor-com.aspose.drawing.Region-) | 将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [Region](../../com.aspose.drawing/region) 的并集减去交集。 |
| [exclude(RectangleF rect)](#exclude-com.aspose.drawing.RectangleF-) | 将此 [Region](../../com.aspose.drawing/region) 更新为仅包含其内部中未与指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构相交的部分。 |
| [exclude(Rectangle rect)](#exclude-com.aspose.drawing.Rectangle-) | 将此 [Region](../../com.aspose.drawing/region) 更新为仅包含其内部中未与指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构相交的部分。 |
| [exclude(GraphicsPath path)](#exclude-com.aspose.drawing.drawing2d.GraphicsPath-) | 将此 [Region](../../com.aspose.drawing/region) 更新为仅包含其内部中未与指定的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 相交的部分。 |
| [exclude(Region region)](#exclude-com.aspose.drawing.Region-) | 将此 [Region](../../com.aspose.drawing/region) 更新为仅包含其内部中未与指定的 [Region](../../com.aspose.drawing/region) 相交的部分。 |
| [complement(RectangleF rect)](#complement-com.aspose.drawing.RectangleF-) | 将此 [Region](../../com.aspose.drawing/region) 更新为包含指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构中未与此 [Region](../../com.aspose.drawing/region) 相交的部分。 |
| [complement(Rectangle rect)](#complement-com.aspose.drawing.Rectangle-) | 将此 [Region](../../com.aspose.drawing/region) 更新为包含指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构中未与此 [Region](../../com.aspose.drawing/region) 相交的部分。 |
| [complement(GraphicsPath path)](#complement-com.aspose.drawing.drawing2d.GraphicsPath-) | 将此 [Region](../../com.aspose.drawing/region) 更新为包含指定的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 中未与此 [Region](../../com.aspose.drawing/region) 相交的部分。 |
| [complement(Region region)](#complement-com.aspose.drawing.Region-) | 更新此 [Region](../../com.aspose.drawing/region) 以包含指定的 [Region](../../com.aspose.drawing/region) 中未与此 [Region](../../com.aspose.drawing/region) 相交的部分。 |
| [translate(float dx, float dy)](#translate-float-float-) | 按指定的量偏移此 [Region](../../com.aspose.drawing/region) 的坐标。 |
| [translate(int dx, int dy)](#translate-int-int-) | 按指定的量偏移此 [Region](../../com.aspose.drawing/region) 的坐标。 |
| [transform(Matrix matrix)](#transform-com.aspose.drawing.drawing2d.Matrix-) | 使用指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 对此 [Region](../../com.aspose.drawing/region) 进行变换。 |
| [getBounds(Graphics g)](#getBounds-com.aspose.drawing.Graphics-) | 获取一个 [RectangleF](../../com.aspose.drawing/rectanglef) 结构，表示在 [Graphics](../../com.aspose.drawing/graphics) 对象的绘图表面上界定此 [Region](../../com.aspose.drawing/region) 的矩形。 |
| [getRegionScans(Matrix matrix)](#getRegionScans-com.aspose.drawing.drawing2d.Matrix-) | 返回一个 [RectangleF](../../com.aspose.drawing/rectanglef) 结构数组，表示在应用指定矩阵变换后近似此 [Region](../../com.aspose.drawing/region) 的形状。 |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.drawing.Graphics-) | 测试此 [Region](../../com.aspose.drawing/region) 在指定的绘图表面上是否具有空的内部。 |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.drawing.Graphics-) | 测试此 [Region](../../com.aspose.drawing/region) 在指定的绘图表面上是否具有无限的内部。 |
| [isVisible(float x, float y)](#isVisible-float-float-) | 测试指定的点是否包含在此 [Region](../../com.aspose.drawing/region) 中。 |
| [isVisible(PointF point)](#isVisible-com.aspose.drawing.PointF-) | 测试指定的 [PointF](../../com.aspose.drawing/pointf) 结构是否包含在此 [Region](../../com.aspose.drawing/region) 中。 |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.drawing.Graphics-) | 在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 绘制时，测试指定的点是否包含在此 [Region](../../com.aspose.drawing/region) 中。 |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-) | 在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 绘制时，测试指定的 [PointF](../../com.aspose.drawing/pointf) 结构是否包含在此 [Region](../../com.aspose.drawing/region) 中。 |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | 测试指定矩形的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。 |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.drawing.RectangleF-) | 测试指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。 |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.drawing.Graphics-) | 在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 绘制时，测试指定矩形的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。 |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-) | 在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 绘制时，测试指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。 |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.drawing.Graphics-) | 在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 对象绘制时，测试指定的点是否包含在此 [Region](../../com.aspose.drawing/region) 对象中。 |
| [isVisible(Point point)](#isVisible-com.aspose.drawing.Point-) | 测试指定的 [Point](../../com.aspose.drawing/point) 结构是否包含在此 [Region](../../com.aspose.drawing/region) 中。 |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-) | 在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 绘制时，测试指定的 [Point](../../com.aspose.drawing/point) 结构是否包含在此 [Region](../../com.aspose.drawing/region) 中。 |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | 测试指定矩形的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。 |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.drawing.Rectangle-) | 测试指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。 |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.drawing.Graphics-) | 在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 绘制时，测试指定矩形的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。 |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-) | 在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 绘制时，测试指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。 |
### Region() {#Region--}
```
public Region()
```


初始化 [Region](../../com.aspose.drawing/region) 类的新实例。

### Region(RectangleF rect) {#Region-com.aspose.drawing.RectangleF-}
```
public Region(RectangleF rect)
```


从指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构初始化 [Region](../../com.aspose.drawing/region) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 一个定义新 [Region](../../com.aspose.drawing/region) 内部的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |

### Region(Rectangle rect) {#Region-com.aspose.drawing.Rectangle-}
```
public Region(Rectangle rect)
```


从指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构初始化 [Region](../../com.aspose.drawing/region) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 一个定义新 [Region](../../com.aspose.drawing/region) 内部的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |

### Region(GraphicsPath path) {#Region-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public Region(GraphicsPath path)
```


使用指定的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 初始化 [Region](../../com.aspose.drawing/region) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 一个定义新 [Region](../../com.aspose.drawing/region) 的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)。 |

### Region(RegionData rgnData) {#Region-com.aspose.drawing.drawing2d.RegionData-}
```
public Region(RegionData rgnData)
```


从指定的数据初始化 [Region](../../com.aspose.drawing/region) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rgnData | [RegionData](../../com.aspose.drawing.drawing2d/regiondata) | 一个定义新 [Region](../../com.aspose.drawing/region) 内部的 [RegionData](../../com.aspose.drawing.drawing2d/regiondata)。 |

### dispose() {#dispose--}
```
public void dispose()
```


释放此 [Region](../../com.aspose.drawing/region) 使用的所有资源。

### equals(Region region, Graphics g) {#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-}
```
public boolean equals(Region region, Graphics g)
```


测试指定的 [Region](../../com.aspose.drawing/region) 是否在指定的绘图表面上与此 [Region](../../com.aspose.drawing/region) 完全相同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | 要测试的 [Region](../../com.aspose.drawing/region)。 |
| g | [Graphics](../../com.aspose.drawing/graphics) | 一个表示绘图表面的 [Graphics](../../com.aspose.drawing/graphics)。 |

**Returns:**
布尔值 - 如果在应用与 `g` 参数关联的变换后，区域的内部与此区域的内部相同，则为 true；否则为 false。
### deepClone() {#deepClone--}
```
public Region deepClone()
```


创建此 [Region](../../com.aspose.drawing/region) 的精确副本。

**Returns:**
[Region](../../com.aspose.drawing/region) - The [Region](../../com.aspose.drawing/region) that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


将此 [Region](../../com.aspose.drawing/region) 对象初始化为无限内部。

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


将此 [Region](../../com.aspose.drawing/region) 初始化为空内部。

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public void intersect(RectangleF rect)
```


将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 用于与此 [Region](../../com.aspose.drawing/region) 相交的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |

### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public void intersect(Rectangle rect)
```


将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构的交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 用于与此 [Region](../../com.aspose.drawing/region) 相交的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |

### intersect(GraphicsPath path) {#intersect-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 的交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 用于与此 [Region](../../com.aspose.drawing/region) 相交的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 结构。 |

### intersect(Region region) {#intersect-com.aspose.drawing.Region-}
```
public void intersect(Region region)
```


将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [Region](../../com.aspose.drawing/region) 的交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | 用于与此 [Region](../../com.aspose.drawing/region) 相交的 [Region](../../com.aspose.drawing/region) 结构。 |

### union(RectangleF rect) {#union-com.aspose.drawing.RectangleF-}
```
public void union(RectangleF rect)
```


将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的并集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 用于与此 [Region](../../com.aspose.drawing/region) 合并的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |

--------------------

并集会使无限区域保持为无限。 |

### union(Rectangle rect) {#union-com.aspose.drawing.Rectangle-}
```
public void union(Rectangle rect)
```


将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构的并集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | rect | [Rectangle](../../com.aspose.drawing/rectangle) | 用于与此 [Region](../../com.aspose.drawing/region) 合并的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |

--------------------

并集会使无限区域保持为无限。 |

### union(GraphicsPath path) {#union-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void union(GraphicsPath path)
```


将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 的并集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 用于与此 [Region](../../com.aspose.drawing/region) 合并的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 结构。 |

--------------------

并集会使无限区域保持为无限。 |

### union(Region region) {#union-com.aspose.drawing.Region-}
```
public void union(Region region)
```


将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [Region](../../com.aspose.drawing/region) 的并集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | region | [Region](../../com.aspose.drawing/region) | 用于与此 [Region](../../com.aspose.drawing/region) 合并的 [Region](../../com.aspose.drawing/region) 结构。 |

--------------------

并集会使无限区域保持为无限。 |

### getRegionData() {#getRegionData--}
```
public RegionData getRegionData()
```


返回一个表示描述此 [Region](../../com.aspose.drawing/region) 信息的 [RegionData](../../com.aspose.drawing.drawing2d/regiondata)。

**Returns:**
[RegionData](../../com.aspose.drawing.drawing2d/regiondata) - A [RegionData](../../com.aspose.drawing.drawing2d/regiondata) that represents the information that describes this [Region](../../com.aspose.drawing/region).
### xor(RectangleF rect) {#xor-com.aspose.drawing.RectangleF-}
```
public void xor(RectangleF rect)
```


将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的并集减去交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 用于与此 [Region](../../com.aspose.drawing/region) 进行 `M:Region.Xor(Drawing2D.GraphicsPath)` 的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |

### xor(Rectangle rect) {#xor-com.aspose.drawing.Rectangle-}
```
public void xor(Rectangle rect)
```


将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构的并集减去交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 用于与此 [Region](../../com.aspose.drawing/region) 进行 `M:Region.Xor(Rectangle)` 的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |

### xor(GraphicsPath path) {#xor-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 的并集减去交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 用于与此 [Region](../../com.aspose.drawing/region) 进行 `M:Region.Xor(GraphicsPath)` 的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 结构。 |

### xor(Region region) {#xor-com.aspose.drawing.Region-}
```
public void xor(Region region)
```


将此 [Region](../../com.aspose.drawing/region) 更新为其自身与指定的 [Region](../../com.aspose.drawing/region) 的并集减去交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | 用于与此 [Region](../../com.aspose.drawing/region) 进行 `M:Region.Xor(Region)` 的 [Region](../../com.aspose.drawing/region) 结构。 |

### exclude(RectangleF rect) {#exclude-com.aspose.drawing.RectangleF-}
```
public void exclude(RectangleF rect)
```


将此 [Region](../../com.aspose.drawing/region) 更新为仅包含其内部中未与指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 用于从此 [Region](../../com.aspose.drawing/region) 排除的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |

### exclude(Rectangle rect) {#exclude-com.aspose.drawing.Rectangle-}
```
public void exclude(Rectangle rect)
```


将此 [Region](../../com.aspose.drawing/region) 更新为仅包含其内部中未与指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 用于从此 [Region](../../com.aspose.drawing/region) 排除的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |

### exclude(GraphicsPath path) {#exclude-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


将此 [Region](../../com.aspose.drawing/region) 更新为仅包含其内部中未与指定的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 用于从此 [Region](../../com.aspose.drawing/region) 排除的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 结构。 |

### exclude(Region region) {#exclude-com.aspose.drawing.Region-}
```
public void exclude(Region region)
```


将此 [Region](../../com.aspose.drawing/region) 更新为仅包含其内部中未与指定的 [Region](../../com.aspose.drawing/region) 相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | 用于从此 [Region](../../com.aspose.drawing/region) 排除的 [Region](../../com.aspose.drawing/region) 结构。 |

### complement(RectangleF rect) {#complement-com.aspose.drawing.RectangleF-}
```
public void complement(RectangleF rect)
```


将此 [Region](../../com.aspose.drawing/region) 更新为包含指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构中未与此 [Region](../../com.aspose.drawing/region) 相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 用于补充此 [Region](../../com.aspose.drawing/region) 的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |

### complement(Rectangle rect) {#complement-com.aspose.drawing.Rectangle-}
```
public void complement(Rectangle rect)
```


将此 [Region](../../com.aspose.drawing/region) 更新为包含指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构中未与此 [Region](../../com.aspose.drawing/region) 相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 用于补充此 [Region](../../com.aspose.drawing/region) 的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |

### complement(GraphicsPath path) {#complement-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


将此 [Region](../../com.aspose.drawing/region) 更新为包含指定的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 中未与此 [Region](../../com.aspose.drawing/region) 相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 用于补充此 [Region](../../com.aspose.drawing/region) 的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 结构。 |

### complement(Region region) {#complement-com.aspose.drawing.Region-}
```
public void complement(Region region)
```


更新此 [Region](../../com.aspose.drawing/region) 以包含指定的 [Region](../../com.aspose.drawing/region) 中未与此 [Region](../../com.aspose.drawing/region) 相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | 用于补充此 [Region](../../com.aspose.drawing/region) 对象的 [Region](../../com.aspose.drawing/region) 对象。 |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


按指定的量偏移此 [Region](../../com.aspose.drawing/region) 的坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | float | 此 [Region](../../com.aspose.drawing/region) 水平偏移的量。 |
| dy | float | 此 [Region](../../com.aspose.drawing/region) 垂直偏移的量。 |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


按指定的量偏移此 [Region](../../com.aspose.drawing/region) 的坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | int | 水平偏移此[Region](../../com.aspose.drawing/region)的量. |
| dy | int | 此 [Region](../../com.aspose.drawing/region) 垂直偏移的量。 |

### transform(Matrix matrix) {#transform-com.aspose.drawing.drawing2d.Matrix-}
```
public void transform(Matrix matrix)
```


使用指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 对此 [Region](../../com.aspose.drawing/region) 进行变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 用于转换此[Region](../../com.aspose.drawing/region)的[Matrix](../../com.aspose.drawing.drawing2d/matrix). |

### getBounds(Graphics g) {#getBounds-com.aspose.drawing.Graphics-}
```
public RectangleF getBounds(Graphics g)
```


获取一个 [RectangleF](../../com.aspose.drawing/rectanglef) 结构，表示在 [Graphics](../../com.aspose.drawing/graphics) 对象的绘图表面上界定此 [Region](../../com.aspose.drawing/region) 的矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | 此[Region](../../com.aspose.drawing/region)被绘制的[Graphics](../../com.aspose.drawing/graphics). |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents the bounding rectangle for this [Region](../../com.aspose.drawing/region) on the specified drawing surface.
### getRegionScans(Matrix matrix) {#getRegionScans-com.aspose.drawing.drawing2d.Matrix-}
```
public RectangleF[] getRegionScans(Matrix matrix)
```


返回一个 [RectangleF](../../com.aspose.drawing/rectanglef) 结构数组，表示在应用指定矩阵变换后近似此 [Region](../../com.aspose.drawing/region) 的形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 表示要应用于此[Region](../../com.aspose.drawing/region)的几何变换的[Matrix](../../com.aspose.drawing.drawing2d/matrix). |

**Returns:**
com.aspose.drawing.RectangleF[] - 在应用指定矩阵变换后近似此[Region](../../com.aspose.drawing/region)的[RectangleF](../../com.aspose.drawing/rectanglef)结构数组.
### isEmpty(Graphics g) {#isEmpty-com.aspose.drawing.Graphics-}
```
public boolean isEmpty(Graphics g)
```


测试此 [Region](../../com.aspose.drawing/region) 在指定的绘图表面上是否具有空的内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | 一个表示绘图表面的 [Graphics](../../com.aspose.drawing/graphics)。 |

**Returns:**
boolean - 当对 `g` 关联的变换应用时，如果此[Region](../../com.aspose.drawing/region)的内部为空，则为 true；否则为 false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.drawing.Graphics-}
```
public boolean isInfinite(Graphics g)
```


测试此 [Region](../../com.aspose.drawing/region) 在指定的绘图表面上是否具有无限的内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | 一个表示绘图表面的 [Graphics](../../com.aspose.drawing/graphics)。 |

**Returns:**
boolean - 当对 `g` 关联的变换应用时，如果此[Region](../../com.aspose.drawing/region)的内部是无限的，则为 true；否则为 false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


测试指定的点是否包含在此 [Region](../../com.aspose.drawing/region) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | 浮点数 | 要测试的点的 x 坐标。 |
| y | 浮点数 | 要测试的点的 y 坐标。 |

**Returns:**
boolean - 当指定的点位于此[Region](../../com.aspose.drawing/region)内部时为 true；否则为 false.
### isVisible(PointF point) {#isVisible-com.aspose.drawing.PointF-}
```
public boolean isVisible(PointF point)
```


测试指定的 [PointF](../../com.aspose.drawing/pointf) 结构是否包含在此 [Region](../../com.aspose.drawing/region) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | 要测试的[PointF](../../com.aspose.drawing/pointf)结构. |

**Returns:**
boolean - 当 `point` 位于此[Region](../../com.aspose.drawing/region)内部时为 true；否则为 false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 绘制时，测试指定的点是否包含在此 [Region](../../com.aspose.drawing/region) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | 浮点数 | 要测试的点的 x 坐标。 |
| y | 浮点数 | 要测试的点的 y 坐标。 |
| g | [Graphics](../../com.aspose.drawing/graphics) | 表示图形上下文的[Graphics](../../com.aspose.drawing/graphics). |

**Returns:**
boolean - 当指定的点位于此[Region](../../com.aspose.drawing/region)内部时为 true；否则为 false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 绘制时，测试指定的 [PointF](../../com.aspose.drawing/pointf) 结构是否包含在此 [Region](../../com.aspose.drawing/region) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | 要测试的[PointF](../../com.aspose.drawing/pointf)结构. |
| g | [Graphics](../../com.aspose.drawing/graphics) | 表示图形上下文的[Graphics](../../com.aspose.drawing/graphics). |

**Returns:**
boolean - 当 `point` 位于此[Region](../../com.aspose.drawing/region)内部时为 true；否则为 false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


测试指定矩形的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | 浮点数 | 要测试的矩形左上角的 x 坐标. |
| y | 浮点数 | 要测试的矩形左上角的 y 坐标. |
| 宽度 | 浮点数 | 要测试的矩形的宽度. |
| 高度 | 浮点数 | 要测试的矩形的高度. |

**Returns:**
boolean - 当指定矩形的任何部分位于此[Region](../../com.aspose.drawing/region)对象内部时为 true；否则为 false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.drawing.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


测试指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 要测试的[RectangleF](../../com.aspose.drawing/rectanglef)结构. |

**Returns:**
boolean - 当 `rect` 的任何部分位于此[Region](../../com.aspose.drawing/region)内部时为 true；否则为 false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 绘制时，测试指定矩形的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | 浮点数 | 要测试的矩形左上角的 x 坐标. |
| y | 浮点数 | 要测试的矩形左上角的 y 坐标. |
| 宽度 | 浮点数 | 要测试的矩形的宽度. |
| 高度 | 浮点数 | 要测试的矩形的高度. |
| g | [Graphics](../../com.aspose.drawing/graphics) | 表示图形上下文的[Graphics](../../com.aspose.drawing/graphics). |

**Returns:**
boolean - 当指定矩形的任何部分位于此[Region](../../com.aspose.drawing/region)内部时为 true；否则为 false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 绘制时，测试指定的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 要测试的[RectangleF](../../com.aspose.drawing/rectanglef)结构. |
| g | [Graphics](../../com.aspose.drawing/graphics) | 表示图形上下文的[Graphics](../../com.aspose.drawing/graphics). |

**Returns:**
boolean - 当 `rect` 位于此[Region](../../com.aspose.drawing/region)内部时为 true；否则为 false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 对象绘制时，测试指定的点是否包含在此 [Region](../../com.aspose.drawing/region) 对象中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |
| g | [Graphics](../../com.aspose.drawing/graphics) | 表示图形上下文的[Graphics](../../com.aspose.drawing/graphics). |

**Returns:**
boolean - 当指定的点位于此[Region](../../com.aspose.drawing/region)内部时为 true；否则为 false.
### isVisible(Point point) {#isVisible-com.aspose.drawing.Point-}
```
public boolean isVisible(Point point)
```


测试指定的 [Point](../../com.aspose.drawing/point) 结构是否包含在此 [Region](../../com.aspose.drawing/region) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | 要测试的[Point](../../com.aspose.drawing/point)结构. |

**Returns:**
boolean - 当 `point` 位于此[Region](../../com.aspose.drawing/region)内部时为 true；否则为 false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 绘制时，测试指定的 [Point](../../com.aspose.drawing/point) 结构是否包含在此 [Region](../../com.aspose.drawing/region) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | 要测试的[Point](../../com.aspose.drawing/point)结构. |
| g | [Graphics](../../com.aspose.drawing/graphics) | 表示图形上下文的[Graphics](../../com.aspose.drawing/graphics). |

**Returns:**
boolean - 当 `point` 位于此[Region](../../com.aspose.drawing/region)内部时为 true；否则为 false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


测试指定矩形的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 要测试的矩形左上角的 x 坐标. |
| y | int | 要测试的矩形左上角的 y 坐标. |
| 宽度 | int | 要测试的矩形的宽度. |
| 高度 | int | 要测试的矩形的高度. |

**Returns:**
boolean - 当指定矩形的任何部分位于此[Region](../../com.aspose.drawing/region)内部时为 true；否则为 false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.drawing.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


测试指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 要测试的[Rectangle](../../com.aspose.drawing/rectangle)结构. |

**Returns:**
boolean - 当 `rect` 的任何部分位于此[Region](../../com.aspose.drawing/region)内部时，此方法返回 true；否则返回 false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 绘制时，测试指定矩形的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 要测试的矩形左上角的 x 坐标. |
| y | int | 要测试的矩形左上角的 y 坐标. |
| 宽度 | int | 要测试的矩形的宽度. |
| 高度 | int | 要测试的矩形的高度. |
| g | [Graphics](../../com.aspose.drawing/graphics) | 表示图形上下文的[Graphics](../../com.aspose.drawing/graphics). |

**Returns:**
boolean - 当指定矩形的任何部分位于此[Region](../../com.aspose.drawing/region)内部时为 true；否则为 false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


在使用指定的 [Graphics](../../com.aspose.drawing/graphics) 绘制时，测试指定的 [Rectangle](../../com.aspose.drawing/rectangle) 结构的任何部分是否包含在此 [Region](../../com.aspose.drawing/region) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 要测试的[Rectangle](../../com.aspose.drawing/rectangle)结构. |
| g | [Graphics](../../com.aspose.drawing/graphics) | 表示图形上下文的[Graphics](../../com.aspose.drawing/graphics). |

**Returns:**
boolean - 当 `rect` 的任何部分位于此[Region](../../com.aspose.drawing/region)内部时为 true；否则为 false.
