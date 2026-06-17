---
title: Region
second_title: Riferimento API di Aspose.Drawing per Java
description: Descrive l'interno di una forma grafica composta da rettangoli e percorsi.
type: docs
weight: 40
url: /it/java/com.aspose.drawing/region/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Region implements System.IDisposable
```

Descrive l'interno di una forma grafica composta da rettangoli e percorsi. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Region()](#Region--) | Inizializza una nuova istanza della classe [Region](../../com.aspose.drawing/region). |
| [Region(RectangleF rect)](#Region-com.aspose.drawing.RectangleF-) | Inizializza una nuova istanza della classe [Region](../../com.aspose.drawing/region) dalla struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata. |
| [Region(Rectangle rect)](#Region-com.aspose.drawing.Rectangle-) | Inizializza una nuova istanza della classe [Region](../../com.aspose.drawing/region) dalla struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata. |
| [Region(GraphicsPath path)](#Region-com.aspose.drawing.drawing2d.GraphicsPath-) | Inizializza una nuova istanza della classe [Region](../../com.aspose.drawing/region) con il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) specificato. |
| [Region(RegionData rgnData)](#Region-com.aspose.drawing.drawing2d.RegionData-) | Inizializza una nuova istanza della classe [Region](../../com.aspose.drawing/region) dai dati specificati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [dispose()](#dispose--) | Rilascia tutte le risorse utilizzate da questo [Region](../../com.aspose.drawing/region). |
| [equals(Region region, Graphics g)](#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-) | Verifica se il [Region](../../com.aspose.drawing/region) specificato è identico a questo [Region](../../com.aspose.drawing/region) sulla superficie di disegno specificata. |
| [deepClone()](#deepClone--) | Crea una copia esatta di questo [Region](../../com.aspose.drawing/region). |
| [makeInfinite()](#makeInfinite--) | Inizializza questo oggetto [Region](../../com.aspose.drawing/region) a un interno infinito. |
| [makeEmpty()](#makeEmpty--) | Inizializza questo [Region](../../com.aspose.drawing/region) a un interno vuoto. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Aggiorna questo [Region](../../com.aspose.drawing/region) all'intersezione di sé con la struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata. |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Aggiorna questo [Region](../../com.aspose.drawing/region) all'intersezione di sé con la struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.drawing.drawing2d.GraphicsPath-) | Aggiorna questo [Region](../../com.aspose.drawing/region) all'intersezione di sé con il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) specificato. |
| [intersect(Region region)](#intersect-com.aspose.drawing.Region-) | Aggiorna questo [Region](../../com.aspose.drawing/region) all'intersezione di sé con il [Region](../../com.aspose.drawing/region) specificato. |
| [union(RectangleF rect)](#union-com.aspose.drawing.RectangleF-) | Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione di sé con la struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata. |
| [union(Rectangle rect)](#union-com.aspose.drawing.Rectangle-) | Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione di sé con la struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata. |
| [union(GraphicsPath path)](#union-com.aspose.drawing.drawing2d.GraphicsPath-) | Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione di sé con il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) specificato. |
| [union(Region region)](#union-com.aspose.drawing.Region-) | Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione di sé con il [Region](../../com.aspose.drawing/region) specificato. |
| [getRegionData()](#getRegionData--) | Restituisce un [RegionData](../../com.aspose.drawing.drawing2d/regiondata) che rappresenta le informazioni che descrivono questo [Region](../../com.aspose.drawing/region). |
| [xor(RectangleF rect)](#xor-com.aspose.drawing.RectangleF-) | Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione meno l'intersezione di sé con la struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata. |
| [xor(Rectangle rect)](#xor-com.aspose.drawing.Rectangle-) | Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione meno l'intersezione di sé con la struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata. |
| [xor(GraphicsPath path)](#xor-com.aspose.drawing.drawing2d.GraphicsPath-) | Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione meno l'intersezione di sé con il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) specificato. |
| [xor(Region region)](#xor-com.aspose.drawing.Region-) | Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione meno l'intersezione di sé con il [Region](../../com.aspose.drawing/region) specificato. |
| [exclude(RectangleF rect)](#exclude-com.aspose.drawing.RectangleF-) | Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere solo la parte del suo interno che non interseca la struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata. |
| [exclude(Rectangle rect)](#exclude-com.aspose.drawing.Rectangle-) | Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere solo la parte del suo interno che non interseca la struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.drawing.drawing2d.GraphicsPath-) | Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere solo la parte del suo interno che non interseca il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) specificato. |
| [exclude(Region region)](#exclude-com.aspose.drawing.Region-) | Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere solo la parte del suo interno che non interseca il [Region](../../com.aspose.drawing/region) specificato. |
| [complement(RectangleF rect)](#complement-com.aspose.drawing.RectangleF-) | Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere la parte della struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata che non interseca questo [Region](../../com.aspose.drawing/region). |
| [complement(Rectangle rect)](#complement-com.aspose.drawing.Rectangle-) | Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere la parte della struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata che non interseca questo [Region](../../com.aspose.drawing/region). |
| [complement(GraphicsPath path)](#complement-com.aspose.drawing.drawing2d.GraphicsPath-) | Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere la parte del [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) specificato che non interseca questo [Region](../../com.aspose.drawing/region). |
| [complement(Region region)](#complement-com.aspose.drawing.Region-) | Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere la porzione della [Region](../../com.aspose.drawing/region) specificata che non interseca questo [Region](../../com.aspose.drawing/region). |
| [translate(float dx, float dy)](#translate-float-float-) | Sposta le coordinate di questo [Region](../../com.aspose.drawing/region) dell'importo specificato. |
| [translate(int dx, int dy)](#translate-int-int-) | Sposta le coordinate di questo [Region](../../com.aspose.drawing/region) dell'importo specificato. |
| [transform(Matrix matrix)](#transform-com.aspose.drawing.drawing2d.Matrix-) | Trasforma questo [Region](../../com.aspose.drawing/region) con la [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificata. |
| [getBounds(Graphics g)](#getBounds-com.aspose.drawing.Graphics-) | Ottiene una struttura [RectangleF](../../com.aspose.drawing/rectanglef) che rappresenta un rettangolo che delimita questo [Region](../../com.aspose.drawing/region) sulla superficie di disegno di un oggetto [Graphics](../../com.aspose.drawing/graphics). |
| [getRegionScans(Matrix matrix)](#getRegionScans-com.aspose.drawing.drawing2d.Matrix-) | Restituisce un array di strutture [RectangleF](../../com.aspose.drawing/rectanglef) che approssimano questo [Region](../../com.aspose.drawing/region) dopo l'applicazione della trasformazione matriciale specificata. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.drawing.Graphics-) | Verifica se questo [Region](../../com.aspose.drawing/region) ha un interno vuoto sulla superficie di disegno specificata. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.drawing.Graphics-) | Verifica se questo [Region](../../com.aspose.drawing/region) ha un interno infinito sulla superficie di disegno specificata. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Verifica se il punto specificato è contenuto all'interno di questo [Region](../../com.aspose.drawing/region). |
| [isVisible(PointF point)](#isVisible-com.aspose.drawing.PointF-) | Verifica se la struttura [PointF](../../com.aspose.drawing/pointf) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region). |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.drawing.Graphics-) | Verifica se il punto specificato è contenuto all'interno di questo [Region](../../com.aspose.drawing/region) quando viene disegnato con il [Graphics](../../com.aspose.drawing/graphics) specificato. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-) | Verifica se la struttura [PointF](../../com.aspose.drawing/pointf) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region) quando viene disegnata con il [Graphics](../../com.aspose.drawing/graphics) specificato. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Verifica se qualche porzione del rettangolo specificato è contenuta all'interno di questo [Region](../../com.aspose.drawing/region). |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.drawing.RectangleF-) | Verifica se qualche porzione della struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region). |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.drawing.Graphics-) | Verifica se qualche porzione del rettangolo specificato è contenuta all'interno di questo [Region](../../com.aspose.drawing/region) quando viene disegnato con il [Graphics](../../com.aspose.drawing/graphics) specificato. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-) | Verifica se qualche porzione della struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region) quando viene disegnata con il [Graphics](../../com.aspose.drawing/graphics) specificato. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.drawing.Graphics-) | Verifica se il punto specificato è contenuto all'interno di questo oggetto [Region](../../com.aspose.drawing/region) quando viene disegnato con l'oggetto [Graphics](../../com.aspose.drawing/graphics) specificato. |
| [isVisible(Point point)](#isVisible-com.aspose.drawing.Point-) | Verifica se la struttura [Point](../../com.aspose.drawing/point) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region). |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-) | Verifica se la struttura [Point](../../com.aspose.drawing/point) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region) quando viene disegnata con il [Graphics](../../com.aspose.drawing/graphics) specificato. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Verifica se qualche porzione del rettangolo specificato è contenuta all'interno di questo [Region](../../com.aspose.drawing/region). |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.drawing.Rectangle-) | Verifica se qualche porzione della struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region). |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.drawing.Graphics-) | Verifica se qualche porzione del rettangolo specificato è contenuta all'interno di questo [Region](../../com.aspose.drawing/region) quando viene disegnato con il [Graphics](../../com.aspose.drawing/graphics) specificato. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-) | Verifica se qualche porzione della struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region) quando viene disegnata con il [Graphics](../../com.aspose.drawing/graphics) specificato. |
### Region() {#Region--}
```
public Region()
```


Inizializza una nuova istanza della classe [Region](../../com.aspose.drawing/region).

### Region(RectangleF rect) {#Region-com.aspose.drawing.RectangleF-}
```
public Region(RectangleF rect)
```


Inizializza una nuova istanza della classe [Region](../../com.aspose.drawing/region) dalla struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una struttura [RectangleF](../../com.aspose.drawing/rectanglef) che definisce l'interno del nuovo [Region](../../com.aspose.drawing/region). |

### Region(Rectangle rect) {#Region-com.aspose.drawing.Rectangle-}
```
public Region(Rectangle rect)
```


Inizializza una nuova istanza della classe [Region](../../com.aspose.drawing/region) dalla struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Una struttura [Rectangle](../../com.aspose.drawing/rectangle) che definisce l'interno del nuovo [Region](../../com.aspose.drawing/region). |

### Region(GraphicsPath path) {#Region-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Inizializza una nuova istanza della classe [Region](../../com.aspose.drawing/region) con il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) che definisce il nuovo [Region](../../com.aspose.drawing/region). |

### Region(RegionData rgnData) {#Region-com.aspose.drawing.drawing2d.RegionData-}
```
public Region(RegionData rgnData)
```


Inizializza una nuova istanza della classe [Region](../../com.aspose.drawing/region) dai dati specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rgnData | [RegionData](../../com.aspose.drawing.drawing2d/regiondata) | Un [RegionData](../../com.aspose.drawing.drawing2d/regiondata) che definisce l'interno del nuovo [Region](../../com.aspose.drawing/region). |

### dispose() {#dispose--}
```
public void dispose()
```


Rilascia tutte le risorse utilizzate da questo [Region](../../com.aspose.drawing/region).

### equals(Region region, Graphics g) {#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-}
```
public boolean equals(Region region, Graphics g)
```


Verifica se il [Region](../../com.aspose.drawing/region) specificato è identico a questo [Region](../../com.aspose.drawing/region) sulla superficie di disegno specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Il [Region](../../com.aspose.drawing/region) da testare. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) che rappresenta una superficie di disegno. |

**Returns:**
boolean - true se l'interno della regione è identico all'interno di questa regione quando la trasformazione associata al parametro `g` è applicata; altrimenti, false.
### deepClone() {#deepClone--}
```
public Region deepClone()
```


Crea una copia esatta di questo [Region](../../com.aspose.drawing/region).

**Returns:**
[Region](../../com.aspose.drawing/region) - The [Region](../../com.aspose.drawing/region) that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Inizializza questo oggetto [Region](../../com.aspose.drawing/region) a un interno infinito.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Inizializza questo [Region](../../com.aspose.drawing/region) a un interno vuoto.

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public void intersect(RectangleF rect)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) all'intersezione di sé con la struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La struttura [RectangleF](../../com.aspose.drawing/rectanglef) da intersecare con questa [Region](../../com.aspose.drawing/region). |

### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public void intersect(Rectangle rect)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) all'intersezione di sé con la struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La struttura [Rectangle](../../com.aspose.drawing/rectangle) da intersecare con questa [Region](../../com.aspose.drawing/region). |

### intersect(GraphicsPath path) {#intersect-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) all'intersezione di sé con il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) da intersecare con questa [Region](../../com.aspose.drawing/region). |

### intersect(Region region) {#intersect-com.aspose.drawing.Region-}
```
public void intersect(Region region)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) all'intersezione di sé con il [Region](../../com.aspose.drawing/region) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | La [Region](../../com.aspose.drawing/region) da intersecare con questa [Region](../../com.aspose.drawing/region). |

