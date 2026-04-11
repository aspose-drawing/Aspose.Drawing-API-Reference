---
title: BitmapData
second_title: Aspose.Drawing voor Java API-referentie
description: Specificeert de attributen van een bitmapafbeelding.
type: docs
weight: 10
url: /nl/java/com.aspose.drawing.imaging/bitmapdata/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapData
```

Specificeert de attributen van een bitmap‑afbeelding. De [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) klasse wordt gebruikt door de `E:Bitmap.LockBits`‑ en `M:Bitmap.UnlockBits(BitmapData)`‑methoden van de [Bitmap](../../com.aspose.drawing/bitmap) klasse. Niet erfbaar.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [BitmapData()](#BitmapData--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getWidth()](#getWidth--) | Haalt de pixelbreedte van het [Bitmap](../../com.aspose.drawing/bitmap) object op. |
| [setWidth(int value)](#setWidth-int-) | Stelt de pixelbreedte van het [Bitmap](../../com.aspose.drawing/bitmap) object in. |
| [getHeight()](#getHeight--) | Haalt de pixelhoogte van het [Bitmap](../../com.aspose.drawing/bitmap) object op. |
| [setHeight(int value)](#setHeight-int-) | Stelt de pixelhoogte van het [Bitmap](../../com.aspose.drawing/bitmap) object in. |
| [getStride()](#getStride--) | Haalt de stride‑breedte (ook wel scan‑breedte genoemd) van het [Bitmap](../../com.aspose.drawing/bitmap) object op. |
| [setStride(int value)](#setStride-int-) | Stelt de stride‑breedte (ook wel scan‑breedte genoemd) van het [Bitmap](../../com.aspose.drawing/bitmap) object in. |
| [getPixelFormat()](#getPixelFormat--) | Haalt het formaat van de pixelinformatie in het [Bitmap](../../com.aspose.drawing/bitmap) object op dat dit [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) object heeft geretourneerd. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Stelt het formaat van de pixelinformatie in het [Bitmap](../../com.aspose.drawing/bitmap) object in dat dit [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) object heeft geretourneerd. |
| [getScan0()](#getScan0--) | Haalt het adres van de eerste pixelgegevens in de bitmap op. |
| [setScan0(int[] value)](#setScan0-int---) | Stelt het adres van de eerste pixelgegevens in de bitmap in. |
### BitmapData() {#BitmapData--}
```
public BitmapData()
```


### getWidth() {#getWidth--}
```
public int getWidth()
```


Haalt de pixelbreedte van het [Bitmap](../../com.aspose.drawing/bitmap) object op. Dit kan ook worden gezien als het aantal pixels in één scan‑lijn.

**Returns:**
int - De pixelbreedte van het [Bitmap](../../com.aspose.drawing/bitmap) object.
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Stelt de pixelbreedte van het [Bitmap](../../com.aspose.drawing/bitmap) object in. Dit kan ook worden opgevat als het aantal pixels in één scanlijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | de pixelbreedte van het [Bitmap](../../com.aspose.drawing/bitmap) object. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Haalt de pixelhoogte van het [Bitmap](../../com.aspose.drawing/bitmap) object op. Wordt soms ook aangeduid als het aantal scanlijnen.

**Returns:**
int - De pixelhoogte van het [Bitmap](../../com.aspose.drawing/bitmap) object.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Stelt de pixelhoogte van het [Bitmap](../../com.aspose.drawing/bitmap) object in. Wordt soms ook aangeduid als het aantal scanlijnen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | de pixelhoogte van het [Bitmap](../../com.aspose.drawing/bitmap) object. |

### getStride() {#getStride--}
```
public int getStride()
```


Haalt de stride‑breedte (ook wel scan‑breedte genoemd) van het [Bitmap](../../com.aspose.drawing/bitmap) object op.

**Returns:**
int - De stride-breedte, in bytes, van het [Bitmap](../../com.aspose.drawing/bitmap) object.
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Stelt de stride‑breedte (ook wel scan‑breedte genoemd) van het [Bitmap](../../com.aspose.drawing/bitmap) object in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | de stride-breedte (ook wel scanbreedte genoemd) van het [Bitmap](../../com.aspose.drawing/bitmap) object. |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Haalt het formaat van de pixelinformatie in het [Bitmap](../../com.aspose.drawing/bitmap) object op dat dit [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) object heeft geretourneerd.

**Returns:**
int - Een `PixelFormat`([.getPixelFormat](../../null/\#getPixelFormat)/[.setPixelFormat(int)](../../null/\#setPixelFormat-int-)) die het formaat van de pixelinformatie in het bijbehorende [Bitmap](../../com.aspose.drawing/bitmap) object specificeert.
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Stelt het formaat van de pixelinformatie in het [Bitmap](../../com.aspose.drawing/bitmap) object in dat dit [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) object heeft geretourneerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | het formaat van de pixelinformatie in het [Bitmap](../../com.aspose.drawing/bitmap) object dat dit [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) object retourneerde. |

### getScan0() {#getScan0--}
```
public int[] getScan0()
```


Haalt het adres van de eerste pixelgegevens in de bitmap op. Dit kan ook worden opgevat als de eerste scanlijn in de bitmap.

**Returns:**
int[] - Het adres van de eerste pixelgegevens in de bitmap.
### setScan0(int[] value) {#setScan0-int---}
```
public void setScan0(int[] value)
```


Stelt het adres van de eerste pixelgegevens in de bitmap in. Dit kan ook worden opgevat als de eerste scanlijn in de bitmap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int[] | het adres van de eerste pixelgegevens in de bitmap. |

