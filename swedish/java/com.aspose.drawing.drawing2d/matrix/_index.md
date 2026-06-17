---
title: Matrix
second_title: Aspose.Drawing för Java API‑referens
description: Inkapslar en 3×3 affinkmatris som representerar en geometrisk transformation.
type: docs
weight: 33
url: /sv/java/com.aspose.drawing.drawing2d/matrix/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Matrix implements System.IDisposable
```

Inkapslar en 3×3 affinkommatris som representerar en geometrisk transformation. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Matrix()](#Matrix--) | Initierar en ny instans av Matrix-klassen som identitetsmatris. |
| [Matrix(float m11, float m12, float m21, float m22, float dx, float dy)](#Matrix-float-float-float-float-float-float-) | Initierar en ny instans av Matrix-klassen med de angivna elementen. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---) | Initierar en ny instans av [Matrix](../../com.aspose.drawing.drawing2d/matrix)-klassen till den geometriska transformation som definieras av den angivna rektangeln och punktarrayen. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---) | Initierar en ny instans av [Matrix](../../com.aspose.drawing.drawing2d/matrix)-klassen till den geometriska transformation som definieras av den angivna rektangeln och punktarrayen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [IdentityTransform](#IdentityTransform) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getElements()](#getElements--) | Hämtar en array av flyttal som representerar elementen i denna Matrix. |
| [isIdentity()](#isIdentity--) | Hämtar ett värde som indikerar om denna Matrix är identitetsmatrisen. |
| [isInvertible()](#isInvertible--) | Hämtar ett värde som indikerar om denna Matrix är inverterbar. |
| [getOffsetX()](#getOffsetX--) | Hämtar x‑översättningsvärdet (dx‑värdet, eller elementet i den tredje raden och första kolumnen) för denna Matrix. |
| [getOffsetY()](#getOffsetY--) | Hämtar y‑översättningsvärdet (värdet `dy`, eller elementet i den tredje raden och andra kolumnen) för denna Matrix. |
| [dispose()](#dispose--) | Frigör alla resurser som används av denna Matrix. |
| [deepClone()](#deepClone--) | Skapar en exakt kopia av denna Matrix. |
| [invert()](#invert--) | Inverterar denna Matrix, om den är inverterbar. |
| [translate(float offsetX, float offsetY)](#translate-float-float-) | Tillämpar den angivna translationsvektorn (offsetX och offsetY) på denna Matrix genom att föregå med translationsvektorn. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Tillämpar den angivna translationsvektorn på denna Matrix i den angivna ordningen. |
| [transformVectors(PointF[] pts)](#transformVectors-com.aspose.drawing.PointF---) | Multiplicerar varje vektor i en array med matrisen. |
| [scale(float scaleX, float scaleY)](#scale-float-float-) | Tillämpar den angivna skalningsvektorn på denna Matrix genom att föregå med skalningsvektorn. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Tillämpar den angivna skalningsvektorn (scaleX och scaleY) på denna Matrix med den angivna ordningen. |
| [shear(float shearX, float shearY)](#shear-float-float-) | Tillämpar den angivna skevningsvektorn på denna Matrix genom att föregå med skevningstransformationen. |
| [shear(float shearX, float shearY, int order)](#shear-float-float-int-) | Tillämpar den angivna skevningsvektorn på denna Matrix i den angivna ordningen. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.drawing.PointF-) | Tillämpar en medurs rotation på denna Matrix runt den punkt som anges i punkt‑parametern, och genom att föregå med rotationen. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.drawing.PointF-int-) | Tillämpar en medurs rotation kring den angivna punkten på denna Matrix i den angivna ordningen. |
| [transformPoints(PointF[] pts)](#transformPoints-com.aspose.drawing.PointF---) | Tillämpar den geometriska transformationen som representeras av denna [Matrix](../../com.aspose.drawing.drawing2d/matrix) på en angiven array av punkter. |
| [transformPoints(Point[] pts)](#transformPoints-com.aspose.drawing.Point---) | Tillämpar den geometriska transformationen som representeras av denna [Matrix](../../com.aspose.drawing.drawing2d/matrix) på en angiven array av punkter. |
| [multiply(Matrix matrix)](#multiply-com.aspose.drawing.drawing2d.Matrix-) | Multiplicerar denna [Matrix](../../com.aspose.drawing.drawing2d/matrix) med matrisen som anges i parametern `matrix`, genom att föregå med den angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [multiply(Matrix matrix, int order)](#multiply-com.aspose.drawing.drawing2d.Matrix-int-) | Multiplicerar denna [Matrix](../../com.aspose.drawing.drawing2d/matrix) med matrisen som anges i parametern `matrix`, och i den ordning som anges i parametern `order`. |
| [rotate(float angle)](#rotate-float-) | Föregå denna [Matrix](../../com.aspose.drawing.drawing2d/matrix) med en medurs rotation, runt origo och med den angivna vinkeln. |
| [rotate(float angle, int order)](#rotate-float-int-) | Tillämpar en medurs rotation i den mängd som anges i vinkel‑parametern, runt origo (noll x‑ och y‑koordinater) för denna [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [reset()](#reset--) | Återställer denna [Matrix](../../com.aspose.drawing.drawing2d/matrix) så att den har elementen i identitetsmatrisen. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Initierar en ny instans av Matrix-klassen som identitetsmatris.

### Matrix(float m11, float m12, float m21, float m22, float dx, float dy) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


Initierar en ny instans av Matrix-klassen med de angivna elementen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| m11 | flyttal | Värdet i den första raden och första kolumnen i den nya Matrix. |
| m12 | flyttal | Värdet i den första raden och andra kolumnen i den nya Matrix. |
| m21 | flyttal | Värdet i den andra raden och första kolumnen i den nya matrisen. |
| m22 | flyttal | Värdet i den andra raden och andra kolumnen i den nya matrisen. |
| dx | flyttal | Värdet i den tredje raden och första kolumnen i den nya matrisen. |
| dy | flyttal | Värdet i den tredje raden och andra kolumnen i den nya matrisen. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Initierar en ny instans av [Matrix](../../com.aspose.drawing.drawing2d/matrix)-klassen till den geometriska transformation som definieras av den angivna rektangeln och punktarrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | En [Rectangle](../../com.aspose.drawing/rectangle)-struktur som representerar rektangeln som ska transformeras. |
| plgpts | [Point\[\]](../../com.aspose.drawing/point) | En array med tre [Point](../../com.aspose.drawing/point)-strukturer som representerar punkterna i ett parallellogram till vilket det övre vänstra, övre högra och nedre vänstra hörnet av rektangeln ska transformeras. Det nedre högra hörnet av parallellogrammet antas av de första tre hörnen. |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Initierar en ny instans av [Matrix](../../com.aspose.drawing.drawing2d/matrix)-klassen till den geometriska transformation som definieras av den angivna rektangeln och punktarrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | En [RectangleF](../../com.aspose.drawing/rectanglef)-struktur som representerar rektangeln som ska transformeras. |
| plgpts | [PointF\[\]](../../com.aspose.drawing/pointf) | En array med tre [PointF](../../com.aspose.drawing/pointf)-strukturer som representerar punkterna i ett parallellogram till vilket det övre vänstra, övre högra och nedre vänstra hörnet av rektangeln ska transformeras. Det nedre högra hörnet av parallellogrammet antas av de första tre hörnen. |

### IdentityTransform {#IdentityTransform}
```
public static final Matrix IdentityTransform
```


### getElements() {#getElements--}
```
public float[] getElements()
```


Hämtar en array av flyttal som representerar elementen i denna Matrix.

**Returns:**
float[] – en array med flyttal som representerar elementen i denna matris.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Hämtar ett värde som indikerar om denna Matrix är identitetsmatrisen.

**Returns:**
boolean – ett värde som indikerar om denna matris är identitetsmatrisen.
### isInvertible() {#isInvertible--}
```
public boolean isInvertible()
```


Hämtar ett värde som indikerar om denna Matrix är inverterbar.

**Returns:**
boolean – ett värde som indikerar om denna matris är inverterbar.
### getOffsetX() {#getOffsetX--}
```
public float getOffsetX()
```


Hämtar x‑översättningsvärdet (dx‑värdet, eller elementet i den tredje raden och första kolumnen) för denna Matrix.

**Returns:**
float – x‑översättningsvärdet (dx‑värdet, eller elementet i den tredje raden och första kolumnen) för denna matris.
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```


