---
title: TextureBrush
second_title: Aspose.Drawing för Java API‑referens
description: Varje egenskap i klassen TextureBrush är ett Brush‑objekt som använder en bild för att fylla insidan av en form.
type: docs
weight: 53
url: /sv/java/com.aspose.drawing/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class TextureBrush extends Brush
```

Varje egenskap i klassen TextureBrush är ett Brush-objekt som använder en bild för att fylla insidan av en form. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TextureBrush(Image bitmap)](#TextureBrush-com.aspose.drawing.Image-) | Initierar en ny instans av klassen [TextureBrush](../../com.aspose.drawing/texturebrush) som använder den angivna bilden. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.drawing.Image-int-) | Initierar en ny instans av klassen [TextureBrush](../../com.aspose.drawing/texturebrush) som använder den angivna bilden och omslagsläget. |
| [TextureBrush(Image image, int wrapMode, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-) | Initierar en ny instans av klassen [TextureBrush](../../com.aspose.drawing/texturebrush) som använder den angivna bilden, omslagsläget och den avgränsande rektangeln. |
| [TextureBrush(Image image, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-) | Initierar en ny instans av klassen [TextureBrush](../../com.aspose.drawing/texturebrush) som använder den angivna bilden och den avgränsande rektangeln. |
| [TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-) | Initierar en ny instans av klassen [TextureBrush](../../com.aspose.drawing/texturebrush) som använder den angivna bilden, den avgränsande rektangeln och bildattributen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getImage()](#getImage--) | Hämtar Image-objektet som är associerat med detta TextureBrush-objekt. |
| [getTransform()](#getTransform--) | Hämtar en kopia av Matrix-objektet som definierar en lokal geometrisk transformation för bilden som är associerad med detta TextureBrush-objekt. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Ställer in en kopia av Matrix-objektet som definierar en lokal geometrisk transformation för bilden som är associerad med detta TextureBrush-objekt. |
| [getWrapMode()](#getWrapMode--) | Hämtar en WrapMode‑enumeration som anger omslagsläget för detta TextureBrush-objekt. |
| [setWrapMode(int value)](#setWrapMode-int-) | Ställer in en WrapMode‑enumeration som anger omslagsläget för detta TextureBrush-objekt. |
| [deepClone()](#deepClone--) | Skapar en exakt kopia av detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt. |
| [resetTransform()](#resetTransform--) | Återställer Transform‑egenskapen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt till identitet. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Multiplicerar [Matrix](../../com.aspose.drawing.drawing2d/matrix)-objektet som representerar den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt med det angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix)-objektet genom att föregå det angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix)-objektet. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Multiplicerar [Matrix](../../com.aspose.drawing.drawing2d/matrix)-objektet som representerar den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt med det angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix)-objektet i den angivna ordningen. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Förflyttar den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt med de angivna dimensionerna. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Förflyttar den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt med de angivna dimensionerna i den angivna ordningen. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skalar den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt med de angivna mängderna. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skalar den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt med de angivna mängderna i den angivna ordningen. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Roterar den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt med den angivna mängden. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Roterar den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt med den angivna mängden i den angivna ordningen. |
### TextureBrush(Image bitmap) {#TextureBrush-com.aspose.drawing.Image-}
```
public TextureBrush(Image bitmap)
```


Initierar en ny instans av klassen [TextureBrush](../../com.aspose.drawing/texturebrush) som använder den angivna bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitmap | [Image](../../com.aspose.drawing/image) | `Image`([.getImage](../../null/\#getImage))-objektet som detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt fyller interiörer med. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.drawing.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Initierar en ny instans av klassen [TextureBrush](../../com.aspose.drawing/texturebrush) som använder den angivna bilden och omslagsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Bilden. |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-))-enumeration som specificerar hur detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt upprepas. |

### TextureBrush(Image image, int wrapMode, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF dstRect)
```


Initierar en ny instans av klassen [TextureBrush](../../com.aspose.drawing/texturebrush) som använder den angivna bilden, omslagsläget och den avgränsande rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Bilden. |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-))-enumeration som specificerar hur detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt upprepas. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | En [RectangleF](../../com.aspose.drawing/rectanglef)-struktur som representerar den avgränsande rektangeln för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt. |

### TextureBrush(Image image, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, RectangleF dstRect)
```


Initierar en ny instans av klassen [TextureBrush](../../com.aspose.drawing/texturebrush) som använder den angivna bilden och den avgränsande rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | `Image`([.getImage](../../null/\#getImage))-objektet som detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt fyller interiörer med. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | En [RectangleF](../../com.aspose.drawing/rectanglef)-struktur som representerar den avgränsande rektangeln för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt. |

### TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)
```


