---
title: BitmapData
second_title: Aspose.Drawing for Java API 参考
description: 指定位图图像的属性。
type: docs
weight: 10
url: /zh/java/com.aspose.drawing.imaging/bitmapdata/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapData
```

指定位图图像的属性。[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) 类由 [Bitmap](../../com.aspose.drawing/bitmap) 类的 `E:Bitmap.LockBits` 和 `M:Bitmap.UnlockBits(BitmapData)` 方法使用。不可继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BitmapData()](#BitmapData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWidth()](#getWidth--) | 获取 [Bitmap](../../com.aspose.drawing/bitmap) 对象的像素宽度。 |
| [setWidth(int value)](#setWidth-int-) | 设置 [Bitmap](../../com.aspose.drawing/bitmap) 对象的像素宽度。 |
| [getHeight()](#getHeight--) | 获取 [Bitmap](../../com.aspose.drawing/bitmap) 对象的像素高度。 |
| [setHeight(int value)](#setHeight-int-) | 设置 [Bitmap](../../com.aspose.drawing/bitmap) 对象的像素高度。 |
| [getStride()](#getStride--) | 获取 [Bitmap](../../com.aspose.drawing/bitmap) 对象的跨距宽度（亦称扫描宽度）。 |
| [setStride(int value)](#setStride-int-) | 设置 [Bitmap](../../com.aspose.drawing/bitmap) 对象的跨距宽度（亦称扫描宽度）。 |
| [getPixelFormat()](#getPixelFormat--) | 获取返回此 [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) 对象的 [Bitmap](../../com.aspose.drawing/bitmap) 对象中像素信息的格式。 |
| [setPixelFormat(int value)](#setPixelFormat-int-) | 设置返回此 [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) 对象的 [Bitmap](../../com.aspose.drawing/bitmap) 对象中像素信息的格式。 |
| [getScan0()](#getScan0--) | 获取位图中第一个像素数据的地址。 |
| [setScan0(int[] value)](#setScan0-int---) | 设置位图中第一个像素数据的地址。 |
### BitmapData() {#BitmapData--}
```
public BitmapData()
```


### getWidth() {#getWidth--}
```
public int getWidth()
```


获取 [Bitmap](../../com.aspose.drawing/bitmap) 对象的像素宽度。这也可以视为一行扫描线中的像素数量。

**Returns:**
int - [Bitmap](../../com.aspose.drawing/bitmap) 对象的像素宽度。
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


设置 [Bitmap](../../com.aspose.drawing/bitmap) 对象的像素宽度。这也可以视为一行扫描线中的像素数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | [Bitmap](../../com.aspose.drawing/bitmap) 对象的像素宽度。 |

### getHeight() {#getHeight--}
```
public int getHeight()
```


获取 [Bitmap](../../com.aspose.drawing/bitmap) 对象的像素高度。有时也称为扫描线的数量。

**Returns:**
int - [Bitmap](../../com.aspose.drawing/bitmap) 对象的像素高度。
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


设置 [Bitmap](../../com.aspose.drawing/bitmap) 对象的像素高度。有时也称为扫描线的数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | [Bitmap](../../com.aspose.drawing/bitmap) 对象的像素高度。 |

### getStride() {#getStride--}
```
public int getStride()
```


获取 [Bitmap](../../com.aspose.drawing/bitmap) 对象的跨距宽度（亦称扫描宽度）。

**Returns:**
int - [Bitmap](../../com.aspose.drawing/bitmap) 对象的跨距宽度（以字节为单位）。
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


设置 [Bitmap](../../com.aspose.drawing/bitmap) 对象的跨距宽度（亦称扫描宽度）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | [Bitmap](../../com.aspose.drawing/bitmap) 对象的跨距宽度（也称为扫描宽度）。 |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


获取返回此 [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) 对象的 [Bitmap](../../com.aspose.drawing/bitmap) 对象中像素信息的格式。

**Returns:**
int - 一个 `PixelFormat`（[.getPixelFormat](../../null/\#getPixelFormat)/[.setPixelFormat(int)](../../null/\#setPixelFormat-int-)）指定关联的 [Bitmap](../../com.aspose.drawing/bitmap) 对象中像素信息的格式。
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


设置返回此 [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) 对象的 [Bitmap](../../com.aspose.drawing/bitmap) 对象中像素信息的格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 返回此 [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) 对象的 [Bitmap](../../com.aspose.drawing/bitmap) 对象中像素信息的格式。 |

### getScan0() {#getScan0--}
```
public int[] getScan0()
```


获取位图中第一个像素数据的地址。这也可以视为位图中的第一行扫描线。

**Returns:**
int[] - 位图中第一个像素数据的地址。
### setScan0(int[] value) {#setScan0-int---}
```
public void setScan0(int[] value)
```


设置位图中第一个像素数据的地址。这也可以视为位图中的第一行扫描线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] | 位图中第一个像素数据的地址。 |

