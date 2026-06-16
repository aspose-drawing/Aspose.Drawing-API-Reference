---
title: PathGradientBrush
second_title: Aspose.Drawing voor Java API-referentie
description: Omvat een object dat de binnenkant van een object vult met een gradient.
type: docs
weight: 36
url: /nl/java/com.aspose.drawing.drawing2d/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class PathGradientBrush extends Brush
```

Omvat een [Brush](../../com.aspose.drawing/brush) object dat de binnenkant van een [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) object vult met een gradient. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.drawing.PointF---) | Initialiseert een nieuwe instantie van de [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) klasse met de opgegeven punten. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.PointF---int-) | Initialiseert een nieuwe instantie van de [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) klasse met de opgegeven punten en wrap-modus. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.drawing.Point---) | Initialiseert een nieuwe instantie van de [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) klasse met de opgegeven punten. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.Point---int-) | Initialiseert een nieuwe instantie van de [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) klasse met de opgegeven punten en wrap-modus. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-) | Initialiseert een nieuwe instantie van de [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) klasse met het opgegeven pad. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCenterColor()](#getCenterColor--) | Krijgt of stelt de kleur in het centrum van de padgradient in. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.drawing.Color-) | Krijgt of stelt de kleur in het centrum van de padgradient in. |
| [getSurroundColors()](#getSurroundColors--) | Krijgt of stelt een array van kleuren in die overeenkomen met de punten in het pad dat deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) vult. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.drawing.Color---) | Krijgt of stelt een array van kleuren in die overeenkomen met de punten in het pad dat deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) vult. |
| [getCenterPoint()](#getCenterPoint--) | Krijgt of stelt het middelpunt van de padgradient in. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.drawing.PointF-) | Krijgt of stelt het middelpunt van de padgradient in. |
| [getRectangle()](#getRectangle--) | Haalt een begrenzende rechthoek op voor deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getBlend()](#getBlend--) | Geeft of stelt een `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) in die posities en factoren specificeert die een aangepaste afname voor de gradient definiëren. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Geeft of stelt een `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) in die posities en factoren specificeert die een aangepaste afname voor de gradient definiëren. |
| [getInterpolationColors()](#getInterpolationColors--) | Geeft of stelt een [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) in die een meerkleurige lineaire gradient definieert. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Geeft of stelt een [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) in die een meerkleurige lineaire gradient definieert. |
| [getTransform()](#getTransform--) | Krijgt of stelt een kopie van de [Matrix](../../com.aspose.drawing.drawing2d/matrix) in die een lokale geometrische transformatie definieert voor deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Krijgt of stelt een kopie van de [Matrix](../../com.aspose.drawing.drawing2d/matrix) in die een lokale geometrische transformatie definieert voor deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getFocusScales()](#getFocusScales--) | Krijgt of stelt het focuspunt voor de gradient-afname in. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.drawing.PointF-) | Krijgt of stelt het focuspunt voor de gradient-afname in. |
| [getWrapMode()](#getWrapMode--) | Krijgt of stelt een `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) in die de wrap-modus aangeeft voor deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | Krijgt of stelt een `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) in die de wrap-modus aangeeft voor deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [deepClone()](#deepClone--) | Maakt een exacte kopie van deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Maakt een gradientkwast die de kleur verandert, beginnend vanaf het centrum van het pad naar de rand van het pad. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Maakt een gradientkwast die de kleur verandert, beginnend vanaf het centrum van het pad naar de rand van het pad. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Maakt een gradient met een centrale kleur en een lineaire afname naar één omringende kleur. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Maakt een verloop met een middelkleur en een lineaire afname naar elke omringende kleur. |
| [resetTransform()](#resetTransform--) | Stelt de `PathGradientBrush.Transform`-eigenschap opnieuw in op de identiteit. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Werkt de transformatie‑matrix van de penseel bij met het product van de transformatie‑matrix van de penseel vermenigvuldigd met een andere matrix. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Werkt de transformatie‑matrix van de penseel bij met het product van de transformatie‑matrix van de penseel vermenigvuldigd met een andere matrix. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Past de opgegeven translatie toe op de lokale geometrische transformatie. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Past de opgegeven translatie toe op de lokale geometrische transformatie in de opgegeven volgorde. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden in de opgegeven volgorde. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.drawing.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Initialiseert een nieuwe instantie van de [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) klasse met de opgegeven punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Een array van [PointF](../../com.aspose.drawing/pointf)-structuren die de punten vertegenwoordigen die de hoekpunten van het pad vormen. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Initialiseert een nieuwe instantie van de [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) klasse met de opgegeven punten en wrap-modus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Een array van [PointF](../../com.aspose.drawing/pointf)-structuren die de punten vertegenwoordigen die de hoekpunten van het pad vormen. |
| wrapMode | int | Een `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) die specificeert hoe vullingen die met deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) worden getekend, worden getegeld. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.drawing.Point---}
```
public PathGradientBrush(Point[] points)
```


