---
title: TextureBrush
second_title: Aspose.Drawing voor Java API-referentie
description: Elke eigenschap van de TextureBrush‑klasse is een Brush‑object dat een afbeelding gebruikt om het binnenste van een vorm te vullen.
type: docs
weight: 53
url: /nl/java/com.aspose.drawing/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class TextureBrush extends Brush
```

Elke eigenschap van de TextureBrush-klasse is een Brush-object dat een afbeelding gebruikt om het interieur van een vorm te vullen. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TextureBrush(Image bitmap)](#TextureBrush-com.aspose.drawing.Image-) | Initialiseert een nieuw exemplaar van de [TextureBrush](../../com.aspose.drawing/texturebrush) klasse die de opgegeven afbeelding gebruikt. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.drawing.Image-int-) | Initialiseert een nieuw exemplaar van de [TextureBrush](../../com.aspose.drawing/texturebrush) klasse die de opgegeven afbeelding en wrap-modus gebruikt. |
| [TextureBrush(Image image, int wrapMode, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-) | Initialiseert een nieuw exemplaar van de [TextureBrush](../../com.aspose.drawing/texturebrush) klasse die de opgegeven afbeelding, wrap-modus en begrenzende rechthoek gebruikt. |
| [TextureBrush(Image image, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-) | Initialiseert een nieuw exemplaar van de [TextureBrush](../../com.aspose.drawing/texturebrush) klasse die de opgegeven afbeelding en begrenzende rechthoek gebruikt. |
| [TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-) | Initialiseert een nieuw exemplaar van de [TextureBrush](../../com.aspose.drawing/texturebrush) klasse die de opgegeven afbeelding, begrenzende rechthoek en afbeeldingsattributen gebruikt. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getImage()](#getImage--) | Haalt het Image-object op dat aan dit TextureBrush-object is gekoppeld. |
| [getTransform()](#getTransform--) | Haalt een kopie op van het Matrix-object dat een lokale geometrische transformatie voor de afbeelding definieert die aan dit TextureBrush-object is gekoppeld. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Stelt een kopie in van het Matrix-object dat een lokale geometrische transformatie voor de afbeelding definieert die aan dit TextureBrush-object is gekoppeld. |
| [getWrapMode()](#getWrapMode--) | Haalt een WrapMode-enumeratie op die de wrap-modus voor dit TextureBrush-object aangeeft. |
| [setWrapMode(int value)](#setWrapMode-int-) | Stelt een WrapMode-enumeratie in die de wrap-modus voor dit TextureBrush-object aangeeft. |
| [deepClone()](#deepClone--) | Maakt een exacte kopie van dit [TextureBrush](../../com.aspose.drawing/texturebrush) object. |
| [resetTransform()](#resetTransform--) | Reset de Transform-eigenschap van dit [TextureBrush](../../com.aspose.drawing/texturebrush) object naar de identiteit. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Vermenigvuldigt het [Matrix](../../com.aspose.drawing.drawing2d/matrix)-object dat de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object weergeeft met het opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix)-object door het opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix)-object vooraan te plaatsen. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Vermenigvuldigt het [Matrix](../../com.aspose.drawing.drawing2d/matrix)-object dat de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object weergeeft met het opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix)-object in de opgegeven volgorde. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschuift de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object met de opgegeven afmetingen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Verschuift de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object met de opgegeven afmetingen in de opgegeven volgorde. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Schaalt de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object met de opgegeven hoeveelheden. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Schaalt de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object met de opgegeven hoeveelheden in de opgegeven volgorde. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Roteert de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object met de opgegeven hoeveelheid. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Roteert de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object met de opgegeven hoeveelheid in de opgegeven volgorde. |
### TextureBrush(Image bitmap) {#TextureBrush-com.aspose.drawing.Image-}
```
public TextureBrush(Image bitmap)
```


Initialiseert een nieuw exemplaar van de [TextureBrush](../../com.aspose.drawing/texturebrush) klasse die de opgegeven afbeelding gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitmap | [Image](../../com.aspose.drawing/image) | Het `Image`([.getImage](../../null/\#getImage)) object waarmee dit [TextureBrush](../../com.aspose.drawing/texturebrush) object interieurs vult. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.drawing.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Initialiseert een nieuw exemplaar van de [TextureBrush](../../com.aspose.drawing/texturebrush) klasse die de opgegeven afbeelding en wrap-modus gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | De afbeelding. |
| wrapMode | int | Een `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) enumeratie die specificeert hoe dit [TextureBrush](../../com.aspose.drawing/texturebrush) object wordt getegeld. |

### TextureBrush(Image image, int wrapMode, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF dstRect)
```


Initialiseert een nieuw exemplaar van de [TextureBrush](../../com.aspose.drawing/texturebrush) klasse die de opgegeven afbeelding, wrap-modus en begrenzende rechthoek gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | De afbeelding. |
| wrapMode | int | Een `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) enumeratie die specificeert hoe dit [TextureBrush](../../com.aspose.drawing/texturebrush) object wordt getegeld. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Een [RectangleF](../../com.aspose.drawing/rectanglef)-structuur die de begrenzende rechthoek voor dit [TextureBrush](../../com.aspose.drawing/texturebrush) object weergeeft. |

