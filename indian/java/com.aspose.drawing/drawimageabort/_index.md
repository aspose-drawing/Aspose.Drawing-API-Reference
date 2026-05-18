---
title: Graphics.DrawImageAbort
second_title: Aspose.Drawing for Java API संदर्भ
description: 
type: docs
weight: 10
url: /hi/java/com.aspose.drawing/graphics.drawimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.DrawImageAbort extends System.MulticastDelegate
```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [DrawImageAbort()](#DrawImageAbort--) |  |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [invoke(System.IntPtr callbackdata)](#invoke-com.aspose.ms.System.IntPtr-) | `DrawImage` मेथड को कब पूर्व-समाप्त करके निष्पादन रद्द करना है और छवि को ड्रॉ करना बंद करना है, यह तय करने के लिए एक कॉलबैक मेथड प्रदान करता है। |
| [beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### DrawImageAbort() {#DrawImageAbort--}
```
public DrawImageAbort()
```


### invoke(System.IntPtr callbackdata) {#invoke-com.aspose.ms.System.IntPtr-}
```
public abstract boolean invoke(System.IntPtr callbackdata)
```


`DrawImage` मेथड को कब पूर्व-समाप्त करके निष्पादन रद्द करना है और छवि को ड्रॉ करना बंद करना है, यह तय करने के लिए एक कॉलबैक मेथड प्रदान करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr | आंतरिक पॉइंटर जो कॉलबैक मेथड के लिए डेटा निर्दिष्ट करता है। यह पैरामीटर सभी `DrawImage` ओवरलोड्स द्वारा पास नहीं किया जाता है। आप इसकी अनुपस्थिति का परीक्षण `System.IntPtr.Zero` मान की जाँच करके कर सकते हैं। |

**Returns:**
boolean - यह मेथड true लौटाता है यदि यह तय करता है कि `DrawImage` मेथड को जल्दबाजी में निष्पादन रोक देना चाहिए। अन्यथा यह false लौटाता है यह संकेत देने के लिए कि `DrawImage` मेथड को निष्पादन जारी रखना चाहिए।
### beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final boolean endInvoke(System.IAsyncResult result)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
