---
title: PlayRecordCallback
second_title: Aspose.Drawing for Java API संदर्भ
description: यह प्रतिनिधि (delegate) उपयोग नहीं किया जाता है।
type: docs
weight: 35
url: /hi/java/com.aspose.drawing.imaging/playrecordcallback/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class PlayRecordCallback extends System.MulticastDelegate
```

यह डेलीगेट उपयोग नहीं किया जाता है। मेटाफाइल के रिकॉर्ड्स को क्रमबद्ध करने के उदाहरण के लिए, देखें [Graphics.enumerateMetafile(Metafile, Point, Graphics.EnumerateMetafileProc)](../../com.aspose.drawing/graphics\#enumerateMetafile-Metafile--Point--Graphics.EnumerateMetafileProc-).
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [PlayRecordCallback()](#PlayRecordCallback--) |  |
## मेथड्स

| विधि | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

