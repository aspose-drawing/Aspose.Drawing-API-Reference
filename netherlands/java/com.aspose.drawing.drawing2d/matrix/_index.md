---
title: Matrix
second_title: Aspose.Drawing voor Java API-referentie
description: Omvat een 3x3 affine matrix die een geometrische transformatie vertegenwoordigt.
type: docs
weight: 33
url: /nl/java/com.aspose.drawing.drawing2d/matrix/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Matrix implements System.IDisposable
```

Omvat een 3x3 affine matrix die een geometrische transformatie vertegenwoordigt. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Matrix()](#Matrix--) | Initialiseert een nieuw exemplaar van de Matrix-klasse als de identiteitsmatrix. |
| [Matrix(float m11, float m12, float m21, float m22, float dx, float dy)](#Matrix-float-float-float-float-float-float-) | Initialiseert een nieuw exemplaar van de Matrix-klasse met de opgegeven elementen. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---) | Initialiseert een nieuw exemplaar van de [Matrix](../../com.aspose.drawing.drawing2d/matrix) klasse naar de geometrische transformatie gedefinieerd door het opgegeven rechthoek en de array van punten. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---) | Initialiseert een nieuw exemplaar van de [Matrix](../../com.aspose.drawing.drawing2d/matrix) klasse naar de geometrische transformatie gedefinieerd door het opgegeven rechthoek en de array van punten. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [IdentityTransform](#IdentityTransform) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getElements()](#getElements--) | Haalt een array van floating-point waarden op die de elementen van deze Matrix vertegenwoordigen. |
| [isIdentity()](#isIdentity--) | Haalt een waarde op die aangeeft of deze Matrix de identiteitsmatrix is. |
| [isInvertible()](#isInvertible--) | Haalt een waarde op die aangeeft of deze Matrix omkeerbaar is. |
| [getOffsetX()](#getOffsetX--) | Haalt de x-translatiewaarde op (de dx-waarde, of het element in de derde rij en eerste kolom) van deze Matrix. |
| [getOffsetY()](#getOffsetY--) | Haalt de y-translatiewaarde op (de `dy`-waarde, of het element in de derde rij en tweede kolom) van deze Matrix. |
| [dispose()](#dispose--) | Geeft alle bronnen vrij die door deze Matrix worden gebruikt. |
| [deepClone()](#deepClone--) | Maakt een exacte kopie van deze Matrix. |
| [invert()](#invert--) | Keert deze Matrix om, als deze omkeerbaar is. |
| [translate(float offsetX, float offsetY)](#translate-float-float-) | Past de opgegeven translatievector (offsetX en offsetY) toe op deze Matrix door de translatievector voor te voegen. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Past de opgegeven translatievector toe op deze Matrix in de opgegeven volgorde. |
| [transformVectors(PointF[] pts)](#transformVectors-com.aspose.drawing.PointF---) | Vermenigvuldigt elke vector in een array met de matrix. |
| [scale(float scaleX, float scaleY)](#scale-float-float-) | Past de opgegeven schaalvector toe op deze Matrix door de schaalvector voor te voegen. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Past de opgegeven schaalvector (scaleX en scaleY) toe op deze Matrix met gebruik van de opgegeven volgorde. |
| [shear(float shearX, float shearY)](#shear-float-float-) | Past de opgegeven schuivingsvector toe op deze Matrix door de schuivingstransformatie voor te voegen. |
| [shear(float shearX, float shearY, int order)](#shear-float-float-int-) | Past de opgegeven schuivingsvector toe op deze Matrix in de opgegeven volgorde. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.drawing.PointF-) | Past een met de klok mee rotatie toe op deze Matrix rond het punt dat is opgegeven in de puntparameter, en door de rotatie voor te voegen. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.drawing.PointF-int-) | Past een met de klok mee rotatie rond het opgegeven punt toe op deze Matrix in de opgegeven volgorde. |
| [transformPoints(PointF[] pts)](#transformPoints-com.aspose.drawing.PointF---) | Past de geometrische transformatie toe die wordt vertegenwoordigd door deze [Matrix](../../com.aspose.drawing.drawing2d/matrix) op een opgegeven array van punten. |
| [transformPoints(Point[] pts)](#transformPoints-com.aspose.drawing.Point---) | Past de geometrische transformatie toe die wordt vertegenwoordigd door deze [Matrix](../../com.aspose.drawing.drawing2d/matrix) op een opgegeven array van punten. |
| [multiply(Matrix matrix)](#multiply-com.aspose.drawing.drawing2d.Matrix-) | Vermenigvuldigt deze [Matrix](../../com.aspose.drawing.drawing2d/matrix) met de matrix die is opgegeven in de `matrix`-parameter, door de opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix) voor te voegen. |
| [multiply(Matrix matrix, int order)](#multiply-com.aspose.drawing.drawing2d.Matrix-int-) | Vermenigvuldigt deze [Matrix](../../com.aspose.drawing.drawing2d/matrix) met de matrix die is opgegeven in de `matrix`-parameter, en in de volgorde die is opgegeven in de `order`-parameter. |
| [rotate(float angle)](#rotate-float-) | Voeg aan deze [Matrix](../../com.aspose.drawing.drawing2d/matrix) een met de klok mee rotatie toe, rond de oorsprong en met de opgegeven hoek. |
| [rotate(float angle, int order)](#rotate-float-int-) | Past een met de klok mee rotatie toe van een hoeveelheid die is opgegeven in de hoekparameter, rond de oorsprong (nul x- en y-coördinaten) voor deze [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [reset()](#reset--) | Reset deze [Matrix](../../com.aspose.drawing.drawing2d/matrix) zodat deze de elementen van de identiteitsmatrix bevat. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Initialiseert een nieuw exemplaar van de Matrix-klasse als de identiteitsmatrix.

### Matrix(float m11, float m12, float m21, float m22, float dx, float dy) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


Initialiseert een nieuw exemplaar van de Matrix-klasse met de opgegeven elementen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| m11 | float | De waarde in de eerste rij en eerste kolom van de nieuwe Matrix. |
| m12 | float | De waarde in de eerste rij en tweede kolom van de nieuwe Matrix. |
| m21 | float | De waarde in de tweede rij en eerste kolom van de nieuwe Matrix. |
| m22 | float | De waarde in de tweede rij en tweede kolom van de nieuwe Matrix. |
| dx | float | De waarde in de derde rij en eerste kolom van de nieuwe Matrix. |
| dy | float | De waarde in de derde rij en tweede kolom van de nieuwe Matrix. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Initialiseert een nieuw exemplaar van de [Matrix](../../com.aspose.drawing.drawing2d/matrix) klasse naar de geometrische transformatie gedefinieerd door het opgegeven rechthoek en de array van punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Een [Rectangle](../../com.aspose.drawing/rectangle) structuur die de te transformeren rechthoek vertegenwoordigt. |
| plgpts | [Point\[\]](../../com.aspose.drawing/point) | Een array van drie [Point](../../com.aspose.drawing/point) structuren die de punten van een parallellogram vertegenwoordigen waartoe de linkerboven-, rechterboven- en linksonderhoeken van de rechthoek moeten worden getransformeerd. De rechteronderhoek van het parallellogram wordt geïmpliceerd door de eerste drie hoeken. |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Initialiseert een nieuw exemplaar van de [Matrix](../../com.aspose.drawing.drawing2d/matrix) klasse naar de geometrische transformatie gedefinieerd door het opgegeven rechthoek en de array van punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Een [RectangleF](../../com.aspose.drawing/rectanglef) structuur die de te transformeren rechthoek vertegenwoordigt. |
| plgpts | [PointF\[\]](../../com.aspose.drawing/pointf) | Een array van drie [PointF](../../com.aspose.drawing/pointf) structuren die de punten van een parallellogram vertegenwoordigen waartoe de linkerboven-, rechterboven- en linksonderhoeken van de rechthoek moeten worden getransformeerd. De rechteronderhoek van het parallellogram wordt geïmpliceerd door de eerste drie hoeken. |

### IdentityTransform {#IdentityTransform}
```
public static final Matrix IdentityTransform
```


### getElements() {#getElements--}
```
public float[] getElements()
```


Haalt een array van floating-point waarden op die de elementen van deze Matrix vertegenwoordigen.

**Returns:**
float[] - een array van floating-point waarden die de elementen van deze Matrix vertegenwoordigen.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Haalt een waarde op die aangeeft of deze Matrix de identiteitsmatrix is.

**Returns:**
boolean - een waarde die aangeeft of deze Matrix de identiteitsmatrix is.
### isInvertible() {#isInvertible--}
```
public boolean isInvertible()
```


Haalt een waarde op die aangeeft of deze Matrix omkeerbaar is.

**Returns:**
boolean - een waarde die aangeeft of deze Matrix inverteerbaar is.
### getOffsetX() {#getOffsetX--}
```
public float getOffsetX()
```


Haalt de x-translatiewaarde op (de dx-waarde, of het element in de derde rij en eerste kolom) van deze Matrix.

**Returns:**
float - de x-translatiewaarde (de dx-waarde, of het element in de derde rij en eerste kolom) van deze Matrix.
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```


