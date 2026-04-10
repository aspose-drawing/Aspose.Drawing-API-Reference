---
title: TextureBrush
second_title: Aspose.Drawing für Java API-Referenz
description: Jede Eigenschaft der TextureBrush‑Klasse ist ein Brush‑Objekt, das ein Bild verwendet, um das Innere einer Form zu füllen.
type: docs
weight: 53
url: /de/java/com.aspose.drawing/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class TextureBrush extends Brush
```

Jede Eigenschaft der Klasse TextureBrush ist ein Brush-Objekt, das ein Bild verwendet, um das Innere einer Form zu füllen. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextureBrush(Image bitmap)](#TextureBrush-com.aspose.drawing.Image-) | Initialisiert eine neue Instanz der [TextureBrush](../../com.aspose.drawing/texturebrush)-Klasse, die das angegebene Bild verwendet. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.drawing.Image-int-) | Initialisiert eine neue Instanz der [TextureBrush](../../com.aspose.drawing/texturebrush)-Klasse, die das angegebene Bild und den Wrap-Modus verwendet. |
| [TextureBrush(Image image, int wrapMode, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-) | Initialisiert eine neue Instanz der [TextureBrush](../../com.aspose.drawing/texturebrush)-Klasse, die das angegebene Bild, den Wrap-Modus und das Begrenzungsrechteck verwendet. |
| [TextureBrush(Image image, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-) | Initialisiert eine neue Instanz der [TextureBrush](../../com.aspose.drawing/texturebrush)-Klasse, die das angegebene Bild und das Begrenzungsrechteck verwendet. |
| [TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-) | Initialisiert eine neue Instanz der [TextureBrush](../../com.aspose.drawing/texturebrush)-Klasse, die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getImage()](#getImage--) | Liefert das Image-Objekt, das mit diesem TextureBrush-Objekt verknüpft ist. |
| [getTransform()](#getTransform--) | Liefert eine Kopie des Matrix-Objekts, das eine lokale geometrische Transformation für das mit diesem TextureBrush-Objekt verknüpfte Bild definiert. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Setzt eine Kopie des Matrix-Objekts, das eine lokale geometrische Transformation für das mit diesem TextureBrush-Objekt verknüpfte Bild definiert. |
| [getWrapMode()](#getWrapMode--) | Liefert eine WrapMode-Aufzählung, die den Wrap-Modus für dieses TextureBrush-Objekt angibt. |
| [setWrapMode(int value)](#setWrapMode-int-) | Setzt eine WrapMode-Aufzählung, die den Wrap-Modus für dieses TextureBrush-Objekt angibt. |
| [deepClone()](#deepClone--) | Erstellt eine exakte Kopie dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts. |
| [resetTransform()](#resetTransform--) | Setzt die Transform-Eigenschaft dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts auf die Identität zurück. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Multipliziert das [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Objekt, das die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts darstellt, mit dem angegebenen [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Objekt, indem das angegebene [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Objekt vorangestellt wird. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Multipliziert das [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Objekt, das die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts darstellt, mit dem angegebenen [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Objekt in der angegebenen Reihenfolge. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschiebt die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts um die angegebenen Dimensionen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Verschiebt die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts um die angegebenen Dimensionen in der angegebenen Reihenfolge. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skaliert die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts um die angegebenen Werte. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skaliert die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts um die angegebenen Werte in der angegebenen Reihenfolge. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Dreht die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts um den angegebenen Betrag. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Dreht die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts um den angegebenen Betrag in der angegebenen Reihenfolge. |
### TextureBrush(Image bitmap) {#TextureBrush-com.aspose.drawing.Image-}
```
public TextureBrush(Image bitmap)
```


Initialisiert eine neue Instanz der [TextureBrush](../../com.aspose.drawing/texturebrush)-Klasse, die das angegebene Bild verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitmap | [Image](../../com.aspose.drawing/image) | Das `Image`([.getImage](../../null/\#getImage))-Objekt, mit dem dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekt Innenflächen füllt. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.drawing.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Initialisiert eine neue Instanz der [TextureBrush](../../com.aspose.drawing/texturebrush)-Klasse, die das angegebene Bild und den Wrap-Modus verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Das Bild. |
| wrapMode | int | Eine `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-))-Aufzählung, die angibt, wie dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekt gekachelt wird. |

