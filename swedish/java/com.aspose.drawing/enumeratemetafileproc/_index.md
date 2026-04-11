---
title: Graphics.EnumerateMetafileProc
second_title: Aspose.Drawing för Java API‑referens
description: 
type: docs
weight: 11
url: /sv/java/com.aspose.drawing/graphics.enumeratemetafileproc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProc extends System.MulticastDelegate
```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EnumerateMetafileProc()](#EnumerateMetafileProc--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)](#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-) | Tillhandahåller en återuppringningsmetod för `EnumerateMetafile`‑metoden. |
| [beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
### EnumerateMetafileProc() {#EnumerateMetafileProc--}
```
public EnumerateMetafileProc()
```


### invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData) {#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-}
```
public abstract boolean invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)
```


Tillhandahåller en återuppringningsmetod för `EnumerateMetafile`‑metoden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recordType | int | Medlem av uppräkningen [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) som specificerar typen av metafilpost. |
| flaggor | int | Uppsättning av flaggor som specificerar attribut för posten. |
| datastorlek | int | Antal byte i postens data. |
| data | com.aspose.ms.System.IntPtr | Pekare till en buffert som innehåller postdata. |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) | Argumentet används inte. |

**Returns:**
boolean - Returnera true om du vill fortsätta enumerera poster; annars false.
### beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recordType | int |  |
| flaggor | int |  |
| datastorlek | int |  |
| data | com.aspose.ms.System.IntPtr |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
| återanrop | com.aspose.ms.System.AsyncCallback |  |
| tillstånd | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
