---
title: GraphicsPathIterator
second_title: Aspose.Drawing for Java API 参考
description: 提供遍历子路径的能力，并测试每个子路径中包含的形状类型。
type: docs
weight: 24
url: /zh/java/com.aspose.drawing.drawing2d/graphicspathiterator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class GraphicsPathIterator implements System.IDisposable
```

提供遍历 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 中子路径并测试每个子路径中包含的形状类型的能力。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GraphicsPathIterator(GraphicsPath path)](#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-) | 初始化 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 获取路径中的点数。 |
| [getSubpathCount()](#getSubpathCount--) | 获取路径中的子路径数量。 |
| [dispose()](#dispose--) | 执行与释放、释放或重置非托管资源相关的应用程序定义任务。 |
| [copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)](#copyData-com.aspose.drawing.PointF-----byte-----int-int-) | 将关联的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 的 GraphicsPath.PathPoints 属性和 GraphicsPath.PathTypes 属性数组复制到两个指定的数组中。 |
| [enumerate(PointF[][] points, byte[][] types)](#enumerate-com.aspose.drawing.PointF-----byte-----) | 将关联的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 的 GraphicsPath.PathPoints 属性和 GraphicsPath.PathTypes 属性数组复制到两个指定的数组中。 |
| [hasCurve()](#hasCurve--) | 指示与此 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 关联的路径是否包含曲线。 |
| [nextMarker(int[] startIndex, int[] endIndex)](#nextMarker-int---int---) | 将 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 前进到路径中的下一个标记，并通过 [out] 参数返回起始和结束索引。 |
| [nextMarker(GraphicsPath path)](#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-) | 此 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 对象关联有一个 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 对象。 |
| [nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)](#nextPathType-byte---int---int---) | 获取下一组具有相同类型的数据点的起始索引和结束索引。 |
| [nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)](#nextSubpath-int---int---boolean---) | 将 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 移动到路径中的下一个子路径。 |
| [nextSubpath(GraphicsPath path, boolean[] isClosed)](#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---) | 从此 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 关联的路径中获取下一个图形（子路径）。 |
| [rewind()](#rewind--) | 将此 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 重新定位到其关联路径的起始位置。 |
### GraphicsPathIterator(GraphicsPath path) {#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public GraphicsPathIterator(GraphicsPath path)
```


初始化 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 用于初始化此帮助类的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 对象。 |

### getCount() {#getCount--}
```
public int getCount()
```


获取路径中的点数。

**Returns:**
int - 路径中的点数。
### getSubpathCount() {#getSubpathCount--}
```
public int getSubpathCount()
```


获取路径中的子路径数量。

**Returns:**
int - 路径中的子路径数量。
### dispose() {#dispose--}
```
public void dispose()
```


执行与释放、释放或重置非托管资源相关的应用程序定义任务。

### copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex) {#copyData-com.aspose.drawing.PointF-----byte-----int-int-}
```
public int copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)
```


将关联的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 的 GraphicsPath.PathPoints 属性和 GraphicsPath.PathTypes 属性数组复制到两个指定的数组中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | 返回时，包含表示路径中点的 System.Drawing.PointF 结构数组。 |
| 类型 | byte[][] | 返回时，包含表示路径中点类型的字节数组。 |
| startIndex | int | 指定数组的起始索引。 |
| endIndex | int | 指定数组的结束索引。 |

**Returns:**
int - 已复制的点数。
### enumerate(PointF[][] points, byte[][] types) {#enumerate-com.aspose.drawing.PointF-----byte-----}
```
public int enumerate(PointF[][] points, byte[][] types)
```


将关联的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 的 GraphicsPath.PathPoints 属性和 GraphicsPath.PathTypes 属性数组复制到两个指定的数组中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | 返回时，包含表示路径中点的 System.Drawing.PointF 结构数组。 |
| 类型 | byte[][] | 返回时，包含表示路径中点类型的字节数组。 |

**Returns:**
int - 已复制的点数。
### hasCurve() {#hasCurve--}
```
public boolean hasCurve()
```


指示与此 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 关联的路径是否包含曲线。

**Returns:**
boolean - 如果当前子路径包含曲线，则此方法返回 true；否则返回 false。
### nextMarker(int[] startIndex, int[] endIndex) {#nextMarker-int---int---}
```
public int nextMarker(int[] startIndex, int[] endIndex)
```


将 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 前进到路径中的下一个标记，并通过 [out] 参数返回起始和结束索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int[] | [out] 传入此参数的整数引用接收开始子路径的点的索引。 |
| endIndex | int[] | [out] 传入此参数的整数引用接收由 startIndex 指向的子路径结束点的索引。 |

**Returns:**
int - 此标记与下一个标记之间的点数。
### nextMarker(GraphicsPath path) {#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public int nextMarker(GraphicsPath path)
```


此 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 对象关联了一个 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 对象。此方法将关联的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 前进到路径中的下一个标记，并将当前标记与下一个标记（或路径结束）之间的所有点复制到通过参数传入的第二个 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 对象中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 要将点复制到的 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 对象。 |

**Returns:**
int - 此标记与下一个标记之间的点数。
### nextPathType(byte[] pathType, int[] startIndex, int[] endIndex) {#nextPathType-byte---int---int---}
```
public int nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)
```


获取下一组具有相同类型的数据点的起始索引和结束索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pathType | byte[] | [out] 接收组中所有点共享的点类型。可从 [PathPointType](../../com.aspose.drawing.drawing2d/pathpointtype) 枚举中获取可能的类型。 |
| startIndex | int[] | [out] 接收点组的起始索引。 |
| endIndex | int[] | [out] 接收点组的结束索引。 |

**Returns:**
int - 此方法返回组中的数据点数量。如果路径中没有更多组，则此方法返回 0。
### nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed) {#nextSubpath-int---int---boolean---}
```
public int nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)
```


将 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 移动到路径中的下一个子路径。下一个子路径的起始索引和结束索引包含在 [out] 参数中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int[] | [out] 接收下一个子路径的起始索引。 |
| endIndex | int[] | [out] 接收下一个子路径的结束索引。 |
| isClosed | boolean[] | [out] 指示子路径是否闭合。 |

**Returns:**
int - 检索到的图形（子路径）中的数据点数量。如果没有更多图形可检索，则返回零。
### nextSubpath(GraphicsPath path, boolean[] isClosed) {#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---}
```
public int nextSubpath(GraphicsPath path, boolean[] isClosed)
```


从此 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 关联的路径中获取下一个图形（子路径）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 一个 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)，其数据点将被设置为匹配此迭代器检索到的图形（子路径）的数据点。 |
| isClosed | boolean[] | [out] 指示当前子路径是否闭合。如果图形闭合则为 true，否则为 false。 |

**Returns:**
int - 检索到的图形（子路径）中的数据点数量。如果没有更多图形可检索，则返回零。
### rewind() {#rewind--}
```
public void rewind()
```


将此 [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) 重新定位到其关联路径的起始位置。

