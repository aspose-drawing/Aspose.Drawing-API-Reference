---
title: GraphicsPathIterator.NextPathType
second_title: Aspose.Drawing for .NET API Reference
description: GraphicsPathIterator method. Gets the starting index and the ending index of the next group of data points that all have the same type
type: docs
weight: 90
url: /net/system.drawing.drawing2d/graphicspathiterator/nextpathtype/
---
## GraphicsPathIterator.NextPathType method

Gets the starting index and the ending index of the next group of data points that all have the same type.

```csharp
public int NextPathType(out byte pathType, out int startIndex, out int endIndex)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pathType | Byte& | [out] Receives the point type shared by all points in the group. Possible types can be retrieved from the PathPointType enumeration. |
| startIndex | Int32& | [out] Receives the starting index of the group of points. |
| endIndex | Int32& | [out] Receives the ending index of the group of points. |

### Return Value

This method returns the number of data points in the group. If there are no more groups in the path, this method returns 0.

### See Also

* class [GraphicsPathIterator](../)
* namespace [System.Drawing.Drawing2D](../../graphicspathiterator/)
* assembly [Aspose.Drawing](../../../)


