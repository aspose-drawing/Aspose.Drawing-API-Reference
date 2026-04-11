---
title: PathGradientBrush
second_title: Aspose.Drawing för Java API‑referens
description: Inkapslar ett objekt som fyller insidan av ett objekt med en gradient.
type: docs
weight: 36
url: /sv/java/com.aspose.drawing.drawing2d/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class PathGradientBrush extends Brush
```

Inkapslar ett [Brush](../../com.aspose.drawing/brush)-objekt som fyller insidan av ett [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-objekt med en gradient. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.drawing.PointF---) | Initierar en ny instans av klassen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) med de angivna punkterna. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.PointF---int-) | Initierar en ny instans av klassen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) med de angivna punkterna och omslagsläget. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.drawing.Point---) | Initierar en ny instans av klassen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) med de angivna punkterna. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.Point---int-) | Initierar en ny instans av klassen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) med de angivna punkterna och omslagsläget. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-) | Initierar en ny instans av klassen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) med den angivna banan. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCenterColor()](#getCenterColor--) | Hämtar eller anger färgen i mitten av bangradienten. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.drawing.Color-) | Hämtar eller anger färgen i mitten av bangradienten. |
| [getSurroundColors()](#getSurroundColors--) | Hämtar eller anger en array av färger som motsvarar punkterna i den bana som detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) fyller. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.drawing.Color---) | Hämtar eller anger en array av färger som motsvarar punkterna i den bana som detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) fyller. |
| [getCenterPoint()](#getCenterPoint--) | Hämtar eller anger mittpunkten för bangradienten. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.drawing.PointF-) | Hämtar eller anger mittpunkten för bangradienten. |
| [getRectangle()](#getRectangle--) | Hämtar en omgivande rektangel för detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getBlend()](#getBlend--) | Hämtar eller anger ett `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Hämtar eller anger ett `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| [getInterpolationColors()](#getInterpolationColors--) | Hämtar eller anger ett [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) som definierar en flerfärgad linjär gradient. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Hämtar eller anger ett [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) som definierar en flerfärgad linjär gradient. |
| [getTransform()](#getTransform--) | Hämtar eller anger en kopia av [Matrix](../../com.aspose.drawing.drawing2d/matrix) som definierar en lokal geometrisk transformation för detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Hämtar eller anger en kopia av [Matrix](../../com.aspose.drawing.drawing2d/matrix) som definierar en lokal geometrisk transformation för detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getFocusScales()](#getFocusScales--) | Hämtar eller anger fokuspunkten för gradientens avtagande. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.drawing.PointF-) | Hämtar eller anger fokuspunkten för gradientens avtagande. |
| [getWrapMode()](#getWrapMode--) | Hämtar eller anger ett `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) som indikerar omslagsläget för detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | Hämtar eller anger ett `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) som indikerar omslagsläget för detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [deepClone()](#deepClone--) | Skapar en exakt kopia av detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Skapar en gradientpensel som ändrar färg från mitten av banan utåt till banans gräns. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Skapar en gradientpensel som ändrar färg från mitten av banan utåt till banans gräns. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Skapar en gradient med en mittfärg och ett linjärt avtagande till en omgivande färg. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Skapar en gradient med en centrisk färg och ett linjärt avtagande till varje omgivande färg. |
| [resetTransform()](#resetTransform--) | Återställer egenskapen `PathGradientBrush.Transform` till identitet. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Uppdaterar borstens transformationsmatris med produkten av borstens transformationsmatris multiplicerad med en annan matris. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Uppdaterar borstens transformationsmatris med produkten av borstens transformationsmatris multiplicerad med en annan matris. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Tillämpar den angivna translationen på den lokala geometriska transformationen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Tillämpar den angivna translationen på den lokala geometriska transformationen i den angivna ordningen. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skalar den lokala geometriska transformationen med de angivna mängderna. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skalar den lokala geometriska transformationen med de angivna mängderna i den angivna ordningen. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Roterar den lokala geometriska transformationen med den angivna mängden. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Roterar den lokala geometriska transformationen med den angivna mängden i den angivna ordningen. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.drawing.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Initierar en ny instans av klassen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) med de angivna punkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | En array av [PointF](../../com.aspose.drawing/pointf)-strukturer som representerar de punkter som utgör vägens hörn. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Initierar en ny instans av klassen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) med de angivna punkterna och omslagsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | En array av [PointF](../../com.aspose.drawing/pointf)-strukturer som representerar de punkter som utgör vägens hörn. |
| wrapMode | int | Ett `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) som specificerar hur fyllningar som ritas med denna [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) tileläggs. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.drawing.Point---}
```
public PathGradientBrush(Point[] points)
```