Initierar en ny instans av klassen [TextureBrush](../../com.aspose.drawing/texturebrush) som använder den angivna bilden, den avgränsande rektangeln och bildattributen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Image-objektet som detta TextureBrush-objekt fyller interiörer med. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | En RectangleF-struktur som representerar den avgränsande rektangeln för detta TextureBrush-objekt. |
| imageAttr | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) | Ett ImageAttributes-objekt som innehåller ytterligare information om bilden som används av detta TextureBrush-objekt. |

### getImage() {#getImage--}
```
public Image getImage()
```


Hämtar Image-objektet som är associerat med detta TextureBrush-objekt.

**Returns:**
[Image](../../com.aspose.drawing/image) - the Image object associated with this TextureBrush object.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Hämtar en kopia av Matrix-objektet som definierar en lokal geometrisk transformation för bilden som är associerad med detta TextureBrush-objekt.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - a copy of the Matrix object that defines a local geometric transformation for the image associated with this TextureBrush object.
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Ställer in en kopia av Matrix-objektet som definierar en lokal geometrisk transformation för bilden som är associerad med detta TextureBrush-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | en kopia av Matrix-objektet som definierar en lokal geometrisk transformation för bilden som är associerad med detta TextureBrush-objekt. |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Hämtar en WrapMode‑enumeration som anger omslagsläget för detta TextureBrush-objekt.

**Returns:**
int - en WrapMode‑enumeration som indikerar omslagsläget för detta TextureBrush‑objekt.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Ställer in en WrapMode‑enumeration som anger omslagsläget för detta TextureBrush-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | en WrapMode‑enumeration som indikerar omslagsläget för detta TextureBrush‑objekt. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar en exakt kopia av detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt.

**Returns:**
java.lang.Object - Det [TextureBrush](../../com.aspose.drawing/texturebrush)‑objekt som den här metoden skapar, kastat som ett Object‑objekt.
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Återställer Transform‑egenskapen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt till identitet.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplicerar [Matrix](../../com.aspose.drawing.drawing2d/matrix)-objektet som representerar den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt med det angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix)-objektet genom att föregå det angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix)-objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Det [Matrix](../../com.aspose.drawing.drawing2d/matrix)‑objekt som används för att multiplicera den geometriska transformationen. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplicerar [Matrix](../../com.aspose.drawing.drawing2d/matrix)-objektet som representerar den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt med det angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix)-objektet i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Det [Matrix](../../com.aspose.drawing.drawing2d/matrix)‑objekt som används för att multiplicera den geometriska transformationen. |
| order | int | En [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)‑enumeration som specificerar i vilken ordning de två matriserna ska multipliceras. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Översätter den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)‑objekt med de angivna dimensionerna. Denna metod lägger till översättningen i början av transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | flyttal | Dimensionen som används för att översätta transformationen i x‑riktningen. |
| dy | flyttal | Dimensionen som används för att översätta transformationen i y‑riktningen. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Förflyttar den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt med de angivna dimensionerna i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | flyttal | Dimensionen som används för att översätta transformationen i x‑riktningen. |
| dy | flyttal | Dimensionen som används för att översätta transformationen i y‑riktningen. |
| ordning | int | Ordningen (före eller efter) som översättningen ska tillämpas i. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Skalar den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)‑objekt med de angivna värdena. Denna metod lägger till skalningsmatrisen i början av transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | flyttal | Mängden som används för att skala transformationen i x‑riktningen. |
| sy | flyttal | Mängden som används för att skala transformationen i y‑riktningen. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skalar den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt med de angivna mängderna i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | flyttal | Mängden som används för att skala transformationen i x‑riktningen. |
| sy | flyttal | Mängden som används för att skala transformationen i y‑riktningen. |
| order | int | En [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)‑enumeration som specificerar om skalningsmatrisen ska läggas till i slutet eller i början. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Roterar den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)‑objekt med den angivna mängden. Denna metod lägger till rotationen i början av transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | flyttal | Rotationsvinkeln. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Roterar den lokala geometriska transformationen för detta [TextureBrush](../../com.aspose.drawing/texturebrush)-objekt med den angivna mängden i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | flyttal | Rotationsvinkeln. |
| order | int | En [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)‑enumeration som specificerar om rotationsmatrisen ska läggas till i slutet eller i början. |

