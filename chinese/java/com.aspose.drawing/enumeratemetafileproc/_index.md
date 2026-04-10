---
title: Graphics.EnumerateMetafileProc
second_title: Aspose.Drawing for Java API 参考
description: 
type: docs
weight: 11
url: /zh/java/com.aspose.drawing/graphics.enumeratemetafileproc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProc extends System.MulticastDelegate
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EnumerateMetafileProc()](#EnumerateMetafileProc--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)](#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-) | 为 `EnumerateMetafile` 方法提供回调方法。 |
| [beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
### EnumerateMetafileProc() {#EnumerateMetafileProc--}
```
public EnumerateMetafileProc()
```


### invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData) {#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-}
```
public abstract boolean invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)
```


为 `EnumerateMetafile` 方法提供回调方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recordType | int | 是 [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) 枚举的成员，用于指定元文件记录的类型。 |
| flags | int | 指定记录属性的标志集合。 |
| dataSize | int | 记录数据的字节数。 |
| 数据 | com.aspose.ms.System.IntPtr | 指向包含记录数据的缓冲区的指针。 |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) | 此参数未被使用。 |

**Returns:**
boolean - 如果想继续枚举记录则返回 true；否则返回 false。
### beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| 数据 | com.aspose.ms.System.IntPtr |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
