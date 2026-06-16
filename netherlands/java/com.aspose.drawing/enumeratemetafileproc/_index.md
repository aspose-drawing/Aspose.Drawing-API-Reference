---
title: Graphics.EnumerateMetafileProc
second_title: Aspose.Drawing voor Java API-referentie
description: 
type: docs
weight: 11
url: /nl/java/com.aspose.drawing/graphics.enumeratemetafileproc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProc extends System.MulticastDelegate
```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [EnumerateMetafileProc()](#EnumerateMetafileProc--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)](#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-) | Biedt een callback-methode voor de `EnumerateMetafile`-methode. |
| [beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
### EnumerateMetafileProc() {#EnumerateMetafileProc--}
```
public EnumerateMetafileProc()
```


### invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData) {#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-}
```
public abstract boolean invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)
```


Biedt een callback-methode voor de `EnumerateMetafile`-methode.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recordType | int | Lid van de [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) enumeratie die het type metafile-record specificeert. |
| flags | int | Set van vlaggen die attributen van het record specificeren. |
| dataSize | int | Aantal bytes in de recordgegevens. |
| gegevens | com.aspose.ms.System.IntPtr | Pointer naar een buffer die de recordgegevens bevat. |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) | Het argument wordt niet gebruikt. |

**Returns:**
boolean - Retourneer true als u wilt doorgaan met het enumereren van records; anders false.
### beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| gegevens | com.aspose.ms.System.IntPtr |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
