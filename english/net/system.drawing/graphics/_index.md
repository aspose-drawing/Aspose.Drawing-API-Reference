---
title: Class Graphics
second_title: Aspose.Drawing for .NET API Reference
description: System.Drawing.Graphics class. Encapsulates drawing surface
type: docs
weight: 520
url: /net/system.drawing/graphics/
---
## Graphics class

Encapsulates drawing surface.

```csharp
public class Graphics : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Clip](../../system.drawing/graphics/clip/) { get; set; } | Gets or sets a Region that limits the drawing region of this Graphics. |
| [ClipBounds](../../system.drawing/graphics/clipbounds/) { get; } | Gets a [`RectangleF`](../rectanglef/) structure that bounds the clipping region of this `Graphics`. |
| [CompositingMode](../../system.drawing/graphics/compositingmode/) { get; set; } | Gets or sets a value that specifies how composited images are drawn to this Graphics. |
| [CompositingQuality](../../system.drawing/graphics/compositingquality/) { get; set; } | Gets or sets the rendering quality of composited images drawn to this Graphics. |
| [DpiX](../../system.drawing/graphics/dpix/) { get; } | Gets the horizontal resolution of this Graphics. |
| [DpiY](../../system.drawing/graphics/dpiy/) { get; } | Gets the vertical resolution of this Graphics. |
| [InterpolationMode](../../system.drawing/graphics/interpolationmode/) { get; set; } | Gets or sets the interpolation mode associated with this Graphics. |
| [IsClipEmpty](../../system.drawing/graphics/isclipempty/) { get; } | Gets a value indicating whether the clipping region of this Graphics is empty. |
| [IsVisibleClipEmpty](../../system.drawing/graphics/isvisibleclipempty/) { get; } | Gets a value indicating whether the visible clipping region of this Graphics is empty. |
| [PageScale](../../system.drawing/graphics/pagescale/) { get; set; } | Gets or sets the scaling between world units and page units for this Graphics. |
| [PageUnit](../../system.drawing/graphics/pageunit/) { get; set; } | Gets or sets the unit of measure used for page coordinates in this Graphics. |
| [PixelOffsetMode](../../system.drawing/graphics/pixeloffsetmode/) { get; set; } | Gets or sets a value specifying how pixels are offset during rendering of this Graphics. |
| [RenderingOrigin](../../system.drawing/graphics/renderingorigin/) { get; set; } | Gets or sets the rendering origin of this Graphics for dithering and for hatch brushes. |
| [SmoothingMode](../../system.drawing/graphics/smoothingmode/) { get; set; } | Gets or sets the rendering quality for this Graphics. |
| [TextContrast](../../system.drawing/graphics/textcontrast/) { get; set; } | Gets or sets the gamma correction value for rendering text. |
| [TextRenderingHint](../../system.drawing/graphics/textrenderinghint/) { get; set; } | Gets or sets the rendering mode for text associated with this Graphics. |
| [Transform](../../system.drawing/graphics/transform/) { get; set; } | Gets or sets a copy of the geometric world transformation for this Graphics. |
| [VisibleClipBounds](../../system.drawing/graphics/visibleclipbounds/) { get; } | Gets the bounding rectangle of the visible clipping region of this Graphics. |

## Methods

| Name | Description |
| --- | --- |
| static [FromHwnd](../../system.drawing/graphics/fromhwnd/)(IntPtr) | Creates a new Graphics from the specified handle to a window. |
| static [FromImage](../../system.drawing/graphics/fromimage/)(Image) | Creates a new Graphics from the specified Image. |
| [AddMetafileComment](../../system.drawing/graphics/addmetafilecomment/)(byte[]) | Adds a comment to the current Metafile. |
| [BeginContainer](../../system.drawing/graphics/begincontainer/#begincontainer)() | Saves a graphics container with the current state of this Graphics and opens and uses a new graphics container. |
| [BeginContainer](../../system.drawing/graphics/begincontainer/#begincontainer_1)(Rectangle, Rectangle, GraphicsUnit) | Saves a graphics container with the current state of this Graphics and opens and uses a new graphics container with the specified scale transformation. |
| [BeginContainer](../../system.drawing/graphics/begincontainer/#begincontainer_2)(RectangleF, RectangleF, GraphicsUnit) | Saves a graphics container with the current state of this Graphics and opens and uses a new graphics container with the specified scale transformation. |
| [Clear](../../system.drawing/graphics/clear/)(Color) | Clears the entire drawing surface and fills it with the specified background color. |
| [CopyFromScreen](../../system.drawing/graphics/copyfromscreen/#copyfromscreen_1)(Point, Point, Size) | Performs a bit-block transfer of color data, corresponding to a rectangle of pixels, from the screen to the drawing surface of the Graphics. |
| [CopyFromScreen](../../system.drawing/graphics/copyfromscreen/#copyfromscreen_2)(Point, Point, Size, CopyPixelOperation) | Performs a bit-block transfer of color data, corresponding to a rectangle of pixels, from the screen to the drawing surface of the Graphics. |
| [CopyFromScreen](../../system.drawing/graphics/copyfromscreen/#copyfromscreen)(int, int, int, int, Size, CopyPixelOperation) | Performs a bit-block transfer of the color data, corresponding to a rectangle of pixels, from the screen to the drawing surface of the Graphics. |
| [Dispose](../../system.drawing/graphics/dispose/)() | Releases all resources used by this Graphics. |
| [DrawArc](../../system.drawing/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | Draws an arc representing a portion of an ellipse specified by a RectangleF structure. |
| [DrawArc](../../system.drawing/graphics/drawarc/#drawarc)(Pen, float, float, float, float, float, float) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [DrawBezier](../../system.drawing/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Draws a Bézier spline defined by four PointF structures. |
| [DrawBezier](../../system.drawing/graphics/drawbezier/#drawbezier)(Pen, float, float, float, float, float, float, float, float) | Draws a Bézier spline defined by four ordered pairs of coordinates that represent points. |
| [DrawBeziers](../../system.drawing/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | Draws a series of Bézier splines from an array of Point structures. |
| [DrawBeziers](../../system.drawing/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | Draws a series of Bézier splines from an array of PointF structures. |
| [DrawClosedCurve](../../system.drawing/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | Draws a closed cardinal spline defined by an array of PointF structures. |
| [DrawClosedCurve](../../system.drawing/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | Draws a closed cardinal spline defined by an array of Point structures. |
| [DrawClosedCurve](../../system.drawing/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float, FillMode) | Draws a closed cardinal spline defined by an array of PointF structures using a specified tension. |
| [DrawClosedCurve](../../system.drawing/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float, FillMode) | Draws a closed cardinal spline defined by an array of Point structures using a specified tension. |
| [DrawCurve](../../system.drawing/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | Draws a cardinal spline through a specified array of PointF structures. |
| [DrawCurve](../../system.drawing/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | Draws a cardinal spline through a specified array of Point structures. |
| [DrawCurve](../../system.drawing/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | Draws a cardinal spline through a specified array of PointF structures using a specified tension. |
| [DrawCurve](../../system.drawing/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | Draws a cardinal spline through a specified array of Point structures using a specified tension. |
| [DrawCurve](../../system.drawing/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | Draws a cardinal spline through a specified array of PointF structures using a specified tension. The drawing begins offset from the beginning of the array. |
| [DrawCurve](../../system.drawing/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | Draws a cardinal spline through a specified array of PointF structures using a specified tension. The drawing begins offset from the beginning of the array. |
| [DrawCurve](../../system.drawing/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | Draws a cardinal spline through a specified array of Point structures using a specified tension. The drawing begins offset from the beginning of the array. |
| [DrawEllipse](../../system.drawing/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | Draws an ellipse defined by a bounding RectangleF. |
| [DrawEllipse](../../system.drawing/graphics/drawellipse/#drawellipse)(Pen, float, float, float, float) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [DrawIcon](../../system.drawing/graphics/drawicon/#drawicon_1)(Icon, Rectangle) | Draws the image represented by the specified Icon within the area specified by a Rectangle structure. |
| [DrawIcon](../../system.drawing/graphics/drawicon/#drawicon)(Icon, int, int) | Draws the image represented by the specified Icon at the specified coordinates. |
| [DrawIconUnstretched](../../system.drawing/graphics/drawiconunstretched/)(Icon, Rectangle) | Draws the image represented by the specified Icon without scaling the image. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_6)(Image, Point) | Draws the specified Image, using its original physical size, at the specified location. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_7)(Image, PointF) | Draws the specified Image, using its original physical size, at the specified location. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_8)(Image, PointF[]) | Draws the specified Image at the specified location and with the specified shape and size. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_11)(Image, Point[]) | Draws the specified Е:Image at the specified location and with the specified shape and size. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_14)(Image, Rectangle) | Draws the specified Image at the specified location and with the specified size. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_20)(Image, RectangleF) | Draws the specified Image at the specified location and with the specified size. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_3)(Image, float, float) | Draws the specified Image, using its original physical size, at the specified location. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage)(Image, int, int) | Draws the specified image, using its original physical size, at the location specified by a coordinate pair. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_9)(Image, PointF[], RectangleF, GraphicsUnit) | Draws the specified portion of the specified Image at the specified location and with the specified size. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_12)(Image, Point[], Rectangle, GraphicsUnit) | Draws the specified portion of the specified Image at the specified location and with the specified size. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_19)(Image, Rectangle, Rectangle, GraphicsUnit) | Draws the specified portion of the specified Image at the specified location and with the specified size. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_21)(Image, RectangleF, RectangleF, GraphicsUnit) | Draws the specified portion of the specified Image at the specified location and with the specified size. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_4)(Image, float, float, float, float) | Draws the specified Image, using its original physical size, at the specified location and with the specified size. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_5)(Image, float, float, RectangleF, GraphicsUnit) | Draws a portion of an image at a specified location. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_1)(Image, int, int, int, int) | Draws the specified Image at the specified location and with the specified size. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_2)(Image, int, int, Rectangle, GraphicsUnit) | Draws a portion of an image at a specified location. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_10)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Draws the specified portion of the specified Image at the specified location and with the specified size. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_13)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Draws the specified portion of the specified Image at the specified location and with the specified size. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_17)(Image, Rectangle, float, float, float, float, GraphicsUnit) | Draws the specified portion of the specified Image at the specified location and with the specified size. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_15)(Image, Rectangle, int, int, int, int, GraphicsUnit) | Draws the specified portion of the specified Image at the specified location and with the specified size. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_18)(Image, Rectangle, float, float, float, float, GraphicsUnit, ImageAttributes) | Draws the specified portion of the specified Image at the specified location and with the specified size. |
| [DrawImage](../../system.drawing/graphics/drawimage/#drawimage_16)(Image, Rectangle, int, int, int, int, GraphicsUnit, ImageAttributes) | Draws the specified portion of the specified Image at the specified location and with the specified size. |
| [DrawImageUnscaled](../../system.drawing/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, Point) | Draws a specified image using its original physical size at a specified location. |
| [DrawImageUnscaled](../../system.drawing/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, Rectangle) | Draws a specified image using its original physical size at a specified location. |
| [DrawImageUnscaled](../../system.drawing/graphics/drawimageunscaled/#drawimageunscaled)(Image, int, int) | Draws the specified image using its original physical size at the location specified by a coordinate pair. |
| [DrawImageUnscaled](../../system.drawing/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, int, int, int, int) | Draws the specified image using its original physical size at the location specified by a coordinate pair. |
| [DrawImageUnscaledAndClipped](../../system.drawing/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | Draws the specified image without scaling and clips it, if necessary, to fit in the specified rectangle. |
| [DrawLine](../../system.drawing/graphics/drawline/#drawline_2)(Pen, Point, Point) | Draws a line connecting two Point structures. |
| [DrawLine](../../system.drawing/graphics/drawline/#drawline_3)(Pen, PointF, PointF) | Draws a line connecting two PointF structures. |
| [DrawLine](../../system.drawing/graphics/drawline/#drawline_1)(Pen, float, float, float, float) | Draws a line connecting the two points specified by the coordinate pairs. |
| [DrawLine](../../system.drawing/graphics/drawline/#drawline)(Pen, int, int, int, int) | Draws a line connecting the two points specified by the coordinate pairs. |
| [DrawLines](../../system.drawing/graphics/drawlines/#drawlines)(Pen, PointF[]) | Draws a series of line segments that connect an array of PointF structures. |
| [DrawLines](../../system.drawing/graphics/drawlines/#drawlines_1)(Pen, Point[]) | Draws a series of line segments that connect an array of Point structures. |
| [DrawPath](../../system.drawing/graphics/drawpath/)(Pen, GraphicsPath) | Draws a GraphicsPath. |
| [DrawPie](../../system.drawing/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | Draws a pie shape defined by an ellipse specified by a RectangleF structure and two radial lines. |
| [DrawPie](../../system.drawing/graphics/drawpie/#drawpie)(Pen, float, float, float, float, float, float) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [DrawPolygon](../../system.drawing/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | Draws a polygon defined by an array of PointF structures. |
| [DrawPolygon](../../system.drawing/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | Draws a polygon defined by an array of Point structures. |
| [DrawRectangle](../../system.drawing/graphics/drawrectangle/#drawrectangle_2)(Pen, Rectangle) | Draws a rectangle specified by a Rectangle structure. |
| [DrawRectangle](../../system.drawing/graphics/drawrectangle/#drawrectangle_1)(Pen, float, float, float, float) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [DrawRectangle](../../system.drawing/graphics/drawrectangle/#drawrectangle)(Pen, int, int, int, int) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [DrawRectangles](../../system.drawing/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | Draws a series of rectangles specified by RectangleF structures. |
| [DrawRectangles](../../system.drawing/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | Draws a series of rectangles specified by Rectangle structures. |
| [DrawString](../../system.drawing/graphics/drawstring/#drawstring_2)(string, Font, Brush, PointF) | Draws the specified text string at the specified location with the specified Brush and Font objects. |
| [DrawString](../../system.drawing/graphics/drawstring/#drawstring_4)(string, Font, Brush, RectangleF) | Draws the specified text string in the specified rectangle with the specified Brush and Font objects using the formatting attributes of the specified StringFormat. |
| [DrawString](../../system.drawing/graphics/drawstring/#drawstring)(string, Font, Brush, float, float) | Draws the specified text string at the specified location with the specified Brush and Font objects. |
| [DrawString](../../system.drawing/graphics/drawstring/#drawstring_3)(string, Font, Brush, PointF, StringFormat) | Draws the specified text string at the specified location with the specified Brush and Font objects using the formatting attributes of the specified StringFormat. |
| [DrawString](../../system.drawing/graphics/drawstring/#drawstring_5)(string, Font, Brush, RectangleF, StringFormat) | Draws the specified text string in the specified rectangle with the specified Brush and Font objects using the formatting attributes of the specified StringFormat. |
| [DrawString](../../system.drawing/graphics/drawstring/#drawstring_1)(string, Font, Brush, float, float, StringFormat) | Draws the specified text string at the specified location with the specified Brush and Font objects using the formatting attributes of the specified StringFormat. |
| [EndContainer](../../system.drawing/graphics/endcontainer/)(GraphicsContainer) | Closes the current graphics container and restores the state of this Graphics to the state saved by a call to the BeginContainer method. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile)(Metafile, Point, EnumerateMetafileProc) | Sends the records in the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_6)(Metafile, PointF, EnumerateMetafileProc) | Sends the records in the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_12)(Metafile, PointF[], EnumerateMetafileProc) | Sends the records in the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_18)(Metafile, Point[], EnumerateMetafileProc) | Sends the records in the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_24)(Metafile, Rectangle, EnumerateMetafileProc) | Sends the records of the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_30)(Metafile, RectangleF, EnumerateMetafileProc) | Sends the records of the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_1)(Metafile, Point, EnumerateMetafileProc, IntPtr) | Sends the records in the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_7)(Metafile, PointF, EnumerateMetafileProc, IntPtr) | Sends the records in the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_13)(Metafile, PointF[], EnumerateMetafileProc, IntPtr) | Sends the records in the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_19)(Metafile, Point[], EnumerateMetafileProc, IntPtr) | Sends the records in the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_25)(Metafile, Rectangle, EnumerateMetafileProc, IntPtr) | Sends the records of the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_31)(Metafile, RectangleF, EnumerateMetafileProc, IntPtr) | Sends the records of the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_2)(Metafile, Point, EnumerateMetafileProc, IntPtr, ImageAttributes) | Sends the records in the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point using specified image attributes. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_3)(Metafile, Point, Rectangle, GraphicsUnit, EnumerateMetafileProc) | Sends the records in a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_8)(Metafile, PointF, EnumerateMetafileProc, IntPtr, ImageAttributes) | Sends the records in the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point using specified image attributes. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_9)(Metafile, PointF, RectangleF, GraphicsUnit, EnumerateMetafileProc) | Sends the records in a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_14)(Metafile, PointF[], EnumerateMetafileProc, IntPtr, ImageAttributes) | Sends the records in the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram using specified image attributes. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_15)(Metafile, PointF[], RectangleF, GraphicsUnit, EnumerateMetafileProc) | Sends the records in a selected rectangle from a S[`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_20)(Metafile, Point[], EnumerateMetafileProc, IntPtr, ImageAttributes) | Sends the records in the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram using specified image attributes. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_21)(Metafile, Point[], Rectangle, GraphicsUnit, EnumerateMetafileProc) | Sends the records in a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_26)(Metafile, Rectangle, EnumerateMetafileProc, IntPtr, ImageAttributes) | Sends the records of the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle using specified image attributes. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_27)(Metafile, Rectangle, Rectangle, GraphicsUnit, EnumerateMetafileProc) | Sends the records of a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_32)(Metafile, RectangleF, EnumerateMetafileProc, IntPtr, ImageAttributes) | Sends the records of the specified [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle using specified image attributes. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_33)(Metafile, RectangleF, RectangleF, GraphicsUnit, EnumerateMetafileProc) | Sends the records of a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_4)(Metafile, Point, Rectangle, GraphicsUnit, EnumerateMetafileProc, IntPtr) | Sends the records in a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_10)(Metafile, PointF, RectangleF, GraphicsUnit, EnumerateMetafileProc, IntPtr) | Sends the records in a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_16)(Metafile, PointF[], RectangleF, GraphicsUnit, EnumerateMetafileProc, IntPtr) | Sends the records in a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_22)(Metafile, Point[], Rectangle, GraphicsUnit, EnumerateMetafileProc, IntPtr) | Sends the records in a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_28)(Metafile, Rectangle, Rectangle, GraphicsUnit, EnumerateMetafileProc, IntPtr) | Sends the records of a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_34)(Metafile, RectangleF, RectangleF, GraphicsUnit, EnumerateMetafileProc, IntPtr) | Sends the records of a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_5)(Metafile, Point, Rectangle, GraphicsUnit, EnumerateMetafileProc, IntPtr, ImageAttributes) | Sends the records in a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point using specified image attributes. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_11)(Metafile, PointF, RectangleF, GraphicsUnit, EnumerateMetafileProc, IntPtr, ImageAttributes) | Sends the records in a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point using specified image attributes. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_17)(Metafile, PointF[], RectangleF, GraphicsUnit, EnumerateMetafileProc, IntPtr, ImageAttributes) | Sends the records in a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram using specified image attributes. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_23)(Metafile, Point[], Rectangle, GraphicsUnit, EnumerateMetafileProc, IntPtr, ImageAttributes) | Sends the records in a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram using specified image attributes. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_29)(Metafile, Rectangle, Rectangle, GraphicsUnit, EnumerateMetafileProc, IntPtr, ImageAttributes) | Sends the records of a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle using specified image attributes. |
| [EnumerateMetafile](../../system.drawing/graphics/enumeratemetafile/#enumeratemetafile_35)(Metafile, RectangleF, RectangleF, GraphicsUnit, EnumerateMetafileProc, IntPtr, ImageAttributes) | Sends the records of a selected rectangle from a [`Metafile`](../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle using specified image attributes. |
| [ExcludeClip](../../system.drawing/graphics/excludeclip/#excludeclip)(Rectangle) | Updates the clip region of this Graphics to exclude the area specified by a Rectangle |
| [ExcludeClip](../../system.drawing/graphics/excludeclip/#excludeclip_1)(Region) | Updates the clip region of this Graphics to exclude the area specified by a Region. |
| [FillClosedCurve](../../system.drawing/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | Fills the interior of a closed cardinal spline curve defined by an array of PointF structures. |
| [FillClosedCurve](../../system.drawing/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | Fills the interior of a closed cardinal spline curve defined by an array of Point structures. |
| [FillClosedCurve](../../system.drawing/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | Fills the interior of a closed cardinal spline curve defined by an array of PointF structures using the specified fill mode. |
| [FillClosedCurve](../../system.drawing/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | Fills the interior of a closed cardinal spline curve defined by an array of Point structures using the specified fill mode. |
| [FillClosedCurve](../../system.drawing/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Fills the interior of a closed cardinal spline curve defined by an array of PointF structures using the specified fill mode and tension. |
| [FillClosedCurve](../../system.drawing/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Fills the interior of a closed cardinal spline curve defined by an array of Point structures using the specified fill mode. |
| [FillEllipse](../../system.drawing/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | Fills the interior of an ellipse defined by a bounding rectangle specified by a RectangleF structure. |
| [FillEllipse](../../system.drawing/graphics/fillellipse/#fillellipse)(Brush, float, float, float, float) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [FillPath](../../system.drawing/graphics/fillpath/)(Brush, GraphicsPath) | Fills the interior of a GraphicsPath. |
| [FillPie](../../system.drawing/graphics/fillpie/#fillpie_2)(Brush, Rectangle, float, float) | Fills the interior of a pie section defined by an ellipse specified by a Rectangle structure and two radial lines. |
| [FillPie](../../system.drawing/graphics/fillpie/#fillpie_1)(Brush, float, float, float, float, float, float) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [FillPie](../../system.drawing/graphics/fillpie/#fillpie)(Brush, int, int, int, int, int, int) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [FillPolygon](../../system.drawing/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | Fills the interior of a polygon defined by an array of points specified by PointF structures. |
| [FillPolygon](../../system.drawing/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | Fills the interior of a polygon defined by an array of points specified by Point structures. |
| [FillPolygon](../../system.drawing/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | Fills the interior of a polygon defined by an array of points specified by PointF structures using the specified fill mode. |
| [FillPolygon](../../system.drawing/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | Fills the interior of a polygon defined by an array of points specified by Point structures using the specified fill mode. |
| [FillRectangle](../../system.drawing/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | Fills the interior of a rectangle specified by a RectangleF structure. |
| [FillRectangle](../../system.drawing/graphics/fillrectangle/#fillrectangle)(Brush, float, float, float, float) | Fills the interior of a rectangle specified by a pair of coordinates, a width, and a height. |
| [FillRectangles](../../system.drawing/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | Fills the interiors of a series of rectangles specified by RectangleF structures. |
| [FillRectangles](../../system.drawing/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | Fills the interiors of a series of rectangles specified by Rectangle structures. |
| [FillRegion](../../system.drawing/graphics/fillregion/)(Brush, Region) | Fills the interior of a Region. |
| [Flush](../../system.drawing/graphics/flush/#flush)() | Forces execution of all pending graphics operations and returns immediately without waiting for the operations to finish. |
| [Flush](../../system.drawing/graphics/flush/#flush_1)(FlushIntention) | Forces execution of all pending graphics operations with the method waiting or not waiting, as specified, to return before the operations finish. |
| [GetHdc](../../system.drawing/graphics/gethdc/)() | Gets the handle to the device context associated with this Graphics. |
| [GetNearestColor](../../system.drawing/graphics/getnearestcolor/)(Color) | Gets the nearest color to the specified Color structure. |
| [IntersectClip](../../system.drawing/graphics/intersectclip/#intersectclip)(Rectangle) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Rectangle structure. |
| [IntersectClip](../../system.drawing/graphics/intersectclip/#intersectclip_1)(RectangleF) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified RectangleF structure. |
| [IntersectClip](../../system.drawing/graphics/intersectclip/#intersectclip_2)(Region) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Region. |
| [IsVisible](../../system.drawing/graphics/isvisible/#isvisible_4)(Point) | Indicates whether the specified Point structure is contained within the visible clip region of this Graphics. |
| [IsVisible](../../system.drawing/graphics/isvisible/#isvisible_5)(PointF) | Indicates whether the specified PointF structure is contained within the visible clip region of this Graphics. |
| [IsVisible](../../system.drawing/graphics/isvisible/#isvisible_6)(Rectangle) | Indicates whether the rectangle specified by a Rectangle structure is contained within the visible clip region of this Graphics. |
| [IsVisible](../../system.drawing/graphics/isvisible/#isvisible_7)(RectangleF) | Indicates whether the rectangle specified by a RectangleF structure is contained within the visible clip region of this Graphics. |
| [IsVisible](../../system.drawing/graphics/isvisible/#isvisible_2)(float, float) | Indicates whether the point specified by a pair of coordinates is contained within the visible clip region of this Graphics. |
| [IsVisible](../../system.drawing/graphics/isvisible/#isvisible)(int, int) | Indicates whether the point specified by a pair of coordinates is contained within the visible clip region of this Graphics. |
| [IsVisible](../../system.drawing/graphics/isvisible/#isvisible_3)(float, float, float, float) | Indicates whether the rectangle specified by a pair of coordinates, a width, and a height is contained within the visible clip region of this Graphics. |
| [IsVisible](../../system.drawing/graphics/isvisible/#isvisible_1)(int, int, int, int) | Indicates whether the rectangle specified by a pair of coordinates, a width, and a height is contained within the visible clip region of this Graphics. |
| [MeasureCharacterRanges](../../system.drawing/graphics/measurecharacterranges/)(string, Font, RectangleF, StringFormat) | Gets an array of Region objects, each of which bounds a range of character positions within the specified string. |
| [MeasureString](../../system.drawing/graphics/measurestring/#measurestring)(string, Font) | Measures the specified string when drawn with the specified Font. |
| [MeasureString](../../system.drawing/graphics/measurestring/#measurestring_1)(string, Font, int) | Measures the specified string when drawn with the specified Font. |
| [MeasureString](../../system.drawing/graphics/measurestring/#measurestring_4)(string, Font, SizeF) | Measures the specified string when drawn with the specified Font. |
| [MeasureString](../../system.drawing/graphics/measurestring/#measurestring_2)(string, Font, int, StringFormat) | Measures the specified string when drawn with the specified Font and formatted with the specified StringFormat. |
| [MeasureString](../../system.drawing/graphics/measurestring/#measurestring_3)(string, Font, PointF, StringFormat) | Measures the specified string when drawn with the specified Font and formatted with the specified StringFormat. |
| [MeasureString](../../system.drawing/graphics/measurestring/#measurestring_5)(string, Font, SizeF, StringFormat) | Measures the specified string when drawn with the specified Font and formatted with the specified StringFormat. |
| [MeasureString](../../system.drawing/graphics/measurestring/#measurestring_6)(string, Font, SizeF, StringFormat, out int, out int) | Measures the specified string when drawn with the specified Font and formatted with the specified StringFormat. |
| [MultiplyTransform](../../system.drawing/graphics/multiplytransform/#multiplytransform)(Matrix) | Multiplies the world transformation of this Graphics and specified the Matrix. |
| [MultiplyTransform](../../system.drawing/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplies the world transformation of this Graphics and specified the Matrix in the specified order. |
| [ReleaseHdc](../../system.drawing/graphics/releasehdc/#releasehdc)() | Releases a device context handle obtained by a previous call to the GetHdc method of this Graphics. |
| [ReleaseHdc](../../system.drawing/graphics/releasehdc/#releasehdc_1)(IntPtr) | Releases a device context handle obtained by a previous call to the GetHdc method of this Graphics. |
| [ResetClip](../../system.drawing/graphics/resetclip/)() | Resets the clip region of this Graphics to an infinite region. |
| [ResetTransform](../../system.drawing/graphics/resettransform/)() | Resets the world transformation matrix of this Graphics to the identity matrix. |
| [Restore](../../system.drawing/graphics/restore/)(GraphicsState) | Restores the state of this `Graphics` to the state represented by a [`GraphicsState`](../../system.drawing.drawing2d/graphicsstate/). |
| [RotateTransform](../../system.drawing/graphics/rotatetransform/#rotatetransform)(float) | Applies the specified rotation to the transformation matrix of this Graphics. |
| [RotateTransform](../../system.drawing/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Applies the specified rotation to the transformation matrix of this Graphics in the specified order. |
| [Save](../../system.drawing/graphics/save/)() | Saves the current state of this `Graphics` and identifies the saved state with a [`GraphicsState`](../../system.drawing.drawing2d/graphicsstate/). |
| [ScaleTransform](../../system.drawing/graphics/scaletransform/#scaletransform)(float, float) | Applies the specified scaling operation to the transformation matrix of this Graphics by prepending it to the object's transformation matrix. |
| [ScaleTransform](../../system.drawing/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Applies the specified scaling operation to the transformation matrix of this Graphics in the specified order. |
| [SetClip](../../system.drawing/graphics/setclip/#setclip_2)(Graphics) | Sets the clipping region of this `Graphics` to the Clip property of the specified `Graphics` |
| [SetClip](../../system.drawing/graphics/setclip/#setclip)(GraphicsPath) | Sets the clipping region of this `Graphics` to the specified [`GraphicsPath`](../../system.drawing.drawing2d/graphicspath/) . |
| [SetClip](../../system.drawing/graphics/setclip/#setclip_4)(Rectangle) | Sets the clipping region of this `Graphics` to the result of the specified operation combining the current clip region and the rectangle specified by a [`Rectangle`](../rectangle/) structure. |
| [SetClip](../../system.drawing/graphics/setclip/#setclip_6)(RectangleF) | Sets the clipping region of this `Graphics` to the result of the specified operation combining the current clip region and the rectangle specified by a [`RectangleF`](../rectanglef/) structure. |
| [SetClip](../../system.drawing/graphics/setclip/#setclip_3)(Graphics, CombineMode) | Sets the clipping region of this `Graphics` to the result of the specified combining operation of the current clip region and the Clip property of the specified `Graphics`. |
| [SetClip](../../system.drawing/graphics/setclip/#setclip_1)(GraphicsPath, CombineMode) | Sets the clipping region of this `Graphics` to the result of the specified operation combining the current clip region and the specified [`GraphicsPath`](../../system.drawing.drawing2d/graphicspath/). |
| [SetClip](../../system.drawing/graphics/setclip/#setclip_5)(Rectangle, CombineMode) | Sets the clipping region of this `Graphics` to the result of the specified operation combining the current clip region and the rectangle specified by a [`Rectangle`](../rectangle/) structure. |
| [SetClip](../../system.drawing/graphics/setclip/#setclip_7)(RectangleF, CombineMode) | Sets the clipping region of this `Graphics` to the result of the specified operation combining the current clip region and the rectangle specified by a [`RectangleF`](../rectanglef/) structure. |
| [SetClip](../../system.drawing/graphics/setclip/#setclip_8)(Region, CombineMode) | Sets the clipping region of this Graphics to the result of the specified operation combining the current clip region and the specified Region. |
| [TransformPoints](../../system.drawing/graphics/transformpoints/#transformpoints)(CoordinateSpace, CoordinateSpace, PointF[]) | Transforms an array of points from one coordinate space to another using the current world and page transformations of this Graphics. |
| [TransformPoints](../../system.drawing/graphics/transformpoints/#transformpoints_1)(CoordinateSpace, CoordinateSpace, Point[]) | Transforms an array of points from one coordinate space to another using the current world and page transformations of this Graphics. |
| [TranslateClip](../../system.drawing/graphics/translateclip/#translateclip_1)(float, float) | Translates the clipping region of this Graphics by specified amounts in the horizontal and vertical directions. |
| [TranslateClip](../../system.drawing/graphics/translateclip/#translateclip)(int, int) | Translates the clipping region of this Graphics by specified amounts in the horizontal and vertical directions. |
| [TranslateTransform](../../system.drawing/graphics/translatetransform/#translatetransform)(float, float) | Changes the origin of the coordinate system by prepending the specified translation to the transformation matrix of this Graphics. |
| [TranslateTransform](../../system.drawing/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Changes the origin of the coordinate system by applying the specified translation to the transformation matrix of this Graphics in the specified order. |

## Other Members

| Name | Description |
| --- | --- |
| delegate [DrawImageAbort](../../system.drawing/graphics.drawimageabort) | Provides a callback method for deciding when the [`DrawImage`](./drawimage/) method should prematurely cancel execution and stop drawing an image. |
| delegate [EnumerateMetafileProc](../../system.drawing/graphics.enumeratemetafileproc) | Provides a callback method for the [`EnumerateMetafile`](./enumeratemetafile/) method. |

### See Also

* namespace [System.Drawing](../../system.drawing/)
* assembly [Aspose.Drawing](../../)


