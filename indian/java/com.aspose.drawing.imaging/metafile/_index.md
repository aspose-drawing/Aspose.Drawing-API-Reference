---
title: Metafile
second_title: Aspose.Drawing for Java API संदर्भ
description: एक ग्राफिक मेटाफाइल को परिभाषित करता है।
type: docs
weight: 30
url: /hi/java/com.aspose.drawing.imaging/metafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public final class Metafile extends Image
```

एक ग्राफिक मेटाफाइल को परिभाषित करता है। एक मेटाफाइल रिकॉर्ड्स रखती है जो ग्राफिक ऑपरेशनों की क्रमबद्धता का वर्णन करती हैं, जिन्हें रिकॉर्ड (निर्मित) किया जा सकता है और पुनः चलाया (प्रदर्शित) जा सकता है। यह क्लास विरासत में नहीं ली जा सकती।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Metafile(byte[] henhmetafile, boolean deleteEmf)](#Metafile-byte---boolean-) | निर्दिष्ट हैंडल से [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है। |
| [Metafile(byte[] referenceHdc, int emfType)](#Metafile-byte---int-) | निर्दिष्ट हैंडल से डिवाइस कॉन्टेक्स्ट और एक [EmfType](../../com.aspose.drawing.imaging/emftype) एन्यूमरेशन, जो [Metafile](../../com.aspose.drawing.imaging/metafile) के स्वरूप को निर्दिष्ट करता है, के साथ [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है। |
| [Metafile(String filename)](#Metafile-java.lang.String-) | निर्दिष्ट फ़ाइल नाम से [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है। |
| [Metafile(String filename, byte[] referenceHdc)](#Metafile-java.lang.String-byte---) | निर्दिष्ट फ़ाइल नाम से [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है। |
| [Metafile(InputStream stream)](#Metafile-java.io.InputStream-) | निर्दिष्ट डेटा स्ट्रीम से [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है। |
| [Metafile(InputStream stream, byte[] referenceHdc)](#Metafile-java.io.InputStream-byte---) | निर्दिष्ट डेटा स्ट्रीम और डिवाइस कॉन्टेक्स्ट के लिए एक Windows हैंडल से [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है। |
| [Metafile(System.IO.Stream stream, int type)](#Metafile-com.aspose.ms.System.IO.Stream-int-) | निर्दिष्ट डेटा स्ट्रीम और डिवाइस कॉन्टेक्स्ट के लिए एक Windows हैंडल से [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है। |
| [Metafile(InputStream stream, byte[] referenceHdc, int type)](#Metafile-java.io.InputStream-byte---int-) | निर्दिष्ट डेटा स्ट्रीम, डिवाइस कॉन्टेक्स्ट के लिए Windows हैंडल, और एक [EmfType](../../com.aspose.drawing.imaging/emftype) एन्यूमरेशन, जो [Metafile](../../com.aspose.drawing.imaging/metafile) के स्वरूप को निर्दिष्ट करता है, के साथ [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है। |
| [Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)](#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-) | निर्दिष्ट डेटा स्ट्रीम, डिवाइस कॉन्टेक्स्ट के लिए Windows हैंडल, और एक [EmfType](../../com.aspose.drawing.imaging/emftype) एन्यूमरेशन, जो [Metafile](../../com.aspose.drawing.imaging/metafile) के स्वरूप को निर्दिष्ट करता है, के साथ [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getWidth()](#getWidth--) | इस [Metafile](../../com.aspose.drawing.imaging/metafile) की चौड़ाई, पिक्सेल में, प्राप्त करता है। |
| [getHeight()](#getHeight--) | इस [Metafile](../../com.aspose.drawing.imaging/metafile) की ऊँचाई, पिक्सेल में, प्राप्त करता है। |
| [getRawFormat()](#getRawFormat--) | इस [Image](../../com.aspose.drawing/image) का फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getPixelFormat()](#getPixelFormat--) | इस [Image](../../com.aspose.drawing/image) का पिक्सेल फ़ॉर्मेट प्राप्त करता है। |
| [getPalette()](#getPalette--) | इस [Image](../../com.aspose.drawing/image) के लिए उपयोग किए जाने वाले रंग पैलेट को प्राप्त करता है या सेट करता है। |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | इस [Image](../../com.aspose.drawing/image) के लिए उपयोग किए जाने वाले रंग पैलेट को प्राप्त करता है या सेट करता है। |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | इस [Image](../../com.aspose.drawing/image) के भीतर फ्रेमों के आयामों को दर्शाने वाले GUIDs की एक सरणी प्राप्त करता है। |
| [getPropertyIdList()](#getPropertyIdList--) | इस [Image](../../com.aspose.drawing/image) में संग्रहीत प्रॉपर्टी आइटम्स के IDs प्राप्त करता है। |
| [getPropertyItems()](#getPropertyItems--) | इस [Image](../../com.aspose.drawing/image) में संग्रहीत सभी प्रॉपर्टी आइटम्स (मेटाडेटा के टुकड़े) प्राप्त करता है। |
| [getMetafileHeader(InputStream stream)](#getMetafileHeader-java.io.InputStream-) | निर्दिष्ट [Metafile](../../com.aspose.drawing.imaging/metafile) से जुड़े [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) को लौटाता है। |
| [getMetafileHeader(String fileName)](#getMetafileHeader-java.lang.String-) | निर्दिष्ट [Metafile](../../com.aspose.drawing.imaging/metafile) से जुड़े [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) को लौटाता है। |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | यह मेथड [Image](../../com.aspose.drawing/image) को घुमाता, उलटता, या घुमाकर उलटता है। |
| [getHenhmetafile()](#getHenhmetafile--) | एक उन्नत [Metafile](../../com.aspose.drawing.imaging/metafile) के लिए Windows हैंडल लौटाता है। |
| [playRecord(int recordType, int flags, int dataSize, byte[] dataArray)](#playRecord-int-int-int-byte---) | एक व्यक्तिगत मेटाफाइल रिकॉर्ड चलाता है। |
| [getMetafileHeader()](#getMetafileHeader--) | इस [Metafile](../../com.aspose.drawing.imaging/metafile) से जुड़े [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) को लौटाता है। |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | इस [Image](../../com.aspose.drawing/image) से निर्दिष्ट प्रॉपर्टी आइटम प्राप्त करता है। |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | इस [Image](../../com.aspose.drawing/image) से निर्दिष्ट प्रॉपर्टी आइटम को हटाता है। |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | इस [Image](../../com.aspose.drawing/image) में एक प्रॉपर्टी आइटम (मेटाडेटा का टुकड़ा) संग्रहीत करता है। |
### Metafile(byte[] henhmetafile, boolean deleteEmf) {#Metafile-byte---boolean-}
```
public Metafile(byte[] henhmetafile, boolean deleteEmf)
```


निर्दिष्ट हैंडल से [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| henhmetafile | byte[] | एक हैंडल उन्नत मेटाफाइल के लिए। |
| deleteEmf | boolean | जब [Metafile](../../com.aspose.drawing.imaging/metafile) हटाया जाता है तो उन्नत मेटाफाइल हैंडल को हटाने के लिए true; अन्यथा false। |

### Metafile(byte[] referenceHdc, int emfType) {#Metafile-byte---int-}
```
public Metafile(byte[] referenceHdc, int emfType)
```


निर्दिष्ट हैंडल से डिवाइस कॉन्टेक्स्ट और एक [EmfType](../../com.aspose.drawing.imaging/emftype) एन्यूमरेशन, जो [Metafile](../../com.aspose.drawing.imaging/metafile) के स्वरूप को निर्दिष्ट करता है, के साथ [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| referenceHdc | byte[] | डिवाइस कॉन्टेक्स्ट के लिए हैंडल। |
| emfType | int | एक [EmfType](../../com.aspose.drawing.imaging/emftype) जो [Metafile](../../com.aspose.drawing.imaging/metafile) का फ़ॉर्मेट निर्दिष्ट करता है। |

### Metafile(String filename) {#Metafile-java.lang.String-}
```
public Metafile(String filename)
```


निर्दिष्ट फ़ाइल नाम से [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | java.lang.String | एक स्ट्रिंग जो फ़ाइल नाम दर्शाती है जिससे नया [Metafile](../../com.aspose.drawing.imaging/metafile) बनाया जाता है। |

### Metafile(String filename, byte[] referenceHdc) {#Metafile-java.lang.String-byte---}
```
public Metafile(String filename, byte[] referenceHdc)
```


निर्दिष्ट फ़ाइल नाम से [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | java.lang.String | एक स्ट्रिंग जो फ़ाइल नाम दर्शाती है जिससे नया [Metafile](../../com.aspose.drawing.imaging/metafile) बनाया जाता है। |
| referenceHdc | byte[] | डिवाइस कॉन्टेक्स्ट के लिए एक Windows हैंडल। |

### Metafile(InputStream stream) {#Metafile-java.io.InputStream-}
```
public Metafile(InputStream stream)
```


निर्दिष्ट डेटा स्ट्रीम से [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | इनपुटस्ट्रीम जिससे नया [Metafile](../../com.aspose.drawing.imaging/metafile) बनाया जाता है। |

### Metafile(InputStream stream, byte[] referenceHdc) {#Metafile-java.io.InputStream-byte---}
```
public Metafile(InputStream stream, byte[] referenceHdc)
```


निर्दिष्ट डेटा स्ट्रीम और डिवाइस कॉन्टेक्स्ट के Windows हैंडल से [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। />.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | एक इनपुटस्ट्रीम जिसमें इस [Metafile](../../com.aspose.drawing.imaging/metafile) के डेटा होते हैं। |
| referenceHdc | byte[] | एक Windows हैंडल जो [Metafile](../../com.aspose.drawing.imaging/metafile) ऑब्जेक्ट के डिवाइस कॉन्टेक्स्ट के लिए है। |

### Metafile(System.IO.Stream stream, int type) {#Metafile-com.aspose.ms.System.IO.Stream-int-}
```
public Metafile(System.IO.Stream stream, int type)
```


निर्दिष्ट डेटा स्ट्रीम और डिवाइस कॉन्टेक्स्ट के Windows हैंडल से [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। />.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | एक इनपुटस्ट्रीम जिसमें इस [Metafile](../../com.aspose.drawing.imaging/metafile) के डेटा होते हैं। |
| प्रकार | int | int 1 होना चाहिए। |

### Metafile(InputStream stream, byte[] referenceHdc, int type) {#Metafile-java.io.InputStream-byte---int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, int type)
```


