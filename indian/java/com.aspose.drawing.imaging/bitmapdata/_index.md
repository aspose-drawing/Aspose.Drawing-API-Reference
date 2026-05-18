---
title: BitmapData
second_title: Aspose.Drawing for Java API संदर्भ
description: एक बिटमैप छवि के गुणों को निर्दिष्ट करता है।
type: docs
weight: 10
url: /hi/java/com.aspose.drawing.imaging/bitmapdata/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapData
```

एक बिटमैप इमेज के गुणों को निर्दिष्ट करता है। [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) क्लास का उपयोग [Bitmap](../../com.aspose.drawing/bitmap) क्लास की `E:Bitmap.LockBits` और `M:Bitmap.UnlockBits(BitmapData)` विधियों द्वारा किया जाता है। यह विरासत में नहीं ली जा सकती।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [BitmapData()](#BitmapData--) |  |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getWidth()](#getWidth--) | [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की पिक्सेल चौड़ाई प्राप्त करता है। |
| [setWidth(int value)](#setWidth-int-) | [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की पिक्सेल चौड़ाई सेट करता है। |
| [getHeight()](#getHeight--) | [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की पिक्सेल ऊँचाई प्राप्त करता है। |
| [setHeight(int value)](#setHeight-int-) | [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की पिक्सेल ऊँचाई सेट करता है। |
| [getStride()](#getStride--) | [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की स्ट्राइड चौड़ाई (जिसे स्कैन चौड़ाई भी कहा जाता है) प्राप्त करता है। |
| [setStride(int value)](#setStride-int-) | [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की स्ट्राइड चौड़ाई (जिसे स्कैन चौड़ाई भी कहा जाता है) सेट करता है। |
| [getPixelFormat()](#getPixelFormat--) | [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट में पिक्सेल जानकारी के स्वरूप को प्राप्त करता है, जिसने यह [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) ऑब्जेक्ट लौटाया है। |
| [setPixelFormat(int value)](#setPixelFormat-int-) | [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट में पिक्सेल जानकारी के स्वरूप को सेट करता है, जिसने यह [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) ऑब्जेक्ट लौटाया है। |
| [getScan0()](#getScan0--) | बिटमैप में पहले पिक्सेल डेटा का पता प्राप्त करता है। |
| [setScan0(int[] value)](#setScan0-int---) | बिटमैप में पहले पिक्सेल डेटा का पता सेट करता है। |
### BitmapData() {#BitmapData--}
```
public BitmapData()
```


### getWidth() {#getWidth--}
```
public int getWidth()
```


[Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की पिक्सेल चौड़ाई प्राप्त करता है। इसे एक स्कैन लाइन में पिक्सेल की संख्या के रूप में भी समझा जा सकता है।

**Returns:**
int - [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की पिक्सेल चौड़ाई।
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


सेट करता है [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की पिक्सेल चौड़ाई। इसे एक स्कैन लाइन में पिक्सेल की संख्या के रूप में भी समझा जा सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | यह [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की पिक्सेल चौड़ाई। |

### getHeight() {#getHeight--}
```
public int getHeight()
```


प्राप्त करता है [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की पिक्सेल ऊँचाई। इसे कभी-कभी स्कैन लाइनों की संख्या के रूप में भी कहा जाता है।

**Returns:**
int - [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की पिक्सेल ऊँचाई।
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


सेट करता है [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की पिक्सेल ऊँचाई। इसे कभी-कभी स्कैन लाइनों की संख्या के रूप में भी कहा जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | यह [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की पिक्सेल ऊँचाई। |

### getStride() {#getStride--}
```
public int getStride()
```


[Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की स्ट्राइड चौड़ाई (जिसे स्कैन चौड़ाई भी कहा जाता है) प्राप्त करता है।

**Returns:**
int - [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की स्ट्राइड चौड़ाई, बाइट्स में।
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


[Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की स्ट्राइड चौड़ाई (जिसे स्कैन चौड़ाई भी कहा जाता है) सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | यह [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट की स्ट्राइड चौड़ाई (जिसे स्कैन चौड़ाई भी कहा जाता है)। |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


[Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट में पिक्सेल जानकारी के स्वरूप को प्राप्त करता है, जिसने यह [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) ऑब्जेक्ट लौटाया है।

**Returns:**
int - A `PixelFormat`([.getPixelFormat](../../null/\#getPixelFormat)/[.setPixelFormat(int)](../../null/\#setPixelFormat-int-)) जो संबंधित [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट में पिक्सेल जानकारी के स्वरूप को निर्दिष्ट करता है।
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


[Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट में पिक्सेल जानकारी के स्वरूप को सेट करता है, जिसने यह [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) ऑब्जेक्ट लौटाया है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | यह [Bitmap](../../com.aspose.drawing/bitmap) ऑब्जेक्ट में पिक्सेल जानकारी का स्वरूप है जिसने यह [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) ऑब्जेक्ट लौटाया। |

### getScan0() {#getScan0--}
```
public int[] getScan0()
```


प्राप्त करता है बिटमैप में प्रथम पिक्सेल डेटा का पता। इसे बिटमैप में पहली स्कैन लाइन के रूप में भी समझा जा सकता है।

**Returns:**
int[] - बिटमैप में प्रथम पिक्सेल डेटा का पता।
### setScan0(int[] value) {#setScan0-int---}
```
public void setScan0(int[] value)
```


सेट करता है बिटमैप में प्रथम पिक्सेल डेटा का पता। इसे बिटमैप में पहली स्कैन लाइन के रूप में भी समझा जा सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int[] | बिटमैप में प्रथम पिक्सेल डेटा का पता। |

