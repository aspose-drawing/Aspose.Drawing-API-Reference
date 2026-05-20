---
title: Matrix
second_title: Aspose.Drawing for Java API 参考
description: 封装表示几何变换的 3×3 仿射矩阵。
type: docs
weight: 33
url: /zh/java/com.aspose.drawing.drawing2d/matrix/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Matrix implements System.IDisposable
```

封装一个 3×3 仿射矩阵，表示几何变换。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Matrix()](#Matrix--) | 初始化 Matrix 类的新实例为单位矩阵。 |
| [Matrix(float m11, float m12, float m21, float m22, float dx, float dy)](#Matrix-float-float-float-float-float-float-) | 使用指定的元素初始化 Matrix 类的新实例。 |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---) | 将 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 类初始化为由指定矩形和点数组定义的几何变换的新实例。 |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---) | 将 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 类初始化为由指定矩形和点数组定义的几何变换的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [IdentityTransform](#IdentityTransform) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getElements()](#getElements--) | 获取表示此 Matrix 元素的浮点值数组。 |
| [isIdentity()](#isIdentity--) | 获取一个值，指示此 Matrix 是否为单位矩阵。 |
| [isInvertible()](#isInvertible--) | 获取一个值，指示此 Matrix 是否可逆。 |
| [getOffsetX()](#getOffsetX--) | 获取此 Matrix 的 x 平移值（dx 值，或第三行第一列的元素）。 |
| [getOffsetY()](#getOffsetY--) | 获取此 Matrix 的 y 平移值（`dy` 值，或第三行第二列的元素）。 |
| [dispose()](#dispose--) | 释放此 Matrix 使用的所有资源。 |
| [deepClone()](#deepClone--) | 创建此 Matrix 的精确副本。 |
| [invert()](#invert--) | 如果可逆，则对该 Matrix 进行求逆。 |
| [translate(float offsetX, float offsetY)](#translate-float-float-) | 通过在前面添加平移向量，将指定的平移向量（offsetX 和 offsetY）应用于此 Matrix。 |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | 按照指定顺序将指定的平移向量应用于此 Matrix。 |
| [transformVectors(PointF[] pts)](#transformVectors-com.aspose.drawing.PointF---) | 将数组中的每个向量乘以此 Matrix。 |
| [scale(float scaleX, float scaleY)](#scale-float-float-) | 通过在前面添加缩放向量，将指定的缩放向量应用于此 Matrix。 |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | 使用指定顺序，将指定的缩放向量（scaleX 和 scaleY）应用于此 Matrix。 |
| [shear(float shearX, float shearY)](#shear-float-float-) | 通过在前面添加剪切变换，将指定的剪切向量应用于此 Matrix。 |
| [shear(float shearX, float shearY, int order)](#shear-float-float-int-) | 按照指定顺序将指定的剪切向量应用于此 Matrix。 |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.drawing.PointF-) | 围绕 point 参数指定的点，通过在前面添加旋转，将顺时针旋转应用于此 Matrix。 |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.drawing.PointF-int-) | 按照指定顺序围绕指定点将顺时针旋转应用于此 Matrix。 |
| [transformPoints(PointF[] pts)](#transformPoints-com.aspose.drawing.PointF---) | 将此 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 表示的几何变换应用于指定的点数组。 |
| [transformPoints(Point[] pts)](#transformPoints-com.aspose.drawing.Point---) | 将此 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 表示的几何变换应用于指定的点数组。 |
| [multiply(Matrix matrix)](#multiply-com.aspose.drawing.drawing2d.Matrix-) | 通过在前面添加指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)，将此 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 与 `matrix` 参数中指定的矩阵相乘。 |
| [multiply(Matrix matrix, int order)](#multiply-com.aspose.drawing.drawing2d.Matrix-int-) | 将此 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 与 `matrix` 参数中指定的矩阵相乘，并按照 `order` 参数中指定的顺序进行。 |
| [rotate(float angle)](#rotate-float-) | 在此 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 前添加一个围绕原点、按指定角度的顺时针旋转。 |
| [rotate(float angle, int order)](#rotate-float-int-) | 对该 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 围绕原点（零 x 和 y 坐标）进行一个角度参数指定的顺时针旋转。 |
| [reset()](#reset--) | 将此 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 重置为单位矩阵的元素。 |
### Matrix() {#Matrix--}
```
public Matrix()
```


初始化 Matrix 类的新实例为单位矩阵。

### Matrix(float m11, float m12, float m21, float m22, float dx, float dy) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


使用指定的元素初始化 Matrix 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| m11 | 浮点数 | 新 Matrix 第一行第一列的值。 |
| m12 | 浮点数 | 新 Matrix 第一行第二列的值。 |
| m21 | 浮点数 | 新矩阵第二行第一列的值。 |
| m22 | 浮点数 | 新矩阵第二行第二列的值。 |
| dx | 浮点数 | 新矩阵第三行第一列的值。 |
| dy | 浮点数 | 新矩阵第三行第二列的值。 |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


将 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 类初始化为由指定矩形和点数组定义的几何变换的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 一个表示要转换的矩形的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |
| plgpts | [Point\[\]](../../com.aspose.drawing/point) | 一个包含三个 [Point](../../com.aspose.drawing/point) 结构的数组，表示要将矩形的左上、右上和左下角转换到的平行四边形的三个点。平行四边形的右下角由前面三个角推断得到。 |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


将 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 类初始化为由指定矩形和点数组定义的几何变换的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 一个表示要转换的矩形的 [RectangleF](../../com.aspose.drawing/rectanglef) 结构。 |
| plgpts | [PointF\[\]](../../com.aspose.drawing/pointf) | 一个包含三个 [PointF](../../com.aspose.drawing/pointf) 结构的数组，表示要将矩形的左上、右上和左下角转换到的平行四边形的三个点。平行四边形的右下角由前面三个角推断得到。 |

### IdentityTransform {#IdentityTransform}
```
public static final Matrix IdentityTransform
```


### getElements() {#getElements--}
```
public float[] getElements()
```


获取表示此 Matrix 元素的浮点值数组。

**Returns:**
float[] - 表示此矩阵元素的浮点值数组。
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


获取一个值，指示此 Matrix 是否为单位矩阵。

**Returns:**
boolean - 指示此矩阵是否为单位矩阵的值。
### isInvertible() {#isInvertible--}
```
public boolean isInvertible()
```


获取一个值，指示此 Matrix 是否可逆。

**Returns:**
boolean - 指示此矩阵是否可逆的值。
### getOffsetX() {#getOffsetX--}
```
public float getOffsetX()
```


获取此 Matrix 的 x 平移值（dx 值，或第三行第一列的元素）。

**Returns:**
float - 此矩阵的 x 平移值（dx 值，或第三行第一列的元素）。
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```


