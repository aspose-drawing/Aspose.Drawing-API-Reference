---
title: Region
second_title: Référence de l'API Aspose.Drawing pour Java
description: Décrit l'intérieur d'une forme graphique composée de rectangles et de chemins.
type: docs
weight: 40
url: /fr/java/com.aspose.drawing/region/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Region implements System.IDisposable
```

Décrit l'intérieur d'une forme graphique composée de rectangles et de chemins. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Region()](#Region--) | Initialise une nouvelle instance de la classe [Region](../../com.aspose.drawing/region). |
| [Region(RectangleF rect)](#Region-com.aspose.drawing.RectangleF-) | Initialise une nouvelle instance de la classe [Region](../../com.aspose.drawing/region) à partir de la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée. |
| [Region(Rectangle rect)](#Region-com.aspose.drawing.Rectangle-) | Initialise une nouvelle instance de la classe [Region](../../com.aspose.drawing/region) à partir de la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée. |
| [Region(GraphicsPath path)](#Region-com.aspose.drawing.drawing2d.GraphicsPath-) | Initialise une nouvelle instance de la classe [Region](../../com.aspose.drawing/region) avec le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) spécifié. |
| [Region(RegionData rgnData)](#Region-com.aspose.drawing.drawing2d.RegionData-) | Initialise une nouvelle instance de la classe [Region](../../com.aspose.drawing/region) à partir des données spécifiées. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [dispose()](#dispose--) | Libère toutes les ressources utilisées par cette [Region](../../com.aspose.drawing/region). |
| [equals(Region region, Graphics g)](#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-) | Teste si la [Region](../../com.aspose.drawing/region) spécifiée est identique à cette [Region](../../com.aspose.drawing/region) sur la surface de dessin spécifiée. |
| [deepClone()](#deepClone--) | Crée une copie exacte de cette [Region](../../com.aspose.drawing/region). |
| [makeInfinite()](#makeInfinite--) | Initialise cet objet [Region](../../com.aspose.drawing/region) avec un intérieur infini. |
| [makeEmpty()](#makeEmpty--) | Initialise cette [Region](../../com.aspose.drawing/region) avec un intérieur vide. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’intersection d’elle‑même avec la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée. |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’intersection d’elle‑même avec la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.drawing.drawing2d.GraphicsPath-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’intersection d’elle‑même avec le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) spécifié. |
| [intersect(Region region)](#intersect-com.aspose.drawing.Region-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’intersection d’elle‑même avec la [Region](../../com.aspose.drawing/region) spécifiée. |
| [union(RectangleF rect)](#union-com.aspose.drawing.RectangleF-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union d’elle‑même avec la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée. |
| [union(Rectangle rect)](#union-com.aspose.drawing.Rectangle-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union d’elle‑même avec la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée. |
| [union(GraphicsPath path)](#union-com.aspose.drawing.drawing2d.GraphicsPath-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union d’elle‑même avec le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) spécifié. |
| [union(Region region)](#union-com.aspose.drawing.Region-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union d’elle‑même avec la [Region](../../com.aspose.drawing/region) spécifiée. |
| [getRegionData()](#getRegionData--) | Renvoie un [RegionData](../../com.aspose.drawing.drawing2d/regiondata) qui représente les informations décrivant cette [Region](../../com.aspose.drawing/region). |
| [xor(RectangleF rect)](#xor-com.aspose.drawing.RectangleF-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union moins l’intersection d’elle‑même avec la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée. |
| [xor(Rectangle rect)](#xor-com.aspose.drawing.Rectangle-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union moins l’intersection d’elle‑même avec la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée. |
| [xor(GraphicsPath path)](#xor-com.aspose.drawing.drawing2d.GraphicsPath-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union moins l’intersection d’elle‑même avec le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) spécifié. |
| [xor(Region region)](#xor-com.aspose.drawing.Region-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union moins l’intersection d’elle‑même avec la [Region](../../com.aspose.drawing/region) spécifiée. |
| [exclude(RectangleF rect)](#exclude-com.aspose.drawing.RectangleF-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour ne contenir que la partie de son intérieur qui n’intersecte pas la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée. |
| [exclude(Rectangle rect)](#exclude-com.aspose.drawing.Rectangle-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour ne contenir que la partie de son intérieur qui n’intersecte pas la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.drawing.drawing2d.GraphicsPath-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour ne contenir que la partie de son intérieur qui n’intersecte pas le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) spécifié. |
| [exclude(Region region)](#exclude-com.aspose.drawing.Region-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour ne contenir que la partie de son intérieur qui n’intersecte pas la [Region](../../com.aspose.drawing/region) spécifiée. |
| [complement(RectangleF rect)](#complement-com.aspose.drawing.RectangleF-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour contenir la partie de la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée qui n’intersecte pas cette [Region](../../com.aspose.drawing/region). |
| [complement(Rectangle rect)](#complement-com.aspose.drawing.Rectangle-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour contenir la partie de la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée qui n’intersecte pas cette [Region](../../com.aspose.drawing/region). |
| [complement(GraphicsPath path)](#complement-com.aspose.drawing.drawing2d.GraphicsPath-) | Met à jour cette [Region](../../com.aspose.drawing/region) pour contenir la partie du [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) spécifié qui n’intersecte pas cette [Region](../../com.aspose.drawing/region). |
| [complement(Region region)](#complement-com.aspose.drawing.Region-) | Met à jour ce [Region](../../com.aspose.drawing/region) pour contenir la partie du [Region](../../com.aspose.drawing/region) spécifié qui n’intersecte pas avec ce [Region](../../com.aspose.drawing/region). |
| [translate(float dx, float dy)](#translate-float-float-) | Décale les coordonnées de ce [Region](../../com.aspose.drawing/region) de la quantité spécifiée. |
| [translate(int dx, int dy)](#translate-int-int-) | Décale les coordonnées de ce [Region](../../com.aspose.drawing/region) de la quantité spécifiée. |
| [transform(Matrix matrix)](#transform-com.aspose.drawing.drawing2d.Matrix-) | Transforme ce [Region](../../com.aspose.drawing/region) à l’aide de la [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifiée. |
| [getBounds(Graphics g)](#getBounds-com.aspose.drawing.Graphics-) | Obtient une structure [RectangleF](../../com.aspose.drawing/rectanglef) qui représente un rectangle englobant ce [Region](../../com.aspose.drawing/region) sur la surface de dessin d’un objet [Graphics](../../com.aspose.drawing/graphics). |
| [getRegionScans(Matrix matrix)](#getRegionScans-com.aspose.drawing.drawing2d.Matrix-) | Renvoie un tableau de structures [RectangleF](../../com.aspose.drawing/rectanglef) qui approximent ce [Region](../../com.aspose.drawing/region) après l’application de la transformation matricielle spécifiée. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.drawing.Graphics-) | Teste si ce [Region](../../com.aspose.drawing/region) possède un intérieur vide sur la surface de dessin spécifiée. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.drawing.Graphics-) | Teste si ce [Region](../../com.aspose.drawing/region) possède un intérieur infini sur la surface de dessin spécifiée. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Teste si le point spécifié est contenu dans ce [Region](../../com.aspose.drawing/region). |
| [isVisible(PointF point)](#isVisible-com.aspose.drawing.PointF-) | Teste si la structure [PointF](../../com.aspose.drawing/pointf) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region). |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.drawing.Graphics-) | Teste si le point spécifié est contenu dans ce [Region](../../com.aspose.drawing/region) lorsqu’il est dessiné à l’aide du [Graphics](../../com.aspose.drawing/graphics) spécifié. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-) | Teste si la structure [PointF](../../com.aspose.drawing/pointf) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region) lorsqu’elle est dessinée à l’aide du [Graphics](../../com.aspose.drawing/graphics) spécifié. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Teste si une partie du rectangle spécifié est contenue dans ce [Region](../../com.aspose.drawing/region). |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.drawing.RectangleF-) | Teste si une partie de la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region). |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.drawing.Graphics-) | Teste si une partie du rectangle spécifié est contenue dans ce [Region](../../com.aspose.drawing/region) lorsqu’il est dessiné à l’aide du [Graphics](../../com.aspose.drawing/graphics) spécifié. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-) | Teste si une partie de la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region) lorsqu’elle est dessinée à l’aide du [Graphics](../../com.aspose.drawing/graphics) spécifié. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.drawing.Graphics-) | Teste si le point spécifié est contenu dans cet objet [Region](../../com.aspose.drawing/region) lorsqu’il est dessiné à l’aide de l’objet [Graphics](../../com.aspose.drawing/graphics) spécifié. |
| [isVisible(Point point)](#isVisible-com.aspose.drawing.Point-) | Teste si la structure [Point](../../com.aspose.drawing/point) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region). |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-) | Teste si la structure [Point](../../com.aspose.drawing/point) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region) lorsqu’elle est dessinée à l’aide du [Graphics](../../com.aspose.drawing/graphics) spécifié. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Teste si une partie du rectangle spécifié est contenue dans ce [Region](../../com.aspose.drawing/region). |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.drawing.Rectangle-) | Teste si une partie de la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region). |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.drawing.Graphics-) | Teste si une partie du rectangle spécifié est contenue dans ce [Region](../../com.aspose.drawing/region) lorsqu’il est dessiné à l’aide du [Graphics](../../com.aspose.drawing/graphics) spécifié. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-) | Teste si une partie de la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region) lorsqu’elle est dessinée à l’aide du [Graphics](../../com.aspose.drawing/graphics) spécifié. |
### Region() {#Region--}
```
public Region()
```


Initialise une nouvelle instance de la classe [Region](../../com.aspose.drawing/region).

### Region(RectangleF rect) {#Region-com.aspose.drawing.RectangleF-}
```
public Region(RectangleF rect)
```


Initialise une nouvelle instance de la classe [Region](../../com.aspose.drawing/region) à partir de la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Une structure [RectangleF](../../com.aspose.drawing/rectanglef) qui définit l’intérieur du nouveau [Region](../../com.aspose.drawing/region). |

### Region(Rectangle rect) {#Region-com.aspose.drawing.Rectangle-}
```
public Region(Rectangle rect)
```


Initialise une nouvelle instance de la classe [Region](../../com.aspose.drawing/region) à partir de la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Une structure [Rectangle](../../com.aspose.drawing/rectangle) qui définit l’intérieur du nouveau [Region](../../com.aspose.drawing/region). |

### Region(GraphicsPath path) {#Region-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Initialise une nouvelle instance de la classe [Region](../../com.aspose.drawing/region) avec le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) qui définit le nouveau [Region](../../com.aspose.drawing/region). |

### Region(RegionData rgnData) {#Region-com.aspose.drawing.drawing2d.RegionData-}
```
public Region(RegionData rgnData)
```


Initialise une nouvelle instance de la classe [Region](../../com.aspose.drawing/region) à partir des données spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rgnData | [RegionData](../../com.aspose.drawing.drawing2d/regiondata) | Un [RegionData](../../com.aspose.drawing.drawing2d/regiondata) qui définit l’intérieur du nouveau [Region](../../com.aspose.drawing/region). |

### dispose() {#dispose--}
```
public void dispose()
```


Libère toutes les ressources utilisées par cette [Region](../../com.aspose.drawing/region).

### equals(Region region, Graphics g) {#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-}
```
public boolean equals(Region region, Graphics g)
```


Teste si la [Region](../../com.aspose.drawing/region) spécifiée est identique à cette [Region](../../com.aspose.drawing/region) sur la surface de dessin spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Le [Region](../../com.aspose.drawing/region) à tester. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) qui représente une surface de dessin. |

**Returns:**
booléen - vrai si l'intérieur de la région est identique à l'intérieur de cette région lorsque la transformation associée au paramètre `g` est appliquée ; sinon, faux.
### deepClone() {#deepClone--}
```
public Region deepClone()
```


Crée une copie exacte de cette [Region](../../com.aspose.drawing/region).

**Returns:**
[Region](../../com.aspose.drawing/region) - The [Region](../../com.aspose.drawing/region) that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Initialise cet objet [Region](../../com.aspose.drawing/region) avec un intérieur infini.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Initialise cette [Region](../../com.aspose.drawing/region) avec un intérieur vide.

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public void intersect(RectangleF rect)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’intersection d’elle‑même avec la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La structure [RectangleF](../../com.aspose.drawing/rectanglef) à intersecter avec cette [Region](../../com.aspose.drawing/region). |

### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public void intersect(Rectangle rect)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’intersection d’elle‑même avec la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La structure [Rectangle](../../com.aspose.drawing/rectangle) à intersecter avec cette [Region](../../com.aspose.drawing/region). |

### intersect(GraphicsPath path) {#intersect-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’intersection d’elle‑même avec le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) à intersecter avec cette [Region](../../com.aspose.drawing/region). |

### intersect(Region region) {#intersect-com.aspose.drawing.Region-}
```
public void intersect(Region region)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’intersection d’elle‑même avec la [Region](../../com.aspose.drawing/region) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | La [Region](../../com.aspose.drawing/region) à intersecter avec cette [Region](../../com.aspose.drawing/region). |

