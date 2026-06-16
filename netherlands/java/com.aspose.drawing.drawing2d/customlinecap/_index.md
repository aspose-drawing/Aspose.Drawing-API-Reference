---
title: CustomLineCap
second_title: Aspose.Drawing voor Java API-referentie
description: Omsluit een aangepaste door de gebruiker gedefinieerde lijnkap.
type: docs
weight: 17
url: /nl/java/com.aspose.drawing.drawing2d/customlinecap/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class CustomLineCap implements System.IDisposable
```

Omsluit een aangepaste door de gebruiker gedefinieerde lijnkap.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-) | Initialiseert een nieuw exemplaar van de [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) klasse met de opgegeven omtrek en vulling. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-) | Initialiseert een nieuw exemplaar van de [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) klasse vanuit de opgegeven bestaande [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeratie met de opgegeven omtrek en vulling. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-) | Initialiseert een nieuw exemplaar van de [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) klasse vanuit de opgegeven bestaande [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeratie met de opgegeven omtrek, vulling en inset. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getStrokeJoin()](#getStrokeJoin--) | Haalt op of stelt de [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) enumeratie in die bepaalt hoe lijnen die dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) object vormen, worden samengevoegd. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Haalt op of stelt de [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) enumeratie in die bepaalt hoe lijnen die dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) object vormen, worden samengevoegd. |
| [getBaseCap()](#getBaseCap--) | Haalt op of stelt de [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeratie in waarop dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) is gebaseerd. |
| [setBaseCap(int value)](#setBaseCap-int-) | Haalt op of stelt de [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeratie in waarop dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) is gebaseerd. |
| [getBaseInset()](#getBaseInset--) | Haalt op of stelt de afstand tussen de kap en de lijn in. |
| [setBaseInset(float value)](#setBaseInset-float-) | Haalt op of stelt de afstand tussen de kap en de lijn in. |
| [getWidthScale()](#getWidthScale--) | Haalt op of stelt de hoeveelheid in waarmee dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) klasse‑object wordt geschaald ten opzichte van de breedte van het [Pen](../../com.aspose.drawing/pen) object. |
| [setWidthScale(float value)](#setWidthScale-float-) | Haalt op of stelt de hoeveelheid in waarmee dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) klasse‑object wordt geschaald ten opzichte van de breedte van het [Pen](../../com.aspose.drawing/pen) object. |
| [dispose()](#dispose--) | Geeft alle bronnen vrij die door dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) object worden gebruikt. |
| [deepClone()](#deepClone--) | Maakt een exacte kopie van dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Stelt de caps in die worden gebruikt om lijnen te beginnen en te beëindigen die deze aangepaste cap vormen. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Haalt de caps op die worden gebruikt om lijnen te beginnen en te beëindigen die deze aangepaste cap vormen. |
| [getFillPath()](#getFillPath--) |  |
| [getStrokePath()](#getStrokePath--) | Haalt het object op dat de omtrek van de aangepaste cap definieert. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Initialiseert een nieuw exemplaar van de [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) klasse met de opgegeven omtrek en vulling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Een [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-object dat de vulling voor de aangepaste cap definieert. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Een [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-object dat de omtrek van de aangepaste cap definieert. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Initialiseert een nieuw exemplaar van de [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) klasse vanuit de opgegeven bestaande [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeratie met de opgegeven omtrek en vulling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Een [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-object dat de vulling voor de aangepaste cap definieert. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Een [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-object dat de omtrek van de aangepaste cap definieert. |
| baseCap | int | De lijncap waaruit de aangepaste cap wordt gemaakt. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Initialiseert een nieuw exemplaar van de [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) klasse vanuit de opgegeven bestaande [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeratie met de opgegeven omtrek, vulling en inset.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Een [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-object dat de vulling voor de aangepaste cap definieert. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Een [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-object dat de omtrek van de aangepaste cap definieert. |
| baseCap | int | De lijncap waaruit de aangepaste cap wordt gemaakt. |
| baseInset | float | De afstand tussen de cap en de lijn. |

### getStrokeJoin() {#getStrokeJoin--}
```
public final int getStrokeJoin()
```


Haalt op of stelt de [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) enumeratie in die bepaalt hoe lijnen die dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) object vormen, worden samengevoegd.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public final void setStrokeJoin(int value)
```


Haalt op of stelt de [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) enumeratie in die bepaalt hoe lijnen die dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) object vormen, worden samengevoegd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public final int getBaseCap()
```


Haalt op of stelt de [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeratie in waarop dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) is gebaseerd.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public final void setBaseCap(int value)
```


Haalt op of stelt de [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeratie in waarop dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) is gebaseerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public final float getBaseInset()
```


Haalt op of stelt de afstand tussen de kap en de lijn in.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public final void setBaseInset(float value)
```


Haalt op of stelt de afstand tussen de kap en de lijn in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public final float getWidthScale()
```


Haalt op of stelt de hoeveelheid in waarmee dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) klasse‑object wordt geschaald ten opzichte van de breedte van het [Pen](../../com.aspose.drawing/pen) object.

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public final void setWidthScale(float value)
```


Haalt op of stelt de hoeveelheid in waarmee dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) klasse‑object wordt geschaald ten opzichte van de breedte van het [Pen](../../com.aspose.drawing/pen) object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### dispose() {#dispose--}
```
public final void dispose()
```


Geeft alle bronnen vrij die door dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) object worden gebruikt.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Maakt een exacte kopie van dit [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
java.lang.Object - De [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) die deze methode maakt, gecast als een object.
### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public final void setStrokeCaps(int startCap, int endCap)
```


Stelt de caps in die worden gebruikt om lijnen te beginnen en te beëindigen die deze aangepaste cap vormen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startCap | int | De [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumeratie die aan het begin van een lijn binnen deze cap wordt gebruikt. |
| endCap | int | De [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumeratie die aan het einde van een lijn binnen deze cap wordt gebruikt. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public final void getStrokeCaps(int[] startCap, int[] endCap)
```


Haalt de caps op die worden gebruikt om lijnen te beginnen en te beëindigen die deze aangepaste cap vormen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startCap | int[] | De [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumeratie die aan het begin van een lijn binnen deze cap wordt gebruikt. |
| endCap | int[] | De [LineCap](../../com.aspose.drawing.drawing2d/linecap)-enumeratie die aan het einde van een lijn binnen deze cap wordt gebruikt. |

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


Haalt het object op dat de omtrek van de aangepaste cap definieert.

**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) - The object that defines the outline of the custom cap.
