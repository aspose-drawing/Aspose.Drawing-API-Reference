---
title: Bitmap
second_title: Aspose.Drawing för Java API‑referens
description: Innesluter en bitmap som består av pixeldata för en grafikbild och dess attribut.
type: docs
weight: 10
url: /sv/java/com.aspose.drawing/bitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public class Bitmap extends Image
```

Innesluter en bitmap, som består av pixeldata för en grafikbild och dess attribut. En [Bitmap](../../com.aspose.drawing/bitmap) är ett objekt som används för att arbeta med bilder definierade av pixeldata.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Bitmap(int width, int height)](#Bitmap-int-int-) | Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) med den angivna storleken. |
| [Bitmap(String filename)](#Bitmap-java.lang.String-) | Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) från den angivna filen. |
| [Bitmap(String filename, boolean useIcm)](#Bitmap-java.lang.String-boolean-) | Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) från den angivna filen. |
| [Bitmap(InputStream stream)](#Bitmap-java.io.InputStream-) | Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) från den angivna datastreamen. |
| [Bitmap(InputStream stream, boolean useIcm)](#Bitmap-java.io.InputStream-boolean-) | Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) från den angivna datastreamen. |
| [Bitmap(int width, int height, int format)](#Bitmap-int-int-int-) | Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) med den angivna storleken och formatet. |
| [Bitmap(int width, int height, int stride, int format, int[] data)](#Bitmap-int-int-int-int-int---) | Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) med den angivna storleken och pixeldata. |
| [Bitmap(Image original)](#Bitmap-com.aspose.drawing.Image-) | Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) från den angivna befintliga bilden. |
| [Bitmap(Image original, Size newSize)](#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-) | Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) från den angivna befintliga bilden, skalad till den angivna storleken. |
| [Bitmap(Image original, int width, int height)](#Bitmap-com.aspose.drawing.Image-int-int-) | Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) från den angivna befintliga bilden, skalad till den angivna storleken. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWidth()](#getWidth--) | Hämtar bredden, i pixlar, för denna Bitmap. |
| [getHeight()](#getHeight--) | Hämtar höjden, i pixlar, för denna Bitmap. |
| [getRawFormat()](#getRawFormat--) | Hämtar filformatet för denna [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Hämtar pixelformatet för denna [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Hämtar eller anger färgpaletten som används för denna [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Hämtar eller anger färgpaletten som används för denna [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Hämtar en array av GUID:er som representerar dimensionerna för ramar inom denna [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Hämtar ID:n för egenskapsobjekten som lagras i denna [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Hämtar alla egenskapsobjekt (metadata) som lagras i denna [Image](../../com.aspose.drawing/image). |
| [deepClone(Rectangle rect, int format)](#deepClone-com.aspose.drawing.Rectangle-int-) | Skapar en kopia av avsnittet av denna [Bitmap](../../com.aspose.drawing/bitmap) definierat av [Rectangle](../../com.aspose.drawing/rectangle)-strukturen och med ett specificerat `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat))‑enumeration. |
| [deepClone(RectangleF rect, int format)](#deepClone-com.aspose.drawing.RectangleF-int-) | Skapar en kopia av avsnittet av denna [Bitmap](../../com.aspose.drawing/bitmap) definierat med ett specificerat [PixelFormat](../../com.aspose.drawing.imaging/pixelformat)-enumeration. |
| [setResolution(float xDpi, float yDpi)](#setResolution-float-float-) | Ställer in upplösningen för denna [Bitmap](../../com.aspose.drawing/bitmap). |
| [lockBits(Rectangle rect, int flags, int format)](#lockBits-com.aspose.drawing.Rectangle-int-int-) | Låser en [Bitmap](../../com.aspose.drawing/bitmap) i systemminnet. |
| [unlockBits(BitmapData bitmapData)](#unlockBits-com.aspose.drawing.imaging.BitmapData-) | Låser upp denna [Bitmap](../../com.aspose.drawing/bitmap) från systemminnet. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Hämtar färgen på den angivna pixeln i denna [Bitmap](../../com.aspose.drawing/bitmap). |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.drawing.Color-) | Ställer in färgen på den angivna pixeln i denna [Bitmap](../../com.aspose.drawing/bitmap). |
| [readArgb32Pixels(int[] pixels)](#readArgb32Pixels-int---) | Läser bitmap-pixlar i ARGB32-format till den angivna arrayen. |
| [writeArgb32Pixels(int[] pixels)](#writeArgb32Pixels-int---) | Skriver pixlar till bitmapen. |
| [makeTransparent()](#makeTransparent--) | Gör den angivna färgen transparent för denna [Bitmap](../../com.aspose.drawing/bitmap). |
| [makeTransparent(Color transparentColor)](#makeTransparent-com.aspose.drawing.Color-) | Gör den angivna färgen transparent för denna [Bitmap](../../com.aspose.drawing/bitmap). |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Denna metod roterar, vänder eller roterar och vänder [Image](../../com.aspose.drawing/image). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Hämtar det angivna egenskapsobjektet från denna [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Tar bort det angivna egenskapsobjektet från denna [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Lagrar ett egenskapsobjekt (metadata) i denna [Image](../../com.aspose.drawing/image). |
### Bitmap(int width, int height) {#Bitmap-int-int-}
```
public Bitmap(int width, int height)
```


Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bredden, i pixlar, för den nya Bitmap. |
|  | höjd | int | Höjden, i pixlar, för den nya Bitmap. |

--------------------

Det enda stödda interna bitmap-formatet för närvarande är motsvarande `PixelFormat.Format32bppPArgb`. |

### Bitmap(String filename) {#Bitmap-java.lang.String-}
```
public Bitmap(String filename)
```


Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) från den angivna filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | java.lang.String | Namnet på bitmap-filen. |

### Bitmap(String filename, boolean useIcm) {#Bitmap-java.lang.String-boolean-}
```
public Bitmap(String filename, boolean useIcm)
```


Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) från den angivna filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | java.lang.String | Namnet på bitmap-filen. |
| useIcm | boolean | true för att använda färgkorrigering för denna [Bitmap](../../com.aspose.drawing/bitmap); annars false. |

### Bitmap(InputStream stream) {#Bitmap-java.io.InputStream-}
```
public Bitmap(InputStream stream)
```


Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) från den angivna datastreamen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Datastreamen som används för att läsa in bilden. |

### Bitmap(InputStream stream, boolean useIcm) {#Bitmap-java.io.InputStream-boolean-}
```
public Bitmap(InputStream stream, boolean useIcm)
```


Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) från den angivna datastreamen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Datastreamen som används för att läsa in bilden. |
| useIcm | boolean | `true` för att använda färgkorrigering för denna [Bitmap](../../com.aspose.drawing/bitmap); annars `false`. |

### Bitmap(int width, int height, int format) {#Bitmap-int-int-int-}
```
public Bitmap(int width, int height, int format)
```


Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) med den angivna storleken och formatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | int | Bredden, i pixlar, för den nya [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | Höjden, i pixlar, för den nya [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Den `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat))‑enumerationen för den nya [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(int width, int height, int stride, int format, int[] data) {#Bitmap-int-int-int-int-int---}
```
public Bitmap(int width, int height, int stride, int format, int[] data)
```


Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) med den angivna storleken och pixeldata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | int | Bredden, i pixlar, för den nya [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | Höjden, i pixlar, för den nya [Bitmap](../../com.aspose.drawing/bitmap). |
| radsteg | int | Byteavståndet mellan början av en rad och nästa, måste vara en multipel av fyra. |
| format | int | Den `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat))‑enumerationen för den nya [Bitmap](../../com.aspose.drawing/bitmap). |
| data | int[] | Pixeldata. |

### Bitmap(Image original) {#Bitmap-com.aspose.drawing.Image-}
```
public Bitmap(Image original)
```


Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) från den angivna befintliga bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | Den [Image](../../com.aspose.drawing/image) som används för att skapa den nya [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(Image original, Size newSize) {#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-}
```
public Bitmap(Image original, Size newSize)
```


Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) från den angivna befintliga bilden, skalad till den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | Den [Image](../../com.aspose.drawing/image) som används för att skapa den nya [Bitmap](../../com.aspose.drawing/bitmap) |
| newSize | [Size](../../com.aspose.drawing/size) | Den `Size`([Image.getSize](../../com.aspose.drawing/image\#getSize)) strukturen som representerar storleken på den nya [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(Image original, int width, int height) {#Bitmap-com.aspose.drawing.Image-int-int-}
```
public Bitmap(Image original, int width, int height)
```


Initierar en ny instans av klassen [Bitmap](../../com.aspose.drawing/bitmap) från den angivna befintliga bilden, skalad till den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | Den [Image](../../com.aspose.drawing/image) som används för att skapa den nya [Bitmap](../../com.aspose.drawing/bitmap). |
| width | int | Bredden, i pixlar, för den nya [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | Höjden, i pixlar, för den nya [Bitmap](../../com.aspose.drawing/bitmap). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bredden, i pixlar, för denna Bitmap.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar höjden, i pixlar, för denna Bitmap.

**Returns:**
int
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


Hämtar filformatet för denna [Image](../../com.aspose.drawing/image).

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Hämtar pixelformatet för denna [Image](../../com.aspose.drawing/image).

**Returns:**
int - En `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) som representerar pixelformatet för denna [Image](../../com.aspose.drawing/image).
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


Hämtar eller anger färgpaletten som används för denna [Image](../../com.aspose.drawing/image).

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


Hämtar eller anger färgpaletten som används för denna [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


Hämtar en array av GUID:er som representerar dimensionerna för ramar inom denna [Image](../../com.aspose.drawing/image).

**Returns:**
java.util.UUID[] - En array av GUID:er som specificerar dimensionerna för ramar inom denna [Image](../../com.aspose.drawing/image) från mest signifikant till minst signifikant.
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


Hämtar ID:n för egenskapsobjekten som lagras i denna [Image](../../com.aspose.drawing/image).

**Returns:**
int[] - En array av egenskaps‑ID:n, en för varje egenskapselement som lagras i denna bild.
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


Hämtar alla egenskapsobjekt (metadata) som lagras i denna [Image](../../com.aspose.drawing/image).

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] - En array av [PropertyItem](../../com.aspose.drawing.imaging/propertyitem)‑objekt, ett för varje egenskapselement som lagras i bilden.
### deepClone(Rectangle rect, int format) {#deepClone-com.aspose.drawing.Rectangle-int-}
```
public final Bitmap deepClone(Rectangle rect, int format)
```


Skapar en kopia av avsnittet av denna [Bitmap](../../com.aspose.drawing/bitmap) definierat av [Rectangle](../../com.aspose.drawing/rectangle)-strukturen och med ett specificerat `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat))‑enumeration.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Definierar den del av denna [Bitmap](../../com.aspose.drawing/bitmap) som ska kopieras. Koordinaterna är relativa till denna [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Anger `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat))‑enumerationen för destinations‑[Bitmap](../../com.aspose.drawing/bitmap). |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The new [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### deepClone(RectangleF rect, int format) {#deepClone-com.aspose.drawing.RectangleF-int-}
```
public final Bitmap deepClone(RectangleF rect, int format)
```


Skapar en kopia av avsnittet av denna [Bitmap](../../com.aspose.drawing/bitmap) definierat med ett specificerat [PixelFormat](../../com.aspose.drawing.imaging/pixelformat)-enumeration.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Definierar den del av denna [Bitmap](../../com.aspose.drawing/bitmap) som ska kopieras. |
| format | int | Anger [PixelFormat](../../com.aspose.drawing.imaging/pixelformat)‑enumerationen för destinations‑[Bitmap](../../com.aspose.drawing/bitmap). |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### setResolution(float xDpi, float yDpi) {#setResolution-float-float-}
```
public final void setResolution(float xDpi, float yDpi)
```


Ställer in upplösningen för denna [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xDpi | float | Den horisontella upplösningen, i punkter per tum, för [Bitmap](../../com.aspose.drawing/bitmap). |
| yDpi | float | Den vertikala upplösningen, i punkter per tum, för [Bitmap](../../com.aspose.drawing/bitmap). |

### lockBits(Rectangle rect, int flags, int format) {#lockBits-com.aspose.drawing.Rectangle-int-int-}
```
public final BitmapData lockBits(Rectangle rect, int flags, int format)
```


Låser en [Bitmap](../../com.aspose.drawing/bitmap) i systemminnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | En [Rectangle](../../com.aspose.drawing/rectangle)‑struktur som specificerar den del av [Bitmap](../../com.aspose.drawing/bitmap) som ska låsas. |
| flags | int | En [ImageLockMode](../../com.aspose.drawing.imaging/imagelockmode)‑enumeration som specificerar åtkomstnivån (läsa/skriva) för [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | En `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat))‑enumeration som specificerar dataformatet för denna [Bitmap](../../com.aspose.drawing/bitmap). |

**Returns:**
[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) - A [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) containing information about this lock operation.
### unlockBits(BitmapData bitmapData) {#unlockBits-com.aspose.drawing.imaging.BitmapData-}
```
public final void unlockBits(BitmapData bitmapData)
```


Låser upp denna [Bitmap](../../com.aspose.drawing/bitmap) från systemminnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitmapData | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) | Ett [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) som specificerar information om låsoperationen. |

### getPixel(int x, int y) {#getPixel-int-int-}
```
public final Color getPixel(int x, int y)
```


Hämtar färgen på den angivna pixeln i denna [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X‑koordinaten för pixeln som ska hämtas. |
| y | int | Y‑koordinaten för pixeln som ska hämtas. |

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) structure that represents the color of the specified pixel.
### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.drawing.Color-}
```
public final void setPixel(int x, int y, Color color)
```


Ställer in färgen på den angivna pixeln i denna [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X‑koordinaten för pixeln som ska sättas. |
| y | int | Y‑koordinaten för pixeln som ska sättas. |
| color | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color)‑struktur som representerar färgen som ska tilldelas den angivna pixeln. |

### readArgb32Pixels(int[] pixels) {#readArgb32Pixels-int---}
```
public final void readArgb32Pixels(int[] pixels)
```


Läser bitmap-pixlar i ARGB32-format till den angivna arrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] | Array för att placera bitmap‑pixlar. Måste ha tillräcklig kapacitet. |

### writeArgb32Pixels(int[] pixels) {#writeArgb32Pixels-int---}
```
public final void writeArgb32Pixels(int[] pixels)
```


Skriver pixlar till bitmapen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] | Array med källpixlar i ARGB32‑format. Måste ha tillräcklig längd. |

### makeTransparent() {#makeTransparent--}
```
public final void makeTransparent()
```


Gör den angivna färgen transparent för denna [Bitmap](../../com.aspose.drawing/bitmap).

### makeTransparent(Color transparentColor) {#makeTransparent-com.aspose.drawing.Color-}
```
public final void makeTransparent(Color transparentColor)
```


Gör den angivna färgen transparent för denna [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| transparentColor | [Color](../../com.aspose.drawing/color) | Den [Color](../../com.aspose.drawing/color)‑struktur som representerar färgen som ska göras transparent. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Denna metod roterar, vänder eller roterar och vänder [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int | En [RotateFlipType](../../com.aspose.drawing/rotatefliptype)‑medlem som specificerar vilken typ av rotation och vändning som ska tillämpas på bilden. |

### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


Hämtar det angivna egenskapsobjektet från denna [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propid | int | ID för egenskapselementet som ska hämtas. |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


Tar bort det angivna egenskapsobjektet från denna [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propid | int | ID för egenskapselementet som ska tas bort. |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


Lagrar ett egenskapsobjekt (metadata) i denna [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | Den [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) som ska lagras. |

