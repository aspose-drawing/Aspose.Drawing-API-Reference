---
title: Graphics.EnumerateMetafileProcByte
second_title: Référence de l'API Aspose.Drawing pour Java
description: 
type: docs
weight: 12
url: /fr/java/com.aspose.drawing/graphics.enumeratemetafileprocbyte/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProcByte extends System.MulticastDelegate
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EnumerateMetafileProcByte()](#EnumerateMetafileProcByte--) |  |
## Méthodes

| Méthode | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| données | byte[] |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |

**Returns:**
boolean
### beginInvoke(int recordType, int flags, int dataSize, byte[] data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-byte---com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, byte[] data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| données | byte[] |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| état | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final boolean endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| résultat | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