### union(RectangleF rect) {#union-com.aspose.drawing.RectangleF-}
```
public void union(RectangleF rect)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione di sé con la struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La struttura [RectangleF](../../com.aspose.drawing/rectanglef) da unire con questa [Region](../../com.aspose.drawing/region). |

--------------------

L'unione lascia la regione infinita come infinita. |

### union(Rectangle rect) {#union-com.aspose.drawing.Rectangle-}
```
public void union(Rectangle rect)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione di sé con la struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | rect | [Rectangle](../../com.aspose.drawing/rectangle) | La struttura [Rectangle](../../com.aspose.drawing/rectangle) da unire con questa [Region](../../com.aspose.drawing/region). |

--------------------

L'unione lascia la regione infinita come infinita. |

### union(GraphicsPath path) {#union-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione di sé con il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) da unire con questa [Region](../../com.aspose.drawing/region). |

--------------------

L'unione lascia la regione infinita come infinita. |

### union(Region region) {#union-com.aspose.drawing.Region-}
```
public void union(Region region)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione di sé con il [Region](../../com.aspose.drawing/region) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | region | [Region](../../com.aspose.drawing/region) | La [Region](../../com.aspose.drawing/region) da unire con questa [Region](../../com.aspose.drawing/region). |

--------------------

L'unione lascia la regione infinita come infinita. |

### getRegionData() {#getRegionData--}
```
public RegionData getRegionData()
```


Restituisce un [RegionData](../../com.aspose.drawing.drawing2d/regiondata) che rappresenta le informazioni che descrivono questo [Region](../../com.aspose.drawing/region).

**Returns:**
[RegionData](../../com.aspose.drawing.drawing2d/regiondata) - A [RegionData](../../com.aspose.drawing.drawing2d/regiondata) that represents the information that describes this [Region](../../com.aspose.drawing/region).
### xor(RectangleF rect) {#xor-com.aspose.drawing.RectangleF-}
```
public void xor(RectangleF rect)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione meno l'intersezione di sé con la struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La struttura [RectangleF](../../com.aspose.drawing/rectanglef) per `M:Region.Xor(Drawing2D.GraphicsPath)` con questa [Region](../../com.aspose.drawing/region). |

