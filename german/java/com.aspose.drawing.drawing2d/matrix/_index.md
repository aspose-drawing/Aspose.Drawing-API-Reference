---
title: Matrix
second_title: Aspose.Drawing für Java API-Referenz
description: Kapselt eine 3‑mal‑3 affine Matrix, die eine geometrische Transformation darstellt.
type: docs
weight: 33
url: /de/java/com.aspose.drawing.drawing2d/matrix/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Matrix implements System.IDisposable
```

Kapselt eine 3‑mal‑3 affine Matrix, die eine geometrische Transformation darstellt. Diese Klasse kann nicht vererbt werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Matrix()](#Matrix--) | Initialisiert eine neue Instanz der Matrix‑Klasse als Einheitsmatrix. |
| [Matrix(float m11, float m12, float m21, float m22, float dx, float dy)](#Matrix-float-float-float-float-float-float-) | Initialisiert eine neue Instanz der Matrix‑Klasse mit den angegebenen Elementen. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---) | Initialisiert eine neue Instanz der [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Klasse für die geometrische Transformation, die durch das angegebene Rechteck und das Punkt‑Array definiert ist. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---) | Initialisiert eine neue Instanz der [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Klasse für die geometrische Transformation, die durch das angegebene Rechteck und das Punkt‑Array definiert ist. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [IdentityTransform](#IdentityTransform) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getElements()](#getElements--) | Gibt ein Array von Gleitkommawerten zurück, das die Elemente dieser Matrix darstellt. |
| [isIdentity()](#isIdentity--) | Gibt einen Wert zurück, der angibt, ob diese Matrix die Einheitsmatrix ist. |
| [isInvertible()](#isInvertible--) | Gibt einen Wert zurück, der angibt, ob diese Matrix invertierbar ist. |
| [getOffsetX()](#getOffsetX--) | Liefert den x-Translationswert (den dx-Wert oder das Element in der dritten Zeile und ersten Spalte) dieser Matrix. |
| [getOffsetY()](#getOffsetY--) | Liefert den y-Translationswert (den `dy`-Wert oder das Element in der dritten Zeile und zweiten Spalte) dieser Matrix. |
| [dispose()](#dispose--) | Gibt alle von dieser Matrix verwendeten Ressourcen frei. |
| [deepClone()](#deepClone--) | Erstellt eine exakte Kopie dieser Matrix. |
| [invert()](#invert--) | Invertiert diese Matrix, falls sie invertierbar ist. |
| [translate(float offsetX, float offsetY)](#translate-float-float-) | Wendet den angegebenen Translationsvektor (offsetX und offsetY) auf diese Matrix an, indem der Translationsvektor vorangestellt wird. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Wendet den angegebenen Translationsvektor in der angegebenen Reihenfolge auf diese Matrix an. |
| [transformVectors(PointF[] pts)](#transformVectors-com.aspose.drawing.PointF---) | Multipliziert jeden Vektor in einem Array mit der Matrix. |
| [scale(float scaleX, float scaleY)](#scale-float-float-) | Wendet den angegebenen Skalierungsvektor auf diese Matrix an, indem der Skalierungsvektor vorangestellt wird. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) unter Verwendung der angegebenen Reihenfolge auf diese Matrix an. |
| [shear(float shearX, float shearY)](#shear-float-float-) | Wendet den angegebenen Scherungsvektor auf diese Matrix an, indem die Scherungs‑Transformation vorangestellt wird. |
| [shear(float shearX, float shearY, int order)](#shear-float-float-int-) | Wendet den angegebenen Scherungsvektor in der angegebenen Reihenfolge auf diese Matrix an. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.drawing.PointF-) | Wendet eine im Uhrzeigersinn gerichtete Drehung auf diese Matrix um den im Parameter point angegebenen Punkt an und indem die Drehung vorangestellt wird. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.drawing.PointF-int-) | Wendet eine im Uhrzeigersinn gerichtete Drehung um den angegebenen Punkt in der angegebenen Reihenfolge auf diese Matrix an. |
| [transformPoints(PointF[] pts)](#transformPoints-com.aspose.drawing.PointF---) | Wendet die geometrische Transformation, die durch diese [Matrix](../../com.aspose.drawing.drawing2d/matrix) dargestellt wird, auf ein angegebenes Array von Punkten an. |
| [transformPoints(Point[] pts)](#transformPoints-com.aspose.drawing.Point---) | Wendet die geometrische Transformation, die durch diese [Matrix](../../com.aspose.drawing.drawing2d/matrix) dargestellt wird, auf ein angegebenes Array von Punkten an. |
| [multiply(Matrix matrix)](#multiply-com.aspose.drawing.drawing2d.Matrix-) | Multipliziert diese [Matrix](../../com.aspose.drawing.drawing2d/matrix) mit der im Parameter `matrix` angegebenen Matrix, indem die angegebene [Matrix](../../com.aspose.drawing.drawing2d/matrix) vorangestellt wird. |
| [multiply(Matrix matrix, int order)](#multiply-com.aspose.drawing.drawing2d.Matrix-int-) | Multipliziert diese [Matrix](../../com.aspose.drawing.drawing2d/matrix) mit der im Parameter `matrix` angegebenen Matrix und in der im Parameter `order` angegebenen Reihenfolge. |
| [rotate(float angle)](#rotate-float-) | Stellt dieser [Matrix](../../com.aspose.drawing.drawing2d/matrix) eine im Uhrzeigersinn gerichtete Drehung um den Ursprung und mit dem angegebenen Winkel voran. |
| [rotate(float angle, int order)](#rotate-float-int-) | Wendet eine im Uhrzeigersinn gerichtete Drehung mit dem im Parameter angle angegebenen Betrag um den Ursprung (null x- und y-Koordinaten) für diese [Matrix](../../com.aspose.drawing.drawing2d/matrix) an. |
| [reset()](#reset--) | Setzt diese [Matrix](../../com.aspose.drawing.drawing2d/matrix) zurück, sodass sie die Elemente der Einheitsmatrix enthält. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Initialisiert eine neue Instanz der Matrix‑Klasse als Einheitsmatrix.

### Matrix(float m11, float m12, float m21, float m22, float dx, float dy) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


Initialisiert eine neue Instanz der Matrix‑Klasse mit den angegebenen Elementen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| m11 | float | Der Wert in der ersten Zeile und ersten Spalte der neuen Matrix. |
| m12 | float | Der Wert in der ersten Zeile und zweiten Spalte der neuen Matrix. |
| m21 | float | Der Wert in der zweiten Zeile und ersten Spalte der neuen Matrix. |
| m22 | float | Der Wert in der zweiten Zeile und zweiten Spalte der neuen Matrix. |
| dx | float | Der Wert in der dritten Zeile und ersten Spalte der neuen Matrix. |
| dy | float | Der Wert in der dritten Zeile und zweiten Spalte der neuen Matrix. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Initialisiert eine neue Instanz der [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Klasse für die geometrische Transformation, die durch das angegebene Rechteck und das Punkt‑Array definiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Eine [Rectangle](../../com.aspose.drawing/rectangle)-Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | [Point\[\]](../../com.aspose.drawing/point) | Ein Array von drei [Point](../../com.aspose.drawing/point)-Strukturen, das die Punkte eines Parallelogramms darstellt, zu dem die obere linke, obere rechte und untere linke Ecke des Rechtecks transformiert werden sollen. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Initialisiert eine neue Instanz der [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Klasse für die geometrische Transformation, die durch das angegebene Rechteck und das Punkt‑Array definiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Eine [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | [PointF\[\]](../../com.aspose.drawing/pointf) | Ein Array von drei [PointF](../../com.aspose.drawing/pointf)-Strukturen, das die Punkte eines Parallelogramms darstellt, zu dem die obere linke, obere rechte und untere linke Ecke des Rechtecks transformiert werden sollen. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

### IdentityTransform {#IdentityTransform}
```
public static final Matrix IdentityTransform
```


### getElements() {#getElements--}
```
public float[] getElements()
```


Gibt ein Array von Gleitkommawerten zurück, das die Elemente dieser Matrix darstellt.

**Returns:**
float[] - ein Array von Gleitkommawerten, das die Elemente dieser Matrix darstellt.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Gibt einen Wert zurück, der angibt, ob diese Matrix die Einheitsmatrix ist.

**Returns:**
boolean - ein Wert, der angibt, ob diese Matrix die Einheitsmatrix ist.
### isInvertible() {#isInvertible--}
```
public boolean isInvertible()
```


Gibt einen Wert zurück, der angibt, ob diese Matrix invertierbar ist.

**Returns:**
boolean - ein Wert, der angibt, ob diese Matrix invertierbar ist.
### getOffsetX() {#getOffsetX--}
```
public float getOffsetX()
```


Liefert den x-Translationswert (den dx-Wert oder das Element in der dritten Zeile und ersten Spalte) dieser Matrix.

**Returns:**
float - der x-Translationswert (der dx-Wert oder das Element in der dritten Zeile und ersten Spalte) dieser Matrix.
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```


