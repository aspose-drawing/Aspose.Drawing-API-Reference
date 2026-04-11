---
title: Region
second_title: Aspose.Drawing för Java API‑referens
description: Beskriver insidan av en grafisk form bestående av rektanglar och banor.
type: docs
weight: 40
url: /sv/java/com.aspose.drawing/region/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Region implements System.IDisposable
```

Beskriver insidan av en grafisk form bestående av rektanglar och banor. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Region()](#Region--) | Initierar en ny instans av klassen [Region](../../com.aspose.drawing/region). |
| [Region(RectangleF rect)](#Region-com.aspose.drawing.RectangleF-) | Initierar en ny instans av klassen [Region](../../com.aspose.drawing/region) från den angivna strukturen [RectangleF](../../com.aspose.drawing/rectanglef). |
| [Region(Rectangle rect)](#Region-com.aspose.drawing.Rectangle-) | Initierar en ny instans av klassen [Region](../../com.aspose.drawing/region) från den angivna strukturen [Rectangle](../../com.aspose.drawing/rectangle). |
| [Region(GraphicsPath path)](#Region-com.aspose.drawing.drawing2d.GraphicsPath-) | Initierar en ny instans av klassen [Region](../../com.aspose.drawing/region) med den angivna [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [Region(RegionData rgnData)](#Region-com.aspose.drawing.drawing2d.RegionData-) | Initierar en ny instans av klassen [Region](../../com.aspose.drawing/region) från de angivna data. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [dispose()](#dispose--) | Frigör alla resurser som används av denna [Region](../../com.aspose.drawing/region). |
| [equals(Region region, Graphics g)](#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-) | Testar om den angivna [Region](../../com.aspose.drawing/region) är identisk med denna [Region](../../com.aspose.drawing/region) på den angivna ritytan. |
| [deepClone()](#deepClone--) | Skapar en exakt kopia av denna [Region](../../com.aspose.drawing/region). |
| [makeInfinite()](#makeInfinite--) | Initierar detta [Region](../../com.aspose.drawing/region)-objekt till ett oändligt inre. |
| [makeEmpty()](#makeEmpty--) | Initierar detta [Region](../../com.aspose.drawing/region) till ett tomt inre. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) till skärningsmängden mellan sig själv och den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen. |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) till skärningsmängden mellan sig själv och den angivna [Rectangle](../../com.aspose.drawing/rectangle)-strukturen. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.drawing.drawing2d.GraphicsPath-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) till skärningsmängden mellan sig själv och den angivna [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-strukturen. |
| [intersect(Region region)](#intersect-com.aspose.drawing.Region-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) till skärningsmängden mellan sig själv och den angivna [Region](../../com.aspose.drawing/region)-strukturen. |
| [union(RectangleF rect)](#union-com.aspose.drawing.RectangleF-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen av sig själv och den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen. |
| [union(Rectangle rect)](#union-com.aspose.drawing.Rectangle-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen av sig själv och den angivna [Rectangle](../../com.aspose.drawing/rectangle)-strukturen. |
| [union(GraphicsPath path)](#union-com.aspose.drawing.drawing2d.GraphicsPath-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen av sig själv och den angivna [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-strukturen. |
| [union(Region region)](#union-com.aspose.drawing.Region-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen av sig själv och den angivna [Region](../../com.aspose.drawing/region)-strukturen. |
| [getRegionData()](#getRegionData--) | Returnerar en [RegionData](../../com.aspose.drawing.drawing2d/regiondata) som representerar informationen som beskriver detta [Region](../../com.aspose.drawing/region). |
| [xor(RectangleF rect)](#xor-com.aspose.drawing.RectangleF-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen minus skärningsmängden mellan sig själv och den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen. |
| [xor(Rectangle rect)](#xor-com.aspose.drawing.Rectangle-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen minus skärningsmängden mellan sig själv och den angivna [Rectangle](../../com.aspose.drawing/rectangle)-strukturen. |
| [xor(GraphicsPath path)](#xor-com.aspose.drawing.drawing2d.GraphicsPath-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen minus skärningsmängden mellan sig själv och den angivna [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-strukturen. |
| [xor(Region region)](#xor-com.aspose.drawing.Region-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen minus skärningsmängden mellan sig själv och den angivna [Region](../../com.aspose.drawing/region)-strukturen. |
| [exclude(RectangleF rect)](#exclude-com.aspose.drawing.RectangleF-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det endast innehåller den del av dess inre som inte skär med den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen. |
| [exclude(Rectangle rect)](#exclude-com.aspose.drawing.Rectangle-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det endast innehåller den del av dess inre som inte skär med den angivna [Rectangle](../../com.aspose.drawing/rectangle)-strukturen. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.drawing.drawing2d.GraphicsPath-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det endast innehåller den del av dess inre som inte skär med den angivna [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-strukturen. |
| [exclude(Region region)](#exclude-com.aspose.drawing.Region-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det endast innehåller den del av dess inre som inte skär med den angivna [Region](../../com.aspose.drawing/region)-strukturen. |
| [complement(RectangleF rect)](#complement-com.aspose.drawing.RectangleF-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det innehåller den del av den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen som inte skär med detta [Region](../../com.aspose.drawing/region). |
| [complement(Rectangle rect)](#complement-com.aspose.drawing.Rectangle-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det innehåller den del av den angivna [Rectangle](../../com.aspose.drawing/rectangle)-strukturen som inte skär med detta [Region](../../com.aspose.drawing/region). |
| [complement(GraphicsPath path)](#complement-com.aspose.drawing.drawing2d.GraphicsPath-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det innehåller den del av den angivna [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-strukturen som inte skär med detta [Region](../../com.aspose.drawing/region). |
| [complement(Region region)](#complement-com.aspose.drawing.Region-) | Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det innehåller den del av den angivna [Region](../../com.aspose.drawing/region) som inte skär sig med detta [Region](../../com.aspose.drawing/region). |
| [translate(float dx, float dy)](#translate-float-float-) | Förskjuter koordinaterna för detta [Region](../../com.aspose.drawing/region) med det angivna beloppet. |
| [translate(int dx, int dy)](#translate-int-int-) | Förskjuter koordinaterna för detta [Region](../../com.aspose.drawing/region) med det angivna beloppet. |
| [transform(Matrix matrix)](#transform-com.aspose.drawing.drawing2d.Matrix-) | Transformerar detta [Region](../../com.aspose.drawing/region) med den angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [getBounds(Graphics g)](#getBounds-com.aspose.drawing.Graphics-) | Hämtar en [RectangleF](../../com.aspose.drawing/rectanglef)-struktur som representerar en rektangel som avgränsar detta [Region](../../com.aspose.drawing/region) på ritningsytan för ett [Graphics](../../com.aspose.drawing/graphics)-objekt. |
| [getRegionScans(Matrix matrix)](#getRegionScans-com.aspose.drawing.drawing2d.Matrix-) | Returnerar en array av [RectangleF](../../com.aspose.drawing/rectanglef)-strukturer som approximerar detta [Region](../../com.aspose.drawing/region) efter att den angivna matrisomvandlingen har tillämpats. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.drawing.Graphics-) | Testar om detta [Region](../../com.aspose.drawing/region) har ett tomt inre på den angivna ritningsytan. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.drawing.Graphics-) | Testar om detta [Region](../../com.aspose.drawing/region) har ett oändligt inre på den angivna ritningsytan. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Testar om den angivna punkten finns inom detta [Region](../../com.aspose.drawing/region). |
| [isVisible(PointF point)](#isVisible-com.aspose.drawing.PointF-) | Testar om den angivna [PointF](../../com.aspose.drawing/pointf)-strukturen finns inom detta [Region](../../com.aspose.drawing/region). |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.drawing.Graphics-) | Testar om den angivna punkten finns inom detta [Region](../../com.aspose.drawing/region) när den ritas med den angivna [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-) | Testar om den angivna [PointF](../../com.aspose.drawing/pointf)-strukturen finns inom detta [Region](../../com.aspose.drawing/region) när den ritas med den angivna [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Testar om någon del av den angivna rektangeln finns inom detta [Region](../../com.aspose.drawing/region). |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.drawing.RectangleF-) | Testar om någon del av den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen finns inom detta [Region](../../com.aspose.drawing/region). |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.drawing.Graphics-) | Testar om någon del av den angivna rektangeln finns inom detta [Region](../../com.aspose.drawing/region) när den ritas med den angivna [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-) | Testar om någon del av den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen finns inom detta [Region](../../com.aspose.drawing/region) när den ritas med den angivna [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.drawing.Graphics-) | Testar om den angivna punkten finns inom detta [Region](../../com.aspose.drawing/region)-objekt när det ritas med det angivna [Graphics](../../com.aspose.drawing/graphics)-objektet. |
| [isVisible(Point point)](#isVisible-com.aspose.drawing.Point-) | Testar om den angivna [Point](../../com.aspose.drawing/point)-strukturen finns inom detta [Region](../../com.aspose.drawing/region). |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-) | Testar om den angivna [Point](../../com.aspose.drawing/point)-strukturen finns inom detta [Region](../../com.aspose.drawing/region) när den ritas med den angivna [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Testar om någon del av den angivna rektangeln finns inom detta [Region](../../com.aspose.drawing/region). |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.drawing.Rectangle-) | Testar om någon del av den angivna [Rectangle](../../com.aspose.drawing/rectangle)-strukturen finns inom detta [Region](../../com.aspose.drawing/region). |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.drawing.Graphics-) | Testar om någon del av den angivna rektangeln finns inom detta [Region](../../com.aspose.drawing/region) när den ritas med den angivna [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-) | Testar om någon del av den angivna [Rectangle](../../com.aspose.drawing/rectangle)-strukturen finns inom detta [Region](../../com.aspose.drawing/region) när den ritas med den angivna [Graphics](../../com.aspose.drawing/graphics). |
### Region() {#Region--}
```
public Region()
```


Initierar en ny instans av klassen [Region](../../com.aspose.drawing/region).

### Region(RectangleF rect) {#Region-com.aspose.drawing.RectangleF-}
```
public Region(RectangleF rect)
```


Initierar en ny instans av klassen [Region](../../com.aspose.drawing/region) från den angivna strukturen [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | En [RectangleF](../../com.aspose.drawing/rectanglef)-struktur som definierar interiören för den nya [Region](../../com.aspose.drawing/region). |

### Region(Rectangle rect) {#Region-com.aspose.drawing.Rectangle-}
```
public Region(Rectangle rect)
```


Initierar en ny instans av klassen [Region](../../com.aspose.drawing/region) från den angivna strukturen [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | En [Rectangle](../../com.aspose.drawing/rectangle)-struktur som definierar interiören för den nya [Region](../../com.aspose.drawing/region). |

### Region(GraphicsPath path) {#Region-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Initierar en ny instans av klassen [Region](../../com.aspose.drawing/region) med den angivna [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | En [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) som definierar den nya [Region](../../com.aspose.drawing/region). |

### Region(RegionData rgnData) {#Region-com.aspose.drawing.drawing2d.RegionData-}
```
public Region(RegionData rgnData)
```


Initierar en ny instans av klassen [Region](../../com.aspose.drawing/region) från de angivna data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgnData | [RegionData](../../com.aspose.drawing.drawing2d/regiondata) | En [RegionData](../../com.aspose.drawing.drawing2d/regiondata) som definierar interiören för den nya [Region](../../com.aspose.drawing/region). |

### dispose() {#dispose--}
```
public void dispose()
```


Frigör alla resurser som används av denna [Region](../../com.aspose.drawing/region).

### equals(Region region, Graphics g) {#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-}
```
public boolean equals(Region region, Graphics g)
```


Testar om den angivna [Region](../../com.aspose.drawing/region) är identisk med denna [Region](../../com.aspose.drawing/region) på den angivna ritytan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Den [Region](../../com.aspose.drawing/region) som ska testas. |
| g | [Graphics](../../com.aspose.drawing/graphics) | En [Graphics](../../com.aspose.drawing/graphics) som representerar en ritningsyta. |

**Returns:**
boolean - sant om regionens inre är identiskt med detta regions inre när transformationen som är associerad med parametern `g` tillämpas; annars falskt.
### deepClone() {#deepClone--}
```
public Region deepClone()
```


Skapar en exakt kopia av denna [Region](../../com.aspose.drawing/region).

**Returns:**
[Region](../../com.aspose.drawing/region) - The [Region](../../com.aspose.drawing/region) that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Initierar detta [Region](../../com.aspose.drawing/region)-objekt till ett oändligt inre.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Initierar detta [Region](../../com.aspose.drawing/region) till ett tomt inre.

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public void intersect(RectangleF rect)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) till skärningsmängden mellan sig själv och den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen för att skära av detta [Region](../../com.aspose.drawing/region). |

### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public void intersect(Rectangle rect)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) till skärningsmängden mellan sig själv och den angivna [Rectangle](../../com.aspose.drawing/rectangle)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Den [Rectangle](../../com.aspose.drawing/rectangle)-strukturen för att skära av detta [Region](../../com.aspose.drawing/region). |

### intersect(GraphicsPath path) {#intersect-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) till skärningsmängden mellan sig själv och den angivna [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Den [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-strukturen för att skära av detta [Region](../../com.aspose.drawing/region). |

### intersect(Region region) {#intersect-com.aspose.drawing.Region-}
```
public void intersect(Region region)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) till skärningsmängden mellan sig själv och den angivna [Region](../../com.aspose.drawing/region)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Det [Region](../../com.aspose.drawing/region)-objektet för att skära av detta [Region](../../com.aspose.drawing/region). |