### union(RectangleF rect) {#union-com.aspose.drawing.RectangleF-}
```
public void union(RectangleF rect)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union d’elle‑même avec la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La structure [RectangleF](../../com.aspose.drawing/rectanglef) à unir avec cette [Region](../../com.aspose.drawing/region). |

--------------------

L'union laisse la région infinie comme infinie. |

### union(Rectangle rect) {#union-com.aspose.drawing.Rectangle-}
```
public void union(Rectangle rect)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union d’elle‑même avec la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | rect | [Rectangle](../../com.aspose.drawing/rectangle) | La structure [Rectangle](../../com.aspose.drawing/rectangle) à unir avec cette [Region](../../com.aspose.drawing/region). |

--------------------

L'union laisse la région infinie comme infinie. |

### union(GraphicsPath path) {#union-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union d’elle‑même avec le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) à unir avec cette [Region](../../com.aspose.drawing/region). |

--------------------

L'union laisse la région infinie comme infinie. |

### union(Region region) {#union-com.aspose.drawing.Region-}
```
public void union(Region region)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union d’elle‑même avec la [Region](../../com.aspose.drawing/region) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | region | [Region](../../com.aspose.drawing/region) | La [Region](../../com.aspose.drawing/region) à unir avec cette [Region](../../com.aspose.drawing/region). |

--------------------

L'union laisse la région infinie comme infinie. |

### getRegionData() {#getRegionData--}
```
public RegionData getRegionData()
```


Renvoie un [RegionData](../../com.aspose.drawing.drawing2d/regiondata) qui représente les informations décrivant cette [Region](../../com.aspose.drawing/region).

**Returns:**
[RegionData](../../com.aspose.drawing.drawing2d/regiondata) - A [RegionData](../../com.aspose.drawing.drawing2d/regiondata) that represents the information that describes this [Region](../../com.aspose.drawing/region).
### xor(RectangleF rect) {#xor-com.aspose.drawing.RectangleF-}
```
public void xor(RectangleF rect)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union moins l’intersection d’elle‑même avec la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La structure [RectangleF](../../com.aspose.drawing/rectanglef) pour `M:Region.Xor(Drawing2D.GraphicsPath)` avec cette [Region](../../com.aspose.drawing/region). |

