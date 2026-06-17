---
title: PlayRecordCallback
second_title: Aspose.Drawing för Java API‑referens
description: Denna delegat används inte.
type: docs
weight: 35
url: /sv/java/com.aspose.drawing.imaging/playrecordcallback/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class PlayRecordCallback extends System.MulticastDelegate
```

Denna delegat används inte. För ett exempel på att enumerera posterna i en metafil, se [Graphics.enumerateMetafile(Metafile, Point, Graphics.EnumerateMetafileProc)](../../com.aspose.drawing/graphics\#enumerateMetafile-Metafile--Point--Graphics.EnumerateMetafileProc-).
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PlayRecordCallback()](#PlayRecordCallback--) |  |
## Metoder

| Metod | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recordType | int |  |
| flaggor | int |  |
| datastorlek | int |  |
| postdata | byte[] |  |

### beginInvoke(int recordType, int flags, int dataSize, byte[] recordData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-byte---com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, byte[] recordData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recordType | int |  |
| flaggor | int |  |
| datastorlek | int |  |
| postdata | byte[] |  |
| återanrop | com.aspose.ms.System.AsyncCallback |  |
| tillstånd | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resultat | com.aspose.ms.System.IAsyncResult |  |

