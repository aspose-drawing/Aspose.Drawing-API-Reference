---
title: TextureBrush
second_title: Aspose.Drawing for Java API 参考
description: 每个 TextureBrush 类的属性都是一个使用图像填充形状内部的 Brush 对象。
type: docs
weight: 53
url: /zh/java/com.aspose.drawing/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class TextureBrush extends Brush
```

TextureBrush 类的每个属性都是使用图像填充形状内部的 Brush 对象。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextureBrush(Image bitmap)](#TextureBrush-com.aspose.drawing.Image-) | 初始化使用指定图像的 [TextureBrush](../../com.aspose.drawing/texturebrush) 类的新实例。 |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.drawing.Image-int-) | 初始化使用指定图像和包装模式的 [TextureBrush](../../com.aspose.drawing/texturebrush) 类的新实例。 |
| [TextureBrush(Image image, int wrapMode, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-) | 初始化使用指定图像、包装模式和边界矩形的 [TextureBrush](../../com.aspose.drawing/texturebrush) 类的新实例。 |
| [TextureBrush(Image image, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-) | 初始化使用指定图像和边界矩形的 [TextureBrush](../../com.aspose.drawing/texturebrush) 类的新实例。 |
| [TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-) | 初始化使用指定图像、边界矩形和图像属性的 [TextureBrush](../../com.aspose.drawing/texturebrush) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getImage()](#getImage--) | 获取与此 TextureBrush 对象关联的 Image 对象。 |
| [getTransform()](#getTransform--) | 获取定义与此 TextureBrush 对象关联的图像的局部几何变换的 Matrix 对象的副本。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | 设置定义与此 TextureBrush 对象关联的图像的局部几何变换的 Matrix 对象的副本。 |
| [getWrapMode()](#getWrapMode--) | 获取指示此 TextureBrush 对象的平铺模式的 WrapMode 枚举。 |
| [setWrapMode(int value)](#setWrapMode-int-) | 设置指示此 TextureBrush 对象的平铺模式的 WrapMode 枚举。 |
| [deepClone()](#deepClone--) | 创建此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的精确副本。 |
| [resetTransform()](#resetTransform--) | 将此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的 Transform 属性重置为标识矩阵。 |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | 将表示此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象局部几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 对象乘以指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 对象，并在前面预置指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 对象。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | 将表示此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象局部几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 对象乘以指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 对象，按指定顺序进行。 |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 按指定的尺寸平移此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的局部几何变换。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 按指定的尺寸平移此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的局部几何变换，按指定顺序。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 按指定的量缩放此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的局部几何变换。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 按指定的量缩放此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的局部几何变换，按指定顺序。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | 按指定的角度旋转此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的局部几何变换。 |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 按指定的角度旋转此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的局部几何变换，按指定顺序。 |
### TextureBrush(Image bitmap) {#TextureBrush-com.aspose.drawing.Image-}
```
public TextureBrush(Image bitmap)
```


初始化使用指定图像的 [TextureBrush](../../com.aspose.drawing/texturebrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitmap | [Image](../../com.aspose.drawing/image) | 此 `Image`([.getImage](../../null/\#getImage)) 对象用于此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象填充内部。 |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.drawing.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


初始化使用指定图像和包装模式的 [TextureBrush](../../com.aspose.drawing/texturebrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | 该图像。 |
| wrapMode | int | 一个 `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) 枚举，指定此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的平铺方式。 |

### TextureBrush(Image image, int wrapMode, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF dstRect)
```


初始化使用指定图像、包装模式和边界矩形的 [TextureBrush](../../com.aspose.drawing/texturebrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | 该图像。 |
| wrapMode | int | 一个 `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) 枚举，指定此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的平铺方式。 |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | 一个 [RectangleF](../../com.aspose.drawing/rectanglef) 结构，表示此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的边界矩形。 |

