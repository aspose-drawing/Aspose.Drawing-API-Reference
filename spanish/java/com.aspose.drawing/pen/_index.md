---
title: Pen
second_title: Referencia de la API de Aspose.Drawing para Java
description: Define un objeto utilizado para dibujar líneas y curvas.
type: docs
weight: 34
url: /es/java/com.aspose.drawing/pen/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class Pen implements System.IDisposable
```

Define un objeto utilizado para dibujar líneas y curvas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.drawing.Color-) | Inicializa una nueva instancia de la clase [Pen](../../com.aspose.drawing/pen) con el `Color` especificado([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)). |
| [Pen(Brush brush, float width)](#Pen-com.aspose.drawing.Brush-float-) | Inicializa una nueva instancia de la clase Pen con el Brush y el Width especificados. |
| [Pen(Brush brush)](#Pen-com.aspose.drawing.Brush-) | Inicializa una nueva instancia de la clase [Pen](../../com.aspose.drawing/pen) con el `Brush` especificado([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)). |
| [Pen(Color color, float width)](#Pen-com.aspose.drawing.Color-float-) | Inicializa una nueva instancia de la clase Pen con las propiedades Color y Width especificadas. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getColor()](#getColor--) | Obtiene o establece el color de este [Pen](../../com.aspose.drawing/pen). |
| [setColor(Color value)](#setColor-com.aspose.drawing.Color-) | Obtiene o establece el color de este [Pen](../../com.aspose.drawing/pen). |
| [getBrush()](#getBrush--) | Obtiene o establece el Brush que determina los atributos de este [Pen](../../com.aspose.drawing/pen). |
| [setBrush(Brush value)](#setBrush-com.aspose.drawing.Brush-) | Obtiene o establece el Brush que determina los atributos de este [Pen](../../com.aspose.drawing/pen). |
| [getCompoundArray()](#getCompoundArray--) | Obtiene o establece una matriz de valores que especifica un pen compuesto. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Obtiene o establece una matriz de valores que especifica un pen compuesto. |
| [getWidth()](#getWidth--) | Obtiene o establece el ancho de este Pen, en unidades del objeto Graphics utilizado para dibujar. |
| [setWidth(float value)](#setWidth-float-) | Obtiene o establece el ancho de este Pen, en unidades del objeto Graphics utilizado para dibujar. |
| [getStartCap()](#getStartCap--) | Obtiene o establece el estilo de cap utilizado al inicio de las líneas dibujadas con este Pen. |
| [setStartCap(int value)](#setStartCap-int-) | Obtiene o establece el estilo de cap utilizado al inicio de las líneas dibujadas con este Pen. |
| [getEndCap()](#getEndCap--) | Obtiene o establece el estilo de cap utilizado al final de las líneas dibujadas con este Pen. |
| [setEndCap(int value)](#setEndCap-int-) | Obtiene o establece el estilo de cap utilizado al final de las líneas dibujadas con este Pen. |
| [getLineJoin()](#getLineJoin--) | Obtiene o establece el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este Pen. |
| [setLineJoin(int value)](#setLineJoin-int-) | Obtiene o establece el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este Pen. |
| [getMiterLimit()](#getMiterLimit--) | Obtiene o establece el límite del grosor de la unión en una esquina biselada. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Obtiene o establece el límite del grosor de la unión en una esquina biselada. |
| [getAlignment()](#getAlignment--) | Obtiene o establece la alineación de este [Pen](../../com.aspose.drawing/pen). |
| [setAlignment(int value)](#setAlignment-int-) | Obtiene o establece la alineación de este [Pen](../../com.aspose.drawing/pen). |
| [getTransform()](#getTransform--) | Obtiene o establece una copia de la transformación geométrica de este [Pen](../../com.aspose.drawing/pen). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Obtiene o establece una copia de la transformación geométrica de este [Pen](../../com.aspose.drawing/pen). |
| [getCustomStartCap()](#getCustomStartCap--) | Obtiene o establece un cap personalizado para usar al inicio de las líneas dibujadas con este [Pen](../../com.aspose.drawing/pen). |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Obtiene o establece un cap personalizado para usar al inicio de las líneas dibujadas con este [Pen](../../com.aspose.drawing/pen). |
| [getCustomEndCap()](#getCustomEndCap--) | Obtiene o establece un cap personalizado para usar al final de las líneas dibujadas con este [Pen](../../com.aspose.drawing/pen). |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Obtiene o establece un cap personalizado para usar al final de las líneas dibujadas con este [Pen](../../com.aspose.drawing/pen). |
| [getDashCap()](#getDashCap--) | Obtiene o establece el estilo de cap utilizado al final de los guiones que forman las líneas discontinuas dibujadas con este [Pen](../../com.aspose.drawing/pen). |
| [setDashCap(int value)](#setDashCap-int-) | Obtiene o establece el estilo de cap utilizado al final de los guiones que forman las líneas discontinuas dibujadas con este [Pen](../../com.aspose.drawing/pen). |
| [getDashOffset()](#getDashOffset--) | Obtiene o establece la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones. |
| [setDashOffset(float value)](#setDashOffset-float-) | Obtiene o establece la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones. |
| [getDashPattern()](#getDashPattern--) | Obtiene o establece una matriz de guiones y espacios personalizados. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Obtiene o establece una matriz de guiones y espacios personalizados. |
| [getDashStyle()](#getDashStyle--) | Obtiene o establece el estilo utilizado para líneas discontinuas dibujadas con este [Pen](../../com.aspose.drawing/pen). |
| [setDashStyle(int value)](#setDashStyle-int-) | Obtiene o establece el estilo utilizado para líneas discontinuas dibujadas con este [Pen](../../com.aspose.drawing/pen). |
| [getPenType()](#getPenType--) | Obtiene el estilo de las líneas dibujadas con este Pen. |
| [dispose()](#dispose--) | Libera todos los recursos utilizados por este Pen. |
| [deepClone()](#deepClone--) | Crea una copia exacta de este [Pen](../../com.aspose.drawing/pen). |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Establece los valores que determinan el estilo de la tapa utilizada para terminar las líneas dibujadas por este [Pen](../../com.aspose.drawing/pen). |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Escala la transformación geométrica local por los factores especificados. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Escala la transformación geométrica local por los factores especificados en el orden especificado. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Traslada la transformación geométrica local por las dimensiones especificadas. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rota la transformación geométrica local por el ángulo especificado. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rota la transformación geométrica local por el ángulo especificado en el orden especificado. |
| [resetTransform()](#resetTransform--) | Restablece la matriz de transformación geométrica para este [Pen](../../com.aspose.drawing/pen) a la identidad. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Multiplica la matriz de transformación para este [Pen](../../com.aspose.drawing/pen) por la [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificada. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Multiplica la matriz de transformación para este [Pen](../../com.aspose.drawing/pen) por la [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificada en el orden especificado. |
### Pen(Color color) {#Pen-com.aspose.drawing.Color-}
```
public Pen(Color color)
```


Inicializa una nueva instancia de la clase [Pen](../../com.aspose.drawing/pen) con el `Color` especificado([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Un `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) que determina las propiedades de relleno de este [Pen](../../com.aspose.drawing/pen). |

