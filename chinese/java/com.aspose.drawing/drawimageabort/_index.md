---
title: Graphics.DrawImageAbort
second_title: Aspose.Drawing for Java API 参考
description: 
type: docs
weight: 10
url: /zh/java/com.aspose.drawing/graphics.drawimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.DrawImageAbort extends System.MulticastDelegate
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DrawImageAbort()](#DrawImageAbort--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(System.IntPtr callbackdata)](#invoke-com.aspose.ms.System.IntPtr-) | 提供一个回调方法，用于决定何时应提前取消 `DrawImage` 方法的执行并停止绘制图像。 |
| [beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### DrawImageAbort() {#DrawImageAbort--}
```
public DrawImageAbort()
```


### invoke(System.IntPtr callbackdata) {#invoke-com.aspose.ms.System.IntPtr-}
```
public abstract boolean invoke(System.IntPtr callbackdata)
```


提供一个回调方法，用于决定何时应提前取消 `DrawImage` 方法的执行并停止绘制图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 回调数据 | com.aspose.ms.System.IntPtr | 内部指针，用于指定回调方法的数据。并非所有 `DrawImage` 重载都会传递此参数。您可以通过检查值 `System.IntPtr.Zero` 来判断其是否缺失。 |

**Returns:**
布尔值 - 如果该方法决定 `DrawImage` 方法应提前停止执行，则返回 true；否则返回 false，表示 `DrawImage` 方法应继续执行。
### beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 回调数据 | com.aspose.ms.System.IntPtr |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final boolean endInvoke(System.IAsyncResult result)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
布尔型
