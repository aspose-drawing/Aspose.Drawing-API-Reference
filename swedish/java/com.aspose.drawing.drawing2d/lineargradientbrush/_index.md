---
title: LinearGradientBrush
second_title: Aspose.Drawing för Java API‑referens
description: Inkapslar en  med en linjär gradient.
type: docs
weight: 31
url: /sv/java/com.aspose.drawing.drawing2d/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class LinearGradientBrush extends Brush
```

Inkapslar en [Brush](../../com.aspose.drawing/brush) med en linjär gradient. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) med de angivna punkterna och färgerna. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) med de angivna punkterna och färgerna. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) baserad på en rektangel, start- och slutfärger samt ett orienteringsläge. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) baserad på en rektangel, start- och slutfärger samt orientering. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLinearColors()](#getLinearColors--) | Hämtar eller anger start- och slutfärgerna för gradienten. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.drawing.Color---) | Hämtar eller anger start- och slutfärgerna för gradienten. |
| [getRectangle()](#getRectangle--) | Hämtar en rektangulär region som definierar start- och slutpunkterna för gradienten. |
| [getGammaCorrection()](#getGammaCorrection--) | Hämtar eller anger ett värde som indikerar om gamma‑korrektion är aktiverad för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Hämtar eller anger ett värde som indikerar om gamma‑korrektion är aktiverad för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getBlend()](#getBlend--) | Hämtar eller anger ett `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Hämtar eller anger ett `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| [getInterpolationColors()](#getInterpolationColors--) | Hämtar eller anger ett [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) som definierar en flerfärgad linjär gradient. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Hämtar eller anger ett [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) som definierar en flerfärgad linjär gradient. |
| [getWrapMode()](#getWrapMode--) | Hämtar eller anger en `WrapMode`‑enumeration som indikerar omslagsläget för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | Hämtar eller anger en `WrapMode`‑enumeration som indikerar omslagsläget för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getTransform()](#getTransform--) | Hämtar eller anger en kopia av [Matrix](../../com.aspose.drawing.drawing2d/matrix) som definierar en lokal geometrisk transformation för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Hämtar eller anger en kopia av [Matrix](../../com.aspose.drawing.drawing2d/matrix) som definierar en lokal geometrisk transformation för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [deepClone()](#deepClone--) | Skapar en exakt kopia av detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Skapar ett gradientavtagande baserat på en klockformad kurva. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Skapar ett gradientavtagande baserat på en klockformad kurva. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar. |
| [resetTransform()](#resetTransform--) | Återställer egenskapen `LinearGradientBrush.Transform` till identitet. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Multiplicerar [Matrix](../../com.aspose.drawing.drawing2d/matrix) som representerar den lokala geometriska transformationen för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) med den angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix) genom att föregå den angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Multiplicerar [Matrix](../../com.aspose.drawing.drawing2d/matrix) som representerar den lokala geometriska transformationen för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) med den angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix) i den angivna ordningen. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skalar den lokala geometriska transformationen med de angivna mängderna. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skalar den lokala geometriska transformationen med de angivna mängderna i den angivna ordningen. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Roterar den lokala geometriska transformationen med den angivna mängden. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Roterar den lokala geometriska transformationen med den angivna mängden i den angivna ordningen. |
### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) med de angivna punkterna och färgerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | En [PointF](../../com.aspose.drawing/pointf) struktur som representerar startpunkten för den linjära gradienten. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | En [PointF](../../com.aspose.drawing/pointf) struktur som representerar slutpunkten för den linjära gradienten. |
| color1 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color) struktur som representerar startfärgen för den linjära gradienten. |
| color2 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color) struktur som representerar slutfärgen för den linjära gradienten. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) med de angivna punkterna och färgerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | En [Point](../../com.aspose.drawing/point) struktur som representerar startpunkten för den linjära gradienten. |
| point2 | [Point](../../com.aspose.drawing/point) | En [Point](../../com.aspose.drawing/point) struktur som representerar slutpunkten för den linjära gradienten. |
| color1 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color) struktur som representerar startfärgen för den linjära gradienten. |
| color2 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color) struktur som representerar slutfärgen för den linjära gradienten. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)
```


Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) baserad på en rektangel, start- och slutfärger samt ett orienteringsläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | En [RectangleF](../../com.aspose.drawing/rectanglef) struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color) struktur som representerar startfärgen för gradienten. |
| color2 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color)-struktur som representerar den avslutande färgen för gradienten. |
| linearGradientMode | int | Ett [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode)-enumerationselement som anger gradientens orientering. Orienteringen bestämmer start- och slutpunkterna för gradienten. Till exempel specificerar LinearGradientMode.ForwardDiagonal att startpunkten är rektangelns övre vänstra hörn och slutpunkten är rektangelns nedre högra hörn. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)
```


Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) baserad på en rektangel, start- och slutfärger samt orientering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | En `Rectangle`([.getRectangle](../../null/\#getRectangle))-struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color) struktur som representerar startfärgen för gradienten. |
| color2 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color)-struktur som representerar den avslutande färgen för gradienten. |
| linearGradientMode | int | Ett [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode)-enumerationselement som anger gradientens orientering. Orienteringen bestämmer start- och slutpunkterna för gradienten. Till exempel specificerar LinearGradientMode.ForwardDiagonal att startpunkten är rektangelns övre vänstra hörn och slutpunkten är rektangelns nedre högra hörn. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | En [RectangleF](../../com.aspose.drawing/rectanglef) struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color) struktur som representerar startfärgen för gradienten. |
| color2 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color)-struktur som representerar den avslutande färgen för gradienten. |
| vinkel | flyttal | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | En [RectangleF](../../com.aspose.drawing/rectanglef) struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color) struktur som representerar startfärgen för gradienten. |
| color2 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color)-struktur som representerar den avslutande färgen för gradienten. |
| vinkel | flyttal | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |
| isAngleScaleable | boolean | Ställ in på true för att ange att vinkeln påverkas av den transform som är associerad med detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush); annars false. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | En `Rectangle`([.getRectangle](../../null/\#getRectangle))-struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color) struktur som representerar startfärgen för gradienten. |
| color2 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color)-struktur som representerar den avslutande färgen för gradienten. |
| vinkel | flyttal | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | En `Rectangle`([.getRectangle](../../null/\#getRectangle))-struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color) struktur som representerar startfärgen för gradienten. |
| color2 | [Color](../../com.aspose.drawing/color) | En [Color](../../com.aspose.drawing/color)-struktur som representerar den avslutande färgen för gradienten. |
| vinkel | flyttal | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |
| isAngleScaleable | boolean | Ställ in på true för att ange att vinkeln påverkas av den transform som är associerad med detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush); annars false. |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Hämtar eller anger start- och slutfärgerna för gradienten.

**Returns:**
com.aspose.drawing.Color[]
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.drawing.Color---}
```
public void setLinearColors(Color[] value)
```


Hämtar eller anger start- och slutfärgerna för gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Hämtar en rektangulär region som definierar start- och slutpunkterna för gradienten.

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Hämtar eller anger ett värde som indikerar om gamma‑korrektion är aktiverad för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
boolean
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Hämtar eller anger ett värde som indikerar om gamma‑korrektion är aktiverad för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Hämtar eller anger ett `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten.