Initialiseert een nieuwe instantie van de [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) klasse met de opgegeven punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Een array van [Point](../../com.aspose.drawing/point)-structuren die de punten vertegenwoordigen die de hoekpunten van het pad vormen. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Initialiseert een nieuwe instantie van de [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) klasse met de opgegeven punten en wrap-modus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Een array van [Point](../../com.aspose.drawing/point)-structuren die de punten vertegenwoordigen die de hoekpunten van het pad vormen. |
| wrapMode | int | Een `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) die specificeert hoe vullingen die met deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) worden getekend, worden getegeld. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Initialiseert een nieuwe instantie van de [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) klasse met het opgegeven pad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | De [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) die het gebied definieert dat wordt gevuld door deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Krijgt of stelt de kleur in het centrum van de padgradient in.

**Returns:**
[Color](../../com.aspose.drawing/color)
### setCenterColor(Color value) {#setCenterColor-com.aspose.drawing.Color-}
```
public void setCenterColor(Color value)
```


Krijgt of stelt de kleur in het centrum van de padgradient in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Krijgt of stelt een array van kleuren in die overeenkomen met de punten in het pad dat deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) vult.

**Returns:**
com.aspose.drawing.Color[]
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.drawing.Color---}
```
public void setSurroundColors(Color[] value)
```


Krijgt of stelt een array van kleuren in die overeenkomen met de punten in het pad dat deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) vult.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Krijgt of stelt het middelpunt van de padgradient in.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.drawing.PointF-}
```
public void setCenterPoint(PointF value)
```


Krijgt of stelt het middelpunt van de padgradient in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Haalt een begrenzende rechthoek op voor deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Geeft of stelt een `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) in die posities en factoren specificeert die een aangepaste afname voor de gradient definiëren.

**Returns:**
[Blend](../../com.aspose.drawing.drawing2d/blend)
### setBlend(Blend value) {#setBlend-com.aspose.drawing.drawing2d.Blend-}
```
public void setBlend(Blend value)
```


