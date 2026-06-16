---
title: PathGradientBrush
second_title: Aspose.Drawing für Java API-Referenz
description: Kapselt ein Objekt, das das Innere eines Objekts mit einem Farbverlauf füllt.
type: docs
weight: 36
url: /de/java/com.aspose.drawing.drawing2d/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class PathGradientBrush extends Brush
```

Kapselt ein [Brush](../../com.aspose.drawing/brush)-Objekt, das das Innere eines [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-Objekts mit einem Farbverlauf füllt. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.drawing.PointF---) | Initialisiert eine neue Instanz der Klasse [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) mit den angegebenen Punkten. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.PointF---int-) | Initialisiert eine neue Instanz der Klasse [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) mit den angegebenen Punkten und dem Wrap-Modus. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.drawing.Point---) | Initialisiert eine neue Instanz der Klasse [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) mit den angegebenen Punkten. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.Point---int-) | Initialisiert eine neue Instanz der Klasse [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) mit den angegebenen Punkten und dem Wrap-Modus. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-) | Initialisiert eine neue Instanz der Klasse [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) mit dem angegebenen Pfad. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCenterColor()](#getCenterColor--) | Liest oder legt die Farbe im Zentrum des Pfadverlaufs fest. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.drawing.Color-) | Liest oder legt die Farbe im Zentrum des Pfadverlaufs fest. |
| [getSurroundColors()](#getSurroundColors--) | Liest oder legt ein Array von Farben fest, das den Punkten im Pfad entspricht, den dieser [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) füllt. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.drawing.Color---) | Liest oder legt ein Array von Farben fest, das den Punkten im Pfad entspricht, den dieser [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) füllt. |
| [getCenterPoint()](#getCenterPoint--) | Liest oder legt den Mittelpunkt des Pfadverlaufs fest. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.drawing.PointF-) | Liest oder legt den Mittelpunkt des Pfadverlaufs fest. |
| [getRectangle()](#getRectangle--) | Liest ein begrenzendes Rechteck für diesen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getBlend()](#getBlend--) | Liest oder setzt ein `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)), das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Liest oder setzt ein `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)), das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [getInterpolationColors()](#getInterpolationColors--) | Liest oder setzt ein [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend), das einen mehrfarbigen linearen Farbverlauf definiert. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Liest oder setzt ein [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend), das einen mehrfarbigen linearen Farbverlauf definiert. |
| [getTransform()](#getTransform--) | Liest oder legt eine Kopie der [Matrix](../../com.aspose.drawing.drawing2d/matrix) fest, die eine lokale geometrische Transformation für diesen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) definiert. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Liest oder legt eine Kopie der [Matrix](../../com.aspose.drawing.drawing2d/matrix) fest, die eine lokale geometrische Transformation für diesen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) definiert. |
| [getFocusScales()](#getFocusScales--) | Liest oder legt den Fokuspunkt für den Farbverlauf-Abfall fest. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.drawing.PointF-) | Liest oder legt den Fokuspunkt für den Farbverlauf-Abfall fest. |
| [getWrapMode()](#getWrapMode--) | Liest oder legt einen `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) fest, der den Wrap-Modus für diesen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) angibt. |
| [setWrapMode(int value)](#setWrapMode-int-) | Liest oder legt einen `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) fest, der den Wrap-Modus für diesen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) angibt. |
| [deepClone()](#deepClone--) | Erstellt eine exakte Kopie dieses [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Erstellt einen Farbverlaufs-Pinsel, der die Farbe vom Zentrum des Pfads nach außen bis zur Begrenzung des Pfads ändert. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Erstellt einen Farbverlaufs-Pinsel, der die Farbe vom Zentrum des Pfads nach außen bis zur Begrenzung des Pfads ändert. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Erstellt einen Farbverlauf mit einer Mittelwertfarbe und einem linearen Abfall zu einer umgebenden Farbe. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Erstellt einen Verlauf mit einer Mittel­farbe und einem linearen Abfall zu jeder umgebenden Farbe. |
| [resetTransform()](#resetTransform--) | Setzt die `PathGradientBrush.Transform`‑Eigenschaft auf die Identität zurück. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Aktualisiert die Transformationsmatrix des Pinsels mit dem Produkt der Transformationsmatrix des Pinsels, multipliziert mit einer anderen Matrix. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Aktualisiert die Transformationsmatrix des Pinsels mit dem Produkt der Transformationsmatrix des Pinsels, multipliziert mit einer anderen Matrix. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Wendet die angegebene Translation auf die lokale geometrische Transformation an. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Wendet die angegebene Translation in der angegebenen Reihenfolge auf die lokale geometrische Transformation an. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skaliert die lokale geometrische Transformation um die angegebenen Werte. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Dreht die lokale geometrische Transformation um den angegebenen Betrag. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.drawing.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Initialisiert eine neue Instanz der Klasse [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) mit den angegebenen Punkten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Ein Array von [PointF](../../com.aspose.drawing/pointf)-Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Initialisiert eine neue Instanz der Klasse [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) mit den angegebenen Punkten und dem Wrap-Modus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Ein Array von [PointF](../../com.aspose.drawing/pointf)-Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |
| wrapMode | int | Ein `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)), das angibt, wie mit diesem [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) gezeichnete Füllungen gekachelt werden. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.drawing.Point---}
```
public PathGradientBrush(Point[] points)
```


Initialisiert eine neue Instanz der Klasse [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) mit den angegebenen Punkten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Ein Array von [Point](../../com.aspose.drawing/point)-Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Initialisiert eine neue Instanz der Klasse [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) mit den angegebenen Punkten und dem Wrap-Modus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Ein Array von [Point](../../com.aspose.drawing/point)-Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |
| wrapMode | int | Ein `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)), das angibt, wie mit diesem [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) gezeichnete Füllungen gekachelt werden. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Initialisiert eine neue Instanz der Klasse [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) mit dem angegebenen Pfad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Der [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), der den von diesem [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) gefüllten Bereich definiert. |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Liest oder legt die Farbe im Zentrum des Pfadverlaufs fest.

**Returns:**
[Color](../../com.aspose.drawing/color)
### setCenterColor(Color value) {#setCenterColor-com.aspose.drawing.Color-}
```
public void setCenterColor(Color value)
```


Liest oder legt die Farbe im Zentrum des Pfadverlaufs fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Liest oder legt ein Array von Farben fest, das den Punkten im Pfad entspricht, den dieser [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) füllt.

**Returns:**
com.aspose.drawing.Color[]
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.drawing.Color---}
```
public void setSurroundColors(Color[] value)
```


