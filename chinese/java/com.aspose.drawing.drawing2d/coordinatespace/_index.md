---
title: 坐标空间
second_title: Aspose.Drawing for Java API 参考
description: 指定评估坐标时使用的系统。
type: docs
weight: 16
url: /zh/java/com.aspose.drawing.drawing2d/coordinatespace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CoordinateSpace extends System.Enum
```

指定评估坐标时使用的系统。
## 字段

| 字段 | 描述 |
| --- | --- |
| [World](#World) | 指定坐标位于世界坐标上下文中。 |
| [Page](#Page) | 指定坐标位于页面坐标上下文中。 |
| [Device](#Device) | 指定坐标位于设备坐标上下文中。 |
### World {#World}
```
public static final int World
```


指定坐标位于世界坐标上下文中。世界坐标用于非物理环境，例如建模环境。

### Page {#Page}
```
public static final int Page
```


指定坐标位于页面坐标上下文中。它们的单位由 Graphics.PageUnit 属性定义，必须是 GraphicsUnit 枚举的其中一个元素。

### Device {#Device}
```
public static final int Device
```


指定坐标位于设备坐标上下文中。在计算机屏幕上，设备坐标通常以像素为单位。