### TextureBrush(Image image, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, RectangleF dstRect)
```


Initialiseert een nieuw exemplaar van de [TextureBrush](../../com.aspose.drawing/texturebrush) klasse die de opgegeven afbeelding en begrenzende rechthoek gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Het `Image`([.getImage](../../null/\#getImage)) object waarmee dit [TextureBrush](../../com.aspose.drawing/texturebrush) object interieurs vult. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Een [RectangleF](../../com.aspose.drawing/rectanglef)-structuur die de begrenzende rechthoek voor dit [TextureBrush](../../com.aspose.drawing/texturebrush) object weergeeft. |

### TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)
```


Initialiseert een nieuw exemplaar van de [TextureBrush](../../com.aspose.drawing/texturebrush) klasse die de opgegeven afbeelding, begrenzende rechthoek en afbeeldingsattributen gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Het Image-object waarmee dit TextureBrush-object interieurs vult. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Een RectangleF-structuur die de begrenzende rechthoek voor dit TextureBrush-object weergeeft. |
| imageAttr | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) | Een ImageAttributes-object dat aanvullende informatie bevat over de afbeelding die door dit TextureBrush-object wordt gebruikt. |

### getImage() {#getImage--}
```
public Image getImage()
```


Haalt het Image-object op dat aan dit TextureBrush-object is gekoppeld.

**Returns:**
[Image](../../com.aspose.drawing/image) - the Image object associated with this TextureBrush object.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Haalt een kopie op van het Matrix-object dat een lokale geometrische transformatie voor de afbeelding definieert die aan dit TextureBrush-object is gekoppeld.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - a copy of the Matrix object that defines a local geometric transformation for the image associated with this TextureBrush object.
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Stelt een kopie in van het Matrix-object dat een lokale geometrische transformatie voor de afbeelding definieert die aan dit TextureBrush-object is gekoppeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | een kopie van het Matrix-object dat een lokale geometrische transformatie voor de afbeelding definieert die aan dit TextureBrush-object is gekoppeld. |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Haalt een WrapMode-enumeratie op die de wrap-modus voor dit TextureBrush-object aangeeft.

**Returns:**
int - een WrapMode-enumeratie die de wrap-modus voor dit TextureBrush-object aangeeft.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Stelt een WrapMode-enumeratie in die de wrap-modus voor dit TextureBrush-object aangeeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | een WrapMode-enumeratie die de wrap-modus voor dit TextureBrush-object aangeeft. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Maakt een exacte kopie van dit [TextureBrush](../../com.aspose.drawing/texturebrush) object.

**Returns:**
java.lang.Object - Het [TextureBrush](../../com.aspose.drawing/texturebrush)-object dat deze methode maakt, gecast als een Object-object.
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Reset de Transform-eigenschap van dit [TextureBrush](../../com.aspose.drawing/texturebrush) object naar de identiteit.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Vermenigvuldigt het [Matrix](../../com.aspose.drawing.drawing2d/matrix)-object dat de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object weergeeft met het opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix)-object door het opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix)-object vooraan te plaatsen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Het [Matrix](../../com.aspose.drawing.drawing2d/matrix)-object waarmee de geometrische transformatie wordt vermenigvuldigd. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Vermenigvuldigt het [Matrix](../../com.aspose.drawing.drawing2d/matrix)-object dat de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object weergeeft met het opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix)-object in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Het [Matrix](../../com.aspose.drawing.drawing2d/matrix)-object waarmee de geometrische transformatie wordt vermenigvuldigd. |
| order | int | Een [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)-enumeratie die de volgorde specificeert waarin de twee matrices worden vermenigvuldigd. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Vertaalt de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object met de opgegeven afmetingen. Deze methode voegt de translatie toe aan het begin van de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | float | De dimensie waarmee de transformatie in de x-richting wordt getransleerd. |
| dy | float | De dimensie waarmee de transformatie in de y-richting wordt getransleerd. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Verschuift de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object met de opgegeven afmetingen in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | float | De dimensie waarmee de transformatie in de x-richting wordt getransleerd. |
| dy | float | De dimensie waarmee de transformatie in de y-richting wordt getransleerd. |
| volgorde | int | De volgorde (voorgaan of toevoegen) waarin de translatie wordt toegepast. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Schaalt de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object met de opgegeven hoeveelheden. Deze methode voegt de schaalmatrix toe aan het begin van de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sx | float | De hoeveelheid waarmee de transformatie in de x-richting wordt geschaald. |
| sy | float | De hoeveelheid waarmee de transformatie in de y-richting wordt geschaald. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Schaalt de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object met de opgegeven hoeveelheden in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sx | float | De hoeveelheid waarmee de transformatie in de x-richting wordt geschaald. |
| sy | float | De hoeveelheid waarmee de transformatie in de y-richting wordt geschaald. |
| order | int | Een [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)-enumeratie die aangeeft of de schaalmatrix moet worden toegevoegd of vooraan moet worden geplaatst. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Draait de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object met de opgegeven hoeveelheid. Deze methode voegt de rotatie toe aan het begin van de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | float | De rotatiehoek. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Roteert de lokale geometrische transformatie van dit [TextureBrush](../../com.aspose.drawing/texturebrush)-object met de opgegeven hoeveelheid in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | float | De rotatiehoek. |
| order | int | Een [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)-enumeratie die aangeeft of de rotatiematrix moet worden toegevoegd of vooraan moet worden geplaatst. |

