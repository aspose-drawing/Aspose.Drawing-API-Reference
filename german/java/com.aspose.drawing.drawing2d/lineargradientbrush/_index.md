---
title: LinearGradientBrush
second_title: Aspose.Drawing für Java API-Referenz
description: Kapselt ein  mit einem linearen Farbverlauf.
type: docs
weight: 31
url: /de/java/com.aspose.drawing.drawing2d/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class LinearGradientBrush extends Brush
```

Kapselt einen [Brush](../../com.aspose.drawing/brush) mit einem linearen Farbverlauf. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) mit den angegebenen Punkten und Farben. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) mit den angegebenen Punkten und Farben. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierungsmodus. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einer Orientierung. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierungswinkel. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierungswinkel. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierungswinkel. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierungswinkel. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLinearColors()](#getLinearColors--) | Liest oder setzt die Anfangs‑ und Endfarben des Farbverlaufs. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.drawing.Color---) | Liest oder setzt die Anfangs‑ und Endfarben des Farbverlaufs. |
| [getRectangle()](#getRectangle--) | Liest einen rechteckigen Bereich, der die Anfangs‑ und Endpunkte des Farbverlaufs definiert. |
| [getGammaCorrection()](#getGammaCorrection--) | Liest oder setzt einen Wert, der angibt, ob die Gammakorrektur für diesen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) aktiviert ist. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Liest oder setzt einen Wert, der angibt, ob die Gammakorrektur für diesen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) aktiviert ist. |
| [getBlend()](#getBlend--) | Liest oder setzt ein `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)), das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Liest oder setzt ein `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)), das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [getInterpolationColors()](#getInterpolationColors--) | Liest oder setzt ein [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend), das einen mehrfarbigen linearen Farbverlauf definiert. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Liest oder setzt ein [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend), das einen mehrfarbigen linearen Farbverlauf definiert. |
| [getWrapMode()](#getWrapMode--) | Liest oder setzt eine `WrapMode`-Aufzählung, die den Wrap‑Modus für diesen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) angibt. |
| [setWrapMode(int value)](#setWrapMode-int-) | Liest oder setzt eine `WrapMode`-Aufzählung, die den Wrap‑Modus für diesen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) angibt. |
| [getTransform()](#getTransform--) | Liest oder setzt eine Kopie der [Matrix](../../com.aspose.drawing.drawing2d/matrix), die eine lokale geometrische Transformation für diesen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) definiert. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Liest oder setzt eine Kopie der [Matrix](../../com.aspose.drawing.drawing2d/matrix), die eine lokale geometrische Transformation für diesen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) definiert. |
| [deepClone()](#deepClone--) | Erstellt eine exakte Kopie dieses [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Erstellt einen Farbverlauf‑Abfall basierend auf einer glockenförmigen Kurve. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Erstellt einen Farbverlauf‑Abfall basierend auf einer glockenförmigen Kurve. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Erstellt einen linearen Farbverlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Erstellt einen linearen Farbverlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden. |
| [resetTransform()](#resetTransform--) | Setzt die Eigenschaft `LinearGradientBrush.Transform` auf die Identität zurück. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Multipliziert die [Matrix](../../com.aspose.drawing.drawing2d/matrix), die die lokale geometrische Transformation dieses [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) darstellt, mit der angegebenen [Matrix](../../com.aspose.drawing.drawing2d/matrix), indem die angegebene [Matrix](../../com.aspose.drawing.drawing2d/matrix) vorangestellt wird. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Multipliziert die [Matrix](../../com.aspose.drawing.drawing2d/matrix), die die lokale geometrische Transformation dieses [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) darstellt, mit der angegebenen [Matrix](../../com.aspose.drawing.drawing2d/matrix) in der angegebenen Reihenfolge. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skaliert die lokale geometrische Transformation um die angegebenen Werte. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Dreht die lokale geometrische Transformation um den angegebenen Betrag. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) mit den angegebenen Punkten und Farben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | Eine [PointF](../../com.aspose.drawing/pointf) Struktur, die den Startpunkt des linearen Farbverlaufs darstellt. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | Eine [PointF](../../com.aspose.drawing/pointf) Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |
| color1 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color) Struktur, die die Startfarbe des linearen Farbverlaufs darstellt. |
| color2 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color) Struktur, die die Endfarbe des linearen Farbverlaufs darstellt. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) mit den angegebenen Punkten und Farben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | Eine [Point](../../com.aspose.drawing/point) Struktur, die den Startpunkt des linearen Farbverlaufs darstellt. |
| point2 | [Point](../../com.aspose.drawing/point) | Eine [Point](../../com.aspose.drawing/point) Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |
| color1 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color) Struktur, die die Startfarbe des linearen Farbverlaufs darstellt. |
| color2 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color) Struktur, die die Endfarbe des linearen Farbverlaufs darstellt. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)
```


Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierungsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Eine [RectangleF](../../com.aspose.drawing/rectanglef) Struktur, die die Begrenzungen des linearen Farbverlaufs angibt. |
| color1 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color)-Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| linearGradientMode | int | Ein [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode)-Aufzählungselement, das die Ausrichtung des Farbverlaufs festlegt. Die Ausrichtung bestimmt die Start- und Endpunkte des Farbverlaufs. Beispielsweise gibt LinearGradientMode.ForwardDiagonal an, dass der Startpunkt die obere linke Ecke des Rechtecks ist und der Endpunkt die untere rechte Ecke des Rechtecks. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)
```


Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einer Orientierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Eine `Rectangle`([.getRectangle](../../null/\#getRectangle))-Struktur, die die Begrenzungen des linearen Farbverlaufs angibt. |
| color1 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color)-Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| linearGradientMode | int | Ein [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode)-Aufzählungselement, das die Ausrichtung des Farbverlaufs festlegt. Die Ausrichtung bestimmt die Start- und Endpunkte des Farbverlaufs. Beispielsweise gibt LinearGradientMode.ForwardDiagonal an, dass der Startpunkt die obere linke Ecke des Rechtecks ist und der Endpunkt die untere rechte Ecke des Rechtecks. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierungswinkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Eine [RectangleF](../../com.aspose.drawing/rectanglef) Struktur, die die Begrenzungen des linearen Farbverlaufs angibt. |
| color1 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color)-Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| Winkel | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierungswinkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Eine [RectangleF](../../com.aspose.drawing/rectanglef) Struktur, die die Begrenzungen des linearen Farbverlaufs angibt. |
| color1 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color)-Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| Winkel | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |
| isAngleScaleable | boolean | Auf true setzen, um anzugeben, dass der Winkel von der mit diesem [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) verbundenen Transformation beeinflusst wird; andernfalls false. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierungswinkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Eine `Rectangle`([.getRectangle](../../null/\#getRectangle))-Struktur, die die Begrenzungen des linearen Farbverlaufs angibt. |
| color1 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color)-Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| Winkel | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Initialisiert eine neue Instanz der Klasse [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierungswinkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Eine `Rectangle`([.getRectangle](../../null/\#getRectangle))-Struktur, die die Begrenzungen des linearen Farbverlaufs angibt. |
| color1 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | [Color](../../com.aspose.drawing/color) | Eine [Color](../../com.aspose.drawing/color)-Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| Winkel | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |
| isAngleScaleable | boolean | Auf true setzen, um anzugeben, dass der Winkel von der mit diesem [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) verbundenen Transformation beeinflusst wird; andernfalls false. |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Liest oder setzt die Anfangs‑ und Endfarben des Farbverlaufs.

**Returns:**
com.aspose.drawing.Color[]
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.drawing.Color---}
```
public void setLinearColors(Color[] value)
```


Liest oder setzt die Anfangs‑ und Endfarben des Farbverlaufs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Liest einen rechteckigen Bereich, der die Anfangs‑ und Endpunkte des Farbverlaufs definiert.

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Liest oder setzt einen Wert, der angibt, ob die Gammakorrektur für diesen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) aktiviert ist.

**Returns:**
boolean
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die Gammakorrektur für diesen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) aktiviert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Liest oder setzt ein `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)), das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren.

