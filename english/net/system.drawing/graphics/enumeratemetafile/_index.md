---
title: Graphics.EnumerateMetafile
second_title: Aspose.Drawing for .NET API Reference
description: Graphics method. Sends the records in the specified Metafile one at a time to a callback method for display at a specified point using specified image attributes
type: docs
weight: 460
url: /net/system.drawing/graphics/enumeratemetafile/
---
## EnumerateMetafile(Metafile, PointF, EnumerateMetafileProc, IntPtr, ImageAttributes) {#enumeratemetafile_8}

Sends the records in the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point using specified image attributes.

```csharp
public void EnumerateMetafile(Metafile metafile, PointF destPoint, EnumerateMetafileProc callback, 
    IntPtr callbackData, ImageAttributes imageAttr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoint | PointF | [`PointF`](../../pointf/) structure that specifies the location of the upper-left corner of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |
| imageAttr | ImageAttributes | [`ImageAttributes`](../../../system.drawing.imaging/imageattributes/) that specifies image attribute information for the drawn image. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [PointF](../../pointf/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, PointF, EnumerateMetafileProc, IntPtr) {#enumeratemetafile_7}

Sends the records in the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point.

```csharp
public void EnumerateMetafile(Metafile metafile, PointF destPoint, EnumerateMetafileProc callback, 
    IntPtr callbackData)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoint | PointF | [`PointF`](../../pointf/) structure that specifies the location of the upper-left corner of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [PointF](../../pointf/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, PointF[], EnumerateMetafileProc) {#enumeratemetafile_12}

Sends the records in the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram.

```csharp
public void EnumerateMetafile(Metafile metafile, PointF[] destPoints, 
    EnumerateMetafileProc callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoints | PointF[] | Array of three [`PointF`](../../pointf/) structures that define a parallelogram that determines the size and location of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [PointF](../../pointf/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Point, EnumerateMetafileProc) {#enumeratemetafile}

Sends the records in the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point.

```csharp
public void EnumerateMetafile(Metafile metafile, Point destPoint, EnumerateMetafileProc callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoint | Point | [`Point`](../../point/) structure that specifies the location of the upper-left corner of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Point](../../point/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Point, EnumerateMetafileProc, IntPtr) {#enumeratemetafile_1}

Sends the records in the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point.

```csharp
public void EnumerateMetafile(Metafile metafile, Point destPoint, EnumerateMetafileProc callback, 
    IntPtr callbackData)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoint | Point | [`Point`](../../point/) structure that specifies the location of the upper-left corner of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Point](../../point/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Point, EnumerateMetafileProc, IntPtr, ImageAttributes) {#enumeratemetafile_2}

Sends the records in the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point using specified image attributes.

```csharp
public void EnumerateMetafile(Metafile metafile, Point destPoint, EnumerateMetafileProc callback, 
    IntPtr callbackData, ImageAttributes imageAttr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoint | Point | [`Point`](../../point/) structure that specifies the location of the upper-left corner of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |
| imageAttr | ImageAttributes | [`ImageAttributes`](../../../system.drawing.imaging/imageattributes/) that specifies image attribute information for the drawn image. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Point](../../point/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, RectangleF, EnumerateMetafileProc) {#enumeratemetafile_30}

Sends the records of the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle.

```csharp
public void EnumerateMetafile(Metafile metafile, RectangleF destRect, 
    EnumerateMetafileProc callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destRect | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the location and size of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [RectangleF](../../rectanglef/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, RectangleF, EnumerateMetafileProc, IntPtr) {#enumeratemetafile_31}

Sends the records of the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle.

```csharp
public void EnumerateMetafile(Metafile metafile, RectangleF destRect, 
    EnumerateMetafileProc callback, IntPtr callbackData)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destRect | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the location and size of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [RectangleF](../../rectanglef/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, RectangleF, EnumerateMetafileProc, IntPtr, ImageAttributes) {#enumeratemetafile_32}

Sends the records of the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle using specified image attributes.

```csharp
public void EnumerateMetafile(Metafile metafile, RectangleF destRect, 
    EnumerateMetafileProc callback, IntPtr callbackData, ImageAttributes imageAttr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destRect | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the location and size of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |
| imageAttr | ImageAttributes | [`ImageAttributes`](../../../system.drawing.imaging/imageattributes/) that specifies image attribute information for the drawn image. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [RectangleF](../../rectanglef/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Rectangle, EnumerateMetafileProc) {#enumeratemetafile_24}

Sends the records of the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle.

```csharp
public void EnumerateMetafile(Metafile metafile, Rectangle destRect, EnumerateMetafileProc callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destRect | Rectangle | [`Rectangle`](../../rectangle/) structure that specifies the location and size of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Rectangle](../../rectangle/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, PointF, EnumerateMetafileProc) {#enumeratemetafile_6}

Sends the records in the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point.

```csharp
public void EnumerateMetafile(Metafile metafile, PointF destPoint, EnumerateMetafileProc callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoint | PointF | [`PointF`](../../pointf/) structure that specifies the location of the upper-left corner of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [PointF](../../pointf/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, PointF[], EnumerateMetafileProc, IntPtr) {#enumeratemetafile_13}

Sends the records in the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram.

```csharp
public void EnumerateMetafile(Metafile metafile, PointF[] destPoints, 
    EnumerateMetafileProc callback, IntPtr callbackData)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoints | PointF[] | Array of three [`PointF`](../../pointf/) structures that define a parallelogram that determines the size and location of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [PointF](../../pointf/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Point[], EnumerateMetafileProc, IntPtr) {#enumeratemetafile_19}

Sends the records in the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram.

```csharp
public void EnumerateMetafile(Metafile metafile, Point[] destPoints, 
    EnumerateMetafileProc callback, IntPtr callbackData)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoints | Point[] | Array of three [`Point`](../../point/) structures that define a parallelogram that determines the size and location of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Point](../../point/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Point[], EnumerateMetafileProc) {#enumeratemetafile_18}

Sends the records in the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram.

```csharp
public void EnumerateMetafile(Metafile metafile, Point[] destPoints, EnumerateMetafileProc callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoints | Point[] | Array of three [`Point`](../../point/) structures that define a parallelogram that determines the size and location of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Point](../../point/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Point[], Rectangle, GraphicsUnit, EnumerateMetafileProc, IntPtr, ImageAttributes) {#enumeratemetafile_23}

Sends the records in a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram using specified image attributes.

```csharp
public void EnumerateMetafile(Metafile metafile, Point[] destPoints, Rectangle srcRect, 
    GraphicsUnit unit, EnumerateMetafileProc callback, IntPtr callbackData, 
    ImageAttributes imageAttr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoints | Point[] | Array of three [`Point`](../../point/) structures that define a parallelogram that determines the size and location of the drawn metafile. |
| srcRect | Rectangle | [`Rectangle`](../../rectangle/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| unit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |
| imageAttr | ImageAttributes | [`ImageAttributes`](../../../system.drawing.imaging/imageattributes/) that specifies image attribute information for the drawn image. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Point[], Rectangle, GraphicsUnit, EnumerateMetafileProc, IntPtr) {#enumeratemetafile_22}

Sends the records in a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram.

```csharp
public void EnumerateMetafile(Metafile metafile, Point[] destPoints, Rectangle srcRect, 
    GraphicsUnit srcUnit, EnumerateMetafileProc callback, IntPtr callbackData)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoints | Point[] | Array of three [`Point`](../../point/) structures that define a parallelogram that determines the size and location of the drawn metafile. |
| srcRect | Rectangle | [`Rectangle`](../../rectangle/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| srcUnit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Point[], Rectangle, GraphicsUnit, EnumerateMetafileProc) {#enumeratemetafile_21}

Sends the records in a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram.

```csharp
public void EnumerateMetafile(Metafile metafile, Point[] destPoints, Rectangle srcRect, 
    GraphicsUnit srcUnit, EnumerateMetafileProc callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoints | Point[] | Array of three [`Point`](../../point/) structures that define a parallelogram that determines the size and location of the drawn metafile. |
| srcRect | Rectangle | [`Rectangle`](../../rectangle/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| srcUnit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, PointF[], RectangleF, GraphicsUnit, EnumerateMetafileProc, IntPtr, ImageAttributes) {#enumeratemetafile_17}

Sends the records in a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram using specified image attributes.

```csharp
public void EnumerateMetafile(Metafile metafile, PointF[] destPoints, RectangleF srcRect, 
    GraphicsUnit unit, EnumerateMetafileProc callback, IntPtr callbackData, 
    ImageAttributes imageAttr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoints | PointF[] | Array of three [`PointF`](../../pointf/) structures that define a parallelogram that determines the size and location of the drawn metafile. |
| srcRect | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| unit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |
| imageAttr | ImageAttributes | [`ImageAttributes`](../../../system.drawing.imaging/imageattributes/) that specifies image attribute information for the drawn image. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, PointF[], RectangleF, GraphicsUnit, EnumerateMetafileProc, IntPtr) {#enumeratemetafile_16}

Sends the records in a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram.

```csharp
public void EnumerateMetafile(Metafile metafile, PointF[] destPoints, RectangleF srcRect, 
    GraphicsUnit srcUnit, EnumerateMetafileProc callback, IntPtr callbackData)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoints | PointF[] | Array of three [`PointF`](../../pointf/) structures that define a parallelogram that determines the size and location of the drawn metafile. |
| srcRect | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| srcUnit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, PointF[], RectangleF, GraphicsUnit, EnumerateMetafileProc) {#enumeratemetafile_15}

Sends the records in a selected rectangle from a S[`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram.

```csharp
public void EnumerateMetafile(Metafile metafile, PointF[] destPoints, RectangleF srcRect, 
    GraphicsUnit srcUnit, EnumerateMetafileProc callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoints | PointF[] | Array of three [`PointF`](../../pointf/) structures that define a parallelogram that determines the size and location of the drawn metafile. |
| srcRect | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| srcUnit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Rectangle, Rectangle, GraphicsUnit, EnumerateMetafileProc, IntPtr, ImageAttributes) {#enumeratemetafile_29}

Sends the records of a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle using specified image attributes.

```csharp
public void EnumerateMetafile(Metafile metafile, Rectangle destRect, Rectangle srcRect, 
    GraphicsUnit unit, EnumerateMetafileProc callback, IntPtr callbackData, 
    ImageAttributes imageAttr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destRect | Rectangle | [`Rectangle`](../../rectangle/) structure that specifies the location and size of the drawn metafile. |
| srcRect | Rectangle | [`Rectangle`](../../rectangle/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| unit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |
| imageAttr | ImageAttributes | [`ImageAttributes`](../../../system.drawing.imaging/imageattributes/) that specifies image attribute information for the drawn image. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Rectangle, Rectangle, GraphicsUnit, EnumerateMetafileProc, IntPtr) {#enumeratemetafile_28}

Sends the records of a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle.

```csharp
public void EnumerateMetafile(Metafile metafile, Rectangle destRect, Rectangle srcRect, 
    GraphicsUnit srcUnit, EnumerateMetafileProc callback, IntPtr callbackData)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destRect | Rectangle | [`Rectangle`](../../rectangle/) structure that specifies the location and size of the drawn metafile. |
| srcRect | Rectangle | [`Rectangle`](../../rectangle/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| srcUnit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Rectangle, Rectangle, GraphicsUnit, EnumerateMetafileProc) {#enumeratemetafile_27}

Sends the records of a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle.

```csharp
public void EnumerateMetafile(Metafile metafile, Rectangle destRect, Rectangle srcRect, 
    GraphicsUnit srcUnit, EnumerateMetafileProc callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destRect | Rectangle | [`Rectangle`](../../rectangle/) structure that specifies the location and size of the drawn metafile. |
| srcRect | Rectangle | [`Rectangle`](../../rectangle/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| srcUnit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, PointF[], EnumerateMetafileProc, IntPtr, ImageAttributes) {#enumeratemetafile_14}

Sends the records in the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram using specified image attributes.

```csharp
public void EnumerateMetafile(Metafile metafile, PointF[] destPoints, 
    EnumerateMetafileProc callback, IntPtr callbackData, ImageAttributes imageAttr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoints | PointF[] | Array of three [`PointF`](../../pointf/) structures that define a parallelogram that determines the size and location of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |
| imageAttr | ImageAttributes | [`ImageAttributes`](../../../system.drawing.imaging/imageattributes/) that specifies image attribute information for the drawn image. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [PointF](../../pointf/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, RectangleF, RectangleF, GraphicsUnit, EnumerateMetafileProc, IntPtr, ImageAttributes) {#enumeratemetafile_35}

Sends the records of a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle using specified image attributes.

```csharp
public void EnumerateMetafile(Metafile metafile, RectangleF destRect, RectangleF srcRect, 
    GraphicsUnit unit, EnumerateMetafileProc callback, IntPtr callbackData, 
    ImageAttributes imageAttr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destRect | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the location and size of the drawn metafile. |
| srcRect | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| unit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |
| imageAttr | ImageAttributes | [`ImageAttributes`](../../../system.drawing.imaging/imageattributes/) that specifies image attribute information for the drawn image. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, RectangleF, RectangleF, GraphicsUnit, EnumerateMetafileProc) {#enumeratemetafile_33}

Sends the records of a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle.

```csharp
public void EnumerateMetafile(Metafile metafile, RectangleF destRect, RectangleF srcRect, 
    GraphicsUnit srcUnit, EnumerateMetafileProc callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destRect | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the location and size of the drawn metafile. |
| srcRect | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| srcUnit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Point, Rectangle, GraphicsUnit, EnumerateMetafileProc, IntPtr, ImageAttributes) {#enumeratemetafile_5}

Sends the records in a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point using specified image attributes.

```csharp
public void EnumerateMetafile(Metafile metafile, Point destPoint, Rectangle srcRect, 
    GraphicsUnit unit, EnumerateMetafileProc callback, IntPtr callbackData, 
    ImageAttributes imageAttr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoint | Point | [`Point`](../../point/) structure that specifies the location of the upper-left corner of the drawn metafile. |
| srcRect | Rectangle | [`Rectangle`](../../rectangle/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| unit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |
| imageAttr | ImageAttributes | [`ImageAttributes`](../../../system.drawing.imaging/imageattributes/) that specifies image attribute information for the drawn image. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Point, Rectangle, GraphicsUnit, EnumerateMetafileProc, IntPtr) {#enumeratemetafile_4}

Sends the records in a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point.

```csharp
public void EnumerateMetafile(Metafile metafile, Point destPoint, Rectangle srcRect, 
    GraphicsUnit srcUnit, EnumerateMetafileProc callback, IntPtr callbackData)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoint | Point | [`Point`](../../point/) structure that specifies the location of the upper-left corner of the drawn metafile. |
| srcRect | Rectangle | [`Rectangle`](../../rectangle/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| srcUnit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Point, Rectangle, GraphicsUnit, EnumerateMetafileProc) {#enumeratemetafile_3}

Sends the records in a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point.

```csharp
public void EnumerateMetafile(Metafile metafile, Point destPoint, Rectangle srcRect, 
    GraphicsUnit srcUnit, EnumerateMetafileProc callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoint | Point | [`Point`](../../point/) structure that specifies the location of the upper-left corner of the drawn metafile. |
| srcRect | Rectangle | [`Rectangle`](../../rectangle/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| srcUnit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Rectangle, EnumerateMetafileProc, IntPtr) {#enumeratemetafile_25}

Sends the records of the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle.

```csharp
public void EnumerateMetafile(Metafile metafile, Rectangle destRect, 
    EnumerateMetafileProc callback, IntPtr callbackData)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destRect | Rectangle | [`RectangleF`](../../rectanglef/) structure that specifies the location and size of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Rectangle](../../rectangle/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, PointF, RectangleF, GraphicsUnit, EnumerateMetafileProc, IntPtr, ImageAttributes) {#enumeratemetafile_11}

Sends the records in a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point using specified image attributes.

```csharp
public void EnumerateMetafile(Metafile metafile, PointF destPoint, RectangleF srcRect, 
    GraphicsUnit unit, EnumerateMetafileProc callback, IntPtr callbackData, 
    ImageAttributes imageAttr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoint | PointF | [`PointF`](../../pointf/) structure that specifies the location of the upper-left corner of the drawn metafile. |
| srcRect | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| unit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |
| imageAttr | ImageAttributes | [`ImageAttributes`](../../../system.drawing.imaging/imageattributes/) that specifies image attribute information for the drawn image. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, PointF, RectangleF, GraphicsUnit, EnumerateMetafileProc, IntPtr) {#enumeratemetafile_10}

Sends the records in a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point.

```csharp
public void EnumerateMetafile(Metafile metafile, PointF destPoint, RectangleF srcRect, 
    GraphicsUnit srcUnit, EnumerateMetafileProc callback, IntPtr callbackData)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoint | PointF | [`PointF`](../../pointf/) structure that specifies the location of the upper-left corner of the drawn metafile. |
| srcRect | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| srcUnit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, PointF, RectangleF, GraphicsUnit, EnumerateMetafileProc) {#enumeratemetafile_9}

Sends the records in a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display at a specified point.

```csharp
public void EnumerateMetafile(Metafile metafile, PointF destPoint, RectangleF srcRect, 
    GraphicsUnit srcUnit, EnumerateMetafileProc callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoint | PointF | [`PointF`](../../pointf/) structure that specifies the location of the upper-left corner of the drawn metafile. |
| srcRect | RectangleF | System.Drawing.RectangleF structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| srcUnit | GraphicsUnit | Member of the[`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Point[], EnumerateMetafileProc, IntPtr, ImageAttributes) {#enumeratemetafile_20}

Sends the records in the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified parallelogram using specified image attributes.

```csharp
public void EnumerateMetafile(Metafile metafile, Point[] destPoints, 
    EnumerateMetafileProc callback, IntPtr callbackData, ImageAttributes imageAttr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destPoints | Point[] | Array of three [`Point`](../../point/) structures that define a parallelogram that determines the size and location of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |
| imageAttr | ImageAttributes | [`ImageAttributes`](../../../system.drawing.imaging/imageattributes/) that specifies image attribute information for the drawn image. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Point](../../point/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, RectangleF, RectangleF, GraphicsUnit, EnumerateMetafileProc, IntPtr) {#enumeratemetafile_34}

Sends the records of a selected rectangle from a [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle.

```csharp
public void EnumerateMetafile(Metafile metafile, RectangleF destRect, RectangleF srcRect, 
    GraphicsUnit srcUnit, EnumerateMetafileProc callback, IntPtr callbackData)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destRect | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the location and size of the drawn metafile. |
| srcRect | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the portion of the metafile, relative to its upper-left corner, to draw. |
| srcUnit | GraphicsUnit | Member of the [`GraphicsUnit`](../../graphicsunit/) enumeration that specifies the unit of measure used to determine the portion of the metafile that the rectangle specified by the *srcRect* parameter contains. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)

---

## EnumerateMetafile(Metafile, Rectangle, EnumerateMetafileProc, IntPtr, ImageAttributes) {#enumeratemetafile_26}

Sends the records of the specified [`Metafile`](../../../system.drawing.imaging/metafile/), one at a time, to a callback method for display in a specified rectangle using specified image attributes.

```csharp
public void EnumerateMetafile(Metafile metafile, Rectangle destRect, 
    EnumerateMetafileProc callback, IntPtr callbackData, ImageAttributes imageAttr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| metafile | Metafile | [`Metafile`](../../../system.drawing.imaging/metafile/) to enumerate. |
| destRect | Rectangle | [`Rectangle`](../../rectangle/) structure that specifies the location and size of the drawn metafile. |
| callback | EnumerateMetafileProc | [`EnumerateMetafileProc`](../../graphics.enumeratemetafileproc/) delegate that specifies the method to which the metafile records are sent. |
| callbackData | IntPtr | Internal pointer that is required, but ignored. You can pass Zero for this parameter. |
| imageAttr | ImageAttributes | [`ImageAttributes`](../../../system.drawing.imaging/imageattributes/) that specifies image attribute information for the drawn image. |

### See Also

* class [Metafile](../../../system.drawing.imaging/metafile/)
* struct [Rectangle](../../rectangle/)
* delegate [EnumerateMetafileProc](../../graphics.enumeratemetafileproc/)
* class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* class [Graphics](../)
* namespace [System.Drawing](../../graphics/)
* assembly [Aspose.Drawing](../../../)


