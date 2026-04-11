---
title: Region
second_title: Referencia de la API de Aspose.Drawing para Java
description: Describe el interior de una forma gráfica compuesta por rectángulos y rutas.
type: docs
weight: 40
url: /es/java/com.aspose.drawing/region/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Region implements System.IDisposable
```

Describe el interior de una forma gráfica compuesta de rectángulos y rutas. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Region()](#Region--) | Inicializa una nueva instancia de la clase [Region](../../com.aspose.drawing/region). |
| [Region(RectangleF rect)](#Region-com.aspose.drawing.RectangleF-) | Inicializa una nueva instancia de la clase [Region](../../com.aspose.drawing/region) a partir de la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada. |
| [Region(Rectangle rect)](#Region-com.aspose.drawing.Rectangle-) | Inicializa una nueva instancia de la clase [Region](../../com.aspose.drawing/region) a partir de la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada. |
| [Region(GraphicsPath path)](#Region-com.aspose.drawing.drawing2d.GraphicsPath-) | Inicializa una nueva instancia de la clase [Region](../../com.aspose.drawing/region) con el [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) especificado. |
| [Region(RegionData rgnData)](#Region-com.aspose.drawing.drawing2d.RegionData-) | Inicializa una nueva instancia de la clase [Region](../../com.aspose.drawing/region) a partir de los datos especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [dispose()](#dispose--) | Libera todos los recursos utilizados por este [Region](../../com.aspose.drawing/region). |
| [equals(Region region, Graphics g)](#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-) | Comprueba si el [Region](../../com.aspose.drawing/region) especificado es idéntico a este [Region](../../com.aspose.drawing/region) en la superficie de dibujo especificada. |
| [deepClone()](#deepClone--) | Crea una copia exacta de este [Region](../../com.aspose.drawing/region). |
| [makeInfinite()](#makeInfinite--) | Inicializa este objeto [Region](../../com.aspose.drawing/region) con un interior infinito. |
| [makeEmpty()](#makeEmpty--) | Inicializa este [Region](../../com.aspose.drawing/region) con un interior vacío. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Actualiza este [Region](../../com.aspose.drawing/region) a la intersección de sí mismo con la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada. |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Actualiza este [Region](../../com.aspose.drawing/region) a la intersección de sí mismo con la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.drawing.drawing2d.GraphicsPath-) | Actualiza este [Region](../../com.aspose.drawing/region) a la intersección de sí mismo con el [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) especificado. |
| [intersect(Region region)](#intersect-com.aspose.drawing.Region-) | Actualiza este [Region](../../com.aspose.drawing/region) a la intersección de sí mismo con el [Region](../../com.aspose.drawing/region) especificado. |
| [union(RectangleF rect)](#union-com.aspose.drawing.RectangleF-) | Actualiza este [Region](../../com.aspose.drawing/region) a la unión de sí mismo y la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada. |
| [union(Rectangle rect)](#union-com.aspose.drawing.Rectangle-) | Actualiza este [Region](../../com.aspose.drawing/region) a la unión de sí mismo y la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada. |
| [union(GraphicsPath path)](#union-com.aspose.drawing.drawing2d.GraphicsPath-) | Actualiza este [Region](../../com.aspose.drawing/region) a la unión de sí mismo y el [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) especificado. |
| [union(Region region)](#union-com.aspose.drawing.Region-) | Actualiza este [Region](../../com.aspose.drawing/region) a la unión de sí mismo y el [Region](../../com.aspose.drawing/region) especificado. |
| [getRegionData()](#getRegionData--) | Devuelve un [RegionData](../../com.aspose.drawing.drawing2d/regiondata) que representa la información que describe este [Region](../../com.aspose.drawing/region). |
| [xor(RectangleF rect)](#xor-com.aspose.drawing.RectangleF-) | Actualiza este [Region](../../com.aspose.drawing/region) a la unión menos la intersección de sí mismo con la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada. |
| [xor(Rectangle rect)](#xor-com.aspose.drawing.Rectangle-) | Actualiza este [Region](../../com.aspose.drawing/region) a la unión menos la intersección de sí mismo con la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada. |
| [xor(GraphicsPath path)](#xor-com.aspose.drawing.drawing2d.GraphicsPath-) | Actualiza este [Region](../../com.aspose.drawing/region) a la unión menos la intersección de sí mismo con el [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) especificado. |
| [xor(Region region)](#xor-com.aspose.drawing.Region-) | Actualiza este [Region](../../com.aspose.drawing/region) a la unión menos la intersección de sí mismo con el [Region](../../com.aspose.drawing/region) especificado. |
| [exclude(RectangleF rect)](#exclude-com.aspose.drawing.RectangleF-) | Actualiza este [Region](../../com.aspose.drawing/region) para contener solo la parte de su interior que no intersecta con la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada. |
| [exclude(Rectangle rect)](#exclude-com.aspose.drawing.Rectangle-) | Actualiza este [Region](../../com.aspose.drawing/region) para contener solo la parte de su interior que no intersecta con la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.drawing.drawing2d.GraphicsPath-) | Actualiza este [Region](../../com.aspose.drawing/region) para contener solo la parte de su interior que no intersecta con el [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) especificado. |
| [exclude(Region region)](#exclude-com.aspose.drawing.Region-) | Actualiza este [Region](../../com.aspose.drawing/region) para contener solo la parte de su interior que no intersecta con el [Region](../../com.aspose.drawing/region) especificado. |
| [complement(RectangleF rect)](#complement-com.aspose.drawing.RectangleF-) | Actualiza este [Region](../../com.aspose.drawing/region) para contener la parte de la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada que no intersecta con este [Region](../../com.aspose.drawing/region). |
| [complement(Rectangle rect)](#complement-com.aspose.drawing.Rectangle-) | Actualiza este [Region](../../com.aspose.drawing/region) para contener la parte de la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada que no intersecta con este [Region](../../com.aspose.drawing/region). |
| [complement(GraphicsPath path)](#complement-com.aspose.drawing.drawing2d.GraphicsPath-) | Actualiza este [Region](../../com.aspose.drawing/region) para contener la parte del [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) especificado que no intersecta con este [Region](../../com.aspose.drawing/region). |
| [complement(Region region)](#complement-com.aspose.drawing.Region-) | Actualiza este [Region](../../com.aspose.drawing/region) para que contenga la porción del [Region](../../com.aspose.drawing/region) especificado que no intersecta con este [Region](../../com.aspose.drawing/region). |
| [translate(float dx, float dy)](#translate-float-float-) | Desplaza las coordenadas de este [Region](../../com.aspose.drawing/region) por la cantidad especificada. |
| [translate(int dx, int dy)](#translate-int-int-) | Desplaza las coordenadas de este [Region](../../com.aspose.drawing/region) por la cantidad especificada. |
| [transform(Matrix matrix)](#transform-com.aspose.drawing.drawing2d.Matrix-) | Transforma este [Region](../../com.aspose.drawing/region) mediante la [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificada. |
| [getBounds(Graphics g)](#getBounds-com.aspose.drawing.Graphics-) | Obtiene una estructura [RectangleF](../../com.aspose.drawing/rectanglef) que representa un rectángulo que delimita este [Region](../../com.aspose.drawing/region) en la superficie de dibujo de un objeto [Graphics](../../com.aspose.drawing/graphics). |
| [getRegionScans(Matrix matrix)](#getRegionScans-com.aspose.drawing.drawing2d.Matrix-) | Devuelve una matriz de estructuras [RectangleF](../../com.aspose.drawing/rectanglef) que aproximan este [Region](../../com.aspose.drawing/region) después de aplicar la transformación de matriz especificada. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.drawing.Graphics-) | Comprueba si este [Region](../../com.aspose.drawing/region) tiene un interior vacío en la superficie de dibujo especificada. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.drawing.Graphics-) | Comprueba si este [Region](../../com.aspose.drawing/region) tiene un interior infinito en la superficie de dibujo especificada. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Comprueba si el punto especificado está contenido dentro de este [Region](../../com.aspose.drawing/region). |
| [isVisible(PointF point)](#isVisible-com.aspose.drawing.PointF-) | Comprueba si la estructura [PointF](../../com.aspose.drawing/pointf) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region). |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.drawing.Graphics-) | Comprueba si el punto especificado está contenido dentro de este [Region](../../com.aspose.drawing/region) cuando se dibuja usando el [Graphics](../../com.aspose.drawing/graphics) especificado. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-) | Comprueba si la estructura [PointF](../../com.aspose.drawing/pointf) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region) cuando se dibuja usando el [Graphics](../../com.aspose.drawing/graphics) especificado. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](../../com.aspose.drawing/region). |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.drawing.RectangleF-) | Comprueba si alguna porción de la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region). |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.drawing.Graphics-) | Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](../../com.aspose.drawing/region) cuando se dibuja usando el [Graphics](../../com.aspose.drawing/graphics) especificado. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-) | Comprueba si alguna porción de la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region) cuando se dibuja usando el [Graphics](../../com.aspose.drawing/graphics) especificado. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.drawing.Graphics-) | Comprueba si el punto especificado está contenido dentro de este objeto [Region](../../com.aspose.drawing/region) cuando se dibuja usando el objeto [Graphics](../../com.aspose.drawing/graphics) especificado. |
| [isVisible(Point point)](#isVisible-com.aspose.drawing.Point-) | Comprueba si la estructura [Point](../../com.aspose.drawing/point) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region). |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-) | Comprueba si la estructura [Point](../../com.aspose.drawing/point) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region) cuando se dibuja usando el [Graphics](../../com.aspose.drawing/graphics) especificado. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](../../com.aspose.drawing/region). |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.drawing.Rectangle-) | Comprueba si alguna porción de la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region). |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.drawing.Graphics-) | Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](../../com.aspose.drawing/region) cuando se dibuja usando el [Graphics](../../com.aspose.drawing/graphics) especificado. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-) | Comprueba si alguna porción de la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region) cuando se dibuja usando el [Graphics](../../com.aspose.drawing/graphics) especificado. |
### Region() {#Region--}
```
public Region()
```


Inicializa una nueva instancia de la clase [Region](../../com.aspose.drawing/region).

### Region(RectangleF rect) {#Region-com.aspose.drawing.RectangleF-}
```
public Region(RectangleF rect)
```


Inicializa una nueva instancia de la clase [Region](../../com.aspose.drawing/region) a partir de la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una estructura [RectangleF](../../com.aspose.drawing/rectanglef) que define el interior del nuevo [Region](../../com.aspose.drawing/region). |

### Region(Rectangle rect) {#Region-com.aspose.drawing.Rectangle-}
```
public Region(Rectangle rect)
```


Inicializa una nueva instancia de la clase [Region](../../com.aspose.drawing/region) a partir de la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Una estructura [Rectangle](../../com.aspose.drawing/rectangle) que define el interior del nuevo [Region](../../com.aspose.drawing/region). |

### Region(GraphicsPath path) {#Region-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Inicializa una nueva instancia de la clase [Region](../../com.aspose.drawing/region) con el [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) que define el nuevo [Region](../../com.aspose.drawing/region). |

### Region(RegionData rgnData) {#Region-com.aspose.drawing.drawing2d.RegionData-}
```
public Region(RegionData rgnData)
```


Inicializa una nueva instancia de la clase [Region](../../com.aspose.drawing/region) a partir de los datos especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgnData | [RegionData](../../com.aspose.drawing.drawing2d/regiondata) | Un [RegionData](../../com.aspose.drawing.drawing2d/regiondata) que define el interior del nuevo [Region](../../com.aspose.drawing/region). |

### dispose() {#dispose--}
```
public void dispose()
```


Libera todos los recursos utilizados por este [Region](../../com.aspose.drawing/region).

### equals(Region region, Graphics g) {#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-}
```
public boolean equals(Region region, Graphics g)
```


Comprueba si el [Region](../../com.aspose.drawing/region) especificado es idéntico a este [Region](../../com.aspose.drawing/region) en la superficie de dibujo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | El [Region](../../com.aspose.drawing/region) a probar. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) que representa una superficie de dibujo. |

**Returns:**
boolean - verdadero si el interior de la región es idéntico al interior de esta región cuando se aplica la transformación asociada con el parámetro `g`; de lo contrario, falso.
### deepClone() {#deepClone--}
```
public Region deepClone()
```


Crea una copia exacta de este [Region](../../com.aspose.drawing/region).

**Returns:**
[Region](../../com.aspose.drawing/region) - The [Region](../../com.aspose.drawing/region) that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Inicializa este objeto [Region](../../com.aspose.drawing/region) con un interior infinito.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Inicializa este [Region](../../com.aspose.drawing/region) con un interior vacío.

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public void intersect(RectangleF rect)
```


