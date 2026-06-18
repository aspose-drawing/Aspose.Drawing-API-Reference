---
title: PlayRecordCallback
second_title: Αναφορά API του Aspose.Drawing for Java
description: Αυτός ο αντιπρόσωπος δεν χρησιμοποιείται.
type: docs
weight: 35
url: /el/java/com.aspose.drawing.imaging/playrecordcallback/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class PlayRecordCallback extends System.MulticastDelegate
```

Αυτό το delegate δεν χρησιμοποιείται. Για ένα παράδειγμα αρίθμησης των εγγραφών ενός metafile, δείτε [Graphics.enumerateMetafile(Metafile, Point, Graphics.EnumerateMetafileProc)](../../com.aspose.drawing/graphics\#enumerateMetafile-Metafile--Point--Graphics.EnumerateMetafileProc-).
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PlayRecordCallback()](#PlayRecordCallback--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