### TextureBrush(Image image, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, RectangleF dstRect)
```


初始化使用指定图像和边界矩形的 [TextureBrush](../../com.aspose.drawing/texturebrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | 此 `Image`([.getImage](../../null/\#getImage)) 对象用于此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象填充内部。 |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | 一个 [RectangleF](../../com.aspose.drawing/rectanglef) 结构，表示此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的边界矩形。 |

### TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)
```


初始化使用指定图像、边界矩形和图像属性的 [TextureBrush](../../com.aspose.drawing/texturebrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | 用于此 TextureBrush 对象填充内部的 Image 对象。 |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | 一个 RectangleF 结构，表示此 TextureBrush 对象的边界矩形。 |
| imageAttr | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) | 一个 ImageAttributes 对象，包含有关此 TextureBrush 对象使用的图像的其他信息。 |

### getImage() {#getImage--}
```
public Image getImage()
```


获取与此 TextureBrush 对象关联的 Image 对象。

**Returns:**
[Image](../../com.aspose.drawing/image) - the Image object associated with this TextureBrush object.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


获取定义与此 TextureBrush 对象关联的图像的局部几何变换的 Matrix 对象的副本。

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - a copy of the Matrix object that defines a local geometric transformation for the image associated with this TextureBrush object.
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


设置定义与此 TextureBrush 对象关联的图像的局部几何变换的 Matrix 对象的副本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 一个定义与此 TextureBrush 对象关联的图像的局部几何变换的 Matrix 对象的副本。 |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


获取指示此 TextureBrush 对象的平铺模式的 WrapMode 枚举。

**Returns:**
int - 一个指示此 TextureBrush 对象的包装模式的 WrapMode 枚举。
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


设置指示此 TextureBrush 对象的平铺模式的 WrapMode 枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 一个指示此 TextureBrush 对象的包装模式的 WrapMode 枚举。 |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


创建此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的精确副本。

**Returns:**
java.lang.Object - 此方法创建的 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象，转换为 Object 对象。
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


将此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的 Transform 属性重置为标识矩阵。

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


将表示此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象局部几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 对象乘以指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 对象，并在前面预置指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 用于乘以几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 对象。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


将表示此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象局部几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 对象乘以指定的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 对象，按指定顺序进行。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 用于乘以几何变换的 [Matrix](../../com.aspose.drawing.drawing2d/matrix) 对象。 |
| order | int | 指定两个矩阵相乘顺序的 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) 枚举。 |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


按指定的尺寸平移此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的局部几何变换。此方法将在变换前添加平移。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | 浮点数 | 在 x 方向上平移变换的尺寸。 |
| dy | 浮点数 | 在 y 方向上平移变换的尺寸。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


按指定的尺寸平移此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的局部几何变换，按指定顺序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | 浮点数 | 在 x 方向上平移变换的尺寸。 |
| dy | 浮点数 | 在 y 方向上平移变换的尺寸。 |
| 顺序 | int | 应用平移的顺序（预先或追加）。 |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


按指定的量缩放此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的局部几何变换。此方法将在变换前添加缩放矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | 浮点数 | 在 x 方向上缩放变换的量。 |
| sy | 浮点数 | 在 y 方向上缩放变换的量。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


按指定的量缩放此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的局部几何变换，按指定顺序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | 浮点数 | 在 x 方向上缩放变换的量。 |
| sy | 浮点数 | 在 y 方向上缩放变换的量。 |
| order | int | 指定是追加还是在前面添加缩放矩阵的 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) 枚举。 |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


按指定的角度旋转此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的局部几何变换。此方法将在变换前添加旋转。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 浮点数 | 旋转角度。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


按指定的角度旋转此 [TextureBrush](../../com.aspose.drawing/texturebrush) 对象的局部几何变换，按指定顺序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 浮点数 | 旋转角度。 |
| order | int | 指定是追加还是在前面添加旋转矩阵的 [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) 枚举。 |

