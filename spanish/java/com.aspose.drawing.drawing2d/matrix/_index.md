---
title: Matrix
second_title: Referencia de la API de Aspose.Drawing para Java
description: Encapsula una matriz afín de 3 por 3 que representa una transformación geométrica.
type: docs
weight: 33
url: /es/java/com.aspose.drawing.drawing2d/matrix/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Matrix implements System.IDisposable
```

Encapsula una matriz afín de 3 por 3 que representa una transformación geométrica. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Matrix()](#Matrix--) | Inicializa una nueva instancia de la clase Matrix como la matriz identidad. |
| [Matrix(float m11, float m12, float m21, float m22, float dx, float dy)](#Matrix-float-float-float-float-float-float-) | Inicializa una nueva instancia de la clase Matrix con los elementos especificados. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---) | Inicializa una nueva instancia de la clase [Matrix](../../com.aspose.drawing.drawing2d/matrix) para la transformación geométrica definida por el rectángulo especificado y la matriz de puntos. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---) | Inicializa una nueva instancia de la clase [Matrix](../../com.aspose.drawing.drawing2d/matrix) para la transformación geométrica definida por el rectángulo especificado y la matriz de puntos. |
## Campos

| Campo | Descripción |
| --- | --- |
| [IdentityTransform](#IdentityTransform) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getElements()](#getElements--) | Obtiene una matriz de valores de punto flotante que representa los elementos de esta Matrix. |
| [isIdentity()](#isIdentity--) | Obtiene un valor que indica si esta Matrix es la matriz identidad. |
| [isInvertible()](#isInvertible--) | Obtiene un valor que indica si esta Matrix es invertible. |
| [getOffsetX()](#getOffsetX--) | Obtiene el valor de traducción x (el valor dx, o el elemento en la tercera fila y primera columna) de esta Matrix. |
| [getOffsetY()](#getOffsetY--) | Obtiene el valor de traducción y (el valor `dy`, o el elemento en la tercera fila y segunda columna) de esta Matrix. |
| [dispose()](#dispose--) | Libera todos los recursos utilizados por esta Matrix. |
| [deepClone()](#deepClone--) | Crea una copia exacta de esta Matrix. |
| [invert()](#invert--) | Invierte esta Matrix, si es invertible. |
| [translate(float offsetX, float offsetY)](#translate-float-float-) | Aplica el vector de traslación especificado (offsetX y offsetY) a esta Matrix precediendo el vector de traslación. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Aplica el vector de traslación especificado a esta Matrix en el orden especificado. |
| [transformVectors(PointF[] pts)](#transformVectors-com.aspose.drawing.PointF---) | Multiplica cada vector en una matriz por la Matrix. |
| [scale(float scaleX, float scaleY)](#scale-float-float-) | Aplica el vector de escala especificado a esta Matrix precediendo el vector de escala. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Aplica el vector de escala especificado (scaleX y scaleY) a esta Matrix usando el orden especificado. |
| [shear(float shearX, float shearY)](#shear-float-float-) | Aplica el vector de cizallamiento especificado a esta Matrix precediendo la transformación de cizallamiento. |
| [shear(float shearX, float shearY, int order)](#shear-float-float-int-) | Aplica el vector de cizallamiento especificado a esta Matrix en el orden especificado. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.drawing.PointF-) | Aplica una rotación en sentido horario a esta Matrix alrededor del punto especificado en el parámetro point, y precediendo la rotación. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.drawing.PointF-int-) | Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden especificado. |
| [transformPoints(PointF[] pts)](#transformPoints-com.aspose.drawing.PointF---) | Aplica la transformación geométrica representada por esta [Matrix](../../com.aspose.drawing.drawing2d/matrix) a una matriz de puntos especificada. |
| [transformPoints(Point[] pts)](#transformPoints-com.aspose.drawing.Point---) | Aplica la transformación geométrica representada por esta [Matrix](../../com.aspose.drawing.drawing2d/matrix) a una matriz de puntos especificada. |
| [multiply(Matrix matrix)](#multiply-com.aspose.drawing.drawing2d.Matrix-) | Multiplica esta [Matrix](../../com.aspose.drawing.drawing2d/matrix) por la matrix especificada en el parámetro `matrix`, precediendo la [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificada. |
| [multiply(Matrix matrix, int order)](#multiply-com.aspose.drawing.drawing2d.Matrix-int-) | Multiplica esta [Matrix](../../com.aspose.drawing.drawing2d/matrix) por la matrix especificada en el parámetro `matrix`, y en el orden especificado en el parámetro `order`. |
| [rotate(float angle)](#rotate-float-) | Precede a esta [Matrix](../../com.aspose.drawing.drawing2d/matrix) una rotación en sentido horario, alrededor del origen y con el ángulo especificado. |
| [rotate(float angle, int order)](#rotate-float-int-) | Aplica una rotación en sentido horario de una cantidad especificada en el parámetro ángulo, alrededor del origen (coordenadas x e y cero) para esta [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [reset()](#reset--) | Restablece esta [Matrix](../../com.aspose.drawing.drawing2d/matrix) para que tenga los elementos de la matriz identidad. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Inicializa una nueva instancia de la clase Matrix como la matriz identidad.

### Matrix(float m11, float m12, float m21, float m22, float dx, float dy) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


Inicializa una nueva instancia de la clase Matrix con los elementos especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| m11 | float | El valor en la primera fila y primera columna de la nueva Matrix. |
| m12 | float | El valor en la primera fila y segunda columna de la nueva Matrix. |
| m21 | float | El valor en la segunda fila y primera columna de la nueva Matriz. |
| m22 | float | El valor en la segunda fila y segunda columna de la nueva Matriz. |
| dx | float | El valor en la tercera fila y primera columna de la nueva Matriz. |
| dy | float | El valor en la tercera fila y segunda columna de la nueva Matriz. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Inicializa una nueva instancia de la clase [Matrix](../../com.aspose.drawing.drawing2d/matrix) para la transformación geométrica definida por el rectángulo especificado y la matriz de puntos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Una estructura [Rectangle](../../com.aspose.drawing/rectangle) que representa el rectángulo a transformar. |
| plgpts | [Point\[\]](../../com.aspose.drawing/point) | Una matriz de tres estructuras [Point](../../com.aspose.drawing/point) que representan los puntos de un paralelogramo al que se transformarán las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo se deduce de las tres primeras esquinas. |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Inicializa una nueva instancia de la clase [Matrix](../../com.aspose.drawing.drawing2d/matrix) para la transformación geométrica definida por el rectángulo especificado y la matriz de puntos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una estructura [RectangleF](../../com.aspose.drawing/rectanglef) que representa el rectángulo a transformar. |
| plgpts | [PointF\[\]](../../com.aspose.drawing/pointf) | Una matriz de tres estructuras [PointF](../../com.aspose.drawing/pointf) que representan los puntos de un paralelogramo al que se transformarán las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo se deduce de las tres primeras esquinas. |

### IdentityTransform {#IdentityTransform}
```
public static final Matrix IdentityTransform
```


### getElements() {#getElements--}
```
public float[] getElements()
```


Obtiene una matriz de valores de punto flotante que representa los elementos de esta Matrix.

**Returns:**
float[] - una matriz de valores de punto flotante que representa los elementos de esta Matriz.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Obtiene un valor que indica si esta Matrix es la matriz identidad.

**Returns:**
boolean - un valor que indica si esta Matriz es la matriz identidad.
### isInvertible() {#isInvertible--}
```
public boolean isInvertible()
```


Obtiene un valor que indica si esta Matrix es invertible.

**Returns:**
boolean - un valor que indica si esta Matriz es invertible.
### getOffsetX() {#getOffsetX--}
```
public float getOffsetX()
```


Obtiene el valor de traducción x (el valor dx, o el elemento en la tercera fila y primera columna) de esta Matrix.

**Returns:**
float - el valor de traslación en x (el valor dx, o el elemento en la tercera fila y primera columna) de esta Matriz.
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```


