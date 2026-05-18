---
title: Icon
second_title: Aspose.Drawing for Java API संदर्भ
description: एक Windows आइकन का प्रतिनिधित्व करता है जो एक छोटा बिटमैप इमेज है जिसका उपयोग किसी ऑब्जेक्ट का प्रतिनिधित्व करने के लिए किया जाता है।
type: docs
weight: 29
url: /hi/java/com.aspose.drawing/icon/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.ms.System.IDisposable
```
public final class Icon implements System.ICloneable, System.IDisposable
```

एक Windows आइकन का प्रतिनिधित्व करता है, जो एक छोटा बिटमैप इमेज है जिसका उपयोग किसी ऑब्जेक्ट का प्रतिनिधित्व करने के लिए किया जाता है। आइकन को पारदर्शी बिटमैप के रूप में समझा जा सकता है, हालांकि उनका आकार सिस्टम द्वारा निर्धारित होता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Icon(String fileName)](#Icon-java.lang.String-) | निर्दिष्ट फ़ाइल नाम से [Icon](../../com.aspose.drawing/icon) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Icon(InputStream stream)](#Icon-java.io.InputStream-) | निर्दिष्ट डेटा स्ट्रीम से [Icon](../../com.aspose.drawing/icon) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Icon(String fileName, Size size)](#Icon-java.lang.String-com.aspose.drawing.Size-) | निर्दिष्ट फ़ाइल से निर्दिष्ट आकार के [Icon](../../com.aspose.drawing/icon) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Icon(Icon original, Size size)](#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-) | [Icon](../../com.aspose.drawing/icon) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है और अनुरोधित आकार से मेल खाने वाले आइकन का संस्करण खोजने का प्रयास करता है। |
| [Icon(Object type, String resource)](#Icon-java.lang.Object-java.lang.String-) | निर्दिष्ट असेंबली में संसाधन से [Icon](../../com.aspose.drawing/icon) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Icon(InputStream stream, Size size)](#Icon-java.io.InputStream-com.aspose.drawing.Size-) | निर्दिष्ट स्ट्रीम से निर्दिष्ट आकार के [Icon](../../com.aspose.drawing/icon) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Icon(String fileName, int width, int height)](#Icon-java.lang.String-int-int-) | निर्दिष्ट फ़ाइल से निर्दिष्ट चौड़ाई और ऊँचाई के साथ [Icon](../../com.aspose.drawing/icon) क्लास का नया उदाहरण प्रारंभ करता है। |
| [Icon(Icon original, int width, int height)](#Icon-com.aspose.drawing.Icon-int-int-) | निर्दिष्ट आकार से मेल खाने वाले आइकन का संस्करण खोजने का प्रयास करते हुए [Icon](../../com.aspose.drawing/icon) क्लास का नया उदाहरण प्रारंभ करता है.. |
| [Icon(InputStream stream, int width, int height)](#Icon-java.io.InputStream-int-int-) | निर्दिष्ट डेटा स्ट्रीम से और निर्दिष्ट चौड़ाई तथा ऊँचाई के साथ [Icon](../../com.aspose.drawing/icon) क्लास का नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getHandle()](#getHandle--) | इस [Icon](../../com.aspose.drawing/icon) के हैंडल को प्राप्त करता है। |
| [getHeight()](#getHeight--) | इस [Icon](../../com.aspose.drawing/icon) की ऊँचाई प्राप्त करता है। |
| [getSize()](#getSize--) | इस [Icon](../../com.aspose.drawing/icon) का आकार प्राप्त करता है। |
| [getWidth()](#getWidth--) | इस [Icon](../../com.aspose.drawing/icon) की चौड़ाई प्राप्त करता है। |
| [extractAssociatedIcon(String filePath)](#extractAssociatedIcon-java.lang.String-) | निर्दिष्ट फ़ाइल में सम्मिलित छवि का आइकन प्रतिनिधित्व लौटाता है। |
| [fromHandle(byte[] handle)](#fromHandle-byte---) | निर्दिष्ट Windows हैंडल (HICON) से GDI+ [Icon](../../com.aspose.drawing/icon) बनाता है। |
| [deepClone()](#deepClone--) | [Icon](../../com.aspose.drawing/icon) को क्लोन करता है, एक डुप्लिकेट छवि बनाते हुए। |
| [dispose()](#dispose--) | अनुप्रयोग-परिभाषित कार्यों को निष्पादित करता है जो अनप्रबंधित संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित हैं। |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | इस [Icon](../../com.aspose.drawing/icon) को निर्दिष्ट आउटपुट java.io.InputStream में सहेजता है। |
| [toBitmap()](#toBitmap--) | इस [Icon](../../com.aspose.drawing/icon) को GDI+ [Bitmap](../../com.aspose.drawing/bitmap) में परिवर्तित करता है। |
| [toString()](#toString--) | [Icon](../../com.aspose.drawing/icon) का वर्णन करने वाली मानव-पठनीय स्ट्रिंग प्राप्त करता है। |
### Icon(String fileName) {#Icon-java.lang.String-}
```
public Icon(String fileName)
```


निर्दिष्ट फ़ाइल नाम से [Icon](../../com.aspose.drawing/icon) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | [Icon](../../com.aspose.drawing/icon) को लोड करने के लिए फ़ाइल। |

### Icon(InputStream stream) {#Icon-java.io.InputStream-}
```
public Icon(InputStream stream)
```


निर्दिष्ट डेटा स्ट्रीम से [Icon](../../com.aspose.drawing/icon) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | [Icon](../../com.aspose.drawing/icon) को लोड करने के लिए डेटा स्ट्रीम। |

### Icon(String fileName, Size size) {#Icon-java.lang.String-com.aspose.drawing.Size-}
```
public Icon(String fileName, Size size)
```


निर्दिष्ट फ़ाइल से निर्दिष्ट आकार के [Icon](../../com.aspose.drawing/icon) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | आइकन डेटा सम्मिलित करने वाली फ़ाइल का नाम और पथ। |
| size | [Size](../../com.aspose.drawing/size) | आइकन का वांछित आकार। |

### Icon(Icon original, Size size) {#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-}
```
public Icon(Icon original, Size size)
```


[Icon](../../com.aspose.drawing/icon) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है और अनुरोधित आकार से मेल खाने वाले आइकन का संस्करण खोजने का प्रयास करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | नए आकार के आइकन को लोड करने के लिए [Icon](../../com.aspose.drawing/icon)। |
| size | [Size](../../com.aspose.drawing/size) | एक `Size`([.getSize](../../null/\#getSize)) संरचना जो नए [Icon](../../com.aspose.drawing/icon) की ऊँचाई और चौड़ाई निर्दिष्ट करती है। |

### Icon(Object type, String resource) {#Icon-java.lang.Object-java.lang.String-}
```
public Icon(Object type, String resource)
```


निर्दिष्ट असेंबली में संसाधन से [Icon](../../com.aspose.drawing/icon) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रकार | java.lang.Object | एक Type जो उस असेंबली को निर्दिष्ट करता है जिसमें संसाधन खोजा जाना चाहिए। |
| संसाधन | java.lang.String | लोड करने के लिए संसाधन नाम। |

### Icon(InputStream stream, Size size) {#Icon-java.io.InputStream-com.aspose.drawing.Size-}
```
public Icon(InputStream stream, Size size)
```


निर्दिष्ट स्ट्रीम से निर्दिष्ट आकार के [Icon](../../com.aspose.drawing/icon) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | आइकन डेटा सम्मिलित करने वाला स्ट्रीम। |
| size | [Size](../../com.aspose.drawing/size) | आइकन का वांछित आकार। |

### Icon(String fileName, int width, int height) {#Icon-java.lang.String-int-int-}
```
public Icon(String fileName, int width, int height)
```


निर्दिष्ट फ़ाइल से निर्दिष्ट चौड़ाई और ऊँचाई के साथ [Icon](../../com.aspose.drawing/icon) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | [Icon](../../com.aspose.drawing/icon) डेटा सम्मिलित करने वाली फ़ाइल का नाम और पथ। |
| width | int | [Icon](../../com.aspose.drawing/icon) की वांछित चौड़ाई। |
| height | int | वांछित ऊँचाई [Icon](../../com.aspose.drawing/icon) की। |

### Icon(Icon original, int width, int height) {#Icon-com.aspose.drawing.Icon-int-int-}
```
public Icon(Icon original, int width, int height)
```


निर्दिष्ट आकार से मेल खाने वाले आइकन का संस्करण खोजने का प्रयास करते हुए [Icon](../../com.aspose.drawing/icon) क्लास का नया उदाहरण प्रारंभ करता है..

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | वह आइकन जिससे विभिन्न आकार लोड किए जाएँ। |
| चौड़ाई | int | नए आइकन की चौड़ाई। |
| ऊँचाई | int | नए आइकन की ऊँचाई। |

### Icon(InputStream stream, int width, int height) {#Icon-java.io.InputStream-int-int-}
```
public Icon(InputStream stream, int width, int height)
```


निर्दिष्ट डेटा स्ट्रीम से और निर्दिष्ट चौड़ाई तथा ऊँचाई के साथ [Icon](../../com.aspose.drawing/icon) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | डेटा स्ट्रीम जिससे आइकन लोड किया जाता है। |
| चौड़ाई | int | आइकन की चौड़ाई, पिक्सेल में। |
| ऊँचाई | int | आइकन की ऊँचाई, पिक्सेल में। |

### getHandle() {#getHandle--}
```
public System.IntPtr getHandle()
```


इस [Icon](../../com.aspose.drawing/icon) के हैंडल को प्राप्त करता है। यह हैंडल की प्रतिलिपि नहीं है; इसे मुक्त न करें।

मान: आइकन का Windows हैंडल।

**Returns:**
com.aspose.ms.System.IntPtr
### getHeight() {#getHeight--}
```
public int getHeight()
```


इस [Icon](../../com.aspose.drawing/icon) की ऊँचाई प्राप्त करता है।

मान: इस [Icon](../../com.aspose.drawing/icon) की ऊँचाई।

**Returns:**
int
### getSize() {#getSize--}
```
public Size getSize()
```


इस [Icon](../../com.aspose.drawing/icon) का आकार प्राप्त करता है।

मान: एक `Size`([.getSize](../../null/\#getSize)) संरचना जो इस [Icon](../../com.aspose.drawing/icon) की चौड़ाई और ऊँचाई निर्दिष्ट करती है।

**Returns:**
[Size](../../com.aspose.drawing/size)
### getWidth() {#getWidth--}
```
public int getWidth()
```


इस [Icon](../../com.aspose.drawing/icon) की चौड़ाई प्राप्त करता है।

मान: इस [Icon](../../com.aspose.drawing/icon) की चौड़ाई।

**Returns:**
int
### extractAssociatedIcon(String filePath) {#extractAssociatedIcon-java.lang.String-}
```
public static Icon extractAssociatedIcon(String filePath)
```


निर्दिष्ट फ़ाइल में सम्मिलित छवि का आइकन प्रतिनिधित्व लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | फ़ाइल का पथ जिसमें छवि होती है। |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) representation of the image that is contained in the specified file.
### fromHandle(byte[] handle) {#fromHandle-byte---}
```
public static Icon fromHandle(byte[] handle)
```


निर्दिष्ट Windows हैंडल (HICON) से GDI+ [Icon](../../com.aspose.drawing/icon) बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| handle | byte[] | आइकन का Windows हैंडल। |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) this method creates.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


[Icon](../../com.aspose.drawing/icon) को क्लोन करता है, एक डुप्लिकेट छवि बनाते हुए।

**Returns:**
java.lang.Object - एक ऑब्जेक्ट जिसे [Icon](../../com.aspose.drawing/icon) में कास्ट किया जा सकता है।
### dispose() {#dispose--}
```
public void dispose()
```


अनुप्रयोग-परिभाषित कार्यों को निष्पादित करता है जो अनप्रबंधित संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित हैं।

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


इस [Icon](../../com.aspose.drawing/icon) को निर्दिष्ट आउटपुट java.io.InputStream में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| outputStream | java.io.OutputStream | सेव करने के लिए java.io.InputStream। |

### toBitmap() {#toBitmap--}
```
public Bitmap toBitmap()
```


इस [Icon](../../com.aspose.drawing/icon) को GDI+ [Bitmap](../../com.aspose.drawing/bitmap) में परिवर्तित करता है।

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - A [Bitmap](../../com.aspose.drawing/bitmap) that represents the converted [Icon](../../com.aspose.drawing/icon).
### toString() {#toString--}
```
public String toString()
```


[Icon](../../com.aspose.drawing/icon) का वर्णन करने वाली मानव-पठनीय स्ट्रिंग प्राप्त करता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो [Icon](../../com.aspose.drawing/icon) का वर्णन करती है।
