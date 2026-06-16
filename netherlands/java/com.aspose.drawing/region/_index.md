---
title: Region
second_title: Aspose.Drawing voor Java API-referentie
description: Beschrijft het interieur van een grafische vorm die bestaat uit rechthoeken en paden.
type: docs
weight: 40
url: /nl/java/com.aspose.drawing/region/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Region implements System.IDisposable
```

Beschrijft het interieur van een grafische vorm bestaande uit rechthoeken en paden. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Region()](#Region--) | Initialiseert een nieuw exemplaar van de [Region](../../com.aspose.drawing/region) klasse. |
| [Region(RectangleF rect)](#Region-com.aspose.drawing.RectangleF-) | Initialiseert een nieuw exemplaar van de [Region](../../com.aspose.drawing/region) klasse vanuit de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) structuur. |
| [Region(Rectangle rect)](#Region-com.aspose.drawing.Rectangle-) | Initialiseert een nieuw exemplaar van de [Region](../../com.aspose.drawing/region) klasse vanuit de opgegeven [Rectangle](../../com.aspose.drawing/rectangle) structuur. |
| [Region(GraphicsPath path)](#Region-com.aspose.drawing.drawing2d.GraphicsPath-) | Initialiseert een nieuw exemplaar van de [Region](../../com.aspose.drawing/region) klasse met het opgegeven [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [Region(RegionData rgnData)](#Region-com.aspose.drawing.drawing2d.RegionData-) | Initialiseert een nieuw exemplaar van de [Region](../../com.aspose.drawing/region) klasse vanuit de opgegeven gegevens. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [dispose()](#dispose--) | Geeft alle bronnen vrij die door deze [Region](../../com.aspose.drawing/region) worden gebruikt. |
| [equals(Region region, Graphics g)](#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-) | Test of de opgegeven [Region](../../com.aspose.drawing/region) identiek is aan deze [Region](../../com.aspose.drawing/region) op het opgegeven tekenoppervlak. |
| [deepClone()](#deepClone--) | Maakt een exacte kopie van deze [Region](../../com.aspose.drawing/region). |
| [makeInfinite()](#makeInfinite--) | Initialiseert dit [Region](../../com.aspose.drawing/region)-object met een oneindig binnengebied. |
| [makeEmpty()](#makeEmpty--) | Initialiseert deze [Region](../../com.aspose.drawing/region) met een leeg binnengebied. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Werk deze [Region](../../com.aspose.drawing/region) bij naar de doorsnede van zichzelf met de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef)-structuur. |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Werk deze [Region](../../com.aspose.drawing/region) bij naar de doorsnede van zichzelf met de opgegeven [Rectangle](../../com.aspose.drawing/rectangle)-structuur. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.drawing.drawing2d.GraphicsPath-) | Werk deze [Region](../../com.aspose.drawing/region) bij naar de doorsnede van zichzelf met het opgegeven [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [intersect(Region region)](#intersect-com.aspose.drawing.Region-) | Werk deze [Region](../../com.aspose.drawing/region) bij naar de doorsnede van zichzelf met de opgegeven [Region](../../com.aspose.drawing/region). |
| [union(RectangleF rect)](#union-com.aspose.drawing.RectangleF-) | Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie van zichzelf en de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef)-structuur. |
| [union(Rectangle rect)](#union-com.aspose.drawing.Rectangle-) | Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie van zichzelf en de opgegeven [Rectangle](../../com.aspose.drawing/rectangle)-structuur. |
| [union(GraphicsPath path)](#union-com.aspose.drawing.drawing2d.GraphicsPath-) | Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie van zichzelf en het opgegeven [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [union(Region region)](#union-com.aspose.drawing.Region-) | Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie van zichzelf en de opgegeven [Region](../../com.aspose.drawing/region). |
| [getRegionData()](#getRegionData--) | Retourneert een [RegionData](../../com.aspose.drawing.drawing2d/regiondata) die de informatie weergeeft die deze [Region](../../com.aspose.drawing/region) beschrijft. |
| [xor(RectangleF rect)](#xor-com.aspose.drawing.RectangleF-) | Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie min de doorsnede van zichzelf met de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef)-structuur. |
| [xor(Rectangle rect)](#xor-com.aspose.drawing.Rectangle-) | Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie min de doorsnede van zichzelf met de opgegeven [Rectangle](../../com.aspose.drawing/rectangle)-structuur. |
| [xor(GraphicsPath path)](#xor-com.aspose.drawing.drawing2d.GraphicsPath-) | Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie min de doorsnede van zichzelf met het opgegeven [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [xor(Region region)](#xor-com.aspose.drawing.Region-) | Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie min de doorsnede van zichzelf met de opgegeven [Region](../../com.aspose.drawing/region). |
| [exclude(RectangleF rect)](#exclude-com.aspose.drawing.RectangleF-) | Werk deze [Region](../../com.aspose.drawing/region) bij zodat deze alleen het gedeelte van zijn binnengebied bevat dat niet overlapt met de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef)-structuur. |
| [exclude(Rectangle rect)](#exclude-com.aspose.drawing.Rectangle-) | Werk deze [Region](../../com.aspose.drawing/region) bij zodat deze alleen het gedeelte van zijn binnengebied bevat dat niet overlapt met de opgegeven [Rectangle](../../com.aspose.drawing/rectangle)-structuur. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.drawing.drawing2d.GraphicsPath-) | Werk deze [Region](../../com.aspose.drawing/region) bij zodat deze alleen het gedeelte van zijn binnengebied bevat dat niet overlapt met het opgegeven [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [exclude(Region region)](#exclude-com.aspose.drawing.Region-) | Werk deze [Region](../../com.aspose.drawing/region) bij zodat deze alleen het gedeelte van zijn binnengebied bevat dat niet overlapt met de opgegeven [Region](../../com.aspose.drawing/region). |
| [complement(RectangleF rect)](#complement-com.aspose.drawing.RectangleF-) | Werk deze [Region](../../com.aspose.drawing/region) bij zodat deze het gedeelte van de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef)-structuur bevat dat niet overlapt met deze [Region](../../com.aspose.drawing/region). |
| [complement(Rectangle rect)](#complement-com.aspose.drawing.Rectangle-) | Werk deze [Region](../../com.aspose.drawing/region) bij zodat deze het gedeelte van de opgegeven [Rectangle](../../com.aspose.drawing/rectangle)-structuur bevat dat niet overlapt met deze [Region](../../com.aspose.drawing/region). |
| [complement(GraphicsPath path)](#complement-com.aspose.drawing.drawing2d.GraphicsPath-) | Werk deze [Region](../../com.aspose.drawing/region) bij zodat deze het gedeelte van het opgegeven [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) bevat dat niet overlapt met deze [Region](../../com.aspose.drawing/region). |
| [complement(Region region)](#complement-com.aspose.drawing.Region-) | Werk dit [Region](../../com.aspose.drawing/region) bij zodat het het gedeelte van de opgegeven [Region](../../com.aspose.drawing/region) bevat dat niet intersecteert met dit [Region](../../com.aspose.drawing/region). |
| [translate(float dx, float dy)](#translate-float-float-) | Verschuift de coördinaten van dit [Region](../../com.aspose.drawing/region) met de opgegeven hoeveelheid. |
| [translate(int dx, int dy)](#translate-int-int-) | Verschuift de coördinaten van dit [Region](../../com.aspose.drawing/region) met de opgegeven hoeveelheid. |
| [transform(Matrix matrix)](#transform-com.aspose.drawing.drawing2d.Matrix-) | Transformeert dit [Region](../../com.aspose.drawing/region) met de opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [getBounds(Graphics g)](#getBounds-com.aspose.drawing.Graphics-) | Haalt een [RectangleF](../../com.aspose.drawing/rectanglef) structuur op die een rechthoek weergeeft die dit [Region](../../com.aspose.drawing/region) begrenst op het tekenoppervlak van een [Graphics](../../com.aspose.drawing/graphics) object. |
| [getRegionScans(Matrix matrix)](#getRegionScans-com.aspose.drawing.drawing2d.Matrix-) | Retourneert een array van [RectangleF](../../com.aspose.drawing/rectanglef) structuren die dit [Region](../../com.aspose.drawing/region) benaderen nadat de opgegeven matrixtransformatie is toegepast. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.drawing.Graphics-) | Test of dit [Region](../../com.aspose.drawing/region) een lege binnenkant heeft op het opgegeven tekenoppervlak. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.drawing.Graphics-) | Test of dit [Region](../../com.aspose.drawing/region) een oneindige binnenkant heeft op het opgegeven tekenoppervlak. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Test of het opgegeven punt zich binnen dit [Region](../../com.aspose.drawing/region) bevindt. |
| [isVisible(PointF point)](#isVisible-com.aspose.drawing.PointF-) | Test of de opgegeven [PointF](../../com.aspose.drawing/pointf) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.drawing.Graphics-) | Test of het opgegeven punt zich binnen dit [Region](../../com.aspose.drawing/region) bevindt wanneer getekend met de opgegeven [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-) | Test of de opgegeven [PointF](../../com.aspose.drawing/pointf) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt wanneer getekend met de opgegeven [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Test of een deel van de opgegeven rechthoek zich binnen dit [Region](../../com.aspose.drawing/region) bevindt. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.drawing.RectangleF-) | Test of een deel van de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.drawing.Graphics-) | Test of een deel van de opgegeven rechthoek zich binnen dit [Region](../../com.aspose.drawing/region) bevindt wanneer getekend met de opgegeven [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-) | Test of een deel van de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt wanneer getekend met de opgegeven [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.drawing.Graphics-) | Test of het opgegeven punt zich binnen dit [Region](../../com.aspose.drawing/region) object bevindt wanneer getekend met het opgegeven [Graphics](../../com.aspose.drawing/graphics) object. |
| [isVisible(Point point)](#isVisible-com.aspose.drawing.Point-) | Test of de opgegeven [Point](../../com.aspose.drawing/point) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-) | Test of de opgegeven [Point](../../com.aspose.drawing/point) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt wanneer getekend met de opgegeven [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Test of een deel van de opgegeven rechthoek zich binnen dit [Region](../../com.aspose.drawing/region) bevindt. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.drawing.Rectangle-) | Test of een deel van de opgegeven [Rectangle](../../com.aspose.drawing/rectangle) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.drawing.Graphics-) | Test of een deel van de opgegeven rechthoek zich binnen dit [Region](../../com.aspose.drawing/region) bevindt wanneer getekend met de opgegeven [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-) | Test of een deel van de opgegeven [Rectangle](../../com.aspose.drawing/rectangle) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt wanneer getekend met de opgegeven [Graphics](../../com.aspose.drawing/graphics). |
### Region() {#Region--}
```
public Region()
```


Initialiseert een nieuw exemplaar van de [Region](../../com.aspose.drawing/region) klasse.

### Region(RectangleF rect) {#Region-com.aspose.drawing.RectangleF-}
```
public Region(RectangleF rect)
```


Initialiseert een nieuw exemplaar van de [Region](../../com.aspose.drawing/region) klasse vanuit de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Een [RectangleF](../../com.aspose.drawing/rectanglef) structuur die het binnenste van het nieuwe [Region](../../com.aspose.drawing/region) definieert. |

### Region(Rectangle rect) {#Region-com.aspose.drawing.Rectangle-}
```
public Region(Rectangle rect)
```


Initialiseert een nieuw exemplaar van de [Region](../../com.aspose.drawing/region) klasse vanuit de opgegeven [Rectangle](../../com.aspose.drawing/rectangle) structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Een [Rectangle](../../com.aspose.drawing/rectangle) structuur die het binnenste van het nieuwe [Region](../../com.aspose.drawing/region) definieert. |

### Region(GraphicsPath path) {#Region-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Initialiseert een nieuw exemplaar van de [Region](../../com.aspose.drawing/region) klasse met het opgegeven [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Een [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) die het nieuwe [Region](../../com.aspose.drawing/region) definieert. |

### Region(RegionData rgnData) {#Region-com.aspose.drawing.drawing2d.RegionData-}
```
public Region(RegionData rgnData)
```


Initialiseert een nieuw exemplaar van de [Region](../../com.aspose.drawing/region) klasse vanuit de opgegeven gegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rgnData | [RegionData](../../com.aspose.drawing.drawing2d/regiondata) | Een [RegionData](../../com.aspose.drawing.drawing2d/regiondata) die het binnenste van het nieuwe [Region](../../com.aspose.drawing/region) definieert. |

### dispose() {#dispose--}
```
public void dispose()
```


Geeft alle bronnen vrij die door deze [Region](../../com.aspose.drawing/region) worden gebruikt.

### equals(Region region, Graphics g) {#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-}
```
public boolean equals(Region region, Graphics g)
```


Test of de opgegeven [Region](../../com.aspose.drawing/region) identiek is aan deze [Region](../../com.aspose.drawing/region) op het opgegeven tekenoppervlak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | De [Region](../../com.aspose.drawing/region) om te testen. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Een [Graphics](../../com.aspose.drawing/graphics) die een tekenoppervlak vertegenwoordigt. |

**Returns:**
boolean - true als de binnenkant van de regio identiek is aan de binnenkant van deze regio wanneer de transformatie geassocieerd met de parameter `g` wordt toegepast; anders false.
### deepClone() {#deepClone--}
```
public Region deepClone()
```


Maakt een exacte kopie van deze [Region](../../com.aspose.drawing/region).

**Returns:**
[Region](../../com.aspose.drawing/region) - The [Region](../../com.aspose.drawing/region) that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Initialiseert dit [Region](../../com.aspose.drawing/region)-object met een oneindig binnengebied.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Initialiseert deze [Region](../../com.aspose.drawing/region) met een leeg binnengebied.

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public void intersect(RectangleF rect)
```