Obtiene el valor de traducción y (el valor `dy`, o el elemento en la tercera fila y segunda columna) de esta Matrix.

**Returns:**
float - el valor de traslación en y (el valor `dy`, o el elemento en la tercera fila y segunda columna) de esta Matriz.
### dispose() {#dispose--}
```
public void dispose()
```


Libera todos los recursos utilizados por esta Matrix.

--------------------

Este método en realidad no hace nada. Sólo sirve para compatibilidad con la API System.Drawing.

### deepClone() {#deepClone--}
```
public Matrix deepClone()
```


Crea una copia exacta de esta Matrix.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - The Matrix that this method creates.
### invert() {#invert--}
```
public void invert()
```


Invierte esta Matrix, si es invertible.

### translate(float offsetX, float offsetY) {#translate-float-float-}
```
public void translate(float offsetX, float offsetY)
```


Aplica el vector de traslación especificado (offsetX y offsetY) a esta Matrix precediendo el vector de traslación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| offsetX | float | El valor x por el cual trasladar esta Matriz. |
| offsetY | float | El valor y por el cual trasladar esta Matriz. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Aplica el vector de traslación especificado a esta Matrix en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| offsetX | float | El valor x por el cual trasladar esta Matriz. |
| offsetY | float | El valor y por el cual trasladar esta Matriz. |
| orden | int | Un MatrixOrder que especifica el orden (añadir o anteponer) en el que se aplica la traslación a esta Matriz. |

### transformVectors(PointF[] pts) {#transformVectors-com.aspose.drawing.PointF---}
```
public void transformVectors(PointF[] pts)
```