### union(RectangleF rect) {#union-com.aspose.drawing.RectangleF-}
```
public void union(RectangleF rect)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen av sig själv och den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen för att förena med detta [Region](../../com.aspose.drawing/region). |

--------------------

Förening lämnar oändlig region som oändlig. |

### union(Rectangle rect) {#union-com.aspose.drawing.Rectangle-}
```
public void union(Rectangle rect)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen av sig själv och den angivna [Rectangle](../../com.aspose.drawing/rectangle)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | rect | [Rectangle](../../com.aspose.drawing/rectangle) | Den [Rectangle](../../com.aspose.drawing/rectangle)-strukturen för att förena med detta [Region](../../com.aspose.drawing/region). |

--------------------

Förening lämnar oändlig region som oändlig. |

### union(GraphicsPath path) {#union-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen av sig själv och den angivna [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Den [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-strukturen för att förena med detta [Region](../../com.aspose.drawing/region). |

--------------------

Förening lämnar oändlig region som oändlig. |

### union(Region region) {#union-com.aspose.drawing.Region-}
```
public void union(Region region)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen av sig själv och den angivna [Region](../../com.aspose.drawing/region)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | region | [Region](../../com.aspose.drawing/region) | Det [Region](../../com.aspose.drawing/region)-objektet för att förena med detta [Region](../../com.aspose.drawing/region). |

--------------------

Förening lämnar oändlig region som oändlig. |

### getRegionData() {#getRegionData--}
```
public RegionData getRegionData()
```


Returnerar en [RegionData](../../com.aspose.drawing.drawing2d/regiondata) som representerar informationen som beskriver detta [Region](../../com.aspose.drawing/region).

**Returns:**
[RegionData](../../com.aspose.drawing.drawing2d/regiondata) - A [RegionData](../../com.aspose.drawing.drawing2d/regiondata) that represents the information that describes this [Region](../../com.aspose.drawing/region).
### xor(RectangleF rect) {#xor-com.aspose.drawing.RectangleF-}
```
public void xor(RectangleF rect)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen minus skärningsmängden mellan sig själv och den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen för att `M:Region.Xor(Drawing2D.GraphicsPath)` med detta [Region](../../com.aspose.drawing/region). |

