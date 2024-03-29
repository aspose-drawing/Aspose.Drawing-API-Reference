---
title: Bitmap
second_title: Aspose.Drawing for .NET API 参考
description: 初始化Bitmapsystem.drawing/bitmap具有指定大小的类
type: docs
weight: 10
url: /zh/net/system.drawing/bitmap/bitmap/
---
## Bitmap(int, int) {#constructor}

初始化[`Bitmap`](../../bitmap)具有指定大小的类。

```csharp
public Bitmap(int width, int height)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 新位图的宽度（以像素为单位）。 |
| height | Int32 | 新位图的高度（以像素为单位）。 |

### 评论

目前唯一支持的内部位图格式相当于`PixelFormat.Format32bppPArgb`.

### 也可以看看

* class [Bitmap](../../bitmap)
* 命名空间 [System.Drawing](../../bitmap)
* 部件 [Aspose.Drawing](../../../)

---

## Bitmap(string) {#constructor_8}

初始化[`Bitmap`](../../bitmap)来自指定文件的类。

```csharp
public Bitmap(string filename)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filename | String | 位图文件的名称。 |

### 也可以看看

* class [Bitmap](../../bitmap)
* 命名空间 [System.Drawing](../../bitmap)
* 部件 [Aspose.Drawing](../../../)

---

## Bitmap(string, bool) {#constructor_9}

初始化[`Bitmap`](../../bitmap)来自指定文件的类。

```csharp
public Bitmap(string filename, bool useIcm)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filename | String | 位图文件的名称。 |
| useIcm | Boolean | true 对此使用颜色校正Bitmap;否则为假。 |

### 也可以看看

* class [Bitmap](../../bitmap)
* 命名空间 [System.Drawing](../../bitmap)
* 部件 [Aspose.Drawing](../../../)

---

## Bitmap(Stream) {#constructor_6}

初始化[`Bitmap`](../../bitmap)来自指定数据流的类。

```csharp
public Bitmap(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像的数据流。 |

### 也可以看看

* class [Bitmap](../../bitmap)
* 命名空间 [System.Drawing](../../bitmap)
* 部件 [Aspose.Drawing](../../../)

---

## Bitmap(Stream, bool) {#constructor_7}

初始化[`Bitmap`](../../bitmap)来自指定数据流的类。

```csharp
public Bitmap(Stream stream, bool useIcm)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像的数据流。 |
| useIcm | Boolean | `真的`为此使用颜色校正Bitmap;否则，`错误的`. |

### 也可以看看

* class [Bitmap](../../bitmap)
* 命名空间 [System.Drawing](../../bitmap)
* 部件 [Aspose.Drawing](../../../)

---

## Bitmap(int, int, PixelFormat) {#constructor_2}

初始化[`Bitmap`](../../bitmap)具有指定大小和格式的类。

```csharp
public Bitmap(int width, int height, PixelFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 新的宽度，以像素为单位Bitmap. |
| height | Int32 | 新的高度，以像素为单位Bitmap. |
| format | PixelFormat | 这PixelFormat新的枚举Bitmap. |

### 也可以看看

* enum [PixelFormat](../../../system.drawing.imaging/pixelformat)
* class [Bitmap](../../bitmap)
* 命名空间 [System.Drawing](../../bitmap)
* 部件 [Aspose.Drawing](../../../)

---

## Bitmap(int, int, int, PixelFormat, int[]) {#constructor_1}

初始化[`Bitmap`](../../bitmap)具有指定大小和像素数据的类。

```csharp
public Bitmap(int width, int height, int stride, PixelFormat format, int[] data)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 新的宽度，以像素为单位Bitmap. |
| height | Int32 | 新的高度，以像素为单位Bitmap. |
| stride | Int32 | 一个扫描线的开头和下一个扫描线之间的字节偏移量必须是四的倍数。 |
| format | PixelFormat | 这PixelFormat新的枚举Bitmap. |
| data | Int32[] | 像素数据。 |

### 也可以看看

* enum [PixelFormat](../../../system.drawing.imaging/pixelformat)
* class [Bitmap](../../bitmap)
* 命名空间 [System.Drawing](../../bitmap)
* 部件 [Aspose.Drawing](../../../)

---

## Bitmap(Image) {#constructor_3}

初始化[`Bitmap`](../../bitmap)来自指定的现有图像的类。

```csharp
public Bitmap(Image original)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| original | Image | 这Image从中创建新的Bitmap. |

### 也可以看看

* class [Image](../../image)
* class [Bitmap](../../bitmap)
* 命名空间 [System.Drawing](../../bitmap)
* 部件 [Aspose.Drawing](../../../)

---

## Bitmap(Image, Size) {#constructor_5}

初始化[`Bitmap`](../../bitmap)来自指定的现有图像的类，缩放到指定的大小。

```csharp
public Bitmap(Image original, Size newSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| original | Image | 这Image从中创建新的Bitmap |
| newSize | Size | 这Size代表新的大小的结构Bitmap. |

### 也可以看看

* class [Image](../../image)
* struct [Size](../../size)
* class [Bitmap](../../bitmap)
* 命名空间 [System.Drawing](../../bitmap)
* 部件 [Aspose.Drawing](../../../)

---

## Bitmap(Image, int, int) {#constructor_4}

初始化[`Bitmap`](../../bitmap)来自指定现有图像的类， 缩放到指定大小。

```csharp
public Bitmap(Image original, int width, int height)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| original | Image | 这Image从中创建新的Bitmap. |
| width | Int32 | 新的宽度，以像素为单位Bitmap. |
| height | Int32 | 新的高度，以像素为单位Bitmap. |

### 也可以看看

* class [Image](../../image)
* class [Bitmap](../../bitmap)
* 命名空间 [System.Drawing](../../bitmap)
* 部件 [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