**Returns:**
[Blend](../../com.aspose.drawing.drawing2d/blend)
### setBlend(Blend value) {#setBlend-com.aspose.drawing.drawing2d.Blend-}
```
public void setBlend(Blend value)
```


Liest oder setzt ein `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)), das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Blend](../../com.aspose.drawing.drawing2d/blend) |  |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Liest oder setzt ein [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend), das einen mehrfarbigen linearen Farbverlauf definiert.

**Returns:**
[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Liest oder setzt ein [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend), das einen mehrfarbigen linearen Farbverlauf definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Liest oder setzt eine `WrapMode`-Aufzählung, die den Wrap‑Modus für diesen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) angibt.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Liest oder setzt eine `WrapMode`-Aufzählung, die den Wrap‑Modus für diesen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Liest oder setzt eine Kopie der [Matrix](../../com.aspose.drawing.drawing2d/matrix), die eine lokale geometrische Transformation für diesen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) definiert.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Liest oder setzt eine Kopie der [Matrix](../../com.aspose.drawing.drawing2d/matrix), die eine lokale geometrische Transformation für diesen [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Erstellt eine exakte Kopie dieses [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
java.lang.Object – Der [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), den diese Methode erstellt, als Objekt umgewandelt.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Erstellt einen Farbverlauf‑Abfall basierend auf einer glockenförmigen Kurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem die Startfarbe und die Endfarbe zu gleichen Teilen gemischt werden). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Erstellt einen Farbverlauf‑Abfall basierend auf einer glockenförmigen Kurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem der Farbverlauf ausschließlich aus der Endfarbe besteht). |
| Skala | float | Ein Wert von 0 bis 1, der angibt, wie schnell die Farben vom `focus` abfallen. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Erstellt einen linearen Farbverlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem der Farbverlauf ausschließlich aus der Endfarbe besteht). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Erstellt einen linearen Farbverlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem der Farbverlauf ausschließlich aus der Endfarbe besteht). |
| Skala | float | Ein Wert von 0 bis 1, der angibt, wie schnell die Farben von der Startfarbe zum `focus` (Endfarbe) abfallen. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Setzt die Eigenschaft `LinearGradientBrush.Transform` auf die Identität zurück.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multipliziert die [Matrix](../../com.aspose.drawing.drawing2d/matrix), die die lokale geometrische Transformation dieses [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) darstellt, mit der angegebenen [Matrix](../../com.aspose.drawing.drawing2d/matrix), indem die angegebene [Matrix](../../com.aspose.drawing.drawing2d/matrix) vorangestellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Die [Matrix](../../com.aspose.drawing.drawing2d/matrix), mit der die geometrische Transformation multipliziert wird. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multipliziert die [Matrix](../../com.aspose.drawing.drawing2d/matrix), die die lokale geometrische Transformation dieses [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) darstellt, mit der angegebenen [Matrix](../../com.aspose.drawing.drawing2d/matrix) in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Die [Matrix](../../com.aspose.drawing.drawing2d/matrix), mit der die geometrische Transformation multipliziert wird. |
| order | int | Ein [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), das angibt, in welcher Reihenfolge die beiden Matrizen multipliziert werden. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Verschiebt die lokale geometrische Transformation um die angegebenen Maße. Diese Methode fügt die Verschiebung der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |
| Reihenfolge | int | Die Reihenfolge (voranstellen oder anhängen), in der die Verschiebung angewendet wird. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungsmatrix vor der Transformation ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Betrag, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y-Richtung skaliert wird. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Betrag, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y-Richtung skaliert wird. |
| order | int | Ein [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), das angibt, ob die Skalierungsmatrix angehängt oder vorangestellt wird. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rotiert die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotationsmatrix vor der Transformation ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel. |
| order | int | Ein [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), das angibt, ob die Rotationsmatrix angehängt oder vorangestellt wird. |