### xor(Rectangle rect) {#xor-com.aspose.drawing.Rectangle-}
```
public void xor(Rectangle rect)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen minus skärningsmängden mellan sig själv och den angivna [Rectangle](../../com.aspose.drawing/rectangle)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Den [Rectangle](../../com.aspose.drawing/rectangle)-strukturen för att `M:Region.Xor(Rectangle)` med detta [Region](../../com.aspose.drawing/region). |

### xor(GraphicsPath path) {#xor-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen minus skärningsmängden mellan sig själv och den angivna [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Den [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-strukturen för att `M:Region.Xor(GraphicsPath)` med detta [Region](../../com.aspose.drawing/region). |

### xor(Region region) {#xor-com.aspose.drawing.Region-}
```
public void xor(Region region)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) till unionen minus skärningsmängden mellan sig själv och den angivna [Region](../../com.aspose.drawing/region)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Det [Region](../../com.aspose.drawing/region)-objektet för att `M:Region.Xor(Region)` med detta [Region](../../com.aspose.drawing/region). |

### exclude(RectangleF rect) {#exclude-com.aspose.drawing.RectangleF-}
```
public void exclude(RectangleF rect)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det endast innehåller den del av dess inre som inte skär med den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen för att utesluta från detta [Region](../../com.aspose.drawing/region). |

### exclude(Rectangle rect) {#exclude-com.aspose.drawing.Rectangle-}
```
public void exclude(Rectangle rect)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det endast innehåller den del av dess inre som inte skär med den angivna [Rectangle](../../com.aspose.drawing/rectangle)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Den [Rectangle](../../com.aspose.drawing/rectangle)-strukturen för att utesluta från detta [Region](../../com.aspose.drawing/region). |

