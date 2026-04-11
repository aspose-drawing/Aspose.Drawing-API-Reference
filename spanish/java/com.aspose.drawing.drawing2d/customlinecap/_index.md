---
title: CustomLineCap
second_title: Referencia de la API de Aspose.Drawing para Java
description: Encapsula una tapa de línea personalizada definida por el usuario.
type: docs
weight: 17
url: /es/java/com.aspose.drawing.drawing2d/customlinecap/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class CustomLineCap implements System.IDisposable
```

Encapsula una tapa de línea personalizada definida por el usuario.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-) | Inicializa una nueva instancia de la clase [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) con el contorno y relleno especificados. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-) | Inicializa una nueva instancia de la clase [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) a partir de la enumeración [LineCap](../../com.aspose.drawing.drawing2d/linecap) existente especificada, con el contorno y relleno especificados. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-) | Inicializa una nueva instancia de la clase [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) a partir de la enumeración [LineCap](../../com.aspose.drawing.drawing2d/linecap) existente especificada, con el contorno, relleno y inset especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getStrokeJoin()](#getStrokeJoin--) | Obtiene o establece la enumeración [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) que determina cómo se unen las líneas que componen este objeto [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Obtiene o establece la enumeración [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) que determina cómo se unen las líneas que componen este objeto [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [getBaseCap()](#getBaseCap--) | Obtiene o establece la enumeración [LineCap](../../com.aspose.drawing.drawing2d/linecap) en la que se basa este [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setBaseCap(int value)](#setBaseCap-int-) | Obtiene o establece la enumeración [LineCap](../../com.aspose.drawing.drawing2d/linecap) en la que se basa este [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [getBaseInset()](#getBaseInset--) | Obtiene o establece la distancia entre la tapa y la línea. |
| [setBaseInset(float value)](#setBaseInset-float-) | Obtiene o establece la distancia entre la tapa y la línea. |
| [getWidthScale()](#getWidthScale--) | Obtiene o establece la cantidad por la que escalar este objeto de clase [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) con respecto al ancho del objeto [Pen](../../com.aspose.drawing/pen). |
| [setWidthScale(float value)](#setWidthScale-float-) | Obtiene o establece la cantidad por la que escalar este objeto de clase [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) con respecto al ancho del objeto [Pen](../../com.aspose.drawing/pen). |
| [dispose()](#dispose--) | Libera todos los recursos utilizados por este objeto [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [deepClone()](#deepClone--) | Crea una copia exacta de este [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Establece los caps usados para iniciar y terminar líneas que forman este custom cap. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Obtiene los caps usados para iniciar y terminar líneas que forman este custom cap. |
| [getFillPath()](#getFillPath--) |  |
| [getStrokePath()](#getStrokePath--) | Obtiene el objeto que define el contorno del custom cap. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Inicializa una nueva instancia de la clase [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) con el contorno y relleno especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un objeto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) que define el relleno del custom cap. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un objeto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) que define el contorno del custom cap. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Inicializa una nueva instancia de la clase [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) a partir de la enumeración [LineCap](../../com.aspose.drawing.drawing2d/linecap) existente especificada, con el contorno y relleno especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un objeto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) que define el relleno del custom cap. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un objeto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) que define el contorno del custom cap. |
| baseCap | int | El line cap a partir del cual crear el custom cap. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Inicializa una nueva instancia de la clase [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) a partir de la enumeración [LineCap](../../com.aspose.drawing.drawing2d/linecap) existente especificada, con el contorno, relleno y inset especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un objeto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) que define el relleno del custom cap. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un objeto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) que define el contorno del custom cap. |
| baseCap | int | El line cap a partir del cual crear el custom cap. |
| baseInset | float | La distancia entre el cap y la línea. |

### getStrokeJoin() {#getStrokeJoin--}
```
public final int getStrokeJoin()
```


Obtiene o establece la enumeración [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) que determina cómo se unen las líneas que componen este objeto [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public final void setStrokeJoin(int value)
```


Obtiene o establece la enumeración [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) que determina cómo se unen las líneas que componen este objeto [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public final int getBaseCap()
```


Obtiene o establece la enumeración [LineCap](../../com.aspose.drawing.drawing2d/linecap) en la que se basa este [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public final void setBaseCap(int value)
```


Obtiene o establece la enumeración [LineCap](../../com.aspose.drawing.drawing2d/linecap) en la que se basa este [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public final float getBaseInset()
```


Obtiene o establece la distancia entre la tapa y la línea.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public final void setBaseInset(float value)
```


Obtiene o establece la distancia entre la tapa y la línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public final float getWidthScale()
```


Obtiene o establece la cantidad por la que escalar este objeto de clase [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) con respecto al ancho del objeto [Pen](../../com.aspose.drawing/pen).

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public final void setWidthScale(float value)
```


Obtiene o establece la cantidad por la que escalar este objeto de clase [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) con respecto al ancho del objeto [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### dispose() {#dispose--}
```
public final void dispose()
```


Libera todos los recursos utilizados por este objeto [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Crea una copia exacta de este [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
java.lang.Object - El [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) que este método crea, convertido a objeto.
### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public final void setStrokeCaps(int startCap, int endCap)
```


Establece los caps usados para iniciar y terminar líneas que forman este custom cap.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startCap | int | La enumeración [LineCap](../../com.aspose.drawing.drawing2d/linecap) usada al inicio de una línea dentro de este cap. |
| endCap | int | La enumeración [LineCap](../../com.aspose.drawing.drawing2d/linecap) usada al final de una línea dentro de este cap. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public final void getStrokeCaps(int[] startCap, int[] endCap)
```


Obtiene los caps usados para iniciar y terminar líneas que forman este custom cap.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startCap | int[] | La enumeración [LineCap](../../com.aspose.drawing.drawing2d/linecap) usada al inicio de una línea dentro de este cap. |
| endCap | int[] | La enumeración [LineCap](../../com.aspose.drawing.drawing2d/linecap) usada al final de una línea dentro de este cap. |

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


Obtiene el objeto que define el contorno del custom cap.

**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) - The object that defines the outline of the custom cap.
