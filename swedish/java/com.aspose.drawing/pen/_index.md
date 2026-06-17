---
title: Pen
second_title: Aspose.Drawing för Java API‑referens
description: Definierar ett objekt som används för att rita linjer och kurvor.
type: docs
weight: 34
url: /sv/java/com.aspose.drawing/pen/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class Pen implements System.IDisposable
```

Definierar ett objekt som används för att rita linjer och kurvor.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.drawing.Color-) | Initierar en ny instans av [Pen](../../com.aspose.drawing/pen)-klassen med den angivna `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)). |
| [Pen(Brush brush, float width)](#Pen-com.aspose.drawing.Brush-float-) | Initierar en ny instans av Pen-klassen med den angivna Brush och Width. |
| [Pen(Brush brush)](#Pen-com.aspose.drawing.Brush-) | Initierar en ny instans av [Pen](../../com.aspose.drawing/pen)-klassen med den angivna `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)). |
| [Pen(Color color, float width)](#Pen-com.aspose.drawing.Color-float-) | Initierar en ny instans av Pen-klassen med de angivna Color- och Width-egenskaperna. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColor()](#getColor--) | Hämtar eller anger färgen på detta [Pen](../../com.aspose.drawing/pen). |
| [setColor(Color value)](#setColor-com.aspose.drawing.Color-) | Hämtar eller anger färgen på detta [Pen](../../com.aspose.drawing/pen). |
| [getBrush()](#getBrush--) | Hämtar eller anger Brush som bestämmer attribut för detta [Pen](../../com.aspose.drawing/pen). |
| [setBrush(Brush value)](#setBrush-com.aspose.drawing.Brush-) | Hämtar eller anger Brush som bestämmer attribut för detta [Pen](../../com.aspose.drawing/pen). |
| [getCompoundArray()](#getCompoundArray--) | Hämtar eller anger en array av värden som specificerar en sammansatt penna. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Hämtar eller anger en array av värden som specificerar en sammansatt penna. |
| [getWidth()](#getWidth--) | Hämtar eller anger bredden på detta Pen, i enheter av Graphics-objektet som används för ritning. |
| [setWidth(float value)](#setWidth-float-) | Hämtar eller anger bredden på detta Pen, i enheter av Graphics-objektet som används för ritning. |
| [getStartCap()](#getStartCap--) | Hämtar eller anger kapslingsstilen som används i början av linjer som ritas med detta Pen. |
| [setStartCap(int value)](#setStartCap-int-) | Hämtar eller anger kapslingsstilen som används i början av linjer som ritas med detta Pen. |
| [getEndCap()](#getEndCap--) | Hämtar eller anger kapslingsstilen som används i slutet av linjer som ritas med detta Pen. |
| [setEndCap(int value)](#setEndCap-int-) | Hämtar eller anger kapslingsstilen som används i slutet av linjer som ritas med detta Pen. |
| [getLineJoin()](#getLineJoin--) | Hämtar eller anger sammanfogningsstilen för ändarna på två på varandra följande linjer som ritas med detta Pen. |
| [setLineJoin(int value)](#setLineJoin-int-) | Hämtar eller anger sammanfogningsstilen för ändarna på två på varandra följande linjer som ritas med detta Pen. |
| [getMiterLimit()](#getMiterLimit--) | Hämtar eller anger gränsen för tjockleken på sammanfogningen på ett snedkantigt hörn. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Hämtar eller anger gränsen för tjockleken på sammanfogningen på ett snedkantigt hörn. |
| [getAlignment()](#getAlignment--) | Hämtar eller anger justeringen för detta [Pen](../../com.aspose.drawing/pen). |
| [setAlignment(int value)](#setAlignment-int-) | Hämtar eller anger justeringen för detta [Pen](../../com.aspose.drawing/pen). |
| [getTransform()](#getTransform--) | Hämtar eller anger en kopia av den geometriska transformationen för detta [Pen](../../com.aspose.drawing/pen). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Hämtar eller anger en kopia av den geometriska transformationen för detta [Pen](../../com.aspose.drawing/pen). |
| [getCustomStartCap()](#getCustomStartCap--) | Hämtar eller anger en anpassad kapsling att använda i början av linjer som ritas med detta [Pen](../../com.aspose.drawing/pen). |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Hämtar eller anger en anpassad kapsling att använda i början av linjer som ritas med detta [Pen](../../com.aspose.drawing/pen). |
| [getCustomEndCap()](#getCustomEndCap--) | Hämtar eller anger en anpassad kapsling att använda i slutet av linjer som ritas med detta [Pen](../../com.aspose.drawing/pen). |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Hämtar eller anger en anpassad kapsling att använda i slutet av linjer som ritas med detta [Pen](../../com.aspose.drawing/pen). |
| [getDashCap()](#getDashCap--) | Hämtar eller anger kapslingsstilen som används i slutet av strecken som utgör streckade linjer ritat med detta [Pen](../../com.aspose.drawing/pen). |
| [setDashCap(int value)](#setDashCap-int-) | Hämtar eller anger kapslingsstilen som används i slutet av strecken som utgör streckade linjer ritat med detta [Pen](../../com.aspose.drawing/pen). |
| [getDashOffset()](#getDashOffset--) | Hämtar eller anger avståndet från början av en linje till början av ett streckmönster. |
| [setDashOffset(float value)](#setDashOffset-float-) | Hämtar eller anger avståndet från början av en linje till början av ett streckmönster. |
| [getDashPattern()](#getDashPattern--) | Hämtar eller anger en array av anpassade streck och mellanslag. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Hämtar eller anger en array av anpassade streck och mellanslag. |
| [getDashStyle()](#getDashStyle--) | Hämtar eller anger stilen som används för streckade linjer ritat med detta [Pen](../../com.aspose.drawing/pen). |
| [setDashStyle(int value)](#setDashStyle-int-) | Hämtar eller anger stilen som används för streckade linjer ritat med detta [Pen](../../com.aspose.drawing/pen). |
| [getPenType()](#getPenType--) | Hämtar stilen på linjer ritat med detta Pen. |
| [dispose()](#dispose--) | Frigör alla resurser som används av detta Pen. |
| [deepClone()](#deepClone--) | Skapar en exakt kopia av denna [Pen](../../com.aspose.drawing/pen). |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Ställer in värdena som bestämmer stil för ändkappen som används för att avsluta linjer som ritas av denna [Pen](../../com.aspose.drawing/pen). |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skalar den lokala geometriska transformationen med de angivna faktorerna. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skalar den lokala geometriska transformationen med de angivna faktorerna i angiven ordning. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i angiven ordning. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rotera den lokala geometriska transformationen med den angivna vinkeln. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rotera den lokala geometriska transformationen med den angivna vinkeln i angiven ordning. |
| [resetTransform()](#resetTransform--) | Återställer den geometriska transformationsmatrisen för denna [Pen](../../com.aspose.drawing/pen) till identitet. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Multiplicerar transformationsmatrisen för denna [Pen](../../com.aspose.drawing/pen) med den angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Multiplicerar transformationsmatrisen för denna [Pen](../../com.aspose.drawing/pen) med den angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix) i angiven ordning. |
### Pen(Color color) {#Pen-com.aspose.drawing.Color-}
```
public Pen(Color color)
```


Initierar en ny instans av [Pen](../../com.aspose.drawing/pen)-klassen med den angivna `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | En `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) som bestämmer fyllningsegenskaperna för denna [Pen](../../com.aspose.drawing/pen). |

### Pen(Brush brush, float width) {#Pen-com.aspose.drawing.Brush-float-}
```
public Pen(Brush brush, float width)
```


Initierar en ny instans av Pen-klassen med den angivna Brush och Width.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | En Brush som bestämmer egenskaperna för denna Pen. |
| bredd | flyttal | Bredden på den nya Pen. |

### Pen(Brush brush) {#Pen-com.aspose.drawing.Brush-}
```
public Pen(Brush brush)
```


Initierar en ny instans av [Pen](../../com.aspose.drawing/pen)-klassen med den angivna `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | En `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)) som bestämmer fyllningsegenskaperna för denna [Pen](../../com.aspose.drawing/pen). |

### Pen(Color color, float width) {#Pen-com.aspose.drawing.Color-float-}
```
public Pen(Color color, float width)
```


Initierar en ny instans av Pen-klassen med de angivna Color- och Width-egenskaperna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | En Color-struktur som anger färgen på denna Pen. |
| bredd | flyttal | Ett värde som anger bredden på denna Pen. |

### getColor() {#getColor--}
```
public final Color getColor()
```


Hämtar eller anger färgen på detta [Pen](../../com.aspose.drawing/pen).

Värde: En `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) struktur som representerar färgen på denna [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Color](../../com.aspose.drawing/color)
### setColor(Color value) {#setColor-com.aspose.drawing.Color-}
```
public final void setColor(Color value)
```


Hämtar eller anger färgen på detta [Pen](../../com.aspose.drawing/pen).

Värde: En `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) struktur som representerar färgen på denna [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Hämtar eller anger Brush som bestämmer attribut för detta [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Brush](../../com.aspose.drawing/brush)
### setBrush(Brush value) {#setBrush-com.aspose.drawing.Brush-}
```
public final void setBrush(Brush value)
```


Hämtar eller anger Brush som bestämmer attribut för detta [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Brush](../../com.aspose.drawing/brush) |  |

### getCompoundArray() {#getCompoundArray--}
```
public final float[] getCompoundArray()
```


Hämtar eller anger en array av värden som specificerar en sammansatt penna. En sammansatt penna ritar en sammansatt linje bestående av parallella linjer och mellanrum.

**Returns:**
float[] - En array av reella tal som specificerar den sammansatta arrayen. Elementen i arrayen måste vara i stigande ordning, inte mindre än 0 och inte större än 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public final void setCompoundArray(float[] value)
```


Hämtar eller anger en array av värden som specificerar en sammansatt penna. En sammansatt penna ritar en sammansatt linje bestående av parallella linjer och mellanrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float[] |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Hämtar eller anger bredden på detta Pen, i enheter av Graphics-objektet som används för ritning.

**Returns:**
flyttal
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Hämtar eller anger bredden på detta Pen, i enheter av Graphics-objektet som används för ritning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | flyttal |  |

### getStartCap() {#getStartCap--}
```
public final int getStartCap()
```


Hämtar eller anger kapslingsstilen som används i början av linjer som ritas med detta Pen.

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public final void setStartCap(int value)
```


Hämtar eller anger kapslingsstilen som används i början av linjer som ritas med detta Pen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public final int getEndCap()
```


Hämtar eller anger kapslingsstilen som används i slutet av linjer som ritas med detta Pen.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public final void setEndCap(int value)
```


Hämtar eller anger kapslingsstilen som används i slutet av linjer som ritas med detta Pen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public final int getLineJoin()
```


Hämtar eller anger sammanfogningsstilen för ändarna på två på varandra följande linjer som ritas med detta Pen.

--------------------

För närvarande fungerar Miter-fog faktiskt som MiterClipped.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public final void setLineJoin(int value)
```


Hämtar eller anger sammanfogningsstilen för ändarna på två på varandra följande linjer som ritas med detta Pen.

--------------------

För närvarande fungerar Miter-fog faktiskt som MiterClipped.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


Hämtar eller anger gränsen för tjockleken på sammanfogningen på ett snedkantigt hörn.

**Returns:**
flyttal
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


Hämtar eller anger gränsen för tjockleken på sammanfogningen på ett snedkantigt hörn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | flyttal |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Hämtar eller anger justeringen för detta [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - En [PenAlignment](../../com.aspose.drawing.drawing2d/penalignment) som representerar justeringen för denna [Pen](../../com.aspose.drawing/pen).
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Hämtar eller anger justeringen för detta [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public final Matrix getTransform()
```


Hämtar eller anger en kopia av den geometriska transformationen för detta [Pen](../../com.aspose.drawing/pen).

Värde: En kopia av [Matrix](../../com.aspose.drawing.drawing2d/matrix) som representerar den geometriska transformationen för denna [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void setTransform(Matrix value)
```


Hämtar eller anger en kopia av den geometriska transformationen för detta [Pen](../../com.aspose.drawing/pen).

Värde: En kopia av [Matrix](../../com.aspose.drawing.drawing2d/matrix) som representerar den geometriska transformationen för denna [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getCustomStartCap() {#getCustomStartCap--}
```
public final CustomLineCap getCustomStartCap()
```


Hämtar eller anger en anpassad kapsling att använda i början av linjer som ritas med detta [Pen](../../com.aspose.drawing/pen).

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the beginning of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomStartCap(CustomLineCap value)
```


Hämtar eller anger en anpassad kapsling att använda i början av linjer som ritas med detta [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getCustomEndCap() {#getCustomEndCap--}
```
public final CustomLineCap getCustomEndCap()
```


Hämtar eller anger en anpassad kapsling att använda i slutet av linjer som ritas med detta [Pen](../../com.aspose.drawing/pen).

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the end of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomEndCap(CustomLineCap value)
```


Hämtar eller anger en anpassad kapsling att använda i slutet av linjer som ritas med detta [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getDashCap() {#getDashCap--}
```
public final int getDashCap()
```


Hämtar eller anger kapslingsstilen som används i slutet av strecken som utgör streckade linjer ritat med detta [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - Ett av `DashCap`([.getDashCap](../../null/\#getDashCap)/[.setDashCap(int)](../../null/\#setDashCap-int-)) värdena som representerar kapps stilen som används i början och slutet av strecken som utgör streckade linjer ritade med denna [Pen](../../com.aspose.drawing/pen).
### setDashCap(int value) {#setDashCap-int-}
```
public final void setDashCap(int value)
```


Hämtar eller anger kapslingsstilen som används i slutet av strecken som utgör streckade linjer ritat med detta [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public final float getDashOffset()
```


Hämtar eller anger avståndet från början av en linje till början av ett streckmönster.

**Returns:**
float - Avståndet från början av en linje till början av ett streckmönster.
### setDashOffset(float value) {#setDashOffset-float-}
```
public final void setDashOffset(float value)
```


Hämtar eller anger avståndet från början av en linje till början av ett streckmönster.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | flyttal |  |

### getDashPattern() {#getDashPattern--}
```
public final float[] getDashPattern()
```


Hämtar eller anger en array av anpassade streck och mellanslag.

**Returns:**
float[] - En array av reella tal som specificerar längderna på alternerande streck och mellanrum i streckade linjer.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public final void setDashPattern(float[] value)
```


Hämtar eller anger en array av anpassade streck och mellanslag.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float[] |  |

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Hämtar eller anger stilen som används för streckade linjer ritat med detta [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - En `DashStyle`([.getDashStyle](../../null/\#getDashStyle)/[.setDashStyle(int)](../../null/\#setDashStyle-int-)) som representerar stilen som används för streckade linjer ritade med denna [Pen](../../com.aspose.drawing/pen).
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Hämtar eller anger stilen som används för streckade linjer ritat med detta [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPenType() {#getPenType--}
```
public final int getPenType()
```


Hämtar stilen på linjer ritat med detta Pen.

Värde: En `PenType`([.getPenType](../../null/\#getPenType))‑enumeration som specificerar stil på linjer ritade med denna [Pen](../../com.aspose.drawing/pen).

**Returns:**
int
### dispose() {#dispose--}
```
public final void dispose()
```


Frigör alla resurser som används av detta Pen.

--------------------

Denna metod gör faktiskt ingenting. Den finns bara för kompatibilitet med System.Drawing‑API:et.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Skapar en exakt kopia av denna [Pen](../../com.aspose.drawing/pen).

**Returns:**
java.lang.Object - Ett objekt som kan kastas till en [Pen](../../com.aspose.drawing/pen).
### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public final void setLineCap(int startCap, int endCap, int dashCap)
```


Ställer in värdena som bestämmer stil för ändkappen som används för att avsluta linjer som ritas av denna [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startCap | int | En [LineCap](../../com.aspose.drawing.drawing2d/linecap) som representerar toppsstil att använda i början av linjer ritade med denna [Pen](../../com.aspose.drawing/pen). |
| endCap | int | En [LineCap](../../com.aspose.drawing.drawing2d/linecap) som representerar toppsstil att använda i slutet av linjer ritade med denna [Pen](../../com.aspose.drawing/pen). |
| dashCap | int | En [LineCap](../../com.aspose.drawing.drawing2d/linecap) som representerar toppsstil att använda i början eller slutet av streckade linjer ritade med denna [Pen](../../com.aspose.drawing/pen). |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public final void scaleTransform(float sx, float sy)
```


Skalar den lokala geometriska transformationen med de angivna faktorerna. Denna metod lägger till skalningsmatrisen i början av transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | flyttal | Faktorn som används för att skala transformationen i x‑axelns riktning. |
| sy | flyttal | Faktorn som används för att skala transformationen i y‑axelns riktning. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public final void scaleTransform(float sx, float sy, int order)
```


Skalar den lokala geometriska transformationen med de angivna faktorerna i angiven ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | flyttal | Faktorn som används för att skala transformationen i x‑axelns riktning. |
| sy | flyttal | Faktorn som används för att skala transformationen i y‑axelns riktning. |
| order | int | En [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) som anger om skalningsmatrisen ska läggas till i slutet eller i början. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public final void translateTransform(float dx, float dy)
```


Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod lägger till förflyttningen i början av transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | flyttal | Värdet för översättningen i x. |
| dy | flyttal | Värdet för översättningen i y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public final void translateTransform(float dx, float dy, int order)
```


Översätter den lokala geometriska transformationen med de angivna dimensionerna i angiven ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | flyttal | Värdet för översättningen i x. |
| dy | flyttal | Värdet för översättningen i y. |
| ordning | int | Ordningen (före eller efter) som översättningen ska tillämpas i. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public final void rotateTransform(float angle)
```


Roterar den lokala geometriska transformationen med den angivna vinkeln. Denna metod lägger till rotationen i början av transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | flyttal | Rotationsvinkeln. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public final void rotateTransform(float angle, int order)
```


Rotera den lokala geometriska transformationen med den angivna vinkeln i angiven ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | flyttal | Rotationsvinkeln. |
| order | int | En [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) som anger om rotationsmatrisen ska läggas till i slutet eller i början. |

### resetTransform() {#resetTransform--}
```
public final void resetTransform()
```


Återställer den geometriska transformationsmatrisen för denna [Pen](../../com.aspose.drawing/pen) till identitet.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void multiplyTransform(Matrix matrix)
```


Multiplicerar transformationsmatrisen för denna [Pen](../../com.aspose.drawing/pen) med den angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Det [Matrix](../../com.aspose.drawing.drawing2d/matrix)-objekt som ska multipliceras med transformationsmatrisen. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public final void multiplyTransform(Matrix matrix, int order)
```


Multiplicerar transformationsmatrisen för denna [Pen](../../com.aspose.drawing/pen) med den angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix) i angiven ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Den java.awt.geom.AffineTransform som ska multipliceras med transformationsmatrisen. |
| ordning | int | Den ordning i vilken multiplikationsoperationen ska utföras. |

