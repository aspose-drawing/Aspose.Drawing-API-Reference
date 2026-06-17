---
title: PlayRecordCallback
second_title: Riferimento API di Aspose.Drawing per Java
description: Questo delegato non è utilizzato.
type: docs
weight: 35
url: /it/java/com.aspose.drawing.imaging/playrecordcallback/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class PlayRecordCallback extends System.MulticastDelegate
```

Questo delegato non è utilizzato. Per un esempio di enumerazione dei record di un metafile, vedere [Graphics.enumerateMetafile(Metafile, Point, Graphics.EnumerateMetafileProc)](../../com.aspose.drawing/graphics\#enumerateMetafile-Metafile--Point--Graphics.EnumerateMetafileProc-).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PlayRecordCallback()](#PlayRecordCallback--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, byte[] recordData)](#invoke-int-int-int-byte---) |  |
| [beginInvoke(int recordType, int flags, int dataSize, byte[] recordData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-byte---com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### PlayRecordCallback() {#PlayRecordCallback--}
```
public PlayRecordCallback()
```


### invoke(int recordType, int flags, int dataSize, byte[] recordData) {#invoke-int-int-int-byte---}
```
public abstract void invoke(int recordType, int flags, int dataSize, byte[] recordData)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| recordData | byte[] |  |

### beginInvoke(int recordType, int flags, int dataSize, byte[] recordData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-byte---com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, byte[] recordData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| recordData | byte[] |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