निर्दिष्ट डेटा स्ट्रीम, डिवाइस कॉन्टेक्स्ट के लिए Windows हैंडल, और एक [EmfType](../../com.aspose.drawing.imaging/emftype) एन्यूमरेशन, जो [Metafile](../../com.aspose.drawing.imaging/metafile) के स्वरूप को निर्दिष्ट करता है, के साथ [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | एक इनपुटस्ट्रीम जिसमें इस [Metafile](../../com.aspose.drawing.imaging/metafile) के डेटा होते हैं। |
| referenceHdc | byte[] | डिवाइस कॉन्टेक्स्ट के लिए एक Windows हैंडल। |
| type | int | एक [EmfType](../../com.aspose.drawing.imaging/emftype) जो [Metafile](../../com.aspose.drawing.imaging/metafile) का फ़ॉर्मेट निर्दिष्ट करता है। |

### Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type) {#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)
```


निर्दिष्ट डेटा स्ट्रीम, डिवाइस कॉन्टेक्स्ट के लिए Windows हैंडल, और एक [EmfType](../../com.aspose.drawing.imaging/emftype) एन्यूमरेशन, जो [Metafile](../../com.aspose.drawing.imaging/metafile) के स्वरूप को निर्दिष्ट करता है, के साथ [Metafile](../../com.aspose.drawing.imaging/metafile) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | एक इनपुटस्ट्रीम जिसमें इस [Metafile](../../com.aspose.drawing.imaging/metafile) के डेटा होते हैं। |
| referenceHdc | byte[] | डिवाइस कॉन्टेक्स्ट के लिए एक Windows हैंडल। |
| frameRect | [RectangleF](../../com.aspose.drawing/rectanglef) | एक [Rectangle](../../com.aspose.drawing/rectangle) जो नए [Metafile](../../com.aspose.drawing.imaging/metafile) को सीमित करने वाला आयत दर्शाता है। |
| frameUnit | int | एक [MetafileFrameUnit](../../com.aspose.drawing.imaging/metafileframeunit) जो frameRect के माप इकाई को निर्दिष्ट करता है। |
| type | int | एक [EmfType](../../com.aspose.drawing.imaging/emftype) जो [Metafile](../../com.aspose.drawing.imaging/metafile) का फ़ॉर्मेट निर्दिष्ट करता है। |

### getWidth() {#getWidth--}
```
public int getWidth()
```


इस [Metafile](../../com.aspose.drawing.imaging/metafile) की चौड़ाई, पिक्सेल में, प्राप्त करता है।

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


इस [Metafile](../../com.aspose.drawing.imaging/metafile) की ऊँचाई, पिक्सेल में, प्राप्त करता है।

**Returns:**
int - इस [Metafile](../../com.aspose.drawing.imaging/metafile) की ऊँचाई, पिक्सेल में।
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


इस [Image](../../com.aspose.drawing/image) का फ़ाइल फ़ॉर्मेट प्राप्त करता है।

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


इस [Image](../../com.aspose.drawing/image) का पिक्सेल फ़ॉर्मेट प्राप्त करता है।

**Returns:**
int - एक `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) जो इस [Image](../../com.aspose.drawing/image) के पिक्सेल फ़ॉर्मेट को दर्शाता है।
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