### Pen(Brush brush, float width) {#Pen-com.aspose.drawing.Brush-float-}
```
public Pen(Brush brush, float width)
```


Inicializa una nueva instancia de la clase Pen con el Brush y el Width especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Un Brush que determina las características de este Pen. |
| ancho | float | El ancho del nuevo Pen. |

### Pen(Brush brush) {#Pen-com.aspose.drawing.Brush-}
```
public Pen(Brush brush)
```


Inicializa una nueva instancia de la clase [Pen](../../com.aspose.drawing/pen) con el `Brush` especificado([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Un `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)) que determina las propiedades de relleno de este [Pen](../../com.aspose.drawing/pen). |

### Pen(Color color, float width) {#Pen-com.aspose.drawing.Color-float-}
```
public Pen(Color color, float width)
```


Inicializa una nueva instancia de la clase Pen con las propiedades Color y Width especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Una estructura Color que indica el color de este Pen. |
| ancho | float | Un valor que indica el ancho de este Pen. |

### getColor() {#getColor--}
```
public final Color getColor()
```


Obtiene o establece el color de este [Pen](../../com.aspose.drawing/pen).

Valor: Una estructura `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) que representa el color de este [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Color](../../com.aspose.drawing/color)
### setColor(Color value) {#setColor-com.aspose.drawing.Color-}
```
public final void setColor(Color value)
```


Obtiene o establece el color de este [Pen](../../com.aspose.drawing/pen).

Valor: Una estructura `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) que representa el color de este [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Obtiene o establece el Brush que determina los atributos de este [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Brush](../../com.aspose.drawing/brush)
### setBrush(Brush value) {#setBrush-com.aspose.drawing.Brush-}
```
public final void setBrush(Brush value)
```


Obtiene o establece el Brush que determina los atributos de este [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Brush](../../com.aspose.drawing/brush) |  |

### getCompoundArray() {#getCompoundArray--}
```
public final float[] getCompoundArray()
```


Obtiene o establece una matriz de valores que especifica un pen compuesto. Un pen compuesto dibuja una línea compuesta formada por líneas paralelas y espacios.

**Returns:**
float[] - Una matriz de números reales que especifica la matriz compuesta. Los elementos de la matriz deben estar en orden creciente, no ser menores que 0 y no ser mayores que 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public final void setCompoundArray(float[] value)
```


Obtiene o establece una matriz de valores que especifica un pen compuesto. Un pen compuesto dibuja una línea compuesta formada por líneas paralelas y espacios.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float[] |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Obtiene o establece el ancho de este Pen, en unidades del objeto Graphics utilizado para dibujar.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Obtiene o establece el ancho de este Pen, en unidades del objeto Graphics utilizado para dibujar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getStartCap() {#getStartCap--}
```
public final int getStartCap()
```


Obtiene o establece el estilo de cap utilizado al inicio de las líneas dibujadas con este Pen.

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public final void setStartCap(int value)
```


Obtiene o establece el estilo de cap utilizado al inicio de las líneas dibujadas con este Pen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public final int getEndCap()
```


Obtiene o establece el estilo de cap utilizado al final de las líneas dibujadas con este Pen.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public final void setEndCap(int value)
```


Obtiene o establece el estilo de cap utilizado al final de las líneas dibujadas con este Pen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public final int getLineJoin()
```


Obtiene o establece el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este Pen.

--------------------

En este momento la unión Miter realmente funciona como MiterClipped.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public final void setLineJoin(int value)
```


Obtiene o establece el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este Pen.

--------------------

En este momento la unión Miter realmente funciona como MiterClipped.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


Obtiene o establece el límite del grosor de la unión en una esquina biselada.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


Obtiene o establece el límite del grosor de la unión en una esquina biselada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Obtiene o establece la alineación de este [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - Un [PenAlignment](../../com.aspose.drawing.drawing2d/penalignment) que representa la alineación de este [Pen](../../com.aspose.drawing/pen).
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Obtiene o establece la alineación de este [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public final Matrix getTransform()
```


Obtiene o establece una copia de la transformación geométrica de este [Pen](../../com.aspose.drawing/pen).

Valor: Una copia de la [Matrix](../../com.aspose.drawing.drawing2d/matrix) que representa la transformación geométrica de este [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void setTransform(Matrix value)
```


Obtiene o establece una copia de la transformación geométrica de este [Pen](../../com.aspose.drawing/pen).

Valor: Una copia de la [Matrix](../../com.aspose.drawing.drawing2d/matrix) que representa la transformación geométrica de este [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getCustomStartCap() {#getCustomStartCap--}
```
public final CustomLineCap getCustomStartCap()
```


Obtiene o establece un cap personalizado para usar al inicio de las líneas dibujadas con este [Pen](../../com.aspose.drawing/pen).

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the beginning of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomStartCap(CustomLineCap value)
```


Obtiene o establece un cap personalizado para usar al inicio de las líneas dibujadas con este [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getCustomEndCap() {#getCustomEndCap--}
```
public final CustomLineCap getCustomEndCap()
```


Obtiene o establece un cap personalizado para usar al final de las líneas dibujadas con este [Pen](../../com.aspose.drawing/pen).

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the end of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomEndCap(CustomLineCap value)
```


Obtiene o establece un cap personalizado para usar al final de las líneas dibujadas con este [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getDashCap() {#getDashCap--}
```
public final int getDashCap()
```


Obtiene o establece el estilo de cap utilizado al final de los guiones que forman las líneas discontinuas dibujadas con este [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - Uno de los valores `DashCap`([.getDashCap](../../null/\#getDashCap)/[.setDashCap(int)](../../null/\#setDashCap-int-)) que representa el estilo de la tapa usado al inicio y al final de los guiones que forman líneas discontinuas dibujadas con este [Pen](../../com.aspose.drawing/pen).
### setDashCap(int value) {#setDashCap-int-}
```
public final void setDashCap(int value)
```


Obtiene o establece el estilo de cap utilizado al final de los guiones que forman las líneas discontinuas dibujadas con este [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public final float getDashOffset()
```


Obtiene o establece la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones.

**Returns:**
float - La distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones.
### setDashOffset(float value) {#setDashOffset-float-}
```
public final void setDashOffset(float value)
```


Obtiene o establece la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getDashPattern() {#getDashPattern--}
```
public final float[] getDashPattern()
```


Obtiene o establece una matriz de guiones y espacios personalizados.

**Returns:**
float[] - Una matriz de números reales que especifica las longitudes de guiones y espacios alternados en líneas discontinuas.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public final void setDashPattern(float[] value)
```


Obtiene o establece una matriz de guiones y espacios personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float[] |  |

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Obtiene o establece el estilo utilizado para líneas discontinuas dibujadas con este [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - Un `DashStyle`([.getDashStyle](../../null/\#getDashStyle)/[.setDashStyle(int)](../../null/\#setDashStyle-int-)) que representa el estilo utilizado para líneas discontinuas dibujadas con este [Pen](../../com.aspose.drawing/pen).
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Obtiene o establece el estilo utilizado para líneas discontinuas dibujadas con este [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPenType() {#getPenType--}
```
public final int getPenType()
```


Obtiene el estilo de las líneas dibujadas con este Pen.

Valor: Un `PenType`([.getPenType](../../null/\#getPenType)) enumeración que especifica el estilo de las líneas dibujadas con este [Pen](../../com.aspose.drawing/pen).

**Returns:**
int
### dispose() {#dispose--}
```
public final void dispose()
```


Libera todos los recursos utilizados por este Pen.

--------------------

Este método en realidad no hace nada. Sólo sirve para compatibilidad con la API System.Drawing.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Crea una copia exacta de este [Pen](../../com.aspose.drawing/pen).

**Returns:**
java.lang.Object - Un objeto que puede convertirse a un [Pen](../../com.aspose.drawing/pen).
### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public final void setLineCap(int startCap, int endCap, int dashCap)
```


Establece los valores que determinan el estilo de la tapa utilizada para terminar las líneas dibujadas por este [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startCap | int | Un [LineCap](../../com.aspose.drawing.drawing2d/linecap) que representa el estilo de extremo a usar al inicio de las líneas dibujadas con este [Pen](../../com.aspose.drawing/pen). |
| endCap | int | Un [LineCap](../../com.aspose.drawing.drawing2d/linecap) que representa el estilo de extremo a usar al final de las líneas dibujadas con este [Pen](../../com.aspose.drawing/pen). |
| dashCap | int | Un [LineCap](../../com.aspose.drawing.drawing2d/linecap) que representa el estilo de extremo a usar al inicio o al final de líneas discontinuas dibujadas con este [Pen](../../com.aspose.drawing/pen). |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public final void scaleTransform(float sx, float sy)
```


Escala la transformación geométrica local por los factores especificados. Este método antepone la matriz de escala a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | El factor por el cual escalar la transformación en la dirección del eje x. |
| sy | float | El factor por el cual escalar la transformación en la dirección del eje y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public final void scaleTransform(float sx, float sy, int order)
```


Escala la transformación geométrica local por los factores especificados en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | El factor por el cual escalar la transformación en la dirección del eje x. |
| sy | float | El factor por el cual escalar la transformación en la dirección del eje y. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) que especifica si se debe añadir al final o anteponer la matriz de escala. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public final void translateTransform(float dx, float dy)
```


Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public final void translateTransform(float dx, float dy, int order)
```


Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |
| orden | int | El orden (anteponer o anexar) en el que aplicar la traslación. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public final void rotateTransform(float angle)
```


Rota la transformación geométrica local por el ángulo especificado. Este método antepone la rotación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | float | El ángulo de rotación. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public final void rotateTransform(float angle, int order)
```


Rota la transformación geométrica local por el ángulo especificado en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | float | El ángulo de rotación. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) que especifica si se debe añadir al final o anteponer la matriz de rotación. |

### resetTransform() {#resetTransform--}
```
public final void resetTransform()
```


Restablece la matriz de transformación geométrica para este [Pen](../../com.aspose.drawing/pen) a la identidad.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void multiplyTransform(Matrix matrix)
```


Multiplica la matriz de transformación para este [Pen](../../com.aspose.drawing/pen) por la [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | El objeto [Matrix](../../com.aspose.drawing.drawing2d/matrix) por el cual multiplicar la matriz de transformación. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public final void multiplyTransform(Matrix matrix, int order)
```


Multiplica la matriz de transformación para este [Pen](../../com.aspose.drawing/pen) por la [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificada en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | El java.awt.geom.AffineTransform por el cual multiplicar la matriz de transformación. |
| orden | int | El orden en el que realizar la operación de multiplicación. |

