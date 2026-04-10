---
title: Graphics.EnumerateMetafileProc
second_title: Αναφορά API του Aspose.Drawing for Java
description: 
type: docs
weight: 11
url: /el/java/com.aspose.drawing/graphics.enumeratemetafileproc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProc extends System.MulticastDelegate
```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [EnumerateMetafileProc()](#EnumerateMetafileProc--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)](#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-) | Παρέχει μια μέθοδο callback για τη μέθοδο `EnumerateMetafile`. |
| [beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
### EnumerateMetafileProc() {#EnumerateMetafileProc--}
```
public EnumerateMetafileProc()
```


### invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData) {#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-}
```
public abstract boolean invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)
```


Παρέχει μια μέθοδο callback για τη μέθοδο `EnumerateMetafile`.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| recordType | int | Μέλος της απαρίθμησης [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) που καθορίζει τον τύπο της εγγραφής μετααρχείου. |
| flags | int | Σύνολο σημαιών που καθορίζουν τα χαρακτηριστικά της εγγραφής. |
| dataSize | int | Αριθμός byte στα δεδομένα της εγγραφής. |
| δεδομένα | com.aspose.ms.System.IntPtr | Δείκτης σε ένα buffer που περιέχει τα δεδομένα της εγγραφής. |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) | Το όρισμα δεν χρησιμοποιείται. |

**Returns:**
boolean - Επιστρέψτε true εάν θέλετε να συνεχίσετε την απαρίθμηση των εγγραφών· διαφορετικά, false.
### beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| δεδομένα | com.aspose.ms.System.IntPtr |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
