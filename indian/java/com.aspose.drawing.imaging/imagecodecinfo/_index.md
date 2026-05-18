---
title: ImageCodecInfo
second_title: Aspose.Drawing for Java API संदर्भ
description: यह class आवश्यक स्टोरेज सदस्य और विधियाँ प्रदान करता है ताकि स्थापित इमेज एन्कोडर और डिकोडर (जिन्हें codecs कहा जाता है) के बारे में सभी प्रासंगिक जानकारी प्राप्त की जा सके।
type: docs
weight: 25
url: /hi/java/com.aspose.drawing.imaging/imagecodecinfo/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCodecInfo
```

यह [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) क्लास आवश्यक स्टोरेज सदस्य और विधियाँ प्रदान करती है जो स्थापित इमेज एन्कोडर और डिकोडर (जिन्हें कोडेक कहा जाता है) के बारे में सभी प्रासंगिक जानकारी प्राप्त करने के लिए उपयोगी हैं। यह इनहेरिटेबल नहीं है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [ImageCodecInfo()](#ImageCodecInfo--) | यह [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)](#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-) |  |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getClsid()](#getClsid--) | एक java.util.UUID संरचना प्राप्त करता है जिसमें एक GUID होता है जो एक विशिष्ट कोडेक की पहचान करता है। |
| [setClsid(UUID value)](#setClsid-java.util.UUID-) | एक java.util.UUID संरचना सेट करता है जिसमें एक GUID होता है जो एक विशिष्ट कोडेक की पहचान करता है। |
| [getFormatID()](#getFormatID--) | एक java.util.UUID संरचना प्राप्त करता है जिसमें एक GUID होता है जो कोडेक के फ़ॉर्मेट की पहचान करता है। |
| [setFormatID(UUID value)](#setFormatID-java.util.UUID-) | एक java.util.UUID संरचना सेट करता है जिसमें एक GUID होता है जो कोडेक के फ़ॉर्मेट की पहचान करता है। |
| [getCodecName()](#getCodecName--) | कोडेक के नाम को सम्मिलित करने वाली स्ट्रिंग प्राप्त करता है या सेट करता है। |
| [setCodecName(String value)](#setCodecName-java.lang.String-) | कोडेक के नाम को सम्मिलित करने वाली स्ट्रिंग प्राप्त करता है या सेट करता है। |
| [getFormatDescription()](#getFormatDescription--) | कोडेक के फ़ाइल फ़ॉर्मेट का वर्णन करने वाली स्ट्रिंग प्राप्त करता है या सेट करता है। |
| [setFormatDescription(String value)](#setFormatDescription-java.lang.String-) | कोडेक के फ़ाइल फ़ॉर्मेट का वर्णन करने वाली स्ट्रिंग प्राप्त करता है या सेट करता है। |
| [getFilenameExtension()](#getFilenameExtension--) | कोडेक में उपयोग किए जाने वाले फ़ाइल नाम एक्सटेंशन(s) को सम्मिलित करने वाली स्ट्रिंग प्राप्त करता है या सेट करता है। |
| [setFilenameExtension(String value)](#setFilenameExtension-java.lang.String-) | कोडेक में उपयोग किए जाने वाले फ़ाइल नाम एक्सटेंशन(s) को सम्मिलित करने वाली स्ट्रिंग प्राप्त करता है या सेट करता है। |
| [getMimeType()](#getMimeType--) | कोडेक के मल्टीपर्पज़ इंटरनेट मेल एक्सटेंशन (MIME) प्रकार को सम्मिलित करने वाली स्ट्रिंग प्राप्त करता है या सेट करता है। |
| [setMimeType(String value)](#setMimeType-java.lang.String-) | कोडेक के मल्टीपर्पज़ इंटरनेट मेल एक्सटेंशन (MIME) प्रकार को सम्मिलित करने वाली स्ट्रिंग प्राप्त करता है या सेट करता है। |
| [getVersion()](#getVersion--) | कोडेक का संस्करण संख्या प्राप्त करता है या सेट करता है। |
| [setVersion(int value)](#setVersion-int-) | कोडेक का संस्करण संख्या प्राप्त करता है या सेट करता है। |
| [getSignaturePatterns()](#getSignaturePatterns--) | कोडेक के सिग्नेचर को दर्शाने वाले बाइट्स के दो-आयामी एरे को प्राप्त करता है या सेट करता है। |
| [setSignaturePatterns(byte[][] value)](#setSignaturePatterns-byte-----) | कोडेक के सिग्नेचर को दर्शाने वाले बाइट्स के दो-आयामी एरे को प्राप्त करता है या सेट करता है। |
| [getSignatureMasks()](#getSignatureMasks--) | फ़िल्टर के रूप में उपयोग की जा सकने वाले बाइट्स के दो-आयामी एरे को प्राप्त करता है या सेट करता है। |
| [setSignatureMasks(byte[][] value)](#setSignatureMasks-byte-----) | फ़िल्टर के रूप में उपयोग की जा सकने वाले बाइट्स के दो-आयामी एरे को प्राप्त करता है या सेट करता है। |
| [getImageDecoders()](#getImageDecoders--) | GDI+ में निर्मित इमेज डिकोडर के बारे में जानकारी रखने वाले [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) ऑब्जेक्ट्स की एक एरे लौटाता है। |
| [getImageEncoders()](#getImageEncoders--) | GDI+ में निर्मित इमेज एन्कोडर के बारे में जानकारी रखने वाले [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) ऑब्जेक्ट्स की एक एरे लौटाता है। |
### ImageCodecInfo() {#ImageCodecInfo--}
```
public ImageCodecInfo()
```


यह [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) क्लास का नया इंस्टेंस प्रारंभ करता है।

### ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version) {#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-}
```
public ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| clsid | java.util.UUID |  |
| codecName | java.lang.String |  |
| filenameExtension | java.lang.String |  |
| formatDescription | java.lang.String |  |
| formatID | java.util.UUID |  |
| mimeType | java.lang.String |  |
| version | int |  |

