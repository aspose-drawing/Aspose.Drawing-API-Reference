---
title: CopyPixelOperation
second_title: Aspose.Drawing for Java API 参考
description: 确定在复制像素操作中，源颜色如何与目标颜色合并以产生最终颜色。
type: docs
weight: 18
url: /zh/java/com.aspose.drawing/copypixeloperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CopyPixelOperation extends System.Enum
```

确定在复制像素操作中，源颜色如何与目标颜色合并以产生最终颜色。
## 字段

| 字段 | 描述 |
| --- | --- |
| [NoMirrorBitmap](#NoMirrorBitmap) | 位图未被镜像。 |
| [Blackness](#Blackness) | 目标区域使用物理调色板中索引 0 对应的颜色进行填充。 |
| [NotSourceErase](#NotSourceErase) | 源颜色和目标颜色使用布尔 `OR` 运算符进行组合，然后对结果颜色进行反转。 |
| [NotSourceCopy](#NotSourceCopy) | 已反转的源区域被复制到目标。 |
| [SourceErase](#SourceErase) | 目标区域的已反转颜色使用布尔 `AND` 运算符与源区域的颜色进行组合。 |
| [DestinationInvert](#DestinationInvert) | 目标区域被反转。 |
| [PatInvert](#PatInvert) | 在目标设备上下文中当前选中的画笔颜色使用布尔 `XOR` 运算符与目标颜色进行组合。 |
| [SourceInvert](#SourceInvert) | 源区域和目标区域的颜色使用布尔 `XOR` 运算符进行组合。 |
| [SourceAnd](#SourceAnd) | 源区域和目标区域的颜色使用布尔 `AND` 运算符进行组合。 |
| [MergePaint](#MergePaint) | 已反转的源区域颜色使用布尔 `OR` 运算符合并到目标区域的颜色中。 |
| [MergeCopy](#MergeCopy) | 源区域的颜色使用布尔 `AND` 运算符与目标设备上下文中选定的画笔颜色合并。 |
| [SourceCopy](#SourceCopy) | 源区域直接复制到目标区域。 |
| [SourcePaint](#SourcePaint) | 源区域和目标区域的颜色使用布尔 `OR` 运算符进行组合。 |
| [PatCopy](#PatCopy) | 在目标设备上下文中当前选中的画笔被复制到目标位图。 |
| [PatPaint](#PatPaint) | 在目标设备上下文中当前选中的画笔颜色使用布尔 `OR` 运算符与已反转的源区域颜色进行组合。 |
| [Whiteness](#Whiteness) | 目标区域使用物理调色板中索引 1 对应的颜色进行填充。 |
| [CaptureBlt](#CaptureBlt) | 位于您窗口之上层叠的窗口会包含在生成的图像中。 |
### NoMirrorBitmap {#NoMirrorBitmap}
```
public static final int NoMirrorBitmap
```


位图未被镜像。

### Blackness {#Blackness}
```
public static final int Blackness
```


目标区域使用物理调色板中索引 0 对应的颜色进行填充。（此颜色为默认物理调色板的黑色。）

### NotSourceErase {#NotSourceErase}
```
public static final int NotSourceErase
```


源颜色和目标颜色使用布尔 `OR` 运算符进行组合，然后对结果颜色进行反转。

### NotSourceCopy {#NotSourceCopy}
```
public static final int NotSourceCopy
```


已反转的源区域被复制到目标。

### SourceErase {#SourceErase}
```
public static final int SourceErase
```


目标区域的已反转颜色使用布尔 `AND` 运算符与源区域的颜色进行组合。

### DestinationInvert {#DestinationInvert}
```
public static final int DestinationInvert
```


目标区域被反转。

### PatInvert {#PatInvert}
```
public static final int PatInvert
```


在目标设备上下文中当前选中的画笔颜色使用布尔 `XOR` 运算符与目标颜色进行组合。

### SourceInvert {#SourceInvert}
```
public static final int SourceInvert
```


源区域和目标区域的颜色使用布尔 `XOR` 运算符进行组合。

### SourceAnd {#SourceAnd}
```
public static final int SourceAnd
```


源区域和目标区域的颜色使用布尔 `AND` 运算符进行组合。

### MergePaint {#MergePaint}
```
public static final int MergePaint
```


已反转的源区域颜色使用布尔 `OR` 运算符合并到目标区域的颜色中。

### MergeCopy {#MergeCopy}
```
public static final int MergeCopy
```


源区域的颜色使用布尔 `AND` 运算符与目标设备上下文中选定的画笔颜色合并。

### SourceCopy {#SourceCopy}
```
public static final int SourceCopy
```


源区域直接复制到目标区域。

### SourcePaint {#SourcePaint}
```
public static final int SourcePaint
```


源区域和目标区域的颜色使用布尔 `OR` 运算符进行组合。

### PatCopy {#PatCopy}
```
public static final int PatCopy
```


在目标设备上下文中当前选中的画笔被复制到目标位图。

### PatPaint {#PatPaint}
```
public static final int PatPaint
```


当前在目标设备上下文中选定的画笔颜色与使用布尔 `OR` 运算符的反转源区域颜色相结合。此操作的结果再使用布尔 `OR` 运算符与目标区域的颜色相结合。

### Whiteness {#Whiteness}
```
public static final int Whiteness
```


目标区域通过使用物理调色板中索引 1 对应的颜色进行填充。（默认物理调色板中此颜色为白色。）

### CaptureBlt {#CaptureBlt}
```
public static final int CaptureBlt
```


位于您窗口之上层叠的窗口会包含在生成的图像中。默认情况下，图像仅包含您的窗口。请注意，这通常不能用于打印设备上下文。

