---
title: Class Font
second_title: Aspose.Drawing for .NET API Reference
description: Aspose.Drawing.Font class. Defines a particular format for text including font face size and style attributes. This class cannot be inherited
type: docs
weight: 470
url: /net/aspose.drawing/font/
---
## Font class

Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

```csharp
public sealed class Font : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Initializes a new instance of the `Font` class uses the specified existing Font and FontStyle enumeration.. |
| [Font](font/#constructor_1)(FontFamily, float) | Initializes a new instance of the `Font` class. |
| [Font](font/#constructor_7)(string, float) | Initializes a new instance of the `Font` class using a specified size. |
| [Font](font/#constructor_2)(FontFamily, float, FontStyle) | Initializes a new instance of the `Font` class using a specified size and style.. |
| [Font](font/#constructor_6)(FontFamily, float, GraphicsUnit) | Initializes a new instance of the `Font` class using a specified size and unit. Sets the style to Regular. |
| [Font](font/#constructor_8)(string, float, FontStyle) | Initializes a new instance of the `Font` class using a specified size and style. |
| [Font](font/#constructor_12)(string, float, GraphicsUnit) | Initializes a new instance of the `Font` class using a specified size and unit. The style is set to Regular. |
| [Font](font/#constructor_3)(FontFamily, float, FontStyle, GraphicsUnit) | Initializes a new instance of the `Font` class using a specified size, style, and unit. |
| [Font](font/#constructor_9)(string, float, FontStyle, GraphicsUnit) | Initializes a new instance of the `Font` class using a specified size, style, and unit. |
| [Font](font/#constructor_4)(FontFamily, float, FontStyle, GraphicsUnit, byte) | Initializes a new instance of the `Font` class using a specified size, style, unit, and character set.. |
| [Font](font/#constructor_10)(string, float, FontStyle, GraphicsUnit, byte) | Initializes a new instance of the `Font` class using a specified size, style, unit, and character set. |
| [Font](font/#constructor_5)(FontFamily, float, FontStyle, GraphicsUnit, byte, bool) | Initializes a new instance of the `Font` class using a specified size, style, unit, and character set.. |
| [Font](font/#constructor_11)(string, float, FontStyle, GraphicsUnit, byte, bool) | Initializes a new instance of the `Font` class using the specified size, style, unit, and character set. |

## Properties

| Name | Description |
| --- | --- |
| [Bold](../../aspose.drawing/font/bold/) { get; } | Gets a value indicating whether this Font is bold. |
| [FontFamily](../../aspose.drawing/font/fontfamily/) { get; } | Gets the FontFamily associated with this Font. |
| [GdiCharSet](../../aspose.drawing/font/gdicharset/) { get; } | Gets a byte value that specifies the GDI character set that this Font uses. |
| [GdiVerticalFont](../../aspose.drawing/font/gdiverticalfont/) { get; } | Gets a value indicating whether this Font is derived from a GDI vertical font.. |
| [Height](../../aspose.drawing/font/height/) { get; } | Gets the line spacing of this font. |
| [IsSystemFont](../../aspose.drawing/font/issystemfont/) { get; } | Gets a value indicating whether the font is a member of SystemFonts. |
| [Italic](../../aspose.drawing/font/italic/) { get; } | Gets a value indicating whether this Font is italic. |
| [Name](../../aspose.drawing/font/name/) { get; } | Gets the face name of this Font. |
| [OriginalFontName](../../aspose.drawing/font/originalfontname/) { get; } | Gets the name of the font originally specified. |
| [Size](../../aspose.drawing/font/size/) { get; } | Gets the em-size of this Font measured in the units specified by the Unit property. |
| [SizeInPoints](../../aspose.drawing/font/sizeinpoints/) { get; } | Gets the em-size, in points, of this Font. |
| [Strikeout](../../aspose.drawing/font/strikeout/) { get; } | Gets a value indicating whether this Font specifies a horizontal line through the font. |
| [Style](../../aspose.drawing/font/style/) { get; } | Gets style information for this Font. |
| [SystemFontName](../../aspose.drawing/font/systemfontname/) { get; } | Gets the name of the system font if the IsSystemFont property returns true. |
| [Underline](../../aspose.drawing/font/underline/) { get; } | Gets a value indicating whether this Font is underlined. |
| [Unit](../../aspose.drawing/font/unit/) { get; } | Gets the unit of measure for this Font. |

## Methods

| Name | Description |
| --- | --- |
| [Clone](../../aspose.drawing/font/clone/)() | Creates an exact copy of this Font. |
| [Dispose](../../aspose.drawing/font/dispose/)() | Releases all resources used by this Font. |
| override [Equals](../../aspose.drawing/font/equals/)(object) | Indicates whether the specified object is a Font and has the same FontFamily, GdiVerticalFont, GdiCharSet, Style, Size, and Unit property values as this Font. |
| override [GetHashCode](../../aspose.drawing/font/gethashcode/)() | Gets the hash code for this Font. |
| [GetHeight](../../aspose.drawing/font/getheight/#getheight)() | Returns the line spacing, in pixels, of this font. |
| [GetHeight](../../aspose.drawing/font/getheight/#getheight_2)(float) | Returns the height, in pixels, of this Font when drawn to a device with the specified vertical resolution. |
| [GetHeight](../../aspose.drawing/font/getheight/#getheight_1)(Graphics) | Returns the line spacing, in the current unit of a specified Graphics, of this font. |
| override [ToString](../../aspose.drawing/font/tostring/)() | Returns a human-readable string representation of this Font. |

### See Also

* namespace [Aspose.Drawing](../../aspose.drawing/)
* assembly [Aspose.Drawing.Common](../../)


