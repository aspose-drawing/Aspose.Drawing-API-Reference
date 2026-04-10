---
title: Graphics.EnumerateMetafileProcByte
second_title: Aspose.Drawing for Java API 참조
description: 
type: docs
weight: 12
url: /ko/java/com.aspose.drawing/graphics.enumeratemetafileprocbyte/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProcByte extends System.MulticastDelegate
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [EnumerateMetafileProcByte()](#EnumerateMetafileProcByte--) |  |
## 메서드

| 메서드 | 설명 |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| 데이터 | byte[] |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |

**Returns:**
boolean
### beginInvoke(int recordType, int flags, int dataSize, byte[] data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-byte---com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, byte[] data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| 데이터 | byte[] |  |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
