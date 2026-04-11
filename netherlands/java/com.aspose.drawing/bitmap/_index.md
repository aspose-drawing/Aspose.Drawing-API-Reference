---
title: Bitmap
second_title: Aspose.Drawing voor Java API-referentie
description: Omvat een bitmap die bestaat uit de pixelgegevens voor een grafische afbeelding en de bijbehorende attributen.
type: docs
weight: 10
url: /nl/java/com.aspose.drawing/bitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public class Bitmap extends Image
```

Omvat een bitmap, die bestaat uit de pixelgegevens voor een grafische afbeelding en de bijbehorende attributen. Een [Bitmap](../../com.aspose.drawing/bitmap) is een object dat wordt gebruikt om te werken met afbeeldingen die zijn gedefinieerd door pixelgegevens.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Bitmap(int width, int height)](#Bitmap-int-int-) | Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse met de opgegeven grootte. |
| [Bitmap(String filename)](#Bitmap-java.lang.String-) | Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse vanuit het opgegeven bestand. |
| [Bitmap(String filename, boolean useIcm)](#Bitmap-java.lang.String-boolean-) | Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse vanuit het opgegeven bestand. |
| [Bitmap(InputStream stream)](#Bitmap-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse vanuit de opgegeven gegevensstroom. |
| [Bitmap(InputStream stream, boolean useIcm)](#Bitmap-java.io.InputStream-boolean-) | Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse vanuit de opgegeven gegevensstroom. |
| [Bitmap(int width, int height, int format)](#Bitmap-int-int-int-) | Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse met de opgegeven grootte en indeling. |
| [Bitmap(int width, int height, int stride, int format, int[] data)](#Bitmap-int-int-int-int-int---) | Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse met de opgegeven grootte en pixelgegevens. |
| [Bitmap(Image original)](#Bitmap-com.aspose.drawing.Image-) | Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse vanuit de opgegeven bestaande afbeelding. |
| [Bitmap(Image original, Size newSize)](#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-) | Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse vanuit de opgegeven bestaande afbeelding, geschaald naar de opgegeven grootte. |
| [Bitmap(Image original, int width, int height)](#Bitmap-com.aspose.drawing.Image-int-int-) | Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse vanuit de opgegeven bestaande afbeelding, geschaald naar de opgegeven grootte. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getWidth()](#getWidth--) | Haalt de breedte, in pixels, van deze Bitmap op. |
| [getHeight()](#getHeight--) | Haalt de hoogte, in pixels, van deze Bitmap op. |
| [getRawFormat()](#getRawFormat--) | Gets the file format of this [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Gets the pixel format for this [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Gets or sets the color palette used for this [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Gets or sets the color palette used for this [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Gets an array of GUIDs that represent the dimensions of frames within this [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Gets IDs of the property items stored in this [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Gets all the property items (pieces of metadata) stored in this [Image](../../com.aspose.drawing/image). |
| [deepClone(Rectangle rect, int format)](#deepClone-com.aspose.drawing.Rectangle-int-) | Maakt een kopie van het gedeelte van deze [Bitmap](../../com.aspose.drawing/bitmap) dat wordt gedefinieerd door de [Rectangle](../../com.aspose.drawing/rectangle)-structuur en met een opgegeven `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) enumeratie. |
| [deepClone(RectangleF rect, int format)](#deepClone-com.aspose.drawing.RectangleF-int-) | Maakt een kopie van het gedeelte van deze [Bitmap](../../com.aspose.drawing/bitmap) gedefinieerd met een opgegeven [PixelFormat](../../com.aspose.drawing.imaging/pixelformat)-enumeratie. |
| [setResolution(float xDpi, float yDpi)](#setResolution-float-float-) | Stelt de resolutie in voor deze [Bitmap](../../com.aspose.drawing/bitmap). |
| [lockBits(Rectangle rect, int flags, int format)](#lockBits-com.aspose.drawing.Rectangle-int-int-) | Vergrendelt een [Bitmap](../../com.aspose.drawing/bitmap) in het systeemgeheugen. |
| [unlockBits(BitmapData bitmapData)](#unlockBits-com.aspose.drawing.imaging.BitmapData-) | Ontgrendelt deze [Bitmap](../../com.aspose.drawing/bitmap) uit het systeemgeheugen. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Haalt de kleur op van de opgegeven pixel in deze [Bitmap](../../com.aspose.drawing/bitmap). |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.drawing.Color-) | Stelt de kleur in van de opgegeven pixel in deze [Bitmap](../../com.aspose.drawing/bitmap). |
| [readArgb32Pixels(int[] pixels)](#readArgb32Pixels-int---) | Leest bitmap-pixels in ARGB32-formaat in de opgegeven array. |
| [writeArgb32Pixels(int[] pixels)](#writeArgb32Pixels-int---) | Schrijft pixels naar de bitmap. |
| [makeTransparent()](#makeTransparent--) | Maakt de opgegeven kleur transparant voor deze [Bitmap](../../com.aspose.drawing/bitmap). |
| [makeTransparent(Color transparentColor)](#makeTransparent-com.aspose.drawing.Color-) | Maakt de opgegeven kleur transparant voor deze [Bitmap](../../com.aspose.drawing/bitmap). |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | This method rotates, flips, or rotates and flips the [Image](../../com.aspose.drawing/image). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Gets the specified property item from this [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Removes the specified property item from this [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Stores a property item (piece of metadata) in this [Image](../../com.aspose.drawing/image). |
### Bitmap(int width, int height) {#Bitmap-int-int-}
```
public Bitmap(int width, int height)
```


Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| breedte | int | De breedte, in pixels, van de nieuwe Bitmap. |
|  | hoogte | int | De hoogte, in pixels, van de nieuwe Bitmap. |

--------------------

Het enige ondersteunde interne bitmapformaat op dit moment is gelijk aan `PixelFormat.Format32bppPArgb`. |

### Bitmap(String filename) {#Bitmap-java.lang.String-}
```
public Bitmap(String filename)
```


Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse vanuit het opgegeven bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestandsnaam | java.lang.String | De naam van het bitmapbestand. |

### Bitmap(String filename, boolean useIcm) {#Bitmap-java.lang.String-boolean-}
```
public Bitmap(String filename, boolean useIcm)
```


Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse vanuit het opgegeven bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestandsnaam | java.lang.String | De naam van het bitmapbestand. |
| useIcm | boolean | true om kleurcorrectie te gebruiken voor deze [Bitmap](../../com.aspose.drawing/bitmap); anders false. |

### Bitmap(InputStream stream) {#Bitmap-java.io.InputStream-}
```
public Bitmap(InputStream stream)
```


Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse vanuit de opgegeven gegevensstroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | java.io.InputStream | De datastroom die wordt gebruikt om de afbeelding te laden. |

### Bitmap(InputStream stream, boolean useIcm) {#Bitmap-java.io.InputStream-boolean-}
```
public Bitmap(InputStream stream, boolean useIcm)
```


Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse vanuit de opgegeven gegevensstroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | java.io.InputStream | De datastroom die wordt gebruikt om de afbeelding te laden. |
| useIcm | boolean | `true` om kleurcorrectie te gebruiken voor deze [Bitmap](../../com.aspose.drawing/bitmap); anders `false`. |

### Bitmap(int width, int height, int format) {#Bitmap-int-int-int-}
```
public Bitmap(int width, int height, int format)
```


Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse met de opgegeven grootte en indeling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | int | De breedte, in pixels, van de nieuwe [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | De hoogte, in pixels, van de nieuwe [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | De `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) enumeratie voor de nieuwe [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(int width, int height, int stride, int format, int[] data) {#Bitmap-int-int-int-int-int---}
```
public Bitmap(int width, int height, int stride, int format, int[] data)
```


Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse met de opgegeven grootte en pixelgegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | int | De breedte, in pixels, van de nieuwe [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | De hoogte, in pixels, van de nieuwe [Bitmap](../../com.aspose.drawing/bitmap). |
| stride | int | De byte-offset tussen het begin van één scanlijn en de volgende, moet een veelvoud van vier zijn. |
| format | int | De `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) enumeratie voor de nieuwe [Bitmap](../../com.aspose.drawing/bitmap). |
| gegevens | int[] | De pixelgegevens. |

### Bitmap(Image original) {#Bitmap-com.aspose.drawing.Image-}
```
public Bitmap(Image original)
```


Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse vanuit de opgegeven bestaande afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | De [Image](../../com.aspose.drawing/image) waaruit de nieuwe [Bitmap](../../com.aspose.drawing/bitmap) moet worden gemaakt. |

### Bitmap(Image original, Size newSize) {#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-}
```
public Bitmap(Image original, Size newSize)
```


Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse vanuit de opgegeven bestaande afbeelding, geschaald naar de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | De [Image](../../com.aspose.drawing/image) waaruit de nieuwe [Bitmap](../../com.aspose.drawing/bitmap) moet worden gemaakt |
| newSize | [Size](../../com.aspose.drawing/size) | De `Size`([Image.getSize](../../com.aspose.drawing/image\#getSize)) structuur die de grootte van de nieuwe [Bitmap](../../com.aspose.drawing/bitmap) vertegenwoordigt. |

### Bitmap(Image original, int width, int height) {#Bitmap-com.aspose.drawing.Image-int-int-}
```
public Bitmap(Image original, int width, int height)
```


Initialiseert een nieuw exemplaar van de [Bitmap](../../com.aspose.drawing/bitmap)-klasse vanuit de opgegeven bestaande afbeelding, geschaald naar de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | De [Image](../../com.aspose.drawing/image) waaruit de nieuwe [Bitmap](../../com.aspose.drawing/bitmap) moet worden gemaakt. |
| width | int | De breedte, in pixels, van de nieuwe [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | De hoogte, in pixels, van de nieuwe [Bitmap](../../com.aspose.drawing/bitmap). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Haalt de breedte, in pixels, van deze Bitmap op.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Haalt de hoogte, in pixels, van deze Bitmap op.

**Returns:**
int
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
### deepClone(Rectangle rect, int format) {#deepClone-com.aspose.drawing.Rectangle-int-}
```
public final Bitmap deepClone(Rectangle rect, int format)
```


Maakt een kopie van het gedeelte van deze [Bitmap](../../com.aspose.drawing/bitmap) dat wordt gedefinieerd door de [Rectangle](../../com.aspose.drawing/rectangle)-structuur en met een opgegeven `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) enumeratie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Definieert het gedeelte van deze [Bitmap](../../com.aspose.drawing/bitmap) dat gekopieerd moet worden. Coördinaten zijn relatief ten opzichte van deze [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Specificeert de `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) enumeratie voor de doel-[Bitmap](../../com.aspose.drawing/bitmap). |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The new [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### deepClone(RectangleF rect, int format) {#deepClone-com.aspose.drawing.RectangleF-int-}
```
public final Bitmap deepClone(RectangleF rect, int format)
```


Maakt een kopie van het gedeelte van deze [Bitmap](../../com.aspose.drawing/bitmap) gedefinieerd met een opgegeven [PixelFormat](../../com.aspose.drawing.imaging/pixelformat)-enumeratie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Definieert het gedeelte van deze [Bitmap](../../com.aspose.drawing/bitmap) dat gekopieerd moet worden. |
| format | int | Specificeert de [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) enumeratie voor de doel-[Bitmap](../../com.aspose.drawing/bitmap). |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### setResolution(float xDpi, float yDpi) {#setResolution-float-float-}
```
public final void setResolution(float xDpi, float yDpi)
```


Stelt de resolutie in voor deze [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xDpi | float | De horizontale resolutie, in punten per inch, van de [Bitmap](../../com.aspose.drawing/bitmap). |
| yDpi | float | De verticale resolutie, in punten per inch, van de [Bitmap](../../com.aspose.drawing/bitmap). |

### lockBits(Rectangle rect, int flags, int format) {#lockBits-com.aspose.drawing.Rectangle-int-int-}
```
public final BitmapData lockBits(Rectangle rect, int flags, int format)
```


Vergrendelt een [Bitmap](../../com.aspose.drawing/bitmap) in het systeemgeheugen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Een [Rectangle](../../com.aspose.drawing/rectangle) structuur die het gedeelte van de [Bitmap](../../com.aspose.drawing/bitmap) specificeert dat vergrendeld moet worden. |
| flags | int | Een [ImageLockMode](../../com.aspose.drawing.imaging/imagelockmode) enumeratie die het toegangsniveau (lezen/schrijven) voor de [Bitmap](../../com.aspose.drawing/bitmap) specificeert. |
| format | int | Een `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) enumeratie die het gegevensformaat van deze [Bitmap](../../com.aspose.drawing/bitmap) specificeert. |

**Returns:**
[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) - A [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) containing information about this lock operation.
### unlockBits(BitmapData bitmapData) {#unlockBits-com.aspose.drawing.imaging.BitmapData-}
```
public final void unlockBits(BitmapData bitmapData)
```


Ontgrendelt deze [Bitmap](../../com.aspose.drawing/bitmap) uit het systeemgeheugen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitmapData | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) | Een [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) die informatie over de vergrendelingsbewerking specificeert. |

### getPixel(int x, int y) {#getPixel-int-int-}
```
public final Color getPixel(int x, int y)
```


Haalt de kleur op van de opgegeven pixel in deze [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van de pixel die opgehaald moet worden. |
| y | int | De y-coördinaat van de pixel die opgehaald moet worden. |

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) structure that represents the color of the specified pixel.
### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.drawing.Color-}
```
public final void setPixel(int x, int y, Color color)
```


Stelt de kleur in van de opgegeven pixel in deze [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van de pixel die ingesteld moet worden. |
| y | int | De y-coördinaat van de pixel die ingesteld moet worden. |
| color | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color) structuur die de kleur vertegenwoordigt die aan de opgegeven pixel moet worden toegewezen. |

### readArgb32Pixels(int[] pixels) {#readArgb32Pixels-int---}
```
public final void readArgb32Pixels(int[] pixels)
```


Leest bitmap-pixels in ARGB32-formaat in de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixels | int[] | Array om bitmappixels te plaatsen. Moet voldoende capaciteit hebben. |

### writeArgb32Pixels(int[] pixels) {#writeArgb32Pixels-int---}
```
public final void writeArgb32Pixels(int[] pixels)
```


Schrijft pixels naar de bitmap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixels | int[] | Array met bronpixels in ARGB32-formaat. Moet voldoende lengte hebben. |

### makeTransparent() {#makeTransparent--}
```
public final void makeTransparent()
```


Maakt de opgegeven kleur transparant voor deze [Bitmap](../../com.aspose.drawing/bitmap).

### makeTransparent(Color transparentColor) {#makeTransparent-com.aspose.drawing.Color-}
```
public final void makeTransparent(Color transparentColor)
```


Maakt de opgegeven kleur transparant voor deze [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| transparentColor | [Color](../../com.aspose.drawing/color) | De [Color](../../com.aspose.drawing/color) structuur die de kleur vertegenwoordigt die transparant moet worden gemaakt. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


This method rotates, flips, or rotates and flips the [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rotateFlipType | int | Een [RotateFlipType](../../com.aspose.drawing/rotatefliptype) lid dat het type rotatie en omkering specificeert dat op de afbeelding moet worden toegepast. |

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