获取此 Matrix 的 y 平移值（`dy` 值，或第三行第二列的元素）。

**Returns:**
float - 此矩阵的 y 平移值（`dy` 值，或第三行第二列的元素）。
### dispose() {#dispose--}
```
public void dispose()
```


释放此 Matrix 使用的所有资源。

--------------------

此方法实际上不执行任何操作。它仅用于与 System.Drawing API 的兼容性。

### deepClone() {#deepClone--}
```
public Matrix deepClone()
```


创建此 Matrix 的精确副本。

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - The Matrix that this method creates.
### invert() {#invert--}
```
public void invert()
```


如果可逆，则对该 Matrix 进行求逆。

### translate(float offsetX, float offsetY) {#translate-float-float-}
```
public void translate(float offsetX, float offsetY)
```


通过在前面添加平移向量，将指定的平移向量（offsetX 和 offsetY）应用于此 Matrix。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| offsetX | 浮点数 | 用于平移此矩阵的 x 值。 |
| offsetY | 浮点数 | 用于平移此矩阵的 y 值。 |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


按照指定顺序将指定的平移向量应用于此 Matrix。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| offsetX | 浮点数 | 用于平移此矩阵的 x 值。 |
| offsetY | 浮点数 | 用于平移此矩阵的 y 值。 |
| 顺序 | int | 一个指定平移在此矩阵上应用顺序（追加或预置）的 MatrixOrder。 |

### transformVectors(PointF[] pts) {#transformVectors-com.aspose.drawing.PointF---}
```
public void transformVectors(PointF[] pts)
```


