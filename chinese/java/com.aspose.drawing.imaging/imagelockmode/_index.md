---
title: ImageLockMode
second_title: Aspose.Drawing for Java API 参考
description: 指定传递给 flags 参数的标志。
type: docs
weight: 28
url: /zh/java/com.aspose.drawing.imaging/imagelockmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageLockMode extends System.Enum
```

指定传递给 flags 参数的标志，使用 [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) 方法。该 [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) 方法锁定图像的一部分，以便您可以读取或写入像素数据。
## 字段

| 字段 | 描述 |
| --- | --- |
| [ReadOnly](#ReadOnly) | 指定图像的一部分被锁定用于读取。 |
| [WriteOnly](#WriteOnly) | 指定图像的一部分被锁定用于写入。 |
| [ReadWrite](#ReadWrite) | 指定图像的一部分被锁定用于读取或写入。 |
| [UserInputBuffer](#UserInputBuffer) | 指定用于读取或写入像素数据的缓冲区由用户分配。 |
### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


指定图像的一部分被锁定用于读取。

### WriteOnly {#WriteOnly}
```
public static final int WriteOnly
```


指定图像的一部分被锁定用于写入。

### ReadWrite {#ReadWrite}
```
public static final int ReadWrite
```


指定图像的一部分被锁定用于读取或写入。

### UserInputBuffer {#UserInputBuffer}
```
public static final int UserInputBuffer
```


指定用于读取或写入像素数据的缓冲区由用户分配。如果设置了此标志，`flags` 参数在 [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) 方法中用作输入参数（也可能用作输出参数）。如果清除此标志，则 `flags` 参数仅用作输出参数。