Actualiza este [Region](../../com.aspose.drawing/region) a la intersección de sí mismo con la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La estructura [RectangleF](../../com.aspose.drawing/rectanglef) para intersectar con esta [Region](../../com.aspose.drawing/region). |

### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public void intersect(Rectangle rect)
```


Actualiza este [Region](../../com.aspose.drawing/region) a la intersección de sí mismo con la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La estructura [Rectangle](../../com.aspose.drawing/rectangle) para intersectar con esta [Region](../../com.aspose.drawing/region). |

### intersect(GraphicsPath path) {#intersect-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Actualiza este [Region](../../com.aspose.drawing/region) a la intersección de sí mismo con el [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | El [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) para intersectar con esta [Region](../../com.aspose.drawing/region). |

### intersect(Region region) {#intersect-com.aspose.drawing.Region-}
```
public void intersect(Region region)
```


Actualiza este [Region](../../com.aspose.drawing/region) a la intersección de sí mismo con el [Region](../../com.aspose.drawing/region) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | La [Region](../../com.aspose.drawing/region) para intersectar con esta [Region](../../com.aspose.drawing/region). |

### union(RectangleF rect) {#union-com.aspose.drawing.RectangleF-}
```
public void union(RectangleF rect)
```


Actualiza este [Region](../../com.aspose.drawing/region) a la unión de sí mismo y la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La estructura [RectangleF](../../com.aspose.drawing/rectanglef) para unir con esta [Region](../../com.aspose.drawing/region). |

--------------------

La unión deja la región infinita como infinita. |

### union(Rectangle rect) {#union-com.aspose.drawing.Rectangle-}
```
public void union(Rectangle rect)
```


Actualiza este [Region](../../com.aspose.drawing/region) a la unión de sí mismo y la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | rect | [Rectangle](../../com.aspose.drawing/rectangle) | La estructura [Rectangle](../../com.aspose.drawing/rectangle) para unir con esta [Region](../../com.aspose.drawing/region). |

--------------------

La unión deja la región infinita como infinita. |

### union(GraphicsPath path) {#union-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Actualiza este [Region](../../com.aspose.drawing/region) a la unión de sí mismo y el [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | El [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) para unir con esta [Region](../../com.aspose.drawing/region). |

--------------------

La unión deja la región infinita como infinita. |

### union(Region region) {#union-com.aspose.drawing.Region-}
```
public void union(Region region)
```


Actualiza este [Region](../../com.aspose.drawing/region) a la unión de sí mismo y el [Region](../../com.aspose.drawing/region) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | region | [Region](../../com.aspose.drawing/region) | La [Region](../../com.aspose.drawing/region) para unir con esta [Region](../../com.aspose.drawing/region). |

--------------------

La unión deja la región infinita como infinita. |

### getRegionData() {#getRegionData--}
```
public RegionData getRegionData()
```


Devuelve un [RegionData](../../com.aspose.drawing.drawing2d/regiondata) que representa la información que describe este [Region](../../com.aspose.drawing/region).

**Returns:**
[RegionData](../../com.aspose.drawing.drawing2d/regiondata) - A [RegionData](../../com.aspose.drawing.drawing2d/regiondata) that represents the information that describes this [Region](../../com.aspose.drawing/region).
### xor(RectangleF rect) {#xor-com.aspose.drawing.RectangleF-}
```
public void xor(RectangleF rect)
```


Actualiza este [Region](../../com.aspose.drawing/region) a la unión menos la intersección de sí mismo con la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La estructura [RectangleF](../../com.aspose.drawing/rectanglef) para `M:Region.Xor(Drawing2D.GraphicsPath)` con esta [Region](../../com.aspose.drawing/region). |

### xor(Rectangle rect) {#xor-com.aspose.drawing.Rectangle-}
```
public void xor(Rectangle rect)
```


Actualiza este [Region](../../com.aspose.drawing/region) a la unión menos la intersección de sí mismo con la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La estructura [Rectangle](../../com.aspose.drawing/rectangle) para `M:Region.Xor(Rectangle)` con esta [Region](../../com.aspose.drawing/region). |

### xor(GraphicsPath path) {#xor-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Actualiza este [Region](../../com.aspose.drawing/region) a la unión menos la intersección de sí mismo con el [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | El [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) para `M:Region.Xor(GraphicsPath)` con esta [Region](../../com.aspose.drawing/region). |

### xor(Region region) {#xor-com.aspose.drawing.Region-}
```
public void xor(Region region)
```


Actualiza este [Region](../../com.aspose.drawing/region) a la unión menos la intersección de sí mismo con el [Region](../../com.aspose.drawing/region) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | La [Region](../../com.aspose.drawing/region) para `M:Region.Xor(Region)` con esta [Region](../../com.aspose.drawing/region). |

### exclude(RectangleF rect) {#exclude-com.aspose.drawing.RectangleF-}
```
public void exclude(RectangleF rect)
```


Actualiza este [Region](../../com.aspose.drawing/region) para contener solo la parte de su interior que no intersecta con la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La estructura [RectangleF](../../com.aspose.drawing/rectanglef) para excluir de esta [Region](../../com.aspose.drawing/region). |

### exclude(Rectangle rect) {#exclude-com.aspose.drawing.Rectangle-}
```
public void exclude(Rectangle rect)
```


Actualiza este [Region](../../com.aspose.drawing/region) para contener solo la parte de su interior que no intersecta con la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La estructura [Rectangle](../../com.aspose.drawing/rectangle) para excluir de esta [Region](../../com.aspose.drawing/region). |

### exclude(GraphicsPath path) {#exclude-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Actualiza este [Region](../../com.aspose.drawing/region) para contener solo la parte de su interior que no intersecta con el [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | El [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) para excluir de esta [Region](../../com.aspose.drawing/region). |

### exclude(Region region) {#exclude-com.aspose.drawing.Region-}
```
public void exclude(Region region)
```


Actualiza este [Region](../../com.aspose.drawing/region) para contener solo la parte de su interior que no intersecta con el [Region](../../com.aspose.drawing/region) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | La [Region](../../com.aspose.drawing/region) para excluir de esta [Region](../../com.aspose.drawing/region). |

### complement(RectangleF rect) {#complement-com.aspose.drawing.RectangleF-}
```
public void complement(RectangleF rect)
```


Actualiza este [Region](../../com.aspose.drawing/region) para contener la parte de la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada que no intersecta con este [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La estructura [RectangleF](../../com.aspose.drawing/rectanglef) para complementar esta [Region](../../com.aspose.drawing/region). |

### complement(Rectangle rect) {#complement-com.aspose.drawing.Rectangle-}
```
public void complement(Rectangle rect)
```


Actualiza este [Region](../../com.aspose.drawing/region) para contener la parte de la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada que no intersecta con este [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La estructura [Rectangle](../../com.aspose.drawing/rectangle) para complementar esta [Region](../../com.aspose.drawing/region). |

### complement(GraphicsPath path) {#complement-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Actualiza este [Region](../../com.aspose.drawing/region) para contener la parte del [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) especificado que no intersecta con este [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | El [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) para complementar esta [Region](../../com.aspose.drawing/region). |

### complement(Region region) {#complement-com.aspose.drawing.Region-}
```
public void complement(Region region)
```


Actualiza este [Region](../../com.aspose.drawing/region) para que contenga la porción del [Region](../../com.aspose.drawing/region) especificado que no intersecta con este [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | El objeto [Region](../../com.aspose.drawing/region) para complementar este objeto [Region](../../com.aspose.drawing/region). |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Desplaza las coordenadas de este [Region](../../com.aspose.drawing/region) por la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | La cantidad para desplazar horizontalmente esta [Region](../../com.aspose.drawing/region). |
| dy | float | La cantidad para desplazar verticalmente esta [Region](../../com.aspose.drawing/region). |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Desplaza las coordenadas de este [Region](../../com.aspose.drawing/region) por la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | int | La cantidad para desplazar horizontalmente este [Region](../../com.aspose.drawing/region) |
| dy | int | La cantidad para desplazar verticalmente esta [Region](../../com.aspose.drawing/region). |

### transform(Matrix matrix) {#transform-com.aspose.drawing.drawing2d.Matrix-}
```
public void transform(Matrix matrix)
```


Transforma este [Region](../../com.aspose.drawing/region) mediante la [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | La [Matrix](../../com.aspose.drawing.drawing2d/matrix) mediante la cual transformar este [Region](../../com.aspose.drawing/region). |

### getBounds(Graphics g) {#getBounds-com.aspose.drawing.Graphics-}
```
public RectangleF getBounds(Graphics g)
```


Obtiene una estructura [RectangleF](../../com.aspose.drawing/rectanglef) que representa un rectángulo que delimita este [Region](../../com.aspose.drawing/region) en la superficie de dibujo de un objeto [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | El [Graphics](../../com.aspose.drawing/graphics) en el que se dibuja este [Region](../../com.aspose.drawing/region). |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents the bounding rectangle for this [Region](../../com.aspose.drawing/region) on the specified drawing surface.
### getRegionScans(Matrix matrix) {#getRegionScans-com.aspose.drawing.drawing2d.Matrix-}
```
public RectangleF[] getRegionScans(Matrix matrix)
```


Devuelve una matriz de estructuras [RectangleF](../../com.aspose.drawing/rectanglef) que aproximan este [Region](../../com.aspose.drawing/region) después de aplicar la transformación de matriz especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Una [Matrix](../../com.aspose.drawing.drawing2d/matrix) que representa una transformación geométrica para aplicar a la región. |

**Returns:**
com.aspose.drawing.RectangleF[] - Una matriz de estructuras [RectangleF](../../com.aspose.drawing/rectanglef) que aproximan este [Region](../../com.aspose.drawing/region) después de aplicar la transformación de matriz especificada.
### isEmpty(Graphics g) {#isEmpty-com.aspose.drawing.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Comprueba si este [Region](../../com.aspose.drawing/region) tiene un interior vacío en la superficie de dibujo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) que representa una superficie de dibujo. |

**Returns:**
boolean - verdadero si el interior de este [Region](../../com.aspose.drawing/region) está vacío cuando se aplica la transformación asociada con `g`; de lo contrario, falso.
### isInfinite(Graphics g) {#isInfinite-com.aspose.drawing.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Comprueba si este [Region](../../com.aspose.drawing/region) tiene un interior infinito en la superficie de dibujo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) que representa una superficie de dibujo. |

**Returns:**
boolean - verdadero si el interior de este [Region](../../com.aspose.drawing/region) es infinito cuando se aplica la transformación asociada con `g`; de lo contrario, falso.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Comprueba si el punto especificado está contenido dentro de este [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns:**
boolean - verdadero cuando el punto especificado está contenido dentro de este [Region](../../com.aspose.drawing/region); de lo contrario, falso.
### isVisible(PointF point) {#isVisible-com.aspose.drawing.PointF-}
```
public boolean isVisible(PointF point)
```


Comprueba si la estructura [PointF](../../com.aspose.drawing/pointf) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | La estructura [PointF](../../com.aspose.drawing/pointf) a probar. |

**Returns:**
boolean - verdadero cuando `point` está contenido dentro de este [Region](../../com.aspose.drawing/region); de lo contrario, falso.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Comprueba si el punto especificado está contenido dentro de este [Region](../../com.aspose.drawing/region) cuando se dibuja usando el [Graphics](../../com.aspose.drawing/graphics) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando el punto especificado está contenido dentro de este [Region](../../com.aspose.drawing/region); de lo contrario, falso.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Comprueba si la estructura [PointF](../../com.aspose.drawing/pointf) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region) cuando se dibuja usando el [Graphics](../../com.aspose.drawing/graphics) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | La estructura [PointF](../../com.aspose.drawing/pointf) a probar. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando `point` está contenido dentro de este [Region](../../com.aspose.drawing/region); de lo contrario, falso.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| ancho | float | El ancho del rectángulo a probar. |
| alto | float | La altura del rectángulo a probar. |

**Returns:**
boolean - verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este objeto [Region](../../com.aspose.drawing/region); de lo contrario, falso.
### isVisible(RectangleF rect) {#isVisible-com.aspose.drawing.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Comprueba si alguna porción de la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La estructura [RectangleF](../../com.aspose.drawing/rectanglef) a probar. |

**Returns:**
boolean - verdadero cuando cualquier parte de `rect` está contenida dentro de este [Region](../../com.aspose.drawing/region); de lo contrario, falso.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](../../com.aspose.drawing/region) cuando se dibuja usando el [Graphics](../../com.aspose.drawing/graphics) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| ancho | float | El ancho del rectángulo a probar. |
| alto | float | La altura del rectángulo a probar. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este [Region](../../com.aspose.drawing/region); de lo contrario, falso.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Comprueba si alguna porción de la estructura [RectangleF](../../com.aspose.drawing/rectanglef) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region) cuando se dibuja usando el [Graphics](../../com.aspose.drawing/graphics) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | La estructura [RectangleF](../../com.aspose.drawing/rectanglef) a probar. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando `rect` está contenido dentro de este [Region](../../com.aspose.drawing/region); de lo contrario, falso.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Comprueba si el punto especificado está contenido dentro de este objeto [Region](../../com.aspose.drawing/region) cuando se dibuja usando el objeto [Graphics](../../com.aspose.drawing/graphics) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando el punto especificado está contenido dentro de este [Region](../../com.aspose.drawing/region); de lo contrario, falso.
### isVisible(Point point) {#isVisible-com.aspose.drawing.Point-}
```
public boolean isVisible(Point point)
```


Comprueba si la estructura [Point](../../com.aspose.drawing/point) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | La estructura [Point](../../com.aspose.drawing/point) a probar. |

**Returns:**
boolean - verdadero cuando `point` está contenido dentro de este [Region](../../com.aspose.drawing/region); de lo contrario, falso.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Comprueba si la estructura [Point](../../com.aspose.drawing/point) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region) cuando se dibuja usando el [Graphics](../../com.aspose.drawing/graphics) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | La estructura [Point](../../com.aspose.drawing/point) a probar. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando `point` está contenido dentro de este [Region](../../com.aspose.drawing/region); de lo contrario, falso.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| ancho | int | El ancho del rectángulo a probar. |
| alto | int | La altura del rectángulo a probar. |

**Returns:**
boolean - verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este [Region](../../com.aspose.drawing/region); de lo contrario, falso.
### isVisible(Rectangle rect) {#isVisible-com.aspose.drawing.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Comprueba si alguna porción de la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La estructura [Rectangle](../../com.aspose.drawing/rectangle) a probar. |

**Returns:**
boolean - Este método devuelve verdadero cuando cualquier parte de `rect` está contenida dentro de este [Region](../../com.aspose.drawing/region); de lo contrario, falso.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](../../com.aspose.drawing/region) cuando se dibuja usando el [Graphics](../../com.aspose.drawing/graphics) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| ancho | int | El ancho del rectángulo a probar. |
| alto | int | La altura del rectángulo a probar. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este [Region](../../com.aspose.drawing/region); de lo contrario, falso.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Comprueba si alguna porción de la estructura [Rectangle](../../com.aspose.drawing/rectangle) especificada está contenida dentro de este [Region](../../com.aspose.drawing/region) cuando se dibuja usando el [Graphics](../../com.aspose.drawing/graphics) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | La estructura [Rectangle](../../com.aspose.drawing/rectangle) a probar. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando cualquier parte del `rect` está contenida dentro de este [Region](../../com.aspose.drawing/region); de lo contrario, falso.
