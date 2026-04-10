---
title: DrawingSettings
second_title: Aspose.Drawing for Java API 参考
description: 允许在使用尚未完全实现的某些功能时调整绘图库的行为。
type: docs
weight: 19
url: /zh/java/com.aspose.drawing/drawingsettings/
---
**Inheritance:**
java.lang.Object
```
public final class DrawingSettings
```

允许在使用尚未完全实现的某些功能时调整绘图库的行为。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DrawingSettings()](#DrawingSettings--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | 获取一个值，指示是否启用了对未实现功能的更严格捕获。 |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | 设置一个值，指示是否启用了对未实现功能的更严格捕获。 |
### DrawingSettings() {#DrawingSettings--}
```
public DrawingSettings()
```


### getStrictMode() {#getStrictMode--}
```
public static boolean getStrictMode()
```


获取一个值，指示是否启用了对未实现功能的更严格捕获。

--------------------

如果设置为 true，则在使用当前实现中无法正确工作的功能/参数时，库将抛出 NotImplementedException。如果设置为 false，某些参数可能会被忽略，以使用户程序有机会运行。在这种情况下，绘图结果可能与 GDI+ 的比较有所不同。

**Returns:**
boolean - 一个值，指示是否启用了对未实现功能的更严格捕获。
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public static void setStrictMode(boolean value)
```


设置一个值，指示是否启用了对未实现功能的更严格捕获。

--------------------

如果设置为 true，则在使用当前实现中无法正确工作的功能/参数时，库将抛出 NotImplementedException。如果设置为 false，某些参数可能会被忽略，以使用户程序有机会运行。在这种情况下，绘图结果可能与 GDI+ 的比较有所不同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 布尔型 | 一个值，指示是否启用了对未实现功能的更严格捕获。 |