Werk deze [Region](../../com.aspose.drawing/region) bij naar de doorsnede van zichzelf met de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef) structuur om te kruisen met deze [Region](../../com.aspose.drawing/region). |

### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public void intersect(Rectangle rect)
```


Werk deze [Region](../../com.aspose.drawing/region) bij naar de doorsnede van zichzelf met de opgegeven [Rectangle](../../com.aspose.drawing/rectangle)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | De [Rectangle](../../com.aspose.drawing/rectangle) structuur om te kruisen met deze [Region](../../com.aspose.drawing/region). |

### intersect(GraphicsPath path) {#intersect-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Werk deze [Region](../../com.aspose.drawing/region) bij naar de doorsnede van zichzelf met het opgegeven [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | De [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) om te kruisen met deze [Region](../../com.aspose.drawing/region). |

### intersect(Region region) {#intersect-com.aspose.drawing.Region-}
```
public void intersect(Region region)
```


Werk deze [Region](../../com.aspose.drawing/region) bij naar de doorsnede van zichzelf met de opgegeven [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | De [Region](../../com.aspose.drawing/region) om te kruisen met deze [Region](../../com.aspose.drawing/region). |

### union(RectangleF rect) {#union-com.aspose.drawing.RectangleF-}
```
public void union(RectangleF rect)
```


Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie van zichzelf en de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | rect | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef) structuur om te verenigen met deze [Region](../../com.aspose.drawing/region). |

--------------------

Vereniging laat een oneindige regio oneindig. |

### union(Rectangle rect) {#union-com.aspose.drawing.Rectangle-}
```
public void union(Rectangle rect)
```


Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie van zichzelf en de opgegeven [Rectangle](../../com.aspose.drawing/rectangle)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | rect | [Rectangle](../../com.aspose.drawing/rectangle) | De [Rectangle](../../com.aspose.drawing/rectangle) structuur om te verenigen met deze [Region](../../com.aspose.drawing/region). |

--------------------

Vereniging laat een oneindige regio oneindig. |

### union(GraphicsPath path) {#union-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie van zichzelf en het opgegeven [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | De [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) om te verenigen met deze [Region](../../com.aspose.drawing/region). |

--------------------

Vereniging laat een oneindige regio oneindig. |

### union(Region region) {#union-com.aspose.drawing.Region-}
```
public void union(Region region)
```


Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie van zichzelf en de opgegeven [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | region | [Region](../../com.aspose.drawing/region) | De [Region](../../com.aspose.drawing/region) om te verenigen met deze [Region](../../com.aspose.drawing/region). |

--------------------

Vereniging laat een oneindige regio oneindig. |

### getRegionData() {#getRegionData--}
```
public RegionData getRegionData()
```


Retourneert een [RegionData](../../com.aspose.drawing.drawing2d/regiondata) die de informatie weergeeft die deze [Region](../../com.aspose.drawing/region) beschrijft.

**Returns:**
[RegionData](../../com.aspose.drawing.drawing2d/regiondata) - A [RegionData](../../com.aspose.drawing.drawing2d/regiondata) that represents the information that describes this [Region](../../com.aspose.drawing/region).
### xor(RectangleF rect) {#xor-com.aspose.drawing.RectangleF-}
```
public void xor(RectangleF rect)
```


Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie min de doorsnede van zichzelf met de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef) structuur om `M:Region.Xor(Drawing2D.GraphicsPath)` met deze [Region](../../com.aspose.drawing/region). |

### xor(Rectangle rect) {#xor-com.aspose.drawing.Rectangle-}
```
public void xor(Rectangle rect)
```


Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie min de doorsnede van zichzelf met de opgegeven [Rectangle](../../com.aspose.drawing/rectangle)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | De [Rectangle](../../com.aspose.drawing/rectangle) structuur om `M:Region.Xor(Rectangle)` met deze [Region](../../com.aspose.drawing/region). |

### xor(GraphicsPath path) {#xor-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie min de doorsnede van zichzelf met het opgegeven [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | De [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) structuur om `M:Region.Xor(GraphicsPath)` met deze [Region](../../com.aspose.drawing/region). |

### xor(Region region) {#xor-com.aspose.drawing.Region-}
```
public void xor(Region region)
```


Werk deze [Region](../../com.aspose.drawing/region) bij naar de unie min de doorsnede van zichzelf met de opgegeven [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | De [Region](../../com.aspose.drawing/region) structuur om `M:Region.Xor(Region)` met deze [Region](../../com.aspose.drawing/region). |

### exclude(RectangleF rect) {#exclude-com.aspose.drawing.RectangleF-}
```
public void exclude(RectangleF rect)
```


Werk deze [Region](../../com.aspose.drawing/region) bij zodat deze alleen het gedeelte van zijn binnengebied bevat dat niet overlapt met de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef) structuur om uit te sluiten van deze [Region](../../com.aspose.drawing/region). |

### exclude(Rectangle rect) {#exclude-com.aspose.drawing.Rectangle-}
```
public void exclude(Rectangle rect)
```


Werk deze [Region](../../com.aspose.drawing/region) bij zodat deze alleen het gedeelte van zijn binnengebied bevat dat niet overlapt met de opgegeven [Rectangle](../../com.aspose.drawing/rectangle)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | De [Rectangle](../../com.aspose.drawing/rectangle) structuur om uit te sluiten van deze [Region](../../com.aspose.drawing/region). |

### exclude(GraphicsPath path) {#exclude-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Werk deze [Region](../../com.aspose.drawing/region) bij zodat deze alleen het gedeelte van zijn binnengebied bevat dat niet overlapt met het opgegeven [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | De [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) structuur om uit te sluiten van deze [Region](../../com.aspose.drawing/region). |

### exclude(Region region) {#exclude-com.aspose.drawing.Region-}
```
public void exclude(Region region)
```


Werk deze [Region](../../com.aspose.drawing/region) bij zodat deze alleen het gedeelte van zijn binnengebied bevat dat niet overlapt met de opgegeven [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | De [Region](../../com.aspose.drawing/region) structuur om uit te sluiten van deze [Region](../../com.aspose.drawing/region). |

### complement(RectangleF rect) {#complement-com.aspose.drawing.RectangleF-}
```
public void complement(RectangleF rect)
```


Werk deze [Region](../../com.aspose.drawing/region) bij zodat deze het gedeelte van de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef)-structuur bevat dat niet overlapt met deze [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef) structuur om deze [Region](../../com.aspose.drawing/region) aan te vullen. |

### complement(Rectangle rect) {#complement-com.aspose.drawing.Rectangle-}
```
public void complement(Rectangle rect)
```


Werk deze [Region](../../com.aspose.drawing/region) bij zodat deze het gedeelte van de opgegeven [Rectangle](../../com.aspose.drawing/rectangle)-structuur bevat dat niet overlapt met deze [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | De [Rectangle](../../com.aspose.drawing/rectangle) structuur om deze [Region](../../com.aspose.drawing/region) aan te vullen. |

### complement(GraphicsPath path) {#complement-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Werk deze [Region](../../com.aspose.drawing/region) bij zodat deze het gedeelte van het opgegeven [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) bevat dat niet overlapt met deze [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | De [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) structuur om deze [Region](../../com.aspose.drawing/region) aan te vullen. |

### complement(Region region) {#complement-com.aspose.drawing.Region-}
```
public void complement(Region region)
```


Werk dit [Region](../../com.aspose.drawing/region) bij zodat het het gedeelte van de opgegeven [Region](../../com.aspose.drawing/region) bevat dat niet intersecteert met dit [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Het [Region](../../com.aspose.drawing/region) object om dit [Region](../../com.aspose.drawing/region) object aan te vullen. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Verschuift de coördinaten van dit [Region](../../com.aspose.drawing/region) met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | float | De hoeveelheid om deze [Region](../../com.aspose.drawing/region) horizontaal te verschuiven. |
| dy | float | De hoeveelheid om deze [Region](../../com.aspose.drawing/region) verticaal te verschuiven. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Verschuift de coördinaten van dit [Region](../../com.aspose.drawing/region) met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | int | De hoeveelheid om deze [Region](../../com.aspose.drawing/region) horizontaal te verschuiven |
| dy | int | De hoeveelheid om deze [Region](../../com.aspose.drawing/region) verticaal te verschuiven. |

### transform(Matrix matrix) {#transform-com.aspose.drawing.drawing2d.Matrix-}
```
public void transform(Matrix matrix)
```


Transformeert dit [Region](../../com.aspose.drawing/region) met de opgegeven [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | De [Matrix](../../com.aspose.drawing.drawing2d/matrix) waarmee deze [Region](../../com.aspose.drawing/region) wordt getransformeerd. |

### getBounds(Graphics g) {#getBounds-com.aspose.drawing.Graphics-}
```
public RectangleF getBounds(Graphics g)
```


Haalt een [RectangleF](../../com.aspose.drawing/rectanglef) structuur op die een rechthoek weergeeft die dit [Region](../../com.aspose.drawing/region) begrenst op het tekenoppervlak van een [Graphics](../../com.aspose.drawing/graphics) object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | De [Graphics](../../com.aspose.drawing/graphics) waarop deze [Region](../../com.aspose.drawing/region) wordt getekend. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents the bounding rectangle for this [Region](../../com.aspose.drawing/region) on the specified drawing surface.
### getRegionScans(Matrix matrix) {#getRegionScans-com.aspose.drawing.drawing2d.Matrix-}
```
public RectangleF[] getRegionScans(Matrix matrix)
```


Retourneert een array van [RectangleF](../../com.aspose.drawing/rectanglef) structuren die dit [Region](../../com.aspose.drawing/region) benaderen nadat de opgegeven matrixtransformatie is toegepast.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Een [Matrix](../../com.aspose.drawing.drawing2d/matrix) die een geometrische transformatie vertegenwoordigt die op de region moet worden toegepast. |

**Returns:**
com.aspose.drawing.RectangleF[] - Een array van [RectangleF](../../com.aspose.drawing/rectanglef) structuren die deze [Region](../../com.aspose.drawing/region) benaderen nadat de opgegeven matrixtransformatie is toegepast.
### isEmpty(Graphics g) {#isEmpty-com.aspose.drawing.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Test of dit [Region](../../com.aspose.drawing/region) een lege binnenkant heeft op het opgegeven tekenoppervlak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Een [Graphics](../../com.aspose.drawing/graphics) die een tekenoppervlak vertegenwoordigt. |

**Returns:**
boolean - true als de binnenkant van deze [Region](../../com.aspose.drawing/region) leeg is wanneer de transformatie geassocieerd met `g` wordt toegepast; anders false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.drawing.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Test of dit [Region](../../com.aspose.drawing/region) een oneindige binnenkant heeft op het opgegeven tekenoppervlak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Een [Graphics](../../com.aspose.drawing/graphics) die een tekenoppervlak vertegenwoordigt. |

**Returns:**
boolean - true als de binnenkant van deze [Region](../../com.aspose.drawing/region) oneindig is wanneer de transformatie geassocieerd met `g` wordt toegepast; anders false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Test of het opgegeven punt zich binnen dit [Region](../../com.aspose.drawing/region) bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het te testen punt. |
| y | float | De y-coördinaat van het punt om te testen. |

**Returns:**
boolean - true wanneer het opgegeven punt zich binnen deze [Region](../../com.aspose.drawing/region) bevindt; anders false.
### isVisible(PointF point) {#isVisible-com.aspose.drawing.PointF-}
```
public boolean isVisible(PointF point)
```


Test of de opgegeven [PointF](../../com.aspose.drawing/pointf) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | De [PointF](../../com.aspose.drawing/pointf) structuur om te testen. |

**Returns:**
boolean - true wanneer `point` zich binnen deze [Region](../../com.aspose.drawing/region) bevindt; anders false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Test of het opgegeven punt zich binnen dit [Region](../../com.aspose.drawing/region) bevindt wanneer getekend met de opgegeven [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het te testen punt. |
| y | float | De y-coördinaat van het punt om te testen. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Een [Graphics](../../com.aspose.drawing/graphics) die een grafische context vertegenwoordigt. |

**Returns:**
boolean - true wanneer het opgegeven punt zich binnen deze [Region](../../com.aspose.drawing/region) bevindt; anders false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Test of de opgegeven [PointF](../../com.aspose.drawing/pointf) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt wanneer getekend met de opgegeven [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | De [PointF](../../com.aspose.drawing/pointf) structuur om te testen. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Een [Graphics](../../com.aspose.drawing/graphics) die een grafische context vertegenwoordigt. |

**Returns:**
boolean - true wanneer `point` zich binnen deze [Region](../../com.aspose.drawing/region) bevindt; anders false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Test of een deel van de opgegeven rechthoek zich binnen dit [Region](../../com.aspose.drawing/region) bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| y | float | De y-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| breedte | float | De breedte van de te testen rechthoek. |
| hoogte | float | De hoogte van de te testen rechthoek. |

**Returns:**
boolean - true wanneer een deel van de opgegeven rechthoek zich binnen dit [Region](../../com.aspose.drawing/region) object bevindt; anders false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.drawing.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Test of een deel van de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef) structuur om te testen. |

**Returns:**
boolean - true wanneer een deel van `rect` zich binnen dit [Region](../../com.aspose.drawing/region) bevindt; anders false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Test of een deel van de opgegeven rechthoek zich binnen dit [Region](../../com.aspose.drawing/region) bevindt wanneer getekend met de opgegeven [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| y | float | De y-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| breedte | float | De breedte van de te testen rechthoek. |
| hoogte | float | De hoogte van de te testen rechthoek. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Een [Graphics](../../com.aspose.drawing/graphics) die een grafische context vertegenwoordigt. |

**Returns:**
boolean - true wanneer een deel van de opgegeven rechthoek zich binnen dit [Region](../../com.aspose.drawing/region) bevindt; anders false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Test of een deel van de opgegeven [RectangleF](../../com.aspose.drawing/rectanglef) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt wanneer getekend met de opgegeven [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | De [RectangleF](../../com.aspose.drawing/rectanglef) structuur om te testen. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Een [Graphics](../../com.aspose.drawing/graphics) die een grafische context vertegenwoordigt. |

**Returns:**
boolean - true wanneer `rect` zich binnen dit [Region](../../com.aspose.drawing/region) bevindt; anders false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Test of het opgegeven punt zich binnen dit [Region](../../com.aspose.drawing/region) object bevindt wanneer getekend met het opgegeven [Graphics](../../com.aspose.drawing/graphics) object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van het te testen punt. |
| y | int | De y-coördinaat van het punt om te testen. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Een [Graphics](../../com.aspose.drawing/graphics) die een grafische context vertegenwoordigt. |

**Returns:**
boolean - true wanneer het opgegeven punt zich binnen deze [Region](../../com.aspose.drawing/region) bevindt; anders false.
### isVisible(Point point) {#isVisible-com.aspose.drawing.Point-}
```
public boolean isVisible(Point point)
```


Test of de opgegeven [Point](../../com.aspose.drawing/point) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | De [Point](../../com.aspose.drawing/point) structuur om te testen. |

**Returns:**
boolean - true wanneer `point` zich binnen deze [Region](../../com.aspose.drawing/region) bevindt; anders false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Test of de opgegeven [Point](../../com.aspose.drawing/point) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt wanneer getekend met de opgegeven [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | De [Point](../../com.aspose.drawing/point) structuur om te testen. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Een [Graphics](../../com.aspose.drawing/graphics) die een grafische context vertegenwoordigt. |

**Returns:**
boolean - true wanneer `point` zich binnen deze [Region](../../com.aspose.drawing/region) bevindt; anders false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Test of een deel van de opgegeven rechthoek zich binnen dit [Region](../../com.aspose.drawing/region) bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| y | int | De y-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| breedte | int | De breedte van de te testen rechthoek. |
| hoogte | int | De hoogte van de te testen rechthoek. |

**Returns:**
boolean - true wanneer een deel van de opgegeven rechthoek zich binnen dit [Region](../../com.aspose.drawing/region) bevindt; anders false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.drawing.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Test of een deel van de opgegeven [Rectangle](../../com.aspose.drawing/rectangle) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | De [Rectangle](../../com.aspose.drawing/rectangle) structuur om te testen. |

**Returns:**
boolean - Deze methode retourneert true wanneer een deel van `rect` zich binnen dit [Region](../../com.aspose.drawing/region) bevindt; anders false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Test of een deel van de opgegeven rechthoek zich binnen dit [Region](../../com.aspose.drawing/region) bevindt wanneer getekend met de opgegeven [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| y | int | De y-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| breedte | int | De breedte van de te testen rechthoek. |
| hoogte | int | De hoogte van de te testen rechthoek. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Een [Graphics](../../com.aspose.drawing/graphics) die een grafische context vertegenwoordigt. |

**Returns:**
boolean - true wanneer een deel van de opgegeven rechthoek zich binnen dit [Region](../../com.aspose.drawing/region) bevindt; anders false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Test of een deel van de opgegeven [Rectangle](../../com.aspose.drawing/rectangle) structuur zich binnen dit [Region](../../com.aspose.drawing/region) bevindt wanneer getekend met de opgegeven [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | De [Rectangle](../../com.aspose.drawing/rectangle) structuur om te testen. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Een [Graphics](../../com.aspose.drawing/graphics) die een grafische context vertegenwoordigt. |

**Returns:**
boolean - true wanneer een deel van de `rect` zich binnen dit [Region](../../com.aspose.drawing/region) bevindt; anders false.