### getClsid() {#getClsid--}
```
public UUID getClsid()
```


एक java.util.UUID संरचना प्राप्त करता है जिसमें एक GUID होता है जो एक विशिष्ट कोडेक की पहचान करता है।

**Returns:**
java.util.UUID - एक java.util.UUID
### setClsid(UUID value) {#setClsid-java.util.UUID-}
```
public void setClsid(UUID value)
```


एक java.util.UUID संरचना सेट करता है जिसमें एक GUID होता है जो एक विशिष्ट कोडेक की पहचान करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.UUID | एक java.util.UUID |

### getFormatID() {#getFormatID--}
```
public UUID getFormatID()
```


एक java.util.UUID संरचना प्राप्त करता है जिसमें एक GUID होता है जो कोडेक के फ़ॉर्मेट की पहचान करता है।

**Returns:**
java.util.UUID - एक java.util.UUID
### setFormatID(UUID value) {#setFormatID-java.util.UUID-}
```
public void setFormatID(UUID value)
```


एक java.util.UUID संरचना सेट करता है जिसमें एक GUID होता है जो कोडेक के फ़ॉर्मेट की पहचान करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.UUID | एक java.util.UUID |

### getCodecName() {#getCodecName--}
```
public String getCodecName()
```


कोडेक के नाम को सम्मिलित करने वाली स्ट्रिंग प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setCodecName(String value) {#setCodecName-java.lang.String-}
```
public void setCodecName(String value)
```


कोडेक के नाम को सम्मिलित करने वाली स्ट्रिंग प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormatDescription() {#getFormatDescription--}
```
public String getFormatDescription()
```


कोडेक के फ़ाइल फ़ॉर्मेट का वर्णन करने वाली स्ट्रिंग प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setFormatDescription(String value) {#setFormatDescription-java.lang.String-}
```
public void setFormatDescription(String value)
```


कोडेक के फ़ाइल फ़ॉर्मेट का वर्णन करने वाली स्ट्रिंग प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getFilenameExtension() {#getFilenameExtension--}
```
public String getFilenameExtension()
```


कोडेक में उपयोग किए जाने वाले फ़ाइल नाम एक्सटेंशन(s) को शामिल करने वाली स्ट्रिंग को प्राप्त करता है या सेट करता है। एक्सटेंशन सेमीकोलन द्वारा अलग किए गए हैं।

**Returns:**
java.lang.String
### setFilenameExtension(String value) {#setFilenameExtension-java.lang.String-}
```
public void setFilenameExtension(String value)
```


कोडेक में उपयोग किए जाने वाले फ़ाइल नाम एक्सटेंशन(s) को शामिल करने वाली स्ट्रिंग को प्राप्त करता है या सेट करता है। एक्सटेंशन सेमीकोलन द्वारा अलग किए गए हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getMimeType() {#getMimeType--}
```
public String getMimeType()
```


कोडेक के मल्टीपर्पज़ इंटरनेट मेल एक्सटेंशन (MIME) प्रकार को सम्मिलित करने वाली स्ट्रिंग प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setMimeType(String value) {#setMimeType-java.lang.String-}
```
public void setMimeType(String value)
```


कोडेक के मल्टीपर्पज़ इंटरनेट मेल एक्सटेंशन (MIME) प्रकार को सम्मिलित करने वाली स्ट्रिंग प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


कोडेक का संस्करण संख्या प्राप्त करता है या सेट करता है।

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


कोडेक का संस्करण संख्या प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSignaturePatterns() {#getSignaturePatterns--}
```
public byte[][] getSignaturePatterns()
```


कोडेक के सिग्नेचर को दर्शाने वाले बाइट्स के दो-आयामी एरे को प्राप्त करता है या सेट करता है।

**Returns:**
byte[][]
### setSignaturePatterns(byte[][] value) {#setSignaturePatterns-byte-----}
```
public void setSignaturePatterns(byte[][] value)
```


कोडेक के सिग्नेचर को दर्शाने वाले बाइट्स के दो-आयामी एरे को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte[][] |  |

### getSignatureMasks() {#getSignatureMasks--}
```
public byte[][] getSignatureMasks()
```


फ़िल्टर के रूप में उपयोग की जा सकने वाले बाइट्स के दो-आयामी एरे को प्राप्त करता है या सेट करता है।

**Returns:**
byte[][]
### setSignatureMasks(byte[][] value) {#setSignatureMasks-byte-----}
```
public void setSignatureMasks(byte[][] value)
```


फ़िल्टर के रूप में उपयोग की जा सकने वाले बाइट्स के दो-आयामी एरे को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte[][] |  |

### getImageDecoders() {#getImageDecoders--}
```
public static ImageCodecInfo[] getImageDecoders()
```


GDI+ में निर्मित इमेज डिकोडर के बारे में जानकारी रखने वाले [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) ऑब्जेक्ट्स की एक एरे लौटाता है।

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) ऑब्जेक्ट्स की एक सरणी। सरणी में प्रत्येक [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) ऑब्जेक्ट में निर्मित इमेज डिकोडर्स में से एक के बारे में जानकारी होती है।
### getImageEncoders() {#getImageEncoders--}
```
public static ImageCodecInfo[] getImageEncoders()
```


GDI+ में निर्मित इमेज एन्कोडर के बारे में जानकारी रखने वाले [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) ऑब्जेक्ट्स की एक एरे लौटाता है।

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) ऑब्जेक्ट्स की एक सरणी। सरणी में प्रत्येक [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) ऑब्जेक्ट में निर्मित इमेज एन्कोडर्स में से एक के बारे में जानकारी होती है।
