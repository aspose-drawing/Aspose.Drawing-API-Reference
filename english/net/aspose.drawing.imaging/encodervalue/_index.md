---
title: Enum EncoderValue
second_title: Aspose.Drawing for .NET API Reference
description: Aspose.Drawing.Imaging.EncoderValue enum. Used to specify the parameter value passed to a JPEG or TIFF image encoder when using the EncoderParameters or EncoderParameters methods
type: docs
weight: 690
url: /net/aspose.drawing.imaging/encodervalue/
---
## EncoderValue enumeration

Used to specify the parameter value passed to a JPEG or TIFF image encoder when using the EncoderParameters) or EncoderParameters) methods.

```csharp
public enum EncoderValue
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| ColorTypeCMYK | `0` | Not used in GDI+ version 1.0. |
| ColorTypeYCCK | `1` | Not used in GDI+ version 1.0. |
| CompressionLZW | `2` | Specifies the LZW compression scheme. Can be passed to the TIFF encoder as a parameter that belongs to the Compression category. |
| CompressionCCITT3 | `3` | Specifies the CCITT3 compression scheme. Can be passed to the TIFF encoder as a parameter that belongs to the compression category. |
| CompressionCCITT4 | `4` | Specifies the CCITT4 compression scheme. Can be passed to the TIFF encoder as a parameter that belongs to the compression category. |
| CompressionRle | `5` | Specifies the RLE compression scheme. Can be passed to the TIFF encoder as a parameter that belongs to the compression category. |
| CompressionNone | `6` | Specifies no compression. Can be passed to the TIFF encoder as a parameter that belongs to the compression category. |
| ScanMethodInterlaced | `7` | Not used in GDI+ version 1.0. |
| ScanMethodNonInterlaced | `8` | Not used in GDI+ version 1.0. |
| VersionGif87 | `9` | Not used in GDI+ version 1.0. |
| VersionGif89 | `10` | Not used in GDI+ version 1.0. |
| RenderProgressive | `11` | Not used in GDI+ version 1.0. |
| RenderNonProgressive | `12` | Not used in GDI+ version 1.0. |
| TransformRotate90 | `13` | Specifies that the image is to be rotated clockwise 90 degrees about its center. Can be passed to the JPEG encoder as a parameter that belongs to the transformation category. |
| TransformRotate180 | `14` | Specifies that the image is to be rotated 180 degrees about its center. Can be passed to the JPEG encoder as a parameter that belongs to the transformation category. |
| TransformRotate270 | `15` | Specifies that the image is to be rotated clockwise 270 degrees about its center. Can be passed to the JPEG encoder as a parameter that belongs to the transformation category. |
| TransformFlipHorizontal | `16` | Specifies that the image is to be flipped horizontally (about the vertical axis). Can be passed to the JPEG encoder as a parameter that belongs to the transformation category. |
| TransformFlipVertical | `17` | Specifies that the image is to be flipped vertically (about the horizontal axis). Can be passed to the JPEG encoder as a parameter that belongs to the transformation category. |
| MultiFrame | `18` | Specifies that the image has more than one frame (page). Can be passed to the TIFF encoder as a parameter that belongs to the save flag category. |
| LastFrame | `19` | Specifies the last frame in a multiple-frame image. Can be passed to the TIFF encoder as a parameter that belongs to the save flag category. |
| Flush | `20` | Specifies that a multiple-frame file or stream should be closed. Can be passed to the TIFF encoder as a parameter that belongs to the save flag category. |
| FrameDimensionTime | `21` | Not used in GDI+ version 1.0. |
| FrameDimensionResolution | `22` | Not used in GDI+ version 1.0. |
| FrameDimensionPage | `23` | Specifies that a frame is to be added to the page dimension of an image. Can be passed to the TIFF encoder as a parameter that belongs to the save flag category. |

### See Also

* namespace [Aspose.Drawing.Imaging](../../aspose.drawing.imaging/)
* assembly [Aspose.Drawing.Common](../../)

