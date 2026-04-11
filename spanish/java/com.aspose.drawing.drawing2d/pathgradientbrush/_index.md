---
title: PathGradientBrush
second_title: Referencia de la API de Aspose.Drawing para Java
description: Encapsula un objeto que llena el interior de un objeto con un degradado.
type: docs
weight: 36
url: /es/java/com.aspose.drawing.drawing2d/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class PathGradientBrush extends Brush
```

Encapsula un objeto [Brush](../../com.aspose.drawing/brush) que llena el interior de un objeto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) con un degradado. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.drawing.PointF---) | Inicializa una nueva instancia de la clase [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con los puntos especificados. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.PointF---int-) | Inicializa una nueva instancia de la clase [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con los puntos especificados y el modo de ajuste. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.drawing.Point---) | Inicializa una nueva instancia de la clase [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con los puntos especificados. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.Point---int-) | Inicializa una nueva instancia de la clase [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con los puntos especificados y el modo de ajuste. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-) | Inicializa una nueva instancia de la clase [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con la ruta especificada. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCenterColor()](#getCenterColor--) | Obtiene o establece el color en el centro del degradado de la ruta. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.drawing.Color-) | Obtiene o establece el color en el centro del degradado de la ruta. |
| [getSurroundColors()](#getSurroundColors--) | Obtiene o establece una matriz de colores que corresponden a los puntos en la ruta que este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) rellena. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.drawing.Color---) | Obtiene o establece una matriz de colores que corresponden a los puntos en la ruta que este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) rellena. |
| [getCenterPoint()](#getCenterPoint--) | Obtiene o establece el punto central del degradado de la ruta. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.drawing.PointF-) | Obtiene o establece el punto central del degradado de la ruta. |
| [getRectangle()](#getRectangle--) | Obtiene un rectángulo delimitador para este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getBlend()](#getBlend--) | Obtiene o establece un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) que especifica posiciones y factores que definen una caída personalizada para el degradado. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Obtiene o establece un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) que especifica posiciones y factores que definen una caída personalizada para el degradado. |
| [getInterpolationColors()](#getInterpolationColors--) | Obtiene o establece un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) que define un degradado lineal multicolor. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Obtiene o establece un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) que define un degradado lineal multicolor. |
| [getTransform()](#getTransform--) | Obtiene o establece una copia de la [Matrix](../../com.aspose.drawing.drawing2d/matrix) que define una transformación geométrica local para este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Obtiene o establece una copia de la [Matrix](../../com.aspose.drawing.drawing2d/matrix) que define una transformación geométrica local para este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getFocusScales()](#getFocusScales--) | Obtiene o establece el punto focal para la caída del degradado. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.drawing.PointF-) | Obtiene o establece el punto focal para la caída del degradado. |
| [getWrapMode()](#getWrapMode--) | Obtiene o establece un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) que indica el modo de ajuste para este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtiene o establece un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) que indica el modo de ajuste para este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [deepClone()](#deepClone--) | Crea una copia exacta de este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crea un pincel de degradado que cambia de color comenzando desde el centro de la ruta hacia el borde de la ruta. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crea un pincel de degradado que cambia de color comenzando desde el centro de la ruta hacia el borde de la ruta. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crea un degradado con un color central y una caída lineal hacia un color circundante. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crea un degradado con un color central y una disminución lineal hacia cada color circundante. |
| [resetTransform()](#resetTransform--) | Restablece la propiedad `PathGradientBrush.Transform` a la identidad. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Actualiza la matriz de transformación del pincel con el producto de la matriz de transformación del pincel multiplicada por otra matriz. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Actualiza la matriz de transformación del pincel con el producto de la matriz de transformación del pincel multiplicada por otra matriz. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Aplica la traslación especificada a la transformación geométrica local. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Aplica la traslación especificada a la transformación geométrica local en el orden especificado. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Escala la transformación geométrica local por las cantidades especificadas. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Escala la transformación geométrica local por las cantidades especificadas en el orden indicado. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rota la transformación geométrica local por la cantidad especificada. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rota la transformación geométrica local por la cantidad especificada en el orden indicado. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.drawing.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Inicializa una nueva instancia de la clase [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con los puntos especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Una matriz de estructuras [PointF](../../com.aspose.drawing/pointf) que representa los puntos que forman los vértices de la ruta. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Inicializa una nueva instancia de la clase [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con los puntos especificados y el modo de ajuste.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Una matriz de estructuras [PointF](../../com.aspose.drawing/pointf) que representa los puntos que forman los vértices de la ruta. |
| wrapMode | int | Un `WrapMode`([.getWrapMode](../../null/\\#getWrapMode)/[.setWrapMode(int)](../../null/\\#setWrapMode-int-)) que especifica cómo se repiten los rellenos dibujados con este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.drawing.Point---}
```
public PathGradientBrush(Point[] points)
```


Inicializa una nueva instancia de la clase [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con los puntos especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Una matriz de estructuras [Point](../../com.aspose.drawing/point) que representa los puntos que forman los vértices de la ruta. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Inicializa una nueva instancia de la clase [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con los puntos especificados y el modo de ajuste.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Una matriz de estructuras [Point](../../com.aspose.drawing/point) que representa los puntos que forman los vértices de la ruta. |
| wrapMode | int | Un `WrapMode`([.getWrapMode](../../null/\\#getWrapMode)/[.setWrapMode(int)](../../null/\\#setWrapMode-int-)) que especifica cómo se repiten los rellenos dibujados con este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Inicializa una nueva instancia de la clase [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con la ruta especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | El [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) que define el área rellenada por este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Obtiene o establece el color en el centro del degradado de la ruta.

**Returns:**
[Color](../../com.aspose.drawing/color)
### setCenterColor(Color value) {#setCenterColor-com.aspose.drawing.Color-}
```
public void setCenterColor(Color value)
```


Obtiene o establece el color en el centro del degradado de la ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Obtiene o establece una matriz de colores que corresponden a los puntos en la ruta que este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) rellena.

**Returns:**
com.aspose.drawing.Color[]
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.drawing.Color---}
```
public void setSurroundColors(Color[] value)
```


Obtiene o establece una matriz de colores que corresponden a los puntos en la ruta que este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) rellena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Obtiene o establece el punto central del degradado de la ruta.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.drawing.PointF-}
```
public void setCenterPoint(PointF value)
```


Obtiene o establece el punto central del degradado de la ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Obtiene un rectángulo delimitador para este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Obtiene o establece un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) que especifica posiciones y factores que definen una caída personalizada para el degradado.

**Returns:**
[Blend](../../com.aspose.drawing.drawing2d/blend)
### setBlend(Blend value) {#setBlend-com.aspose.drawing.drawing2d.Blend-}
```
public void setBlend(Blend value)
```


Obtiene o establece un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) que especifica posiciones y factores que definen una caída personalizada para el degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Blend](../../com.aspose.drawing.drawing2d/blend) |  |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Obtiene o establece un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) que define un degradado lineal multicolor.

**Returns:**
[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Obtiene o establece un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) que define un degradado lineal multicolor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtiene o establece una copia de la [Matrix](../../com.aspose.drawing.drawing2d/matrix) que define una transformación geométrica local para este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Obtiene o establece una copia de la [Matrix](../../com.aspose.drawing.drawing2d/matrix) que define una transformación geométrica local para este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Obtiene o establece el punto focal para la caída del degradado.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setFocusScales(PointF value) {#setFocusScales-com.aspose.drawing.PointF-}
```
public void setFocusScales(PointF value)
```


Obtiene o establece el punto focal para la caída del degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtiene o establece un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) que indica el modo de ajuste para este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtiene o establece un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) que indica el modo de ajuste para este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia exacta de este [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
java.lang.Object - El [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) que este método crea, convertido a objeto.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Crea un pincel de degradado que cambia de color comenzando desde el centro de la ruta hacia el límite de la ruta. La transición de un color a otro se basa en una curva en forma de campana.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| foco | float | Un valor de 0 a 1 que especifica dónde, a lo largo de cualquier radial desde el centro de la ruta hasta el límite de la ruta, el color central alcanzará su mayor intensidad. Un valor de 1 (el predeterminado) coloca la mayor intensidad en el centro de la ruta. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crea un pincel de degradado que cambia de color comenzando desde el centro de la ruta hacia el límite de la ruta. La transición de un color a otro se basa en una curva en forma de campana.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| foco | float | Un valor de 0 a 1 que especifica dónde, a lo largo de cualquier radial desde el centro de la ruta hasta el límite de la ruta, el color central alcanzará su mayor intensidad. Un valor de 1 (el predeterminado) coloca la mayor intensidad en el centro de la ruta. |
| escala | float | Un valor de 0 a 1 que especifica la intensidad máxima del color central que se mezcla con el color del límite. Un valor de 1 produce la mayor intensidad posible del color central, y es el valor predeterminado. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Crea un degradado con un color central y una caída lineal hacia un color circundante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| foco | float | Un valor de 0 a 1 que especifica dónde, a lo largo de cualquier radial desde el centro de la ruta hasta el límite de la ruta, el color central alcanzará su mayor intensidad. Un valor de 1 (el predeterminado) coloca la mayor intensidad en el centro de la ruta. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crea un degradado con un color central y una disminución lineal hacia cada color circundante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| foco | float | Un valor de 0 a 1 que especifica dónde, a lo largo de cualquier radial desde el centro de la ruta hasta el límite de la ruta, el color central alcanzará su mayor intensidad. Un valor de 1 (el predeterminado) coloca la mayor intensidad en el centro de la ruta. |
| escala | float | Un valor de 0 a 1 que especifica la intensidad máxima del color central que se mezcla con el color del límite. Un valor de 1 produce la mayor intensidad posible del color central, y es el valor predeterminado. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Restablece la propiedad `PathGradientBrush.Transform` a la identidad.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Actualiza la matriz de transformación del pincel con el producto de la matriz de transformación del pincel multiplicada por otra matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | La [Matrix](../../com.aspose.drawing.drawing2d/matrix) que se multiplicará por la matriz de transformación actual del pincel. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Actualiza la matriz de transformación del pincel con el producto de la matriz de transformación del pincel multiplicada por otra matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | La [Matrix](../../com.aspose.drawing.drawing2d/matrix) que se multiplicará por la matriz de transformación actual del pincel. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) que especifica en qué orden multiplicar las dos matrices. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Aplica la traslación especificada a la transformación geométrica local. Este método antepone la traslación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Aplica la traslación especificada a la transformación geométrica local en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |
| orden | int | El orden (anteponer o anexar) en el que aplicar la traslación. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Escala la transformación geométrica local por las cantidades especificadas. Este método antepone la matriz de escala a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | El factor de escala de la transformación en la dirección del eje x. |
| sy | float | El factor de escala de la transformación en la dirección del eje y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Escala la transformación geométrica local por las cantidades especificadas en el orden indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | El factor de escala de la transformación en la dirección del eje x. |
| sy | float | El factor de escala de la transformación en la dirección del eje y. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) que especifica si se debe añadir al final o anteponer la matriz de escala. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rota la transformación geométrica local por la cantidad especificada. Este método antepone la rotación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | float | El ángulo (extensión) de rotación. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rota la transformación geométrica local por la cantidad especificada en el orden indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | float | El ángulo (extensión) de rotación. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) que especifica si se debe añadir al final o anteponer la matriz de rotación. |

