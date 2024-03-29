---
title: Class Icon
second_title: Aspose.Drawing for .NET API Reference
description: Aspose.Drawing.Icon class. Represents a Windows icon which is a small bitmap image that is used to represent an object. Icons can be thought of as transparent bitmaps although their size is determined by the system
type: docs
weight: 540
url: /net/aspose.drawing/icon/
---
## Icon class

Represents a Windows icon, which is a small bitmap image that is used to represent an object. Icons can be thought of as transparent bitmaps, although their size is determined by the system.

```csharp
public sealed class Icon : ICloneable, IDisposable, ISerializable
```

## Constructors

| Name | Description |
| --- | --- |
| [Icon](icon/#constructor_2)(Stream) | Initializes a new instance of the `Icon` class from the specified data stream. |
| [Icon](icon/#constructor_5)(string) | Initializes a new instance of the `Icon` class from the specified file name. |
| [Icon](icon/#constructor)(Icon, Size) | Initializes a new instance of the `Icon` class and attempts to find a version of the icon that matches the requested size. |
| [Icon](icon/#constructor_3)(Stream, Size) | Initializes a new instance of the `Icon` class of the specified size from the specified stream. |
| [Icon](icon/#constructor_6)(string, Size) | Initializes a new instance of the `Icon` class of the specified size from the specified file. |
| [Icon](icon/#constructor_8)(Type, string) | Initializes a new instance of the `Icon` class from a resource in the specified assembly. |
| [Icon](icon/#constructor_1)(Icon, int, int) | Initializes a new instance of the `Icon` class and attempts to find a version of the icon that matches the requested size.. |
| [Icon](icon/#constructor_4)(Stream, int, int) | Initializes a new instance of the `Icon` class from the specified data stream and with the specified width and height. |
| [Icon](icon/#constructor_7)(string, int, int) | Initializes a new instance of the `Icon` class with the specified width and height from the specified file. |

## Properties

| Name | Description |
| --- | --- |
| [Handle](../../aspose.drawing/icon/handle/) { get; } | Gets the handle for this Icon. This is not a copy of the handle; do not free it. |
| [Height](../../aspose.drawing/icon/height/) { get; } | Gets the height of this Icon. |
| [Size](../../aspose.drawing/icon/size/) { get; } | Gets the size of this Icon. |
| [Width](../../aspose.drawing/icon/width/) { get; } | Gets the width of this Icon. |

## Methods

| Name | Description |
| --- | --- |
| static [ExtractAssociatedIcon](../../aspose.drawing/icon/extractassociatedicon/)(string) | Returns an icon representation of an image that is contained in the specified file. |
| static [FromHandle](../../aspose.drawing/icon/fromhandle/)(IntPtr) | Creates a GDI+ Icon from the specified Windows handle to an icon (HICON). |
| [Clone](../../aspose.drawing/icon/clone/)() | Clones the Icon, creating a duplicate image. |
| [Dispose](../../aspose.drawing/icon/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [Save](../../aspose.drawing/icon/save/)(Stream) | Saves this Icon to the specified output Stream. |
| [ToBitmap](../../aspose.drawing/icon/tobitmap/)() | Converts this Icon to a GDI+ Bitmap. |
| override [ToString](../../aspose.drawing/icon/tostring/)() | Gets a human-readable string that describes the Icon. |

### See Also

* namespace [Aspose.Drawing](../../aspose.drawing/)
* assembly [Aspose.Drawing.Common](../../)


