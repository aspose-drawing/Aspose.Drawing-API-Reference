---
title: BitmapData
second_title: Riferimento API di Aspose.Drawing per Java
description: Specifica gli attributi di un'immagine bitmap.
type: docs
weight: 10
url: /it/java/com.aspose.drawing.imaging/bitmapdata/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapData
```

Specifica gli attributi di un'immagine bitmap. La classe [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) è utilizzata dai metodi `E:Bitmap.LockBits` e `M:Bitmap.UnlockBits(BitmapData)` della classe [Bitmap](../../com.aspose.drawing/bitmap). Non ereditabile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BitmapData()](#BitmapData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWidth()](#getWidth--) | Ottiene la larghezza in pixel dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap). |
| [setWidth(int value)](#setWidth-int-) | Imposta la larghezza in pixel dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap). |
| [getHeight()](#getHeight--) | Ottiene l'altezza in pixel dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap). |
| [setHeight(int value)](#setHeight-int-) | Imposta l'altezza in pixel dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap). |
| [getStride()](#getStride--) | Ottiene la larghezza dello stride (detta anche larghezza di scansione) dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap). |
| [setStride(int value)](#setStride-int-) | Imposta la larghezza dello stride (detta anche larghezza di scansione) dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap). |
| [getPixelFormat()](#getPixelFormat--) | Ottiene il formato delle informazioni pixel nell'oggetto [Bitmap](../../com.aspose.drawing/bitmap) che ha restituito questo oggetto [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Imposta il formato delle informazioni pixel nell'oggetto [Bitmap](../../com.aspose.drawing/bitmap) che ha restituito questo oggetto [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |
| [getScan0()](#getScan0--) | Ottiene l'indirizzo del primo dato pixel nel bitmap. |
| [setScan0(int[] value)](#setScan0-int---) | Imposta l'indirizzo del primo dato pixel nel bitmap. |
### BitmapData() {#BitmapData--}
```
public BitmapData()
```


### getWidth() {#getWidth--}
```
public int getWidth()
```


Ottiene la larghezza in pixel dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap). Questo può anche essere considerato come il numero di pixel in una singola linea di scansione.

**Returns:**
int - La larghezza in pixel dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap).
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Imposta la larghezza in pixel dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap). Questo può anche essere considerato come il numero di pixel in una singola linea di scansione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | la larghezza in pixel dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap). |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottiene l'altezza in pixel dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap). Talvolta è anche indicata come il numero di linee di scansione.

**Returns:**
int - L'altezza in pixel dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap).
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Imposta l'altezza in pixel dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap). Talvolta è anche indicata come il numero di linee di scansione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | l'altezza in pixel dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap). |

### getStride() {#getStride--}
```
public int getStride()
```


Ottiene la larghezza dello stride (detta anche larghezza di scansione) dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap).

**Returns:**
int - La larghezza di stride, in byte, dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap).
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Imposta la larghezza dello stride (detta anche larghezza di scansione) dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | la larghezza di stride (nota anche come larghezza di scansione) dell'oggetto [Bitmap](../../com.aspose.drawing/bitmap). |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Ottiene il formato delle informazioni pixel nell'oggetto [Bitmap](../../com.aspose.drawing/bitmap) che ha restituito questo oggetto [BitmapData](../../com.aspose.drawing.imaging/bitmapdata).

**Returns:**
int - Un `PixelFormat`([.getPixelFormat](../../null/\#getPixelFormat)/[.setPixelFormat(int)](../../null/\#setPixelFormat-int-)) che specifica il formato delle informazioni pixel nell'oggetto [Bitmap](../../com.aspose.drawing/bitmap) associato.
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Imposta il formato delle informazioni pixel nell'oggetto [Bitmap](../../com.aspose.drawing/bitmap) che ha restituito questo oggetto [BitmapData](../../com.aspose.drawing.imaging/bitmapdata).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | il formato delle informazioni pixel nell'oggetto [Bitmap](../../com.aspose.drawing/bitmap) che ha restituito questo oggetto [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |

### getScan0() {#getScan0--}
```
public int[] getScan0()
```


Ottiene l'indirizzo dei primi dati pixel nel bitmap. Questo può anche essere considerato come la prima linea di scansione nel bitmap.

**Returns:**
int[] - L'indirizzo dei primi dati pixel nel bitmap.
### setScan0(int[] value) {#setScan0-int---}
```
public void setScan0(int[] value)
```


Imposta l'indirizzo dei primi dati pixel nel bitmap. Questo può anche essere considerato come la prima linea di scansione nel bitmap.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int[] | l'indirizzo dei primi dati pixel nel bitmap. |

