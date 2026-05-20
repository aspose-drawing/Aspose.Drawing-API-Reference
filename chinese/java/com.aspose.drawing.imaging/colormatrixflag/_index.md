---
title: ColorMatrixFlag
second_title: Aspose.Drawing for Java API 参考
description: 指定将受到颜色和灰度调整设置影响的图像和颜色类型。
type: docs
weight: 15
url: /zh/java/com.aspose.drawing.imaging/colormatrixflag/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorMatrixFlag extends System.Enum
```

指定将受到 [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) 的颜色和灰度调整设置影响的图像和颜色类型。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Default](#Default) | 所有颜色值（包括灰色阴影）均通过相同的颜色调整矩阵进行调整。 |
| [SkipGrays](#SkipGrays) | 所有颜色都会被调整，但灰色阴影不进行调整。 |
| [AltGrays](#AltGrays) | 仅调整灰色阴影。 |
### Default {#Default}
```
public static final int Default
```


所有颜色值（包括灰色阴影）均通过相同的颜色调整矩阵进行调整。

### SkipGrays {#SkipGrays}
```
public static final int SkipGrays
```


所有颜色都会被调整，但灰色阴影不进行调整。灰色阴影是指红、绿、蓝分量值相同的任何颜色。

### AltGrays {#AltGrays}
```
public static final int AltGrays
```


仅调整灰色阴影。