Multiplica cada vector en una matriz por la matriz. Los elementos de traslación de esta matriz (tercera fila) se ignoran.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Una matriz de estructuras [PointF](../../com.aspose.drawing/pointf) que representa los puntos a transformar. |

### scale(float scaleX, float scaleY) {#scale-float-float-}
```
public void scale(float scaleX, float scaleY)
```


Aplica el vector de escala especificado a esta Matrix precediendo el vector de escala.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scaleX | float | El valor por el cual escalar esta Matriz en la dirección del eje x. |
| scaleY | float | El valor por el cual escalar esta Matrix en la dirección del eje y. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Aplica el vector de escala especificado (scaleX y scaleY) a esta Matrix usando el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scaleX | float | El valor por el cual escalar esta Matriz en la dirección del eje x. |
| scaleY | float | El valor por el cual escalar esta Matrix en la dirección del eje y. |
| orden | int | Un MatrixOrder que especifica el orden (append o prepend) en el que el vector de escala se aplica a esta Matrix. |

### shear(float shearX, float shearY) {#shear-float-float-}
```
public void shear(float shearX, float shearY)
```


Aplica el vector de cizallamiento especificado a esta Matrix precediendo la transformación de cizallamiento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shearX | float | El factor de cizallamiento horizontal. |
| shearY | float | El factor de cizallamiento vertical. |

### shear(float shearX, float shearY, int order) {#shear-float-float-int-}
```
public void shear(float shearX, float shearY, int order)
```


Aplica el vector de cizallamiento especificado a esta Matrix en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shearX | float | El factor de cizallamiento horizontal. |
| shearY | float | El factor de cizallamiento vertical. |
| orden | int | Un MatrixOrder que especifica el orden (append o prepend) en el que se aplica la cizalla. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.drawing.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Aplica una rotación en sentido horario a esta Matrix alrededor del punto especificado en el parámetro point, y precediendo la rotación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | float | El ángulo (amplitud) de la rotación, en grados. |
| point | [PointF](../../com.aspose.drawing/pointf) | Un PointF que representa el centro de la rotación. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.drawing.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | float | El ángulo de la rotación, en grados. |
| point | [PointF](../../com.aspose.drawing/pointf) | Un PointF que representa el centro de la rotación. |
| orden | int | Un MatrixOrder que especifica el orden (append o prepend) en el que se aplica la rotación. |

### transformPoints(PointF[] pts) {#transformPoints-com.aspose.drawing.PointF---}
```
public void transformPoints(PointF[] pts)
```


Aplica la transformación geométrica representada por esta [Matrix](../../com.aspose.drawing.drawing2d/matrix) a una matriz de puntos especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Una matriz de estructuras [PointF](../../com.aspose.drawing/pointf) que representa los puntos a transformar. |

### transformPoints(Point[] pts) {#transformPoints-com.aspose.drawing.Point---}
```
public void transformPoints(Point[] pts)
```


Aplica la transformación geométrica representada por esta [Matrix](../../com.aspose.drawing.drawing2d/matrix) a una matriz de puntos especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pts | [Point\[\]](../../com.aspose.drawing/point) | Una matriz de estructuras [Point](../../com.aspose.drawing/point) que representa los puntos a transformar. |

### multiply(Matrix matrix) {#multiply-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiply(Matrix matrix)
```


Multiplica esta [Matrix](../../com.aspose.drawing.drawing2d/matrix) por la matrix especificada en el parámetro `matrix`, precediendo la [Matrix](../../com.aspose.drawing.drawing2d/matrix) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | El [Matrix](../../com.aspose.drawing.drawing2d/matrix) por el cual este [Matrix](../../com.aspose.drawing.drawing2d/matrix) debe ser multiplicado. |

### multiply(Matrix matrix, int order) {#multiply-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiply(Matrix matrix, int order)
```


Multiplica esta [Matrix](../../com.aspose.drawing.drawing2d/matrix) por la matrix especificada en el parámetro `matrix`, y en el orden especificado en el parámetro `order`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | El [Matrix](../../com.aspose.drawing.drawing2d/matrix) por el cual este [Matrix](../../com.aspose.drawing.drawing2d/matrix) debe ser multiplicado. |
| order | int | El [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) que representa el orden de la multiplicación. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Precede a esta [Matrix](../../com.aspose.drawing.drawing2d/matrix) una rotación en sentido horario, alrededor del origen y con el ángulo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | float | El ángulo de la rotación, en grados. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Aplica una rotación en sentido horario de una cantidad especificada en el parámetro ángulo, alrededor del origen (coordenadas x e y cero) para esta [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | float | El ángulo de la rotación, en grados. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) que especifica el orden (append o prepend) en el que se aplica la rotación a este [Matrix](../../com.aspose.drawing.drawing2d/matrix). |

### reset() {#reset--}
```
public void reset()
```


Restablece esta [Matrix](../../com.aspose.drawing.drawing2d/matrix) para que tenga los elementos de la matriz identidad.

