---
title: Graphics.EnumerateMetafileProc
second_title: Aspose.Drawing für Java API-Referenz
description: 
type: docs
weight: 11
url: /de/java/com.aspose.drawing/graphics.enumeratemetafileproc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProc extends System.MulticastDelegate
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EnumerateMetafileProc()](#EnumerateMetafileProc--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)](#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-) | Stellt eine Rückrufmethode für die `EnumerateMetafile`‑Methode bereit. |
| [beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
### EnumerateMetafileProc() {#EnumerateMetafileProc--}
```
public EnumerateMetafileProc()
```


### invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData) {#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-}
```
public abstract boolean invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)
```


Stellt eine Rückrufmethode für die `EnumerateMetafile`‑Methode bereit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recordType | int | Mitglied der Aufzählung [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype), die den Typ des Metadatei‑Eintrags angibt. |
| flags | int | Menge von Flags, die Attribute des Eintrags festlegen. |
| dataSize | int | Anzahl der Bytes in den Aufzeichnungsdaten. |
| Daten | com.aspose.ms.System.IntPtr | Zeiger auf einen Puffer, der die Datensatzdaten enthält. |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) | Das Argument wird nicht verwendet. |

**Returns:**
boolean - Gibt true zurück, wenn Sie die Aufzählung der Datensätze fortsetzen möchten; andernfalls false.
### beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| Daten | com.aspose.ms.System.IntPtr |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
