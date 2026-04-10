---
title: Bitmap
second_title: Aspose.Drawing für Java API-Referenz
description: Kapselt ein Bitmap, das aus den Pixeldaten für ein Grafikbild und dessen Attribute besteht.
type: docs
weight: 10
url: /de/java/com.aspose.drawing/bitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public class Bitmap extends Image
```

Kapselt ein Bitmap, das aus den Pixeldaten für ein Grafikbild und dessen Attribute besteht. Ein [Bitmap](../../com.aspose.drawing/bitmap) ist ein Objekt, das zum Arbeiten mit Bildern verwendet wird, die durch Pixeldaten definiert sind.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Bitmap(int width, int height)](#Bitmap-int-int-) | Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse mit der angegebenen Größe. |
| [Bitmap(String filename)](#Bitmap-java.lang.String-) | Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse aus der angegebenen Datei. |
| [Bitmap(String filename, boolean useIcm)](#Bitmap-java.lang.String-boolean-) | Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse aus der angegebenen Datei. |
| [Bitmap(InputStream stream)](#Bitmap-java.io.InputStream-) | Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse aus dem angegebenen Datenstrom. |
| [Bitmap(InputStream stream, boolean useIcm)](#Bitmap-java.io.InputStream-boolean-) | Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse aus dem angegebenen Datenstrom. |
| [Bitmap(int width, int height, int format)](#Bitmap-int-int-int-) | Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse mit der angegebenen Größe und dem Format. |
| [Bitmap(int width, int height, int stride, int format, int[] data)](#Bitmap-int-int-int-int-int---) | Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse mit der angegebenen Größe und den Pixeldaten. |
| [Bitmap(Image original)](#Bitmap-com.aspose.drawing.Image-) | Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse aus dem angegebenen vorhandenen Bild. |
| [Bitmap(Image original, Size newSize)](#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-) | Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse aus dem angegebenen vorhandenen Bild, skaliert auf die angegebene Größe. |
| [Bitmap(Image original, int width, int height)](#Bitmap-com.aspose.drawing.Image-int-int-) | Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse aus dem angegebenen vorhandenen Bild, skaliert auf die angegebene Größe. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWidth()](#getWidth--) | Gibt die Breite dieses Bitmaps in Pixeln zurück. |
| [getHeight()](#getHeight--) | Gibt die Höhe dieses Bitmaps in Pixeln zurück. |
| [getRawFormat()](#getRawFormat--) | Ermittelt das Dateiformat dieses [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Ermittelt das Pixelformat dieses [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Liest oder legt die für dieses [Image](../../com.aspose.drawing/image) verwendete Farbpalette fest. |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Liest oder legt die für dieses [Image](../../com.aspose.drawing/image) verwendete Farbpalette fest. |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Ermittelt ein Array von GUIDs, das die Abmessungen der Frames innerhalb dieses [Image](../../com.aspose.drawing/image) darstellt. |
| [getPropertyIdList()](#getPropertyIdList--) | Ermittelt die IDs der in diesem [Image](../../com.aspose.drawing/image) gespeicherten Eigenschaftselemente. |
| [getPropertyItems()](#getPropertyItems--) | Ermittelt alle Eigenschaftselemente (Metadatenstücke), die in diesem [Image](../../com.aspose.drawing/image) gespeichert sind. |
| [deepClone(Rectangle rect, int format)](#deepClone-com.aspose.drawing.Rectangle-int-) | Erstellt eine Kopie des Abschnitts dieses [Bitmap](../../com.aspose.drawing/bitmap), definiert durch die [Rectangle](../../com.aspose.drawing/rectangle)-Struktur und mit einem angegebenen `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat))-Aufzählungstyp. |
| [deepClone(RectangleF rect, int format)](#deepClone-com.aspose.drawing.RectangleF-int-) | Erstellt eine Kopie des Abschnitts dieses [Bitmap](../../com.aspose.drawing/bitmap), definiert mit einem angegebenen [PixelFormat](../../com.aspose.drawing.imaging/pixelformat)-Aufzählungstyp. |
| [setResolution(float xDpi, float yDpi)](#setResolution-float-float-) | Legt die Auflösung für dieses [Bitmap](../../com.aspose.drawing/bitmap) fest. |
| [lockBits(Rectangle rect, int flags, int format)](#lockBits-com.aspose.drawing.Rectangle-int-int-) | Sperrt ein [Bitmap](../../com.aspose.drawing/bitmap) im Systemspeicher. |
| [unlockBits(BitmapData bitmapData)](#unlockBits-com.aspose.drawing.imaging.BitmapData-) | Entsperrt dieses [Bitmap](../../com.aspose.drawing/bitmap) aus dem Systemspeicher. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Ermittelt die Farbe des angegebenen Pixels in diesem [Bitmap](../../com.aspose.drawing/bitmap). |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.drawing.Color-) | Setzt die Farbe des angegebenen Pixels in diesem [Bitmap](../../com.aspose.drawing/bitmap). |
| [readArgb32Pixels(int[] pixels)](#readArgb32Pixels-int---) | Liest Bitmap-Pixel im ARGB32-Format in das angegebene Array ein. |
| [writeArgb32Pixels(int[] pixels)](#writeArgb32Pixels-int---) | Schreibt Pixel in das Bitmap. |
| [makeTransparent()](#makeTransparent--) | Macht die angegebene Farbe für dieses [Bitmap](../../com.aspose.drawing/bitmap) transparent. |
| [makeTransparent(Color transparentColor)](#makeTransparent-com.aspose.drawing.Color-) | Macht die angegebene Farbe für dieses [Bitmap](../../com.aspose.drawing/bitmap) transparent. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Diese Methode dreht, spiegelt oder dreht und spiegelt das [Image](../../com.aspose.drawing/image). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Ermittelt das angegebene Eigenschaftselement aus diesem [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Entfernt das angegebene Eigenschaftselement aus diesem [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Speichert ein Eigenschaftselement (Metadatenstück) in diesem [Image](../../com.aspose.drawing/image). |
### Bitmap(int width, int height) {#Bitmap-int-int-}
```
public Bitmap(int width, int height)
```


Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Breite, in Pixeln, des neuen Bitmaps. |
|  | Höhe | int | Die Höhe, in Pixeln, des neuen Bitmaps. |

--------------------

Das derzeit einzige unterstützte interne Bitmap-Format entspricht `PixelFormat.Format32bppPArgb`. |

### Bitmap(String filename) {#Bitmap-java.lang.String-}
```
public Bitmap(String filename)
```


Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse aus der angegebenen Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateiname | java.lang.String | Der Name der Bitmap-Datei. |

### Bitmap(String filename, boolean useIcm) {#Bitmap-java.lang.String-boolean-}
```
public Bitmap(String filename, boolean useIcm)
```


Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse aus der angegebenen Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateiname | java.lang.String | Der Name der Bitmap-Datei. |
| useIcm | boolean | true, um Farbkorrektur für dieses [Bitmap](../../com.aspose.drawing/bitmap) zu verwenden; andernfalls false. |

### Bitmap(InputStream stream) {#Bitmap-java.io.InputStream-}
```
public Bitmap(InputStream stream)
```


Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse aus dem angegebenen Datenstrom.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Datenstrom, der zum Laden des Bildes verwendet wird. |

### Bitmap(InputStream stream, boolean useIcm) {#Bitmap-java.io.InputStream-boolean-}
```
public Bitmap(InputStream stream, boolean useIcm)
```


Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse aus dem angegebenen Datenstrom.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Datenstrom, der zum Laden des Bildes verwendet wird. |
| useIcm | boolean | `true`, um Farbkorrektur für dieses [Bitmap](../../com.aspose.drawing/bitmap) zu verwenden; andernfalls `false`. |

### Bitmap(int width, int height, int format) {#Bitmap-int-int-int-}
```
public Bitmap(int width, int height, int format)
```


Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse mit der angegebenen Größe und dem Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | int | Die Breite, in Pixeln, des neuen [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | Die Höhe, in Pixeln, des neuen [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Die `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat))-Aufzählung für das neue [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(int width, int height, int stride, int format, int[] data) {#Bitmap-int-int-int-int-int---}
```
public Bitmap(int width, int height, int stride, int format, int[] data)
```


Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse mit der angegebenen Größe und den Pixeldaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | int | Die Breite, in Pixeln, des neuen [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | Die Höhe, in Pixeln, des neuen [Bitmap](../../com.aspose.drawing/bitmap). |
| Stride | int | Der Byte-Offset zwischen dem Beginn einer Scanzeile und der nächsten, muss ein Vielfaches von vier sein. |
| format | int | Die `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat))-Aufzählung für das neue [Bitmap](../../com.aspose.drawing/bitmap). |
| Daten | int[] | Die Pixeldaten. |

### Bitmap(Image original) {#Bitmap-com.aspose.drawing.Image-}
```
public Bitmap(Image original)
```


Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse aus dem angegebenen vorhandenen Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | Das [Image](../../com.aspose.drawing/image), aus dem das neue [Bitmap](../../com.aspose.drawing/bitmap) erstellt wird. |

### Bitmap(Image original, Size newSize) {#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-}
```
public Bitmap(Image original, Size newSize)
```


Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse aus dem angegebenen vorhandenen Bild, skaliert auf die angegebene Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | Das [Image](../../com.aspose.drawing/image), aus dem das neue [Bitmap](../../com.aspose.drawing/bitmap) erstellt wird |
| newSize | [Size](../../com.aspose.drawing/size) | Die `Size`([Image.getSize](../../com.aspose.drawing/image\#getSize)) Struktur, die die Größe des neuen [Bitmap](../../com.aspose.drawing/bitmap) darstellt. |

### Bitmap(Image original, int width, int height) {#Bitmap-com.aspose.drawing.Image-int-int-}
```
public Bitmap(Image original, int width, int height)
```


Initialisiert eine neue Instanz der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse aus dem angegebenen vorhandenen Bild, skaliert auf die angegebene Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | Das [Image](../../com.aspose.drawing/image), aus dem das neue [Bitmap](../../com.aspose.drawing/bitmap) erstellt wird. |
| width | int | Die Breite, in Pixeln, des neuen [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | Die Höhe, in Pixeln, des neuen [Bitmap](../../com.aspose.drawing/bitmap). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Gibt die Breite dieses Bitmaps in Pixeln zurück.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gibt die Höhe dieses Bitmaps in Pixeln zurück.

**Returns:**
int
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


Ermittelt das Dateiformat dieses [Image](../../com.aspose.drawing/image).

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Ermittelt das Pixelformat dieses [Image](../../com.aspose.drawing/image).

**Returns:**
int – Ein `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) das das Pixel-Format für dieses [Image](../../com.aspose.drawing/image) darstellt.
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


Liest oder legt die für dieses [Image](../../com.aspose.drawing/image) verwendete Farbpalette fest.

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


Liest oder legt die für dieses [Image](../../com.aspose.drawing/image) verwendete Farbpalette fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


Ermittelt ein Array von GUIDs, das die Abmessungen der Frames innerhalb dieses [Image](../../com.aspose.drawing/image) darstellt.

**Returns:**
java.util.UUID[] – Ein Array von GUIDs, das die Abmessungen der Frames innerhalb dieses [Image](../../com.aspose.drawing/image) von höchstwertig zu niederwertig angibt.
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


Ermittelt die IDs der in diesem [Image](../../com.aspose.drawing/image) gespeicherten Eigenschaftselemente.

**Returns:**
int[] – Ein Array der Eigenschafts-IDs, jeweils eine für jedes in diesem Bild gespeicherte Eigenschaftselement.
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


Ermittelt alle Eigenschaftselemente (Metadatenstücke), die in diesem [Image](../../com.aspose.drawing/image) gespeichert sind.

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] – Ein Array von [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) Objekten, jeweils eines für jedes in dem Bild gespeicherte Eigenschaftselement.
### deepClone(Rectangle rect, int format) {#deepClone-com.aspose.drawing.Rectangle-int-}
```
public final Bitmap deepClone(Rectangle rect, int format)
```


Erstellt eine Kopie des Abschnitts dieses [Bitmap](../../com.aspose.drawing/bitmap), definiert durch die [Rectangle](../../com.aspose.drawing/rectangle)-Struktur und mit einem angegebenen `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat))-Aufzählungstyp.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Definiert den Teil dieses [Bitmap](../../com.aspose.drawing/bitmap), der kopiert werden soll. Die Koordinaten sind relativ zu diesem [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Gibt die `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) Aufzählung für das Ziel-[Bitmap](../../com.aspose.drawing/bitmap) an. |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The new [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### deepClone(RectangleF rect, int format) {#deepClone-com.aspose.drawing.RectangleF-int-}
```
public final Bitmap deepClone(RectangleF rect, int format)
```


Erstellt eine Kopie des Abschnitts dieses [Bitmap](../../com.aspose.drawing/bitmap), definiert mit einem angegebenen [PixelFormat](../../com.aspose.drawing.imaging/pixelformat)-Aufzählungstyp.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Definiert den Teil dieses [Bitmap](../../com.aspose.drawing/bitmap), der kopiert werden soll. |
| format | int | Gibt die [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) Aufzählung für das Ziel-[Bitmap](../../com.aspose.drawing/bitmap) an. |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### setResolution(float xDpi, float yDpi) {#setResolution-float-float-}
```
public final void setResolution(float xDpi, float yDpi)
```


Legt die Auflösung für dieses [Bitmap](../../com.aspose.drawing/bitmap) fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xDpi | float | Die horizontale Auflösung in Punkten pro Zoll des [Bitmap](../../com.aspose.drawing/bitmap). |
| yDpi | float | Die vertikale Auflösung in Punkten pro Zoll des [Bitmap](../../com.aspose.drawing/bitmap). |

### lockBits(Rectangle rect, int flags, int format) {#lockBits-com.aspose.drawing.Rectangle-int-int-}
```
public final BitmapData lockBits(Rectangle rect, int flags, int format)
```


Sperrt ein [Bitmap](../../com.aspose.drawing/bitmap) im Systemspeicher.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Eine [Rectangle](../../com.aspose.drawing/rectangle) Struktur, die den Teil des [Bitmap](../../com.aspose.drawing/bitmap) zum Sperren angibt. |
| flags | int | Eine [ImageLockMode](../../com.aspose.drawing.imaging/imagelockmode) Aufzählung, die die Zugriffsebene (Lesen/Schreiben) für das [Bitmap](../../com.aspose.drawing/bitmap) angibt. |
| format | int | Eine `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) Aufzählung, die das Datenformat dieses [Bitmap](../../com.aspose.drawing/bitmap) angibt. |

**Returns:**
[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) - A [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) containing information about this lock operation.
### unlockBits(BitmapData bitmapData) {#unlockBits-com.aspose.drawing.imaging.BitmapData-}
```
public final void unlockBits(BitmapData bitmapData)
```


Entsperrt dieses [Bitmap](../../com.aspose.drawing/bitmap) aus dem Systemspeicher.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitmapData | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) | Ein [BitmapData](../../com.aspose.drawing.imaging/bitmapdata), das Informationen über die Sperroperation angibt. |

### getPixel(int x, int y) {#getPixel-int-int-}
```
public final Color getPixel(int x, int y)
```


Ermittelt die Farbe des angegebenen Pixels in diesem [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des abzurufenden Pixels. |
| y | int | Die y-Koordinate des abzurufenden Pixels. |

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) structure that represents the color of the specified pixel.
### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.drawing.Color-}
```
public final void setPixel(int x, int y, Color color)
```


Setzt die Farbe des angegebenen Pixels in diesem [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des zu setzenden Pixels. |
| y | int | Die y-Koordinate des zu setzenden Pixels. |
| color | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color) Struktur, die die Farbe darstellt, die dem angegebenen Pixel zugewiesen wird. |

### readArgb32Pixels(int[] pixels) {#readArgb32Pixels-int---}
```
public final void readArgb32Pixels(int[] pixels)
```


Liest Bitmap-Pixel im ARGB32-Format in das angegebene Array ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int[] | Array zum Platzieren von Bitmap-Pixeln. Muss ausreichende Kapazität besitzen. |

### writeArgb32Pixels(int[] pixels) {#writeArgb32Pixels-int---}
```
public final void writeArgb32Pixels(int[] pixels)
```


Schreibt Pixel in das Bitmap.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int[] | Array mit Quellpixeln im ARGB32-Format. Muss ausreichende Länge besitzen. |

### makeTransparent() {#makeTransparent--}
```
public final void makeTransparent()
```


Macht die angegebene Farbe für dieses [Bitmap](../../com.aspose.drawing/bitmap) transparent.

### makeTransparent(Color transparentColor) {#makeTransparent-com.aspose.drawing.Color-}
```
public final void makeTransparent(Color transparentColor)
```


Macht die angegebene Farbe für dieses [Bitmap](../../com.aspose.drawing/bitmap) transparent.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| transparentColor | [Color](../../com.aspose.drawing/color) | Die [Color](../../com.aspose.drawing/color) Struktur, die die Farbe darstellt, die transparent gemacht werden soll. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Diese Methode dreht, spiegelt oder dreht und spiegelt das [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int | Ein [RotateFlipType](../../com.aspose.drawing/rotatefliptype) Mitglied, das den Typ der Rotation und Spiegelung angibt, die auf das Bild angewendet werden soll. |

### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


Ermittelt das angegebene Eigenschaftselement aus diesem [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propid | int | Die ID des abzurufenden Property‑Elements. |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


Entfernt das angegebene Eigenschaftselement aus diesem [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propid | int | Die ID des zu entfernenden Property‑Elements. |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


Speichert ein Eigenschaftselement (Metadatenstück) in diesem [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | Das [PropertyItem](../../com.aspose.drawing.imaging/propertyitem), das gespeichert werden soll. |

