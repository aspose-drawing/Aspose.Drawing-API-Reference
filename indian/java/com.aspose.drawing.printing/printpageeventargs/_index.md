---
title: PrintPageEventArgs
second_title: Aspose.Drawing for Java API संदर्भ
description: EPrintDocument.PrintPage इवेंट के लिए डेटा प्रदान करता है।
type: docs
weight: 13
url: /hi/java/com.aspose.drawing.printing/printpageeventargs/
---
**Inheritance:**
java.lang.Object
```
public class PrintPageEventArgs
```

`E:PrintDocument.PrintPage` इवेंट के लिए डेटा प्रदान करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [PrintPageEventArgs()](#PrintPageEventArgs--) |  |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getGraphics()](#getGraphics--) | पृष्ठ को पेंट करने के लिए उपयोग किए जाने वाले `Graphics`([.getGraphics](../../null/\#getGraphics)) प्राप्त करता है। |
| [hasMorePages()](#hasMorePages--) | एक मान प्राप्त करता है जो दर्शाता है कि क्या अतिरिक्त पृष्ठ प्रिंट किया जाना चाहिए। |
| [setMorePages(boolean value)](#setMorePages-boolean-) | एक मान सेट करता है जो दर्शाता है कि क्या अतिरिक्त पृष्ठ प्रिंट किया जाना चाहिए। |
| [getPageSettings()](#getPageSettings--) | वर्तमान पृष्ठ के लिए पृष्ठ सेटिंग्स प्राप्त करता है। |
### PrintPageEventArgs() {#PrintPageEventArgs--}
```
public PrintPageEventArgs()
```


### getGraphics() {#getGraphics--}
```
public final Graphics getGraphics()
```


पृष्ठ को पेंट करने के लिए उपयोग किए जाने वाले `Graphics`([.getGraphics](../../null/\#getGraphics)) प्राप्त करता है।

**Returns:**
[Graphics](../../com.aspose.drawing/graphics) - The `Graphics`([.getGraphics](../../null/\#getGraphics)) used to paint the page.
### hasMorePages() {#hasMorePages--}
```
public final boolean hasMorePages()
```


एक मान प्राप्त करता है जो दर्शाता है कि क्या अतिरिक्त पृष्ठ प्रिंट किया जाना चाहिए।

**Returns:**
boolean - यदि अतिरिक्त पृष्ठ प्रिंट किया जाना चाहिए तो `true`; अन्यथा, false. डिफ़ॉल्ट `false` है।
### setMorePages(boolean value) {#setMorePages-boolean-}
```
public final void setMorePages(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि क्या अतिरिक्त पृष्ठ प्रिंट किया जाना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | एक मान जो दर्शाता है कि क्या अतिरिक्त पृष्ठ प्रिंट किया जाना चाहिए। |

### getPageSettings() {#getPageSettings--}
```
public final PageSettings getPageSettings()
```


वर्तमान पृष्ठ के लिए पृष्ठ सेटिंग्स प्राप्त करता है।

**Returns:**
[PageSettings](../../com.aspose.drawing.printing/pagesettings) - The page settings for the current page.
