---
title: BitmapData
second_title: Aspose.Drawing für Java API-Referenz
description: Gibt die Attribute eines Bitmap-Bildes an.
type: docs
weight: 10
url: /de/java/com.aspose.drawing.imaging/bitmapdata/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapData
```

Gibt die Attribute eines Bitmap-Bildes an. Die [BitmapData](../../com.aspose.drawing.imaging/bitmapdata)-Klasse wird von den Methoden `E:Bitmap.LockBits` und `M:Bitmap.UnlockBits(BitmapData)` der [Bitmap](../../com.aspose.drawing/bitmap)-Klasse verwendet. Nicht vererbbar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BitmapData()](#BitmapData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWidth()](#getWidth--) | Liest die Pixelbreite des [Bitmap](../../com.aspose.drawing/bitmap)-Objekts. |
| [setWidth(int value)](#setWidth-int-) | Legt die Pixelbreite des [Bitmap](../../com.aspose.drawing/bitmap)-Objekts fest. |
| [getHeight()](#getHeight--) | Liest die Pixelhöhe des [Bitmap](../../com.aspose.drawing/bitmap)-Objekts. |
| [setHeight(int value)](#setHeight-int-) | Legt die Pixelhöhe des [Bitmap](../../com.aspose.drawing/bitmap)-Objekts fest. |
| [getStride()](#getStride--) | Liest die Stride-Breite (auch Scan-Breite genannt) des [Bitmap](../../com.aspose.drawing/bitmap)-Objekts. |
| [setStride(int value)](#setStride-int-) | Legt die Stride-Breite (auch Scan-Breite genannt) des [Bitmap](../../com.aspose.drawing/bitmap)-Objekts fest. |
| [getPixelFormat()](#getPixelFormat--) | Liest das Format der Pixelinformationen im [Bitmap](../../com.aspose.drawing/bitmap)-Objekt, das dieses [BitmapData](../../com.aspose.drawing.imaging/bitmapdata)-Objekt zurückgegeben hat. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Legt das Format der Pixelinformationen im [Bitmap](../../com.aspose.drawing/bitmap)-Objekt fest, das dieses [BitmapData](../../com.aspose.drawing.imaging/bitmapdata)-Objekt zurückgegeben hat. |
| [getScan0()](#getScan0--) | Liest die Adresse der ersten Pixeldaten im Bitmap. |
| [setScan0(int[] value)](#setScan0-int---) | Legt die Adresse der ersten Pixeldaten im Bitmap fest. |
### BitmapData() {#BitmapData--}
```
public BitmapData()
```


### getWidth() {#getWidth--}
```
public int getWidth()
```


Liest die Pixelbreite des [Bitmap](../../com.aspose.drawing/bitmap)-Objekts. Dies kann auch als die Anzahl der Pixel in einer Scanzeile verstanden werden.

**Returns:**
int - Die Pixelbreite des [Bitmap](../../com.aspose.drawing/bitmap) Objekts.
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Setzt die Pixelbreite des [Bitmap](../../com.aspose.drawing/bitmap) Objekts. Dies kann auch als die Anzahl der Pixel in einer Scanzeile verstanden werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | die Pixelbreite des [Bitmap](../../com.aspose.drawing/bitmap) Objekts. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Liest die Pixelhöhe des [Bitmap](../../com.aspose.drawing/bitmap) Objekts. Wird auch manchmal als die Anzahl der Scanzeilen bezeichnet.

**Returns:**
int - Die Pixelhöhe des [Bitmap](../../com.aspose.drawing/bitmap) Objekts.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Setzt die Pixelhöhe des [Bitmap](../../com.aspose.drawing/bitmap) Objekts. Wird auch manchmal als die Anzahl der Scanzeilen bezeichnet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | die Pixelhöhe des [Bitmap](../../com.aspose.drawing/bitmap) Objekts. |

### getStride() {#getStride--}
```
public int getStride()
```


Liest die Stride-Breite (auch Scan-Breite genannt) des [Bitmap](../../com.aspose.drawing/bitmap)-Objekts.

**Returns:**
int - Die Zeilenbreite, in Bytes, des [Bitmap](../../com.aspose.drawing/bitmap) Objekts.
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Legt die Stride-Breite (auch Scan-Breite genannt) des [Bitmap](../../com.aspose.drawing/bitmap)-Objekts fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | die Zeilenbreite (auch Scanbreite genannt) des [Bitmap](../../com.aspose.drawing/bitmap) Objekts. |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Liest das Format der Pixelinformationen im [Bitmap](../../com.aspose.drawing/bitmap)-Objekt, das dieses [BitmapData](../../com.aspose.drawing.imaging/bitmapdata)-Objekt zurückgegeben hat.

**Returns:**
int - Ein `PixelFormat`([.getPixelFormat](../../null/\#getPixelFormat)/[.setPixelFormat(int)](../../null/\#setPixelFormat-int-)), das das Format der Pixelinformationen im zugehörigen [Bitmap](../../com.aspose.drawing/bitmap) Objekt spezifiziert.
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Legt das Format der Pixelinformationen im [Bitmap](../../com.aspose.drawing/bitmap)-Objekt fest, das dieses [BitmapData](../../com.aspose.drawing.imaging/bitmapdata)-Objekt zurückgegeben hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | das Format der Pixelinformationen im [Bitmap](../../com.aspose.drawing/bitmap) Objekt, das dieses [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) Objekt zurückgegeben hat. |

### getScan0() {#getScan0--}
```
public int[] getScan0()
```


Liest die Adresse der ersten Pixeldaten im Bitmap. Dies kann auch als die erste Scanzeile im Bitmap betrachtet werden.

**Returns:**
int[] - Die Adresse der ersten Pixeldaten im Bitmap.
### setScan0(int[] value) {#setScan0-int---}
```
public void setScan0(int[] value)
```


Setzt die Adresse der ersten Pixeldaten im Bitmap. Dies kann auch als die erste Scanzeile im Bitmap betrachtet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int[] | die Adresse der ersten Pixeldaten im Bitmap. |

