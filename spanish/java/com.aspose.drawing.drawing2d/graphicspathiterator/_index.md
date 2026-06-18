---
title: GraphicsPathIterator
second_title: Referencia de la API de Aspose.Drawing para Java
description: Proporciona la capacidad de iterar a través de subrutas en un  y probar los tipos de formas contenidas en cada subruta.
type: docs
weight: 24
url: /es/java/com.aspose.drawing.drawing2d/graphicspathiterator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class GraphicsPathIterator implements System.IDisposable
```

Proporciona la capacidad de iterar a través de subrutas en un [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) y probar los tipos de formas contenidas en cada subruta. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GraphicsPathIterator(GraphicsPath path)](#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-) | Inicializa una nueva instancia de la clase [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCount()](#getCount--) | Obtiene el número de puntos en la ruta. |
| [getSubpathCount()](#getSubpathCount--) | Obtiene el número de subrutas en la ruta. |
| [dispose()](#dispose--) | Realiza tareas definidas por la aplicación asociadas con la liberación, el desalojo o el restablecimiento de recursos no administrados. |
| [copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)](#copyData-com.aspose.drawing.PointF-----byte-----int-int-) | Copia las matrices de la propiedad GraphicsPath.PathPoints y de la propiedad GraphicsPath.PathTypes del [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) asociado en las dos matrices especificadas. |
| [enumerate(PointF[][] points, byte[][] types)](#enumerate-com.aspose.drawing.PointF-----byte-----) | Copia las matrices de la propiedad GraphicsPath.PathPoints y de la propiedad GraphicsPath.PathTypes del [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) asociado en las dos matrices especificadas. |
| [hasCurve()](#hasCurve--) | Indica si la ruta asociada con este [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) contiene una curva. |
| [nextMarker(int[] startIndex, int[] endIndex)](#nextMarker-int---int---) | Incrementa el [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) al siguiente marcador en la ruta y devuelve los índices de inicio y fin mediante los parámetros [out]. |
| [nextMarker(GraphicsPath path)](#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-) | Este objeto [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) tiene un objeto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) asociado. |
| [nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)](#nextPathType-byte---int---int---) | Obtiene el índice inicial y el índice final del siguiente grupo de puntos de datos que todos tienen el mismo tipo. |
| [nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)](#nextSubpath-int---int---boolean---) | Mueve el [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) a la siguiente subruta en la ruta. |
| [nextSubpath(GraphicsPath path, boolean[] isClosed)](#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---) | Obtiene la siguiente figura (subruta) de la ruta asociada de este [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
| [rewind()](#rewind--) | Rebobina este [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) al comienzo de su ruta asociada. |
### GraphicsPathIterator(GraphicsPath path) {#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public GraphicsPathIterator(GraphicsPath path)
```


Inicializa una nueva instancia de la clase [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | El objeto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) para el cual se debe inicializar esta clase auxiliar. |

### getCount() {#getCount--}
```
public int getCount()
```


Obtiene el número de puntos en la ruta.

**Returns:**
int - el número de puntos en la ruta.
### getSubpathCount() {#getSubpathCount--}
```
public int getSubpathCount()
```


Obtiene el número de subrutas en la ruta.

**Returns:**
int - el número de subrutas en la ruta.
### dispose() {#dispose--}
```
public void dispose()
```


Realiza tareas definidas por la aplicación asociadas con la liberación, el desalojo o el restablecimiento de recursos no administrados.

### copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex) {#copyData-com.aspose.drawing.PointF-----byte-----int-int-}
```
public int copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)
```


Copia las matrices de la propiedad GraphicsPath.PathPoints y de la propiedad GraphicsPath.PathTypes del [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) asociado en las dos matrices especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Al regresar, contiene una matriz de estructuras System.Drawing.PointF que representa los puntos en la ruta. |
| tipos | byte[][] | Al regresar, contiene una matriz de bytes que representa los tipos de puntos en la ruta. |
| startIndex | int | Especifica el índice inicial de las matrices. |
| endIndex | int | Especifica el índice final de las matrices. |