Initierar en ny instans av klassen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) med de angivna punkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | En array av [Point](../../com.aspose.drawing/point)-strukturer som representerar de punkter som utgör vägens hörn. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Initierar en ny instans av klassen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) med de angivna punkterna och omslagsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | En array av [Point](../../com.aspose.drawing/point)-strukturer som representerar de punkter som utgör vägens hörn. |
| wrapMode | int | Ett `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) som specificerar hur fyllningar som ritas med denna [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) tileläggs. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Initierar en ny instans av klassen [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) med den angivna banan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Den [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) som definierar området som fylls av denna [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Hämtar eller anger färgen i mitten av bangradienten.

**Returns:**
[Color](../../com.aspose.drawing/color)
### setCenterColor(Color value) {#setCenterColor-com.aspose.drawing.Color-}
```
public void setCenterColor(Color value)
```


Hämtar eller anger färgen i mitten av bangradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Hämtar eller anger en array av färger som motsvarar punkterna i den bana som detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) fyller.

**Returns:**
com.aspose.drawing.Color[]
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.drawing.Color---}
```
public void setSurroundColors(Color[] value)
```


Hämtar eller anger en array av färger som motsvarar punkterna i den bana som detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) fyller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Hämtar eller anger mittpunkten för bangradienten.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.drawing.PointF-}
```
public void setCenterPoint(PointF value)
```


Hämtar eller anger mittpunkten för bangradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Hämtar en omgivande rektangel för detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
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

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Hämtar eller anger en kopia av [Matrix](../../com.aspose.drawing.drawing2d/matrix) som definierar en lokal geometrisk transformation för detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Hämtar eller anger en kopia av [Matrix](../../com.aspose.drawing.drawing2d/matrix) som definierar en lokal geometrisk transformation för detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Hämtar eller anger fokuspunkten för gradientens avtagande.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setFocusScales(PointF value) {#setFocusScales-com.aspose.drawing.PointF-}
```
public void setFocusScales(PointF value)
```


Hämtar eller anger fokuspunkten för gradientens avtagande.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Hämtar eller anger ett `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) som indikerar omslagsläget för detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Hämtar eller anger ett `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) som indikerar omslagsläget för detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar en exakt kopia av detta [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
java.lang.Object - Den [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) som denna metod skapar, kastad som ett objekt.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Skapar en gradientpensel som ändrar färg från vägens centrum utåt till vägens gräns. Övergången från en färg till en annan baseras på en klockformad kurva.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | flyttal | Ett värde mellan 0 och 1 som specificerar var, längs någon radie från vägens centrum till vägens gräns, den centrala färgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i vägens centrum. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Skapar en gradientpensel som ändrar färg från vägens centrum utåt till vägens gräns. Övergången från en färg till en annan baseras på en klockformad kurva.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | flyttal | Ett värde mellan 0 och 1 som specificerar var, längs någon radie från vägens centrum till vägens gräns, den centrala färgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i vägens centrum. |
| skala | flyttal | Ett värde mellan 0 och 1 som specificerar den maximala intensiteten för den centrala färgen som blandas med gränsfärgen. Ett värde på 1 ger den högsta möjliga intensiteten för den centrala färgen, och det är standardvärdet. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Skapar en gradient med en mittfärg och ett linjärt avtagande till en omgivande färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | flyttal | Ett värde mellan 0 och 1 som specificerar var, längs någon radie från vägens centrum till vägens gräns, den centrala färgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i vägens centrum. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Skapar en gradient med en centrisk färg och ett linjärt avtagande till varje omgivande färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | flyttal | Ett värde mellan 0 och 1 som specificerar var, längs någon radie från vägens centrum till vägens gräns, den centrala färgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i vägens centrum. |
| skala | flyttal | Ett värde mellan 0 och 1 som specificerar den maximala intensiteten för den centrala färgen som blandas med gränsfärgen. Ett värde på 1 ger den högsta möjliga intensiteten för den centrala färgen, och det är standardvärdet. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Återställer egenskapen `PathGradientBrush.Transform` till identitet.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Uppdaterar borstens transformationsmatris med produkten av borstens transformationsmatris multiplicerad med en annan matris.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Den [Matrix](../../com.aspose.drawing.drawing2d/matrix) som kommer att multipliceras med borstens aktuella transformationsmatris. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Uppdaterar borstens transformationsmatris med produkten av borstens transformationsmatris multiplicerad med en annan matris.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Den [Matrix](../../com.aspose.drawing.drawing2d/matrix) som kommer att multipliceras med borstens aktuella transformationsmatris. |
| order | int | Ett [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) som specificerar i vilken ordning de två matriserna ska multipliceras. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Tillämpar den angivna translationen på den lokala geometriska transformationen. Denna metod lägger till translationen i början av transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | flyttal | Värdet för översättningen i x. |
| dy | flyttal | Värdet för översättningen i y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Tillämpar den angivna translationen på den lokala geometriska transformationen i den angivna ordningen.

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
| sx | flyttal | Transformens skalningsfaktor i x-axelns riktning. |
| sy | flyttal | Transformens skalningsfaktor i y-axelns riktning. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skalar den lokala geometriska transformationen med de angivna mängderna i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | flyttal | Transformens skalningsfaktor i x-axelns riktning. |
| sy | flyttal | Transformens skalningsfaktor i y-axelns riktning. |
| order | int | En [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) som anger om skalningsmatrisen ska läggas till i slutet eller i början. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Roterar den lokala geometriska transformen med den angivna mängden. Denna metod lägger till rotationen i början av transformen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | flyttal | Vinkeln (omfånget) för rotation. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Roterar den lokala geometriska transformationen med den angivna mängden i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | flyttal | Vinkeln (omfånget) för rotation. |
| order | int | En [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) som anger om rotationsmatrisen ska läggas till i slutet eller i början. |

