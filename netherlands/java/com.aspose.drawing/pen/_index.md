---
title: Pen
second_title: Aspose.Drawing voor Java API-referentie
description: Definieert een object dat wordt gebruikt om lijnen en krommen te tekenen.
type: docs
weight: 34
url: /nl/java/com.aspose.drawing/pen/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class Pen implements System.IDisposable
```

Definieert een object dat wordt gebruikt om lijnen en krommen te tekenen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.drawing.Color-) | Initialiseert een nieuw exemplaar van de [Pen](../../com.aspose.drawing/pen) klasse met de opgegeven `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)). |
| [Pen(Brush brush, float width)](#Pen-com.aspose.drawing.Brush-float-) | Initialiseert een nieuw exemplaar van de Pen‑klasse met de opgegeven Brush en Width. |
| [Pen(Brush brush)](#Pen-com.aspose.drawing.Brush-) | Initialiseert een nieuw exemplaar van de [Pen](../../com.aspose.drawing/pen) klasse met de opgegeven `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)). |
| [Pen(Color color, float width)](#Pen-com.aspose.drawing.Color-float-) | Initialiseert een nieuw exemplaar van de Pen‑klasse met de opgegeven Color‑ en Width‑eigenschappen. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getColor()](#getColor--) | Haalt de kleur op of stelt deze in voor deze [Pen](../../com.aspose.drawing/pen). |
| [setColor(Color value)](#setColor-com.aspose.drawing.Color-) | Haalt de kleur op of stelt deze in voor deze [Pen](../../com.aspose.drawing/pen). |
| [getBrush()](#getBrush--) | Haalt de Brush op of stelt deze in die de attributen van deze [Pen](../../com.aspose.drawing/pen) bepaalt. |
| [setBrush(Brush value)](#setBrush-com.aspose.drawing.Brush-) | Haalt de Brush op of stelt deze in die de attributen van deze [Pen](../../com.aspose.drawing/pen) bepaalt. |
| [getCompoundArray()](#getCompoundArray--) | Haalt een array van waarden op of stelt deze in die een samengestelde pen specificeert. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Haalt een array van waarden op of stelt deze in die een samengestelde pen specificeert. |
| [getWidth()](#getWidth--) | Haalt de breedte van deze Pen op of stelt deze in, in eenheden van het Graphics‑object dat voor het tekenen wordt gebruikt. |
| [setWidth(float value)](#setWidth-float-) | Haalt de breedte van deze Pen op of stelt deze in, in eenheden van het Graphics‑object dat voor het tekenen wordt gebruikt. |
| [getStartCap()](#getStartCap--) | Haalt de cap‑stijl op of stelt deze in die aan het begin van lijnen die met deze Pen worden getekend, wordt gebruikt. |
| [setStartCap(int value)](#setStartCap-int-) | Haalt de cap‑stijl op of stelt deze in die aan het begin van lijnen die met deze Pen worden getekend, wordt gebruikt. |
| [getEndCap()](#getEndCap--) | Haalt de cap‑stijl op of stelt deze in die aan het einde van lijnen die met deze Pen worden getekend, wordt gebruikt. |
| [setEndCap(int value)](#setEndCap-int-) | Haalt de cap‑stijl op of stelt deze in die aan het einde van lijnen die met deze Pen worden getekend, wordt gebruikt. |
| [getLineJoin()](#getLineJoin--) | Haalt de join‑stijl op of stelt deze in voor de uiteinden van twee opeenvolgende lijnen die met deze Pen worden getekend. |
| [setLineJoin(int value)](#setLineJoin-int-) | Haalt de join‑stijl op of stelt deze in voor de uiteinden van twee opeenvolgende lijnen die met deze Pen worden getekend. |
| [getMiterLimit()](#getMiterLimit--) | Haalt de limiet van de dikte van de join op of stelt deze in op een afgeschuinde hoek. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Haalt de limiet van de dikte van de join op of stelt deze in op een afgeschuinde hoek. |
| [getAlignment()](#getAlignment--) | Haalt de uitlijning op of stelt deze in voor deze [Pen](../../com.aspose.drawing/pen). |
| [setAlignment(int value)](#setAlignment-int-) | Haalt de uitlijning op of stelt deze in voor deze [Pen](../../com.aspose.drawing/pen). |
| [getTransform()](#getTransform--) | Haalt een kopie van de geometrische transformatie op of stelt deze in voor deze [Pen](../../com.aspose.drawing/pen). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Haalt een kopie van de geometrische transformatie op of stelt deze in voor deze [Pen](../../com.aspose.drawing/pen). |
| [getCustomStartCap()](#getCustomStartCap--) | Haalt een aangepaste cap op of stelt deze in die aan het begin van lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend, wordt gebruikt. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Haalt een aangepaste cap op of stelt deze in die aan het begin van lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend, wordt gebruikt. |
| [getCustomEndCap()](#getCustomEndCap--) | Haalt een aangepaste cap op of stelt deze in die aan het einde van lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend, wordt gebruikt. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Haalt een aangepaste cap op of stelt deze in die aan het einde van lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend, wordt gebruikt. |
| [getDashCap()](#getDashCap--) | Haalt de cap‑stijl op of stelt deze in die aan het einde van de streepjes die gestippelde lijnen vormen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend, wordt gebruikt. |
| [setDashCap(int value)](#setDashCap-int-) | Haalt de cap‑stijl op of stelt deze in die aan het einde van de streepjes die gestippelde lijnen vormen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend, wordt gebruikt. |
| [getDashOffset()](#getDashOffset--) | Haalt de afstand op of stelt deze in van het begin van een lijn tot het begin van een streepjespatroon. |
| [setDashOffset(float value)](#setDashOffset-float-) | Haalt de afstand op of stelt deze in van het begin van een lijn tot het begin van een streepjespatroon. |
| [getDashPattern()](#getDashPattern--) | Haalt een array van aangepaste streepjes en spaties op of stelt deze in. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Haalt een array van aangepaste streepjes en spaties op of stelt deze in. |
| [getDashStyle()](#getDashStyle--) | Haalt de stijl op of stelt deze in die wordt gebruikt voor gestippelde lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend. |
| [setDashStyle(int value)](#setDashStyle-int-) | Haalt de stijl op of stelt deze in die wordt gebruikt voor gestippelde lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend. |
| [getPenType()](#getPenType--) | Haalt de stijl van lijnen op die met deze Pen worden getekend. |
| [dispose()](#dispose--) | Geeft alle bronnen vrij die door deze Pen worden gebruikt. |
| [deepClone()](#deepClone--) | Maakt een exacte kopie van deze [Pen](../../com.aspose.drawing/pen). |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Stelt de waarden in die de stijl van de cap bepalen die wordt gebruikt om lijnen die door deze [Pen](../../com.aspose.drawing/pen) zijn getekend te beëindigen. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Schaalt de lokale geometrische transformatie met de opgegeven factoren. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Schaalt de lokale geometrische transformatie met de opgegeven factoren in de opgegeven volgorde. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschuift de lokale geometrische transformatie met de opgegeven afmetingen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Verschuift de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Roteert de lokale geometrische transformatie met de opgegeven hoek. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Roteert de lokale geometrische transformatie met de opgegeven hoek in de opgegeven volgorde. |
| [resetTransform()](#resetTransform--) | Reset de matrix voor de geometrische transformatie van deze [Pen](../../com.aspose.drawing/pen) naar de identiteit. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Vermenigvuldigt de transformatie‑matrix voor deze [Pen](../../com.aspose.drawing/pen) met de opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Vermenigvuldigt de transformatie‑matrix voor deze [Pen](../../com.aspose.drawing/pen) met de opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix) in de opgegeven volgorde. |
### Pen(Color color) {#Pen-com.aspose.drawing.Color-}
```
public Pen(Color color)
```


Initialiseert een nieuw exemplaar van de [Pen](../../com.aspose.drawing/pen) klasse met de opgegeven `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Een `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) die de vul‑eigenschappen van deze [Pen](../../com.aspose.drawing/pen) bepaalt. |

### Pen(Brush brush, float width) {#Pen-com.aspose.drawing.Brush-float-}
```
public Pen(Brush brush, float width)
```


Initialiseert een nieuw exemplaar van de Pen‑klasse met de opgegeven Brush en Width.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Een Brush die de kenmerken van deze Pen bepaalt. |
| breedte | float | De breedte van de nieuwe Pen. |

### Pen(Brush brush) {#Pen-com.aspose.drawing.Brush-}
```
public Pen(Brush brush)
```


Initialiseert een nieuw exemplaar van de [Pen](../../com.aspose.drawing/pen) klasse met de opgegeven `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Een `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)) die de vul‑eigenschappen van deze [Pen](../../com.aspose.drawing/pen) bepaalt. |

### Pen(Color color, float width) {#Pen-com.aspose.drawing.Color-float-}
```
public Pen(Color color, float width)
```


Initialiseert een nieuw exemplaar van de Pen‑klasse met de opgegeven Color‑ en Width‑eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Een Color‑structuur die de kleur van deze Pen aangeeft. |
| breedte | float | Een waarde die de breedte van deze Pen aangeeft. |

### getColor() {#getColor--}
```
public final Color getColor()
```


Haalt de kleur op of stelt deze in voor deze [Pen](../../com.aspose.drawing/pen).

Waarde: Een `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-))‑structuur die de kleur van deze [Pen](../../com.aspose.drawing/pen) vertegenwoordigt.

**Returns:**
[Color](../../com.aspose.drawing/color)
### setColor(Color value) {#setColor-com.aspose.drawing.Color-}
```
public final void setColor(Color value)
```


Haalt de kleur op of stelt deze in voor deze [Pen](../../com.aspose.drawing/pen).

Waarde: Een `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-))‑structuur die de kleur van deze [Pen](../../com.aspose.drawing/pen) vertegenwoordigt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Haalt de Brush op of stelt deze in die de attributen van deze [Pen](../../com.aspose.drawing/pen) bepaalt.

**Returns:**
[Brush](../../com.aspose.drawing/brush)
### setBrush(Brush value) {#setBrush-com.aspose.drawing.Brush-}
```
public final void setBrush(Brush value)
```


Haalt de Brush op of stelt deze in die de attributen van deze [Pen](../../com.aspose.drawing/pen) bepaalt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Brush](../../com.aspose.drawing/brush) |  |

### getCompoundArray() {#getCompoundArray--}
```
public final float[] getCompoundArray()
```


Haalt een array met waarden op of stelt deze in die een samengestelde pen specificeert. Een samengestelde pen tekent een samengestelde lijn bestaande uit parallelle lijnen en spaties.

**Returns:**
float[] - Een array van reële getallen die de samengestelde array specificeert. De elementen in de array moeten in oplopende volgorde staan, niet kleiner dan 0 en niet groter dan 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public final void setCompoundArray(float[] value)
```


Haalt een array met waarden op of stelt deze in die een samengestelde pen specificeert. Een samengestelde pen tekent een samengestelde lijn bestaande uit parallelle lijnen en spaties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float[] |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Haalt de breedte van deze Pen op of stelt deze in, in eenheden van het Graphics‑object dat voor het tekenen wordt gebruikt.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Haalt de breedte van deze Pen op of stelt deze in, in eenheden van het Graphics‑object dat voor het tekenen wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getStartCap() {#getStartCap--}
```
public final int getStartCap()
```


Haalt de cap‑stijl op of stelt deze in die aan het begin van lijnen die met deze Pen worden getekend, wordt gebruikt.

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public final void setStartCap(int value)
```


Haalt de cap‑stijl op of stelt deze in die aan het begin van lijnen die met deze Pen worden getekend, wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public final int getEndCap()
```


Haalt de cap‑stijl op of stelt deze in die aan het einde van lijnen die met deze Pen worden getekend, wordt gebruikt.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public final void setEndCap(int value)
```


Haalt de cap‑stijl op of stelt deze in die aan het einde van lijnen die met deze Pen worden getekend, wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public final int getLineJoin()
```


Haalt de join‑stijl op of stelt deze in voor de uiteinden van twee opeenvolgende lijnen die met deze Pen worden getekend.

--------------------

Op dit moment werkt de verstekverbinding eigenlijk als MiterClipped.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public final void setLineJoin(int value)
```


Haalt de join‑stijl op of stelt deze in voor de uiteinden van twee opeenvolgende lijnen die met deze Pen worden getekend.

--------------------

Op dit moment werkt de verstekverbinding eigenlijk als MiterClipped.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


Haalt de limiet van de dikte van de join op of stelt deze in op een afgeschuinde hoek.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


Haalt de limiet van de dikte van de join op of stelt deze in op een afgeschuinde hoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Haalt de uitlijning op of stelt deze in voor deze [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - Een [PenAlignment](../../com.aspose.drawing.drawing2d/penalignment) die de uitlijning voor deze [Pen](../../com.aspose.drawing/pen) vertegenwoordigt.
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Haalt de uitlijning op of stelt deze in voor deze [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public final Matrix getTransform()
```


Haalt een kopie van de geometrische transformatie op of stelt deze in voor deze [Pen](../../com.aspose.drawing/pen).

Waarde: Een kopie van de [Matrix](../../com.aspose.drawing.drawing2d/matrix) die de geometrische transformatie voor deze [Pen](../../com.aspose.drawing/pen) vertegenwoordigt.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void setTransform(Matrix value)
```


Haalt een kopie van de geometrische transformatie op of stelt deze in voor deze [Pen](../../com.aspose.drawing/pen).

Waarde: Een kopie van de [Matrix](../../com.aspose.drawing.drawing2d/matrix) die de geometrische transformatie voor deze [Pen](../../com.aspose.drawing/pen) vertegenwoordigt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getCustomStartCap() {#getCustomStartCap--}
```
public final CustomLineCap getCustomStartCap()
```


Haalt een aangepaste cap op of stelt deze in die aan het begin van lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend, wordt gebruikt.

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the beginning of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomStartCap(CustomLineCap value)
```


Haalt een aangepaste cap op of stelt deze in die aan het begin van lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend, wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getCustomEndCap() {#getCustomEndCap--}
```
public final CustomLineCap getCustomEndCap()
```


Haalt een aangepaste cap op of stelt deze in die aan het einde van lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend, wordt gebruikt.

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the end of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomEndCap(CustomLineCap value)
```


Haalt een aangepaste cap op of stelt deze in die aan het einde van lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend, wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getDashCap() {#getDashCap--}
```
public final int getDashCap()
```


Haalt de cap‑stijl op of stelt deze in die aan het einde van de streepjes die gestippelde lijnen vormen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend, wordt gebruikt.

**Returns:**
int - Een van de `DashCap`([.getDashCap](../../null/\#getDashCap)/[.setDashCap(int)](../../null/\#setDashCap-int-))‑waarden die de cap‑stijl vertegenwoordigt die aan het begin en einde van de streepjes wordt gebruikt die de gestippelde lijnen vormen die met deze [Pen](../../com.aspose.drawing/pen) zijn getekend.
### setDashCap(int value) {#setDashCap-int-}
```
public final void setDashCap(int value)
```


Haalt de cap‑stijl op of stelt deze in die aan het einde van de streepjes die gestippelde lijnen vormen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend, wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public final float getDashOffset()
```


Haalt de afstand op of stelt deze in van het begin van een lijn tot het begin van een streepjespatroon.

**Returns:**
float - De afstand van het begin van een lijn tot het begin van een streepjespatroon.
### setDashOffset(float value) {#setDashOffset-float-}
```
public final void setDashOffset(float value)
```


Haalt de afstand op of stelt deze in van het begin van een lijn tot het begin van een streepjespatroon.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getDashPattern() {#getDashPattern--}
```
public final float[] getDashPattern()
```


Haalt een array van aangepaste streepjes en spaties op of stelt deze in.

**Returns:**
float[] - Een array van reële getallen die de lengtes van afwisselende streepjes en spaties in gestippelde lijnen specificeert.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public final void setDashPattern(float[] value)
```


Haalt een array van aangepaste streepjes en spaties op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float[] |  |

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Haalt de stijl op of stelt deze in die wordt gebruikt voor gestippelde lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend.

**Returns:**
int - Een `DashStyle`([.getDashStyle](../../null/\#getDashStyle)/[.setDashStyle(int)](../../null/\#setDashStyle-int-)) die de stijl vertegenwoordigt die wordt gebruikt voor gestreepte lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend.
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Haalt de stijl op of stelt deze in die wordt gebruikt voor gestippelde lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPenType() {#getPenType--}
```
public final int getPenType()
```


Haalt de stijl van lijnen op die met deze Pen worden getekend.

Waarde: Een `PenType`([.getPenType](../../null/\#getPenType)) enumeratie die de stijl van lijnen specificeert die met deze [Pen](../../com.aspose.drawing/pen) worden getekend.

**Returns:**
int
### dispose() {#dispose--}
```
public final void dispose()
```


Geeft alle bronnen vrij die door deze Pen worden gebruikt.

--------------------

Deze methode doet eigenlijk niets. Het is alleen voor compatibiliteit met de System.Drawing API.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Maakt een exacte kopie van deze [Pen](../../com.aspose.drawing/pen).

**Returns:**
java.lang.Object - Een Object dat kan worden gecast naar een [Pen](../../com.aspose.drawing/pen).
### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public final void setLineCap(int startCap, int endCap, int dashCap)
```


Stelt de waarden in die de stijl van de cap bepalen die wordt gebruikt om lijnen die door deze [Pen](../../com.aspose.drawing/pen) zijn getekend te beëindigen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startCap | int | Een [LineCap](../../com.aspose.drawing.drawing2d/linecap) die de capstijl vertegenwoordigt die moet worden gebruikt aan het begin van lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend. |
| endCap | int | Een [LineCap](../../com.aspose.drawing.drawing2d/linecap) die de capstijl vertegenwoordigt die moet worden gebruikt aan het einde van lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend. |
| dashCap | int | Een [LineCap](../../com.aspose.drawing.drawing2d/linecap) die de capstijl vertegenwoordigt die moet worden gebruikt aan het begin of einde van gestreepte lijnen die met deze [Pen](../../com.aspose.drawing/pen) worden getekend. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public final void scaleTransform(float sx, float sy)
```


Schaalt de lokale geometrische transformatie met de opgegeven factoren. Deze methode plaatst de schaalmatrix vóór de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sx | float | De factor waarmee de transformatie in de x-richting wordt geschaald. |
| sy | float | De factor waarmee de transformatie in de y-richting wordt geschaald. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public final void scaleTransform(float sx, float sy, int order)
```


Schaalt de lokale geometrische transformatie met de opgegeven factoren in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sx | float | De factor waarmee de transformatie in de x-richting wordt geschaald. |
| sy | float | De factor waarmee de transformatie in de y-richting wordt geschaald. |
| order | int | Een [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) die aangeeft of de schaalmatrix moet worden toegevoegd of voorafgeplaatst. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public final void translateTransform(float dx, float dy)
```


Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. Deze methode plaatst de translatie vóór de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public final void translateTransform(float dx, float dy, int order)
```


Verschuift de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |
| volgorde | int | De volgorde (voorgaan of toevoegen) waarin de translatie wordt toegepast. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public final void rotateTransform(float angle)
```


Roteert de lokale geometrische transformatie met de opgegeven hoek. Deze methode plaatst de rotatie vóór de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | float | De rotatiehoek. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public final void rotateTransform(float angle, int order)
```


Roteert de lokale geometrische transformatie met de opgegeven hoek in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | float | De rotatiehoek. |
| order | int | Een [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) die aangeeft of de rotatiematrix moet worden toegevoegd of voorafgeplaatst. |

### resetTransform() {#resetTransform--}
```
public final void resetTransform()
```


Reset de matrix voor de geometrische transformatie van deze [Pen](../../com.aspose.drawing/pen) naar de identiteit.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void multiplyTransform(Matrix matrix)
```


Vermenigvuldigt de transformatie‑matrix voor deze [Pen](../../com.aspose.drawing/pen) met de opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Het [Matrix](../../com.aspose.drawing.drawing2d/matrix) object waarmee de transformatie-matrix moet worden vermenigvuldigd. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public final void multiplyTransform(Matrix matrix, int order)
```


Vermenigvuldigt de transformatie‑matrix voor deze [Pen](../../com.aspose.drawing/pen) met de opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix) in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | De java.awt.geom.AffineTransform waarmee de transformatie-matrix moet worden vermenigvuldigd. |
| volgorde | int | De volgorde waarin de vermenigvuldigingsoperatie moet worden uitgevoerd. |

