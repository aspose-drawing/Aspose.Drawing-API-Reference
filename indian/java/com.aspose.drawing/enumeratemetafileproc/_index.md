---
title: Graphics.EnumerateMetafileProc
second_title: Aspose.Drawing for Java API संदर्भ
description: 
type: docs
weight: 11
url: /hi/java/com.aspose.drawing/graphics.enumeratemetafileproc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProc extends System.MulticastDelegate
```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [EnumerateMetafileProc()](#EnumerateMetafileProc--) |  |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)](#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-) | `EnumerateMetafile` विधि के लिए एक कॉलबैक मेथड प्रदान करता है। |
| [beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
### EnumerateMetafileProc() {#EnumerateMetafileProc--}
```
public EnumerateMetafileProc()
```


### invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData) {#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-}
```
public abstract boolean invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)
```


`EnumerateMetafile` विधि के लिए एक कॉलबैक मेथड प्रदान करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| recordType | int | [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) enumeration का सदस्य जो मेटाफाइल रिकॉर्ड का प्रकार निर्दिष्ट करता है। |
| flags | int | फ़्लैग्स का सेट जो रिकॉर्ड के गुणों को निर्दिष्ट करता है। |
| dataSize | int | रिकॉर्ड डेटा में बाइट्स की संख्या। |
| डेटा | com.aspose.ms.System.IntPtr | रिकॉर्ड डेटा को समाहित करने वाले बफ़र का पॉइंटर। |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) | आर्ग्यूमेंट का उपयोग नहीं किया गया है। |

**Returns:**
boolean - यदि आप रिकॉर्ड्स की गिनती जारी रखना चाहते हैं तो true लौटाएँ; अन्यथा false।
### beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| डेटा | com.aspose.ms.System.IntPtr |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