Liefert den y-Translationswert (den `dy`-Wert oder das Element in der dritten Zeile und zweiten Spalte) dieser Matrix.

**Returns:**
float - der y-Translationswert (der `dy`-Wert oder das Element in der dritten Zeile und zweiten Spalte) dieser Matrix.
### dispose() {#dispose--}
```
public void dispose()
```


Gibt alle von dieser Matrix verwendeten Ressourcen frei.

--------------------

Diese Methode tut tatsächlich nichts. Sie dient nur der Kompatibilität mit der System.Drawing-API.

### deepClone() {#deepClone--}
```
public Matrix deepClone()
```


Erstellt eine exakte Kopie dieser Matrix.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - The Matrix that this method creates.
### invert() {#invert--}
```
public void invert()
```


Invertiert diese Matrix, falls sie invertierbar ist.

### translate(float offsetX, float offsetY) {#translate-float-float-}
```
public void translate(float offsetX, float offsetY)
```


Wendet den angegebenen Translationsvektor (offsetX und offsetY) auf diese Matrix an, indem der Translationsvektor vorangestellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| offsetX | float | Der x-Wert, um den diese Matrix übersetzt wird. |
| offsetY | float | Der y-Wert, um den diese Matrix übersetzt wird. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Wendet den angegebenen Translationsvektor in der angegebenen Reihenfolge auf diese Matrix an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| offsetX | float | Der x-Wert, um den diese Matrix übersetzt wird. |
| offsetY | float | Der y-Wert, um den diese Matrix übersetzt wird. |
| Reihenfolge | int | Ein MatrixOrder, der die Reihenfolge (Anhängen oder Voranstellen) angibt, in der die Translation auf diese Matrix angewendet wird. |

