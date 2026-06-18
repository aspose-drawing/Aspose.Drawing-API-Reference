---
title: PlayRecordCallback
second_title: Referencia de la API de Aspose.Drawing para Java
description: Este delegado no se usa.
type: docs
weight: 35
url: /es/java/com.aspose.drawing.imaging/playrecordcallback/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class PlayRecordCallback extends System.MulticastDelegate
```

Este delegado no se utiliza. Para un ejemplo de enumerar los registros de un metafile, vea [Graphics.enumerateMetafile(Metafile, Point, Graphics.EnumerateMetafileProc)](../../com.aspose.drawing/graphics\#enumerateMetafile-Metafile--Point--Graphics.EnumerateMetafileProc-).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PlayRecordCallback()](#PlayRecordCallback--) |  |
## Métodos

| Método | Descripción |
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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

