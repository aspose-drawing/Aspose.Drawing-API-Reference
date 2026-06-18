---
title: LinearGradientBrush
second_title: Referencia de la API de Aspose.Drawing para Java
description: Encapsula un  con un degradado lineal.
type: docs
weight: 31
url: /es/java/com.aspose.drawing.drawing2d/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class LinearGradientBrush extends Brush
```

Encapsula un [Brush](../../com.aspose.drawing/brush) con un degradado lineal. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) con los puntos y colores especificados. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) con los puntos y colores especificados. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basada en un rectángulo, colores de inicio y fin, y un modo de orientación. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basada en un rectángulo, colores de inicio y fin, y orientación. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLinearColors()](#getLinearColors--) | Obtiene o establece los colores de inicio y fin del degradado. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.drawing.Color---) | Obtiene o establece los colores de inicio y fin del degradado. |
| [getRectangle()](#getRectangle--) | Obtiene una región rectangular que define los puntos de inicio y fin del degradado. |
| [getGammaCorrection()](#getGammaCorrection--) | Obtiene o establece un valor que indica si la corrección gamma está habilitada para este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Obtiene o establece un valor que indica si la corrección gamma está habilitada para este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getBlend()](#getBlend--) | Obtiene o establece un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) que especifica posiciones y factores que definen una caída personalizada para el degradado. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Obtiene o establece un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) que especifica posiciones y factores que definen una caída personalizada para el degradado. |
| [getInterpolationColors()](#getInterpolationColors--) | Obtiene o establece un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) que define un degradado lineal multicolor. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Obtiene o establece un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) que define un degradado lineal multicolor. |
| [getWrapMode()](#getWrapMode--) | Obtiene o establece una enumeración `WrapMode` que indica el modo de ajuste para este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtiene o establece una enumeración `WrapMode` que indica el modo de ajuste para este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getTransform()](#getTransform--) | Obtiene o establece una copia de [Matrix](../../com.aspose.drawing.drawing2d/matrix) que define una transformación geométrica local para este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Obtiene o establece una copia de [Matrix](../../com.aspose.drawing.drawing2d/matrix) que define una transformación geométrica local para este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [deepClone()](#deepClone--) | Crea una copia exacta de este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crea una caída de degradado basada en una curva en forma de campana. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crea una caída de degradado basada en una curva en forma de campana. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos. |
| [resetTransform()](#resetTransform--) | Restablece la propiedad `LinearGradientBrush.Transform` a la identidad. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Multiplica la [Matrix](../../com.aspose.drawing.drawing2d/matrix) que representa la transformación geométrica local de este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) por la [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificada, anteponiendo la [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificada. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Multiplica la [Matrix](../../com.aspose.drawing.drawing2d/matrix) que representa la transformación geométrica local de este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) por la [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificada en el orden indicado. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Traslada la transformación geométrica local por las dimensiones especificadas. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden indicado. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Escala la transformación geométrica local por las cantidades especificadas. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Escala la transformación geométrica local por las cantidades especificadas en el orden indicado. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rota la transformación geométrica local por la cantidad especificada. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rota la transformación geométrica local por la cantidad especificada en el orden indicado. |
### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) con los puntos y colores especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | Una estructura [PointF](../../com.aspose.drawing/pointf) que representa el punto inicial del degradado lineal. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | Una estructura [PointF](../../com.aspose.drawing/pointf) que representa el punto final del degradado lineal. |
| color1 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color inicial del degradado lineal. |
| color2 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color final del degradado lineal. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) con los puntos y colores especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | Una estructura [Point](../../com.aspose.drawing/point) que representa el punto inicial del degradado lineal. |
| point2 | [Point](../../com.aspose.drawing/point) | Una estructura [Point](../../com.aspose.drawing/point) que representa el punto final del degradado lineal. |
| color1 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color inicial del degradado lineal. |
| color2 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color final del degradado lineal. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)
```


Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basada en un rectángulo, colores de inicio y fin, y un modo de orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una estructura [RectangleF](../../com.aspose.drawing/rectanglef) que especifica los límites del degradado lineal. |
| color1 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color inicial del degradado. |
| color2 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color final del degradado. |
| linearGradientMode | int | Un elemento de enumeración [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) que especifica la orientación del degradado. La orientación determina los puntos de inicio y fin del degradado. Por ejemplo, LinearGradientMode.ForwardDiagonal especifica que el punto de inicio es la esquina superior izquierda del rectángulo y el punto de fin es la esquina inferior derecha del rectángulo. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)
```


Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basada en un rectángulo, colores de inicio y fin, y orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Una estructura `Rectangle`([.getRectangle](../../null/\#getRectangle)) que especifica los límites del degradado lineal. |
| color1 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color inicial del degradado. |
| color2 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color final del degradado. |
| linearGradientMode | int | Un elemento de enumeración [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) que especifica la orientación del degradado. La orientación determina los puntos de inicio y fin del degradado. Por ejemplo, LinearGradientMode.ForwardDiagonal especifica que el punto de inicio es la esquina superior izquierda del rectángulo y el punto de fin es la esquina inferior derecha del rectángulo. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una estructura [RectangleF](../../com.aspose.drawing/rectanglef) que especifica los límites del degradado lineal. |
| color1 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color inicial del degradado. |
| color2 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color final del degradado. |
| ángulo | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una estructura [RectangleF](../../com.aspose.drawing/rectanglef) que especifica los límites del degradado lineal. |
| color1 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color inicial del degradado. |
| color2 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color final del degradado. |
| ángulo | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |
| isAngleScaleable | boolean | Establezca en true para especificar que el ángulo se ve afectado por la transformación asociada a este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush); de lo contrario, false. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Una estructura `Rectangle`([.getRectangle](../../null/\#getRectangle)) que especifica los límites del degradado lineal. |
| color1 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color inicial del degradado. |
| color2 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color final del degradado. |
| ángulo | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Una estructura `Rectangle`([.getRectangle](../../null/\#getRectangle)) que especifica los límites del degradado lineal. |
| color1 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color inicial del degradado. |
| color2 | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color final del degradado. |
| ángulo | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |
| isAngleScaleable | boolean | Establezca en true para especificar que el ángulo se ve afectado por la transformación asociada a este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush); de lo contrario, false. |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Obtiene o establece los colores de inicio y fin del degradado.

**Returns:**
com.aspose.drawing.Color[]
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.drawing.Color---}
```
public void setLinearColors(Color[] value)
```


Obtiene o establece los colores de inicio y fin del degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Obtiene una región rectangular que define los puntos de inicio y fin del degradado.

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Obtiene o establece un valor que indica si la corrección gamma está habilitada para este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
boolean
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Obtiene o establece un valor que indica si la corrección gamma está habilitada para este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

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

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtiene o establece una enumeración `WrapMode` que indica el modo de ajuste para este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtiene o establece una enumeración `WrapMode` que indica el modo de ajuste para este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtiene o establece una copia de [Matrix](../../com.aspose.drawing.drawing2d/matrix) que define una transformación geométrica local para este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Obtiene o establece una copia de [Matrix](../../com.aspose.drawing.drawing2d/matrix) que define una transformación geométrica local para este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia exacta de este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
java.lang.Object - El [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) que crea este método, convertido a objeto.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Crea una caída de degradado basada en una curva en forma de campana.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| foco | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el color inicial y el color final se mezclan por igual). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crea una caída de degradado basada en una curva en forma de campana.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| foco | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el degradado está compuesto únicamente por el color final). |
| escala | float | Un valor de 0 a 1 que especifica la rapidez con la que los colores disminuyen desde el `foco`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| foco | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el degradado está compuesto únicamente por el color final). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| foco | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el degradado está compuesto únicamente por el color final). |
| escala | float | Un valor de 0 a 1 que especifica la rapidez con la que los colores disminuyen desde el color inicial hasta el `foco` (color final) |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Restablece la propiedad `LinearGradientBrush.Transform` a la identidad.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplica la [Matrix](../../com.aspose.drawing.drawing2d/matrix) que representa la transformación geométrica local de este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) por la [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificada, anteponiendo la [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | La [Matrix](../../com.aspose.drawing.drawing2d/matrix) por la cual multiplicar la transformación geométrica. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplica la [Matrix](../../com.aspose.drawing.drawing2d/matrix) que representa la transformación geométrica local de este [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) por la [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificada en el orden indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | La [Matrix](../../com.aspose.drawing.drawing2d/matrix) por la cual multiplicar la transformación geométrica. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) que especifica en qué orden multiplicar las dos matrices. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Traslada la transformación geométrica local por las dimensiones especificadas en el orden indicado.

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
| sx | float | La cantidad por la cual escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección del eje y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Escala la transformación geométrica local por las cantidades especificadas en el orden indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección del eje y. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) que especifica si se debe añadir al final o anteponer la matriz de escala. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rota la transformación geométrica local por la cantidad especificada. Este método antepone la rotación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | float | El ángulo de rotación. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rota la transformación geométrica local por la cantidad especificada en el orden indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | float | El ángulo de rotación. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) que especifica si se debe añadir al final o anteponer la matriz de rotación. |

