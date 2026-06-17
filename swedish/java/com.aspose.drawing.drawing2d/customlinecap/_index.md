---
title: CustomLineCap
second_title: Aspose.Drawing för Java API‑referens
description: Inkapslar en anpassad användardefinierad linjekap.
type: docs
weight: 17
url: /sv/java/com.aspose.drawing.drawing2d/customlinecap/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class CustomLineCap implements System.IDisposable
```

Inkapslar en anpassad användardefinierad linjekap.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-) | Initierar en ny instans av klassen [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) med den angivna konturen och fyllningen. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-) | Initierar en ny instans av klassen [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) från den angivna befintliga [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumerationen med den angivna konturen och fyllningen. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-) | Initierar en ny instans av klassen [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) från den angivna befintliga [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumerationen med den angivna konturen, fyllningen och insättningen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getStrokeJoin()](#getStrokeJoin--) | Hämtar eller anger [LineJoin](../../com.aspose.drawing.drawing2d/linejoin)-enumerationen som bestämmer hur linjer som utgör detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-objekt sammanfogas. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Hämtar eller anger [LineJoin](../../com.aspose.drawing.drawing2d/linejoin)-enumerationen som bestämmer hur linjer som utgör detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-objekt sammanfogas. |
| [getBaseCap()](#getBaseCap--) | Hämtar eller anger [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumerationen som detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) är baserat på. |
| [setBaseCap(int value)](#setBaseCap-int-) | Hämtar eller anger [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumerationen som detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) är baserat på. |
| [getBaseInset()](#getBaseInset--) | Hämtar eller anger avståndet mellan toppen och linjen. |
| [setBaseInset(float value)](#setBaseInset-float-) | Hämtar eller anger avståndet mellan toppen och linjen. |
| [getWidthScale()](#getWidthScale--) | Hämtar eller anger hur mycket detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-klassobjekt ska skalas i förhållande till bredden på [Pen](../../com.aspose.drawing/pen)-objektet. |
| [setWidthScale(float value)](#setWidthScale-float-) | Hämtar eller anger hur mycket detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-klassobjekt ska skalas i förhållande till bredden på [Pen](../../com.aspose.drawing/pen)-objektet. |
| [dispose()](#dispose--) | Frigör alla resurser som används av detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-objekt. |
| [deepClone()](#deepClone--) | Skapar en exakt kopia av detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Ställer in de spetsar som används för att starta och avsluta linjer som utgör denna anpassade spets. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Hämtar de spetsar som används för att starta och avsluta linjer som utgör denna anpassade spets. |
| [getFillPath()](#getFillPath--) |  |
| [getStrokePath()](#getStrokePath--) | Hämtar objektet som definierar konturen av den anpassade spetsen. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Initierar en ny instans av klassen [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) med den angivna konturen och fyllningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ett [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-objekt som definierar fyllningen för den anpassade spetsen. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ett [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-objekt som definierar konturen av den anpassade spetsen. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Initierar en ny instans av klassen [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) från den angivna befintliga [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumerationen med den angivna konturen och fyllningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ett [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-objekt som definierar fyllningen för den anpassade spetsen. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ett [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-objekt som definierar konturen av den anpassade spetsen. |
| baseCap | int | Linjespetsen som den anpassade spetsen ska skapas från. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Initierar en ny instans av klassen [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) från den angivna befintliga [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumerationen med den angivna konturen, fyllningen och insättningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ett [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-objekt som definierar fyllningen för den anpassade spetsen. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ett [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-objekt som definierar konturen av den anpassade spetsen. |
| baseCap | int | Linjespetsen som den anpassade spetsen ska skapas från. |
| baseInset | flyttal | Avståndet mellan spetsen och linjen. |

### getStrokeJoin() {#getStrokeJoin--}
```
public final int getStrokeJoin()
```


Hämtar eller anger [LineJoin](../../com.aspose.drawing.drawing2d/linejoin)-enumerationen som bestämmer hur linjer som utgör detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-objekt sammanfogas.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public final void setStrokeJoin(int value)
```


Hämtar eller anger [LineJoin](../../com.aspose.drawing.drawing2d/linejoin)-enumerationen som bestämmer hur linjer som utgör detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-objekt sammanfogas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public final int getBaseCap()
```


Hämtar eller anger [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumerationen som detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) är baserat på.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public final void setBaseCap(int value)
```


Hämtar eller anger [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumerationen som detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) är baserat på.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public final float getBaseInset()
```


Hämtar eller anger avståndet mellan toppen och linjen.

**Returns:**
flyttal
### setBaseInset(float value) {#setBaseInset-float-}
```
public final void setBaseInset(float value)
```


Hämtar eller anger avståndet mellan toppen och linjen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | flyttal |  |

### getWidthScale() {#getWidthScale--}
```
public final float getWidthScale()
```


Hämtar eller anger hur mycket detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-klassobjekt ska skalas i förhållande till bredden på [Pen](../../com.aspose.drawing/pen)-objektet.

**Returns:**
flyttal
### setWidthScale(float value) {#setWidthScale-float-}
```
public final void setWidthScale(float value)
```


Hämtar eller anger hur mycket detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-klassobjekt ska skalas i förhållande till bredden på [Pen](../../com.aspose.drawing/pen)-objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | flyttal |  |

### dispose() {#dispose--}
```
public final void dispose()
```


Frigör alla resurser som används av detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-objekt.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Skapar en exakt kopia av detta [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
java.lang.Object - Den [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) som denna metod skapar, kastad som ett objekt.
### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public final void setStrokeCaps(int startCap, int endCap)
```


Ställer in de spetsar som används för att starta och avsluta linjer som utgör denna anpassade spets.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startCap | int | Den [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumerationen som används i början av en linje inom denna spets. |
| endCap | int | Den [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumerationen som används i slutet av en linje inom denna spets. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public final void getStrokeCaps(int[] startCap, int[] endCap)
```


Hämtar de spetsar som används för att starta och avsluta linjer som utgör denna anpassade spets.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startCap | int[] | Den [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumerationen som används i början av en linje inom denna spets. |
| endCap | int[] | Den [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumerationen som används i slutet av en linje inom denna spets. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```




**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Hämtar objektet som definierar konturen av den anpassade spetsen.

**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) - The object that defines the outline of the custom cap.