### exclude(GraphicsPath path) {#exclude-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det endast innehåller den del av dess inre som inte skär med den angivna [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Den [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-strukturen för att utesluta från detta [Region](../../com.aspose.drawing/region). |

### exclude(Region region) {#exclude-com.aspose.drawing.Region-}
```
public void exclude(Region region)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det endast innehåller den del av dess inre som inte skär med den angivna [Region](../../com.aspose.drawing/region)-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Det [Region](../../com.aspose.drawing/region)-objektet för att utesluta från detta [Region](../../com.aspose.drawing/region). |

### complement(RectangleF rect) {#complement-com.aspose.drawing.RectangleF-}
```
public void complement(RectangleF rect)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det innehåller den del av den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen som inte skär med detta [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen för att komplementera detta [Region](../../com.aspose.drawing/region). |

### complement(Rectangle rect) {#complement-com.aspose.drawing.Rectangle-}
```
public void complement(Rectangle rect)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det innehåller den del av den angivna [Rectangle](../../com.aspose.drawing/rectangle)-strukturen som inte skär med detta [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Den [Rectangle](../../com.aspose.drawing/rectangle)-strukturen för att komplementera detta [Region](../../com.aspose.drawing/region). |

### complement(GraphicsPath path) {#complement-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det innehåller den del av den angivna [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-strukturen som inte skär med detta [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Den [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-strukturen för att komplementera detta [Region](../../com.aspose.drawing/region). |

### complement(Region region) {#complement-com.aspose.drawing.Region-}
```
public void complement(Region region)
```


Uppdaterar detta [Region](../../com.aspose.drawing/region) så att det innehåller den del av den angivna [Region](../../com.aspose.drawing/region) som inte skär sig med detta [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Det [Region](../../com.aspose.drawing/region)-objektet för att komplementera detta [Region](../../com.aspose.drawing/region)-objekt. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Förskjuter koordinaterna för detta [Region](../../com.aspose.drawing/region) med det angivna beloppet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | float | Mängden för att förskjuta detta [Region](../../com.aspose.drawing/region) horisontellt. |
| dy | float | Mängden för att förskjuta detta [Region](../../com.aspose.drawing/region) vertikalt. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Förskjuter koordinaterna för detta [Region](../../com.aspose.drawing/region) med det angivna beloppet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | int | Mängden för att förskjuta detta [Region](../../com.aspose.drawing/region) horisontellt |
| dy | int | Mängden för att förskjuta detta [Region](../../com.aspose.drawing/region) vertikalt. |

### transform(Matrix matrix) {#transform-com.aspose.drawing.drawing2d.Matrix-}
```
public void transform(Matrix matrix)
```


Transformerar detta [Region](../../com.aspose.drawing/region) med den angivna [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Den [Matrix](../../com.aspose.drawing.drawing2d/matrix) som används för att transformera detta [Region](../../com.aspose.drawing/region). |

### getBounds(Graphics g) {#getBounds-com.aspose.drawing.Graphics-}
```
public RectangleF getBounds(Graphics g)
```


Hämtar en [RectangleF](../../com.aspose.drawing/rectanglef)-struktur som representerar en rektangel som avgränsar detta [Region](../../com.aspose.drawing/region) på ritningsytan för ett [Graphics](../../com.aspose.drawing/graphics)-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Den [Graphics](../../com.aspose.drawing/graphics) som detta [Region](../../com.aspose.drawing/region) ritas på. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents the bounding rectangle for this [Region](../../com.aspose.drawing/region) on the specified drawing surface.
### getRegionScans(Matrix matrix) {#getRegionScans-com.aspose.drawing.drawing2d.Matrix-}
```
public RectangleF[] getRegionScans(Matrix matrix)
```


Returnerar en array av [RectangleF](../../com.aspose.drawing/rectanglef)-strukturer som approximerar detta [Region](../../com.aspose.drawing/region) efter att den angivna matrisomvandlingen har tillämpats.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | En [Matrix](../../com.aspose.drawing.drawing2d/matrix) som representerar en geometrisk transformation att tillämpa på regionen. |

**Returns:**
com.aspose.drawing.RectangleF[] - En array av [RectangleF](../../com.aspose.drawing/rectanglef) strukturer som approximerar detta [Region](../../com.aspose.drawing/region) efter att den angivna matrisomvandlingen har tillämpats.
### isEmpty(Graphics g) {#isEmpty-com.aspose.drawing.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Testar om detta [Region](../../com.aspose.drawing/region) har ett tomt inre på den angivna ritningsytan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | En [Graphics](../../com.aspose.drawing/graphics) som representerar en ritningsyta. |

**Returns:**
boolean - true om innanmätet av detta [Region](../../com.aspose.drawing/region) är tomt när transformationen som är associerad med `g` tillämpas; annars false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.drawing.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Testar om detta [Region](../../com.aspose.drawing/region) har ett oändligt inre på den angivna ritningsytan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | En [Graphics](../../com.aspose.drawing/graphics) som representerar en ritningsyta. |

**Returns:**
boolean - true om innanmätet av detta [Region](../../com.aspose.drawing/region) är oändligt när transformationen som är associerad med `g` tillämpas; annars false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Testar om den angivna punkten finns inom detta [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | flyttal | x‑koordinaten för den punkt som ska testas. |
| y | flyttal | y-koordinaten för punkten som ska testas. |

**Returns:**
boolean - true när den angivna punkten finns inom detta [Region](../../com.aspose.drawing/region); annars false.
### isVisible(PointF point) {#isVisible-com.aspose.drawing.PointF-}
```
public boolean isVisible(PointF point)
```


Testar om den angivna [PointF](../../com.aspose.drawing/pointf)-strukturen finns inom detta [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | Den [PointF](../../com.aspose.drawing/pointf) strukturen att testa. |

**Returns:**
boolean - true när `point` finns inom detta [Region](../../com.aspose.drawing/region); annars false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Testar om den angivna punkten finns inom detta [Region](../../com.aspose.drawing/region) när den ritas med den angivna [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | flyttal | x‑koordinaten för den punkt som ska testas. |
| y | flyttal | y-koordinaten för punkten som ska testas. |
| g | [Graphics](../../com.aspose.drawing/graphics) | En [Graphics](../../com.aspose.drawing/graphics) som representerar ett grafiskt sammanhang. |

**Returns:**
boolean - true när den angivna punkten finns inom detta [Region](../../com.aspose.drawing/region); annars false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Testar om den angivna [PointF](../../com.aspose.drawing/pointf)-strukturen finns inom detta [Region](../../com.aspose.drawing/region) när den ritas med den angivna [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | Den [PointF](../../com.aspose.drawing/pointf) strukturen att testa. |
| g | [Graphics](../../com.aspose.drawing/graphics) | En [Graphics](../../com.aspose.drawing/graphics) som representerar ett grafiskt sammanhang. |

**Returns:**
boolean - true när `point` finns inom detta [Region](../../com.aspose.drawing/region); annars false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Testar om någon del av den angivna rektangeln finns inom detta [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | flyttal | X‑koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| y | flyttal | Y‑koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| bredd | flyttal | Bredden på rektangeln som ska testas. |
| höjd | flyttal | Höjden på rektangeln som ska testas. |

**Returns:**
boolean - true när någon del av den angivna rektangeln finns inom detta [Region](../../com.aspose.drawing/region)‑objekt; annars false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.drawing.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Testar om någon del av den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen finns inom detta [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef) strukturen att testa. |

**Returns:**
boolean - true när någon del av `rect` finns inom detta [Region](../../com.aspose.drawing/region); annars false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Testar om någon del av den angivna rektangeln finns inom detta [Region](../../com.aspose.drawing/region) när den ritas med den angivna [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | flyttal | X‑koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| y | flyttal | Y‑koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| bredd | flyttal | Bredden på rektangeln som ska testas. |
| höjd | flyttal | Höjden på rektangeln som ska testas. |
| g | [Graphics](../../com.aspose.drawing/graphics) | En [Graphics](../../com.aspose.drawing/graphics) som representerar ett grafiskt sammanhang. |

**Returns:**
boolean - true när någon del av den angivna rektangeln finns inom detta [Region](../../com.aspose.drawing/region); annars false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Testar om någon del av den angivna [RectangleF](../../com.aspose.drawing/rectanglef)-strukturen finns inom detta [Region](../../com.aspose.drawing/region) när den ritas med den angivna [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Den [RectangleF](../../com.aspose.drawing/rectanglef) strukturen att testa. |
| g | [Graphics](../../com.aspose.drawing/graphics) | En [Graphics](../../com.aspose.drawing/graphics) som representerar ett grafiskt sammanhang. |

**Returns:**
boolean - true när `rect` finns inom detta [Region](../../com.aspose.drawing/region); annars false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Testar om den angivna punkten finns inom detta [Region](../../com.aspose.drawing/region)-objekt när det ritas med det angivna [Graphics](../../com.aspose.drawing/graphics)-objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | x‑koordinaten för den punkt som ska testas. |
| y | int | y-koordinaten för punkten som ska testas. |
| g | [Graphics](../../com.aspose.drawing/graphics) | En [Graphics](../../com.aspose.drawing/graphics) som representerar ett grafiskt sammanhang. |

**Returns:**
boolean - true när den angivna punkten finns inom detta [Region](../../com.aspose.drawing/region); annars false.
### isVisible(Point point) {#isVisible-com.aspose.drawing.Point-}
```
public boolean isVisible(Point point)
```


Testar om den angivna [Point](../../com.aspose.drawing/point)-strukturen finns inom detta [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | Den [Point](../../com.aspose.drawing/point) strukturen att testa. |

**Returns:**
boolean - true när `point` finns inom detta [Region](../../com.aspose.drawing/region); annars false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Testar om den angivna [Point](../../com.aspose.drawing/point)-strukturen finns inom detta [Region](../../com.aspose.drawing/region) när den ritas med den angivna [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | Den [Point](../../com.aspose.drawing/point) strukturen att testa. |
| g | [Graphics](../../com.aspose.drawing/graphics) | En [Graphics](../../com.aspose.drawing/graphics) som representerar ett grafiskt sammanhang. |

**Returns:**
boolean - true när `point` finns inom detta [Region](../../com.aspose.drawing/region); annars false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Testar om någon del av den angivna rektangeln finns inom detta [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X‑koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| y | int | Y‑koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| bredd | int | Bredden på rektangeln som ska testas. |
| höjd | int | Höjden på rektangeln som ska testas. |

**Returns:**
boolean - true när någon del av den angivna rektangeln finns inom detta [Region](../../com.aspose.drawing/region); annars false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.drawing.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Testar om någon del av den angivna [Rectangle](../../com.aspose.drawing/rectangle)-strukturen finns inom detta [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Den [Rectangle](../../com.aspose.drawing/rectangle) strukturen att testa. |

**Returns:**
boolean - Denna metod returnerar true när någon del av `rect` finns inom detta [Region](../../com.aspose.drawing/region); annars false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Testar om någon del av den angivna rektangeln finns inom detta [Region](../../com.aspose.drawing/region) när den ritas med den angivna [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X‑koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| y | int | Y‑koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| bredd | int | Bredden på rektangeln som ska testas. |
| höjd | int | Höjden på rektangeln som ska testas. |
| g | [Graphics](../../com.aspose.drawing/graphics) | En [Graphics](../../com.aspose.drawing/graphics) som representerar ett grafiskt sammanhang. |

**Returns:**
boolean - true när någon del av den angivna rektangeln finns inom detta [Region](../../com.aspose.drawing/region); annars false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Testar om någon del av den angivna [Rectangle](../../com.aspose.drawing/rectangle)-strukturen finns inom detta [Region](../../com.aspose.drawing/region) när den ritas med den angivna [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Den [Rectangle](../../com.aspose.drawing/rectangle) strukturen att testa. |
| g | [Graphics](../../com.aspose.drawing/graphics) | En [Graphics](../../com.aspose.drawing/graphics) som representerar ett grafiskt sammanhang. |

**Returns:**
boolean - true när någon del av `rect` finns inom detta [Region](../../com.aspose.drawing/region); annars false.