Geeft of stelt een `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) in die posities en factoren specificeert die een aangepaste afname voor de gradient definiëren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Blend](../../com.aspose.drawing.drawing2d/blend) |  |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Geeft of stelt een [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) in die een meerkleurige lineaire gradient definieert.

**Returns:**
[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Geeft of stelt een [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) in die een meerkleurige lineaire gradient definieert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Krijgt of stelt een kopie van de [Matrix](../../com.aspose.drawing.drawing2d/matrix) in die een lokale geometrische transformatie definieert voor deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Krijgt of stelt een kopie van de [Matrix](../../com.aspose.drawing.drawing2d/matrix) in die een lokale geometrische transformatie definieert voor deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Krijgt of stelt het focuspunt voor de gradient-afname in.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setFocusScales(PointF value) {#setFocusScales-com.aspose.drawing.PointF-}
```
public void setFocusScales(PointF value)
```


Krijgt of stelt het focuspunt voor de gradient-afname in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Krijgt of stelt een `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) in die de wrap-modus aangeeft voor deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Krijgt of stelt een `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) in die de wrap-modus aangeeft voor deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Maakt een exacte kopie van deze [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
java.lang.Object - De [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) die deze methode maakt, gecast als een object.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Maakt een verlooppenseel dat van kleur verandert, beginnend vanaf het midden van het pad naar de rand van het pad. De overgang van de ene kleur naar de andere is gebaseerd op een klokvormige curve.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| focus | float | Een waarde van 0 tot 1 die aangeeft waar, langs elke radiaal van het midden van het pad naar de rand van het pad, de middelkleur de hoogste intensiteit heeft. Een waarde van 1 (de standaard) plaatst de hoogste intensiteit in het midden van het pad. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Maakt een verlooppenseel dat van kleur verandert, beginnend vanaf het midden van het pad naar de rand van het pad. De overgang van de ene kleur naar de andere is gebaseerd op een klokvormige curve.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| focus | float | Een waarde van 0 tot 1 die aangeeft waar, langs elke radiaal van het midden van het pad naar de rand van het pad, de middelkleur de hoogste intensiteit heeft. Een waarde van 1 (de standaard) plaatst de hoogste intensiteit in het midden van het pad. |
| schaal | float | Een waarde van 0 tot 1 die de maximale intensiteit van de middelkleur specificeert die wordt gemengd met de randkleur. Een waarde van 1 veroorzaakt de hoogst mogelijke intensiteit van de middelkleur, en dit is de standaardwaarde. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Maakt een gradient met een centrale kleur en een lineaire afname naar één omringende kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| focus | float | Een waarde van 0 tot 1 die aangeeft waar, langs elke radiaal van het midden van het pad naar de rand van het pad, de middelkleur de hoogste intensiteit heeft. Een waarde van 1 (de standaard) plaatst de hoogste intensiteit in het midden van het pad. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Maakt een verloop met een middelkleur en een lineaire afname naar elke omringende kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| focus | float | Een waarde van 0 tot 1 die aangeeft waar, langs elke radiaal van het midden van het pad naar de rand van het pad, de middelkleur de hoogste intensiteit heeft. Een waarde van 1 (de standaard) plaatst de hoogste intensiteit in het midden van het pad. |
| schaal | float | Een waarde van 0 tot 1 die de maximale intensiteit van de middelkleur specificeert die wordt gemengd met de randkleur. Een waarde van 1 veroorzaakt de hoogst mogelijke intensiteit van de middelkleur, en dit is de standaardwaarde. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Stelt de `PathGradientBrush.Transform`-eigenschap opnieuw in op de identiteit.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Werkt de transformatie‑matrix van de penseel bij met het product van de transformatie‑matrix van de penseel vermenigvuldigd met een andere matrix.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | De [Matrix](../../com.aspose.drawing.drawing2d/matrix) die wordt vermenigvuldigd met de huidige transformatie‑matrix van de penseel. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Werkt de transformatie‑matrix van de penseel bij met het product van de transformatie‑matrix van de penseel vermenigvuldigd met een andere matrix.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | De [Matrix](../../com.aspose.drawing.drawing2d/matrix) die wordt vermenigvuldigd met de huidige transformatie‑matrix van de penseel. |
| order | int | Een [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) die aangeeft in welke volgorde de twee matrices worden vermenigvuldigd. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Past de opgegeven translatie toe op de lokale geometrische transformatie. Deze methode plaatst de translatie vóór de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Past de opgegeven translatie toe op de lokale geometrische transformatie in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |
| volgorde | int | De volgorde (voorgaan of toevoegen) waarin de translatie wordt toegepast. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Schaalt de lokale geometrische transformatie met de opgegeven waarden. Deze methode plaatst de schaalmatrix vóór de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sx | float | De schaalfactor van de transformatie in de x-as. |
| sy | float | De schaalfactor van de transformatie in de y-as. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sx | float | De schaalfactor van de transformatie in de x-as. |
| sy | float | De schaalfactor van de transformatie in de y-as. |
| order | int | Een [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) die aangeeft of de schaalmatrix moet worden toegevoegd of voorafgeplaatst. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid. Deze methode plaatst de rotatie vóór de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | float | De hoek (reikwijdte) van rotatie. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | float | De hoek (reikwijdte) van rotatie. |
| order | int | Een [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) die aangeeft of de rotatiematrix moet worden toegevoegd of voorafgeplaatst. |

