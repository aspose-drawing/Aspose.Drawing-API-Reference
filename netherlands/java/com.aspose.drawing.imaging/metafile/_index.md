---
title: Metafile
second_title: Aspose.Drawing voor Java API-referentie
description: Definieert een grafische metafile.
type: docs
weight: 30
url: /nl/java/com.aspose.drawing.imaging/metafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public final class Metafile extends Image
```

Defines a graphic metafile. A metafile contains records that describe a sequence of graphics operations that can be recorded (constructed) and played back (displayed). This class is not inheritable.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Metafile(byte[] henhmetafile, boolean deleteEmf)](#Metafile-byte---boolean-) | Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified handle. |
| [Metafile(byte[] referenceHdc, int emfType)](#Metafile-byte---int-) | Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified handle to a device context and an [EmfType](../../com.aspose.drawing.imaging/emftype) enumeration that specifies the format of the [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(String filename)](#Metafile-java.lang.String-) | Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified file name. |
| [Metafile(String filename, byte[] referenceHdc)](#Metafile-java.lang.String-byte---) | Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified file name. |
| [Metafile(InputStream stream)](#Metafile-java.io.InputStream-) | Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified data stream. |
| [Metafile(InputStream stream, byte[] referenceHdc)](#Metafile-java.io.InputStream-byte---) | Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified data stream and a Windows handle to a device context. |
| [Metafile(System.IO.Stream stream, int type)](#Metafile-com.aspose.ms.System.IO.Stream-int-) | Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified data stream and a Windows handle to a device context. |
| [Metafile(InputStream stream, byte[] referenceHdc, int type)](#Metafile-java.io.InputStream-byte---int-) | Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified data stream, a Windows handle to a device context, and an [EmfType](../../com.aspose.drawing.imaging/emftype) enumeration that specifies the format of the [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)](#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-) | Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified data stream, a Windows handle to a device context, and an [EmfType](../../com.aspose.drawing.imaging/emftype) enumeration that specifies the format of the [Metafile](../../com.aspose.drawing.imaging/metafile). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getWidth()](#getWidth--) | Gets the width, in pixels, of this [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getHeight()](#getHeight--) | Gets the height, in pixels, of this [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getRawFormat()](#getRawFormat--) | Gets the file format of this [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Gets the pixel format for this [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Gets or sets the color palette used for this [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Gets or sets the color palette used for this [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Gets an array of GUIDs that represent the dimensions of frames within this [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Gets IDs of the property items stored in this [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Gets all the property items (pieces of metadata) stored in this [Image](../../com.aspose.drawing/image). |
| [getMetafileHeader(InputStream stream)](#getMetafileHeader-java.io.InputStream-) | Returns the [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getMetafileHeader(String fileName)](#getMetafileHeader-java.lang.String-) | Returns the [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | This method rotates, flips, or rotates and flips the [Image](../../com.aspose.drawing/image). |
| [getHenhmetafile()](#getHenhmetafile--) | Returns a Windows handle to an enhanced [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [playRecord(int recordType, int flags, int dataSize, byte[] dataArray)](#playRecord-int-int-int-byte---) | Plays an individual metafile record. |
| [getMetafileHeader()](#getMetafileHeader--) | Returns the [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Gets the specified property item from this [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Removes the specified property item from this [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Stores a property item (piece of metadata) in this [Image](../../com.aspose.drawing/image). |
### Metafile(byte[] henhmetafile, boolean deleteEmf) {#Metafile-byte---boolean-}
```
public Metafile(byte[] henhmetafile, boolean deleteEmf)
```


Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified handle.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| henhmetafile | byte[] | Een handle naar een verbeterde metafile. |
| deleteEmf | boolean | true om de handle van het verbeterde metafile te verwijderen wanneer de [Metafile](../../com.aspose.drawing.imaging/metafile) wordt verwijderd; anders false. |

### Metafile(byte[] referenceHdc, int emfType) {#Metafile-byte---int-}
```
public Metafile(byte[] referenceHdc, int emfType)
```


Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified handle to a device context and an [EmfType](../../com.aspose.drawing.imaging/emftype) enumeration that specifies the format of the [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| referenceHdc | byte[] | De handle naar een apparaatcontext. |
| emfType | int | Een [EmfType](../../com.aspose.drawing.imaging/emftype) die het formaat van de [Metafile](../../com.aspose.drawing.imaging/metafile) specificeert. |

### Metafile(String filename) {#Metafile-java.lang.String-}
```
public Metafile(String filename)
```


Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified file name.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | java.lang.String | Een String die de bestandsnaam weergeeft waaruit het nieuwe [Metafile](../../com.aspose.drawing.imaging/metafile) moet worden gemaakt. |

### Metafile(String filename, byte[] referenceHdc) {#Metafile-java.lang.String-byte---}
```
public Metafile(String filename, byte[] referenceHdc)
```


Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified file name.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | java.lang.String | Een String die de bestandsnaam weergeeft waaruit het nieuwe [Metafile](../../com.aspose.drawing.imaging/metafile) moet worden gemaakt. |
| referenceHdc | byte[] | Een Windows-handle naar een apparaatcontext. |

### Metafile(InputStream stream) {#Metafile-java.io.InputStream-}
```
public Metafile(InputStream stream)
```


Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified data stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De InputStream waaruit het nieuwe [Metafile](../../com.aspose.drawing.imaging/metafile) moet worden gemaakt. |

### Metafile(InputStream stream, byte[] referenceHdc) {#Metafile-java.io.InputStream-byte---}
```
public Metafile(InputStream stream, byte[] referenceHdc)
```


Initialiseert een nieuw exemplaar van de [Metafile](../../com.aspose.drawing.imaging/metafile) klasse vanuit de opgegeven datastroom en een Windows-handle naar een apparaatcontext. />.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Een InputStream die de gegevens voor dit [Metafile](../../com.aspose.drawing.imaging/metafile) bevat. |
| referenceHdc | byte[] | Een Windows-handle naar een apparaatcontext van het [Metafile](../../com.aspose.drawing.imaging/metafile) object. |

### Metafile(System.IO.Stream stream, int type) {#Metafile-com.aspose.ms.System.IO.Stream-int-}
```
public Metafile(System.IO.Stream stream, int type)
```


Initialiseert een nieuw exemplaar van de [Metafile](../../com.aspose.drawing.imaging/metafile) klasse vanuit de opgegeven datastroom en een Windows-handle naar een apparaatcontext. />.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Een InputStream die de gegevens voor dit [Metafile](../../com.aspose.drawing.imaging/metafile) bevat. |
| type | int | moet int 1 zijn. |

### Metafile(InputStream stream, byte[] referenceHdc, int type) {#Metafile-java.io.InputStream-byte---int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, int type)
```


Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified data stream, a Windows handle to a device context, and an [EmfType](../../com.aspose.drawing.imaging/emftype) enumeration that specifies the format of the [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Een InputStream die de gegevens voor dit [Metafile](../../com.aspose.drawing.imaging/metafile) bevat. |
| referenceHdc | byte[] | Een Windows-handle naar een apparaatcontext. |
| type | int | Een [EmfType](../../com.aspose.drawing.imaging/emftype) die het formaat van de [Metafile](../../com.aspose.drawing.imaging/metafile) specificeert. |

### Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type) {#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)
```


Initializes a new instance of the [Metafile](../../com.aspose.drawing.imaging/metafile) class from the specified data stream, a Windows handle to a device context, and an [EmfType](../../com.aspose.drawing.imaging/emftype) enumeration that specifies the format of the [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Een InputStream die de gegevens voor dit [Metafile](../../com.aspose.drawing.imaging/metafile) bevat. |
| referenceHdc | byte[] | Een Windows-handle naar een apparaatcontext. |
| frameRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Een [Rectangle](../../com.aspose.drawing/rectangle) die de rechthoek weergeeft die het nieuwe [Metafile](../../com.aspose.drawing.imaging/metafile) omsluit. |
| frameUnit | int | Een [MetafileFrameUnit](../../com.aspose.drawing.imaging/metafileframeunit) die de meeteenheid voor frameRect specificeert. |
| type | int | Een [EmfType](../../com.aspose.drawing.imaging/emftype) die het formaat van de [Metafile](../../com.aspose.drawing.imaging/metafile) specificeert. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the width, in pixels, of this [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets the height, in pixels, of this [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int - de hoogte, in pixels, van dit [Metafile](../../com.aspose.drawing.imaging/metafile).
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


Gets the file format of this [Image](../../com.aspose.drawing/image).

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Gets the pixel format for this [Image](../../com.aspose.drawing/image).

**Returns:**
int - Een `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) die het pixelformaat voor deze [Image](../../com.aspose.drawing/image) weergeeft.
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


