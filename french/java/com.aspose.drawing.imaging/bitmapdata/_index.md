---
title: BitmapData
second_title: Référence de l'API Aspose.Drawing pour Java
description: Spécifie les attributs d'une image bitmap.
type: docs
weight: 10
url: /fr/java/com.aspose.drawing.imaging/bitmapdata/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapData
```

Spécifie les attributs d'une image bitmap. La classe [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) est utilisée par les méthodes `E:Bitmap.LockBits` et `M:Bitmap.UnlockBits(BitmapData)` de la classe [Bitmap](../../com.aspose.drawing/bitmap). Non héritable.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BitmapData()](#BitmapData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Obtient la largeur en pixels de l'objet [Bitmap](../../com.aspose.drawing/bitmap). |
| [setWidth(int value)](#setWidth-int-) | Définit la largeur en pixels de l'objet [Bitmap](../../com.aspose.drawing/bitmap). |
| [getHeight()](#getHeight--) | Obtient la hauteur en pixels de l'objet [Bitmap](../../com.aspose.drawing/bitmap). |
| [setHeight(int value)](#setHeight-int-) | Définit la hauteur en pixels de l'objet [Bitmap](../../com.aspose.drawing/bitmap). |
| [getStride()](#getStride--) | Obtient la largeur du pas (également appelée largeur de balayage) de l'objet [Bitmap](../../com.aspose.drawing/bitmap). |
| [setStride(int value)](#setStride-int-) | Définit la largeur du pas (également appelée largeur de balayage) de l'objet [Bitmap](../../com.aspose.drawing/bitmap). |
| [getPixelFormat()](#getPixelFormat--) | Obtient le format des informations de pixel dans l'objet [Bitmap](../../com.aspose.drawing/bitmap) qui a renvoyé cet objet [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Définit le format des informations de pixel dans l'objet [Bitmap](../../com.aspose.drawing/bitmap) qui a renvoyé cet objet [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |
| [getScan0()](#getScan0--) | Obtient l'adresse des premières données de pixel dans le bitmap. |
| [setScan0(int[] value)](#setScan0-int---) | Définit l'adresse des premières données de pixel dans le bitmap. |
### BitmapData() {#BitmapData--}
```
public BitmapData()
```


### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur en pixels de l'objet [Bitmap](../../com.aspose.drawing/bitmap). Cela peut également être considéré comme le nombre de pixels dans une ligne de balayage.

**Returns:**
int - La largeur en pixels de l'objet [Bitmap](../../com.aspose.drawing/bitmap).
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Définit la largeur en pixels de l'objet [Bitmap](../../com.aspose.drawing/bitmap). Cela peut également être considéré comme le nombre de pixels sur une ligne de numérisation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | la largeur en pixels de l'objet [Bitmap](../../com.aspose.drawing/bitmap). |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient la hauteur en pixels de l'objet [Bitmap](../../com.aspose.drawing/bitmap). Parfois également appelée le nombre de lignes de numérisation.

**Returns:**
int - La hauteur en pixels de l'objet [Bitmap](../../com.aspose.drawing/bitmap).
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Définit la hauteur en pixels de l'objet [Bitmap](../../com.aspose.drawing/bitmap). Parfois également appelée le nombre de lignes de numérisation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | la hauteur en pixels de l'objet [Bitmap](../../com.aspose.drawing/bitmap). |

### getStride() {#getStride--}
```
public int getStride()
```


Obtient la largeur du pas (également appelée largeur de balayage) de l'objet [Bitmap](../../com.aspose.drawing/bitmap).

**Returns:**
int - La largeur du pas, en octets, de l'objet [Bitmap](../../com.aspose.drawing/bitmap).
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Définit la largeur du pas (également appelée largeur de balayage) de l'objet [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | la largeur du pas (également appelée largeur de numérisation) de l'objet [Bitmap](../../com.aspose.drawing/bitmap). |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Obtient le format des informations de pixel dans l'objet [Bitmap](../../com.aspose.drawing/bitmap) qui a renvoyé cet objet [BitmapData](../../com.aspose.drawing.imaging/bitmapdata).

**Returns:**
int - Un `PixelFormat`([.getPixelFormat](../../null/\#getPixelFormat)/[.setPixelFormat(int)](../../null/\#setPixelFormat-int-)) qui spécifie le format des informations de pixel dans l'objet [Bitmap](../../com.aspose.drawing/bitmap) associé.
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Définit le format des informations de pixel dans l'objet [Bitmap](../../com.aspose.drawing/bitmap) qui a renvoyé cet objet [BitmapData](../../com.aspose.drawing.imaging/bitmapdata).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | le format des informations de pixel dans l'objet [Bitmap](../../com.aspose.drawing/bitmap) qui a renvoyé cet objet [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |

### getScan0() {#getScan0--}
```
public int[] getScan0()
```


Obtient l'adresse des premières données de pixel dans le bitmap. Cela peut également être considéré comme la première ligne de numérisation du bitmap.

**Returns:**
int[] - L'adresse des premières données de pixel dans le bitmap.
### setScan0(int[] value) {#setScan0-int---}
```
public void setScan0(int[] value)
```


Définit l'adresse des premières données de pixel dans le bitmap. Cela peut également être considéré comme la première ligne de numérisation du bitmap.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int[] | l'adresse des premières données de pixel dans le bitmap. |