### xor(Rectangle rect) {#xor-com.aspose.drawing.Rectangle-}
```
public void xor(Rectangle rect)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione meno l'intersezione di sé con la struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La struttura [Rectangle](../../com.aspose.drawing/rectangle) per `M:Region.Xor(Rectangle)` con questa [Region](../../com.aspose.drawing/region). |

### xor(GraphicsPath path) {#xor-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione meno l'intersezione di sé con il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) per `M:Region.Xor(GraphicsPath)` con questa [Region](../../com.aspose.drawing/region). |

### xor(Region region) {#xor-com.aspose.drawing.Region-}
```
public void xor(Region region)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) all'unione meno l'intersezione di sé con il [Region](../../com.aspose.drawing/region) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | La [Region](../../com.aspose.drawing/region) per `M:Region.Xor(Region)` con questa [Region](../../com.aspose.drawing/region). |

### exclude(RectangleF rect) {#exclude-com.aspose.drawing.RectangleF-}
```
public void exclude(RectangleF rect)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere solo la parte del suo interno che non interseca la struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La struttura [RectangleF](../../com.aspose.drawing/rectanglef) da escludere da questa [Region](../../com.aspose.drawing/region). |

### exclude(Rectangle rect) {#exclude-com.aspose.drawing.Rectangle-}
```
public void exclude(Rectangle rect)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere solo la parte del suo interno che non interseca la struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La struttura [Rectangle](../../com.aspose.drawing/rectangle) da escludere da questa [Region](../../com.aspose.drawing/region). |