इस [Image](../../com.aspose.drawing/image) के लिए उपयोग किए जाने वाले रंग पैलेट को प्राप्त करता है या सेट करता है।

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


इस [Image](../../com.aspose.drawing/image) के लिए उपयोग किए जाने वाले रंग पैलेट को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


इस [Image](../../com.aspose.drawing/image) के भीतर फ्रेमों के आयामों को दर्शाने वाले GUIDs की एक सरणी प्राप्त करता है।

**Returns:**
java.util.UUID[] - GUIDs की एक एरे जो इस [Image](../../com.aspose.drawing/image) के फ्रेमों के आयामों को सबसे महत्वपूर्ण से कम महत्वपूर्ण तक निर्दिष्ट करती है।
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


इस [Image](../../com.aspose.drawing/image) में संग्रहीत प्रॉपर्टी आइटम्स के IDs प्राप्त करता है।

**Returns:**
int[] - प्रॉपर्टी IDs की एरे, प्रत्येक प्रॉपर्टी आइटम के लिए एक, जो इस इमेज में संग्रहीत है।
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


इस [Image](../../com.aspose.drawing/image) में संग्रहीत सभी प्रॉपर्टी आइटम्स (मेटाडेटा के टुकड़े) प्राप्त करता है।

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] - [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) ऑब्जेक्ट्स की एरे, प्रत्येक प्रॉपर्टी आइटम के लिए एक, जो इमेज में संग्रहीत है।
### getMetafileHeader(InputStream stream) {#getMetafileHeader-java.io.InputStream-}
```
public static MetafileHeader getMetafileHeader(InputStream stream)
```


