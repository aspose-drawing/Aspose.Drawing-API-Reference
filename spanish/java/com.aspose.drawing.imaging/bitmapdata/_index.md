---
title: BitmapData
second_title: Referencia de la API de Aspose.Drawing para Java
description: Especifica los atributos de una imagen bitmap.
type: docs
weight: 10
url: /es/java/com.aspose.drawing.imaging/bitmapdata/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapData
```

Especifica los atributos de una imagen bitmap. La clase [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) es utilizada por los métodos `E:Bitmap.LockBits` y `M:Bitmap.UnlockBits(BitmapData)` de la clase [Bitmap](../../com.aspose.drawing/bitmap). No heredable.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BitmapData()](#BitmapData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getWidth()](#getWidth--) | Obtiene el ancho en píxeles del objeto [Bitmap](../../com.aspose.drawing/bitmap). |
| [setWidth(int value)](#setWidth-int-) | Establece el ancho en píxeles del objeto [Bitmap](../../com.aspose.drawing/bitmap). |
| [getHeight()](#getHeight--) | Obtiene la altura en píxeles del objeto [Bitmap](../../com.aspose.drawing/bitmap). |
| [setHeight(int value)](#setHeight-int-) | Establece la altura en píxeles del objeto [Bitmap](../../com.aspose.drawing/bitmap). |
| [getStride()](#getStride--) | Obtiene el ancho de paso (también llamado ancho de escaneo) del objeto [Bitmap](../../com.aspose.drawing/bitmap). |
| [setStride(int value)](#setStride-int-) | Establece el ancho de paso (también llamado ancho de escaneo) del objeto [Bitmap](../../com.aspose.drawing/bitmap). |
| [getPixelFormat()](#getPixelFormat--) | Obtiene el formato de la información de píxeles en el objeto [Bitmap](../../com.aspose.drawing/bitmap) que devolvió este objeto [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Establece el formato de la información de píxeles en el objeto [Bitmap](../../com.aspose.drawing/bitmap) que devolvió este objeto [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |
| [getScan0()](#getScan0--) | Obtiene la dirección del primer dato de píxel en el bitmap. |
| [setScan0(int[] value)](#setScan0-int---) | Establece la dirección del primer dato de píxel en el bitmap. |
### BitmapData() {#BitmapData--}
```
public BitmapData()
```


### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho en píxeles del objeto [Bitmap](../../com.aspose.drawing/bitmap). Esto también puede considerarse como el número de píxeles en una línea de escaneo.

**Returns:**
int - El ancho de píxel del objeto [Bitmap](../../com.aspose.drawing/bitmap).
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Establece el ancho de píxel del objeto [Bitmap](../../com.aspose.drawing/bitmap). Esto también puede considerarse como el número de píxeles en una línea de escaneo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | el ancho de píxel del objeto [Bitmap](../../com.aspose.drawing/bitmap). |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene el alto de píxel del objeto [Bitmap](../../com.aspose.drawing/bitmap). También a veces se refiere como el número de líneas de escaneo.

**Returns:**
int - El alto de píxel del objeto [Bitmap](../../com.aspose.drawing/bitmap).
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Establece el alto de píxel del objeto [Bitmap](../../com.aspose.drawing/bitmap). También a veces se refiere como el número de líneas de escaneo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | el alto de píxel del objeto [Bitmap](../../com.aspose.drawing/bitmap). |

### getStride() {#getStride--}
```
public int getStride()
```


Obtiene el ancho de paso (también llamado ancho de escaneo) del objeto [Bitmap](../../com.aspose.drawing/bitmap).

**Returns:**
int - El ancho de paso (stride), en bytes, del objeto [Bitmap](../../com.aspose.drawing/bitmap).
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Establece el ancho de paso (también llamado ancho de escaneo) del objeto [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | el ancho de paso (también llamado ancho de escaneo) del objeto [Bitmap](../../com.aspose.drawing/bitmap). |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Obtiene el formato de la información de píxeles en el objeto [Bitmap](../../com.aspose.drawing/bitmap) que devolvió este objeto [BitmapData](../../com.aspose.drawing.imaging/bitmapdata).

**Returns:**
int - Un `PixelFormat`([.getPixelFormat](../../null/\#getPixelFormat)/[.setPixelFormat(int)](../../null/\#setPixelFormat-int-)) que especifica el formato de la información de píxeles en el objeto [Bitmap](../../com.aspose.drawing/bitmap) asociado.
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Establece el formato de la información de píxeles en el objeto [Bitmap](../../com.aspose.drawing/bitmap) que devolvió este objeto [BitmapData](../../com.aspose.drawing.imaging/bitmapdata).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | el formato de la información de píxeles en el objeto [Bitmap](../../com.aspose.drawing/bitmap) que devolvió este objeto [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |

### getScan0() {#getScan0--}
```
public int[] getScan0()
```


Obtiene la dirección del primer dato de píxel en el mapa de bits. Esto también puede considerarse como la primera línea de escaneo en el mapa de bits.

**Returns:**
int[] - La dirección del primer dato de píxel en el mapa de bits.
### setScan0(int[] value) {#setScan0-int---}
```
public void setScan0(int[] value)
```


Establece la dirección del primer dato de píxel en el mapa de bits. Esto también puede considerarse como la primera línea de escaneo en el mapa de bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int[] | la dirección del primer dato de píxel en el mapa de bits. |