Hämtar y‑översättningsvärdet (värdet `dy`, eller elementet i den tredje raden och andra kolumnen) för denna Matrix.

**Returns:**
float – y‑översättningsvärdet (det `dy`‑värdet, eller elementet i den tredje raden och andra kolumnen) för denna matris.
### dispose() {#dispose--}
```
public void dispose()
```


Frigör alla resurser som används av denna Matrix.

--------------------

Denna metod gör faktiskt ingenting. Den finns bara för kompatibilitet med System.Drawing‑API:et.

### deepClone() {#deepClone--}
```
public Matrix deepClone()
```


Skapar en exakt kopia av denna Matrix.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - The Matrix that this method creates.
### invert() {#invert--}
```
public void invert()
```


Inverterar denna Matrix, om den är inverterbar.

### translate(float offsetX, float offsetY) {#translate-float-float-}
```
public void translate(float offsetX, float offsetY)
```


Tillämpar den angivna translationsvektorn (offsetX och offsetY) på denna Matrix genom att föregå med translationsvektorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| offsetX | flyttal | x‑värdet som matrisen ska översättas med. |
| offsetY | flyttal | y‑värdet som matrisen ska översättas med. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Tillämpar den angivna translationsvektorn på denna Matrix i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| offsetX | flyttal | x‑värdet som matrisen ska översättas med. |
| offsetY | flyttal | y‑värdet som matrisen ska översättas med. |
| ordning | int | En MatrixOrder som specificerar ordningen (append eller prepend) i vilken översättningen appliceras på denna matris. |

### transformVectors(PointF[] pts) {#transformVectors-com.aspose.drawing.PointF---}
```
public void transformVectors(PointF[] pts)
```