निर्दिष्ट [Metafile](../../com.aspose.drawing.imaging/metafile) से जुड़े [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) को लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | एक इनपुटस्ट्रीम जिसमें वह [Metafile](../../com.aspose.drawing.imaging/metafile) है जिसके लिए हेडर प्राप्त किया जाता है। |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### getMetafileHeader(String fileName) {#getMetafileHeader-java.lang.String-}
```
public static MetafileHeader getMetafileHeader(String fileName)
```


निर्दिष्ट [Metafile](../../com.aspose.drawing.imaging/metafile) से जुड़े [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) को लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | एक स्ट्रिंग जिसमें उस [Metafile](../../com.aspose.drawing.imaging/metafile) का नाम है जिसके लिए हेडर प्राप्त किया जाता है। |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


यह मेथड [Image](../../com.aspose.drawing/image) को घुमाता, उलटता, या घुमाकर उलटता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rotateFlipType | int | एक [RotateFlipType](../../com.aspose.drawing/rotatefliptype) सदस्य जो इमेज पर लागू होने वाले रोटेशन और फ्लिप के प्रकार को निर्दिष्ट करता है। |

### getHenhmetafile() {#getHenhmetafile--}
```
public System.IntPtr getHenhmetafile()
```


एक उन्नत [Metafile](../../com.aspose.drawing.imaging/metafile) के लिए Windows हैंडल लौटाता है।

**Returns:**
com.aspose.ms.System.IntPtr - इस उन्नत [Metafile](../../com.aspose.drawing.imaging/metafile) के लिए एक Windows हैंडल।
### playRecord(int recordType, int flags, int dataSize, byte[] dataArray) {#playRecord-int-int-int-byte---}
```
public void playRecord(int recordType, int flags, int dataSize, byte[] dataArray)
```


एक व्यक्तिगत मेटाफाइल रिकॉर्ड चलाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| recordType | int | Metafाइल रिकॉर्ड के प्रकार को निर्दिष्ट करने वाला [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) का तत्व। |
| flags | int | रिकॉर्ड के गुणों को निर्दिष्ट करने वाले फ़्लैग्स का सेट। |
| dataSize | int | रिकॉर्ड डेटा में बाइट्स की संख्या। |
| dataArray | byte[] | बाइट्स की एक एरे जो रिकॉर्ड डेटा को समाहित करती है। |

### getMetafileHeader() {#getMetafileHeader--}
```
public MetafileHeader getMetafileHeader()
```


इस [Metafile](../../com.aspose.drawing.imaging/metafile) से जुड़े [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) को लौटाता है।

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile).
### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


इस [Image](../../com.aspose.drawing/image) से निर्दिष्ट प्रॉपर्टी आइटम प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propid | int | प्राप्त करने के लिए प्रॉपर्टी आइटम की आईडी। |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


इस [Image](../../com.aspose.drawing/image) से निर्दिष्ट प्रॉपर्टी आइटम को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propid | int | हटाने के लिए प्रॉपर्टी आइटम की आईडी। |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


इस [Image](../../com.aspose.drawing/image) में एक प्रॉपर्टी आइटम (मेटाडेटा का टुकड़ा) संग्रहीत करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | सहेजे जाने वाले [PropertyItem](../../com.aspose.drawing.imaging/propertyitem)। |