Haalt de y-translatiewaarde op (de `dy`-waarde, of het element in de derde rij en tweede kolom) van deze Matrix.

**Returns:**
float - de y-translatiewaarde (de `dy`-waarde, of het element in de derde rij en tweede kolom) van deze Matrix.
### dispose() {#dispose--}
```
public void dispose()
```


Geeft alle bronnen vrij die door deze Matrix worden gebruikt.

--------------------

Deze methode doet eigenlijk niets. Het is alleen voor compatibiliteit met de System.Drawing API.

### deepClone() {#deepClone--}
```
public Matrix deepClone()
```


Maakt een exacte kopie van deze Matrix.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - The Matrix that this method creates.
### invert() {#invert--}
```
public void invert()
```


Keert deze Matrix om, als deze omkeerbaar is.

### translate(float offsetX, float offsetY) {#translate-float-float-}
```
public void translate(float offsetX, float offsetY)
```


Past de opgegeven translatievector (offsetX en offsetY) toe op deze Matrix door de translatievector voor te voegen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| offsetX | float | De x-waarde waarmee deze Matrix moet worden getransleerd. |
| offsetY | float | De y-waarde waarmee deze Matrix moet worden getransleerd. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Past de opgegeven translatievector toe op deze Matrix in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| offsetX | float | De x-waarde waarmee deze Matrix moet worden getransleerd. |
| offsetY | float | De y-waarde waarmee deze Matrix moet worden getransleerd. |
| volgorde | int | Een MatrixOrder die de volgorde (toevoegen of voorvoegen) specificeert waarin de translatie op deze Matrix wordt toegepast. |

