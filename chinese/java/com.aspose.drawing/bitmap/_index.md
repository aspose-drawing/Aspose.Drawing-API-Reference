---
title: 位图
second_title: Aspose.Drawing for Java API 参考
description: 封装一个位图，该位图由图形图像的像素数据及其属性组成。
type: docs
weight: 10
url: /zh/java/com.aspose.drawing/bitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public class Bitmap extends Image
```

封装一个位图，该位图由图形图像的像素数据及其属性组成。一个 [Bitmap](../../com.aspose.drawing/bitmap) 是用于处理由像素数据定义的图像的对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Bitmap(int width, int height)](#Bitmap-int-int-) | 使用指定的大小初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。 |
| [Bitmap(String filename)](#Bitmap-java.lang.String-) | 从指定的文件初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。 |
| [Bitmap(String filename, boolean useIcm)](#Bitmap-java.lang.String-boolean-) | 从指定的文件初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。 |
| [Bitmap(InputStream stream)](#Bitmap-java.io.InputStream-) | 从指定的数据流初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。 |
| [Bitmap(InputStream stream, boolean useIcm)](#Bitmap-java.io.InputStream-boolean-) | 从指定的数据流初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。 |
| [Bitmap(int width, int height, int format)](#Bitmap-int-int-int-) | 使用指定的大小和格式初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。 |
| [Bitmap(int width, int height, int stride, int format, int[] data)](#Bitmap-int-int-int-int-int---) | 使用指定的大小和像素数据初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。 |
| [Bitmap(Image original)](#Bitmap-com.aspose.drawing.Image-) | 从指定的现有图像初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。 |
| [Bitmap(Image original, Size newSize)](#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-) | 从指定的现有图像初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例，并按指定大小进行缩放。 |
| [Bitmap(Image original, int width, int height)](#Bitmap-com.aspose.drawing.Image-int-int-) | 从指定的现有图像初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例，并按指定大小进行缩放。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWidth()](#getWidth--) | 获取此位图的宽度（以像素为单位）。 |
| [getHeight()](#getHeight--) | 获取此位图的高度（以像素为单位）。 |
| [getRawFormat()](#getRawFormat--) | 获取此 [Image](../../com.aspose.drawing/image) 的文件格式。 |
| [getPixelFormat()](#getPixelFormat--) | 获取此 [Image](../../com.aspose.drawing/image) 的像素格式。 |
| [getPalette()](#getPalette--) | 获取或设置此 [Image](../../com.aspose.drawing/image) 使用的颜色调色板。 |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | 获取或设置此 [Image](../../com.aspose.drawing/image) 使用的颜色调色板。 |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | 获取表示此 [Image](../../com.aspose.drawing/image) 中帧维度的 GUID 数组。 |
| [getPropertyIdList()](#getPropertyIdList--) | 获取存储在此 [Image](../../com.aspose.drawing/image) 中的属性项的 ID。 |
| [getPropertyItems()](#getPropertyItems--) | 获取存储在此 [Image](../../com.aspose.drawing/image) 中的所有属性项（元数据片段）。 |
| [deepClone(Rectangle rect, int format)](#deepClone-com.aspose.drawing.Rectangle-int-) | 创建此 [Bitmap](../../com.aspose.drawing/bitmap) 的一个副本，该副本由 [Rectangle](../../com.aspose.drawing/rectangle) 结构定义，并使用指定的 `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 枚举。 |
| [deepClone(RectangleF rect, int format)](#deepClone-com.aspose.drawing.RectangleF-int-) | 创建此 [Bitmap](../../com.aspose.drawing/bitmap) 的一个副本，该副本使用指定的 [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) 枚举定义。 |
| [setResolution(float xDpi, float yDpi)](#setResolution-float-float-) | 设置此 [Bitmap](../../com.aspose.drawing/bitmap) 的分辨率。 |
| [lockBits(Rectangle rect, int flags, int format)](#lockBits-com.aspose.drawing.Rectangle-int-int-) | 将 [Bitmap](../../com.aspose.drawing/bitmap) 锁定到系统内存中。 |
| [unlockBits(BitmapData bitmapData)](#unlockBits-com.aspose.drawing.imaging.BitmapData-) | 从系统内存中解锁此 [Bitmap](../../com.aspose.drawing/bitmap)。 |
| [getPixel(int x, int y)](#getPixel-int-int-) | 获取此 [Bitmap](../../com.aspose.drawing/bitmap) 中指定像素的颜色。 |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.drawing.Color-) | 设置此 [Bitmap](../../com.aspose.drawing/bitmap) 中指定像素的颜色。 |
| [readArgb32Pixels(int[] pixels)](#readArgb32Pixels-int---) | 以 ARGB32 格式读取位图像素到给定数组中。 |
| [writeArgb32Pixels(int[] pixels)](#writeArgb32Pixels-int---) | 将像素写入位图。 |
| [makeTransparent()](#makeTransparent--) | 使此 [Bitmap](../../com.aspose.drawing/bitmap) 中的指定颜色透明。 |
| [makeTransparent(Color transparentColor)](#makeTransparent-com.aspose.drawing.Color-) | 使此 [Bitmap](../../com.aspose.drawing/bitmap) 中的指定颜色透明。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | 此方法可旋转、翻转或同时旋转并翻转 [Image](../../com.aspose.drawing/image)。 |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | 获取此 [Image](../../com.aspose.drawing/image) 中的指定属性项。 |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | 从此 [Image](../../com.aspose.drawing/image) 中移除指定的属性项。 |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | 在此 [Image](../../com.aspose.drawing/image) 中存储属性项（元数据片段）。 |
### Bitmap(int width, int height) {#Bitmap-int-int-}
```
public Bitmap(int width, int height)
```


使用指定的大小初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 新 Bitmap 的宽度（以像素为单位）。 |
|  | 高度 | int | 新 Bitmap 的高度（以像素为单位）。 |

--------------------

目前唯一支持的内部位图格式等同于 `PixelFormat.Format32bppPArgb`。 |

### Bitmap(String filename) {#Bitmap-java.lang.String-}
```
public Bitmap(String filename)
```


从指定的文件初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 位图文件的名称。 |

### Bitmap(String filename, boolean useIcm) {#Bitmap-java.lang.String-boolean-}
```
public Bitmap(String filename, boolean useIcm)
```


从指定的文件初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 位图文件的名称。 |
| useIcm | boolean | true 表示对该 [Bitmap](../../com.aspose.drawing/bitmap) 使用颜色校正；否则为 false。 |

### Bitmap(InputStream stream) {#Bitmap-java.io.InputStream-}
```
public Bitmap(InputStream stream)
```


从指定的数据流初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 用于加载图像的数据流。 |

### Bitmap(InputStream stream, boolean useIcm) {#Bitmap-java.io.InputStream-boolean-}
```
public Bitmap(InputStream stream, boolean useIcm)
```


从指定的数据流初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 用于加载图像的数据流。 |
| useIcm | boolean | `true` 表示对该 [Bitmap](../../com.aspose.drawing/bitmap) 使用颜色校正；否则为 `false`。 |

### Bitmap(int width, int height, int format) {#Bitmap-int-int-int-}
```
public Bitmap(int width, int height, int format)
```


使用指定的大小和格式初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 新 [Bitmap](../../com.aspose.drawing/bitmap) 的宽度（以像素为单位）。 |
| height | int | 新 [Bitmap](../../com.aspose.drawing/bitmap) 的高度（以像素为单位）。 |
| format | int | 新 [Bitmap](../../com.aspose.drawing/bitmap) 的 `PixelFormat`（[Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)）枚举。 |

### Bitmap(int width, int height, int stride, int format, int[] data) {#Bitmap-int-int-int-int-int---}
```
public Bitmap(int width, int height, int stride, int format, int[] data)
```


使用指定的大小和像素数据初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 新 [Bitmap](../../com.aspose.drawing/bitmap) 的宽度（以像素为单位）。 |
| height | int | 新 [Bitmap](../../com.aspose.drawing/bitmap) 的高度（以像素为单位）。 |
| 步幅 | int | 每条扫描线起始之间的字节偏移量，必须是四的倍数。 |
| format | int | 新 [Bitmap](../../com.aspose.drawing/bitmap) 的 `PixelFormat`（[Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)）枚举。 |
| 数据 | int[] | 像素数据。 |

### Bitmap(Image original) {#Bitmap-com.aspose.drawing.Image-}
```
public Bitmap(Image original)
```


从指定的现有图像初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | 用于创建新 [Bitmap](../../com.aspose.drawing/bitmap) 的 [Image](../../com.aspose.drawing/image)。 |

### Bitmap(Image original, Size newSize) {#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-}
```
public Bitmap(Image original, Size newSize)
```


从指定的现有图像初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例，并按指定大小进行缩放。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | 用于创建新 [Bitmap](../../com.aspose.drawing/bitmap) 的 [Image](../../com.aspose.drawing/image) |
| newSize | [Size](../../com.aspose.drawing/size) | 表示新 [Bitmap](../../com.aspose.drawing/bitmap) 大小的 `Size`([Image.getSize](../../com.aspose.drawing/image\#getSize)) 结构。 |

### Bitmap(Image original, int width, int height) {#Bitmap-com.aspose.drawing.Image-int-int-}
```
public Bitmap(Image original, int width, int height)
```


从指定的现有图像初始化 [Bitmap](../../com.aspose.drawing/bitmap) 类的新实例，并按指定大小进行缩放。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | 用于创建新 [Bitmap](../../com.aspose.drawing/bitmap) 的 [Image](../../com.aspose.drawing/image)。 |
| width | int | 新 [Bitmap](../../com.aspose.drawing/bitmap) 的宽度（以像素为单位）。 |
| height | int | 新 [Bitmap](../../com.aspose.drawing/bitmap) 的高度（以像素为单位）。 |

### getWidth() {#getWidth--}
```
public int getWidth()
```


获取此位图的宽度（以像素为单位）。

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取此位图的高度（以像素为单位）。

**Returns:**
int
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


获取此 [Image](../../com.aspose.drawing/image) 的文件格式。

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


获取此 [Image](../../com.aspose.drawing/image) 的像素格式。

**Returns:**
int - 表示此 [Image](../../com.aspose.drawing/image) 像素格式的 `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat))。
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


获取或设置此 [Image](../../com.aspose.drawing/image) 使用的颜色调色板。

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


获取或设置此 [Image](../../com.aspose.drawing/image) 使用的颜色调色板。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


获取表示此 [Image](../../com.aspose.drawing/image) 中帧维度的 GUID 数组。

**Returns:**
java.util.UUID[] - 一个从最高位到最低位指定此 [Image](../../com.aspose.drawing/image) 中帧尺寸的 GUID 数组。
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


获取存储在此 [Image](../../com.aspose.drawing/image) 中的属性项的 ID。

**Returns:**
int[] - 一个属性 ID 数组，每个属性项在此图像中存储一个对应的 ID。
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


获取存储在此 [Image](../../com.aspose.drawing/image) 中的所有属性项（元数据片段）。

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] - 一个 [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) 对象数组，每个属性项在图像中存储一个对象。
### deepClone(Rectangle rect, int format) {#deepClone-com.aspose.drawing.Rectangle-int-}
```
public final Bitmap deepClone(Rectangle rect, int format)
```


创建此 [Bitmap](../../com.aspose.drawing/bitmap) 的一个副本，该副本由 [Rectangle](../../com.aspose.drawing/rectangle) 结构定义，并使用指定的 `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 定义要从此 [Bitmap](../../com.aspose.drawing/bitmap) 复制的区域。坐标相对于此 [Bitmap](../../com.aspose.drawing/bitmap)。 |
| format | int | 指定目标 [Bitmap](../../com.aspose.drawing/bitmap) 的 `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 枚举。 |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The new [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### deepClone(RectangleF rect, int format) {#deepClone-com.aspose.drawing.RectangleF-int-}
```
public final Bitmap deepClone(RectangleF rect, int format)
```


创建此 [Bitmap](../../com.aspose.drawing/bitmap) 的一个副本，该副本使用指定的 [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) 枚举定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 定义此 [Bitmap](../../com.aspose.drawing/bitmap) 要复制的区域。 |
| format | int | 指定目标 [Bitmap](../../com.aspose.drawing/bitmap) 的 [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) 枚举。 |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### setResolution(float xDpi, float yDpi) {#setResolution-float-float-}
```
public final void setResolution(float xDpi, float yDpi)
```


设置此 [Bitmap](../../com.aspose.drawing/bitmap) 的分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xDpi | float | [Bitmap](../../com.aspose.drawing/bitmap) 的水平分辨率（每英寸点数）。 |
| yDpi | float | [Bitmap](../../com.aspose.drawing/bitmap) 的垂直分辨率（每英寸点数）。 |

### lockBits(Rectangle rect, int flags, int format) {#lockBits-com.aspose.drawing.Rectangle-int-int-}
```
public final BitmapData lockBits(Rectangle rect, int flags, int format)
```


将 [Bitmap](../../com.aspose.drawing/bitmap) 锁定到系统内存中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 指定要锁定的 [Bitmap](../../com.aspose.drawing/bitmap) 区域的 [Rectangle](../../com.aspose.drawing/rectangle) 结构。 |
| flags | int | 指定 [Bitmap](../../com.aspose.drawing/bitmap) 访问级别（读取/写入）的 [ImageLockMode](../../com.aspose.drawing.imaging/imagelockmode) 枚举。 |
| format | int | 指定此 [Bitmap](../../com.aspose.drawing/bitmap) 数据格式的 `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) 枚举。 |

**Returns:**
[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) - A [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) containing information about this lock operation.
### unlockBits(BitmapData bitmapData) {#unlockBits-com.aspose.drawing.imaging.BitmapData-}
```
public final void unlockBits(BitmapData bitmapData)
```


从系统内存中解锁此 [Bitmap](../../com.aspose.drawing/bitmap)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitmapData | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) | 指定锁定操作信息的 [BitmapData](../../com.aspose.drawing.imaging/bitmapdata)。 |

### getPixel(int x, int y) {#getPixel-int-int-}
```
public final Color getPixel(int x, int y)
```


获取此 [Bitmap](../../com.aspose.drawing/bitmap) 中指定像素的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 要检索的像素的 x 坐标。 |
| y | int | 要检索的像素的 y 坐标。 |

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) structure that represents the color of the specified pixel.
### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.drawing.Color-}
```
public final void setPixel(int x, int y, Color color)
```


设置此 [Bitmap](../../com.aspose.drawing/bitmap) 中指定像素的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 要设置的像素的 x 坐标。 |
| y | int | 要设置的像素的 y 坐标。 |
| color | [Color](../../com.aspose.drawing/color) | 表示要分配给指定像素的颜色的 [Color](../../com.aspose.drawing/color) 结构。 |

### readArgb32Pixels(int[] pixels) {#readArgb32Pixels-int---}
```
public final void readArgb32Pixels(int[] pixels)
```


以 ARGB32 格式读取位图像素到给定数组中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | int[] | 用于放置位图像素的数组。必须具有足够的容量。 |

### writeArgb32Pixels(int[] pixels) {#writeArgb32Pixels-int---}
```
public final void writeArgb32Pixels(int[] pixels)
```


将像素写入位图。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | int[] | 包含 ARGB32 格式源像素的数组。必须具有足够的长度。 |

### makeTransparent() {#makeTransparent--}
```
public final void makeTransparent()
```


使此 [Bitmap](../../com.aspose.drawing/bitmap) 中的指定颜色透明。

### makeTransparent(Color transparentColor) {#makeTransparent-com.aspose.drawing.Color-}
```
public final void makeTransparent(Color transparentColor)
```


使此 [Bitmap](../../com.aspose.drawing/bitmap) 中的指定颜色透明。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| transparentColor | [Color](../../com.aspose.drawing/color) | 表示要设为透明的颜色的 [Color](../../com.aspose.drawing/color) 结构。 |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


此方法可旋转、翻转或同时旋转并翻转 [Image](../../com.aspose.drawing/image)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | int | 一个指定对图像应用的旋转和翻转类型的 [RotateFlipType](../../com.aspose.drawing/rotatefliptype) 成员。 |

### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


获取此 [Image](../../com.aspose.drawing/image) 中的指定属性项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propid | int | 要获取的属性项的 ID。 |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


从此 [Image](../../com.aspose.drawing/image) 中移除指定的属性项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propid | int | 要移除的属性项的 ID。 |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


在此 [Image](../../com.aspose.drawing/image) 中存储属性项（元数据片段）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | 要存储的 [PropertyItem](../../com.aspose.drawing.imaging/propertyitem)。 |

