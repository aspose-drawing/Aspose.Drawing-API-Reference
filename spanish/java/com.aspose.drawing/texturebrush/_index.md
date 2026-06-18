---
title: TextureBrush
second_title: Referencia de la API de Aspose.Drawing para Java
description: Cada propiedad de la clase TextureBrush es un objeto Brush que utiliza una imagen para rellenar el interior de una forma.
type: docs
weight: 53
url: /es/java/com.aspose.drawing/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class TextureBrush extends Brush
```

Cada propiedad de la clase TextureBrush es un objeto Brush que utiliza una imagen para rellenar el interior de una forma. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextureBrush(Image bitmap)](#TextureBrush-com.aspose.drawing.Image-) | Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.drawing/texturebrush) que utiliza la imagen especificada. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.drawing.Image-int-) | Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.drawing/texturebrush) que utiliza la imagen especificada y el modo de ajuste. |
| [TextureBrush(Image image, int wrapMode, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-) | Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.drawing/texturebrush) que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador. |
| [TextureBrush(Image image, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-) | Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.drawing/texturebrush) que utiliza la imagen especificada y el rectángulo delimitador. |
| [TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-) | Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.drawing/texturebrush) que utiliza la imagen especificada, el rectángulo delimitador y los atributos de imagen. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getImage()](#getImage--) | Obtiene el objeto Image asociado a este objeto TextureBrush. |
| [getTransform()](#getTransform--) | Obtiene una copia del objeto Matrix que define una transformación geométrica local para la imagen asociada a este objeto TextureBrush. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Establece una copia del objeto Matrix que define una transformación geométrica local para la imagen asociada a este objeto TextureBrush. |
| [getWrapMode()](#getWrapMode--) | Obtiene una enumeración WrapMode que indica el modo de ajuste para este objeto TextureBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | Establece una enumeración WrapMode que indica el modo de ajuste para este objeto TextureBrush. |
| [deepClone()](#deepClone--) | Crea una copia exacta de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush). |
| [resetTransform()](#resetTransform--) | Restablece la propiedad Transform de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) a la identidad. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Multiplica el objeto [Matrix](../../com.aspose.drawing.drawing2d/matrix) que representa la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) por el objeto [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificado, anteponiendo el objeto [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificado. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Multiplica el objeto [Matrix](../../com.aspose.drawing.drawing2d/matrix) que representa la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) por el objeto [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificado en el orden especificado. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Traslada la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) por las dimensiones especificadas. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Traslada la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) por las dimensiones especificadas en el orden especificado. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Escala la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) por las cantidades especificadas. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Escala la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) por las cantidades especificadas en el orden especificado. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rota la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) por la cantidad especificada. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rota la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) por la cantidad especificada en el orden especificado. |
### TextureBrush(Image bitmap) {#TextureBrush-com.aspose.drawing.Image-}
```
public TextureBrush(Image bitmap)
```


Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.drawing/texturebrush) que utiliza la imagen especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitmap | [Image](../../com.aspose.drawing/image) | El objeto `Image`([.getImage](../../null/\#getImage)) con el que este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) rellena los interiores. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.drawing.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.drawing/texturebrush) que utiliza la imagen especificada y el modo de ajuste.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | La imagen. |
| wrapMode | int | Una enumeración `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) que especifica cómo se mosaica este objeto [TextureBrush](../../com.aspose.drawing/texturebrush). |

### TextureBrush(Image image, int wrapMode, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF dstRect)
```


Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.drawing/texturebrush) que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | La imagen. |
| wrapMode | int | Una enumeración `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) que especifica cómo se mosaica este objeto [TextureBrush](../../com.aspose.drawing/texturebrush). |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una estructura [RectangleF](../../com.aspose.drawing/rectanglef) que representa el rectángulo delimitador de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush). |

### TextureBrush(Image image, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, RectangleF dstRect)
```


Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.drawing/texturebrush) que utiliza la imagen especificada y el rectángulo delimitador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | El objeto `Image`([.getImage](../../null/\#getImage)) con el que este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) rellena los interiores. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una estructura [RectangleF](../../com.aspose.drawing/rectanglef) que representa el rectángulo delimitador de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush). |

### TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)
```


Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.drawing/texturebrush) que utiliza la imagen especificada, el rectángulo delimitador y los atributos de imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | El objeto Image con el que este objeto TextureBrush rellena los interiores. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una estructura RectangleF que representa el rectángulo delimitador de este objeto TextureBrush. |
| imageAttr | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) | Un objeto ImageAttributes que contiene información adicional sobre la imagen utilizada por este objeto TextureBrush. |

### getImage() {#getImage--}
```
public Image getImage()
```


Obtiene el objeto Image asociado a este objeto TextureBrush.

**Returns:**
[Image](../../com.aspose.drawing/image) - the Image object associated with this TextureBrush object.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtiene una copia del objeto Matrix que define una transformación geométrica local para la imagen asociada a este objeto TextureBrush.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - a copy of the Matrix object that defines a local geometric transformation for the image associated with this TextureBrush object.
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Establece una copia del objeto Matrix que define una transformación geométrica local para la imagen asociada a este objeto TextureBrush.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | una copia del objeto Matrix que define una transformación geométrica local para la imagen asociada a este objeto TextureBrush. |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtiene una enumeración WrapMode que indica el modo de ajuste para este objeto TextureBrush.

**Returns:**
int - una enumeración WrapMode que indica el modo de ajuste para este objeto TextureBrush.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Establece una enumeración WrapMode que indica el modo de ajuste para este objeto TextureBrush.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | una enumeración WrapMode que indica el modo de ajuste para este objeto TextureBrush. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia exacta de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush).

**Returns:**
java.lang.Object - El objeto [TextureBrush](../../com.aspose.drawing/texturebrush) que este método crea, convertido a un objeto Object.
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Restablece la propiedad Transform de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) a la identidad.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplica el objeto [Matrix](../../com.aspose.drawing.drawing2d/matrix) que representa la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) por el objeto [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificado, anteponiendo el objeto [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | El objeto [Matrix](../../com.aspose.drawing.drawing2d/matrix) por el cual multiplicar la transformación geométrica. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplica el objeto [Matrix](../../com.aspose.drawing.drawing2d/matrix) que representa la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) por el objeto [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificado en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | El objeto [Matrix](../../com.aspose.drawing.drawing2d/matrix) por el cual multiplicar la transformación geométrica. |
| order | int | Una enumeración [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) que especifica el orden en que multiplicar las dos matrices. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Traslada la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) según las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | La dimensión por la cual trasladar la transformación en la dirección x. |
| dy | float | La dimensión por la cual trasladar la transformación en la dirección y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Traslada la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) por las dimensiones especificadas en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | La dimensión por la cual trasladar la transformación en la dirección x. |
| dy | float | La dimensión por la cual trasladar la transformación en la dirección y. |
| orden | int | El orden (anteponer o anexar) en el que aplicar la traslación. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Escala la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) según las cantidades especificadas. Este método antepone la matriz de escala a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Escala la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) por las cantidades especificadas en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección y. |
| order | int | Una enumeración [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) que especifica si se debe anexar o anteponer la matriz de escala. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rota la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) según la cantidad especificada. Este método antepone la rotación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | float | El ángulo de rotación. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rota la transformación geométrica local de este objeto [TextureBrush](../../com.aspose.drawing/texturebrush) por la cantidad especificada en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | float | El ángulo de rotación. |
| order | int | Una enumeración [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) que especifica si se debe anexar o anteponer la matriz de rotación. |

