---
title: Graphics.EnumerateMetafileProc
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: 
type: docs
weight: 11
url: /ar/java/com.aspose.drawing/graphics.enumeratemetafileproc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProc extends System.MulticastDelegate
```
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [EnumerateMetafileProc()](#EnumerateMetafileProc--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)](#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-) | يوفر طريقة رد نداء لـ `EnumerateMetafile`. |
| [beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
### EnumerateMetafileProc() {#EnumerateMetafileProc--}
```
public EnumerateMetafileProc()
```


### invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData) {#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-}
```
public abstract boolean invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)
```


يوفر طريقة رد نداء لـ `EnumerateMetafile`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| recordType | int | عضو في تعداد [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) الذي يحدد نوع سجل ملف الميتا. |
| flags | int | مجموعة من العلامات التي تحدد سمات السجل. |
| dataSize | int | عدد البايتات في بيانات السجل. |
| بيانات | com.aspose.ms.System.IntPtr | مؤشر إلى مخزن مؤقت يحتوي على بيانات السجل. |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) | المعامل غير مستخدم. |

**Returns:**
boolean - إرجاع true إذا كنت تريد الاستمرار في تعداد السجلات؛ وإلا، false.
### beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| بيانات | com.aspose.ms.System.IntPtr |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
