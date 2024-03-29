---
title: RectangleF
second_title: Aspose.Drawing for .NET API 参考
description: 存储一组四个浮点数表示矩形的位置和大小 对于更高级的区域函数请使用 Region 对象
type: docs
weight: 1050
url: /zh/net/system.drawing/rectanglef/
---
## RectangleF structure

存储一组四个浮点数，表示矩形的位置和大小。 对于更高级的区域函数，请使用 Region 对象。

```csharp
public struct RectangleF : IEquatable<RectangleF>
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [RectangleF](rectanglef#constructor_1)(PointF, SizeF) | 使用指定的位置和大小初始化 RectangleF 结构的新实例。 |
| [RectangleF](rectanglef#constructor)(float, float, float, float) | 使用指定的位置和大小初始化 RectangleF 结构的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Bottom](../../system.drawing/rectanglef/bottom) { get; } | 获取 y 坐标，即此 RectangleF 结构的 Y 和高度之和。 |
| [Height](../../system.drawing/rectanglef/height) { get; set; } | 获取或设置此 RectangleF 结构的高度。 |
| [IsEmpty](../../system.drawing/rectanglef/isempty) { get; } | 获取一个值，该值指示是否Width或者Heightproperty 这个RectangleF值为零。 |
| [Left](../../system.drawing/rectanglef/left) { get; } | 获取此 RectangleF 结构左边缘的 x 坐标。 |
| [Location](../../system.drawing/rectanglef/location) { get; set; } | 获取或设置this的左上角坐标RectangleF结构. |
| [Right](../../system.drawing/rectanglef/right) { get; } | 获取 x 坐标，即此 RectangleF 结构的 X 和宽度之和。 |
| [Size](../../system.drawing/rectanglef/size) { get; set; } | 获取或设置 this 的大小RectangleF. |
| [Top](../../system.drawing/rectanglef/top) { get; } | 获取此 RectangleF 结构的上边缘的 y 坐标。 |
| [Width](../../system.drawing/rectanglef/width) { get; set; } | 获取或设置此 RectangleF 结构的宽度。 |
| [X](../../system.drawing/rectanglef/x) { get; set; } | 获取或设置此 RectangleF 结构左上角的 x 坐标。 |
| [Y](../../system.drawing/rectanglef/y) { get; set; } | 获取或设置此 RectangleF 结构左上角的 x 坐标。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromLTRB](../../system.drawing/rectanglef/fromltrb)(float, float, float, float) | 在指定位置创建一个具有左上角和右下角的 RectangleF 结构。 |
| static [Inflate](../../system.drawing/rectanglef/inflate)(RectangleF, float, float) | 创建并返回指定的膨胀副本RectangleFstructure. 副本按指定数量膨胀。原始矩形保持不变。 |
| static [Intersect](../../system.drawing/rectanglef/intersect)(RectangleF, RectangleF) | 返回一个RectangleF表示两个矩形交集的结构体。 如果没有交集，则为空RectangleF被退回。 |
| static [Union](../../system.drawing/rectanglef/union)(RectangleF, RectangleF) | 创建最小的第三个矩形，该矩形可以包含形成联合的两个矩形。 |
| [Contains](../../system.drawing/rectanglef/contains#contains_1)(PointF) | 确定指定点是否包含在此范围内RectangleF结构. |
| [Contains](../../system.drawing/rectanglef/contains#contains_2)(RectangleF) | 确定矩形区域是否由*rect*完全包含在这个RectangleF结构. |
| [Contains](../../system.drawing/rectanglef/contains#contains)(float, float) | 确定指定点是否包含在此范围内RectangleF结构. |
| override [Equals](../../system.drawing/rectanglef/equals#equals_1)(object) | 判断是否指定Object 等于这个实例。 |
| [Equals](../../system.drawing/rectanglef/equals#equals)(RectangleF) | 测试是否有其他[`RectangleF`](../rectanglef)结构具有相同的位置和大小[`RectangleF`](../rectanglef)结构. |
| override [GetHashCode](../../system.drawing/rectanglef/gethashcode)() | 返回此实例的哈希码。 |
| [Inflate](../../system.drawing/rectanglef/inflate#inflate_1)(SizeF) | 膨胀这个RectangleF按指定数量。 |
| [Inflate](../../system.drawing/rectanglef/inflate#inflate)(float, float) | 膨胀这个RectangleF指定数量的结构。 |
| [Intersect](../../system.drawing/rectanglef/intersect)(RectangleF) | 替换这个RectangleF具有自身与指定 交集的结构RectangleF结构. |
| [IntersectsWith](../../system.drawing/rectanglef/intersectswith)(RectangleF) | 确定此矩形是否与*rect*. |
| [Offset](../../system.drawing/rectanglef/offset#offset_1)(PointF) | 按指定量调整此矩形的位置。 |
| [Offset](../../system.drawing/rectanglef/offset#offset)(float, float) | 按指定量调整此矩形的位置。 |
| override [ToString](../../system.drawing/rectanglef/tostring)() | 转换 this 的属性[`Rectangle`](../rectangle)到人类可读的字符串。 |
| [operator ==](../../system.drawing/rectanglef/op_equality) | 测试是否两个RectangleF结构具有相同的位置和大小。 |
| [implicit operator](../../system.drawing/rectanglef/op_implicit) | 将指定的 Rectangle 结构转换为 RectangleF 结构。 |
| [operator !=](../../system.drawing/rectanglef/op_inequality) | 测试是否两个RectangleF结构的位置或大小不同。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static readonly [Empty](../../system.drawing/rectanglef/empty) | 代表一个实例RectangleF其成员未初始化的类。 |

### 也可以看看

* 命名空间 [System.Drawing](../../system.drawing)
* 部件 [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
