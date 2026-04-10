---
title: 元文件
second_title: Aspose.Drawing for Java API 参考
description: 定义图形元文件。
type: docs
weight: 30
url: /zh/java/com.aspose.drawing.imaging/metafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public final class Metafile extends Image
```

定义图形元文件。元文件包含描述一系列图形操作的记录，这些操作可以被记录（构造）并回放（显示）。此类不可继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Metafile(byte[] henhmetafile, boolean deleteEmf)](#Metafile-byte---boolean-) | 使用指定的句柄初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。 |
| [Metafile(byte[] referenceHdc, int emfType)](#Metafile-byte---int-) | 使用指定的设备上下文句柄和一个指定 [Metafile](../../com.aspose.drawing.imaging/metafile) 格式的 [EmfType](../../com.aspose.drawing.imaging/emftype) 枚举，从句柄初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。 |
| [Metafile(String filename)](#Metafile-java.lang.String-) | 使用指定的文件名初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。 |
| [Metafile(String filename, byte[] referenceHdc)](#Metafile-java.lang.String-byte---) | 使用指定的文件名初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。 |
| [Metafile(InputStream stream)](#Metafile-java.io.InputStream-) | 使用指定的数据流初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。 |
| [Metafile(InputStream stream, byte[] referenceHdc)](#Metafile-java.io.InputStream-byte---) | 使用指定的数据流和指向设备上下文的 Windows 句柄初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。 |
| [Metafile(System.IO.Stream stream, int type)](#Metafile-com.aspose.ms.System.IO.Stream-int-) | 使用指定的数据流和指向设备上下文的 Windows 句柄初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。 |
| [Metafile(InputStream stream, byte[] referenceHdc, int type)](#Metafile-java.io.InputStream-byte---int-) | 使用指定的数据流、指向设备上下文的 Windows 句柄以及指定 [Metafile](../../com.aspose.drawing.imaging/metafile) 格式的 [EmfType](../../com.aspose.drawing.imaging/emftype) 枚举，初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。 |
| [Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)](#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-) | 使用指定的数据流、指向设备上下文的 Windows 句柄以及指定 [Metafile](../../com.aspose.drawing.imaging/metafile) 格式的 [EmfType](../../com.aspose.drawing.imaging/emftype) 枚举，初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWidth()](#getWidth--) | 获取此 [Metafile](../../com.aspose.drawing.imaging/metafile) 的宽度（以像素为单位）。 |
| [getHeight()](#getHeight--) | 获取此 [Metafile](../../com.aspose.drawing.imaging/metafile) 的高度（以像素为单位）。 |
| [getRawFormat()](#getRawFormat--) | 获取此 [Image](../../com.aspose.drawing/image) 的文件格式。 |
| [getPixelFormat()](#getPixelFormat--) | 获取此 [Image](../../com.aspose.drawing/image) 的像素格式。 |
| [getPalette()](#getPalette--) | 获取或设置此 [Image](../../com.aspose.drawing/image) 使用的颜色调色板。 |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | 获取或设置此 [Image](../../com.aspose.drawing/image) 使用的颜色调色板。 |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | 获取表示此 [Image](../../com.aspose.drawing/image) 中帧维度的 GUID 数组。 |
| [getPropertyIdList()](#getPropertyIdList--) | 获取存储在此 [Image](../../com.aspose.drawing/image) 中的属性项的 ID。 |
| [getPropertyItems()](#getPropertyItems--) | 获取存储在此 [Image](../../com.aspose.drawing/image) 中的所有属性项（元数据片段）。 |
| [getMetafileHeader(InputStream stream)](#getMetafileHeader-java.io.InputStream-) | 返回与指定的 [Metafile](../../com.aspose.drawing.imaging/metafile) 关联的 [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader)。 |
| [getMetafileHeader(String fileName)](#getMetafileHeader-java.lang.String-) | 返回与指定的 [Metafile](../../com.aspose.drawing.imaging/metafile) 关联的 [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader)。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | 此方法可旋转、翻转或同时旋转并翻转 [Image](../../com.aspose.drawing/image)。 |
| [getHenhmetafile()](#getHenhmetafile--) | 返回指向增强型 [Metafile](../../com.aspose.drawing.imaging/metafile) 的 Windows 句柄。 |
| [playRecord(int recordType, int flags, int dataSize, byte[] dataArray)](#playRecord-int-int-int-byte---) | 播放单个元文件记录。 |
| [getMetafileHeader()](#getMetafileHeader--) | 返回与此 [Metafile](../../com.aspose.drawing.imaging/metafile) 关联的 [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader)。 |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | 获取此 [Image](../../com.aspose.drawing/image) 中的指定属性项。 |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | 从此 [Image](../../com.aspose.drawing/image) 中移除指定的属性项。 |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | 在此 [Image](../../com.aspose.drawing/image) 中存储属性项（元数据片段）。 |
### Metafile(byte[] henhmetafile, boolean deleteEmf) {#Metafile-byte---boolean-}
```
public Metafile(byte[] henhmetafile, boolean deleteEmf)
```


使用指定的句柄初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| henhmetafile | byte[] | 一个指向增强型元文件的句柄。 |
| deleteEmf | boolean | 当 [Metafile](../../com.aspose.drawing.imaging/metafile) 被删除时，设为 true 以删除增强型元文件句柄；否则为 false。 |

### Metafile(byte[] referenceHdc, int emfType) {#Metafile-byte---int-}
```
public Metafile(byte[] referenceHdc, int emfType)
```


使用指定的设备上下文句柄和一个指定 [Metafile](../../com.aspose.drawing.imaging/metafile) 格式的 [EmfType](../../com.aspose.drawing.imaging/emftype) 枚举，从句柄初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| referenceHdc | byte[] | 设备上下文的句柄。 |
| emfType | int | 一个指定 [Metafile](../../com.aspose.drawing.imaging/metafile) 格式的 [EmfType](../../com.aspose.drawing.imaging/emftype)。 |

### Metafile(String filename) {#Metafile-java.lang.String-}
```
public Metafile(String filename)
```


使用指定的文件名初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | java.lang.String | 一个表示用于创建新 [Metafile](../../com.aspose.drawing.imaging/metafile) 的文件名的字符串。 |

### Metafile(String filename, byte[] referenceHdc) {#Metafile-java.lang.String-byte---}
```
public Metafile(String filename, byte[] referenceHdc)
```


使用指定的文件名初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | java.lang.String | 一个表示用于创建新 [Metafile](../../com.aspose.drawing.imaging/metafile) 的文件名的字符串。 |
| referenceHdc | byte[] | 指向设备上下文的 Windows 句柄。 |

### Metafile(InputStream stream) {#Metafile-java.io.InputStream-}
```
public Metafile(InputStream stream)
```


使用指定的数据流初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于创建新 [Metafile](../../com.aspose.drawing.imaging/metafile) 的 InputStream。 |

### Metafile(InputStream stream, byte[] referenceHdc) {#Metafile-java.io.InputStream-byte---}
```
public Metafile(InputStream stream, byte[] referenceHdc)
```


从指定的数据流和指向设备上下文的 Windows 句柄初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。/>。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 一个包含此 [Metafile](../../com.aspose.drawing.imaging/metafile) 数据的 InputStream。 |
| referenceHdc | byte[] | 指向 [Metafile](../../com.aspose.drawing.imaging/metafile) 对象的设备上下文的 Windows 句柄。 |

### Metafile(System.IO.Stream stream, int type) {#Metafile-com.aspose.ms.System.IO.Stream-int-}
```
public Metafile(System.IO.Stream stream, int type)
```


从指定的数据流和指向设备上下文的 Windows 句柄初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。/>。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 一个包含此 [Metafile](../../com.aspose.drawing.imaging/metafile) 数据的 InputStream。 |
| type | int | 必须为 int 1。 |

### Metafile(InputStream stream, byte[] referenceHdc, int type) {#Metafile-java.io.InputStream-byte---int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, int type)
```


