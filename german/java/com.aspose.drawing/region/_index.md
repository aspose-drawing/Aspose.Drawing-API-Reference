---
title: Region
second_title: Aspose.Drawing für Java API-Referenz
description: Beschreibt das Innere einer Grafikform, die aus Rechtecken und Pfaden besteht.
type: docs
weight: 40
url: /de/java/com.aspose.drawing/region/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Region implements System.IDisposable
```

Beschreibt das Innere einer Grafikform, die aus Rechtecken und Pfaden besteht. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Region()](#Region--) | Initialisiert eine neue Instanz der Klasse [Region](../../com.aspose.drawing/region). |
| [Region(RectangleF rect)](#Region-com.aspose.drawing.RectangleF-) | Initialisiert eine neue Instanz der Klasse [Region](../../com.aspose.drawing/region) aus der angegebenen Struktur [RectangleF](../../com.aspose.drawing/rectanglef). |
| [Region(Rectangle rect)](#Region-com.aspose.drawing.Rectangle-) | Initialisiert eine neue Instanz der Klasse [Region](../../com.aspose.drawing/region) aus der angegebenen Struktur [Rectangle](../../com.aspose.drawing/rectangle). |
| [Region(GraphicsPath path)](#Region-com.aspose.drawing.drawing2d.GraphicsPath-) | Initialisiert eine neue Instanz der Klasse [Region](../../com.aspose.drawing/region) mit dem angegebenen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [Region(RegionData rgnData)](#Region-com.aspose.drawing.drawing2d.RegionData-) | Initialisiert eine neue Instanz der Klasse [Region](../../com.aspose.drawing/region) aus den angegebenen Daten. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [dispose()](#dispose--) | Gibt alle von dieser [Region](../../com.aspose.drawing/region) verwendeten Ressourcen frei. |
| [equals(Region region, Graphics g)](#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-) | Prüft, ob die angegebene [Region](../../com.aspose.drawing/region) auf der angegebenen Zeichenfläche identisch mit dieser [Region](../../com.aspose.drawing/region) ist. |
| [deepClone()](#deepClone--) | Erstellt eine exakte Kopie dieser [Region](../../com.aspose.drawing/region). |
| [makeInfinite()](#makeInfinite--) | Initialisiert dieses [Region](../../com.aspose.drawing/region)-Objekt mit einem unendlichen Innenbereich. |
| [makeEmpty()](#makeEmpty--) | Initialisiert diese [Region](../../com.aspose.drawing/region) mit einem leeren Innenbereich. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Schnittmenge mit der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur. |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Schnittmenge mit der angegebenen [Rectangle](../../com.aspose.drawing/rectangle)-Struktur. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.drawing.drawing2d.GraphicsPath-) | Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Schnittmenge mit dem angegebenen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [intersect(Region region)](#intersect-com.aspose.drawing.Region-) | Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Schnittmenge mit der angegebenen [Region](../../com.aspose.drawing/region). |
| [union(RectangleF rect)](#union-com.aspose.drawing.RectangleF-) | Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung mit der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur. |
| [union(Rectangle rect)](#union-com.aspose.drawing.Rectangle-) | Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung mit der angegebenen [Rectangle](../../com.aspose.drawing/rectangle)-Struktur. |
| [union(GraphicsPath path)](#union-com.aspose.drawing.drawing2d.GraphicsPath-) | Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung mit dem angegebenen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [union(Region region)](#union-com.aspose.drawing.Region-) | Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung mit der angegebenen [Region](../../com.aspose.drawing/region). |
| [getRegionData()](#getRegionData--) | Gibt ein [RegionData](../../com.aspose.drawing.drawing2d/regiondata) zurück, das die Informationen darstellt, die diese [Region](../../com.aspose.drawing/region) beschreiben. |
| [xor(RectangleF rect)](#xor-com.aspose.drawing.RectangleF-) | Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung minus die Schnittmenge mit der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur. |
| [xor(Rectangle rect)](#xor-com.aspose.drawing.Rectangle-) | Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung minus die Schnittmenge mit der angegebenen [Rectangle](../../com.aspose.drawing/rectangle)-Struktur. |
| [xor(GraphicsPath path)](#xor-com.aspose.drawing.drawing2d.GraphicsPath-) | Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung minus die Schnittmenge mit dem angegebenen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [xor(Region region)](#xor-com.aspose.drawing.Region-) | Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung minus die Schnittmenge mit der angegebenen [Region](../../com.aspose.drawing/region). |
| [exclude(RectangleF rect)](#exclude-com.aspose.drawing.RectangleF-) | Aktualisiert diese [Region](../../com.aspose.drawing/region), sodass sie nur den Teil ihres Innenbereichs enthält, der nicht mit der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur schneidet. |
| [exclude(Rectangle rect)](#exclude-com.aspose.drawing.Rectangle-) | Aktualisiert diese [Region](../../com.aspose.drawing/region), sodass sie nur den Teil ihres Innenbereichs enthält, der nicht mit der angegebenen [Rectangle](../../com.aspose.drawing/rectangle)-Struktur schneidet. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.drawing.drawing2d.GraphicsPath-) | Aktualisiert diese [Region](../../com.aspose.drawing/region), sodass sie nur den Teil ihres Innenbereichs enthält, der nicht mit dem angegebenen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) schneidet. |
| [exclude(Region region)](#exclude-com.aspose.drawing.Region-) | Aktualisiert diese [Region](../../com.aspose.drawing/region), sodass sie nur den Teil ihres Innenbereichs enthält, der nicht mit der angegebenen [Region](../../com.aspose.drawing/region) schneidet. |
| [complement(RectangleF rect)](#complement-com.aspose.drawing.RectangleF-) | Aktualisiert diese [Region](../../com.aspose.drawing/region), sodass sie den Teil der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur enthält, der nicht mit dieser [Region](../../com.aspose.drawing/region) schneidet. |
| [complement(Rectangle rect)](#complement-com.aspose.drawing.Rectangle-) | Aktualisiert diese [Region](../../com.aspose.drawing/region), sodass sie den Teil der angegebenen [Rectangle](../../com.aspose.drawing/rectangle)-Struktur enthält, der nicht mit dieser [Region](../../com.aspose.drawing/region) schneidet. |
| [complement(GraphicsPath path)](#complement-com.aspose.drawing.drawing2d.GraphicsPath-) | Aktualisiert diese [Region](../../com.aspose.drawing/region), sodass sie den Teil des angegebenen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) enthält, der nicht mit dieser [Region](../../com.aspose.drawing/region) schneidet. |
| [complement(Region region)](#complement-com.aspose.drawing.Region-) | Aktualisiert dieses [Region](../../com.aspose.drawing/region), sodass es den Teil des angegebenen [Region](../../com.aspose.drawing/region) enthält, der nicht mit diesem [Region](../../com.aspose.drawing/region) überschneidet. |
| [translate(float dx, float dy)](#translate-float-float-) | Verschiebt die Koordinaten dieses [Region](../../com.aspose.drawing/region) um den angegebenen Betrag. |
| [translate(int dx, int dy)](#translate-int-int-) | Verschiebt die Koordinaten dieses [Region](../../com.aspose.drawing/region) um den angegebenen Betrag. |
| [transform(Matrix matrix)](#transform-com.aspose.drawing.drawing2d.Matrix-) | Transformiert dieses [Region](../../com.aspose.drawing/region) mit der angegebenen [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [getBounds(Graphics g)](#getBounds-com.aspose.drawing.Graphics-) | Gibt eine [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur zurück, die ein Rechteck darstellt, das dieses [Region](../../com.aspose.drawing/region) auf der Zeichenfläche eines [Graphics](../../com.aspose.drawing/graphics)-Objekts begrenzt. |
| [getRegionScans(Matrix matrix)](#getRegionScans-com.aspose.drawing.drawing2d.Matrix-) | Gibt ein Array von [RectangleF](../../com.aspose.drawing/rectanglef)-Strukturen zurück, die dieses [Region](../../com.aspose.drawing/region) nach Anwendung der angegebenen Matrixtransformation annähern. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.drawing.Graphics-) | Prüft, ob dieses [Region](../../com.aspose.drawing/region) auf der angegebenen Zeichenfläche ein leeres Inneres hat. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.drawing.Graphics-) | Prüft, ob dieses [Region](../../com.aspose.drawing/region) auf der angegebenen Zeichenfläche ein unendliches Inneres hat. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Prüft, ob der angegebene Punkt innerhalb dieses [Region](../../com.aspose.drawing/region) liegt. |
| [isVisible(PointF point)](#isVisible-com.aspose.drawing.PointF-) | Prüft, ob die angegebene [PointF](../../com.aspose.drawing/pointf)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.drawing.Graphics-) | Prüft, ob der angegebene Punkt innerhalb dieses [Region](../../com.aspose.drawing/region) liegt, wenn er mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics) gezeichnet wird. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-) | Prüft, ob die angegebene [PointF](../../com.aspose.drawing/pointf)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt, wenn sie mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics) gezeichnet wird. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](../../com.aspose.drawing/region) liegt. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.drawing.RectangleF-) | Prüft, ob irgendein Teil der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.drawing.Graphics-) | Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](../../com.aspose.drawing/region) liegt, wenn es mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics) gezeichnet wird. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-) | Prüft, ob irgendein Teil der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt, wenn sie mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics) gezeichnet wird. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.drawing.Graphics-) | Prüft, ob der angegebene Punkt innerhalb dieses [Region](../../com.aspose.drawing/region)-Objekts liegt, wenn er mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics)-Objekt gezeichnet wird. |
| [isVisible(Point point)](#isVisible-com.aspose.drawing.Point-) | Prüft, ob die angegebene [Point](../../com.aspose.drawing/point)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-) | Prüft, ob die angegebene [Point](../../com.aspose.drawing/point)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt, wenn sie mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics) gezeichnet wird. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](../../com.aspose.drawing/region) liegt. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.drawing.Rectangle-) | Prüft, ob irgendein Teil der angegebenen [Rectangle](../../com.aspose.drawing/rectangle)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.drawing.Graphics-) | Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](../../com.aspose.drawing/region) liegt, wenn es mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics) gezeichnet wird. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-) | Prüft, ob irgendein Teil der angegebenen [Rectangle](../../com.aspose.drawing/rectangle)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt, wenn sie mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics) gezeichnet wird. |
### Region() {#Region--}
```
public Region()
```


Initialisiert eine neue Instanz der Klasse [Region](../../com.aspose.drawing/region).

### Region(RectangleF rect) {#Region-com.aspose.drawing.RectangleF-}
```
public Region(RectangleF rect)
```


Initialisiert eine neue Instanz der Klasse [Region](../../com.aspose.drawing/region) aus der angegebenen Struktur [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Eine [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur, die das Innere des neuen [Region](../../com.aspose.drawing/region) definiert. |

### Region(Rectangle rect) {#Region-com.aspose.drawing.Rectangle-}
```
public Region(Rectangle rect)
```


Initialisiert eine neue Instanz der Klasse [Region](../../com.aspose.drawing/region) aus der angegebenen Struktur [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Eine [Rectangle](../../com.aspose.drawing/rectangle)-Struktur, die das Innere des neuen [Region](../../com.aspose.drawing/region) definiert. |

### Region(GraphicsPath path) {#Region-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Initialisiert eine neue Instanz der Klasse [Region](../../com.aspose.drawing/region) mit dem angegebenen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ein [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), der das neue [Region](../../com.aspose.drawing/region) definiert. |

### Region(RegionData rgnData) {#Region-com.aspose.drawing.drawing2d.RegionData-}
```
public Region(RegionData rgnData)
```


Initialisiert eine neue Instanz der Klasse [Region](../../com.aspose.drawing/region) aus den angegebenen Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgnData | [RegionData](../../com.aspose.drawing.drawing2d/regiondata) | Ein [RegionData](../../com.aspose.drawing.drawing2d/regiondata), der das Innere des neuen [Region](../../com.aspose.drawing/region) definiert. |

### dispose() {#dispose--}
```
public void dispose()
```


Gibt alle von dieser [Region](../../com.aspose.drawing/region) verwendeten Ressourcen frei.

### equals(Region region, Graphics g) {#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-}
```
public boolean equals(Region region, Graphics g)
```


Prüft, ob die angegebene [Region](../../com.aspose.drawing/region) auf der angegebenen Zeichenfläche identisch mit dieser [Region](../../com.aspose.drawing/region) ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Das zu testende [Region](../../com.aspose.drawing/region). |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ein [Graphics](../../com.aspose.drawing/graphics), das eine Zeichenfläche darstellt. |

**Returns:**
boolean – true, wenn das Innere der Region identisch mit dem Inneren dieser Region ist, wenn die mit dem Parameter `g` verbundene Transformation angewendet wird; andernfalls false.
### deepClone() {#deepClone--}
```
public Region deepClone()
```


Erstellt eine exakte Kopie dieser [Region](../../com.aspose.drawing/region).

**Returns:**
[Region](../../com.aspose.drawing/region) - The [Region](../../com.aspose.drawing/region) that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Initialisiert dieses [Region](../../com.aspose.drawing/region)-Objekt mit einem unendlichen Innenbereich.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Initialisiert diese [Region](../../com.aspose.drawing/region) mit einem leeren Innenbereich.

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public void intersect(RectangleF rect)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Schnittmenge mit der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Die [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur zum Schneiden mit dieser [Region](../../com.aspose.drawing/region). |

### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public void intersect(Rectangle rect)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Schnittmenge mit der angegebenen [Rectangle](../../com.aspose.drawing/rectangle)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Die [Rectangle](../../com.aspose.drawing/rectangle)-Struktur zum Schneiden mit dieser [Region](../../com.aspose.drawing/region). |

### intersect(GraphicsPath path) {#intersect-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Schnittmenge mit dem angegebenen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Der [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) zum Schneiden mit dieser [Region](../../com.aspose.drawing/region). |

### intersect(Region region) {#intersect-com.aspose.drawing.Region-}
```
public void intersect(Region region)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Schnittmenge mit der angegebenen [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Die [Region](../../com.aspose.drawing/region) zum Schneiden mit dieser [Region](../../com.aspose.drawing/region). |

### union(RectangleF rect) {#union-com.aspose.drawing.RectangleF-}
```
public void union(RectangleF rect)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung mit der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Die [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur zur Vereinigung mit dieser [Region](../../com.aspose.drawing/region). |

--------------------

Vereinigung lässt unendliche Region unendlich bleiben. |

### union(Rectangle rect) {#union-com.aspose.drawing.Rectangle-}
```
public void union(Rectangle rect)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung mit der angegebenen [Rectangle](../../com.aspose.drawing/rectangle)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | rect | [Rectangle](../../com.aspose.drawing/rectangle) | Die [Rectangle](../../com.aspose.drawing/rectangle)-Struktur zur Vereinigung mit dieser [Region](../../com.aspose.drawing/region). |

--------------------

Vereinigung lässt unendliche Region unendlich bleiben. |

### union(GraphicsPath path) {#union-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung mit dem angegebenen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Der [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) zur Vereinigung mit dieser [Region](../../com.aspose.drawing/region). |

--------------------

Vereinigung lässt unendliche Region unendlich bleiben. |

### union(Region region) {#union-com.aspose.drawing.Region-}
```
public void union(Region region)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung mit der angegebenen [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | region | [Region](../../com.aspose.drawing/region) | Die [Region](../../com.aspose.drawing/region) zur Vereinigung mit dieser [Region](../../com.aspose.drawing/region). |

--------------------

Vereinigung lässt unendliche Region unendlich bleiben. |

### getRegionData() {#getRegionData--}
```
public RegionData getRegionData()
```


Gibt ein [RegionData](../../com.aspose.drawing.drawing2d/regiondata) zurück, das die Informationen darstellt, die diese [Region](../../com.aspose.drawing/region) beschreiben.

**Returns:**
[RegionData](../../com.aspose.drawing.drawing2d/regiondata) - A [RegionData](../../com.aspose.drawing.drawing2d/regiondata) that represents the information that describes this [Region](../../com.aspose.drawing/region).
### xor(RectangleF rect) {#xor-com.aspose.drawing.RectangleF-}
```
public void xor(RectangleF rect)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung minus die Schnittmenge mit der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Die [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur zu `M:Region.Xor(Drawing2D.GraphicsPath)` mit dieser [Region](../../com.aspose.drawing/region). |

### xor(Rectangle rect) {#xor-com.aspose.drawing.Rectangle-}
```
public void xor(Rectangle rect)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung minus die Schnittmenge mit der angegebenen [Rectangle](../../com.aspose.drawing/rectangle)-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Die [Rectangle](../../com.aspose.drawing/rectangle)-Struktur zu `M:Region.Xor(Rectangle)` mit dieser [Region](../../com.aspose.drawing/region). |

### xor(GraphicsPath path) {#xor-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung minus die Schnittmenge mit dem angegebenen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Der [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) zu `M:Region.Xor(GraphicsPath)` mit dieser [Region](../../com.aspose.drawing/region). |

### xor(Region region) {#xor-com.aspose.drawing.Region-}
```
public void xor(Region region)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region) auf die Vereinigung minus die Schnittmenge mit der angegebenen [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Die [Region](../../com.aspose.drawing/region) zu `M:Region.Xor(Region)` mit dieser [Region](../../com.aspose.drawing/region). |

### exclude(RectangleF rect) {#exclude-com.aspose.drawing.RectangleF-}
```
public void exclude(RectangleF rect)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region), sodass sie nur den Teil ihres Innenbereichs enthält, der nicht mit der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Die [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur zum Ausschließen aus dieser [Region](../../com.aspose.drawing/region). |

### exclude(Rectangle rect) {#exclude-com.aspose.drawing.Rectangle-}
```
public void exclude(Rectangle rect)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region), sodass sie nur den Teil ihres Innenbereichs enthält, der nicht mit der angegebenen [Rectangle](../../com.aspose.drawing/rectangle)-Struktur schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Die [Rectangle](../../com.aspose.drawing/rectangle)-Struktur zum Ausschließen aus dieser [Region](../../com.aspose.drawing/region). |

### exclude(GraphicsPath path) {#exclude-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region), sodass sie nur den Teil ihres Innenbereichs enthält, der nicht mit dem angegebenen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Der [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) zum Ausschließen aus dieser [Region](../../com.aspose.drawing/region). |

### exclude(Region region) {#exclude-com.aspose.drawing.Region-}
```
public void exclude(Region region)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region), sodass sie nur den Teil ihres Innenbereichs enthält, der nicht mit der angegebenen [Region](../../com.aspose.drawing/region) schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Die [Region](../../com.aspose.drawing/region) zum Ausschließen aus dieser [Region](../../com.aspose.drawing/region). |

### complement(RectangleF rect) {#complement-com.aspose.drawing.RectangleF-}
```
public void complement(RectangleF rect)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region), sodass sie den Teil der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur enthält, der nicht mit dieser [Region](../../com.aspose.drawing/region) schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Die [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur zur Ergänzung dieser [Region](../../com.aspose.drawing/region). |

### complement(Rectangle rect) {#complement-com.aspose.drawing.Rectangle-}
```
public void complement(Rectangle rect)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region), sodass sie den Teil der angegebenen [Rectangle](../../com.aspose.drawing/rectangle)-Struktur enthält, der nicht mit dieser [Region](../../com.aspose.drawing/region) schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Die [Rectangle](../../com.aspose.drawing/rectangle)-Struktur zur Ergänzung dieser [Region](../../com.aspose.drawing/region). |

### complement(GraphicsPath path) {#complement-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Aktualisiert diese [Region](../../com.aspose.drawing/region), sodass sie den Teil des angegebenen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) enthält, der nicht mit dieser [Region](../../com.aspose.drawing/region) schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Der [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) zur Ergänzung dieser [Region](../../com.aspose.drawing/region). |

### complement(Region region) {#complement-com.aspose.drawing.Region-}
```
public void complement(Region region)
```


Aktualisiert dieses [Region](../../com.aspose.drawing/region), sodass es den Teil des angegebenen [Region](../../com.aspose.drawing/region) enthält, der nicht mit diesem [Region](../../com.aspose.drawing/region) überschneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Das [Region](../../com.aspose.drawing/region)-Objekt zur Ergänzung dieses [Region](../../com.aspose.drawing/region)-Objekts. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Verschiebt die Koordinaten dieses [Region](../../com.aspose.drawing/region) um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Betrag, um den diese [Region](../../com.aspose.drawing/region) horizontal verschoben wird. |
| dy | float | Der Betrag, um den diese [Region](../../com.aspose.drawing/region) vertikal verschoben wird. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Verschiebt die Koordinaten dieses [Region](../../com.aspose.drawing/region) um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | int | Der Betrag, um diesen [Region](../../com.aspose.drawing/region) horizontal zu verschieben |
| dy | int | Der Betrag, um den diese [Region](../../com.aspose.drawing/region) vertikal verschoben wird. |

### transform(Matrix matrix) {#transform-com.aspose.drawing.drawing2d.Matrix-}
```
public void transform(Matrix matrix)
```


Transformiert dieses [Region](../../com.aspose.drawing/region) mit der angegebenen [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Die [Matrix](../../com.aspose.drawing.drawing2d/matrix), mit der dieses [Region](../../com.aspose.drawing/region) transformiert wird. |

### getBounds(Graphics g) {#getBounds-com.aspose.drawing.Graphics-}
```
public RectangleF getBounds(Graphics g)
```


Gibt eine [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur zurück, die ein Rechteck darstellt, das dieses [Region](../../com.aspose.drawing/region) auf der Zeichenfläche eines [Graphics](../../com.aspose.drawing/graphics)-Objekts begrenzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Die [Graphics](../../com.aspose.drawing/graphics), auf der dieses [Region](../../com.aspose.drawing/region) gezeichnet wird. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents the bounding rectangle for this [Region](../../com.aspose.drawing/region) on the specified drawing surface.
### getRegionScans(Matrix matrix) {#getRegionScans-com.aspose.drawing.drawing2d.Matrix-}
```
public RectangleF[] getRegionScans(Matrix matrix)
```


Gibt ein Array von [RectangleF](../../com.aspose.drawing/rectanglef)-Strukturen zurück, die dieses [Region](../../com.aspose.drawing/region) nach Anwendung der angegebenen Matrixtransformation annähern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Eine [Matrix](../../com.aspose.drawing.drawing2d/matrix), die eine geometrische Transformation darstellt, die auf die Region angewendet werden soll. |

**Returns:**
com.aspose.drawing.RectangleF[] - Ein Array von [RectangleF](../../com.aspose.drawing/rectanglef)-Strukturen, die dieses [Region](../../com.aspose.drawing/region) nach Anwendung der angegebenen Matrixtransformation annähern.
### isEmpty(Graphics g) {#isEmpty-com.aspose.drawing.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Prüft, ob dieses [Region](../../com.aspose.drawing/region) auf der angegebenen Zeichenfläche ein leeres Inneres hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ein [Graphics](../../com.aspose.drawing/graphics), das eine Zeichenfläche darstellt. |

**Returns:**
boolean - true, wenn das Innere dieses [Region](../../com.aspose.drawing/region) leer ist, wenn die mit `g` verbundene Transformation angewendet wird; andernfalls false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.drawing.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Prüft, ob dieses [Region](../../com.aspose.drawing/region) auf der angegebenen Zeichenfläche ein unendliches Inneres hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ein [Graphics](../../com.aspose.drawing/graphics), das eine Zeichenfläche darstellt. |

**Returns:**
boolean - true, wenn das Innere dieses [Region](../../com.aspose.drawing/region) unendlich ist, wenn die mit `g` verbundene Transformation angewendet wird; andernfalls false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Prüft, ob der angegebene Punkt innerhalb dieses [Region](../../com.aspose.drawing/region) liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y‑Koordinate des zu testenden Punktes. |

**Returns:**
boolean - true, wenn der angegebene Punkt innerhalb dieses [Region](../../com.aspose.drawing/region) liegt; andernfalls false.
### isVisible(PointF point) {#isVisible-com.aspose.drawing.PointF-}
```
public boolean isVisible(PointF point)
```


Prüft, ob die angegebene [PointF](../../com.aspose.drawing/pointf)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | Die zu testende [PointF](../../com.aspose.drawing/pointf)-Struktur. |

**Returns:**
boolean - true, wenn `point` innerhalb dieses [Region](../../com.aspose.drawing/region) liegt; andernfalls false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Prüft, ob der angegebene Punkt innerhalb dieses [Region](../../com.aspose.drawing/region) liegt, wenn er mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics) gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y‑Koordinate des zu testenden Punktes. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ein [Graphics](../../com.aspose.drawing/graphics), das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - true, wenn der angegebene Punkt innerhalb dieses [Region](../../com.aspose.drawing/region) liegt; andernfalls false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Prüft, ob die angegebene [PointF](../../com.aspose.drawing/pointf)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt, wenn sie mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics) gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | Die zu testende [PointF](../../com.aspose.drawing/pointf)-Struktur. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ein [Graphics](../../com.aspose.drawing/graphics), das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - true, wenn `point` innerhalb dieses [Region](../../com.aspose.drawing/region) liegt; andernfalls false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](../../com.aspose.drawing/region) liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | float | Die y-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| Breite | float | Die Breite des zu testenden Rechtecks. |
| Höhe | float | Die Höhe des zu testenden Rechtecks. |

**Returns:**
boolean - true, wenn irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](../../com.aspose.drawing/region)-Objekts liegt; andernfalls false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.drawing.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Prüft, ob irgendein Teil der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Die zu testende [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur. |

**Returns:**
boolean - true, wenn irgendein Teil von `rect` innerhalb dieses [Region](../../com.aspose.drawing/region) liegt; andernfalls false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](../../com.aspose.drawing/region) liegt, wenn es mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics) gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | float | Die y-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| Breite | float | Die Breite des zu testenden Rechtecks. |
| Höhe | float | Die Höhe des zu testenden Rechtecks. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ein [Graphics](../../com.aspose.drawing/graphics), das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - true, wenn irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](../../com.aspose.drawing/region) liegt; andernfalls false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Prüft, ob irgendein Teil der angegebenen [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt, wenn sie mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics) gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Die zu testende [RectangleF](../../com.aspose.drawing/rectanglef)-Struktur. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ein [Graphics](../../com.aspose.drawing/graphics), das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - true, wenn `rect` innerhalb dieses [Region](../../com.aspose.drawing/region) liegt; andernfalls false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Prüft, ob der angegebene Punkt innerhalb dieses [Region](../../com.aspose.drawing/region)-Objekts liegt, wenn er mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics)-Objekt gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y‑Koordinate des zu testenden Punktes. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ein [Graphics](../../com.aspose.drawing/graphics), das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - true, wenn der angegebene Punkt innerhalb dieses [Region](../../com.aspose.drawing/region) liegt; andernfalls false.
### isVisible(Point point) {#isVisible-com.aspose.drawing.Point-}
```
public boolean isVisible(Point point)
```


Prüft, ob die angegebene [Point](../../com.aspose.drawing/point)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | Die zu testende [Point](../../com.aspose.drawing/point)-Struktur. |

**Returns:**
boolean - true, wenn `point` innerhalb dieses [Region](../../com.aspose.drawing/region) liegt; andernfalls false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Prüft, ob die angegebene [Point](../../com.aspose.drawing/point)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt, wenn sie mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics) gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | Die zu testende [Point](../../com.aspose.drawing/point)-Struktur. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ein [Graphics](../../com.aspose.drawing/graphics), das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - true, wenn `point` innerhalb dieses [Region](../../com.aspose.drawing/region) liegt; andernfalls false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](../../com.aspose.drawing/region) liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| Breite | int | Die Breite des zu testenden Rechtecks. |
| Höhe | int | Die Höhe des zu testenden Rechtecks. |

**Returns:**
boolean - true, wenn irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](../../com.aspose.drawing/region) liegt; andernfalls false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.drawing.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Prüft, ob irgendein Teil der angegebenen [Rectangle](../../com.aspose.drawing/rectangle)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Die zu testende [Rectangle](../../com.aspose.drawing/rectangle)-Struktur. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn irgendein Teil von `rect` innerhalb dieses [Region](../../com.aspose.drawing/region) liegt; andernfalls false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](../../com.aspose.drawing/region) liegt, wenn es mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics) gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| Breite | int | Die Breite des zu testenden Rechtecks. |
| Höhe | int | Die Höhe des zu testenden Rechtecks. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ein [Graphics](../../com.aspose.drawing/graphics), das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - true, wenn irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](../../com.aspose.drawing/region) liegt; andernfalls false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Prüft, ob irgendein Teil der angegebenen [Rectangle](../../com.aspose.drawing/rectangle)-Struktur innerhalb dieses [Region](../../com.aspose.drawing/region) liegt, wenn sie mit dem angegebenen [Graphics](../../com.aspose.drawing/graphics) gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Die zu testende [Rectangle](../../com.aspose.drawing/rectangle)-Struktur. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ein [Graphics](../../com.aspose.drawing/graphics), das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - true, wenn irgendein Teil des `rect` innerhalb dieses [Region](../../com.aspose.drawing/region) liegt; andernfalls false.