**Returns:**
[Blend](../../com.aspose.drawing.drawing2d/blend)
### setBlend(Blend value) {#setBlend-com.aspose.drawing.drawing2d.Blend-}
```
public void setBlend(Blend value)
```


Hämtar eller anger ett `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Blend](../../com.aspose.drawing.drawing2d/blend) |  |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Hämtar eller anger ett [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) som definierar en flerfärgad linjär gradient.

**Returns:**
[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Hämtar eller anger ett [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) som definierar en flerfärgad linjär gradient.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Hämtar eller anger en `WrapMode`‑enumeration som indikerar omslagsläget för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Hämtar eller anger en `WrapMode`‑enumeration som indikerar omslagsläget för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Hämtar eller anger en kopia av [Matrix](../../com.aspose.drawing.drawing2d/matrix) som definierar en lokal geometrisk transformation för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Hämtar eller anger en kopia av [Matrix](../../com.aspose.drawing.drawing2d/matrix) som definierar en lokal geometrisk transformation för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar en exakt kopia av detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
java.lang.Object - Det [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) som denna metod skapar, kastat som ett objekt.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Skapar ett gradientavtagande baserat på en klockformad kurva.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | flyttal | Ett värde mellan 0 och 1 som specificerar gradientens centrum (punkten där startfärgen och slutfärgen blandas lika). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Skapar ett gradientavtagande baserat på en klockformad kurva.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | flyttal | Ett värde mellan 0 och 1 som specificerar gradientens centrum (punkten där gradienten består enbart av slutfärgen). |
| skala | flyttal | Ett värde mellan 0 och 1 som anger hur snabbt färgerna avtar från `focus`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | flyttal | Ett värde mellan 0 och 1 som specificerar gradientens centrum (punkten där gradienten består enbart av slutfärgen). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | flyttal | Ett värde mellan 0 och 1 som specificerar gradientens centrum (punkten där gradienten består enbart av slutfärgen). |
| skala | flyttal | Ett värde mellan 0 och 1 som anger hur snabbt färgerna avtar från startfärgen till `focus` (slutfärg). |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Återställer egenskapen `LinearGradientBrush.Transform` till identitet.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplicerar [Matrix](../../com.aspose.drawing.drawing2d/matrix) som representerar den lokala geometriska transformationen för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) med den angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix) genom att föregå den angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Den [Matrix](../../com.aspose.drawing.drawing2d/matrix) som ska multipliceras med den geometriska transformen. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplicerar [Matrix](../../com.aspose.drawing.drawing2d/matrix) som representerar den lokala geometriska transformationen för detta [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) med den angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix) i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Den [Matrix](../../com.aspose.drawing.drawing2d/matrix) som ska multipliceras med den geometriska transformen. |
| order | int | Ett [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) som specificerar i vilken ordning de två matriserna ska multipliceras. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Översätter den lokala geometriska transformen med de angivna dimensionerna. Denna metod lägger till översättningen i början av transformen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | flyttal | Värdet för översättningen i x. |
| dy | flyttal | Värdet för översättningen i y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | flyttal | Värdet för översättningen i x. |
| dy | flyttal | Värdet för översättningen i y. |
| ordning | int | Ordningen (före eller efter) som översättningen ska tillämpas i. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Skalar den lokala geometriska transformen med de angivna värdena. Denna metod lägger till skalningsmatrisen i början av transformen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | flyttal | Mängden att skala transformen i x-axelns riktning. |
| sy | flyttal | Mängden att skala transformen i y-axelns riktning. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skalar den lokala geometriska transformationen med de angivna mängderna i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | flyttal | Mängden att skala transformen i x-axelns riktning. |
| sy | flyttal | Mängden att skala transformen i y-axelns riktning. |
| order | int | En [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) som anger om skalningsmatrisen ska läggas till i slutet eller i början. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Roterar den lokala geometriska transformen med den angivna mängden. Denna metod lägger till rotationen i början av transformen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | flyttal | Rotationsvinkeln. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Roterar den lokala geometriska transformationen med den angivna mängden i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | flyttal | Rotationsvinkeln. |
| order | int | En [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) som anger om rotationsmatrisen ska läggas till i slutet eller i början. |