将数组中的每个向量乘以矩阵。此矩阵的平移元素（第三行）将被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | 一个表示要转换的点的 [PointF](../../com.aspose.drawing/pointf) 结构数组。 |

### scale(float scaleX, float scaleY) {#scale-float-float-}
```
public void scale(float scaleX, float scaleY)
```


通过在前面添加缩放向量，将指定的缩放向量应用于此 Matrix。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scaleX | 浮点数 | 此矩阵在 x 轴方向上的缩放值。 |
| scaleY | 浮点数 | 在 y 轴方向上缩放此 Matrix 的值。 |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


使用指定顺序，将指定的缩放向量（scaleX 和 scaleY）应用于此 Matrix。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scaleX | 浮点数 | 此矩阵在 x 轴方向上的缩放值。 |
| scaleY | 浮点数 | 在 y 轴方向上缩放此 Matrix 的值。 |
| 顺序 | int | 一个 MatrixOrder，指定将缩放向量应用于此 Matrix 的顺序（追加或预置）。 |

### shear(float shearX, float shearY) {#shear-float-float-}
```
public void shear(float shearX, float shearY)
```


通过在前面添加剪切变换，将指定的剪切向量应用于此 Matrix。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shearX | 浮点数 | 水平剪切因子。 |
| shearY | 浮点数 | 垂直剪切因子。 |

### shear(float shearX, float shearY, int order) {#shear-float-float-int-}
```
public void shear(float shearX, float shearY, int order)
```


按照指定顺序将指定的剪切向量应用于此 Matrix。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shearX | 浮点数 | 水平剪切因子。 |
| shearY | 浮点数 | 垂直剪切因子。 |
| 顺序 | int | 一个 MatrixOrder，指定剪切的应用顺序（追加或预置）。 |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.drawing.PointF-}
```
public void rotateAt(float angle, PointF point)
```


围绕 point 参数指定的点，通过在前面添加旋转，将顺时针旋转应用于此 Matrix。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 浮点数 | 旋转的角度（幅度），单位为度。 |
| point | [PointF](../../com.aspose.drawing/pointf) | 一个 PointF，表示旋转的中心。 |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.drawing.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


按照指定顺序围绕指定点将顺时针旋转应用于此 Matrix。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 浮点数 | 旋转的角度，单位为度。 |
| point | [PointF](../../com.aspose.drawing/pointf) | 一个 PointF，表示旋转的中心。 |
| 顺序 | int | 一个 MatrixOrder，指定旋转的应用顺序（追加或预置）。 |

### transformPoints(PointF[] pts) {#transformPoints-com.aspose.drawing.PointF---}
```
public void transformPoints(PointF[] pts)
```


将此 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 表示的几何变换应用于指定的点数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | 一个表示要转换的点的 [PointF](../../com.aspose.drawing/pointf) 结构数组。 |

### transformPoints(Point[] pts) {#transformPoints-com.aspose.drawing.Point---}
```
public void transformPoints(Point[] pts)
```


将此 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 表示的几何变换应用于指定的点数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pts | [Point\[\]](../../com.aspose.drawing/point) | 一个由 [Point](../../com.aspose.drawing/point) 结构组成的数组，表示要转换的点。 |

### multiply(Matrix matrix) {#multiply-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiply(Matrix matrix)
```


通过在前面添加指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)，将此 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 与 `matrix` 参数中指定的矩阵相乘。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 用于将此 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 相乘的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)。 |

### multiply(Matrix matrix, int order) {#multiply-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiply(Matrix matrix, int order)
```


将此 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 与 `matrix` 参数中指定的矩阵相乘，并按照 `order` 参数中指定的顺序进行。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 用于将此 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 相乘的 [Matrix](../../com.aspose.drawing.drawing2d/matrix)。 |
| order | int | 表示乘法顺序的 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)。 |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


在此 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 前添加一个围绕原点、按指定角度的顺时针旋转。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 浮点数 | 旋转的角度，单位为度。 |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


对该 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 围绕原点（零 x 和 y 坐标）进行一个角度参数指定的顺时针旋转。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 浮点数 | 旋转的角度，单位为度。 |
| order | int | 一个 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder)，指定将旋转应用于此 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 的顺序（追加或预置）。 |

### reset() {#reset--}
```
public void reset()
```


将此 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 重置为单位矩阵的元素。

