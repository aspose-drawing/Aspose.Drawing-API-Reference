---
title: Graphics.DrawImageAbort
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: 
type: docs
weight: 10
url: /ar/java/com.aspose.drawing/graphics.drawimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.DrawImageAbort extends System.MulticastDelegate
```
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [DrawImageAbort()](#DrawImageAbort--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [invoke(System.IntPtr callbackdata)](#invoke-com.aspose.ms.System.IntPtr-) | يوفر طريقة رد نداء لتحديد متى يجب أن تُلغي طريقة `DrawImage` التنفيذ مسبقًا وتوقف رسم الصورة. |
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


يوفر طريقة رد نداء لتحديد متى يجب أن تُلغي طريقة `DrawImage` التنفيذ مسبقًا وتوقف رسم الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr | مؤشر داخلي يحدد البيانات لطريقة الاستدعاء الراجع. لا يتم تمرير هذا المعامل في جميع التحميلات الزائدة لـ `DrawImage`. يمكنك اختبار عدم وجوده عن طريق التحقق من القيمة `System.IntPtr.Zero`. |

**Returns:**
منطقي - تُعيد هذه الطريقة true إذا قررت أن طريقة `DrawImage` يجب أن توقف التنفيذ مبكرًا. وإلا تُعيد false للإشارة إلى أن طريقة `DrawImage` يجب أن تواصل التنفيذ.
### beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)
```




**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
