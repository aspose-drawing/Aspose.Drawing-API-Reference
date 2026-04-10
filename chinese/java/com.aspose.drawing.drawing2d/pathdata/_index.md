---
title: PathData
second_title: Aspose.Drawing for Java API 参考
description: 包含构成对象的图形数据。
type: docs
weight: 35
url: /zh/java/com.aspose.drawing.drawing2d/pathdata/
---
**Inheritance:**
java.lang.Object
```
public final class PathData
```

包含构成 [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) 对象的图形数据。此类不可继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PathData()](#PathData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPoints()](#getPoints--) | 获取一个 [PointF](../../com.aspose.drawing/pointf) 结构数组，表示路径构建所经过的点。 |
| [setPoints(PointF[] value)](#setPoints-com.aspose.drawing.PointF---) | 设置一个 [PointF](../../com.aspose.drawing/pointf) 结构数组，表示路径构建所经过的点。 |
| [getTypes()](#getTypes--) | 获取路径中相应点的类型。 |
| [setTypes(byte[] value)](#setTypes-byte---) | 设置路径中相应点的类型。 |
### PathData() {#PathData--}
```
public PathData()
```


### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


获取一个 [PointF](../../com.aspose.drawing/pointf) 结构数组，表示路径构建所经过的点。

值：一个 [PointF](../../com.aspose.drawing/pointf) 对象数组，表示路径构建所经过的点。

**Returns:**
com.aspose.drawing.PointF[] - 一个 [PointF](../../com.aspose.drawing/pointf) 结构数组，表示路径构建所经过的点。
### setPoints(PointF[] value) {#setPoints-com.aspose.drawing.PointF---}
```
public void setPoints(PointF[] value)
```


设置一个 [PointF](../../com.aspose.drawing/pointf) 结构数组，表示路径构建所经过的点。

值：一个 [PointF](../../com.aspose.drawing/pointf) 对象数组，表示路径构建所经过的点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.drawing/pointf) | 一个 [PointF](../../com.aspose.drawing/pointf) 结构数组，表示路径构建所经过的点。 |

### getTypes() {#getTypes--}
```
public byte[] getTypes()
```


获取路径中相应点的类型。

值：一个字节数组，指定路径中相应点的类型。

**Returns:**
byte[] - 路径中相应点的类型。
### setTypes(byte[] value) {#setTypes-byte---}
```
public void setTypes(byte[] value)
```


设置路径中相应点的类型。

值：一个字节数组，指定路径中相应点的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] | 路径中相应点的类型。 |