### transformVectors(PointF[] pts) {#transformVectors-com.aspose.drawing.PointF---}
```
public void transformVectors(PointF[] pts)
```


Vermenigvuldigt elke vector in een array met de matrix. De translatie‑elementen van deze matrix (derde rij) worden genegeerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Een array van [PointF](../../com.aspose.drawing/pointf) structuren die de te transformeren punten vertegenwoordigen. |

### scale(float scaleX, float scaleY) {#scale-float-float-}
```
public void scale(float scaleX, float scaleY)
```


Past de opgegeven schaalvector toe op deze Matrix door de schaalvector voor te voegen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scaleX | float | De waarde waarmee deze Matrix in de x-richting wordt geschaald. |
| scaleY | float | De waarde waarmee deze Matrix in de y-asrichting wordt geschaald. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Past de opgegeven schaalvector (scaleX en scaleY) toe op deze Matrix met gebruik van de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scaleX | float | De waarde waarmee deze Matrix in de x-richting wordt geschaald. |
| scaleY | float | De waarde waarmee deze Matrix in de y-asrichting wordt geschaald. |
| volgorde | int | Een MatrixOrder die de volgorde (toevoegen of voorafgaand) specificeert waarin de schaalvector op deze Matrix wordt toegepast. |

### shear(float shearX, float shearY) {#shear-float-float-}
```
public void shear(float shearX, float shearY)
```


Past de opgegeven schuivingsvector toe op deze Matrix door de schuivingstransformatie voor te voegen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shearX | float | De horizontale schuiffactor. |
| shearY | float | De verticale schuiffactor. |

