---
title: Bitmap.LockBits
second_title: Aspose.Drawing for .NET API Reference
description: Bitmap method. Locks a Bitmap into system memory
type: docs
weight: 130
url: /net/system.drawing/bitmap/lockbits/
---
## Bitmap.LockBits method

Locks a Bitmap into system memory.

```csharp
public BitmapData LockBits(Rectangle rect, ImageLockMode flags, PixelFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | A Rectangle structure specifying the portion of the Bitmap to lock. |
| flags | ImageLockMode | An ImageLockMode enumeration specifying the access level (read/write) for the Bitmap. |
| format | PixelFormat | A PixelFormat enumeration specifying the data format of this Bitmap. |

### Return Value

A BitmapData containing information about this lock operation.

### See Also

* class [BitmapData](../../../system.drawing.imaging/bitmapdata/)
* struct [Rectangle](../../rectangle/)
* enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* class [Bitmap](../)
* namespace [System.Drawing](../../bitmap/)
* assembly [Aspose.Drawing](../../../)