### exclude(GraphicsPath path) {#exclude-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere solo la parte del suo interno che non interseca il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) da escludere da questa [Region](../../com.aspose.drawing/region). |

### exclude(Region region) {#exclude-com.aspose.drawing.Region-}
```
public void exclude(Region region)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere solo la parte del suo interno che non interseca il [Region](../../com.aspose.drawing/region) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | La [Region](../../com.aspose.drawing/region) da escludere da questa [Region](../../com.aspose.drawing/region). |

### complement(RectangleF rect) {#complement-com.aspose.drawing.RectangleF-}
```
public void complement(RectangleF rect)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere la parte della struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata che non interseca questo [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La struttura [RectangleF](../../com.aspose.drawing/rectanglef) per complementare questa [Region](../../com.aspose.drawing/region). |

### complement(Rectangle rect) {#complement-com.aspose.drawing.Rectangle-}
```
public void complement(Rectangle rect)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere la parte della struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata che non interseca questo [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La struttura [Rectangle](../../com.aspose.drawing/rectangle) per complementare questa [Region](../../com.aspose.drawing/region). |

### complement(GraphicsPath path) {#complement-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere la parte del [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) specificato che non interseca questo [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) per complementare questa [Region](../../com.aspose.drawing/region). |

### complement(Region region) {#complement-com.aspose.drawing.Region-}
```
public void complement(Region region)
```


Aggiorna questo [Region](../../com.aspose.drawing/region) per contenere la porzione della [Region](../../com.aspose.drawing/region) specificata che non interseca questo [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | L'oggetto [Region](../../com.aspose.drawing/region) per complementare questo oggetto [Region](../../com.aspose.drawing/region). |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Sposta le coordinate di questo [Region](../../com.aspose.drawing/region) dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | La quantità per spostare orizzontalmente questa [Region](../../com.aspose.drawing/region). |
| dy | float | La quantità per spostare verticalmente questa [Region](../../com.aspose.drawing/region). |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Sposta le coordinate di questo [Region](../../com.aspose.drawing/region) dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | int | La quantità per spostare orizzontalmente questa [Region](../../com.aspose.drawing/region) |
| dy | int | La quantità per spostare verticalmente questa [Region](../../com.aspose.drawing/region). |

### transform(Matrix matrix) {#transform-com.aspose.drawing.drawing2d.Matrix-}
```
public void transform(Matrix matrix)
```


Trasforma questo [Region](../../com.aspose.drawing/region) con la [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | La [Matrix](../../com.aspose.drawing.drawing2d/matrix) con cui trasformare questa [Region](../../com.aspose.drawing/region). |

### getBounds(Graphics g) {#getBounds-com.aspose.drawing.Graphics-}
```
public RectangleF getBounds(Graphics g)
```


Ottiene una struttura [RectangleF](../../com.aspose.drawing/rectanglef) che rappresenta un rettangolo che delimita questo [Region](../../com.aspose.drawing/region) sulla superficie di disegno di un oggetto [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Il [Graphics](../../com.aspose.drawing/graphics) su cui viene disegnata questa [Region](../../com.aspose.drawing/region). |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents the bounding rectangle for this [Region](../../com.aspose.drawing/region) on the specified drawing surface.
### getRegionScans(Matrix matrix) {#getRegionScans-com.aspose.drawing.drawing2d.Matrix-}
```
public RectangleF[] getRegionScans(Matrix matrix)
```


Restituisce un array di strutture [RectangleF](../../com.aspose.drawing/rectanglef) che approssimano questo [Region](../../com.aspose.drawing/region) dopo l'applicazione della trasformazione matriciale specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Una [Matrix](../../com.aspose.drawing.drawing2d/matrix) che rappresenta una trasformazione geometrica da applicare alla regione. |

**Returns:**
com.aspose.drawing.RectangleF[] - Un array di strutture [RectangleF](../../com.aspose.drawing/rectanglef) che approssimano questa [Region](../../com.aspose.drawing/region) dopo l'applicazione della trasformazione matrice specificata.
### isEmpty(Graphics g) {#isEmpty-com.aspose.drawing.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Verifica se questo [Region](../../com.aspose.drawing/region) ha un interno vuoto sulla superficie di disegno specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) che rappresenta una superficie di disegno. |

**Returns:**
boolean - true se l'interno di questa [Region](../../com.aspose.drawing/region) è vuoto quando viene applicata la trasformazione associata a `g`; altrimenti, false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.drawing.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Verifica se questo [Region](../../com.aspose.drawing/region) ha un interno infinito sulla superficie di disegno specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) che rappresenta una superficie di disegno. |

**Returns:**
boolean - true se l'interno di questa [Region](../../com.aspose.drawing/region) è infinito quando viene applicata la trasformazione associata a `g`; altrimenti, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Verifica se il punto specificato è contenuto all'interno di questo [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns:**
boolean - true quando il punto specificato è contenuto all'interno di questa [Region](../../com.aspose.drawing/region); altrimenti, false.
### isVisible(PointF point) {#isVisible-com.aspose.drawing.PointF-}
```
public boolean isVisible(PointF point)
```


Verifica se la struttura [PointF](../../com.aspose.drawing/pointf) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | La struttura [PointF](../../com.aspose.drawing/pointf) da testare. |

**Returns:**
boolean - true quando `point` è contenuto all'interno di questa [Region](../../com.aspose.drawing/region); altrimenti, false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Verifica se il punto specificato è contenuto all'interno di questo [Region](../../com.aspose.drawing/region) quando viene disegnato con il [Graphics](../../com.aspose.drawing/graphics) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando il punto specificato è contenuto all'interno di questa [Region](../../com.aspose.drawing/region); altrimenti, false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Verifica se la struttura [PointF](../../com.aspose.drawing/pointf) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region) quando viene disegnata con il [Graphics](../../com.aspose.drawing/graphics) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | La struttura [PointF](../../com.aspose.drawing/pointf) da testare. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando `point` è contenuto all'interno di questa [Region](../../com.aspose.drawing/region); altrimenti, false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Verifica se qualche porzione del rettangolo specificato è contenuta all'interno di questo [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | float | La larghezza del rettangolo da testare. |
| height | float | L'altezza del rettangolo da testare. |

**Returns:**
boolean - true quando qualsiasi parte del rettangolo specificato è contenuta all'interno di questo oggetto [Region](../../com.aspose.drawing/region); altrimenti, false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.drawing.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Verifica se qualche porzione della struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La struttura [RectangleF](../../com.aspose.drawing/rectanglef) da testare. |

**Returns:**
boolean - true quando qualsiasi parte di `rect` è contenuta all'interno di questa [Region](../../com.aspose.drawing/region); altrimenti, false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Verifica se qualche porzione del rettangolo specificato è contenuta all'interno di questo [Region](../../com.aspose.drawing/region) quando viene disegnato con il [Graphics](../../com.aspose.drawing/graphics) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | float | La larghezza del rettangolo da testare. |
| height | float | L'altezza del rettangolo da testare. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando qualsiasi parte del rettangolo specificato è contenuta all'interno di questa [Region](../../com.aspose.drawing/region); altrimenti, false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Verifica se qualche porzione della struttura [RectangleF](../../com.aspose.drawing/rectanglef) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region) quando viene disegnata con il [Graphics](../../com.aspose.drawing/graphics) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La struttura [RectangleF](../../com.aspose.drawing/rectanglef) da testare. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando `rect` è contenuto all'interno di questa [Region](../../com.aspose.drawing/region); altrimenti, false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Verifica se il punto specificato è contenuto all'interno di questo oggetto [Region](../../com.aspose.drawing/region) quando viene disegnato con l'oggetto [Graphics](../../com.aspose.drawing/graphics) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando il punto specificato è contenuto all'interno di questa [Region](../../com.aspose.drawing/region); altrimenti, false.
### isVisible(Point point) {#isVisible-com.aspose.drawing.Point-}
```
public boolean isVisible(Point point)
```


Verifica se la struttura [Point](../../com.aspose.drawing/point) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | La struttura [Point](../../com.aspose.drawing/point) da testare. |

**Returns:**
boolean - true quando `point` è contenuto all'interno di questa [Region](../../com.aspose.drawing/region); altrimenti, false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Verifica se la struttura [Point](../../com.aspose.drawing/point) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region) quando viene disegnata con il [Graphics](../../com.aspose.drawing/graphics) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | La struttura [Point](../../com.aspose.drawing/point) da testare. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando `point` è contenuto all'interno di questa [Region](../../com.aspose.drawing/region); altrimenti, false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Verifica se qualche porzione del rettangolo specificato è contenuta all'interno di questo [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | int | La larghezza del rettangolo da testare. |
| height | int | L'altezza del rettangolo da testare. |

**Returns:**
boolean - true quando qualsiasi parte del rettangolo specificato è contenuta all'interno di questa [Region](../../com.aspose.drawing/region); altrimenti, false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.drawing.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Verifica se qualche porzione della struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La struttura [Rectangle](../../com.aspose.drawing/rectangle) da testare. |

**Returns:**
boolean - Questo metodo restituisce true quando qualsiasi parte di `rect` è contenuta all'interno di questa [Region](../../com.aspose.drawing/region); altrimenti, false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Verifica se qualche porzione del rettangolo specificato è contenuta all'interno di questo [Region](../../com.aspose.drawing/region) quando viene disegnato con il [Graphics](../../com.aspose.drawing/graphics) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | int | La larghezza del rettangolo da testare. |
| height | int | L'altezza del rettangolo da testare. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando qualsiasi parte del rettangolo specificato è contenuta all'interno di questa [Region](../../com.aspose.drawing/region); altrimenti, false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Verifica se qualche porzione della struttura [Rectangle](../../com.aspose.drawing/rectangle) specificata è contenuta all'interno di questo [Region](../../com.aspose.drawing/region) quando viene disegnata con il [Graphics](../../com.aspose.drawing/graphics) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La struttura [Rectangle](../../com.aspose.drawing/rectangle) da testare. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando qualsiasi parte del `rect` è contenuta all'interno di questa [Region](../../com.aspose.drawing/region); altrimenti, false.
