---
title: Graphics.EnumerateMetafileProcByte
second_title: Aspose.Drawing for Java API 参考
description: 
type: docs
weight: 12
url: /zh/java/com.aspose.drawing/graphics.enumeratemetafileprocbyte/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProcByte extends System.MulticastDelegate
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EnumerateMetafileProcByte()](#EnumerateMetafileProcByte--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, byte[] data, PlayRecordCallback callbackData)](#invoke-int-int-int-byte---com.aspose.drawing.imaging.PlayRecordCallback-) |  |
| [beginInvoke(int recordType, int flags, int dataSize, byte[] data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-byte---com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### EnumerateMetafileProcByte() {#EnumerateMetafileProcByte--}
```
public EnumerateMetafileProcByte()
```


### invoke(int recordType, int flags, int dataSize, byte[] data, PlayRecordCallback callbackData) {#invoke-int-int-int-byte---com.aspose.drawing.imaging.PlayRecordCallback-}
```
public abstract boolean invoke(int recordType, int flags, int dataSize, byte[] data, PlayRecordCallback callbackData)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| 数据 | byte[] |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |

**Returns:**
布尔型
### beginInvoke(int recordType, int flags, int dataSize, byte[] data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-byte---com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, byte[] data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| 数据 | byte[] |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
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