使用指定的数据流、指向设备上下文的 Windows 句柄以及指定 [Metafile](../../com.aspose.drawing.imaging/metafile) 格式的 [EmfType](../../com.aspose.drawing.imaging/emftype) 枚举，初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 一个包含此 [Metafile](../../com.aspose.drawing.imaging/metafile) 数据的 InputStream。 |
| referenceHdc | byte[] | 指向设备上下文的 Windows 句柄。 |
| type | int | 一个指定 [Metafile](../../com.aspose.drawing.imaging/metafile) 格式的 [EmfType](../../com.aspose.drawing.imaging/emftype)。 |

### Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type) {#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)
```


使用指定的数据流、指向设备上下文的 Windows 句柄以及指定 [Metafile](../../com.aspose.drawing.imaging/metafile) 格式的 [EmfType](../../com.aspose.drawing.imaging/emftype) 枚举，初始化 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 一个包含此 [Metafile](../../com.aspose.drawing.imaging/metafile) 数据的 InputStream。 |
| referenceHdc | byte[] | 指向设备上下文的 Windows 句柄。 |
| frameRect | [RectangleF](../../com.aspose.drawing/rectanglef) | 一个表示界定新 [Metafile](../../com.aspose.drawing.imaging/metafile) 的矩形的 [Rectangle](../../com.aspose.drawing/rectangle)。 |
| frameUnit | int | 一个指定 frameRect 测量单位的 [MetafileFrameUnit](../../com.aspose.drawing.imaging/metafileframeunit)。 |
| type | int | 一个指定 [Metafile](../../com.aspose.drawing.imaging/metafile) 格式的 [EmfType](../../com.aspose.drawing.imaging/emftype)。 |

### getWidth() {#getWidth--}
```
public int getWidth()
```


获取此 [Metafile](../../com.aspose.drawing.imaging/metafile) 的宽度（以像素为单位）。

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取此 [Metafile](../../com.aspose.drawing.imaging/metafile) 的高度（以像素为单位）。

**Returns:**
int - 此 [Metafile](../../com.aspose.drawing.imaging/metafile) 的高度（以像素为单位）。
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
### getMetafileHeader(InputStream stream) {#getMetafileHeader-java.io.InputStream-}
```
public static MetafileHeader getMetafileHeader(InputStream stream)
```


返回与指定的 [Metafile](../../com.aspose.drawing.imaging/metafile) 关联的 [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 一个包含要检索其头部的 [Metafile](../../com.aspose.drawing.imaging/metafile) 的 InputStream。 |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### getMetafileHeader(String fileName) {#getMetafileHeader-java.lang.String-}
```
public static MetafileHeader getMetafileHeader(String fileName)
```


返回与指定的 [Metafile](../../com.aspose.drawing.imaging/metafile) 关联的 [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 一个包含要检索其头部的 [Metafile](../../com.aspose.drawing.imaging/metafile) 名称的字符串。 |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


此方法可旋转、翻转或同时旋转并翻转 [Image](../../com.aspose.drawing/image)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | int | 一个指定对图像应用的旋转和翻转类型的 [RotateFlipType](../../com.aspose.drawing/rotatefliptype) 成员。 |

### getHenhmetafile() {#getHenhmetafile--}
```
public System.IntPtr getHenhmetafile()
```


返回指向增强型 [Metafile](../../com.aspose.drawing.imaging/metafile) 的 Windows 句柄。

**Returns:**
com.aspose.ms.System.IntPtr - 指向此增强型 [Metafile](../../com.aspose.drawing.imaging/metafile) 的 Windows 句柄。
### playRecord(int recordType, int flags, int dataSize, byte[] dataArray) {#playRecord-int-int-int-byte---}
```
public void playRecord(int recordType, int flags, int dataSize, byte[] dataArray)
```


播放单个元文件记录。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recordType | int | 表示正在播放的元文件记录类型的 [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) 元素。 |
| flags | int | 指定记录属性的一组标志。 |
| dataSize | int | 记录数据中的字节数。 |
| dataArray | byte[] | 包含记录数据的字节数组。 |

### getMetafileHeader() {#getMetafileHeader--}
```
public MetafileHeader getMetafileHeader()
```


返回与此 [Metafile](../../com.aspose.drawing.imaging/metafile) 关联的 [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader)。

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile).
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