### shear(float shearX, float shearY, int order) {#shear-float-float-int-}
```
public void shear(float shearX, float shearY, int order)
```


Past de opgegeven schuivingsvector toe op deze Matrix in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shearX | float | De horizontale schuiffactor. |
| shearY | float | De verticale schuiffactor. |
| volgorde | int | Een MatrixOrder die de volgorde (toevoegen of voorafgaand) specificeert waarin de schuif wordt toegepast. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.drawing.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Past een met de klok mee rotatie toe op deze Matrix rond het punt dat is opgegeven in de puntparameter, en door de rotatie voor te voegen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | float | De hoek (omvang) van de rotatie, in graden. |
| point | [PointF](../../com.aspose.drawing/pointf) | Een PointF die het middelpunt van de rotatie weergeeft. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.drawing.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Past een met de klok mee rotatie rond het opgegeven punt toe op deze Matrix in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | float | De hoek van de rotatie, in graden. |
| point | [PointF](../../com.aspose.drawing/pointf) | Een PointF die het middelpunt van de rotatie weergeeft. |
| volgorde | int | Een MatrixOrder die de volgorde (toevoegen of voorafgaand) specificeert waarin de rotatie wordt toegepast. |

### transformPoints(PointF[] pts) {#transformPoints-com.aspose.drawing.PointF---}
```
public void transformPoints(PointF[] pts)
```


Past de geometrische transformatie toe die wordt vertegenwoordigd door deze [Matrix](../../com.aspose.drawing.drawing2d/matrix) op een opgegeven array van punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Een array van [PointF](../../com.aspose.drawing/pointf) structuren die de te transformeren punten vertegenwoordigen. |

### transformPoints(Point[] pts) {#transformPoints-com.aspose.drawing.Point---}
```
public void transformPoints(Point[] pts)
```


Past de geometrische transformatie toe die wordt vertegenwoordigd door deze [Matrix](../../com.aspose.drawing.drawing2d/matrix) op een opgegeven array van punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pts | [Point\[\]](../../com.aspose.drawing/point) | Een array van [Point](../../com.aspose.drawing/point) structuren die de te transformeren punten weergeven. |

### multiply(Matrix matrix) {#multiply-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiply(Matrix matrix)
```


Vermenigvuldigt deze [Matrix](../../com.aspose.drawing.drawing2d/matrix) met de matrix die is opgegeven in de `matrix`-parameter, door de opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix) voor te voegen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | De [Matrix](../../com.aspose.drawing.drawing2d/matrix) waarmee deze [Matrix](../../com.aspose.drawing.drawing2d/matrix) moet worden vermenigvuldigd. |

### multiply(Matrix matrix, int order) {#multiply-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiply(Matrix matrix, int order)
```


Vermenigvuldigt deze [Matrix](../../com.aspose.drawing.drawing2d/matrix) met de matrix die is opgegeven in de `matrix`-parameter, en in de volgorde die is opgegeven in de `order`-parameter.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | De [Matrix](../../com.aspose.drawing.drawing2d/matrix) waarmee deze [Matrix](../../com.aspose.drawing.drawing2d/matrix) moet worden vermenigvuldigd. |
| order | int | De [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) die de volgorde van de vermenigvuldiging weergeeft. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Voeg aan deze [Matrix](../../com.aspose.drawing.drawing2d/matrix) een met de klok mee rotatie toe, rond de oorsprong en met de opgegeven hoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | float | De hoek van de rotatie, in graden. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Past een met de klok mee rotatie toe van een hoeveelheid die is opgegeven in de hoekparameter, rond de oorsprong (nul x- en y-coördinaten) voor deze [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | float | De hoek van de rotatie, in graden. |
| order | int | Een [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) die de volgorde (toevoegen of voorafgaand) specificeert waarin de rotatie op deze [Matrix](../../com.aspose.drawing.drawing2d/matrix) wordt toegepast. |

### reset() {#reset--}
```
public void reset()
```


Reset deze [Matrix](../../com.aspose.drawing.drawing2d/matrix) zodat deze de elementen van de identiteitsmatrix bevat.

