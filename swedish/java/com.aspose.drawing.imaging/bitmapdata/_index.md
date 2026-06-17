---
title: BitmapData
second_title: Aspose.Drawing för Java API‑referens
description: Anger attributen för en bitmap-bild.
type: docs
weight: 10
url: /sv/java/com.aspose.drawing.imaging/bitmapdata/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapData
```

Anger attributen för en bitmap-bild. Klassen [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) används av metoderna `E:Bitmap.LockBits` och `M:Bitmap.UnlockBits(BitmapData)` i klassen [Bitmap](../../com.aspose.drawing/bitmap). Ej ärvd.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BitmapData()](#BitmapData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWidth()](#getWidth--) | Hämtar pixelbredden för [Bitmap](../../com.aspose.drawing/bitmap)‑objektet. |
| [setWidth(int value)](#setWidth-int-) | Anger pixelbredden för [Bitmap](../../com.aspose.drawing/bitmap)‑objektet. |
| [getHeight()](#getHeight--) | Hämtar pixelhöjden för [Bitmap](../../com.aspose.drawing/bitmap)‑objektet. |
| [setHeight(int value)](#setHeight-int-) | Anger pixelhöjden för [Bitmap](../../com.aspose.drawing/bitmap)‑objektet. |
| [getStride()](#getStride--) | Hämtar radbredden (även kallad skanningsbredd) för [Bitmap](../../com.aspose.drawing/bitmap)‑objektet. |
| [setStride(int value)](#setStride-int-) | Anger radbredden (även kallad skanningsbredd) för [Bitmap](../../com.aspose.drawing/bitmap)‑objektet. |
| [getPixelFormat()](#getPixelFormat--) | Hämtar formatet för pixelinformationen i [Bitmap](../../com.aspose.drawing/bitmap)‑objektet som returnerade detta [BitmapData](../../com.aspose.drawing.imaging/bitmapdata)‑objekt. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Anger formatet för pixelinformationen i [Bitmap](../../com.aspose.drawing/bitmap)‑objektet som returnerade detta [BitmapData](../../com.aspose.drawing.imaging/bitmapdata)‑objekt. |
| [getScan0()](#getScan0--) | Hämtar adressen till den första pixeldata i bitmapen. |
| [setScan0(int[] value)](#setScan0-int---) | Anger adressen till den första pixeldata i bitmapen. |
### BitmapData() {#BitmapData--}
```
public BitmapData()
```


### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar pixelbredden för [Bitmap](../../com.aspose.drawing/bitmap)‑objektet. Detta kan också betraktas som antalet pixlar i en skanningsrad.

**Returns:**
int - Pixelbredden för [Bitmap](../../com.aspose.drawing/bitmap) objektet.
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Ställer in pixelbredden för [Bitmap](../../com.aspose.drawing/bitmap) objektet. Detta kan också ses som antalet pixlar i en skanningsrad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | pixelbredden för [Bitmap](../../com.aspose.drawing/bitmap) objektet. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar pixelhöjden för [Bitmap](../../com.aspose.drawing/bitmap) objektet. Kallas ibland även antalet skanningsrader.

**Returns:**
int - Pixelhöjden för [Bitmap](../../com.aspose.drawing/bitmap) objektet.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Ställer in pixelhöjden för [Bitmap](../../com.aspose.drawing/bitmap) objektet. Kallas ibland även antalet skanningsrader.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | pixelhöjden för [Bitmap](../../com.aspose.drawing/bitmap) objektet. |

### getStride() {#getStride--}
```
public int getStride()
```


Hämtar radbredden (även kallad skanningsbredd) för [Bitmap](../../com.aspose.drawing/bitmap)‑objektet.

**Returns:**
int - Stride-bredden, i byte, för [Bitmap](../../com.aspose.drawing/bitmap) objektet.
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Anger radbredden (även kallad skanningsbredd) för [Bitmap](../../com.aspose.drawing/bitmap)‑objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | stride-bredden (även kallad skanningsbredd) för [Bitmap](../../com.aspose.drawing/bitmap) objektet. |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Hämtar formatet för pixelinformationen i [Bitmap](../../com.aspose.drawing/bitmap)‑objektet som returnerade detta [BitmapData](../../com.aspose.drawing.imaging/bitmapdata)‑objekt.

**Returns:**
int - En `PixelFormat`([.getPixelFormat](../../null/\#getPixelFormat)/[.setPixelFormat(int)](../../null/\#setPixelFormat-int-)) som specificerar formatet för pixelinformationen i det associerade [Bitmap](../../com.aspose.drawing/bitmap) objektet.
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Anger formatet för pixelinformationen i [Bitmap](../../com.aspose.drawing/bitmap)‑objektet som returnerade detta [BitmapData](../../com.aspose.drawing.imaging/bitmapdata)‑objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | formatet för pixelinformationen i [Bitmap](../../com.aspose.drawing/bitmap) objektet som returnerade detta [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) objekt. |

### getScan0() {#getScan0--}
```
public int[] getScan0()
```


Hämtar adressen till den första pixeldata i bitmapen. Detta kan också ses som den första skanningsraden i bitmapen.

**Returns:**
int[] - Adressen till den första pixeldata i bitmapen.
### setScan0(int[] value) {#setScan0-int---}
```
public void setScan0(int[] value)
```


Ställer in adressen till den första pixeldata i bitmapen. Detta kan också ses som den första skanningsraden i bitmapen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int[] | adressen till den första pixeldata i bitmapen. |