### TextureBrush(Image image, int wrapMode, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF dstRect)
```


Initialisiert eine neue Instanz der [TextureBrush](../../com.aspose.drawing/texturebrush)-Klasse, die das angegebene Bild, den Wrap-Modus und das Begrenzungsrechteck verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Das Bild. |
| wrapMode | int | Eine `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-))-Aufzählung, die angibt, wie dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekt gekachelt wird. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Eine [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur, die das Begrenzungsrechteck für dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekt darstellt. |

### TextureBrush(Image image, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, RectangleF dstRect)
```


Initialisiert eine neue Instanz der [TextureBrush](../../com.aspose.drawing/texturebrush)-Klasse, die das angegebene Bild und das Begrenzungsrechteck verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Das `Image`([.getImage](../../null/\#getImage))-Objekt, mit dem dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekt Innenflächen füllt. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Eine [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur, die das Begrenzungsrechteck für dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekt darstellt. |

### TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)
```


Initialisiert eine neue Instanz der [TextureBrush](../../com.aspose.drawing/texturebrush)-Klasse, die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Das Image-Objekt, mit dem dieses TextureBrush-Objekt Innenflächen füllt. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Eine RectangleF-Struktur, die das Begrenzungsrechteck für dieses TextureBrush-Objekt darstellt. |
| imageAttr | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) | Ein ImageAttributes-Objekt, das zusätzliche Informationen über das von diesem TextureBrush-Objekt verwendete Bild enthält. |

### getImage() {#getImage--}
```
public Image getImage()
```


Liefert das Image-Objekt, das mit diesem TextureBrush-Objekt verknüpft ist.

**Returns:**
[Image](../../com.aspose.drawing/image) - the Image object associated with this TextureBrush object.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Liefert eine Kopie des Matrix-Objekts, das eine lokale geometrische Transformation für das mit diesem TextureBrush-Objekt verknüpfte Bild definiert.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - a copy of the Matrix object that defines a local geometric transformation for the image associated with this TextureBrush object.
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Setzt eine Kopie des Matrix-Objekts, das eine lokale geometrische Transformation für das mit diesem TextureBrush-Objekt verknüpfte Bild definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | eine Kopie des Matrix-Objekts, das eine lokale geometrische Transformation für das mit diesem TextureBrush-Objekt verknüpfte Bild definiert. |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Liefert eine WrapMode-Aufzählung, die den Wrap-Modus für dieses TextureBrush-Objekt angibt.

**Returns:**
int - eine WrapMode-Aufzählung, die den Wrap-Modus für dieses TextureBrush-Objekt angibt.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Setzt eine WrapMode-Aufzählung, die den Wrap-Modus für dieses TextureBrush-Objekt angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | eine WrapMode-Aufzählung, die den Wrap-Modus für dieses TextureBrush-Objekt angibt. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Erstellt eine exakte Kopie dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts.

**Returns:**
java.lang.Object - Das [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekt, das diese Methode erstellt, als Object-Objekt umgewandelt.
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Setzt die Transform-Eigenschaft dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts auf die Identität zurück.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multipliziert das [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Objekt, das die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts darstellt, mit dem angegebenen [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Objekt, indem das angegebene [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Objekt vorangestellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Das [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Objekt, mit dem die geometrische Transformation multipliziert wird. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multipliziert das [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Objekt, das die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts darstellt, mit dem angegebenen [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Objekt in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Das [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Objekt, mit dem die geometrische Transformation multipliziert wird. |
| order | int | Eine [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)-Aufzählung, die die Reihenfolge angibt, in der die beiden Matrizen multipliziert werden. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Übersetzt die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Die Dimension, um die die Transformation in x‑Richtung übersetzt wird. |
| dy | float | Die Dimension, um die die Transformation in y‑Richtung übersetzt wird. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Verschiebt die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts um die angegebenen Dimensionen in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Die Dimension, um die die Transformation in x‑Richtung übersetzt wird. |
| dy | float | Die Dimension, um die die Transformation in y‑Richtung übersetzt wird. |
| Reihenfolge | int | Die Reihenfolge (voranstellen oder anhängen), in der die Verschiebung angewendet wird. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Skaliert die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts um die angegebenen Werte. Diese Methode fügt die Skalierungs‑matrix der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Betrag, um den die Transformation in x‑Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y‑Richtung skaliert wird. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skaliert die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts um die angegebenen Werte in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Betrag, um den die Transformation in x‑Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y‑Richtung skaliert wird. |
| order | int | Eine [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)-Aufzählung, die angibt, ob die Skalierungs‑matrix angehängt oder vorangestellt wird. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Dreht die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts um den angegebenen Betrag. Diese Methode fügt die Rotation der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Dreht die lokale geometrische Transformation dieses [TextureBrush](../../com.aspose.drawing/texturebrush)-Objekts um den angegebenen Betrag in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel. |
| order | int | Eine [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)-Aufzählung, die angibt, ob die Rotations‑matrix angehängt oder vorangestellt wird. |

