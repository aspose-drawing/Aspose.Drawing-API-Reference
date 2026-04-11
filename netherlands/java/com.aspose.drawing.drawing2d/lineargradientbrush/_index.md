---
title: LinearGradientBrush
second_title: Aspose.Drawing voor Java API-referentie
description: Omvat een met een lineaire gradiënt.
type: docs
weight: 31
url: /nl/java/com.aspose.drawing.drawing2d/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class LinearGradientBrush extends Brush
```

Omvat een [Brush](../../com.aspose.drawing/brush) met een lineaire gradiënt. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse met de opgegeven punten en kleuren. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse met de opgegeven punten en kleuren. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse op basis van een rechthoek, start- en eindkleuren, en een oriëntatiemodus. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse op basis van een rechthoek, start- en eindkleuren, en oriëntatie. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse op basis van een rechthoek, start- en eindkleuren, en een oriëntatiehoek. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse op basis van een rechthoek, start- en eindkleuren, en een oriëntatiehoek. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse op basis van een rechthoek, start- en eindkleuren, en een oriëntatiehoek. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse op basis van een rechthoek, start- en eindkleuren, en een oriëntatiehoek. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLinearColors()](#getLinearColors--) | Haalt of stelt de start- en eindkleuren van de gradiënt in. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.drawing.Color---) | Haalt of stelt de start- en eindkleuren van de gradiënt in. |
| [getRectangle()](#getRectangle--) | Haalt een rechthoekig gebied op dat de start- en eindpunten van de gradiënt definieert. |
| [getGammaCorrection()](#getGammaCorrection--) | Geeft of stelt een waarde in die aangeeft of gamma-correctie is ingeschakeld voor deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Geeft of stelt een waarde in die aangeeft of gamma-correctie is ingeschakeld voor deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getBlend()](#getBlend--) | Geeft of stelt een `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) in die posities en factoren specificeert die een aangepaste afname voor de gradient definiëren. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Geeft of stelt een `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) in die posities en factoren specificeert die een aangepaste afname voor de gradient definiëren. |
| [getInterpolationColors()](#getInterpolationColors--) | Geeft of stelt een [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) in die een meerkleurige lineaire gradient definieert. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Geeft of stelt een [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) in die een meerkleurige lineaire gradient definieert. |
| [getWrapMode()](#getWrapMode--) | Geeft of stelt een `WrapMode`-enumeratie in die de wrap-modus voor deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) aangeeft. |
| [setWrapMode(int value)](#setWrapMode-int-) | Geeft of stelt een `WrapMode`-enumeratie in die de wrap-modus voor deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) aangeeft. |
| [getTransform()](#getTransform--) | Geeft of stelt een kopie van [Matrix](../../com.aspose.drawing.drawing2d/matrix) in die een lokale geometrische transformatie voor deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) definieert. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Geeft of stelt een kopie van [Matrix](../../com.aspose.drawing.drawing2d/matrix) in die een lokale geometrische transformatie voor deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) definieert. |
| [deepClone()](#deepClone--) | Maakt een exacte kopie van deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Maakt een gradient-afname op basis van een klokvormige curve. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Maakt een gradient-afname op basis van een klokvormige curve. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Maakt een lineaire gradient met een middenkleur en een lineaire afname naar één kleur aan beide uiteinden. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Maakt een lineaire gradient met een middenkleur en een lineaire afname naar één kleur aan beide uiteinden. |
| [resetTransform()](#resetTransform--) | Reset de `LinearGradientBrush.Transform`-eigenschap naar de identiteit. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Vermenigvuldigt de [Matrix](../../com.aspose.drawing.drawing2d/matrix) die de lokale geometrische transformatie van deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) weergeeft met de opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix) door de opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix) voor te voegen. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Vermenigvuldigt de [Matrix](../../com.aspose.drawing.drawing2d/matrix) die de lokale geometrische transformatie van deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) weergeeft met de opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix) in de opgegeven volgorde. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschuift de lokale geometrische transformatie met de opgegeven afmetingen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Verschuift de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden in de opgegeven volgorde. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde. |
### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse met de opgegeven punten en kleuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | Een [PointF](../../com.aspose.drawing/pointf)-structuur die het startpunt van de lineaire gradient weergeeft. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | Een [PointF](../../com.aspose.drawing/pointf)-structuur die het eindpunt van de lineaire gradient weergeeft. |
| color1 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color)-structuur die de startkleur van de lineaire gradient weergeeft. |
| color2 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color)-structuur die de eindkleur van de lineaire gradient weergeeft. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse met de opgegeven punten en kleuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | Een [Point](../../com.aspose.drawing/point)-structuur die het startpunt van de lineaire gradient weergeeft. |
| point2 | [Point](../../com.aspose.drawing/point) | Een [Point](../../com.aspose.drawing/point)-structuur die het eindpunt van de lineaire gradient weergeeft. |
| color1 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color)-structuur die de startkleur van de lineaire gradient weergeeft. |
| color2 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color)-structuur die de eindkleur van de lineaire gradient weergeeft. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)
```


Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse op basis van een rechthoek, start- en eindkleuren, en een oriëntatiemodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Een [RectangleF](../../com.aspose.drawing/rectanglef)-structuur die de grenzen van de lineaire gradient specificeert. |
| color1 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color)-structuur die de startkleur voor de gradient weergeeft. |
| color2 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color) structuur die de eindkleur voor de gradient weergeeft. |
| linearGradientMode | int | Een [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) enumeratie‑element dat de oriëntatie van de gradient specificeert. De oriëntatie bepaalt de begin‑ en eindpunten van de gradient. Bijvoorbeeld, LinearGradientMode.ForwardDiagonal geeft aan dat het beginpunt de linkerbovenhoek van de rechthoek is en het eindpunt de rechteronderhoek van de rechthoek. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)
```


Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse op basis van een rechthoek, start- en eindkleuren, en oriëntatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Een `Rectangle`([.getRectangle](../../null/\#getRectangle)) structuur die de grenzen van de lineaire gradient specificeert. |
| color1 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color)-structuur die de startkleur voor de gradient weergeeft. |
| color2 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color) structuur die de eindkleur voor de gradient weergeeft. |
| linearGradientMode | int | Een [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) enumeratie‑element dat de oriëntatie van de gradient specificeert. De oriëntatie bepaalt de begin‑ en eindpunten van de gradient. Bijvoorbeeld, LinearGradientMode.ForwardDiagonal geeft aan dat het beginpunt de linkerbovenhoek van de rechthoek is en het eindpunt de rechteronderhoek van de rechthoek. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse op basis van een rechthoek, start- en eindkleuren, en een oriëntatiehoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Een [RectangleF](../../com.aspose.drawing/rectanglef)-structuur die de grenzen van de lineaire gradient specificeert. |
| color1 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color)-structuur die de startkleur voor de gradient weergeeft. |
| color2 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color) structuur die de eindkleur voor de gradient weergeeft. |
| hoek | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradient. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse op basis van een rechthoek, start- en eindkleuren, en een oriëntatiehoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Een [RectangleF](../../com.aspose.drawing/rectanglef)-structuur die de grenzen van de lineaire gradient specificeert. |
| color1 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color)-structuur die de startkleur voor de gradient weergeeft. |
| color2 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color) structuur die de eindkleur voor de gradient weergeeft. |
| hoek | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradient. |
| isAngleScaleable | boolean | Stel in op true om aan te geven dat de hoek wordt beïnvloed door de transformatie die aan deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) is gekoppeld; anders false. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse op basis van een rechthoek, start- en eindkleuren, en een oriëntatiehoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Een `Rectangle`([.getRectangle](../../null/\#getRectangle)) structuur die de grenzen van de lineaire gradient specificeert. |
| color1 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color)-structuur die de startkleur voor de gradient weergeeft. |
| color2 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color) structuur die de eindkleur voor de gradient weergeeft. |
| hoek | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradient. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Initialiseert een nieuw exemplaar van de [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) klasse op basis van een rechthoek, start- en eindkleuren, en een oriëntatiehoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Een `Rectangle`([.getRectangle](../../null/\#getRectangle)) structuur die de grenzen van de lineaire gradient specificeert. |
| color1 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color)-structuur die de startkleur voor de gradient weergeeft. |
| color2 | [Color](../../com.aspose.drawing/color) | Een [Color](../../com.aspose.drawing/color) structuur die de eindkleur voor de gradient weergeeft. |
| hoek | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradient. |
| isAngleScaleable | boolean | Stel in op true om aan te geven dat de hoek wordt beïnvloed door de transformatie die aan deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) is gekoppeld; anders false. |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Haalt of stelt de start- en eindkleuren van de gradiënt in.

**Returns:**
com.aspose.drawing.Color[]
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.drawing.Color---}
```
public void setLinearColors(Color[] value)
```


Haalt of stelt de start- en eindkleuren van de gradiënt in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Haalt een rechthoekig gebied op dat de start- en eindpunten van de gradiënt definieert.

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Geeft of stelt een waarde in die aangeeft of gamma-correctie is ingeschakeld voor deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
boolean
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Geeft of stelt een waarde in die aangeeft of gamma-correctie is ingeschakeld voor deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

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

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Geeft of stelt een `WrapMode`-enumeratie in die de wrap-modus voor deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) aangeeft.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Geeft of stelt een `WrapMode`-enumeratie in die de wrap-modus voor deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) aangeeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Geeft of stelt een kopie van [Matrix](../../com.aspose.drawing.drawing2d/matrix) in die een lokale geometrische transformatie voor deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) definieert.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Geeft of stelt een kopie van [Matrix](../../com.aspose.drawing.drawing2d/matrix) in die een lokale geometrische transformatie voor deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) definieert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Maakt een exacte kopie van deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
java.lang.Object - De [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) die deze methode maakt, gecast als een object.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Maakt een gradient-afname op basis van een klokvormige curve.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| focus | float | Een waarde van 0 tot 1 die het centrum van de gradient specificeert (het punt waar de startkleur en eindkleur gelijkmatig worden gemengd). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Maakt een gradient-afname op basis van een klokvormige curve.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| focus | float | Een waarde van 0 tot 1 die het centrum van de gradient specificeert (het punt waar de gradient uitsluitend uit de eindkleur bestaat). |
| schaal | float | Een waarde van 0 tot 1 die aangeeft hoe snel de kleuren afnemen vanaf de `focus`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Maakt een lineaire gradient met een middenkleur en een lineaire afname naar één kleur aan beide uiteinden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| focus | float | Een waarde van 0 tot 1 die het centrum van de gradient specificeert (het punt waar de gradient uitsluitend uit de eindkleur bestaat). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Maakt een lineaire gradient met een middenkleur en een lineaire afname naar één kleur aan beide uiteinden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| focus | float | Een waarde van 0 tot 1 die het centrum van de gradient specificeert (het punt waar de gradient uitsluitend uit de eindkleur bestaat). |
| schaal | float | Een waarde van 0 tot 1 die aangeeft hoe snel de kleuren afnemen van de startkleur naar de `focus` (eindkleur). |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Reset de `LinearGradientBrush.Transform`-eigenschap naar de identiteit.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Vermenigvuldigt de [Matrix](../../com.aspose.drawing.drawing2d/matrix) die de lokale geometrische transformatie van deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) weergeeft met de opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix) door de opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix) voor te voegen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | De [Matrix](../../com.aspose.drawing.drawing2d/matrix) waarmee de geometrische transformatie wordt vermenigvuldigd. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Vermenigvuldigt de [Matrix](../../com.aspose.drawing.drawing2d/matrix) die de lokale geometrische transformatie van deze [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) weergeeft met de opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix) in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | De [Matrix](../../com.aspose.drawing.drawing2d/matrix) waarmee de geometrische transformatie wordt vermenigvuldigd. |
| order | int | Een [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) die aangeeft in welke volgorde de twee matrices worden vermenigvuldigd. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. Deze methode plaatst de translatie vóór de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Verschuift de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde.

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
| sx | float | De hoeveelheid waarmee de transformatie in de x-richting wordt geschaald. |
| sy | float | De hoeveelheid waarmee de transformatie in de y-richting wordt geschaald. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sx | float | De hoeveelheid waarmee de transformatie in de x-richting wordt geschaald. |
| sy | float | De hoeveelheid waarmee de transformatie in de y-richting wordt geschaald. |
| order | int | Een [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) die aangeeft of de schaalmatrix moet worden toegevoegd of voorafgeplaatst. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid. Deze methode plaatst de rotatie vóór de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | float | De rotatiehoek. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | float | De rotatiehoek. |
| order | int | Een [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) die aangeeft of de rotatiematrix moet worden toegevoegd of voorafgeplaatst. |