**Returns:**
int - El número de puntos copiados.
### enumerate(PointF[][] points, byte[][] types) {#enumerate-com.aspose.drawing.PointF-----byte-----}
```
public int enumerate(PointF[][] points, byte[][] types)
```


Copia las matrices de la propiedad GraphicsPath.PathPoints y de la propiedad GraphicsPath.PathTypes del [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) asociado en las dos matrices especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Al regresar, contiene una matriz de estructuras System.Drawing.PointF que representa los puntos en la ruta. |
| tipos | byte[][] | Al regresar, contiene una matriz de bytes que representa los tipos de puntos en la ruta. |

**Returns:**
int - El número de puntos copiados.
### hasCurve() {#hasCurve--}
```
public boolean hasCurve()
```


Indica si la ruta asociada con este [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) contiene una curva.

**Returns:**
boolean - Este método devuelve true si la subruta actual contiene una curva; de lo contrario, false.
### nextMarker(int[] startIndex, int[] endIndex) {#nextMarker-int---int---}
```
public int nextMarker(int[] startIndex, int[] endIndex)
```


Incrementa el [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) al siguiente marcador en la ruta y devuelve los índices de inicio y fin mediante los parámetros [out].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int[] | [out] La referencia entera suministrada a este parámetro recibe el índice del punto que inicia una subruta. |
| endIndex | int[] | [out] La referencia entera suministrada a este parámetro recibe el índice del punto que finaliza la subruta a la que apunta startIndex. |

**Returns:**
int - El número de puntos entre este marcador y el siguiente.
### nextMarker(GraphicsPath path) {#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public int nextMarker(GraphicsPath path)
```


Este objeto [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) tiene un objeto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) asociado. Este método incrementa el [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) asociado al siguiente marcador en su ruta y copia todos los puntos contenidos entre el marcador actual y el siguiente marcador (o el final de la ruta) a un segundo objeto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) pasado como parámetro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | El objeto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) al que se copiarán los puntos. |

**Returns:**
int - El número de puntos entre este marcador y el siguiente.
### nextPathType(byte[] pathType, int[] startIndex, int[] endIndex) {#nextPathType-byte---int---int---}
```
public int nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)
```


Obtiene el índice inicial y el índice final del siguiente grupo de puntos de datos que todos tienen el mismo tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pathType | byte[] | [out] Recibe el tipo de punto compartido por todos los puntos del grupo. Los tipos posibles pueden obtenerse de la enumeración [PathPointType](../../com.aspose.drawing.drawing2d/pathpointtype). |
| startIndex | int[] | [out] Recibe el índice inicial del grupo de puntos. |
| endIndex | int[] | [out] Recibe el índice final del grupo de puntos. |

**Returns:**
int - Este método devuelve el número de puntos de datos en el grupo. Si no hay más grupos en la ruta, este método devuelve 0.
### nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed) {#nextSubpath-int---int---boolean---}
```
public int nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)
```


Mueve el [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) a la siguiente subruta en la ruta. El índice de inicio y el índice de fin de la siguiente subruta están contenidos en los parámetros [out].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int[] | [out] Recibe el índice de inicio de la siguiente subruta. |
| endIndex | int[] | [out] Recibe el índice de fin de la siguiente subruta. |
| isClosed | boolean[] | [out] Indica si la subruta está cerrada. |

**Returns:**
int - El número de puntos de datos en la figura (subruta) recuperada. Si no hay más figuras que recuperar, se devuelve cero.
### nextSubpath(GraphicsPath path, boolean[] isClosed) {#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---}
```
public int nextSubpath(GraphicsPath path, boolean[] isClosed)
```


Obtiene la siguiente figura (subruta) de la ruta asociada de este [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) que debe tener sus puntos de datos configurados para coincidir con los puntos de datos de la figura (subruta) recuperada para este iterador. |
| isClosed | boolean[] | [out] Indica si la subruta actual está cerrada. Es true si la figura está cerrada, de lo contrario es false. |

**Returns:**
int - El número de puntos de datos en la figura (subruta) recuperada. Si no hay más figuras que recuperar, se devuelve cero.
### rewind() {#rewind--}
```
public void rewind()
```


Rebobina este [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) al comienzo de su ruta asociada.