Liest oder legt ein Array von Farben fest, das den Punkten im Pfad entspricht, den dieser [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) füllt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Liest oder legt den Mittelpunkt des Pfadverlaufs fest.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.drawing.PointF-}
```
public void setCenterPoint(PointF value)
```


Liest oder legt den Mittelpunkt des Pfadverlaufs fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Liest ein begrenzendes Rechteck für diesen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
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

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Liest oder legt eine Kopie der [Matrix](../../com.aspose.drawing.drawing2d/matrix) fest, die eine lokale geometrische Transformation für diesen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) definiert.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Liest oder legt eine Kopie der [Matrix](../../com.aspose.drawing.drawing2d/matrix) fest, die eine lokale geometrische Transformation für diesen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Liest oder legt den Fokuspunkt für den Farbverlauf-Abfall fest.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setFocusScales(PointF value) {#setFocusScales-com.aspose.drawing.PointF-}
```
public void setFocusScales(PointF value)
```


Liest oder legt den Fokuspunkt für den Farbverlauf-Abfall fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Liest oder legt einen `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) fest, der den Wrap-Modus für diesen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) angibt.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Liest oder legt einen `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) fest, der den Wrap-Modus für diesen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Erstellt eine exakte Kopie dieses [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
java.lang.Object – Der [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush), den diese Methode erstellt, als Objekt umgewandelt.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Erstellt einen Farbverlauf‑Pinsel, der die Farbe vom Mittelpunkt des Pfads nach außen bis zur Pfadrand ändert. Der Übergang von einer Farbe zur anderen basiert auf einer glockenförmigen Kurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Mittelpunkt des Pfads bis zum Pfadrand die Mittel­farbe ihre höchste Intensität erreicht. Ein Wert von 1 (der Standard) legt die höchste Intensität in den Mittelpunkt des Pfads. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Erstellt einen Farbverlauf‑Pinsel, der die Farbe vom Mittelpunkt des Pfads nach außen bis zur Pfadrand ändert. Der Übergang von einer Farbe zur anderen basiert auf einer glockenförmigen Kurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Mittelpunkt des Pfads bis zum Pfadrand die Mittel­farbe ihre höchste Intensität erreicht. Ein Wert von 1 (der Standard) legt die höchste Intensität in den Mittelpunkt des Pfads. |
| Skala | float | Ein Wert von 0 bis 1, der die maximale Intensität der Mittel­farbe angibt, die mit der Randfarbe gemischt wird. Ein Wert von 1 bewirkt die höchstmögliche Intensität der Mittel­farbe und ist der Standardwert. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Erstellt einen Farbverlauf mit einer Mittelwertfarbe und einem linearen Abfall zu einer umgebenden Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Mittelpunkt des Pfads bis zum Pfadrand die Mittel­farbe ihre höchste Intensität erreicht. Ein Wert von 1 (der Standard) legt die höchste Intensität in den Mittelpunkt des Pfads. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Erstellt einen Verlauf mit einer Mittel­farbe und einem linearen Abfall zu jeder umgebenden Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Mittelpunkt des Pfads bis zum Pfadrand die Mittel­farbe ihre höchste Intensität erreicht. Ein Wert von 1 (der Standard) legt die höchste Intensität in den Mittelpunkt des Pfads. |
| Skala | float | Ein Wert von 0 bis 1, der die maximale Intensität der Mittel­farbe angibt, die mit der Randfarbe gemischt wird. Ein Wert von 1 bewirkt die höchstmögliche Intensität der Mittel­farbe und ist der Standardwert. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Setzt die `PathGradientBrush.Transform`‑Eigenschaft auf die Identität zurück.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Aktualisiert die Transformationsmatrix des Pinsels mit dem Produkt der Transformationsmatrix des Pinsels, multipliziert mit einer anderen Matrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Die [Matrix](../../com.aspose.drawing.drawing2d/matrix), die mit der aktuellen Transformationsmatrix des Pinsels multipliziert wird. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Aktualisiert die Transformationsmatrix des Pinsels mit dem Produkt der Transformationsmatrix des Pinsels, multipliziert mit einer anderen Matrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Die [Matrix](../../com.aspose.drawing.drawing2d/matrix), die mit der aktuellen Transformationsmatrix des Pinsels multipliziert wird. |
| order | int | Ein [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), das angibt, in welcher Reihenfolge die beiden Matrizen multipliziert werden. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Wendet die angegebene Translation auf die lokale geometrische Transformation an. Diese Methode fügt die Translation vor der Transformation ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Wendet die angegebene Translation in der angegebenen Reihenfolge auf die lokale geometrische Transformation an.

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
| sx | float | Der Skalierungsfaktor der Transformation in x‑Richtung. |
| sy | float | Der Skalierungsfaktor der Transformation in y‑Richtung. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Skalierungsfaktor der Transformation in x‑Richtung. |
| sy | float | Der Skalierungsfaktor der Transformation in y‑Richtung. |
| order | int | Ein [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), das angibt, ob die Skalierungsmatrix angehängt oder vorangestellt wird. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rotiert die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotationsmatrix vor der Transformation ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Winkel (Ausdehnung) der Drehung. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Winkel (Ausdehnung) der Drehung. |
| order | int | Ein [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), das angibt, ob die Rotationsmatrix angehängt oder vorangestellt wird. |

