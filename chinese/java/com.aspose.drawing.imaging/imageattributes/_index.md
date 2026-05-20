---
title: ImageAttributes
second_title: Aspose.Drawing for Java API 参考
description: 包含有关在渲染过程中如何操作位图和元文件颜色的信息。
type: docs
weight: 24
url: /zh/java/com.aspose.drawing.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class ImageAttributes implements System.IDisposable
```

包含有关在渲染过程中如何操作位图和元文件颜色的信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | 初始化 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [dispose()](#dispose--) | 释放此 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 对象使用的所有资源。 |
| [deepClone()](#deepClone--) | 创建此 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 对象的精确副本。 |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | 为默认类别设置颜色调整矩阵。 |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | 为默认类别设置颜色调整矩阵。 |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | 为指定类别设置颜色调整矩阵。 |
| [clearColorMatrix()](#clearColorMatrix--) | 清除默认类别的颜色调整矩阵。 |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | 清除指定类别的颜色调整矩阵。 |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | 为默认类别设置颜色调整矩阵和灰度调整矩阵。 |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | 为默认类别设置颜色调整矩阵和灰度调整矩阵。 |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | 为指定类别设置颜色调整矩阵和灰度调整矩阵。 |
| [setThreshold(float threshold)](#setThreshold-float-) | 为默认类别设置阈值（透明度范围）。 |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | 为指定类别设置阈值（透明度范围）。 |
| [clearThreshold()](#clearThreshold--) | 清除默认类别的阈值。 |
| [clearThreshold(int type)](#clearThreshold-int-) | 清除指定类别的阈值。 |
| [setGamma(float gamma)](#setGamma-float-) | 为默认类别设置伽马值。 |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | 为指定类别设置伽马值。 |
| [clearGamma()](#clearGamma--) | 禁用默认类别的伽马校正。 |
| [clearGamma(int type)](#clearGamma-int-) | 禁用指定类别的伽马校正。 |
| [setNoOp()](#setNoOp--) | 关闭默认类别的颜色调整。 |
| [setNoOp(int type)](#setNoOp-int-) | 关闭指定类别的颜色调整。 |
| [clearNoOp()](#clearNoOp--) | 清除默认类别的 NoOp 设置。 |
| [clearNoOp(int type)](#clearNoOp-int-) | 清除指定类别的 NoOp 设置。 |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-) | 为默认类别设置颜色键。 |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | 为指定类别设置颜色键（透明度范围）。 |
| [clearColorKey()](#clearColorKey--) | 清除默认类别的颜色键（透明度范围）。 |
| [clearColorKey(int type)](#clearColorKey-int-) | 清除指定类别的颜色键（透明度范围）。 |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | 为默认类别设置 CMYK（青-品红-黄-黑）输出通道。 |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | 为指定类别设置 CMYK（青-品红-黄-黑）输出通道。 |
| [clearOutputChannel()](#clearOutputChannel--) | 清除默认类别的 CMYK（青-品红-黄-黑）输出通道设置。 |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | 清除指定类别的（青-品红-黄-黑）输出通道设置。 |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | 为默认类别设置输出通道色彩配置文件。 |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | 为指定类别设置输出通道颜色配置文件。 |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | 清除默认类别的输出通道颜色配置设置。 |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | 清除指定类别的输出通道颜色配置设置。 |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---) | 为默认类别设置颜色重新映射表。 |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-) | 为指定类别设置颜色重新映射表。 |
| [clearRemapTable()](#clearRemapTable--) | 清除默认类别的颜色重新映射表。 |
| [clearRemapTable(int type)](#clearRemapTable-int-) | 清除指定类别的颜色重新映射表。 |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---) | 为画笔类别设置颜色重新映射表。 |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | 清除此 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 对象的画笔颜色重新映射表。 |
| [setWrapMode(int mode)](#setWrapMode-int-) | 设置用于决定如何在形状上或形状边界处平铺纹理的包装模式。 |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.drawing.Color-) | 设置用于决定如何在形状上或形状边界处平铺纹理的包装模式和颜色。 |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.drawing.Color-boolean-) | 设置用于决定如何在形状上或形状边界处平铺纹理的包装模式和颜色。 |
| [getAdjustedPalette(ColorPalette palette, int type)](#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-) | 根据指定类别的调整设置调整调色板中的颜色。 |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


初始化 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 类的新实例。

### dispose() {#dispose--}
```
public void dispose()
```


释放此 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 对象使用的所有资源。

### deepClone() {#deepClone--}
```
public Object deepClone()
```


创建此 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 对象的精确副本。

**Returns:**
java.lang.Object - 此类创建的 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 对象，作为对象进行强制转换。
### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


为默认类别设置颜色调整矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 颜色调整矩阵。 |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


为默认类别设置颜色调整矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 颜色调整矩阵。 |
| flags | int | 一个 [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) 元素，指定将受到颜色调整矩阵影响的图像和颜色类型。 |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


为指定类别设置颜色调整矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 颜色调整矩阵。 |
| mode | int | 一个 [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) 元素，指定将受到颜色调整矩阵影响的图像和颜色类型。 |
| type | int | 一个 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 元素，指定设置颜色调整矩阵的类别。 |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


清除默认类别的颜色调整矩阵。

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


清除指定类别的颜色调整矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 一个 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 元素，指定清除颜色调整矩阵的类别。 |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


为默认类别设置颜色调整矩阵和灰度调整矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 颜色调整矩阵。 |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 灰度调整矩阵。 |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


为默认类别设置颜色调整矩阵和灰度调整矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 颜色调整矩阵。 |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 灰度调整矩阵。 |
| flags | int | 一个 [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) 元素，指定将受到颜色调整和灰度调整矩阵影响的图像和颜色类型。 |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


为指定类别设置颜色调整矩阵和灰度调整矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 颜色调整矩阵。 |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | 灰度调整矩阵。 |
| mode | int | 一个 [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) 元素，指定将受到颜色调整和灰度调整矩阵影响的图像和颜色类型。 |
| type | int | 一个 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 元素，指定设置颜色调整和灰度调整矩阵的类别。 |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


为默认类别设置阈值（透明度范围）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 阈值 | 浮点数 | 指定阈值的实数。 |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


为指定类别设置阈值（透明度范围）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 阈值 | 浮点数 | 从 0.0 到 1.0 的阈值，用作分界点，以对将映射到最大值或最小值的颜色进行排序。 |
| type | int | 一个 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 元素，指定设置颜色阈值的类别。 |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


清除默认类别的阈值。

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


清除指定类别的阈值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 一个 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 元素，指定清除阈值的类别。 |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


为默认类别设置伽马值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 伽马 | 浮点数 | 伽马校正值。 |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


为指定类别设置伽马值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 伽马 | 浮点数 | 伽马校正值。 |
| type | int | 枚举 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 的一个元素，用于指定设置伽马值的类别。 |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


禁用默认类别的伽马校正。

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


禁用指定类别的伽马校正。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 枚举 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 的一个元素，用于指定禁用伽马校正的类别。 |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


关闭默认类别的颜色调整。您可以调用 [.clearNoOp](../../null/\#clearNoOp) 方法来恢复在调用 [.setNoOp](../../null/\#setNoOp) 方法之前的颜色调整设置。

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


关闭指定类别的颜色调整。您可以调用 [.clearNoOp](../../null/\#clearNoOp) 方法来恢复在调用 [.setNoOp](../../null/\#setNoOp) 方法之前的颜色调整设置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 枚举 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 的一个元素，用于指定关闭颜色校正的类别。 |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


清除默认类别的 NoOp 设置。

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


清除指定类别的 NoOp 设置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 枚举 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 的一个元素，用于指定清除 NoOp 设置的类别。 |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


为默认类别设置颜色键。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | 低颜色键值。 |
| colorHigh | [Color](../../com.aspose.drawing/color) | 高颜色键值。 |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


为指定类别设置颜色键（透明度范围）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | 低颜色键值。 |
| colorHigh | [Color](../../com.aspose.drawing/color) | 高颜色键值。 |
| type | int | 枚举 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 的一个元素，用于指定设置颜色键的类别。 |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


清除默认类别的颜色键（透明度范围）。

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


清除指定类别的颜色键（透明度范围）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 枚举 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 的一个元素，用于指定清除颜色键的类别。 |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


为默认类别设置 CMYK（青-品红-黄-黑）输出通道。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| flags | int | 枚举 [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) 的一个元素，用于指定输出通道。 |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


为指定类别设置 CMYK（青-品红-黄-黑）输出通道。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| flags | int | 枚举 [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) 的一个元素，用于指定输出通道。 |
| type | int | 枚举 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 的一个元素，用于指定设置输出通道的类别。 |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


清除默认类别的 CMYK（青-品红-黄-黑）输出通道设置。

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


清除指定类别的（青-品红-黄-黑）输出通道设置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 枚举 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 的一个元素，用于指定清除输出通道设置的类别。 |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


为默认类别设置输出通道色彩配置文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | 颜色配置文件的路径名。如果颜色配置文件位于 %SystemRoot%\\System32\\Spool\\Drivers\\Color 目录中，则此参数可以是文件名。否则，此参数必须是完整的路径名。 |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


为指定类别设置输出通道颜色配置文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | 颜色配置文件的路径名。如果颜色配置文件位于 %SystemRoot%\\System32\\Spool\\Drivers\\Color 目录中，则此参数可以是文件名。否则，此参数必须是完整的路径名。 |
| type | int | 枚举 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 的一个元素，用于指定设置输出通道颜色配置文件的类别。 |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


清除默认类别的输出通道颜色配置设置。

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


清除指定类别的输出通道颜色配置设置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 枚举 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 的一个元素，用于指定清除输出通道配置文件设置的类别。 |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


为默认类别设置颜色重新映射表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | 类型为 [ColorMap](../../com.aspose.drawing.imaging/colormap) 的颜色对数组。每个颜色对包含一个现有颜色（第一个值）和它将映射到的颜色（第二个值）。 |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


为指定类别设置颜色重新映射表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | 类型为 [ColorMap](../../com.aspose.drawing.imaging/colormap) 的颜色对数组。每个颜色对包含一个现有颜色（第一个值）和它将映射到的颜色（第二个值）。 |
| type | int | 枚举 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 的一个元素，用于指定设置颜色重新映射表的类别。 |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


清除默认类别的颜色重新映射表。

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


清除指定类别的颜色重新映射表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 枚举 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 的一个元素，用于指定清除重新映射表的类别。 |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


为画笔类别设置颜色重新映射表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | [ColorMap](../../com.aspose.drawing.imaging/colormap) 对象数组。 |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


清除此 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 对象的画笔颜色重新映射表。

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


设置用于决定如何在形状上或形状边界处平铺纹理的包装模式。当纹理小于要填充的形状时，纹理会在形状上平铺以填充。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mode | int | 枚举 [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) 的一个元素，用于指定图像的重复副本如何用于平铺区域。 |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.drawing.Color-}
```
public void setWrapMode(int mode, Color color)
```


设置用于决定如何在形状上或形状边界处平铺纹理的包装模式和颜色。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mode | int | 枚举 [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) 的一个元素，用于指定图像的重复副本如何用于平铺区域。 |
| color | [Color](../../com.aspose.drawing/color) | 一个 [Color](../../com.aspose.drawing/color) 对象，指定渲染图像之外像素的颜色。如果 mode 参数设置为 `WrapMode.Clamp` 且传递给 `Graphics.DrawImage` 的源矩形大于图像本身，则此颜色可见。 |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.drawing.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


设置用于决定如何在形状上或形状边界处平铺纹理的包装模式和颜色。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mode | int | 枚举 [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) 的一个元素，用于指定图像的重复副本如何用于平铺区域。 |
| color | [Color](../../com.aspose.drawing/color) | 一个颜色对象，指定渲染图像之外像素的颜色。如果 mode 参数设置为 `WrapMode.Clamp` 且传递给 `Graphics.DrawImage` 的源矩形大于图像本身，则此颜色可见。 |
| 夹紧 | 布尔型 | 此参数无效。请将其设为 false。 |

### getAdjustedPalette(ColorPalette palette, int type) {#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-}
```
public void getAdjustedPalette(ColorPalette palette, int type)
```


根据指定类别的调整设置调整调色板中的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| palette | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) | 一个 [ColorPalette](../../com.aspose.drawing.imaging/colorpalette)，在输入时包含待调整的调色板，输出时包含已调整的调色板。 |
| type | int | 一个 [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) 元素，指定其调整设置将应用于调色板的类别。 |

