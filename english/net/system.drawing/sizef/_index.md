---
title: Struct SizeF
second_title: Aspose.Drawing for .NET API Reference
description: System.Drawing.SizeF struct. Stores an ordered pair of floatingpoint numbers typically the width and height of a rectangle
type: docs
weight: 1050
url: /net/system.drawing/sizef/
---
## SizeF structure

Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

```csharp
public struct SizeF : IEquatable<SizeF>
```

## Constructors

| Name | Description |
| --- | --- |
| [SizeF](sizef/#constructor_1)(PointF) | Initializes a new instance of the `SizeF` struct. |
| [SizeF](sizef/#constructor_2)(SizeF) | Initializes a new instance of the `SizeF` struct. |
| [SizeF](sizef/#constructor)(float, float) | Initializes a new instance of the SizeF structure from the specified dimensions. |

## Properties

| Name | Description |
| --- | --- |
| [Height](../../system.drawing/sizef/height/) { get; set; } | Gets or sets the vertical component of this SizeF structure. |
| [IsEmpty](../../system.drawing/sizef/isempty/) { get; } | Gets a value indicating whether this SizeF structure has zero width and height. |
| [Width](../../system.drawing/sizef/width/) { get; set; } | Gets or sets the horizontal component of this SizeF structure. |

## Methods

| Name | Description |
| --- | --- |
| static [Add](../../system.drawing/sizef/add/)(SizeF, SizeF) | Adds the width and height of one SizeF structure to the width and height of another SizeF structure. |
| static [Subtract](../../system.drawing/sizef/subtract/)(SizeF, SizeF) | Subtracts the width and height of one SizeF structure from the width and height of another SizeF structure. |
| override [Equals](../../system.drawing/sizef/equals/#equals_1)(object) | Tests to see whether the specified object is a SizeF structure with the same dimensions as this SizeF structure. |
| [Equals](../../system.drawing/sizef/equals/#equals)(SizeF) | Tests whether other `SizeF` structure has the same size of this `SizeF` structure. |
| override [GetHashCode](../../system.drawing/sizef/gethashcode/)() | Returns a hash code for this SizeF structure. |
| [ToPointF](../../system.drawing/sizef/topointf/)() | Converts a SizeF structure to a PointF structure. |
| [ToSize](../../system.drawing/sizef/tosize/)() | Converts a SizeF structure to a Size structure. |
| override [ToString](../../system.drawing/sizef/tostring/)() | Converts the attributes of this `SizeF` to a human readable string. |
| [operator +](../../system.drawing/sizef/op_addition/) | Adds the width and height of one SizeF structure to the width and height of another SizeF structure. |
| [operator /](../../system.drawing/sizef/op_division/) | Divides `SizeF` by a Single producing `SizeF`. |
| [operator ==](../../system.drawing/sizef/op_equality/) | Tests whether two SizeF structures are equal. |
| [explicit operator](../../system.drawing/sizef/op_explicit/) | Converts the specified `SizeF` to a [`PointF`](../pointf/). |
| [operator !=](../../system.drawing/sizef/op_inequality/) | Tests whether two SizeF structures are different. |
| [operator *](../../system.drawing/sizef/op_multiply/#op_multiply) | Multiplies `SizeF` by a Single producing `SizeF`. (2 operators) |
| [operator -](../../system.drawing/sizef/op_subtraction/) | Subtracts the width and height of one SizeF structure from the width and height of another SizeF structure. |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Empty](../../system.drawing/sizef/empty/) | Gets a SizeF structure that has a Height and Width value of 0. |

### See Also

* namespace [System.Drawing](../../system.drawing/)
* assembly [Aspose.Drawing](../../)