### xor(Rectangle rect) {#xor-com.aspose.drawing.Rectangle-}
```
public void xor(Rectangle rect)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union moins l’intersection d’elle‑même avec la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La structure [Rectangle](../../com.aspose.drawing/rectangle) pour `M:Region.Xor(Rectangle)` avec cette [Region](../../com.aspose.drawing/region). |

### xor(GraphicsPath path) {#xor-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union moins l’intersection d’elle‑même avec le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) pour `M:Region.Xor(GraphicsPath)` avec cette [Region](../../com.aspose.drawing/region). |

### xor(Region region) {#xor-com.aspose.drawing.Region-}
```
public void xor(Region region)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour qu’elle corresponde à l’union moins l’intersection d’elle‑même avec la [Region](../../com.aspose.drawing/region) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | La [Region](../../com.aspose.drawing/region) pour `M:Region.Xor(Region)` avec cette [Region](../../com.aspose.drawing/region). |

### exclude(RectangleF rect) {#exclude-com.aspose.drawing.RectangleF-}
```
public void exclude(RectangleF rect)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour ne contenir que la partie de son intérieur qui n’intersecte pas la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La structure [RectangleF](../../com.aspose.drawing/rectanglef) à exclure de cette [Region](../../com.aspose.drawing/region). |

### exclude(Rectangle rect) {#exclude-com.aspose.drawing.Rectangle-}
```
public void exclude(Rectangle rect)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour ne contenir que la partie de son intérieur qui n’intersecte pas la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La structure [Rectangle](../../com.aspose.drawing/rectangle) à exclure de cette [Region](../../com.aspose.drawing/region). |