Gets or sets the color palette used for this [Image](../../com.aspose.drawing/image).

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


Gets or sets the color palette used for this [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


Gets an array of GUIDs that represent the dimensions of frames within this [Image](../../com.aspose.drawing/image).

**Returns:**
java.util.UUID[] - Een array van GUID's die de afmetingen van frames binnen deze [Image](../../com.aspose.drawing/image) van meest significant tot minst significant specificeren.
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


Gets IDs of the property items stored in this [Image](../../com.aspose.drawing/image).

**Returns:**
int[] - Een array van de eigenschap-ID's, één voor elk eigenschap-item dat in deze afbeelding is opgeslagen.
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


Gets all the property items (pieces of metadata) stored in this [Image](../../com.aspose.drawing/image).

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] - Een array van [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) objecten, één voor elk eigenschap-item dat in de afbeelding is opgeslagen.
### getMetafileHeader(InputStream stream) {#getMetafileHeader-java.io.InputStream-}
```
public static MetafileHeader getMetafileHeader(InputStream stream)
```


Returns the [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Een InputStream die de [Metafile](../../com.aspose.drawing.imaging/metafile) bevat waarvoor een header wordt opgehaald. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### getMetafileHeader(String fileName) {#getMetafileHeader-java.lang.String-}
```
public static MetafileHeader getMetafileHeader(String fileName)
```


Returns the [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Een String die de naam van de [Metafile](../../com.aspose.drawing.imaging/metafile) bevat waarvoor een header wordt opgehaald. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


This method rotates, flips, or rotates and flips the [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rotateFlipType | int | Een [RotateFlipType](../../com.aspose.drawing/rotatefliptype) lid dat het type rotatie en omkering specificeert dat op de afbeelding moet worden toegepast. |

### getHenhmetafile() {#getHenhmetafile--}
```
public System.IntPtr getHenhmetafile()
```


Returns a Windows handle to an enhanced [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
com.aspose.ms.System.IntPtr - Een Windows-handle naar dit verbeterde [Metafile](../../com.aspose.drawing.imaging/metafile).
### playRecord(int recordType, int flags, int dataSize, byte[] dataArray) {#playRecord-int-int-int-byte---}
```
public void playRecord(int recordType, int flags, int dataSize, byte[] dataArray)
```


Plays an individual metafile record.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recordType | int | Element van de [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) dat het type metafile‑record aangeeft dat wordt afgespeeld. |
| flags | int | Een set vlaggen die attributen van het record specificeren. |
| dataSize | int | Het aantal bytes in de recordgegevens. |
| dataArray | byte[] | Een array van bytes die de recordgegevens bevat. |

### getMetafileHeader() {#getMetafileHeader--}
```
public MetafileHeader getMetafileHeader()
```


Returns the [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile).
### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


Gets the specified property item from this [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propid | int | De ID van het eigenschap‑item om op te halen. |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


Removes the specified property item from this [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propid | int | De ID van het eigenschap‑item om te verwijderen. |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


Stores a property item (piece of metadata) in this [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | Het [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) dat moet worden opgeslagen. |

