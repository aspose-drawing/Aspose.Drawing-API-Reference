---
title: Graphics.EnumerateMetafileProc
second_title: Riferimento API di Aspose.Drawing per Java
description: 
type: docs
weight: 11
url: /it/java/com.aspose.drawing/graphics.enumeratemetafileproc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProc extends System.MulticastDelegate
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EnumerateMetafileProc()](#EnumerateMetafileProc--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)](#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-) | Fornisce un metodo di callback per il metodo `EnumerateMetafile`. |
| [beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
### EnumerateMetafileProc() {#EnumerateMetafileProc--}
```
public EnumerateMetafileProc()
```


### invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData) {#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-}
```
public abstract boolean invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)
```


Fornisce un metodo di callback per il metodo `EnumerateMetafile`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recordType | int | Membro dell'enumerazione [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) che specifica il tipo di record metafile. |
| flags | int | Set di flag che specificano gli attributi del record. |
| dataSize | int | Numero di byte nei dati del record. |
| dati | com.aspose.ms.System.IntPtr | Puntatore a un buffer che contiene i dati del record. |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) | L'argomento non è utilizzato. |

**Returns:**
boolean - Restituisce true se si desidera continuare a enumerare i record; altrimenti, false.
### beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| dati | com.aspose.ms.System.IntPtr |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