### exclude(GraphicsPath path) {#exclude-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour ne contenir que la partie de son intérieur qui n’intersecte pas le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) à exclure de cette [Region](../../com.aspose.drawing/region). |

### exclude(Region region) {#exclude-com.aspose.drawing.Region-}
```
public void exclude(Region region)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour ne contenir que la partie de son intérieur qui n’intersecte pas la [Region](../../com.aspose.drawing/region) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | La [Region](../../com.aspose.drawing/region) à exclure de cette [Region](../../com.aspose.drawing/region). |

### complement(RectangleF rect) {#complement-com.aspose.drawing.RectangleF-}
```
public void complement(RectangleF rect)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour contenir la partie de la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée qui n’intersecte pas cette [Region](../../com.aspose.drawing/region).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La structure [RectangleF](../../com.aspose.drawing/rectanglef) pour compléter cette [Region](../../com.aspose.drawing/region). |

### complement(Rectangle rect) {#complement-com.aspose.drawing.Rectangle-}
```
public void complement(Rectangle rect)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour contenir la partie de la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée qui n’intersecte pas cette [Region](../../com.aspose.drawing/region).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La structure [Rectangle](../../com.aspose.drawing/rectangle) pour compléter cette [Region](../../com.aspose.drawing/region). |

### complement(GraphicsPath path) {#complement-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Met à jour cette [Region](../../com.aspose.drawing/region) pour contenir la partie du [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) spécifié qui n’intersecte pas cette [Region](../../com.aspose.drawing/region).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) pour compléter cette [Region](../../com.aspose.drawing/region). |

### complement(Region region) {#complement-com.aspose.drawing.Region-}
```
public void complement(Region region)
```


Met à jour ce [Region](../../com.aspose.drawing/region) pour contenir la partie du [Region](../../com.aspose.drawing/region) spécifié qui n’intersecte pas avec ce [Region](../../com.aspose.drawing/region).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | L'objet [Region](../../com.aspose.drawing/region) pour compléter cet objet [Region](../../com.aspose.drawing/region). |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Décale les coordonnées de ce [Region](../../com.aspose.drawing/region) de la quantité spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La quantité pour décaler horizontalement cette [Region](../../com.aspose.drawing/region). |
| dy | float | La quantité pour décaler verticalement cette [Region](../../com.aspose.drawing/region). |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Décale les coordonnées de ce [Region](../../com.aspose.drawing/region) de la quantité spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | int | Le montant pour décaler horizontalement cette [Region](../../com.aspose.drawing/region) |
| dy | int | La quantité pour décaler verticalement cette [Region](../../com.aspose.drawing/region). |

### transform(Matrix matrix) {#transform-com.aspose.drawing.drawing2d.Matrix-}
```
public void transform(Matrix matrix)
```


Transforme ce [Region](../../com.aspose.drawing/region) à l’aide de la [Matrix](../../com.aspose.drawing.drawing2d/matrix) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | La [Matrix](../../com.aspose.drawing.drawing2d/matrix) par laquelle transformer cette [Region](../../com.aspose.drawing/region). |

### getBounds(Graphics g) {#getBounds-com.aspose.drawing.Graphics-}
```
public RectangleF getBounds(Graphics g)
```


Obtient une structure [RectangleF](../../com.aspose.drawing/rectanglef) qui représente un rectangle englobant ce [Region](../../com.aspose.drawing/region) sur la surface de dessin d’un objet [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Le [Graphics](../../com.aspose.drawing/graphics) sur lequel cette [Region](../../com.aspose.drawing/region) est dessinée. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents the bounding rectangle for this [Region](../../com.aspose.drawing/region) on the specified drawing surface.
### getRegionScans(Matrix matrix) {#getRegionScans-com.aspose.drawing.drawing2d.Matrix-}
```
public RectangleF[] getRegionScans(Matrix matrix)
```


Renvoie un tableau de structures [RectangleF](../../com.aspose.drawing/rectanglef) qui approximent ce [Region](../../com.aspose.drawing/region) après l’application de la transformation matricielle spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Une [Matrix](../../com.aspose.drawing.drawing2d/matrix) qui représente une transformation géométrique à appliquer à la région. |

**Returns:**
com.aspose.drawing.RectangleF[] - Un tableau de structures [RectangleF](../../com.aspose.drawing/rectanglef) qui approximent cette [Region](../../com.aspose.drawing/region) après l'application de la transformation matricielle spécifiée.
### isEmpty(Graphics g) {#isEmpty-com.aspose.drawing.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Teste si ce [Region](../../com.aspose.drawing/region) possède un intérieur vide sur la surface de dessin spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) qui représente une surface de dessin. |

**Returns:**
boolean - vrai si l'intérieur de cette [Region](../../com.aspose.drawing/region) est vide lorsque la transformation associée à `g` est appliquée ; sinon, faux.
### isInfinite(Graphics g) {#isInfinite-com.aspose.drawing.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Teste si ce [Region](../../com.aspose.drawing/region) possède un intérieur infini sur la surface de dessin spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) qui représente une surface de dessin. |

**Returns:**
boolean - vrai si l'intérieur de cette [Region](../../com.aspose.drawing/region) est infini lorsque la transformation associée à `g` est appliquée ; sinon, faux.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Teste si le point spécifié est contenu dans ce [Region](../../com.aspose.drawing/region).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns:**
boolean - vrai lorsque le point spécifié est contenu dans cette [Region](../../com.aspose.drawing/region) ; sinon, faux.
### isVisible(PointF point) {#isVisible-com.aspose.drawing.PointF-}
```
public boolean isVisible(PointF point)
```


Teste si la structure [PointF](../../com.aspose.drawing/pointf) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | La structure [PointF](../../com.aspose.drawing/pointf) à tester. |

**Returns:**
boolean - vrai lorsque `point` est contenu dans cette [Region](../../com.aspose.drawing/region) ; sinon, faux.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Teste si le point spécifié est contenu dans ce [Region](../../com.aspose.drawing/region) lorsqu’il est dessiné à l’aide du [Graphics](../../com.aspose.drawing/graphics) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) qui représente un contexte graphique. |

**Returns:**
boolean - vrai lorsque le point spécifié est contenu dans cette [Region](../../com.aspose.drawing/region) ; sinon, faux.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Teste si la structure [PointF](../../com.aspose.drawing/pointf) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region) lorsqu’elle est dessinée à l’aide du [Graphics](../../com.aspose.drawing/graphics) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | La structure [PointF](../../com.aspose.drawing/pointf) à tester. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) qui représente un contexte graphique. |

**Returns:**
boolean - vrai lorsque `point` est contenu dans cette [Region](../../com.aspose.drawing/region) ; sinon, faux.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Teste si une partie du rectangle spécifié est contenue dans ce [Region](../../com.aspose.drawing/region).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| largeur | float | La largeur du rectangle à tester. |
| hauteur | float | La hauteur du rectangle à tester. |

**Returns:**
boolean - vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans cet objet [Region](../../com.aspose.drawing/region) ; sinon, faux.
### isVisible(RectangleF rect) {#isVisible-com.aspose.drawing.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Teste si une partie de la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La structure [RectangleF](../../com.aspose.drawing/rectanglef) à tester. |

**Returns:**
boolean - vrai lorsque n'importe quelle partie de `rect` est contenue dans cette [Region](../../com.aspose.drawing/region) ; sinon, faux.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Teste si une partie du rectangle spécifié est contenue dans ce [Region](../../com.aspose.drawing/region) lorsqu’il est dessiné à l’aide du [Graphics](../../com.aspose.drawing/graphics) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| largeur | float | La largeur du rectangle à tester. |
| hauteur | float | La hauteur du rectangle à tester. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) qui représente un contexte graphique. |

**Returns:**
boolean - vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans cette [Region](../../com.aspose.drawing/region) ; sinon, faux.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Teste si une partie de la structure [RectangleF](../../com.aspose.drawing/rectanglef) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region) lorsqu’elle est dessinée à l’aide du [Graphics](../../com.aspose.drawing/graphics) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La structure [RectangleF](../../com.aspose.drawing/rectanglef) à tester. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) qui représente un contexte graphique. |

**Returns:**
boolean - vrai lorsque `rect` est contenu dans cette [Region](../../com.aspose.drawing/region) ; sinon, faux.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Teste si le point spécifié est contenu dans cet objet [Region](../../com.aspose.drawing/region) lorsqu’il est dessiné à l’aide de l’objet [Graphics](../../com.aspose.drawing/graphics) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) qui représente un contexte graphique. |

**Returns:**
boolean - vrai lorsque le point spécifié est contenu dans cette [Region](../../com.aspose.drawing/region) ; sinon, faux.
### isVisible(Point point) {#isVisible-com.aspose.drawing.Point-}
```
public boolean isVisible(Point point)
```


Teste si la structure [Point](../../com.aspose.drawing/point) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | La structure [Point](../../com.aspose.drawing/point) à tester. |

**Returns:**
boolean - vrai lorsque `point` est contenu dans cette [Region](../../com.aspose.drawing/region) ; sinon, faux.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Teste si la structure [Point](../../com.aspose.drawing/point) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region) lorsqu’elle est dessinée à l’aide du [Graphics](../../com.aspose.drawing/graphics) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | La structure [Point](../../com.aspose.drawing/point) à tester. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) qui représente un contexte graphique. |

**Returns:**
boolean - vrai lorsque `point` est contenu dans cette [Region](../../com.aspose.drawing/region) ; sinon, faux.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Teste si une partie du rectangle spécifié est contenue dans ce [Region](../../com.aspose.drawing/region).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| largeur | int | La largeur du rectangle à tester. |
| hauteur | int | La hauteur du rectangle à tester. |

**Returns:**
boolean - vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans cette [Region](../../com.aspose.drawing/region) ; sinon, faux.
### isVisible(Rectangle rect) {#isVisible-com.aspose.drawing.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Teste si une partie de la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La structure [Rectangle](../../com.aspose.drawing/rectangle) à tester. |

**Returns:**
boolean - Cette méthode renvoie vrai lorsque n'importe quelle partie de `rect` est contenue dans cette [Region](../../com.aspose.drawing/region) ; sinon, faux.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Teste si une partie du rectangle spécifié est contenue dans ce [Region](../../com.aspose.drawing/region) lorsqu’il est dessiné à l’aide du [Graphics](../../com.aspose.drawing/graphics) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| largeur | int | La largeur du rectangle à tester. |
| hauteur | int | La hauteur du rectangle à tester. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) qui représente un contexte graphique. |

**Returns:**
boolean - vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans cette [Region](../../com.aspose.drawing/region) ; sinon, faux.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Teste si une partie de la structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiée est contenue dans ce [Region](../../com.aspose.drawing/region) lorsqu’elle est dessinée à l’aide du [Graphics](../../com.aspose.drawing/graphics) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La structure [Rectangle](../../com.aspose.drawing/rectangle) à tester. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) qui représente un contexte graphique. |

**Returns:**
boolean - vrai lorsque n'importe quelle partie du `rect` est contenue dans cette [Region](../../com.aspose.drawing/region) ; sinon, faux.