### transformVectors(PointF[] pts) {#transformVectors-com.aspose.drawing.PointF---}
```
public void transformVectors(PointF[] pts)
```


Multipliziert jeden Vektor in einem Array mit der Matrix. Die Translationskomponenten dieser Matrix (dritte Zeile) werden ignoriert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Ein Array von [PointF](../../com.aspose.drawing/pointf)-Strukturen, das die zu transformierenden Punkte darstellt. |

### scale(float scaleX, float scaleY) {#scale-float-float-}
```
public void scale(float scaleX, float scaleY)
```


Wendet den angegebenen Skalierungsvektor auf diese Matrix an, indem der Skalierungsvektor vorangestellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scaleX | float | Der Wert, um den diese Matrix in x-Richtung skaliert wird. |
| scaleY | float | Der Wert, um den diese Matrix in y‑Achsenrichtung skaliert wird. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) unter Verwendung der angegebenen Reihenfolge auf diese Matrix an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scaleX | float | Der Wert, um den diese Matrix in x-Richtung skaliert wird. |
| scaleY | float | Der Wert, um den diese Matrix in y‑Achsenrichtung skaliert wird. |
| Reihenfolge | int | Ein MatrixOrder, der die Reihenfolge (Anhängen oder Voranstellen) angibt, in der der Skalierungsvektor auf diese Matrix angewendet wird. |

### shear(float shearX, float shearY) {#shear-float-float-}
```
public void shear(float shearX, float shearY)
```


Wendet den angegebenen Scherungsvektor auf diese Matrix an, indem die Scherungs‑Transformation vorangestellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shearX | float | Der horizontale Scherfaktor. |
| shearY | float | Der vertikale Scherfaktor. |

### shear(float shearX, float shearY, int order) {#shear-float-float-int-}
```
public void shear(float shearX, float shearY, int order)
```