Multiplicerar varje vektor i en array med matrisen. Översättningselementen i denna matris (tredje raden) ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | En array med [PointF](../../com.aspose.drawing/pointf)-strukturer som representerar punkterna att transformera. |

### scale(float scaleX, float scaleY) {#scale-float-float-}
```
public void scale(float scaleX, float scaleY)
```


Tillämpar den angivna skalningsvektorn på denna Matrix genom att föregå med skalningsvektorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scaleX | flyttal | Värdet som matrisen ska skalas med i x‑axelns riktning. |
| scaleY | flyttal | Värdet som används för att skala denna Matrix i y‑axelns riktning. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Tillämpar den angivna skalningsvektorn (scaleX och scaleY) på denna Matrix med den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scaleX | flyttal | Värdet som matrisen ska skalas med i x‑axelns riktning. |
| scaleY | flyttal | Värdet som används för att skala denna Matrix i y‑axelns riktning. |
| ordning | int | En MatrixOrder som specificerar ordningen (append eller prepend) i vilken skalfaktorn tillämpas på denna Matrix. |

### shear(float shearX, float shearY) {#shear-float-float-}
```
public void shear(float shearX, float shearY)
```


Tillämpar den angivna skevningsvektorn på denna Matrix genom att föregå med skevningstransformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shearX | flyttal | Den horisontella skevningsfaktorn. |
| shearY | flyttal | Den vertikala skevningsfaktorn. |

### shear(float shearX, float shearY, int order) {#shear-float-float-int-}
```
public void shear(float shearX, float shearY, int order)
```


Tillämpar den angivna skevningsvektorn på denna Matrix i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shearX | flyttal | Den horisontella skevningsfaktorn. |
| shearY | flyttal | Den vertikala skevningsfaktorn. |
| ordning | int | En MatrixOrder som specificerar ordningen (append eller prepend) i vilken skevning tillämpas. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.drawing.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Tillämpar en medurs rotation på denna Matrix runt den punkt som anges i punkt‑parametern, och genom att föregå med rotationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | flyttal | Vinkeln (omfånget) för rotationen, i grader. |
| point | [PointF](../../com.aspose.drawing/pointf) | En PointF som representerar rotationscentrum. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.drawing.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Tillämpar en medurs rotation kring den angivna punkten på denna Matrix i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | flyttal | Vinkeln för rotationen, i grader. |
| point | [PointF](../../com.aspose.drawing/pointf) | En PointF som representerar rotationscentrum. |
| ordning | int | En MatrixOrder som specificerar ordningen (append eller prepend) i vilken rotationen tillämpas. |

### transformPoints(PointF[] pts) {#transformPoints-com.aspose.drawing.PointF---}
```
public void transformPoints(PointF[] pts)
```


Tillämpar den geometriska transformationen som representeras av denna [Matrix](../../com.aspose.drawing.drawing2d/matrix) på en angiven array av punkter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | En array med [PointF](../../com.aspose.drawing/pointf)-strukturer som representerar punkterna att transformera. |

### transformPoints(Point[] pts) {#transformPoints-com.aspose.drawing.Point---}
```
public void transformPoints(Point[] pts)
```


Tillämpar den geometriska transformationen som representeras av denna [Matrix](../../com.aspose.drawing.drawing2d/matrix) på en angiven array av punkter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pts | [Point\[\]](../../com.aspose.drawing/point) | En array av [Point](../../com.aspose.drawing/point)-strukturer som representerar punkterna som ska transformeras. |

### multiply(Matrix matrix) {#multiply-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiply(Matrix matrix)
```


Multiplicerar denna [Matrix](../../com.aspose.drawing.drawing2d/matrix) med matrisen som anges i parametern `matrix`, genom att föregå med den angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Den [Matrix](../../com.aspose.drawing.drawing2d/matrix) med vilken denna [Matrix](../../com.aspose.drawing.drawing2d/matrix) ska multipliceras. |

### multiply(Matrix matrix, int order) {#multiply-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiply(Matrix matrix, int order)
```


Multiplicerar denna [Matrix](../../com.aspose.drawing.drawing2d/matrix) med matrisen som anges i parametern `matrix`, och i den ordning som anges i parametern `order`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Den [Matrix](../../com.aspose.drawing.drawing2d/matrix) med vilken denna [Matrix](../../com.aspose.drawing.drawing2d/matrix) ska multipliceras. |
| order | int | Den [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) som representerar multiplikationsordningen. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Föregå denna [Matrix](../../com.aspose.drawing.drawing2d/matrix) med en medurs rotation, runt origo och med den angivna vinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | flyttal | Vinkeln för rotationen, i grader. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Tillämpar en medurs rotation i den mängd som anges i vinkel‑parametern, runt origo (noll x‑ och y‑koordinater) för denna [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | flyttal | Vinkeln för rotationen, i grader. |
| order | int | En [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) som specificerar ordningen (append eller prepend) i vilken rotationen tillämpas på denna [Matrix](../../com.aspose.drawing.drawing2d/matrix). |

### reset() {#reset--}
```
public void reset()
```


Återställer denna [Matrix](../../com.aspose.drawing.drawing2d/matrix) så att den har elementen i identitetsmatrisen.

