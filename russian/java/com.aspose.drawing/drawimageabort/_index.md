---
title: Graphics.DrawImageAbort
second_title: Справочник API Aspose.Drawing для Java
description: 
type: docs
weight: 10
url: /ru/java/com.aspose.drawing/graphics.drawimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.DrawImageAbort extends System.MulticastDelegate
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DrawImageAbort()](#DrawImageAbort--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [invoke(System.IntPtr callbackdata)](#invoke-com.aspose.ms.System.IntPtr-) | Предоставляет метод обратного вызова, определяющий, когда метод `DrawImage` должен преждевременно отменить выполнение и прекратить отрисовку изображения. |
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


Предоставляет метод обратного вызова, определяющий, когда метод `DrawImage` должен преждевременно отменить выполнение и прекратить отрисовку изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr | Внутренний указатель, который задает данные для метода обратного вызова. Этот параметр не передаётся всеми перегрузками `DrawImage`. Вы можете проверить его отсутствие, проверив значение `System.IntPtr.Zero`. |

**Returns:**
boolean — Этот метод возвращает true, если он решает, что метод `DrawImage` должен преждевременно остановить выполнение. В противном случае он возвращает false, указывая, что метод `DrawImage` должен продолжить выполнение.
### beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final boolean endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