Wendet den angegebenen Scherungsvektor in der angegebenen Reihenfolge auf diese Matrix an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shearX | float | Der horizontale Scherfaktor. |
| shearY | float | Der vertikale Scherfaktor. |
| Reihenfolge | int | Ein MatrixOrder, der die Reihenfolge (Anhängen oder Voranstellen) angibt, in der die Scherung angewendet wird. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.drawing.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Wendet eine im Uhrzeigersinn gerichtete Drehung auf diese Matrix um den im Parameter point angegebenen Punkt an und indem die Drehung vorangestellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Winkel (Ausmaß) der Drehung in Grad. |
| point | [PointF](../../com.aspose.drawing/pointf) | Ein PointF, der das Zentrum der Drehung darstellt. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.drawing.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Wendet eine im Uhrzeigersinn gerichtete Drehung um den angegebenen Punkt in der angegebenen Reihenfolge auf diese Matrix an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Winkel der Drehung in Grad. |
| point | [PointF](../../com.aspose.drawing/pointf) | Ein PointF, der das Zentrum der Drehung darstellt. |
| Reihenfolge | int | Ein MatrixOrder, der die Reihenfolge (Anhängen oder Voranstellen) angibt, in der die Drehung angewendet wird. |

### transformPoints(PointF[] pts) {#transformPoints-com.aspose.drawing.PointF---}
```
public void transformPoints(PointF[] pts)
```


Wendet die geometrische Transformation, die durch diese [Matrix](../../com.aspose.drawing.drawing2d/matrix) dargestellt wird, auf ein angegebenes Array von Punkten an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Ein Array von [PointF](../../com.aspose.drawing/pointf)-Strukturen, das die zu transformierenden Punkte darstellt. |

### transformPoints(Point[] pts) {#transformPoints-com.aspose.drawing.Point---}
```
public void transformPoints(Point[] pts)
```


Wendet die geometrische Transformation, die durch diese [Matrix](../../com.aspose.drawing.drawing2d/matrix) dargestellt wird, auf ein angegebenes Array von Punkten an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pts | [Point\[\]](../../com.aspose.drawing/point) | Ein Array von [Point](../../com.aspose.drawing/point)-Strukturen, das die zu transformierenden Punkte darstellt. |

### multiply(Matrix matrix) {#multiply-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiply(Matrix matrix)
```


Multipliziert diese [Matrix](../../com.aspose.drawing.drawing2d/matrix) mit der im Parameter `matrix` angegebenen Matrix, indem die angegebene [Matrix](../../com.aspose.drawing.drawing2d/matrix) vorangestellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Die [Matrix](../../com.aspose.drawing.drawing2d/matrix), mit der diese [Matrix](../../com.aspose.drawing.drawing2d/matrix) multipliziert werden soll. |

### multiply(Matrix matrix, int order) {#multiply-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiply(Matrix matrix, int order)
```


Multipliziert diese [Matrix](../../com.aspose.drawing.drawing2d/matrix) mit der im Parameter `matrix` angegebenen Matrix und in der im Parameter `order` angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Die [Matrix](../../com.aspose.drawing.drawing2d/matrix), mit der diese [Matrix](../../com.aspose.drawing.drawing2d/matrix) multipliziert werden soll. |
| order | int | Der [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), der die Reihenfolge der Multiplikation darstellt. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Stellt dieser [Matrix](../../com.aspose.drawing.drawing2d/matrix) eine im Uhrzeigersinn gerichtete Drehung um den Ursprung und mit dem angegebenen Winkel voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Winkel der Drehung in Grad. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Wendet eine im Uhrzeigersinn gerichtete Drehung mit dem im Parameter angle angegebenen Betrag um den Ursprung (null x- und y-Koordinaten) für diese [Matrix](../../com.aspose.drawing.drawing2d/matrix) an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Winkel der Drehung in Grad. |
| order | int | Ein [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), der die Reihenfolge (Anhängen oder Voranstellen) angibt, in der die Drehung auf diese [Matrix](../../com.aspose.drawing.drawing2d/matrix) angewendet wird. |

### reset() {#reset--}
```
public void reset()
```


Setzt diese [Matrix](../../com.aspose.drawing.drawing2d/matrix) zurück, sodass sie die Elemente der Einheitsmatrix enthält.

